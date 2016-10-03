주간닷넷 2016년 9월 20일

### On .NET 소식
[지난 주 On .NET]()에는 David Morhovich, Zach Brown와 함께  마이크로 서비스 패턴 범용 툴킷인  Steeltoe에 대해서 얘기 나누어보았습니다.

// 동영상

[이번 주 On .NET]()에는  Sébastien Ros 와  .NET Core에서 실행되는 새로운 버전의 .NET CMS(Content Management System)툴인 Orchard 2(링크) 에 대해 알아보겠습니다.

### 금주의 패키지  -  C# Functional Extensions
C# functional extensions(링크)는 일반적으로 사용되는 함수사용 패턴들 예를들면 tuples, option types, monads, "declaration:var add = fun( (int x, int y) => x + y );"와 같이 좀더 쉬운 람다(Lambda)식의 표현 그리고 패턴 매칭등의 기능을 포함합니다. Agents간의 메시지 통신을 기반으로 한 얼랑(Erlang)과 비듯한 형태의 동시성도 역시 지원합니다.  

// 코드

### 금주의 게임 - Firewatch
Firewatch는 아름다운 그래픽의 스토리기반의 어드벤쳐 게임입니다. 게임 스토리의 시작은 단순한 화재 감시탑의 감시원 직원인 Henry가  드넓은 산속과 황야를 탐험하게되는 계기가 된 사건을 목격한 1989년데로 거슬거 올라갑니다.  자신의 보잘것 없는 생활을 정리하고 화재 감시원으로 살고있는 게임 케릭터 Henry는 와이오밍의 황무지를 탐험하며  게임이 진행  됩니다. 게임 중 외부와의 연락은 가능하지만 오로지 직장 상사 Delilah(데릴라)와만 가능하며 휴대용 무전기통해서 연락하며 서로 정보를 주고 받습니다.

//그림

Firewatch는 Unity와 C을 이용하여 Campo Santo에서 제작 했으며 현재 Steam과 Good Old Game을 통해서  PlayStation 4, Windows, Mac OS X 에서 즐기실 수 있습니다.  Xbox One 버전으로는 2016-09-21일 출시되었습니다.

### .NET 소식
* Self-contained .NET Core Applications : Scott Hanselman이 Self-contained  형식의  .NET Core Applications 개발 방법을 공유했습니다.
* Marten 1.0 is Here! : Jeremy D. Miller가 Marten 1.0 릴리즈 소식을 공유했습니다.
* Authenticode Signing Service and Client : Oren Novotny가 서명된 인증코드 서비스와 클라이언트를 설명했습니다.
* Creating Beautiful Effects for UWP : Michael Crump가 UWP(Universal Windows Platform)에서 활용할수있는 유용한 그래픽 효과를 설명했습니다.
* Subverting .NET Type Safety with ‘System.Runtime.CompilerServices.Unsafe’ (NSFW in a completely new sense of the term) and Compact strings in the CLR : Matt Warren이 System.Runtime.CompilerServices.Unsafe api의 설명(링크)과 CLR의 Compact strings 에 대해 설명(링크)했습니다.
* Use HiLo to generate keys with Entity Framework Core : Talking Dotnet에서 Entity Framework Core를 이용한 HiLo 패턴 키 생성에 대해 설명했습니다.
* Asynchronous Programming – Exception Handling : jbe2277이 비동기 프로그램에서의 예외처리에 대해 설명했습니다.
* A first look at Entity Framework Core with SQLite database on Ubuntu Linux : Võ Minh Trí가 Ubuntu Linux 에서  SQLite database , Entity Framework Core 의 활용법을 공유했습니다.
* Using PeerFinder from Console: Wi-Fi Direct data transfer in C# : PlasticSCM이  Wi-Fi Direct 기능을 이용하여 일반 콘솔 프로그램에서도 서로 파일을 공유할수있도록 해주는 PeerFinder 클레스의 사용 방법을 설명 했습니다.
* Graph Database with Neo4j and a .NET Client : Chris Skardon와 Michael Hunger가 Neo4j ,  .NET Client을 이용한 Graph Database의 구현을 설명했습니다

