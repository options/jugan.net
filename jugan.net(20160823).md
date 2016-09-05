### On .NET 소식
On .NET이 새롭게 합류한 호스트 JB Evain와  함께 Channel 9의 새로운 스트디오에서 진행되었습니다.  [지난 주 On .NET]() 에서는 Unity의 Lucas Meijer와 함께 얘기를 나누어 보았습니다.  Lucas Meijer와 Unity 3D의 여러 기술적인 얘기를 나누었으며 멋진 3D 데모도 확인 할수있었습니다.

// 동영상

[이번 주 On .NET]에서는 Phillip Carter와 함께 F#에 대해서 얘기를 나누어 보도록 하겠습니다.

### 금주의 툴 -  I can has .NET Core
Octopus Deploy가 제공하는 유용한 웹 툴인 “I can has .NET Core” 은  NuGet 패키지와  GitHub 리포의 종속 그래프를 그려주며 또한 이를 통해서 참조하고 있는 라이브러리들 중 하나가 .NET Core 버전으로 마이그레이션되었을 경우 이를 알려줍니다. 그리고 이와 같이 교체 가능한  .NET Core 버전이 있을 경우 기존 참조하고있는 라이브러리의 교체를 제안해줍니다.

// 그림


### 금주의 패키지  - Warden
Warden은 웹사이트, API, CPU 등의 리소스를 쉽게 모니터링 할 수 있도록 도와주는 간단한 클로스 플랫폼 라이브러리입니다. 리소스를 모니터링 하는 감시자(watcher)들을 쉽고 빠르게 정의할 수 있으며  리소스 상태에 따라 notification 등을 구현함으로써 시스템을 다운시킬수있는 상황에 미리 대처해 할 수 있도록 도와줍니다.
//코드

### 금주의 게임 - Stardew Valley
Stardew Valley 는 오픈-앤드 형식의 농장 경영(country-life) 롤플레이 게임입니다.  플레이어는 농장생활에 필요한 약간의 도구, 돈 그리고  상속받은 농장을 운영하며 게임속의 인생을 진행하게됩니다. 어쩌면 단조롭고 따분할수있는 농장생활이지만 마을 사람들과  유대 관계를 맺고 커뮤니티 활동을 함으로서 또는  위험한 몬스터들과 강력한 무기, 다양한 보물들로 가득찬 방대하고 신비스러운 동굴을 탐색함으로서 아주 바쁜 시골 생활을 보낼수도 있습니다.  Stardew Valley는 일시적으로 플레이어의 기술을 향상시키거나 오일 메이커 , 용광로, 허수아비등의 아이템을  만드는데 사용할수있는 100가지가 넘는 조합의 기술도 제공하고 있습니다.

//그림

Stardew Valley는 XNA와 C#를 이용하여 Eric Barone (ConcernedApe)에서 제작 했으며 현재 Steam을 통해서 Windows, Mac OS X 에서 즐기실 수 있습니다. 

### .NET 소식
* Visual Studio “15” Preview 4 : John Montgomery가 Visual Studio “15” Preview 4버전을 소개했습니다.
* PowerShell on Linux and Open Source : Kenneth Hansen과  Angel Calvo이 Open Source로 제공되는 Linux 환경용PowerShell 을 소개했습니다. 
* GitHub Extension for Visual Studio 2.0 is now available : Andreia Gaita가 GitHub Extension for Visual Studio 2.0 버전 릴리즈 소식을 공유했습니다.
* GC pauses and safe points and Preventing .NET garbage collections with the TryStartNoGCRegion API : Matt Warren이 GC pauses 와 safe points에 대한 설명[링크]과  .NET의 GC 동작시 특정 코드 블록수행중에는 수집에서 제외되도록 제한 할수있는 TryStartNoGCRegion API에 대해 설명[링크]했습니다.
* An approach to building .NET Core apps using Bamboo and Cake : Matthew Abbott이 Atlassian 프레임워크의 Bamboo와 C# 컴파일/자동배포 시스템인 Cake을 이용한 .NET Core apps의 빌드 방법을 공유했습니다.
* Detecting and Setting Zoom Level in the WPF WebBrowser Control : Rick Strahl이 WPF WebBrowser Control의 Zoom 설정 방법및 zoom 값 변경시 이를 감지하는 방법을 공유했습니다.
* Wire – Writing one of the fastest .NET serializers : Roger Johansson이  Akka.NET의 serialize 엔진인 Wire의 구현 과정을 공유했습니다.
* Analysing Optimisations in the Wire Serialiser : Matt Warren이 Wire Serialiser를 이용한 최적화 에 대해서 설명했습니다.

