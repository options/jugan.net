### On .NET 소식

지난 주 On .NET 소식에서는 두개의 비디오를 공유해 드렸습니다. [첫번째 비디오](링크)에서는  [Scott Hunter](링크)가 Visual Studio 2017과 .NET Core에 대해서 얘기해주었습니다

//사진

[두번째 비디오](링크)에서는 [Stackify](링크)의 [Matt Watson](링크)이 가볍고 빠른 웹 개발 도구로서 실시간 로그, 에러, 쿼리 등의 도움기능과 성능 분석 기능을 가진 [Prefix](링크)를 소개해 주었습니다.


//사진

이번주 On .NET 쇼는 예정 되어있지 않습니다

### Happy Birthday .NET!
지난주에는 마이크로스프트 멤버 OB 모임이 있었습니다. 이전 .NET 팀들과 함께 .NET 15주년을 축하하며 즐거운 시간을 보냈습니다. 참석 하신분들중 개발자 커뮤니티 지원 부서의 원년 맴버이며 MVP 프로그램 발전에도 많은 도움을 주었던 Dee Dee Walsh가 Happy Birthday .NET 비디오에 함께해 주셨습니다. 

//동영상

### 금주의 패키지: C#용 MessagePack 
지금까지 직열화(serialization) 관련된 라이브러리를 소개시켜드릴 기회가 몇번있었는데 이번에 또 다른 하나를 더 소개해 드리려 합니다. 라이브러리 [MessagePack](링크)은 효과적으로 바이너리 직열화 포멧을 지원하며 약 50여 가지의 다양한 개발 플렛폼을 지원함니다. No SQL 메모리 DB인 Redis 에서도 사용가능 하며  .NET 플랫폼에서 사용가능하도록 구현된 MessagePack 라이브러리는 적어도 5가지 이상의 버전이 있습니다. 그중 오늘 소개해 드릴 MessagePack은 [ZeroFormatter](링크)를 개발한 개발자 Yoshifumi Kawai가 구현한 [MessagePack for C#](링크)으로 neuecc라고도 알려져 있습니다. 이 라이브러리는 LZ4 압축 알고리즘을 지원하여 직열화 작업과 역직열화 작업시 아주 빠르게 동작하며 직열화 결과물의 크기도 아주 작습니다.

직열화 대상 데이터 객체를 아래와 같이 정의할 수 있습니다.

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

그런 다음 직열화 작업과 역직열화 작업을 수행하면 됩니다. 

var mc = new MyClass
{
Age = 23,
FirstName = "Bertrand",
LastName = "Le Roy",
};
var bytes = MessagePackSerializer.Serialize(mc);
var mc2 = MessagePackSerializer.Deserialize<MyClass>(bytes);

### .NET 소식
* What’s New in the .NET Platform (video) :  .NET Platform 소개 동영상을 공유했습니다(Scott Hunter)
* Announcing NuGet 4.0 RTM : NuGet 4.0 RTM을 소개했습니다(Anand Gaurav).
* Optimize your productivity with .NET in Visual Studio 2017 : Visual Studio 2017의 개발 생산성 기능을 설명했습니다 (Kasey Uhlenhuth).
* Live Unit Testing in Visual Studio 2017 Enterprise : Visual Studio 2017 Enterprise의 새로운 기능중 "Live Unit Testing" 기능을 소개했습니다 (Joe Morris, Manish Jayaswal).
* Run To Click Debugging in Visual Studio 2017 : Visual Studio 2017 의 새로운 디버깅 기능 "Run To Click Debugging" 을 소개했습니다(Kaycee Anderson).
* Cake v0.18.0 released : Cake v0.18.0 버전이 릴리즈 되었습니다.
* Getting Started with .NET Core on Mac and Linux by Nate Cook for Pluralsight : 교육 사이트 Pluralsight에  ".NET Core on Mac and Linux " 과정이 새롭게 등록되었습니다.
* P/invoke with unions in C# : C#으로 P/invoke 호출시 union의 사용 방법을 설명했습니다(Yi Zhang).
* exploring .NET Core with Visual Studio 2017 and the updated CLI Tools :  .NET Core의 새로운 기능을 Visual Studio 2017와 업데이트된 CLI Tool과 함께 설명했습니다( Michael Crump).
* Turning off Telemetry Data in .NET Core : .NET Core 의 데이터 수집 기능을 off 하는 방법을 공유했습니다 (Michael Crump).

### ASP.NET 소식
* Supporting both LTS and Current releases for ASP.NET Core : ASP.NET Core의 최신 버전과 LTS(Long Term Support)버전 동시에 지원하는 방법에 대해서 설명했습니다(Andrew Lock).
* What is the Microsoft.AspNetCore metapackage? : Microsoft.AspNetCore의 metapackage를 설명했습니다(Andrew Lock).
* Testing an ASP.NET Core MVC Protobuf API using HTTPClient and xUnit : HTTPClient와 xUnit 이용한 Protobuf API 사용코드의 테스트방법을 설명 했습니다(Damien Bowden).
* ASP.NET Core MVC Anatomy (Part 1) – AddMvcCore : "ASP.NET Core MVC 분석 - 파트1"을 공유했습니다(Steve Gordon).
* Fritz’s 10 Minute Tips – ASP.NET Core Configuration :"ASP.NET Core 개발 10분 팁-동영상"을 공유했습니다(Jeffrey T. Fritz).
* ASP.NET Core: Environment based configuring methods : 환경 기반 설정 메서드의 활용법을 설명 했습니다 (Gunnar Peipman).
* Environment Variables in ASP.NET Core : ASP.NET Core 환경 변수를 설명했습니다(Derek Comartin).
* A way too early discussion of “Jasper” :  (Jeremy D. Miller).
* Creating a simple blog engine : 간단한 블로그 엔진 구현 과정을 공유했습니다 (Ivan Gavryliuk).
* Book: Applying Domain Driven Design with CQRS and Event Sourcing by Nick Chamberlain, with all examples written with ASP.NET MVC: 새로운 서적의 출간 정보가 공유 되었습니다.
* Precompiling MVC Views in ASP.NET Core with .csproj : ASP.NET Core, .csproj 타입 프로젝트에서  MVC View 를Precompile 하는 방법을 설명했습니다 (Scott Sauber).
* Improve the security of your website using SSL and HSTS with ASP.NET Core : SSL과 HSTS를 이용한 ASP.NET Core 웹사이트의 보안을 강화 하는 방법을 공유했습니다 (Gérald Barré).
* Simple localization and language based URLs : URL 정보를 기반으로 지역/언어 설정을 쉽게하는 방법을 설명했습니다(Gunnar Peipman).

### C# 소식
* New Features in C# 7.0 : C# 7.0의 새로운 기능을 설명했습니다 (Mads Torgersen).
* Exploring C# Productivity in Visual Studio 2017 (video) : Visual Studio 2017의 C# 코드 생산성 기능을 소개했습니다(Mads Torgersen, Kasey Uhlenhuth).

### F# 소식
* Using Elixir and F# Together : Elixir와 F#의 사용 방법을 공유했습니다(Bryan Hunter).
* Some Details about Visual F# Tools in VS 2017, : 잘 알려지지않은 VS 2017의 F# 툴 기능을 공유했습니다 (Vasily Kirichenko).
* Creating an Azure Function in F# from the ground up (Part 2): "F#으로 Azure Function 처음부터 만들어보기 - 파트 2"를 공유했습니다  (Mathias Brandewinder).
* Magic of F# Type Providers : F# Type Provider를 설명 했습니다(Max Fedotov).
* Creating a fully functional F# microservice part 2: Azure, FSharp.Configuration, and part 3: Quartz.Net, Net.Mail : F# 마이크로서비스 구축하기 - "파트 2 : Azure, FSharp.Configuration"(링크), "파트 3: Quartz.Net, Net.Mail"(링크)를 공유했습니다 (ichał Niegrzybowski).
* Contractive Functions on Streams in F#, : Matthew Doig.

### Xamarin 소식
* Visual Studio for Mac – Preview 4 : Visual Studio for Mac – Preview 4 버전이 공개 되었습니다 (Bri Brothers).
* Xamarin Alpha Release: 15.1 Alpha Preview 2 : Xamarin Alpha Release: 15.1 Alpha Preview 2이 공개되었습니다(Bri Brothers).
* Xamarin Dev Days are Coming to your City! : Xamarin 개발자 행사 일정을 공유했습니다 (Jayme Singleton).
* Better Apps Faster with Visual Studio 2017 and Xamarin :Xamarin과 Visual Studio 2017을 활용한 효과적인 어플 개발 방법을 소개했습니다(Miguel de Icaza).
* Live Webinar: Introduction to Xamarin for Visual Studio 2017 : Visual Studio 2017을 이용한 Xamarin 개발 방법을 소개했습니다(James Montemagno).
* Mobile Center: Xamarin support, detailed app analytics, and more : 모바일 센터의 Xamarin 지원, 어플 분석등의 기능을 소개했습니다(Keith Ballinger).
* Avoid these six mobile development pitfalls : 모바일 개발시 피해야할 6가지 사항을 공유했습니다(Cormac Foster).
* Setting up Visual Studio 2017 for Xamarin Development : Xamarin 개발을 위한 Visual Studio 2017 설정방법을 공유했습니다(James Montemagno).
* NuGet Support in Xamarin Studio 6.2 : Xamarin Studio 6.2의 NuGet지원 소식을 공유했습니다(Matt Ward).
* Xamarin Forms User Control : Xamarin Forms의 사용자 컨트롤 개발에 대해서 설명했습니다 (Adam Pedley).
* Xamarin.Controls – Creating Your Own iOS Markdown UILabel, & Xamarin.Forms Borderless Entry :"iOS 의 Markdown UILabel 구현"(링크),  "Borderless Entry 구현"(링크) 방법을 공유했습니다 (Alex Dunn).
* Xamarin Plugins / .NET Standard with Martijn van Dijk and Michael Ridland : 동영상 "Xamarin Plugins / .NET Standard 알아보기"를 소개했습니다 (Michael Ridland).
* Xamarin Forms, MVVMCross, and SkiaSharp: The Holy Trinity of Cross-Platform App Development : Xamarin Forms, MVVMCross, SkiaSharp을 이용한 다중 플랫폼 어플  개발 방법을 공유했습니다(Sylvain Gravel).
* A Xamarin port of the usb-serial-for-android library : Xamarin 안드로이드용 usb-serial 라이브러리를 소개했습니다 (Chris Miller).
* Pull to Refresh Example Using Xamarin.Forms : Xamarin.Forms 예제의 업데이트 방법을 공유했습니다(Mario Jesús Galván Miranda).
* Sending Files to a Xamarin.Forms App – Part 2: Android : Xamarin.Forms 어플에서 파일 연결하기-"파트2  안드로이드"를 공유했습니다(Matthew Soucoup).
* Swipe to Delete and more on Xamarin.iOS : Xamarin.iOS에서 밀어서 삭제하기 기능 구현방법을 설명 했습니다 (Can Bilgin).
* Xamarin Forms with Microsoft Azure : Xamarin Forms과 Microsoft Azure의 활용방법을 공유했습니다(Daniel Krzyczkowski).
* Validating User Input in Xamarin.Forms, & Validating User Input in Xamarin.Forms II : "사용자 입력값 검증 - 파트1"(링크), "사용자 입력값 검증 - 파트2"(링크)를 공유했습니다(David Britch).
* Forms Previewer and Custom Controls : Xamarin.Forms Previewer와 사용자 정의 컨트롤 구현시 발생할수있는 오류와 대처방법을 공유했습니다(Peter Foot).

### UWP 소식
* Visual Studio 2017 – Now Ready for Your Windows Application Development Needs : Visual Studio 2017  UWP 개발방법을 설명했습니다(Karan Nandwani).
* Desktop Bridge: Smooth User Transition and Data Migration : 기존 Desktop 어플리케이션을 UWP로 쉽게 전환 할 수있도록 도와주는 Desktop Bridge를 소개했습니다(Arian Ghotbi).
* Building the Terminator Vision HUD in HoloLens : 홀로 렌즈에서 터미네이터 화면과 같은 UI의 구현 과정을 공유했습니다(Windows Apps Team).
* Playable Ads – Acquire Users Who Love to Engage with Your App : Playable Ads를 소개했습니다(Vikram Bodavula).
* Dragging and Dropping Images and Files into the Web Browser Control : 이미지를 Web Browser Control로 드래드&드랍 하는 개발 방법을 설명했습니다(Rick Strahl).
* Debugging the Web Browser Control with FireBug :FireBug 를 이용한 Web Browser Contro디버깅 방법을 설명했습니다 (Rick Strahl).

### Data 소식
* Oracle Data Provider for .NET Support for Microsoft .NET Core : Oracle Data Provider의 .NET Core 지원정보를 공유했습니다(Oracle).
* ODP.NET on Microsoft .NET Core :  ODP.NET의 .NET Core 지원 소식을 공유했습니다 (Maher Jendoubi).

### Game 소식
* Getting Started with MonoGame on Visual Studio 2017 : Visual Studio 2017과 MonoGame를 이용한 게임 개발 방법을 소개했습니다( Simon Jackson).
* GDC 2017 Talks: GDC 2017 컨퍼런스 세션 영상이 공유되었습니다.
* Project Tanks 1: Simple Fake-3D Wireframes : "3D 느낌나는 와이어 프레임 구성하기"(James Furness).
* Curated #UnityTips No. 36 by Devdog March 2017.
* Fixeds, Floats and a Block Damage Effect by Kyle Halladay.
* Real Time Strategy in Unity – Making Units Construct Buildings (2) by Unit02Games.
* 11.0 Unity Tower defense tutorial – Selling towers : inScope Studios에서 타워 디펜스 게임 구현 방법에 대해 설명했습니다. 


// 전무님 소개
