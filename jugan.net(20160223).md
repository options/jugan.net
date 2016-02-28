### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=WuqrfuJLbgk)는 Joe Duffy 를 모시고 마이크로소프트가 의욕적으로 진행했었던 차세대 OS 개발 연구 프로젝트인 [Midori](http://joeduffyblog.com/2015/11/03/blogging-about-midori/) 프로젝트에 대해 이야기를 나누었습니다. 

[이번 On.NET 유튜브 동영상 인터뷰]는 국내 개발자들에서도 많이 알려진 분인 마이크로소프트의 Principal Program Manager 인 Scott Hanselman 을 모시고 이야기를 나누었습니다.

### 금주의 패키지 – RestSharp     
이론적으로는 표준 HTTP 만을 사용하여 웹 REST 자원을 서비스에 사용하는 코드를 개발 하는다는 것이 가능해보입니다. 하지만 실무 프로젝트를 하다 보면 HTTP 표준 기술만으로는 해결되지 않는 문제들이 있습니다. 객체 직렬화나 웹 사용자 인증 등과 같은 예를 들 수 있습니다. RestSharp 은 REST 자원을 이용할 때 사용할 수 있는 유용한 .NET 라이브러리입니다.

아래는 RestSharp을 이용하여 가상의 사용자 정보를 조회하는 코드입니다.
<section>
{{RestSharp.cs}}<script src="https://gist.github.com/bleroy/8443953a1fd661eb276a.js"></script>
</section>

