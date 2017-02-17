여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

##On .NET 소식

지난 주 On .NET에는 Sébastien Ros 와 Orchard 2에 대해서 이야기 나누어보았습니다.

// 동영상

이번 주 On .NET에는 JB Evain와 Visual Studio 2015 Tools for Unity, 그리고 .NET 프로파일링 오픈소스 라이브러리 Cecil에 대해 알아보겠습니다.

Mocking on .NET Core

3개의 대표적인 .NET mocking framework가 .NET Standard를 지원하는 프리-릴리즈 버전을 공개했습니다.

* FakeItEasy
* Moq
* NSubstitute

##금주의 패키지 - Storyteller

BDD “Behavior Driven Development”는 테스트 케이스를 먼저 작성하고 실제 동작 코드를 나중에 작성하는 TDD에서 한발 더 나아가 테스트 케이스 자체가 사양이 되도록 하는 개발 방식입니다. BDD를 진행하기 위해 Storyteller 패키지를 사용한다면 원하는 테스트 작업을 문장(영문)으로 서술하면 코드로 실행하므로, 기술적인 배경이 없는 실무자도 쉽게 테스트를 진행할 수 있습니다. Storyteller는 .NET을 지원하는 (곧 .NET Core도 지원할 예정인) BDD에 패키지로서 통합테스트, 실행 검수, 코드 문서 산출물 생성등에 유용하게 사용할 수 있습니다 최근에 StoryTeller의 3.0 버전이 릴리즈되어 StructureMap, Marten등의 제품이 패키지의 도움을 받았습니다.

// 코드

##금주의 게임 - Armello

Armello는 전략 카드게임과 롤플레잉 요소를 포함한 게임으로 아름다운 그래픽 효과를 자랑하는 보드게임입니다. 게임은 각자 특별한 능력을 가진 8명의 영웅 중 한명을 선택하여 탐험하며 보스를 물리치고 왕이 되는 것이 게임의 목적입니다. 1인 및 다중 플레이를 지원하며, 120개가 넘는 다양한 카드의 그래픽효과를 볼 수 있습니다.

//그림

Armello은 Unity와 C#을 이용하여 League of Geeks에서 제작 했으며 현재 Xbox One, PlayStation 4에서 지원되며 Steam을 통해서 Windows, Mac, Linux 에서 즐기실 수 있습니다.

##.NET 소식
* Introducing .NET Standard : Immo Landwerth가 .NET Standard에 대해 소개합니다.
* Get started with VS Code using C# and .NET Core : Kendra Havens가 VS Code 와 C#을 이용한 .NET Core용 어플리케이션 개발 방법에 대해 소개합니다.
* GLAD is available : Maoni Stephens이 메모리 프로파일링 관련 오픈소스 SDK인 GLAD에 대해 소개합니다.
* Announcing the DotNet Compiler Platform 1.0.2 release : Matt FJH가 DotNet Compiler Platform 1.0.2 릴리스 정보를 공유했습니다.
* Cake v0.16.0 released : Patrik Svensson이 C# 빌드 엔진 시스템 Cake v0.16.0 버전 릴리즈 정보를 공유했습니다.
* When a disk cache performs better than an in-memory cache (befriending the .net GC) : Productive Rage가 디스크 케쉬가 인-메모리 케쉬보다 빠를 수 있는 상황을 설명합니다.
* The Dotnet Watch Tool : Muhammad Rehan Saeed가 툴 "Dotnet Watch"에 대해 소개합니다.
* Deal with Swallowed Exceptions Magically with IL Weaving : Nick Chamberlain이 예외처리 코드중에 개발자가 catch문에 예외처리를 하지 않은 코드를 쉽게 해결할 수 있는 방법에 대해 공유했습니다.
* September Update to docs.microsoft.com : Jeff Sandquist가 docs.microsoft.com 사이트의 9월 업데이트 사항을 공유했습니다.

##ASP.NET 소식
* Reusing Configuration Files in ASP.NET Core : Connie Yau가 기존 ASP.NET의 설정파일(*.config)을 ASP.NET Core 에서 재사용하는 방법에 대해 설명합니다.
* Introducing IdentityServer4 for authentication and access control in ASP.NET Core : Jeffrey T. Fritz가 ASP.NET Core에서 사용자 인증과 권한 관리를 위해 IdentityServer4를 활용하는 방법에 대해 설명합니다.
* IdentityServer4 RC1 : Dominick Baier가 IdentityServer4 RC1에 대해 소개합니다.
* NGINX for ASP.NET Core In-Depth : Muhammad Rehan Saeed가 오픈소스 웹서버 NGINX에 대해 소개합니다.
* To do: write “to do” app with ASP.Net Core : Andy Butland가 to do 리스트를 관리하는 ASP.Net Core 어플리케이션의 구현 과정을 공유했습니다.
* Use NancyFx in ASP.NET Core : Talking Dotnet이 오픈소스 웹서버 NancyFx를 ASP.NET Core 환경에서 사용하는 방법에 대해 소개합니다.
* Step by step: ASP.NET Core on Docker : Carlos Mendible이 도커환경에서 ASP.NET Core 를 활용하는 방법에 대해 설명합니다.
* Adding Localisation to an ASP.NET Core application and How to use machine-specific configuration with ASP.NET Core : Andrew Lock이 ASP.NET Core 어플리케이션의 Localization 기능 구현 방법과 ASP.NET Core의 서버 설정 방법에 대해 설명합니다.
* Troubleshooting High CPU Usage of a .NET Web Application : Paulo Henrique S.S.가 CPU 점유율이 높은 웹 어플리케이션의 문제 해결 과정을 공유했습니다.

