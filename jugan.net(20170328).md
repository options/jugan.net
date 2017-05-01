주간닷넷 2017년 03월 28일

### On .NET 소식

지난  주 On .NET 소식에서는 삼성에 근무하시는 Sidarth Gupta와  함께 TV, 시계, 스마트폰을 포함한 여러 디바이스에 탑제될 타이젠 오픈소스 OS에 대해서 얘기했습니다.  타이젠은  .NET Core와 Xamarin Forms을 기반으로한 개발 플랫폼을 지원합니다.

//사진

이번  주 On .NET 소식에서는Tamás Vajk과 함께  SonarLint(링크)에 대해서 얘기 나눌예정입니다.  

### Happy Birthday .NET!
Bertrand Le Roy(링크)는 초기 베타 시절부터 .NET을 활용했으며 자신의 CMS 개발 프로젝트도 .NET 환경으로 구축했습니다. 그가 미국에 정착해서 ASP.NET 팀에 합류 할 시절은  ASP.NET 팀이 ASP.NET 2.0을 한창 개발하고있던 때였습니다. 그는  그 유명한 ASP.NET Ajax(UpdatePanel을 포함한)의 초기 개발자 이며 Orchard CMS의 공동 창업자이기도합니다.  지금 현재 Bertrand Le Roy는 .NET Core의 프로그램 매니저이며 가끔 자신을 말할때  3인칭 형식으로 말하기도합니다.

//동영상

### 금주의 패키지: JSON.NET 10
 JSON.NET에 대해서는 이미 지난 여러 코너(링크)에서 다룬 적이있습니다. NuGet 패키지(링크)로서 5억 이상의 다운로드를 기록하고있는  다운로드 1위 패키지로서 현재 버전10이 릴리즈되었습니다. 이번 릴리즈된 버전에는 다양한 기능이 추가되었으며 완전한 비동기 모드를 지원한다고 합니다.

//코드

### .NET
* A Hitchhikers Guide to the CoreCLR Source Code : Matt Warren이 CoreCLR Source Code를 쉽게 이해하는데 도움을 줄 수 있는 가이드를 공유했습니다.
* Command Line: Using dotnet watch test for continuous testing with .NET Core 1.0 and XUnit.net : Scott Hanselman이 .NET Core 1.0, XUnit.net 와 "dotnet watch test" 명령어를 이용한 지속적인 테스팅 방법을 설명했습니다
* Visual Studio 2017 can automatically recommend NuGet packages for unknown types : Scott Hanselman이 Visual Studio 2017의  알려지지않은 타입에 대한 NuGet 패키지 제안 기능(코드의에서 미 정의된 타입을 사용할 경우 NuGet 패키지들에서 이를 검색하여 해당 타입이 포함된 패키지의 설치를 제안하는 기능)을 소개했습니다.
* Fast Dictionary and struct generic arguments : Ayende Rahien이 자신이 개발한 FastDictionary 클래스의 성능을 공유했습니다
* ClrMD Part 2 – From ClrRuntime to ClrHeap or how to traverse the managed heap : CriteoLabs가  "CLR MD" (Microsoft.Diagnostics.Runtime.dll )를 이용한 관리되는힙 메모리의 분석 방법을 설명했습니다. 
* NuGet Versioning Hell : Ivan Gavryliuk이 NuGet 사용시 발생할 수 있는 버전 문제 (Versioning Hell)와 이에 대한 해결책을 설명했습니다.
* Dynamically generating classes in runtime : Nikola Lukovic이 Reflection API 을 이용한 "실행중 클래스 동적 정의" 방법을 설명했습니다.
* dotnet new Feature Selection : Muhammad Rehan Saeed가 "dotnet new" 명령어의 기능 선택 옵션을 설명했습니다.
* Happy LibYear! : Steve Desmond이 (종속 컴포넌트의 업데이트상황을 쉽게 파악할수있게 도와주는) LibYear를 소개했습니다.
* Introductie van .NET Core, .NET Standard, and Developer experience – deel 1 van 2 (Dutch) : Sander Molenkamp와 Edwin van Wijk이  .NET Core(링크), .NET Standard(링크), Developer experience(링크)에 대한 동영상을 공유했습니다(네덜란드어로 녹화된 동영상이라 해독 불가네요) 