### .NET 소식
* [An update on ASP.NET Core and .NET Core](https://blogs.msdn.microsoft.com/webdev/2016/02/01/an-update-on-asp-net-core-and-net-core/) : Jeffrey T. Fritz 가 ASP.NET Core와 .NET Core의 업데이트 내용을 msdn 블로그에 공유했습니다.
* [Porting MSBuild to .NET Core](https://blogs.msdn.microsoft.com/dotnet/2016/02/23/porting-msbuild-to-net-core/) : MS의 .NET Team에있는 Daniel Plaisted가 MSBuild시스템을 .NET Core로 전환한 작업의 과정과 경험을 msdn 블로그에 공유했습니다.
* [The evolution of interactive C#](http://tirania.org/blog/archive/2016/Feb-17.html) by Miguel de Icaza.
* [SQLite Code First (GitHub)](https://github.com/msallin/SQLiteCodeFirst) :  Marc Sallin가 SQLite 데이터베이스 기반에서 엔티티프레임워크(EF)의 code first 방법으로 작업 가능한 SQLite Code First 라이브러리를 GitHub에 공유했습니다 .
* [Async-Friendly Stack Trace (GitHub)](https://github.com/aelij/AsyncFriendlyStackTrace) : Eli Arbel이 예외처리시 발생하는 호출스택 정보(Stack Trace)를 비동기 작업에서도 좀더 효과적으로 보일 수 있도록 도와주는 확장클래스를 공유했습니다.
* [Moq on .NET Core](http://dotnetliberty.com/index.php/2016/02/22/moq-on-net-core/) : Armen Shimoon이 닷넷용 모킹 프레임워크로 잘 알려진 Moq 를 .NET Core 에서 사용할 수 있는 방법을 공유했습니다.

### ASP.NET 소식
* [ASP.NET Core – 2300% More Requests Served Per Second](http://www.ageofascent.com/asp-net-core-exeeds-1-15-million-requests-12-6-gbps/) : Ben Adams 가 기존의 ASP.NET 보다  성능이 향상된 ASP.NET Core 의 성능 측정치 및 측정 결과를 얻는 과정을 공유했습니다.
* [Getting ASP.NET Core running on Ubuntu](http://www.mcrook.com/2016/02/getting-mvc-6-and-net-core-running-on.html) : 우분투 운영체제에서 ASP.NET Core 를 동작시키기 위한 설치및 설정 과정을 공유했습니다 .
* [ASP.NET Core 1.0 – Create web application using Yeoman and Visual Studio Code](http://www.mithunvp.com/asp-net-core-visual-studio-code-yeoman/) : Mithun Pattankar가 Visual Studio Code와 Yeoman 라이브러리를 이용해서 손쉽게  ASP.NET Core 웹 어플리케이션을 만드는 방법을 소개했습니다..
* [How to send email from ASP.NET Core with MailKit](http://stevejgordon.co.uk/how-to-send-emails-in-asp-net-core-1-0) : Steve Gordon가 ASP.NET Core 어플리케이션에서 MailKit을 이용한 이메일 보내는 방법을 공유했습니다 .
* [Writing custom middleware in ASP.NET Core](http://www.exceptionnotfound.net/writing-custom-middleware-in-asp-net-core-1-0/) : Matthew P Jones가 ASP.NET Core를 이용해서 사용자 미들웨어를 제작하는 방법을 소개했습니다.
* [View Components in ASP.NET Core](http://www.mikesdotnetting.com/article/294/view-components-in-asp-net-core-mvc) : Mike Brind가 ASP.NET Core MVC(기존의 MVC 6)에 새롭게 등장한 View Components에 대해서 공유했습니다.
* [Developing ASP.NET apps in Docker containers](http://blogs.msdn.com/b/stevelasker/archive/2016/02/19/developing-asp-net-apps-in-docker-containers.aspx) : Steve Lasker가 Docker Tools for Visual Studio를 이용하여 Docker containers환경에서 ASP.NET 어플리케이션 개발 방법을 소개했습니다.
* [The cost of routing](https://ayende.com/blog/173282/the-cost-of-routing?Key=5236b9ce-234e-4255-b25b-98de4068dc93) : Ayende Rahien가 MVC / WebAPI환경의 웹 라우팅 성능 밴치마킹의 결과를 공유했습니다..
* [Two Razor view errors you might be doing too](http://codeclimber.net.nz/archive/2016/02/19/Two-Razor-view-errors-you-might-be-doing-too.aspx) : Simone Chiaretta가 ASP.NET MVC  Razor 개발환경에서 발생할 수 있는 두가지 예외사항에 대한 해결 경험을 공유했습니다.

### F# 소식
* [fsharpConf 2016](http://fsharpconf.com/) is live on Channel 9 on March 4th : F# 컨퍼런스인 fsharpConf 2016가 3월 4일 Channel 9에서 라이브 중계됩니다. 지금 발표자들을 확인해 보세요
* [Ionide and the State of F# Open Source Development](https://www.youtube.com/watch?v=JWe1pOeh84U&feature=youtu.be) : Krzysztof Cieślak이 F# 오픈소스 프로젝트인 Ionide 에 대한 정보를 동영상으로 공유했습니다.
* [Building Concurrent, Fault-tolerant, Scalable Applications in F# Using Akka.NET](https://www.youtube.com/watch?v=gwWS1e0f-L0&feature=youtu.be) : Riccardo Terrell가 Akka.NET을 이용해서 Fault-tolerant기능을 지원하며  확장성이 뛰어나고 동시성을 이용한 빠른성능및 고가용성을 가진 F# 어플리케이션을 만드는 방법을 동영상으로 공유했습니다
* [Domain Modeling with Types](https://www.youtube.com/watch?v=970nkg60lHs) : Ryan Riley이 F#의 도메인 모델링에 대한 설명을 담은 동영상을 공유했습니다.
* [Managing RabbitMQ Messages with F# and Akka.NET](http://miles.no/blogg/managing-rabbitmq-messages-with-f-and-akkanet) : Vagif Abilov이 F#에서 Akka.NET을 이용한 Managing RabbitMQ 사용 방법을 공유했습니다.
* [Benchmarking IEnumerables in F# – Seq.timed](http://latkin.org/blog/2016/02/08/benchmarking-ienumerables-in-f-seq-timed/) : Lincoln Atkinson이 F#의 IEnumerables 타입 성능비교 결과를 공유했습니다
* [Types + Properties = Software: Designing with Types](http://blog.ploeh.dk/2016/02/10/types-properties-software-designing-with-types/) by Mark Seemann.
* [F# Will Solve Your Everyday Problem Without a Headache](http://blog.2mas.xyz/fsharp-will-solve-your-everyday-problem-without-a-headache/) by Tomas Jansson.

### Game 소식
* [Unity 5.3.3 Release](http://unity3d.com/unity/whats-new/unity-5.3.3) : 유니티 새로운 버전 5.3.3이 발표됐네요. 지금 확인해 보세요
* [Intro to Shooter Mechanics](https://blogs.msdn.microsoft.com/dotnet/2016/02/23/the-week-in-net-2232016/) : 유니티의 Matthew Schell가 2/23일과 2/29일 이틀간 유니티 교육을 라이브로 진행합니다.
* [Introduction to Scriptable Objects](http://unity3d.com/learn/tutorials/modules/beginner/live-training-archive/scriptable-objects) : 유니티의 Adam Buckner가 진행했던 라이브 교육을 다시 보실 수 있습니다.