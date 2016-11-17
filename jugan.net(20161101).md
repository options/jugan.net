주간닷넷 2016년 11월 01일

### On .NET 소식
[지난 주 On .NET]()에는 Martin Woodward와 함께 .NET Foundation에 대해서 이야기 나누었습니다. 

이번주에는 Mei-Chin Tsai 그리고 Jan Kotas와 함께 CoreRT and .NET Native(링크)에 대해서 얘기를 나누어볼 계획입니다.

### 금주의 패키지  -  Serilog
현대적인 어플리케이션은 매우 복잡하며, 많은 작업 처리해야 합니다. 따라서 어플리케이션은 비동기적으로 처리되고 분산 환경에 친화적이여야 합니다. 이러한 현대적인 어플리케이션은 개발과정에서 개발자가 코드를 빠르게 이해하며 버그를  효과적으로 찾는다는것은 쉽지않은 작업입니다. 어플리케이션을 모니터링하고 디버깅해주는 툴은 계속 발전 하고 있으며 Serilog을 이용하면 어플리케이션의 로그 데이터 로딩과 분석을 아주 쉽게 해결할 수 있습니다.

아래 코드는 라이브러리를 통해서 로그를 남기는 코드입니다.

// 코드

로그 메시지는 문자 포맷을 지원하기 때문에 Serilog 는 정해진 위치 지정자를 가지며 Elapsed(작업시간)과 같은 인자를 전달하여 로깅 할 수 있습니다.

// 코드

많은 Serilog sinks(링크)는 JSON 구조의 데이터를 지원하므로 정규식을 이용하거나 로그 파일을 파싱하지않고도 Elapsed > 10 같은 검색조건을  직접 실행하여 결과를 얻을 수 있습니다.

### 금주의 게임 - Super Dungeon Bros
Super Dungeon Bros는 빠르게 진행되는 액션게임으로 최대 4명이 동시에 플레이할 수 있습니다. 플레이어는 게임에서 헤비메탈 음악 락의 영웅인 Axl, Lars, Freddie ,Ozzie 중 하나를 선택하게 되며 선택된 영웅을 통해서 각 맵의 퀘스트를 성공적으로 완수해야 합니다. 동료 영웅들과 협동하여 맵을 탐색하고, 전투를 벌이고, 아이탬을 획득하며, 적 몬스터들을 사냥하게됩니다. 게임 Super Dungeon Bros는 다중 플레이어, 다중 맵, 동적 맴 생성 그리고 일간, 주간 시리즈로 진행할수있는 퀴스트 제공등의 기능이 있습니다.

//그림

Super Dungeon Bros(링크)는 현재  React Games (링크)에서 Unity(링크)와 C#(링크)을 이용하여 개발중이며 Xbox One, PlayStation 4 그리고 Steam을 통해서 플레이 할 수 있습니다.

### .NET 소식
* Announcing NuGet 3.5 RTM : Harikrishna Menon이 NuGet 3.5 RTM 을 소개했습니다.
* Using dotnet watch test for continuous testing with .NET Core and XUnit.net : Scott Hanselman이 .NET Core, XUnit.net 환경에서 dotnet watch 명령을 이용한  이용한 지속적인 테스트 방법을 설명했습니다.
* What’s new in Serilog? : Nicholas Blumhardt가 로깅라이브러리인 Serilog의 새로운 기능을 소개했습니다.
* Entity Framework Core – Table per Hierarchy : Christian Nagel이 Entity Framework Core - Table per Hierarchy를 설명했습니다.
* How does the ‘fixed’ keyword work? : Matt Warren이 C#의 fixed 키워드에 대해 설명했습니다.
* A monthly compilation of community posts : MyGet이 한달간의 커뮤니시 소식을 정리해서 공유했습니다.
* Using NDepend to Help Improve Architecture : Steve Desmond가 아키택쳐의 설계 향상을 위해 NDepend를 이용하는 방법을 소개했습니다.
* RavenDB 3.5 RTM released : Ayende Rahien이 RavenDB 3.5 RTM 릴리즈 소식을 공유했습니다.
* Project.json made my life easier and it is not a joke : Piotr Stapp가 Project.json 프로젝트 타입의 장점을 설명했습니다. 
* Implementing LUIS Routing within BotFramework : Robin Osborne가 BotFramework에 MVC의 LUIS Routing을 구현하는 방법을 설명했습니다. 
* Automating Installation Builds and Chocolatey Packaging : Rick Strahl이 빌드 자동화와 Chocolatey 를 이용한 패키징에 대해 설명했습니다. 
* InfoQ eMag: A Preview of C# 7 (free eBook): 무료 eBook "A Preview of C# 7"이 공유 되었습니다.
* Interception in .NET – Part 4: An Interception Framework : Ricardo Peres가 Interception Framework 구현방법 Part 4를  공유했습니다.
* .NET Core Tooling in Visual Studio “15” : David Carmona와 Joe Morris가  Visual Studio “15” 버전의 .NET Core 지원 기능을 소개했습니다.

