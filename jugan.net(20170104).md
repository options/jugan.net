주간닷넷 2017년 01월 04일

### On .NET 소식

[지난 주 On .NET]()(링크)에는 MVP 서밋에 참여한  Glenn Versweyveld와 함께 오픈소스 스트라바(Strava) 윈도우 클라언트 Kliva 에 대해서 얘기 나눈 인터뷰를 올려드렸습니다. 

이번주에도 역시  서밋에 참여한 MVP인 Reed Copsey와 함께 F# Software Foundation 에 대한 인터뷰 동영상을 공유할 예정입니다. 

### 금주의 패키지: Protobuf.NET
Protocol Buffers (혹은 짧게 Protobufs)는 구글에서 개발한 직렬화 포멧입니다. 간단하면서 쉽게 사용할수있고 성능또한 뛰어나서 개발자들의 많은 인기를 얻고있는 라이브러리입니다. 이미 구글의 C# 라이브러리(링크)에는 Protobufs을 지원하는 C#용 코드가 포함되어 있습니다. 하지만 Protobuf.NET 라이브러리는 구글의 기본 라이브러리와 다르게 DataContractSerializer 등과 같은 기존 의 .NET 직렬화 아키텍쳐와 잘 호환되게 설계되었으며 간단히 어프리뷰트를 적용함으로서 특정 직렬화 계약을 설정 할 수 있습니다. 어프리뷰트로 계약을 적용한후에 개발자가 작업하게되는 직렬화/역직렬화 코드 작업은 아주 간단합니다.

// 코드

// 코드

### 금주의 게임 : Arizona Sunshine

//그림
Arizona Sunshine은 VR환경을 기반으로한 1인칭 슈팅게임으로 세상의 종말이후의 상황을 게임의 배경으로 합니다. VR 해드셋을 단단히 고정하고 좀비들이 득실거리는 세계에서 맵을 탐색하고 적 좀비들과 싸우면서 생존 해야합니다. 게임 Arizona Sunshine는 25개가넘는 많은 무기체계와 다양한 맵을 포함하며 싱글모드와 멀티모드로 게임을 즐길수 있습니다.

//그림

Arizona Sunshine(링크)는 Vertigo Games(링크)와  Jaywalkers Interactive(링크)에서 C#(링크)과  Unity(링크)이용하여 개발되었습니다. Steam(링크) 통해서 HTC 바이브(Vive)와 오큘러스 리프트(Oculus Riftthe) 에서 즐기실 수 있습니다.

### .NET 소식
* Back to basics: string interpolation in C# : Rick Strahl이 C# 6.0 버전에 포함된 새로운 기능인 물자열 보간법을 설명했습니다.
* Not your grandad’s .net – Pipes Part 1, A faster lower allocation stream stack wielded for ALPN/TLS and… HTTP2 – Pipes Part 2, and The journey continues to Secure Pipelines, via OpenSsl – Pipes Part 3 : Tim Seaward가 SSL과 통신 보안에 관련된 시리즈 강좌  Part 1, Part 2, Part 3 을 게시했습니다.
* In-memory C# compilation (and .dll generation) using Roslyn : Joseph Woodward가 Roslyn 의 In-memory compilation 기능을 소개했습니다.
* .NET Posts – 2016 Year In Review : Joe Petrakovich가 자신의 2016 한해 블로깅 작업을 리뷰했습니다.
* Implementing the retry pattern in C# using Polly : Alastair Crabtree가 Polly를 이용한 retry 패턴구현 방법을 설명했습니다.
* Rx over the wire : Sacha Barber가 RX(Reactive Extensions) 기능을 네트워크 통신에 활용할 수 있는 확장 컴포넌트 기능을 소개했습니다.
* New release of my NATS client focusing on simplifying usage :  Daniel Wertheim가 NATS client를 좀더 쉽게 활용할 수 있게 해주는 MyNatsClient 오픈소스 프로젝트를 공유했습니다.

