이번 주에는 리팩토링된 코드를 배포할 때의 부담감을 줄일 수 있는 Scientist 라이브러리를 소개합니다. 아직 프로젝트가 초기 단계인  만큼 관심 있으신 개발자분들 이라면 Contributor 로 참여해보시는 것도 좋을 것 같습니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=BEvn9aI6rd0)는 Aaron Stannard 를 모시고 .NET 용 액터 모델 기반의 프레임워크인 Akka.NET 과 NBench 및 DotNetty 프로젝트에 대해 이야기를 나누었습니다.

[이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=WuqrfuJLbgk)는 Joe Duffy 를 모시고 마이크로소프트가 의욕적으로 진행했었던 차세대 OS 개발 연구 프로젝트인 [Midori](http://joeduffyblog.com/2015/11/03/blogging-about-midori/) 프로젝트에 대해 이야기를 나누었습니다. (현재 Midori 프로젝트는 2015 기준으로 중단된 상태이며 팀은 공식적으로 해체되었습니다.)

### 금주의 패키지 – Scientist ports  
     
기존에 개발된 코드를 정리하고 새로운 기능을 추가하다 보면 코드 리팩토링을 자주하게 됩니다. 코드 리팩토링을 통해 코드의 품질을 향상하고 코드의 일관성을 유지할 수 있으므로 자주 할 수 있다면 좋을 것입니다. 하지만 운영 환경에서 이미 동작 중인 코드라면 어떨까요? 이러한 환경에 새로운 코드를 적용하는 것은 리팩토링한 코드의 양과 구조에 따라 상당한 리스크가 있을 수 있습니다. 

GitHub 를 통해 배포되고 있는 Ruby 언어용 Scientist 라이브러리는 이러한 문제를 해결하기 위해 개발되었습니다. 이 라이브러리를 이용하면 기존 코드와 리팩토링한 코드를 동시에 실행시켜 결과를 비교해 볼 수 있습니다. 기존 코드가 동작하고 있으므로 새로운 코드 배포에 대한 위험 부담을 줄일 수 있습니다. 더불어 기존 코드와 실행결과가 다른 경우에 대해 해결책을 세울 수 있고, 새로운 코드가 운영환경에 적용되었을 때의 결과도 짐작할 수 있습니다.(이는 실제로 수행되는 것이 아니라 로그상으로만 수행되기 때문에 가능한 것으로 판단됩니다.)

* [Scientist](https://github.com/github/scientist) 

현재 여러 개의 포팅 프로젝트가 진행되고 있는데 그중 두 가지를 살펴보겠습니다. 첫 번째는 [Phil Haack](http://haacked.com/) 이  GitHub 를 통해서 진행중인 [Scienctist.NET](https://github.com/haacked/scientist.net) 입니다. 두번째는 Dave Zych 가 진행 중인 [Schience](https://github.com/davezych/shience) 프로젝트로 현재로써는 첫 번째 프로젝트보다 조금 더 완성도가 높습니다.

두 프로젝트가 모두 초기 단계이지만 개발자라면 분명 관심 있게 보셔야 할 프로젝트임에는 틀림없습니다. 이번 기회에 용기 내서 프로젝트의 Contributor 로 참여해 보세요.    

<section>
{{Schience.cs}}<script src="https://gist.github.com/bleroy/7f668d844f4023c9537f.js"></script>
</section>

### .NET 소식

* [A (Hitchhiker's) Guide To The .NET Core Projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/) : Mark Rendle 가 GitHub 에서 .NET Core 프로젝트를 사용하는 방법을 소개했습니다.
* [Run dotnet CLI on unsupported Linux distros with docknet](https://blog.rendle.io/run-dotnet-cli-on-unsupported-linux-distros-with-docknet/) : Mark Rendle는 dontnet CLI 를 공식 지원하지 않는 Linux 배포판에서 docknet 을 이용하는 방법에 대해서 소개하였습니다.
* [.NET Core: Introduction To Microsoft.Data.Sqlite](http://www.c-sharpcorner.com/UploadFile/ranjancse/net-co-introduction-to-microsoft-data-sqlite/) : Ranjan Dailata 가 .NET Core 에서 사용할 수 있는 NuGet 패키지인 Microsoft.Data.Sqlite 를 소개했습니다. 
* [Weak events in .NET using Reactive Extensions](http://www.codeproject.com/Tips/1078183/Weak-events-in-NET-using-Reactive-Extensions-Rx) : Kenneth Haugland 가 Reactive Extensions 을 이용한 Weak events 의 구현과 활용에 대해서 공유했습니다.

### ASP.NET 소식

* [Our Major Minor – introducing Umbraco 7.4](http://umbraco.com/follow-us/blog-archive/2016/2/11/our-major-minor-introducing-umbraco-74/) : Niels Hartvig 가 오픈소스 기반 CMS(콘텐츠 관리 시스템)인 Umbraco 7.4 버전의 새로운 기능을 소개합니다.
* [RESTful Web API Help Documentation using Swagger UI and Swashbuckle](http://www.codeproject.com/Articles/1078249/RESTful-Web-API-Help-Documentation-using-Swagger-U) : Sreekanth Mothukuru 가 Swagger UI 와 Swashbuckle 를 이용해서 RESTful Web API 의 도움말 문서를 만드는 방법을 공유했습니다.
* Henrik F Nielsen 의 [ASP.NET WebHooks and Slack Slash Commands](https://blogs.msdn.microsoft.com/webdev/2016/02/14/asp-net-webhooks-and-slack-slash-commands/) : Henrik F Nielsen 이 Slack Slash Commands 와 함께 사용하면 좋은 ASP.NET WebHooks 의 새로운 기능에 대해 소개했습니다. 
* [Authoring ASP.NET Core MVC Tag Helper](http://www.hossambarakat.net/2016/02/15/authoring-asp-net-core-mvc-tag-helper/) : Hossam Barakat 이 ASP.NET Core MVC 에 추가된 Tag Helper 를 이용하여 Custom Tag 를 작성하는 방법을 소개합니다.  
* [Authorization policies and data protection with Identity Server 4 in ASP.NET Core](http://damienbod.com/2016/02/14/authorization-policies-and-data-protection-with-identityserver4-in-asp-net-core/) : Damien Bod 이 ASP.NET Core 에서 Identity Server 4 를 이용한 인증 정책과 데이터 보호에 대한 글을 작성하였습니다.
* [ServiceStack and Razor Forms](https://visualstudiomagazine.com/articles/2016/02/01/servicestack-and-razor-forms.aspx) : Patrick Steele 이 Razor Forms 기능 덕분에 완벽한 웹 애플리케이션 프레임워크로 발전하고 있는 ServiceStack 에 대해 소개합니다. 
* [ASP.NET Core Identity Token Providers – Under the Hood](http://stevejgordon.co.uk/asp-net-core-identity-token-providers) : Steve Gordon 이 새로운 사용자를 등록하기 위해 사용되는 이메일 토큰에 대해 소개했습니다. 
* [AppVeyor and ASP.NET Core](http://shazwazza.com/post/appveyor-and-aspnet-core/) : Shazwazza 이 ASP.NET Core 에서 지속 배포 서비스인 AppVeyor 의 사용방법을 안내합니다.  

[주간닷넷](https://www.facebook.com/jugan.net/)은 [.NET Blog](https://blogs.msdn.microsoft.com/dotnet/) 에서 매주 발행하는 The week in .NET 을 번역하여 진행하고 있으며, 한글 번역 작업을 오픈에스지닷넷의 송기수 이사님의 도움을 받아 진행하고 있습니다.  



