여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On .NET 소식
[지난주 On .NET]( https://sec.ch9.ms/ch9/11fd/568d2b2f-7d9f-4637-9a50-c3ed893111fd/onnet20160915steeltoe_mid.mp4)에는 David Morhovich, Zach Brown와 함께 마이크로 서비스 패턴 범용 툴킷인 Steeltoe에 대해서 얘기 나누어보았습니다.

// 동영상 https://sec.ch9.ms/ch9/11fd/568d2b2f-7d9f-4637-9a50-c3ed893111fd/onnet20160915steeltoe_mid.mp4

[이번 주 On .NET]( https://sec.ch9.ms/ch9/d576/52fe7232-7f90-4e82-b6d5-823b7241d576/onnet20160922sebros_mid.mp4에는 (Sebastien Ros)[ http://sebastienros.com/] 와  .NET Core에서 실행되는 새로운 버전의 .NET CMS(Content Management System) 틀인 [Orchard 2]( https://github.com/orchardcms/orchard2) 에 대해 알아보겠습니다.
### 금주의 패키지  -  C# Functional Extensions
[C# functional extensions]( https://github.com/louthy/language-ext)는 자주 사용하는 함수 패턴들 예를 들면 tuples, option types, monads, “var add = fun( (int x, int y) => x + y );”처럼 람다(Lambda) 선언을 더욱 쉽도록 하며, 패턴 매칭 등의 기능을 포함합니다. 또한 [Agents](https://en.wikipedia.org/wiki/Agent-oriented_programming)간의 메시지 통신을 기반으로 한 얼랑(Erlang)과 비듯한 형태의 동시성도 지원합니다.
// 코드 <script src="https://gist.github.com/bleroy/979a68b397080726d8966d98624ab25f.js"></script>

### 금주의 게임 - Firewatch
[Firewatch]( http://www.firewatchgame.com/)는 아름다운 그래픽과 재미있는 스토리를 갖춘 탐험 게임입니다. Firewatch는 1989년을 배경으로 하며 주인공인 Henry가 지루하던 화재 감시탑의 감시원으로의 삶을 떨쳐내고 드넓은 산속과 황하를 탐험하게 되는 스토리입니다.
//그림

(Firewatch)[ http://www.meetup.com/wrocnet/] 는 (Unity)[ https://unity3d.com/] 와 (C#)[https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners] 을 이용하여 Campo Santo에서 제작했으며 현재 Steam과 Good Old Game을 통해서 PlayStation 4, Windows, Mac OSX 에서 즐기실 수 있습니다. Xbox One 버전으로는 2016-09~21일 출시되었습니다.

### .NET 소식
* (Self-contained .NET Core Applications)[ http://www.hanselman.com/blog/SelfcontainedNETCoreApplications.aspx] : Scott Hanselman이 Self-contained  형식의  .NET Core Applications 개발 방법을 공유했습니다.
* (Marten 1.0 is Here!)[ https://jeremydmiller.com/2016/09/14/marten-1-0-is-here/] : Jeremy D. Miller가 Marten 1.0 릴리즈 소식을 공유했습니다.
* (Authenticode Signing Service and Client)[ https://oren.codes/2016/09/12/authenticode-signing-service-and-client/] : Oren Novotny가 인증코드 서명 서비스와 클라이언트에 대해 설명합니다.
* (Creating Beautiful Effects for UWP)[ https://blogs.windows.com/buildingapps/2016/09/12/creating-beautiful-effects-for-uwp/#zdYK2PhlbZc1R6EE.97] : Michael Crump가 UWP(Universal Windows Platform)에서 활용할수있는 유용한 그래픽 효과에 대해 설명합니다.
* (Subverting .NET Type Safety with ‘System.Runtime.CompilerServices.Unsafe’)[ http://mattwarren.org/2016/09/14/Subverting-.NET-Type-Safety-with-System.Runtime.CompilerServices.Unsafe/] (NSFW in a completely new sense of the term) and (Compact strings in the CLR)[ http://mattwarren.org/2016/09/19/Compact-strings-in-the-CLR/]: Matt Warren이 “System.Runtime.CompilerServices.Unsafe API”에 대한 설명과 CLR의 “Compact strings”에 대해 설명합니다.
* (Use HiLo to generate keys with Entity Framework Core)[ http://www.talkingdotnet.com/use-hilo-to-generate-keys-with-entity-framework-core/] : Talking Dotnet에서 Entity Framework Core를 이용한 HiLo 패턴 키 생성에 대해 설명합니다.
* (Asynchronous Programming – Exception Handling)[ https://github.com/jbe2277/waf/wiki/Exception-Handling] : jbe2277이 비동기 프로그램에서 예외 처리에 대해 설명합니다.
* (A first look at Entity Framework Core with SQLite database on Ubuntu Linux)[ http://vmtri.com/a-first-look-at-entity-framework-core-with-sqlite-database-on-ubuntu-linux/] : Võ Minh Trí가 Ubuntu Linux 에서  SQLite database , Entity Framework Core 의 활용법을 공유했습니다.
* (Using PeerFinder from Console: Wi-Fi Direct data transfer in C#)[http://blog.plasticscm.com/2016/09/using-peerfinder-from-console-wi-fi.html] : PlasticSCM이  Wi-Fi Direct 기능을 이용하여, 일반 콘솔 프로그램에서도 파일을 공유할수있도록 돕는 PeerFinder 클레스의 사용 방법에 대해 설명합니다.
* (Graph Database with Neo4j and a .NET Client)[ http://thenewstack.io/graph-database-neo4j-net-client/] : Chris Skardon와 Michael Hunger가 Neo4j , .NET Client을 이용한 Graph Database의 구현에 대해 설명합니다.

### ASP.NET 소식
* (Custom ASP.NET Core Middleware Example)[ https://blogs.msdn.microsoft.com/dotnet/2016/09/19/custom-asp-net-core-middleware-example/] : Mike Rousos가 ASP.NET Core Middleware의 커스터마이징 예를 소개합니다.
* (Peachpie: What Difference Does the ‘Core’ Make?)[ http://www.peachpie.io/2016/09/coretesting.html] : Benjamin Fistein이 ASP.NET 와 ASP.NET Core를 비교하여 설명합니다.
* (Configuring environment specific services in ASP.NET Core – Part 2)[ http://andrewlock.net/configuring-environment-specific-services-in-asp-net-core-part-2/], (HTML minification using WebMarkupMin in ASP.NET Core)[ http://andrewlock.net/html-minification-using-webmarkupmin-in-asp-net-core/], and (Viewing what’s changed in ASP.NET Core 1.0.1)[ http://andrewlock.net/viewing-whats-changed-in-asp-net-core-1-0-1/] : Andrew Lock이 ASP.NET Core에서 환경설정 서비스 구현 방법과 WebMarkupMin의 활용, ASP.NET Core 1.0.1의 변경된 사항에 대해 설명합니다.
* (ASP.NET Core with Angular2 – tutorial)[ https://devblog.dymel.pl/2016/09/08/aspnet-core-with-angular2-tutorial/] : Michał Dymel이 ASP.NET Core용 Angular2에 대해 소개합니다.
* (Step by step: Serilog with ASP.NET Core and .NET Core)[ https://carlos.mendible.com/2016/09/19/step-step-serilog-asp-net-core/] and (Microsoft Bot Framework)[ https://carlos.mendible.com/2016/09/11/netcore-and-microsoft-bot-framework/] : Carlos Mendible이 로그 라이브러리 Serilog을 ASP.NET Core에서 활용하는 방법과 Microsoft Bot Framework을 .NET Core에서 활용하는 방법에 대해 설명합니다.
* (AWS DynamoDB on .NET Core: Getting Started)[ http://dotnetliberty.com/index.php/2016/09/19/aws-dynamodb-on-net-core-getting-started/] : Armen Shimoon이  .NET Core에서 AWS DynamoDB를 활용하는 방법에 대해 공유했습니다. 
* (Bending ASP.NET Core MVC To Your Will)[ http://jameschambers.com/2016/09/Bending-ASP-NET-MVC-Core-To-Your-Will/] : James Chambers가 ASP.NET Core MVC 프로젝트 구조와 MVC 동작 과정에 대해 설명합니다.
* (Include user properties in IdentityServer4 with ASP.NET Identity)[ http://dkbe.ch/post/include-user-properties-in-identityserver4-with-asp-net-core-identity] : David Keller가 IdentityServer4 인증 서버 환경에서 ASP.NET Identity에  사용자 정의 속성을 추가하는 방법을 공유했습니다.
* (Full Server logout with IdentityServer4 and OpenID Connect Implicit Flow)[ https://damienbod.com/2016/09/16/full-server-logout-with-identityserver4-and-openid-connect-implicit-flow/] : Damien Bowden이 OpenID와 IdentityServer4를 사용하는 환경에서 완전하게 로그아웃하는 방법에 대해 설명합니다.
* (Getting started with EF Core + Sqlite + Asp.Net core Web api on Mac)[ https://wannabeegeek.com/2016/09/09/getting-started-with-ef-core-sqlite-asp-net-core-web-api-on-mac/] : Swaminathan Vetri가 Mac 에서 EF Core ,  Sqlite,  Asp.Net core Web API를 이용하는 방법에 대해 소개합니다.
* (Real-World CQRS/ES with ASP.NET and Redis Part 3 – The Read Mode0[https://www.exceptionnotfound.net/real-world-cqrs-es-with-asp-net-and-redis-part-3-the-read-model/]l, (Part 4 – Creating the APIs)[ https://www.exceptionnotfound.net/real-world-cqrs-es-with-asp-net-and-redis-part-4-creating-the-apis/], and (Part 5 – Running the APIs)[ https://www.exceptionnotfound.net/real-world-cqrs-es-with-asp-net-and-redis-part-5-running-the-apis/] : Matthew Jones가 ASP.NET에서 CQRS(Command-Query Responsibility Segregation), ES(Event Sourcing) 패턴과 Redis의 활용방법을 Part 3에서,  API 생성 방법을 Part 4에서 , API 실행 방법을 Part 5에서 설명합니다.  

### F# 소식
* (Langston’s Ant in F#)[https://technicalitee.blogspot.com.by/2016/09/langtons-ant-in-f.html] : Ram이 F#으로 구현한 랭턴의 개미(Langton's Ant)에 대해 공유했습니다
* (Programming UrhoSharp with F#)[https://developer.xamarin.com/guides/cross-platform/urho/fsharp-and-urhosharp/] : Xamarin의 UrhoSharp을 F# 프로젝트에서 활용하는 방법에 대해 설명했습니다.
* (Use apply and carry on)[ http://red-green-rewrite.github.io/2016/09/14/Use-apply-and-carry-on/] : Milosz Krajewski가 F# 언어 문법상 연산(파이프 연산자 |>) 실행 순서 등에 대해 설명합니다.
* (F# Series: Building Real-World Applications in F#)[https://medium.com/@odytrice/f-series-building-real-world-applications-in-f-b45b62ac653d#.7yzhd17dx] : Ody Mbegbu가 F# 언어에 대해 소개합니다.

### Xamarin 소식
* (Major Updates: iOS 10, Android Nougat, and Other Tasty Bits)[ https://blog.xamarin.com/major-updates-ios-10-android-nougat-and-other-tasty-bits/] : Miguel de Icaza가 iOS 10, Android Nougat 업데이트 등의 소식을 공유했습니다.
* (Xamarin Stable Release: Cycle 8 with iOS 10 and Xcode 8 Support)[ https://releases.xamarin.com/stable-release-cycle-8-w-ios-10-and-xcode8-support/] and (Xamarin Preview: Xamarin Profiler 0.34.1)[ https://releases.xamarin.com/preview-xamarin-profiler-0-34-1/] : Adrian Murphy가 iOS 10,Xcode 8 을 지원하는 Cycle 8 버전 소식과 Xamarin Profiler 0.34.1 프리뷰 버전 정보를 공유했습니다.
* (Testing iOS 10 in Xamarin Test Cloud)[ https://blog.xamarin.com/testing-ios-10-in-xamarin-test-cloud/] : John Lago가 Xamarin Test Cloud에서 iOS10 APP 테스트 방법에 대해 설명했습니다.
* (Introducing the Azure Track in Xamarin University)[ https://blog.xamarin.com/introducing-the-azure-track-in-xamarin-university/] : Bryan Costanich가 Xamarin University의 새로운 Azure 교육과정에 대해 소개 합니다.
* (Preparing for Native Library Linking Changes in Android N)[ https://blog.xamarin.com/preparing-for-native-library-linking-changes-in-android-n/] and (Preparing Machines for Xamarin Cycle 8 / iOS10 / Android N)[ http://motzcod.es/post/150380059392/preparing-machines-for-xamarin-cycle] : James Montemagno가  Android N 버전의 Native 라이브러리 변경 사항과 Xamarin Cycle 8 / iOS10 / Android N 개발 환경 설정 방법을 공유했습니다.
* (Xamarin Podcast: iOS 10, iPhone 7, Apple Watch Series 2, and more!)[ https://blog.xamarin.com/podcast-ios-10-iphone-7-apple-watch-series-2-and-more/] : Pierce Boggan이 Xamarin 팟케스트 ( iOS 10, iPhone 7, Apple Watch Series 2)를  공유했습니다.
* (Yet Another Podcast #163: James Montemagno and Xamarin Cycle 8)[ http://jesseliberty.com/2016/09/13/yet-another-podcast-163-james-montemagno-and-xamarin-cycle-8/] : Jesse Liberty가 MS Xamarin team 메니저 James Montemagno와 Xamarin Cycle 8 를 주제로 팟케스트를 진행합니다.
* (VSTS September Extensions Roundup – App Stores!)[ https://blogs.msdn.microsoft.com/visualstudioalm/2016/09/13/team-services-september-extensions-roundup-app-stores/]  : Joe Bourne가 VSTS  9월 업데이트 정보를 공유했습니다.
* (Access a Control Method from a ViewModel)[ https://xamarinhelp.com/access-a-control-method-from-a-viewmodel/] : Adam Pedley가 MVVM 패턴을 사용할 때, ViewModel에서 VIew의  Control에 접근하는 방법에 대해 설명 합니다.
* (Now Xamarin Devs can create Hololens Apps!)[ https://elbruno.com/2016/09/13/hololens-now-xamarin-devs-can-create-hololens-apps/] : Bruno Capuano가 Xamarin에서 Hololens 플랫폼 개발이 지원된다는 소식을 공유했습니다.
* (LoaderViewXamarin – Loading animations for Android TextView and ImageView elements)[ https://github.com/martijn00/LoaderViewXamarin] : Martijn van Dijk가 TextView, ImageView 요소에 애니메이션을 실행할 수 있는 오픈소스 라이브러리인 LoaderViewXamarin을 소개합니다.

### Azure 소식
* (Serving Static Content From Azure Storage: Content Delivery Network Setup)[ https://www.dougv.com/2016/09/serving-static-content-azure-storage-content-delivery-network-setup/] : Doug Vanderweide가 Azure Storage에 정적 컨텐츠를 설정하는 방법에 대해 소개 합니다.

### Games 소식
* (MonoGame – Building multi-platform solutions)[ http://darkgenesis.zenithmoon.com/monogame-building-multi-platform-solutions/] :  Simon Jackson이 멀티 플랫폼 게임 개발 도구인 Monogame에 대해 소개합니다.
* (Tutorial – Zelda style screen transitions in Unity)[ https://theadrainblog.wordpress.com/2016/09/15/zelda-style-screen-transitions-in-unity/] : Unity 에서 2D 수직/수평 스크롤 스타일로 이동하는 방법을 공유했습니다.
* (Seeing Is Deceiving: Your Brain and VR)[ http://www.crytek.com/blog/seeing-is-deceiving-your-brain-and-vr] : crytek에서 VR 효과를 뇌가 이해하는 과정에 대해 설명했습니다.
* (Episode 22: MonoGame (video))[ https://channel9.msdn.com/Shows/Level-Up/Episode-22-MonoGame] : Katie Stone Perez가 MonoGame 개발 방법을 공유했습니다.
* (Unity: In Beta – Animation Window Workflows)[ https://blogs.unity3d.com/2016/09/19/in-beta-animation-window-workflows/] : Will Goldstone이  Unity 5.5 beta의 향상된 Animation Window Workflows 기능에 대하여 소개합니다.
* (Curated #UnityTips No. 13)[ http://devdog.io/blog/2016/09/9-best-unity-tips-for-game-developers-13] : DevDog가 Unity 개발에 도움 될수있는 Tip 정보를 공유했습니다.
* (Unity: Make the Camera Follow a Player (or any GameObject) Smoothly and Fluidly)[ https://kylewbanks.com/blog/unity-make-camera-follow-player-smoothly-and-fluidly] : Kyle W. Banks가 플레이어(혹은 게임객체)를 따라다니는 카메라 시각 효과의 구현 방법에 대해 설명합니다.
* (Unity: Terrain Generation Part 1(2)- Viking Game #2 (video))[ https://www.youtube.com/watch?v=V0dwkrS6CoI] : System Cult에서 게임에 사용될 지형생성 방법을 소개 합니다.


// 전무님 소개
