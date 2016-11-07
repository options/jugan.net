주간닷넷 2016년 10월 25일


### .NET Core 1.1, ASP.NET Core 1.1, EF Core 1.1 의 프리뷰 버전1이 릴리즈 되었습니다.
* Announcing .NET Core 1.1 Preview 1 by Rich Lander.(링크)
* Announcing ASP.NET Core 1.1 Preview 1 by Jeffrey T. Fritz.(링크)
* Announcing Entity Framework Core 1.1 Preview 1 by Rowan Miller.(링크)

### On .NET 소식
[지난 주 On .NET]()에는   Rowan Miller와 함께 .Entity Framework Core 1.1 에 대해서 이야기 나누었습니다. 

이번주에는  Martin Woodward와함께   .NET Foundation에 대해서 얘기를 나누어볼 계획입니다.

### 금주의 패키지  -  FluentValidation
FluentValidation는 아주 가벼운 유효성 검증 라이브러리입니다. Jeremy Skinner이 개발한 이 라이브러리는 다양한 사용자 인터페이스를 지원하며 람다식을 사용해서 유효성 검증 규칙 생성을 할 수도 있습니다. 또한 .NET Standard 1.0 에서도 동작합니다.

// 코드


### 금주의 게임 - Reverse: Time Collapse
게임 Reverse: Time Collapse는 액션-어브벤쳐 게임으로 과거로 여행이 가능한 시간여행이라는 독특한 기능을  특징으로 합니다. 게임속에서 플레이어는 시간여행을 하면서 상황에 맞게 과학자, 저널리스트, 비밀요원 역할을 하게됩니다. 각각의 캐릭터를 통해서 적 비밀요원의 공격을 피하면서 주어진 퍼즐을 풀어야합니다  . Time Collapse는 2010년 폭로된 위키리스키에 포함된 케네디 암살(1963), 로스웰 사건(1947)등과 같이 많은 실제 사건들을 배경으로 하고 있습니다.

//그림

Reverse: Time Collapse(링크)는 현재  Meangrip(링크)에서 Unity(링크)와 C#(링크)을 이용하여 개발 중입니다.

### .NET 소식
* .NET Core Tooling in Visual Studio “15” : David Carmona와 Joe Morris가  Visual Studio “15” 버전의 .NET Core 지원 기능을 소개했습니다.
* Announcing the October 2016 Update for .NET Core 1.0 : Lee Coward가   2016 년 10월 .NET Core 1.0 업데이트를 공유했습니다.
* Introducing C# script runner for .NET Core and .NET CLI : Filip W가 .NET Core , .NET CLI 용 C# 스크립트를 소개했습니다.
* Making .NET code less allocatey – Allocations and the Garbage Collector : Maarten Balliauw가 .NET의 GC(Garbage Collector) 동작을 설명했습니다.
* Tuples with C# 7.0 : Christian Nagel이 C# 7.0의 Tuple 클래스 사용 방법을 설명했습니다
* Generate C# ETW EventSource classes from event specifications using T4 : Ohad Schneider가 T4 소스 제너레이션 템플릿을 이용한  JSON 이벤트 스팩으로부터 C# ETW 이벤트 소스를 생성하는 방법을 설명했습니다.
* EntityFramework Configuration Provider for .NET Framework & .NET Core : Patrick J. Nolan이 .NET Framework & .NET Core 의 EntityFramework Configuration Provider을 설명했습니다.
* Windows 10 1607, UWP and Lifecycle on HoloLens (2), Composition APIs–Walked Through Demo Code, and Project Rome–Transferring Browser Tabs Across Devices : Mike Taulty가 Windows 10(버전 1607)의 UWP 의 주요기능으로 홀로랜즈 App의 Lifecycle(링크),  Composition API (데모 코드를 이용해서)설명(링크), 그리고 개발자가 서로 다른 디바이스에 특정 정보를 동기화 할 수 있게 해주는 프로젝트 Rome 를 설명(링크)했습니다.
* Why the Command Line? Why now? : Sam Basu가 다중 플랫폼 개발이 중요시되는 요즘 Command Line 명령어 사용의 중요성과 배경를 설명했습니다.
* Multiple optimizations passes with case insensitive routing : Ayende Rahien이  대/소문자 비교 옵션이 성능에 미치는 영향을 설명했습니다
* Introducing NATSConsumer and .NET Core support : Daniel Wertheim이  .NET Core 를 지원하는 NATSConsumer 를 소개했습니다.
* Interception in .NET – Part 3: Static Interception : Ricardo Peres가 .NET의 Static Interception에 대해서 설명했습니다
* .NET Core Microservices using GeekseatBus : Welly Tambunan이 GeekseatBus 을 이용한 .NET Core의 Microservice를 설명했습니다.


