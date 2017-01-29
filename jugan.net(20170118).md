### On .NET 소식

[지난 주 On .NET]()(링크)에는 David와 함께 일정, 날씨등 다양한 정보를 표시해주는 자작 매직미러(스크린 거울)의 제작 과정을 알아보았습니다. 제작된 매직미러는 라즈베리파이 Pi3와 Windows 10 IoT Core를 기반으로 만들어졌으며 구동되는 어플은 직접 코딩한 UWP 및 오프소스 UWP 어플리케이션이 적용되었으며 카메라, 마이크, 사운드, 음성인식 기반 동작등의 기능도 포함되어 있습니다.

//그림

이번주에는 올해의 .NET 플랫폼의 전망과 방향에 대해서 얘기해 보려 합니다. 아직 구체적인 게스트는 정해지지 않았지만 유익하고 놀랄만한 만한 정보가 될 수 있도록 준비해 보겠습니다.


### 금주의 패키지: PwdLess
암호는 그 생성과 관리가 신중해야 하며 그와 더불어 사용하는것도 많은 번거로움이 있습니다. 또한 이미 생성되어 사용중인 수십,수백억의 많은 암호가 보안에 취약하다고 알려져 있습니다. 암호를 사용하지 않고 다른 방법을 택할수도 있을까요? 다행히 다른 대안이 있으며 어플리케이션에 따라선 이 방법이 더 적당할 수 있습니다.

이미 잘알려진 대안으로는 "매직링크"로 일컬어지며 일반적으로 nonces 라는 값으로 어플리케이션에서  사용자의 이메일이나 전화번호를 포함하여 보내는 경우입니다.

PwdLess는 "매직링크"를 지원하기위해  .NET 기반으로 구축된 라이브러리입니다.  .NET 기반으로 만들어졌지만 다른 플랫폼에서도 간단히 HTTP API. GET /auth/sendNonce?identifier=[IDENTIFIER] 을 보내고  GET /auth/nonceToToken?nonce=[NONCE]을 응답코드 200번 코드로  JWT(JSON Web Tokens, 링크)형식으로 답할 수 있다면 어디서든지 사용가능합니다.

PwdLess는 JSON 파일로 간단하게  설정가능합니다.

// 코드


### 금주의 게임 : Terraria
Terraria는 샌드박스의 자유로움을 잘살리면서 액션 게임과 메카닉게임요소가 혼합된 환상적인 2D 어드벤처 생존 게임입니다. Terraria 게임 플레이어는 땅을 파고, 싸우며 아이탬 업그레이드 하기위해서 맵을 탐색하여 자원을 수집 해야합니다. 플레이어는 자기 자신만의 맵과 도시를 만들수도 있습니다.  Terraria는 랜덤형식으로 많은 맵의 생성이 가능하며 수 많은종류의 무기와 갑옷 아이템등 다양한 옵션을 제공합니다.

//그림  

Terraria(링크)는  Re-Logic(링크)에서 C#(링크)과  XNA를이용하여 개발되었습니다. 현재 Steam(링크)을 통해서 Windows, Mac, Xbox 360, Xbox One, PlayStation 3, PlayStation 4, PSVita, Android, iOS에서 즐기실 수 있습니다. 



### .NET 소식
* What .NET Developers ought to know to start in 2017 : Scott Hanselman이 2017년 신년에 .NET 개발자가 알아야할 정보를 정리하여 공유했습니다.
* Essential .NET – Essential MSBuild: a build engine overview for .NET tooling : Mark Michaelis가 "닷넷 기본기 다지기" 시리즈 닷넷 빌드툴 "MSBuild :  build engine overview for .NET tooling"을 설명했습니다.
* Engineering changes for corefx : Wes Haggard가 .NET Core의 Corefx 라이브러리의 Engineering 버전 변경 사항을 공유했습니다.
* Smarter build scripts with MSBuild and .NET Core :  Matthew Abbott가 MSBuild와 .NET Core용 프로젝트 파일을 좀더 효과적으로 구성할 수 있는  스크립트 기능을 소개했습니다.
* Faking out the .NET Runtime version : Rick Strahl이 어플리케이션ㄴ의 실행환경 .NET 버전과 .NET 4.x 버전의 하위 호환성에 대해서 설명했습니다.
* My first ScriptCS :  Shawn Wildermuth가 C# 스크립트 엔진인 ScriptCS 를 소개했습니다
* Implement IDisposable : jbe2277가 Idisposable 인터페이스의 개념과 올바른 구현방법을 설명했습니다.
* Analysing pause times in the .NET GC : Matt Warren이 서버와 워크스테이션의 .NET 환경에서 각각의 GC pause time값의 분석결과를 공유했습니다.
* Visual Studio 2017 and Visual Studio 2015 with .NET Core : Christian Nagel이 .NET Core 어플리케이션 개발환경으로 Visual Studio 2017 와 Visual Studio 2015를 동시에 사용할때 발생할 수 있는 문제점과 해결방법을 공유했습니다.
* C# code formatting settings in VS Code and OmniSharp : Filip W가 VS Code와 OmniSharp를 이용한 C# 코드 포멧 설정 기능을 설명했습니다.
* Analyzing GitHub LINQ usage – the results : Dror Helper가 GitHub에 공유된 많은 소스들이 사용하는 LINQ 명령 패턴의 분석 결과를 공유했습니다.
* VSTS and MSBuild (v15) : Darren Neimke가 VSTS 에서 .NET Core 프로젝트를 자동 빌드하기위한 MSBuild 용 빌드 에이전트 구성방법을 설명했습니다.

