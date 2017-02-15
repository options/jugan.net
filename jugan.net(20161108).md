주간닷넷 2016년 11월 08일

### On .NET 소식
[지난 주 On .NET]( https://channel9.msdn.com/Shows/On-NET/Mei-Chin-Tsai--Jan-Kotas-CoreRT--NET-Native)에는 Mei-Chin Tsai와 Jan Kotas가 CoreRT와 .NET Native에 관해 이야기 나누었습니다.

https://sec.ch9.ms/ch9/2543/c0ab6118-b52e-4108-86f3-c4908a122543/onnet20161103meichinjan_high.mp4

이번 주 On .NET에서는 2016년 11월 개최된 MVP summit에 참가한 [전세계 MVP]( https://mvp.microsoft.com/en-us)를 대상으로 인터뷰를 진행할 예정입니다.

### 금주의 패키지 - Enums.NET
[Enums.NET]( https://github.com/TylerBrinkley/Enums.NET)은 .NET 열거형 타입 관련 고성능 유틸리티 라이브러리입니다. 열거형 멤버의 이름, 값, 어트리뷰트 등을 캐싱하고 이와 관련된 다양한 C# 확장 메서드(extension method)를 제공합니다. 
[NuGet Package]( https://www.nuget.org/packages/Enums.NET/)를 통해 사용하실 수 있으며, .NET Framework 2.0+ 그리고 .NET Standard 1.0+와 호환됩니다.

// 코드
<script src="https://gist.github.com/bleroy/0801db77e8dac1ac20e7f3459aed33d1.js"></script>

https://github.com/TylerBrinkley/Enums.NET/raw/master/Doc/performance.png
### 금주의 게임 - Ylands
[Ylands]( https://ylands.com/)는 마인크래프트와 비슷하게 플레이어가 게임 속 다양한 툴로 자신만의 맵과 시나리오를 생성할 수 있는 로우폴리곤 생존 게임입니다.
처음 게임을 시작하면 플레이어는 특정 섬을 선택한 후, 자유롭게 지형을 편집/수정할 수 있습니다. 그 다음 시나리오 편집기로 원하는 모든 스토리를 연출하여 모험을 즐길 수 있습니다. 말하는 상자, 공간이동, 적들에게 둘러싸여 위기에 빠진 성 등 여러가지 스토리로 연출이 가능하며, 나아가 여러 동료들과 함께 모험을 즐길 수 있는 시나리오도 설정이 가능합니다

//그림
https://cloud.githubusercontent.com/assets/4108756/20107931/23449a72-a58f-11e6-9078-b4db8ad09204.jpg

[Ylands]( https://ylands.com/)는 현재[ Bohemia Interactive]( https://www.bistudio.com/)에서 [Unity]( https://unity3d.com/)와 [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 개발되고 있으며 [윈도우용 초기 알파 버전]( https://store.bistudio.com/products/ylands)을 무료 체험판으로 체험해 보실 수 있습니다.


### 금주의 어플 - Markdown Monster
금주엔 블로거 Rick Strahl이 구현한 마크다운 편집기 [Markdown Monster]( https://weblog.west-wind.com/posts/2016/Nov/04/Introducing-Markdown-Monster-a-new-Markdown-Editor)에 관해 소개합니다. 

//그림
https://msdnshared.blob.core.windows.net/media/2016/11/markdownmonster_thumb.png

### .NET 소식
* C# NumberFormat Sections : Rick Strahl이 C# 숫자 포맷에 관해 설명합니다.
* The “Internet of Stranger Things” Wall, Part 1 – Introduction and Remote Wiring : Pete Brown이 무선 기능에 관해 설명합니다.
* Custom Project File for Building Nuget Packages : Robb Schiefer가 NuGet Package 프로젝트를 위해 어떻게 사용자 지정 파일을 생성하는지에 관해 소개합니다.
* Why an HTML5-Compliant .NET is Important : Mike-EEE가 HTML5-Compliant .NET의 중요성을 설명합니다.
* Paket-like NuGet with MSBuild : Brice Lambson이 Paket과 비슷한 구조로 NuGet 레퍼런스를 구성하는 방법에 관해 설명합니다.
* .NET Standard based Windows Service support for .NET : Martin Andreas Ullrich가 full (desktop) .NET Framework 어셈블리의 참조 없이도 Windows Service 기능을 사용할 수 있도록 지원하는 .NET Standard 라이브러리를 소개합니다.
* Mapping to Getter-only Properties with EF Core : Christian Nagel이 EF Core에서 읽기 전용 속성을 Mapping 하는 방법을 공유했습니다.
* .NET Document Databases with Marten : Jason Roberts가 .NET의 Document Database와 같은 NoSQL의 엔진인 Marten 라이브러리를 소개합니다.
* Learn .NET Core : example (or micro example) – Part II : Jon Hilton이 .NET Core 를 이해하는데 도움이 될 만한 예제들을 공유했습니다
* High performance field clobbering and HTTP benchmark and pipelining : Ayende Rahien이 동적으로 필드의 값을 얻고자 할 때, 사용할 수 있는 가장 빠른 방법과 웹사이트 HTTP를 밴치마킹할때 알아야 할 파이프라인을 설명합니다.
* ASP.NET Core RESTful Web API versioning made easy and The mystery of dotnet watch and ‘Microsoft.NETCore.App’, version ‘1.1.0-preview1-001100-00’ was not found : Scott Hanselman이 ASP.NET Core Web API의 버전의 구현과 version ‘1.1.0-preview1-001100-00’ was not found 예외발생 사항시 대처 방법에 관해 설명합니다.
* Install .NET Core on Mint 18 or Elementary OS : Hrvoje Hudoletnjak이 Mint 18와 Elementary OS에 .NET Core를 설치하는 방법을 설명합니다.
* Lazy async initialization for expiring objects : Filip W가 객체를 Lazy initialization 형태로 초기화하는 경우, 비동기 함수를 사용할 수 있는 방법과 이 기능을 포함한 AsyncExpiringLazy<T> 타입 구현 방법을 설명합니다.
* Streaming API in Seq 3.4 : Nicholas Blumhardt가 structured logging 라이브러리인 Seq의 로깅정보를 실시간으로 확인 가능한 Streaming API를 소개합니다.
* .NET Core + RabbitMQ = RawRabbit : Piotr Gankiewicz가 NET Core에서 RabbitMQ을 이용하여 RawRabbit 라이브러리를 활용하는 방법에 관해 설명합니다.

### ASP.NET 소식
* Bearer Token Authentication in ASP.NET Core : Mike Rousos가 ASP.NET Core에서 JWT bearer token 사용 방법에 관해 설명합니다.
* ASP.NET Core Budgeting App Series (Part 5 FINALE) – A basic UI with React, enabling CORS, and my opinion of ASP.NET Core so far : Joe Petrakovich가 ASP.NET Core 버전 경비 처리 애플리케이션 구현 시리즈(Part 5)에서 
Joe Petrakovich가 ASP.NET Core 버전 경비처리 애플리케이션 구현하기 시리즈에서 React를 이용한 UI 구현 및 cross-origin requests를 가능토록 하는 설정 방법과 기타 관련 정보 등을 소개합니다.
* Adding Cache-Control headers to Static Files in ASP.NET Core : Andrew Lock이 ASP.NET Core에서 정적 파일의 캐싱 설정 방법과 이에 관련된 헤더 정보를 공유하였습니다.
* ASP.NET Core: Using view injection : Gunnar Peipman이 view injection에 관해 설명합니다.
* Step by step: Scale ASP.NET Core with Docker Swarm : Carlos Mendible이 Docker를 이용한 ASP.NET Core 성능 확장 방법을 설명합니다.


### F# 소식
* Join the F# Slack Team : F# Slack Team이 생성되었습니다
* LINQPad Dump for F# : Mark Heath이 F#용 LINQPad의 Dump 기능에 관해 소개합니다.
* F# and .NET Core with SDK Development Group #1 
* Case Study : Writing Microservices with F# : Rachel Reese가 F#으로 Microservices를 구현하는 방법을 소개합니다.
* TDD Kata in F# / C# using FsCheck : Michał Niegrzybowski가 FsCheck을 이용한 F#, C#의 TDD 활용 방법을 소개합니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 8 Service Release 1 RC Builds and Xamarin Preview: iOS Simulator (For Windows) update 6 : Adrian Murphy가 Xamarin 베타 버전 Cycle 8 Service Release 1RC Builds와 Xamarin Preview:iOS Simulator update 6를 소개했습니다
* Xamarin Developer Events in November : Jayme Singleton이 11월 Xamarin 행사 일정을 공유 했습니다.
* Live Webinar | Scale Your Mobile Quality: Industry Benchmarks and Testing Best Practices : Courtney Witmer가 "산업 밴치마크와 테스트 성공 사례" 주제의 웨비나를 공유했습니다.
* Mobile Leaders Podcast | Productivity and Delight in Enterprise Apps with Josh Clark of Big Medium : Anusha Sethuraman이 Big Medium 창립자 Josh Clark와 함께 "산업용 애플리케이션 생산성과 즐거움"을 주제로 팟캐스트를 진행했습니다.
* Adding the Microsoft Graph to Your Xamarin.Forms Mobile Apps : Mayur Tendulkar가 Xamarin.Forms 애플리케이션에서 마이크로소프트의 통합 API End Point인 Microsoft Graph을 사용하는 방법을 소개합니다.
* Xamarin Podcast: What’s New in Xamarin.Forms 2.3.3 : Pierce Boggan이 Xamarin.Forms 버전 2.3.3의 업데이트 사항을 주제로 팟캐스트를 진행했습니다.
* Say Hello to Siri with SiriKit : Mike James가 SiriKit을 이용한 Siri 기능 활용 방법을 소개합니다.
* The Xamarin Show: Grab a Snack Pack! : Cody Beyer가 Xamarin Show의 요약 정리 버전(Snack Pack)을 공유했습니다.
* The Xamarin Show 8: Microsoft Graph with Simon Jäger and Cross Platform Photos with Media Plugin : Xamarin Show 8에서 먼저 Simon Jäger가 Microsoft Graph를 소개하고 이어서 James Montemagno가 Cross Platform Photos과 Media Plugin에 관해 소개합니다.
* Operation Separation, Introduction to UrhoSharp in Xamarin Forms, and UrhoSharp 3D Moving Object : Adam Pedley가 Operation Separation에 대한 소개를 시작으로 Xamarin Forms에서 UrhoSharp을 사용해보고 UrhoSharp 3D객체에 대해 설명합니다.
 .
* Xamarin Quick Tip – Changing the UI Segmented Control Text Color and Xamarin Quick Tip : Identifying if a device is an iPad or an iPhone using UserInterfaceIdiom : Carey Payette가 Xamarin UI Segmented Control의 텍스트 색상 변경 팁 소개를 시작으로 Apple 디바이스로 부터 ID 정보 얻는 방법을 소개합니다.
* The Golden Rules Of Bottom Navigation Design : Nick Babich가 Bottom Navigation Design의 몇가지 중요한 규칙을 소개했습니다.
* Be more awesome with MFractor for Xamarin Studio : Michael Ridland이 Xamarin Studio에서 편집 기능이 향상된 Plugin MFractor에 대해 소개합니다.
* ReactiveUI Goodies – Merge : Jan Hannemann이 ReactiveUI - Merge에 관해 설명합니다.
* Announcing Azure Storage Client Library GA for Xamarin : Windows Azure Storage에서 Xamarin용 Azure Storage Client Library GA를 발표했습니다.
* Prism for Xamarin.Forms 6.3 Preview with Improved Template Pack : Brian Lagunas가 Xamarin.Forms용 Prism 6.3 Preview의 업그레이드된 Template Pack에 관해 소개했습니다.
* Banish Compiler Directives From Shared Projects! : Matthew Soucoup이 공통 프로젝트에서 컴파일러시, 컴파일 지시자를 무시하는 방법에 관해 설명합니다.

### Azure 소식
* Using Azure DocumentDB and ASP.NET Core for extreme NoSQL performance : Matías Quaranta가 Azure DocumentDB와 ASP.NET Core를 활용한 고성능 NoSQL 서버를 구하는 방법을 소개합니다.


### Games 소식
* Unite 2016 Keynote Wrap Up: News on Graphics, Platforms, VR and More : Alice Liang가 Unite 2016 행사 키노트 내용을 공유하였습니다.
* Unity – 2D Movement (Part 6c) – Animation : Aim (video) : Pixel Make에서 Unity – 2D 움직임 (Part 6c) - 애니메이션에 관해 설명합니다.
* [Unity 5] Tutorial: How to make a compass in unity (video) : Gamad가 unity에서 나침반 기능 구현을 방법을 공유하였습니다.
* Mono game drawing tutorial (video) : Tj Bomba가 "모노 게임 그리기"에 관해 설명합니다.
* The challenges of porting XCOM 2 to consoles by Alan Bradley가 XCOM 2게임을 콘솔용으로 포팅하는 과정을 공유했습니다.
* 5 Most Expensive Game Localization Mistakes : Damien Yoccoz가 게임 지역화(Localization) 과정 중 꼭 피해야 하는 5가지 잘못된 사례를 제시합니다.

// 전무님 소개