### ASP.NET 소식
* Building production ready Angular apps with Visual Studio and ASP.NET Core : Damien Bod가 VS에서 ASP.NET Core와 Angular를 이용한 어플리케이션 개발 방법을 설명했습니다.
* Introducing a new Markdown View Engine for ASP.NET Core : Hisham Bin Ateya가 마크다운 오픈소스엔진 MarkdownViewEngine(https://github.com/hishamco/MarkdownViewEngine)를 소개했습니다.
* Creating a WebSockets middleware for ASP.NET Core : Radu Matei가 ASP.NET Core에서 WebSockets middleware의 구현방법을 설명했습니다.
* How to enable gZip compression in ASP.NET Core : Talking DotNet에서 ASP.NET Core의 response에 gZip 압축 기능을 적용하는 방법을 설명했습니다.
* Change primary key for ASP.NET Core Identity and more : Thien Nguyen이 ASP.NET Core의 사용자 ID 의 데이터 타입 변경(기본 형식인 문자타입에서  숫자 타입으로)하는 방법을 설명했습니다.
* Content negotiation and custom formatter in ASP.NET Web API : Snesh Prajapati가 ASP.NET Web API에서 서버의 응답(문서) 형식이 사용자 포멧을 지원하도록 Content 타협 기능을 설정하는 방법을 설명했습니다.
* Create HTTP request pipeline using ASP.NET Core custom middleware: build/run on Mac, Windows, Linux or Docker container : Neal Pandey가  HTTP request pipeline을 지원하는 커스텀 middleware의 구현 방법과 구현된 서버를 Mac, Windows, Linux의 도커환경에 배포, 테스트 하는 방법을 설명했습니다. 
* In-memory caching in ASP.NET Core : Jignesh Trivedi가 ASP.NET Core의 In-memory 캐시 기능을 설명했습니다.

### F# 소식
* F# Software Foundation grows from over 200 members to over 1200 members since January of 2015 : F# Software Foundation의 2016년 현황이 공유되었습니다.
* F# Advent 2016 Gitbook – over 600 pages of F# Wisdom!, curated : Scott Wlaschin이 F# Advent 2016 (어드벤트 칼린더)형태의 무료 eBook을 공유했습니다.
* The magic of Type Providers : Roman Nevolin이 Type Provider의 장점을 소개했습니다.
* End to end F# with the Elm Architecture : Matthew Doig가 F#을 이용한 Web App개발시 적용할 수 있는  Elm Architecture에 대해서 설명했습니다.
* Azure Notebook in F# – creative way to share your notes beside the code : Michał Niegrzybowski가 F# 코드를 직접 실행할 수 있는 Azure Notebook을 소개했습니다.
* More simple mocking with object expressions : Jeremy Bytes가 F#의 object expression을 활용하여 좀더 효과적으로 모킹작업을 수행하는 방법을 설명했습니다.
* Suave Web Services : ASP.NET Monsters에서 F#과 Suave(https://suave.io/)을 이용해서  웹서비스를 구현하는 방법을 소개했습니다.

### Xamarin 소식
* Xamarin.Android – Entity Framework : Jon Douglas가 Xamarin.Android에서 Entity Framework을 활용하는 방법을 설명했습니다.
* Making It Snow! Xamarin.Forms and CocosSharp and Particles : Matthew Soucoup가  CocosSharp을 이용한 Xamarin.Forms에서 파티클 효과를 적용한 눈내리는 장면의 구현방법을 설명했습니다.
* Introduction to the Mobile Software Development Lifecycle : Xamarin에서 모바일 프로그램 개발에 관한 라이프사이클과 이에 관한 고려사항등을 정리했습니다. 
* Enabling TLS 1.2 in Xamarin.Android and Xamarin.iOS : Xamarin.Android와 Xamarin.iOS에서 TLS(Transport Layer Security) 1.2 를 사용하는 방법을 설명했습니다.
* An introduction to SkiaSharp : Xamarin에서 2차원 그래픽 엔진인 SkiaSharp 을 소개했습니다.
* Xamarin Show Snack Pack 5: Android Archive Manager for Visual Studio : James Montemagno가 시리즈  "Snack Pack 5: Android Archive Manager for Visual Studio" 동영상을 공유했습니다.
* Creating Tizen applications using Xamarin.Forms : Javier Suárez Ruiz가 Xamarin.Forms를 이용해서 타이젠 App를 구현하는 방법을 소개했습니다.
* Xamarin Forms pull to refresh with ListView : Adam Pedley가 Xamarin.Forms ListView 컨트롤의 refresh 관련 속성을 설명했습니다.
* Identifying users with HockeyApp : Tomasz Cielecki가 HockeyApp 기능에 사용자 id 정보를 추가하는 방법을 설명했습니다.
* Wrapping views in Xamarin.iOS : Marcos Cobeña Morián이 Xamarin.iOS에서 사용할 수 있는 일종의 Wrap view 형태의 오픈소스 컨트롤 MyWrappingView를 공유했습니다.

### Azure 소식
* Sharing code between Azure Functions : Jeremy Hutchinson이 Azure Function에서 코드를 공유하는 방법을 설명했습니다.
* My take on an Azure open source cross-platform DevOps toolkit – The beginning, a 12-part series : Bruno Terkaly가 Azure 오픈소스 툴킷 DevOps toolkit의 사용경험을 공유했습니다.

### Game 소식
* Game design deep dive: how Rogue Legacy handles tutorials without being boring : Teddy Lee가 게임 초보자를 위한 게임 튜토리얼을 어떻게 흥미있게 구성할 수 있는지 Rogue Legacy의 예를 들어서 설명했습니다.
* Ludum Dare 37 Results : Ludum Dare 37회 게임 개발 대회의 결과가 공유되었습니다.
* Unity: Blend trees are awesome! A quick tutorial! : TheoremGames에서 Unity의 Blend tree 개념을 설명했습니다.
* 16 highlights from 2016 on the Unity blog : Community Team에서 2016년의 주요 블로그 내용 16개를 공유했습니다.
* (SadConsole) Controls overview : Andy De George가 오슨소스 컨트롤 SadConsole을 소개했습니다.
* [Unity 5] Tutorial: How to make an inventory system – part 3 by Gamad에서 "[Unity 5] Tutorial" 시리즈 "인벤토리 시스템 구현" part 3 동영상을 공유했습니다.
* A* Pathfinding (E07: smooth weights) : Sebastian Lague가 그림상의 패스 경로를 파악하는 방법을 설명했습니다.

// 전무님 소개
