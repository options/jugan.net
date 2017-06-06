주간닷넷 2017년 05월 09일

### Microsoft Build 2017 소식

Microsoft Build(링크) 행사가 시에틀에서 열립니다. 채널9 행사동영상(링크) 통해서 진행된 기술세션을 보실수 있습니다.


### .NET Core 2.0 소식
이제 몇일만 있으면 .NET Core 2.0의 현재까지 알려진 모든 버그를 픽스하기 할수 있을것 같습니다.  지금까지 상당한 품질의 진전이 있었고 많은 버그를 픽스했지만 그래도 아직 163개의 버그가 남아있습니다.

//그림1

//그림2



### Happy Birthday .NET! - Eilon Lipton
지난 2월 마이크로소프트의 OB(동창회)모임의 .NET birthday 15 주년 파티에서 .NET 초기 멤버들의 이전 활약상과 현재 근황을 알려드린적이있습니다. 이번 인터뷰에서는 마이크로소프트에서 2002년부터 개발자로 근무하시고 대부분 ASP.NET분야쪽에서 작업했던 Eilon Lipton과 함께했습니다.  그는 자신의 가장 자랑스러운 결과물인  update panel(AJAX의 업데이트 페널)개발 경험과 자신이 초기 .NET 멤버로서의 가장기억에남고 영광스러웠던 순간들을 공유해주었습니다
//동영상

### On .NET
지난주에는 Alfonso García-Caro(링크)와 함께 F# 자바스크립트 컴파일러인  Fable(링크)에 대해서 함께 얘기했습니다.

//동영상


### 금주의 패키지: Stanford CoreNLP
Stanford CoreNLP(링크)는  재무/회계분야 자연어 처리 라이브러리로서 .NET 버전 라이브러리 Stanford.NLP.NET(링크)도 함께 제공합니다
 
//코드


### .NET
* Announcing the .NET Framework 4.7 General Availability : Rich Lander가  .NET Framework 4.7의 GA(General Availability) 버전을 설명했습니다
* Arrays and the CLR – a Very Special Relationship : Matt Warren이 Array(배열)을 CLR 관점에서 설명했습니다.
* ClrMD Part 3 – Dealing with static and instance fields to list timers : Christophe Nasarre와 Kevin Gosse가 "CLR MD" (Microsoft.Diagnostics.Runtime.dll )를 이용한 정적 필드, 인스턴스 필드 값의 추적방법을 설명했습니다 
* Use a XBox Controller to control your Angular2 App : Martin Kramer가 XBox 게임기의 컨트롤러를 Angular2 어플리케이션에서 활용하는 방법을 설명했습니다.
* Testing .NET Core with NUnit in Visual Studio 2017 : Rob Prouse가 NUnit 테스트 프레임워크와 Visual Studio 2017를 이용한 .NET Core용 어플리케이션의  테스트 방법을 설명했습니다.
* Who needs Visual Studio? A look at using .NET Core on Linux : Iveta Moldavcuk 가 Linux 용  .NET Core의 활용 웨비나를 공유했습니다.
* Debugging .NET core with SOS everywhere : Pam Lahoud가 SOS Debugging Extension을 이용한 NET core 어플리케이션의 디버깅 방법을 설명했습니다.
* Step by step: Kafka Pub/Sub with Docker and .Net Core : Carlos Mendible가 Docker와 .Net Core 환경에서 아파지 Kafka 의 Pub/Sub 메시지 시스템 활용 위크샵 참여 경험을 공유했습니다.
* How to Write a Sophisticated SPA: TodoMVC using C# : Muigai Mwaura가 고난이도의 SPA(Single Page Applications )의 구현을 좀 더 쉽게 구현할수있는 방법 소개했습니다.
* Using .NET Core 2 to read from an I2C device connected to a Raspberry Pi 3 with Ubuntu 16.04 : Jeremy Lindsay가 Raspberry Pi 3 와  Ubuntu 16.04환경에서 .NET Core 2를 이용한 I2C 디바이스 접근 방법을 설명했습니다. 
* Domain Command Patterns – Handlers : Jimmy Bogard가 Domain Command Pattern "Handlers"편을 공유했습니다.
* Fiddler And LINQ : Eric Lawrence가 웹 어플리케이션 디버깅 툴의 스크립트에 LINQ기능을 활용하는 방법을 설명했습니다.
* Maximizing Throughput – The Overhead of 1 Million Tasks : Daniel Crabtree가 대용량 작업 처리시 과도한 Task 오브젝트 사용의 단점을 설명했습니다.