### ASP.NET 소식
* Free ASP.NET Core 1.0 Training on Microsoft Virtual Academy : Scott Hanselman이  ASP.NET Core 1.0 무료 교육 과정을 소개했습니다.
* Bearer Token Authentication in ASP.NET Core : Jeffrey T. Fritz가 ASP.NET Core의 Bearer Token Authentication 방법을 설명했습니다.
* Angular2 CLI with ASP.NET Core application – tutorial : Michał Dymel이 ASP.NET Core에서 Angular2 CLI 의 활용법을 설명했습니다.
* Step by step: Scale ASP.NET Core with Docker Swarm : Carlos Mendible이 도커 컨테이너를 이용하여 ASP.NET Core 처리능력을 향상하는 방법을 공유했습니다.
* Resource-based authorisation in ASP.NET Core and Accessing services when configuring MvcOptions in ASP.NET Core : Andrew Lock이 ASP.NET Core의 리소스 기반 권한 관리(링크)와 MvcOptions을 이용한 서비스 접근(링크)을 설명했습니다.
* Angular2 search with ASP.NET Core and Elasticsearch : Damien Bowden이 ASP.NET Core에서 Angular2 와 Elasticsearch를 이용한 웹사이트 검색기능의 구현방법을 설명했습니다.
* Testing SSL in ASP.NET Core : Shawn Wildermuth가 ASP.NET Core의 SSL 구성과 이를 확인하는 방법을 설명했습니다.
* ASP.NET Core and the Enterprise Part 2: Hosting : K. Scott Allen이 "ASP.NET Core과 기업 어플리케이션: 파트 2 : 호스팅"에 대해서 설명했습니다
* Vertical Slice Test Fixtures for MediatR and ASP.NET Core : Jimmy Bogard가 MediatR 과 ASP.NET Core에서 주요 단계별 테스트 방법을 설명했습니다.
* Run & Deploy ASP.NET Core Web Applications on Ubuntu behind Apache Server : Sumit Chauhan이 우분투의 아파치 서버에 ASP.NET Core 웹 어플리케이션을 배포하고 실행시키는 방법을 설명했습니다.
### F# 소식
* F# Domain Modeling : Luke Merrett이 F# Domain Model을 설명했습니다.
* Paket ‘why’ command, : Tomasz Heimowski가 Paket 새롭게 추가된 'why' 명령어를 설명했습니다.
* F# Language Suggestions are now : GitHub에 F# 언어의 추가 기능제안이 공유되었습니다.
* Yahtzee Scoring Kata in F# : Mark Heath가 주사위 게임 Yahtzee 의 점수계산을  F#으로 구현하여 설명했습니다
* F# support on .NET Core SDK Preview 3:.NET Core SDK Preview 3 버전에서 F#의 지원 내용이 소개 되었습니다

### Xamarin 소식
* Last Xamarin Dev Days of 2016 : Jayme Singleton이 2016년 마지막  Xamarin Dev Days 개발 행사 일정을 공유했습니다.
* The Xamarin Show Snack Pack 3: Xamarin Test Recorder for macOS : James Montemagno의  Xamarin Show Snack Pack 3( Xamarin Test Recorder for macOS)이 소개 되었습니다.
* Xamarin Android 9-Patch Image Splashscreen, Navigating in Xamarin Forms, and Configuration Files In Xamarin Forms : Adam Pedley가 Android  Xamarin 에서 Splashscreen으로 사용할 수 있는 9-Patch Image(링크)와 Xamarin Forms에서의 화면 이동 방법(링크), Xamarin Forms의 설정 파일 구현및 활용(링크)에 대해서 설명 했습니다.
* Better Navigation in Xamarin.Forms : Jesse Liberty가 Xamarin.Forms에서 화면간 전환 방법에 대해 설명했습니다.

### Azure 소식
* Announcing Azure Storage Client Library GA for Xamarin : Dinesh Murthy가 
Windows Azure Storage에서 Xamarin용 Azure Storage Client Library GA를 발표소식을 공유했습니다.

### Games 소식
* Unite ’16 Keynote (video) : Unite 2016 행사 키노트가 공유되었습니다.
* Introducing Holographic Emulation (video) : Peter Freese가 Holographic Emulation을 소개했습니다.
* MonoGame Live #6 : XNA Sample Conversion, Localisation (video) : MonoGame에서 MonoGame Live #6을 진행했습니다.

* Unity – 2D Movement (part 6a) – Animation : Wheels and Unity – 2D Movement (Part 6b) – Animation : Tread (video) : Pixel Make에서 Unity 2D Movement - Animation에 관련된 동영상 교육 2개(part 6a, part 6b)를 공유했습니다.
