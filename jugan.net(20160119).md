지난호의 Facebook 주간닷넷 페이지 도달 수가 10,000을 넘었습니다. 지속적인 관심 부탁 드리며 앞으로도 알찬 소식 전할 수 있도록 노력하겠습니다. 지난호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

[지난번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=pwdxfY2Y2Ow)에는 Jonathan Chambers 를 모시고 Unity 에 관해 이야기 나누는 시간을 가졌습니다. 이번 주 [On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=aWnmzrCvTbg)는 Don Syme 과 함께 F# 에 대해서 이야기를 나누었습니다. 

### 금주의 패키지 #1 – NATS client

마이크로서비스와 IoT는 접속자가 많아서 고속의 안정적인 통신이 가능한 분산환경을 요구합니다. [NATS](http://nats.io/) 는 이러한 요구사항을 만족시키는 고성능의 클라우드 기반 메시징 시스템으로 유명한데요. [NATS](http://nats.io/) 의 닷넷 용 클라이언트 라이브러리는 초당 3백만 개의 메시지를 처리할 수 있습니다.

* [A C# Client for NATS](https://github.com/nats-io/csnats)

다음 코드는 "foo" 라는 범주에 속한 객체를 메시지 버스에 보내는 방법을 보여줍니다.

<section>
{{NatsPublish.cs}} <script src="https://gist.github.com/bleroy/df2b3d46a18146a561c6#file-natspublish-cs"></script>
</section>

이 메시지를 처리하는 쪽에서는 "foo" 범주에 속한 메시지들을 비동기적으로 전달받아 처리합니다.

<section>
{{NatsSubscribe.cs}} <script src="https://gist.github.com/bleroy/40b1953dd6940b2493a0#file-natssubscribe-cs"></script>
</section>

NATS 의 닷넷 클라이언트에 대한 보다 자세한 정보는 [NATS In Microsoft .NET](http://nats.io/blog/nats-in-dotnet/) 에서 확인하시기 바랍니다. 

### 금주의 패키지 #2 – VerbalExpressions

정규 표현식을 쓰고, 읽고, 디버깅하는 작업은 쉽지 않습니다. 이렇듯 정규 표현식은 사용하기 어렵지만 매우 강력한 도메인 특화 언어(DSL: Domain Specific Language)라는 장점이 있습니다. VerbalExpressions 라이브러리는 정규 표현식을 사용하기 쉬운 표현 구문으로 구성해 주는 역할을 합니다.

* [VerbalExpressions](https://github.com/VerbalExpressions/CSharpVerbalExpressions)

<section>
{{VerbalExpressions.cs}} <script src="https://gist.github.com/bleroy/fa1520b664f15d3db8e0#file-verbalexpressions-cs"></script>
</section>

정규 표현식 문법을 사용하셔도 되지만, VerbalExpressions 을 이용하시면 좀 더 가독성이 뛰어난 코드를 만드실 수 있습니다.

### 금주의 비주얼 스튜디오 플러그인 - Alive

[Alive 플러그인](https://comealive.io/)은 타이핑 시 변경되는 코드를 시각화해주는 멋진 도구입니다.

* [Basic operation of Alive for Visual studio](https://youtu.be/PZni_54s0o4)

### .NET 소식

* [Introducing ASP.NET Core 1.0 and .NET Core 1.0](http://www.hanselman.com/blog/ASPNET5IsDeadIntroducingASPNETCore10AndNETCore10.aspx) : ASP.NET 5, .NET Core 5 의 이름이 각각 ASP.NET Core 1.0, .NET Core 1.0 으로 바뀌었습니다. Scott Hanselman 이 이를 소개합니다. 
* [Learn Roslyn now: the Emit API](https://joshvarty.wordpress.com/2016/01/16/learn-roslyn-now-part-16-the-emit-api/) : Josh Varty 가 Roslyn 의 컴파일 결과물을 디스크나 메모리에 출력할 때 사용할 수 있는 Emit API 를 설명합니다.
* [NBench performance testing code throughput](http://www.dotnetalgorithms.com/2016/01/nbench-performance-testing-code-throughput/) : Andrea Angella 가 [2주 전에 Petabridge 에서 소개한 NBench](https://petabridge.com/blog/introduction-to-nbench/) 를 자신만의 방식으로 설명합니다.
* [비주얼 스튜디오 플러그 인 - VS Constructor Field Refactoring](https://github.com/sebastienros/vsconstructorfield/releases) : Sébastien Ros 가 생성자 기반의 의존성 주입 플러그인을 제작해 소스코드와 함께 공개했습니다.
* [How to optimize JSON.NET serialization performance](http://www.tomdupont.net/2016/01/how-to-optimize-jsonnet-serialization.html) : Tom DuPont 는 리플렉션이 아닌, 사용자 정의 JsonConverter 를 이용해 Json.NET 의 성능을 개선하는 팁을 공유했습니다.
* [.NET method inlining and loops](http://www.codeproject.com/Tips/1072041/NET-Methods-Inlining-and-Loops) : 릴리즈 빌드로 인한 장점으로 코드의 인라인을 통한 성능 향상이 있습니다. Dmitry Orzhevsky 가 자신이 직접 코드를 테스트해보면서 발견한 루프 문에서의 인라인 규칙을 설명합니다.

### ASP.NET 소식

* [What's New with ASP.NET MVC 6](https://rewards.msdn.microsoft.com/Challenge/804434af-9658-4ff1-8746-76fcfdf27132) : Ugo Lattanzi 는 ASP.NET MVC 6 의 변화를 영상을 통해 소개합니다.
* [Using an ASP.NET module to debug async calls](http://blogs.msdn.com/b/webdev/archive/2015/12/29/using-asp-net-module-to-debug-async-calls.aspx) : Xing (Shin) Mao 는 TPLEventListenerModule 을 이용해 비동기 호출을 디버깅할 수 있는 방법을 설명합니다.
* [Setting up ASP.NET v5 (vNext) to use JWT tokens (using OpenIddict)](http://capesean.co.za/blog/asp-net-5-jwt-tokens/) : Capesean은 ASP.NET v5 에서 JWT 토큰을 사용하는 방법을 설명합니다. (참고로 JWT 토큰은 인증 당사자 간 클레임의 표현을 안전하게 만드는 방법에 관한 공개된 업계 표준으로 현재 RFC 7519 에 명세되어 있습니다.)
* [Configuring SQL Server for session state in MVC 6](http://www.mikesdotnetting.com/Article/292/configuring-sql-server-for-session-state-in-mvc-6) : Mike Brind 는 MVC 6 환경에서 세션 상태를 SQL 서버를 이용해 공유하기 위한 설정 방법을 소개합니다. 
* [Develop ReactJS + ASP.NET Web API apps in Visual Studio 2015](http://blogs.taiga.nl/martijn/2015/12/10/develop-reactjs-asp-net-web-api-apps-in-visual-studio-2015/) : Martijn Boland 는 비주얼 스튜디오 2015에서 ReactJS 와 ASP.NET Web API 응용 프로그램을 개발한 경험담을 소개합니다.
* [ASP.NET 5 MVC 6 file upload with Sql Server FileTable](http://damienbod.com/2015/12/05/asp-net-5-mvc-6-file-upload-with-ms-sql-server-filetable/) : Damien Bod 는 ASP.NET 5 MVC 6 기반의 환경에서 SQL 서버의 파일 테이블에 직접 파일을 업로드 하는 방법을 설명합니다.
* [Running the KestrelHttpServer on Linux with CoreCLR](http://mikehadlow.blogspot.co.uk/2016/01/running-kestrelhttpserver-on-linux-with.html) : Mike Hadlow 는 리눅스 운영체제 상에서 CoreCLR 로 KestrelHttpServer 웹 서버를 구동하는 방법을 설명합니다.

### F# 소식

* [Build proto-compiler using coreclr based LKG](https://github.com/Microsoft/visualfsharp/pull/850) : 닷넷 Core 기반의 F# 컴파일러가 오픈 소스 F# 컴파일러를 고려하기 시작했습니다.
* [preliminary support for F# in the new dotnet CLI.](https://twitter.com/VisualFSharp/status/684470596810358785) : Erico Sada 가 dotnet CLI 에 F# 지원을 추가했습니다.
* [merging part of the F# Compiler Service](https://github.com/Microsoft/visualfsharp/pull/853) : Don Syme 이 현재 F# 컴파일러 서비스 기능을 Visual F# 컴파일러에 반영하고 있습니다. 
* [Suave v1.0.0](https://github.com/SuaveIO/suave/releases/tag/v1.0.0) : Suave 가 개발중인 경량의 F# 웹 개발 라이브러리 버전이 1.0이 되었습니다.
* Riccardo Terrell의 [Building Concurrent, Fault-tolerant, Scalable Applications in F# with Akka.NET](https://www.youtube.com/watch?v=gwWS1e0f-L0&list=PLE7tQUdRKcybh21_zOg8_y4f2oMKDHpUS&index=20)
* Reid Evans의 [A Developer's Journey from OO to Functional](http://reidev275.github.io/ReducingDeveloperFriction/#/)
* Scott Wlaschin의 [Designing with Capabilities](http://fsharpforfunandprofit.com/cap/)
* Isaac Abraham의 [Freeing Your Azure Data with F# Type Providers](https://blogs.msdn.microsoft.com/mvpawardprogram/2016/01/05/freeing-your-azure-data-with-f-type-providers/)


