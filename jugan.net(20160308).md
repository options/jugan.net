이번 호에는 개발자들이 사랑하는 웹 페이지인 StackOverflow 에서 일하고 계시는 Nick Craver 와의 인터뷰가 실려있습니다. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=4DJWQP2Uxps)는 Rachel Reese 를 모시고 F# 을 이용하여 백앤드를 개발하고 있는 스타트업인 Jet.com 과 F# 에 대해서 이야기 나누었습니다. [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=DJn8-Psznsw)는 StackOverflow 에서 개발자이자 시스템 관리자로 근무하고 계시는 [Nick Craver](http://nickcraver.com/) 를 모시고 StackOverflow 의 성능에 대해 이야기 나누었습니다. StackOverflow 는 개발자들이 질문을 올리고 해결책을 공유하는 웹 사이트 입니다. 국내에서도 많은 개발자 분들이 애용하는 웹사이트 인데요. 하루 약 2억 건의 request 와 3TB 의 정보를 수신 할 정도로 처리하는 트랜잭션의 양도 엄청납니다. 이러한 대형 웹사이트의 시스템 아키텍쳐와 구성에 대해 이야기 나누었습니다.

### Project of the week
자선 단체인 Humanitarian Toolbox 에서 진행하는 allReady 프로젝트는 재난상황을 대비하거나 지원하는 등의 인도주의적 봉사활동을 돕기 위해 기획되었습니다. 현재는 미국 적십자를 통해 시카고 지역의 흡연 알람 장치 설치 캠페인의 초기 테스트를 진행하고 있습니다. 재난발생시 자원봉사자와 지원 물자 등을 적절히 분배하고 효과적으로 관리하도록 도와주는 프로젝트로 현재 오픈소스로 진행되고 있으며, ASP.NET Core 기반의 Entity Framework 7 을 사용하고 있습니다. 현재 많은 개발자들이 재능기부 형식으로 프로젝트에 참여하고 있습니다.

