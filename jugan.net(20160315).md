### On.NET 소식
지난주는 StackOverflow에서 일하고 계시는 Nick Craver 와의 인터뷰를 실어드렸습니다. 많은 개발자들의 사랑을 받고있는 StackOverflow 웹사이트가 어떻게 빠른 성능과 품질을 유지하는지 궁금하시다면 동영상을 꼭 한번  보시기 바랍니다. 이번주 인터뷰는 예정되있지 않습니다. 따라서 이번주는 On.NET 동영상 인터뷰를 생략하겠습니다.

### Package of the week: Quartz.NET
어플리케이션에서 필요한 백그라운드 job을 스케줄링하고 관리하는 것은 많은 코드 작업을 필요로 합니다. 라이브러리 패키지인 Quartz.NET를 이용하면 이같이 어플리케이션에서 필요한 백그라운드 관련 작업을 효율적으로 관리할 수 있습니다. 스래드풀을 관리하고 job 트리거를 스케줄링하는등의 복잡한 내용을 간단히 완성할 수 있도록 풍부한 API들을 제공합니다.

### .NET 소식
* Experimental .NET Core Debugging in VS Code : Daniel Meixner 가 VS Code에서 ASP.NET Core 어플리케이션을 디버깅 할 수 있도록 해주는 ASP.NET Core CLI toolset(현재 프리뷰 버전)을 사용방법과 함께 소개했습니다
*  Roslyn scripting on CoreCLR (.NET CLI and DNX) and in memory assemblies :  C# 컴파일러 스크립트 API인 Roslyn이 CoreCLR 을 지원합니다. 즉 다중 플렛폼을 지원하게 된것이지요. Filip W가 CoreCLR에서 Roslyn 의 사용방법을 공유했습니다
* A cross-platform interactive C# script editor : Roslyn을 이용해서 동적  C# script editor 을 만드는 방법을 Christian Jacobsen가 공유했습니다.
* Hamburger controls for UWP : UWP(Windows Universal Apps) 프로젝트에서 사용할 수 있는 app 프로젝트에서 사용할 수 있는 햄버거 버튼 컨트롤을 Pedro Lamas가 소개했습니다. 이 햄버거 버튼 컨트롤은 Cimbalino Toolkit 에서 제공되는 컨트롤들중 하나입니다.
* Using the Project Oxford Emotion API in C# and JavaScript : Martin Kearn이 머신러닝 프로젝트로 유명한 "프로젝트 옥스포드"에서 제공되는 Emotion API 를 소개합니다.

### ASP.NET 소식
* How to Create a Custom Action Filter in ASP.NET MVC : Dhananjay Kumar가 ASP.NET MVC에서 사용자 정의 Action Filter를 구현하는 방법을 공유하였습니다.
* Multi-tenant middleware pipelines in ASP.NET Core : Ben Foster가 ASP.NET Core의 멀티 테넌트(Multi-Tenant) 환경에서 ASP.NET Authentication Middleware 사용시 발생할 수 있는 이슈와 해결방법을 소개했습니다.
* What is middleware anyway? : Simon Timms이 ASP.NET Core에서 자주 언급되는 middleware 의 개념을 정리해서 공유했습니다.
* ASP.NET 5 on Nano Server : Sourabh Shirhatti이  서버 코어보다 더 작은 Windows Server 2016 나노 서버(Nano Server)에서 ASP.NET 5 어플리케이션을 운영하는 방법을 ASP.NET 사이트에 공유했습니다.
* Use IdentityServer in SwaggerUI to consume a secured ASP.Net WebAPI :Daniel Wertheim 이 SwaggerUI 에서 IdentityServer 인증 서버의 ASP.NET 용 WebAPI 를 사용하는 방법을 공유했습니다.
* Custom Validation in ASP.NET Web API with FluentValidation : Matthew Jones가 FluentValidation 라이브러리의 API를 이용한 사용자 정의 Validation 구현 방법을  공유했습니다.
* Understanding ASP.NET Performance for Reading Incoming Data : Matt Watson이 ASP.NET의 request 수신과 이와 관련된 데이터 성능 측정에 대한 개념적인 이해 및 설명을 공유했습니다.

### F# 소식
* F# with .NET Core and CLI : Enrico Sada이 F#을 이용해서 .NET Core와 CLI 를 사용하는 예와 기존의 .NET 어플리케이션을 .NET Core로 전환 하는 방법을 유투브 비디오로에 공유했습니다.
* Path to F# and NGO Fraudbuster : Jacqueline Homan이 자신의 NGO Fraudbuster 어플개발에 F#을 사용하게 된 배경과 경험을 공유했습니다.
* On.NET: F# at Jet.com, : Rachel Reese 이 F#으로 개발된 전자상거래 웹사이트 Jet.com 의 개발과정을 공유했습니다
* Converting a DSL to Executable F# Code On-the-Fly, Part 2, : Mathias Brandewinder 가 DSL(domain-specific language) 로 작성한 코드를 F# 실행코드로 변환하는 방법 Part 2를 자신의 블로그에 소개했습니다.
* GPUs and Domain Specific Languages for Life Insurance Modeling : Daniel Egloff이 많은 수학적 계산을 필요로 하는 생명보험 업계 업무 모델을 DSL(domain-specific language) 과 GPU를 이용하여  F#으로 구현하는 예를 공유했습니다.

### Games
* A Letter from Chris Charla: Chris Charla가 ID@Xbox 프로그램 업데이트와 GDC(Game Developers Conference) 소식을 전해왔습니다.
* Getting Started Creating Editor Extensions in Unity : Elmar Talibzade가 Unity의 Editor 확장기능을 구현하는 방법을 공유했습니다.

### Game of the week: Overload

Overload는 Descent에서 개발한 3차원 슈팅게임입니다. 플레이어는 적 로봇을 격파, 인질 구출, 원자로 파괴등의 미션을 수행하고 기지가 파괴되기전에 탈출로 찾아서 탈출하는 게임입니다. 현재 Overload는 아직 초기개발중이며 link를 통해서 미리 동영상 티저를 확인할 수 있습니다.
