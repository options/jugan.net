### .NET Architecture - 마이크로서비스 & 컨테이너
최근에 .NET 웹사이트에 아키텍쳐 기술 가이드(링크)가 추가되었습니다. 이 페이지들은 .NET의 각 타입별 어플리케이션 구현과 관련된 아키텍쳐 정보를 제공하고 있으며, 앞으로도 관련 기술이 업데이트 되면 페이지에도 추가할 예정입니다.

여러 기술항목중 마이크로서비스&컨테이너(Microservices & Containers) 섹션부분은 .NET의 마이크로서비스의 빌드, 배포부분에 관련한 유용한 정보가 포함되어있으며  이와 관련해서 .NET Product Team 매니저 Cesar De la Torre(링크)는 두개의 eBooks을 집필하여 공유했습니다. 그중 하나는 마이크로서비스의 디자인과 구현에 관한 내용이고 다른 하나는 운영환경의 배포와 관리적인 측면에 대한 내용입니다. 또한 eShopOnContainers 샘플 어플리케이션을 학습함으로서 컨테이너의 개념을 좀더 쉽게 이해하실 수 있습니다.

### On .NET 소식 : Omer Raviv – OzCode
MS 빌드 컨퍼런스 기간중 여러 참가자와 인터뷰(링크)를 진행했었습니다. 그중 이번주에는 Visual Studio 디버깅 확장툴인 OzCode(링크) 데모와 함께 Omer Raviv(링크)와의 인터뷰를 공유해드리고자 합니다. OzCode툴은 손쉬운 Linq 표현식 디버깅 코드 편집기에 변수값 바로 표현등의 기능을 포함하고있습니다. 이번 인터뷰는 특히 디버깅에 관심 있으신 분들이 보시면 많은 도움이 될것입니다.

//그림

### 금주의 패키지: Sprache
개발자로서 프로그램개발 하면서 문자열을 파싱하는 작업은 가장 흔하면서도 번거로운 기본작업중에 하나일것입니다. 문자열 파싱 작업은 소규모의 업무 DSL을 정의하고 분석하거나, 문자열에 단순한 특정 형식을 확인하거나, 또는 사용자가 정한 복작합 형식을 비교하여 분석하기도 합니다. 하지만 공통적으로 이런 모든 상황에서 작업 문자열은 어떠한 방법으로든 문자열에서 데이터로 변환 되어야만 프로그램에서 자료로서 활용하는것이 가능합니다. 

이미 "ANTLR"(링크)라는 툴은 이런 모든 기능을 지원해주며 이미 많은 언어의 문법등이 정의되어 개발자가 복잡한 파싱도 쉽게하도록 도와줄수있습니다. 하지만 이 툴은 복잡한 대규모 분석에서 효과적으로 사용할 수 있으며 간단한 단순 문자열분석등에는 오히려 비능률적일 수 있습니다. 대부분의 경우 개발자는 가볍고 단단하게 사용할수있는 문자열 분석 엔진을 필요로 합니다. 이때 사용할수있는 툴이 "Sprache"(링크)입니다.

 Sprache는 단순 파싱 작업에 적합 하도록 설계된 가벼운 문자열 파싱 엔진 입니다. 이제 더 이상 정규식을 사용하지 않고도 쉽고 조작 가능한 파서를 이용한 문자열 분석이 가능합니다.

/
Parser<string> identifier =
    from leading in Parse.WhiteSpace.Many()
    from first in Parse.Letter.Once()
    from rest in Parse.LetterOrDigit.Many()
    from trailing in Parse.WhiteSpace.Many()
    select new string(first.Concat(rest).ToArray());
var id = identifier.Parse(" abc123  ");
Assert.AreEqual("abc123", id);

* Sprache on GitHub
* Sprache on NuGet
* Building a DSL using Sprache by Nicholas Blumhardt

