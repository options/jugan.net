이번주에는 백그라운드 작업을 효율적으로 관리할 수 있는 패키지인 Quartz.NET 을 소개합니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=DJn8-Psznsw)는 StackOverflow 에서 개발자이자 시스템 관리자로 근무하고 계시는 [Nick Craver](http://nickcraver.com/) 를 모시고 StackOverflow 의 성능에 대해 이야기 나누었습니다. 
많은 개발자들의 사랑을 받고있는 StackOverflow 가 어떻게 빠른 성능과 품질을 유지하는지 궁금하시다면 동영상을 꼭 한번 보시기 바랍니다. 이번주 On.NET 동영상 인터뷰는 예정되어 있지 않은 관계로 생략하겠습니다.

### 금주의 패키지 - Quartz.NET
애플리케이션에서 백그라운드 작업을 관리하기위해 많은 번거로운 코드 작업이 필요합니다. 라이브러리 패키지인 Quartz.NET 을 이용하여 백그라운드 작업을 효율적으로 관리할 수 있습니다. [Quartz.NET](http://www.quartz-scheduler.net/) 이 제공하는 풍부한 API 를 이용해 스레드풀을 관리하고 트리거 스케줄링과 같은 복잡한 작업을 간단히 완성할 수 있습니다. 

<section>
{{QuartzNet.cs}}<script src="https://gist.github.com/bleroy/1f3f752dfebde0e9ae7b.js"></script>
</section>


### .NET 소식
* [Experimental .NET Core Debugging in VS Code](https://blogs.msdn.microsoft.com/visualstudioalm/2016/03/10/experimental-net-core-debugging-in-vs-code/) : Daniel Meixner 이 Visual Studio Code 를 이용하여 ASP.NET Core 로 작성된 애플리케이션 디버깅을 지원하는 ASP.NET Core CLI toolset(현재 프리뷰 버전)을 소개했습니다.
* [Roslyn scripting on CoreCLR (.NET CLI and DNX) and in memory assemblies](http://www.strathweb.com/2016/03/roslyn-scripting-on-coreclr-net-cli-and-dnx-and-in-memory-assemblies/) :  C# 컴파일러 스크립트 API 인 Roslyn 은 CoreCLR 을 포함하여 다중 플렛폼을 지원하고 있습니다. Filip W 가 CoreCLR 에서 Roslyn 을 사용하며 겪은 어려움과 해결책을 공유했습니다.
* [A cross-platform interactive C# script editor](http://www.jayway.com/2016/03/09/interactive-c-script-editor-built-electron-edgejs/) : Christian Jacobsen 가 크로스 플랫폼용 데스크탑 애플리케이션으로서 REPL(Read-eval-print loop) 을 만드는 가능성을 공유했습니다. 
* [Hamburger controls for UWP](https://www.pedrolamas.com/2016/03/07/cimbalino-toolkit-hamburger-controls-for-uwp/) : Pedro Lamas 가 UWP(Windows Universal Platform) 프로젝트에서 사용할 수 있는 햄버거 버튼 컨트롤을 소개했습니다. 
* [Using the Project Oxford Emotion API in C# and JavaScript](http://blogs.msdn.com/b/martinkearn/archive/2016/03/07/using-the-project-oxford-emotion-api-in-c-and-javascript.aspx) : Martin Kearn 이 유명한 머신러닝 프로젝트인 Project Oxford 에서 제공되는 Emotion API 를 소개합니다.

### ASP.NET 소식
* [How to Create a Custom Action Filter in ASP.NET MVC](http://www.infragistics.com/community/blogs/dhananjay_kumar/archive/2016/03/04/how-to-create-a-custom-action-filter-in-asp-net-mvc.aspx) : Dhananjay Kumar 가 ASP.NET MVC 에서 사용자 정의 Action Filter 를 구현하는 방법을 공유하였습니다.
* [Multi-tenant middleware pipelines in ASP.NET Core](http://benfoster.io/blog/aspnet-core-multi-tenant-middleware-pipelines) : Ben Foster 가 ASP.NET Core 환경에서 멀티 테넌트(Multi-Tenant) 미들웨어 파이프라인을 설계하는 법을 예제와 함께 소개했습니다.
* [What is middleware anyway?](http://aspnetmonsters.com/2016/03/2016-02-28-what-is-middleware-anyway/) : Simon Timms 이 ASP.NET Core 에서 자주 언급되는 미들웨어의 개념을 정리해서 공유했습니다.
* [ASP.NET 5 on Nano Server](http://docs.asp.net/en/latest/tutorials/nano-server.html) : Sourabh Shirhatti 가 Windows Server 2016 프리뷰에서 공개된 나노 서버(Nano Server) 에서 ASP.NET 5 애플리케이션을 운영하는 방법을 공유했습니다.
* [Use IdentityServer in SwaggerUI to consume a secured ASP.Net WebAPI](http://danielwertheim.se/use-identityserver-in-swaggerui-to-consume-a-secured-asp-net-webapi/) : Daniel Wertheim 이 SwaggerUI 로 부터 API 호출을 이용하여 IdentityServer 를 사용하기 위한 토큰을 받는 방법을 공유했습니다.
* [Custom Validation in ASP.NET Web API with FluentValidation](http://www.exceptionnotfound.net/custom-validation-in-asp-net-web-api-with-fluentvalidation/) : Matthew Jones 가 FluentValidation 라이브러리 API 를 이용한 사용자 정의 검증을 구현했던  공유했습니다.
* [Understanding ASP.NET Performance for Reading Incoming Data](http://stackify.com/understanding-asp-net-performance-for-reading-incoming-data/) : Matt Watson 이 ASP.NET 의 데이터 수신 방법과 측정된 성능을 비교하는 방법을 공유했습니다.

### F# 소식
* [F# with .NET Core and CLI](https://www.youtube.com/watch?v=_0Q-Q2UeyP0) : Enrico Sada 이 .NET Core 와 .NET CLI 를 F# 과 함께 사용하는 방법과 기존의 .NET 애플리케이션을 .NET Core 로 전환하는 방법을 공유했습니다.
* [Path to F# and NGO Fraudbuster](https://www.youtube.com/watch?v=nZwQ9JVl-d8&feature=youtu.be) : Jacqueline Homan 이 NGO Fraudbuster 애플리케이션 개발에 F# 을 사용하게 된 배경과 경험담을 공유했습니다.
* [Converting a DSL to Executable F# Code On-the-Fly, Part 2](http://brandewinder.com/2016/03/06/converting-dsl-to-fsharp-code-part-2/) : Mathias Brandewinder 가 DSL(domain-specific language) 로 작성된 코드를 F# 실행코드로 변환하는 방법을 소개했습니다.
* [GPUs and Domain Specific Languages for Life Insurance Modeling](http://blog.quantalea.com/?p=9321) : Daniel Egloff 이 많은 계산을 필요로 하는 생명보험 업무모델을 DSL(domain-specific language) 과 GPU 를 이용하여 F#으로 구현했던 경험담을 공유했습니다.

### Games
* [A Letter from Chris Charla](http://news.xbox.com/2016/03/14/letter-chris-charla-idxbox-updates-gdc/) : Chris Charla 가 이번으로 GDC(Game Developers Conference) 에 세번 째 출연중인 ID@Xbox 소식을 전해왔습니다.
* [Getting Started Creating Editor Extensions in Unity](http://appgoodies.net/unity/getting-started-creating-editor-extensions-in-unity/) : Elmar Talibzade 가 Unity 의 Editor 확장기능을 구현하는 방법을 공유했습니다.

### Game of the week: Overload
[Overload](http://playoverload.com/) 는 Descent 에서 개발한 3 차원 슈팅게임입니다. 플레이어는 로봇을 격파하고, 인질을 구출하고, 원자로 파괴 미션을 수행한 후 기지가 연기로 뒤덮히기 전에 탈출해야 하는 게임입니다. 아직 초기 개발 단계이지만 [이 곳](http://store.steampowered.com/app/450220/)에서 동영상 티저를 확인할 수 있습니다.

image