이번 주에도 알찬 정보를 가지고 주간닷넷이 돌아왔습니다. 저는 복잡한 리팩토링 작업을 도와주는 SemanticMerge 툴을 흥미롭게 보았는데요. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

[지난번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=aWnmzrCvTbg)에는 Don Syme 을 모시고 F# 의 미래와 커뮤니티에 관해 이야기 나누었습니다. 지난주에 소개해 드린 "[NATS Client](https://github.com/nats-io/csnats)"를 기억하시나요? [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=h3x6eY0RAr4)는 Apcera 회사 소속의 Brian Flannery 와 Colin Sullivan 과 함께 [NATS](http://nats.io/) 서비스에 대해서 이야기를 나누었습니다. 


### 금주의 패키지 – ASP.NET MVC Boilerplate

"ASP.NET MVC Boilerplate"는 ASP.NET MVC 기반의 다양한 응용 프로그램 템플릿을 제공합니다. 설치 후 비주얼 스튜디오의 프로젝트 템플릿을 선택할 수도 있고 "Feature Selection" 마법사를 이용해 여러분이 만들고자 하는 웹 사이트 유형을 선택할 수 있습니다.

* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate)

[Image](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate/raw/master/Images/ASP.NET%20MVC%20Boilerplate%20Feature%20Selection%20Wizard%201.png)

### 금주의 툴 - SemanticMerge

