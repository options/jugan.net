주간닷넷 2016년 10월 18일

### On .NET 소식
[지난 주 On .NET]()에는  On .NET Show 가 진행되지 못했습니다. 

이번주에는 Rowan Miller와 함께 .NET과 Entity Framework Core 1.1 에 대해서 얘기를 나누어볼 계획입니다.

### 금주의 패키지  -  Bond
Bond는  데이터를 직열화/역직열화 하기위한 검증된 바이너리 포멧 라이브러리로서 구글의 Google’s Protocol Buffer와 유사한 라이브러리입니다. Bond 라이브러리는 Linux, macOS, Windows에서 동작하며 C++, C#, Python 등의 언어를 지원합니다.
개발자가 Bond 을 사용하기 위해서는  IDL과 비슷한 형식으로 스키마를 먼저 정의해야합니다.

// 코드

그런후 이 스키마를 툴을 통하여 C#코드로 제네레이션합니다.

// 코드

이렇게 생성된 타입을 초기화하고 직열화, 역직열화 하기위해서 개발자는 제너레이션된 라이브러리의 C# 코드를 사용할 수 있습니다.

// 코드

### 금주의 게임 - The Gallery – Episode 1: Call of the Starseed
게임 The Gallery – Episode 1: Call of the Starseed는 4개의 에피소드로 나누어진 판타지 어드벤처 VR게임 입니다. 게임 플레이어는 게임속 주인공의 실종된 여동생 멜리스을 찾는 과정에서 신비하고 기이한 게임 캐릭터들과 접하면서 모험을 펼치게 됩니다. The Gallery – Episode 1은 방  크기 정도의 범위에서 안고, 서고, 웅크리고, 기는 등의 동작을 지원하는 full-room scale VR 기능을 포함합니다

//그림

The Gallery – Episode 1: Call of the Starseed(링크)은  Unity(링크)와 C#(링크)을 이용하여  Cloudhead Games(링크)에서 제작 했으며 Steam(링크)을 통해서 HTC Vive에서 플레이하실수 있으며 12월에는 Oculus Home을 통해서 Oculus Touch에서도 즐기실수있습니다.

### .NET 소식
*  .NET Framework Monthly Rollups Explained and .NET Framework Monthly Rollup: October 2016 : Stacey Haffner가 앞으로 계속 발행예정인 NET Framework 월간 업데이트의 정보를 설명(링크)했으며 이번달(10월) NET Framework 월간 업데이트를(링크) 공유했습니다 
*  Learning .NET Core by example : Jon Hilton이 .NET Core를 쉽게 이해할 수 있는 예제와 튜토리얼을 소개 했습니다.
*  Parallel Test Execution : Pratap Lakshman이 Parallel Test Execution 에 대해서 설명했습니다.
*  Porting Apache Avro into .NET Core : Welly Tambunan이 Apache 버전의 Avro를 .NET Core버전으로 전환한 경험을 공유했습니다.
*  Timing the time it takes to parse time part 1 and part 2 : Ayende Rahien이 DateTime 데이터 형식을 효과적으로 파싱하는 방법을 공유했습니다.
*  Microsoft IIS Administration Preview : IIS 관리 API 라이브러리인 Microsoft IIS Administration API 의 프리뷰 버전이 소개되었습니다.
*  Deal with time dependencies in Tests : Carlos Mendible이 테스트 시점(시간)에 따라서 결과가 바뀔수 있는 서비스의 정확한 테스트 접근법을 설명했습니다.
*  Metric.NET: dealing with measurement units : Ivan Milutinović이 단위 변환 오픈소스 라이브러리 Metric.NET를 소개했습니다.
*  Stuntman now works with .NET Core : .개발시점에 인증된 사용자 정보를 자유롭게 바꿀수있는 사용자 인증 라이브러리 Stuntman 이 NET Core을 지원한다는 정보와 함께 소개되었습니다.
*  MediatR Pipeline Examples : Jimmy Bogard가 Mediator pattern 라이브러리 MediatR을 이용한 예제를 소개했습니다.
*  Using Core class library from .NET 4.6 project : Hrvoje Hudoletnjak가 일반 .NET 4.6 project 에서 Core 용 클레스 라이브러리를 사용하는 방법을 소개했습니다.
*  Calling UWP APIs from a Desktop Application : Mike Taulty가 Desktop Application에서 UWP API의 호출 방법을 공유했습니다.


### ASP.NET 소식
* Exploring ASP.NET Core with Docker in both Linux and Windows Containers : Scott Hanselman이 Linux와 Window용 Containers와  ASP.NET Core의 도커 시스템을 설명했습니다.
* Custom authorization policies and requirements in ASP.NET Core : Andrew Lock이 ASP.NET Core의 인증 정책과 이에 필요한사항을 설명했습니다.
* Debugging into ASP.NET Core Source : Steve Gordon이 ASP.NET Core 소스 디버깅 방법을 공유했습니다.
* Localization & Routing in ASP.NET Core 1.0 : Hisham Bin Ateya가 ASP.NET Core 1.0에서 지역화(Localization)와 라우팅(Routing)에 대해서 설명했습니다.
* ASP.NET Core and the Enterprise: Part 1 Frameworks : K. Scott Allen이 "ASP.NET Core과 기업 어플리케이션: 파트 1 프레임워크"에 대해서 설명했습니다.

