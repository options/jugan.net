### .NET Architecture - 마이크로서비스 & 컨테이너

최근에 .NET 웹사이트에 [아키텍처 기술 가이드](https://www.microsoft.com/net/learn/architecture)가 추가되었습니다. 이 페이지들은 .NET의 각 타입별 애플리케이션 구현과 관련된 아키텍처 정보를 제공하고 있으며, 앞으로도 관련 내용을 계속 추가할 예정입니다.

여러 기술 항목 중 마이크로서비스 & 컨테이너(Microservices & Containers) 부분은 .NET의 마이크로서비스의 빌드, 배포부분에 관련한 유용한 정보가 포함되어있으며 이와 관련해서 .NET Product Team 매니저인 [Cesar De la Torre](https://twitter.com/cesardelatorre)는 두개의 eBooks을 집필하여 공유했습니다. 그 중 하나는 마이크로서비스의 디자인과 구현에 관한 내용이고 다른 하나는 운영환경의 배포와 관리에 대한 내용입니다. 또한 eShopOnContainers 샘플 애플리케이션을 학습하면서 컨테이너의 개념을 좀 더 쉽게 이해하실 수 있습니다.

* [Architecture Guidance page](https://www.microsoft.com/net/learn/architecture)

### On .NET 소식 : Omer Raviv – OzCode

Microsoft 빌드 컨퍼런스 기간 중 [여러 참가자들과 인터뷰](https://channel9.msdn.com/Shows/On-NET/Omer-Raviv-OzCode)를 진행했었습니다. 이번주에는 Omer Raviv와의 인터뷰를 소개해드리려고 하며, Visual Studio 디버깅 확장툴인 [OzCode](https://oz-code.com/) 데모를 보실 수 있습니다. OzCode를 이용하면 Linq 표현식을 쉽게 디버그 하실 수 있으며, 편집기에서 바로 변수값도 확인하실 수 있습니다. 이번 인터뷰는 특히 디버깅에 관심 있으신 분들에게 많은 도움이 될 것입니다.

//그림

### 금주의 패키지: Sprache

개발자에게 문자열을 파싱하는 작업은 가장 흔하면서도 번거로운 기본 작업 중에 하나일 것 입니다. 문자열 파싱작업은 소규모의 업무용 DSL(Domain Specific Language)를 정의하고 분석하거나, 특이한 데이터 형식을 사용하거나, 또는 사용자가 정한 복잡합 형식을 분석하는 경우 텍스트를 데이터 구조로 변환하는 방법을 기술해야 합니다. 이러한 상황에서 작업 문자열은 어떠한 방법으로든 문자열에서 데이터로 변환 되어야만 프로그램에서 자료로서 활용하는 것이 가능합니다. 

[ANTLR](http://www.antlr.org/)라는 툴은 이러한 기능을 지원해주며, 이미 많은 언어의 문법이 정의되어 있어서 개발자가 복잡한 파싱도 쉽게 할 수 있도록 도와줍니다. 하지만 간단한 문자열 파싱에는 오히려 번거로울 수 있습니다. 대부분의 개발자들은 가볍게 사용할 수 있는 문자열 분석 엔진을 필요로 하는데, 이때 사용할 수 있는 툴이 [Sprache](https://github.com/sprache/Sprache)입니다.

Sprache는 단순 파싱 작업에 적합한 문자열 파싱 엔진으로, 이제 더이상 정규식을 사용하지 않고도 파서를 이용하여 문자열 분석이 가능합니다.

'''
Parser<string> identifier =
    from leading in Parse.WhiteSpace.Many()
    from first in Parse.Letter.Once()
    from rest in Parse.LetterOrDigit.Many()
    from trailing in Parse.WhiteSpace.Many()
    select new string(first.Concat(rest).ToArray());
var id = identifier.Parse(" abc123  ");
Assert.AreEqual("abc123", id);
'''

* [Sprache on GitHub](https://github.com/sprache/Sprache)
* [Sprache on NuGet](https://www.nuget.org/packages/Sprache)
* [Building a DSL using Sprache by Nicholas Blumhardt](https://nblumhardt.com/2010/01/building-an-external-dsl-in-c/)

### .NET 소식

* [Microsoft .NET Framework 4.7 is available on Windows Update, WSUS, and MU(Microsoft Update) Catalog](https://blogs.msdn.microsoft.com/dotnet/2017/06/13/microsoft-net-framework-4-7-is-available-on-windows-update-wsus-and-mu-catalog/) : Jamshed Damkewalark가 Windows Update, WSUS(Windows Server Update Services), MU(Microsoft Update) Catalog에서 .NET Framework 4.7를 사용할 수 있다는 소식을 공유했습니다.
* [How the .NET Runtime loads a Type](http://mattwarren.org/2017/06/15/How-the-.NET-Rutime-loads-a-Type/) : Matt Warren이 .NET 런타임이 Type을 로드하는 과정을 설명했습니다.
* [Rider EAP 23: .NET Core debugger is back, Code Cleanup, and more](https://blog.jetbrains.com/dotnet/2017/06/16/rider-eap-23-net-core-debugger-back-code-cleanup/) : Jura Gorohovsky가 .NET Core 디버깅, Code Cleanup 등의 기능을 포함한 Rider의 pre-release 버전 EAP(Early Access Program)23을 소개했습니다.
* [Automate Testing and Running Apps with dotnet watch](http://ardalis.com/automate-testing-and-running-apps-with-dotnet-watch) : Steve Smith가 dotnet watch를 이용한 App 자동실행 및 테스트 방법을 설명했습니다.
* [One year of running the Windsor-Essex .NET Developers](https://codeopinion.com/one-year-of-running-a-windsor-essex-net-developers/) : Derek Comartin이 지역 커뮤니티인 Windsor-Essex를 1년 진행한 과정과 계획을 공유했습니다.
* [From Java to .NET Core, Part 2: Types](https://developers.redhat.com/blog/2017/06/15/from-java-to-net-core-part-2-types/) : Yev Bronshteyn이 "Java코드 .Net Core 전환 가이드 파트2: 타입" 블로그를 게시했습니다.
* [AutoMapper 6.1.0 released](https://jimmybogard.com/automapper-6-1-0-released/) : Jimmy Bogard가 AutoMapper 6.1.0 릴리즈 소식을 공유했습니다.
* [Consuming REST Services from Your Mobile Application Using Swagger and AutoRest](https://visualstudiomagazine.com/articles/2017/04/01/consuming-rest-services.aspx) : Nick Randolph가 Swagger와 AutoRest를 이용한 모바일 애플리케이션의 REST Services 호출 방법을 설명했습니다. 
* [.NET Core .csproj – Automatically Packaging README.txt](https://www.bengribaudo.com/blog/2017/06/19/3635/net-core-csproj-automatically-packaging-readme-txt) : Ben Gribaudo가 .NET Core의 .csproj 프로젝트 항목에 "README.txt"를 포함시키는 방법을 공유했습니다.
* [To Heap or not to Heap; That’s the Large Object Question?](https://www.codeproject.com/Articles/1191534/To-Heap-or-not-to-Heap-That-s-the-Large-Object-Que) : Doug Duerner가 .NET 시스템의 Large Object 메모리 관리 방법과 개념을 설명했습니다.
* [Create a Free Private NuGet Server with Continuous Deployment using VSTS](https://www.devtrends.co.uk/blog/create-a-free-private-nuget-server-with-continuous-deployment-using-vsts) : Paul Hiles가 VSTS를 이용하여 CD(Continuous Deployment) 환경구축을 위한 프로젝트 전용 NuGet Server 구축 방법을 설명했습니다.
* [How to reference a .NET Core library in WinForms – Or, .NET Standard Explained](https://www.hanselman.com/blog/HowToReferenceANETCoreLibraryInWinFormsOrNETStandardExplained.aspx) : Scott Hanselman이 .NET Core library를 기존 WinForms 프로젝트 혹은 .NET Standard 프로젝트에서 참조하여 활용하는 방법을 설명했습니다.

### ASP.NET 소식

* [Automatically validating anti-forgery tokens in ASP.NET Core with the AutoValidateAntiforgeryTokenAttribute](https://andrewlock.net/automatically-validating-anti-forgery-tokens-in-asp-net-core-with-the-autovalidateantiforgerytokenattribute/) : Andrew Lock이 ASP.NET Core의 AutoValidateAntiforgeryTokenAttribute을 이용한 위조방지 토큰 유효성의 자동 검증방법을 설명했습니다.
* [Minimal ASP.NET Core Web API project](https://www.meziantou.net/2017/06/19/minimal-asp-net-core-web-api-project) : Gérald Barré가 간단한 ASP.NET Core Web API 프로젝트 구현과정을 공유했습니다.
* Steve Gordon이 .NET 개발자를 위한 도커 시스템 학습 시리즈 [파트 3: ASP.NET Core를 도커환경에 구축해야 하는 이유](https://www.stevejgordon.co.uk/docker-for-dotnet-developers-part-3)와 [파트4 : docker-compose 활용과  ASP.NET Core 마이크로서비스](https://www.stevejgordon.co.uk/docker-for-dotnet-developers-part-4)편을 공유했습니다.
* [Resolving ASP.NET Core Startup class from the DI container](https://www.strathweb.com/2017/06/resolving-asp-net-core-startup-class-from-the-di-container/) : Filip W가 DI(Dependency Injection) 컨테이너에서 ASP.NET Core의 Startup 클레스를 찾는 방법을 설명했습니다.
* [Integrating Microsoft Identity Authorization into a Menu System](https://www.danylkoweb.com/Blog/integrating-microsoft-identity-authorization-into-a-menu-system-IV) : Jonathan Danylko가 애플리케이션 메뉴 시스템의 권한기능 구현시 Microsoft의 인증 정보를 포함하는 방법을 설명했습니다.
* [Middleware in ASP.NET Core – Handling requests](https://codingblast.com/asp-net-core-middleware/) : Ibrahim Šuta가 "ASP.NET Core 미들웨어 : 요청 처리하기"편을 공유했습니다
* [From 0 to 100 with this ASP.NET Core/AngularX Project Template](https://channel9.msdn.com/coding4fun/blog/From-0-to-100-with-this-ASPNET-CoreAngularX-Project-Template?WT.mc_id=DX_MVP4025064) : Greg Duncan이 ASP.NET Core/AngularX 프로젝트 템플릿을 소개했습니다.
* [Exploring GraphQL and creating a GraphQL endpoint in ASP.NET Core](http://asp.net-hacker.rocks/2017/05/29/graphql-and-aspnetcore.html) : Jürgen Gutsch가 ASP.NET Core환경에서 GraphQL 활용법을 소개했습니다.
* [Using Consul for Health Checks with ASP.NET Core](http://cecilphillip.com/using-consul-for-health-checks-with-asp-net-core/) : Cecil Phillip이 Consul을 활용한 ASP.NET Core 애플리케이션의 장애유무 확인 방법을 설명했습니다.
* [ASP.NET Core deployment using Docker, Nginx and Ubuntu Server](http://piotrgankiewicz.com/2017/06/12/asp-net-core-deployment-using-docker-nginx-and-ubuntu-server/) : Piotr Gankiewicz가 도커를 활용하여 Nginx와 우분투에 ASP.NET Core를 배포하는 방법을 설명했습니다.
* [Options for Configuring ASP.NET Core Application Settings](http://rion.io/2017/06/10/options-for-configuring-asp-net-core-application-settings/): Rion Williams가 ASP.NET Core Application에서 config를 위한 오픈소스 라이브러리인 "Options"를 소개했습니다.
* [Michael Ballhaus (MCPD + SCJP)  Show off your API with a little Swagger](http://geekswithblogs.net/ballhaus/archive/2017/06/14/swaggerapi.aspx) : Michael Ballhaus이 Swagger를 활용한 Web API 노출방법을 설명했습니다.
* [10 Things To Know About In-Memory Caching In ASP.NET Core](http://www.binaryintellect.net/articles/a7d9edfd-1f86-45f8-a668-64cc86d8e248.aspx) : Bipin Joshi가 ASP.NET Core의 In-Memory Caching에 대해 알아야할 10가지 정보를 공유했습니다.

### C# 소식

* [C# 7.x and 8.0: Uncertainty and Awesomeness](https://www.erikheemskerk.nl/c-sharp-7-2-and-8-0-uncertainty-awesomeness/) : Erik Heemskerk가 C# 7.x, 8.0 버전의 새로운 기능을 소개했습니다.
* [My Favorite C# 7 Feature: More expression-bodied members](http://motzcod.es/post/161630386432/my-favorite-c-7-feature-more-expression-bodied) : James Montemagno가 C# 7.0의 향상된 기능 "표현식-함수 멤버"을 소개했습니다.
* [Practical C# – Extern Alias in C#](http://www.andreaangella.com/2017/06/practical-csharp-extern-alias/) : Andrea Angella가 학습 비디오 "C# 실무 : Extern Alias"를 공유했습니다.

### F# 소식

* [Building Roguelike in F#](https://www.reaktor.com/blog/building-roguelike-in-f/) : Simo Raman이 F#을 이용한 로그라이크 타입 게임 구현 방법을 설명했습니다.
* [Options in F#](https://dotnetcodr.com/2017/06/17/options-in-f/) : Andras Nemes가 F#의 Options object를 설명했습니다.
* [Pulling state from F# Mailboxes](http://www.codingwithsam.com/pulling-state-from-f-mailboxes/) : Sam Williams가 F#의 MailboxProcessor를 소개했습니다.
* [The Foundations of Functional Concurrency is 37% off!](http://freecontent.manning.com/the-foundations-of-functional-concurrency/) : Manning, Riccardo Terrell이 기술 서적 "The Foundations of Functional Concurrency"의 소개와 Functional Concurrency의 중요성을 설명했습니다.
* [When to Unit Test in F#](https://cockneycoder.wordpress.com/2017/06/12/when-to-unit-test-in-f/) : Isaac Abraham가 F#에서 Unit Test를 해야하는 경우에 대해 소개했습니다.

### VB 소식

* [Visual Basic and Cross-Platform: Mobile Apps with VB, Xamarin, and .NET Standard!](https://blogs.msdn.microsoft.com/vbteam/2017/06/13/visual-basic-and-cross-platform-mobile-apps-with-vb-xamarin-and-net-standard/) : Klaus Löffelmann이 VB, Xamarin, .NET Standard를 이용한 모바일 애플리케이션 개발방법을 소개했습니다.
* [Calling Web Services with HttpWebRequest, WebClient and HttpClient](https://visualstudiomagazine.com/articles/2017/06/01/calling-web-services.aspx) : Peter Vogel이 HttpWebRequest, WebClient, HttpClient를 이용한 웹서비스 호출 방법에 관해 설명했습니다.
* [Viva, Visual Basic! Or, Does VB Have a Future?](https://visualstudiomagazine.com/articles/2017/06/13/visual-basic-future.aspx) : Michael Domingo가 향후 VB의 로드맵을 공유했습니다.

### Xamarin 소식

* [Stable Release: 15.2.3 Xamarin.VS Servicing Release](https://releases.xamarin.com/stable-release-15-2-3-xamarin-vs-servicing-release/) : Bri Brothers가 15.2.3 Xamarin.VS 서비스 릴리즈 정보를 공유했습니다.
* [Xamarin Forms, the MVVMLight Toolkit and I: navigation and modal pages](https://msicc.net/xamarin-forms-the-mvvmlight-toolkit-and-i-navigation-and-modal-pages/) : Marco Siccardi가 Xamarin Forms의 navigation과 modal pages를 설명했습니다.
* [Visual States in Xamarin.Forms using BuildIt.Forms](https://nicksnettravels.builttoroam.com/post/2017/06/10/Visual-States-in-XamarinForms-using-BuildItForms.aspx) : Nick Randolph가 Xamarin.Forms에서 BuildIt.Forms을 이용한 Visual States 활용방법을 설명했습니다.
* [Xamarin.Forms Visual States with View Models](https://nicksnettravels.builttoroam.com/post/2017/06/10/XamarinForms-Visual-States-with-View-Models.aspx) : Nick Randolph가 View Models에서 Visual States 활용방법을 설명했습니다.
* [Chat Bot with Xamarin Forms](https://xamarinhelp.com/chat-bot-xamarin-forms/) : Adam Pedley가 Microsoft Bot Framework를 이용한 Xamarin Forms로 Chat Bot 구현 방법을 설명했습니다.
* [Is Xamarin Forms Making Traditional Xamarin Obsolete?](https://xamarinhelp.com/xamarin-forms-making-traditional-xamarin-obsolete/) : Adam Pedley가 Xamarin Forms와 Xamarin native의 로드맵과 상호관계를 설명했스빈다.
* [Xamarin Forms ChatBot Application using the Microsoft Bot Framework](http://xamarininterviewquestion.blogspot.com/2017/06/xamarin-forms-chatbot-application-using.html) : Suthahar J가 Microsoft Bot Framework을 활용한 ChatBot 애플리케이션 구현 방법을 공유했습니다.
* [Boosting Your Productivity with MFractor](https://blog.verslu.is/tools/boosting-productivity-mfractor/) : Gerald Versluis가 Visual Studio Mac용 확장툴인 MFractor를 소개했습니다.
* [5 Ways to Boost Xamarin.Forms App Startup Time](https://blog.xamarin.com/5-ways-boost-xamarin-forms-app-startup-time/) : David Ortinau가 Xamarin.Forms 애플리케이션의 초기 실행시간을 단축 시킬수있는 5가지 방법을 소개했습니다.
* [Adding Face Tracking and Live Recognition to your Android App](https://blog.xamarin.com/adding-face-tracking-live-recognition-android-app/) : Nish Anil이 안드로이드 애플리케이션에 안면인식기능을 추가하는 방법을 설명했습니다.
* [Demystifying Build Configurations](https://blog.xamarin.com/demystifying-build-configurations/) : Jon Goldberger가 빌드 설정을 알기쉽게 설명했습니다.
* [Episode 25: Unity Game Development with Visual Studio for Mac with Jb Evain](https://channel9.msdn.com/Shows/XamarinShow/Episode-25-Unity-Game-Development-with-Visual-Studio-for-Mac-with-Jb-Evain) : The Xamarin Show에서 에피소드 25편 "Visual Studio for Mac을 이용한 Unity 게임 개발"편을 공유했습니다.
* [Growing Your First Xamarin.Forms Mac App](https://codemilltech.com/growing-your-first-xamarin-forms-mac-app/) : Matthew Soucoup가 Xamarin.Forms을 활용한 Mac용 애플리케이션 구현방법을 설명했습니다.
* [Things I Think Are Cool: Custom XAML Markup Extensions](https://codemilltech.com/things-i-think-are-cool-xaml-markup-extensions/) : Matthew Soucoup가 "XAML 마크업 사용자 확장" 기능을 설명했습니다
* [Embedding Xamarin.Forms into a Xamarin Native App #TheFuture](http://motzcod.es/post/161785997897/embedding-xamarinforms-into-a-xamarin-native-app) : James Montemagno가 Xamarin Native에서 Xamarin.Form을 포함(Embedding)하는 방법을 설명했습니다.

### Azure 소식

* [Azure via C# – Working with Azure Queues](http://www.andreaangella.com/2017/06/azure-via-csharp-azure-queues/) : Andrea Angella가 Azure 학습 비디오 "Azure, C# : Azure Queues"를 공유했습니다.
* [Writing an Azure Function in C# to create an ICS Calendar File](http://michaelcrump.net/building-an-ics-for-azure-functions-webinar/) : Michael Crump가 Azure Function에서 ICS 일정파일의 생성 방법을 설명했습니다.
* [Creating ASP.NET Web App In Azure](http://michaelcrump.net/building-an-ics-for-azure-functions-webinar/) : Viral Jain이 Azure에서 ASP.NET 웹 애플리케이션 구현방법을 공유했습니다.
* [AppVeyor – Continuous Delivery to Azure for your .NET Core Applications](https://dotnetcore.gaprogman.com/2017/06/15/appveyor-continuous-delivery-for-your-net-core-applications/) : Jamie Taylor가 AppVeyor를 활용한 Azure .NET Core 애플리케이션의 CD(Continuous Delivery) 환경 구축과정을 설명했습니다.

### UWP 소식

* [Adding Fluent Design Acrylic Material to UWP via Xamarin.Forms](https://nicksnettravels.builttoroam.com/post/2017/06/11/Adding-Fluent-Design-Acrylic-Material-to-UWP-via-XamarinForms.aspx) : Nick Randolph가 Xamarin.Forms을 이용해서 Fluent Design을 UWP에 적용하는 방법을 설명했습니다.
* [iBeacons and UWP](https://channel9.msdn.com/coding4fun/blog/iBeacons-and-UWP) : Channel 9에서 iBeacon을 UWP에서 활용하는 방법을 소개했습니다.
* [Setting up a HoloLens project with the HoloToolkit](https://channel9.msdn.com/coding4fun/blog/iBeacons-and-UWP) : Joost van Schaik가 홀로렌즈 개발툴킷인 HoloToolkit의 HoloLens 프로젝트를 소개했습니다.

### Data 소식

* [Introducing DataReaderAdapter: Adds AsDataReader()/AsDataReaderOfObjects() to IEnumerable](https://www.bengribaudo.com/blog/2017/06/16/3612/introducing-datareaderadapter) : Ben Gribaudo이 DataReaderAdapter를 설명했습니다.

### Game development소식

* [Getting Started with Duality – Part 1](https://channel9.msdn.com/Shows/dotGAME/Getting-Started-with-Duality--Part-1) : Stacey Haffner가 오픈소스 2D 게임엔진 "Duality"를 소개했습니다.
* [Attributes – Unity Tips](https://youtu.be/fxHOfV3yM9o) : GameGrind에서 Attributes를 설명했습니다.
* [Unity 5.6 Tutorial: How to create a Maze Generator – part 1](https://youtu.be/fxHOfV3yM9o) : Gamad에서 "미로 생성하기-파트 1" 동영상을 공유했습니다.
* [TDD in Unity – Heart Based Health System – Part 1](https://youtu.be/R1aO4Tmw3zA) : Infallible Code에서 TDD in Unity 시리즈 "Heart Based Health System – 파트 1" 동영상을 공유했습니다
* [Real Time Strategy in Unity – AI Implementation - Economy](https://youtu.be/R1aO4Tmw3zA) : Unit02Games에서 실시간 전략 게임 구현 시리즈 "AI 구현 : Economy" 동영상을 공유했습니다

// 전무님 소개
