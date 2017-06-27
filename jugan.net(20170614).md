### On .NET 소식 :  Mattias Karlsson – Cake 개발자

MS 빌드 컨퍼런스 기간중 여러 참가자와 인터뷰(링크)를 진행했었습니다. 그중 이번에는 Mattias Karlsson(링크)과의 인터뷰를 공유해드리고자 합니다. Mattias Karlsson(링크)는 C#과 DSL 기술을 기반으로 한 자동 빌드 시스템 Cake(링크)의 오픈소스 프로젝트 핵심 참여자 이기도 합니다

//동영상

* Cake
* Mattias on GitHub


### 금주의 패키지: Topshelf
Topshelf는 서비스 호스팅을 위한 프레임워크로 .NET 기반으로 구현되었습니다. 개발자가 (윈도우)서비스의 생성, 디버깅및 인스톨을 쉽고 간단히 구성 할 수 있도록 도와줍니다.


//예제코드

public class TownCrier
{
    readonly Timer _timer;
    public TownCrier()
    {
        _timer = new Timer(1000) {AutoReset = true};
        _timer.Elapsed += (sender, eventArgs) =>
            Console.WriteLine($"It is {DateTime.Now} and all is well");
    }
    public void Start() { _timer.Start(); }
    public void Stop() { _timer.Stop(); }
}
public class Program
{
    public static void Main()
    {
        HostFactory.Run(x =>
        {
            x.Service<TownCrier>(s =>
            {
               s.ConstructUsing(name=> new TownCrier());
               s.WhenStarted(tc => tc.Start());
               s.WhenStopped(tc => tc.Stop());
            });
            x.RunAsLocalSystem();
x.SetDescription("Sample Topshelf Host");
            x.SetDisplayName("TownCrier");
            x.SetServiceName("TownCrier");
        });
    }
}

* Topshelf web site
* Topshelf on NuGet
* Topshelf source code
* Topshelf documentation

### .NET 소식
* Performance Improvements in .NET Core : Stephen Toub가 .NET Core 성능 향상 팁과 정보를 공유했습니다.
* Measuring Performance Improvements in .NET Core with BenchmarkDotNet (Part 1) :  Andrey Akinshin이 BenchmarkDotNet 을 활용한 .NET Core 성능 측정방법을 가이드 했습니다.
* .NET Core 2 and Visual Studio 2017 Preview 2 : Lee Coward가 .NET Core 2와 Visual Studio 2017 Preview 2 정보를 공유했습니다.
* .NET Fringe: A Great Role Model for Community Oriented Conferences : Immo Landwerth가 커뮤니티 중심의 기술 이벤트".NET Fringe"를 소개했습니다.
* .NET and Docker : Scott Hanselman이 윈도우 도커와 .NET 환경 구성 방법를 공유했습니다.
* Trying .NET Core on Linux with just a tarball (without apt-get) : Scott Hanselman이 리눅스환경에서 tarball (Tar.gz 파일)형식의 설치 파일을 이용한 간단한 .NET Core 환경 구성 방법을 소개했습니다.  
* Continuously publishing Nuget package to MyGet using VSTS : Gérald Barré가 MyGet와 VSTS를 이용한 지속적인 Nuget package 배포방법을 소개했습니다.
* Porting a .NET Framework library to .NET Core : "Harsh Gupta 9"이 .NET Framework용 라이브러리를 .NET Core 용으로 포팅한 경험과 방법을 공유했습니다.
* Creating your first shared library in .NET Core : Paul Hiles가 .NET Core 용 공유 라이브러리 구현방법을 설명했습니다.
* Contributing to the .NET Core SDK source code for the first time, and how OSS helped me : Jeremy Lindsay가 .NET Core SDK  오픈소스 프로젝트 정보와 OSS(Open Source Software)에 참여한 자신의 경험을 공유했습니다.
* 5 Reasons You Should Stop Using System.Drawing from ASP.NET : Clinton Ingram이 ASP.NET 프로젝트에서 System.Drawing을 사용(참조)하면 안되는 5가지 이유를 설명했습니다.
* First Foray into .NET Core 2.0 : Julie Lerman이 .NET Core 2.0환경의 첫 개발 경험을 공유했습니다.
* Testavior: A Happy Solution To Test Your ASP.NET Core Applications : Arnaud가 ASP.NET Core 어플리케이션용 테스트 솔루션 "Testavior"를 소개했습니다.
* Getting Started with PowerShell Core on Windows, Mac, and Linux : Ashley McGlone이 다중 플랫폼 환경(Windows, Mac, Linux )을 지원하는  PowerShell Core를 소개했습니다.
* Logging with Log4Net and Common Logging : Matthew Groves가 Log4Net과 Common Logging을 이용한 로깅방법을 설명했습니다.
* Implementing a scheduler for your orchestrations : Szymon Kulec ‘Scooletz’가 async-await 패턴과 Task 객체를 이용한 코드 실행순서 제어방법을 설명했습니다.

