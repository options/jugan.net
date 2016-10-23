주간닷넷 2016년 9월 27일

### On .NET 소식
[지난 주 On .NET]()에는  JB Evain와  Visual Studio 2015 Tools for Unity, 그리고 .NET 프로파일링 오픈소스 라이브러리 Cecil에 대해서 얘기 나누어보았습니다.

// 동영상

[이번 주 On .NET]()에는 .NET team의 Immo Landwerth와  NetStandard 2.0(링크)에 대해 얘기를 나누어 보겠습니다.

### 금주의 패키지  -  NAudio
Naudio는 오디오 파일의 읽기, 쓰기 ,디코딩,  인코딩, 컨버팅 작업등을 손쉽게 처리해 주는 라이브러리입니다.

아래의 코드는 여러 오디오 파일 정보를 화면에 표시하는 예입니다.

// 코드

### 금주의 자마린 어플 - Speech Central
iPhone 어플 Speech Central은 인터넷 웹 페이지의 화면을 직접 보고 있지 않고도 음성명령을 통해서 탐색하고 페이지의 내용을  읽어주는 어플입니다.
화면을 보고있지 않아도 되기 때문에  조깅, 대화등 일상생활 활동 중에도 웹을 통해서  항상 새로운 뉴스를 전달 받으실 수 있습니다. 또한 화면이 꺼져있는 상태에서 동작가능하므로 베터리소모량도 적습니다.

### 금주의 게임 - Hand of Fate
게임 Hand of Fate은 액션, RPG , 덱빌딩 게임장르의 요소가 복합되어 구성된 게임입니다.  게임에서 플레이어는 전략적인 결정을 통해 자신의 덱을 쌓아가야 하며  진행된 덱에 따라서  RPG 액션 스타일의  게임이 진행되기도 합니다. 게임 Hand of Fate은 독특한 덱 빌딩 구조과  다양한 적, 아이템, 무기, 장비 등이 포함되어있습니다.

//그림

Hand of Fate(링크)은  Unity(링크)와 C#(링크)을 이용하여  Defiant Development(링크)에서 제작 했으며 현재   Xbox One, PlayStation 4에서 지원되며 Steam(링크)을 통해서 Windows, Mac, Linux 에서도 즐기실 수 있습니다.

### .NET 소식
* Scientist.NET 1.0 released! : Phil Haack가 Scientist.NET 1.0 의 릴리즈 소식을 공유했습니다.
* TLS 1.2 Comes to Mono - Update : Miguel de Icaza가 TLS 1.2  버전 소식을 공유했습니다.
* Storing and using secrets in Azure : Bertrand Le Roy가 Azure 환경에서 보안에 민감한 정보를 안전하게 저장하고 접근할 수 있도록 해주는 Azure 기능 "Key Vault"를 설명했습니다.
* An Experience Report of Moving a Complicated Codebase to the CoreCLR : Jeremy D. Miller가 기존 코드를 CoreCLR 코드로 전환한 경험을 공유했습니다.
* Implementing Seeding, Custom Conventions and Interceptors in EF Core 1.0 : Alina Popa가 EF Core 1.0의 Seed 방법, 커스텀 Convention 구현,  Interceptor 구현 방법을 설명했습니다.
* Cake for Visual Studio released and Announcing Cake for Yeoman : Alistair Chapman이 Visual Studio용 Cake 의 릴리즈 정보(링크)와 Cake의 Yeoman 지원 소식(링크)을 공유했습니다.
* How to debug a Cake file using Visual Studio Code : Martin Björkström이 Visual Studio Code를 이용한 Cake 파일 디버깅 방법을 공유했습니다.
* Optimising LINQ and Adding a verb to the dotnet CLI tooling : Matt Warren이 LINQ 최적화(링크)와 dotnet CLI tool에 사용자 명령을 추가하는 방법(링크)을 설명했습니다.
* Should I learn .NET Core?  : Jon Hilton 이  .NET Core의 개발 배경와 중요성을 설명했습니다.

