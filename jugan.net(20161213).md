주간닷넷 2016년 12월 13일

### On .NET 소식

[지난 주 On .NET]()(링크)에는 섬밋기간중 MVP와 인터뷰한 내용 두개를 보내드렸습니다.

Stephen Cleary talked about his AsyncEx library(링크)
Luis Valencia showed his IoT work with sensor data aggregation using Azure(링크)
[이번 주 On .NET](링크)에는 Immo Landwerth, Karel Zikmund, 그리고 Wes Haggard 와 함께 .NET team 이 .NET Core 오픈소스 프로젝트와 리포들을 어떻게 관리하는지 얘기 나누도록 하겠습니다


### 금주의 App  -  Ulterius
Ulterius는 웹 브라우저에서 실행되는 완벽한 원격 제어 솔루션(링크)입니다.  하드웨어와 프로세스 모니터링 및 관리, 원격 쉘 실행 (cmd, PowerShell, and bash), 파일 시스템 억세스, 스케줄링, 웹캠 억세스 그리고 원격 데스트탑 기능을 포함합니다.

// 그림

Ulterius는 .NET 기반 오픈소스(링크) 프로젝트입니다.

### 금주의 App  -  Inferno
Inferno는 관련분야 인증을 받은 범용 목적의 현대적인 .NET 기반 오픈소스 암호화 라이브러리입니다.  
보안관련 서적 Security-drive .NET의 저자인  Stan Drapkin가 개발하였습니다.

//코드

### 금주의 게임 - Bastion
Bastion은 액션 롤 플레잉 게임입니다. 플레이어는 게임속 자신의 세계가 Calamity이라는 엄청난 재앙으로 산산히 부서진 후 Bastion이라는 곳으로 탐험을 떠나는 젊은 전사의 역할을하게됩니다. 손으로 수작업하여 아름답게 그려진 40여개가 넘는 그래픽 배경과 어우러진 맵을 탐사하면서 Calamity 의 비밀을 풀어나가게됩니다. 게임 Bastion에는 플레이어에게  도움을 주는 게임 나래이터 기능이 있는데 플레이어가 이동하거나 무기를 업그레이드할때 혹은 게임 캐릭터를 업그레이드 할때 등 상황 맞는 정보를 음성으로 알려 줍니다.

//그림

Bastion
(링크)는 현재  Supergiant Games(링크)에서 C#(링크)과 자신들이 직접 개발한 게임엔진을 이용하여 개발되었습니다. 현재는 Steam, Xbox One, Xbox 360, PlayStation 4, PlayStation VITA 그리고 the Apple App Store를 통해서 즐기실 수 있습니다.

### .NET 소식
Matt Warren가 "research papers in the .NET source"(링크) 게시물을 공유했습니다.