### ASP.NET 소식
* Defining custom logging messages with LoggerMessage.Define in ASP.NET Core : Andrew Lock이 ASP.NET Core의 로깅 프레임워크와 LoggerMessage Helper 클래스를 소개했습니다.
* Defining ASP.NET Core Controller action constraint to match the correct action : Pam Lahoud가 ASP.NET Core Controller의 action을 특정 조건을 기준으로 제어하는 방법을 설명했습니다.
* Excluding the node_modules folder when publishing ASP.NET projects. : Cecil Phillip이 ASP.NET 어플리케이션 배포시 node js를 제외하고 배포하는 방법을 설명했습니다.
* Simplest Possible ASP.NET Core Web Application in Docker for Windows : Bobby Johnson이  ASP.NET Core 웹 어플리케이션을 윈도우 도커에 설치하는 간단한 예를 설명했습니다.
* Theming in ASP.NET Core : Hisham Bin Ateya가 ASP.NET Core 웹 어플리케이션용 테마기능 구현방법을 설명했습니다.
* Keep your ASP.NET Core application’s secrets safe during development : Jon Hilton이 ASP.NET Core 웹 어플리케이션에서 보안에 민감한 정보를 안전하게 저장및 처리하는 방법을 설명했습니다.
* Self Descriptive HTTP API in ASP.NET Core: Hypermedia Clients : Derek Comartin이 ASP.NET Core 환경에서 자기기술적(Self Descriptive)HTTP API 개발 방법을 소개했습니다.
* OpenID Connect Session Management using an Angular application and IdentityServer4 : Damien Bowden이 Angular 환경에서 "OpenID Connect Session Management"의 구현방법을 설명했습니다.
* Building the Ultimate RestSharp Client in ASP.NET and C# : Matthew Jones가 C#과 RestSharp(REST/HTTP API 클라이언트 라이브러리)를 활용한 강력한 웹(API) 클라이언트 개발방법을 설명했습니다.
* ASP.NET Core POCO Controllers : Dino Esposito가 ASP.NET Core MVC 컨트롤러의 내부 생성 과정과 구조를 설명했습니다.
* Feeding Server Timing API from ASP.NET Core : Tomasz Pęczek이 웹 어플리케이션 성능평가를 위해 사용할 수 있는 여러 시간 측정 API 들 중에서 서버시간 측정용 라이브러리를 소개했습니다.

### C# 소식
* C# 7 Features with Mads Torgersen : Mads Torgersen, Maria Naggaga, Jon Galloway이 C# 7.0 기능을 소개했습니다.
* An Early Look at C# 7.1 - Part 1 : InfoQ에서 "C# 7.1 기능 미리보기" - 파트1 을 공유했습니다.
* C# 7.2 and 8.0 Roadmap : InfoQ에서 C# 7.2과 8.0 버전 로드맵을 공유했습니다.
* C# 7 Series, Part 3 - Default Literals : Mark Zhou가 C# 7 시리즈 - 파트 3  "기본 리터럴"을 공유했습니다.
* Disambiguate method trick based on generic constraint : Matthieu Mezil가 제너닉 조건을 기반한 메서드 구분  방법을 설명했습니다.
* Top 20 Recommended Microsoft Build 2017 Sessions for C# Developers : Alvin Ashcraft가 MS 빌드 2017 행사의 세션중 C# 개발자에게 추천하는 20개 세션리스트를 공유했습니다.
* Null checking allocations and mass refactoring with Resharper : Alexander Tsvetkov가  Resharper의 Null checking allocation 기능과 여러 refactoring  기능을 소개했습니다.
* Practical C# – LINQ Set Operations : : Andrea Angella가 학습 비디오 "C# 실무 : LINQ Set 연산자"를 공유했습니다.

