지난주 5/10 ~ 5/12 에는 마이크로소프트의 개발자행사인 [Microsoft Build 2017](https://build.microsoft.com/)이 개최되었습니다. Build에서 발표되었던 내용은 [Channel 9](https://channel9.msdn.com/)을 통해 전부 다시 시청하실 수 있습니다. 또한, 빌드의 열기를 직접 느껴볼 수 있는 Build Tour가 서울에서도 개최됩니다! 6/13 ~ 6/14 양일에 걸쳐서 진행되는 Build Tour Seoul에서는 빌드에서 발표된 주요 내용을 듣고 해커돈에도 직접 참가하실 수 있습니다. 자세한 내용은 아래의 링크를 참고하시기 바랍니다. 

* [Build 2017 발표영상 다시보기](https://channel9.msdn.com/Events/Build/2017)
* [Build Tour Seoul 참가 신청하기](https://www.microsoftevents.com/profile/form/index.cfm?PKformID=0x19997896a19) 
* [Scott Guthrie가 작성한 Build 2017에서 발표된 주요 내용 확인하기](https://azure.microsoft.com/en-us/blog/new-innovations-at-microsoft-build-2017-helping-developers-achieve-more/)
* [Build 2017의 주요 내용이 정리된 5월 16일자 주간닷넷 미리보기](https://blogs.msdn.microsoft.com/dotnet/2017/05/16/the-week-in-net-microsoft-build-2017-net-core-2-0-preview-1-for-the-king/)

### On .NET 소식

지난 주 On .NET 소식에서는 Tamás Vajk, Olivier Gaudin과 함께 [SonarLint](http://www.sonarlint.org/visualstudio/index.html)와 [SonarQube](https://www.sonarqube.org/)에 대해서 이야기 나누어 보았습니다. 

//사진

이번  주 On .NET 소식에서는 [Sébastien Ros](https://twitter.com/sebastienros)과 함께 [Orchard Core](https://github.com/orchardcms/orchard2) 프로젝트 구현경험과 더불어  ASP.NET 애플리케이션의 모듈화를 주제로 이야기 나눌예정입니다.  

### Happy Birthday .NET! - Dan Fernandez

지난 달 .NET birthday 파티에서 .NET 초기 멤버인 Dan Fernandez와 Visual Studio를 무료 배포와 같은 아이디어등 초기시절에 있었던 여러 애피소드에 대해 얘기 나누었습니다. Dan 은 Channel9 의 원년 멤버이자 최고의 .NET 에반젤리스트 중 한명입니다.
//동영상

### 금주의 프로젝트: nopCommerce

 [nopCommerce](http://www.nopcommerce.com/)는 가장 인기있는 오픈소스 전자상거래 시스템중 하나로 ASP.NET MVC, Autofac, Entity Framework을 기반으로 구축된 시스템입니다. 현재까지 180만 다운로드를 기록하고있으며 100개이상의 파트너를 보유하고있고 Volvo, BMW, Puma, Reebok, Lacoste와 같이 유명 브랜드들도 역시 이 시스템을 사용하고 있습니다.

//사진

###  금주의 블로거: Steve Gordon

Steve Gordon의 블로그에서는 ASP.NET에 대한 깊이있는 내용을 다룹니다. ASP.NET Core anatomy 시리즈를 보는 것은 ASP.NET Core에서 요청이 처리되는 과정을 배울 수 있는 가장 좋은 방법입니다. 이번 주에는 Steve의 두 편의 글을 소개합니다.

### .NET

* [No GCs for your allocations?](https://blogs.msdn.microsoft.com/maoni/2017/04/02/no-gcs-for-your-allocations/) : Maoni Stephens이 가비지컬렉터의 메모리 수집을 억제 기능인 "NoGCRegion"을 소개했습니다.
* [.NET Core console app running on Raspberry Pi](http://laurentkempe.com/2017/04/03/Dotnet-Core-app-running-on-raspberry-pi/) : Laurent Kempé이 라즈베리파이3 에서.NET Core 콘솔용 "Hello World" 어플 개발 방법을 설명했습니다.
* [The .NET IL Interpreter](http://mattwarren.org/2017/03/30/The-.NET-IL-Interpreter/) : Matt Warren이 .NET의 IL Interpreter에 대해서 설명했습니다.
* Sasha Goldshtein이 [리눅스 .NET Core 에서 이벤트 trace 활용 방법](http://blogs.microsoft.co.il/sasha/2017/03/30/tracing-runtime-events-in-net-core-on-linux/), [리눅스 .NET Core 에서 USDT(User Statically Defined Tracing)와 BCC(BPF Compiler Collection) 활용 방법](http://blogs.microsoft.co.il/sasha/2017/04/02/tracing-net-core-on-linux-with-usdt-and-bcc/)을  설명했습니다.
* [Externalizing the HttpClient internals for fun & profit](https://ayende.com/blog/177505/externalizing-the-httpclient-internals-for-fun-profit) : Ayende Rahien이 HttpClient의 캡슐화된 내부기능의 활용 방법과 예제를 설명했습니다. 
* [Building DockNetFiddle using Docker and .NET Core](http://www.dotnetcurry.com/windows-azure/1339/docknetfiddle-using-docker-dotnet-core) : Daniel Jimenez Garcia가 도커, .NET Core 환경에서 DockNetFiddle 구축 과정을 설명했습니다.
* [Generate Documentation from Your Build](http://www.daedtech.com/generate-documentation-build/) : Erik Dietrich가 개발소스의 주석을 기반으로 문서를 생성해주는 문서자동화 툴 GhostDoc 을 소개했습니다.
* [A TPL Actor Pattern](https://tech.winton.com/blog/2017/03/a-tpl-actor-pattern) : Jos Hickson이 Task Parallel Library(TPL) 액터 패턴을 소개했습니다.
* [Cake and Fake on the ThoughtWorks technology radar](https://www.thoughtworks.com/radar/tools/cake-and-fake) :  빌드 자동화 툴인 [Cake](http://cakebuild.net/)와 [Fake] (http://fsharp.github.io/FAKE/)가 소개되었습니다.

### ASP.NET

* [How to create your own templates for dotnet new](https://blogs.msdn.microsoft.com/dotnet/2017/04/02/how-to-create-your-own-templates-for-dotnet-new/) : Sayed Hashimi가 dotnet new 명령어를 이용한 사용자 정의 템플릿의 활용 방법을 설명했습니다.
* [ASP.NET Core Anatomy (Part 3) – UseMvc – Dissecting and understanding the internals of ASP.NET Core](https://www.stevejgordon.co.uk/asp-net-core-anatomy-part-3-addmvc) : Steve Gordon이 ASP.NET Core MVC 분석(파트3)- "UseMvc" ASP.NET Core 내부 이해하기 편을 공유했습니다.
* [Re-execute the middleware pipeline with the StatusCodePages Middleware to create custom error pages](https://andrewlock.net/re-execute-the-middleware-pipeline-with-the-statuscodepages-middleware-to-create-custom-error-pages/) : Andrew Lock이 StatusCodePages 값과 middleware 재실행을 통한 에러 페이지 구축 방법을 설명했습니다.
* [Retrieving the path that generated an error with the StatusCodePages Middleware](https://andrewlock.net/retrieving-the-path-that-generated-an-error-with-the-statuscodepages-middleware/) : Andrew Lock이 StatusCodePages 값을 활용하여 예외발생 경로를 얻는 방법을 설명했습니다.
* [Hash Passwords with ASP.NET Membership Providers](https://blogs.msdn.microsoft.com/webdev/2017/03/31/hash-passwords-with-asp-net-membership-providers/) : Jeffrey T. Fritz가 ASP.NET Membership Providers의 Hash Passwords 기능 활용법을 소개했습니다. 
* [Raspberry Pi: Run ASP.NET Core on Startup](https://carlos.mendible.com/2017/03/26/raspberry-pi-run-aspnet-core-on-startup/) : Carlos Mendible이 라즈베리파이에서 ASP.NET Core 애플리케이션을 OS 시작 시점에 실행하는 방법을 소개했습니다.
* [Updating my AlbumViewer Sample to ASP.NET Core 1.1 and Angular 4](https://weblog.west-wind.com/posts/2017/Mar/31/Updating-my-AlbumViewer-Sample-to-ASPNET-Core-11-and-Angular-4) : Rick Strahl이 ASP.NET Core 1.1과 Angular 4를 이용해 AlbumViewer 샘플을 업데이트한 과정을 공유했습니다.
* [Secure and explore ASP.NET Core Web APIs](http://conductofcode.io/post/secure-and-explore-aspnet-core-web-apis/) : Henrik Lau Eriksson이 [JSON Web Tokens](https://jwt.io/), [Swagger UI](http://swagger.io/swagger-ui/), [Postman](https://www.getpostman.com/)을 이용한 ASP.NET Core Web API의 구축 과정을 예로 설명했습니다.
* [dotnet new feature selection](http://rehansaeed.com/dotnet-new-feature-selection/) : Muhammad Rehan Saeed가 "dotnet new" 명령어의 기능 선택 옵션을 설명했습니다.
* [Add MVC to your ASP.NET 1.1 application using the dotnet command line](https://azureinsights.net/2017/03/31/add-mvc-to-your-asp-net-1-1-application-using-the-dotnet-command-line/) : Jon Hilton이 ASP.NET 1.1에 dotnet 명령을 이용하여 MVC 기능을 추가하는 방법을 소개했습니다.
* [Migrating from project.json to csproj using Visual Studio 2017 – Moving a real world ASP.NET Core application using VS2015 project.json to VS2017 and csproj](https://www.stevejgordon.co.uk/migrating-project-json-to-csproj-visual-studio-2017) : Steve Gordon이 Visual Studio 2017를 활용하여 project.json을 csproj 프로젝트로 변환하는 방법을 소개했습니다.
* [.NET Core, ASP.NET Core logging with NLog and PostgreSQL](https://damienbod.com/2017/03/29/net-core-asp-net-core-logging-with-nlog-and-postgresql/) : Damien Bowden이 .NET Core, ASP.NET Core환경에서 NLog와 PostgreSQL를 이용한 로깅 방법을 설명했습니다. 
* [Model Binding in ASP.NET Core](https://www.simple-talk.com/dotnet/asp-net/model-binding-asp-net-core/) : Dino Esposito가 ASP.NET Core, MVC의 Model Binding 기능을 설명했습니다.
* [Adding Global Error Handling and Logging in ASP.NET Core with IExceptionHandlerPathFeature](https://scottsauber.com/2017/04/03/adding-global-error-handling-and-logging-in-asp-net-core/) : Scott Sauber가 IExceptionHandlerPathFeature를 이용한 전역 예외 처리 및 로깅 방법을 설명했습니다. 
* [Await your event handlers completion with Deferred Events](https://www.pedrolamas.com/2017/04/04/await-your-event-handlers-completion-with-deferred-events/) : Pedro Lamas이 자신이 구현한 비동기 이벤트 "Deferred Events"를 소개했습니다.
* [Get Started with MultiRow Data Grid for ASP.NET MVC (video)](http://our.componentone.com/2017/03/30/get-started-with-multirow-data-grid-for-asp-net-mvc/) : Jody Handley가 ASP.NET MVC용 ComponentOne Data Grid의 MultiRow 기능을 소개했습니다.

### C#

* [Christian Nagel is giving away a free chapter on C# 7 from his C# and .NET Core book](https://csharp.christiannagel.com/2017/04/03/csharp7/) : Christian Nagel이 자신의 저서인 C# and .NET Core book에서 C# 7.0에 대한 무료 챕터를 공유했습니다.
* [C# 7.0: Deconstruction demystified](https://surfingthecode.com/2017/04/c-sharp7-deconstruction-demystified/) : Alexander Tsvetkov가 C# 7.0의 새로운 기능인 Deconstruction 을 소개했습니다.
* [Sharing .NET generic code under the hood](http://yizhang82.me/dotnet-generics-sharing) : Yi Zhang이 .NET의 제네릭 기능을 설명했습니다.
* [Expression Trees in C# with an example](http://dotnetcrunch.com/expression-trees-c-example/) : Sanskriti가 C#의 Expression Tree를 설명했습니다.
* [C# 7–The Good Parts–Pattern Matching (video)](http://markheath.net/post/csharp-7-pattern-matching) : Mark Heath가 C# 7의 패턴매칭을 소개하는 비디오를 공유했습니다. 
* [Understand monads with LINQ](http://codewithstyle.info/understand-monads-linq/) : Miłosz Piechocki가 LINQ 개념과 기능을 설명했습니다.

### F#

* [Getting Started with .NET Core using F#](https://www.youtube.com/watch?v=2xG31sUsCdc&feature=youtu.be) : NET Core 환경에서 F# 활용방법을 소개했습니다.
* [Building a security testing service with F#](https://www.youtube.com/watch?v=ZVvcWIjbbhk&feature=youtu.be) : William Blum이 F#을 이용한 보안 테스트 클라우드 서비스 프로젝트인 "Springfield"의 진행과정을 공유했습니다.
* [Using F# to write serverless Azure functions](https://blogs.msdn.microsoft.com/uk_faculty_connection/2017/03/24/using-f-to-write-serverless-azure-functions) : Lee Stott이 F#을 이용한 Azure function구축 방법을 공유했습니다.
* [Gram Schmidt in Fsharp](http://jeremybellows.com/blog/Gram-Schmidt-in-FSharp) : Jeremy Bellows가 F# 에서 그람-슈미트과정(직교화과정)을 구현하는 방법을 공유했습니다.
* [Slack TypeProvider](http://rflechner.github.io/SlackTypeProvider/#/) : Flechner Romain이 슬랙(Slack)에서 사용가능한 TypeProvider의 구현 과정을 소개했습니다.
* [A Reusable ApiController Adapter](http://blog.ploeh.dk/2017/03/30/a-reusable-apicontroller-adapter/) : Mark Seemann이 F# 기반으로 개발된 ASP.NET RESTful API 용  ApiController Adapter 구현방법을 설명했습니다.
* [Creating an Azure Functions solution diagram](http://brandewinder.com/2017/04/01/azure-function-app-diagram/) : Mathias Brandewinder가 F#과 GraphViz(http://www.graphviz.org/)를 이용하여 Azure Function의 구조를 다이어그램으로 표현하는 방법을 설명했습니다.

### VB

* [What’s New in Visual Basic 2017](https://blogs.msdn.microsoft.com/vbteam/2017/03/30/whats-new-in-visual-basic-2017/) : Klaus Löffelmann이 Visual Basic 2017 의 새로운 기능을 정리했습니다.

### Xamarin

* [Stable Release: Cycle 9 SR0 with Xcode 8.3 Support](https://releases.xamarin.com/stable-release-cycle-9-with-xcode-8-3-support/) : Bri Brothers가 Xcode 8.3을지원하는 Cycle 9 버전정보를 공유했습니다.
* [Technical Bulletin: Xcode 8.3 Support for VS 2017](https://releases.xamarin.com/technical-bulletin-xcode-8-3-support-for-vs-2017/) : Adrian Murphy가 VS 2017에서 Xcode 8.3의 지원 소식을 공유했습니다.
* [Beta Release: 15.1 Beta Preview 2](https://releases.xamarin.com/beta-release-15-1-rc2/) : Bri Brothers가 15.1 Beta Preview 2 버전 정보를 공유했습니다.
* [Pre-release: Xamarin.Forms 2.3.4.221-pre6](https://releases.xamarin.com/pre-release-xamarin-forms-2-3-4-221-pre6/) : David Ortinau 가 Xamarin.Forms 2.3.4.221-pre6 버전 정보를 공유했습니다.
* [Xamarin Alpha Preview](https://blog.xamarin.com/xamarin-alpha-preview/) : Cody Beyer가 Xamarin Alpha Preview 버전  정보를 공유했습니다.
* [Xamarin Podcast: Enhanced XAML Productivity with MFractor](https://blog.xamarin.com/podcast-enhanced-xaml-productivity-with-mfractor/) : Pierce Boggan이 MFractor(Xamarin Studio와 Visual Studio for Mac용 확장 툴)를 이용한 XAML 개발 생산성 향상 팟케스트를 진행 했습니다.
* [Announcing New Monthly Pricing for Xamarin University!](https://blog.xamarin.com/new-monthly-pricing-for-xamarin-university-2/) : Mark Smith가 Xamarin University의 새로운 월간 요금 체계를 소개했습니다.
* [Become a Mobile Developer with Visual Studio 2017 and Xamarin University](https://blogs.msdn.microsoft.com/visualstudio/2017/03/30/become-a-mobile-developer-with-visual-studio-2017-and-xamarin-university/) : Mark Smith가 Xamarin University를 소개했습니다.
* [Episode 20: Realm Mobile Databases with Adam Fish by The Xamarin Show](https://channel9.msdn.com/Shows/XamarinShow/Episode-20-Realm-Mobile-Databases-with-Adam-Fish) : Xamarin Show 20편 - Realm의 Product Manager 인 Adam Fish와 Realm Mobile Database 알아보기가 공유되었습니다.
* [Validating User Input in Xamarin.Forms IV](http://www.davidbritch.com/2017/03/validating-user-input-in-xamarinforms-iv.html) : David Britch가 Xamarin.Forms의 "사용자 입력 값 유효성 검증" 과 관련된 블로그 글을 공유했습니다.
* [Beautiful Xamarin Apps](https://mobileprogrammerblog.wordpress.com/2017/03/25/beautiful-xamarin-apps/) : Daniel Krzyczkowski가 Xamarin에서 다양한 효과를 내기위한  여러가지 확장 툴 정보를 소개했습니다.
* [File Persistence in Xamarin.Forms Apps](http://jesseliberty.com/2017/03/25/file-persistence-in-xamarin-forms-apps/) : Jesse Liberty가 Xamarin.Forms 환경에서 파일 접근 방법을 설명했습니다.
* [Xamarin.Forms application with MvvmCross – VIII](https://canbilgin.wordpress.com/2017/03/26/xamarin-forms-application-with-mvvmcross/) : Can Bilgin이 MvvmCross을 이용한 애플리케이션 개발 방법을 설명했습니다..
* [Transition from Xamarin.Forms to Xamarin Native Pt. 1](http://15mgm15.ghost.io/2017/03/27/transition-from-xamarin-forms-to-xamarin-native-pt-1/) : Mario Jesús Galván Miranda가 Xamarin.Forms과 Xamarin Native의 UI 구성요소를 비교하여 설명했습니다.
* [Colored Map Markers on Xamarin iOS and Android](http://motzcod.es/post/158924172147/colored-map-markers-ios-and-android) : James Montemagno가  iOS와 Android 지도에 마커를 표시하는 방법을 소개했습니다.
* [Connect to your Android emulator running on mac from your windows VM](http://www.devprotocol.com/connect-to-your-android-emulator-running-on-mac-from-your-windows-vm/) : Jan Tourlamain이 Parallels Desktop으로 실행되는 Windows VM에서 IOS의 Android 에뮬레이터 접속방법을 설명했습니다.
* [Bindable Properties in Xamarin Forms](https://xamarinhelp.com/bindable-properties-xamarin-forms/) : Adam Pedley가 속성 바인딩 방법을 설명했습니다.
* [Less repetitive code to reach REST APIs for your Xamarin.Forms app with Refit](https://blog.verslu.is/xamarin/xamarin-forms-xamarin/less-repetitive-code-to-reach-rest-apis-for-your-xamarin-forms-app-with-refit/) : Gerald Versluis가 Xamarin.Forms에서 REST API 접근시 사용할 수 있는 확장 툴인 Refit을 소개했습니다. 
* [Supporting Xamarin.Forms Master Detail Page in Caliburn.Micro](http://compiledexperience.com/blog/posts/master-detail-forms) : Nigel Sampson이 Caliburn.Micro 프레임워크를 이용한 마스터-디테일 페이지 구현방법을 설명했습니다.
* Aluex Dunn이 Xamarin 개발시 알아두면 좋을 팁들을 공유했습니다.
    * [Xamarin.Tips – Xamarin.Forms iOS ListView Refresh Spinner](https://alexdunn.org/2017/03/24/xamarin-tips-xamarin-forms-ios-listview-refresh-spinner-color/) :iOS ListView의 Refresh Spinner 색상변경 방법을 설명했습니다.
    * [Xamarin.Tips – Create Your Own Star Wars Intro Text!](https://alexdunn.org/2017/03/27/xamarin-tips-create-your-own-star-wars-intro-text/) : 스타워즈 인트로 효과 구현방법을 설명합니다.
    * [Xamarin.Tips – Visual Studio Code Templates/Snippets for MVVM Light](https://alexdunn.org/2017/03/28/xamarin-tips-visual-studio-code-templatessnippets-for-mvvm-light/) : MVVM Light용 코드 템플릿, 스니핏을 공유했습니다.
    * [Xamarin.University – Upcoming Guest Lecture on Cross-Platform WebRTC](https://alexdunn.org/2017/03/28/xamarin-university-upcoming-guest-lecture-on-cross-platform-webrtc/) : Xamarin University 과정 WebRTC (Web Real-Time Communication) 정보를 공유했습니다.

### Azure

* [HTTP-triggered Azure Functions](http://gunnarpeipman.com/2017/04/azure-functions-http/) : Gunnar Peipman이 HTTP 요청에 응답하는 Azure Function에 대해서 설명했습니다.

### UWP

* [Announcing UWP Community Toolkit 1.4](https://blogs.windows.com/buildingapps/2017/04/03/announcing-uwp-community-toolkit-1-4) : David Catuhe가 UWP Community Toolkit 1.4버전 릴리즈 정보를 공유했습니다.
* [Desktop Bridge: Creators Update](https://blogs.windows.com/buildingapps/2017/03/31/desktop-bridge-creators-update/) : Arian Ghotbi가 윈도우10 크리에이터 업데이트(Creators Update)에 포함된 새로운 기능을 소개했습니다.
* [New MapControl features in Windows 10 Creators Update](https://blogs.windows.com/buildingapps/2017/03/31/new-mapcontrol-features-windows-10-creators-update/) : Sandra Lori-Amin가 윈도우10 크리에이터 업데이트(Creators Update)에 포함된 새로운 지도 컨트롤을 소개했습니다.
* [Simplify payments in UWP Apps with the Payment Request API from Microsoft](https://blogs.windows.com/buildingapps/2017/03/28/simplify-payments-uwp-apps-payment-request-api-microsoft/) : Stan Chang이 UWP 애플리케이션용 결재 API를 소개했습니다.

### Data

* [Building Better Entity Framework Applications](https://www.simple-talk.com/dotnet/net-development/building-better-entity-framework-applications/) : Jon Smith가 Entity Framework을 효과적으로 사용하기 위한 방법을 설명했습니다.

### Game 개발

* [[Unity] Social Sharing Tutorial (Unity, Android)](https://youtu.be/E4E4EfkGs0Y) : Reso Coder가 Unity, Android 환경에서 SNS 에 컨텐츠를 쉽게 공유할 수 있는 방법을 설명했습니다.
* [Why F.E.A.R.’s AI is still the best in first-person shooters](https://www.rockpapershotgun.com/2017/04/03/why-fears-ai-is-still-the-best-in-first-person-shooters/) : Samuel Horti가 1인칭 슈팅케임 F.E.A.R.의 AI 기능을 설명했습니다.
* [Designing Game Controls](http://www.gamasutra.com/blogs/AndrewDotsenko/20170329/294676/Designing_Game_Controls.php) : Andrew Dotsenko 가 다양한 방법으로 게임 조작(키,마우스등)시 구성 및 설계 방법을 설명했습니다.
* [The Stress of Game Development – Tips for Survival](https://youtu.be/XUcp2bNTwBg) : Extra Credits에서 게임 개발시에 유용한 팁을 공유했습니다.
* [Curated #UnityTips No. 39 by Devdog March 2017](http://devdog.io/blog/2017/04/16-best-unity-tips-for-game-developers-39) : Unity 개발시 도움이 될 만한 39번째 팁이 공유되었습니다. 
* [5.6 is now available and completes the Unity 5 cycle](https://blogs.unity3d.com/kr/2017/03/31/5-6-is-now-available-and-completes-the-unity-5-cycle/) : Alex Lian이 Unity 5.6 버전 릴리즈 정보를 공유했습니다.
* [Classic Game Postmortem - Maniac Mansion](https://youtu.be/WD64ExGHBWE) : 2017 GDC의 "고전 게임 매니악 맨션(Maniac Mansion)  개발 과정" 세션 동영상이 공유되었습니다.
* [From Rational to Emotional: Designs that Increase Player Retention](https://youtu.be/_Hjm9LLSICg) : 2017 GDC의 UX 세션 동영상" Designs that Increase Player Retention"이 공유되었습니다.


// 전무님 소개
