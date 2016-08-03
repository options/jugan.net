여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷](https://www.facebook.com/jugan.net/) 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 커뮤니티 소식
[Taeyo.NET](http://taeyo.net/)에서 http://docs.asp.net의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
* [Azure에 ASP.NET Core 웹 응용 프로그램 배포하기(VS)](http://www.taeyo.net/Columns/View.aspx?SEQ=548&PSEQ=39&IDX=0)
* [dotnet watch를 활용한 ASP.NET Core 응용 프로그램 개발](http://www.taeyo.net/Columns/View.aspx?SEQ=550&PSEQ=39&IDX=0)
* [나노 서버에 ASP.NET Core 응용 프로그램 배포하기](http://www.taeyo.net/Columns/View.aspx?SEQ=551&PSEQ=39&IDX=0)

### On.NET 소식
[지난 On.NET 인터뷰](https://youtu.be/voT4VhDboC4)에서는 Rowan Miller와 함께 EF Core(Entity Framework Core)에 대해서 이야기 나누어 보았습니다.

// Youtube 동영상 부분

이번 주 On.NET는 취소되었습니다. 다음 주부터는 다시 정상적으로 진행됩니다.

### 금주의 패키지 - OpenPop.NET
[OpenPop.NET](https://www.nuget.org/packages/OpenPop.NET/)은 POP3 클라이언트 기능과 강력한 MIME 파서를 포함한 C# 오픈 소스 프로젝트입니다. POP3 서버로부터 이메일을 받는 코드를 작성하는 경우 OpenPop.NET 라이브러리를 이용하면 몇 분 내로 구현할 수 있습니다.

아래 코드는 서버로부터 모든 이메일을 다운로드하는 예제 코드입니다.

// 코드

### 금주의 Xamarin 애플리케이션 - Continuous .NET 

iPad용 개발 IDE인 [Continuous .NET C# and F# IDE](http://continuous.codes/)를 이용하면 iPad에서 C#과 F# 애플리케이션을 개발할 수 있습니다. Continuous .NET은 코드 자동 완성 기능과 문법 체크 기능도 제공하며, 코드를 입력함에 따라 실시간으로 반응하는 output window 기능도 포함하고 있습니다.

// 그림

### 금주의 게임 - FRU
[FRU](http://frugame.com/)는 Xbox One에서 플레이할 수 있는 새로운 스타일의 퍼즐 게임입니다. 플레이어는 키넥트를 통해서 게임 화면에 자신의 실루엣을 투영시킬 수 있으며, 투영된 영상은 게임에서 퍼즐을 풀 수 있는 도구로 사용됩니다. 게임은 총 4개의 챕터로 구성되며 플레이어는 자신의 실루엣을 이용하여 게임 속의 다양한 물체들을 활성화 시키거나 피할 수 있습니다. 따라서 게임을 풀어나가기 위해서는 독특한 실루엣을 투영시켜야 할 필요가 있습니다.

// 그림

FRU는 [Unity](http://unity3d.com/)와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 개발되었습니다. FRU는 현재 Xbox One에서 플레이 하실 수 있습니다. 

### .NET 소식
* [[.NET Foundation] New Community Director, Rachel Rees](http://www.dotnetfoundation.org/blog/welcome-rachel) : Rachel Reese가 .NET Foundation 커뮤니티의 담당 이사를 맡게 되었습니다.
* [Developer Productivity in VS 2015 and VS 15 – [Video]](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Developer-Productivity-in-VS-2015-and-VS-15) : Kasey Uhlenhuth가 Visual Studio 2015 와 Visual Studio '15' 의 개발 생산성을 비교해 주셨습니다.
* [The Power of Global.json: Leveraging .NET Core Tooling Features](https://ievangelist.github.io/blog/the-global-json/) : David Pine이 .NET Core 용 Visual Studio 프로젝트에서 사용되는 Global.json을 소개해 주셨습니다.
* [Using C# to Create PowerShell Cmdlets: Beyond the Basics](https://www.simple-talk.com/dotnet/development/using-c-to-create-powershell-cmdlets-beyond-the-basics/) : Michael Sorens가 C#을 이용한 PowerShell Cmdlets의 구현 방법을 공유하였습니다. (Part 5)
* [.NET backward compatibility – Part 4](http://www.codeproject.com/Articles/1114286/NET-backward-compatibility-Part) :  Bastian Eicher가 Visual Studio NuGet packages의 .NET Framework 다중 버전 지원 설정 방법에 대해 설명하였습니다. (Part 4)
* [TPL: Producer Consumer Pattern – Thread Safe Queue Collection](http://www.codeproject.com/Articles/1112510/TPL-Producer-Consumer-Pattern-Thread-Safe-Queue-Co) : Ameet Parse가 생산자-소비자 시나리오에서 동시성 큐(Queue)를 사용해 Thread safe queue를 만드는 법을 소개해 주셨습니다.
* [Freezable Pattern](https://github.com/jbe2277/waf/wiki/Freezable-Pattern) : WPF에서 Race conditions을 방지하는 데 사용되는 Freezable Pattern에 대해 소개하고 있습니다.
* [Reducing allocations and resource usages when using Task.Delay](https://ayende.com/blog/174851/reducing-allocations-and-resource-usages-when-using-task-delay) : Ayende가 Task.Delay를 좀 더 효율적으로 사용하는 방법에 대해 소개해 주셨습니다.
* [Key Steps in Developing .NET Core Applications](https://blogs.msdn.microsoft.com/mvpawardprogram/2016/07/19/key-steps-in-developing-net-core-applications/) : Damir Dobric이 .NET Core용 애플리케이션 개발 방법을 가이드 해주었습니다.

### ASP.NET 소식
* [Status Code With Empty Response in ASP.NET Core](https://devblog.dymel.pl/2016/06/29/asp-net-core-status-code-empty-response/) : Michal이 ASP.NET Core 애플리케이션에서 클라이언트의 요청에 빈 컨텐츠를 반환해야 하는 경우 사용할 수 있는 개발 코드를 정리해 주셨습니다.
* [Return 401 Unauthorized From ASP.NET Core API](https://devblog.dymel.pl/2016/07/07/return-401-unauthorized-from-asp-net-core-api/) : Michal이 ASP.NET Core 애플리케이션에서 사용자 인증을 처리하는 방법을 설명해 주셨습니다.
* [Loading tenants from the database with SaasKit in ASP.NET Core](http://andrewlock.net/loading-tenants-from-the-database-with-saaskit-in-asp-net-core/) :  Andrew Lock이 ASP.NET Core 환경에서 오픈 소스 프로젝트인 SaasKit을 이용하여 데이터베이스 애플리케이션을 로드하고 구성하는 방법을 소개해 주셨습니다.
* [Service Discovery Patterns with ASP.NET Core](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) : Cecil Phillip이 Service Discovery Patterns 오픈 소스 프로젝트를 공유해 주셨습니다.
* [The Minimal ASP.NET Core App](http://ardalis.com/the-minimal-aspnet-core-app) : Steve Smith가 가장 간단한 ASP.NET Core 애플리케이션의 코드를 공유해 주셨습니다.
* [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/) : Ed Charbeneau가 ASP.NET Core 애플리케이션의 구성 방식 및 초기 시작 과정을 소개해 주셨습니다.
* [Build, ship and run ASP.NET Core on Microsoft Azure using Docker Cloud](http://laurentkempe.com/2016/07/18/Build-ship-and-run-ASP-NET-Core-on-Microsoft-Azure-using-Docker-Cloud/) : Laurent Kempé가 Docker Cloud를 이용해 ASP.NET Core 애플리케이션을 Microsoft Azure에 빌드, 배포 및 실행 방법을 소개해 주셨습니다.

### F# 소식
* [A Peek into F# 4.1](https://blogs.msdn.microsoft.com/dotnet/2016/07/25/a-peek-into-f-4-1/) : Phillip Carter가 F# 4.1에 추가된 주요 기능과 변경사항을 리뷰해 주셨습니다.
* [F# on .NET Core 1.0 RTM SDK Preview 2](https://www.youtube.com/watch?v=ufmlCL8IqmM) : Enrico Sada가 NET Core 1.0 RTM SDK Preview 2에서의 F#을 소개해 주셨습니다.
* [F#: Fixing Recursive-Induced Damage](https://bizmonger.wordpress.com/2016/07/23/f-fixing-recursive-induced-damage/) : Scott Nimrod가 F#에서 재귀함수를 이용할 때의 위험성을 최소화시키는 방법에 대해 공유해 주셨습니다.
* [Currying and Partial Application in F#](http://blog.guvweb.co.uk/2016/07/23/currying_in_fsharp/) : GuvBlog에서 함수형 언어인 F#의 특징을 소개해 주셨습니다.
* [Building a Poker Bot: Function Fold as a Decision Tree](http://mikhail.io/2016/07/building-a-poker-bot-functional-fold-as-decision-tree-pattern/) : Mikhail Shilkov이 포커게임 봇의 구현에 필요한 결정 트리(Decision Tree) 로직과 F# 예제 코드를 공유해 주셨습니다.

### Xamarin 소식
* [New Xamarin Dev Days Cities Announced!](https://blog.xamarin.com/new-xamarin-dev-days-cities-announced/) : Xamarin Dev Days 컨퍼런스가 열릴 도시가 선정되었습니다. 아쉽게도 한국, 중국, 일본은 포함되지 않았습니다.
* [Introducing Stack Overflow Documentation](https://blog.xamarin.com/introducing-stack-overflow-documentation/) : Craig Dunn이 Xamarin과 Microsoft가 새롭게 진행하는 Stack Overflow Documentation 프로젝트를 소개해 주셨습니다. Xamarin과 관련된 내요을 문서화 하는 프로젝트입니다.
* [Explore iOS 10, tvOS 10, watchOS 3, and macOS Sierra Previews Today](https://blog.xamarin.com/explore-ios-10-tvos-10-and-watchos-3-previews-today) : Miguel de Icaza가 iOS 10, tvOS 10, watchOS 3, 그리고 macOS Sierra Previews등 다양한 버전을 지원하는 Xamarin의 소개와 각 버전에 해당하는 Xamarin 개발 문서를 공유해 주셨습니다.
* [Effects with XAML](http://jesseliberty.com/2016/07/18/effects-with-xaml) : Jesse Liberty가 Xamarin.Forms 프로젝트에서 XAML을 이용해 만들 수 있는 effects를 소개해 주셨습니다.
* [Build C# and F# Apps on Your iPad with Continuous Mobile Development Environment](https://blog.xamarin.com/build-c-f-apps-on-your-ipad-with-continuous) : James Montemagno가 iPad용 개발 IDE인 Continuous .NET IDE를 이용해서 C#, F# 애플리케이션을 만드는 과정을 설명해 주셨습니다.
* [Xamarin Forms – View Model First Navigation](https://codemilltech.com/xamarin-forms-view-model-first-navigation) : Xamarin Forms에서 View Model을 구현하는 방법에 대해 소개해 주었습니다.

### Games
* [SadConsole – Version 3 Release](http://thraka.github.io/2016/07/13/version-3-release/) : Andy De George가 SadConsole 버전 3의 출시 소식을 공유해 주셨습니다.
* [Shaders Case Study – Stealth Games’ XRay Vision – [Video]](https://www.youtube.com/watch?v=OJkGGuudm38) : Makin’ Stuff Look Good에서 잠입 액션 게임에 사용될 수 있는 XRay 렌더링 기능을 공유했습니다.
* [Hex Map 1: Creating a Hexagonal Grid](http://catlikecoding.com/unity/tutorials/hex-map-1/) : Catlike Coding에서 퍼즐형 게임에 많이 활용되는 6각형 맵의 구현 및 활용 과정을 소개해 주셨습니다.
* [1.0 Unity Tower defense tutorial – Placing tiles – [Video]](https://www.youtube.com/watch?v=wS2LBCcnSQs) : inScope Studios에서 타워 디펜스 게임에 사용될 수 있는 기본 타일 정렬 방법 및 구성 방법을 가이드 해주었습니다.
* [Unity and C# Tutorial – Lesson Two – Statements – [Video]](https://www.youtube.com/watch?v=Aic0ae1eFZY) : Craig Hinrichs가 Unity와 C#을 사용하는 방법을 가이드 해주었습니다. (Lesson 2, 기본 문법)
* [C# Monogame RPG Made Easy Tutorial 1 – Introduction – [Video]](https://www.youtube.com/watch?v=agt9-J9RPZ0) : CodingMadeEasy에서 C#을 이용헤 RPG 게임을 만드는 과정을 공유해 주셨습니다. (첫 번째 시리즈)
* [Dynamically Resizing Colliders to Match Sprites in Unity](http://www.improxgames.com/blog/2016/7/1/tutorial-dynamically-resizing-colliders-to-match-sprites) : Improx Games에서 스프라이트 크기에 맞게 동적으로 Collider 크기를 재설정하는 방법에 대해 공유해 주셨습니다. (Collider : 충돌 기능을 담당하는 Unity 객체)

// 전무님 소개