### ASP.NET
* Real-time chart using ASP.NET Core and WebSocket : Gunnar Peipman이 ASP.NET Core에서 WebSocket을 이용한 실시간 차트의 구현 방법을 공유했습니다.
* Preventing mass assignment or over posting in ASP.NET Core : Andrew Lock이 overposting, mass assignment의 보안 위협의 대처 방법을 공유했습니다.
* Step by step: Running ASP.NET Core on Raspberry Pi, and Raspberry Pi: Run ASP.NET Core on Startup : Carlos Mendible이 "라즈베리파이에서 ASP.NET Core실행하기"(링크)와 "라즈베리파이 Startup 시점에 ASP.NET Core실행하기"(링크)을 설명했습니다.
* MVC 5 encrypt parameters : Andrei Ignat이 MVC 5에서 암호화된 인자를 사용할 수 있도록 도와주는 오픈소스 라이브러리와 이의 사용방법을 공유했습니다.

### C#
* Why .NET Core Made C# Your Next Programming Language to Learn : Matt Watson이 .NET Core 플랫폼과 C# 언어의 학습 중요성을 설명했습니다.
* Exploring C# 7 : David Pine이 C# 7.0의 기능을 설명했습니다.
* Deconstructors for non-tuple types in C# 7.0 : Andrew Lock이 C# 7.0의 새로운 기능 Deconstructors를 설명했습니다.
* C# 7.0: Out variables : Gunnar Peipman이 C#7.0의 향상된 Out 변수 키워드를 설명했습니다.
* How to build a simple object graph delta comparer in C# using Structurizer : Daniel Wertheim이 오브젝트 그래프를 이용하여 두 객체 상태를 비교하는 코드를 설명했습니다.

