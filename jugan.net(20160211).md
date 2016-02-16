 이번 주 소식에는 LADOTNET 커뮤니티 분들과 함께 .NET Core, C# 6, 그리고 향후 C# 의 방향에 대해 이야기를 나눈 내용이 포함되어 있습니다. 관련된 자료는 아래의 .NET 소식에서 확인하실 수 있습니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=g2a4W6Q7aRw)는 ASP.NET 팀의 수석 프로그램 매니저인 Scott Hunter 를 모시고 .NET, ASP.NET 및 .NET Core 릴리즈 관련 이야기를 나누었습니다. 

[이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=BEvn9aI6rd0)는 Aaron Stannard 를 모시고 Actor 모델 기반의 .NET 용 프레임워크인 Akka.NET 과 NBench 및 DotNetty 프로젝트 관련 이야기를 나누었습니다.

### 금주의 패키지 – Polly

분산 애플리케이션 프로젝트가 활성화되면서 예외 처리로 일시적인 에러나 흐름을 제어하는 것이 항상 효과적인 방법은 아닙니다. 클라이언트 프로그램이 원격 서비스와 통신을 하는 경우를 예를 들어 보겠습니다. 원격 서비스 접속에 실패할 경우 일정 시간이 지난 후  재접속을 시도하는 로직을 구현하려 할 수 있습니다. Polly 는 이러한 상황에 적용할 수 있는 다양한 API 를 제공합니다

<section>
{{pollyasyncsample.cs}}<script src="https://gist.github.com/bleroy/33881883f87a763f5ceb.js"></script>
</section>


### 금주의 툴 - DotNetAPIs

DotNetAPIs 는 통합 API 문서 웹 사이트이며 동시에 수많은 .NET API 와 라이브러리를 검색할 수 있는 훌륭한 페이지입니다. 이 서비스는 모든 NuGet 패키지를 분석하여 관련된 XML 문서를 하나도 빠짐없이 추출하는 방식으로 서비스를 제공합니다. 닷넷 개발자들에게 아주 유용한 새로운 툴 입니다.

