여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

###금주의 커뮤니티 소식
Taeyo.NET에서 http://docs.asp.net의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
* [MVC : View – 레이아웃]( http://taeyo.net/Columns/View.aspx?SEQ=570&PSEQ=40)

### .NET Core 1.1, ASP.NET Core 1.1, EF Core 1.1 의 프리뷰 버전1이 릴리즈 되었습니다.
* [.NET Core 1.1 Preview 1 버전 소개]( https://blogs.msdn.microsoft.com/dotnet/2016/10/25/announcing-net-core-1-1-preview-1/)
* [ASP.NET Core 1.1 Preview 1 버전 소개]( https://blogs.msdn.microsoft.com/webdev/2016/10/25/announcing-asp-net-core-1-1-preview-1/)
* [Entity Framework Core 1.1 Preview 1 버전 소개]( https://blogs.msdn.microsoft.com/dotnet/2016/10/25/announcing-entity-framework-core-1-1-preview-1/)

### On .NET 소식
[지난 주 On .NET]( https://sec.ch9.ms/ch9/e3ad/c8a22c83-2ca6-4970-aa24-814c5625e3ad/OnNetRowanMiller_high.mp4)에는 Rowan Miller와 함께 .Entity Framework Core 1.1 에 대해 얘기 나누었습니다.
https://sec.ch9.ms/ch9/e3ad/c8a22c83-2ca6-4970-aa24-814c5625e3ad/OnNetRowanMiller_high.mp4
[이번주]( https://sec.ch9.ms/ch9/377a/4cadaf76-2cc1-492e-ab93-c392f6b5377a/onnet20161027martinwoodward_mid.mp4)에는 Martin Woodward와 함께 .NET Foundation에 대해 얘기 나누어 보겠습니다.

### 금주의 패키지 - FluentValidation
ASP.NET MVC 웹 애플리케이션에서 사용자 입력값의 유효성을 검사하는 방법은 여러 가지가 있겠지만, 보통은 DataAnnodations 방법을 이용합니다. 그러나 FluentValidation 라이브러리를 이용하면 훨씬 더 편리하게 유효성 검사를 수행할 수 있습니다. Jeremy Skinner가 개발한 FluentValidation 라이브러리는 다양한 사용자 인터페이스를 제공하며, 람다 식을 사용해서 유효성 검증할 수 있는 규칙을 생성을 할 수도 있습니다.
<script src="https://gist.github.com/bleroy/8a6f163485cde1f89c9c0ebc94b5cbd9.js"></script>

### 금주의 게임 - Reverse: Time Collapse
게임 [Reverse: Time Collapse]( https://madewith.unity.com/games/reverse-time-collapse)는 액션-탐험 게임으로 시간 여행이 가능한 독특한 게임 컨셉을 가지고 있습니다. 플레이어는 시간여행을 하면서 스토리에 따라 과학자, 저널리스트, 비밀요원 역할을 하며, 적 비밀요원을 피해 숨겨진 사건에 대한 단서를 찾고 진실을 파해치는 것이 게임의 목적입니다. Reverse: Time Collapse는 케네디 암살(1963), 로즈웰 사건(1947) 등 실제 일어난 사건들을 배경으로 하고 있습니다.

//그림

Reverse: Time Collapse는 현재 [Meangrip]( http://www.meangrip.com/)에서 [Unity]( https://unity3d.com/)와 [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용해 개발 중입니다.

### .NET 소식
* .NET Core Tooling in Visual Studio “15” : David Carmona와 Joe Morris가 Visual Studio “15” 버전의 .NET Core 기능에 관해 소개합니다.
* Announcing the October 2016 Update for .NET Core 1.0 : Lee Coward가 .NET Core 1.0 최근 업데이트 사항에 관해 소개합니다.
* Introducing C# script runner for .NET Core and .NET CLI : Filip W가 .NET Core와 .NET CLI 용 C# script를 소개했습니다.
* Making .NET code less allocatey – Allocations and the Garbage Collector : Maarten Balliauw가 .NET의 GC(Garbage Collector) 기능에 관해 설명합니다.
* Tuples with C# 7.0 : Christian Nagel이 C# 7.0에서 Tuple Class 사용 방법을 공유했습니다.
* Generate C# ETW EventSource classes from event specifications using T4 : Ohad Schneider가 C# ETW 클래스를 위한 T4 TEXT Template 코드 생성기인 ET4W에 관해 설명합니다.  
* EntityFramework Configuration Provider for .NET Framework & .NET Core : Patrick J. Nolan이 .NET Framework & .NET Core의 EntityFramework Configuration Provider에 관해 소개합니다.
* Windows 10 1607, UWP and Lifecycle on HoloLens (2), Composition APIs–Walked Through Demo Code, and Project Rome–Transferring Browser Tabs Across Devices : Mike Taulty가 Windows 10의 1607 버전에서 업데이트된 UWP의 주요기능과 홀로렌즈 Lifecycle에 관해 설명하고, 다른 디바이스에서 특정 정보를 동기화 할 수 있는 ‘Rome’에 대해 소개합니다.
* Why the Command Line? Why now? : Sam Basu가 다중 플랫폼 개발에 필요한 Command Line 명령어 사용 방법과 중요성에 관해 설명합니다.
* Multiple optimizations passes with case insensitive routing : Ayende Rahien이 대/소문자 비교 코드를 추가해 라우팅 속도를 최적화 하는 방법에 관해 설명합니다.
* Introducing NATSConsumer and .NET Core support : Daniel Wertheim이 .NET Core를 지원하는 NATSConsumer에 관해 소개합니다.
* Interception in .NET – Part 3: Static Interception : Ricardo Peres가 .NET의 Static Interception에 관해 설명합니다.
* .NET Core Microservices using GeekseatBus : Welly Tambunan이 GeekseatBus을 이용한 .NET Core의 Microservice에 관해 설명합니다.

### ASP.NET 소식
* Exploring ServiceStack’s simple and fast web services on .NET Core and Exploring Application Insights for disconnected or connected deep telemetry in ASP.NET Apps : Scott Hanselman이 .NET Core의 ServiceStack과 Application Insights에 관해 설명합니다.
* Modifying the UI based on user authorisation in ASP.NET Core : Andrew Lock이 ASP.NET Core에서 사용자 인증 결과에 따라 UI를 다르게 구성하는 방법을 공유했습니다.
* Angular 2 and ASP.NET Core MVC : Ryan Southgate가 Angular 2 와 ASP.NET Core MVC에 관해 설명합니다.
* Creating route links and passing-in values : Marek Fišera가 RouteLink 생성시, 인자를 전달 받는 방법에 관해 설명합니다.
* Contoso University updated to ASP.NET Core : Jimmy Bogard가 ASP.NET Core 개발 참고용 오픈소스인 Contoso University Core를 공유했습니다. 
* Using Apache Web Server as a reverse-proxy for ASP.NET Core : Shayne Boyer가 Apache 웹 서버를 reverse-proxy 서버로 활용하는 방법을 소개합니다.
* Creating a new .NET Core web application, what are your options? : Jon Hilton이 .NET Core web application 설정 메뉴에서 제공하는 기능들을 소개합니다.
* Accessing SQL from Entity Framework Core Queries in ASP.NET Core : Rion Williams가 ASP.NET Core 환경에서 Entity Framework Core 쿼리로 SQL을 확인하는 방법에 관해 설명합니다.
* Request Filtering for ASP.NET Core applications: Part 4 – Extending the Request Filtering Rules and Localization Resource Generator & Translator via “dotnet” CLI : Hisham Bin Ateya가 ASP.NET Core 애플리케이션에 요청 필터링을 확장시키는 방법과 “dotnet” 명령 창에서 사용할 수 있는 지역화 리소스 생성기/번역기 구현 방법에 관해 설명했습니다.
* ASP.NET Core: Globalization and Localization : Daniel Jimenez Garcia가 ASP.NET Core의 국제화(Globalization)와 지역화(Localization)에 관해 설명합니다.
* Building Apps with Polymer and ASP.NET Core and Don’t Share Your Secrets! (.NET Core Secret Manager Tool) : Fizz와 Polymer가 ASP.NET Core를 이용한 애플리케이션 개발 방법과 .NET Core Secret Manager Tool에 관해 소개합니다.
* Error Handling and ExceptionFilter Dependency Injection for ASP.NET Core APIs : Rick Strahl이 ASP.NET Core APIs 예외 처리와 ExceptionFilter Dependency Injection에 관해 설명합니다.
* Working with Environments and Launch Settings in ASP.NET Core : Matthew P Jones이 ASP.NET Core 실행 환경과 설정 기능에 관해 소개합니다.

### F# 소식
* Deploying F# Suave web application to Azure using Flynn : Zohaib Rauf가 F# Suave를 이용한 웹 어플리케이션을 Flynn으로 Azure에 배포하는 방법을 공유했습니다.
* F# – Basic Merkle Tree : Ramón Soto Mathiesen이 F#을 이용한 머큘트리(Merkle Tree) 알고리즘 구현 방법을 소개합니다.
* Writing a PNG Decoder in F#, Part I : Steve Hawley이 F#을 이용한 PNG Decoder 구현 방법을 공유했습니다.
* Implementing Spark Apps in F# : Kaarthik Sivashanmugam이 F#을 이용해 Spark Apps을 구현하는 방법에 관해 설명합니다.
* F# compiler speeds up, thanks to Gusty : 향상된 F# 컴파일러 성능을 소개합니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 8 Service Release 1 : Adrian Murphy가 Xamarin 베타 버전 Cycle 8 Service Release 1에 관해 소개합니다.
* Xamarin.Forms Book Now Available in Easy to Digest Chapter Summaries : Charles Petzold가 Xamarin.Forms에 대해 소개하는 eBook인 "Creating Mobile Apps with Xamarin.Forms Book First Edition"에 대해 소개합니다.
* Create a Game with iOS 10 and Message App Extensions : John Miller가 iOS 10의 게임 어플 제작시 추가적인 메세지 확장 기능에 관해 소개합니다.
* Understanding the Uniqueness of Mobile DevOps with Roy Cornelissen, Xpirit : Anusha Sethuraman과 Roy Cornelissen가 Mobile DevOps를 주제로 팟케스트를 진행했습니다.
* Snack Pack 2: iOS Simulators and The Xamarin Show 7: Continuous C# & F# IDE for iPad with Frank Krueger : James Montemagno가 Channel9에서 iOS Simulators와 iPad를 위한 Continuous C# & F# IDE에 관해 소개합니다.
* Push Notifications Lifecycle : Adam Pedley이 Push Notifications의 Lifecycle에 관해 설명합니다.
* Reactive Goodies – IReactiveDerivedList Basics, ReactiveUI Goodies – IReactiveDerivedList Filtering 1, ReactiveUI Goodies – IReactiveDerivedList Filtering 2, and ReactiveUI Goodies – IReactiveDerivedList Grouping : Jan Hannemann이 IReactiveDerivedList의 기본개념과 필터링 그리고 그룹핑 방법에 관해 설명합니다.
* ADAL and the .NET Standard Transition : Nicolò Carandini가 ADAL(Active Directory Authentication Library)과 .NET Standard에 관해 설명합니다.
* Getting the most out of your assets – The MonoGame Content Pipeline : Simon Jackson이 게임엔진 MonoGame의 Content Pipeline에 대해 소개합니다.
* VSTS – Mac build agent fail restoring NuGet packages : Jim Blizzard가 VSTS 빌드에이전트를 사용하는 Mac 환경에서 NuGet 패키지를 읽을 때, 발행할 수 있는 오류 해결 방법을 공유했습니다.
* How To Build Honest UIs And Help Users Make Better Decisions : Graeme Fulton이 사용자가 만족할 수 있는 UI 구성 방법에 대해 설명합니다.
* Icons As Part Of A Great User Experience : Nick Babich가 Xamarin UX 디자인를 위한 좋은 아이콘들을 추천합니다.

### Azure 소식
* Use .NET Core to Create Azure Blob Storage SAS Keys : Carlos Mendible이 .NET Core에서 Azure Blob Storage SAS(shared access signatures) Key 생성 방법을 알려드립니다.


### Games 소식
* Kat Commentary – VR Techniques (Part 1 – Movement) : Kat Harris가 VR Techniques (Part 1 – 이동)에 관해 소개합니다.
* The Damage Is Too Damn High or Achieving the Perfect Balance : Arthur Mostovoy가 게임을 기획할때 공격무기, 방어, 마법 기술 벨런스 조정 방법에 대해 설명합니다.
* Beginning C# Part 15: Do/While Loops : Brian Moakley가 C# 언어강좌에서 Do/While 반복문에 대해 소개합니다.
* Tobi’s Unity Utilities : Tobias Wehrum이 Unity에서 사용할 수 있는 오픈 소스 프로젝트 Tobi's Unity Utilities을 공유했습니다.
* MVC Pattern : Alex Ouellet이 MVC 패턴에 대해 소개합니다.

// 전무님 소개
