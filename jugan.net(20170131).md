여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On .NET 소식

지난 주에는 ON.NET에서는 2개의 쇼가 진행되었습니다
Scott Hanselman이 Kasey Uhlenhuth, Maria Naggaga Nakanwagi, Donovan Brown, Mitch Muenster와 함께 스튜디오에서 기술 토론을 진행하였습니다.
//그림

Patrick Smacchia가 .NET 관리 코드를 위한 정적 분석 도구인 [ndepend]( http://www.ndepend.com/)의 새로운 버전을 소개합니다.

//그림


### 금주의 툴: CrazyCore
.NET 팀의 개발자인 [Eric Mellino]( https://github.com/mellinoe)은 요즘 여가를 활용하여 자작 게임 엔진 구현에 몰두해있습니다. Eric Mellino가 개발중인 게임엔진 이름은 [CrazyCore]( https://github.com/mellinoe/CrazyCore)이며, 아직 초기 버전이지만 여러모로 매우 흥미로운 엔진입니다.
CrazyCore는 오픈소스 프로젝트로 진행 중이며, 크로스 플랫폼을 지원하고 .NET Core 환경에서 동작합니다.
Eric Mellino가 .NET Core에 존재하지 않는 게임 엔진 라이브러리를 앞으로 어떠한 형태로 구현해나갈지 기대됩니다.

// 그림

CrazyCore에 대한 자세한 내용은 [Building a 3D Game Engine with .NET Core]( https://mellinoe.wordpress.com/2017/01/18/net-core-game-engine/)에서 확인하실 수 있습니다.

### 금주의 게임 : The Perils of Man
[The Perils of Man]( http://www.perilsofman.com/)은 롤 플레잉 스타일의 어드벤쳐 게임입니다. 이 게임은 10년 전 과학계에서 사기꾼으로 알려져 퇴출당한 과학자, Max Eberling 실종에 대한 이야기 속으로 플레이어를 초대합니다.
Max Eberling 실종 사건의 수상한 점은 그의 아버지도 몇 년 전에 실종되었다는 것입니다.
게임 플레이어는 Max Eberling의 딸인 Ana Eberling이 되어, 게임 속 시간여행을 통해 얻은 정보와 다수의 사건들 인과관계를 유추하여 과거 실종과 관련된 미스터리를 푸는 것이 게임의 미션입니다.

//그림 

[The Perils of Man]( http://www.perilsofman.com/)는 [IF Games]( http://if-games.com/)와 [Vertigo Games]( http://vertigo-games.com/)의 합작이며, [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)과 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2017/01/31/the-week-in-net-on-net-on-public-speaking-ndepend-crazycore-the-perils-of-man/unity3d.com)로 개발되었습니다.

### .NET 소식
* Virtual Panel: What’s Next for .NET? : Pierre-Luc Maheu가 .NET팀과 함께 .NET의 새로운 버전 그리고 향후 비전에 관해 토론한 내용을 공유하였습니다.
* Open sourcing the VS Test platform : Brian Harry가 오픈소스 프로젝트 ‘VS Test platform’를 소개합니다.
* Publishing .NET Core NuGet packages : Ryan Stelly가 .NET Core의 NuGet package 배포 방법을 설명합니다.
* Announcing a new documentation experience: easy to customize API, content/wiki pages, and blog posts in the new Wyam Docs recipe : Dave Glick이 문서작성 오픈소스 라이브러리 프로젝트 ‘Wyam Docs’를 소개합니다.
* How to print a GIF : stupotmcdoodlepip에서 GIF 파일 프린트 방법에 관해 소개합니다.
* Common code style in Visual Studio 2017 and VS 2017 + new csproj = useful or useless? : Piotr Stapp이 VS2017에 새롭게 적용된 Editor Config으로 코딩 스타일을 설정하는 방법과 VS2017에 변경된 프로젝트 타입 csproj에 관해 설명합니다.
* What happened to my Thread.CurrentPrincipal : David Pine이 ASP.NET Core의 Thread.CurrentPrincipal에 관해 설명합니다.
* C# 7.0 expression bodied members : Christian Nagel이 C# 7.0 버전의 "expression bodied member" 기능을 소개합니다.
* .Net Core, Roslyn and code generation : Carlos Mendible이 .Net Core 환경에서 Roslyn과 code generation를 테스트 해본 결과를 공유하였습니다.
* Adding Files to Visual Studio Projects : Rick Strahl이 Visual Studio 프로젝트에 새로운 파일 아이템을 추가할 때 알아두면 도움이 되는 기능들을 소개합니다.
* Debugging .NET Core on Unix over SSH : Gregg Miskelly이 SSH(Secure Shell)로 유닉스의 .NET Core 애플리케이션을 디버깅하는 방법을 소개합니다.

### ASP.NET 소식
* Microsoft Security Advisory 4010983: Vulnerability in ASP.NET Core MVC 1.1.0 Could Allow Denial of Service : ASP.NET Core MVC 1.1.0에서 발견된 보안 취약점을 해결할 수 있는 솔루션이 공유되었습니다. 
* ASP.NET Core Authentication with IdentityServer4 : Mike Rousos가 ASP.NET Core에서 IdentityServer4를 통해 인증 토큰을 발급하는 방법을 소개합니다.
Docker compose with ASP.NET Core, EF Core and the PostgreSQL image : Damien Bod이 Docker를 사용하여 PostgreSQL 데이터베이스와 ASP.NET Core 애플리케이션을 함께 설정할 수있는 방법을 소개합니다.
* Reloading strongly typed options in ASP.NET Core 1.1.0 : Andrew Lock이 ASP.NET Core 1.1.0에서 새로운 IOptionsSnapshot <> 인터페이스를 통해 외부 설정 파일에 저장된 여러 사용자 옵션 값을 다시 로드하는 효과적인 방법을 설명했습니다.
* A file upload API with Nancy, .NET Core in a shockingly small amount of code : NandoTech가 Nancy와 .NET Core API를 이용한 파일 업로드 방법을 소개합니다.
* Introducing Alba for integration testing against ASP.Net Core applications : Jeremy D Miller가 ASP.NET Core 애플리케이션용 통합 테스트 오픈소스 라이브러리 ‘Alba’를 소개합니다.
* ASP.NET Core – Migrating to MSBuild : Aaron Marisi가 ASP.NET Core의 기존 JSON기반으로 구성된 프로젝트 파일을 MSBuild용 프로젝트(csproj)로 전환하는 방법을 설명했습니다.
* Building complex UI components with ASP.NET Core MVC Tag Helpers : Scott Addie가 ASP.NET Core MVC Tag Helper로 복잡한 UI 구성 요소를 개발하는 방법을 소개합니다.
* Building microservices with ASP.NET Core (without MVC) : Filip W가 ASP.NET Core (MVC 포함않된)로 microservices를 구현하는 방법을 소개합니다.
* Building simple plug-ins system for ASP.NET Core : Gunnar Peipman이 ASP.NET Core에서 plug-in 시스템 기능을 구현하는 방법을 공유했습니다.

### F# 소식
* Learning Visual F# – Foundations : F# 전문 서적 "Learning Visual F#"에 대한 최신 정보를 웹사이트에서 확인하실 수 있습니다.
* Modeling state in action : Isaac Abraham이 F#에서 상태 관리 방법(모델링)에 관해 설명합니다.
* Fiddling with ASP.NET Core with F# and Suave, : Shane Logsdon이 F#과 Suave로 ASP.NET Core 애플리케이션을 개발하는 방법을 소개합니다.
* F# – How to keep domain pure when logic depends on current date, : Lauri Taimila가 도메인 논리 자체에 영향을 주지 않으면서 현재 날짜의 개념에 의존하는 일부 도메인 논리를 구현하는 방법을 소개합니다.
* Authentication for WebSharper sitelet with JWT token in F#, : Kimserey Lam이 WebSharper sitelet에서 F#으로 JWT(JSON Web Token )토큰을 인증하는 방법을 설명합니다.

### Azure 소식
* Manage App Service, SQL Database, and more – Azure Management Libraries for .NET : Asir Selvasingh가 App Service, SQL Database 등을 관리할 수 있는 "Azure Management Libraries for .NET 베타 4”를 소개합니다.
* Azure Tools for Visual Studio Code 1.2.0 – ARM export, batch, telemetry : Brady Gaster가 최근 공개된 Azure Tools for Visual Studio Code 1.2.0 버전 기능들을 소개합니다.
* How To Build Planet Scale Mobile App in Minutes with Xamarin and DocumentDB : Kirill Gavrylyuk이 Xamarin과 DocumentDB를 이용한 고가용성 모바일 애플리케이션을 빠르고 효과적으로 구축하는 방법을 소개합니다.
* Using Azure Functions to add a Contact Form to a Static Site : Eli Weinstock-Herman이 정적 웹사이트에서 연락처 양식에 Azure Function 기능을 활용하는 방법을 설명했습니다.

### Xamarin 소식
* Visual Studio for Mac – Preview 3 : Adrian Murphy가 Visual Studio for Mac – Preview 3 버전을 소개합니다.
* Xamarin Beta Release: Cycle 9 RC Refresh Builds : Bri Brothers가 Xamarin Beta -Cycle 9 RC 버전을 소개합니다.
* Mobile Composer Transforms Products, People, and Processes with Xamarin Apps : Lacey Butler가 Xamarin 플랫폼의 성공 사례로서 컨설팅 회사 "Mobile Composer"를 소개합니다.
* Ship Better Apps Faster with the Mobile Center Webinar Series : Keith Ballinger가 Visual Studio Mobile Center (현재 프리뷰 버전)관련 웨비나 시리즈 소식을 공유했습니다.
* Learn More About Mobile Center with Our New Webinar Series : HockeyApp Team이 Visual Studio Mobile Center와 관련된 웨비나 시리즈 정보를 공유했습니다.
* Planet Xamarin: Follow Your Favorite Community Bloggers & Lightweight Ads for Android Apps : James Montemagno가 Xamarin에서 활용할 수 있는 Xamarin 관련 커뮤니티 블로깅 수집 사이트 ‘Planet Xamarin’와 구글의 모바일 광고 플랫폼 ‘AdMob’을 소개합니다.
* Announcing the Newest Xamarin MVPs! : Jayme Singleton이 새롭게 선정된 Xamarin MVP 멤버들을 소개합니다.
* Xamarin.iOS Build Mechanics by Xamarin : 이 가이드에서는 iOS 애플리케이션의 시간을 정하는 방법과 프로젝트의 빌드 구성 및 옵션에 따른 고려사항에 관해 소개합니다.
* Simplified In-App Purchases for Xamarin iOS and Android & Opening App Store for Ratings on iOS and Android : James Montemagno가 iOS, Android App에서 In-App 결제 기능을 간단히 구현하는 방법와 평가를 위한 앱스토어 오픈 방법을 소개합니다.
* The Xamarin Show – Snack Pack 7: Plugins for Xamarin and Windows : James Montemagno가 Snack Pack 4 시리즈의 “Plugins for Xamarin and Windows”편을 공유하였습니다.
* Creating .NET Bindings for C Libraries with ObjectiveSharpie : Miguel de Icaza가 Objective-C API를 C# 코드로 자동 생성 및 매핑해주는 툴 "ObjectiveSharpie"을 소개합니다.
* Incremental ListView Control and Plugin for Xamarin.Forms : John Miller가 Xamarin.Form의 Incremental ListView Control에 관해 소개합니다.
* Introduction To Exrin (Video), Xamarin Forms Debugging The WebView In Chrome, & Cookie Sharing with WebView and the Http Client : Adam Pedley이 Xamarin Forms용 MVVM framework "Exrin" 소개, 크롬에 포함된 WebView를 디버깅 하는방법, WebView와 Http Client가 쿠키 정보를 공유하는 방법을 소개했습니다.
* Attached Properties – What Are They Good For? : Matthew Soucoup이 Attached Property에 관해 소개합니다.
* Xamarin Mac Agent–Unable to connect : David Yardy가 Xamarin Mac Agent에 접속 불가했던 상황을 공유했습니다.
* How To Design Eye-Catching App Icons : Michael Flarup이 모바일용 아이콘을 눈에 띄게 디자인하는 방법을 소개합니다.
* More Than Just Pretty: How Imagery Drives User Experience : Nick Babich이 이미지를 디자인에 성공적으로 통합하는데 도움되는 유용한 원칙과 모범 사례를 소개합니다.

### UWP 소식
* Calling Windows 10 APIs From WinForms, WPF and more! : Michael Crump이 WinForms, WPF 환경에서 Windows 10 API를 호출하는 방법을 설명합니다.
* Observing system color changes in UWP apps : Martin Zikmund이 시스템 색상 변화를 감지하여 이를 확인 할 수 있는 App의 구현방법을 설명했습니다. 
* Time stamping AppX packages : Mattias Sjögren이 AppX package의 서명(signing)에 사용되는 Time stamp의 중요성과 의미를 설명합니다.
* Testing a desktop app converted with the Desktop Bridge in the proper way : Matteo Pagani가 Desktop Bridge를 사용하여 데스크탑용으로 변환된 애플리케이션의 올바른 기능 테스트 방법을 소개합니다.

### Game 소식
* Inventory and store system – Part 1 by Stacey Haffner가 RPG 게임의 아이템 상점과 인벤토리 구현 방법에 관해 소개합니다.
* Top 10 Unity tips : Brackeys가 Unity 개발에 도움이 되는 팁 10가지를 공유했습니다.
* Blender table animation in Unity 5 : Jay AnAm이 Unity painter texture를 사용하여 Blender table 모델을 Unity 5로 가져오고 애니메이터 컨트롤러와 C# 스크립트로 애니메이션을 재생하는 방법을 소개합니다.
* Hex Map 13: managing maps : Catlike Coding가 육각형 지도에 관한 튜토리얼 13번째 시리즈를공유하였습니다.
* MonoGame – Engines, frameworks & more : Simon Jackson이 MonoGame 엔진, 확장 컴포넌트에 관해 소개합니다.
* [Unity 5] Tutorial: how to create an infinite background (2D) : Gamad에서 끝없는 배경(2D) 구현방법을 소개합니다.

// 전무님 소개
//  닷넷