### ASP.NET 소식
* An introduction to ViewComponents – a login status view component : Andrew Lock이 ASP.NET Core  Razor view의 View Component를 활용한 로그인 상태 컴포넌트 구현방법을 설명했습니다.
* Getting down to business building an ASP.NET Core API service : Rick Strahl이 Angular 2.0과 ASP.NET Core를 이용한 업무 어플리케이션 구현예를 설명했습니다.
* When a single ASP.NET client makes concurrent requests for writeable session variables : Sanjay Patel이  ASP.NET에서 성능향상을 위해 다중 스레드에서 세션변수를 접근하는 방법을 설명했습니다. 
* .NET Core and NancyFX: can writing a WebApi get any simpler? : Carlos Mendible이 .NET Core와 NancyFX을 이용하여 간단하게 WebApi 를 구성하는 방법을 설명했습니다.
* Enabling gzip compression with ASP.NET Core : Gérald Barré가 ASP.NET Core에서 gzip 압축기능을 사용하는 방법을 소개했습니다.
* Standardize page objects with Visual Studio item templates : Anton Angelov가 Visual Studio의 아이템 템플릿을 이용한 페이지 오브젝트 타입의 표준화 방법을 소개했습니다.
* File logging on ASP.NET Core : Gunnar Peipman이  로그 라이브러리 Serilog 을 ASP.NET Core에서 이용하는 방법을 설명했습니다.

### F# 소식
* F# has won me over: coming to .NET world from outside .NET, : Tom Prior가 F# 언어의 장정과 Mac에서의 F# 개발환경을 소개했습니다.
* New release of @fsibot, now on Azure Functions : Matthias Brandewinder가 자신이 만든  @fsibot 트위터 봇 프로그램을 Azure Function 환경으로 전환한 경험을 공유했습니다.
* You too can build Xamarin apps with F# : Greg Shackles가 F#을 이용한 Xamarin 어플 개발 방법을 소개했습니다.
* Pairwise distance calculation on the GPU :  Xiang Zhang이 GPU를 이용한 "Pairwise distance" 연산 처리 방법을 소개했습니다.
* Estimating Pi on the GPU : Xiang Zhang이 GPU를 이용한 Pi 값계산 방법을 설명했습니다.

### Xamarin 소식
* What Xamarin developers ought to know to start 2017 : James Montemagno가 2017년 Xamarin 개발자가 알아야할 사항을 공유했습니다.
* Xamarin Alpha Preview 7: Cycle 9 : Adrian Murphy가 알파 프리뷰 7 버전을 소개했습니다. 
* Webinar series: Xamarin University presents getting started with Xamarin : Bryan Costanich가 웨비나 시리즈 : Xamarin 초보자를 위한 가이드 웨비나 정보 5개를 고융했습니다.
* The top 12 Xamarin blog posts of 2016 : Courtney Witmer가 2016년 Xamarin  최고의 블로깅 포스트 12개를 공유했습니다.
* Start the new year with Xamarin developer events : Jayme Singleton이 신년  Xamarin 개발자 행사 일정을 공유했습니다
* The Xamarin show: getting started with MVVM & snack pack 6: managing Android SDKs : James Montemagno가 MVVM을 설명한 Xamarin show(링크)와 snack pack 6번째 시리즈  "Android SDK 관리하기"(링크)를 공유했습니다.
* Securing Mac application with Touch ID : Prashant Cholachagudda가 Mac 어플리케이션에 시스템 Touch ID를  사용하는 방법을 설명했습니다.
* Jumpstart your Xamarin app development : Sam Basu가 모바일 개발을 위한  Xamarin 환경 구축 방법을 설명했습니다.
* Designing a responsive music player in sketch (Part 1) : Christian Krammer가 Mac의 sketch 디자인툴을 이용한 뮤직 플레이 어플리케이션의 디자인 과정을 설명했습니다.
* Multi-targeting the world: a single project to rule them all : Oren Novotny가 Visual Studio 2017의 멀티 타겟 기능과  NET Standard Librarie 프로젝트 그리고 PCL의 차이점을 비교설명했습니다. 
* Adding databound pickers to a ListView : Jesse Liberty가 ListView에 databound picker를 포함시키는 방법을 설명했습니다.