### ASP.NET 소식
* Sharing Authorization Cookies between ASP.NET 4.x and ASP.NET Core 1.0 : Scott Hanselman이  ASP.NET 4.x and ASP.NET Core 1.0 어플리케이션에서 서로 쿠키인증 정보를 공유하는 방법을 설명했습니다.
* External Network Access to Kestrel and IIS Express in ASP.NET Core : Rick Strahl이 Kestrel 와 IIS Express 환경의  ASP.NET Core 어플리케이션에서 외부 네트위크에 접근하는 방법을 설명했습니다.
* Localising the DisplayAttribute and avoiding magic strings in ASP.NET Core and Injecting services into ValidationAttributes in ASP.NET Core by Andrew Lock이  ASP.NET Core 에서 지역화 문자열 표시를 위한 DisplayAttribute의 사용방법(링크)과 유효성 검증을 위한 ValidationAttributes 의 사용방법(링크)을 설명했습니다.
* IdentityServer4, Web API and Angular2 in a single ASP.NET Core project : Damien Bod이 하나의 ASP.NET Core 에서 IdentityServer4, Web API, Angular2를 사용하여 구성한 프로젝트를 설명했습니다.
* Introducing the ASP.Net Async SessionState Module : Matt FJH가 ASP.Net Async SessionState 모듈을 소개했습니다.
* Strongly typed configuration in ASP.NET Core without IOptions<T> : Filip W이 ASP.NET Core에서 IOptions<T>를 이용한 명시적(강력한) 타입 설정 파일의 사용 방법을 설명했습니다.
* ASP.NET Core MVC Attribute Routing : Derek Comartin이 ASP.NET Core MVC에서 Attribute Routing에 대해서 설명했습니다.
* Using OpenID Connect : Shaun Luttin이 OpenID Connect의 활용법을 설명했습니다.

### F# 소식
* Ionide F# 2.5.0 for VS Code is released, now you can write in F# Interactive! : VS Code에서 사용가능한  Ionide F# 2.5.0이 릴리즈되었습니다.
* Function Application and Composition : David Raab가 F#의 함수지향적 언어 문법의 구조와 특징을 설명하였습니다.
* Can programming be liberated from function abstraction?, : Tomas Petricek이 F# 프로그램에서 함수가 갖는 의미를 설명했습니다.
* Using the ALGLIB random forest with F#, : Mathias Brandewinder가 F#에서 수치해석 오픈소스 라이브러리 ALGLIB 을 이용한  random forest 활용 방법을 공유했습니다.
* Creating Slack Slash Commands With Azure Functions, : Greg Shackles가 Azure Function을 사용하여 Slack Slash Command를 구현하는방법을 공유하였습니다.
* BuildStats.info |> F#, : Dustin Moris Gorski가 빌드 상황을 표현해주는 그래픽 위짓인 BuildStats.info의 사용 경험을 공유했습니다.

