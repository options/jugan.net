여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷](https://www.facebook.com/jugan.net/) 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 커뮤니티 소식
Taeyo.NET 에서 [http://docs.asp.net](http://docs.asp.net/) 의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.

* [MVC : Model - 응답 데이터 서식화](http://taeyo.net/Columns/View.aspx?SEQ=555&PSEQ=40)

Microsoft MVP인 박문찬님께서 C# UWP App 기초 개발 과정을 개설하셨습니다. 관심 있는 분들은 확인해 보셔도 좋을 것 같습니다.

* [Windows 10 UWP App(C#, XAML) 개발 - 기초 과정](http://onoffmix.com/event/75919)

### On .NET 소식
[지난 주 On .NET](https://www.youtube.com/watch?v=wPNKyC5sbac)에서는 Pablo Santos 및 Francisco Monteverde와 함께 [PlasticSCM](https://www.plasticscm.com/)에 대해 얘기를 나누어 보았습니다. PlasticSCM은 Semantic Merge와 같은 흥미로운 기능을 포함하는 형상 관리 (Version Control) 시스템입니다. 이미 유명한 형상 관리 시스템인 Git에 익숙하시고, Git만한 프로그램 없다고 생각하신다면, 이 비디오를 통해 깜짝 놀랄 준비 하시죠!

// 동영상

[이번 주 On .NET]에서는 Unity 3D의 Lucas Meijer와 함께 얘기를 나누어 보겠습니다.

### 금주의 패키지 - Orleans
[Orleans](http://dotnet.github.io/orleans/)은 복잡한 동시성 및 고가용성 패턴을 배우지 않아도 고가용 분산 애플리케이션(Distributed High-Scale Computing Applications)을 쉽게 구현할 수 있게 하는 프레임워크입니다. Microsoft Research에서 만들었으며 클라우드 환경에서 사용될 수 있도록 설계되었습니다.

Orleans는 Microsoft Azure로 제공되고 있으며, 주로 Microsoft 제품군에서 널리 사용됩니다. 특히 343 Industries가 개발한 액션 슈팅 게임 Halo 4와 Halo 5의 클라우드 서비스를 구축하는 데에도 널리 사용이 됐고, 여러 회사들도 Orleans를 채택하고 있습니다.

아래 예제는 Orleans가 사용자의 출입을 관리하는 예제 코드입니다.

// 코드

아래 예제는 클라이언트를 구성할 때 사용할 수 있는 예제 코드입니다.

// 코드

### .NET 소식
* [Introducing the .NET Framework Monthly Rollup](https://blogs.msdn.microsoft.com/dotnet/2016/08/15/introducing-the-net-framework-monthly-rollup) : Stacey Haffner가 한 달간 있었던 .NET Framework 소식을 정리해 주었습니다.
* [Announcing NuGet 3.5 RC](http://blog.nuget.org/20160811/Announcing-NuGet-3.5-RC.html) : Harikrishna Menon이 NuGet 3.5 RC 버전의 출시 소식을 공유했습니다.
* [How to avoid recursion](http://metacoding.azurewebsites.net/2016/08/16/how-to-avoid-recursion/) : Matthieu Mezil이 재귀함수를 최적화 하는 기법을 공유했습니다.
* [I tell you, that thing is a bona fide ZEBRA, or a tale of being utterly stupid](https://ayende.com/blog/174947/i-tell-you-that-thing-is-a-bona-fide-zebra-or-a-tale-of-being-utterly-stupid) 및 [Exceptional costs, Part II](https://ayende.com/blog/175010/digging-into-the-coreclr-exceptional-costs-part-ii) : Ayende Rahien이 .NET 애플리케이션 디버그시 발생할 수 있는 예외 사항을 설명했으며 예외 처리 성능에 대해서 설명했습니다.
* [Building a Producer Consumer Queue with TPL Dataflow](https://jeremydmiller.com/2016/08/09/building-a-producer-consumer-queue-with-tpl-dataflow/) 및 [Health Monitoring and Task Reassignment in our Service Bus Applications](https://jeremydmiller.com/2016/08/11/using-the-bully-algorithm-in-our-service-bus-applications/) : Jeremy D Miller가 TPL Dataflow 라이브러리를 이용한 Queue의 구현과 FubuMVC를 이용한 Service Bus Applications의 기능에 대해서 설명했습니다.
* [MSTest V2 – First impressions](http://blog.drorhelper.com/2016/08/mstest-v2-first-impressions.html) : Dror Helper가 테스트 프레임워크인 MSTest V2의 첫 사용 경험을 공유했습니다.
* [Retrieving Performance Counter from a remote PC using C#](http://www.productiverage.com/retrieving-performance-counter-from-a-remote-pc-using-c-sharp) : Productive Rage에서 C#을 이용하여 성능 측정기 값을 원격 PC에서 조회하는 구현 방법을 공유했습니다.
* [Couchbase .NET SDK 2.3.5 now available with .NET Core support](http://blog.couchbase.com/2016/august/couchbase-.net-sdk-2.3.5-now-available) : Jeff Morris가 .NET Core를 지원하는 Couchbase .NET SDK 2.3.5 출시 소식을 공유했습니다.
* [Application Insights & Semantic Logging for Service Fabric Microservices](http://www.medic-consulting.com/2016/08/12/Application-Insights-and-Semantic-Logging-for-Service-Fabric-Microservices/) : Andrej Medic이 Service Fabric Microservices에서 Application Insights와 Semantic Logging를 사용하는 방법을 소개했습니다.

### ASP.NET 소식
Microsoft MVP인 박용준 강사님께서 ASP.NET Core 관련 동영상 강의를 공유해 주셨습니다.
* [SPA 만들기 파트 5 : Angular로 발표자 상세보기 페이지 기본 완성하기](https://youtu.be/tgWtd3gmL7E)
* [SPA 만들기 파트 6 : WebAPI를 사용하여 발표자 리스트 정보를 JSON으로 제공하여 사용하기](https://youtu.be/7Z2e5sImcsU)

* [Debug Dockerized .NET Core Apps with VS Code](http://www.bloggedbychris.com/2016/08/03/debug-dockerized-net-core-apps-code/) : Chris Myers가 Visual Studio Code를 이용한 Docker용 .NET Core 애플리케이션의 디버그 방법을 소개했습니다.
* [Introduction to Authentication with ASP.NET Core](http://andrewlock.net/introduction-to-authentication-with-asp-net-core/) 및 [Access services inside ConfigureServices using IConfigureOptions in ASP.NET Core](http://andrewlock.net/access-services-inside-options-and-startup-using-configureoptions/) : Andrew Lock이 ASP.NET Core의 인증 절차와 IConfigureOptions을 이용한 ConfigureServices의 사용 방법을 설명하였습니다.
* [Practical Permissions-based Authorization in ASP.NET Core MVC](http://benjamincollins.com/blog/practical-permission-based-authorization-in-asp-net-core/) : Ben Collins가 ASP.NET Core MVC의 Authorization을 설명하였습니다.
* [Real-World ASP.NET Core MVC Filters](https://msdn.microsoft.com/en-us/magazine/mt767699.aspx) : Steve Smith가 ASP.NET Core MVC의 Filter를 설명했습니다.
* [Using Semantic UI with ASP.NET Core](http://www.khalidabuhakmeh.com/using-semantic-ui-with-asp-net-core) 및 [Strongly Typed Configuration Settings in ASP.NET Core Part II](http://rimdev.io/strongly-typed-configuration-settings-in-asp-net-core-part-ii/) : Khalid Abuhakmeh가 ASP.NET Core에서 Semantic UI의 설정 및 사용 방법 설명과 Strongly Typed Configuration의 사용법을 공유했습니다.
* [Global Routes for ASP.NET Core MVC](http://benjii.me/2016/08/global-routes-for-asp-net-core-mvc/) : Ben Cull이 ASP.NET Core MVC의 Global Routes에 대해서 설명했습니다.
* [Add Swagger to ASP.NET Core Web API](http://www.talkingdotnet.com/add-swagger-to-asp-net-core-web-api/) : Talking Dotnet에서 ASP.NET Core에 RESTful API 라이브러리인 Swagger를 추가하는 방법을 공유했습니다.
* [Should I Use ASP.NET Core or MVC 5?](http://www.jeffreyfritz.com/2016/08/should-i-use-asp-net-core-or-mvc-5/) : Jeffrey T Fritz가 ASP.NET Core와 MVC 5를 비교 설명했습니다.
* [WebAPIContrib.Core](https://channel9.msdn.com/coding4fun/blog/WebAPIContribCore) : Greg Duncan이 WebAPIContrib.Core를 소개했습니다.

### F# 소식
* [Jet.com, an F# and Azure startup, sells for 3 Billion Dollars](https://techcrunch.com/2016/08/07/walmart-buys-jet-com-for-3-billion/) : 미국 월마트가 jet.com을 33억 달러(약 3조 6316억원)에 인수한다는 소식을 전했습니다.
* [How to Parse a Git Log with FParsec](http://blog.leifbattermann.de/2016/08/11/how-to-parse-a-git-log-with-fparsec/) : Leif Batterman이 Fparsec를 이용한 Git Log를 파싱하는 방법을 공유했습니다.
* [Understanding Xamarin Forms Data Bindings with F#](https://kimsereyblog.blogspot.com.by/2016/08/understand-xamarin-forms-data-bindings.html) : Kimserey Lam이 F#을 이용한 Xamarin Forms의 데이터 바인딩을 소개했습니다.
* [Experiment with F# for Data Visualization of the Olympics](http://rio2016.thegamma.net/) : Tomas Petricek이 F#을 이용한 올림픽 데이터의 시각화(Data Visualization) 작업 경험을 공유했습니다.
* [A F# Akka.NET actor example for pub-sub pattern with NATS server](http://carstenj.io/2016/07/01/docker-nats.io-akka.net-fsharp.html) : Сarsten Jørgensen이 F# Akka.NET의 NATS Server 환경에서 Publish–subscribe pattern 패턴의 actor 예를 소개했습니다.

### Xamarin 소식
* [Xamarin Dev Days: More Dates & More Cities!](https://blog.xamarin.com/xamarin-dev-days-more-dates-more-cities/) : Jayme Singleton이 Xamarin Dev Days 행사에 대해 소개했습니다.
* [Preview: iOS 10 / Xcode 8 / Sierra Support Update 2](https://releases.xamarin.com/preview-ios-10-xcode-8-sierra-support-update-2/) 및 [Preview: iOS Simulator (For Windows) update 3](https://releases.xamarin.com/preview-ios-simulator-for-windows-update-3/) : Adrian Murphy가 iOS 10 / Xcode 8 / Sierra를 지원하는 Update 2 소식과 iOS Simulator update 3 소식을 공유했습니다.
* [Authenticating Mobile Apps with Azure Active Directory B2C](https://blog.xamarin.com/authenticating-mobile-apps-with-azure-active-directory-b2c/) 와 [Performing OCR for iOS, Android, and Windows with Microsoft Cognitive Services](https://blog.xamarin.com/performing-ocr-for-ios-android-and-windows-with-microsoft-cognitive-services/) : Pierce Boggan이 Azure Active Directory B2C를 이용한 모바일 앱 인증과 iOS, Android, Windows용 애플리케이션에 Microsoft Cognitive Services를 이용하여 OCR 기능을 추가하는 방법을 공유했습니다.
* [Declarative & implicit animations Library for Xamarin Forms](https://github.com/OliveTreeBible/Xamarin.Transitions) : Olive Tree가 Xamarin.Forms용 에니메이션 라이브러리를 소개했습니다.
* [Announcing Cake.Raygun](https://ghuntley.com/archive/2016/08/09/announcing-cake-raygun/) : Geoffrey Huntley가 Cake.Raygun add-in을 소개했습니다.
* [Interacting with Siri on Xamarin in iOS 10](https://xamarinhelp.com/interacting-siri-xamarin/) : Adam Pedley가 iOS 10의 Siri를 활용하는 방법을 공유했습니다.
* [Formatted number entry](http://thatcsharpguy.com/post/formatted-number-entry/) : Antonio Feregrino Bolaños가 C#의 숫자 포맷을 설명했습니다.
* [Creating Animations with Xamarin.Forms](https://blog.xamarin.com/creating-animations-with-xamarin-forms/) : David Britch가 Xamarin.Forms에서 에니메이션 구현 방법을 설명했습니다.
* [Composable Customizations with Xamarin.Forms](https://visualstudiomagazine.com/articles/2016/08/01/composable-customizations.aspx) : Greg Shackles가 Xamarin.Forms의 다양한 기능에 대해 설명했습니다.
* [Installing a PCL into netstandard Libraries](http://motzcod.es/post/148657853472/installing-a-pcl-into-netstandard-libraries) : James Montemagno가 PCL(Portable Class Library)을 Netstandard Libraries에 활용하는 과정과 방법을 공유했습니다.
* [Using the ContainerView to Transition between Views – aka More Fragments in Xamarin.iOS](http://www.blogaboutxamarin.com/using-the-containerview-to-transition-between-views-aka-more-fragments-in-xamarin-ios/) : Richard Woollcott이 Xamarin.iOS에서 ContainerView를 활용하는 방법을 소개했습니다.

// 전무님 소개