복잡한 리팩토링 작업 중에 다른 부분을 찾고 병합하는 것은 더욱 어렵습니다. [SemanticMerge](https://www.semanticmerge.com/) 도구는 해석된 코드를 바탕으로 다른 부분을 찾아내는 방법을 사용함으로써 어려움을 개선했습니다. 

* [SemanticMerge](https://www.semanticmerge.com/)

코드의 문자열을 직접 비교하는 대신에 코드가 해석된 구조 자체를 비교합니다. 현재 버전은 .NET 을 지원하고 있으며 향후 JavaScript 도 추가될 예정입니다.

### .NET 소식

* [미국 천문학 협의회(AAS)가 WWT(WorldWide Telescope) 프로젝트 진행](http://aas.org/media/press-releases/aas-assumes-leadership-worldwide-telescope) :  마이크로소프트에서는 우주를 인터넷으로 볼 수 있게 해주는 WWT(WorldWide Telescope) 프로젝트를 수행해왔습니다. WWT 프로젝트는 닷넷 기반의 가상 망원경을 이용해 세계에서 가장 우수한 장비로 측정한 천문 데이터를 과학계의 연구 종사자뿐만 아니라 개인에게도 제공해주는 프로젝트입니다. 최근에 이 프로젝트의 리더 역할을 미국 천문학 협의회(AAS: American Astronomical Society)에서 해주겠다는 고무적인 발표가 있었습니다. 이에 힘입어 WWT 개발팀이 이 프로젝트를 전일로 담당할 수 있게 되었습니다.
* [Cross-platform IDE for C#](http://blog.jetbrains.com/dotnet/2016/01/13/project-rider-a-csharp-ide/) : [JetBrains](http://www.jetbrains.com/) 사가 크로스 플랫폼용 C# 통합 개발 환경을 발표했습니다.
* [ Tips for deploying your .NET project ](http://gregorsuttie.com/2016/01/19/tips-for-deploying-your-net-project/) : Gregor Suttie 는 닷넷 프로젝트를 배포했던 경험에서 얻은 팁을 공유했습니다.
* [.NET Rocks](http://www.dotnetrocks.com/) 운영진이 이번 주에는 GitHub 에서 일하고 있는 Phil Haack 과 인터뷰를 진행했습니다.
* [ Shared projects or PCL? ](http://tirania.org/blog/archive/2016/Jan-22.html) : Miguel de Icaza 는 공통 소스코드 관리를 PCL(Portable Class Library) 를 이용해야 하는지, 별도의 공유 프로젝트를 생성해야 하는지에 대한 의견을 공유했습니다.

### ASP.NET 소식

* [Configuration in ASP.NET Core MVC](http://jameschambers.com/2016/01/Configuration-in-ASP-NET-Core-MVC/) : James Chambers 가 ASP.NET Core MVC 프로젝트에 새로 도입된 설정 관리 방법을 설명합니다.
* [FontAwesome fonts and MIME types in IIS and other web servers](http://weblog.west-wind.com/posts/2016/Jan/25/FontAwesome-Fonts-and-Mime-Types-in-IIS-and-other-Web-Servers) : 텍스트 방식으로 아이콘을 만들 수 있게 도와주는 FontAwesome 솔루션이 있습니다. Rick Strahl 이 IIS 와 다른 웹 서버에서 이를 사용할 때 필요한 MIME 타입 설정에 대해 설명합니다.
* [Angular 2 quickstart with ASP.NET Core](http://www.elanderson.net/2016/01/angular-2-quickstart-with-asp-net-core/) : Eric L. Anderson 은 ASP.NET Core 프로젝트에서 현재 베타 버전인 Angular 버전 2를 적용하는 방법을 설명합니다.
* [ASP.NET Core logging using trace listeners and how to filter logs](http://www.codeproject.com/Articles/1073028/ASP-NET-Logging-using-Trace-Listeners-and-How-to-F) : Girish J Jain 은 ASP.NET Core 의 로깅 방식과 그것을 필터링하는 방법을 설명합니다.
* [Dynamically adding meta tags](http://dotnet-helpers.com/2016/01/23/dynamically-adding-meta-tags-asp-net-mvc/) : Thiyagu 가 ASP.NET MVC 프로젝트에서 메타 태그(\<meta\/\>) 를 동적으로 추가하는 방법을 설명합니다.
* [How to create a custom controller factory](http://www.jomendez.com/2016/01/20/how-to-create-a-custom-controller-factory-asp-net-mvc/) : Jose Mendez 가 ASP.NET MVC 프로젝트에서 (IControllerFactory를 상속하는) 사용자 정의 컨트롤러 팩토리 클래스를 만드는 방법을 설명합니다.
* [Common aspects of ASP.NET code in WebForms and MVC](https://www.simple-talk.com/dotnet/asp.net/common-aspects-of-asp.net-code-in-web-forms-and-mvc/) : Dino Esposito 는 ASP.NET 웹 폼과 MVC 간의 핵심 구조는 다르지 않음을 각각의 동작 방식을 비교하며 설명합니다.
* [Generate C# client API for ASP.NET WebAPI](http://www.codeproject.com/Articles/1074039/Generate-Csharp-Client-API-for-ASP-NET-Web-API) : Zijian 은 ASP.NET Web API 서비스의 클라이언트 측 호출 코드를 자동 생성해주는 [Strongly Typed Client API Generators for ASP.NET Web API](https://webapiclientgen.codeplex.com/) 사용법을 설명합니다.
* [Handling request too large and identifying limits](https://lennybacon.com/post/2016/01/20/handling-request-too-large-and-identify-limits-in-aspnet) : Daniel Fisher 는 대용량 요청을 처리하는 방법과 최댓값을 넘어섰을 때의 요청을 인식하는 방법을 설명합니다.

### F# 소식

* [가상 F# 컨퍼런스](http://fsharpconf.com/)가 2016년 3월 4일에 라이브-스트리밍 방식으로 진행될 예정입니다.
* [Xamarin Studio 6.0 프리뷰 버전](http://developer.xamarin.com/releases/studio/xamarin.studio_6.0/xamarin.studio_6.0/#F_Enhancements)부터 F# PCL 및 공유 프로젝트를 포함하여 몇 가지의 F# 지원을 추가했습니다.
* [Running F# on Microsoft Azure](https://cockneycoder.wordpress.com/2016/01/20/running-fsharp-on-microsoft-azure/) : Isaac Abraham 이 마이크로소프트 클라우드 환경인 애저에서 F# 응용 프로그램을 호스팅하는 것에 관한 글을 공유했습니다.
* [Using F# on Linux](https://curran.in/jonathan/2015-01-16-using-fsharp-on-linux.html) : Jonathan Curran 은 리눅스 환경에서 F# 응용 프로그램을 작성하는 것에 관한 글을 공유했습니다.
* [Chart-tastic F# Goodness](http://bearandhammer.net/2016/01/17/chart-tastic-f-goodness/) : Bear & Hammer 는 FSharp.Charting 라이브러리를 이용하여 다양한 차트를 다루는 F# 소스 코드를 공유했습니다.
* [.NET: A Look Through F# Lenses](http://blog.pluralsight.com/tutorial-f-sharp) : Jacqueline Homan 은 F# 을 통해 닷넷 플랫폼을 설명하는 글을 공유했습니다.

### .NET 게임 소식

[Image](http://globalgamejam.org/sites/default/files/styles/responsive_large__wide/public/facebookheaderlarge.png) 

Global Game Jam 행사가 지난 1월 29일부터 3일간 개최되었습니다. .NET으로 개발된 게임을 Stacey Haffner ([@yecats131](http://twitter.com/yecats131)) 트위터 계정이나 [Gist](https://gist.github.com/bleroy/cb15b20d89f5730120d5) 를 통해 알려주세요.
