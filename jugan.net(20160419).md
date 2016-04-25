지난 토요일에 개최된 Build 2016 다시보기 행사에 200명에 가까운 분들이 함께해주셨습니다. 성원에 감사드립니다. 
지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난 번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=hDDd_Pjtbx8)는 모바일 백엔드 플랫폼을 제공하는 회사인 PlayFab 에서 근무하고 계신 분들을 모시고 게임 개발자들이 클라우드 서비스를 이용함으로써 얻을 수 있는 장점에 대해 알아보았습니다. [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=7E7JyvBIGKs)는 3rd Party 컴포넌트 제작사인 [Telerik](http://www.telerik.com/) 에서 근무하고 계시는 분들과 이야기 나누었습니다. 

### 금주의 패키지- NUglify
Nuglify 는 JavaScript 와 CSS 를 최소한으로 사용할 수 있도록 도와주는 라이브러리입니다. 별도의 외부 라이브러리 참조를 전혀 필요로 하지 않는 독립적인 라이브러리이며  .NET Core 에서 동작합니다.

Code

### 금주의 Xamarin 애플리케이션 - Cinemark
Cinemark 는 북미 지역에서 유명한 영화관으로 연간 27 억불(약 3조원)의 매출을 기록하며 약 5,600 개의 상영관을 가지고 있습니다. 하이브리드 애플리케이션 개발 프레임워크인 Appcelerator 와 Sencha Touch 을 이용한 애플리케이션 개발에 만족하지 못하고, 결국 Xamarin 을 이용하여 개발하기로 결정했습니다. 그 결과 미국 최대의 영화관이라는 명성에 걸맞는 애플리케이션이 개발되었고 이 애플리케이션을 통한 예약 및 결재 트랜잭션도 증가하였습니다. 

### 금주의 컴포넌트 - SharpDevelop’s WPF Designer
2015년 10월 이후, [SharpDevelop](http://www.icsharpcode.net/OpenSource/SD/Default.aspx) 의 [WPF 디자인 도구](https://github.com/icsharpcode/WpfDesigner/)는 [독립 컴포넌트](https://www.nuget.org/packages/ICSharpCode.WpfDesigner/)가 되어 XAML 디자인 도구와 연동하여 어떠한 애플리케이션에서도 재사용이 가능해졌습니다. 또한 기존에 참조하였던 3rd Party 도구들을 더 이상 사용하지 않기 때문에 [의존성이 없고](http://community.sharpdevelop.net/blogs/jochenkuehner/archive/2016/04/12/wpf-designer-news.aspx) 개발 및 배포 관리도 더욱 용이해졌습니다. 

image - Component

### 금주의 게임 - Dungeon of the Endless
 [Amplitude Studios](http://madewith.unity.com/profiles/amplitude-studios) 에서 개발한 [Dungeon of the Endless](http://madewith.unity.com/games/dungeon-endless) 는 [Unity](http://unity3d.com/) 와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 개발되었으며 던전에서 방어하는 형식의 게임으로 일종의 [로그라이크(Rogue-Like)](https://en.wikipedia.org/wiki/Roguelike) 게임입니다. 게이머는 혼자 혹은 팀을 이루어 타워를 방어하며 팀을 조종합니다. RPG 형태의 로그라이크 케렉터와 아이템들이 아름답게 잘 구현되어져 있습니다. 플레이어는 Auriga 행성에 충돌한 우주선의 크리스털 파워를 보호하고 탈출의 길을 찾으면서 팀 영웅의 역할 수행을 합니다. Dungeon of the Endless 의 각각의 스테이지에 여러 종류의 몬스터와 악당들이 등장하여 플레이어를 괴롭힙니다 . 이들의 목적은 플레이어가 컨트롤하는 영웅과 우주선의 크리스털 파워를 죽이는 것이며 각각의 스테이지를 클리어 할 때마다  새로운 팀을 꾸릴 수 있는 기회가 주어집니다. 새롭게 구성된 팀으로 다른 던전을 계속 탐험하게 됩니다.

Steam 과 iTunes 에서 Dungeon of the Endless 를 다운로드 받으실 수 있으며, 자세한 내용은 [링크](http://madewith.unity.com/games/dungeon-endless)를 확인하시기 바랍니다.

image - Game

### .NET 소식
* [What’s new for the .NET Native Compiler and Runtime in Visual Studio 2015 Update 2](https://blogs.msdn.microsoft.com/dotnet/2016/04/18/whats-new-for-the-net-native-compiler-and-runtime-in-visual-studio-2015-update-2/) : Stacey Haffner 와 Matthew Whilden 가 Visual Studio 2015 Update 2 에 포함된 .NET Native Compiler 와 Runtime 의 새로운 기능을 소개합니다. 
* [Introducing the Microsoft .NET Framework Repair Tool Version 1.3](https://blogs.msdn.microsoft.com/dotnet/2016/04/19/introducing-the-microsoft-net-framework-repair-tool-version-1-3/) : Rakesh Ranjan Singh 가 .NET Framework 의 이슈를 점검하고 업데이트 하는 도구인 Microsoft .NET Framework Repair Tool 을 소개합니다.   
* [How to host your own NuGet server and package feed](http://www.hanselman.com/blog/HowToHostYourOwnNuGetServerAndPackageFeed.aspx) : Scott Hanselman 이 NuGet Server 를 설치하고 운영하는 방법을 소개합니다. 
* [Moq on .NET Core](http://dotnetliberty.com/index.php/2016/02/22/moq-on-net-core/) : Armen Shimoon 이 .NET Core 에서 Moq 의 활용법을 공유했습니다. 
* [Visual Studio Code 1.0 has been released!](http://code.visualstudio.com/blogs/2016/04/14/vscode-1.0) : Visual Studio Code 의 첫번째 정식버전이 출시되었습니다. 

### ASP.NET 소식
* [An update on ASP.NET Core 1.0 RC2](http://www.hanselman.com/blog/AnUpdateOnASPNETCore10RC2.aspx) : Scott Hanselman 이 ASP.NET Core 1.0 RC2 의 업데이트 정보를 소개합니다. 
* [Notes from the ASP.NET Community Standup – April 12, 2016](https://blogs.msdn.microsoft.com/webdev/2016/04/14/notes-from-the-asp-net-community-standup-april-12-2016/) : Jeffrey T. Fritz 가 ASP.NET 커뮤니티 행사에서 논의되었던 내용을 정리했습니다. 
* Shawn Wildermuth 이 [자신의 블로그 시스템을 .NET Core 기반으로 이전하는 과정](http://wildermuth.com/2016/04/14/Welcome-to-the-New-Wildermuth-com)을 [오픈소스 프로젝트](https://github.com/shawnwildermuth/wilderblog)로써 진행하며 [RSS](https://github.com/shawnwildermuth/RssSyndication) 와 [XML RPC](https://github.com/shawnwildermuth/MetaWeblog) 라이브러리도 개발했으며 오픈소스로 공개했습니다. 
* [Enhancing Claims with Owin Middleware & Claims Transformation](http://www.cognim.co.uk/transforming-claims-claimsprincipal/) : Darren Hall 이 Owin 미들웨어에서 인증 토근의 전환 및  인증하는 방법에 대해서 공유했습니다.
* [How to perform partial resource updates with JSON Patch and ASP.NET Core](http://benfoster.io/blog/aspnet-core-json-patch-partial-api-updates) : Ben Foster 가 JSON 문서의 변경사항을 기술하는 형식인 JSON Patch 를 이용하여 리소스를 부분적으로 업데이트 하는 방법을 소개합니다.
* [ASP.NET Core custom service based on request](http://dotnetliberty.com/index.php/2016/04/11/asp-net-core-custom-service-based-on-request/) : Armen Shimoon 이 사용자 요청에 따라 ASP.NET Core 기반의 서비스를 만들고 제공하는 것을 예제와 함께 설명합니다. 
* [Entity Framework Core: The Future of EF for ASP.NET Core (video)](https://channel9.msdn.com/Blogs/DevRadio/DR1644) : Chris Caldwell 이 [Edge of the Web](https://channel9.msdn.com/Blogs/DevRadio?Tag=edge-of-the-web) 시리즈의 주제로 ASP.NET Core 의 EF(Entity Framework) 미래라는 제목의 동영상을 공유했습니다.
* [ASP.NET Core on Nano Server Preview](http://blog.guardrex.com/2016/04/aspnet-core-on-nano-server-preview.html) : Luke Latham 이 프리뷰 버전의 Azure Nano Server 에 ASP.NET Core 웹 애플리케이션을 배포하는 방법을 자세하게 소개합니다. 
* [Hooking up ASP.NET Core 1.0 RC1 web api with Auth0 bearer tokens](http://blog.novanet.no/hooking-up-asp-net-core-1-rc1-web-api-with-auth0-bearer-tokens/) : Hans Arne Vartdal 가 ASP.NET Core 1.0 RC1 환경의 web api 에서 Auth0 인증 토큰을 활용하는 방법을 공유하였습니다.
* [Using Cache in ASP.NET Core 1.0 RC1](http://wildermuth.com/2016/04/14/Using-Cache-in-ASP-NET-Core-1-0-RC1) : Shawn Wildermuth 이 ASP.NET Core 1.0 RC1 에서 Caching 을 사용하는 방법을 설명합니다. 
* [Exploring Prefix: A Free ASP.NET Profiling Tool](http://www.mikesdotnetting.com/article/296/exploring-prefix-a-free-asp-net-profiling-tool) : Mike Brind 가 ASP.NET 애플리케이션의 무료 Profiler 도구인 Prefix 를 소개합니다.

### F# 소식
* [F# eXchange 2016](https://skillsmatter.com/conferences/7145-f-exchange-2016#skillscasts) : 2016년도 F# eXchange 콘퍼런스에서 발표된 12개 이상의 세션이 녹화되여 온라인 상에 공유되었습니다. 
* [Happy F# Day! Growing and Getting Better Each Year](http://fsharpforfunandprofit.com/posts/happy-fsharp-day-2/) : Scott Wlaschin 가 F# 탄생을 기념하며 지난 1년간의 F# 의 발전모습에 대하여 포스팅했습니다.
* [.NET Core 에서 Atom 및 Visual Studio Code 에서 사용가능한 Ionide extension 을 지원하는 소식](https://twitter.com/k_cieslak/status/719923250583769088)이 트위터에 공유되었습니다.
* [Async as Surrogate IO](http://blog.ploeh.dk/2016/04/11/async-as-surrogate-io/) : Mark Seemann 이 IO 작업을 대신하기 위해 Async 를 사용하는 방법을 소개했습니다. 
* [Optionals](http://sidburn.github.io/blog/2016/04/11/optionals) : David Raab 이 null 대신 Optionals 을 사용하는 것의 이점에 대해 설명합니다. 
* [Functional Error Handling in F# by Example](http://blog.leifbattermann.de/2016/04/09/functional-error-handling-in-fsharp-by-example/) : Leif Battermann 가 F# 에서의 함수지향적 예외처리방법을 소개합니다. 

송기수 이사님 소개멘트 