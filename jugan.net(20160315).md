지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=DJn8-Psznsw)는 StackOverflow 에서 개발자이자 시스템 관리자로 근무하고 계시는 [Nick Craver](http://nickcraver.com/) 를 모시고 StackOverflow 의 성능에 대해 이야기 나누었습니다. 
많은 개발자들의 사랑을 받고있는 StackOverflow 가 어떻게 빠른 성능과 품질을 유지하는지 궁금하시다면 동영상을 꼭 한번 보시기 바랍니다. 이번주 On.NET 동영상 인터뷰는 예정되어 있지 않은 관계로 생략하겠습니다.

### 금주의 패키지 - Quartz.NET
어플리케이션에서 필요한 백그라운드 job을 스케줄링하고 관리하는 것은 많은 번거로운 코드 작업을 필요로 합니다. 라이브러리 패키지인 Quartz.NET를 이용하면 백그라운드 작업을 효율적으로 관리할 수 있습니다. 스래드풀을 관리하고 job 트리거를 스케줄링하는등의 복잡한 내용을 간단히 완성할 수 있도록 [Quartz.NET](http://www.quartz-scheduler.net/) 은 풍부한 API 를 제공합니다.

<section>
{{QuartzNet.cs}}<script src="https://gist.github.com/bleroy/1f3f752dfebde0e9ae7b.js"></script>
</section>


### .NET 소식
* [Experimental .NET Core Debugging in VS Code](https://blogs.msdn.microsoft.com/visualstudioalm/2016/03/10/experimental-net-core-debugging-in-vs-code/) : Daniel Meixner 이 VS Code 에서 ASP.NET Core 애플리케이션을 디버깅 해주는 ASP.NET Core CLI toolset(현재 프리뷰 버전)을 사용방법과 함께 소개했습니다.
* [Roslyn scripting on CoreCLR (.NET CLI and DNX) and in memory assemblies](http://www.strathweb.com/2016/03/roslyn-scripting-on-coreclr-net-cli-and-dnx-and-in-memory-assemblies/) :  C# 컴파일러 스크립트 API 인 Roslyn 이 CoreCLR 을 포함하여 다중 플렛폼을 지원하게 되었습니다. Filip W 가 CoreCLR 에서 Roslyn 의 사용방법을 공유했습니다.
* [A cross-platform interactive C# script editor](http://www.jayway.com/2016/03/09/interactive-c-script-editor-built-electron-edgejs/) : Rosly n을 이용해서 동적 C# script editor 를 만드는 방법을 Christian Jacobsen 가 공유했습니다.
* [Hamburger controls for UWP](https://www.pedrolamas.com/2016/03/07/cimbalino-toolkit-hamburger-controls-for-uwp/) : Pedro Lamas 가 UWP(Windows Universal Platform) 프로젝트에서 사용할 수 있는 햄버거 버튼 컨트롤을 소개했습니다. 소개되는 햄버거 버튼 컨트롤은 Cimbalino Toolkit 에서 제공되는 컨트롤 중 하나입니다.
* [Using the Project Oxford Emotion API in C# and JavaScript](http://blogs.msdn.com/b/martinkearn/archive/2016/03/07/using-the-project-oxford-emotion-api-in-c-and-javascript.aspx) : Martin Kearn 이 유명한 머신러닝 프로젝트인 "프로젝트 옥스포드" 에서 제공되는 Emotion API 를 소개합니다.

### ASP.NET 소식
* [How to Create a Custom Action Filter in ASP.NET MVC](http://www.infragistics.com/community/blogs/dhananjay_kumar/archive/2016/03/04/how-to-create-a-custom-action-filter-in-asp-net-mvc.aspx) : Dhananjay Kumar 가 ASP.NET MVC 에서 사용자 정의 Action Filter 를 구현하는 방법을 공유하였습니다.
* [Multi-tenant middleware pipelines in ASP.NET Core](http://benfoster.io/blog/aspnet-core-multi-tenant-middleware-pipelines) : Ben Foster 가 ASP.NET Core 의 멀티 테넌트(Multi-Tenant) 환경에서 ASP.NET 인증 미들웨어를 사용할 때 발생할 수 있는 문제점과 해결방법을 소개했습니다.
* [What is middleware anyway?](http://aspnetmonsters.com/2016/03/2016-02-28-what-is-middleware-anyway/) : Simon Timms 이 ASP.NET Core 에서 자주 언급되는 middleware 의 개념을 정리해서 공유했습니다.
* [ASP.NET 5 on Nano Server](http://docs.asp.net/en/latest/tutorials/nano-server.html) : Sourabh Shirhatti 이 서버 코어보다 더 작은 Windows Server 2016 나노 서버(Nano Server) 에서 ASP.NET 5 어플리케이션을 운영하는 방법을 공유했습니다.
* [Use IdentityServer in SwaggerUI to consume a secured ASP.Net WebAPI](http://danielwertheim.se/use-identityserver-in-swaggerui-to-consume-a-secured-asp-net-webapi/) :Daniel Wertheim 이 SwaggerUI 에서 IdentityServer 인증 서버의 ASP.NET 용 WebAPI 를 사용하는 방법을 공유했습니다.
* [Custom Validation in ASP.NET Web API with FluentValidation](http://www.exceptionnotfound.net/custom-validation-in-asp-net-web-api-with-fluentvalidation/) : Matthew Jones 가 FluentValidation 라이브러리 API 를 이용한 사용자 정의 검증 구현 방법을  공유했습니다.
* [Understanding ASP.NET Performance for Reading Incoming Data](http://stackify.com/understanding-asp-net-performance-for-reading-incoming-data/) : Matt Watson이 ASP.NET의 request 수신과 이와 관련된 데이터 성능 측정에 대한 개념적인 이해 및 설명을 공유했습니다.

### F# 소식
* [F# with .NET Core and CLI](https://www.youtube.com/watch?v=_0Q-Q2UeyP0) : Enrico Sada 이 F# 을 이용한 .NET Core 와 CLI 를 사용하는 예와 기존의 .NET 어플리케이션을 .NET Core 로 전환 하는 방법을 유투브 비디오로 공유했습니다.
* [Path to F# and NGO Fraudbuster](https://www.youtube.com/watch?v=nZwQ9JVl-d8&feature=youtu.be) : Jacqueline Homan이 자신의 NGO Fraudbuster app개발에 F#을 사용하게 된 배경과 경험을 공유했습니다.
* [On.NET: F# at Jet.com](https://blogs.msdn.microsoft.com/dotnet/2016/03/08/on-net-332016-rachel-reese-on-f-at-jet-com/) : Rachel Reese 이 F#으로 개발된 전자상거래 웹사이트 Jet.com 의 개발과정을 공유했습니다
* [Converting a DSL to Executable F# Code On-the-Fly, Part 2](http://brandewinder.com/2016/03/06/converting-dsl-to-fsharp-code-part-2/) : Mathias Brandewinder 가 DSL(domain-specific language) 로 작성한 코드를 F# 실행코드로 변환하는 방법 Part 2 를 자신의 블로그에 소개했습니다.
* [GPUs and Domain Specific Languages for Life Insurance Modeling](http://blog.quantalea.com/?p=9321) : Daniel Egloff이 많은 수학적 계산을 필요로 하는 생명보험 업계 업무 모델을 DSL(domain-specific language) 과 GPU 를 이용하여 F#으로 구현하는 예를 공유했습니다.

### Games
* [A Letter from Chris Charla](http://news.xbox.com/2016/03/14/letter-chris-charla-idxbox-updates-gdc/) : Chris Charla 가 ID@Xbox 프로그램 업데이트와 GDC(Game Developers Conference) 소식을 전해왔습니다.
* [Getting Started Creating Editor Extensions in Unity](http://appgoodies.net/unity/getting-started-creating-editor-extensions-in-unity/) : Elmar Talibzade 가 Unity 의 Editor 확장기능을 구현하는 방법을 공유했습니다.

### Game of the week: Overload
[Overload](http://playoverload.com/) 는 Descent 에서 개발한 3차원 슈팅게임입니다. 플레이어는 적 로봇 격파, 인질 구출, 원자로 파괴등의 미션을 수행하고 기지가 파괴되기전에 탈출로를 찾아서 탈출해야 하는 게임입니다. 아직 초기 개발 단계이지만 [이 곳](http://store.steampowered.com/app/450220/)을 통해서 동영상 티저를 확인할 수 있습니다.

image