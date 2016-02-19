### On.NET 소식
[지난번 On.NET 동영상 인터뷰]지난주는 Aaron Stannard와 함께 .NET용 액터 모델 기반의 프레임워크인 Akka.NET에 대해서 얘기나누었습니다.

[이번 On.NET 유튜브 동영상 인터뷰] 이번주는 Joe Duffy를 모시고 마이크로소프트가 의욕적으로 진행했던 차세대 OS 프로젝트인 Midori 프로젝트에 대해서 얘기해 볼 예정입니다. (현재 Midori 프로젝트는 취소된 상태이며 팀은 공식적으로 해체되었습니다. 하지만 그들의 경험은 많은 도움이 될것입니다)

### 금주의 패키지 – Scientist ports
이미 개발된 코드를 정리하고 리뷰하다 보면 코드 리팩토링작업을 빈번히 하게 마련입니다. 하지만 개발이 완료되어 이미 운영 환경에 배포 되어있는 코드에 대해서 리팩토링 작업을 하는것은 상당히 부담스러운 작업입니다. 아무리 효과적으로 튜닝된 코드라 하더라도 이미 잘 돌아가고있는 기존 코드를 버리고 새로운 코드로 변경 한다는것은 사실 개발자 입장에서는 버그수정과 같은 아주 급하지 않은 상황이라면 하고 싶지 않을 것입니다. 특히 운영환경에 새로운 코드를 적용 한다는 것은 리팩토링된 코드의 양과 구조에 따라서 상당한 리스크가 있을수있으며 결과를 충분히 예측하기가 상당히 어렵습니다.
이러한 문제를 Scientist는 참신한 아이디어를 바탕으로 해결해줌니다. Scientist는 원본 코드와 리팩토링된 코드를 동시에 그리고 안전하게 실행시켜주며 각각의 실행 결과를 로그로 남겨주어 개발자가 비교할수있게 해주는 라이브러리이다. 원래 Scientist는 GitHub 를 통해서 배포되는 루비언어 진영 라이브러리의 하나입니다. 이 라이브러리를 이용하면 새로운 코드를 배포하는데 있어서 위험 부담을 
상당히 줄일 수 있읍니다. 또 원본 코드와 수정된 코드의 실행 결과가 서로 다르면 개발자는 이를 바탕으로 다음 판단을 빠르게 수행할 수 있습니다. 그리고 새로운 코드가 운영환경에 적용되어 수행될때 얻을수있는 여러 데이터를 아무런 부담없이 수집이 가능합니다.(이는 실제로 수행되지않고 로그상으로만 수행되게 할 수 있으므로)
현재 라이브러리에 대해서는 적어도 두개이상의 .NET 포팅작업이 이루어지고 있습니다. 하나는 Phil Haack가 GitHub 를 통해서 진행하고 있는 
Scientist.NET 프로젝트입니다. 또 다른 하나는 이보다는 좀 더 완성도가 높은 Dave Zych의 Schience입니다.
두개 모두 아직은 초기 버전입니다. 안전한 운영환경을 위해서 아직 완성되지않은 불안전한 라이브러리 설치하는것은 왠지 좀 앞뒤가 맞지않는것 같군요. 하지만 개발자라면 분명히 관심깊게 볼 가치가 있는 프로젝트인거 같습니다. 그리고 용기내어 이런 유용한 프로젝트에 참여해서 완성도를 높이는데 공헌해 보는것도 좋은 생각인것 같습니다.

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