### ASP.NET
* Extending RestSharp to Handle Timeouts in ASP.NET MVC : Matthew Jones가 ASP.NET MVC 환경에서 타임아웃기능이 포함된 확장 RestSharp 의 개발방법을 설명했습니다.
* Starting a http file server from the file explorer using .NET Core : Gérald Barré가  .NET Core환경에서 정적 파일 웹 서버의 구축 방법을 설명했습니다.
* ASP.NET Core – API versioning by convention : Tpodolak이 ASP.NET Core의 사용자 API 버전에 관련된 정보를 공유했습니다.
* IIS and ASP.NET Core Rewrite Rules for Static Files and Html 5 Routing : Rick Strahl이  ASP.NET Core를 IIS 환경에서 활용할 경우의 장점을 설명했습니다.
* Large JSON Array Streaming in ASP.NET Web API : Robert Vandenberg Huang이  ASP.NET Web API 환경에서 대용량 JSON  배열을 스트리밍 처리하는 방법을 설명했습니다.
* Create API with ASP.NET Core (Day 1): Getting Started and ASP.NET Core Request Pipeline : Akhil Mittal이 ASP.NET Core 활용 API 구축하기(1편): "ASP.NET Core Request Pipeline 이해하기" 편을 공유했습니다.
* Installing ASP.NET Core Docker For Windows : Sibeesh Passion이 윈도우 환경에서 ASP.NET Core 도커의 설치정보를 공유했습니다. 
* Login & Authentication for your ASP.NET Core Web API – The Big Picture : Jon Hilton이 ASP.NET Core Web API어플리케이션에서 로그인/인증 관련된 개념을 설명했습니다.
* Using Angular in an ASP.NET Core View with Webpack : damienbod가 ASP.NET Core View와 Webpack  프레임워크 환경에서 Angular 의 활용법을 설명했습니다.
* Secure ASP.NET Core MVC with Angular using IdentityServer4 OpenID Connect Hybrid Flow : damienbod가 Angular와 ASP.NET Core MVC환경에서 IdentityServer4 의 OpenID의 활용법을 공유했습니다.
* Plugins for ASP.NET Core Middleware : Michal Dymel이 ASP.NET Core Middleware에서 활용할수있는 Plugin의 구현방법을 설명했습니다.
* Publish And Deploy ASP.NET Core MVC On IIS : Jignesh Trivedi가 ASP.NET Core MVC를 IIS에 배포, 게시 하는 방법을 공유했습니다.
* Using ImageSharp to resize images in ASP.NET Core – Part 2 : Andrew Lock이 "ASP.NET Core에서 ImageSharp 을 이용한 이미지 resize 방법-파트2"를 공유했습니다.
* Registering Open Generics in ASPNET Core Dependency Injection : Steve Smith이  ASPNET Core DI( Dependency Injection) 기능중 제너릭 메서드의 활용방법을 공유했습니다.
* When Should You Upgrade to ASP.NET Core? : Steve Smith가 ASP.NET Core의 버전과 업그레이드 가이드 정보를 공유했습니다.
* Self Descriptive HTTP API in ASP.NET Core: Object as Resource : Derek Comartin이  OAR(Object as Resource) 패턴을 설명했습니다.
* Adding WebApi & OAuth Authentication to an Existing Project : Mitchell Sellers가 기존 프로젝트에 WebApi 와 OAuth  인증 추가방법을 공유했습니다.
* ASP.NET Core Anatomy (Part 4) – Invoking the MVC Middleware-Dissecting and understanding the internals of ASP.NET Core : Steve Gordon이 ASP.NET Core MVC 분석 (파트4)- "MVC Middleware호출, ASP.NET Core 내부 이해하기": 편을 공유했습니다.