### F# 소식
* Kami 2 Solver in F# – Part 1 : Chris Smith가 퍼즐 게임 "Kami 2" 의 Solver를 F#으로 구현한 경험을 공유했습니다.
* Minimalistic Live Testing Fable Apps With QUnit : Zaid Ajaj가 QUnit 을 이용한 Fable Apps의 Live Test 방법을 설명했습니다.
* Parallel Programming with F# and Hopac : Natallia Dzenisenka가 .NET Fringe 행사 기술 세션 "F#과 Hopac 환경의 병렬 프로그램" 동영상을 공유했습니다.
* Productive Web Applications (F#) : Jeremy Abbot이 .NET Fringe 행사 기술 세션 "웹 어플리케이션 개발 생산성(F#)" 동영상을 공유했습니다.

### VB 소식
* Building web API apps on ASP.NET Core 2 and VB.NET : Gunnar Peipman이 VB.NET로 ASP.NET Core 2  web API 어플리케이션을 구현하는 방법을 설명했습니다.

### Xamarin 소식
* Enterprise Application Patterns using Xamarin.Forms : David Britch가 Xamarin.Forms에서 활용할 수 있는 Enterprise Application Patterns을 소개했습니다.
* Enterprise Apps Made Easy with New Authentication & Microsoft Graph Libraries : Mayur Tendulka가 Microsoft Graph 라이브러리와 새로운 인증 기능을 활용한 Enterprise App 구현 방법을 설명했습니다.
* Unleashed: Embedding Xamarin.Forms in Xamarin Native : David Ortinau가 Xamarin Native환경에서 Xamarin.Form을 포함(Embedding)하는 방법을 설명했습니다.
* WWDC 2017 Recap for iOS Developers : Pierce Boggan이 iOS 개발자에게 도움이되는 WWDC 2017 행사 내용을 정리했습니다.
* Xamarin Developer Events This June : Jayme Singleton이 6월 Xamarin 개발자 행사 정보를 공유했습니다.
* Episode 24: Xamarin Live Player : Xamarin Show 24편 "Xamarin Live Player"가 공유되었습니다.
* Getting started with MonoGame using XML : Simon Jackson이 MonoGame과 XML 을 활용한 게임 개발 방법을 설명했습니다.
* Creating Custom Controls with Bindable Properties in Xamarin.Forms : Bryan Anthony Garcia가 Xamarin.Forms에서 Bindable 속성을 포함한 사용자 정의 컨트롤 구현 방법을 설명했습니다.
* Xamarin Forms, the MVVMLight Toolkit and I: Dependecy Injection : Marco Siccardi가 "MVVMLight Toolkit"을 소개했습니다.
* Alpha Release: Xamarin Workbooks & Inspector 1.3.0-alpha2 : Bri Brothers가 Xamarin Workbooks & Inspector 1.3.0-alpha2 버전 정보를 공유했습니다.
* Common issues in the Xamarin 15.2.2 release being tracked by the Xamarin team : Brendan Zagaeski가 Xamarin 15.2.2 release 버전의 알려진 이슈에 대한 정보를 공유했습니다.
* Optimize memory usage in Xamarin apps : Samuel Debruyn이 Xamarin 어플리케이션의 메모리활용 최적화 방법을 설명했습니다.
* Mobile Center plugin for fastlane : Mobile Center Team에서 "Fastlane"용 Mobile Center 플러그인을 소개했습니다.
* Zero to Build: Create new Xamarin apps in minutes with AppMap : Infragistics에서 Xamarin 개발환경용 라이브러리 AppMap 을 소개했습니다.
* Can’t Start Android Emulator on macOS? It’s Probably Conflicting with Docker : Junian Triajianto가 macOS에서 Android Emulator 가 동작하지않을 경우 문제해결 방법을 공유했습니다.
* Xamarin and DevOps: Setting up your iOS CI : Steven Thewissen이 "Xamarin DevOps : iOS CI(Continuous Integration) 환경 구성"를 공유했습니다.
* Xamarin and DevOps: Versioning your app : Steven Thewissen이 "Xamarin DevOps : App 버전 셋팅하기"를 공유했습니다.
* Getting Started with Xamarin Forms for Mac Preview : S Ravi Kumar가 "Xamarin Forms for Mac Preview" 버전를 소개했습니다.
* Realm Mobile Database with Xamarin Forms Step By Step Guide : S Ravi Kumar가 Xamarin Forms 에서 Realm 모바일 데이터베이스 활용 방법을 설명했습니다.
* NuGet Support in Visual Studio for Mac 7.0 : Matt Ward가 Visual Studio for Mac 7.0 의 NuGet 지원 정보를 공유했습니다.
* Xamarin.Forms & PaintCode : Antonio Feregrino Bolaños가 Xamarin.Forms에서 PaintCode 의 활용방법을 설명했습니다.

### Azure 소식
* Azure via C# – Delete Azure Blobs : Andrea Angella가  학습 비디오 "Azure, C# : Blobs 파일 삭제"를 공유했습니다.
* Azure via C# – Download Azure Blobs : Andrea Angella가  학습 비디오 "Azure, C# : Blobs 파일 다운로드"를 공유했습니다.
* Upgrade your .Net Core Service Fabric Microservices from VS 2015 to VS 2017 : Andrej Medic이.Net Core Service Fabric Microservices의 개발 환경을  VS 2015에서 VS 2017로 업그레이드하는 방법을 공유했습니다.
* Architecting Azure Functions: Function Timeouts and Work Fan-Out with Queues : Jason Roberts가 Azure Function 아키텍쳐를 설명했습니다.
* Remote debug your Azure App Service 2017 including ASP.NET Core : Benjamin Perkins가 "Azure App Service 2017"의 원격 디버깅 방법을 설명했습니다.

### UWP 소식
* Native Ads in Microsoft Advertising SDK : Vivek Mohan이 "Native Ads in Microsoft Advertising SDK"를 소개했습니다.
* Using color fonts for beautiful text and icons : Rick Manning이 사용자 정의 폰트의 일종인 "color fonts"의 소개, 지원 범위와 활용방법등을 설명했습니다.

### Data 소식
* Reduce Overhead When Retrieving Objects with Entity Framework : Peter Vogel이 "EF를 활용한 효과적인  데이터 조회방법" 을 공유했습니다.
* LLBLGen Pro for .NET and .NET Core – Database Entity Modeling with any ORM : Scott Hanselman이 "LLBLGen (ORM 브릿지의 일종)"을 소개했습니다.

### Game development소식
* Advanced VR Mechanics With Unity and the HTC Vive – Part 2 : Eric Van de Kerckhove가 "HTC Vive(VR장비)와 Unity 를 활용한 VR 개발 가이드 - 파트 2"를 공유했습니다.
* Getting started with MonoGame using XML : Simon Jackson이 MonoGame과 XML 을 활용한 게임 개발 방법을 설명했습니다.
* Sid Meier and Bruce Shelley’s postmortem of Civilization : Sid Meier와 Bruce Shelley가 GDC 2017 행사에서 진행된 "postmortem of Civilization" 세션 동영상을 공유했습니다.
* Getting started with Mixer Interactivity in Unity : Stacey Haffner가 " Unity를 활용한 Mixer Interactivity "를 설명했습니다.

// 전무님 소개
