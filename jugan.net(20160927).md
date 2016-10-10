주간닷넷 2016년 9월 27일

### On .NET 소식
[지난 주 On .NET]()에는 Sébastien Ros 와  Orchard 2(링크)에 대해서 얘기 나누어보았습니다.

// 동영상

[이번 주 On .NET]()에는  JB Evain와  Visual Studio 2015 Tools for Unity, 그리고 .NET 프로파일링 오픈소스 라이브러리 Cecil에 대해 얘기를 나누어 보겠습니다.

### Mocking on .NET Core
 .NET의 대표적인  mocking frameworks 3개가 .NET Standard를 지원하는 프리-릴리즈 버전을 공개했습니다.

- FakeItEasy(링크)

- Moq: (주의:gitbub에 moq.netcore 라는 이름의 패키지도 있지만 이것은 공식적인 Moq와는 전혀 다른 개인적인 프로젝트 이므로 공식 Moq package의 사용을 권장합니다)

- NSubstitute(링크)

### 금주의 패키지  -  Storyteller
BDD(링크, Behavior Driven Development : 행동 주도 개발) 방법론은 코드의 기능 개발에 집중할 수 있도록 해줍니다.  패키지 Storyteller는 원하는 테스트 작업을  문장(물론 영문으로)으로 서술하면 코드를 실행해 줍니다. 따라서 기술적인 배경이없는 일반 업무대상자도 쉽게 코드를 실행함으로서 테스트를 진행할 수 있습니다.  코드에 이런한 문장을 포함할 수 있으며 개발자가 문장내용을 쉽게 수정하는것도 가능합니다.

Storyteller(링크)는 .NET을 지원하는 (곧 .NET Core도 지원할 예정인)  BDD 패키지로서 통합테스트, 실행 검수, 코드 문서 산출물 생성등에 효과적으로 사용할 수 있습니다
StoryTeller 3.0이 최근에 릴리즈되었으며 StructureMap, Marten등의 제품이 이패키지의 도움을 받았으며 StoryTeller 제품 역시 자신의 테스트에 StoryTeller를 사용하고 있습니다.

// 코드

### 금주의 게임 - Armello
Armello는 전략 카드게임과 롤플레잉 요소를 포함한 게임으로 아름다운 그래픽 효과를 자랑하는 보드게임입니다. 게임을 시작면 플레이어는 Armello의 세계에서 8명의 영웅중 하나의 역할을 선택하게 됩니다. 각각 영웅 케릭터는 각자의 독특한 특성이 있습니다. 플레이어는 게임에서 탐험, 탐색하고 몬스터와의 전투에서 승리하여 현재의 왕을 타도하고 자신이 통치가가 되어야 합니다. 게임 Armello는 1인 및 다중 플레이를 지원하며, 동적 레벨 생성 시스템, 그리고 120개가 넘는 다양한 그래픽효과의 카드가 사용됩니다.

//그림

Armello
Unity와 C을 이용하여 League of Geeks에서 제작 했으며 현재   Xbox One, PlayStation 4에서 지원되며 Steam을 통해서 Windows, Mac, Linux 에서 즐기실 수 있습니다.


### .NET 소식
* Introducing .NET Standard : Immo Landwerth가 .NET Standard 를 소개했습니다.
* Get started with VS Code using C# and .NET Core : Kendra Havens가  VS Code 와  C# 을 이용한 .NET Core용 어플리케이션 개발방법을 소개했습니다.
* GLAD is available : Maoni Stephens이 메모리 프로파일링 관련 오픈소스 SDK인 GLAD 를 소개했습니다.
* Announcing the DotNetCompilerPlatform 1.0.2 release : Matt FJH가 DotNetCompilerPlatform 1.0.2 릴리스 정보를 공유했습니다.
* Cake v0.16.0 released : Patrik Svensson이 C# 빌드 엔진 시스템 Cake v0.16.0 버전 릴리즈 정보를 공유했습니다.
* When a disk cache performs better than an in-memory cache (befriending the .net GC) : Productive Rage가 디스크 케쉬가 인-메모리 케쉬보다 빠를 수 있는 상황을 설명했습니다.
* The Dotnet Watch Tool : Muhammad Rehan Saeed가 툴 "Dotnet Watch"을 소개했습니다.
* Deal with Swallowed Exceptions Magically with IL Weaving : Nick Chamberlain이 예외처리 코드중 개발자가 catch문에 예외처리를  하지않은 코드들을 쉽게 해결할수있는 방법을 공유했습니다.
* September Update to docs.microsoft.com : Jeff Sandquist가 docs.microsoft.com  사이트의 9월 업데이트 사항을 공유했습니다.



