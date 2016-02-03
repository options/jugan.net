이번 주에도 어김없이 알찬 정보를 가지고 주간닷넷이 돌아왔습니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

On.NET 인터뷰 동영상을 [기존의 유튜브 채널](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw)에서뿐만 아니라 [Channel 9](https://channel9.msdn.com/Shows/On-NET)에서도 볼 수 있게 되었습니다. 더 많은 분들이 볼 수 있게 되었다는 면에서도 의미가 있지만 무엇보다도 Channel 9에서 MP3 음성 파일을 함께 제공해주기 때문에 결과적으로 화면을 시청하지 못하는 분들을 위한 음성 팟 캐스트 서비스가 On.NET에 추가되었습니다.

[지난번 인터뷰](https://youtu.be/h3x6eY0RAr4)는 Apcera 의 Brian Flannery 와 Colin Sullivan 과 함께 [NATS](http://nats.io/) 서비스에 대한 이야기를 나누었습니다. 좀더 자세한 정보는 [NATS 웹 사이트](http://nats.io/)에서 확인할 수 있습니다.

이번주 인터뷰는 Scott Hunter를 모시고 .NET, ASP.NET 및 .NET Core 릴리즈 관련 이야기를 나눕니다.

### 금주의 패키지 – AutoMapper

AutoMapper는 객체 간의 데이터를 손쉽게 매핑해주는 라이브러리입니다.

* [AutoMapper](https://github.com/AutoMapper/AutoMapper)

제작자인 Jimmy Bogard의 말에 따르면 객체들 간의 매퍼인 셈입니다. 보통 UI 영역에서 사용하는 데이터 객체와 도메인 영역에서 사용하는 데이터 객체가 다른 경우가 많습니다. 서비스와 도메인 간의 관계에서도 마찬가지인데, 이런 식의 레이어 경계에서 데이터 객체들 간의 값 전달을 쉽게 하기 위한 목적으로 AutoMapper를 사용할 수 있습니다.

<section>
var config = new MapperConfiguration(cfg => cfg.CreateMap<Order, OrderDto>());
var mapper = config.CreateMapper();
OrderDto dto = mapper.Map<OrderDto>(order);
</section>

AutoMapper는 여러분들의 코드에서 사용된 공통 규칙을 인식하도록 설정하는 것도 가능하고, 나아가 사용자 정의할 수 있는 데이터 변환기로써의 용도로도 사용될 수 있습니다.

### 금주의 툴 - Cake

msbuild.exe만 .NET 프로젝트를 빌드할 수 있는 것은 아닙니다. .NET 개발자들이 알아둘만한 또 다른 자동화 빌드 시스템으로써 Cake 도구가 있는데, 이는 다중 플랫폼을 지원할 뿐만 아니라 빌드 스크립트 자체가 C#으로 만들어졌다는 점에서 차별화를 두고 있습니다. 

* [Cake](http://cakebuild.net/blog/2016/01/cake-v0-8-0-released)

[...그림...](https://camo.githubusercontent.com/bd580d5d5e2d9b70e3ea617a599cf72c1f025329/687474703a2f2f63616b656275696c642e6e65742f436f6e74656e742f696d672f73637265656e73686f742e706e67)

최근에 버전 0.8이 릴리즈되었습니다.

### 금주의 커뮤니티 소식


### .NET 소식

* .[NET Framework 4.6.1 버전이 윈도우 업데이트를 통해 공식적으로 배포되기 시작했습니다.](http://blogs.msdn.com/b/dotnet/archive/2016/01/26/microsoft-net-framework-4-6-1-is-available-on-windows-update-and-wsus.aspx)
* 여러분들의 닷넷 응용 프로그램에 대한 다중 플랫폼 이식성을 테스트할 수 있는 ".NET Portability Analyzer" 도구가 있습니다. [이 도구를 설명하는 동영상](https://channel9.msdn.com/Blogs/Seth-Juarez/A-Brief-Look-at-the-NET-Portability-Analyzer)이 Channel 9에 올라왔습니다.
* Interactive coding with C# and F# REPLs : Scott Hanselman이 C#및 F#의 REPL 환경을 다룹니다.
* How (and why) to lobby companies to support .NET OSS : 제목에서 ".NET"을 빼도 무방할 것 같습니다. 여러분의 회사가 오픈 소스를 사용한다면 그 오픈 소스의 발전을 위해 기여하는 것이 타당하다는 Sean Killeen의 글입니다. 아울러 회사가 기여를 하도록 어떻게 분위기를 만들 수 있는가에 관한 의견도 적고 있습니다.
* What I’ve learned about .NET Native : Mark Rendle은 .NET Native를 접하면서 알게 된 사항들을 공유했습니다.
* NBench Testing – Memory Allocations : Andrea Angella는 [NBench 프레임워크](https://github.com/petabridge/NBench)를 이용해 메모리 테스트를 하는 방법을 공유했습니다. 
* Porting Microbus to .NET Core : Daniel Little은 Microbus 오픈 소스 프로젝트를 .NET Core에 포팅하는 경험담을 공유했습니다.
* Generic resource leak detection with ETW and EasyHook : 윈도우 운영체제의 [ETW(Event Tracing for Windows)](https://msdn.microsoft.com/en-us/library/windows/desktop/bb968803(v=vs.85).aspx)와 API 후킹에 사용되는 [EasyHook 라이브러리](https://github.com/EasyHook/EasyHook)를 이용한 리소스 누수 감지에 대해 Alois Kraus가 설명합니다.


### ASP.NET 소식

* JavaScript debugging in Visual Studio with Chrome : Martin Kramer는 크롬 웹 브라우저와 함께 비주얼 스튜디오에서 자바스크립트를 디버깅하는 방법에 관해 글을 공유했습니다.
* Understanding the new ASP.NET Core configuration in startup.cs : Mike Mengell은 새롭게 startup.cs에서 이뤄지는 ASP.NET Core 설정 방법을 설명하고 있습니다.
* NGINX Reverse Proxy and Load Balancing for ASP.NET 5 Applications with Docker Compose : Tugberk Ugurlu는 ASP.NET 5 응용 프로그램을 대상으로 NGINX 리버스 프록시를 이용해 로드 밸런싱 환경을 구성하는 방법을 소개하고 있습니다.
* Isolated ASP.NET attribute routing : Shannon Deminick은 WebApi의 라우팅 관련 특성을 분리하는 것에 관한 글을 썼습니다.
* A practical approach to cache busting with Webpack and ASP.NET Core : Scott Addie는 ASP.NET Core 기반의 응용 프로그램에서 Webpack을 사용하는 경우, 그로 인해 생성된 정적 컨텐츠에 대한 Cache 관리를 위한 현실적인 방법을 제시합니다.
* Using subdomains in ASP.NET MVC : Jonathan Danylko는 ASP.NET MVC 환경에서의 서브 도메인 사용법을 설명합니다.
* ASP.NET Core 1.0 using SQL localization : Damien Bod는 SQL 데이터베이스를 사용하는 ASP.NET Core 응용 프로그램에서 어떻게 SQL 지역화를 할 수 있는지 설명합니다.
* Inline images in ASP.NET Core : Ricardo Peres는 ASP.NET Core 응용 프로그램에서 <img /> 태그에 인라인 이미지를 적용하는 방법을 설명합니다.


### F# 소식

* Krishna Vangapandu의 Microservices & Messaging at Jet
* Frank Krueger의 Continuously writing an iPhone app, on an iPad Pro, using F#
* Evelina Gabasova의 Star Wars social networks: The Force Awakens
* Pierre-Luc Maheu의 Interview with Henrik Feldt on Suave 1.0
* Yan Cui의 Building a random art bot in F#
* Roslyn으로 Visual Studio의 F# 편집기를 개선하는 것에 관한 [토론](https://github.com/Microsoft/visualfsharp/issues/913)이 있었습니다.
* 최근 있었던 F# 소프트웨어 재단의 [임원 회의에서 나왔던 기록](http://foundation.fsharp.org/board_meeting_20151214)이 공개되었습니다.

그 외에 원한다면 F# 커뮤니티 소식을 배포하는 [F# Weekly](https://sergeytihon.wordpress.com/category/f-weekly/)를 통해 더 많은 정보를 얻을 수 있습니다.

### .NET 게임 소식

* Unity comes to New Nintendo DS : Andrew Innes는 Unity가 Nintendo DS 플랫폼을 새롭게 지원하게 되었다는 소식을 공유했습니다.

### Global Game Jam 2016 Submission

"Oh God, it’s Monday"라는 제목의 게임을 소개하고자 합니다. 게이머는 주어진 업무 시간 내에 종업원들이 그들의 일을 완료할 수 있도록 최대한 효율적인 경로를 선택해야 한다는 시나리오입니다. 일과 시간 중에 어떤 종업원이든 다른 동료에게 가게 된다면 업무의 중단과 함께 수다를 떨게 되는데, 이로 인해 그들은 일을 완료할 수 없게 되어 게이머가 실패하는 조건이 됩니다.

[...그림....](https://cloud.githubusercontent.com/assets/4108756/12756896/9cfa9178-c98a-11e5-99f7-b8bf0b885eb0.jpg)