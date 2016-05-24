 5/15일 ASP.NET Core RC2, .NET Core RC2, and the preview 1 of the associated SDK. We also released Entity Framework Core RC2 가 릴리즈 되었습니다.
* .NET Core RC2 SDK Preview 1 download
* .NET Core RC2 Announcement
* ASP.NET Core RC2 Announcement 
* Release notes
새로운 닷넷 개발 정보 웹사이트가 오픈 되었습니다. 주소는 아주 단순하게 dot.net 이네요.

### On.NET 소식
지난번 On.NET 인터뷰에는 5/15일 날짜로 저희가 릴리즈한 .net 기술들에 대해 얘기 했습니다. 
이번주는 On.NET 인터뷰의 1회 초대손님이였던 Miguel de Icaza를 다시 모시고 얘기해볼까 합니다.

### 금주의 툴 - Web Accessibility Checker
개발된 웹사이트의 웹 접근성을 항상 확인한다는 것은 그리 즐거운 일만은 아닙니다. 하지만 만약 여러분의 개발코드 스스로 웹표준에 근거해서 웹접근성을 체크해줄 수 있다면 얼마나 편리할까요? 그리고 웹 표준에 위반되는 항목은 비주얼스트디오의 에러리스트에 결과항목으로 나올 수 있다면 많은 도움이 되겠죠?
Mads Kristensen의 Web Accessibility Checker를 이용하면 위에서 얘기한 기능들을 실제로 사용할 수 있습니다.

//그림

### 금주의 Xamarin 애플리케이션 - Xactware
Xactware 회사는 북미지역의 주택보험 보상, 주택하자 관련 분쟁들중 전체의 약 80%를 처리하고 있습니다. 이는 금액으로 환산하면 한해에 $340 빌리언(3400억원, 헉~! 약400조???, 맞나요?)에 해당합니다. Xactware는 기존에 개발된 C# 코드와 Xamarin을 이용하여 iOS및 Android용 모바일 어플 Xactimate을 만들었습니다. 담당자는 이를 이용하여 현장에서 하자항목을 관리하고 직접 3차원 주택의 설계도를 구성하며, 현장에서 바로 예상 비용을 산정할수있습니다. 또 이러한 모든 정보를 즉시 서버에 전송할수도 있습니다.

//이미지  

### 금주의 게임 - Dex
이번주 소개해 드릴 게임은 Dex입니다. Dex는 아주 잘 구성된 2차원 픽셀 형태의 게임입니다. 올드하다고 느끼실 수 있는 2차원 픽셀 스타일이긴 하지만 실제 게임의 느낌은 뭔가 꽤 현대적입니다. 좌우로 스크롤되는 스타일의 엑션/RPG게임으로 아름다운 배경 그래픽과 현란한 효과가 돋보입니다. 초기 오프닝이나 중간중간 스토리를 전해주는 컷신(cut scenes)은 마치 전에 읽었던 잘그려진 만화책을 보는듯하며 게임의 내용과 아주 잘어울립니다.

//이미지  

게임은 플레이어가 하버프라임의 "사이버펑크 시티"라는 가상의 도시에 떨어지면서 시작하게 됩니다. 플레이어는 이 도시의 거리를 활보하고 탐험하면서 임무를 완성하게 됩니다. 플레이어 레벨이 따라서 캐렉터를 플레이스타일에 맞게 설정 할 수 있습니다. 예를 들면 적과 마추치게될 경우 조용히 접근해서 대화를 할 것인지 아니면 총을 마구 쏠것인지 플레이서가 선택할 수 있습니다.  또한 게임안에서는 플레이어의 의식을 디지털화하여 적의 전자 방어시스템에 침투한후 미션을 수행할수도 있습니다.

Dex는 Dreadlocks LTD에의해서 Unity와 C#으로 만들어졌습니다. 현재 Linux, Mac and Windows에서 플레이가 가능합니다. 또한 가까운시일에 Good Old Games (GoG), Xbox One and PlayStation 4에서도 플레이가 가능할 예정입니다.

좀 더 자세한 정보는 [Made With Unity]페이지에서 확인하실 수 있습니다. 

### .NET 소식

* .NET Core RC2 가 발표되었습니다
* A billion is cool by Phil Haack, and Nuget’s post on the same topic with some cool stats : Phil Haack가 Nuget 패키지가 10억건 다운로드를 기록한 소식(링크)을 전해주었습니다. 또한 몇가지 부가적인 통계정보와 함께 동일 내용이  [링크]에도 게시되었습니다. 
* Visual Studio “15” Preview 2 : John Montgomery가 Visual Studio “15” Preview 2의 정보를 공유해주었습니다.
* All Together Now: .NET, RHEL, Hyper-V and VSCode : Don Schenck가 기업용 리눅스인 Red Hat Enterprise Linux(RHEL) 환경에서 .NET, Hyper-V 그리고  VSCode을 이용한 작업방법을 공유해주었습니다.
* ServiceStack, a journey into the madness of microservices, part 3 : Scott Mackay 가 "ServiceStack"를 설명한 마이크로서비스 시리즈 3편을 공유해주었습니다.
* Automated Testing of Message Based Systems, and How we do Semantic Logging : Jeremy Miller이 메시지 기반 시스템에서 테스트자동화에 대해서 공유[링크]해주었으며 의미있는 로그를 체계적 남기는 방법에 대해서 공유[링크]해주었습니다. 
* Announcing MSBuild Structured Log: record and visualize your builds : Kirill Osenkov가 MSBuild 의 구조화된 로그정보 체계인 "MSBuild Structured Log"를 공유해주었습니다.
* Welcoming Protobuild to the .NET Foundation by the .NET Foundation : Protobuild 가  .NET Foundation의 멤버가 되었습니다.
* The Business Case for Actors and Akka.NET : Aaron Stannard이 Akka.NET 개발 환경에서 Actors 모델에 대해 설명해주었습니다.
* Fun with Expressions : robmikh이 Expressions 에 대해서 소개해 주었습니다.

