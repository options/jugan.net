여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.
금주의 커뮤니티 소식
Taeyo.NET에서 [http://docs.asp.net](http://docs.asp.net)의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
•	[ASP.NET Core 보안 소개]( http://taeyo.net/Columns/View.aspx?SEQ=579&PSEQ=39)
•	[ASP.NET Core 보안 : 간단한 권한부여]( http://taeyo.net/Columns/View.aspx?SEQ=580&PSEQ=39)

### On .NET 소식
[지난 주 On .NET]( https://sec.ch9.ms/ch9/c18a/5cd42521-bbff-46a9-b303-31c76ed4c18a/20161222onnetstevesmith_high.mp4)에서는 Steve Smith와 짧은 인터뷰를 통해 Steve가 ASP.NET Core 개발에 기여한 일들과 관련 문서, 컨설팅 활동 그리고 Kickstarter의 software craftsmanship calendar 프로젝트에 관해 이야기 나누었습니다.

[이번 주 On .NET]( https://sec.ch9.ms/ch9/fc3f/7cb884b9-8303-4ac8-b5b9-617f77bffc3f/onnet12292016glennversweyveld_high.mp4)에서는 MVP Summit에서 만난 Glenn Versweyveld와 윈도우용 오픈소스인 Strava 클라이언트에 관해 이야기 나누어보겠습니다.

### 금주의 패키지: Jint
[Jint]( https://github.com/sebastienros/jint)는 완전한 [ECMA 5.1 규격]( https://github.com/sebastienros/jint/tree/es6)을 지원하는 .NET의 자바스크립트 인터프리터로 [.NET Framework 4.5와 .NET Standard 1.3 환경에서 실행 가능]( https://www.nuget.org/packages/Jint)하며, .NET 애플리케이션에 스크립트 기능을 추가하고자 할 때 사용할 수 있는 최고의 솔루션입니다. [RavenDB]( https://ayende.com/blog/160705/design-patterns-in-the-test-of-time-interpreter)는 Jint을 통해 사소한 데이터 변경을 수행하고 있으며, 게임에서도 스크립팅 엔진으로 사용되고 있습니다.
Jint를 이용한 자바스크립트 코드는 인터프리터에서 실행될 수 있을 정도로 간단명료하기 때문에 객체와 호출 인자 등의 동적 제어가 가능합니다.
// 코드

Jint의 상호 운용성은 간단한 변경을 통해 일반적은 타입과 제네릭 지원 타입 방식으로 사용할 수 있습니다.

### 금주의 게임 : Blue Effect
게임 [Blue Effect]( http://blue-effect.com/)는 1인칭 가상현실 슈팅 호러 게임입니다. 게임 스토리는 인류를 몰살하려는 에일리언 종족이 사는 행성 Exo-277에 주인공이 도작하는 것을 배경으로 합니다.
플레이어는 “Little Buddy”(무엇이든 녹일 수 있는 레이저건), “Enlightenment”(길을 비추는 원), “Blue Effect”(장비에 동력을 공급하는 희귀한 에너지)로 잔인한 외계인과 맞서서 생존해야 합니다.
Blue Effect는 Hide & Seek 모드를 통해 로컬 멀티 플레이가 가능합니다. Hide & Seek 모드에서 플레이어 1은 VR 헤드셋을 착용하고 3분 동안 에일리언 군단으로부터 생존해야 합니다. 플레이어 2는 게임 컨트롤러를 사용해 Blue Effect에서 등장하는 보스 에일리언 중 하나가 되어, 어둠에 숨어있는 친구를 찾아 두려워 말고 처치 해야하는 미션이 주어집니다.
//그림

[Blue Effect]( http://blue-effect.com/)는 [DIVR Labs]( http://divrlabs.com/)에서 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2016/12/28/the-week-in-net-on-net-with-steve-smith-jint/unity3d.com)와 [C#](http://divrlabs.com/)을 이용해 개발되었으며, 현재 게임의 early access버전을 [Steam]( http://store.steampowered.com/app/522020/)을 통해 HTC Vive 와 Oculus Rift에서 플레이하실 수 있습니다.

### .NET 소식
* The New and Improved Visual Studio 2017 RC: Ollie Bannsiter가 Visual Studio 2017 RC 버전의 기능을 리뷰하였습니다.
* Why Exceptions should be Exceptional : Matt Warren이 예외 처리의 중요성에 관해 설명합니다.
* Decimal vs Double and Other Tips About Number Types in .NET : Matthew Jones가 .NET의 Decimal, Double 등 숫자 타입 사용 시 알아야 할 팁을 공유했습니다.
* Akka.Net, Async/Await, .NET Core, Micro-ORMs and EFCore : 2016년 12월에 프랑스 파리의 개발 커뮤니티 “알트 넷(Alt.Net France)”의 3번째 번개 세미나가 개최되었으며, Maher Jendoubi가 해당 세미나 관련 내용을 공유하였습니다.
* Making bits faster and Dividing a bit in two for performance : Szymon Warda가 ‘효과적인 비트연산 방법’과 ‘비트값의 나누기 연산을 이용한 성능 향상 방법’에 관해 설명합니다.
* Gotchas with HttpClient’s CancelPendingRequests and Timeout in .NET : Maher Jendoubi가 HttpClient에서 보류 중인 요청을 모두 취소할 수 있는 기능인 CancelPendingRequests와 Timeout 기능 사용 시, 숙지해야 할 정보를 공유하였습니다.

### ASP.NET 소식
* Free Intermediate ASP.NET Core 1.0 Training on Microsoft Virtual Academy : Scott Hanselman이 ASP.NET Core 1.0 무료 교육 과정을 소개합니다.
* Redirecting unknown cultures when using the url culture provider : Andrew Lock이 ASP.NET Core 1.1의 필터 기능 중에서 미들웨어를 사용하여 응용 프로그램에 url Culture 공급자를 추가하는 방법에 관해 소개합니다.
* Page redirection and URL Rewriting with ASP.NET Core : Gérald Barré가 Page redirection과 URL Rewriting의 차이점에 관해 설명합니다.
* Your First Angular 2, ASP.NET Core Project in Visual Studio Code – Part 6 : Aaron Marisi가 Visual Studio Code에서 ASP.NET Core로 Angular 2 애플리케이션을 만드는 방법에 관해 설명합니다.
* Distributed Cache using Redis and ASP.NET Core : Petru Faurescu가 ASP.NET Core와 Redis를 이용한 분산 캐시 활용 방법에 관해 설명합니다.

### F# 소식
* Exploring F# with .NET Core and Kestrel : Shane Logsdon이 .NET Core에서 Kestrel과 F#의 활용방법을 공유하였습니다.
* Functional approaches to dependency injection : Scott Wlaschin이 F#에 DI(의존성 주입) 방법에 관해 설명합니다.
* Data structures and algorithms – helping Santa Claus find his road to San Francisco : Tomasz Jaskula가 알고리즘과 근본적인 데이터 구조의 핵심적인 세부 사항을 이해하는 방법에 관해 설명합니다.
* ReF#actoring: rewriting an actor in F# : Vagif Abilov이 Akka.NET의 actor 모델을 더욱 효과적으로 유지 보수할 수 있도록 리펙터링하는 방법에 관해 설명합니다.
* The Traveling Santa Problem… a Neural Network solution : Riccardo Terrell이 신경망(Neural Network) 솔루션을 이용한 최적 경로 탐색 방법에 관해 설명합니다.
* About Expandable F# Compiler project : Kouji Matsui가 오픈소스 프로젝트인 "Expandable F# Compiler(fscx)"에 관해 소개합니다.
* When Playstation meets F#, PSX |> Pi : Ross McKinlay와 Andrea McAts가 F#을 Playstation 컨트롤러와 라즈베리파이에 활용한 사례를 소개합니다.
* From Elm to Fable: trying F# In The Frontend : Lucas Reis가 기존에 사용하던 언어 Elm에서 F# 과 Fable을 사용하게 된 계기와 장점을 설명합니다.
* Evaluate JsonPath Queries using FSharp.Data : Jonathan Leaver가 FSharp.Data 오픈소스 라이브러리를 활용하여 JsonPath Querie를 구현하는 과정을 설명합니다.

### Azure 소식
* Service Bus, .NET Standard, and Open Source : John Taubensee가 .NET Standard client의 GitHub 공유 소식을 전합니다.
* Using Azure App Service Authentication with ASP.NET (Classic) MVC Applications : Adrian Hall이 ASP.NET MVC 애플리케이션에서 Azure App Service Authentication 서비스를 활용하는 방법에 관해 설명합니다.
* Getting started with Azure Functions and using them within Logic Apps : Steef-Jan Wiggers가 Azure Functions 사용 방법과 Azure Logic Apps에서 Azure Function을 활용하는 방법에 관해 설명합니다.

### Xamarin 소식
* Xamarin Stable Release: Cycle 8 Service Release 2 : Luis Aguilera가 Xamarin의 Cycle 8 Service Release 2 릴리즈 소식을 공유 했습니다.
* Xamarin Alpha Preview 6: Cycle 9 : Bri Brothers가 Xamarin Alpha Preview 6: Cycle 9 릴리즈 소식을 공유 했습니다.
* Android 7.1 Developer Preview Now Available : Miguel de Icaza가 Android 7.1 Developer Preview 릴리즈 소식을 공유 했습니다
* Build your Mobile Development Toolkit for 2017 : Cormac Foster가 2017년 상반기에 Xamarin 개발자가 놓쳐서는 안될 4가지를 공유하였습니다.
* Simple and Intuitive App Shortcuts in Android 7.1 : James Montemagno가 Android 7.1의 App Shortcut 기능에 관해 설명합니다.
* Xamarin Dev Days Available On-Demand : Jayme Singleton이 Xamarin Dev Days 녹화 영상 링크를 공유하였습니다.
* The Xamarin Show Snack Pack 4: Interactive Learning with Xamarin Workbooks : James Montemagno가 Snack Pack 4 시리즈 Interactive Learning with Xamarin Workbooks 편을 공유하였습니다.
* Going Serverless with Azure Functions: SendGrid : James Montemagno가 Azure Functions에 관해 설명합니다.
* Xamarin.Forms: Google AdMob Ads in Android & Xamarin.Forms: Google Admob Ads in iOS : James Montemagno가 Android에서 Google AdMob Ads 활용하는 방법과 iOS에서 Google AdMob Ads를 활용하는 방법을 설명합니다.
* Deploy the Android 7 Multi-Window Mode via Xamarin : Wallace McClure가 Xamarin.Android에서 지원하는 Android 버전 7의 주요 기능 중 Multi-Window Mode에 관해 설명합니다.
* Xamarin Forms Layout Engine, Under The Hood : Adam Pedley가 Xamarin Forms 레이아웃 엔진에 관해 설명합니다.
* How to Make an Android and iOS App in C# on a Mac : Demir Selmanovic이 Mac에서 C#으로 Android와 iOS 애플리케이션을 만드는 방법을 소개합니다.

### Data 소식
* Looking at Entity Framework Core 1.0 : Peter Vogel이 Entity Framework Core 1.0에 관해 소개합니다.

### Game 소식
* Take a look behind-the-scenes with design documents from The Legend of Zelda! : The Legend of Zelda 오리지날 버전의 디자인 제작 과정이 공유되었습니다.
* Object construction with factory method : Pasquale Franzese가 factory method를 이용한 객체 생성 방법을 공유하였습니다.
* [Unity 5] Tutorial: How to make an inventory system – part 1 (Video) : gamad에서 연재하는 "[Unity 5] Tutorial" 시리즈의 “인벤토리 시스템 구현” 편이 게시되었습니다.
* Generating Collision Meshes for a Voxel Chunk : Benjamin James Drury가 충돌을 감지하는 3차원 오브젝트 제작 방법에 관해 설명합니다.
* Procedural Landmass Generation (E17: texture shader) : Sebastian Lague가 연재하는 “Procedural Landmass Generation” 시리즈의 “texture shade” 편이 게시되었습니다.

// 전무님 소개
