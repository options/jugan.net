주간닷넷 2016년 10월 18일

### On .NET 소식
[지난 주 On .NET]( https://blogs.msdn.microsoft.com/dotnet/2016/10/11/the-week-in-net-on-net-on-net-standard-2-0-nancy-satellite-reign/)에는 On .NET Show가 진행되지 못했습니다. 

### 금주의 패키지 - Bond
[Bond]( https://microsoft.github.io/bond/manual/bond_cs.html)는 구글의 [Protocol Buffer]( https://microsoft.github.io/bond/manual/bond_cs.html)와 매우 유사한 데이터 직렬화 라이브러리로서 메시지(혹은 구조체)를 연속된 비트로 만들고, 반대로 비트에서 원래의 메시지로 만들 수 있습니다, macOS, Windows에서 동작하고 C++, C#, Python 등의 언어를 지원하지만, 개발자가 Bond를 사용하기 위해서는 아래 코드 처럼 IDA와 비슷한 형식으로 먼저 스키마를 정의해야 합니다.

// 코드

그다음, 아래처럼 C# 코드를 작성합니다.

// 코드
그다음, 아래 작성된 C# 코드를 사용하면 C# Serialize로 개체를 binary형태로 저장을 하였다가 Deserialize로 다시 개체를 얻어올 수 있습니다.
// 코드

### 금주의 게임 - The Gallery – Episode 1: Call of the Starseed
게임 [The Gallery – Episode 1: Call of the Starseed]( https://madewith.unity.com/games/the-gallery-episode-1-call-of-the-starseed)는 4개의 에피소드로 나누어진 판타지 어드벤처 VR 게임입니다. 게임 플레이어는 게임 속 주인공이 되어 실종된 여동생을 찾는 과정에서 신비하고 기이한 게임 캐릭터들과 만나며 모험을 펼치게 됩니다. The Gallery – Episode 1은 ‘full-room scale VR’ 기능으로 실제 방에서 안고, 서고, 웅크리고, 기는 동작 등을 인식하여 실감나게 게임을 즐기실 수 있습니다.

//그림

[The Gallery – Episode 1: Call of the Starseed]( https://madewith.unity.com/games/the-gallery-episode-1-call-of-the-starseed)은 [Cloudhead Games]( http://cloudheadgames.com/cloudhead/)에서 [Unity]( https://unity3d.com/)와 [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 제작 했으며, [Steam]( http://store.steampowered.com/app/270130/)을 통해 HTC Vive에서 플레이하실 수 있고 12월에는 Oculus Home을 통해 Oculus Touch에서도 즐기실수있습니다.

### .NET 소식
* [.NET Framework Monthly Rollups Explained]( https://blogs.msdn.microsoft.com/dotnet/2016/10/11/net-framework-monthly-rollups-explained/) and [.NET Framework Monthly Rollup: October 2016]( https://blogs.msdn.microsoft.com/dotnet/2016/10/11/net-framework-monthly-rollup-october-2016/) : Stacey Haffner가 10월 호를 시작으로 매달 NET Framework 업데이트 정보를 공유할 예정입니다.
* [Learning .NET Core by example]( https://jonhilton.net/2016/10/12/learning-dotnet-core-by-example/) : Jon Hilton이 .NET Core를 쉽게 배울 수 있는 예제와 튜토리얼을 공유했습니다
* [Parallel Test Execution]( https://blogs.msdn.microsoft.com/visualstudioalm/2016/10/10/parallel-test-execution/) : Pratap Lakshman이 Parallel Test Execution에 관해 설명합니다.
* [Porting Apache Avro into .NET Core]( https://weltam.wordpress.com/2016/09/07/porting-apache-avro-into-net-core/) : Welly Tambunan이 Avro를 Apache버전에서 .NET Core버전으로 전환하는 방법에 관해 설명합니다.
* [Timing the time it takes to parse time part 1 and part 2]( https://ayende.com/blog/175713/timing-the-time-it-takes-to-parse-time-part-i) : Ayende Rahien이 DateTime의 데이터 형식을 효과적으로 파싱하는 방법에 관해 소개합니다.
* [Microsoft IIS Administration Preview]( https://blogs.iis.net/adminapi/microsoft-iis-administration-api-preview) : Microsoft IIS Administration API의 프리뷰 버전이 공개되었습니다.
* [Deal with time dependencies in Tests]( https://carlos.mendible.com/2016/10/11/deal-with-time-dependencies-in-tests/) : Carlos Mendible이 테스트 시간에 따라 결과가 바뀔 수 있는 프로그램을 어떻게 정확히 테스트할 수 있는지 설명합니다.
* [Metric.NET: dealing with measurement units]( https://github.com/milutinovici/metric) : Ivan Milutinović이 단위 변환 오픈소스 라이브러리인 Metric.NET에 관해 소개합니다.
* [Stuntman now works with .NET Core]( https://github.com/ritterim/stuntman) : 멤버들이 자유롭게 시나리오 공유하여 개발할 수 있도록 돕는 Stuntman 라이브러리가 .NET Core에서도 지원한다는 소식이 공유되었습니다.
* [MediatR Pipeline Examples]( https://lostechies.com/jimmybogard/2016/10/13/mediatr-pipeline-examples/) : Jimmy Bogard가 Mediator pattern 라이브러리인 MediatR을 예제를 통해 소개합니다.
* [Using Core class library from .NET 4.6 project]( http://hudosvibe.net/post/using-core-class-library-from-.net-4.6-project) : Hrvoje Hudoletnjak가 일반적인 .NET 4.6 프로젝트에서 Core용 클래스 라이브러리를 사용하는 방법에 관해 소개합니다.
* [Calling UWP APIs from a Desktop Application]( https://mtaulty.com/2016/10/11/calling-uwp-apis-from-a-desktop-application/) : Mike Taulty가 Desktop Application에서 UWP API을 호출하는 방법에 관해 소개합니다.
### ASP.NET 소식
* [Exploring ASP.NET Core with Docker in both Linux and Windows Containers]( http://www.hanselman.com/blog/ExploringASPNETCoreWithDockerInBothLinuxAndWindowsContainers.aspx) : Scott Hanselman이 Linux와 Window용 Containers와 ASP.NET Core의 도커 시스템에 관해 설명합니다.
* [Custom authorization policies and requirements in ASP.NET Core]( http://andrewlock.net/custom-authorisation-policies-and-requirements-in-asp-net-core/) : Andrew Lock이 ASP.NET Core 인증 정책 필요 사항에 관해 설명합니다.
* [Debugging into ASP.NET Core Source]( https://www.stevejgordon.co.uk/debugging-into-asp-net-core-source) : Steve Gordon이 ASP.NET Core 소스 디버깅 방법을 공유했습니다.
* Localization & Routing in ASP.NET Core 1.0 : Hisham Bin Ateya가 ASP.NET Core 1.0에 Localization과 Routing에 관해 설명합니다.
* ASP.NET Core and the Enterprise: Part 1 Frameworks : K. Scott Allen이 .NET Framework에 관해 소개합니다.

### F# 소식
* Using F# on Azure : Sylvan Clebsch가 Azure 환경에서 F#을 사용하는 방법에 관해 소개합니다.
* Getting Started with F# in Visual Studio Code with Ionide : Phillip Carter가 Visual Studio Code에서 Ionide을 이용해 F#을 사용하는 방법에 관해 소개합니다.
* Using F# with .NET Core : Ody Mbegbu가 .NET Core 환경의 F# 사용 방법을 소개합니다.
* ASP.NET Identity in an F# Web Application, Part One : Ernest Pazera가 F#의 웹 애플리케이션에ASP.NET Identity에 관해 설명합니다.
* Prefer Records of Functions to Interfaces : Matthew Doig가 F#에서 Interface 활용에 관해 설명합니다.

### Xamarin 소식
* Xamarin Preview: Xamarin Profiler 0.38.0 : Adrian Murphy가 Xamarin Profiler 프리뷰 버전 0.38.0을 소개 합니다.
* Xamarin Dev Days Continue to Roll Out! : Jayme Singleton이 Xamarin Dev Days 개발 행사 일정을 공유했습니다.
* Mobile Leaders Podcast | Enterprise Mobility Trends with Maribel Lopez : Anusha Sethuraman이 모바일 전문 연구기관 Lopez Research의 창립자인 Maribel Lopez와 기업 모빌리티 트랜드에 대해서 팟캐스트를 진행했습니다.
* Live Webinar | Xamarin University Presents: Introduction to Xamarin with Visual Studio : Courtney Witmer가 웹 세미나에서 Visual Studio로 Xamarin을 개발해보는 데모를 진행했습니다.
* Understanding Android’s Doze Functionality and The Xamarin Show 6: User Interface Automation with Charles Wang : James Montemagno가 Android 절전 기능에 대해 소개하고 Xamarin Show 6에서는 사용자 인터페이스에 관해 설명합니다.
* Bringing Platform-Specific Functionality to Xamarin.Forms Apps : Pierce Boggan이 모바일 플랫폼 기존 기능을 Xamarin.Forms Apps에서 사용하는 방법에 관해 설명합니다.
* Designing Card-Based User Interfaces : Nick Babich가 카드-뷰 형태의 사용자 인터페이스 디자인에 관해 소개합니다.
* Creating A Splash Screen In Xamarin Forms and Misuses Of MessagingCenter : Adam Pedley가 Xamarin Forms에서 Splash Screen 의 구현방법과 MessagingCenter의 잘못된 사용 예를 설명 합니다.
* ReactiveUI Goodies – Search and ReactiveUI Goodies – ReactiveList : Jan Hannemann이 오픈소스 UI framework인 ReactiveUI를 이용한 Search 기능 구현 방법과 ObservableCollection의 일종인 ReactiveList에 관해 설명합니다.
* Semantic Versioning of Xamarin Applications : Geoffrey Huntley가 Xamarin 애플리케이션의 효과적인 버전 관리 방법을 소개합니다.
* Templates and Extensions for Xamarin & Mono : Terrence Dorsey가 Xamarin, Mono 환경에서 사용할 수 있는 여러가지 컴포넌트와 확장 기능에 대해 설명합니다.

### Azure 소식
* Simpler Azure Management Libraries for .NET : Asir Selvasingh가 Azure 관리 라이브러리 "Simpler Azure Management Libraries for .NET"의 개발자 프리뷰 버전을 소개합니다.
* Hosting .NET Core Services on Service Fabric : Vaijanath Angadihiremath가 Service Fabric에서 .NET Core Services를 호스트하는 방법에 관해 설명합니다.
* Running Worker Roles with Docker in .NET Core : Pepijn Schoen이 .NET Core의 도커 환경에서 Worker Roles을 실행/관리하는 방법을 설명합니다.
* ASP.NET Core 1.0 – Configure Application Insights : Joao Sousa가 ASP.NET Core 1.0에서 Application Insights 기능 설정 방법에 관해 설명합니다.
* App Service Mobile Apps .NET Client SDK 3.0.1 release : Mimi Xu가 App Service Mobile Apps .NET Client SDK 3.0.1 버전에 관해 소개합니다.
* Sending a Regular SMS with Azure Functions and Twilio : Jason Roberts가 Azure Functions과 Twilio 이용하여 메시지를 전송하는 방법에 관해 소개합니다.


### Games 소식
* Curated #UnityTips No. 17 by DevDog October 2016 : DevDog가 Unity 개발에 도움이 될 수 있는 17번째 Tip을 공유했습니다.
* Unity 5 Tutorial: How to debug raycasts (video) : Gamad에서 raycasts를 디버깅하는 방법에 관해 설명합니다.
* Using InputFields with C# Unity 5.4 (video) : Learn To Be Indie에서 C# Unity 5.4에 인풋필드를 설명합니다.

// 전무님 소개
