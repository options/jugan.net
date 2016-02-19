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
 

* [DotNetAPIs](http://dotnetapis.com/)
###.NET 소식
•A (Hitchhiker's) Guide To The .NET Core Projects on GitHub : Mark Rendle가 GitHub환경에서 .NET Core 프로젝트를 사용하는 가이드를 공유
했습니다
•Run dotnet CLI on unsupported Linux distros with docknet by Mark Rendle.
•.NET Core: Introduction To Microsoft.Data.Sqlite by Ranjan Dailata.
•Weak events in .NET using Reactive Extensions by Kenneth Haugland.
* Immo Landwerth 가 [기존 .NET 코드를 .NET Core 로 이식하는 방법](https://blogs.msdn.microsoft.com/dotnet/2016/02/10/porting-to-net-
core/)을 공유했습니다.
* Joe Duffy 가 [미도리(Midori) 라는 마이크로소프트가 개발 중인 차세대 운영 체제에 대한 글을 에러 패턴에 대한 내용과 함께 연재]
(http://joeduffyblog.com/2016/02/07/the-error-model/)하고 있습니다. 
* [What I’ve learned about .NET Native](https://blog.rendle.io/what-ive-learned-about-dotnet-native/) : Mark Rendle 이 .NET Native 를 
접하면서 알게 된 여러 사항들을 공유했습니다.
* Bertrand Le Roy 가 LADOTNET 커뮤니티에서 [.NET Core](http://www.slideshare.net/BertrandLeRoy/net-core) 및 [C# Today and Tomorrow]
(http://www.slideshare.net/BertrandLeRoy/c-today-and-tomorrow) 라는 주제로 발표했습니다.  
* [Learn how to use the Windows Event Log via C#](http://automatetheplanet.com/windows-event-log-tips/) : Anton Angelov 가 C# 의 윈도우 
이벤트 로그를 활용하는 방법을 공유했습니다.
* [Project.json all the things](https://oren.codes/2016/02/08/project-json-all-the-things/) : Oren Novotny 이 Visual Studio 2015 에서 
Project.json 을 사용하는 방법을 공유했습니다. 
* [FormatFilter and MediaTypeMappings in ASP.NET Core 1.0 MVC](http://www.strathweb.com/2016/02/formatfilter-and-mediatypemappings-in-
asp-net-core-1-0-mvc/) : Filip W. 가 ASP.NET Core 1.0 MVC 에서 FormatFilter 와 MediaTypeMappings 을 사용하는 방법을 소개했습니다.

### ASP.NET 소식
•Our Major Minor – introducing Umbraco 7.4 by Niels Hartvig.
•RESTful Web API Help Documentation using Swagger UI and Swashbuckle by Sreekanth Mothukuru.
•ASP.NET WebHooks and Slack Slash Commands by Henrik F Nielsen.
•Authoring ASP.NET Core MVC Tag Helper by Hossam Barakat.
•Authorization policies and data protection with Identity Server 4 in ASP.NET Core by Damien Bod.
•ServiceStack and Razor Forms by Patrick Steele.
•ASP.NET Core Identity Token Providers – Under the Hood by Steve Gordon.
•AppVeyor and ASP.NET Core by Shazwazza.

* [The Ultimate Guide To Unit Testing in ASP.NET MVC](http://www.danylkoweb.com//Blog/the-ultimate-guide-to-unit-testing-in-aspnet-
mvc-E2) : Jonathan Danylko 가 ASP.NET MVC 에서 단위 테스트 구현 및 활용 방법을 소개했습니다.
* [A run around the new ASP.NET Data Protection & Authorization Stacks (video)](https://vimeo.com/153102690) : Barry Dorrans 이 NDC 컨
퍼런스에서 ASP.NET 의 보안과 관련된 세션을 진행했습니다.
* [Configuring Redis as the ASP.NET Core session store](http://www.hossambarakat.net/2016/02/03/configuring-redis-as-asp-net-core-1-0-
session-store/) : Hossam Barakat 이 ASP.NET 에서 사용할 수 있는 인 메모리 데이터 엔진인 Redis 를 구성하고 활용하는 방법을 공유했습니다.
* [Release management using VSTS](https://codesnob.wordpress.com/2016/02/04/release-management-using-vsts/) : Alton Crossley 가 VSTS 를 
이용해 배포를 관리하는 법을 공유했습니다.
* [A simple authentication library for .NET Core, because sometimes less is more]
(https://github.com/joeaudette/cloudscribe.Web.SimpleAuth) : Joe Audette 가 ASP.NET Core 에서 데이터베이스 없이 간단하게 권한을 관리 할 
수 있는 라이브러리를 공개했습니다.
* [Preventing sensitive data exposure in ASP.NET Part 1, Part 2](http://lockmedown.com/preventing-sensitive-data-exposure-aspnet-
part1/) : Max R McCarty 이 ASP.NET 애플리케이션에서 외부에 노출되면 안되는 민감한 사용자 데이터를 쉽게 관리하고 보호하는 방법을 [Part 
1](http://lockmedown.com/preventing-sensitive-data-exposure-aspnet-part1/) 과 [Part 2](http://lockmedown.com/preventing-sensitive-
data-exposure-aspnet-part2/) 에 걸쳐서 공유했습니다.
* [Great series on multi-tenancy with ASP.NET MVC](http://benfoster.io/blog/tagged/multi-tenancy) : Ben Foster 가 ASP.NET Core 기반의 
Multi-tenancy 웹 사이트를 만드는 방법을 연재하고 있습니다.
* Rich Hosek 이 [ASP.NET Core 응용 프로그램에서 태그에 인라인 이미지를 적용하는 방법]
(http://adventuresinwebprogramming.blogspot.kr/2016/02/inline-image-taghelper.html)을 설명합니다.