### ASP.NET 소식
* Exploring ServiceStack’s simple and fast web services on .NET Core and Exploring Application Insights for disconnected or connected deep telemetry in ASP.NET Apps : Scott Hanselman이 .NET Core 의 ServiceStack(링크), Application Insights(링크)를 설명했습니다.
* Modifying the UI based on user authorisation in ASP.NET Core : Andrew Lock이  ASP.NET Core에서 사용자 인증결과에 따라서 UI를  다르게 구성하는 방법을 설명했습니다.
* Angular 2 and ASP.NET Core MVC :  Ryan Southgate가 Angular 2 와  ASP.NET Core MVC에 대해 설명했습니다.
* Creating route links and passing-in values : Marek Fišera가 RouteLink 생성시 인자를 전달받는 방법을 공유했습니다.
* Contoso University updated to ASP.NET Core : Jimmy Bogard가 개발자 참고용 샘플 (오픈소스)프로젝트 Contoso University Core를 소개했습니다.
* Using Apache Web Server as a reverse-proxy for ASP.NET Core : Shayne Boyer가 아파치 웹서버를 리버스-프록시 서버로 활용하는 방법을 설명했습니다
* Creating a new .NET Core web application, what are your options? : Jon Hilton이  .NET Core web application 구성시 사용할 수 있는 설정을 설명했습니다.
* Accessing SQL from Entity Framework Core Queries in ASP.NET Core : Rion Williams가  ASP.NET Core환경에서 Entity Framework Core의 쿼리에서 SQL을 확인하는 방법을 설명했습니다.
* Request Filtering for ASP.NET Core applications: Part 4 – Extending the Request Filtering Rules and Localization Resource Generator & Translator via “dotnet” CLI : Hisham Bin Ateya가 Request Filtering for ASP.NET Core applications: Part 4 - Request Filtering Rules의 확장(링크)과 “dotnet”명령창에서 사용할수있는 지역화 리소스 생성기/번역기의 구현 (링크)를 설명했습니다.
* ASP.NET Core: Globalization and Localization : Daniel Jimenez Garcia가 ASP.NET Core의 국제화(Globalization)와 지역화(Localization)를 설명했습니다
* Building Apps with Polymer and ASP.NET CORE and Don’t Share Your Secrets! (.NET CORE Secret Manager Tool) : Fizz가 Polymer와 ASP.NET CORE를이용한 어플리케이션 개발(링크)와 .NET CORE Secret Manager Tool(링크)를 설명했습니다.
* Error Handling and ExceptionFilter Dependency Injection for ASP.NET Core APIs : Rick Strahl이  ASP.NET Core APIs를 위한 예외처리와 ExceptionFilter Dependency Injection을 설명했습니다.
* Working with Environments and Launch Settings in ASP.NET Core : Matthew P Jones이  ASP.NET Core 의 실행환경과 설정에 대해서 설명했습니다.

