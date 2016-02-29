이번 주에는 REST 자원을 이용할 때에 유용하게 사용하실 수 있는 RestSharp 라이브러리를 소개합니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=WuqrfuJLbgk)는 Joe Duffy 를 모시고 마이크로소프트가 의욕적으로 진행했었던 차세대 OS 개발 연구 프로젝트인 [Midori](http://joeduffyblog.com/2015/11/03/blogging-about-midori/) 프로젝트에 대해 이야기를 나누었습니다. 

이번 On.NET 유튜브 동영상 인터뷰는 마이크로소프트의 Principal Program Manager 이신 Scott Hanselman 을 모시고 이야기 나누었습니다. 빌드와 같은 세미나에 단골 스피커로 등장하여 익히 알려지신 분이기도 하죠. 인터뷰 동영상은 아직 업로드 되지 않았습니다.  

### 금주의 패키지 – RestSharp     
이론적으로는 표준 HTTP 만을 사용하여 웹 REST 자원을 활용하는 것이 가능해 보일지는 몰라도 실제로 프로젝트를 진행하다 보면 객체 직렬화나 웹 사용자 인증과 같이 HTTP 표준 기술만으로는 해결되지 않는 문제들이 있습니다. RestSharp 은 이처럼 REST 자원을 이용할 때 필요한 핵심 기능들을 구현해 둔 유용한 .NET 라이브러리입니다.

아래는 RestSharp 을 이용하여 직원의 정보를 조회하는 가상의 서비스를 구현한 코드입니다.

<section>
{{RestSharp.cs}}<script src="https://gist.github.com/bleroy/8443953a1fd661eb276a.js"></script>
</section>

### .NET 소식
* [An update on ASP.NET Core and .NET Core](https://blogs.msdn.microsoft.com/webdev/2016/02/01/an-update-on-asp-net-core-and-net-core/) : Jeffrey T. Fritz 가 ASP.NET Core 및 .NET Core 의 업데이트된 내용을 공유했습니다.
* [Porting MSBuild to .NET Core](https://blogs.msdn.microsoft.com/dotnet/2016/02/23/porting-msbuild-to-net-core/) : 마이크로소프트 .NET 팀의 Daniel Plaisted 가 .NET Core 용으로 MSBuild 를 수정하면서 겪었던 경험을 공유했습니다.
* [The evolution of interactive C#](http://tirania.org/blog/archive/2016/Feb-17.html) Miguel de Icaza 이 interactive C# shell 의 발전 과정과 향후 목표에 대해 기고했습니다. 
* [SQLite Code First (GitHub)](https://github.com/msallin/SQLiteCodeFirst) :  Marc Sallin 가 SQLite 데이터베이스를 사용할 때에도 엔티티프레임워크(EF)의 code first 기법을 사용할 수 있는 SQLite Code First 라이브러리를 공개했습니다 .
* [Async-Friendly Stack Trace (GitHub)](https://github.com/aelij/AsyncFriendlyStackTrace) : Eli Arbel 이 예외처리 시 발생하는 호출스택 정보(Stack Trace)를 비동기 작업에서도 효과적으로 확인할 수 있게 도와주는 확장클래스를 소개했습니다.
* [Moq on .NET Core](http://dotnetliberty.com/index.php/2016/02/22/moq-on-net-core/) : Armen Shimoon 이 닷넷용 모킹 프레임워크로 잘 알려진 Moq 을 .NET Core 에서 사용할 수 있는 방법을 공유했습니다.

### ASP.NET 소식
* [ASP.NET Core – 2300% More Requests Served Per Second](http://www.ageofascent.com/asp-net-core-exeeds-1-15-million-requests-12-6-gbps/) : Ben Adams 가 기존의 ASP.NET 보다  성능이 향상된 ASP.NET Core 의 성능측정 결과와 그것이 가지는 의의를 공유했습니다.
* [Getting ASP.NET Core running on Ubuntu](http://www.mcrook.com/2016/02/getting-mvc-6-and-net-core-running-on.html) : Ubuntu 에서 ASP.NET Core 를 실행하기 위한 과정을 소개했습니다.
* [ASP.NET Core 1.0 – Create web application using Yeoman and Visual Studio Code](http://www.mithunvp.com/asp-net-core-visual-studio-code-yeoman/) : Mithun Pattankar 가 Visual Studio Code 와 Yeoman 라이브러리를 이용해서 손쉽게 ASP.NET Core 웹 애플리케이션을 만드는 방법을 소개했습니다.
* [How to send email from ASP.NET Core with MailKit](http://stevejgordon.co.uk/how-to-send-emails-in-asp-net-core-1-0) : Steve Gordon 가 ASP.NET Core 웹 애플리케이션에서 MailKit 라이브러리를 이용하여 이메일을 전송하는 법을 공유했습니다 .
* [Writing custom middleware in ASP.NET Core](http://www.exceptionnotfound.net/writing-custom-middleware-in-asp-net-core-1-0/) : Matthew P Jones 가 ASP.NET Core 를 이용해서 커스텀 미들웨어를 제작하는 방법을 소개했습니다.
* [View Components in ASP.NET Core](http://www.mikesdotnetting.com/article/294/view-components-in-asp-net-core-mvc) : Mike Brind 가 ASP.NET Core MVC 에 새롭게 추가된 View Components 의 기능을 소개했습니다.
* [Developing ASP.NET apps in Docker containers](http://blogs.msdn.com/b/stevelasker/archive/2016/02/19/developing-asp-net-apps-in-docker-containers.aspx) : Steve Lasker 가 Docker Tools for Visual Studio 를 이용하여 ASP.NET 애플리케이션을 Docker containers 환경으로 배포하는 방법을 소개했습니다.
* [The cost of routing](https://ayende.com/blog/173282/the-cost-of-routing?Key=5236b9ce-234e-4255-b25b-98de4068dc93) : Ayende Rahien가 MVC / WebAPI 환경에서 웹 라우팅 성능 밴치마킹 결과를 공유했습니다.
* [Two Razor view errors you might be doing too](http://codeclimber.net.nz/archive/2016/02/19/Two-Razor-view-errors-you-might-be-doing-too.aspx) : Simone Chiaretta 가 ASP.NET MVC Razor 개발환경에서 발생할 수 있는 두 가지 예외사항에 대한 해결책을 공유했습니다.

### F# 소식
* [fsharpConf 2016](http://fsharpconf.com/) is live on Channel 9 on March 4th : F# 컨퍼런스인 fsharpConf 2016가 3월 4일 Channel 9 에서 라이브 중계됩니다. 지금 발표자들을 확인해 보세요!
* [Ionide and the State of F# Open Source Development](https://www.youtube.com/watch?v=JWe1pOeh84U&feature=youtu.be) : Krzysztof Cieślak 이 F# 오픈소스 프로젝트인 Ionide 에 대해 소개했습니다. 
* [Building Concurrent, Fault-tolerant, Scalable Applications in F# Using Akka.NET](https://www.youtube.com/watch?v=gwWS1e0f-L0&feature=youtu.be) : Riccardo Terrell 가 Akka.NET 을 이용하여 Fault-tolerant 를 지원하고 확장성이 뛰어나며  고가용성을 가진 F# 애플리케이션을 만드는 방법을 소개했습니다.
* [Domain Modeling with Types](https://www.youtube.com/watch?v=970nkg60lHs) : Ryan Riley 이 F# 의 도메인 모델링에 대해 설명합니다. 
* [Managing RabbitMQ Messages with F# and Akka.NET](http://miles.no/blogg/managing-rabbitmq-messages-with-f-and-akkanet) : Vagif Abilov 이 F# 에서 Akka.NET 을 이용한 Managing RabbitMQ 사용방법을 공유했습니다.
* [Benchmarking IEnumerables in F# – Seq.timed](http://latkin.org/blog/2016/02/08/benchmarking-ienumerables-in-f-seq-timed/) : Lincoln Atkinson 이 F# 의 IEnumerables 타입 성능비교 결과를 공유했습니다.
* [Types + Properties = Software: Designing with Types](http://blog.ploeh.dk/2016/02/10/types-properties-software-designing-with-types/) : Mark Seemann 가 F# 에서 Type 을 설계하는 방법을 공유했습니다. 
* [F# Will Solve Your Everyday Problem Without a Headache](http://blog.2mas.xyz/fsharp-will-solve-your-everyday-problem-without-a-headache/) : Tomas Jansson 이 FSM(Finite State Machine)을 이용하여 다른 언어보다 문제를 효과적으로 해결할 수 있음을 예제와 함께 소개합니다. 

### Game 소식
* [Unity 5.3.3 Release](http://unity3d.com/unity/whats-new/unity-5.3.3) : Unity 버전 5.3.3 이 발표되었습니다. 지금 확인해보세요! 
* [Intro to Shooter Mechanics](https://blogs.msdn.microsoft.com/dotnet/2016/02/23/the-week-in-net-2232016/) : Unity 의 Matthew Schell 가 진행하는 Unity 교육이 2/23 부터 2/29 까지 이틀간 라이브로 진행되었습니다.
* [Introduction to Scriptable Objects](http://unity3d.com/learn/tutorials/modules/beginner/live-training-archive/scriptable-objects) : Unity 의 Adam Buckner 가 진행했던 교육을 다시 시청하실 수 있습니다.