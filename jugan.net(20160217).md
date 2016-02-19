### On.NET 소식
[지난번 On.NET 동영상 인터뷰]지난주는 Aaron Stannard와 함께 .NET용 액터 모델 기반의 프레임워크인 Akka.NET에 대해서 얘기나누었습니다.

[이번 On.NET 유튜브 동영상 인터뷰] 이번주는 Joe Duffy를 모시고 마이크로소프트가 의욕적으로 진행했던 하지만 포기한(ㅠㅠ) 차세대 OS 개발 연구 프로젝트인 Midori 프로젝트에 대해서 얘기해 볼까 합니다. (현재 Midori 프로젝트는 2015 기준으로 취소된 상태이며 팀은 공식적으로 해체되었습니다. 하지만 이 프로젝트와 팀원들의 경험담은 많은 도움이 될것입니다)

### 금주의 패키지 – Scientist ports
이미 개발된 코드를 정리하거나 새로운 기능을 추가하다 보면 기존 코드 리팩토링을 자주하게 마련입니다. 사실 일반적으로 코드 리팩토링은 자주하면 할수록 코드의 품질이 좋아지고 전체적으로 코드의 일관성이 유지 되기 때문에 권장되는 작업입니다. 하지만 이미 개발이 완료되어 운영 환경에서 잘 돌아 가는 코드에 대한 리팩토링 작업은 어떨까요? 아무리 효과적으로 튜닝한 코드라 하더라도 이미 잘 돌아가고 있는 기존 코드를 버리고 새로운 코드로 변경 한다는것은 사실 담당 개발자 입장에서는 반갑지는 않을겁니다. 혹 아주 급한 버그수정이면 모를까 왠만하면 코드수정에 부정적일것입니다. 새로운 코드를 적용 한다는 것은 리팩토링된 코드의 양과 구조에 따라서 상당한 리스크가 있을수있습니다. 이는 새로운 코드를 운영 환경에서 충분히 테스트 하는것이 현실적으로 어렵고 또 이때문에 적용후 결과를 충분히 예측하기가 힘들기 때문입니다.

이러한 문제를 참신한 아이디어를 바탕으로 개발된 Scientist라는 라이브러가 해결해 줄수있습니다. Scientist는 원본 코드와 리팩토링된 코드를 동시에 그리고 안전하게 실행시켜 주는 것이 가능합니다. 또 각각의 실행 결과를 로그로 남겨주어 개발자가 결과를 쉽게 비교할 수있게 해주는 라이브러리입니다. 원래 Scientist는 GitHub를 통해서 배포되는 루비언어 진영 라이브러리의 하나입니다. 이 라이브러리를 이용하면 새로운 코드를 배포하는데 있어서 위험 부담을 상당히 줄일 수 있읍니다. 원본 코드와 수정된 코드의 실행 결과가 서로 다르면 개발자는 이를 바탕으로 다음 판단을 빠르게 수행할 수 있습니다. 그리고 부가적으로 새로운 코드가 운영환경에 적용되어 수행될때 얻을수있는 여러 데이터를 아무런 위험부담없이 수집 가능합니다.(이는 실제로 수행되지않고 로그상으로만 수행되게 할 수 있으므로 가능할것으로 판단됩니다)

이 라이브러리는 .NET환경으로 포팅작업이 이루어지고 있습니다. 현재 복수개의 포팅 프로젝트가 진행중인데 그중 크게 두개의 프로젝트가 있습니다. 하나는 Phil Haack가 GitHub 를 통해서 진행하고 있는 Scientist.NET 프로젝트이고 또 다른 하나는 이보다는 좀 더 완성도가 높은 Dave Zych의 Schience라는 프로젝트입니다.
이 라이브러리들의 한가지 약점은 두개 닷넷 포팅버전이 아직은 초기라는 것입니다. 따라서  운영 환경에 적용하는데는 아직 무리가 있을수 있겠지만 개발자라면 분명히 관심있게 봐야할 프로젝트인거는 확실한것 같습니다. 그리고 이 기회에 용기내어 이들 프로젝트에 참여해 보는것도 나쁘지 않은 생각인것 같습니다.

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

