주간닷넷 2016년 11월 08일

### On .NET 소식
[지난 주 On .NET]()에는 Mei-Chin Tsai 그리고 Jan Kotas와 함께 CoreRT와 .NET Native에 대해서 이야기 나누었습니다. 

이번 주 On .NET 쇼는 예정되어있지 않습니다. 하지만 11/07 부터 진행된  MVP 서밋에 참여한 전세계 MVP들중 여러분과 10~15분정도 짤막한 인터뷰를 진행할 예정입니다.

### 금주의 패키지  -  Enums.NET
Enums.NET은  .NET 열거형 타입 관련 고성능 유틸리티 라이브러리입니다. 열거형 멤버의 이름, 값, 어트리뷰트 등을 캐싱하고  이와 관련된 다양한 C# 확장 메서드(extension method)를 제공합니다. NuGet Package로 제공되는 오픈소스는 .NET Framework 2.0+ 과 .NET Standard 1.0+을 지원합니다.

// 코드

### 금주의 게임 - Ylands
게임 Ylands는 게임 마인크래프트 같이 사용자가 자신만의 맵과 시나리오를 생성할 수 있으며 이를 쉽게 구성하도록 도와주는 툴을 제공해주는 low-poly 샌드박스 게임입니다. 플레이어가 Ylands 게임을 시작 하면 플레이어는 특정 섬을 선택한 후 스스로 맵을 편집/수정하면서 자신만의 모험을 즐길 수 있습니다. 시나리오 편집기를 이용하여 플레이어는 모든 상황을 연출하는 것이 가능합니다 - 말하는 상자, 공간이동, 적들에게 포위당해서 위기에 빠진 성, 등 여러가지 상황이 연출가능하며 나아가 여러 동료와 모험을 즐길수있는 대형 맵의 시나리오의 설정도 가능합니다

//그림

Ylands(링크)는 현재  Bohemia Interactive(링크)에서 Unity(링크)와 C#(링크)을 이용하여 개발되고 있으며 현재는 윈도우용 초기 알파버전까지 완성되었으며 무료 체험판(링크)을 통해서 체험해 보실 수 있습니다.


### 금주의 어플 - Markdown Monster
블로거 Rick Strahl는 블로깅만 자주하는것이 아니라 실제 쓸만한 툴도 자주 만듭니다. 이번주 그는 자신이 구현한 Markdown Monster라는 마크다운 편집기를 자신의 블로그에 소개했습니다. Markdown Monster는 WPF 어플리케이션입니다.

//그림

### .NET 소식
* C# NumberFormat Sections : Rick Strahl이 숫자 포맷에 대해서 설명했습니다.
* The “Internet of Stranger Things” Wall, Part 1 – Introduction and Remote Wiring : Pete Brown이  “Internet of Stranger Things” - 소개와 무선기능에 대해서 설명했습니다.
* Custom Project File for Building Nuget Packages : Robb Schiefer가 프로젝트 파일에서 Nuget Packages 관련 사용자 정의 빌드 파일에 대해서 설명했습니다.
* Why an HTML5-Compliant .NET is Important : Mike-EEE가 HTML5 스팩을 따르는 .NET의 중요성을 설명했습니다.
* Paket-like NuGet with MSBuild : Brice Lambson이 Paket과 비슷한 구조로 NuGet 레퍼런스를 구성하는 방법을 설명했습니다.
* .NET Standard based Windows Service support for .NET : Martin Andreas Ullrich가  full (desktop) .NET Framework 어셈블리의 참조없이도 Windows Service 기능을 사용할 수 있도록 지원하는 .NET Standard 라이브러리를 소개했습니다.
* Mapping to Getter-only Properties with EF Core : Christian Nagel이 EF Core에서 Getter만 있는 속성(읽기전용 속성)을 Mapping 하는 방법을 공유했습니다.
* .NET Document Databases with Marten : Jason Roberts가 .NET의 Document Database와 같은 NoSQL 엔진인 Marten 라이브러리를 소개 했습니다
* Learn .NET Core : example (or micro example) – Part II : Jon Hilton이 .NET Core 를 이해하는데 도움을 줄 수 있는 예제들을 공유했습니다
* High performance field clobbering and HTTP benchmark and pipelining : Ayende Rahien이 동적으로 필드의 값을 얻고자 할 때 사용할 수 있는 가장 빠른 방법(링크)과 웹사이트 HTTP 밴치마킹시 알고 있어야 하는 파이프라인의 이해(링크)에 대해서 설명했습니다.
* ASP.NET Core RESTful Web API versioning made easy and The mystery of dotnet watch and ‘Microsoft.NETCore.App’, version ‘1.1.0-preview1-001100-00’ was not found : Scott Hanselman이 ASP.NET Core Web API의 버전의 구현(링크)과  version ‘1.1.0-preview1-001100-00’ was not found 예외발생 사항시 대처방법(링크)에 대해서 설명했습니다.
* Install .NET Core on Mint 18 or Elementary OS : Hrvoje Hudoletnjak이  Mint 18와 Elementary OS에서 .NET Core 의 설치방법을 설명했습니다.
* Lazy async initialization for expiring objects : Filip W가 객체를 Lazy initialization 형태로 초기화하는경우 비동기 함수를 사용할 수 있는 방법과 이 기능을 포함한 AsyncExpiringLazy<T> 타입의 구현을 설명했습니다
* Streaming API in Seq 3.4 : Nicholas Blumhardt가  structured logging 라이브러리인 Seq의 로깅정보를 실시간으로 확인 가능한 Streaming API 를 소개했습니다.
* .NET Core + RabbitMQ = RawRabbit : Piotr Gankiewicz가 NET Core에서 , RabbitMQ을 이용하여 RawRabbit 라이브러리를 활용하는 방법을 설명했습니다