### Azure 소식
* Azure Mobile Apps .NET SDK releases : Adrian Hall이 Azure Mobile SDK 릴리즈 소식을 공유했습니다.
* Announcing the Azure Tools Extension for Visual Studio Code : Brady Gaster가 Visual Studio Code의 Azure Tools Extension의 발표 소식을 공유했습니다.
* Create you first ASP.NET Core App and host it in a Linux Docker container on Microsoft Azure Part 1, Part 2, and Part 3 : Malte Lantin이 완성된 ASP.NET Core App을 Azure 클라우드의 리눅스 도커환경에 호스팅 하는 방법을  Part 1(링크), Part 2(링크), Part 3(링크)로 나누어 설명했습니다.
* Azure Storage Queues new feature: pop-receipt on add message : Sercan Guler가 Azure Storage Queue의 새로운 기능 "pop-receipt on add message:메시지 추가시 트래킹 키 얻어오기"을 설명했습니다.

### UWP 소식
* Join us on Feb 8th for Windows Developer Day – Creators Update livestream : Windows Apps Team에서 Windows Developer Day 라이브 행사 진행 소식을 공유했습니다.
* Adafruit Class Library for Windows IoT Core : Rick Lesniak가 취미용 전자기기 업체 에이타프르트(Adafruit)의 여러 IoT 장비를 제어할 수 있는 Adafruit Class Library for Windows IoT Core를 소개했습니다.
* Modern Apps – Exploring the UWP Community Toolkit : Frank La Vigne이 UWP 개발에 도움이되는 많은 샘플을 포함한 UWP Community Toolkit을 소개했습니다.
* Using custom fonts in C# UWP apps : Martin Zikmund가 C# UWP용 어플에서 사용자 폰트를 적용하는 방법을 설명했습니다.
* Hitchhiking the HoloToolkit-Unity, Leg 9–Holes in the Walls : Mike Taulty가 HoloToolkit을 이용한 샘플개발 9번째 "벽의 구멍 효과 활용하기"를 설명했습니다.
* Windows 10, UWP, IoT Core, SpeechSynthesizer, Raspberry PI and ‘Audio Popping’ : Mike Taulty가 Windows 10, UWP, IoT Core 플랫폼에서 사용가능한  음성출력기능 "Audio Popping"을 설명했습니다.

### Data 소식
* Paging with Entity Framework Core : Gunnar Peipman이 Entity Framework Core를 이용한 페이징 데이터 처리방법을 설명했습니다.
* What’s New in Entity Framework Core 1.1 : Ricardo Peres가 Entity Framework Core 1.1의 새로운 변경 사항을 공유했습니다.

### Game 소식
* Unity Navigation – Part 1 : Stacey Haffner.
* How I taught people to play my game in 8 steps.
* Character design – some tips and tricks : Chris Hildenbrand가 캐릭터 디자인에 도움이 되는 팁 & 트릭을 공유했습니다.
* Why Angry Birds is so successful and popular: a cognitive teardown of the user experience : Charles Mauro가 앵그리버드의 인기비결에 대한 자신의 의견을 공유했습니다.
* Developer perspectives: lessons from E McNeill : 오큘러스 VR 게임 대회 우승작품을 디자인한  E McNeill의 개발자 관점에서의 프로젝트  경험을 공유했습니다.
* Why adventure games rock – Part 1 : Bryce Covert가 어드벤쳐 게임의 인기 비결을 설명했습니다.
* Curated #UnityTips No. 28 by DevDog January 2017 by DevDog.
* Unity UFPS tutorial: enemy hit & damage animation : Jay AnAm가 Unity 확장 아이템 UFPS (Ultimate FPS)의 활용법을 설명했습니다.

// 전무님 소개
