여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.
금주의 커뮤니티 소식
Taeyo.NET에서 http://docs.asp.net의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
• [ASP.NET Core 보안 : 클레임 기반 권한부여]( http://taeyo.net/Columns/View.aspx?SEQ=582&PSEQ=39)
• [ASP.NET Core 보안 : 역할 기반 권한부여]( http://taeyo.net/Columns/View.aspx?SEQ=581&PSEQ=39)
### On .NET 소식

[지난 주 ON.NET]( https://channel9.msdn.com/Shows/On-NET/Glenn-Versweyveld-Kliva)에서는 MVP Summit에서 만난 Glenn Versweyveld와 함께 윈도우용 오픈소스인 Strava 클라이언트에 관해 이야기 나누었습니다.

[이번 주 ON.NET]( https://channel9.msdn.com/Shows/On-NET/Reed-Copsey-Jr-F-Software-Foundation)에서는 [F# 소프트웨어 재단]( http://fsharp.org/)의 수석 이사인 Reed Copsey, Jr과 함께 재단에서 진행하는 멘토링 및 발표자 프로그램에 관해 이야기 나누어보겠습니다.

### 금주의 패키지: Protobuf.NET
[Protocol Buffers]( https://developers.google.com/protocol-buffers/) (혹은 짧게 Protobufs)는 구글에서 개발한 직렬화 포맷입니다. 간단하면서 쉽게 사용할 수 있고 성능도 뛰어나서 개발자들에게 많은 인기를 얻고 있는 라이브러리입니다.
이미 [구글의 C# 라이브러리]( https://developers.google.com/protocol-buffers/docs/csharptutorial)는 Protobufs 사양에서 C# 코드를 생성하고 있습니다. 하지만 [Protobuf.NET 라이브러리]( https://github.com/mgravell/protobuf-net)는 구글의 기본 라이브러리와 다르게 DataContractSerializer 처럼 기존 .NET 직렬화 아키텍처와 잘 호환되게 설계되었으며, 간단히 어프리뷰트를 적용함으로써 특정 직렬화 계약을 설정할 수가 있습니다.
어프리뷰트로 계약을 적용한다면 개발자가 역 직렬화 또는 직렬화 코드 작업을 아주 간단하게 처리할 수 있습니다. 

//코드

// 코드

### 금주의 게임 : Arizona Sunshine

//그림
[Arizona Sunshine]( http://www.arizona-sunshine.com/)은 VR 환경의 1인칭 슈팅게임으로 세계 종말 이후를 배경으로 하고 있습니다.
VR 헤드셋을 착용하고 좀비들이 득실거리는 광야에서 생존을 위한 미션을 수행하세요! Arizona Sunshine은 VR 환경의 실감 나는 움직임과 탐험을 즐길 수 있는 여러 환경 그리고 25가지 이상의 무기로 경험해보지 못한 스릴을 느끼실 수가 있습니다. 또한, 풀 사이즈의 싱글 플레이어 캠페인 및 협동 멀티 플레이 모드를 선택하여 플레이할 수 있습니다.
//그림

[Arizona Sunshine]( http://www.arizona-sunshine.com/)는 [Vertigo Games]( http://vertigo-games.com/)와 [Jaywalkers Interactive]( http://jaywalkersinteractive.com/)에서 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)과 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2017/01/04/the-week-in-net-on-net-with-glenn-versweyveld-protobuf-net-arizona-sunshine/unity3d.com)로 개발하였으며, [Steam]( http://store.steampowered.com/app/342180/) 통해서 HTC 바이브(Vive)와 오큘러스 리프트(Oculus Riftthe)에서 즐기실 수 있습니다.

### .NET 소식
* Back to basics: string interpolation in C# : Rick Strahl이 C# 6.0 버전에 포함된 새로운 기능인 String Interpolation에 관해 설명합니다.
* Not your grandad’s .net – Pipes Part 1, A faster lower allocation stream stack wielded for ALPN/TLS and… HTTP2 – Pipes Part 2, and The journey continues to Secure Pipelines, via OpenSsl – Pipes Part 3 : Tim Seaward가 자신의 블로그에 SSL과 통신 보안에 관련된 세편의 시리즈 강좌를 게시했습니다.
* In-memory C# compilation (and .dll generation) using Roslyn : Joseph Woodward가 Roslyn의 In-memory compilation기능에 관해 소개합니다.
* .NET Posts – 2016 Year In Review : 소프트웨어 엔지니어이자 기술 도서 저자인 Joe Petrakovich가 반년동안 .NET에 관한 글을 쓰면서 느낀 점을 공유하였습니다.
* Implementing the retry pattern in C# using Polly : Alastair Crabtree가 애플리케이션의 안정성을 향상시킬 수 있는 retry 패턴을 Polly로 구현하는 방법에 관해 설명합니다.
* Rx over the wire : Sacha Barber가 연속되는 데이터를 다루는데 특화된 RE(Reactive Extensions) 오픈소스 라이브러리를 예제를 통해 소개합니다.
* New release of my NATS client focusing on simplifying usage : Daniel Wertheim가 NATS client를 더욱 쉽게 활용할 수 있게 해주는 MyNatsClient 오픈소스 프로젝트를 공유했습니다.

### ASP.NET 소식
* Building production ready Angular apps with Visual Studio and ASP.NET Core : Damien Bod가 VS에서 ASP.NET Core와 Angular를 이용한 애플리케이션 개발 방법을 소개합니다.
* Introducing a new Markdown View Engine for ASP.NET Core : Hisham Bin Ateya가 마크다운 오픈소스 엔진에 관해 소개합니다.
* Creating a WebSockets middleware for ASP.NET Core : Radu Matei가 ASP.NET Core에서 WebSockets middleware를 구현하는 방법을 소개합니다.
* How to enable gZip compression in ASP.NET Core : Talking DotNet에서는 ASP.NET Core에서 gZip 압축을 활성화하는 방법에 관해 설명합니다.
* Change primary key for ASP.NET Core Identity and more : Thien Nguyen이 ASP.NET Core의 사용자 ID 데이터 타입을 변경하는 방법에 관해 설명합니다.
* Content negotiation and custom formatter in ASP.NET Web API : Snesh Prajapati가 ASP.NET Web API에서 서버 응답 형식이 사용자 포맷을 지원하도록 Content 타협 기능을 설정하는 방법에 관해 설명합니다.
* Create HTTP request pipeline using ASP.NET Core custom middleware: build/run on Mac, Windows, Linux or Docker container : Neal Pandey가 HTTP request pipeline을 지원하는 Custom Middleware 구현 방법과 구현된 서버를 Mac, Windows, Linux의 도커 환경에 배포, 테스트하는 방법을 공유하였습니다.
* In-memory caching in ASP.NET Core : Jignesh Trivedi가 ASP.NET Core의 In-memory 캐시 기능에 관해 설명합니다.

### F# 소식
* F# Software Foundation grows from over 200 members to over 1200 members since January of 2015 : F# 소프트웨어 재단의 2016년 활동내역이 공개되었습니다.
* F# Advent 2016 Gitbook – over 600 pages of F# Wisdom!, curated : Scott Wlaschin이 F# Advent 2016 (어드벤트 칼린더)형태의 무료 eBook을 공유했습니다.
* The magic of Type Providers : Roman Nevolin이 Type Provider의 장점을 소개합니다.
* End to end F# with the Elm Architecture : Matthew Doig가 F#을 이용한 Web App개발시, 적용할 수 있는 Elm Architecture에 관해 설명합니다.
* Azure Notebook in F# – creative way to share your notes beside the code : Michał Niegrzybowski가 F# 코드를 웹앱에서 실행할 수 있는 Azure Notebook에 관해 소개합니다.
* More simple mocking with object expressions : Jeremy Bytes가 F#의 object expression을 활용하여 더욱 효과적으로 모킹작업을 수행하는 방법에 관해 설명합니다.
* Suave Web Services : ASP.NET Monsters에서 F#과 Suave(https://suave.io/)을 이용해 웹서비스를 구현하는 방법에 관해 소개합니다.

### Xamarin 소식
* Xamarin.Android – Entity Framework : Jon Douglas가 Xamarin.Android에서 Entity Framework을 활용하는 방법을 소개합니다.
* Making It Snow! Xamarin.Forms and CocosSharp and Particles : Matthew Soucoup가 Xamarin.Forms에서 CocosSharp을 이용해 눈 내리는 파티클을 구현하는 방법에 관해 설명합니다.
* Introduction to the Mobile Software Development Lifecycle : Xamarin 팀에서 모바일 애플리케이션과 관련된 소프트웨어 개발 라이프 사이클에 대해 설명하고 모바일 프로젝트를 구축할 때 몇가지 고려사항에 대해 소개합니다.
* Enabling TLS 1.2 in Xamarin.Android and Xamarin.iOS : Xamarin.Android 또는 Xamarin.iOS에서 TLS(Transport Layer Security) 1.2를 사용하는 방법에 관해 설명합니다.
* An introduction to SkiaSharp : Xamarin에서 2D 엔진인 SkiaSharp에 관해 소개합니다.
* Xamarin Show Snack Pack 5: Android Archive Manager for Visual Studio : James Montemagno가 연재하는 Xamarin Show Snack의 5번째 시리즈가 업로드되었습니다.
* Creating Tizen applications using Xamarin.Forms : Javier Suárez Ruiz가 Xamarin.Forms으로 타이젠 애플리케이션을 구현하는 방법을 소개합니다.
* Xamarin Forms pull to refresh with ListView : Adam Pedley가 Xamarin.Forms ListView 컨트롤에서 맨 위에서 아래로 당겨 새로 고침하는 명령을 다른 명령으로 조작하는 방법에 관해 설명합니다.
* Identifying users with HockeyApp : Tomasz Cielecki가 HockeyApp 기능에 사용자 ID 정보를 추가하는 방법에 관해 설명합니다.
* Wrapping views in Xamarin.iOS : Marcos Cobeña Morián이 C#으로 구현한 Xamarin.iOS용 랩뷰 ‘MyWrappingView ‘를 GitHub에 공유하였습니다.

### Azure 소식
* Sharing code between Azure Functions : Jeremy Hutchinson이 Azure Function에 코드를 공유하는 방법을 소개합니다.
* My take on an Azure open source cross-platform DevOps toolkit – The beginning, a 12-part series : Bruno Terkaly가 Azure 오픈소스 툴킷인 ‘DevOps toolkit’의 사용담을 공유했습니다.

### Game 소식
* Game design deep dive: how Rogue Legacy handles tutorials without being boring : Teddy Lee가 게임 튜토리얼을 어떻게 흥미있게 구성할 수 있는지 Rogue Legacy의 예를 들어 설명합니다.

* Ludum Dare 37 Results : Ludum Dare 37의 게임 결과가 공개되었습니다.
* Unity: Blend trees are awesome! A quick tutorial! : TheoremGames에서 Unity의 Blend tree 개념을 설명합니다.
* 16 highlights from 2016 on the Unity blog : Community Team에서 하이라이트 블로그 포스팅 16개을 공개하였습니다.
* (SadConsole) Controls overview : Andy De George가 오픈소스 컨트롤인 SadConsole에 관해 소개합니다.
* [Unity 5] Tutorial: How to make an inventory system – part 3 : Gamad에서 연재하는 [Unity 5] Tutorial 시리즈의 “인벤토리 시스템 구현”편 3번째 파트가 게시되었습니다.
* A* Pathfinding (E07: smooth weights) : Sebastian Lague가 상자 흐림 효과를 지형도에 적용하여이미지의 패스 경로를 더욱 자연스럽게 파악하는 방법에 관해 소개합니다.

// 전무님 소개
