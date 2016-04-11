### On.NET 소식
이번주 On.NET에서는 John Kemnetz와 함께 VS Code에 새롭게 포한됨  C# 디버깅을 중심으로 얘기해볼까합니다. 그리고 이번주부터 On.NET 인터뷰에 약간의 변화를 주었습니다. 지금까지 On.NET 동영상은 보통 1시간 분량으로 진행했었지만 이번 On.NET 유튜브 동영상부터는 녹화시간을 20분으로 줄여서 진행할 예정입니다. 좀더 짧은 시간에 유용한 정보를 담도록 노력하겠습니다. 

### 금주의 패키지 - Autofac
DI(dependency injection, 의존성 주입)기능이 ASP.NET Core의 주요기능으로 부각되고 있습니다. 이와 연하되어 ASP.NET 컨테이너의 결합을 느슨하게 유지하면서 코딩개발을 할수있는 기술이 아주 중요해졌습니다. 더불어 ASP.NET은 최소한의 컨테이너만 제공하는데 심지어는 기본제공되는 컨테이너를 전혀다른 컨테이터 타입으로 교체할수있는 옵션도 제공됩니다. Autofac는 이같은 상황에서 기본 컨테이너를 대체할수있는 인기있는 .NET Core용 IoC 컨테이너입니다. 

아래의 코드는 인터페이스 IOutput에 이 인터페이스를 구현한 실체(실제 인스턴스)를 어떻게 등록 하는지 보여주는 예입니다. 이 코드는 아마도 어플리케이션 실행 초입 부분에 포함됨으로서 이후 참조된 다른 컴포넌트에서도 IOutput 인터페이스의 실체를 접근(Resolve)할수있습니다.

public IServiceProvider ConfigureServices(IServiceCollection services)
{
services.AddMvc();
var builder = new ContainerBuilder();
builder.RegisterType<ConsoleOutput>().As<IOutput>();
builder.Populate(services);
var container = builder.Build();
return container.Resolve<IServiceProvider>();
}

다음 작업으로 컨트롤러와 서비스에 IOutput를 주입(inject) 할 수 있습니다.

public class MyController : Controller
{
private IOutput _output;
public MyController(IOutput output)
{
_output = output;
}
public IActionResult DoSomething()
{
_output.Write("I did something.");
return View();
}
}

위의 코드는 Autofac의 아주 간단한 사용 예입니다. 하지만 실제 프로젝트에서는 좀더 자세한 정보가 필요합니다. 좀더 상세한 내용의 문서와 샘플 정보는 링크를 통해서 확인할 수 있습니다. 또한 이번주에는 DI에 관련 주제 글이 좀 더 준비 되있습니다. ASP.NET 소식 링크에서  관련정보를 확인해 보세요.

Orchard CMS가 IoC 컨테이너로 Autofac을 사용한다는것 또한 주목할만한 점입니다.