### F# 소식
* Using F# on Azure : Sylvan Clebsch가 Azure 환경에서  F#을 사용하는 방법을 소개했습니다.
* Getting Started with F# in Visual Studio Code with Ionide : Phillip Carter가 Visual Studio Code에서 Ionide 을 이용한 F# 사용 방법을 공유했습니다.
* Using F# with .NET Core : Ody Mbegbu가 .NET Core 환경의 F# 사용방법을 소개했습니다.
* ASP.NET Identity in an F# Web Application, Part One : Ernest Pazera가 F#의 웹어플리케이션에서 ASP.NET Identity 를 설명했습니다.
* Prefer Records of Functions to Interfaces : Matthew Doig가 F#에서 Interface의 활용에 대해서 설명했습니다.

### Xamarin 소식
* Xamarin Preview: Xamarin Profiler 0.38.0 : Adrian Murphy가 Xamarin Profiler 프리뷰 버전 0.38.0을 소개했습니다.
* Xamarin Dev Days Continue to Roll Out! : Jayme Singleton이 업데이트된  Xamarin Dev Days 개발 행사 일정을 공유했습니다.
* Mobile Leaders Podcast | Enterprise Mobility Trends with Maribel Lopez : Anusha Sethuraman이 모바일 전문 연구기관 Lopez Research의 창립자인 Maribel Lopez와 기업 모빌리티 트랜드에 대해서 팟케스트를 진행했습니다.
* Live Webinar | Xamarin University Presents: Introduction to Xamarin with Visual Studio : Courtney Witmer가 Xamarin과 Visual Studio에 대해서 웨비나(웹 세미나)를 진행했습니다.
* Understanding Android’s Doze Functionality and The Xamarin Show 6: User Interface Automation with Charles Wang : James Montemagno가 Android의 절전 기능의 설명(링크)과 Xamarin Show 6 : 사용자 인터페이스(링크)를  공유했습니다.
* Bringing Platform-Specific Functionality to Xamarin.Forms Apps : Pierce Boggan이 모바일 플렛폼 고유의 기능을 Xamarin.Forms Apps에서 사용하는 방법을 공유했습니다.
* Designing Card-Based User Interfaces : Nick Babich가 카드-뷰 형태의 사용자 인터페이스 디자인을 설명했습니다.
* Creating A Splash Screen In Xamarin Forms and Misuses Of MessagingCenter : Adam Pedley가 Xamarin Forms에서 Splash Screen 의 구현방법과(링크) MessagingCenter의 잘못된 사용예를 설명(링크)했습니다
* ReactiveUI Goodies – Search and ReactiveUI Goodies – ReactiveList : Jan Hannemann이 오픈소스 UI 프레임워크 ReactiveUI를 이용한 Search 기능의 구현(링크)과 ObservableCollection의 일종인 ReactiveList를 설명(링크)했습니다.
* Semantic Versioning of Xamarin Applications : Geoffrey Huntley가 Xamarin 어플리케이션의 효과적인 버전관리를 위한 버전 넘버 의미를 설명했습니다.
* Templates and Extensions for Xamarin & Mono : Terrence Dorsey가 Xamarin, Mono 환경에서 사용할수있는 여러 컴포넌트와 확장 기능에 대해설명했습니다.

### Azure 소식
* Simpler Azure Management Libraries for .NET : Asir Selvasingh가 Azure 관리 라이브러리 "Simpler Azure Management Libraries for .NET"의 개발자 프리뷰 버전을 소개했습니다.
* Hosting .NET Core Services on Service Fabric : Vaijanath Angadihiremath가 Service Fabric에서 .NET Core Services 를 호스트하는 방법을 공유했습니다.
* Running Worker Roles with Docker in .NET Core : Pepijn Schoen이 .NET Core의 도커환경에서 Worker Roles을 실행/관리하는 방법을 설명했습니다
* ASP.NET Core 1.0 – Configure Application Insights : Joao Sousa가 ASP.NET Core 1.0 에서 Application Insights기능 설정 방법을 설명했습니다.
* App Service Mobile Apps .NET Client SDK 3.0.1 release : Mimi Xu가 App Service Mobile Apps .NET Client SDK 3.0.1 버전을 소개했습니다
* Sending a Regular SMS with Azure Functions and Twilio : Jason Roberts가 Azure Functions과 Twilio 이용하여 일반 단문 메시지를 전송하는 방법을 설명했습니다.


### Games 소식
* Curated #UnityTips No. 17 by DevDog October 2016 : DevDog가 Unity 개발에 도움이 될수있는 17번째 Tip을 공유했습니다.
* Unity 5 Tutorial: How to debug raycasts (video) : Gamad에서 raycasts를 디버깅하는 방법을 설명했습니다.
* Using InputFields with C# Unity 5.4 (video) : Learn To Be Indie에서 C# Unity 5.4 의 입력값에 대해서 설명했습니다.

// 전무님 소개
