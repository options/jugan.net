### On.NET 소식
[지난번 On.NET 동영상 인터뷰]지난주는 Aaron Stannard와 함께 .NET용 액터 모델 기반의 프레임워크인 Akka.NET에 대해서 얘기나누었습니다.

[이번 On.NET 유튜브 동영상 인터뷰] 이번주는 Joe Duffy를 모시고 현재마이크로 소프트가 진행했던 차세대 OS 프로젝트인 Midori 프로젝트에 대
해서 얘기해 볼 예정입니다. (현재 Midori 프로젝트는 취소된 상태이며 팀은 공식적으로 해체되었습니다)

### 금주의 패키지 – Scientist ports
코드를 정리하고 리뷰 하다 보면 코드 리팩토링작업은 필수적으로 하게 마련이다. 그런데 이미 운영 환경에 배포되어있는 코드에 대해서 리팩토
링하는것은 개발자에게는 상당히 부담스러운 작업이다. 이전에 잘돌아가던 코드를 리팩토링된 새로운 코드로 변경한다는것은 특히 운영환경에 적
용한다는것은 리팩토링 양에 따라서 상당한 리스크가 있기떄문이다.
Scientist는 원본 코드와 리팩토링된 코드를 동시에 실행시켜주며 각각의 결과를 로그로 남겨주어 비교할수있게 해주는 라이브러리이다. 원래 
Scientist는 GitHub 를 통해서 배포되는 루비 진영의 라이브러리이다. 이 라이브러리를 이용하면 새로운 코드를 배포하는데 있어서 위험 부담을 
많이 줄일수있다. 그리고 원본 코드와 수정코드의 결과가 서로 다르면 개발자는 어떻게 다음 작업을 할지 쉽게 결정할수있도록 도와준다. 또한 
운영환경에서의 새로운 코드의 데이터를 아무런 부담없이 수집이 가능하다.
이 라이브러리에 대해서 적어도 두개이상의 .NET 포팅작업이 이루어지고있는데 하나는 Phil Haack 가 GitHub 를 통해서 진행하고있는 
Scientist.NET 프로젝트이며 다른 하나는 좀더 완성도가 높은 Dave Zych의 Schience 이다.
두개 모두 아직은 초기 버전이지만 개발자라면 관심깊게 볼 필요가 있는 프로젝트이다. 그리고 용기내어 프로젝트에 참여해보는것도 좋을듯하다.

<section>
 var publisher = new FilePublisher(@"C:\file\path\to\results.log"); 
 
 
 var userCanRead = Shience.New<bool>("widget-permissions") 
     .Test(control: () => UserPermissions.CheckUser(currentUser),  
           candidate: () => User.Can(currentUser, Permission.Read)) 
     .PublishTo(publisher.Publish) 
     .Execute(); 
</section>

###.NET 소식
* A (Hitchhiker's) Guide To The .NET Core Projects on GitHub : Mark Rendle가 GitHub 환경에서 .NET Core 프로젝트를 사용하는 가이드를 소개
했습니다
* Run dotnet CLI on unsupported Linux distros with docknet by Mark Rendle.
* .NET Core: Introduction To Microsoft.Data.Sqlite : Ranjan Dailata가 .NET Core기반에서 사용할수있는 오픈소스 NuGet 패키지인 "Microsoft.Data.Sqlite"를 소개했습니다. 
* Weak events in .NET using Reactive Extensions : Kenneth Haugland가 Reactive Extensions을 이용한 Weak events의 구현과 활용에 대해서 공유했습니다.

### ASP.NET 소식
* Our Major Minor – introducing Umbraco 7.4 : Niels Hartvig가 오픈소스기반 CMS(컨텐트 관리 시스템)인 Umbraco의 7.4 버전의 새로운 기능에 대해서 소개했습니다
* RESTful Web API Help Documentation using Swagger UI and Swashbuckle : Sreekanth Mothukuru가 Swagger UI와 Swashbuckle를 이용해서 서버에 서비스되는 RESTful Web API의 도움말 문서를 만드는 방법을 공유했습니다.
* ASP.NET WebHooks and Slack Slash Commands by Henrik F Nielsen.
* Authoring ASP.NET Core MVC Tag Helper by Hossam Barakat.
* Authorization policies and data protection with Identity Server 4 in ASP.NET Core by Damien Bod.
* ServiceStack and Razor Forms by Patrick Steele.
* ASP.NET Core Identity Token Providers – Under the Hood by Steve Gordon.
* AppVeyor and ASP.NET Core by Shazwazza.

