주간닷넷 2017년 03월 28일

### Microsoft Tech Summit 서울

Microsoft Tech Summit 서울 행사가 성황리에 끝났습니다! 참석해주신 모든 분들 감사드립니다. 발표자료는 아

### On .NET 소식

지난 주 On .NET 소식에서는 삼성에 근무하시는 Sidarth Gupta와 함께 TV, 시계, 스마트폰을 포함한 여러 디바이스에 탑제될 오픈소스 운영체제인 [타이젠](https://www.tizen.org/)에 대해서 이야기 나누었습니다. 타이젠은 .NET Core와 Xamarin Forms를 기반으로한 개발 플랫폼을 지원합니다.

//사진

이번 주 On .NET 소식에서는 Tamás Vajk과 함께 [SonarLint](http://www.sonarlint.org/visualstudio/index.html)에 대해서 이야기 나눌 예정입니다.  

### Happy Birthday .NET!

개발 엔지니어인 [Bertrand Le Roy](https://twitter.com/bleroy)는 초기 베타 시절부터 .NET을 사용해왔으며 자신의 CMS 개발 프로젝트도 .NET 환경으로 구축했습니다. 그가 미국에 정착해서 ASP.NET 팀에 합류했던 시점은 ASP.NET 팀이 ASP.NET 2.0을 한창 개발하고 있던 때였습니다. 그는 ASP.NET Ajax(UpdatePanel을 포함한)의 초기 개발자이며 Orchard CMS의 공동 창업자이기도 합니다. 현재 Bertrand Le Roy는 .NET Core의 프로그램 매니저이며 가끔 자신을 3인칭 형식으로 언급하기도 합니다.

//동영상

### 금주의 패키지: JSON.NET 10

 JSON.NET에 대해서는 이미 [지난 포스트](https://blogs.msdn.microsoft.com/dotnet/2016/01/12/the-week-in-net-1122016/)에서 다룬적이 있습니다. JSON.NET은 5 천만 건 이상의 다운로드를 자랑하는 [NuGet 패키지 중 1위 패키지](https://www.nuget.org/packages)이며 최근 버전 10이 새롭게 릴리즈 되었습니다. 이번 버전에는 다양한 기능들이 추가되었으며 완벽한 비동기 모드를 지원한다고 합니다.

//코드

* [NuGet.org 에서 JSON.NET 10 다운로드](https://www.nuget.org/packages/Newtonsoft.Json/)

### 금주의 블로거: Gunnar Peipman

[Gunnar Peipman](http://gunnarpeipman.com/)은 일주일에 적어도 하나 이상의 포스트를 작성해왔으며 이번주에도 어김없이 [ASP.NET](http://gunnarpeipman.com/2017/03/aspnet-core-websocket-chart/), [C#](http://gunnarpeipman.com/2017/03/csharp-out-variables/), [Azure](http://gunnarpeipman.com/2017/03/aspnet-core-azure-ad/)에 대한 포스트를 작성했습니다. 항상 유용한 포스트를 작성해주는 [Gunnar의 블로그](http://gunnarpeipman.com/)를 지금 바로 방문해보세요! 

### .NET

* [A Hitchhikers Guide to the CoreCLR Source Code](http://mattwarren.org/2017/03/23/Hitchhikers-Guide-to-the-CoreCLR-Source-Code/) : Matt Warren이 CoreCLR 소스코드를 쉽게 이해하는데 도움을 줄 수 있는 가이드를 공유했습니다
* [Command Line: Using dotnet watch test for continuous testing with .NET Core 1.0 and XUnit.net](https://www.hanselman.com/blog/CommandLineUsingDotnetWatchTestForContinuousTestingWithNETCore10AndXUnitnet.aspx) : Scott Hanselman이 .NET Core 1.0, XUnit.net 와 "dotnet watch test" 명령어를 이용한 지속적인 테스팅 방법을 설명했습니다
* [Visual Studio 2017 can automatically recommend NuGet packages for unknown types](https://www.hanselman.com/blog/VisualStudio2017CanAutomaticallyRecommendNuGetPackagesForUnknownTypes.aspx) : Scott Hanselman이 Visual Studio 2017의 알려지지 않은 타입에 대한 NuGet 패키지 제안 기능(코드에서 정의되지 않은 타입을 사용한 경우 NuGet 패키지들에서 이를 검색하여 해당 타입이 포함된 패키지 설치를 제안하는 기능)을 소개했습니다
* [Fast Dictionary and struct generic arguments](https://ayende.com/blog/177377/fast-dictionary-and-struct-generic-arguments) : Ayende Rahien이 자신이 개발한 FastDictionary 클래스의 성능을 공유했습니다
* [ClrMD Part 2 – From ClrRuntime to ClrHeap or how to traverse the managed heap](http://labs.criteo.com/2017/03/clrmd-part-2-clrruntime-clrheap-traverse-managed-heap/) : CriteoLabs가 "CLR MD"(Microsoft.Diagnostics.Runtime.dll)를 이용한 관리되는 힙의 메모리 분석 방법을 설명했습니다
* [NuGet Versioning Hell](http://isolineltd.com/blog/2017/03/23/NuGet-Versioning-Hell) : Ivan Gavryliuk이 NuGet 사용시 발생할 수 있는 버전 문제와 이에 대한 해결책을 설명했습니다
* [Dynamically generating classes in runtime](https://nikolalukovic.com/programming/NET-Dynamically-generating-classes-in-runtime.html) : Nikola Lukovic이 Reflection API 을 이용한 "실행 중 클래스 동적 정의" 방법을 설명했습니다
* [dotnet new Feature Selection](http://rehansaeed.com/dotnet-new-feature-selection/) : Muhammad Rehan Saeed가 "dotnet new" 명령어의 기능 선택 옵션을 설명했습니다.
* [Happy LibYear!](https://stevedesmond.ca/blog/happy-libyear) : Steve Desmond가 종속 컴포넌트의 업데이트 상황을 쉽게 파악할 수 있게 도와주는 LibYear을 소개했습니다

### ASP.NET
* [Real-time chart using ASP.NET Core and WebSocket](http://gunnarpeipman.com/2017/03/aspnet-core-websocket-chart/) : Gunnar Peipman이 ASP.NET Core에서 WebSocket을 이용한 실시간 차트의 구현 방법을 공유했습니다
* [Preventing mass assignment or over posting in ASP.NET Core](https://andrewlock.net/preventing-mass-assignment-or-over-posting-in-asp-net-core/) : Andrew Lock이 over posting, mass assignment 등 보안위협시 대처 방법을 공유했습니다
* Carlos Mendible이 ["라즈베리파이에서 ASP.NET Core실행하기"](https://carlos.mendible.com/2017/03/21/step-by-step-running-aspnet-core-on-raspberry-pi/)와 ["라즈베리파이 Startup 시점에 ASP.NET Core실행하기"](https://carlos.mendible.com/2017/03/26/raspberry-pi-run-aspnet-core-on-startup/)을 설명했습니다
* [MVC 5 encrypt parameters](http://msprogrammer.serviciipeweb.ro/2017/03/20/mvc-5-encrypt-parameters/) : Andrei Ignat이 MVC 5에서 암호화 된 인자를 사용할 수 있도록 도와주는 오픈소스 라이브러리와 사용방법을 공유했습니다

### C#
* [Why .NET Core Made C# Your Next Programming Language to Learn](https://stackify.com/net-core-csharp-next-programming-language/) : Matt Watson이 .NET Core 플랫폼과 C# 언어 학습의 중요성을 설명했습니다
* [Exploring C# 7](http://davidpine.net/blog/exploring-csharp-seven/) : David Pine이 C# 7.0의 기능을 설명했습니다
* [Deconstructors for non-tuple types in C# 7.0](https://andrewlock.net/deconstructors-for-non-tuple-types-in-c-7-0/) : Andrew Lock이 C# 7.0의 새로운 기능 중 하나로 필드의 값들을 외부로 전댈하는 역할을 하는 Deconstructors에 대해 설명합니다
* [C# 7.0: Out variables](http://gunnarpeipman.com/2017/03/csharp-out-variables/) : Gunnar Peipman이 C# 7.0에서 out 파라미터를 미리 선언하지 않고도 사용가능하게끔 개선된 점을 설명했습니다.
* [How to build a simple object graph delta comparer in C# using Structurizer](https://danielwertheim.se/how-to-build-a-simple-object-graph-delta-comparer-in-csharp-using-structurizer/) : Daniel Wertheim이 오브젝트 그래프를 이용하여 두 객체 상태를 비교하는 코드를 설명했습니다.

### F#
* [Exploring StackOverflow Data](https://www.youtube.com/watch?v=VU1ObHfDNPQ) : Evalina Gabasova가 StackOverflow 의 여러 통계 데이터를 소개했습니다.
* [Visualizing Olympic Medals with F# and Fable](https://www.youtube.com/watch?v=C4xzEudljWE) : Tomas Petricek이 F#을 이용한 올림픽 데이터의 시각화(Data Visualization) 작업 경험을 공유했습니다. 
* [Building a MUD with F# and Akka.NET – Part One](https://www.seventeencups.net/building-a-mud-with-f-sharp-and-akka-net-part-one/) : Joe Clay가 F# 과 Akka.NET을 이용하여 텍스트 기반 온라인게임인 MUD의 구현 방법 - 파트1 을 공유했습니다 
* [Why OO Matters (in F#)](https://eiriktsarpalis.wordpress.com/2017/03/20/why-oo-matters-in-f/) : Eirik Tsarpalis가 F# 에서 객체지향 프로그램의 중요성을 설명했습니다.
* [Answering “What’s for lunch?” using Azure Functions, F# and Slack](https://martinand.net/2017/03/20/what-is-for-lunch/) : Martin Andersen이 F#과 Slack 그리고 Azure Functions을 이용한 개발 경험을 공유했습니다.
* [Examining the F# Programming Language](http://insights.dice.com/2017/03/20/examining-f-programming-language/?utm_campaign=shareaholic&utm_medium=twitter&utm_source=socialnetwork) : David Bolton이 F# 언어를 소개했습니다.
* [Visual F# Attributions](https://github.com/Microsoft/visualfsharp/blob/master/attributions.md) : F#의 여러 확장기능과 관련 오픈 소스 프로젝트 참여자 리스트를 공유합니다.

F# 언어에 대한 새로운 제안들을 소개합니다!
* [Constrained type 제안](https://github.com/fsharp/fslang-suggestions/issues/553)
* [Flow based null check analysis for [<AllowNullLiteralAttribute>] types and alike](https://github.com/fsharp/fslang-suggestions/issues/552)

더 많은 소식은 [F# Weekly](https://sergeytihon.wordpress.com/category/f-weekly/) 에서 확인하실 수 있습니다

### Xamarin

* [Xamarin Beta Release: 15.1 Beta Preview 1](https://releases.xamarin.com/beta-release-15-1-beta-preview-1/) : Bri Brothers가 15.1 Beta Preview 1 버전 정보를 공유했습니다
* [Xamarin Stable Release: Xamarin Workbooks & Inspector 1.2.0](https://releases.xamarin.com/stable-release-xamarin-workbooks-inspector/) : Bri Brothers가 Workbooks & Inspector 1.2.0 버전 정보를 공유했습니다
* [Xamarin Technical Bulletin: Updating Xamarin Visual Studio 2017 & Side-by-Side](https://releases.xamarin.com/technical-bulletin-updating-xamarin-visual-studio-2017-side-by-side/) : Dominic Nahous가 Xamarin Visual Studio 2017의 Side-by-Side(타버전과 동시 설치및 운영 가능성) 정보를 공유했습니다
* [Introducing the Kimono Designer for SkiaSharp](https://blog.xamarin.com/introducing-the-kimono-designer-for-skiasharp/) : Kevin Mullins가 SkiaSharp을 위한 비주얼 디자이너 "Kimono Designer"를 소개했습니다
* [Xamarin University Webinar Recording | Building Your First Android App with Xamarin for Visual Studio](https://blog.xamarin.com/xamarin-university-webinar-recording-building-your-first-android-app-with-xamarin-for-visual-studio/) : Courtney Witmer가 Xamarin University의 웨비나 "Xamarin 으로 첫번째 안드로이드 App 개발 하기"를 공유했습니다
* [Play Audio and Video with the MediaManager Plugin for Xamarin](https://blog.xamarin.com/play-audio-and-video-with-the-mediamanager-plugin-for-xamarin/) : Martijn van Dijk이 MediaManager 를 이용한 비디오/오디오 플레이 방법을 설명했습니다
* [Organize a Xamarin Dev Days!](https://blog.xamarin.com/organize-your-xamarin-dev-days/) : Jayme Singleton이 "Xamarin Dev Days" 개발자 행사 진행과정을 설명했습니다
* [Catch Up on Visual Studio 2017 and Visual Studio for Mac with Channel 9](https://blog.xamarin.com/catch-up-on-vs2017-visual-studio-for-mac-channel-9/) : James Montemagno가 Visual Studio 2017 및 Visual Studio for Mac관련된 Channel 9 동영상을 공유했습니다
* [Introduction to Game Development with MonoGame by Xamarin](https://developer.xamarin.com/guides/cross-platform/game_development/monogame/introduction/) : MonoGame 을 이용한 게임 개발 가이드 문서가 공유되었습니다
* [New HockeySDK releases for Xamarin and Unity by HockeyApp](https://www.hockeyapp.net/blog/2017/03/22/HockeySDK-Xamarin-4-1-2.html) : Xamarin과 Unity에서 사용가능한 새로운 버전의 HockeySDK가 릴리즈 되었습니다
* [Behind the Scenes: How Chefs for Seniors uses Xamarin, HockeyApp & Azure App Service to Power its Daily Operations](https://channel9.msdn.com/Blogs/DevRadio/DR1719) : DevRadio에서 "Chefs For Seniors"회사의 Xamarin, HockeyApp 그리고 Azure를 이용한 애플리케이션 활용 사례 비디오를 공유했습니다
* [Episode 19: MonoGame – Write Once, Play Everywhere with Dean Ellis by The Xamarin Show](https://channel9.msdn.com/Shows/XamarinShow/Episode-19-MonoGame-Write-Once-Play-Everywhere-with-Dean-Ellis) : Xamarin Show 19편 "MonoGame"이 공유되었습니다
* [Cleaning Up Space on Your Xamarin Development Machine](http://motzcod.es/post/158519702967/cleanup-up-space-xamarin-dev-machine) : James Montemagno가 기존 Visual Studio를 제거하고 2017 버전을 설치하는 경우 디스크 공간 확보를 위한 몇 가지 정보와 경험을 공유했습니다
* [Xamarin.Forms Layout Challenges – Great Places](http://www.kymphillpotts.com/xamarin-forms-layout-challenges-great-places/) : Kym Phillpotts가 Xamarin.Forms의 레이아웃에 대해 자세하게 설명했습니다.
* [Connecting To A Remote Database in Xamarin Forms](https://xamarinhelp.com/connecting-remote-database-xamarin-forms/) : Adam Pedley가 Xamarin Forms 에서 원격지에 있는 데이터 접속 방법에 관하여 설명했습니다.
* [UISleuth – Visually Inspect Your Xamarin Forms Application](https://xamarinhelp.com/uisleuth-visually-inspect-xamarin-forms-application/) : Adam Pedley가 Xamarin Forms 애플리케이션용 비주얼 탐색기 "UISleuth"를 소개했습니다.
* [Xamarin Forms Binding](https://xamarinhelp.com/xamarin-forms-binding/) : Adam Pedley가 Xamarin Forms의 바인딩 기능을 설명했습니다
* [Xamarin.Forms: Grouping data with Tabbed page](https://almirvuk.blogspot.com/2017/03/xamarinforms-grouping-data-with-tabbed.html) : Almir Vuk가 Tabbed page를 이용한 데이터 그룹핑 기능 구현 경험을 공유했습니다
* [Xamarin.Forms: Caching for the ListView](https://visualstudiomagazine.com/articles/2017/03/01/xamarinforms-ios-android-mobile-visual-studio.aspx) : Wallace McClure가 ListView의 이미지 데이터 캐시방법을 설명했습니다
* Alex Dunn이 Xamarin과 관련하여 여러가지 Tip들을 소개합니다 
    * [Xamarin.Forms Android Custom TableView Section Titles](https://alexdunn.org/2017/03/21/xamarin-tips-xamarin-forms-android-custom-tableview-section-titles/) : Xamarin.Forms에서 Android 용 TableView의 사용자 정의 섹션 타이틀 구현 방법을 설명했습니다
    * [Xamarin.Forms iOS Custom TableView Section Titles](https://alexdunn.org/2017/03/21/xamarin-tips-xamarin-forms-ios-custom-tableview-section-titles/) : Xamarin.Forms에서  iOS 용 TableView의 사용자 정의 섹션 타이틀 구현 방법을 설명했습니다
    * [Android Shadows on Transparent Views](https://alexdunn.org/2017/03/22/xamarin-tips-android-shadows-on-transparent-views/) : 안드로이드 그림자 효과 구현 방법을 설명했습니다
    * [Changing a TableView’s Separator Color](https://alexdunn.org/2017/03/23/xamarin-tips-changing-a-tableviews-separator-color/) :TableView의 구분선 색상 변경 방법을 설명했습니다
    
### Azure

* [Service Fabric .NET SDK goes open source](https://blogs.msdn.microsoft.com/azureservicefabric/2017/03/24/service-fabric-net-sdk-goes-open-source/) : Service Fabric team에서 Service Fabric .NET SDK의 오픈소스 정책을 공유했습니다
* [Using Azure AD with ASP.NET Core](http://gunnarpeipman.com/2017/03/aspnet-core-azure-ad/) : Gunnar Peipman이 ASP.NET Core 환경에서 Azure AD의 활용방법을 설명했습니다
* [How to deploy an ASP.NET Core 1.1 application to an Azure App Services Web App using Visual Studio 2017](https://blogs.msdn.microsoft.com/benjaminperkins/2017/03/21/how-to-deploy-an-asp-net-core-1-1-application-to-an-azure-app-services-web-app-using-visual-studio-2017/) : Benjamin Perkins가 Visual Studio 2017를 이용한 ASP.NET Core 1.1 애플리케이션의 Azure 배포방법을 설명했습니다.

### UWP

* [New Year, New Dev – Windows IoT Core By Windows Apps Team](https://blogs.windows.com/buildingapps/2017/03/22/new-year-new-dev-windows-iot-core/) : Windows IoT Core용 애플리케이션 개발방법을 설명 했습니다
* [Project Rome for Android Update: Now with App Services Support](https://blogs.windows.com/buildingapps/2017/03/23/project-rome-android-update-now-app-services-support/) : Carmen Forsmann이 다중 통신/플렛폼 애플리케이션 개발 플렛폼인 Project Rome SDK for Android의 최신 정보를 공유했습니다
* [How the UWP Community Toolkit helps Windows developers easily create well-designed and user-friendly apps](https://blogs.windows.com/buildingapps/2017/03/24/uwp-community-toolkit-helps-windows-developers-easily-create-well-designed-user-friendly-apps/) : Windows Apps Team에서 UWP개발에 도움이되는 UWP Community Toolkit 샘플 정보를 공유했습니다.
* [Dialing an Etch-a-Sketch](https://channel9.msdn.com/coding4fun/blog/Dialing-an-Etch-a-Sketch) : Greg Duncan이 Surface Dial을 이용한 Etch-a-Sketch(좌우/상하 로만 움직이면서 그림을 그리는 것으로 국내에서는 매직 스크린이라는 이름으로 한때 유행했었습니다)의 구현방법을 공유했습니다.
* [Setting a custom User-Agent in the UWP WebView control](https://www.pedrolamas.com/2017/03/21/setting-a-custom-user-agent-in-the-uwp-webview-control/) : Pedro Lamas가 UWP의 WebView 컨트롤에서 사용자 정의 User-Agent 문자열의 사용 방법을 설명했습니다.

### Data

* Julie Lerman이 EF Core에 대한 ["Channel 9 학습 동영상"](http://thedatafarm.com/uncategorized/quick-start-ef-core-videos-on-channel-9/), ["ASP.NET Core in Visual Studio 2017"](https://channel9.msdn.com/Blogs/MVP-VisualStudio-Dev/EF-Core-Quick-Starts-ASPNET-Core-in-Visual-Studio-2017), ["Full .NET in Visual Studio 2015"](https://channel9.msdn.com/Blogs/MVP-VisualStudio-Dev/EF-Core-Quick-Starts-Full-NET-in-Visual-Studio-2015) 학습 동영상정보를 공유했습니다
* [Using Resilient Entity Framework Core Sql Connections and Transactions: Retries with Exponential Backoff](https://blogs.msdn.microsoft.com/cesardelatorre/2017/03/26/using-resilient-entity-framework-core-sql-connections-and-transactions-retries-with-exponential-backoff/) : Cesar de la Torre가 Exponential Backoff가 존재하는 경우의 재시도 방식에 대해 설명합니다
* [Entity Framework Query Caching](https://blogs.msdn.microsoft.com/premier_developer/2017/03/23/entity-framework-query-caching/) : Deepak Malik가 엔티티 혹은 쿼리결과를 캐시 처리할 수 있는 방법을 설명했습니다
* [Checking Up on Your Entity Framework Objects with DbEntityEntry](https://visualstudiomagazine.com/articles/2017/03/01/check-ef-objects-dbentityentry.aspx) : Peter Vogel이 EF의 주요 클래스인 DbEntityEntry 클래스를 설명했습니다

### Game 개발

* [Inventory and Store System – Part 4.2 (Populating the Data)](https://channel9.msdn.com/Shows/dotGAME/Inventory-and-Store-System-Part-42-Populating-the-Data) : Stacey Haffner가 인벤토리 그리고 스토리 시스템 시리즈 - 파트 4.2편 : "데이터 처리하기" 동영상을 공유했습니다
* [Implementing robust AI for SecondHand: Enemy Positioning](http://www.rikodu.com/implementing-robust-ai-for-secondhand-enemy-positioning/) : Radu S. Cristea가 인공지능 "SecondHand" 구현 블로그 : "(적)오브젝트 위치 실시간 판단하기" 편을 공유했습니다
* [SadConsole – Engine Revision Completed](http://thraka.github.io/2017/03/18/engine-revision-completed/#more) : Andy De George가 새로운 엔진이 적용된 SadConsole 소식을 공유해 주었습니다
* [Is Early Access Worth It?](http://www.gamasutra.com/blogs/JamesBuckle/20170327/294546/Is_Early_Access_Worth_It.php) : James Buckle이 게임 개발시 Early Access(공개 테스트)의 중요성과 의미를 설명했습니다
* [[Unity 5.5] Tutorial: How to create a Mirror](https://youtu.be/Ey8MHswqzko) : Gamad에서 거울 효과 구현 방법을 설명했습니다
* [Hex Map 15: Distances](http://catlikecoding.com/unity/tutorials/hex-map/part-15/) : Catlike Coding에서 Hex Map 15: "공간 거리"편을 소개 했습니다
* [Unity 5: Fade Between Scenes](https://youtu.be/iV-igTT5yE4) : Dual Core Studio에서 두개의 Scene 이 fade in/out 으로 전환되는 효과를 설명했습니다
* [Curated #UnityTips No. 38](http://devdog.io/blog/2017/03/9-best-unity-tips-for-game-developers-38) : DevDog가 Unity 개발에 도움이 될수있는 38번째 Tip 모음을 공유했습니다
* [Hajime Tabata talks about the transformation of Versus XIII to Final Fantasy XV](http://www.usgamer.net/articles/hajime-tabata-talks-about-the-transformation-of-versus-xiii-to-final-fantasy-xv) : Jeremy Parish 파이널 판타지 게임의 Versus XIII 과 Final Fantasy XV 의 변화된 점에 관한 포스트를 공유했습니다

// 전무님 소개
