주간닷넷 2016년 10월 4일

### On .NET 소식
[지난 주 On .NET]( https://channel9.msdn.com/Shows/On-NET/JB-Evain-Cecil-modifying-IL)에는 JB Evain와 Visual Studio 2015 Tools for Unity, 그리고 .NET 프로파일링 오픈소스 라이브러리 Cecil에 대해서 얘기 나누어보았습니다.

https://sec.ch9.ms/ch9/6fe0/899e4cc5-4b17-4342-8b71-2e708a5a6fe0/onnet20160929jbevain_mid.mp4

[이번 주 On .NET]( https://channel9.msdn.com/Shows/On-NET/Immo-Landwerth-Net-Standard)에는 .NET team의 [Immo Landwerth]( https://twitter.com/terrajobst)와 [NetStandard 2.0]( https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard/)에 대해 얘기 나누어 보겠습니다.

### 금주의 패키지 - NAudio
[Naudio]( https://github.com/naudio/NAudio)는 오디오 파일의 읽기, 쓰기, 디코딩, 인코딩, 컨버팅 작업 등을 손쉽게 처리할 수 있는 라이브러리입니다.

아래의 코드는 오디오 파일 정보를 화면에 표시하는 예입니다.

// 코드

### 금주의 자마린 어플 - Speech Central
iPhone 어플 [Speech Central]( https://itunes.apple.com/us/app/speech-central-take-web-on/id1127349155?ls=1&mt=8)은 인터넷 웹 페이지를 직접 보고 있지 않아도 음성으로 웹 페이지 텍스트를 읽어주는 어플입니다.
스마트폰을 보고 있지 않아도 되기 때문에 일상 생활 중에도 음성으로 새로운 뉴스를 전달 받으실 수 있습니다. 또한 화면이 꺼져있는 상태에서도 동작 가능하여 베터리 소모량도 적습니다.

### 금주의 게임 - Hand of Fate
[Hand of Fate](http://www.defiantdev.com/hof1.html)는 전략 카드게임과 액션, RPG 요소가 포함된 게임입니다. 플레이어는 자신의 카드를 전략적으로 사용하여, 제시한 카드에 따라 액션, RPG 게임이 진행되는 특별한 게임 운영 방식을 즐기실 수 있습니다.
https://cloud.githubusercontent.com/assets/4108756/19081035/becf5a74-8a0d-11e6-91f0-61dd5ab58b19.png
[Hand of Fate]( http://armello.com/)은 [Defiant Development]( http://www.defiantdev.com/)에서 [Unity]( https://unity3d.com/)와 [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 제작 했으며, 현재 Xbox One, PlayStation4와 [Steam]( http://store.steampowered.com/app/266510/)을 통해 Windows, Mac, Linux에서 즐기실 수 있습니다.

### .NET 소식
* [Scientist.NET 1.0 released!]( http://haacked.com/archive/2016/09/29/scientist-1.0-released/) : Phil Haack가 Scientist.NET 1.0 릴리즈 소식을 공유했습니다.
* [TLS 1.2 Comes to Mono – Update]( http://tirania.org/blog/archive/2016/Sep-30.html) : Miguel de Icaza가 TLS 1.2 버전 소식을 공유했습니다.
* [Storing and using secrets in Azure]( https://blogs.msdn.microsoft.com/dotnet/2016/10/03/storing-and-using-secrets-in-azure/) : Bertrand Le Roy가 Azure 환경에서 보안에 민감한 정보를 안전하게 저장하고 접근할 수 있도록 해주는 "Key Vault" 기능에 대해 설명합니다.
* [An Experience Report of Moving a Complicated Codebase to the CoreCLR]( https://jeremydmiller.com/2016/09/28/an-experience-report-of-moving-a-complicated-codebase-to-the-coreclr/) : Jeremy D. Miller가 기존 코드를 CoreCLR 코드로 전환한 경험에 대해 말합니다.
* [Implementing Seeding, Custom Conventions and Interceptors in EF Core 1.0]( https://blogs.msdn.microsoft.com/dotnet/2016/09/29/implementing-seeding-custom-conventions-and-interceptors-in-ef-core-1-0/) : Alina Popa가 EF Core 1.0의 Seed 방법과 Convention, Interceptor 구현 방법에 대해 설명합니다.
* [Cake for Visual Studio released](http://cakebuild.net/blog/2016/09/cake-for-yeoman) and [Announcing Cake for Yeoman]( http://cakebuild.net/blog/2016/09/cake-for-yeoman) : Alistair Chapman이 Visual Studio용 Cake 릴리즈 정보와 Yeoman 지원 소식에 대해 전해드립니다.
* [How to debug a Cake file using Visual Studio Code]( http://cakebuild.net/blog/2016/09/debug-cake-vscode) : Martin Björkström이 Visual Studio Code를 이용한 Cake 파일 디버깅 방법을 공유했습니다.
* [Optimising LINQ]( http://mattwarren.org/2016/09/29/Optimising-LINQ/) and [Adding a verb to the dotnet CLI tooling]( http://mattwarren.org/2016/10/03/Adding-a-verb-to-the-dotnet-CLI-tooling/) : Matt Warren이 LINQ 최적화와 dotnet CLI tool에 사용자 명령을 추가하는 방법에 대해 설명합니다.
* [Should I learn .NET Core?]( https://jonhilton.net/2016/09/28/should-i-learn-net-core/) : Jon Hilton이 .NET Core의 개발 배경과 중요성에 대해 설명합니다.

### ASP.NET 소식
* [Sharing Authorization Cookies between ASP.NET 4.x and ASP.NET Core 1.0]( http://www.hanselman.com/blog/SharingAuthorizationCookiesBetweenASPNET4xAndASPNETCore10.aspx) : Scott Hanselman이 ASP.NET 4.x와 ASP.NET Core 1.0 어플리케이션에서 교차로 쿠키를 인증하는 방법에 대해 설명합니다.
* [External Network Access to Kestrel and IIS Express in ASP.NET Core]( https://weblog.west-wind.com/posts/2016/Sep/28/External-Network-Access-to-Kestrel-and-IIS-Express-in-ASPNET-Core) : Rick Strahl이 Kestrel 와 IIS Express 환경의 ASP.NET Core 어플리케이션에서 외부 네트위크에 접근하는 방법에 대해 설명합니다.
* [Localising the DisplayAttribute and avoiding magic strings in ASP.NET Core]( https://andrewlock.net/localising-the-displayattribute-and-avoiding-magic-strings-in-asp-net-core/) and [Injecting services into ValidationAttributes in ASP.NET Core]( https://andrewlock.net/injecting-services-into-validationattributes-in-asp-net-core/) : Andrew Lock이 ASP.NET Core 에서 지역화된 문자열 표시를 위한 DisplayAttribute 사용 방법과 유효성 검증을 위한 ValidationAttributes 사용 방법에 대해 설명합니다.
* [IdentityServer4, Web API and Angular2 in a single ASP.NET Core project]( https://damienbod.com/2016/10/01/identityserver4-webapi-and-angular2-in-a-single-asp-net-core-project/) : Damien Bod이 하나의 ASP.NET Core에서 IdentityServer4, Web API, Angular2를 사용하여 구성한 프로젝트에 대해 설명합니다.
* [Introducing the ASP.Net Async SessionState Module]( https://blogs.msdn.microsoft.com/webdev/2016/09/29/introducing-the-asp-net-async-sessionstate-module/) : Matt FJH가 ASP.Net Async SessionState 모듈에 대해 소개합니다.
* [Strongly typed configuration in ASP.NET Core without IOptions<T>](http://www.strathweb.com/2016/09/strongly-typed-configuration-in-asp-net-core-without-ioptionst/) : Filip W가 ASP.NET에서 IOptions<T>없이 명시적 선언하는 방법에 대해 소개합니다.
* [ASP.NET Core MVC Attribute Routing]( http://codeopinion.com/asp-net-core-mvc-attribute-routing/) : Derek Comartin이 ASP.NET Core MVC에 Routing 속성에 대해 설명합니다.
* [Using OpenID Connect]( https://blogs.msdn.microsoft.com/mvpawardprogram/2016/09/27/using-openid-connect/) : Shaun Luttin이 OpenID Connect 활용 방법에 대해 설명합니다.

### F# 소식
* [Ionide F# 2.5.0 for VS Code is released, now you can write in F# Interactive!]( https://twitter.com/IonideProject/status/780053835729473536) : VS Code에서 사용가능한 Ionide F# 2.5.0이 릴리즈되었습니다.
* [Function Application and Composition]( http://sidburn.github.io/blog/2016/09/25/function-application-and-composition) : David Raab가 F#의 함수지향적 문법 구조와 특징에 대해 설명합니다.
* [Can programming be liberated from function abstraction?]( http://tomasp.net/blog/2016/no-functions/) : Tomas Petricek이 F# 프로그램에서 함수의 의미를 설명합니다.
* [Using the ALGLIB random forest with F#](http://brandewinder.com/2016/09/25/alglib-random-forest-with-fsharp/) : Mathias Brandewinder가 F#에 수치해석 라이브러리인 ALGLIB을 이용한 random forest에 대해 설명합니다.
* [Creating Slack Slash Commands With Azure Functions]( https://gregshackles.com/creating-slack-slash-commands-with-azure-functions/) : Greg Shackles가 Azure Function을 사용하여 Slack Slash Command를 구현하는 방법에 대해 설명합니다.
* [BuildStats.info |> F#](https://dusted.codes/buildstatsinfo-fsharp) : Dustin Moris Gorski가 빌드 상황을 표현해주는 그래픽 위젯 BuildStats.info의 사용 경험을 공유했습니다.

### Xamarin 소식
* [Stable Release: Cycle 8 Service Release 0]( https://releases.xamarin.com/stable-release-cycle-8-service-release-0/), [Preview : Xamarin Profiler 0.34.2]( https://releases.xamarin.com/preview-xamarin-profiler-0-34-2/), [Preview: iOS Simulator (for Windows) Update 5]( https://releases.xamarin.com/preview-ios-simulator-for-windows-update-5/), and [Alpha Preview: Xamarin.Mac Support on MacOS 10.12 Sierra](https://releases.xamarin.com/alpha-preview-xamarin-mac-support-on-macos-10-12-sierra/) :  Adrian Murphy가 Xamarin 업데이트 정보를 공유했습니다.
* [HockeySDK 4.1.0 for Xamarin]( https://www.hockeyapp.net/blog/2016/09/26/hockeysdk-xamarin-4-1-0.html) : HockeyApp Team에서 HockeySDK 4.1.0 for Xamarin에 대해 소개합니다.
* [Iowa Caucuses Launch Inaugural Polling Apps with Xamarin]( https://blog.xamarin.com/iowa-caucuses-launch-inaugural-polling-apps-with-xamarin/) : Lacey Butler가 Xamarin으로 미국 대선 여론조사용 모바일 어플을 개발한 사례를 공유했습니다.
* [Speech Recognition in iOS10]( https://blog.xamarin.com/speech-recognition-in-ios-10/) : Pierce Boggan이 iOS 10에서 음성 인식기능을 사용하는 방법에 대해 소개합니다.
* [Enhanced Notifications in Android N with Direct Reply]( https://blog.xamarin.com/enhanced-notifications-in-android-n-with-direct-reply/), [Android Archiving and Publishing Made Easy]( https://blog.xamarin.com/android-archiving-and-publishing-made-easy/) : James Montemagno가 Android N에서 Direct Reply를 이용한 알림(Notification)기능, 안드로이드 애플리케이션을 개발할때 백업과 배포를 더욱 쉽게 할 수 있는 방법에 대해 공유했습니다.
* [The Xamarin Show #3 : Xamarin.Forms Performance Tips and Tricks]( https://channel9.msdn.com/Shows/XamarinShow/XamarinForms-Performance-Tips-and-Tricks), and [Updating Azure Mobile SQLiteStore to 3.0]( http://motzcod.es/post/150988588867/updating-azure-mobile-sqlitestore-to-30) : Xamarin Show 3화에서는 팁&트릭 기능과 업데이트된 Azure Mobile SQLiteStore 3.0 버전 정보에 대해 공유했습니다.
* [Background Audio and Cross Platform Development with Xamarin (App Dev on Xbox series)]( https://blogs.windows.com/buildingapps/2016/09/23/background-audio-and-cross-platform-development-with-xamarin-app-dev-on-xbox-series/) : Nikola Metulev가 UWP 어플에서 배경 음악을 추가하는 방법에 대해 설명합니다.
* [Xamarin vs. Native]( https://colbylwilliams.github.io/2016/09/27/xamarin-vs-native.html), [Default Designer]( https://colbylwilliams.github.io/2016/09/26/default-designer.html), and [Type Names as Storyboard IDs]( https://colbylwilliams.github.io/2016/09/28/type-name-storyboard-id.html) : Colby Williams가 Xamarin vs. Native, Default Designer, Storyboard ID에 대해 설명합니다.
* [Toast Notifications for Xamarin Forms]( https://xamarinhelp.com/toast-notifications-xamarin-forms/), [Proxy Pattern To Separate Dependencies]( https://xamarinhelp.com/proxy-pattern-separate-dependencies/), and [Layered Dependency Injection]( https://xamarinhelp.com/layered-dependency-injection/) : Adam Pedley가 Xamarin Forms의 알림기능, 종속성 분리를 위한 Proxy Pattern, Layered Dependency Injection에 대해 설명합니다.
* [Realities of Cross-Platform Development: How Platform-Specific Can You Go?]( https://visualstudiomagazine.com/articles/2016/09/01/how-platform-specific-can-you-go.aspx) : Wallace McClure가 크로스플랫폼 어플을 개발할때, Xamarin 환경이 각 플랫폼의 특징과 기능을 얼마나 잘 표현할 수 있는지 설명합니다.
* [Debugging provisioning profiles on the command line]( http://www.knowing.net/index.php/2016/09/22/debugging-provisioning-profiles-on-the-command-line/) : Larry O’Brien이 iOS, Xamarin에서 command line 명령을 이용해서 provisioning profiles 파일을 확인하는 방법에 대해 공유했습니다.
* [How To Design Error States For Mobile Apps]( https://www.smashingmagazine.com/2016/09/how-to-design-error-states-for-mobile-apps) : Nick Babich가 모바일 어플 개발시 적절한 예외 상황 정의 방법과 올바른 예외 페이지 구현에 대해서 설명했습니다. 
* [Back It On Up! Android and Xamarin and Backups!]( https://codemilltech.com/back-up-xamarin-android/) : Matthew Soucoup가 Android 환경에서 개인화 정보 저장/불러오기 기능 구현 방법에 대해 설명합니다. 
* [Improving layout performance on Android]( http://blog.ostebaronen.dk/2016/09/improving-layout-performance-on-android.html) : Tomasz Cielecki가 Android에서 layout을 적절하게 배치하는 방법에 대해 공유했습니다.
* [Genymotion and VirtualBox install issue]( http://codeworks.it/blog/?p=502) : Corrado Cavalli가 지니 모션과 버추얼 박스를 통해서 PC에 안드로이드 에뮬레이터 환경을 구축하는 방법에 대해 공유했습니다.

### Azure 소식
* [Azure Functions in practice]( https://www.troyhunt.com/azure-functions-in-practice/) : Troy Hunt가 Azure Functions 기능에 대해 설명합니다.

### Games 소식
* [[Unity] Creating a 2D Platformer (E13. max slopes)]( https://www.youtube.com/watch?v=1i1hTLU6JTY) : Sebastian Lague가 슈퍼마리오와 같은 2D Platformer(PLATFORM GAME) 장르의 게임 구현 방법을 공유했습니다.
* [Unity – 2D Movement (Part 3B) – Jump]( https://www.youtube.com/watch?v=Kvje4xqB258) : Standard Jump : Pixel Make에서 2D Movement (Part 3B) - Jump 기능구현에 대해 설명합니다.
* [Unity – 2D Movement (Part 4A) – Shoot]( https://www.youtube.com/watch?v=xc2jsbYIXjY) : Spawn Bullet : Pixel Make에서 2D Movement (Part 3B) - Shoot 기능구현에 대해 설명합니다.
* [Curated #UnityTips No. 15 by DevDog October 2016]( http://devdog.io/blog/2016/10/11-best-unity-tips-for-game-developers-15) : DevDog가 Unity 개발에 도움이 될 수 있는 15번째 팁을 공유했습니다.
* [[Unity 5] Tutorial: How to make a climbing system like in Assassins Creed in Unity – part 9]( https://www.youtube.com/watch?v=qOdNKxUe__o&feature=youtu.be) : Game에서 ‘오르기(등반) 동작’ 구현 방법에 대해 설명합니다.


// 전무님 소개