### ASP.NET 소식
* Exploring the cookie authentication middleware in ASP.NET Core and How to set the hosting environment in ASP.NET Core : Andrew Lock이 ASP.NET Core 의 CookieAuthenticationMiddleware 클래스에  대한 설명과 ASP.NET Core 호스팅 환경 설정 대해서 설명했습니다.
* ASP.NET Core Basic Security Settings Cheatsheet : Nick Coblentz가 ASP.NET Core 프로젝트 진행시 알아야할 보안관련 항목을 정리하여 공유했습니다.
* Dependency Injection with .NET Core, Dependency Injection with Options, Configuration with .NET Core, Dependency Injection with Configuration, and Professional C# 6 : Christian Nagel이 .NET Core의 Dependency Injection[링크], Dependency Injection 옵션[링크], .NET Core Configuration [링크], Configuration 을 이용한 Dependency Injection [링크] 등의 설명과 자신이 집필중인 서적 Professional C# 6 의 소개를 공유했습니다.
* Netling, a load tester client : Tore Lervik이 웹 어플리케이션 로드 테스트 클라이언트인 Netling 대해서 소개했습니다.
* Looking At ASP.NET Core’s IApplicationLifetime : Khalid Abuhakmeh이  ASP.NET Core의  IApplicationLifetime 인터페이스에 대해서 설명했습니다
* Welcome Razor Pages : Hisham이 ASP.NET Core의 Page 기반 개발 프로그래밍 모델인 Razor Pages 오픈소스를 소개했습니다.
* The basics of publishing your .NET Core web app : Jon Hilton의  .NET Core web app의 기본적인 배포방법을 설명 했습니다.
* ASP.NET Core logging with NLog and SQL Server : Damien Bod이 ASP.NET Core에서 NLog 를 이용한 로깅 방법과 SQL Server의 연동 방법을 공유했습니다.
* Building a lightweight, controller-less, Markdown-only website in ASP.NET Core : Filip W이 특별한 설정및 구현 코드 없이도 간단하게 사용할 수 있는 마크다운 지원 ASP.NET Core 웹사이트 구현을 공유했습니다.
* ASP.NET MVC: Precompiling views : Gunnar Peipman이 ASP.NET MVC의 view에 대해서 설명했습니다.

### F# 소식
* Functional Programming with F#, a YouTube series : David Wilson이  F#의 Functional Programming기능에 대해서 소개했습니다.
* Basic Regression Tree, : Mathias Brandewinder가 기본 회귀분석 트리 구현에 대해서 설명했습니다.
* OOP in F# – How to define and implement classes, abstract classes and interfaces, : Kimserey Lam이 F#의 OOP 특징의 기능 및 구현에 대해서 설명했습니다.
* FAKE your way to ASP.NET Core on Azure WebApps, part 1 – The Problem, : Jakub Fijałkowski 가 Azure에 호스팅된  ASP.NET Core 웹 어플리케이션의 배포를 위한 FAKE 의 활용법을 소개했습니다.
* Fable |> React – Running a F# Sudoku solver everywhere, : Steffen Forkmann이 Fable과  React를 이용하여 Sudoku (스도쿠) 문제 해결 어플리케이션을  모바일 어플리케이션으로 변환한 과정을 소개했습니다.

### Xamarin 소식
* “Document All the Things” Contest Winners : Chris Hardy가  새롭게 진행되는 Stack Overflow의 아티클 관련 컨테스트를 소개했습니다.
* Webinar Recording | Continuous Everything: Why You Need Mobile DevOps : Courtney Witmer가 모바일 개발에서 DevOps 의 중요성을 소개했습니다.
* Continuous Integration for Android with Visual Studio Team Services : James Montemagno가 안드로이드 어플을 프로젝트 진행시 사용할 수 있는 VSTS(Visual Studio Team Services)의 활용방법을 소개했습니다.
* Preview: Xamarin Profiler 0.34.0 : Adrian Murphy가 Xamarin Profiler 0.34.0 를 소개했습니다.
* Xamarin.Forms E-Z Print : Matthew Soucoup이 Xamarin.Forms용 Print관련 라이브러리인 E-Z Print를 소개 했습니다.
* Yet Another Podcast #161 – David Britch : Jesse Liberty가 David Britch 와 인터뷰한 Podcast 를 공유했습니다.
* Prism for Xamarin.Forms 6.2 Release : Brian Lagunas가 Xamarin.Forms용 Prism 프레임워크 6.2 Release소식을 공유했습니다
* Announcing FreshMvvm 2.1 and 2.2 : Michael Ridland가 FreshMvvm 버전 2.1, 2.2을 소개했습니다.
* Latest Version of InTheHand.Core : Peter Foot이 오픈소스 프로젝트 InTheHand.Core의 최신 버전 소식을 공유했습니다.

### Games소식
* Developing for HoloLens with the Emulator : René Schulte가 에뮬레이터를 이용한 HoloLens용 어플리케이션 개발을 소개했습니다.
* Shaders Case Study – No Man’s Sky: Topographic Scanner (video) : Makin’ Stuff Look Good이 지형 탐색(스케닝)효과에 사용할 수 있는 Shader 활용 예를 소개 했습니다.
* [Unity 5] Tutorial: How to make a Circular (Pie) menu part 1 : [Unity 5] 학습-원형(파이형태)의 메뉴 만들기 파트1(링크)
* Hex Map 4: Irregulatity :Catlike Coding에서 퍼즐형 게임에 많이 활용되는 6각형 맵의 구현 및 활용 과정을 소개해 주셨습니다.[셀의 불규칙성]
* 1.3 Unity Tower defense tutorial – Map from text : inScope Studios에서 타워 디펜스 게임 구현 방법에 대해 설명했습니다.
* Unity and C# Tutorial 5 – Methods (video) : Craig Hinrichs가 C#을 이용한 Unity 프로그램 개발의 기초(메서드의 사용)를 설명했습니다.
* C# Monogame RPG Made Easy Tutorial 4 – (Recap)Xml Serialization (video) : CodingMadeEasy에서 Microsoft XNA framework 기반 게임 엔진인 MonoGame을 이용하여 RPG 게임을 구현하는 방법에 대해 설명하였습니다.



// 전무님 소개