* [DotNetAPIs](http://dotnetapis.com/)

###.NET 소식

* Immo Landwerth 가 [기존 .NET 코드를 .NET Core 로 이식하는 방법](https://blogs.msdn.microsoft.com/dotnet/2016/02/10/porting-to-net-core/)을 Porting to .NET Core 에 공유했습니다.

* Joe Duffy 가 [미도리(Midori) 라는 마이크로소프트가 개발 중인 차세대 운영 체제에 대한 글을 에러 패턴에 대한 내용과 함께 연재](http://joeduffyblog.com/2016/02/07/the-error-model/)하고 있습니다. 

* [What I’ve learned about .NET Native](https://blog.rendle.io/what-ive-learned-about-dotnet-native/) : Mark Rendle 이 .NET Native 를 접하면서 알게 된 사항들을 공유했습니다.

* Bertrand Le Roy 가 LADOTNET 커뮤니티에서 [.NET Core](http://www.slideshare.net/BertrandLeRoy/net-core) 및 [C# Today and Tomorrow](http://www.slideshare.net/BertrandLeRoy/c-today-and-tomorrow) 라는 주제로 발표했습니다.  

* [Learn how to use the Windows Event Log via C#](http://automatetheplanet.com/windows-event-log-tips/) : Anton Angelov 가 C# 의 윈도우 이벤트 로그를 활용하는 방법을 공유했습니다.

* [Project.json all the things](https://oren.codes/2016/02/08/project-json-all-the-things/) : Oren Novotny 이 VisualStudio 2015 에서 Project.json 을 사용하는 방법을 공유했습니다. 

* [FormatFilter and MediaTypeMappings in ASP.NET Core 1.0 MVC](http://www.strathweb.com/2016/02/formatfilter-and-mediatypemappings-in-asp-net-core-1-0-mvc/) : Filip W. 가 ASP.NET Core 1.0 MVC 에서 FormatFilter 와 MediaTypeMappings 을 사용하는 방법을 소개했습니다.


### ASP.NET 소식

* [The Ultimate Guide To Unit Testing in ASP.NET MVC](http://www.danylkoweb.com//Blog/the-ultimate-guide-to-unit-testing-in-aspnet-mvc-E2) : Jonathan Danylko 가 ASP.NET MVC 에서 단위 테스트 구현 및 활용 방법을 소개했습니다.

* [A run around the new ASP.NET Data Protection & Authorization Stacks (video)](https://vimeo.com/153102690) : Barry Dorrans 이 NDC 컨퍼런스에서 ASP.NET 의 보안과 관련된 세션을 진행했습니다.

* [Configuring Redis as the ASP.NET Core session store](http://www.hossambarakat.net/2016/02/03/configuring-redis-as-asp-net-core-1-0-session-store/) : Hossam Barakat 이 ASP.NET 에서 사용할 수 있는 인 메모리 데이터 엔진인 Redis 를 설정하고 활용하는 방법을 공유했습니다.

* [Release management using VSTS](https://codesnob.wordpress.com/2016/02/04/release-management-using-vsts/) : Alton Crossley 가 VSTS 를 이용해 배포를 관리하는 법을 공유했습니다.

* [A simple authentication library for .NET Core, because sometimes less is more](https://github.com/joeaudette/cloudscribe.Web.SimpleAuth) : Joe Audette 가 ASP.NET Core 에서 데이터베이스 없이 간단하게 권한을 관리 할 수 있는 라이브러리를 공개했습니다.

* [Preventing sensitive data exposure in ASP.NET Part 1, Part 2](http://lockmedown.com/preventing-sensitive-data-exposure-aspnet-part1/) : Max R McCarty 이 ASP.NET 애플리케이션에서 외부에 노출되면 곤란한 민감한 사용자 데이터를 쉽게 관리하고 보호하는 방법을 [Part 1](http://lockmedown.com/preventing-sensitive-data-exposure-aspnet-part1/) 과 [Part 2](http://lockmedown.com/preventing-sensitive-data-exposure-aspnet-part2/) 에 걸쳐서 공유했습니다.

* [Great series on multi-tenancy with ASP.NET MVC](http://benfoster.io/blog/tagged/multi-tenancy) : Ben Foster 가 ASP.NET Core 기반의 Multi-tenancy 웹 사이트를 만드는 방법을 연재하고 있습니다.

* Rich Hosek 이 [ASP.NET Core 응용 프로그램에서 태그에 인라인 이미지를 적용하는 방법](http://adventuresinwebprogramming.blogspot.kr/2016/02/inline-image-taghelper.html)을 설명합니다.

### F# 소식

* [The Jet Engine We Built in 2015](http://techgroup.jet.com/blog/2016/02-05-the-jet-engine-we-built-in-2015/index.html) : Louie Bacaj 이 F# 으로 개발된 전자상거래 사이트인 jet.com 를 소개했습니다.

* [Ten Tips for Productive F# Scripting](http://brandewinder.com/2016/02/06/10-fsharp-scripting-tips/) : Mathias Brandewinder 가 F# 스크립트에 도움이 되는 10가지 팁을 공유했습니다.

* [A Cheatsheet for F#’s DSL-friendly Features](https://github.com/dungpa/dsls-in-action-fsharp/blob/master/DSLCheatsheet.md) : Anh-Dung Phan 가 F# 의 DSL(Domain Specific Languages) 기능을 정리해서 공유했습니다.

* [Building a Poker Bot: Card Recognition](http://mikhail.io/2016/02/building-a-poker-bot-card-recognition/) : Mikhail Shilkov 가 닷넷 프레임워크와 F# 이용해 Poker Bot 게임 만드는 방법을 소개하는 글을 연재하기 시작했습니다.

* [How to Keep the Domain Pure When Logic Depends on the Current Date](http://www.taimila.com/blog/fsharp-pure-time-dependent-domain/) : Lauri Taimila 가 날짜에 의존적이지 않은 함수형 프로그램 개발 방법을 소개했습니다.

* [F# for Beginners](https://sachabarbs.wordpress.com/1406-2/) : Sascha Barbs 가 초보자를 위한 F# 정보를 공유했습니다.


###.NET 게임 소식

* Jb Evain 의 [Visual Studio Tools for Unity 2.2](https://blogs.msdn.microsoft.com/visualstudio/2016/02/04/visual-studio-tools-for-unity-2-2/)

* JP Hawkins 의 [Valve Brings SteamVR to Unity](http://blogs.unity3d.com/2016/02/10/valve-brings-steamvr-to-the-unity-technologies-platform/)

* [Vision Summit 2016 의 키노트 내용](https://www.youtube.com/watch?v=2hYDtxCtzdA)

### Global Game Jam 2016 Submission

 [Cannibroth](http://globalgamejam.org/2016/games/cannibroth) 라는 게임을 소개하고자 합니다. 이 게임은 작은 부족을 방문한 탐험가가 되어보는 게임입니다. 춤으로 소통하는 부족과 대화하기 위해 게이머도 상황에 맞게 적절하게 춤을 추어야 합니다. 그렇지 못하면 뜨거운 단지에 담긴 당근 요리 신세가 되고 말 것 입니다.

[image](https://camo.githubusercontent.com/72ad3c8fd24c3634eb665eb5c62dee80c3d12d69/687474703a2f2f62726574687564736f6e2e636f6d2f67616d6573662f696d616765732f63616e6e6962726f74682e706e67)