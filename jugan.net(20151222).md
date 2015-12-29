지난주 유튜브 [On.NET](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw) 채널의 첫 번째 손님인 Miguel de lcaza를 모시고 [첫 번째 방송](https://www.youtube.com/watch?v=6p6-FMZRiAc)을 즐겁게 촬영했습니다. 닷넷 커뮤니티의 여러 모습을 알고 계신 분들을 모시고 진행할 예정이니, 모시고 싶은 분이 계신다면 알려주세요. 크리스마스 연휴인 관계로 이번 주와 다음 주에는 방송이 없고, 1월 첫째 주부터 다시 시작할 예정입니다. 

[Unity](http://unity3d.com/kr/) 덕분에 최근 들어 게임 개발 커뮤니티에서 닷넷에 대한 관심이 꾸준히 증가하고 있어 이번 주부터는 새롭게 게임 관련 소식도 추가했습니다. 
최신의 닷넷 개발기술을 이용하여 여러분이 선호하시는 플랫폼에서 수행가능한 게임을 개발하는 방법에 대해서 사례 위주로 소개 해 드릴 예정입니다.

이번 주에도 많은 분들께서 보내주신 링크와 팁을 포함하였습니다. 도움을 주신 모든 분께 감사의 말씀을 드립니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 패키지 – Dapper-dot-net

.NET에서 사용할 수 있는 ORM(Object-Relational Mapper)는 제법 많습니다. 그중에서도 Stack Overflow 팀에서 유지 보수 하고 있는 Dapper는 단순한는 접근 방식을 취하고 있는 몇 안되는 ORM입니다. 그 덕분에 성능면에서도 SqlDataReader를 직접 이용해서 코드를 작성했을 때와 유사한 속도를 보일뿐 아니라 Strongly-types API를 제공하고 있습니다.

* [Dapper-dot-net](http://stackexchange.github.io/dapper-dot-net/)

<section>
{{DapperDogSample.cs}} <script src="https://gist.github.com/bleroy/e45aa550b823c71514ef.js"></script>
</section>

겨우 이 정도냐고 하실 분들도 있을 것 같은데요. Dapper를 확장한 [Nuget의 부가 패키지](https://www.nuget.org/packages?q=dapper)들을 보시면 생각이 달라질 수도 있을 것 같습니다.

### .NET 소식

* [WebCamp](https://channel9.msdn.com/Events/Speakers/yongjun-park) : [데브랙](http://devlec.com)의 인기 강사이신 박용준 MVP는 Visual Studio, One ASP.NET, ASP.NET 5과 관련된 내용을 동영상으로 작성하여 공유 해 주셨습니다. 현재 12개의 동영상이 올라가 있고 추가적으로 업데이트 예정이라고 합니다.
* [Getting Started with .NET and Docker](https://blogs.msdn.microsoft.com/mvpawardprogram/2015/12/15/getting-started-with-net-and-docker/) : Elton Stoneman은 .NET Core 기반의 응용 프로그램을 리눅스 도커 컨테이너에 배포 하는 방법을 설명하고 있습니다.
* [The Era of Portable .NET](http://developer.telerik.com/featured/the-era-of-portable-net/) : .NET이 다중 환경을 지원함에 따라 PCL(Portable Class Library) 프로젝트 타입이 더 한층 조명을 받게 되었습니다. 이에 대해 Sam Basu가 자세히 설명하고 있습니다.
* [Raw .NET Data Access / ORM Fetch benchmarks](https://weblogs.asp.net/fbouma/raw-net-data-access-orm-fetch-benchmarks-of-16-dec-2015) : Frans Bouman는 다양한 ORM에 대한 성능 테스트 결과를 공유했습니다.
* [Learn the machine!](https://lenadroid.github.io/posts/machine-learning-fsharp-accorddotnet.html) : Lena Droid는 F# 언어를 이용한 기계 학습에 대한 글을 공유했습니다.

### .NET 게임 소식

게임 관련 첫 소식으로 [Ludum Dare 프로그래밍 컨테스트](http://ludumdare.com/compo/)에 출품된 일부 작품을 소개합니다.

* [Rocks, Maps, Scissors](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=15279) : 전형적인 고전 게임의 하나인 ‘가위, 바위, 보’를 현대식으로 재미있게 구성한 게임입니다.
* [Tile Breaker Evolution](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=63289) : 벽돌이 튀는 방향으로 장애물을 놓아 볼의 방향을 바꾸는 게임으로 꽤나 난이도가 있습니다.  
* [Mobsferatu](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=59414) : Nosferatu에 대항 해 싸워줄 친구들을 모아 안내하는 게임입니다.
* [Growth Industries](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=24965) : 터치 스크린용 게임입니다.

### C# 소식

* [New C# REPL and scripting capabilities](http://bretstateham.com/new-c-repl-and-scripting-capabilities/) : 비주얼 스튜디오 2015 업데이트 1부터 추가된 C# Interactive 창에 대한 사용법을 Bret Stateham이 공유했습니다.
* [Async Linq to objects over MongoDB](http://blog.i3arnon.com/2015/12/16/async-linq-to-objects-over-mongodb/) :  Arnon는 [MongoDB 용 C# 드라이버](https://github.com/mongodb/mongo-csharp-driver)를 비동기 버전으로 완전히 새롭게 개발하였습니다. 이 글을 통해 간략한 사용법을 설명합니다.
* [To String or to string](http://haacked.com/archive/2015/12/16/to-string-or-not/) : C# 언어 사용자라면 누구나 고민해 봤을 문제입니다. System.String 또는 string 중 어떤 것을 사용해야 할까요? Phil Haack이 질문했고 이에 대해 수많은 댓글이 달리고 있습니다.

### F# 소식

* Tomas Jansson의 [F#, Event Sourcing, and CQRS Tutorial...and Agents](http://blog.2mas.xyz/fsharp-event-sourcing-and-cqrs-tutorial-and-agents/)
* Alex Casquete의 [Building a Hypermedia REST API with F# and Suave.io](http://www.casquete.es/building-an-hypermedia-rest-api-with-fsharp-and-suave-io/)
* Evelina Gabasova의 [The Star Wars Social Network](http://evelinag.com/blog/2015/12-15-star-wars-social-network/index.html#.Vm_sTfl96wU)
* Stachu Korick의 [Pseudocode-Driven Development with F#](http://stachu.net/blog/post?postId=6)
* Yan Cui의 [Advent of Code F# - Day 16](http://theburningmonk.com/2015/12/advent-of-code-f-day-16/)
* Paulmichael Blasucci의 [A Mixed-Paradigm Recipe for Exposing Native Code](https://pblasucci.wordpress.com/2015/12/15/advent-drm-adt/)
* Kunjan Dalal의 [1729](http://kunjan.in/2015/12/1729/)
* Jérémie Chassaing의 [Ukulele Fun for Xmas!](http://thinkbeforecoding.com/post/2015/12/17/Ukulele-Fun-for-XMas-%21)
* Anton Tcholakov의 [Using F# for Scientific Instrument Control](https://medium.com/@ant_pt/using-f-for-scientific-instrument-control-b1ef04d20da0#.pmmatrcuk)
* Matt Hawkins의 [REST vs CQRS: The Trigger Problem](http://hawkins6423.github.io/)
* Michael Newton의 [Angels from the Realms of Glory](http://blog.mavnn.co.uk/angels-from-the-realms-of-glory/)
* Steven Pemberton의 [Let it Snow! A Basic Particle System in F# and WPF](http://stevenpemberton.net/blog/2015/12/19/Let-it-snow-FSharp-Advent-2015/)
* Juan Gómez의 [Developing Mobile Apps at the Speed of Light](http://jmgomez.me/advent-calendar-developing-mobile-apps-at-the-spee/)
* Jorge Fioranelli의 [Reactive Messaging Patterns with F# and Akka.NET](http://jorgef.github.io/fsharpreactivepatterns/)

### ASP.NET 소식

* [Tag Helpers in ASP.NET MVC 6](https://blog.mariusschulz.com/2015/12/14/tag-helpers-in-asp-net-mvc-6) : ASP.NET MVC 6에서 사용자 정의 Tag Helpers를 어떻게 작성하는지 Marius Schulz가 설명합니다.
* [ASP.NET 5 MVC 6 API Documentation using Swashbuckle Swagger](http://damienbod.com/2015/12/13/asp-net-5-mvc-6-api-documentation-using-swagger/) : Swagger를 이용해 MVC 6 API를 문서화하는 방법을 damienbod가 설명합니다.
* [What I Learned After A Week of Visual Studio Code and ASP.NET 5](http://www.khalidabuhakmeh.com/what-i-learned-after-a-week-of-visual-studio-code-and-asp-net-5) : Khalid Abuhakmeh가 비주얼 스튜디오 코드 개발도구에서 ASP.NET 5를 사용 해 본 후, 그 경험을 공유 하였습니다.
* [Disabling cryptographic protocols for PCI compliance](http://johnlouros.com/blog/disabling-cryptographic-protocols-for-pci-compliance) : 새롭게 요구되는 PCI(Payment Card Industry) 보안 표준을 위해 특정 암호화 프로토콜을 비활성화하는 방법을 John Louros가 설명합니다.
* [Secure ASP.NET Web API using token-based authentication and using it in an Angular application](http://www.dotnetcurry.com/aspnet/1223/secure-aspnet-web-api-using-tokens-owin-angularjs) : Angular.js와 ASP.NET Web API를 연동할 때 토큰 기반의 인증 처리를 어떻게 해야 하는지 Mahesh Sabnis가 설명합니다.
* [What you need to know about Bootstrap 4](http://www.developerdrive.com/2015/12/what-you-need-to-know-about-bootstrap-4/) : .NET과는 무관하지만 ASP.NET을 이용하여 개발할 때  Bootstrap을 빼놓을 수 는 없을 것입니다. Ezequiel Bruni가 Bootstrap 사용 시 미리 알아야 할 점을 설명합니다.
