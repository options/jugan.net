### On.NET 소식
[지난 On.NET 인터뷰](https://youtu.be/dz-O3vcSq_U)에서는 On.NET 인터뷰의 첫 번쨰 초대손님이었던 Miguel de Icaza 를 모시고 이야기 나누었습니다.

// 동영상 추가 

[이번 주 On.NET 인터뷰](https://www.youtube.com/watch?v=Ue8D1ga1Nhw)에서는 Maoni Stephens 를 모시고 .NET 의 가비지 컬렉션에 대해 이야기 나누어 보려고 합니다.

### 금주의 패키지- Math.NET Symbolics
Math.NET 아주 훌륭한 프로젝트입니다. 이미 [몇 주전 주간닷넷에서 Math.NET 의 수치연산 라이브러리](https://blogs.msdn.microsoft.com/eva/?p=8495)를 소개해 드린적이 있습니다. 오늘은 Math.NET 에서 수학기호를 표현하고 다룰 수 있게 도와주는 Symbolics 라이브러리를 소개합니다. Symbolics 라이브러리를 이용하면 수학기호를 분석하고 파싱할 수 있으며, 수학 기호의 포맷을 적용하고 표현식을 계산하실 수 있습니다. 또한, 기호를 추가 개발하거나, 단순화하고, 차별화 하는 등의 커스터마이징도 가능합니다.

아래의 예제는 기호 미분(symbolic differentiation)를 이용하여 주어진 각의 테일러 전개식(Taylor expansion)을 표현하였습니다.
 
//코드

### 금주의 Xamarin 애플리케이션 - MRW
[스페인의 유명한 국제 물류 회사인 MRW](http://www.mrw.es/) 의 배송 기사들은 배송할 물건을 인수하고, 주문을 접수하고, 배송 일정을 조율을 위해 자체 개발한 안드로이드 애플리케이션을 사용합니다. 애플리케이션의 주요 기능으로 오프라인에서 일하고, 로컬 저장공간, 멀티 스레드 지원, 바코드 확인, 위치 추적, 요금지불 등이 포함되어 있습니다. Xamarin 을 이용하였기 때문에 복잡한 요구사항을 가짐에도 불구하고 빠른 시일에 출시할 수 있었습니다.

//이미지  

### 금주의 게임 - Crashing Season
[Crashing Season](http://madewith.unity.com/games/crashing-season)은 만화 같은 형태의 그래픽의 액션/아케이드 장르의 재미있는 모바일 게임입니다. Crashing Season 에는 플레이어 레벨에 따라서  최대 15 가지의 동물을 선택할 수 있으며, 각각의 동물이 가지는 특징을 이용하여 상대방과 충돌하고 각 레벨 별 정해진 미션을 완수하는것이이 게임의 목표입니다. 또한 온라인상의 친구와 다중 플레이하는 것도 가능하며 이경우 추가 골드(포인트)도 획득 할 수 있습니다.

Crashing Season 은 Unity 와 C# 으로 개발되었고, Koukoi Games 라는 게임사의 게임입니다. iOS 와 Android 에서 5월 26일부터 즐기실 수 있으며, 좀 더 자세한 정보는 [Made With Unity](http://madewith.unity.com/games/crashing-season) 에서 확인하시기 바랍니다. 

//그림


### .NET 소식
* [Changes to project.json](https://blogs.msdn.microsoft.com/dotnet/2016/05/23/changes-to-project-json/) : Scott Hunter 가 csproj 프로젝트와 project.json 의 차이점을 설명합니다.
* [Happy 25th birthday, VB](https://blogs.msdn.microsoft.com/dotnet/2016/05/20/happy-25th-birthday-vb/) : Anthony D. Green 이 VB 25살 생일을 맞은 VB(Visual Basic)을 축하했습니다
* [JSON.NET now works with RC2 without “import” directives](https://www.nuget.org/packages/Newtonsoft.Json/8.0.4-beta1) : RC2 버전부터는 JSON.NET 을 import 지시자 없이도 사용하실수 있게 되었습니다.
* [Updating to RC2: Changes to EFCore, ASPNETCore, PostgreSQL driver & XUnit](http://thedatafarm.com/data-access/updating-to-rc2-changes-to-efcore-aspnetcore-postgresql-driver-xunit/) : Julie Lerman 이 RC2로 업그레이드하기 전에 알아야 할 EFCore, ASPNETCore, PostgreSQL driver, Xunit 의 주요 변경사항을 공유했습니다.   
* [.NET Core goes RC2](http://developer.telerik.com/featured/net-core-goes-rc2/) : Ed Charbeneau 이 .NET Core RC2 버전에 대해서 설명했습니다.
* [How to debug .NET Core RC2 app with Visual Studio Code on Windows](http://codeclimber.net.nz/archive/2016/05/20/How-to-debug-NET-Core-RC2-app-with-Visual-Studio.aspx) : Simone Chiaretta 이 윈도우에서 Visual Studio Code 를 이용한 .NET Core RC2 애플리케이션 디버깅 방법을 설명했습니다.
* [.NET Core, a call to action](https://blog.rendle.io/net-core-a-call-to-action/) : Mark Rendle 이 .NET Core의 개발 배경 및 중요성을 설명했습니다.  
* [Using Windows Runtime in a .NET desktop application](https://github.com/jbe2277/waf/wiki/Using-Windows-Runtime-in-a-.NET-desktop-application) : jbe2277 아이디를 이용하는 사용자가 Windows Runtime API(Windows 8 부터 지원되는 일종의 runtime API)를 .NET 데스크톱 애플리케이션에서 사용하는 방법을 설명하였습니다.

### ASP.NET 소식
* [Migrating ASP.NET 5 RC1 apps to ASP.NET Core](https://chsakell.com/2016/05/21/migrating-asp-net-5-rc1-apps-to-asp-net-core/) : Christos Sakell 이 ASP.NET 5 RC1 에서 개발된 애플리케이션을 ASP.NET Core 버전으로 전환하는 방법을 설명했습니다.
* [Converting an ASP.NET Core RC1 Project to RC2](https://wildermuth.com/2016/05/17/Converting-an-ASP-NET-Core-RC1-Project-to-RC2) : Shawn Wildermuth 이 ASP.NET Core RC1 프로젝트를 RC2 버전 프로젝트로 변환하는 방법을 소개했습니다.
* [Using EF6 with ASP.NET MVC Core 1.0](https://blog.tonysneed.com/2016/01/22/ef6-asp-net-core-mvc6/) : Tony Sneed 가 ASP.NET MVC Core 1.0 에서 EF6(Entity Framework 6)를 사용하는 방법을 공유했습니다.
* [Strongly Typed Configuration Settings in ASP.NET Core](http://weblog.west-wind.com/posts/2016/May/23/Strongly-Typed-Configuration-Settings-in-ASPNET-Core#Addreferences) : Rick Strahl 가 ASP.NET Core 에서 외부 설정 파일의 각 항목이 코드에서 특정 클레스의 멤버로 접근할 수 있도록 하는 강력한 타입의 설정파일을 사용하는 방법을 공유했습니다.
* [How to use the IOptions pattern for configuration in ASP.NET Core RC2](http://andrewlock.net/how-to-use-the-ioptions-pattern-for-configuration-in-asp-net-core-rc2/), and [How to add default security headers in ASP.NET Core using custom middleware](http://andrewlock.net/adding-default-security-headers-in-asp-net-core/) : Andrew Lock 이 ASP.NET Core RC2 환경에서 IOptions pattern 을 이용한 설정 방법과 ASP.NET Core에서 사용자 미들웨어를 이용하여 기본 security header를 추가하는 방법을 설명하였습니다.
* [Building a Static File Server in ASP.NET Core RC2 with the CLI](http://iamnotmyself.com/blog/2016/05/19/building-a-static-file-server-in-asp-net-core-rc2-with-the-cli) : Bobby Johnson 가 ASP.NET Core RC2 에서 CLI를 이용한 정적 파일서버의 구성방법을 공유하였습니다. 
* [Templates for building React.js front-ends in ASP.NET Core and MVC5](http://www.thereformedprogrammer.net/templates-for-building-react-front-ends-in-asp-net-core-and-mvc5/) : Jon Smith이 ASP.NET Core MVC5 환경에서 React.js용 프론트앤드 개발 템플릿을 공유해주었습니다.
* [ASP.NET Core: Watching Code](http://tattoocoder.com/asp-net-core-watching-code/) : Shane Boyer가 운영환경에서 프로젝트 소스의 변화를 감지해주는 여러 모니터링 도구들을 소개해주었습니다.
* [ASP.NET Core distributed cache tag helper](http://aspnetmonsters.com/2016/05/2016-05-22-ASP-NET-Core-Distributed-Cache-Tag-Helper/) : David Paquette가 ASP.NET Core distributed cache tag helper에 대해 설명했습니다. 

### F# 소식
* [A Dive into Cloud<`T>](http://eiriktsarpalis.github.io/mbrace-msrc/index.html#/) : Eirik Tsarpalis 이 Cloud<`T> 에 대해서 설명합니다.
* [Getting Started with Fable and Webpack](http://kcieslak.io/Getting-Started-with-Fable-and-Webpack/) : Krzysztof Cieślak 이 F# 을 JavaScript 로 변경해주는 컴파일러인 Fable 과 모듈형태의 Bundler 인 Webpack 을 소개합니다.
* [Setting up your environment to build an Android app with Xamarin.Forms](https://kimsereyblog.blogspot.kr/2016/05/setup-your-environment-to-build-android.html) : Kimserey Lam 이 F# 과 Xamarin.Forms 를 이용한 안드로이드용 애플리케이션을 만들기 위한 개발 환경 설정방법을 소개했습니다.
* [Dynamic Recursive API with F#](http://www.taimila.com/blog/dynamic-recursive-api-with-fsharp/) : Lauri Taimila 가 F# 의 동적 재귀함수(Dynamic Recursive) API 를 설명합니다. 

### Xamarin 소식
* [10 Developer Takeaways from Xamarin Evolve](http://developer.telerik.com/featured/10-developer-takeaways-xamarin-evolve/) : Sam Basu 가 지난 Xamarin Evolve 행사에서 발표된 내용 중 개발자가 꼭 알아야 할 10가지 항목을 정리하여 공유해주었습니다.
* [James Montemagno interviews Joseph Hill, Xamarin co-founder, and VP of developer relations, on the Xamarin Podcast](https://blog.xamarin.com/podcast-xamarin-evolve-2016-recap-with-joseph-hill/) : 이번 주 Xamarin Podcast 에 Xamarin 의 공동 설립자이자 개발자 지원 부서의 부사장인 Joseph Hill 이 초대되었습니다.
* [The many flavors of HttpClient](http://kerry.lothrop.de/httpclient-flavors/) : Kerry W. Lothrop 가 .NET 에서 제공하는 HttpClient 외에도 사용 가능한 HttpClientHandlers 를 소개합니다. 
* [Embedding Native Controls into Xamarin.Forms](https://blog.xamarin.com/embedding-native-controls-into-xamarin-forms/) : James Montemagno 가 Xamarin.Forms 에서 Native Control 을 사용하는 방법을 공유했습니다.
* [Xamarin.Forms Workbooks](http://conceptdev.blogspot.com.au/2016/05/xamarinforms-workbooks.html), and [Xamarin Workbooks with Nugets](http://conceptdev.blogspot.com.au/2016/05/xamarin-workbooks-with-nugets.html) : Craig Dunn 이 Xamarin.Forms 프로젝트에서 Workbook 을 사용하는 방법과 Nugets 으로 다운로드 받은 소스코드에서 Workbook 을 활용하는 방법을 공유했습니다.

### Games 
* [CRYENGINE 5.1 is here](https://www.cryengine.com/news/cryengine-51-is-here) : 게임 개발 플랫폼인 CRYENGINE 5.1 버전이 릴리즈 되었습니다.
* [Unity Development with VS Code](https://code.visualstudio.com/Docs/runtimes/unity) : Visual Studio Code 를 이용해서 Unity 를 개발하실 수 있게 되었습니다. VS Code 에서 Unity 를 개발하시기 위한 환경설정 방법도 소개합니다.   
* [Build A Unity Game Part 3 – Video](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Build-A-Unity-Game-Part-3) : What Up Games 의 공동 대표이자 개발자인 Stacey Haffnerrk 가 Unity 에서 게임을 개발하는 방법을 소개합니다.
* [(Unity 5) Let’s Make Rust! Episode 01 – Introduction, Video](https://www.youtube.com/watch?v=-q_daB1aN8w) : Gabe Kutuzov 가 생존게임으로 유명한 Rust 와 유사한 스타일의 게임을 Unity 로 개발하는 방법을 소개했습니다.