### F#
* Exploring StackOverflow Data : Evalina Gabasova가 StackOverflow 의 여러 통계 데이터를 소개했습니다.
* Visualizing Olympic Medals with F# and Fable : Tomas Petricek이 F#을 이용한 올림픽 데이터의 시각화(Data Visualization) 작업 경험을 공유했습니다. 
* Building a MUD with F# and Akka.NET – Part One : Joe Clay가 F# 과 Akka.NET을 이용한 "(텍스트 기반 온라인게임) MUD 구현 방법"-파트1 을 공유했습니다 
* Why OO Matters (in F#) : Eirik Tsarpalis가 (F#에서) 객체지향 프로그램의 중요성을 설명했습니다.
* Answering “What’s for lunch?” using Azure Functions, F# and Slack : Martin Andersen이  F#과 Slack 그리고 Azure Functions을 이용한 개발 경험을 공유했습니다.
* Examining the F# Programming Language : David Bolton이 F# 언어를 소개했습니다.
* Visual F# Attributions : F#의 여러 확장기능과 관련 오픈 소스 프로젝트 참여자 리스트를 공유했습니다.

### Xamarin
* Xamarin Beta Release: 15.1 Beta Preview 1 : Bri Brothers가 15.1 Beta Preview 1 버전  정보를 공유했습니다.
* Xamarin Stable Release: Xamarin Workbooks & Inspector 1.2.0 : Bri Brothers가 Workbooks & Inspector 1.2.0 버전  정보를 공유했습니다.
* Xamarin Technical Bulletin: Updating Xamarin Visual Studio 2017 & Side-by-Side : Dominic Nahous가 Xamarin Visual Studio 2017의 Side-by-Side(타버전과 동시 설치및 운영 가능성) 정보를 공유했습니다.
* Introducing the Kimono Designer for SkiaSharp : Kevin Mullins가 SkiaSharp을 위한 비주얼 디자이너 "Kimono Designer"를 소개했습니다.
* Xamarin University Webinar Recording | Building Your First Android App with Xamarin for Visual Studio : Courtney Witmer가 Xamarin University의 웨비나 "Xamarin 으로 첫 안드로이드 App 개발 하기"를 공유했습니다.
* Play Audio and Video with the MediaManager Plugin for Xamarin : Martijn van Dijk이 MediaManager 를 이용한 비디오/오디오 플레이  방법을 설명했습니다.
* Organize a Xamarin Dev Days! : Jayme Singleton이 "Xamarin Dev Days" 개발자 행사 진행과정을 설명했습니다.
* Catch Up on Visual Studio 2017 and Visual Studio for Mac with Channel 9 : James Montemagno가 Visual Studio 2017과 Visual Studio for Mac관련된 Channel 9 동영상을 공유했습니다.
* Introduction to Game Development with MonoGame by Xamarin : MonoGame 을 이용한 개임 개발 가이드 문서가 공유되었습니다.
* New HockeySDK releases for Xamarin and Unity by HockeyApp : Xamarin과 Unity에서 사용가능한 새로운 버전의 HockeySDK가 릴리즈 되었습니다.
* Behind the Scenes: How Chefs for Seniors uses Xamarin, HockeyApp & Azure App Service to Power its Daily Operations : DevRadio에서 "Chefs For Seniors"회사의 Xamarin, HockeyApp 그리고 Azure를 이용한 어플활용 사례 비디오를 공유했습니다.
* Episode 19: MonoGame – Write Once, Play Everywhere with Dean Ellis by The Xamarin Show : Xamarin Show 19 편 "MonoGame "가 공유되었습니다.
* Cleaning Up Space on Your Xamarin Development Machine : James Montemagno가  기존 Visual Studio를 제거하고  2017 버전을 설치할 경우 디스크 공간 확보를 위한 몇가지 정보와 경험을 공유했습니다.
* Xamarin.Forms Layout Challenges – Great Places :  Kym Phillpotts가 Xamarin.Forms의 레이아웃 시스템을 설명했습니다.
* Connecting To A Remote Database in Xamarin Forms : Adam Pedley가 Xamarin Forms 에서 원격지 데이터의 접속 방법들을 설명했습니다.
* UISleuth – Visually Inspect Your Xamarin Forms Application : Adam Pedley가 Xamarin Forms 어플리케이션용 비주얼 탐색기 "UISleuth" 를 소개했습니다.
* Xamarin Forms Binding : Adam Pedley가 Xamarin Forms의 바인딩 기능을 설명했습니다
* Xamarin.Tips – Xamarin.Forms Android Custom TableView Section Titles : Alex Dunn이 Xamarin.Forms에서  Android 용 TableView의 사용자 정의 섹션 타이틀 구현 방법을 설명했습니다.
* Xamarin.Tips – Xamarin.Forms iOS Custom TableView Section Titles : Alex Dunn이 Xamarin.Forms에서   iOS 용 TableView의 사용자 정의 섹션 타이틀 구현 방법을 설명했습니다.
* Xamarin.Tips – Android Shadows on Transparent Views : Alex Dunn이 안드로이드 그림자 효과 구현 방법을 설명했습니다.
* Xamarin.Tips – Changing a TableView’s Separator Color : Alex Dunn이 TableView 의 구분선 색상 변경 방법을 설명했습니다.
* Xamarin.Forms: Grouping data with Tabbed page : Almir Vuk가 Tabbed page를 이용한 데이터 그룹핑기능의 구현 경험을 공유했습니다.
* Xamarin.Forms — Caching for the ListView : Wallace McClure가  ListView의 이미지 데이터 캐시방법을 설명했습니다.

### Azure
* Service Fabric .NET SDK goes open source : the Service Fabric team에서 Service Fabric .NET SDK의 오픈소스 정책을 공유했습니다.
* Using Azure AD with ASP.NET Core : Gunnar Peipman이 ASP.NET Core 환경에서Azure AD의 활용방법을 설명했습니다.
* How to deploy an ASP.NET Core 1.1 application to an Azure App Services Web App using Visual Studio 2017 : Benjamin Perkins가 Visual Studio 2017를 이용한  ASP.NET Core 1.1 어플리케이션의 Azure 배포방법을 설명했습니다.

### UWP
* New Year, New Dev – Windows IoT Core By Windows Apps Team : Windows IoT Core용 어플 개발방법을 설명 했습니다.
* Project Rome for Android Update: Now with App Services Support : Carmen Forsmann이 다중 통신/플렛폼 어플 개발 플렛폼인 Project Rome SDK for Android의 최신 정보를 공유했습니다.
* How the UWP Community Toolkit helps Windows developers easily create well-designed and user-friendly apps : Windows Apps Team에서  UWP개발에 도움이되는 UWP Community Toolkit 샘플 정보를 공유했습니다.
* Dialing an Etch-a-Sketch : Greg Duncan이  Surface Dial을 이용한 Etch-a-Sketch( 좌우/상하 로만 움직이면서 그림을 그리는 것으로 국내에서는 매직 스크린이라는 이름으로 한때 유행했었습니다)의 구현방법을 공유했습니다.
* Setting a custom User-Agent in the UWP WebView control : Pedro Lamas가 UWP의 WebView 컨트롤에서 사용자 정의 User-Agent  문자열의 사용 방법을 설명했습니다.
• 
### Data
* Quick Start EF Core Videos on Channel 9, EF Core Quick Starts: ASP.NET Core in Visual Studio 2017 (video) and EF Core Quick Starts: Full .NET in Visual Studio 2015 (video) : Julie Lerman이 Quick Start EF Core으 "Channel 9 학습 동영상"(링크), "ASP.NET Core in Visual Studio 2017"(링크). "Full .NET in Visual Studio 2015"(링크) 학습 동영상정보를 공유했습니다.
* Using Resilient Entity Framework Core Sql Connections and Transactions: Retries with Exponential Backoff by Cesar de la Torre.
* Entity Framework Query Caching : Deepak Malik가 엔티티 혹은 쿼리결과를 캐시 처리할수있는 방법을 설명했습니다
* Checking Up on Your Entity Framework Objects with DbEntityEntry : Peter Vogel이 EF의 주요 클래스인 DbEntityEntry 클래스를 설명했습니다.

### Game 개발
* Inventory and Store System – Part 4.2 (Populating the Data): Stacey  Haffner가 인벤토리 그리고 스토리 시스템 시리즈  - 파트 4.2편 : "데이터 처리하기(보여주기)"  동영상을 공유했습니다
* Implementing robust AI for SecondHand: Enemy Positioning : Radu S. Cristea가 인공지능 "SecondHand" 구현 블로그 : "(적)오브젝트 위치 실시간 판단하기" 편을 공유했습니다.
* SadConsole – Engine Revision Completed Andy De George가 새로운 엔진이 적용된 SadConsole 소식을 공유해 주었습니다.
* Is Early Access Worth It? : James Buckle이 게임 개발시 Early Access(공개 테스트)의 중요성과 의미를 설명했습니다.
* [Unity 5.5] Tutorial: How to create a Mirror : Gamad에서 거울 효과 구현 방법을 설명했습니다.
* Hex Map 15: Distances : Catlike Coding에서 Hex Map 15 : "공간 거리"편을 소개 했습니다.
* Unity 5: Fade Between Scenes : Dual Core Studio에서 두개의 Scene 이 fade in/out 으로 전환되는 효과를 설명 했습니다.
* Curated #UnityTips No. 38 : Devdog가 DevDog가 Unity 개발에 도움이 될수있는 38번째 Tip 모음 을 공유했습니다.
* Hajime Tabata talks about the transformation of Versus XIII to Final Fantasy XV by Jeremy Parish.
And this is it for this week!


// 전무님 소개
