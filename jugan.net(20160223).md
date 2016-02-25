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
•ASP.NET Core – 2300% More Requests Served Per Second by Ben Adams.
•Getting ASP.NET Core running on Ubuntu by Michael Crook.
•ASP.NET Core 1.0 – Create web application using Yeoman and Visual Studio Code by Mithun Pattankar.
•How to send email from ASP.NET Core with MailKit
 by Steve Gordon.
•Writing custom middleware in ASP.NET Core by Matthew P Jones.
•View Components in ASP.NET Core by Mike Brind.
•Developing ASP.NET apps in Docker containers by Steve Lasker.
•The cost of routing by Ayende Rahien.
•Two Razor view errors you might be doing too by Simone Chiaretta.

* [Our Major Minor – introducing Umbraco 7.4](http://umbraco.com/follow-us/blog-archive/2016/2/11/our-major-minor-introducing-umbraco-74/) : Niels Hartvig 가 오픈소스 기반 CMS(콘텐츠 관리 시스템)인 Umbraco 7.4 버전의 새로운 기능을 소개합니다.
### F# 소식
• fsharpConf 2016 is live on Channel 9 on March 4th. Check out the lineup of speakers!
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
• Introduction to Scriptable Objects – Recorded Live Training done by Adam Buckner from Unity.