### ASP.NET 소식
* Reusing Configuration Files in ASP.NET Core : Connie Yau가 기존 ASP.NET의 설정파일(*.config)을 ASP.NET Core 에서 재사용하는 방법을 설명했습니다.
* Introducing IdentityServer4 for authentication and access control in ASP.NET Core : Jeffrey T. Fritz가  ASP.NET Core에서 사용자인증과 권한관리를 위해 IdentityServer4 를 활용하는 방법을 설명했습니다.
* IdentityServer4 RC1 : Dominick Baier가 IdentityServer4 RC1을 소개했습니다.
* NGINX for ASP.NET Core In-Depth : Muhammad Rehan Saeed가 오픈소스 웹서버 NGINX 을 소개했습니다.
* To do: write “to do” app with ASP.Net Core : Andy Butland가 to do 리스트를 관리하는 ASP.Net Core 어플리케이션의 구현과정을 공유했습니다.
* Use NancyFx in ASP.NET Core : Talking Dotnet이 오픈소스 웹서버 NancyFx를 ASP.NET Core 환경에서 사용하는 방법을 공유했습니다.
* Step by step: ASP.NET Core on Docker : Carlos Mendible이 도커환경에서 ASP.NET Core 를 활용하는 방법을 설명했습니다.
* Adding Localisation to an ASP.NET Core application and How to use machine-specific configuration with ASP.NET Core : Andrew Lock이  ASP.NET Core 어플리케이션의 로컬라이제이션(지역화) 기능 구현방법(링크)과 ASP.NET Core의 서버별 설정 방법(링크)을 설명했습니다.
* Troubleshooting High CPU Usage of a .NET Web Application : Paulo Henrique S.S.가 CPU 점유율이 높은 웹 어플리케이션의 문제를 해결하는 과정을 공유했습니다.

### F# 소식
* xUnit-Jet – Open Sourced : Rand Davis가  C#을 위해서 디자인된 단위테스트 오픈소스 프레임워크인 xunit을 F#에서도 사용할 수 있도록 해주는  확장툴 xunit-jet을 소개했습니다.
* F# and ASP.NET Core (video), by Enrico Sada via Community for F# : Enrico Sada가 F# 과 ASP.NET Core의 활용법을 설명했습니다.
* F# in the Real World (video), : Yan Cui가 F# 언어를 소개했습니다.
* Xando: Down the rabbit hole of CQRS and Event Sourcing, :  alxandr가 CQRS(Command-Query Responsibility Segregation, 명령과 쿼리의 역할구분)와 ES(Event Sourcing) 패턴을 설명했습니다.
* Absolute layout and relative layout Xamarin Forms, : Kimserey Lam이 Xamarin Forms의 Absolute layout, relative layout을 설명했습니다.
* Using F# and Canopy for UI Testing, : Jeremy Bellows가 F# and Canopy 를 이용한 UI테스팅하는 방법을 공유했습니다.
* Learning F#, ASP.NET Core, and Polymer : Joe Audette이  F#, ASP.NET Core환경에서 Polymer 를 사용하는 방법을 공유했습니다.

