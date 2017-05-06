### On .NET 소식

지난  주 On .NET 소식에서는Tamás Vajk, Olivier Gaudin과 함께  SonarLint(링크)와 SonarQube(링크)에 대해서 얘기 나누어 보았습니다.  .

//사진

이번  주 On .NET 소식에서는 Sébastien Ros(링크)과 함께  Orchard Core(링크) 프로젝트 구현경험과 더불어  ASP.NET 어플리케이션의 모듈화를 주제로 얘기 나눌예정입니다.  

### Happy Birthday .NET! - Dan Fernandez
지난 달 .NET birthday 파티에서 .NET 초기 멤버인 Dan Fernandez와 Visual Studio를 무료 배포등의 아이디어등 초기시절에 있었던 여러 애피소드에 대해 얘기 나누었습니다.  Dan 은 Channel9 의 원년 멤버이자 최고의 .NET 에반젤리스트 중 한명입니다.
//동영상

### 금주의 프로젝트: nopCommerce
 nopCommerce(링크)는 가장 인기있는 오픈소스 전자상거래 시스템중 하나로 ASP.NET MVC, Autofac, Entity Framework을 기반으로 구축된 시스템입니다. 현재까지 180만 다운로드를 기록하고있으며 100개이상의 파트너를 보유하고있고  Volvo, BMW, Puma, Reebok, Lacoste와 같이 유명 브랜드들이 이 시스템을 직접 사용하고 있습니다.

//사진