### .NET 소식
* Microsoft .NET Framework 4.7 is available on Windows Update, WSUS, and MU(Microsoft Update) Catalog : Jamshed Damkewalark 가 윈도우 업데이트, WSUS(Windows Server Update Services), MU(Microsoft Update)를 통해서 .NET Framework 4.7 배포가 가능하다는 소식을 공유했습니다.
* How the .NET Runtime loads a Type : Matt Warren이 .NET 런타임이 Type을 로드하는 과정을 설명했습니다.
* Rider EAP 23: .NET Core debugger is back, Code Cleanup, and more : Jura Gorohovsky가  .NET Core 디버깅, Code Cleanup 등의 기능을 포함한 Rider의 pre-release 버전 EAP(Early Access Program)23을 소개했습니다.
* Automate Testing and Running Apps with dotnet watch : Steve Smith가 dotnet watch를 이용한 App 자동실행, 테스트 방법을 설명했습니다.
* One year of running the Windsor-Essex .NET Developers : Derek Comartin이 지역 커뮤니티 Windsor-Essex를 1년 진행한 과정과 계획을 공유했습니다.
* From Java to .Net Core, Part 2: Types : Yev Bronshteyn이 "Java코드 .Net Core 전환 가이드 파트2: 타입" 블로그를 게시했습니다.
* AutoMapper 6.1.0 released : Jimmy Bogard가 AutoMapper 6.1.0 릴리즈 소식을 공유했습니다.
* Consuming REST Services from Your Mobile Application Using Swagger and AutoRest : Nick Randolph가 Swagger와 AutoRest를 이용한 모바일 어플리케이션의 REST Services 호출 방법을 설명했습니다. 
* .Net Core .csproj – Automatically Packaging README.txt : Ben Gribaudo가 .Net Core의 .csproj 프로젝트항목에 "README.txt"를 포함시키는 방법을 공유했습니다.
* To Heap or not to Heap; That’s the Large Object Question? : Doug Duerner가 .NET 시스템의 Large Object 메모리 관리 방법과 개념을 설명했습니다.
* Create a Free Private NuGet Server with Continuous Deployment using VSTS : Paul Hiles가 VSTS를 이용한 CD(Continuous Deployment) 환경구축을 위한 프로젝트 전용 NuGet Server 구축 방법을 설명했습니다.
* How to reference a .NET Core library in WinForms – Or, .NET Standard Explained : Scott Hanselman이 .NET Core lib를 기존 WinForms 프로젝트 혹은  .NET Standard 프로젝트에서 참조하여 활용하는 방법을 설명했습니다.

### ASP.NET 소식
* Automatically validating anti-forgery tokens in ASP.NET Core with the AutoValidateAntiforgeryTokenAttribute : Andrew Lock이 ASP.NET Core의 AutoValidateAntiforgeryTokenAttribute을 이용한 위조방지 토큰 유효성의 자동 검증방법을 설명했습니다.
* Minimal ASP.NET Core Web API project : Gérald Barré가 간단한 ASP.NET Core Web API 프로젝트 구현과정을 공유했습니다.
* Docker for .NET Developers (Part 3) Why we started using Docker with ASP.NET Core and Docker for .NET Developers (Part 4) Working with docker-compose and multiple ASP.NET Core microservices : Steve Gordon이 .NET 개발자를 위한 도커 시스템 학습 시리즈 "파트 3: ASP.NET Core를 도커환경에 구축해야 하는 이유"와  "파트4 : docker-compose 활용과  ASP.NET Core 마이크로서비스"편을 공유했습니다.
* Resolving ASP.NET Core Startup class from the DI container : Filip W가 DI(Dependency Injection) 컨테이너에서 ASP.NET Core의 Startup  클레스를 찾는 방법을 설명했습니다.
* Integrating Microsoft Identity Authorization into a Menu System : Jonathan Danylko가 어플리케이션 메뉴 시스템의 권한기능구현시  MS의 인증 정보를 포함하는 방법을 설명했습니다.
* Middleware in ASP.NET Core – Handling requests : Ibrahim Šuta가 "ASP.NET Core 미들웨어 : 요청 처리하기"편을 공유했습니다
* From 0 to 100 with this ASP.NET Core/AngularX Project Template : Greg Duncan이 ASP.NET Core/AngularX 프로젝트 템플릿을 소개했습니다.
* Exploring GraphQL and creating a GraphQL endpoint in ASP.NET Core : Jürgen Gutsch가 ASP.NET Core환경에서 GraphQL 활용법을 소개했습니다.
* Using Consul for Health Checks with ASP.NET Core : Cecil Phillip이 Consul 을 활용한 ASP.NET Core 어플리케이션의 장애유무 확인 방법을 설명했습니다.
* ASP.NET Core deployment using Docker, Nginx and Ubuntu Server : Piotr Gankiewicz가 도커를 활용한 엔진 x와 우분트 서버환경에 ASP.NET Core를 배포하는 방법을 설명했습니다.
* Options for Configuring ASP.NET Core Application Settings : Rion Williams가 ASP.NET Core Application에서 설정 config를 위한 오픈소스 lib "Options"를 소개했습니다.
* Michael Ballhaus (MCPD + SCJP)  Show off your API with a little Swagger : Michael Ballhaus이 Swagger를 활용한 Web API 노출방법을 설명했습니다.
* 10 Things To Know About In-Memory Caching In ASP.NET Core : Bipin Joshi가 ASP.NET Core의 In-Memory Caching에 대해 알아야할 10가지 정보를 공유했습니다.

