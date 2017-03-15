여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 커뮤니티 소식
Taeyo.NET에서 [http://docs.asp.net](http://docs.asp.net)의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
* [ASP.NET Core 보안(인증) : Facebook 등을 이용한 인증 활성화]( http://taeyo.net/Columns/View.aspx?SEQ=589&PSEQ=39)

### .NET Foundation

[.NET 재단]( https://dotnetfoundation.org/)에 [Jon Galloway]( https://dotnetfoundation.org/blog/welcoming-jon-galloway-as-the-new-executive-director-of-the-net-foundation)가 새로운 전무 이사로 취임하였습니다. Jon은 오래전부터 .NET 개발자 커뮤니티에서 활발하게 활동하였으며, 기술 블로깅 및 매거진, .NET 오픈소스 프로젝트, .NET 개발 서적 ‘ASP.NET MVC’ 시리즈, Microsoft Virtual Academy 웹 개발 클래스, StackOverflow (활동중인 ID : 5!) 등 .NET 기술 발전에 다방면으로 기여하였습니다.
 


### On .NET 소식
[지난 주 On .NET]( https://channel9.msdn.com/Shows/On-NET/Beth-Massi-Happy-Anniversary-NET)에는 [Beth Massi]( https://twitter.com/bethmassi)와 함께 .NET의 지난 15년을 정리해 보았습니다. 

//그림

[이번 주 On .NET]( https://channel9.msdn.com/Shows/On-NET)에는 [Eric Mellino]( https://github.com/mellinoe)가 .NET Core 기반으로 개발된 게임엔진 [CrazyCore]( https://github.com/mellinoe/CrazyCore) 데모를 소개해드릴 예정입니다.

### 금주의 패키지: NeinLinq
[NeinLinq]( https://github.com/axelheer/nein-linq) 라이브러리는 LINQ 공급자를 사용하는 데 유용한 확장을 제공합니다. 특히 함수 재사용, 쿼리 재작성 (null-safe) 작성, (변환 가능한) 조건자 / 선택자를 이용한 동적 쿼리 작성에 매우 유용하게 쓰일 수 있습니다.
아래는 LINQ 표현식의 예로서 사용자 함수를 쉽게 람다식에서 표현할 수 있습니다.
//코드

GitHub에 공유된 rawneinlinq2.cs 파일의 코드 내용

### .NET 소식

* How to evaluate info you read on garbage collectors : Maoni Stephens가 GC의 성능을 평가할때, 주의 깊게 알아봐야할 내용을 소개합니다.
* A common execution path optimization : Sergey Teplyakov가 코드 (논리적) 실행 경로의 최적화 방법을 설명했습니다.
* Storyteller 4.0 is Out! : Jeremy D. Miller가 CoreCLR, Cross Platform을 지원하는 테스트 프레임워크 ‘Storyteller 4.0’ 출시 소식을 공유했습니다.
* The Issue With Scoped Async Synchronization Constructs : Bar Arnon이 현대에 보편화한 동기 구성의 단점과 비동기 구성의 필요성에 관해 설명합니다.
* C# 7.0 – Pattern Matching : Christian Nagel이 C# 7.0의 패턴 매칭 기능을 설명합니다.
* How to create a dotnet new project template in .NET Core : Chad Ramos가 .NET Core 환경에서 dotnet 프로젝트 템플릿 생성 방법을 소개합니다.
* 65535 interfaces ought to be enough for anybody : Andrey Akinhin이 [Rider](https://www.jetbrains.com/rider/)프로젝트를 진행하면서 65,535개 인터페이스 제약사항과 이와 관련된 경혐을 포스팅했습니다.
* State of the union: ReSharper C# 7 and VB.NET 15 support : Maarten Balliauw가 ReSharper의 새로운 버전에서 C# 7, VB.NET 15을 지원한다는 소식을 공유했습니다.
* .NET Core Ecosystem – My thoughts : Malisa Ncube가 .NET Core 생태계에 대한 자신의 의견을 포스팅했습니다.
* Migrating an existing .NET Core to csproj : Michael Crump가 .NET Core 프로젝트를 csproj 형식으로 변환하는 방법을 소개합니다.

### ASP.NET 소식
* Overriding ASP.NET Core Framework-Provided Services : David Pine이 ASP.NET Core의 서비스 재정의(Override) 방법을 공유했습니다.
* Understanding your middleware pipeline with the Middleware Analysis package : Andrew Lock이 Middleware Analysis package를 이용한 미들웨어 파이프라인 구조 파악 방법을 소개합니다.
* Let’s Try WCF Self-Hosted Services in a Container : Jeffrey T. Fritz가 Docker Container에서 간단한 WCF 자체 호스팅 서비스를 실행하는 방법을 소개합니다.
* Enhanced Selenium WebDriver Tests with the New Improved C# 6.0 : Anton Angelov가 C # 5.0을 사용하면 Selenium WebDriver 테스트 결과가 어떻게 나타나는지 공유하였습니다.
* ASP.NET Core CSRF defence with Antiforgery : Daniel Jimenez Garcia가 ASP.NET Core CSRF(Cross Site Request Forgery) 보안 취약점과 이에 대한 솔루션을 소개합니다.
* Minify CSS and JavaScript files with Visual Studio and ASP.NET Core : Gérald Barré가 Visual Studio BundlerMinifier를 이용하여 ASP.NET Core의 CSS, JavaScript 파일을 효과적으로 관리하는 방법 소개합니다.
* Real time ASP.NET Core : Radu Matei가 ASP.NET Core의 실시간 데이터 처리 기술을 소개합니다.
* Enabling Cross-Origin Requests In ASP.NET Core : Jignesh Trivedi가 ASP.NET Core에서 CORS(Cross-Origin Resource Sharing)를 요청하는 방법을 설명합니다.
* AttributeAuthorization with Custom Roles in ASP.NET Core : Mosti16이 ASP.NET Core에서 Attribute Authorization를 이용한 권한 관리 방법을 설명합니다.
* ASP.NET Core logging: what still works and what changed? : Matt Watson이 기존 .NET 로깅 프레임 워크와 ASP.NET Core 및 .NET Core의 새로운 변경 사항에 대해 설명합니다.
* Returning raw JSON data in Web API with Marten : Jason roberts가 Marten의 Web API를 이용한JSON 데이터 반환 방법을 설명합니다.
* HTTP/2 Server Push and ASP.NET MVC – Cache Digest : Tomasz Pęczek이 HTTP/2 Server Push와 ASP.NET MVC의 Cache Diges에 관해 설명합니다. 

### F# 소식
* Easy start with F# in Visual Studio Code : Equisept가 Visual Studio Code를 이용한 F# 개발방법을 소개합니다.
* Thirteen Ways of Looking at a Turtle : Scott Wlaschin이 NDC 런던 개발자 행사에서 발표한 터틀 그래픽스 구현과 이와 관련된 개념을 설명하는 녹화 영상을 공유했습니다.
* Particle Filter in F#, : Gary Evans가 F#으로 구현한 Particle Filter 소스를 공유했습니다.
* Use JS local storage with ListModel with WebSharper UI.Next in F#, : Kimsery Lam이 F#과 WebSharper UI.Next을 이용한 로컬 저장소 접근방법을 설명합니다.
* F# – Mathematical expressiveness, by Ramón Soto Mathiesen가 F#의 수학적 표현력에 관해 소개합니다.
* Discussion: Autocompletion Behavior : VS 2017에서 업데이트된 F# 코드 자동 완성 기능의 성능을 데모합니다..

### Xamarin 소식
* Xamarin Release Candidate: Cycle 9 RC Refresh : Bri Brothers가 Xamarin Cycle 9 RC 버전 정보를 공유했습니다.
* Building Android Apps with Entity Framework : Jon Douglas가 Entity Framework을 이용한 안드로이드 애플리케이션 개발 정보를 공유했습니다.
* Mobile Center Webinar Recordings – Ship Mobile Apps Faster and Give Your Apps an Instant Cloud Backend : Courtney Witmer가 Mobile Center를 소개하는 웨비나 시리즈에서 "모바일 애플리케이션에 클라우드 백앤드 간단하게 연동하기”와 “모바일 애플리케이션 빠르게 완성/배포하기"를 주제로한 웨비나 녹화영상을 공유했습니다.
* Bring Stunning Animations to Your Apps with Lottie : Martijn van Dijk이 Lottie를 이용한 애니메이션 기능을 추가하는 방법을 소개합니다.
* Realtime Databases with the Realm Mobile Platform : Andy Dent이 Realm Mobile Database을 이용한 실시간 DB 기능을 소개합니다.
* Consumable In-App Purchases : James Montemagno가 Consumable In-App Purchases 기능을 설명합니다.
* The Xamarin Show 15 : Appium Mobile Automation with Glenn Wester : James Montemagno가 진행하는 Xamarin Show 시리즈의 15번째 편 "Appium을 이용한 모바일 테스트 자동화"를 공유했습니다.
* Create cross-device experiences with the Project Rome SDK for Android : Jim Galasyn이 Project Rome SDK for Android로 다중 플렛폼용 애플리케이션을 구현하는 방법을 설명합니다. 
* Entity Framework Core with Xamarin Forms, Patterns for Referencing Dependencies in Cross Platform Development, & Visual Studio 2017, .NET Standard and Xamarin : Adam Pedley이 "Xamarin Forms에서 EF(Entity Framework) 사용하기", "다중 플랫폼 애플리케이션 개발시 참조 패턴", "Visual Studio 2017에서 .NET Standard와 Xamarin 활용하기" 자료를 공유했습니다.
* Sending Files to a Xamarin.Forms App – Part 1: iOS and part 2: Android : Matthew Soucoup가 iOS, Android 플랫폼별로 Xamarin.Forms App에 파일 연결(전송)하는 방법을 소개합니다.
* Calligraphy with MvvmCross : Sven-Michael Stübe가 Calligraphy와 MvvmCross을 함께 사용하는 방법을 소개합니다.
* Call an Azure AD protected API in Xamarin/UWP apps : Timothé Larivière가 Xamarin/UWP 애플리케이션에서 Azure AD API를 호출하는 방법을 소개합니다.
* Designer Support for FloatLabeledEntry : Greg Shackles이 자신이 개발한 iOS용 FloatLabeledEntry 컨트롤의 업데이트 내용을 공유했습니다.
* Xamarin.Android Continuous Integration with Visual Studio Team Services : Alex Dunn이 Xamarin.Android 프로젝트에 VSTS의 Continuous Integration을 설정하는 방법을 소개합니다.
* Using an AutomationId with a Cell in Xamarin.Forms : Kevin Ford가 Xamarin.Forms의 AutomationId 활용 방법을 설명합니다.
* Update on the many flavors of HttpClient : Kerry W. Lothrop이 여러 플랫폼의 HttpClient 기능을 정리한 내용을 업데이트하였습니다.
* Unable to start Build 4.3.0.664 agent. when building iOS apps : David Yardy이 iOS 애플리케이션 빌드시 발생할 수 있는 예외상황을 공유했습니다.
* To Use Or Not To Use: Touch Gesture Controls For Mobile Interfaces : Kyle Sanders가 터치 제스쳐를 이용한 UX 인터페이스 디자인에 대해 설명합니다.

### UWP 소식
* Cognitive Services APIs: Vision : Windows Apps Team에서 Cognitive Services API : " Vision " 기능을 소개합니다.

* Implementing a type converter in UWP XAML : Tim Heuer이 UWP XAML에서 활용할 수 있는 타입 컨버터 구현 방법을 소개합니다.
* #Hololens – #SpectatorView, time to use my Credit Card again! : El Bruno이 홀로렌즈의 SpectatorView 기능을 소개합니다.
* Cognitive Services APIs: Speech : Windows Apps Team에서 Cognitive Services API : "Speech" 기능을 소개합니다.
* Cognitive Services APIs: Language : Windows Apps Team에서 Cognitive Services API : "Language"기능을 소개합니다.
* Cognitive Services APIs: Knowledge : Windows Apps Team에서 Cognitive Services API : "Knowledge"기능을 소개합니다.
* Cognitive Services APIs: Search : Windows Apps Team에서 Cognitive Services API : "Search"기능을 소개합니다.

### Azure 소식
* Running ASP.NET Core applications in Azure App Service : Adrian Hall이 Azure App Service에서 ASP.NET Core 애플리케이션을 구동시키는 방법을 소개합니다.
* Logging To Application Insights In Azure Functions : Tim Murphy가 Azure Function에서 Application Insight의 로깅 기능을 활용하는 방법을 설명합니다.
* Optimistic Concurrency in DocumentDB : Derek Comartin이 DocumentDB의 낙관적 동시제어(Optimistic Concurrency)에 관해 설명합니다.

### Game 소식
* The MonoGame Game Loop (just like the XNA Game Loop) and Putting a Sprite onscreen : Chris G. Williams이 "MonoGame의 게임 루프 구조"와 "스크린에 작은 2차원 이미지를 이용한 케릭터 표현 방법"을 소개합니다.

// 전무님 소개
