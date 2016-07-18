### On.NET 소식
[지난 On.NET 인터뷰]에서는  Mukul Sabharwal 를 모시고 검색엔진 Bing에서  .NET Core를 활용된 사례에 대해서 얘기해 봤습니다.

//영상 

[이번 On.NET 인터뷰]에서는 Lucas Meijer와 함께  Unity 기술에 대해서 같이 얘기해보려 합니다.

### 금주의 패키지- LinqToTwitterC
오픈소스라이브러리 LINQ to Twitter는 트위터의 트윗 내용을 LINQ 문법을 사용해서 검색할수있게 해주는 라이브러리입니다.

아래코드는 LinqToTwitter 을 이용하여 "LINQ to Twitter"에 대한 트위팅  검색 결과를 반환하는 예입니다.

//코드


### 금주의 게임 - Assault Android Cactus
Assault Android Cactus는 빠르게 게임이 전개되는 트윈 스틱 슈터(twin stick shooter) 형태의 게임 입니다. Assault Android Cactus 에서 플레이어는 자이언트 로봇이  포함된 적들과 전투를 해야하며 플레이어가 컨트롤하는 안드로이드의 베터리가 모두 소진되기전에 전투에서 승리해야 합니다. 안드로이드를 컨트롤하게될 플레이어는 총 9종류의 안드로이드중 하나를 선택할 수 있습니다.  각각의 안드로이드는 고유한 능력을 지니며 서로 다른 플레이 스타일을 필요로 합니다. Assault Android Cactus는 싱글 플레이어와 협동 플레이 모드( co-op 모드)를 지원합니다.

//그림

Assault Android Cactus는  Witch Beam Games에서 Unity게임엔진과 JavaScript, C#을 이용하여 개발되었습니다. 현재 Windows, Mac, Linux, Wii U 그리고 PlayStation 4에서 플레이가 가능하며 좀더 자세한 정보는  [Made With Unity] 페이지에서 확인하실 수 있습니다. 


### .NET 소식
* Where’s DNVM? Safely running multiple versions of the .NET Core SDK and Tooling with global.json : Scott Hanselman이 서로다른 여러 버전의 .NET Core SDK와 툴을 global.json을 사용하여 활용하는 하는 방법을 공유하였습니다.
* How the dotnet CLI tooling runs your code : Matt Warren이 dotnet CLI(Command Line Interface) 툴을 사용하여 사용자 코드를 실행 하는 방법을 소개 하였습니다. 
* Lucene.NET 4.8 is in beta – and we need your help! : 오픈소스 검색엔진인 Lucene.NET 4.8이 베타버전이 발표되었습니다.
* Step by step: .NET Core and Entity Framework Core : Carlos Mendible이  .NET Core환경에서 Entity Framework Core의 사용법을 가이드 해주었습니다.
* Use the Desktop Bridge to Bring Your Apps to UWP – Video : Rosshe Keantonc이 Desktop Bridge를 이용해서 기존의 데스크톱 어플리케이션을 UWP(Universal Windows Platform)로 전환 하는 방법을 설명하였습니다.
* LongRunning Is Useless For Task.Run With async-await : Bar Arnon이 Task.Run의 효과적인 사용법을 설명했습니다.
* Getting started with StructureMap in ASP.NET Core : Andrew Lock이 ASP.NET Core에서 IoC container의 하나인 StructureMap을 사용하는 방법을 소개해주었습니다.
* Deploy a Service Fabric Cluster to Azure with .NET Framework 4.6 (ARM template) : Andrej Medic이 Service Fabric Cluster 를 NET Framework 4.6 Azure 에 배포하는 방법을 소개해주었습니다.
* How to configure urls for Kestrel, WebListener and IIS express in ASP.NET Core : Andrew Lock이  ASP.NET Core에서 Kestrel 서버 환경 설정과 IIS express의 WebListener 환경설정에 대해서 설명했습니다.

### ASP.NET 소식
* Understanding Routing Precedence in ASP.NET MVC and Web API  : Rion Williams이 ASP.NET MVC의 Web API 환경에서 (웹 주소의) 라우팅 순서를 설명해 주었습니다.
* How to Master ASP.NET Core Web API Attribute Routing : Mobilemancer에서 ASP.NET Core Web API의  Attribute Routing에 대해서 설명했습니다.
* Adding parameters to the OpenID Connect Authorization URL : Jerrie Pelser이 OpenID Connect Authorization URL에 부가정보를 추가하는 방법에 대해서 설명했습니다.
* Issuing and authenticating JWT tokens in ASP.NET Core WebAPI – Part I : William Hallatt이 ASP.NET Core WebAPI 환경에서 JWT(JSON Web Token) 인증 토큰을 사용하는 방법을 설명하였습니다.
* How to continuously deploy a ASP.​NET Core 1.0 web app to Microsoft Azure : Jürgen Gutsch이 ASP.​NET Core 1.0 웹 어플리케이션을  Azure 클라우드에 자동 배포하는 방법을 설명하였습니다. 
* Securing ASP.NET Web API : Sovit Poudel이  ASP.NET Web API의 보안에 대해서 설명했습니다.

### F# 소식
* Continuous – F# IDE for the iPad : Frank Krueger이 iPad용 C#, F# IDE 를 소개 했습니다.
* Hacking Web Stuff with F# : Phil Trelford와 Tomas Petricek가 F#용 라이브러리인 Suave(F#용 윕서버)와 Fable( F#->자바스크립 전환 컴파일러)에 대해서 설명하였습니다.
* Getting Started with F# on .NET Core : Phillip Carter이 .NET Core와 .NET Core SDK 1.0 Preview 2를 이용하여 F#을 사용하는 법을 소개하였습니다.
* Referencing an F# library from C# on .NET Core : Gergely Kalapos이 C#에서  F# 라이브러리를 참조하는 방법을 공유하였습니다.

### Xamarin 소식
* What’s New in Xamarin.Forms – Video : James Montemagno이 최신 버전 Xamarin.Forms의 새로운 기능을 소개해 주었습니다.
* Using Xamarin Forms with .NET Standard : Oren Novotny이 .NET Standard를 이용하여 Xamarin Forms 프로젝트를 구성하는 방법을 설명하였습니다.
* .NET Standard Library with Xamarin Forms : Adam Pedley이 Xamarin Forms 프로젝트에서 기존의 PCL 프로젝트 대신 .NET Standard Library를 사용하고 구성하는 방법을 설명하였습니다.
* Unit testing with Xamarin.Forms’ DependencyService : Rob Gibbens이 Xamarin.Forms에서 기본적으로 제공되는 일종의 Service Locator인 DependencyService 의 사용법을 설명하였습니다.

* ### Games
* Unity 5 Tutorial: How to make a Crafting system like in Minecraft part 1 – Video, : Gamad가 마인크래프트 스타일 게임을 개발하는 방법을 소개하였습니다.
* Build Your First Game with MonoGame: Getting Started : Dean Ellis이 Microsoft’s XNA framework을 기반으로 한 게임엔진인 MonoGame을 이용한 게임구현 방법을 설명하였습니다.
* Unity 5 Swimming System and tutorial – Video : Jay AnAm이 Unity 5의 잠수/수영 효과 시스템의 사용법을 소개하였습니다.


//이사님 소개