### C#
* Just Another .NET AOP Framework: NConcern : 남정현님이 AOP(Aspect Oriented Programming) 프레임워크 NConcern 을 소개했습니다.
* Practical C# Videos – Tuples and Is Expression : Andrea Angella가 C# 개발언어 학습 동영상 리스트를 공유했습니다.
* The curious case of async, await, and IDisposable : Bill Wagner가 async, await 키워드를 이용한 비동기 메서드와 Idisposable을 연관하여 설명했습니다.
* De-virtualization in CoreCLR: Part I : Ayende Rahien이 CoreCLR에서 코드의 "역-가상화" 1편을 공유했습니다.
* De-virtualization in CoreCLR: Part II by Ayende Rahien이 CoreCLR에서 코드의 "역-가상화" 2편을 공유했습니다.
* .NET Core with csproj : Christian Nagel이 자신이 집필중이 기술서적의 Chapter 46 : ".NET Core with csproj" 부분을 공유했습니다.

### F#
* F# Survey 2017 : the F# community로 부터 F# 기능 설문조사가 진행되었습니다.
* Tooling for Your .NET Projects : Rachel Reese이 .NET 프로젝트에 도움이 되는 툴을 공유했습니다.
* ON.NET – Alfonso García-Caro – Fable : Alfonso García-Caro가 F#의 자바스크립트 변환 컴파일러인 Fable 을 소개했습니다.
* Calling F# Code in a C# Project : Connel Hooley가 C# 프로젝트에서 F# 코드를 호출하는 방법을 설명했습니다. 
* Scratching a 7-Year Itch : Paulmichael Blasucci가 자신이 개발한 fszmq 라이브러리의 7년 진행과정을 공유했습니다.
* Higher Kindended Types in F# Part IV – Signature Annotations: Robert Kuzelj이 F#의 HKT(Higher Kindended Types) 타입 4편 "Signature Annotations"을 공유했습니다.

