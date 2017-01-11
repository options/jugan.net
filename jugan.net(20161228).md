
### On .NET 소식

[지난 주 On .NET]()(링크)에는 MVP 서밋에 참여한  Steve Smith와 함께 진행한 인터뷰를 올려드렸습니다. ASP.NET Core 와 Steve Smith가 직접 참여한 개발관련문서, 컨설팅 작업, 그리고 kickstarter의 software craftsmanship calendar 프로젝트에 대해서 얘기 나누었습니다.

다음주에는  MVP 서밋에 참여한 다른  MVP와의 인터뷰 동영상을 공유할 예정입니다.


### 금주의 패키지: Jint
Jint는 ECMA 5.1스팩을 완전하게 지원하는 .NET의 자바스크립트 인터프리터로 .NET Framework 4.5와 .NET Standard 1.3 환경에서 실행가능하며 .NET 어플리케이션에 스크립트 기능을 추가하고자 할때 사용할 수 있는 최상을 솔루션입니다. Jint는 이미 여러 플로젝트와 솔루션에서 이미 적용되고 있는데 RavenDB의 예를 들면 문서정보를 저장/이동시킬때 이 스크립트 엔진을 활용하고있습니다(링크). 또한  게임 엔진등에서 일반적으로 많이 사용될수있습니다.
Jint를 이용한 자바스크립트 코드는 인터프리터에서 실행될 수 있을 정도로 간단 명료하며 객체와 호출인자등의 동적 제어가 가능합니다.

// 코드

Jint의 스크립트는 타입시스템을 지원하며 더구나 제네릭이 포함된 타입 시스템의 활용도 가능합니다.

### 금주의 게임 : Blue Effect
게임 Blue Effect는 1인칭 가상현실 슈팅 호러 게임입니다.  게임은 플레이어가  인류를 몰살하려는 에일리언 종족이 살고있는 행성 Exo-277에 플레이어가 도작하는것을 배경으로 합니다.  플레이어는 자신이 가지고있는 강력한 무기인 레이저건을 이용하여 행성의 모든 에일리언들과 전투를 별이며 생존해야합니다. Blue Effect는 Hide & Seek 모드와 로컬 멀티 플레이모드를 지원합니다. Hide & Seek 모드에서는 두번째 플레이어가 어일리언을 역할을 컨트롤하게 됩니다.

//그림

Blue Effect는 DIVR Labs(링크)에서 Unity(링크)와 C#(링크)을 이용하여 개발되었으며 현재는 early access버전의 게임을 Steam을 통해서 HTC Vive 와 Oculus Rift에서 플레이하실수있습니다

### .NET 소식
* The New and Improved Visual Studio 2017 RC: Ollie Bannsiter가 Visual Studio 2017 RC 버전의 기능을 리뷰했습니다
* Why Exceptions should be Exceptional : Matt Warren이 예외 처리 방법의 중요성을 설명했습니다.?
* Decimal vs Double and Other Tips About Number Types in .NET : Matthew Jones가 .NET의 Decimal, Double 등의 숫자 타입 사용시 알아야할 팁을 공유했습니다.
* Akka.Net, Async/Await, .NET Core, Micro-ORMs and EFCore : Maher Jendoubi가 2016년 12월 파리에서 있었던 커뮤니티 Alt.Net에서 진행된 내용을 정리했습니다. 
* Making bits faster and Dividing a bit in two for performance : Szymon Warda가 효과적인 비트연산(링크) 방법과 비트값의 나누기 연산을 이용한 성능 향상(링크) 방법을 설명했습니다.
* Gotchas with HttpClient’s CancelPendingRequests and Timeout in .NET : Daniel Crabtree가 HttpClient의 CancelPendingRequest과 Timeout 에 대해 설명했습니다.

### ASP.NET 소식
* Free Intermediate ASP.NET Core 1.0 Training on Microsoft Virtual Academy : Scott Hanselman이 ASP.NET Core 1.0 무료 교육 과정을 소개했습니다.
* Redirecting unknown cultures when using the url culture provider : Andrew Lock이 지역언어(지역화)정보를 URL에 포함하는경우 알 수 없는 지역 언어의 예외적인 처리하는 방법을 설명했습니다.
* Page redirection and URL Rewriting with ASP.NET Core : Gérald Barré가 ASP.NET Core에서 Page redirection과 URL Rewriting 방법을 설명했습니다.
* Your First Angular 2, ASP.NET Core Project in Visual Studio Code – Part 6 : Aaron Marisi가 Visual Studio Code를 이용한 Angular 2 프로젝트 개발 방법을 설명했습니다. 
* Distributed Cache using Redis and ASP.NET Core : Petru Faurescu가 ASP.NET Core와 Redis 를 이용한 분산 캐시 활용 방법을 설명했습니다.