* December 2016 Update for .NET Core 1.0 : Kendra Havens가 .NET Core 1.0의 12월 업데이트 내용을 공유했습니다.
* Updating Visual Studio 2017 RC – .NET Core Tooling improvements : Joe Morris와 David Carmona가 Visual Studio 2017 RC에 추가된 새로운 기능 "향상된 .NET Core Tooling 기능"에 대해 설명했습니다.
* .NET Standard (video playlist) : Immo Landwerth가 .NET Standard 학습 시리즈를 공유했습니다.
* Implementing low level trie and Writing my own synchronization primitive ReaderWriterLock : Ayende Rahien가 로우레벨 트리구현 방법(링크)와 ReaderWriterLock 사용자 Lock 객체 구현 방법(링크)를 공유했습니다.
* Orleans 2.0 Tech Preview supporting .NET Core : Julian Dominguez가 Orleans(Azure 클라우드 프로그래밍 모델)의 2.0 Tech Preview 버전이 .NET Core를 지원한다는 소식을 공유했습니다.
* How to calculate 17 billion similarities : Szymon Warda가 자신의 Cookit 웹사이트에서 170억의 유사성을 어떻게 구분/판단하는지 구현내용을 공유했습니다.
* The best log viewer in the universe : Stackify가 로그 뷰어 유틸리티인 "Prefix"(http://stackify.com/prefix)를 소개했습니다. 
* Free eBook: Containerized Docker Application Lifecycle with Microsoft Platform and Tools : Cesar de la Torre가 무료 eBook "Containerized Docker Application Lifecycle with Microsoft Platform and Tools"을 공유했습니다.
* What is this race condition that the OpenMutex documentation is trying to warn me about? : Raymond Chen이 OpenMutex Win32 API 사용시 알아두어야할 주의점을 설명했습니다.

### ASP.NET 소식
* New Updates to Web Tools in Visual Studio 2017 RC : Daniel Roth가 Visual Studio 2017 RC에 새롭게 업데이트된 Web Tool 관련 기능을 정리했습니다.
* Getting started with My Tested ASP.NET Core MVC in less than 15 minutes :  ASP.NET Core MVC의 단위 테스트 라이브러리 "MY TESTED ASP.NET CORE"의 사용 Tutorial 문서를 공유했습니다.
* In-memory testing using ASP.NET Core : Joseph Woodward가 ASP.NET Core의 In-memory test 방법을 설명했습니다.
* Getting started with OLAP for ASP.NET MVC : Prabhakar Mishra가 OLAP ASP.NET MVC 사용방법을 설명했습니다.
* Localization.SqlLocalizer: SQL Localization for ASP.NET Core supporting all EF Core providers. : Damien Bod가 ASP.NET Core에서 지역화 문자열을 쉽게 관리할 수 있도록 도와주는 Localization.SqlLocalizer를 소개했습니다.
* Debug ASP.NET Core on Docker with Visual Studio Code : Carlos Mendible이 Visual Studio Code를 이용하여 도커환경에서 실행되는 ASP.NET Core를 디버깅 하는 방법을 공유했습니다.
* Applying the RouteDataRequest CultureProvider globally with middleware as filters : Andrew Lock이 RouteDataRequest CultureProvider를 미들웨어 필터로 전체 일괄적용하는 방법을 설명했습니다.
* Exploring Wyam – a .NET Static Site Content Generator : Scott Hanselman이 Wyam(사이트 통계 정보 생성기)을 소개했습니다.
* Fat Controller CQRS Diet: Vertical Slices : Derek Comartin이 CQRS(Command-Query Responsibility Segregation, 명령과 쿼리의 역할구분)를 이용하여 MVC 컨트롤러를 효과적으로 개선하는 방법 "Vertical Slices"편을 게시했습니다.
* Migration to ASP.NET Core: Considerations and Strategies : Scott Addie가 ASP.NET Core로 전환시 전략과 고려사항을 정리했습니다.
* Scaffolding ASP.Net Core MVC : Shashangka Shekhar이 Scaffolding을 이용한 ASP.Net Core MVC 개발 예를 설명했습니다.
* Fun with the HttpClient pipeline : Thomas Levesque가 HttpClient의 동작방식과 활용법을 설명했습니다.
* Basic Steps to Migrate HTTP Handlers and HTTP Modules to ASP.NET Core Middleware : Srinivasa Dinesh Parupalli가 기존 HTTP Handlers와 HTTP Modules을 ASP.NET Core 의 Middleware 로 전환하는 기본적인 방법을 설명했습니다.
* Build a REST API for your Mobile Apps with ASP.NET Core : Laura Rodriguez가  ASP.NET Core를 이용한 모바일 App용 REST API의 개발 방법을 설명했습니다.
* Introducing the ASP.Net Async OutputCache Module : lanlanlee2008이 ASP.Net 의 "Async OutputCache Module"을 소개했습니다. 
* Managing Cookie Lifetime with ASP.NET Core OAuth 2.0 providers : Jerrie Pelser가 OAuth 2.0 provider환경에서 Cookie의 Lifetime 관리방법을 설명했습니다.

### F# 소식
* Build your own chatbot therapist in F# : Evalina Gabasova가 F#을 이용한 chatbot 개발 방법을 설명했습니다.
* A gentle introduction to programming networked services on linux : Henrik Feldt가 linux의 F#개발 환경 구축 가이드를 공유했습니다.
* RdKafka for F# Microservices : Jonathan Leaver가 F# Microservices용 RdKafka 를 소개했습니다.
* Asterik Game in F# and WPF : Mark Heath가 F#과 WPF를 이용한 개임 개발 방법을 설명했습니다.
* How F# delighted this newbie while experimenting with distributed systems : Hussam Abu-Libdeh가 분산 시스템 개발환경에서의 F# 장점을 설명했습니다.

### Xamarin 소식
* Bindable Native Views in XAML – With Commands!?! : Matthew Soucoup가 XAML에서 Bindable Native Views 활용하기 : "Command" 편을 게시했습니다.
* Xamarin Alpha Preview 4: Cycle 9 & Preview 2: Visual Studio for Mac :Adrian Murphy가  Visual Studio for Mac을 소개했습니다.
* Join us for the Xamarin Dev Days Live Virtual Event :James Montemagno가 Xamarin Dev Days Live Virtual Event 온라인 세미나 소식을 공유했습니다.
* Webinar Recording | Get Started with Xamarin and Microsoft Azure : Courtney Witmer가 웨비나  "Xamarin과 Azure 활용하기"를 공유했습니다.
* Optimizing Android Apps for Multi-Window Mode : James Montemagno가 모바일 어플이 안드로이드의 멀티 윈도우에 최적화 되어 동작할 수 있도록 하는방법을 설명했습니다
* Google Awareness API for Android: Query and React to Signals : James Montemagno가 Google 의 Awareness API for Android 서비스의 기본적인 활용법을 소개했습니다.
* Vehicle Smart Solves an Everyday Problem with Five-Star Xamarin Apps : Lacey Butler가 영국의 차량 모바일 어플 개발회사 "Vehicle Smart"의 성공 사례를 소개했습니다.
* Xamarin + Universal Windows Platform & Introducing Visual Studio for Mac : Xamarin에서 Xamarin.Forms 가 기존에 지원하던 플랫폼에 추가적으로 UWP(Universal Windows Platform)환경을 지원한다는 소식(링크)과 Visual Studio for Mac을 소개(링크)했습니다.
* The Xamarin Show 12: MVVM Light and Xamarin with Laurent Bugnion : James Montemagno의 "Xamarin Show 12 : MVVM Light and Xamarin" 편을 소개했습니다.
* Setting Up Android x86 HAXM Emulators : James Montemagno가 안드로이드 x86 HAXM 에뮬레이터 설정방법을 공유하였습니다.
* Xamarin.Android – Where Do These Permissions Come From? : Jon Douglas가 안드로이드 권한 관련 파일인 "AndroidManifest.xml"의 병합과정을 설명했습니다.
* Introduction To Xamarin Workbooks : Adam Pedley이 Xamarin Workbooks를 소개했습니다.
* Best Practices For Animated Progress Indicators : Nick Babich가 에니메이션 작업 상태 표시기(Animated Progress Indicators) 디자인 가이드를 공유했습니다
* Putting Aid on the Map with Help from Urban Refuge : Jerry Nixon이 "Urban Refuge" 단체에서 개발중인 난민을 위한 모바일 어플의 개발배경과 과정을 공유했습니다.
* X-Platform Development With Xamarin.Forms & F# : Phillip Trelford가 크로스플렛폼 개발환경으로서 Xamarin.Forms 과 F# 의 조합을 이용한 IDTechEx의 성공 사례를 소개했습니다.
* Xamarin.iOS – How to get the mime type of a file : Thomas Lebrun이 Xamarin.iOS에서 파일의 mime type을 얻는 방법을 설명했습니다.
* Xamarin.iOS – How to pre-calculate the size of a text, depending of its content : Thomas Lebrun이 Xamarin.iOS 에서 텍스트의 영역을 미리 계산할 수 있는 방법을 소개했습니다.
* Xamarin Forms: Customizing the Synfusion Kanban Control is as simple as 1-2-3 : Malcolm Jack이 Synfusion의 Kanban Control의 사용 가이드를 공유했습니다.
* Caliburn.Micro 3.0.2 released : Caliburn.Micro Team이 Caliburn.Micro 3.0.2의 릴리즈 소식을 공유했습니다.

### Azure 소식
* Understanding the Azure App Service Editor : Ken Cenerelli가 Azure App Service Editor의 활용법을 소개했습니다.

### Data 소식
* Integration Testing with Entity Framework Core (video) : ASP.NET Monsters에서 Entity Framework Core 환경의 통합테스트 진행 방법을 설명했습니다.

### Games 소식
* Judging Ludum Dare 37 : PoV가 Ludum Dare 37회 게임 개발 대회의 평가및 투표 정보를 공유했습니다.
* Unity 5.6 Beta is Now Available : Alex Lian이 Unity 5.6 Beta 릴리즈 소식을 공유했습니다.
* Unity 5.6 Wraps Unity 5 Cycle, What’s Next In 2018 : Brett Bibby가 Unity 5.6이 5.x 버전의 마지막 업데이트이며 2017년에는 새로운 메이저 버전이 선보일것이라는 소식을 공유했습니다.
* Asynchronous Serial Communication : Alan Zucconi가 Unity 에서 시리얼 포트로 비동기 통신하는 방법을 설명했습니다
* How to integrate Arduino with Unity : Alan Zucconi가 시리얼 포트를 이용하여 Unity 와 Arduino가 서로 통신하는 방법을 설명했습니다. 
* 13 More Tips for Making a Fun Platformer : Diorgo Jonkers가 Platformer 스타일의 게임 구현시 알아두면 도움이 되는 13가지 팁을 공유했습니다.
* Designing a deep strategy game with no random elements : Dani Garcia가 전략 시뮬레이션 게임의 디자인 과정을 설명했습니다.
* Free Lowpoly Nature Pack Vol.3 : QuaterniusDev에서 무료 3D 모델 "Lowpoly Nature Pack Vol.3"를 공유했습니다.


// 전무님 소개