### F# 소식
* Deploying F# Suave web application to Azure using Flynn, : Zohaib Rauf가 F# Suave를 이용한 웹 어플리케이션을 Flynn을 이용하여 Azure 에  배포하는 방법을 공유했습니다.
* F# – Basic Merkle Tree, : Ramón Soto Mathiesen 이 F#을 이용한 머큘트리(Merkle Tree) 알고리즘 구현을 설명했습니다.
* Writing a PNG Decoder in F#, Part I : Steve Hawley이 F#을 이용한 PNG Decoder 구현 방법 Part I 을 공유했습니다.
* Implementing Spark Apps in F# : Kaarthik Sivashanmugam이 F#을 이용한 Spark Apps 구현을 설명했습니다.
* F# compiler speeds up, thanks to Gusty : F# 컴파일러 성능이 향상되었습니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 8 Service Release 1 : Adrian Murphy가 Xamarin 베타 버전 Cycle 8 Service Release 1 을 소개했습니다.
* Xamarin.Forms Book Now Available in Easy to Digest Chapter Summaries : Charles Petzold가 Xamarin.Forms eBook "Creating Mobile Apps with Xamarin.Forms Book First Edition"을 소개 했습니다.
* Create a Game with iOS 10 and Message App Extensions : John Miller가 iOS 10의 게임 어플제작시 추가할 수 있는 메세지 확장기능을 소개했습니다.
* Understanding the Uniqueness of Mobile DevOps with Roy Cornelissen, Xpirit : Anusha Sethuraman이 Xpirit의 Roy Cornelissen와 함께 Mobile DevOps에 대해 팟케스트를 진행했습니다.
* Snack Pack 2: iOS Simulators and The Xamarin Show 7: Continuous C# & F# IDE for iPad with Frank Krueger : James Montemagno가 Channel9에서 Snack Pack 2: iOS Simulators(링크)와 Xamarin Show 7: Continuous C# & F# IDE for iPad(링크)를 소개했습니다.
* Push Notifications Lifecycle : Adam Pedley이 Push Notifications의 Lifecycle 을 설명했습니다.
* Reactive Goodies – IReactiveDerivedList Basics, ReactiveUI Goodies – IReactiveDerivedList Filtering 1, ReactiveUI Goodies – IReactiveDerivedList Filtering 2, and ReactiveUI Goodies – IReactiveDerivedList Grouping : Jan Hannemann이 IReactiveDerivedList 기본개념(링크), IReactiveDerivedList 필터링 1(링크), IReactiveDerivedList 필터링 2(링크), IReactiveDerivedList 그룹핑(링크)에 대해서 설명했습니다.
* ADAL and the .NET Standard Transition : Nicolò Carandini가 ADAL(Active Directory Authentication Library)과  .NET Standard에 대해서 설명했습니다.
* Getting the most out of your assets – The MonoGame Content Pipeline : Simon Jackson이 게임엔진 MonoGame의 Content Pipeline을 설명했습니다.
* VSTS – Mac build agent fail restoring NuGet packages : Jim Blizzard가 VSTS  빌드에이전트 사용하는 Mac 환경에서  NuGet 패키지를 읽을 때  발행할 수 있는 오류의 해결 방법을 공유했습니다
* How To Build Honest UIs And Help Users Make Better Decisions : Graeme Fulton이 사용자가 올바른 판단을 할 수 있는 합리적인 UI 구성에 대해서 설명했습니다
* Icons As Part Of A Great User Experience : Nick Babich가 UX의 일부인 아이콘의 디자인과 올바른 아이콘의 선택에 대해서 설명했습니다

### Azure 소식
* Use .NET Core to Create Azure Blob Storage SAS Keys : Carlos Mendible이 .NET Core에서 Azure Blob Storage SAS(shared access signatures) Key를 생성 사용하는 방법을 공유했습니다.


### Games 소식
* Kat Commentary – VR Techniques (Part 1 – Movement) : Kat Harris가 VR Techniques (Part 1 – 이동) 을 설명했습니다
* The Damage Is Too Damn High or Achieving the Perfect Balance : Arthur Mostovoy가 게임 디자인시 공격무기, 방어, 마법기술등의 균형힜는 설계에 대해서 설명했습니다 
* Beginning C# Part 15: Do/While Loops : Brian Moakley가 C# 언어강좌 Do/While 반복문을 설명했습니다.
* Tobi’s Unity Utilities : Tobias Wehrum이 Unity에서 사용할 수 있는 오픈 소스 프로젝트 Tobi's Unity Utilities을 공유했습니다
* MVC Pattern : Alex Ouellet이 MVC 패턴을 설명했습니다.

// 전무님 소개