### ASP.NET 소식
* Custom ASP.NET Core Middleware Example : Mike Rousos가 ASP.NET Core Middleware의 커스터마이징 예를 소개했습니다.
* Peachpie: What Difference Does the ‘Core’ Make? : Benjamin Fistein이 ASP.NET 와 ASP.NET Core를 비교 설명했습니다.
* Configuring environment specific services in ASP.NET Core – Part 2, HTML minification using WebMarkupMin in ASP.NET Core, and Viewing what’s changed in ASP.NET Core 1.0.1 : Andrew Lock이 ASP.NET Core 에서 환경설정 서비스의 구현(링크), WebMarkupMin의 활용(링크), ASP.NET Core 1.0.1의 변경된 사항(링크)을 설명했습니다.
* ASP.NET Core with Angular2 – tutorial : Michał Dymel이 ASP.NET Core용 Angular2를 소개했습니다.
* Step by step: Serilog with ASP.NET Core and .NET Core and Microsoft Bot Framework : Carlos Mendible이 로그 라이브러리 Serilog 을 ASP.NET Core에서 활용하는 방법(링크)와 Microsoft Bot Framework을 .NET Core에서 활용하는 방법(링크)를 설명했습니다.
* AWS DynamoDB on .NET Core: Getting Started : Armen Shimoon이  .NET Core에서 AWS DynamoDB를 활용하는 방법을 공유했습니다.
* Bending ASP.NET Core MVC To Your Will : James Chambers가 ASP.NET Core MVC 프로젝트 구조와 MVC 동작 과정을 설명했습니다.
* Include user properties in IdentityServer4 with ASP.NET Identity : David Keller가 IdentityServer4 인증 서버 환경에서 ASP.NET Identity에  사용자 정의 속성을 추가하는 방법을 공유했습니다.
* Full Server logout with IdentityServer4 and OpenID Connect Implicit Flow : Damien Bowden이 OpenID와 IdentityServer4를 사용하는 환경에서 완전하게 로그아웃하는 방법(링크)을 설명하였습니다
* Getting started with EF Core + Sqlite + Asp.Net core Web api on Mac : Swaminathan Vetri가 Mac 에서EF Core ,  Sqlite,  Asp.Net core Web api를 이용한 활용방법을 소개했습니다
* Real-World CQRS/ES with ASP.NET and Redis Part 3 – The Read Model, Part 4 – Creating the APIs, and Part 5 – Running the APIs : Matthew Jones가 ASP.NET에서 CQRS(Command-Query Responsibility Segregation, 명령과 쿼리의 역할구분), ES(Event Sourcing) 패턴과 인메모리 데이터 베이스인 Redis 의 활용방법 (Part 3)(링크),  모델읽기(Part 4)(링크) , API 생성및 실행(Part 5)(링크)을 설명했습니다.  

