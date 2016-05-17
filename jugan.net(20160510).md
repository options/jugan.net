 이번주에는 개발자들에게는 없어서는 안되는 소중한 페이지인 [Stack Overflow 의 배포과정](https://nickcraver.com/blog/2016/05/03/stack-overflow-how-we-do-deployment-2016-edition/)이 소개되었으니 꼭 한번 읽어보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.
 
### On.NET 소식
[지난번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=IvJAwKW28-w)는 Andy De George 와 함께 MonoGame 3.4 기반의 게임 라이브러리인 [SadConsole](https://github.com/thraka/sadconsole/) 에 대해서 이야기 나누었습니다. SadConsole 에서 제공하는 엔진을 이용하여 어릴적 즐겨하던 명령 프롬프트창 스타일의 게임을 시뮬레이션 해보실 수 있습니다. 

### 금주의 포스트 - Stack Overflow, How we do deployment
이번주는 아주 특별한 포스트를 소개해 드리려고 합니다. Stack Overflow 에 근무하시는 [Nick Craver](https://nickcraver.com/) 께서 [Stack Overflow 의 배포 방식](https://nickcraver.com/blog/2016/05/03/stack-overflow-how-we-do-deployment-2016-edition/)을 상세하게 포스팅 하였습니다. IT 업계에 종사하시는 분이라면 꼭 읽어보셔야할 포스팅으로, 배포 과정이 상세하게 소개되었기 때문에 시간적인 여유를 가지고 읽어 보시기 바랍니다. 참고로 Nick 은 약 한달전에 [Stack Overflow 의 성능에 대해 On.NET 유투브의 동영상 인터뷰](https://www.youtube.com/watch?v=DJn8-Psznsw)를 진행했습니다.

### 금주의 툴 - Git Diff Margin
[Git Diff Margin](https://visualstudiogallery.msdn.microsoft.com/cf49cf30-2ca6-4ea0-b7cc-6a8e0dadc1a8) 도구는 사용자가 편집하고 있는 문서의 Git 버전 변화를 Visual Studio 의 여백 및 스크롤 바 부분에 실시간으로 보여주는 Visual Studio 확장 도구입니다. 또한 Visual Studio Git 소스제어 기능 중 하나인 Pending Changes 간의 탐색 기능을 이용하여 이미 작업한 부분을 쉽게 되돌릴 수 있습니다. 

//코드

### 금주의 프로젝트 - Intercom-dotnet
[Intercom](https://www.intercom.io/) 은 웹 사이트의 방문객들과 실시간으로 채팅하고, 피드백을 받으며 고객을 지원하는 통합 서비스 도구입니다. [Intercom-dotnet](https://github.com/intercom/intercom-dotnet) 클라이언트 라이브러리을 이용하면 Intercom 사용자 정보에 .NET 애플리케이션이 접근 할 수 있습니다.

### 금주의 Xamarin 애플리케이션 - JetBlue
JetBlue 항공사는 eGate Solutions 과 Xamarin 을 이용하여 비행기 내부에서 사용하는 디바이스들을 iOS 와 안드로이드로 바꾸었습니다. 이로써 신용카드 트랜잭션 과정에서 종종 발생하던 동기화 문제를 해결하였습니다. JetBlue 의 승무원들은 애플리케이션을 이용하여 비행기 안에서 판매하는 상품의 재고 관리 및 결재 진행을 보다 편리하게 할 수 있게 되었습니다. 

//이미지  

### 금주의 게임 - Endless Legend
이번주 소개해 드릴 게임은 [Endless Legend](http://madewith.unity.com/games/endless-legend) 입니다. Endless Legend 는 전형적인 [4X(eXplore, eXpand, eXploit, eXterminate)](https://en.wikipedia.org/wiki/4X) 전략/RPG 게임으로 플레이어는 8개 종족(DLC:Download Contents일 경우 11개 종족)중 하나의 종족을 선택해서 게임을 진행하게 됩니다. 각각의 종족은 서로 다른 개성있는 스타일과 스토리 라인을 가지고 있습니다. 매번 게임이 시작될 때 마다 지도와 퀘스트가 무작위로 생성되기 때문에 플레이어는 지루할 겨를이 없이 언제나 새로운 화면에서 게임할 수 있습니다. Endless Legend 의 그래픽은 매우 훌륭하여 게이머가 정말 아름답다고 느낄 정도입니다(실제 이 게임의 테스터는 계속 맵을 확대 축소 하면서 그래픽을 감상했다고 합니다). 게이머는 계절 변화에 적응하고 생존하기 위해 4X : 확장하고, 탐헙하고, 자원을 캐고, 그리고 전투를 지속적으로 해야합니다. 처음에는 약간의 학습이 필요한 게임이지만 어느정도 익숙해진 후에는 시간가는 줄 모르고 게임을 즐기시게 될 겁니다.

Endless Legend 는 [Amplitude Studios](http://madewith.unity.com/profiles/amplitude-studios) 에서 [Unity](http://unity3d.com/) 와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners) 을 이용해서 개발되었으며 스트림 서비스를 이용하여 Mac 과 Windows 에서 즐기실 수 있습니다. 좀더 자세한 정보는 [Made With Unity](http://madewith.unity.com/games/endless-legend) 페이지에서 확인하실 수 있습니다. 

//이미지  

### .NET 소식
* [.NET Core RC2 – Improvements, Schedule, and Roadmap](https://blogs.msdn.microsoft.com/dotnet/2016/05/06/net-core-rc2-improvements-schedule-and-roadmap/) : Scott Hunter 가 .NET Core 의 RC2 버전 출시 소식을 소개했습니다.
* [Infographic: Who is the .NET Developer of 2016?](http://www.telerik.com/blogs/infographic-the-dotnet-developer-of-2016) : Nora Georgieva 가 1000명 이상의 닷넷 개발자들을 대상으로 실시한 "2016 .NET Developer Community Report" 설문 조사의 결과를 공유했습니다.
* [Welcoming WiX Toolset to the .NET Foundation](http://www.dotnetfoundation.org/blog/wix-toolset-welcome) : Martin Woodward 가 윈도우용 설치 엔진인 WiX Toolset 이 .NET Foundation 의 새로운 멤버가 되었다는 소식을 전했습니다.
* [Introduction to .NET Framework Compatibility](https://blogs.msdn.microsoft.com/dotnet/2016/05/02/introduction-to-net-framework-compatibility/) and [Tooling to Facilitate Framework Migrations](https://blogs.msdn.microsoft.com/dotnet/2016/05/05/tooling-to-facilitate-framework-migrations/) : Mike Rousos 가 .NET Framework 버전간 호환성에 대한 개요와 .NET Framework Migration 시 도움이 되는 도구를 소개했습니다.
* [Using Mocks or Stubs, Revisited](https://jeremydmiller.com/2016/05/05/using-mocks-or-stubs-revisited/) : Jeremy D. Miller 가 테스트 용도로 사용되는 객체인 Mocks 과 Stubs 의 차이점을 예제와 함께 소개했습니다. 
* [Diving into Visual Studio 2015: Code Analyzers](http://www.codeproject.com/Articles/1098380/Diving-into-Visual-Studio-Day-sharp-Code-Analyzers) : Akhil Mittal 가 Visual Studio 2015 의 코드 분석기가 작동하는 원리를 소개했습니다.
* [Continuing with C# and Nats, now looking at NatsObservable](http://danielwertheim.se/continuing-with-c-and-nats-now-looking-at-natsobservable/) : Daniel Wertheim 이 NatsObservable 클래스를 소개했습니다. 
* [Arithmetic Overflow in .NET – Some Nitty Gritties](http://www.codeproject.com/Articles/1097872/Arithmetic-Overflow-and-Underflow-in-Net-Some-knit) : Rasik Bihari Tiwari 이 .NET 에서 산술적 Overflow 가 발생할 경우의 예외처리 방법을 소개했습니다.
* [Versioning NuGet packages in a continuous delivery world: part 1](https://blogs.msdn.microsoft.com/visualstudioalm/2016/05/03/versioning-nuget-packages-cd-1/) : Matt Cooper 이 NuGet 패키지의 버전관리 방법을 소개했습니다.

### ASP.NET 소식
* [Notes from the ASP.NET Community Standup – May 3, 2016 (video + transcript)](https://blogs.msdn.microsoft.com/webdev/2016/05/09/notes-from-the-asp-net-community-standup-may-3-2016/) : Jeffrey T. Fritz 가 지난 ASP.NET Community Standup 행사에서 있었던 내용을 정리했습니다.
* [Deploying ASP.NET Core with Docker Swarm to Azure Container Service](http://anthonychu.ca/post/aspnet-core-azure-container-service/) : Anthony Chu 가 Docker Swarm 을 이용하여 Azure Container Service 에 ASP.NET Core 를 배포하는 방법을 공유하였습니다. 
* [Working with Developer Pages (video)](https://channel9.msdn.com/Series/aspnetmonsters/Episode-29-Working-with-Developer-Pages) : ASP.NET Monsters 에서 ASP.NET Core 에서 개발할 때에 기본 템플릿 페이지를 다양하게 응용하는 방법을 소개했습니다. 
* [ASP.NET Core: Factory Pattern Dependency Injection](http://dotnetliberty.com/index.php/2016/05/09/asp-net-core-factory-pattern-dependency-injection/) : Armen Shimoon 이 ASP.NET Core 환경에서 Factory Pattern 을 이용한 DI(Dependency Injection, 의존성 주입)을 소개했습니다.
* [Build an ASP.NET Core Application With User Authentication](https://stormpath.com/blog/asp-net-core-authentication) : Nate Barbettini 가 ASP.NET Core 에서 사용자 인증을 구현하는 방법을 자세히 소개했습니다.
* [How to Web with ASP.NET](http://developer.telerik.com/featured/how-to-web-asp-net/) : Jeremy Likness 가 ASP.NET Core 를 이용하여 프로젝트를 진행할 때 적절한 개발 스택을 선택하는 방법을 소개하였습니다. 
* [Tag Helpers in ASP.Net Core (video)](https://channel9.msdn.com/Shows/Web-Hack-Wednesday/Tag-Helpers-in-ASPNet-Core) : Martin Beeby 과 Martin Kearn 이 ASP.NET Core 의 새로운 기능인 Tag Helpers 를 설명했습니다.
* [WebForms can Gulp too](https://blogs.msdn.microsoft.com/webdev/2016/04/29/webforms-can-gulp-too-using-node-tools-with-asp-net-webforms/), [Where did my bundles go in ASP.NET Core?](http://www.jeffreyfritz.com/2016/04/fritzs-10-minute-tips-where-did-my-bundles-go-in-asp-net-core/), and [npm and Gulp part 2 (video)](http://www.jeffreyfritz.com/2016/05/fritzs-10-minute-tips-npm-and-gulp-part-2/) : Jeffrey T. Fritz 가  WebForms 에서 Gulp 를 사용하는 방법과 ASP.NET Core 에서 사용가능한 웹 개발 도구 및 npm, Gulp 이용 팁을 공유했습니다.

### F# 소식
* [Types from Data: Making Structured Data First-Class Citizens in F#](http://tomasp.net/academic/papers/fsharp-data/) : Tomas Petricek, Gustavo Guerra, 그리고 Don Syme 가 데이터 접근 라이브러리인 F# Data 를 소개했습니다. 
* [Akka.NET Streams vs Hopac (vs AsyncSeq – Sort Of)](http://vaskir.blogspot.com.by/2016/05/akkanet-streams-vs-hopac.html) : Vasily Kirichenko 가 Akka.NET 과 Hopac 을 비교하고 어떤 경우에 각각의 기술을 이용하면 좋은지 소개했습니다. 
* [Let’s Make a Bayesian Deal](http://jackfoxy.com/lets-make-a-bayesian-deal/) : Jack Fox 이 유명한 확률문제인 "몬티 홀 문제(Monty Hall problem)"를 F# 을 이용해 해결하는 과정을 보여줬습니다. 

### Games
* [CRYENGINE V 의 C# 튜토리얼 – Collectables 추가하기 (video)](https://www.youtube.com/watch?v=UATgHGheacA), [CRYENGINE V 에서 Scratch C# 튜토리얼 (video)](https://www.youtube.com/watch?v=4u-_a41trHY), and [CRYENGINE V 에서 C# 을 이용한 3D 미로찾기 (video)](https://www.youtube.com/watch?v=Cf1FPbAhcPE) : James Brady 가 게임 개발 엔진인 CRYENGINE V 튜토리얼을 소개했습니다.
* [Build A Unity Game Part 1 (video)](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Build-A-Unity-Game-Part-1) : Stacey Haffnerrk 가 Unity 개발 환경에서 게임의 배경을 만들고, Visual Studio 의 스크립트를 작성하는 방법 등을 소개했습니다. 

//송기수 이사님 소개 