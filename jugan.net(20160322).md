### Build 소식
다음주 저희 팀원중 많은 분들이 2016 Build 컨퍼런스 행사차 샌프란시스코에 있을 예정입니다.  이번 행사는 .NET 최신 소식을 전할수있는 좋은 자리이며 여기서 많은 분들을 만나기를 기대합니다. 하지만 혹시 참여 못하셔서 저희와 만나지 못하시더라도 생방송으로 keynote 세션을 보실 수 있으며 각 파트별 상세 세션들은 녹화되어 빠른 기간안에 Channel 9 공유될 예정이오니 너무 상심하지 마세요

### On.NET 소식
저번 주 동영상 인터뷰는 없었습니다. 하지만 이번 주는 동영상 인터뷰는 진행될 예정이며 Joyent에 근무하는 Richard Kiene를 모시고 .NET Core를 Joyent cloud에 적용한 사례에 대해서 얘기나눌까 합니다.

### 금주의 패키지 - Octopus Deploy
패키지 Octopus Deploy는 안정적이고 연속적인 서버 배포를 할 수 있도록 도와주는 유용한 배포툴 입니다. 테스트 서버, staging 서버(국내환경에서는 흔히 QA 서버라도 합니다), 그리고 운영서버까지 모든 서버 배포 작업에 이 패키지를 이용할 수 있습니다. 사용방법이 쉽고 간단하기 때문에 아주 작은 변경점이라도 있다면 쉽게 그리고 좀더 자주 배포할 수 있습니다. 결과적으로 서버의  새로운기능및 버그 수정을 빠르게 적용할 수 있어 서버 어플리케이션 품질이 향상될 것 입니다. Octopus Deploy는 사용화된 제품이지만 비교적 소규모 팀(5개 이하의 프로젝트로 조합된 결과물을 10개 미만의 서버에 배포하는 경우)에게는 무료로 제공됩니다.

### .NET 소식
* The Sound of .NET : .NET 관련 podcast(비디오/오디오)을 한자리에 모아놨네요.

* High speed applications : Erik Bergman이 .NET에서 빠른 성능을 구현하기 위해 parallelism을  적용하는 방법을 part 1 과 part 2 로 나누어서 공유했습니다.

* Peachpie – Benjamin Fistein이 .NET 용 PHP Compiler 인 Peachpie 를 소개 했습니다.

* LINQPad.QueryPlanVisualizer : 업무 프로젝트 개발시 복잡한 LINQ를 작성하는 경우 LINQPad를 사용하면 많은 도움이 됩니다. 그래서 많은 개발자 분들이 LINQPad를 사용하고 계십니다.   Giorgi Dalakishvili는 이 LINQPad 안에서 query execution plan을 바로 확인 할 수 있도록 해주는  LINQPad의 에드온인 QueryPlanVisualizer를 개발 했으며 이를 자신의 블로그에 소개 했습니다.


* .NBench Performance Testing :Andrea Angella이 오픈소스 테스트 툴인 Nbench 환경에서 NUnit 와 ReSharper 을 연동해서 테스트 하는 방법을 공유했습니다.

### ASP.NET 소식
* cloudscribe SimpleContent : Joe Audette가  ASP.NET Core환경에서 동작하는 블로그 엔진의 초기버전을 개발하여 github에 공유하였습니다

*First Look - Authentication in ASP.NET Core :  리포터 Seth Juarez 와  ASP.NET 프로그램 메니저인 Pranav Rastogi가 ASP.NET Core 인증(Authentication)시스템의 업데이트와 향상된 기능에 대해서 비디오로 공유했습니다.

* Extending the ASP.NET Core 1.0 Identity SignInManager : Steve Gordon가  ASP.NET Core 1.0의 Identity 라이브러리중 SignInManager 클래스의 확장 사용법을 공유했습니다.

* ASP.NET Two Factor Auth with Google’s Authenticator App : Lachlan Barclay가 Google Authenticator를 이용한 손쉬운 이중 인증(Two Factor Auth)의 구현방법을 part 1, part 2 로 나누어 설명하였습니다.

* ASP.NET Web API / OWIN authenticated integration tests without authorization server : Martijn Boland이 ASP.NET Web API OWIN(Open Web Interface for .NET)어플리케이션 개발시 authorization server 서버의 구축 혹은 설정 없이도 인증 테스트를 할 수 있는 방법을 공유했습니다.

