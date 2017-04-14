여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 커뮤니티 소식
[Taeyo.NET](http://taeyo.net/)에서 [http://docs.asp.net](http://docs.asp.net) 의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.

* [ASP.NET Core 보안(인증) : 쿠키 미들웨어 사용하기](http://taeyo.net/Columns/View.aspx?SEQ=595&PSEQ=39)

### On .NET 소식
지난 주 On .NET 소식에서는 두개의 비디오를 공유해 드렸습니다. [첫번째 비디오](https://channel9.msdn.com/Shows/On-NET/Scott-Hunter-NET-Core-SDK)에서는  [Scott Hunter](https://twitter.com/coolcsh)가 Visual Studio 2017과 .NET Core에 대해서 얘기해주었습니다

//사진

[두번째 비디오](https://sec.ch9.ms/ch9/a249/7911e380-dc96-4c73-8278-33a5df15a249/onnet20170309mattwatsonprefix_high.mp4)에서는 [Stackify](https://stackify.com/)의 [Matt Watson](https://stackify.com/author/mwatson/)이 가볍고 빠른 웹 개발 도구로서 실시간 로그, 에러, 쿼리 등의 도움기능과 성능 분석 기능을 가진 [Prefix](https://stackify.com/prefix/)를 소개해 주었습니다.


//사진

이번주 On .NET 쇼는 예정 되어있지 않습니다

### Happy Birthday .NET!
지난주에는 마이크로스프트 멤버 OB 모임이 있었습니다. 이전 .NET 팀들과 함께 .NET 15주년을 축하하며 즐거운 시간을 보냈습니다. 참석 하신분들중 개발자 커뮤니티 지원 부서의 원년 맴버이며 MVP 프로그램 발전에도 많은 도움을 주었던 Dee Dee Walsh가 Happy Birthday .NET 비디오에 함께해 주셨습니다. 

//동영상

### 금주의 패키지: C#용 MessagePack 
지금까지 직렬화(serialization) 관련된 라이브러리를 소개시켜드릴 기회가 몇번있었는데 이번에 또 다른 하나를 더 소개해 드리려 합니다. 라이브러리 [MessagePack](http://msgpack.org/)는 효율적인 바이너리 직렬화 포멧을 지원하며 약 50여 가지의 다양한 개발 플랫폼을 지원함니다. No SQL 메모리 데이터베이스인 Redis 에서도 사용가능 하며 .NET 플랫폼에서 사용가능하도록 구현된 MessagePack 라이브러리는 최소 5가지 이상의 버전이 있습니다. 그중 오늘 소개해 드릴 MessagePack은 [ZeroFormatter](https://github.com/neuecc/ZeroFormatter/)를 개발한 개발자 Yoshifumi Kawai가 구현한 [MessagePack for C#](https://github.com/neuecc/MessagePack-CSharp)으로 neuecc라고도 알려져 있습니다. 이 라이브러리는 LZ4 압축 알고리즘을 지원하며, 직렬화 작업 및 역직렬화 작업을 아주 빠르게 하실 수 있으며, 결과물의 크기도 아주 작습니다.

사용 방법은 다음과 같습니다. 직렬화 대상 데이터 객체를 아래와 같이 정의할 수 있습니다.

[MessagePackObject]
public class MyClass
{
// Key is serialization index, it is important for versioning.
[Key(0)]
public int Age { get; set; }
[Key(1)]
public string FirstName { get; set; }
[Key(2)]
public string LastName { get; set; }
// public members and does not serialize target, mark IgnoreMemberttribute
[IgnoreMember]
public string FullName { get { return FirstName + LastName; } }
}

그런 다음 직렬화 작업과 역직렬화 작업을 수행하면 됩니다. 

var mc = new MyClass
{
Age = 23,
FirstName = "Bertrand",
LastName = "Le Roy",
};
var bytes = MessagePackSerializer.Serialize(mc);
var mc2 = MessagePackSerializer.Deserialize<MyClass>(bytes);

### .NET 소식
* [What’s New in the .NET Platform (video)](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2017-Launch/T103) : Scott Hunter 가 .NET Platform 소개 동영상을 공유했습니다
* [Announcing NuGet 4.0 RTM](http://blog.nuget.org/20170308/Announcing-NuGet-4.0-RTM.html) : Anand Gaurav 가 NuGet 4.0 RTM을 소개했습니다
* [Optimize your productivity with .NET in Visual Studio 2017](https://blogs.msdn.microsoft.com/visualstudio/2017/03/08/optimize-your-productivity-with-net-in-visual-studio-2017-2/) : Kasey Uhlenhuth가 Visual Studio 2017의 개발 생산성 기능을 설명했습니다 
* [Live Unit Testing in Visual Studio 2017 Enterprise](https://blogs.msdn.microsoft.com/visualstudio/2017/03/09/live-unit-testing-in-visual-studio-2017-enterprise/) : Joe Morris 와 Manish Jayaswal가 Visual Studio 2017 Enterprise의 새로운 기능 중 "Live Unit Testing" 기능을 소개했습니다
* [Run To Click Debugging in Visual Studio 2017](https://blogs.msdn.microsoft.com/visualstudioalm/2017/03/07/run-to-click-debugging-in-visual-studio-2017/) : Kaycee Anderson 가 Visual Studio 2017 의 새로운 디버깅 기능 "Run To Click Debugging" 을 소개했습니다
* [Cake v0.18.0 released](http://cakebuild.net/blog/2017/03/cake-v0.18.0-released) : Cake v0.18.0 버전이 릴리즈 되었습니다
* [Getting Started with .NET Core on Mac and Linux by Nate Cook for Pluralsight](https://www.pluralsight.com/courses/dotnet-core-mac-linux-getting-started) : 교육 사이트인 Pluralsight에 ".NET Core on Mac and Linux" 과정이 새롭게 개설되었습니다
* [P/invoke with unions in C#](http://yizhang82.me/pinvoke-union) : Yi Zhang이 C#으로 P/invoke 호출시 union의 사용 방법을 설명했습니다
* [Exploring .NET Core with Visual Studio 2017 and the updated CLI Tools](http://michaelcrump.net/part11-aspnetcore/) : Michael Crump 가 .NET Core의 새로운 기능을 Visual Studio 2017과 업데이트된 CLI Tool과 함께 설명했습니다
* [Turning off Telemetry Data in .NET Core](http://michaelcrump.net/part12-aspnetcore/) : Michael Crump 가 .NET Core 의 데이터 수집 기능을 off 하는 방법을 공유했습니다

### ASP.NET 소식
* [Supporting both LTS and Current releases for ASP.NET Core](https://andrewlock.net/supporting-both-lts-and-current-releases-for-asp-net-core/) : Andrew Lock이 ASP.NET Core의 최신 버전과 LTS(Long Term Support)버전을 동시에 지원하는 방법에 대해서 설명했습니다
* [What is the Microsoft.AspNetCore metapackage?](https://andrewlock.net/what-is-the-microsoft-aspnetcore-metapackage/) : Andrew Lock이 Microsoft.AspNetCore의 metapackage를 설명했습니다
* [Testing an ASP.NET Core MVC Protobuf API using HTTPClient and xUnit](https://damienbod.com/2017/03/09/testing-an-asp-net-core-mvc-protobuf-api-using-httpclient-and-xunit/) : Damien Bowden가 HTTPClient와 xUnit을 이용한 Protobuf API 사용코드의 테스트방법을 설명 했습니다
* [ASP.NET Core MVC Anatomy (Part 1) – AddMvcCore](https://www.stevejgordon.co.uk/asp-net-core-mvc-anatomy-addmvccore) : Steve Gordon이 "ASP.NET Core MVC 분석 - 파트1"을 공유했습니다
* [Fritz’s 10 Minute Tips – ASP.NET Core Configuration](http://www.jeffreyfritz.com/2017/03/fritzs-10-minute-tips-asp-net-core-configuration/) : Jeffrey T. Fritz가 "ASP.NET Core 개발 10분 팁-동영상"을 공유했습니다
* [Environment Variables in ASP.NET Core](https://codeopinion.com/environment-variables-asp-net-core/) : Derek Comartin 이 ASP.NET Core 환경 변수를 설명했습니다
* [A way too early discussion of “Jasper”](https://jeremydmiller.com/2017/03/08/a-way-too-early-discussion-of-jasper/) :  Jeremy D. Miller가 .NET의 분산 서버 개발을 위한 차세대 애플리케이션 개발 프레임 워크인 Jasper에 대한 글을 공유했습니다
* [Creating a simple blog engine](http://isolineltd.com/blog/2017/03/08/Creating-a-simple-Blog-Engine) : Ivan Gavryliuk가 간단한 블로그 엔진 구현 과정을 공유했습니다 
* [Book: Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) : Nick Chamberlain의 새로운 서적의 출간 정보가 공유 되었습니다.
* [Precompiling MVC Views in ASP.NET Core with .csproj](https://scottsauber.com/2017/03/10/pre-compiling-razor-views-in-asp-net-core-with-csprojs/) : Scott Sauber가 ASP.NET Core, .csproj 타입 프로젝트에서  MVC View 를 Precompile 하는 방법을 설명했습니다 
* [Improve the security of your website using SSL and HSTS with ASP.NET Core](https://www.softfluent.com/blog/dev/2017/03/06/Improve-the-security-of-your-website-using-SSL-and-HSTS-with-ASP-NET-Core) : Gérald Barré가 SSL과 HSTS를 이용한 ASP.NET Core 웹사이트의 보안을 강화 하는 방법을 공유했습니다
* [Simple localization and language based URLs](http://gunnarpeipman.com/2017/03/aspnet-core-simple-localization/) : Gunnar Peipman가 URL 정보를 기반으로 지역/언어 설정을 쉽게하는 방법을 설명했습니다

### C# 소식
* [New Features in C# 7.0](https://blogs.msdn.microsoft.com/dotnet/2017/03/09/new-features-in-c-7-0/) : Mads Torgersen가 C# 7.0의 새로운 기능을 소개합니다
* [Exploring C# Productivity in Visual Studio 2017 (video)](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-2017-Launch/140) : Mads Torgersen와 Kasey Uhlenhuth가 Visual Studio 2017의 C# 코드 생산성 기능을 소개했습니다

### F# 소식
* [Using Elixir and F# Together](http://www.channel64.net/2017/03/pipe-forward-using-elixir-and-f.html) : Bryan Hunter가 Elixir와 F#의 사용 방법을 공유했습니다
* [Some Details about Visual F# Tools in VS 2017](https://vasily-kirichenko.github.io/fsharpblog/) : Vasily Kirichenko가 잘 알려지지않은 VS 2017의 F# 툴 기능을 공유했습니다
* [Creating an Azure Function in F# from the ground up (Part 2)](http://brandewinder.com/2017/03/06/fsharp-azure-function-from-the-ground-up-part-2/) : Mathias Brandewinder가 "F#으로 Azure Function 처음부터 만들어보기 - 파트 2"를 공유했습니다
* [Magic of F# Type Providers](https://medium.com/@maximcus/magic-of-f-type-providers-225b1169c7a0#.u6tytsm6a) : F# Type Provider를 설명 했습니다(Max Fedotov).
* [Creating a fully functional F# microservice part 2: Azure, FSharp.Configuration](https://mnie.github.io/2017-03-11-sentimentAppPart2/) and [part 3: Quartz.Net, Net.Mail](https://mnie.github.io/2017-03-11-sentimentAppPart3/) : Michał Niegrzybowski가 F# 마이크로서비스 구축하기 - "파트 2 : Azure, FSharp.Configuration"와 "파트 3: Quartz.Net, Net.Mail"를 공유했습니다
* [Contractive Functions on Streams in F#](https://medium.com/@dogwith1eye/contractive-functions-on-streams-in-f-286fca88d83f#.5bn1upjoz) : Matthew Doig가 F#의 Contractive Function에 대해 소개합니다

### Xamarin 소식
* [Visual Studio for Mac – Preview 4](https://releases.xamarin.com/preview-4-visual-studio-for-mac/) : Visual Studio for Mac – Preview 4 버전이 공개 되었습니다 
* [Xamarin Alpha Release: 15.1 Alpha Preview 2](https://releases.xamarin.com/alpha-release-15-1-alpha-preview-2/) : Bri Brothers이 Xamarin의 15.1 Alpha Preview 2 버전 공개 사실을 공유했습니다
* [Xamarin Dev Days are Coming to your City!](https://blog.xamarin.com/xamarin-dev-days-are-coming-to-your-city/) : Jayme Singleton가 Xamarin 개발자 행사 일정을 공유했습니다
* [Better Apps Faster with Visual Studio 2017 and Xamarin](https://blog.xamarin.com/better-apps-visual-studio-2017/) : Miguel de Icaza가 Xamarin과 Visual Studio 2017을 활용하여 효율적으로 애플리케이션을 개발하는 방법을 소개했습니다
* [Live Webinar: Introduction to Xamarin for Visual Studio 2017](https://blog.xamarin.com/live-webinar-introduction-to-xamarin-for-visual-studio-2017/) : James Montemagno가 Visual Studio 2017을 이용한 Xamarin 개발 방법을 소개했습니다
* [Mobile Center: Xamarin support, detailed app analytics, and more](https://blogs.msdn.microsoft.com/visualstudio/2017/03/07/mobile-center-xamarin-support-detailed-app-analytics-and-more/) : Keith Ballinger가 모바일 센터의 Xamarin 지원, 애플리케이션 분석 등의 기능을 소개했습니다
* [Avoid these six mobile development pitfalls](https://blogs.msdn.microsoft.com/visualstudio/2017/03/03/avoid-these-six-mobile-development-pitfalls/) : Cormac Foster가 모바일 개발시 피해야 할 6가지 사항을 공유했습니다
* [Setting up Visual Studio 2017 for Xamarin Development](http://motzcod.es/post/158155898027/setting-up-vs-2017-for-xamarin-dev) : James Montemagno가 Xamarin 개발을 위한 Visual Studio 2017 설정방법을 공유했습니다
* [NuGet Support in Xamarin Studio 6.2](http://lastexitcode.com/blog/2017/03/05/NuGetSupportInXamarinStudio6-2/) : Matt Ward가 Xamarin Studio 6.2의 NuGet지원 소식을 공유했습니다
* [Xamarin Forms User Control](https://xamarinhelp.com/xamarin-forms-user-control/) : Adam Pedley가 Xamarin Forms의 사용자 컨트롤 개발에 대해서 설명했습니다
* [Xamarin.Controls – Creating Your Own iOS Markdown UILabel](https://alexdunn.org/2017/03/03/xamarin-controls-creating-your-own-ios-markdown-uilabel/) & [Xamarin.Forms Borderless Entry](https://alexdunn.org/2017/03/08/xamarin-forms-borderless-entry/) : Alex Dunn이 iOS 의 Markdown UILabel 구현 및 Borderless Entry 구현 방법을 공유했습니다
* [Xamarin Plugins / .NET Standard with Martijn van Dijk and Michael Ridland](http://www.michaelridland.com/xamarin/xamarin-plugins-net-standard-with-martijn-van-dijk-and-michael-ridland/) : Michael Ridland이 동영상 "Xamarin Plugins / .NET Standard 알아보기"를 소개했습니다
* [Xamarin Forms, MVVMCross, and SkiaSharp: The Holy Trinity of Cross-Platform App Development](https://www.toptal.com/mobile/xamarin-mvvmcross-skiasharp-cross-platform) : Sylvain Gravel가 Xamarin Forms, MVVMCross, SkiaSharp을 이용한 크로스 플랫폼 애플리케이션 개발 방법을 공유했습니다
* [A Xamarin port of the usb-serial-for-android library](https://rajapet.com/2017/03/02/a-xamarin-port-of-the-usb-serial-for-android-library/) : Chris Miller가 Xamarin 안드로이드용 usb-serial 라이브러리를 소개했습니다
* [Pull to Refresh Example Using Xamarin.Forms](http://15mgm15.ghost.io/2017/03/03/pull-to-refresh-example-using-xamarin-forms/) : Mario Jesús Galván Miranda가 애플리케이션에서 화면을 아래쪽으로 끌어당겨 페이지를 새로고침하는 방법인 Pull to Refresh 를 구현하는 Xamarin.Forms 예제를 소개했습니다
* [Sending Files to a Xamarin.Forms App – Part 2: Android](https://codemilltech.com/sending-files-to-a-xamarin-forms-app-part-2-android/) : Matthew Soucoup가 Xamarin.Forms 애플리케이션에서 파일 연결하기-"파트2  안드로이드"를 공유했습니다
* [Swipe to Delete and more on Xamarin.iOS](https://canbilgin.wordpress.com/2017/03/04/swipe-to-delete-and-more-on-xamarin-ios/) : Can Bilgin가 Xamarin.iOS에서 밀어서 삭제하기 기능을 구현하는 방법을 설명했습니다
* [Xamarin Forms with Microsoft Azure](https://mobileprogrammerblog.wordpress.com/2017/03/04/xamarin-forms-with-microsoft-azure/) : Daniel Krzyczkowski가 Xamarin Forms로 만든 애플리케이션에서 Microsoft Azure의 몇가지 기능을 활용하는 방법을 예제와 함께 소개합니다
* [Validating User Input in Xamarin.Forms](http://www.davidbritch.com/2017/03/validating-user-input-in-xamarinforms.html) & [Validating User Input in Xamarin.Forms II](http://www.davidbritch.com/2017/03/validating-user-input-in-xamarinforms-ii.html) : David Britch가 "사용자 입력값 검증 - 파트1" 및 "사용자 입력값 검증 - 파트2"를 공유했습니다
* [Forms Previewer and Custom Controls](https://peterfoot.net/2017/03/08/forms-previewer-and-custom-controls/) : Peter Foot가 Xamarin.Forms Previewer와 사용자 정의 컨트롤 구현시 발생할 수 있는 오류와 대처방법을 공유했습니다

### UWP 소식
* [Visual Studio 2017 – Now Ready for Your Windows Application Development Needs](https://blogs.windows.com/buildingapps/2017/03/07/visual-studio-2017-now-ready-windows-application-development-needs/) : Karan Nandwani가 Visual Studio 2017에서 UWP 개발방법을 설명했습니다
* [Desktop Bridge: Smooth User Transition and Data Migration](https://blogs.windows.com/buildingapps/2017/03/10/desktop-bridge-smooth-user-transition-data-migration/) : Arian Ghotbi가 기존 Desktop 애플리케이션을 UWP로 쉽게 전환 할 수있도록 도와주는 Desktop Bridge를 소개했습니다
* [Building the Terminator Vision HUD in HoloLens](https://blogs.windows.com/buildingapps/2017/03/06/building-terminator-vision-hud-hololens/) : Windows Apps Team에서 홀로 렌즈에서 터미네이터 화면과 같은 UI의 구현 과정을 소개했습니다
* [Playable Ads – Acquire Users Who Love to Engage with Your App](https://blogs.windows.com/buildingapps/2017/03/09/playable-ads-acquire-users-love-engage-app/) : Vikram Bodavula가 Playable Ads를 소개했습니다
* [Dragging and Dropping Images and Files into the Web Browser Control](https://weblog.west-wind.com/posts/2017/Mar/10/Dragging-and-Dropping-Images-and-Files-into-the-Web-Browser-Control) : Rick Strahl가 이미지를 Web Browser Control로 Drag&Drop 하여 개발하는 방법을 설명했습니다
* [Debugging the Web Browser Control with FireBug](https://weblog.west-wind.com/posts/2017/Mar/08/Debugging-the-Web-Browser-Control-with-FireBug) : Rick Strahl가 FireBug 를 이용한 Web Browser Contro디버깅 방법을 설명했습니다

### Data 소식
* [Oracle Data Provider for .NET Support for Microsoft .NET Core](http://www.oracle.com/technetwork/topics/dotnet/tech-info/odpnet-dotnet-core-sod-3628981.pdf) : Oracle Data Provider에서 .NET Core를 지원하기 시작했다는 소식입니다
* [ODP.NET on Microsoft .NET Core](http://www.maherjendoubi.io/odp-net-on-microsoft-net-core/) : Maher Jendoubi이 ODP.NET의 .NET Core 지원 소식을 공유했습니다

### Game 소식
* [Getting Started with MonoGame on Visual Studio 2017](https://youtu.be/zphaylhOrm0) : Simon Jackson이 Visual Studio 2017과 MonoGame를 이용한 게임 개발 방법을 소개했습니다
* [GDC 2017 Talks](http://www.gdcvault.com/browse/gdc-17) : GDC 2017 컨퍼런스 세션 영상이 공유되었습니다
* [Project Tanks 1: Simple Fake-3D Wireframes](http://www.jfurness.uk/project-tanks-1-easy-fake-3d-wireframes/) : James Furness가 "3D 느낌나는 와이어 프레임 구성하기"에 대해 소개합니다
* [Curated #UnityTips No. 36](http://devdog.io/blog/2017/03/11-best-unity-tips-for-game-developers-36) : Devdog이 유니티 개발 팁을 공유했습니다
* [Fixeds, Floats and a Block Damage Effect](http://kylehalladay.com/blog/tutorial/2017/03/13/GlitchFX-In-Unity.html) : Kyle Halladay가 여러가지 효과를 구현하는 방법을 설명합니다
* [Real Time Strategy in Unity – Making Units Construct Buildings (2)](https://youtu.be/veClc0W7dic) : 유튜브 채널인 Unit02Games에서 빌딩을 짓기 위한 유닛을 만드는 방법을 소개합니다 
* [11.0 Unity Tower defense tutorial – Selling towers](https://youtu.be/x2iVy6piOUE?list=PLX-uZVK_0K_4uNwvKian1bscP9mVvOp1M) : inScope Studios에서 타워 디펜스 게임 구현 방법에 대해 설명했습니다

// 전무님 소개