* [allReady](https://github.com/HTBox/allReady)

[image]

### .NET 소식
*  [SQL Server on Linux](https://blogs.microsoft.com/blog/2016/03/07/announcing-sql-server-on-linux/) : 리눅스용 SQL Server :  Microsoft 의 SQL Server 가 리눅스를 지원할 예정입니다. 2017 년 중순에 정식 버전 릴리즈를 목표로 개발 중에 있으며 현재는 프리뷰 버전입니다. 개발자들의 영원한 친구이자 빨간티 개발자로도 유명한 Scott Guthrie 가 이를 소개합니다.

* [.NET Framework Compatibility Diagnostics](https://blogs.msdn.microsoft.com/dotnet/2016/03/03/net-framework-compatibility-diagnostics/) : .NET 팀의 Taylor Southwick 가 .NET Framework 의 호환성을 확인해주는 툴을 소개합니다. 비주얼 스트디오에서 빌드 타겟 버전을 변경할 때 발생할 수 있는 여러 잠재적인 문제를 미리 알려주며, 비주얼 스트디오의 Nuget 패키지를 이용하여 설치 할 수 있습니다. 다만 .NET Framework version 4.0 이후의 호환성만을 체크해줍니다. 

* [C# 7 Feature Proposal: Local Functions](http://thebillwagner.com/Blog/Item/2016-03-02-C7FeatureProposalLocalFunctions) : Bill Wagner 가 C# 7.0 버전에 포함 될 예정인 기능들을 소개했습니다. 

* [JSON.Net Private Setters NuGet](http://danielwertheim.se/json-net-private-setters-nuget/) : Daniel Wertheim 이 JSON 라이브러인 Newtonsoft JSON.Net 에서 Private Setters 의 사용을 도와주는 확장 클래스를 공유했습니다.

* [Friendly, readable expression trees](http://geekswithblogs.net/mrsteve/archive/2016/02/29/friendly-readable-expression-trees-debug-visualizer.aspx) : Steve Wilkes 가 tree 형태로 메서드 호출이나 연산등의 코드를 가지는 데이터 구조체인 Expression trees 를 보기 편하도록 도와주는 Debug Visualizers 를 포함한 확장 메소드인 ReadableExpressions 를 소개했습니다. 

### ASP.NET 소식
* [Introduction to ASP.NET Core (video)](http://codeclimber.net.nz/archive/2016/03/04/Introduction-to-ASP-NET-Core-1-0-video.aspx) : Simone Chiarett 이 ASP.NET Core 의 설치과정 및 ASP.NET Core v1.0 를 이용하여 간단한 웹 사이트를 만드는 방법에 대해 설명했습니다. 
* [Encryption and Decryption in ASP.NET Core](http://www.mikesdotnetting.com/article/295/encryption-and-decryption-in-asp-net-core) : Mike Brind 가 ASP.NET Core 에서 데이터 보호와 관련하여 새롭게 추가된 API 들을 소개했습니다.
* Hossam Barakat 이 [ASP.NET Core 에서의 테스팅 방법 및 Tag Helper 기능](http://hossambarakat.net/2016/02/29/unit-testing-asp-net-core-tag-helper/)과 [ASP.NET Core MVC 프로젝트에서 프로젝트 폴더를 더욱 효과적으로 관리할 수 있는 방법](http://hossambarakat.net/2016/02/16/asp-net-core-mvc-feature-folders/)을 공유했습니다.
* [Use IdentityServer in SwaggerUI to consume a secured ASP.Net WebAPI](http://danielwertheim.se/use-identityserver-in-swaggerui-to-consume-a-secured-asp-net-webapi/) : SwaggerUI 에서 IdentityServer 인증 서버의 ASP.Net 용 WebAPI 를 사용하는 방법을 공유했습니다.

### F# 소식

* F# 언어가 RFC(Request for Comments) 단계를 준비 하고 있습니다. [F# Language Design RFC Github 리파지토리](https://github.com/fsharp/FSharpLangDesign)에서 새로운 기능을 제안하거나 투표에 참여해 보세요.
* .NET Core에서 F#을 좀더 쉽게 사용할 수 있도록 도와주는 안내 문서와 예제 코드가 공개되었습니다. [이 곳](https://github.com/enricosada/fsharp-dotnet-cli-samples/wiki/Getting-Started)에서 확인하세요.
* [Welcome to fsharpConf](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Welcome-to-fsharpConf) : Don Syme 과 Tomas Petricek 이 fsharpConf 의 시작을 알리는 비디오를 Channel9 에 공개했습니다.
* [The F#orce Awakens](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/The-Force-Awakens) : Evelina Gabasova 가 F# 을 이용해 데이터를 처리하고 시각화하는 방법을 소개했습니다. 
* [Patterns and Practices for Real-World Event-Driven Microservices](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Real-World-Microservices) : Rachel Reese가 Jet.com 을 개발하면서 얻은 경험에 비추어 Microservice 를 설명했습니다.
* [Fun and Games with F#](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/DEMO-Fun-and-Games-with-F) : 프로그래밍 언어 중 F# 을 제일 좋아하는 꼬마인 Sean Trelford 의 F# 라이브 코딩 비디오를 소개합니다. 기본적인 3D 모형 그리기에서부터 간단한 게임제작까지 보여줍니다.  
* [The 3D Geometry of Louvre Abu Dhabi](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/The-3D-Geometry-of-Louvre-Abu-Dhabi) : 건축가 Goswin Rothenthal 가 3D CAD App Rhino 와 F# 을 이용하여 아부다비 루브르 박물관을 설계했던 경험을 공유했습니다.
* [Types + Properties = Software](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Types-Properties-Software) : Mark Seeman 이 F# 에서 타입과 속성을 적절히 사용했을때의 강력함을 예제를 통해 보여줍니다. 
* [Ionide and Cross-Platform F# Tools](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/DEMO-Ionide--Cross-platform-F-Tools) : Visual Studio Code 와 Atom editors 에서 사용할 수 있는 F# 개발 툴인 Ionide 의 활용법을 프로젝트 개발팀 리더인 Krzysztof Cieślak 가 소개했습니다.
* [F# Microservices with Logging, Tracing, and More on Docker](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/F-Microservices-with-Logging-Tracing-and-More-on-Docker) : Henrik Feldt 가 [Suave.io](http://suave.io/) 라이브러리를 이용하여 Microservices 아키텍처를 따르는 웹 애플리케이션을 만드는 방법을 소개했습니다. 
* [Web UI Automation with F# and Canopy](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Web-UI-Automation-with-F-and-canopy) : Chris Holt 가 F# 기반의 웹 테스트 라이브러리인 canopy 를 소개했습니다.
* [Using F# at Jet.com](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/INTERVIEW-Using-F-at-Jetcom) : Rachel Reese 이 F# 으로 개발된 전자상거래 웹사이트 Jet.com 의 개발과정을 Channel9 에 공유했습니다.
* [Android Watch Gesture Recognition with Functional State Machines](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Android-Watch-Gesture-Recognition-with-Functional-State-Machines) : Faisal Waris 가 FSM(Finite State Machine) 에 대해 설명하고, 이를 이용하여 동작을 감지하는 안드로이드용 스마트워치 애플리케이션에 대해 소개했습니다.  
* [Cassandra, Docker, and F# Awesomeness](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/Cassandra-Docker-and-F-Awesomeness): Alena Hall 가 Docker 환경에서 F# 으로 Cassandra DB 를 활용하는 방법을 비디오 F# Awesomeness 에서 공유했습니다.
* [F# Community in Japan](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/INTERVIEW-F-Community-in-Japan) : Yukitoshi Suzuki 가 일본의 F# 커뮤니티 소식을 소개했습니다.
* [A Boardgame Night with Geeks](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/A-Boardgame-Night-with-Geeks) : Felienne Hermans 이 A Boardgame Night with Geeks 비디오를 Channel9 에 공유했습니다.
* [Q&A with the Visual F# Team and Community](https://channel9.msdn.com/Events/FSharp-Events/fsharpConf-2016/QA-with-the-F-Team-and-Community) : F# 프로그램 매니저인 David Stephens 와 F# 프로젝트의 오래된 컨트리뷰터인 Tomas Petricek 가 라이브로 F# 에 대한 Q&A 를 진행했습니다.