### Xamarin 소식
* Stable Release: Cycle 8 Service Release 0, Preview: Xamarin Profiler 0.34.2, Preview: iOS Simulator (for Windows) Update 5, and Alpha Preview: Xamarin.Mac Support on MacOS 10.12 Sierra : Adrian Murphy가 안정화 버전 릴리스:Cycle 8 Service Release 0(링크),  프리뷰 버전 : Xamarin Profiler 0.34.2(링크), 프리뷰 버전 : iOS Simulator (for Windows) Update 5(링크), 알파 프리뷰 : Xamarin.Mac의 MacOS 10.12 Sierra지원(링크) 등의 정보를 공유했습니다.
* HockeySDK 4.1.0 for Xamarin : HockeyApp Team에서 HockeySDK 4.1.0 for Xamarin을 소개했습니다.
* Iowa Caucuses Launch Inaugural Polling Apps with Xamarin : Lacey Butler가 미국 대선 아이와 당원대회  여론조사 모바일 어플이 Xamarin 으로 개발된 사례를 공유했습니다.
* Speech Recognition in iOS 10 : Pierce Boggan이 iOS 10에서 음성인식기능의 활용 방법을 공유했습니다.
* Enhanced Notifications in Android N with Direct Reply, Android Archiving and Publishing Made Easy, The Xamarin Show #3: Xamarin.Forms Performance Tips and Tricks, and Updating Azure Mobile SQLiteStore to 3.0 : James Montemagno가 Android N에서 Direct Reply를 이용한 향상된 알림(Notification)기능(링크),좀더 쉬워진 안드로이드 어플개발소스의 백업과 배포(링크),  Xamarin Show 3화 : 성능 튜닝 팁&트릭(링크),  Azure Mobile SQLiteStore 3.0 버전 소식(링크) 등의 정보를 공유했습니다.
* Background Audio and Cross Platform Development with Xamarin (App Dev on Xbox series) : Nikola Metulev가 UWP 어플에  배경음악을 추가하는 방법에 대해서 설명했습니다.
* Xamarin vs. Native, Default Designer, and Type Names as Storyboard IDs : Colby Williams가 Xamarin vs. Native, Default Designer, Storyboard ID 에 대해서 설명했습니다.
* Toast Notifications for Xamarin Forms, Proxy Pattern To Separate Dependencies, and Layered Dependency Injection : Adam Pedley가 Xamarin Forms의 알림기능(링크), 종속성 분리를 위한 Proxy Pattern, Layered Dependency Injection 에 대해 설명했습니다.
* Realities of Cross-Platform Development: How Platform-Specific Can You Go? : Wallace McClure가 크로스플랫폼 어플 개발시 Xamarin 환경이 각 플랫폼의 특징, 기능을  얼마나 잘 표현할 수 있는지 설명했습니다. 
* Debugging provisioning profiles on the command line : Larry O’Brien이  iOS, Xamarin에서 command line 명령을 이용해서 provisioning profiles 파일을 확인하는 방법을 공유했습니다.
* How To Design Error States For Mobile Apps : Nick Babich가 모바일 어플 개발시 적절한 예외 상황 정의와 올바른 예외 페이지 구현에 대해서 설명했습니다. 
* Back It On Up! Android and Xamarin and Backups! : Matthew Soucoup가 Android  환경에서 개인화 정보 저장/불러오기 기능 구현 방법을 설명했습니다. 
* Improving layout performance on Android : Tomasz Cielecki가 Android 의 layout 성능 향상 방법을 공유했습니다.
* Genymotion and VirtualBox install issue : Corrado Cavalli가 지니모션과 버추얼 박스를 이용해서 안드로이드 에뮬레이터 환경을 PC에 구축하는 방법을 공유했습니다.

### Azure 소식
* Azure Functions in practice : Troy Hunt가 Azure Functions 기능을 설명했습니다.

### Games 소식
* [Unity] Creating a 2D Platformer (E13. max slopes) : Sebastian Lague가 슈퍼마리오와 같은 2D Platformer(PLATFORM GAME) 장르의 게임 구현 방법을 설명했습니다.
* Unity – 2D Movement (Part 3B) – Jump : Standard Jump : Pixel Make에서 2D Movement (Part 3B)  - Jump 기능구현을 설명했습니다.
* Unity – 2D Movement (Part 4A) – Shoot : Spawn Bullet : Pixel Make에서 2D Movement (Part 3B)  - Shoot 기능구현을 설명했습니다.
* Curated #UnityTips No. 15 by DevDog October 2016 : DevDog가 Unity 개발에 도움이 될수있는 Tip 정보(15번째)를 공유했습니다.
* [Unity 5] Tutorial: How to make a climbing system like in Assassins Creed in Unity – part 9 :  Gamad에서 게임 Assassins Creed에서 케릭더의 오르기(등반) 동작과 같은 표현을  구현하는 방법을 설명했습니다.


// 전무님 소개