### ASP.NET 소식
* Bearer Token Authentication in ASP.NET Core : Mike Rousos가 ASP.NET Core에서 JWT bearer token의 사용방법을 설명했습니다.
* ASP.NET Core Budgeting App Series (Part 5 FINALE) – A basic UI with React, enabling CORS, and my opinion of ASP.NET Core so far : Joe Petrakovich가 ASP.NET Core 버전 경비처리 어플 구현 시리즈(Part 5) - React를 이용한 UI 구현 및 cross-origin requests 를 가능하게 하는 설정과 기타 관련정보 등을 설명했습니다. 
* Adding Cache-Control headers to Static Files in ASP.NET Core : Andrew Lock이 ASP.NET Core에서 정적 파일의 캐싱설정과 이에 관련된 헤더 정보를 설명했습니다.
* ASP.NET Core: Using view injection : Gunnar Peipman이 view injection을 설명했습니다.
* Step by step: Scale ASP.NET Core with Docker Swarm : Carlos Mendible이 Docker를 이용한  ASP.NET Core 성능확장방법을 설명했습니다.


### F# 소식
* Join the F# Slack Team : F# Slack Team이 생성되었습니다
* LINQPad Dump for F# : Mark Heath이  F#용 LINQPad의 Dump 기능을 소개했습니다.
* F# and .NET Core with SDK Development Group #1 
* Case Study: Writing Microservices with F# : Rachel Reese가 F#으로 Microservices를 구현하는 방법을 설명했습니다.
* TDD Kata in F#/C# using FsCheck : Michał Niegrzybowski가 FsCheck을 이용한  F#,C#의 TDD 활용법을 소개했습니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 8 Service Release 1 RC Builds and Xamarin Preview: iOS Simulator (For Windows) update 6 : Adrian Murphy가 Xamarin 베타 버전 Cycle 8 Service Release 1RC Builds(링크)와 Xamarin Preview:iOS Simulator update 6(링크)를 소개했습니다
* Xamarin Developer Events in November : Jayme Singleton이 11월 Xamarin 개발 행사 일정을 공유했습니다.
* Live Webinar | Scale Your Mobile Quality: Industry Benchmarks and Testing Best Practices : Courtney Witmer가 에비나 "산업 밴치마크와 테스트 성공 사례"를 공유했습니다.
* Mobile Leaders Podcast | Productivity and Delight in Enterprise Apps with Josh Clark of Big Medium : Anusha Sethuraman이 Big Medium 창립자 Josh Clark와 함께 "산업용 어플의 생산성과 보람"에 대해서 팟케스팅을 진행했습니다
* Adding the Microsoft Graph to Your Xamarin.Forms Mobile Apps : Mayur Tendulkar가 Xamarin.Forms 어플에서 마이크로소프트의 통합 API End Point인 Microsoft Graph을 사용하는 방법을 설명했습니다.
* Xamarin Podcast: What’s New in Xamarin.Forms 2.3.3 : Pierce Boggan이 Xamarin.Forms 버전 2.3.3의 새로운 사항에 대해서 팟케스트를 진행했습니다.
* Say Hello to Siri with SiriKit : Mike James가 SiriKit 을 이용한 Siri 기능의 활용법을 공유했습니다.
* The Xamarin Show: Grab a Snack Pack! : Cody Beyer가 Xamarin Show의 간략 정리 버전(Snack Pack) 을 공유했습니다.
* The Xamarin Show 8: Microsoft Graph with Simon Jäger and Cross Platform Photos with Media Plugin : James Montemagno가 Simon Jäger와 함께 진행한 Xamarin Show 8:  Microsoft Graph의 사용(링크)과 Media Plugin을 사용한 Cross Platform Photos(링크)을 소개했습니다.
* Operation Separation, Introduction to UrhoSharp in Xamarin Forms, and UrhoSharp 3D Moving Object : Adam Pedley가 Operation Separation(링크), Xamarin Forms에서 UrhoSharp 활용(링크),  UrhoSharp 3D 객체(링크)를 설명했습니다 .
* Xamarin Quick Tip – Changing the UISegmentedControl Text Color and Xamarin Quick Tip : Identifying if a device is an iPad or an iPhone using UserInterfaceIdiom : Carey Payette가 UISegmentedControl 의 텍스트 색상 변경방법(링크). iPad혹은 UserInterfaceIdiom을 사용하는 iPhone디바이스로 부터 ID 정보 얻는 방법(링크)을 설명했습니다.
* The Golden Rules Of Bottom Navigation Design : Nick Babich가 Bottom Navigation Design의 중요한 몇가지 규칙을 소개했습니다.
* Be more awesome with MFractor for Xamarin Studio : Michael Ridland이 Xamarin Studio의 편집기능 향상 Plugin MFractor를 소개했습니다
* ReactiveUI Goodies – Merge : Jan Hannemann이 ReactiveUI - Merge 를 설명했습니다.
* Announcing Azure Storage Client Library GA for Xamarin : Windows Azure Storage에서 Xamarin용 Azure Storage Client Library GA를 발표했습니다.
* Prism for Xamarin.Forms 6.3 Preview with Improved Template Pack : Brian Lagunas가 Xamarin.Forms용 Prism 6.3 Preview의 향상된 Template Pack을 소개했습니다.
* Banish Compiler Directives From Shared Projects! : Matthew Soucoup이 공통프로젝트에서 컴파일러시 컴파일 지시자를 무시하는 방법을 설명했습니다.

### Azure 소식
* Using Azure DocumentDB and ASP.NET Core for extreme NoSQL performance : Matías Quaranta가 Azure DocumentDB와 ASP.NET Core를 활용한 고성능 NoSQL 서버구현에 대해 설명했습니다.


### Games 소식
* Unite 2016 Keynote Wrap Up: News on Graphics, Platforms, VR and More : Alice Liang가 Unite 2016 행사 키노트 내용을 정리했습니다.
* Unity – 2D Movement (Part 6c) – Animation : Aim (video) : Pixel Make에서 Unity – 2D 이동 (Part 6c)- 애니메이션을 설명했습니다.
* [Unity 5] Tutorial: How to make a compass in unity (video) : Gamad가 unity 에서 나침반 기능구현을 설명했습니다
* Mono game drawing tutorial (video) : Tj Bomba가 "모노 게임 그리기"를 설명했습니다.
* The challenges of porting XCOM 2 to consoles by Alan Bradley가 XCOM 2게임을 콘솔용으로 포팅한 과정을 공유했습니다.
* 5 Most Expensive Game Localization Mistakes : Damien Yoccoz가 게임 지역화 과정중 꼭 피해야 하는 5가지 잘못된 사례를 설명했습니다.

// 전무님 소개