### C# 소식
* C# 7.x and 8.0: Uncertainty and Awesomeness : Erik Heemskerk가 C# 7.x, 8.0 버전의 새로운 기능을 소개했습니다.
* My Favorite C# 7 Feature: More expression-bodied members : James Montemagno가 C# 7.0의 향상된 기능 "표현식-함수 멤버"을 소개했습니다.
* Practical C# – Extern Alias in C# : Andrea Angella가 학습 비디오 "C# 실무 : Extern Alias"를 공유했습니다.

### F# 소식
* Building Roguelike in F# : Simo Raman이 F#을 이용한 로그라이크 타입 게임 구현 방법을 설명했습니다.
* Options in F# : Andras Nemes가 F#의 Options object를 설명했습니다.
* Pulling state from F# Mailboxes : Sam Williams가 F#의 MailboxProcessor를 소개했습니다.
* The Foundations of Functional Concurrency is 37% off! : Manning, Riccardo Terrell이 기술 서적 "The Foundations of Functional Concurrency"의 소개와 Functional Concurrency의 중요성을 설명했습니다.

### VB 소식
* Visual Basic and Cross-Platform: Mobile Apps with VB, Xamarin, and .NET Standard! : Klaus Löffelmann이 VB, Xamarin, .NET Standard를 이용한 모바일 어플 개발방법을 소개했습니다.
* Calling Web Services with HttpWebRequest, WebClient and HttpClient : Peter Vogel이 HttpWebRequest, WebClient, HttpClient를 이용한 웹서비스 호출 방법에 관해 설명했습니다.
* Viva, Visual Basic! Or, Does VB Have a Future? : Michael Domingo가 향후 VB의 로드맵을 공유했습니다.


