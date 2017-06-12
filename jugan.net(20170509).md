주간닷넷 2017년 05월 09일

### Microsoft Build 2017 소식

[Microsoft Build](https://build.microsoft.com/) 행사가 시에틀에서 열렸습니다. [채널9](https://channel9.msdn.com/events/Build/2017)을 통해서 진행된 기술세션을 보실수 있습니다.

### .NET Core 2.0 소식

이제 몇 일만 있으면 .NET Core 2.0의 현재까지 알려진 모든 버그를 픽스하기 할수 있을것 같습니다. 지금까지 상당한 개선이 있었고 많은 버그를 픽스했지만 그래도 아직 163개의 버그가 남아있습니다.

//그림1

//그림2

### Happy Birthday .NET! - Eilon Lipton

지난 2월 마이크로소프트의 OB 모임의 .NET birthday 15 주년 파티에서 .NET 초기 멤버들의 이전 활약상과 현재 근황을 알려 드린적이 있습니다. 이번 인터뷰에서는 마이크로소프트에서 2002년부터 개발자로 근무하셨고 대부분 ASP.NET 에서 일해왔던 Eilon Lipton과 함께 했습니다.  그는 자신의 가장 자랑스러운 결과물인  update panel(AJAX의 업데이트 페널)개발 경험과 초기 .NET 멤버로서 가장 기억에 남고 영광스러웠던 순간들을 공유해주었습니다.

//동영상

### On .NET

지난주에는 [Alfonso García-Caro](https://twitter.com/alfonsogcnunez)와 함께 F# 자바스크립트 컴파일러인 [Fable](http://fable.io/)에 대해서 함께 얘기했습니다.

//동영상


### 금주의 패키지: Stanford CoreNLP

[Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/index.html)는 재무/회계분야 자연어처리 라이브러리로서 .NET 버전 라이브러리인 [Stanford.NLP.NET](http://sergey-tihon.github.io/Stanford.NLP.NET//samples/CoreNLP.Simple.html)도 함께 제공합니다
 
//코드


### .NET

* [Announcing the .NET Framework 4.7 General Availability](https://blogs.msdn.microsoft.com/dotnet/2017/05/02/announcing-the-net-framework-4-7-general-availability/) : Rich Lander가 .NET Framework 4.7의 GA(General Availability) 버전을 설명했습니다.
* [Arrays and the CLR – a Very Special Relationship](http://mattwarren.org/2017/05/08/Arrays-and-the-CLR-a-Very-Special-Relationship/) : Matt Warren이 Array를 CLR 관점에서 설명했습니다.
* [ClrMD Part 3 – Dealing with static and instance fields to list timers](http://labs.criteo.com/2017/05/clrmd-part-3-dealing-static-instance-fields-list-timers/) : Christophe Nasarre와 Kevin Gosse가 "CLR MD" (Microsoft.Diagnostics.Runtime.dll)를 이용한 정적 필드, 인스턴스 필드 값의 추적방법을 설명했습니다.
* [Use a XBox Controller to control your Angular2 App](http://lostindetails.com/blog/post/Use-a-XBox-Controller-to-control-your-Angular2-app) : Martin Kramer가 XBox 게임기의 컨트롤러를 Angular2 애플리케이션에서 활용하는 방법을 설명했습니다.
* [Testing .NET Core with NUnit in Visual Studio 2017](http://www.alteridem.net/2017/05/04/test-net-core-nunit-vs2017/) : Rob Prouse가 NUnit 테스트 프레임워크와 Visual Studio 2017를 이용한 .NET Core용 애플리케이션의 테스트 방법을 설명했습니다.
* [Who needs Visual Studio? A look at using .NET Core on Linux](http://www.postsharp.net/blog/post/webinar-recording-dotnetcore-on-linux) : Iveta Moldavcuk 가 Linux 용 .NET Core의 활용방법에 대한 웨비나를 공유했습니다.
* [Debugging .NET core with SOS everywhere](https://blogs.msdn.microsoft.com/premier_developer/2017/05/02/debugging-net-core-with-sos-everywhere/) : Pam Lahoud가 SOS Debugging Extension을 이용한 .NET Core 애플리케이션의 디버깅 방법을 설명했습니다.
* [Step by step: Kafka Pub/Sub with Docker and .Net Core](https://carlos.mendible.com/2017/05/08/step-by-step-kafka-pub-sub-with-docker-and-net-core/) : Carlos Mendible가 Docker와 .Net Core 환경에서 아파지 Kafka 의 Pub/Sub 메시지 시스템 활용 위크샵 참여 경험을 공유했습니다.
* [How to Write a Sophisticated SPA: TodoMVC using C#](https://hackernoon.com/how-to-write-a-sophisticated-spa-todomvc-using-c-df81ea50f4e0) : Muigai Mwaura가 고난이도의 SPA(Single Page Applications)를 좀 더 쉽게 구현할 수 있는 방법을 소개했습니다.
* [Using .NET Core 2 to read from an I2C device connected to a Raspberry Pi 3 with Ubuntu 16.04](https://jeremylindsayni.wordpress.com/2017/05/08/using-net-core-2-to-read-from-an-i2c-device-connected-to-a-raspberry-pi-3-with-ubuntu-16-04/) : Jeremy Lindsay가 Raspberry Pi 3와  Ubuntu 16.04환경에서 .NET Core 2를 이용한 I2C 디바이스 접근 방법을 설명했습니다. 
* [Domain Command Patterns – Handlers](https://jimmybogard.com/domain-command-patterns-handlers/) : Jimmy Bogard가 Domain Command Pattern "Handlers"편을 공유했습니다.
* [Fiddler And LINQ](https://textslashplain.com/2017/05/03/fiddler-and-linq/) : Eric Lawrence가 웹 애플리케이션 디버깅 툴의 스크립트에 LINQ기능을 활용하는 방법을 설명했습니다.
* [Maximizing Throughput – The Overhead of 1 Million Tasks](https://www.danielcrabtree.com/blog/248/maximizing-throughput-the-overhead-of-1-million-tasks) : Daniel Crabtree가 대용량 작업 처리시 과도한 Task 오브젝트 사용의 단점을 설명했습니다.

### ASP.NET

* [Extending RestSharp to Handle Timeouts in ASP.NET MVC](https://www.exceptionnotfound.net/extending-restsharp-to-handle-timeouts-in-asp-net-mvc/) : Matthew Jones가 ASP.NET MVC 환경에서 타임아웃기능이 포함된 확장 RestSharp 의 개발방법을 설명했습니다.
* [Starting a http file server from the file explorer using .NET Core](https://www.meziantou.net/2017/05/02/starting-a-http-file-server-from-the-file-explorer-using-net-core) : Gérald Barré가 .NET Core 환경에서 정적 파일 웹 서버의 구축 방법을 설명했습니다.
* [ASP.NET Core – API versioning by convention](https://tpodolak.com/blog/2017/05/04/asp-net-core-api-versioning-convention/) : Tpodolak이 ASP.NET Core의 사용자 API 버전에 관련된 정보를 공유했습니다.
* [IIS and ASP.NET Core Rewrite Rules for Static Files and Html 5 Routing](https://weblog.west-wind.com/posts/2017/Apr/27/IIS-and-ASPNET-Core-Rewrite-Rules-for-AspNetCoreModule) : Rick Strahl이  ASP.NET Core를 IIS 환경에서 활용할 경우의 장점을 설명했습니다.
* [Large JSON Array Streaming in ASP.NET Web API](https://www.codeproject.com/Articles/1180464/Large-JSON-Array-Streaming-in-ASP-NET-Web-API) : Robert Vandenberg Huang이 ASP.NET Web API 환경에서 대용량 JSON 배열을 스트리밍 처리하는 방법을 설명했습니다.
* [Create API with ASP.NET Core (Day 1): Getting Started and ASP.NET Core Request Pipeline](https://www.codeproject.com/Articles/1184870/Create-API-with-ASP-NET-Core-Day-Getting-Started-a) : Akhil Mittal이 ASP.NET Core 활용 API 구축하기(1편) - "ASP.NET Core Request Pipeline 이해하기" 소식을 공유했습니다.
* [Installing ASP.NET Core Docker For Windows](https://www.codeproject.com/Articles/1185904/Installing-ASP-NET-Core-Docker-For-Windows) : Sibeesh Passion이 윈도우에서 ASP.NET Core 도커의 설치방법을 공유했습니다. 
* [Login & Authentication for your ASP.NET Core Web API – The Big Picture](https://jonhilton.net/2017/05/03/login-authentication-asp-net-core-web-api-big-picture/) : Jon Hilton이 ASP.NET Core Web API 애플리케이션에서 로그인 및 인증과 관련된 개념을 설명했습니다.
* [Using Angular in an ASP.NET Core View with Webpack](https://damienbod.com/2017/05/02/using-angular-in-an-asp-net-core-view-with-webpack/) : damienbod가 ASP.NET Core View와 Webpack 프레임워크 환경에서 Angular 활용법을 설명했습니다.
* [Secure ASP.NET Core MVC with Angular using IdentityServer4 OpenID Connect Hybrid Flow](https://damienbod.com/2017/05/06/secure-asp-net-core-mvc-with-angular-using-identityserver4-openid-connect-hybrid-flow/) : damienbod가 Angular와 ASP.NET Core MVC 환경에서 IdentityServer4 의 OpenID 활용법을 공유했습니다.
* [Plugins for ASP.NET Core Middleware](https://devblog.dymel.pl/2017/05/03/aspnetcore-middleware-plugins/) : Michal Dymel이 ASP.NET Core Middleware에서 활용할수있는 Plugin의 구현방법을 설명했습니다.
* [Publish And Deploy ASP.NET Core MVC On IIS](http://www.c-sharpcorner.com/article/publish-and-deploy-asp-net-core-mvc-on-iis/) : Jignesh Trivedi가 ASP.NET Core MVC를 IIS에 배포, 게시하는 방법을 공유했습니다.
* [Using ImageSharp to resize images in ASP.NET Core – Part 2](https://andrewlock.net/using-imagesharp-to-resize-images-in-asp-net-core-part-2/) : Andrew Lock이 "ASP.NET Core에서 ImageSharp 을 이용한 이미지 resize 방법-파트2"를 공유했습니다.
* [Registering Open Generics in ASPNET Core Dependency Injection](http://ardalis.com/registering-open-generics-in-aspnet-core-dependency-injection) : Steve Smith이 ASPNET Core DI(Dependency Injection) 기능 중 제너릭 메서드의 활용방법을 공유했습니다.
* [When Should You Upgrade to ASP.NET Core?](http://ardalis.com/when-should-you-upgrade-to-asp-net-core) : Steve Smith가 ASP.NET Core 버전과 업그레이드 가이드 정보를 공유했습니다.
* [Self Descriptive HTTP API in ASP.NET Core: Object as Resource](https://codeopinion.com/self-descriptive-http-api-in-asp-net-core-object-as-resource/) : Derek Comartin이 OAR(Object as Resource) 패턴을 설명했습니다.
* [Adding WebApi & OAuth Authentication to an Existing Project](https://blogs.msdn.microsoft.com/mvpawardprogram/2017/05/02/adding-webapi-oauth-auth/) : Mitchell Sellers가 기존 프로젝트에 WebApi 와 OAuth 인증 추가방법을 공유했습니다.
* [ASP.NET Core Anatomy (Part 4) – Invoking the MVC Middleware-Dissecting and understanding the internals of ASP.NET Core](https://www.stevejgordon.co.uk/invoking-mvc-middleware-asp-net-core-anatomy-part-4) : Steve Gordon이 ASP.NET Core MVC 분석 (파트4)- "MVC Middleware 호출, ASP.NET Core 내부 이해하기": 편을 공유했습니다.

### C#

* [Just Another .NET AOP Framework: NConcern](https://www.codeproject.com/Tips/1185797/Just-Another-NET-AOP-Framework-NConcern) : 남정현님이 AOP(Aspect Oriented Programming) 프레임워크 NConcern을 소개했습니다.
* [Practical C# Videos – Tuples and Is Expression](http://www.andreaangella.com/2017/05/csharp-videos-tuples-is-expression/) : Andrea Angella가 C# 개발언어 학습 동영상 리스트를 공유했습니다.
* [The curious case of async, await, and IDisposable](http://thebillwagner.com/Blog/Item/2017-05-03-ThecuriouscaseofasyncawaitandIDisposable) : Bill Wagner가 async, await 키워드를 이용한 비동기 메서드와 IDisposable을 연관하여 설명했습니다.
* [De-virtualization in CoreCLR: Part I](https://ayende.com/blog/177986/de-virtualization-in-coreclr-part-i) : Ayende Rahien이 CoreCLR에서 코드의 "역-가상화" 1편을 공유했습니다.
* [De-virtualization in CoreCLR: Part II](https://ayende.com/blog/177987/de-virtualization-in-coreclr-part-ii?Key=abe080c5-2d7d-4352-84e1-3da60103f3d6) : Ayende Rahien이 CoreCLR에서 코드의 "역-가상화" 2편을 공유했습니다.
* [.NET Core with csproj](https://csharp.christiannagel.com/2017/05/05/dotnetcore/) : Christian Nagel이 자신이 집필중인 기술서적의 Chapter 46, ".NET Core with csproj" 부분을 공유했습니다.

### F#

* [F# Survey 2017](https://docs.google.com/forms/d/e/1FAIpQLSeZ1EJe1pfztiUudIclcMU1lV-vXCUlGqECPQMZxFD6Q0zGoA/viewform) : F# community에서 F# 기능 설문조사를 진행하였습니다.
* [Tooling for Your .NET Projects](http://www.codemag.com/article/1705051) : Rachel Reese가 .NET 프로젝트에 도움이 되는 툴을 공유했습니다.
* [ON.NET – Alfonso García-Caro – Fable](https://channel9.msdn.com/Shows/On-NET/Alfonso-Garca-Caro-Fable) : Alfonso García-Caro가 F#의 자바스크립트 변환 컴파일러인 Fable 을 소개했습니다.
* [Calling F# Code in a C# Project](http://connelhooley.uk/blog/2017/04/30/f-sharp-to-c-sharp) : Connel Hooley가 C# 프로젝트에서 F# 코드를 호출하는 방법을 설명했습니다. 
* [Scratching a 7-Year Itch](https://pblasucci.wordpress.com/2017/05/02/seven-year-itch/) : Paulmichael Blasucci가 자신이 개발한 fszmq 라이브러리의 7년간의 진행과정을 공유했습니다.
* [Higher Kindended Types in F# Part IV – Signature Annotations](https://robkuz.github.io/HKTs-in-fsharp-part-IV-Signature-Annotations/) : Robert Kuzelj가 F#의 HKT(Higher Kindended Types) 타입 4편 "Signature Annotations"을 공유했습니다.

새로운 F# RFC를 소개합니다
* [F# RFC FS-1032 – Support for F# in the dotnet sdk](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1032-fsharp-in-dotnet-sdk.md)
* [F# RFC FS-1033 – Extend String module](https://github.com/fsharp/fslang-design/blob/master/RFCs/FS-1033-extend-string-module.md)

### Xamarin

* [Xamarin Beta Release: 15.2 Preview 2](https://releases.xamarin.com/beta-release-15-2-preview-2/) :  Luis Aguilera가 Xamarin의 Beta Release: 15.2 Preview 2 릴리즈 소식을 공유 했습니다.
* [Pre-release: Xamarin.Forms 2.3.5.235-pre2](https://releases.xamarin.com/pre-release-xamarin-forms-2-3-5-235-pre2/) : David Ortinau 가 Xamarin.Forms 2.3.5.235-pre2 버전  정보를 공유했습니다.
* [Xamarin University Guest Lecture Recordings Now Free for Everyone!](https://blog.xamarin.com/xamarin-university-guest-lecture-recordings-now-free-everyone/) : Mark Smith가 Xamarin University의 새로운 무료 학습 동영상을 공유했습니다.
* [Making Your Xamarin.Forms Apps Accessible](https://blog.xamarin.com/accessbility-xamarin-forms/) : Paul DiPietro가 Xamarin.Forms의 기존의 Accessibility 클래스의 새 이름인 AutomationProperties 를 설명했습니다.
* [Shopbox Uses C# to Empower Small Business Owners with the Point of Sale System of the Future](https://blog.xamarin.com/shopbox-uses-c-empower-small-business-owners-pos-system-future/) : Lacey Butler가 테블릿 기반 포스(POS, Point-of-Sale) 시스템 Shopbox 의 성공사례를 공유했습니다.
* [Welcome the New Xamarin MVPs!](https://blog.xamarin.com/welcome-new-xamarin-mvps/) : Jayme Singleton이 새롭게 선정된 Xamarin MVP 멤버들을 소개했습니다.
* [Xamarin Events Blossoming in May](https://blog.xamarin.com/xamarin-events-blossoming-may/) : Jayme Singleton이 5월 Xamarin 개발자 행사 정보를 공유했습니다.
* [Developing Enterprise Apps using Xamarin.Forms](https://blog.xamarin.com/developing-enterprise-apps-using-xamarin-forms/) : David Britch가 Xamarin.Forms을 이용한 업무 애플리케이션 개발 방법을 소개했습니다.
* [Snack Pack 11: Understanding Android API Level Settings](https://channel9.msdn.com/Shows/XamarinShow/Snack-Pack-11-Understanding-Android-API-Level-Settings) : Xamarin Show에서 James Montemagno 가 "Snack Pack 11: 안드로이드 API 레벨 설정하기" 동영상을 공유하였습니다.
* [Moving towards MvvmCross 5.0](https://www.mvvmcross.com/mvvmcross/2016/12/14/MovingtowardsMvvmCross5.html) : MvvmCross에서 MvvmCross 5.0의 개발 계획을 공유했습니다. 
* [Create a Backend for Xamarin.Forms using Azure Mobile App’s Easy Tables](https://mindofai.github.io/Create-a-Backend-for-Xamarin.Forms-using-Azure-Mobile-App-Service/) : Bryan Anthony Garcia가 Azure Mobile의 Easy Tables 기능을 활용한 Xamarin.Forms용 백앤드 서비스 개발방법을 소개했습니다.
* [Fantastic Fonts in Xamarin.Forms](https://codemilltech.com/fantastic-fonts-in-xamarin-forms/) : Matthew Soucoup이 Xamarin.Forms에서 사용자 지정 폰트 추가 방법을 공유했습니다.
* [Things I Think Are Cool: JSON Copy in Xamarin Studio](https://codemilltech.com/things-i-think-are-cool-p/) : Matthew Soucoup이 Xamarin Studio의 JSON Copy 기능을 소개했습니다.
* [Xamarin.Tips – Creating a Material Design Button in iOS](https://alexdunn.org/2017/05/02/xamarin-tips-creating-a-material-design-button-in-ios/) : Alex Dunn이 iOS용 커스텀 디자인이 적용된 버튼 개발을 설명했습니다.
* [Xamarin.Tips – Making Your iOS Frame Shadows More Material](https://alexdunn.org/2017/05/01/xamarin-tips-making-your-ios-frame-shadows-more-material/) : Alex Dunn이 그림자 효과가 적용된 iOS용 프레임 컨트롤 개발을 설명했습니다.
* [Xamarin forms – custom ListView separator without BoxView](http://depblog.weblogs.us/2017/04/29/xamarin-forms-custom-listview-separator-without-boxview/) : Glenn Versweyveld가 ListView에 구분선 추가 방법을 설명했습니다.
* [Get more reviews for your Xamarin.Forms app with iOS 10.3](https://blog.verslu.is/xamarin/xamarin-forms-xamarin/get-more-reviews-for-your-xamarin-forms-app-with-ios-10-3/) : Gerald Versluis가 iOS 10.3의 애플리케이션 평가기능 활용방법을 공유했습니다.
* [Xamarin Forms For Windows Developers: Tips, Tricks And Lessons Learned, Part 1](http://www.wintellect.com/devcenter/speterson/xamarin-forms-for-windows-developers-tips-tricks-and-lessons-learned-part-1) : Scott Peterson이 윈도우 개발자를 위한 Xamarin Forms 개발 방법-파트1을 공유했습니다.
* [Xamarin Forms For Windows Developers: Tips, Tricks And Lessons Learned, Part 2](http://www.wintellect.com/devcenter/speterson/xamarin-forms-for-windows-developers-tips-tricks-and-lessons-learned-part-2) : Scott Peterson이 윈도우 개발자를 위한 Xamarin Forms 개발 방법-파트2을 공유했습니다.
* [Solving Real-World Problems with Xamarin.Forms](http://developer.telerik.com/products/ui-for-xamarin/solving-real-world-problems-with-xamarin-forms/) : Sam Basu가 Xamarin.Forms 을 이용한 개발 방법론을 공유했습니다.
* [Android emulator crashes as soon as it starts](http://www.devprotocol.com/android-emulator-crashes-as-soon-as-it-starts/) : Jan Tourlamain이 안드로이드 에뮬레이터의 비정상 종료 현상과 해결방법을 공유했습니다.

### Azure
* [Filtering Application Insights](http://blog.ramondeklein.nl/2017/05/05/filtering-application-insights/) : Ramon de Klein이 Application Insights의 필터링 기능을 설명했습니다.
* [Build a Serverless MBaaS with Azure Functions](https://shellmonger.com/2017/05/03/build-a-serverless-mbaas-with-azure-functions/) : Adrian Hall이 Azure Function을 이용하여 Serverless MBaaS(mobile backends as a service)를 구축하는 방법을 설명했습니다.


### UWP
* [Make App Promotions Work: Acquire & Re-engage the Right Set of Users](https://blogs.windows.com/buildingapps/2017/05/01/make-app-promotions-work-acquire-re-engage-right-set-users/) : Kiran Bangalore가 "사용자에게 올바르게 애플리케이션 할인 정보 제공하기" 방법을 공유했습니다
* [Master the Master-Detail Pattern](https://blogs.windows.com/buildingapps/2017/05/01/master-master-detail-pattern/) : Windows Apps Team에서 마스터-디테일 패턴의 구현방법을 설명했습니다.
* [Hitchhiking the HoloToolkit-Unity, Leg 14-More with Spatial Understanding](https://mtaulty.com/2017/05/03/hitchhiking-the-holotoolkit-unity-leg-14-more-with-spatial-understanding/) : Mike Taulty가 HoloToolkit을 이용한 샘플개발 14번째 "공간에 대한 좀더 구체적인 이해"를 공유했습니다.
* [CultureInfo changes in UWP – Part 2](https://www.pedrolamas.com/2017/05/03/cultureinfo-changes-in-uwp-part-2/) : Pedro Lamas가 UWP 에서 CultureInfo 변경방법을 설명했습니다.

### Data 
* [What is Micro ORM?](http://gunnarpeipman.com/2017/05/micro-orm/) : Gunnar Peipman가 Micro ORM을 설명하였습니다.

// 전무님 소개
