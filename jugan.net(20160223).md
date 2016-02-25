### On.NET 소식
[지난번 On.NET 동영상 인터뷰] 지난주는 Joe Duffy와 함께 Midori 프로젝트에 대해서 얘기해봤습니다. 

[이번 On.NET 유튜브 동영상 인터뷰] 이번 주는 MS에서 Principal Program Manager(타이틀 확인필요…)로 계시는 Scott Hanselman을 모시고 얘기 나누도록 하겠습니다. 이 분은 특히 빌드등 개발자 세미나에 자주 스피커로 등장하면서 국내 개발자들에서도 많이 알려진 분이시죠. 

### 금주의 패키지 – RestSharp  
   
웹 REST 자원을 접근해서 서비스에 사용하는 코드를 개발 하는다는것은 이론적으로 표준 HTTP만을 잘 사용하면 될 것 같아보입니다. 하지만 현실은 약간 다르죠, 실무 프로젝트를 하다 보면 순수한 HTTP 표준  기술만으로는 쉽게해결되 않는 문제들이 있죠. 예를 들면  객체 직열화나 웹 사용자 인증등과 같것들은 약간의 고민이 필요한 작업들입니다 RestSharp은 이같이 REST 자원과 상호작용할 때 사용할 수 있는 유용한 여러가지 기능을 제공해주는 .NET 라이브러리입니다.

아래는 사용자 정보를 조회하는 일반적인 코드를 RestSharp을 이용한 예시코드입니다.
<section>
var client = new RestClient("http://microsoft.com");
var request = new RestRequest("people/{alias}");
var alias = "beleroy";
request.AddUrlSegment("alias", alias);
var person = await client.ExecuteGetTaskAsync<Person>(request).Data;
Console.WriteLine($"{alias} stands for {person.FirstName} {person.LastName}.");
</section>

### .NET 소식

* An update on ASP.NET Core and .NET Core : Jeffrey T. Fritz가 ASP.NET Core와 .NET Core의 업데이트 내용을 msdn 블로그에 공유했습니다.
* Porting MSBuild to .NET Core : MS의 .NET Team에있는 Daniel Plaisted가 MSBuild시스템을 .NET Core로 전환한 작업의 과정과 경험을 msdn 블로그에 공유했습니다.
* The evolution of interactive C# by Miguel de Icaza.
* SQLite Code First (GitHub) :  Marc Sallin가 SQLite 데이터베이스 기반에서 엔티티프레임워크(EF)의 code first 방법으로 작업이 가능한 SQLite Code First 라이브러리를 GitHub에 공유했습니다 .
* Async-Friendly Stack Trace (GitHub) : Eli Arbel이 예외처리 시 발생하는 호출스택 정보(Stack Trace)를 비동기 작업에서도 좀더 효과적으로 보일 수 있도록 도와주는 확장클래스를 공유했습니다.
* Moq on .NET Core : Armen Shimoon이 닷넷용 모킹 프레임워크로 잘 알려진 Moq를 .NET Core에서 사용할 수 있는 방법을 공유했습니다 .

### ASP.NET 소식
• ASP.NET Core – 2300% More Requests Served Per Second : Ben Adams가 기존 ASP.NET 보다 성능이 향상된   ASP.NET Core의 성능 측정치와 과정을 공유했습니다.

•Getting ASP.NET Core running on Ubuntu : 우분투 운영체제에서 ASP.NET Core를 동작시키기 위해서 설치및 설정하는 과정을 공유했습니다 .
•ASP.NET Core 1.0 – Create web application using Yeoman and Visual Studio Code : Mithun Pattankar가 Visual Studio Code와 Yeoman 라이브러리를 이용해서 손쉽게  ASP.NET Core 웹 어플리케이션을 만드는 방법을 소개했습니다..
•How to send email from ASP.NET Core with MailKit : Steve Gordon가 ASP.NET Core 어플리케이션에서 MailKit을 이용한 이메일 보내는 방법을 공유했습니다 .
•Writing custom middleware in ASP.NET Core : Matthew P Jones가 ASP.NET Core를 이용해서 사용자 미들웨어를 제작하는 방법을 소개했습니다.
•View Components in ASP.NET Core : Mike Brind가 ASP.NET Core MVC(기존의 MVC 6)에 새롭게 등장한 View Components에 대해서 공유했습니다.
•Developing ASP.NET apps in Docker containers : Steve Lasker가 Docker Tools for Visual Studio를 이용하여 Docker containers환경에서 ASP.NET 어플리케이션을 개발하는 방법을 소개했습니다.
•The cost of routing : Ayende Rahien가 MVC / WebAPI환경의 웹 라우팅 성능 밴치마킹의 결과를 공유했습니다..
•Two Razor view errors you might be doing too : Simone Chiaretta가 ASP.NET MVC  Razor 개발환경에서 발생할 수 있는 두가지 예외사항에 대한 해결 경험을 공유했습니다.

* [Our Major Minor – introducing Umbraco 7.4](http://umbraco.com/follow-us/blog-archive/2016/2/11/our-major-minor-introducing-umbraco-74/) : Niels Hartvig 가 오픈소스 기반 CMS(콘텐츠 관리 시스템)인 Umbraco 7.4 버전의 새로운 기능을 소개합니다.
### F# 소식
• fsharpConf 2016 is live on Channel 9 on March 4th. Check out the lineup of speakers! : F# 컨퍼런스인 fsharpConf 2016가 3월 4일 Channel 9에서 라이브 중계됩니다. 지금 발표자들을 확인해 보세요
• Ionide and the State of F# Open Source Development, by Krzysztof Cieślak.
• Building Concurrent, Fault-tolerant, Scalable Applications in F# Using Akka.NET, by Riccardo Terrell.
• Domain Modeling with Types, by Ryan Riley.
• Managing RabbitMQ Messages with F# and Akka.NET, by Vagif Abilov.
• Benchmarking IEnumerables in F# – Seq.timed, by Lincoln Atkinson.
• Types + Properties = Software: Designing with Types, by Mark Seemann.
• F# Will Solve Your Everyday Problem Without a Headache, by Tomas Jansson.

### Game 소식
• Unity 5.3.3 Release – Release Notes and Download Link
• Intro to Shooter Mechanics – Live Training at 12:00 PST on 2/23 and 2/29, done by Matthew Schell from Unity.

Introduction to Scriptable Objects – Recorded Live Training done by Adam Buckner from Unity.