## F# 소식
* xUnit-Jet – Open Sourced : xUnit을 F#에서도 사용할 수 있는 xunit-jet 확장 툴에 대해 소개합니다.
* F# and ASP.NET Core (video), by Enrico Sada via Community for F# : Enrico Sada가 F# 과 ASP.NET Core의 활용법에 대해 설명합니다.
* F# in the Real World (video) : Yan Cui가 F# 언어를 소개합니다.
* Xando: Down the rabbit hole of CQRS and Event Sourcing : alxandr가 CQRS(Command-Query Responsibility Segregation, 명령과 쿼리의 역할 구분)와 ES(Event Sourcing) 패턴에 대해 설명합니다.
* Absolute layout and relative layout Xamarin Forms : Kimserey Lam이 Xamarin Forms의 Absolute layout, relative layout에 대해 설명합니다.
* Using F# and Canopy for UI Testing : Jeremy Bellows가 “F# and Canopy”를 이용한 UI 테스팅 방법에 대해 공유했습니다.
* Learning F#, ASP.NET Core and Polymer : Joe Audette이 F#, ASP.NET Core 환경에서 Polymer를 사용하는 방법에 대해 설명합니다.

## Xamarin 소식
* Scaling from Side Project to 200,000+ Downloads with Xamarin and Microsoft Azure : Courtney Witmer가 대학 과제물 프로젝트 웹사이트에서 Xamarin과 Azure를 이용해서 2백만 이상 다운로드를 기록한 웹 어플리케션 “Foundbite”의 사례를 소개 합니다.
* Start Building Azure-Connected Apps with the Xamarin Shopping Demo App : Mike James가 Azure-Connected Apps의 개발을 이해하는데 도움이 되는 어플리케이션 Xamarin Shopping Demo App에 대해 소개합니다.
* Xamarin Around the World with Xamarin Dev Days : Jayme Singleton이 Xamarin Dev Days 행사 최신 일정을 공유했습니다.
* New iOS 10 Privacy Permission Settings, The Xamarin Show 2 – Continuous Integration with Simina Pasat and The Xamarin Show – Snack Pack 1: Android Emulators : James Montemagno가 iOS 10의 새로운 개인 정보 권한 설정 방법과 Xamarin Show 2에서 VSTS를 이용한 Xamarin 개발 방법, Android Emulators에 대해 소개합니다.
* Preview: iOS Simulator (for Windows) Update 4 : Adrian Murphy가 OS Simulator Update 4 정보를 공유했습니다.
* NuGet Support in Xamarin Studio 6.1 : Matt Ward가 NuGet을 지원하는 Xamarin Studio 6.1 버전에 대해 소개합니다.
* Xamarin Forms Triggers vs Behaviors vs Effects : Adam Pedley가 Xamarin Forms의 Triggers, Behaviors, Effects를 소개합니다.
* Hololens app with UrhoSharp : Introduction – Part 1 : Maxime Frappat가 UrhoSharp을 활용한 Hololens App 개발 방법에 대해 소개합니다.
* Hololens – Xamarin, URHO and an Spatial Mapping sample (with 2 more lines of code it became a Shooting Game) : Bruno Capuano가 Xamarin, URHO, 공간 맵핑 기능을 활용한 Hololens Sample에 대해 소개합니다.
* The Thumb Zone: Designing For Mobile Users : Samantha Ingram이 모바일 어플리케이션의 UX 디자인에 대해 설명 했습니다
* Fix for UITest crashing after Xamarin Studio update to 6.1 (build 5441) fails with SetUp : System.InvalidOperationException : Mark J Radacz가 Xamarin Studio 6.1로 업데이트 할 경우, UITest 기능이 특정 예외(System.InvalidOperationException)를 발생시키는 상황을 해결할 수 있는 방법에 대해 설명합니다.
* Yet Another Podcast #164 – Azure Mobile Apps with Chris Risner : Jesse Liberty가 Microsoft의 Principle Software Development Engineer인 Chris Risner와 Azure Mobile Apps라는 주제로 팟케스트를 진행했습니다.

## Azure 소식
* Azure Functions in practice : Troy Hunt가 Azure Functions 기능에 대해 설명합니다.
* Tutorial : Launch Your ASP.NET Core WebApp on Azure with TLS & Authentication : Laura Rodriguez가 Azure에서 ASP.NET Core WebApp에 TLS (HTTPS) 인증 구성 방법에 대해 설명합니다.

## Games 소식
* Unity 5 Tutorial: How to make Snake Movement : Unity 5에서 뱀의 이동 모습을 표현하는 방법에 대해 설명합니다.
* Let’s Learn Unity: Unity Interface Tips and Tricks : Wuzseen이 Unity Interface 사용에 도움이 되는 Tips, Tricks를 공유했습니다.
* Understanding Interfaces : clawsgamedev가 C# Interfaces에 대해 설명합니다.
* Unity 2D Movement (Part 1) – Forwards & Backwards : Pixel Make에서 2D 게임에 필요한 요소중 앞 뒤 이동 기능 구현에 대해 설명합니다.
* Unity 2D: Checking if a Character or Object is on the Ground using Raycasts : Kyle Banks가 Raycasts를 이용하여 객체가 지면 위에 있는지 확인 하는 방법에 대해 설명합니다.
