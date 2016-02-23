이번 주에는 리팩토링된 코드를 배포할 때의 부담감을 줄일 수 있는 Scientist 라이브러리를 소개합니다. 프로젝트의 초기 단계이니 관심있으신 개발자 분들은 프로젝트 Contributor 로 참여해보시는 것도 좋을 것 같습니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=BEvn9aI6rd0)는 Aaron Stannard 를 모시고 .NET용 액터 모델 기반의 프레임워크인 Akka.NET 과 NBench 및 DotNetty 프로젝트에 대해 이야기를 나누었습니다.

[이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=WuqrfuJLbgk)는 Joe Duffy 를 모시고 마이크로소프트가 의욕적으로 진행했었던 차세대 OS 개발 연구 프로젝트인 [Midori](http://joeduffyblog.com/2015/11/03/blogging-about-midori/) 프로젝트에 대해 이야기를 나누었습니다. (현재 Midori 프로젝트는 2015 기준으로 중단된 상태이며 팀은 공식적으로 해체되었습니다.)

### 금주의 패키지 – Scientist ports

아무리 주의 깊게 테스트를 해봐도 리팩토링된 코드가 운영 환경에서 문제가 없을 지 100% 확신하기는 어렵습니다. GitHub 를 통해 배포되고 있는 Ruby 언어 진영의 Scientist 라이브러리를 이용하여 이러한 문제를 해결할 수 있습니다. 기존 코드와 리팩토링된 코드를 동시에 실행시키고 결과를 비교해서 보여줍니다. 기존 코드가 동작하고 있기 때문에 새로운 코드를 배포하는 것에 대한 위험 부담을 줄일 수 있습니다. 또한 기존 코드와 실행결과가 다른 경우에 대해 해결책을 세울 수 있고, 새로운 코드가 운영환경에 적용되었을 때의 결과도 짐작할 수 있습니다. 

* [Scientist](https://github.com/github/scientist) 

현재 여러개의 포팅 프로젝트가 진행되고 있는데 그 중 두가지를 살펴보겠습니다. 첫번째는 [Phil Haack](http://haacked.com/) 가 GitHub 를 통해서 진행중인 [Scienctist.NET](https://github.com/haacked/scientist.net) 입니다. 두번째는 Dave Zych 가 진행중인 [Schience](https://github.com/davezych/shience) 프로젝트로 현재로써는 첫번재 프로젝트 보다 조금 더 완성도가 있습니다. 

두 프로젝트 모두 초기 단계이지만 개발자라면 분명 관심있게 보셔야 할 프로젝트 임에는 틀림 없습니다. 이번 기회에 용기내서 프로젝트의 Contributor 로 참여해 보세요.         
     
이미 개발된 코드를 정리하거나 새로운 기능을 추가하다 보면 코드 리팩토링을 자주하게 됩니다. 코드 리팩토링을 통해 코드의 품질이 향상되고 전체적인 코드의 일관성이 유지 되기 때문에 자주 할수록 좋습니다. 하지만 운영 환경에서 동작 중인 코드에 대한 리팩토링 작업은 어떨까요? 아무리 효과적으로 튜닝한 코드라 하더라도 이미 잘 돌아가고 있는 기존 코드를 버리고 새로운 코드로 변경 한다는것은 사실 담당 개발자 입장에서는 반갑지는 않을겁니다. 혹 아주 급한 버그수정이면 모를까 왠만하면 코드수정에 부정적일것입니다. 새로운 코드를 적용 한다는 것은 리팩토링된 코드의 양과 구조에 따라서 상당한 리스크가 있을 수 있습니다. 이럴수 밖에 없는 것은 새로운 코드를 운영 환경에서 충분히 테스트 하는것이 현실적으로 어렵기 때문입니다. 또 이때문에 적용후 결과 또한  충분히 예측하기가 힘듬니다.

이러한 문제를 참신한 아이디어를 바탕으로 개발된 Scientist라는 라이브러가 해결해 줄수있습니다. Scientist는 원본 코드와 리팩토링된 코드를 동시에 그리고 안전하게 실행시켜 주는 것을 가능하게 도와줍니다. 또 각각의 실행 결과를 로그로 남겨주어 개발자가 결과를 쉽게 비교할 수있게 해줍니다. 원래 Scientist는 GitHub를 통해서 배포되는 루비언어 진영 라이브러리의 하나입니다. 이 라이브러리를 이용하면 새로운 코드를 배포하는데 있어서 위험 부담을 상당히 줄일 수 있읍니다. 원본 코드와 수정된 코드의 실행 결과가 서로 다르면 개발자는 이를 바탕으로 다음 판단을 빠르게 수행할 수 있습니다. 그리고 부가적으로 새로운 코드가 운영환경에 적용되어 수행될때 얻을수있는 여러 데이터를 아무런 위험부담없이 수집하는것 또한 가능합니다.(이는 실제로 수행되지않고 로그상으로만 수행되게 할 수 있으므로 가능할것으로 판단됩니다)

이 라이브러리는 .NET환경으로 포팅작업이 이루어지고 있습니다. 현재 복수개의 포팅 프로젝트가 진행중인데 그중 크게 두개의 프로젝트를 살펴보면 하나는 Phil Haack가 GitHub 를 통해서 진행하고 있는 Scientist.NET 프로젝트이고 또 다른 하나는 이보다는 좀 더 완성도가 높은 Dave Zych의 Schience라는 프로젝트입니다.
이 라이브러리들의 한가지 약점은 두개 닷넷 포팅버전이 아직은 초기버전이라는 것입니다. 따라서 운영 환경에 적용하는데는 아직 무리가 있을수 있겠지만 개발자라면 분명히 관심있게 봐야할 프로젝트인거는 맞는것 같습니다. 이 기회에 용기내어 이들 프로젝트에 참여해 보는것도 나쁘지 않은 생각인것 같습니다.

<section>
{{Schience.cs}}<script src="https://gist.github.com/bleroy/7f668d844f4023c9537f.js"></script>
</section>

###.NET 소식
* [A (Hitchhiker's) Guide To The .NET Core Projects on GitHub](http://umbraco.com/follow-us/blog-archive/2016/2/11/our-major-minor-introducing-umbraco-74/) : Mark Rendle 가 GitHub 에서 .NET Core 프로젝트를 사용하는 방법을 소개했습니다.
* Mark Rendle 의 [Run dotnet CLI on unsupported Linux distros with docknet](https://blog.rendle.io/run-dotnet-cli-on-unsupported-linux-distros-with-docknet/) 
* [.NET Core: Introduction To Microsoft.Data.Sqlite](http://www.c-sharpcorner.com/UploadFile/ranjancse/net-co-introduction-to-microsoft-data-sqlite/) : Ranjan Dailata 가 .NET Core 에서 사용할 수 있는 NuGet 패키지인 Microsoft.Data.Sqlite 를 소개했습니다. 
* [Weak events in .NET using Reactive Extensions](http://www.codeproject.com/Tips/1078183/Weak-events-in-NET-using-Reactive-Extensions-Rx) : Kenneth Haugland 가 Reactive Extensions 을 이용한 Weak events 의 구현과 활용에 대해서 공유했습니다.

### ASP.NET 소식
* [Our Major Minor – introducing Umbraco 7.4](http://umbraco.com/follow-us/blog-archive/2016/2/11/our-major-minor-introducing-umbraco-74/) : Niels Hartvig 가 오픈소스기반 CMS(컨텐츠 관리 시스템)인 Umbraco 7.4 버전의 새로운 기능에 대해서 소개했습니다.
* [RESTful Web API Help Documentation using Swagger UI and Swashbuckle](http://www.codeproject.com/Articles/1078249/RESTful-Web-API-Help-Documentation-using-Swagger-U) : Sreekanth Mothukuru 가 Swagger UI 와 Swashbuckle 를 이용해서 서버에 서비스되는 RESTful Web API 의 도움말 문서를 만드는 방법을 공유했습니다.
* Henrik F Nielsen 의 [ASP.NET WebHooks and Slack Slash Commands](https://blogs.msdn.microsoft.com/webdev/2016/02/14/asp-net-webhooks-and-slack-slash-commands/)
* Hossam Barakat 의 [Authoring ASP.NET Core MVC Tag Helper](http://www.hossambarakat.net/2016/02/15/authoring-asp-net-core-mvc-tag-helper/)
* Damien Bod 의 [Authorization policies and data protection with Identity Server 4 in ASP.NET Core](http://damienbod.com/2016/02/14/authorization-policies-and-data-protection-with-identityserver4-in-asp-net-core/)
* Patrick Steele 의 [ServiceStack and Razor Forms](https://visualstudiomagazine.com/articles/2016/02/01/servicestack-and-razor-forms.aspx)
* Steve Gordon 의 [ASP.NET Core Identity Token Providers – Under the Hood](http://stevejgordon.co.uk/asp-net-core-identity-token-providers)
* Shazwazza 의 [AppVeyor and ASP.NET Core](http://shazwazza.com/post/appveyor-and-aspnet-core/) 

주간닷넷은 [.NET Blog](https://blogs.msdn.microsoft.com/dotnet/) 에서 매주 발행 중인 The week in .NET 을 번역하여 진행하고 있습니다.
The week in .NET 의 한글 번역은 오픈에스지닷넷의 송기수 이사님의 도움을 받아 진행하고 있습니다.  