### F# 소식
* Exploring F# with .NET Core and Kestrel : Shane Logsdon이 NET Core에서 Kestrel과 F#의 활용방법을 설명했습니다.
* Functional approaches to dependency injection : Scott Wlaschin이 F#에서 DI(의존성주입)의 활용법을 설명했습니다.
* Data structures and algorithms – helping Santa Claus find his road to San Francisco : Tomasz Jaskula가 "데이터 구조와 알고리즘 : 센프란시스코에서 산타 길찾기 알고리즘"글을 게시했습니다.
* ReF#actoring: rewriting an actor in F# : Vagif Abilov이  Akka.NET 의 actor 모델을 좀더 효과적으로 유지보수할 수 있도록 리펙터링 하는 방법을 소개했습니다.
* The Traveling Santa Problem… a Neural Network solution : Riccardo Terrell이 신경망(Neural Network) 솔루션을 이용한 최적 경로 탐색 방법을 설명했습니다. 
* About Expandable F# Compiler project : Kouji Matsui가 오픈소스 프로젝트 "Expandable F# Compiler(fscx)"를 소개했습니다.
* When Playstation meets F#, PSX |> Pi : Ross McKinlay와 Andrea McAts가 F#을 이용한 Playstation 컨트롤러와 라즈베이파이의 활용 사례를 소개했습니다.
* From Elm to Fable: trying F# In The Frontend : Lucas Reis가 기존에 사용하던 언어 Elm에서 F# 과 Fable을 사용하게된 경험과 유용한 팁을 설명했습니다.
* Evaluate JsonPath Queries using FSharp.Data : Jonathan Leaver가 FSharp.Data 오픈소스 라이브러리를 활용하여 JsonPath Querie를 구현하는 과정을 설명했습니다.

### Azure 소식
* Service Bus, .NET Standard, and Open Source : John Taubensee가 .NET Standard client 가 GitHub에 등록되었다는 소식을 공유했습니다.
* Using Azure App Service Authentication with ASP.NET (Classic) MVC Applications : Adrian Hall이 ASP.NET MVC 어플리케이션에서 Azure App Service Authentication 서비스의 활용법을 설명했습니다.?
* Getting started with Azure Functions and using them within Logic Apps : Steef-Jan Wiggers가 Azure Functions의 기본 사용법과 Azure Logic Apps에서 Azure Function을 활용하는 방법을 설명했습니다. 

### Xamarin 소식
* Xamarin Stable Release: Cycle 8 Service Release 2 : Luis Aguilera가 Xamarin의 Cycle 8 Service Release 2 릴리즈 소식을 공유 했습니다.
* Xamarin Alpha Preview 6: Cycle 9 : Bri Brothers가 Xamarin Alpha Preview 6: Cycle 9 릴리즈 소식을 공유 했습니다.
* Android 7.1 Developer Preview Now Available : Miguel de Icaza가 Android 7.1 Developer Preview  릴리즈 소식을 공유 했습니다
* Build your Mobile Development Toolkit for 2017 : Cormac Foster가 2017년 상반기에 Xamarin 개발자가 잊지말고 해야할 4가지 사항을 공유했습니다.
* Simple and Intuitive App Shortcuts in Android 7.1 : James Montemagno가 Android 7.1의 간단하면서 직관적인 App Shortcut 기능을 설명했습니다.
* Xamarin Dev Days Available On-Demand : Jayme Singleton이 Xamarin Dev Days 행사 동영상이 공유되었다는 소식을 전했습니다.
* The Xamarin Show Snack Pack 4: Interactive Learning with Xamarin Workbooks : James Montemagno가 시리즈  "Snack Pack 4: Interactive Learning with Xamarin Workbooks" 동영상을 공유했습니다.
* Going Serverless with Azure Functions: SendGrid by James Montemagno가 시리즈 "Going Serverless with Azure Functions:SendGrid" 동영상을 공유했으며,  Azure Function에서 SendGrid를 통한 이메일 송신 방법을 설명했습니다.
* Xamarin.Forms: Google AdMob Ads in Android & Xamarin.Forms: Google Admob Ads in iOS : James Montemagno가 Android에서 Google AdMob Ads(링크) 활용하는 방법과 iOS에서 Google AdMob Ads(링크)를 활용하는 방법을 설명했습니다.
* Deploy the Android 7 Multi-Window Mode via Xamarin : Wallace McClure가 Android 7의 Multi-Window Mode를 지원하는 개발 방법을 설명했습니다.
* Xamarin Forms Layout Engine, Under The Hood : Adam Pedley가 Xamarin Form의 레이아웃 엔진의 내부적인 동작에 대해 설명했습니다.
* How to Make an Android and iOS App in C# on a Mac : Demir Selmanovic이 Mac에서 C#을 활용하여 Android와 iOS의 App 개발 방법을 설명했습니다.

### Data 소식
* Looking at Entity Framework Core 1.0 : Peter Vogel이 Entity Framework Core 1.0 을 소개했습니다.

### Game 소식
* Take a look behind-the-scenes with design documents from The Legend of Zelda! : 게임 "The Legend of Zelda"의 초기 오리지널 버전 제작 디자인 정보을 공유했습니다.
* Object construction with factory method : Pasquale Franzese가 factory method를 이용한 객체 생성 방법을 설명했습니다.
* [Unity 5] Tutorial: How to make an inventory system – part 1 (Video) : Gamad에서 "[Unity 5] Tutorial" 시리즈 "인벤토리 시스템 구현" 동영상을 공유했습니다.
* Generating Collision Meshes for a Voxel Chunk : Benjamin James Drury가 충돌감지 가능한 3차원 오브젝트 구성 방법에 대해 설명 했습니다.
* Procedural Landmass Generation (E17: texture shader) : Sebastian Lague가 시리즈 동영상 "E17: texture shade"를 공유했습니다.

// 전무님 소개