### Xamarin 소식
* Stable Release: 15.2.3 Xamarin.VS Servicing Release : Bri Brothers가 15.2.3 Xamarin  VS 서비스 릴리즈 정보를 공유했습니다.
* Xamarin Forms, the MVVMLight Toolkit and I: navigation and modal pages : Marco Siccardi가 Xamarin Forms의  navigation과 modal pages를 설명했습니다.
* Visual States in Xamarin.Forms using BuildIt.Forms : Nick Randolph가 Xamarin.Forms에서 BuildIt.Forms을 이용한 Visual States 활용방법을 설명했습니다.
* Xamarin.Forms Visual States with View Models : Nick Randolph가 View Models에서 Visual States 활용방법을 설명했습니다.
* Chat Bot with Xamarin Forms : Adam Pedley가 Microsoft Bot Framework를 이용한 Xamarin Forms의 Chat Bot 구현 방법을 설명했습니다.
* Is Xamarin Forms Making Traditional Xamarin Obsolete? : Adam Pedley가 Xamarin Forms와 Xamarin native의 로드맵과 상호관계를 설명했스빈다.
* Xamarin Forms ChatBot Application using the Microsoft Bot Framework : Suthahar J가 Microsoft Bot Framework을 활용한 ChatBot 어플리케이션 구현 방법을 공유했습니다.
* Boosting Your Productivity with MFractor : Gerald Versluis가 Visual Studio Mac용 확장툴인 MFractor를 소개했습니다.
* 5 Ways to Boost Xamarin.Forms App Startup Time : David Ortinau가 Xamarin.Forms 어플리케이션의 초기 실행시간을 단축 시킬수있는 5가지 방법을 소개했습니다.
* Adding Face Tracking and Live Recognition to your Android App : Nish Anil이 이미지와 실시간 스트리밍을 통한 안면인식기능을 안드로이드 어플에 추가 하는 방법을 설명했습니다.
* Demystifying Build Configurations : Jon Goldberger가 빌드 설정을 알기쉽게 설명했습니다.
* Episode 25: Unity Game Development with Visual Studio for Mac with Jb Evain : The Xamarin Show에서 에피소드 25편"Visual Studio for Mac을 이용한 Unity 게임 개발"편을 공유했습니다.
* Growing Your First Xamarin.Forms Mac App : Matthew Soucoup가 Xamarin.Forms을 활용한 Mac 어플구현방법을 설명했습니다.
* Things I Think Are Cool: Custom XAML Markup Extensions : Matthew Soucoup가 "XAML 마크업 사용자 확장" 기능을 설명했습니다
* Embedding Xamarin.Forms into a Xamarin Native App #TheFuture : James Montemagno가 Xamarin Native환경에서 Xamarin.Form을 포함(Embedding)하는 방법을 설명했습니다.

### Azure 소식
* Azure via C# – Working with Azure Queues : Andrea Angella가  Azure 학습 비디오 "Azure, C# : Azure Queues"를 공유했습니다.
* Writing an Azure Function in C# to create an ICS Calendar File : Michael Crump가 Azure Function에서 ICS 일정파일의 생성 방법을 설명했습니다.
* Creating ASP.NET Web App In Azure : Viral Jain이 Azure 환경의 ASP.NET 웹 어플리케이션 구현방법을 공유했습니다.
* AppVeyor – Continuous Delivery to Azure for your .NET Core Applications : Jamie Taylor가 AppVeyor를 활용한 Azure .NET Core 어플리케이션의 CD(Continuous Delivery) 환경 구축과정을 설명했습니다.

### UWP 소식
* Adding Fluent Design Acrylic Material to UWP via Xamarin.Forms. : Nick Randolph가 Xamarin.Forms을 통해서 Fluent Design을 UWP에 적용하는 방법을 설명했습니다.
* iBeacons and UWP : Channel 9에서 iBeacon을 UWP 에서 활용하는 방법을 소개했습니다.
* Setting up a HoloLens project with the HoloToolkit : Joost van Schaik가 홀로렌즈 개발툴킷인 HoloToolkit의 HoloLens 프로젝트를 소개했습니다.

### Data 소식
* Introducing DataReaderAdapter: Adds AsDataReader()/AsDataReaderOfObjects() to IEnumerable : Ben Gribaudo이 DataReaderAdapter를 설명했습니다.

### Game development소식
* Getting Started with Duality – Part 1 : Stacey Haffner가 오픈소스 2D 게임엔진 "Duality"를 소개했습니다.
* Attributes – Unity Tips : GameGrind에서 Attributes 를 설명했습니다.
* Unity 5.6 Tutorial: How to create a Maze Generator – part 1 : Gamad에서 "미로 생성하기-파트1" 동영상편을 공유했습니다.
* TDD in Unity – Heart Based Health System – Part 1 :Infallible Code에서 TDD in Unity 시리즈 "Heart Based Health System – 파트 1" 동영상을 공유했습니다
* Real Time Strategy in Unity – AI Implementation - Economy : Unit02Games에서 실시간 전략 게임 구현 시리즈 "AI 구현 : Economy" 동영상을 공유했습니다


// 전무님 소개
