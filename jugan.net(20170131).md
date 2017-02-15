### On .NET 소식

이번주에는 두개의 쇼가 진행었습니다. 하나는  Kendra Havens, Kasey Uhlenhuth, Maria Naggaga Nakanwagi, Donovan Brown그리고 Scott Hanselman와 함께 기술을 연설 잘하는 방법과 각자의 노하우에 대해서 얘기했습니다

//그림

두번째 쇼에서는 Patrick Smacchia가 최신 버전의 ndepend 코드 툴을 소개해 주었습니다.

//그림


### 금주의 툴: CrazyCore
.NET 팀의 개발자인 Eric Mellino은 요즘 여가시간을 활용하여  자작 게임 엔진구현에 몰두해있습니다.  게임엔진의 이름은 CrazyCore(링크)인데 초기버전이기는 하지만 여러모로 상당히 의미있는 엔진입니다. 이 엔진은 오픈소스형태로 진행중이며 다중 플렛폼을 지원하고 .NET Core 환경에서 동작합니다. Eric Mellino가  .NET Core에는 없는 게임 엔진에 필요한 다양한 기능을 어떠한 형태로 라이브러리에 구현할지 앞으로 관심을 가져볼만 한것 같습니다.

// 그림

CrazyCore에 대한 좀 더 자세한 내용을 Eric Mellino의 블로그 포스트 ".NET Core에서  3D 게임 엔진 만들기"를 참고하세요

### 금주의 게임 : The Perils of Man
The Perils of Man은  롤 플레잉 스타일의 어드벤쳐 게임입니다. The Perils of Man에서 게임 플레이어는 사기꾼 과학자로 알려져 10년전 과학계에서 퇴출당한 과학자 Max Eberling 가 실종된 시점에서 게임을 시작합니다. 실종 사건과 관련하여  좀더 관심가져야 할점은 주인공 Max Eberling가 과학계에 퇴출되기 몇해전에 플에이어의 아버지역시 퇴출됬다는것입니다. 게임에서 플레이어는 Ana Eberling이라는 10대 소녀 역을 하게되며 Max라는 과학자에게 무슨일이 있었는지 수수깨끼를 푸는 역활을 하게됩니다. 게임진행중 시간여행을 통해서 얻은 정보들과와 다수의 사건들의 인과관계를 유추하여 오래된 이 세기의 미스테리를 푸는것이 게임의 미션입니다.

//그림  

The Perils of Man(링크)는 IF Games(링크)와 Vertigo Games(링크)의 합작으로 개발되었으며  C#(링크)과   Unity(링크)를 이용하여 개발되었습니다. 현재 Steam과 iTunes을 통해서 즐기실 수 있습니다. 

