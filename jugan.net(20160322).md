이번 주에는 많은 개발자의 가슴을 두근거리게 할 마이크로소프트의 개발자 행사인 //Build/ 2016 가 있습니다. 샌프란시스코 모스콘 센터에서 3월30일부터 4월1일까지 개최되는 이번 행사를 라이브로 시청하시려면(한국시간 3월 31일(목) 새벽 00:30) http://build.microsoft.com 을 방문해 보시기 바랍니다. 한국에서도 3월31일(목) 저녁 무렵에 “빌드 같이 보기” 행사가 있을 예정입니다. 참가를 희망하시는 분은 http://aka.ms/build2016live 를 통해 등록하시기 바랍니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### Build 소식
이번 주 수요일부터 시작되는 [Build](https://build.microsoft.com/) 행사로 저희 팀원들이 샌프란시스코에 머무를 예정입니다. Build 행사에서 많은 분을 뵙고 .NET 의 최신 소식을 전해드리겠습니다. 행사에 직접 참여하지 못하시더라도 생방송으로 keynote 세션을 시청하실 수 있으며, [Channel 9](https://channel9.msdn.com/Events/Build) 에서 녹화된 세션들을 확인하실 수 있습니다. 한국에서도 김명신 기술 에반젤리스트가 참석하셔서 현장의 발표 내용을 공유 해주실 예정입니다. 

### On.NET 소식
지난번에는 동영상 인터뷰가 없었습니다. [이번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=v5YUoeFCoe8)는 쿨라우드 서비스 제공 업체인 Joyent 에서 엔지니어로 근무하고 계시는 Richard Kiene 를 모시고 CoreCLR 과 ASP.NET 을 이용하여 서비스를 개발한 경험에 대해 이야기를 나누었습니다. 

### 금주의 툴 - Octopus Deploy
Octopus Deploy 는 지속 통합(Continuous Integration)과 지속 배포(Continuous Deployment)를 도와주는 유용한 도구입니다. 이를 이용하면 테스트 서버, 스테이징 서버(국내환경에서는 흔히 QA 서버라도 합니다), 운영서버에 이르기까지 다양한 서버에 손쉽게 배포 작업을 수행하실 수 있습니다. 사용하기 편리하여 작은 변경사항도 쉽게 변경하고 좀더 자주 배포할 수 있으며 결과적으로 서버 어플리케이션의 품질 향상에 도움이 될 것 입니다. Octopus Deploy 는 상업용 제품이지만 소규모 팀(5개 이하의 프로젝트로 조합된 결과물을 10개 미만의 서버에 배포하는 경우)에게는 무료로 제공됩니다.

* [Octopus Deploy](https://octopus.com/)

image

### .NET 소식
* [The Sound of .NET](http://thesoundof.net/) : .NET 과 관련된 팟캐스트 목록을 한눈에 확인하실 수 있습니다. 

* Erik Bergman 이 .NET 에도 적용된 병렬처리에 대해 [part 1](http://www.erikbergman.net/2016/03/10/high-speed-applications-parallelism-in-net-part-1/) 과 [part 2](http://www.erikbergman.net/2016/03/17/high-speed-applications-parallelism-in-net-part-2/) 에 걸쳐서 설명했습니다.

* [Peachpie – the PHP Compiler for .NET](http://blog.peachpie.io/2016/03/intro.html?m=1) : Benjamin Fistein 이 .NET 용 PHP 컴파일러인 Peachpie 를 소개했습니다.

* [LINQPad.QueryPlanVisualizer](http://www.aboutmycode.com/miscellaneous/introducing-linqpad-queryplanvisualizer/) : 많은 개발자분들이 개발할 때 LINQPad 를 사용하고 계십니다. Giorgi Dalakishvili 가 쿼리의 실행 계획을 바로 확인할 수 있도록 도와주는 LINQPad 의 에드온인 QueryPlanVisualizer 를 소개했습니다.

* [NBench Performance Testing – NUnit and ReSharper Integration](http://www.dotnetalgorithms.com/2016/03/nbench-performance-testing-nunit-resharper-integration/) : Andrea Angella 가 성능 측정 도구인 Nbench 가 core library 에 포함되었다는 소식을 전했습니다. 또한, NUnit 과 ReSharper 를 이용한 테스트 방법을 소개했습니다. 

### ASP.NET 소식
* Joe Audette 가 ASP.NET Core 에서 동작하는 블로그 엔진인 [cloudscribe SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) 의 초기버전을 github 에 공유하였습니다

* [First Look: Authentication in ASP.NET Core (video)](https://blogs.msdn.microsoft.com/webdev/2016/03/11/first-look-authentication-in-asp-net-core/) : ASP.NET Core 의 업데이트 및 인증 시스템 개선에 대해 리포터 Seth Juarez 가 ASP.NET 프로그램 매니저인 Pranav Rastogi 와 이야기를 나누었습니다. 

* [Extending the ASP.NET Core 1.0 Identity SignInManager](http://stevejgordon.co.uk/extending-the-asp-net-core-identity-signinmanager) : Steve Gordon 이 ASP.NET Core 1.0 의 인증 라이브러리인 SignInManager 클래스를 확장하여 사용했던 경험을 공유했습니다.

* Lachlan Barclay 가 ASP.NET's Identity 와 Google 의 Authenticator App 을 이용하여 ASP.NET 에서 이중 인증 시스템을 구현한 사례를 [part 1](http://lachlanbarclay.net/2016/02/asp-dot-net-two-factor-auth-with-google-authenticator-app), [part 2](http://lachlanbarclay.net/2016/02/asp-dot-net-two-factor-auth-with-google-authenticator-app-part-2) 로 나누어 설명했습니다.

* [ASP.NET Web API / OWIN authenticated integration tests without authorization server](http://blogs.taiga.nl/martijn/2016/03/10/asp-net-web-api-owin-authenticated-integration-tests-without-authorization-server/) : Martijn Boland 가 ASP.NET Web API OWIN(Open Web Interface for .NET) 애플리케이션 개발시 인증 서버 구축이나 설정 없이도 [Microsoft.Owin.Testing.TestServer](https://blogs.msdn.microsoft.com/webdev/2013/11/26/unit-testing-owin-applications-using-testserver/) 를 이용하여 인증을  테스트하는 방법을 공유했습니다.

* [Integrating ASP.NET Core Configuration in MVC 4](http://scottdorman.github.io/2016/03/19/integrating-asp.net-core-configuration-in-mvc-4/), [Integrating ASP.NET Core Dependency Injection in MVC 4](http://geekswithblogs.net/sdorman/archive/2016/03/17/integrating-asp.net-core-dependency-injection-in-mvc-4.aspx) : Scott Dorman 이 다양한 형식과 환경변수를 지원하는 ASP.NET Core 의 Configuration 사용법과 의존성 주입 방법을 ASP.NET MVC 4 프로젝트를 이용하여 설명했습니다.

* [Using Specflow to test Web API](http://www.codeproject.com/Articles/1086520/Using-Specflow-to-test-Web-API-PART) : Veronica S. Zotali 이 테스트 자동화 라이브러리인 Specflow 를 이용하여 Web API 를 테스트 하는 예제를 codeproject 사이트에 공유했습니다.

* [Logging basics in ASP.NET Core (video)](http://aspnetmonsters.com/2016/03/monsters-weekly%5Cep16/) : ASP.NET Monsters 사이트의 이번 주 소식으로 애플리케이션에 문제가 생긴 경우 그 원인을 찾는데 도움이 되는 Logging 을 설명하는 동영상이 소개되었습니다.

* [Content Negotiation in ASP.NET Core](http://wildermuth.com/2016/03/16/Content_Negotiation_in_ASP_NET_Core) : Shawn Wildermuth 이 ASP.NET Core 에서 사용자 요청의 결과가 XML 이나 JSON 과 같이 정해진 타입(strong type)인 경우에 발생하는 문제점과 Content Negotiation(가변적인 result type을 유연하게 반환하도록 돕는)을 사용하여 이를 해결하는 방법을 공유했습니다.

### F# 소식
* [Building Reactive Services Using Functional Programming](https://www.youtube.com/watch?v=lK-VhOOjxN8) : Rachel Reese 가 Lambda Days 2016 행사에서 함수형 프로그래밍 언어의 다양한 기능을 이용하여 반응형 서비스를 개발하는 것을 소개했습니다.

* [.NET Machine Learning: F# and Accord.NET](http://www.infoq.com/presentations/accord-net-machine-learning) : Alena Hall 이 QCon 세미나에서 다양한 머신러닝 알고리즘을 이용할 수 있는 Accord.NET Framework 를 소개한 후, 예제 문제를 Accord.NET 및 F# 환경에서 머신러닝 알고리즘을 적용하여 해결하는 방법을 소개했습니다. 

* [Functional Reactive Programming with NUI](https://www.youtube.com/watch?v=AU2LT18SFP8) : Riccardo Terrell 이 F# 을 이용하여 NUI(Natural User Interface) 를 효과적으로 구현하는 것을 소개했습니다.

* [GPUs and Domain Specific Languages for Life Insurance Modeling](https://devblogs.nvidia.com/parallelforall/gpus-dsls-life-insurance-modeling/) : 지난주에 소개되었던 Daniel Egloff 의 GPU 와 DSL을 이용하여 생명보험 업무모델을 개발했던 경험이 NVIDIA 개발자 블로그에도 소개되었습니다.

* [Earthquake Scraping with a Type Provider](https://cogitoergofun.ghost.io/earthquake-scrapping-with-a-type-provider/) : Edgar Sánchez 이 F# 의 HTML Type Provider 를 이용하여 웹에서 제공되는 지진계측 자료를 효과적으로 수집하는 예를 공유하였습니다.

* [Functional Architecture is Ports and Adapters](http://blog.ploeh.dk/2016/03/18/functional-architecture-is-ports-and-adapters/) : Mark Seemann 가 함수형 언어를 이용하여 업무로직과 기술적으로 구현하는 것을 분리하는 개념인 Ports 와 Adapters 구조를 쉽게 갖출 수 있음을 설명했습니다.

### Games
* Crytek 이 GDC(Game Developers Conference) 콘퍼런스에서 원하는 만큼만 지불하는 새로운 사업모델을 가지고, C# 지원이 추가된 [CRYENGINE V](http://www.crytek.com/news/crytek-unveils-all-new-cryengine-v-and-community-centered--pay-what-you-want--model) 을 소개했습니다. 
* [Enhanced Visuals, Better Performance, And More : The Unity 5.4 Public Beta is Ready For You to Download](http://blogs.unity3d.com/2016/03/15/enhanced-visuals-better-performance-and-more-the-unity-5-4-public-beta-is-ready/) : Alex Lian 이 Unity 5.4 의 베타 버전의 새로운 기능을 다운받을 수 있는 링크와 함께 소개했습니다. 
* [MonoGame 3.5](http://www.monogame.net/2016/03/17/monogame-3-5/) : Dean Ellis 가 MonoGame 3.5 릴리즈 소식을 다운받을 수 있는 링크와 함께 공유했습니다. 
* [Unity Special Event at GDC (Video)](https://www.youtube.com/watch?v=eN3PsU_iA80) : GDC 콘퍼런스에서 Unity 특별 세션이 있었습니다.