* Integrating ASP.NET Core Configuration in MVC 4, Integrating ASP.NET Core Dependency Injection in MVC 4 : Scott Dorman이 새로운 ASP.NET Core 에서 향상된 기능 중 Configuration 시스템(기존 web.config등의 파일에 접근하기 위한 ) 기능의 사용법을 MVC 4 프로젝트을 예로 설명했습니다. 또한 ASP.NET Core에서 Dependency Injection의 적용 방법 또한 데모 MVC 4 프로젝트을 이용하여 설명하였습니다.

* Using Specflow to test Web API : Veronica S. Zotali이 오픈소스 자동화 테스트 라이브러리인 Specflow 를 이용하여 Web API를 테스트 하는 예를 codeproject 사이트에 공유하였습니다.

* Logging basics in ASP.NET Core (video) : ASP.NET Monsters 웹사이트에 매주 연재되는 내용 중 이번 주 내용으로 ASP.NET Core 에서 Logging 하는 기본적인 방법을 설명하는 동영상이 공유 되었습니다.

* Content Negotiation in ASP.NET Core : Shawn Wildermuth이 ASP.NET Core에서 사용자 웹 요청의 결과로서 content가 반환될 때 XML 혹은 JSON과 같이 정해진 타입(strong type)의 결과를 반환 할 때 생길 수 있는 문제점과 이를 해결하기 위해 사용할 수 있는  Content Negotiation(가변적인 result type을 유연하게 반환하도록 할 수 있는) 기능의 사용방법을 공유했읍니다.

### F# 소식
* Building Reactive Services Using Functional Programming : Rachel Reese이 Lambda Days 2016행사에서 반응형 서비스를 만들기 위한 F#언어의 전반적인 기능 소개를 했으며 녹화된 세션이 유투브에 공유되었습니다.

* .NET Machine Learning: F# and Accord.NET : Alena Hall이 2015 센프란시스코에서 있었던 Qcon 세미나에서 .NET 환경에서 개발된 라이브러리인 Accord.NET을 이용해서 사용할 수 는 머신러닝 알고리즘과 F#을 이용하여 이 알고리즘들을 사용방법을 소개했습니다. 당시 녹화된 세션의 동영상이 infoq 사이트에 공유 되었습니다.

* Functional Reactive Programming with NUI, : Riccardo Terrell이 F#을 이용한 반응형 NUI(Network User Interface)프로그램의 구현 방법을 공유했습니다.

* GPUs and Domain Specific Languages for Life Insurance Modeling : 저번 주 소개되었던 Daniel Egloff 의 DSL(domain-specific language) 과 GPU 를 이용한 생명보험 업무모델  F# 개발 경험담이 nvidia의 개발자 블로그에도 공유되었습니다.

* Earthquake Scraping with a Type Provider, : Edgar Sánchez이 F#의 HTML Type Provider를 이용하여 현재 웹에서 제공되는 지진계측 자료를 효과적으로 수집하는 예를 공유하였습니다

* Functional Architecture is Ports and Adapters, : Mark Seemann가 Functional Architecture가 일반적인 개발 방법론 중 업무로직과 그것의 기술적인 구현을 분리 한다는 개념인 Ports, Adapters architecture(혹은 layered architecture)에 얼마나 적합하고 잘 맞는지 설명해 주었습니다.

### Games
* Crytek Unveils All-New CRYENGINE V and Community-Centered “Pay What You Want” Model (Now Includes C# Support)
* Enhanced Visuals, Better Performance, And More: The Unity 5.4 Public Beta is Ready For You to Download : Alex Lian이 향상된 버전의 Unity 5.4 공개 배타 버전을 다운 받을 수 있는 링크와 새로운 기능을 소개 했습니다. 
* MonoGame 3.5 : Dean Ellis 가 MonoGame 3.5 를 다운받을 수 있는 링크와 릴리즈 소식을 공유 했습니다. 
* Unity Special Event at GDC (Video) : San Francisco에서 있었던 GDC  2016 세미나에서 Unity의 특별 세션이 있었으며 녹화된 세션의 비디오가 유투브에 공유되었습니다.