### .NET
* No GCs for your allocations? : Maoni Stephens이 가비지컬렉터의 메모리 수집을 억제 기능 "NoGCRegion"을 소개했습니다.
* .NET Core console app running on Raspberry Pi : Laurent Kempé이 라즈베리파이3 에서.NET Core 콘솔용 "Hello World" 어플 개발 방법을 설명했습니다.
* The .NET IL Interpreter : Matt Warren이  .NET의 IL Interpreter에 대해서 설명했습니다.
* Tracing Runtime Events in .NET Core on Linux and Tracing .NET Core on Linux with USDT and BCC : Sasha Goldshtein이 "리눅스  .NET Core 에서 이벤트 trace 활용 방법"(링크),  "리눅스  .NET Core 에서 USDT(User Statically Defined Tracing" 와 BCC(BPF Compiler Collection) 활용 방법"을  설명했습니다.
* Externalizing the HttpClient internals for fun & profit : Ayende Rahien이 HttpClient의 캡슐화된 내부기능의 외부 활용 방법과 예를 설명했습니다. 
* Building DockNetFiddle using Docker and .NET Core : Daniel Jimenez Garcia가 도커, .NET Core 환경에서 DockNetFiddle 구축 과정을 설명했습니다.
* Generate Documentation from Your Build : Erik Dietrich가 개발소스의 주석을 기반으로 문서를 생성해주는 문서자동화 툴 GhostDoc 을 소개했습니다.
* A TPL Actor Pattern : Jos Hickson이 Task Parallel Library (TPL) 액터 패턴을 소개했습니다.
* Cake and Fake on the ThoughtWorks technology radar :  빌드 자동화 툴인 Cake(http://cakebuild.net/)와Fake (http://fsharp.github.io/FAKE/)가 소개되었습니다.

### ASP.NET
* How to create your own templates for dotnet new : Sayed Hashimi가 dotnet new 명령어를 이용한 사용자 정의 템플릿의 활용 방법을 설명했습니다.
* ASP.NET Core Anatomy (Part 3) – UseMvc – Dissecting and understanding the internals of ASP.NET Core: Steve Gordon이 ASP.NET Core MVC 분석 (파트3)- "UseMvc" - ASP.NET Core 내부 이해하기: 편을 공유했습니다.
* Re-execute the middleware pipeline with the StatusCodePages Middleware to create custom error pages : Andrew Lock이 StatusCodePages 값과 middleware 재-실행을 통한 에러 페이지 구축 방법을 설명했습니다.
* Retrieving the path that generated an error with the StatusCodePages Middleware : Andrew Lock이 StatusCodePages 값을 활용하여 예외발생 경로를 얻는 방법을 설명했습니다.
* Hash Passwords with ASP.NET Membership Providers : Jeffrey T. Fritz가 ASP.NET Membership Providers의  Hash Passwords 기능 활용법을 소개했습니다. 
* Raspberry Pi: Run ASP.NET Core on Startup : Carlos Mendible이 라즈베리파이에서ASP.NET Core 어플리케이션을  OS 시작 시점에 실행하는 방법을 소개했습니다.
* Updating my AlbumViewer Sample to ASP.NET Core 1.1 and Angular 4 : Rick Strahl이 ASP.NET Core 1.1와 Angular 4을 이용해 자신의 AlbumViewer 샘플을 업데이트한 과정을 공유했습니다.
* Secure and explore ASP.NET Core Web APIs : Henrik Lau Eriksson이 JSON Web Tokens(https://jwt.io/), Swagger UI(http://swagger.io/swagger-ui/)와 Postman(https://www.getpostman.com/)을 이용한 ASP.NET Core Web API의 구축 과정을 예로 설명했습니다.
* dotnet new feature selection : Muhammad Rehan Saeed가 "dotnet new" 명령어의 기능 선택 옵션을 설명했습니다.
* Add MVC to your ASP.NET 1.1 application using the dotnet command line : Jon Hilton이 ASP.NET 1.1에 dotnet 명령을 이용하여 MVC 기능을 추가하는 방법을 소개했습니다.
* Migrating from project.json to csproj using Visual Studio 2017 – Moving a real world ASP.NET Core application using VS2015 project.json to VS2017 and csproj : Steve Gordon이 Visual Studio 2017를 활용하여 project.json을  csproj 프로젝트로 변환하는 방법을 소개했습니다.
* .NET Core, ASP.NET Core logging with NLog and PostgreSQL : Damien Bowden이 .NET Core, ASP.NET Core환경에서 NLog와 PostgreSQL를 이용한 로깅 방법을 설명했습니다. 
* Model Binding in ASP.NET Core : Dino Esposito가 ASP.NET Core, MVC의 Model Binding 기능을 설명했습니다.
* Adding Global Error Handling and Logging in ASP.NET Core with IExceptionHandlerPathFeature : Scott Sauber가 IExceptionHandlerPathFeature를 이용한 전역 예외 처리및 로깅 방법을 설명했습니다. 
* Await your event handlers completion with Deferred Events : Pedro Lamas이 자신이 구현한 비동기 이벤트 "Deferred Events"를 소개했습니다.
* Get Started with MultiRow Data Grid for ASP.NET MVC (video) : Jody Handley가 ASP.NET MVC용 ComponentOne Data Grid의 MultiRow 기능을 소개했습니다.

### C#
* Christian Nagel is giving away a free chapter on C# 7 from his C# and .NET Core book : Christian Nagel이 자신의 C#7 저서 내용중 일부분(47장 - What’s New!)을 공유했습니다.
* C# 7.0: Deconstruction demystified : Alexander Tsvetkov가 C# 7.0의 새로운 기능 Deconstruction 을 설명했습니다.
* Sharing .NET generic code under the hood : Yi Zhang이 .NET의 제너릭 코드 기능을 설명했습니다.
* Expression Trees in C# with an example : Sanskriti가 C#의 Expression Tree를 설명했습니다.
* C# 7–The Good Parts–Pattern Matching (video) by Mark Heath.
* Understand monads with LINQ : Miłosz Piechocki가 LINQ 개념과 기능을 설명했습니다.

### F#
* Getting Started with .NET Core using F# : NET Core 환경에서 F# 활용방법을 소개했습니다.
* Building a security testing service with F#, : William Blum이  F#을 이용한 보안 테스트 클라우드 서비스 "프로젝트 Springfield"의 진행과정을 공유했습니다.
* Using F# to write serverless Azure functions, : Lee Stott이 F#을 이용한 Azure function구축 방법을 공유했습니다.
* Gram Schmidt in Fsharp : Jeremy Bellows가 F#을 이용한 그람-슈미트과정(직교화과정)의 구현 내용을 공유했습니다.
* Slack TypeProvider : Flechner Romain이 슬랙(Slack)에서 사용가능한 TypeProvider의 구현 과정을 소개했습니다.
* A Reusable ApiController Adapter : Mark Seemann이 F# 기반으로 개발된 ASP.NET RESTful API 용  ApiController Adapter 구현방법을 설명했습니다.
* Creating an Azure Functions solution diagram, : Mathias Brandewinder가 F#과 GraphViz(http://www.graphviz.org/)를 이용하여 Azure Function의 구조를 다이어그램으로 표현하는 방법을 설명했습니다.

### VB
* What’s New in Visual Basic 2017 : Klaus Löffelmann이 Visual Basic 2017 의 새로운 기능을 정리했습니다.

### Xamarin
* Stable Release: Cycle 9 SR0 with Xcode 8.3 Support : Bri Brothers가 Xcode 8.3을지원하는 Cycle 9  버전  정보를 공유했습니다.
* Technical Bulletin: Xcode 8.3 Support for VS 2017 : Adrian Murphy가 VS 2017에서  Xcode 8.3의 지원 소식을 공유했습니다.
Beta Release: 15.1 Beta Preview 2 : Bri Brothers가 15.1 Beta Preview 2  버전  정보를 공유했습니다.
* Pre-release: Xamarin.Forms 2.3.4.221-pre6 : David Ortinau 가 Xamarin.Forms 2.3.4.221-pre6  버전  정보를 공유했습니다.
* Xamarin Alpha Preview : Cody Beyer가 Xamarin Alpha Preview 버전  정보를 공유했습니다.
* Xamarin Podcast: Enhanced XAML Productivity with MFractor : Pierce Boggan이 MFractor(Xamarin Studio와 Visual Studio for Mac용 확장 툴)를 이용한 XAML 개발 생산성 향상 팟케스트를 진행 했습니다.
* Announcing New Monthly Pricing for Xamarin University! : Mark Smith가 Xamarin University의 새로운 월간 요금 체계를 소개했습니다.
* Become a Mobile Developer with Visual Studio 2017 and Xamarin University : Mark Smith가 Xamarin University 를 소개했습니다.
* Episode 20: Realm Mobile Databases with Adam Fish by The Xamarin Show : Xamarin Show 20편 "Realm의  Product Manager 인Adam Fish와 Realm Mobile Database 알아보기"편이 공유되었습니다.
* Xamarin.Tips – Xamarin.Forms iOS ListView Refresh Spinner :  Alex Dunn이 iOS ListView의 Refresh Spinner 색상변경 방법을 설명했습니다.
* Xamarin.Tips – Create Your Own Star Wars Intro Text! : Alex Dunn이 스타워즈 인트로 효과 구현방법을 설명했습니다.
* Xamarin.Tips – Visual Studio Code Templates/Snippets for MVVM Light : Alex Dunn이 MVVM Light용 코드 템플릿, 스니핏을 공유했습니다.
* Xamarin.University – Upcoming Guest Lecture on Cross-Platform WebRTC by Alex Dunn이 Xamarin University 과정 WebRTC (Web Real-Time Communication) 정보를 공유했습니다.
* Validating User Input in Xamarin.Forms IV : David Britch가 Xamarin.Forms의 "사용자 입력값 유효성 검증" 4편을 공유했습니다.
* Beautiful Xamarin Apps : Daniel Krzyczkowski가 Xamarin에서 다양한 효과를 내기위한  여러확장 툴정보를 소개했습니다.
* File Persistence in Xamarin.Forms Apps : Jesse Liberty가 Xamarin.Forms 환경에서 파일 접근 방법을 설명했습니다.
* Xamarin.Forms application with MvvmCross – VIII : Can Bilgin이 MvvmCross을 이용한 App 개발 방법을 설명했습니다..
* Transition from Xamarin.Forms to Xamarin Native Pt. 1 : Mario Jesús Galván Miranda가 Xamarin.Forms과 Xamarin Native 의 UI 구성요소를 비교 설명 했습니다.
* Colored Map Markers on Xamarin iOS and Android : James Montemagno가  iOS와 Android 지도에 마커 표시하는 방법을 소개했습니다.
* Connect to your Android emulator running on mac from your windows VM : Jan Tourlamain이 Parallels Desktop으로 실행되는 windows VM에서 IOS의 Android 에뮬레이터 접속방법을 설명했습니다.
* Bindable Properties in Xamarin Forms  : Adam Pedley가 속성 바인딩을 설명했습니다.
* Less repetitive code to reach REST APIs for your Xamarin.Forms app with Refit : Gerald Versluis가 Xamarin.Forms에서 REST API 접근시 사용할 수 있는 확장툴 Refit 을 소개했습니다. 
* Supporting Xamarin.Forms Master Detail Page in Caliburn.Micro : Nigel Sampson이 Caliburn.Micro  프레임워크를 이용한 마스터-디테일 페이지 구현방법을 설명했습니다.

### Azure
* HTTP-triggered Azure Functions : Gunnar Peipman이 HTTP 요청에  응답하는  Azure Function에 대해서 설명했습니다.

### UWP
* Announcing UWP Community Toolkit 1.4 : David Catuhe가 UWP Community Toolkit 1.4버전 릴리즈 정보를 공유했습니다.
* Desktop Bridge: Creators Update : Arian Ghotbi가 윈도우10 크리에이터 업데이트(Creators Update)에 포함된 새로운 기능을 소개했습니다.
* New MapControl features in Windows 10 Creators Update : Sandra Lori-Amin가 윈도우10 크리에이터 업데이트(Creators Update)에 포함된 새로운 지도 컨트롤을 소개했습니다.
* Simplify payments in UWP Apps with the Payment Request API from Microsoft : Stan Chang이 UWP 어플용 결재 API를 소개했습니다.

### Data
* Building Better Entity Framework Applications : Jon Smith가 Entity Framework을 효과적으로 사용하기위한 방법을 설명했습니다.

### Game 개발
* [Unity] Social Sharing Tutorial (Unity, Android) : Reso Coder가 Unity, Android환경에서 SNS 접근방법을 설명을 설명했습니다.
* Why F.E.A.R.’s AI is still the best in first-person shooters : Samuel Horti가 1인칭 슈팅케임 F.E.A.R.의 AI 기능을 설명했습니다.
* Designing Game Controls : Andrew Dotsenko가 다양한 게임 조작(키,마우스등)의 구성및 설계 방법을 설명했습니다.
* The Stress of Game Development – Tips for Survival by Extra Credits.
* Curated #UnityTips No. 39 by Devdog March 2017.
* 5.6 is now available and completes the Unity 5 cycle : Alex Lian이 Unity 5.6 버전 릴리즈 정보를 공유했습니다.
* Classic Game Postmortem - Maniac Mansion : 2017 GDC의 "고전 게임 매니악 맨션(Maniac Mansion)  개발 과정" 세션 동영* 이 을 공유되었습니다.
* From Rational to Emotional: Designs that Increase Player Retention : 2017 GDC의 UX 세션 동영상" Designs that Increase Player Retention"이 공유되었습니다.


// 전무님 소개