### Xamarin 소식
* Scaling from Side Project to 200,000+ Downloads with Xamarin and Microsoft Azure : Courtney Witmer가 대학 과제물 프로젝트 웹사이트에서 Xamarin과 Azure를 이용해서 2백만 이상 다운로드를 기록하는 웹 어플리케션으로 스케일 업된  Foundbite 어플리케이션 사례를 소개했습니다.
* Start Building Azure-Connected Apps with the Xamarin Shopping Demo App : Mike James가 Azure-Connected Apps의 개발을 이해하는데 도움이 되는 데모 어플리케이션 Xamarin Shopping Demo App을 소개했습니다. 
* Xamarin Around the World with Xamarin Dev Days by Jayme Singleton이 업데이트된  Xamarin Dev Days 개발 행사 일정을 공유했습니다.  
* New iOS 10 Privacy Permission Settings, The Xamarin Show 2 – Continuous Integration with Simina Pasat, and The Xamarin Show – Snack Pack 1: Android Emulators : James Montemagno가  iOS 10의 새로운 개인 정보 권한 설정 설명과(링크),  Simina Pasat와 함께 VSTS를 이용한 Xamarin 개발을 소개한  Xamarin Show 2(링크), Android Emulators를 소개한 Xamarin Show (링크)를 공유했습니다.
* Preview: iOS Simulator (for Windows) Update 4 : Adrian Murphy가 OS Simulator Update 4 정보를 공유했습니다.
* NuGet Support in Xamarin Studio 6.1 : Matt Ward가 NuGet을 지원하게된  Xamarin Studio 최신 버전 6.1을 소개했습니다.
* Xamarin Forms Triggers vs Behaviors vs Effects : Adam Pedley가 Xamarin Forms의  Triggers, Behaviors, Effects를 소개했습니다.
* Hololens app with UrhoSharp : Introduction – Part 1 : Maxime Frappat가 UrhoSharp 을 활용한 Hololens app 개발방법을 소개했습니다.
* Hololens – Xamarin, URHO and an Spatial Mapping sample (with 2 more lines of code it became a Shooting Game) : Bruno Capuano가 Xamarin, URHO, 공간 맵핑기능을 활용한 Hololens 샘플을 소개했습니다.
* The Thumb Zone: Designing For Mobile Users : Samantha Ingram이 모바일 어플리케이션의 UX 디자인에 대해 설명 했습니다
* Fix for UITest crashing after Xamarin Studio update to 6.1 (build 5441) fails with SetUp : System.InvalidOperationException : Mark J Radacz가 Xamarin Studio 6.1로 업데이트 할 경우 UITest 기능이 특정 예외(System.InvalidOperationException)를 발생하는 상황을 해결할 수 있는 방법을 공유했습니다.
* Yet Another Podcast #164 – Azure Mobile Apps with Chris Risner : Jesse Liberty가 Microsoft의 Principle Software Development Engineer인 Chris Risner와 Azure Mobile Apps라는 주제로 팟케스트를 진행했습니다.

### Azure 소식
* Azure Functions in practice : Troy Hunt가 Azure Functions 기능을 설명했습니다.
* Tutorial: Launch Your ASP.NET Core WebApp on Azure with TLS & Authentication : Laura Rodriguez가 Azure 에서   ASP.NET Core WebApp을 TLS (HTTPS) 인증구성하는 방법을 설명했습니다.


### Games 소식
* Unity 5 Tutorial: How to make Snake Movement : Unity by Gamad에서 Unity 5에서 뱀의 이동 동작을 표현하는 방법을 설명했습니다.
* Let’s Learn Unity: Unity Interface Tips and Tricks : Wuzseen이 Unity Interface 사용에 도움이되는 Tips,Tricks를 공유했습니다.
* Understanding Interfaces : clawsgamedev가 C# 언어의 Interfaces 에 대해서 설명했습니다.
* Unity 2D Movement (Part 1) – Forwards & Backwards : Pixel Make에서 2D 게임에 필요한 요소중 전/후 이동 기능 구현을 설명했습니다.
* Unity 2D: Checking if a Character or Object is on the Ground using Raycasts : Kyle Banks가 Raycasts 를 이용하여 게임 케릭터 혹은 게임 객체가 지면위에 있는지 확인 하는 방법을  설명했습니다.


// 전무님 소개