### .NET 소식
* [Virtual Panel: What’s Next for .NET?](https://www.infoq.com/articles/virtual-panel-dotnet-future) : Pierre-Luc Maheu가  .NET의 향후 비젼과 다음 버전에 대해서 토의한 내용을 공유했습니다.
* Open sourcing the VS Test platform : Brian Harry가 "VS Test platform" 오픈 소스 프로젝트를 소개했습니다.
* Publishing .NET Core NuGet packages : Ryan Stelly가 .NET Core의 NuGet package 배포 방법을 설명했습니다.
* Announcing a new documentation experience: easy to customize API, content/wiki pages, and blog posts in the new Wyam Docs recipe : Dave Glick이 문서작성 오픈소스 라이브러리 프로젝트 Wyam Docs를 소개했습니다.
* How to print a GIF " stupotmcdoodlepip에서 GIF 파일의 프린트 방법을 설명했습니다.
* Common code style in Visual Studio 2017 and VS 2017 + new csproj = useful or useless? : Piotr Stapp이 VS2017에 새롭게 적용된 Editor Config(링크:http://editorconfig.org/)를 통한 코딩스타일 설정 방법(링크)과 VS2017에 변경된 프로젝트 타입 csproj 에 대해서 설명(링크)했습니다.
* What happened to my Thread.CurrentPrincipal : David Pine이 ASP.NET Core의 Thread.CurrentPrincipal을 설명했습니다.
* C# 7.0 expression bodied members : Christian Nagel이 C# 7.0의 "expression bodied member" 기능을 설명했습니다.
* .Net Core, Roslyn and code generation : Carlos Mendible이 .Net Core환경에서 컴파일러 Roslyn 과 코드 생성에 대해서 설명했습니다.
* Adding Files to Visual Studio Projects : Rick Strahl이 Visual Studio Project에 새로운 파일 아이템의 추가시 알아두면 도움이 되는 관련 기능을 설명했습니다.
* Debugging .NET Core on Unix over SSH : Gregg Miskelly이 SSH(Secure Shell)을 이용해서 유닉스의 .NET Core 어플리케이션을 디버깅 하는 방법을 설명했습니다.

### ASP.NET 소식
* Microsoft Security Advisory 4010983: Vulnerability in ASP.NET Core MVC 1.1.0 Could Allow Denial of Service : ASP.NET Core MVC 1.1.0 에서 발견된 보안 취약점을 해결하기위한 방법이 공유되었습니다. 
* ASP.NET Core Authentication with IdentityServer4 : Mike Rousos가 ASP.NET Core 에서 IdentityServer4 를 이용한 사용자 인증관리 방법을 설명했습니다.
ㅍDocker compose with ASP.NET Core, EF Core and the PostgreSQL image : Damien Bod이 PostgreSQL 을 사용하는 ASP.NET Core App를 도커 컨테이너에 셋업하는 방법을 공유했습니다.
* Reloading strongly typed options in ASP.NET Core 1.1.0 : Andrew Lock이 ASP.NET Core 1.1.0엣 외부 설정파일에 저장된 여러 사용자 옵션값의 (변화가 있을때)최신값을 다시 로드하는 효과적인 방법을 설명했습니다.
* A file upload API with Nancy, .NET Core in a shockingly small amount of code : NandoTech가  Nancy, .NET Core API 를 이용한 파일 업로드 방법을 소개했습니다.
* Introducing Alba for integration testing against ASP.Net Core applications : Jeremy D Miller가 ASP.Net Core  어플리케이션용 통합 테스트  오픈소스 라이브러리 Alba (링크)를 소개했습니다.
* ASP.NET Core – Migrating to MSBuild : Aaron Marisi가 ASP.NET Core의 기존 JSON기반으로 구성된 프로젝트 파일을 MSBuild용으로 프로젝트(csproj)로 전환하는 방법을 설명했습니다.
* Building complex UI components with ASP.NET Core MVC Tag Helpers : Scott Addie가 ASP.NET Core MVC Tag Helper를 이용해서 복잡한 기능의 UI 컴포넌트를 개발하는 방법을 설명했습니다.
* Building microservices with ASP.NET Core (without MVC) : Filip W가 ASP.NET Core (MVC 포함않된)를 이용한 micro service의 구현방법을 설명했습니다.
* Building simple plug-ins system for ASP.NET Core : Gunnar Peipman이 ASP.NET Core에서 plug-in 시스템 기능의 구현방법을 설명했습니다.

### F# 소식
* Learning Visual F# – Foundations : "Learning Visual F#" 서적이 소개되었습니다.
* Modeling state in action, : Isaac Abraham이 F#에서 상태관리방법(모델링)에 대해서 설명했습니다.
* Fiddling with ASP.NET Core with F# and Suave, : Shane Logsdon이 F# 과 Suave를 이용한 ASP.NET Core App 개발 방법을 설명했습니다.
* F# – How to keep domain pure when logic depends on current date, : Lauri Taimila가 최대한 현재 날짜에 의존적이지 않은 함수형 프로그램(functional programming) 개발 방법에 대해서 소개했습니다
* Authentication for WebSharper sitelet with JWT token in F#, : Kimserey Lam이 WebSharper sitelet에서 F#으로 JWT(JSON Web Token )토큰 인증방법을 설명했습니다.

### Azure 소식
* Manage App Service, SQL Database, and more – Azure Management Libraries for .NET : Asir Selvasingh가 App Service, SQL Database 등을 관리할 수 있는 "Azure Management Libraries for .NET" Beta4를 소개했습니다.
* Azure Tools for Visual Studio Code 1.2.0 – ARM export, batch, telemetry : Brady Gaster가 최근 공개된 Azure Tools for Visual Studio Code 1.2.0 버전의 기능을 소개했습니다.
* How To Build Planet Scale Mobile App in Minutes with Xamarin and DocumentDB : Kirill Gavrylyuk이 Xamarin과 DocumentDB를 이용한 고가용성 모바일 App를 빠르고 효과적으로 구축하는 방법을 소개했습니다.
ㅍUsing Azure Functions to add a Contact Form to a Static Site : Eli Weinstock-Herman이 정적 웹사이트의 "담당자 연락 페이지(contact form)"에 Azure Function기능을 활용하는 방법을 설명했습니다.

### Xamarin 소식
* Visual Studio for Mac – Preview 3 : Adrian Murphy가 Visual Studio for Mac – Preview 3 버전을 소개했습니다.
* Xamarin Beta Release: Cycle 9 RC Refresh Builds : Bri Brothers가 Xamarin Beta -Cycle 9 RC 버전을 소개했습니다.
* Mobile Composer Transforms Products, People, and Processes with Xamarin Apps : Lacey Butler가 Xamarin 플랫폼의 성공사례로서 컨설팅 회사 "Mobile Composer"를 소개했습니다.
* Ship Better Apps Faster with the Mobile Center Webinar Series : Keith Ballinger가  Visual Studio Mobile Center (현재 프리뷰 버전)관련 웨비나 시리즈 정보를 공유했습니다.
* Learn More About Mobile Center with Our New Webinar Series : HockeyApp Team이 Visual Studio Mobile Center 관련 웨비나 시리즈 정보를 공유했습니다.
* Planet Xamarin: Follow Your Favorite Community Bloggers & Lightweight Ads for Android Apps : James Montemagno가 Xamarin관련 커뮤니티 블로깅 수집 사이트 Planet Xamarin(링크)와 구글의 모바일 광고 플랫폼인 AdMob의 활용방법(링크)를 소개했습니다.
* Announcing the Newest Xamarin MVPs! : Jayme Singleton이 새롭게 선정된 Xamarin MVP 멤버들이 공개되었습니다.
ㅍXamarin.iOS Build Mechanics by Xamarin : Xamarin.iOS App의 빌드과정과 옵션등을 설명했습니다.
ㅍSimplified In-App Purchases for Xamarin iOS and Android & Opening App Store for Ratings on iOS and Android : James Montemagno가  iOS, Android App에서 In-App 결제(어플 내부에서 결재)기능을 간단히 구현하는 방법(링크)와 어플의 평가를 위해서 App 스토어를 오픈하는방법(링크)을 설명했습니다.
* The Xamarin Show – Snack Pack 7: Plugins for Xamarin and Windows : James Montemagno가 시리즈  "Snack Pack 4: Plugins for Xamarin and Windows" 동영상을 공유했습니다
* Creating .NET Bindings for C Libraries with ObjectiveSharpie : Miguel de Icaza가 Objective-C API를 C# 코드로  자동생성및 매핑해주는 툴 "ObjectiveSharpie"을 소개했습니다.
* Incremental ListView Control and Plugin for Xamarin.Forms : John Miller가 Xamarin.Form의 Incremental ListView Control 을 설명했습니다.
* Introduction To Exrin (Video), Xamarin Forms Debugging The WebView In Chrome, & Cookie Sharing with WebView and the Http Client : Adam Pedley이  Xamarin Forms용 MVVM 프레임워크인 "Exrin"의 동영상 소개(링크)와, 크롬에 포함된 WebView 를 디버깅 하는방법(링크), WebView와 Http Client가 쿠키정보를 공유하는 방법(링크)을 소개했습니다.
* Attached Properties – What Are They Good For? : Matthew Soucoup이 Attached Property를 설명했습니다.
* Xamarin Mac Agent–Unable to connect : David Yardy가 Xamarin Mac Agent에 접속 불가했던 상황을 공유했습니다.
* How To Design Eye-Catching App Icons : Michael Flarup이 돋보이는 모바일용 아이콘의 디자인 방법을 설명했습니다.
* More Than Just Pretty: How Imagery Drives User Experience : Nick Babich이 이미지및 배경의 활용이 UX에 미치는 영향에 대해서 설명했습니다.

### UWP 소식
* Calling Windows 10 APIs From WinForms, WPF and more! : Michael Crump이 WinForms, WPF등의 환경에서 Windows 10 API를 호출하는 방법을 설명했습니다.
* Observing system color changes in UWP apps : Martin Zikmund이 시스템 색상 변화를 감지하여 이를 확인 할 수 있는 App의 구현방법을 설명했습니다. 
* Time stamping AppX packages : Mattias Sjögren이 AppX package의 서명(signing)에 사용되는 Time stamp의 중용성과 의미를 설명했습니다.
* Testing a desktop app converted with the Desktop Bridge in the proper way : Matteo Pagani가 Desktop Bridge를 이용하여 데스크탑용으로 변환된 app기능을 테스트하는 올바른 방법을 설명했습니다.

### Game 소식
* Inventory and store system – Part 1 by Stacey Haffner.
* Top 10 Unity tips : Brackeys가 Unity 를 이용한 개발에 도움이 되는 팁 10가지를 공유했습니다.
* Blender table animation in Unity 5 : Jay AnAm이 Unity 5의 animation 설정용 Blender table 을 설명했습니다.
* Hex Map 13: managing maps by Catlike Coding.
* MonoGame – Engines, frameworks & more : Simon Jackson이 MonoGame : 엔진, 확장 컴포넌트등을 소개했습니다.
* [Unity 5] Tutorial: how to create an infinite background (2D) : Gamad에서 끝이 보이지않는 배경(2D)의 구현방법을 설명했습니다.

// 전무님 소개
