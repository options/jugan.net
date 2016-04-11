마이크로소프트의 개발자 행사인 빌드(//Build/) 2016 의 키노트 [1일 차](https://blogs.msdn.microsoft.com/eva/?p=6981) 와 [2일 차](https://blogs.msdn.microsoft.com/eva/?p=7233)에 대한 글이 에반젤리스트 블로그에 업로드되었습니다. 또한 4/23일에 빌드 특집으로 [Techdays mini 토요세미나](https://msevents.microsoft.com/cui/EventDetail.aspx?EventID=1032755851&culture=ko-KR)를 진행할 예정이오니 관심 있으신 분들은 등록하시기 바랍니다.  
지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=OjNbBOjcLRk)는 John Kemnetz 와 함께 Visual Studio Code 에 새롭게 포함된 C# 디버깅 지원을 중심으로 이야기 나누었습니다. 지금까지 On.NET 동영상 인터뷰를 보통 1시간 정도의 분량으로 진행해왔지만, 이번 On.NET 유튜브 동영상 인터뷰부터는 녹화시간을 20분으로 줄여서 진행하였습니다.  

### 금주의 패키지 - Autofac
DI(dependency injection, 의존성 주입) 기능이 ASP.NET Core 의 주요기능으로 주목받고 있습니다. 이와 관련하여 ASP.NET 컨테이너의 결합을 느슨하게 유지하면서 개발하는 기술이 아주 중요해졌습니다. ASP.NET 은 최소한의 컨테이너만 제공하며, 기본으로 제공되는 컨테이너를 전혀 다른 컨테이터 타입으로 교체하는 옵션도 제공합니다. Autofac 는 이와 같은 상황에서 기본 컨테이너를 대체할수있는 [.NET Core 용 컨테이너](http://autofac.readthedocs.org/en/latest/integration/aspnetcore.html)와 견주어 볼 만한 [IoC](https://en.wikipedia.org/wiki/Inversion_of_control) 컨테이너입니다. 

* [Autofac](https://github.com/autofac/Autofac) 

아래의 코드는 IOutput 인터페이스를 구현한 실체인 실제 인스턴스 등록방법을 보여주는 예제입니다. 애플리케이션을 초기화하는 부분부터 포함됨으로써 이후 참조된 다른 컴포넌트에서도 IOutput 인터페이스의 실체에 접근할 수 있습니다.

code

다음 작업을 통해 컨트롤러와 서비스에 IOutput 를 주입할 수 있습니다.

code

위의 코드는 Autofac 의 아주 간단한 사용 예제이므로 실제 프로젝트를 위한 좀 더 자세한 예제는 [링크](http://autofac.readthedocs.org/en/latest/index.html)를 통해 확인해보시기 바랍니다. ASP.NET 소식에서 DI 와 관련된 좀 더 많은 글이 준비되어 있습니다.

[Orchard CMS](https://orchardproject.net/) 도 IoC 컨테이너로 Autofac 을 사용하는 점이 흥미롭습니다. 

### .NET 소식
* [Xamarin for Everyone](https://blog.xamarin.com/xamarin-for-all/) : Nat Friedman 이 마이크로소프트의 Xamarin 무료 선언에 대한 소식을 공유했습니다. 
* [Announcing the .NET Framework 4.6.2 Preview](https://blogs.msdn.microsoft.com/dotnet/2016/03/30/announcing-the-net-framework-4-6-2-preview/) : Stacey Haffner 가 .NET Framework 4.6.2 Preview 버전에 대한 발표 소식을 공유했습니다.
* [NET at Build 2016 – Open, Cross-platform and FREE](https://blogs.msdn.microsoft.com/dotnet/2016/04/01/net-at-build-2016-open-cross-platform-and-free/) : Rich Lander 가 빌드 2016 행사에서 엿볼 수 있었던 .NET 의 새로운 방향인 오픈소스, 크로스플랫폼, 무료정책과 관련된 발표내용을 정리했습니다.
* [What’s New for C# and VB in Visual Studio](https://blogs.msdn.microsoft.com/dotnet/2016/04/02/whats-new-for-c-and-vb-in-visual-studio/) : Kasey Uhlenhuth 이 빌드 2016 행사에서 발표된 Visual Studio 2015 업데이트 2 와 Visual Studio 15 Preview 버전에서 제공되는 C# 과 VB 개발언어의 새로운 기능들을 정리했습니다.
* [Mobile App Development made easy with Visual Studio and Xamarin](https://blogs.msdn.microsoft.com/visualstudio/2016/03/31/mobile-app-development-made-easy-with-visual-studio-and-xamarin/) : John Montgomery 이 Visual Studio 와 Xamarin 을 이용한 모바일 애플리케이션 구현 방법과 앞으로의 개발 방향에 대해 공유했습니다.
* [Mono Relicensed MIT](http://www.mono-project.com/news/2016/03/31/mono-relicensed-mit/) : Miguel de Icaza 가 .NET Framework 기반의 오픈소스 구현체인 Mono 가 제약이 거의 없는 MIT 라이센스로 갱신되었다는 소식을 전했습니다.
* [.NET Overview (Build session Video)](https://channel9.msdn.com/events/Build/2016/B891) : Scott Hanselman 과 Scott Hunter 가 .NET 의 앞으로의 모습을 .NET Standard Library 에 대한 소개를 시작으로 다양한 내용과 함께 발표했던 .NET Overview 세션이 Channel9 에 공유 되었습니다.
* [A Vision For Visual Studio 2015: Take on Dependencies; stay Productive](https://blogs.msdn.microsoft.com/visualstudio/2016/04/01/visual-studio-2015-take-on-dependencies-stay-productive/) : Michael C. Fanning 와 Joe Morris 가 Visual Studio 2015 로 개발 시에 자신의 프로젝트가 아닌 외부 프로젝트 혹은 외부 라이브러리와 종속성을 유지하면서 동시에 효과적으로 코드 탐색 및 디버깅을 수행하여 생산성을 높이는 방법을 공유했습니다. 
* [Faster, Leaner, Focused on Your Development Needs: The New Visual Studio Installer](https://blogs.msdn.microsoft.com/visualstudio/2016/04/01/faster-leaner-visual-studio-installer/) : Tim Sneath 가 새로운 Visual Studio Installer 의 기능과 개발 배경을 소개합니다.
* [IConfiguration in .NetCore](http://www.ryansouthgate.com/2016/03/23/iconfiguration-in-netcore/) : Ryan Southgate 이 .Net Core 에 포함된 IConfiguration 인터페이스의 사용법과 기본 기능을 확장하는 방법을 공유했습니다.
* [Refactoring Essentials 4.0 Comes With Roslyn Code Converter](http://community.sharpdevelop.net/blogs/christophwille/archive/2016/04/01/refactoring-essentials-4-0-comes-with-roslyn-code-converter.aspx) : Christoph Wille 가 코드 리팩토링 기능과 코드변환기능(C# ->VB 으로 변환)이 포함된 Visual Studio 의 Extention 인 Refactoring Essentials 4.0 버전을 공개했습니다.  
* [Visualization and comparison of sorting algorithms in C#](http://www.codeproject.com/Articles/1087568/Visualization-and-Comparison-of-sorting-algorith) : Mark Monnin 이 여러 정렬 알고리즘을 쉽게 비교할 수 있는 C# 데모 프로젝트를 소개했습니다.
* [Reduce Coupling: free your code and your tests](http://jonhilton.net/2016/03/29/coupling-tests-production/) : Jon Hilton 이 코드사이의 의존성을 줄임으로써 개발된 코드에 대한 테스트 코드를 쉽게 작성하고 리펙토링하여 좀더 정확한 테스트 결과를 얻는 것에 대한 글을 공유했습니다.  
 
### ASP.NET 소식
* [Dependency Injection in ASP.NET Core](https://blogs.msdn.microsoft.com/webdev/2016/03/28/dependency-injection-in-asp-net-core/) : Jeffrey T. Fritz 가 ASP.NET Core 의 DI 에 대해서 설명했습니다.
* [Setting Up Dependency Injection in Web API with StructureMap](http://www.exceptionnotfound.net/setting-up-dependency-injection-in-web-api-with-structuremap/) : Matthew Jones 이 IoC/DI 컨테이너인 StructureMap 을 이용한 Web API 의 DI 기능 활용을 설명했습니다.
* [The Subtle Perils of Controller Dependency Injection in ASP.NET Core MVC](http://www.strathweb.com/2016/03/the-subtle-perils-of-controller-dependency-injection-in-asp-net-core-mvc/) : Filip W 가 ASP.NET Core MVC 의 DI 컨테이너와 MVC 컨트롤러의 연관관계를 설명하고 이전 버전의 프레임워크인 MVC 5 혹은 Web API 2 와의 연관관계와 다른 점, 주의할 점등을 공유했습니다.
* [Docker and ASP.NET Core (video)](http://wildermuth.com/2016/03/28/Docker_and_ASP_NET_Core_A_Webcast) : Shawn Wildermuth 이 오픈소스 블로그 프로젝트인 WilderBlog 의 예를들어 Docker 컨테이너에서 ASP.NET Core 설정 및 실행 방법을 설명한 비디오를 공유하였습니다.
* [ASP.NET Core Password Options and Custom Validators](http://www.elanderson.net/2016/03/asp-net-core-password-options-and-custom-validators/) : Eric L. Anderson 가 ASP.NET Core 에 포함된 기본 인증 기능과 기본 암호의 복잡도를 개발자가 변경하는 방법을 공유했습니다.
* [Building Advanced Tag Helpers (video)](http://aspnetmonsters.com/2016/03/monsters-weekly%5Cep19/) : ASP.NET Monsters 사이트에 ASP.NET Core 의 사용자 Tag Helper 를 구현하는 방법이 공유되었습니다.

### F# 소식
* .NET Core 환경에서의 F# 학습 방법 
  * David Stephens 가 진행하는 [.NET Core 기반의 F# 시작하기](https://channel9.msdn.com/Events/Build/2016/T661) 시청 
  * [Github 에 공유된 F# 문서](https://github.com/enricosada/fsharp-dotnet-cli-samples/wiki/Getting-Started) 읽어보기  
* [Beyond Lists](http://www.infoq.com/presentations/data-structure-lists) : Phil Trelford 가 개발자 콘퍼런스에서 List 에 대해 발표하였습니다.
* [Functional Architecture](https://vimeo.com/161131920) : Mark Seemann 이 Functional Architecture 에 대해 설명하였습니다. 
* [Microservices Chaos Testing at Jet](http://www.infoq.com/presentations/jet-microservices-testing) : Rachel Reese 가 Jet.com 에 적용된 Chaos 테스팅 방법을 소개합니다. 

### Games
* [Unity Joins the .NET Foundation](http://blogs.unity3d.com/2016/04/01/unity-joins-the-net-foundation/) : Jonathan Chambers 가 .NET Framework 기반의 오픈소스를 개발하기 위해 만들어진 단체인 .NET Foundation 에 Unity 도 함께하게 되었다는 소식을 전했습니다.
* [Visual Studio Tools for Unity (Video)](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Visual-Studio-Tools-for-Unity) : Jb Evain 와 Robert Green 이 Unity 로 개발할 때에 Visual Studio 를 사용하는 것을 소개했습니다.