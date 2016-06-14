여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

###금주의 커뮤니티 소식
Taeyo.NET 에서 http://docs.asp.net 의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.

* [ASP.NET Core MVC 모델 추가하기](http://taeyo.net/Columns/View.aspx?SEQ=533&PSEQ=40) : ASP.NET Core 에서 MVC 모델(Model)을 추가하는 방법을 예제와 함께 상세하게 소개합니다.

### On.NET 소식
[지난 On.NET 인터뷰](https://youtu.be/5MnfrL7gfEs)에서는 마이크로스프트의 주요 언어의 프로그램 메니저이면서 동시성 부분의 전문가(concurrency expert) 인 [Lucian Wischik](https://twitter.com/lwischik) 과 함께 이야기 나누어 보았습니다

//인터뷰 동영상 

[이번 주 On.NET 인터뷰](https://www.youtube.com/watch?v=QJ93BMCo_XI)에는 Daniel Egloff 와 함께 .NET 에서 GPU 기능을 활용하는 방법에 대해서 알아보겠습니다.

### 금주의 패키지- Markdig
.NET용 마크다운(markdown) 라이브러리가 많지 않은 가운데, [Markdig](https://github.com/lunet-io/markdig)는 확장성이 있고 [CommonMark](http://commonmark.org/) 표준을 따르는 고성능(빠른속도, 메모리 최적화)의 마크다운 라이브러리입니다. 

//코드

### 금주의 Xamarin 애플리케이션 - Expensya 
Expensya 는 유럽, 아프리카, 호주에서 주로 사용되는 유명한 경비 처리용 애플리케이션입니다 . Expensya 는 C# 으로 개발되었으며 Azure 클라우드 서비스를 이용합니다. Xamarin 을 사용한 덕분에 많은 부분의 코드를 공유할 수 있었고, 팀원들에게 이미 익숙한 기술을 사용할 수 있었으며, 크로스 플랫폼을 지원하고, 업무로직의 단위테스트가 가능하며, 네이티브 수준의 성능을 구현할 수 있었습니다. 그 결과 3 가지 주요 플랫폼인 윈도우, Android, iOS 에서 동작하는 애플리케이션을 불과 수개월만에 개발 할 수 있었습니다. 

//이미지  

### 금주의 게임 - McDroid
[McDroid](http://madewith.unity.com/games/mcdroid) 라는 게임은 성을 지키는 게임(tower defense game)의 일종입니다. McDroid 는 귀여운 로봇으로 행성 충돌로 불시착한 우주선을 수리하고, 수리가 끝날때까지 외계인의 공격을 방어하는 책임을 지고 있습니다.
플레이어는 기본 방어 라인을 구축하여 자원을 안정적으로 수확하고, 주기적인 외계인의 공격을 막아내야 합니다. 다음 단계로 가기 위해 무엇보다 중요한 것은 효율적인 시간관리 입니다. McDroid 는 스토리와 여러 생존 단계와 다중 플레이어 게임모드를 제공합니다.

//그림

McDroid 는 [Grip Digital](http://madewith.unity.com/profiles/grip-digital) 에서 [Unity](http://unity3d.com/)와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 개발되었으며 현재 PlayStation 4, Xbox One 그리고 Windows 에서 즐기실 수 있습니다.
좀더 자세한 정보는 [링크](http://madewith.unity.com/games/mcdroid)에서 확인하실 수 있습니다.

### .NET 소식
* [Inline IL ASM in C# with Roslyn](http://xoofx.com/blog/2016/05/25/inline-il-asm-in-csharp-with-roslyn/) : Alexandre Mutel이 Roslyn을 이용한 C# Inline IL ASM 에 대해 설명 하였습니다.
* [Strings and the CLR – a Special Relationship](http://mattwarren.org/2016/05/31/Strings-and-the-CLR-a-Special-Relationship/) : Matt Warren이 C#의 기본 타입인 문자열이 CLR 에서 어떻게 다루어지고 있는지 설명합니다. 
* [Use project.lock.json to troubleshoot dotnet restore problems](https://andrewlock.net/use-project-lock-json-to-troubleshoot-dotnet-restore-problems/) : Andrew Lock 이 project.json 프로젝트에서 dotnet restore 명령을 이용하여 NuGet 패키지를 다시 로드할때 발생하는 문제를 해결하는 방법을 소개합니다. 
* [Windows 10 Anniversary Update Preview–Composition and the CompositionBackdropBrush]() : Mike Taulty 가 Windows 10 Anniversary Update 에 포함될 예정인 관련 새로운 API 인 Composition API 에 대한 정보를 공유해주었습니다.
* [ASP.NET Core – problems and fixes](https://devblog.dymel.pl/2016/06/06/asp-net-core-problems-fixes/) : Michal Dymel 이 기존에 생성한 ASP.NET 프로젝트를 ASP.NET Core RC2 로 전환하면서 경험한 문제와 해결방법을 공유하였습니다.
* [MSBuild Structured Log: record and visualize your builds](http://www.hanselman.com/blog/MSBuildStructuredLogRecordAndVisualizeYourBuilds.aspx) : Scott Hanselman 이 MSBuild Structured Log 툴을 이용하여 MSBuild 작업의 진행과정을 쉽게 확인 할 수 있는 방법을 소개하였습니다.
* [Storing C# app settings with JSON](http://piotrgankiewicz.com/2016/06/06/storing-c-app-settings-with-json/) : Piotr Gankiewicz 가 기존의 XML 포멧이 아닌 JSON 포멧의 configuration 파일을 이용하는 방법을 소개하였습니다.
* [Async Programming : Unit Testing Asynchronous Code](https://msdn.microsoft.com/en-us/magazine/dn818493.aspx) : Stephen Cleary 가 테스트하기 까다로운 비동기 코드의 단위 테스트 방법을 소개하였습니다.
* [Imageflow: Respect the pixels, accelerate the web (Kickstarter)](https://www.kickstarter.com/projects/njones/imageflow-respect-the-pixels-a-secure-alt-to-image) : Nathanael Jones 가 고성능 이미지 프로세싱 프로젝트인 Imageflow 를 소개합니다.
* [The .NET CLI Decoded](http://developer.telerik.com/featured/net-cli-decoded/) : Sam Basu 가 Windows, OSX 그리고 Linux 에서 공통적으로 사용할 수 있는 새로운 커맨드라인 명령에 대해서 소개해주었습니다.

### ASP.NET 소식
* [Publishing and Running ASP.NET Core Applications with IIS](http://weblog.west-wind.com/posts/2016/Jun/06/Publishing-and-Running-ASPNET-Core-Applications-with-IIS) : Rick Strahl 가 ASP.NET Core 애플리케이션을 IIS 웹 서버에 배포하고 수행하는 방법을 설명하였습니다.
* [Introduction to integration testing with xUnit and TestServer in ASP.NET Core](https://andrewlock.net/introduction-to-integration-testing-with-xunit-and-testserver-in-asp-net-core/) : Andrew Lock 이 xUnit 과 TestServer 클래스를 이용한 통합 테스트 방법을 공유하였습니다.
* [Authorizing your .NET Core MVC6 API requests with OpenIddict and Identity](http://kerryritter.com/authorizing-your-net-core-mvc6-api-requests-with-openiddict-and-identity/) : Kerry Ritter 가 .NET Core MVC6 에서 OpenIddict(OAuth, OpenID 관련 기능을 제공하는 오픈소스 라이브러리)를 이용하는 방법을 설명하였습니다.
* [Cloudscribe.Web.Localization – more flexible localization for ASP.NET Core](https://github.com/joeaudette/cloudscribe.Web.Localization) : Joe Audette 이 ASP.NET Core 의 지역화(Localization)기능을 제공하는 오픈소스 프로젝트인 cloudscribe.Web.Localization 를 소개합니다. 
* [ASP.NET Core RC2 (migration guide)](https://ievangelist.github.io/blog/migrating-to-rc2/) : David Pine 이  ASP.NET Core RC1 애플리케이션을 ASP.NET Core RC2 로 변경하는 방법을 설명하였습니다.

### F# 소식
* [Using XAML in F# Xamarin Forms – A Screencast](http://www.wintellect.com/devcenter/jwood/using-xaml-f-xamarin-forms-screencast) : Jonathan Wood 가 Xamarin Forms 에서 F# 과 XAML 을 사용하는 방법을 공유해주었습니다.
* [Custom error handling and logging in Suave](https://dusted.codes/custom-error-handling-and-logging-in-suave) : Dustin Moris Gorski 이 F# 의 웹 프레임워크인 Suave 에서 사용자정의 예외처리 방법과 이를 로깅하는 방법을 소개해주었습니다.
* [Upcoming F# events – learn Suave, FsLab & more!](http://tomasp.net/blog/2016/fsharp-events/) : Tomas Petricek 이 앞으로 개최될 F# 행사 소식을 공유하였습니다
* [Fable: Super Fable Mario (Mario clone using HTML5 canvas)](http://fsprojects.github.io/Fable/samples/mario/index.html) : HTML5 canvas 를 이용하여 이미지를 랜더링하고, F#을 이용하여 마리오 캐릭터의 기본 움직임을 구현한 소스코드를 공유해주었습니다.

### Xamarin 소식
* [Join the Xamarin Team for dotNetConf](https://blog.xamarin.com/join-the-xamarin-team-for-dotnetconf/) : Joseph Hill 이 지난주에 개최된 온라인 콘퍼런스인 dotNetConf 에 Xamarin 팀에서 근무하고 있는 분들의 참여소식을 전해주었습니다.
* [Xamarin DevOps with VSTS – Setup a Cross Platform Build Agent on OSX](http://www.blogaboutxamarin.com/xamarin-devops-with-vsts-setup-a-cross-platform-build-agent-on-osx/), and [Xamarin DevOps with VSTS – Setup a Cross Platform Build Agent on Windows](http://www.blogaboutxamarin.com/xamarin-devops-with-vsts-setup-a-cross-platform-build-agent-on-windows/) : Richard Woollcott 이 Xamarin DevOps 를 위해 VSTS 용 Build Agent 를 Windows 와 OS X 에 설치하는 방법을 소개해주었습니다. 
* [ASP.NET Core 1.0 RC2 support in Xamarin Studio](http://lastexitcode.com/blog/2016/06/05/AspNetCoreRC2SupportInXamarinStudio/) : Matt Ward 이 Xamarin Studio 에서 ASP.NET Core 1.0 RC2 애플리케이션 개발 및 디버깅 방법을 공유해주었습니다.
* [Watch Kent Boogaart code WorkoutWotch from start to end](https://www.youtube.com/playlist?list=PLwqdWBgwaokVPpdPOOJ-GTGiHcqoG5alU) : Kent Boogaart 이 C# 을 이용해 개발한 iOS 애플리케이션인 Workout Wotch 의 개발과정을 소개합니다. 
* [Xamarin DevOps with VSTS – Getting Started](http://www.thexamarinjournal.com/xamarin-dev-ops-with-vsts-getting-started/) : Richard Woollcott 이 VSTS 를 이용한 Xamarin DevOps 방법을 초보자들을 위해 스크린샷과 함께 자세하게 소개합니다. 
* [Xamarin Forms UI Snippets](http://snppts.io/latest) : Xamarin Forms 의 UI 코드블럭을 공유하는 사이트를 소개합니다. 

### Games 
* [Serialization, Monobehavior Constructors and Unity 5.4](http://blogs.unity3d.com/2016/06/06/serialization-monobehaviour-constructors-and-unity-5-4/) : Lukasz Paczkowski 가 생성자 및 필드 초기화 과정에서 Unity API 호출시 발생할 수 있는 부작용을 방지하기 위해서 Unity5.4 에 추가된 에러를 소개해 주었습니다.
* [Breakout! How to Stop An Infinite Loop in a Unity C# Script](http://blogs.unity3d.com/2016/05/24/breakout-how-to-stop-an-infinite-loop-in-a-unity-c-script/) : Peter Andreasen 이 Unity 애플리케이션 디버깅시 개발자의 C# Script 에서 발생된 무한루프를 중지하는 방법을 공유해주었습니다.
* [Build a Unity Game Part 4 – Video](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Build-a-Unity-Game-Part-4) : Stacey Haffner 이 Unity 게임개발 동영상 가이드 Part 4 를 소개합니다.

//이사님 소개