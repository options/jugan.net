여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### .NET Core 1.0 RTM 출시
지난 밤 개최되었던 Red Hat 의 DevNation 행사를 통해서 .NET Core 1.0 의 정식버전이 드디어 출시되었습니다. .NET Core 가 가지는 의의는 상당합니다. 우선 크로스 플랫폼을 지원하기 때문에 윈도우, MacOS, Linux 에서 모두 수행됩니다. 다양한 배포방법을 지원하기 때문에 앱에 포함된 형태로 배포되거나 사용자별, 컴퓨터별로도 설치하실 수 있습니다. 또한, 모든 기능들을 명령행 도구로 수행하실 수 있습니다. .NET Core 는 [.NET Foundation](http://www.dotnetfoundation.org/)의 일원으로 오픈소스로 개발되고 있습니다. http://dot.net 에서 좀 더 자세한 정보를 확인해보시기 바랍니다. 

* [Announcing .NET Core 1.0](https://blogs.msdn.microsoft.com/dotnet/2016/06/27/announcing-net-core-1-0/) : Richard Lander 가 .NET Core 1.0 출시 소식을 전합니다. 
* [Announcing ASP.NET Core 1.0](https://blogs.msdn.microsoft.com/webdev/2016/06/27/announcing-asp-net-core-1-0/) : Jeffrey T. Fritz 가 ASP.NET Core 1.0 출시 소식을 전합니다. 
* [.NET Core 1.0 RTM 출시](https://blogs.msdn.microsoft.com/eva/?p=11255) : 김명신 기술 에반젤리스트가 .NET Core 1.0 RTM 출시 소식의 중요 쟁점을 소개합니다. 

### 금주의 커뮤니티 소식
Taeyo.NET 에서 http://docs.asp.net 의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.

* [ASP.NET Core MVC : 컨트롤러 메서드와 뷰 살펴보기](http://taeyo.net/Columns/View.aspx?SEQ=536&PSEQ=40)
* [ASP.NET Core 기본 : 응용프로그램 StartUp](http://taeyo.net/Columns/View.aspx?SEQ=537&PSEQ=39)

### On.NET 소식
[지난 On.NET 인터뷰](https://www.youtube.com/watch?v=TmLOLCAp1N8)에서는 Pratap Lakshman 와 함께 MS Test 및 .NET Core 에서 테스트를 수행하는 것에 관한 전반적인 이야기를 나누어 보았습니다.

[이번 On.NET 인터뷰](https://www.youtube.com/watch?v=ZppqEMegCAA)는 Jeremy Kuhne 를 모시고 .NET 에서 지원하는 디렉토리 경로에 대해 이야기 나누어 보았습니다. 

### 금주의 패키지- Stuntman
사용자마다 다른 시나리오를 테스팅하고 디버깅하는 것은 정말 어렵습니다. 이를 위해서는 테스트 환경에서 사용자를 쉽고 빠르게 바꿀 수 있어야 합니다. [Stuntman](https://github.com/ritterim/stuntman) 은 .NET 의 ClaimsIdentity 클래스를 이용하여 개발 환경에서 사용자를 가장(impersonate)해줌으로서 사용자 계정 전환 작업에 도움을 주는 라이브러리입니다. 

//그림

### 금주의 컨트롤 - Telerik DataForm for Xamarin
[Telerik DataForm for Xamarin](http://www.telerik.com/xamarin-ui/dataform) 컨트롤은 풍부한 모바일 화면을 만들수 있도록 합니다. 검증 기능이 포함되어 있고 확대/축소가 가능한 그룹구성 컨트롤 그리고 커스텀 에디터 컨트롤등이 포함 되어있습니다.

//그림

### 금주의 서적 - Machine Learning Projects for .NET Developers by Mathias Brandewinder

//그림

[Machine Learning Projects for .NET Developers](http://www.apress.com/9781430267676) 라는 책은 데이터를 학습하고, 간단한 알고리즘과 머신러닝 기술을 적용하여 현실 세계의 다양한 문제들에 적용할 수 있도록 .NET 애플리케이션을 쉽게 만들 수 있는 방법을 안내합니다. 머신 러닝 로직을 구현하기 위해 개발 언어로 F# 을 이용하여 코드를 구현하고 개발 도구로는 이미 익숙한 Visual Studio를 이용합니다. F# 언어를 처음 접하시는 분들을 위해 처음 시작하는데 필요한 모든 것을 제공해 줄 것입니다. 이미 F#에 익숙하신 분이라도 이 서적을 통해서 F#을 이용한 새로운 개발 영역에 도전해 보실 수 있습니다. 

### 금주의 게임 - Smashy Brick

[Smashy Brick](http://smashybrick.com/) 은 한때 유행했던 Breakout 이나 Arkanoid 와 같은 블록 격파 게임으로 신세대를 위한 게임이며 아름다운 그래픽에 90 단계의 레벨이 있습니다. 기존 게임처럼 좌우로 움직이는 판을 움직이는 것이 아니라, 게이머가 정확한 길이와 각도를 염두하여 반사판을 직접 그리는 방식입니다. Smashy Brick 에서는 고유한 능력을 가진 캐릭터들을 최대 12 개 이용하실 수 있습니다. 귀여운 케릭터와 아름다운 배경에 현혹되지 마십시요. 단계가 올라갈수록 각 레벨의 수준도 점점 어려워 집니다!

//그림

Smashy Brick 게임은 Bulldozer Games 라는 게임회사에서 [Unity](http://unity3d.com/) 와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners) 을 이용하여 개발되었으며, 현재 iOS 와 Android 에서 무료로 즐기실 수 있습니다.  좀 더 자세한 정보는 [Smashy Brick](http://smashybrick.com/) 페이지에서 확인하실 수 있습니다.

## .NET 소식
* [NUnit 3 Tests for .NET Core RC2 and ASP.NET Core RC2](http://www.alteridem.net/2016/06/18/nunit-3-testing-net-core-rc2/) : Rob Prouse 이 .NET Core RC2 와 ASP.NET Core RC2 버전을 지원하는 NUnit 3의 두번째 알파버전에 대해 소개했습니다.  
* [Taking the MSTest Framework forward with “MSTest V2”](https://blogs.msdn.microsoft.com/visualstudioalm/2016/06/17/taking-the-mstest-framework-forward-with-mstest-v2/) : Pratap Lakshman이 MSTest와  .NET Core RC2 / ASP.NET Core RC2 환경을 지원하는 MSTest  V2 버전에 대해서 소개했습니다.
* [Visualising the .NET Garbage Collector](http://mattwarren.org/2016/06/20/Visualising-the-dotNET-Garbage-Collector/) : Matt Warren이 .NET Garbage Collector의 이벤트와 데이터를 시각화 하는 방법에 대해서 소개했습니다.
* [What’s new in .NET Core RC2 (podcast) by the Eat Sleep Code Podcast](https://soundcloud.com/esc-podcast/whats-new-in-net-core-rc2) : .NET Core RC2 의 변화된 기능에 대한 포드 케스트가 공유되었습니다.
* [Rise of the IAsyncStateMachines](https://blog.scooletz.com/2016/06/13/rise-of-the-iasyncstatemachines/) : Szymon Kulec이 C#의 비동기 키워드인 async/await 을 사용할 경우 컴파일러가 자동 생성해주는 여러 코드들에 포함된 IAsyncStateMachines 인터페이스에 대해서 설명해 주었습니다. 
* [IDisposable trumps APM](http://blog.i3arnon.com/2016/06/13/idisposable-trumps-apm/) : Bar Arnon이 Asynchronous Programming Model (APM)에서 Idisposable의 중요성에 대해서 설명하였습니다.
* [How should a class expose a collection?](https://github.com/jbe2277/waf/wiki/How-should-a-class-expose-a-collection%3F) : jbe2277 가 클래스 설계시 컬렉션 속성 구성 방법에 대해서 설명하였습니다. 
* [TreeLib: Balanced Binary Trees – Rank Augmented, for .NET](http://programmatom.github.io/TreeLib/) : Programmaton 에 TreeLib 오픈프로젝트가 소개 되었습니다.
* [IDisposable and Marshal.ReleaseCOMObject and dynamic in C#](http://msprogrammer.serviciipeweb.ro/2016/06/13/idisposable-and-marshal-releasecomobject-and-dynamic-in-c/) : Andrei Ignat 가 COM 오브젝트 활용시 주의 해야 할 점을 공유해 주었습니다.
* [ASP.NET Core and .NET Core Overview](https://weblog.west-wind.com/posts/2016/Jun/13/ASPNET-Core-and-NET-Core-Overview) : Rick Strahl이 ASP.NET Core와 .NET Core의 Overview를 공유하였습니다.

### ASP.NET 소식
* [초간단 ASP.NET Core 웹 앱 구축](https://youtu.be/WAfC_Qpe2NU), [ASP.NET Core 웹앱에 시작 클래스(Startup) 추가](https://youtu.be/GVke_fQMrzY), [ASP.NET Core 1.0 시작하기-콘솔에서 웹과 MVC까지](https://youtu.be/t9JpC4gqkjU) : 마이크로소프트 MVP 인 박용준 강사님께서 ASP.NET Core 1.0 웹 응용 프로그램 제작에 대한 시작 및 깊게 살펴보기 내용을 동영상으로 공유해 주셨습니다.
* [Creating a custom ConfigurationProvider in ASP.NET Core to parse YAML](https://andrewlock.net/creating-a-custom-iconfigurationprovider-in-asp-net-core-to-parse-yaml/) : Andrew Lock 이  ASP.NET Core 에서 YAML 문법 분석을 이용한 사용자 ConfigurationProvider의 구현 방법을 소개하였습니다.
* [Free HTTPS certificates for Docker containers running ASP.NET Core RC2 on Microsoft Azure](http://laurentkempe.com/2016/06/20/Free-HTTPS-certificates-for-Docker-containers-running-ASPNET-Core-RC2-on-Microsoft-Azure/) : Laurent Kempé 가 Microsoft Azure 클라우드의 ASP.NET Core RC2 에서 도커 컨테이너용 무료 HTTPS 인증서를 활용하는 방법을 소개하였습니다.
* [Asp.Net Core RC1, OpenIdConnect, JWT and Angular 2 SPA – Part 1](http://www.medic-consulting.com/2016/03/29/Asp-Net-Core-bug-within-AuthenticationFailed-middleware-on-redirect/) and [Part 2](http://www.medic-consulting.com/2016/06/14/Asp-Net-Core-MVC-6-OpenIdConnect-JWT-and-Angular-2-SPA-Part-2/) : Andrej Medic 가 Asp.Net Core RC1, OpenIdConnect, JWT 그리고Angular 2 SPA 에 대해서  Part 1과 part 2로 나누어 설명하였습니다. 
* [Authenticating a user with LinkedIn in ASP.NET Core](https://auth0.com/blog/2016/06/13/authenticating-a-user-with-linkedin-in-aspnet-core/) : Jerrie Pelser 이 ASP.NET Core 에서 LinkedIn 의 인증을 이용하는 방법을 소개했습니다.
* [Hybrid model binding in ASP.NET Core 1.0 RC2](https://www.billboga.com/posts/hybrid-model-binding-in-aspnet-core-10-rc2) : Bill Boga 이 ASP.NET Core 1.0 RC2 의 MVP 프로젝트에서 하이브리드 모델 바인딩을 구현하는 방법을 공유하였습니다.
* [How to create Rest API(Web API) with ASP.NET Core 1.0](http://www.dotnetjalps.com/2016/06/create-rest-webapi-aspnet-core.html) : Jalpesh Vadgama 이 ASP.NET Core 1.0에서 Rest API(Web API)를 구현하는 방법을 공유하였습니다.

### F# 소식
* [F# for the Practical Developer (video)](https://channel9.msdn.com/Events/dotnetConf/2016/F-for-the-Practical-Developer) : Phillip Carter 가 F# 을 처음 접하는 개발자를 위해 F# 언어를 소개합니다.
* [Types from data: Making structured data first-class citizens in F#](http://tpetricek.github.io/Talks/2016/fsharp-data-pldi/#/) : Tomas Petricek 이 F#의 구조적 데이터 구현을 설명하는 슬라이드를 공유해주었습니다.
* [An F# web API in Azure Container](http://udooz.net/blog/2016/06/fsharp-on-cloudy-container/) : M Sheik Uduman Ali 가 Azure 컨테이너에서 F#을 이용한 Web API의 구성방법을 공유해주었습니다
* [Updated: Getting started with Fable and Webpack](http://kcieslak.io/Getting-Started-with-Fable-and-Webpack) : Krzysztof Cieśla 이 초보자를 위한 Fable 과 Webpack 의 가이드를 제공합니다.
* [Paket 3 Released!](https://github.com/fsprojects/Paket/releases/tag/3.1.7) : .NET 의존성 관리도구인 Paket 의 3.1.7 버전이 릴리즈 되었습니다.

### Xamarin 소식
* [Xamarin.Forms UI Designer is in Beta 1](https://www.xenforms.com/) : Michael Davis 이 Xamarin.Forms 용 UI 디자이너인 XenForms 의 베타 버전 출시 소식을 공유해주었습니다. 
* [Workbooks & Inspector 0.9.0 Released](https://forums.xamarin.com/discussion/66655/workbooks-inspector-0-9-0-released) : Aaron Bockover 가 [Workbooks](https://developer.xamarin.com/guides/cross-platform/workbooks/) 과 [Inspector](https://developer.xamarin.com/guides/cross-platform/workbooks/) 의 0.9.0 버전 릴리즈 소식을 공유해주었습니다.
* [NuGet Support in Xamarin Studio 6.0](http://lastexitcode.com/blog/2016/06/12/NuGetSupportInXamarinStudio6-0/) : Matt Ward 가 Xamarin Studio 6.0 에서 개선된 NuGet 의 기능을 소개해 주었습니다.
* [ASP.NET Core 1.0 RC2 support in Xamarin Studio](http://lastexitcode.com/blog/2016/06/05/AspNetCoreRC2SupportInXamarinStudio/) : Matt Ward 가 Xamarin Studio 에서 ASP.NET Core 1.0 RC2 을 지원한다는 소식을 공유해 주었습니다.
* [Password-protected Encryption Provider for Akavache](http://kent-boogaart.com/blog/password-protected-encryption-provider-for-akavache) : Kent Boogaart 가 비동기 방식으로 Key-Value 값을 저장하는 기능을 제공한 유명한 라이브러리인 Akavache 에서 사용할 수 있는 암호화 라이브러리를 소개해 주었습니다.
* [Preview iOS simulator for Windows](https://releases.xamarin.com/preview-ios-simulator-for-windows/) : Adrian Murphy 가 현재는 프리뷰 버전인 윈도우용 iOS simulator 소개했습니다.
* [Xamarin.Forms UI designer beta released](https://www.xenforms.com/2016/06/beta-1-ready/) : Michael Davis 가 Xamarin.Forms 용 UI 디자이너인 XenForms 의 베타 버전 릴리즈 소식을 공유해주었습니다.
* [Flip through items with Xamarin.Forms CarouselView](https://blog.xamarin.com/flip-through-items-with-xamarin-forms-carouselview/) : James Montemagno 가 Xamarin.Forms (2.3.0)에서 새롭게 추가된 CarouselView 기능을 설명하였습니다.
* [Xamarin.Forms Behaviors: FadeAction](http://www.davidbritch.com/2016/06/xamarinforms-behaviors-fadeaction.html) : David Britch 가 Xamarin.Forms 에서 천천히 사라지는 효과를 주는 Fade Action 클래스와 사용 예제를 소개해주었습니다.

### Games 
* [Shaders Case Study – Hearthstone Golden Cards (Video)](https://www.youtube.com/watch?v=OYjMnMZe1Vg) : Makin’ Stuff Look Good 이 Hearthstone 게임에서 카드에 음영 효과를 주는 기법을 설명하였습니다. 
* [F# Kit by Noobtuts](http://forum.unity3d.com/threads/f-kit.411420/) : Unity 에서 F# 을 사용할 수 있게 해주는 F# Kit 가 공개 되었습니다.
* [DotNetCore Tutorial for Unity3d for Absolute Noobs](https://github.com/NVentimiglia/DotNetCoreUnity3d) : Nicholas Ventimiglia 가 초보자를 위한 Unity 3d 용 .NET Core 튜토리얼을 공유하였습니다.
* [Creating a 2D Platformer (Video)](https://www.youtube.com/watch?v=MbWK8bCAU2w&list=PLFt_AvWsXl0f0hqURlhyIoAabKPgRsqjz&index=1) : Sebastian Lague 가 슈퍼마리오와 같은 장르의 게임인 2D Platformer(PLATFORM GAME) 게임 구현 방법을 공유하였습니다.


//이사님 소개