### F# 소식
* Exploring StackOverflow [with F#], by Evelina Gabasova.
* Langston’s Ant in F#, : Ram이 F#으로 구현한 랭턴의 개미(Langton's Ant)  사례를 공유했습니다
* Programming UrhoSharp with F# : Xamarin의 UrhoSharp을 F# 프로젝트에서 활용하는 방법을 설명했습니다.
* Use apply and carry on, : Milosz Krajewski가 F# 언어 문법상  연산(파이프 연산자 |>) 실행 순서등을 설명했습니다.
* F# Series: Building Real-World Applications in F#, : Ody Mbegbu가 F# 언어를 소개했습니다.

### Xamarin 소식
* Major Updates: iOS 10, Android Nougat, and Other Tasty Bits : Miguel de Icaza가  iOS 10, Android Nougat 업데이트등의 소식을 공유했습니다.
* Xamarin Stable Release: Cycle 8 with iOS 10 and Xcode 8 Support and Xamarin Preview: Xamarin Profiler 0.34.1 : Adrian Murphy가 iOS 10,Xcode 8 을 지원하는 Cycle 8 버전 소식(링크)과Xamarin Profiler 0.34.1 프리뷰 버전 정보(링크)를 공유했습니다.
* Testing iOS 10 in Xamarin Test Cloud : John Lago가 Xamarin Test Cloud에서 iOS 10 어플의 테스트 방법을 설명했습니다.
* Introducing the Azure Track in Xamarin University : Bryan Costanich가 Xamarin University의 새로운 Azure 교육과정 을 소개했습니다.
* Preparing for Native Library Linking Changes in Android N and Preparing Machines for Xamarin Cycle 8 / iOS10 / Android N : James Montemagno가  Android N 버전의 Native 라이브러리 변경정보(링크)와 Xamarin Cycle 8 / iOS10 / Android N 개발 환경 설정 정보(링크)를 공유했습니다.
* Xamarin Podcast: iOS 10, iPhone 7, Apple Watch Series 2, and more!  : Pierce Boggan이 Xamarin 팟케스트 ( iOS 10, iPhone 7, Apple Watch Series 2) 를  공유했습니다.
* Yet Another Podcast #163: James Montemagno and Xamarin Cycle 8 : Jesse Liberty가 MS Xamarin team 메니저 James Montemagno와 Xamarin Cycle 8 를 주제로 팟케스트를 진행했습니다.
* VSTS September Extensions Roundup – App Stores!  : Joe Bourne가 VSTS  9월 업데이트 정보를 공유했습니다.
* Access a Control Method from a ViewModel : Adam Pedley가 MVVM 패턴을 사용할 경우  ViewModel에서 VIew의  Control에 접근하는 방법을 소개했습니다.
* Now Xamarin Devs can create Hololens Apps! : Bruno Capuano가 Xamarin에서 Hololens 플랫폼 개발이 지원된다는 소식을 공유했습니다.
* LoaderViewXamarin – Loading animations for Android TextView and ImageView elements : Martijn van Dijk가 TextView, ImageView 요소에 에니메이션을 실행할수있게 해주는 오픈소스라이브러리 LoaderViewXamarin 을 소개했습니다.

### Azure 소식
* Serving Static Content From Azure Storage: Content Delivery Network Setup : Doug Vanderweide가 Azure Storage에 정적 컨텐츠를 설정하는 방법을 설명했습니다.

### Games 소식
* MonoGame – Building multi-platform solutions :  Simon Jackson이 멀티 플랫폼 게임 개발 도구인 Monogame 을 소개했습니다
* Tutorial – Zelda style screen transitions in Unity : Unity 에서 2D 수직/수평 스크롤 스타일로 이동하는 방법을 공유했습니다.
* Seeing Is Deceiving: Your Brain and VR : crytek에서 VR 효과를 뇌가 이해하는 과정을 설명했습니다.
* Episode 22: MonoGame (video) : Katie Stone Perez가 MonoGame 개발 방법을 공유했습니다.
* Unity: In Beta – Animation Window Workflows : Will Goldstone이  Unity 5.5 beta의 향상된 Animation Window Workflows 기능을 소개했습니다.
* Curated #UnityTips No. 13 : DevDog가 Unity 개발에 도움이 될수있는 Tip 정보를 공유했습니다.
* Unity: Make the Camera Follow a Player (or any GameObject) Smoothly and Fluidly : Kyle W. Banks가 플레이어(혹은 게임객체)를 따라다니는 카메라 시각 효과의 구현 방법을 설명했습니다.
* Unity: Terrain Generation Part 1(2)- Viking Game #2 (video) : System Cult에서 게임에 사용될 지형생성 방법을 설명했습니다.


// 전무님 소개