### .NET 소식
* Xamarin for Everyone : 3월 빌드 행사를 통해서 Xamarin이 추가적인 비용 발생없이 공식적으로 비주얼 스트디오에 추가되었습니다. Nat Friedman이 이와 관련한 Xamarin 제품의 몇가지 변화를 정리해서 Xamarin 개발자 블로그에 공유했습니다.
* Announcing the .NET Framework 4.6.2 Preview : Stacey Haffner가 .NET Framework 4.6.2 Preview 버전의 정보를 공유했습니다.
* NET at Build 2016 – Open, Cross-platform and FREE :  Rich Lander가 빌드 2016 행사에서 오픈소스, 크로스플렛폼, 무료정책등과 관련된 발표내용을 정리해서 공유했습니다.
* What’s New for C# and VB in Visual Studio : Kasey Uhlenhuth이 빌드 2016 행사때 발표된 "Visual Studio 2015 업데이트 2"와 "Visual Studio 15 Preview 버전"에서 확인할수있는 C#, VB 개발언어의 새롭운 기능들을 정리했습니다.
* Mobile App Development made easy with Visual Studio and Xamarin : John Montgomery이 Visual Studio와 Xamarin을 이용한 모바일 어플리케이션 구현 방법과 앞으로의 개발 방향에 대해서 공유해 주었습니다.
* Mono Relicensed MIT : Mono 프로젝트가  MIT 라이선스를 바탕으로 재발표 되었다는 소식을 Miguel de Icaza가 공유해주었습니다.
* .NET Overview (Build session Video) : 빌드 2015 행사에서 Scott Hanselman과 Scott Hunter가 진행한 .NET Overview 세션이 channel9에 공유 되었습니다.
* A Vision For Visual Studio 2015: Take on Dependencies; stay Productive : Michael C. Fanning와 Joe Morris가 Visual Studio 2015로 프로젝트 개발시 자신의 프로젝트가 아닌 외부 프로젝트 혹은 외부 라이브러리와 종속성을 유지하고 동시에 효과적으로 코드 탐색및 디버깅을 수행하여 생산성을 높일 수 있는 방법을 공유하였습니다 
* Faster, Leaner, Focused on Your Development Needs: The New Visual Studio Installer : Tim Sneath이 새롭게 소개될 Visual Studio 설치 인스톨러의 기능과 개발 배경에 대해서 소개했습니다.
* IConfiguration in .NetCore : Ryan Southgate이 .Net Core에 포함된 IConfiguration 인터페이스의 사용방법과 기본 기능의 확장 방법을 공유하였습니다.
* Refactoring Essentials 4.0 Comes With Roslyn Code Converter : Christoph Wille가 코드 리팩토링 기능과 코드변환기능(C# ->VB 으로 변환)이 포함된 비주얼 스트디오의 확장 애드온인 Refactoring Essentials 4.0 버전을 공개했습니다.  
* Visualization and comparison of sorting algorithms in C# : Mark Monnin이 여러 정렬 알고리즘을 비교를 눈으로 쉽게 확인 할수있는 C# 데모 프로젝트를 공유했습니다.
* Reduce Coupling: free your code and your tests : Jon Hilton이 개발 코드사이의 의존성을 줄임으로서 개발 코드에 대한 테스트 코드 구축시 쉽게 코드를 작성하고 또 효율적으로 테스트 코드를 리펙토링하여 좀더 정확한 테스트 결과를 얻을수있는 방법을 공유했습니다.  
 

### ASP.NET 소식
* Dependency Injection in ASP.NET Core : Jeffrey T. Fritz가 ASP.NET Core의 DI(의존성 주입)기능에 대해서 설명했습니다.
* Setting Up Dependency Injection in Web API with StructureMap : Matthew Jones이 IoC/DI 컨테이너인 StructureMap을 이용한 Web API의  DI(의존성 주입)기능활용에 대해서 설명했습니다.
* The Subtle Perils of Controller Dependency Injection in ASP.NET Core MVC : Filip W이 ASP.NET Core MVC의 DI 컨테이너와 MVC controller의 연결관계를 설명하고 이전 버전의 프레임워크인 MVC 5 혹은 Web API 2의 연관관계와 다른점, 주의할점등을 공유해 주었습니다.
* Docker and ASP.NET Core (video) : Shawn Wildermuth이 Docker 컨테이너에서 ASP.NET Core 설정, 실행 방법을 오픈소스 블로그 프로젝트인 WilderBlog를 예로 Docker 환경에서 구축하면서 설명한 비디오를 공유하였습니다.
* ASP.NET Core Password Options and Custom Validators : Eric L. Anderson은 ASP.NET Core에 포함된 기본 인증 기능과 기본 암호의 복잡도를  개발자가 확장, 수정할 수 있는 방법을 공유하였습니다.
* Building Advanced Tag Helpers (video) : ASP.NET Monsters 사이트에 ASP.NET Core의 사용자 Tag Helper를 구현하는 방법이 공유되었습니다.

### F# 소식

*  .NET Core 환경에서 실행할수있는 F#을 쉽게 배울수있는 방법은 
> David Stephens가 진행하는 F# 처음부터 배워보기 동영상 강좌(Getting Started with F# on .NET Core)를 본다
> Github에 공유된 F# 개발 가이드 문서를 참고하여 학습한다 

* Beyond Lists :Phil Trelford 가 개발자 컨퍼런스 "BUILD STUFF"에서 "Beyond Lists"라는 제목의 세션 동영상이 infoq 사이트에 공유되었습니다.
* Functional Architecture, : Mark Seemann이 "Functional Architecture"라는 주제로 진행한 세션 동영상이 비미오(vimeo)에 공유 되었습니다.
* Microservices Chaos Testing at Jet, : Rachel Reese가 Jet.com's 에 적용한 Chaos 테스팅 방법에 대한 동영상 세션이 infoq 사이트에 공유되었습니다.

### Games
* Unity Joins the .NET Foundation : Jonathan Chambers가 Unity 가 .NET Foundation 의 회원사로 가입된 것을 발표했습니다.

* Visual Studio Tools for Unity (Video) : Evain과 Robert Green이 Visual Studio Tools for Unity를 소개하는 동영상을 channel9에 공유했습니다.
