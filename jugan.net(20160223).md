### On.NET 소식

[지난번 On.NET 동영상 인터뷰] 지난주는  Joe Duffy와 함께 Midori 프로젝트에 대해서 얘기해봤습니다. 

[이번 On.NET 유튜브 동영상 인터뷰] 이번 주는 MS에서 Principal Program Manager(타이틀 확인필요…)로 계시는 Scott Hanselman을 모시고 얘기 나누도록 하겠습니다. 특히 이 분은 빌드와 같은 세미나에서 자주 스피커로 등장하면서 국내 개발자들에서도 많이 알려진 분이시죠. 

### 금주의 패키지 – RestSharp  
   
웹에있는 REST 자원에 접근하여 해당 서비스를 억세스하고 상호작용하는것은 이론적으로는 표준 HTTP만을 잘사용하면 될것같습니다. 하지만 현실적으로 실무 프로젝트를 하다보면 직열화나 사용자 인증과 같은 것에 대해서 전혀 고민 하지 않을 수는 없습니다. RestSharp은 이와 같이 REST 자원과 상호작용할 때 필요한 기능을 .NET 코드에서 쉽게 사용할 있도록 도와주는 라이브러리입니다.

아래의 코드는 RestSharp을 이용하여 사용자 정보를 조회하는 일반적인 예입니다.
<section>
var client = new RestClient("http://microsoft.com");
var request = new RestRequest("people/{alias}");
var alias = "beleroy";
request.AddUrlSegment("alias", alias);
var person = await client.ExecuteGetTaskAsync<Person>(request).Data;
Console.WriteLine($"{alias} stands for {person.FirstName} {person.LastName}.");
</section>

### .NET 소식

•An update on ASP.NET Core and .NET Core by Jeffrey T. Fritz.
•Porting MSBuild to .NET Core by Daniel Plaisted.
•The evolution of interactive C# by Miguel de Icaza.
•SQLite Code First (GitHub) by Marc Sallin is a library that enables EF code first to work with SQLite databases.
•Async-Friendly Stack Trace (GitHub) by Eli Arbel.
•Moq on .NET Core by Armen Shimoon.

* [A (Hitchhiker's) Guide To The .NET Core Projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/) : Mark Rendle 가 GitHub 에서 .NET Core 프로젝트를 사용하는 방법을 소개했습니다.
* [Run dotnet CLI on unsupported Linux distros with docknet](https://blog.rendle.io/run-dotnet-cli-on-unsupported-linux-distros-with-docknet/) : Mark Rendle는 dontnet CLI 를 공식 지원하지 않는 Linux 배포판에서 docknet 을 이용하는 방법에 대해서 소개하였습니다.
* [.NET Core: Introduction To Microsoft.Data.Sqlite](http://www.c-sharpcorner.com/UploadFile/ranjancse/net-co-introduction-to-microsoft-data-sqlite/) : Ranjan Dailata 가 .NET Core 에서 사용할 수 있는 NuGet 패키지인 Microsoft.Data.Sqlite 를 소개했습니다. 
* [Weak events in .NET using Reactive Extensions](http://www.codeproject.com/Tips/1078183/Weak-events-in-NET-using-Reactive-Extensions-Rx) : Kenneth Haugland 가 Reactive Extensions 을 이용한 Weak events 의 구현과 활용에 대해서 공유했습니다.

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
