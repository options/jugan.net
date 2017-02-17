여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.
금주의 커뮤니티 소식
Taeyo.NET에서 http://docs.asp.net의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.


### On .NET 소식

[지난 주 On .NET]( https://blogs.msdn.microsoft.com/dotnet/2016/11/29/the-week-in-net-cosmos-on-on-net-gongsolutions-wpf-dragdrop-transistor/)에는 Xavier Decoster가 Maarten Balliauw와 함께 MyGet에 관해 이야기 나누었습니다.

이번 주 On .NET에서는 MVP Summit 현장에서 MVP들과 함께 인터뷰를 진행하였습니다.
* [AsyncEx]( https://www.youtube.com/watch?v=qXqUUmkaPzU) : Stephen Cleary가 async/await를 위한 헬퍼 라이브러리 AsyncEx에 관해 설명합니다.
* [IoT, sensors, and Azure](https://www.youtube.com/watch?v=VgpqztbvzS8) : Luis Valencia가 Azure IoT의 센서 모니터링과 신호에 관해 설명합니다.

### 금주의 패키지 - FlexViewer by ComponentOne
[.NET 개발 환경을 지원하는 리포팅 툴은 상당히 많습니다.]( https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=.net+reporting) 그 중 [ComponentOne]( http://www.componentone.com/)라는 회사에서 개발한 컴포넌트 [FlexViewer]( http://www.componentone.com/Studio/FlexReport#flexviewer)는 개발사에서 직접 기술 지원은 물론 유지 보수까지 A/S하고 있습니다. FlexViewer는 WinForms, UWP, MVC 환경에서 동작하며 PDF, HTML, Office 등 다양한 포맷을 지원합니다.
ComponentOne 홈페이지에서는 [FlexViewer를 이용해 4분만에 리포트를 만들어 볼 수 있는 영상 외 다양한 교육]( http://our.componentone.com/2016/12/01/get-started-with-flexviewer-an-mvc-report-viewer/) 리소스를 제공하고 있습니다.

// 그림

### 금주의 게임 - I Expect You To Die
[I Expect You To Die]( https://iexpectyoutodie.schellgames.com/)는 VR 퍼즐 게임입니다.
플레이어는 최고의 비밀요원이 되어 여러 위험 상황 속에서 미션을 완수해야 하며, 미션마다 주어진 문제를 해결하기 위해 현명하면서도 빠른 순발력을 지녀야 합니다.
게임 진행 방식은 단순히 편안하게 앉아 팔을 뻗은 상태로 VR 환경 속에서 필요한 아이템을 획득하여 게임을 즐기실 수 있습니다.
제목처럼 게임을 진행하다 보면 많은 미션 실패와 죽음을 맞이하게 되는데, 게임상의 퍼즐은 여러 방법으로 풀릴 수 있으며, 여러 번의 퍼즐 실패는 미션을 완료하는 데 많은 도움이 될 것입니다.
//그림

[I Expect You To Die]( https://iexpectyoutodie.schellgames.com/)는 [Schell Games]( https://www.schellgames.com/)에서 [C#](https://www.schellgames.com/)과 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2016/12/06/the-week-in-net-on-net-on-myget-flexviewer-i-expect-you-to-die/unity3d.com)를 이용하여 개발되었으며, 현재 Oculus Rift와 PlayStation VR 버전에서 게임을 즐기실 수 있습니다.

### .NET 소식
* 15 Years of Concurrency : Joe Duffy가 지난 Microsoft 차세대 운영체제 개발 프로젝트인 "미도리"를 진행하면서 얻은 Concurrency (동시성)에 관련한 개발 경험을 공유했습니다.
* Sharing code across .NET platforms with .NET Standard : Jonathan Mezach가 기존의 .NET 플랫폼과 .NET Standard 간에 코드 공유 방법을 공유하였습니다.
* Evolving the Visual Studio Test Platform – Part 3: .NET Core, convergence, and cross-plat : Pratap Lakshman가 Evolving the Visual Studio Test Platform의 3번째 파트를 공유했습니다.
* How I calculate similarities in cookit? : Szymon Warda이 자신이 만든 cookit 사이트(요리 레시피 관련 정보 수집 웹사이트)에서 요리 조리법의 유사성을 어떻게 파악하는지 설명합니다.
* Multiple Versions of .NET Core Runtimes and SDK Tools SxS Survive Guide : Nicolò Carandini가 다중 .NET Core 런타임과 SDK를 사용할때, SxS(side by side) 환경 구축에 필요한 개발 가이드를 공유했습니다.
* Writing C# build scripts with FAKE, OmniSharp and VS Code : Filip W가 FAKE 라이브러리와OmniSharp 그리고 VS Code를 이용한 C# 빌드 스크립트 작성 방법에 관해 설명합니다.
* Implementing the retry pattern for async tasks in C# : Alastair Crabtree가 C# async tasks의 retry 패턴 구현 방법에 관해 설명합니다.
* 10x speedup utilizing Nagle Algorithm in business application : Ayende Rahien가 네이글 알고리즘을 이용하여 10배 빠른 비즈니스 애플리케이션을 구현하는 방법을 설명합니다.
* Designing Akka.NET Applications from Scratch Part 2: Hierarchies and SOLID Principles : Aaron Stannard가 ‘Akka.NET을 이용한 애플리케이션 만들기’ 스리즈에서 2번째로 Hierarchies 와 SOLID Principles에 관한 내용을 정리하였습니다.
* Introduction to Asynchronous Programming in C# (Part 2) (video) : Jeremy Kruer가 C# 비동기 프로그램에 관해 소개합니다.
* AWS Lambda Supports C# on .NET Core : 이제 .NET Core 1.0 런타임을 사용하여 C #에서 AWS 람다 함수를 개발할 수 있습니다. 
* Testing Experimental Code in Production with Scientist.NET : Jason Roberts가 Scientist.NET을 이용하여 비검증된 개발 코드를 운영 환경에서 안전하게 테스트 할 수 있는 방법을 설명합니다.
* Let .NET framework care about transactions handling for you by implementing IEnlistmentNotification : Mateusz Roszczak이 .NET framework 환경에서 IEnlistmentNotification 인터페이스를 구축하여 트랜잭션을 관리하는 방법을 설명합니다.
* First steps with .NET Core Tools MSBuild “alpha” : Carlos Mendible이 .NET Core Tools인 MSBuild “alpha”의 사용 방법을 설명합니다.

### ASP.NET 소식
* Dockerizing a real world asp.net core application : Thien Nguyen이 ASP.NET Core 애플리케이션을 도커환경에서 운영하는 방법을 공유했습니다.
* Url culture provider using middleware as filters in ASP.NET Core 1.1.0 : Andrew Lock이 ASP.NET Core 1.1.0의 '미들웨어를 필터로 사용하기'기능을 사용하여 URL 세그먼트 기반으로 요청 위치를 쉽게 추가하는 방법을 설명합니다.
* Using Let’s encrypt with ASP.NET Core : Gérald Barré가 ASP.NET Core에서 오픈 소스 라이브러리 "Let’s encrypt" 사용 방법을 공유하였습니다.
* Bare metal APIs with ASP.NET Core MVC : Ben Foster가 ASP.NET Core MVC로 오롯이 API만 빌드하려는 경우에 관해 설명합니다.
* Updated EF Core & ASP.NET MVC sample to 1.1 : Damien Bod가 Entity Framework Core를 포함한 ASP.NET Core 1.1 MVC Sample을 자신의 Github에 업데이트하였습니다. 
* The ugly truth behind pretty URLs : Krzysztof Zmorzyński가 ASP.NET MVC의 RouteAttribute 동작방식과 특징에 관해 설명합니다.
* Realtime Twitter Stream Visualization with .NET Core, Emitter and JavaScript : Roman Atachiants가 
‘Emitter messaging broker’를 사용해 실시간으로 Twitter에 데이터 스트림을 캡처하고 브로드 캐스트하는 방법에 관해 설명합니다.
* Fat Controller CQRS Diet: Notifications : Derek Comartin이 CQRS(Command-Query Responsibility Segregation, 명령과 쿼리의 역할구분)를 이용하여 MVC 컨트롤러를 효과적으로 개선하는 방법을 공유하였습니다.
* ASP.NET: Sharing OWIN Authentication Cookie across IIS Applications : Nandip Makwana가 OWIN 인증 쿠기를 IIS Application에 공유하여 활용하는 방법을 설명합니다.
* ASP.NET Core Logging Tutorial : Thomas Ardal이 ASP.NET Core에서 Logging 활용 방법을 배울 수 있는 튜토리얼을 공유하였습니다.
* ASP.NET Core Authentication in a Load Balanced Environment with HAProxy and Redis : Tugberk Ugurlu가 로드 벨러스가 구축된 환경에서 HAProxy과 Redis을 이용하여 ASP.NET Core 인증 동작방식과 이와 관련된 주의사항에 관해 설명합니다. 

### F# 소식
* Azure Notebooks supports F# out of the box! : Azure Notebooks에서 F#을 지원합니다.
* F# in Production : Kristian Schmidt가 자신의 업무 프로젝트에 F#을 활용한 경험담을 공유했습니다.
* Introduction to Azure IoT with F# : Chambers가 Azure IoT에서 F# 활용 방법에 관해 설명합니다.
* Easy Domain Modeling with Types : Mark Seemann이 업무 도메인 모델을 쉽게 구축할 수 있는 F#의 장점들을 소개합니다.
* Introducing Stream Processing in F# : Mikhail Shilkov가 F#의 데이터 처리기능인 Stream Processing을 소개합니다.

### Xamarin 소식
* Xamarin Alpha Preview 3: Cycle 9 : Adrian Murphy가 Xamarin의 새로운 기능인 Cycle 9의 세 번째 알파 프리뷰를 게시하였습니다.
* Xamarin Developer Events in December : Jayme Singleton이 12월 Xamarin 개발자 행사 일정을 공유했습니다.
* Live Webinar | Getting the Most out of iOS 10 and Android N : Courtney Witmer가 iOS 10과 Android N의 주요 기능을 알아보는 웨비나를 진행했습니다.
* Say Hello to the Xamarin Profiler : Nina Vyedin이 Xamarin Profiler에 관해 소개합니다..
* Creating Platform-Specifics in Xamarin.Forms : David Britch이 Xamarin.Forms에서 Platform-Specifics 기능을 구현해본 경험담을 공유하였습니다.
* Learn interactively with Xamarin Workbooks : Xamarin Workbooks을 통해 효과적으로 Xamarin을 학습해보세요.
* Xamarin.iOS Architecture : Xamarin 공식 블로그에서 Xamarin.iOS Architecture를 설명했습니다.
* Xamarin.Android Architecture : Xamarin 공식 블로그에서 Xamarin.Android Architecture를 설명했습니다.
* The Xamarin Show 10: Prism for Xamarin.Forms with Brian Lagunas, The Xamarin Show 11: Xamarin Profiler with Nina Vyedin, & Xamarin.Forms: Java.Lang.IllegalStateException : James Montemagno가 두편의 자마린 쇼와 Java.Lang.IllegalStateException 예외가 발생하는 상황과 원인 대처 방법을 공유하였습니다. 
* Free Xamarin University Resources : Dan Rigby 공유한 Xamarin University Resources 를 통해 
Xamarin을 무료로 배울 수 있습니다.
* Customizing a Xamarin Forms Application, Part 2 : Wallace McClure가’ Customizing a Xamarin Forms Application’의 2번째 파트를 게시하였습니다.
* Accessing Files on Emulators & Accommodating The On Screen Keyboard in Xamarin Forms : Adam Pedley가 에뮬레이터 파일 접근 방법과 Xamarin Forms의 On Screen Keyboard 기능 사용 방법을 설명하였습니다.
* Mastering Azure App Service, Part 4: Building Azure Mobile Apps : Scott J. Peterson이 Mastering Azure App Service의 4번째 스리즈 "Azure Mobile Apps 구축하기"를 게시 하였습니다.
* Building a Puzzle Game with Xamarin Forms : Daniel Vaughan이 Xamarin Forms으로 퍼즐게임을 구현하는 방법을 설명합니다.
* Xamarin Forms – Bindable Picker : Matthew Soucoup이 Xamarin Forms에서 Picker 컨트롤의 데이터 바인딩 방법에 관해 소개합니다.
* Pontoon – Yet More Platforms : Peter Foot이 Xamarin 플렛폼 현황을 정리하였습니다.

### Azure 소식
* Visual Studio Tools for Azure Functions : Andrew B. Hall이 Visual Studio Tools for Azure Functions에 관해 소개합니다.
* Introducing Microsoft Stream : Scott Hanselman과 Rob Caron이 Azure 기반의 비디오 공유 플렛폼인 ‘Microsoft Stream’을 소개합니다.
* NoSQL .NET Core development using a local Azure DocumentDB Emulator : Scott Hanselman이 Azure DocumentDB Emulator를 이용한 .NET Core NoSQL 개발 방법을 설명합니다.
* Deploying Azure Functions Automatically : Adrian Hall이 Azure Functions 자동 배포 방법을 공유했습니다.
* Screen Scraping As A Service with Azure Functions in 5 Mins : Jason Roberts가 Azure Functions을 이용하여 5분 만에 Screen Scraping(일종의 웹 데이터 탐색)기능을 서비스로 구현하는 방법을 설명합니다.

### Games 소식
* Unity 5.5 Is Ready for You : Alex Lian이 Unity 5.5 출시 소식을 공유했습니다.
* [Unity 5] Tutorial: How to make a grappling/grapple hook (Video) : Gamad이 grappling/grapple hook 기능 구현 방법을 공유하였습니다.
* Game Design Deep Dive: Controlling two things at once in Soft Body : Zeke Virant가 두개의 게임 오브젝트를 동시에 컨트롤해야 하는 게임인 "Soft Body"에 관해 소개합니다.
* Unity3D – Archery Arrows that Rotate (Video) : Stuart Spence가 게임 속 화살이 현실감 있게 날아가게 하는 구현 방법을 설명했습니다.
* Kinematic Equations (E01: introduction) (Video) : Sebastian Lague가 게임에서 활용될 수 있는 역학공식 시리즈 E01 : "소개" 편을 공유했습니다.
* Unity Tool: Mesh Combine Wizard : Ennoble Studios가 "Mesh Combine Wizard" 무료 툴을 공유했습니다.


// 전무님 소개