### Xamarin
* Xamarin Beta Release: 15.2 Preview 2 :  Luis Aguilera가 Xamarin의 Beta Release: 15.2 Preview 2 릴리즈 소식을 공유 했습니다.
* Pre-release: Xamarin.Forms 2.3.5.235-pre2 : David Ortinau 가 Xamarin.Forms 2.3.5.235-pre2 버전  정보를 공유했습니다.
* Xamarin University Guest Lecture Recordings Now Free for Everyone! : Mark Smith가 Xamarin University의 새로운 무료 학습 동영상을 공유했습니다.
* Making Your Xamarin.Forms Apps Accessible : Paul DiPietro가 Xamarin.Forms의 새롭운 이름의 AutomationProperties(기존 Accessibility)클레스를 설명했습니다.
* Shopbox Uses C# to Empower Small Business Owners with the Point of Sale System of the Future : Lacey Butler가 타블렛기반 포스(POS, Point-of-Sale) 시스템 Shopbox 의 성공사례를 공유했습니다.
* Welcome the New Xamarin MVPs! : Jayme Singleton이 새롭게 선정된 Xamarin MVP 멤버들을 소개했습니다.
* Xamarin Events Blossoming in May  : Jayme Singleton이 5월 Xamarin 개발자 행사 정보를 공유했습니다.
* Developing Enterprise Apps using Xamarin.Forms : David Britch가 Xamarin.Forms을 이용한 업무 어플리케이션 개발 방법을 소개했습니다.
* Snack Pack 11: Understanding Android API Level Settings by The Xamarin Show  : James Montemagno 가 "Snack Pack 11: 안드로이드 API 레벨 설정하기" 동영상을 공유하였습니다.
* Moving towards MvvmCross 5.0 : MvvmCross에서 MvvmCross 5.0의 개발 계획을 공유했습니다. 
* Create a Backend for Xamarin.Forms using Azure Mobile App’s Easy Tables : Bryan Anthony Garcia가 Azure Mobile의 Easy Tables 기능을 활용한 Xamarin.Forms용 백앤드 서비스 개발방법을 소개했습니다.
* Fantastic Fonts in Xamarin.Forms : Matthew Soucoup이 Xamarin.Forms에 사용자 지정 폰트의 추가 방법을 공유했습니다.
* Things I Think Are Cool: JSON Copy in Xamarin Studio : Matthew Soucoup이 Xamarin Studio의 JSON Copy 기능을 소개했습니다.
* Xamarin.Tips – Creating a Material Design Button in iOS : Alex Dunn이 iOS 용 커스텀 디자인이 적용된 버튼 개발을 설명했습니다.
* Xamarin.Tips – Making Your iOS Frame Shadows More Material : Alex Dunn이 이 그림자 효과가 적용된 iOS 용 프레임 컨트롤 개발을 설명했습니다.
* Xamarin.Tips – Bringing Material Design Fonts to iOS : Alex Dunn이 iOS 어플리케이션에서 사용자 폰트 적용방법을 설명했습니다.
* Xamarin.Tips – Overriding Android Button Shadows/Elevation : Alex Dunn이 안드로이드 버튼에 그림자 효과의 적용 방법을 설명했습니다
* Xamarin forms – custom ListView separator without BoxView : Glenn Versweyveld가 ListView에 구분선 추가 방법을 설명했습니다.
* Get more reviews for your Xamarin.Forms app with iOS 10.3 : Gerald Versluis가 iOS 10.3의 어플리케이션 평가기능 활용방법을 공유했습니다.
* Xamarin Forms For Windows Developers: Tips, Tricks And Lessons Learned, Part 1 : Scott Peterson이 윈도우 개발자를 위한 Xamarin Forms 개발 방법-파트1을 공유했습니다.
* Xamarin Forms For Windows Developers: Tips, Tricks And Lessons Learned, Part 2 : Scott Peterson이 윈도우 개발자를 위한 Xamarin Forms 개발 방법-파트2을 공유했습니다.
* Solving Real-World Problems with Xamarin.Forms : Sam Basu가 Xamarin.Forms 을 이용한 개발 방법론을 공유했습니다.
* Android emulator crashes as soon as it starts : Jan Tourlamain이 안드로이드 에뮬레이터의 비정상 종료 현상과 해결방법을 공유했습니다.

### Azure
* Filtering Application Insights : Ramon de Klein이 Application Insights의 필터링 기능을 설명했습니다.
* Build a Serverless MBaaS with Azure Functions : Adrian Hall이 Azure Function을 이용하여 Serverless MBaaS(mobile backends as a service)를 구축하는 방법을 설명했습니다.


### UWP
* Make App Promotions Work: Acquire & Re-engage the Right Set of Users : Kiran Bangalore가 "사용자에게 올바르게 어플리케이션 할인 정보 제공하기" 를 공유했습니다
* Master the Master-Detail Pattern : Windows Apps Team에서 마스터-디테일 패턴의 구현방법을 설명했습니다.
* Hitchhiking the HoloToolkit-Unity, Leg 14-More with Spatial Understanding  : Mike Taulty가 HoloToolkit을 이용한 샘플개발 14번째 "공간에 대한 좀더 구체적인 이해"를 공유했습니다.
* CultureInfo changes in UWP – Part 2 : Pedro Lamas가 UWP 에서 CultureInfo 변경방법을 설명했습니다.

### Data 
* What is Micro ORM? : Gunnar Peipman가 Micro ORM을 설명하였습니다.

// 전무님 소개