### ASP.NET 소식
* ASP.NET Core RC2 Announcement : ASP.NET Core RC2가 발표되었습니다.
* Notes from the ASP.NET Community Standup – May 10, 2016 : Jeffrey T. Fritz 가 5/10 ASP.NET Community Standup 행사에서 있었던 내용을 정리했습니다.
* Upgrading from ASPNET Core RC1 to RC2 Guide : Steve Smith가 ASPNET Core RC1에서 RC2 로 업그레이드 하는 방법을 가이드 해주었습니다.
* Getting Ready for ASP.NET Core RC2, Converting an ASP.NET Core RC1 Project to RC2, and Writing API Controllers in ASP.NET MVC 6 : Shawn Wildermuth이  ASP.NET Core RC2, ASP.NET Core RC1 프로젝트를 RC2로 변환하는 방법[링크]과  ASP.NET MVC 6에서 API Controllers 를 구현하는 방법[링크]에 대해서 공유해주었습니다.
* ASP.NET Core RC2, Docker and HipChat Connect add-on : Laurent Kempé이 ASP.NET Core RC2, Docker 그리고HipChat Connect 에드온에 대해서 설명해주었습니다.
* 5 Factors to Consider When Converting a WebForms App to ASP.NET MVC Core : Jonathan Danylko이  WebForms App 을 ASP.NET MVC Core 프로젝트로 변환할 경우 주의해야 할 사항 5가지를 소개해주었습니다.
* NDC Oslo Web API sample updated to ASP.NET Core RC2, and IP Filtering in ASP.NET Web API by Filip W. : Filip W가 과거에 자신이 진행한 기술 세미나 샘플을 ASP.NET Core RC2버전으로 업데이트했다는 소식[링크]과 ASP.NET Web API 프로젝트에서 IP 필터링하는 방법에 대해서 공유해주었습니다.
* Modulus: Commercial Docker Containers for running ASP.NET Core Applications by Lohith. : Telerik에 근무하는 Lohith가 자사에서 개발되고있는 ASP.NET Core용 상용 Docker Containers인 "Modulus"에 대해서 소개해 주었습니다.
* Microservice with ASP.NET Core & MVC 6 on Linux : Michał Ogłuszka이 ASP.NET Core & MVC 6 환경에서 리눅스에서 마이크로서비스를 사용하는 방법을 설명했습니다.
* Using the C# 6.0 nameof Operator in ASP.NET MVC Razor Views : Jason Roberts이 ASP.NET MVC Razor Views 에서 C# 6.0의 nameof 연산자 사용법에 대해서 설명해주었습니다.

### Xamarin 소식
* Xamarin.iOS, the garbage collector and me : Krumelur가 Xamarin.iOS의 가비지 컬렉터의 정보를 공유해주었습니다??? 
* Realm Xamarin, a reactive database for .NET developers. : Xamarin 환경에서 " SQLite"을 대체할 수 있는 새로운 모바일 데이터베이스 엔진 "Realm Xamarin"을 소개하였습니다.
* The first ever pull request to Xamarin Forms by thebeekeeper : Xamarin Forms의 버그수정사항이 공유되었습니다.
* Jason Smith’s Xamarin Forms Performance Tips : Kent Boogaart이 Xamarin Forms의 성능 향상을 위한 팁을 공유해주었습니다.
* MvvmCross Hamburger menu for iOS : Marc Bruins이 iOS 에서 사용할 수 있는 MvvmCross의 헴버그메뉴를 소개해주었습니다.
* Xamarin Dev Ops with VSTS – Getting Started : Richard Woollcott이 Xamarin 모바일 개발/운영환경에서 VSTS 의 활용방법을 가이드 해주었습니다.

### F# 소식
* Releasing F# Language Documentation as Open-Source : Den Delimarsky F# 문서가 오픈소스 형태로 릴리즈 되었습니다.
* New Visual F# Portal with Open Source content : 오픈소스 컨텐츠[링크]를 포함한 새로운 비주얼 F# 포털[링크]이 릴리즈 되었습니다.
* Functional Web Applications using F# and Suave, : Tomas Jansson가 F#을 이용한 함수지향적 웹 어플리케이션 구현에 대해서 소개해주었습니다.
* Functions Composition in F# and Scala, : Victor Michaïlovich이 F# 과 Scala를 이용한 함수의 구성에 대해서 설명하였습니다
* Exploring Azure with F# Azure Storage Type Provider : Pierre-Luc Mahe이 Azure 에서 사용할 수 있는 F# Azure Storage Type Provider에 대해서 설명해주었습니다. 

### Games
* [Build A Unity Game Part 2 (video)] : Stacey Haffnerrk 가 Unity 개발 환경에서 게임의 배경을 만들고, Visual Studio 의 스크립트를 작성하는 방법 파트2 을 소개했습니다. 
* Unity and IPv6 Support, : Mantas Puida가 유니티에서 IPv6 를 활용하는 방법을 설명하였습니다.
