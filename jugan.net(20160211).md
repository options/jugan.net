이번 주 주간닷넷은 약간 늦었네요, 이점 사과 드립니다. 이번 주는 캘리포니아에 있는 고객을 방문 하느라 좀 바빴습니다. 지금 이 포스팅은 시애틀로 복귀하는 비행기안에서 쓰고 있습니다. 제가 LA에 있는 동안 LADOTNET 커뮤니티 분들과 함께 .NET Core, C# 6, 그리고 향후 C#의 방향에 대해서 얘기를 나누었습니다. 이에 관련된 자료는 이포스팅의 마지막 부분인  .NET 자료 링크에서 확인할 수 있습니다.

###저번주 주간닷넷을 확인 하시려면 이쪽으로 이동하세요(링크)

###On.NET
지난주  On.NET 동영상은 .NET 프로그램 메니지먼트 새 이사인 Scott Hunter 와 함께했습니다. 저의 직속 상관이기도 하죠.

그리고 이번 주는 평소 목요일에 하던 것과는 다르게 금요일 오전 10시에 라이브 방송이 있을 예정입니다. 이번 주는 Aaron Stannard를 모시고 Actor 모델을 바탕으로 한 .NET용 Framework인 Akka.NET 과 Aaron이 진행하는NBench와 DotNetty라는 프로젝트에 대해서 얘기를 나누어 볼까 합니다.

###금주의 패키지 – Polly
분산 어플리케이션 프로젝트가 많이 활성화 되면서 이에 따른 예외 처리작업도 많아지고 또 복잡해 지고 있습니다. 예외 발생시 관련된 오류 자체를 처리하는 것이나 프로그램의 흐름을 제어하는 것은 때로는 생각보다 쉽지 않습니다. 예를 들면 클라이언트 프로그램이 원격 서비스와 통신을 하는경우를 생각해보죠.  개발자는 클라이언트 프로그램이 원격 서비스 접속에 실패할 경우를 대비해서 접속 실패시 일정시간이 지나면 다시 원격 서비스에 재 접속을 시도하는 로직을 구현하려 할 수 있습니다. Polly는 이와 같은 상황에 쉽게 적용할 수 있는 다양한 API들을 제공합니다

await Policy
.Handle<TimeoutException>()
.Or<HttpException>(ex => ex.WebEventCode == WebEventCodes.RuntimeErrorRequestAbort)
.WaitAndRetryAsync(new[] {1.Seconds(), 5.Seconds()})
.ExecuteAsync(() => DoSomethingAsync());
 
###금주의 툴 - DotNetAPIs
DotNetAPIs는 일종의 통합 API 문서 웹 사이트라고 생각하시면 됩니다.  .NET의  수많은 확장API와 라이브러리를 모아놓은 사이트이며 이를 대상으로 검색 가능한 검색엔진이기도 합니다. 이 서비스의 기본 아이디어는 현존하는 모든 NuGet 패키지와 관련된 XML 문서를 하나도 빠짐없이 추출한 후 추출된 자료를 분석하고 이를 바탕으로 웹사이트의 서비스를 제공하는것입니다. 정말 참신하고 좋은 아이디어이며 모든 닷넷 개발자들이 유용하게 사용할 수 있는 툴입니다.

###.NET 소식
*기존 .NET 코드를 .NET Core로 이식하는 내용을 Immo Landwerth이 Porting to .NET Core 에 공유했습니다

*Joe Duffy이 에러의 유형이라는 주제로 자신의 시리즈를 이어가고 있습니다. Joe Duffy의 글입니다.

*What I’ve learned about .NET Native : Mark Rendle은 .NET Native를 접하면서 알게 된 사항들을 공유했습니다

*아래는 Bertrand Le Roy가 이번 주 LADOTNET 커뮤니티에서 발표한 자료입니다.
- .NET Core  
- C# Today and Tomorrow 

*Learn how to use the Windows Event Log via C# : Anton Angelov가  C#을 이용해서 윈도우 이벤트 로그를 활용할 수 있는 방법을 공유했습니다

*Project.json all the things! Oren Novotny이 VisualStudio 2015에서 Project.json을 사용하는 방법과 관련 정보를 공유했습니다. 

*FormatFilter and MediaTypeMappings in ASP.NET Core 1.0 MVC : Filip W.가 ASP.NET Core 1.0 MVC에서 FormatFilter와 MediaTypeMappings를 사용하는 방법을 소개했습니다


###ASP.NET 소식
*The Ultimate Guide To Unit Testing in ASP.NET MVC : Jonathan Danylko가 ASP.NET MVC에서 단위 테스트 구현 및 활용 가이드를 소개했습니다.

*A run around the new ASP.NET Data Protection & Authorization Stacks (video) : Barry Dorrans이 NDC 컨퍼런스에서 ASP.NET 보안관련 세션을 진행했습니다.

*Configuring Redis as the ASP.NET Core session store : Hossam Barakat 이 ASP.NET 에서 사용할 수 있는 in-memory 데이터 엔진인 Redis을 활용 및 설정하는 내용을 공유 했습니다 

*Release management using VSTS  :  Alton CrossleyASP.NET 이 VSTS를 이용한 배포관리 활용법을 공유했습니다.

*A simple authentication library for .NET Core, because sometimes less is more : Joe Audette이 ASP.NET Core에서 데이터베이스 없이도 간단하게 권한 관리를 할 수 있는 라이브러리를 공개했습니다.

*Preventing sensitive data exposure in ASP.NET Part 1, part 2 : Max R McCarty이 ASP.NET 어플리케이션에서 외부에 노출되면 곤란한 민감한 사용자 데이터를 쉽게 관리하고 보호하는 방법을 공유했습니다.

*Great series on multi-tenancy with ASP.NET MVC  : Ben Foster가 ASP.NET에서 Multi-tenancy 웹사이트를 만드는 시리즈를 진행하고 있습니다.

###F# 소식
*The Jet Engine We Built in 2015 :Louie Bacaj가 F# 기반 전자상거래 사이트 jet.com의 개발사례를  공유했습니다.
*Ten Tips for Productive F# Scripting : Mathias Brandewinder가 F# 스크립트에 도움이 되는 10가지 팁을 공유했습니다
*A Cheatsheet for F#’s DSL-friendly Features : Anh-Dung Phan가 F#의 DSL(Domain Specific Languages)관련 기능을 정리해서 공유했습니다.
*Building a Poker Bot: Card Recognition : Mikhail Shilkov가 F#을 이용한 Poker Bot을 만드는 시리즈를 시작했습니다.
*How to Keep the Domain Pure When Logic Depends on the Current Date, : Lauri Taimila가 최대한 현재 날짜에 의존적이지 않은 함수형 프로그램(functional programming) 개발 방법에 대해서 소개했습니다
*F# for Beginners, : Sascha Barbs가 초보자를 위한 F# 정보를 공유했습니다

그 외에 원한다면 F# 커뮤니티 소식을 배포하는 F# Weekly를 통해 더 많은 정보를 얻을 수 있습니다.

###.NET 게임 소식

*Visual Studio Tools for Unity 2.2, : Jb Evain가 업데이트된 Visual Studio Tools for Unity 2.2 내용을 공유했습니다

*Valve Brings SteamVR to Unity, by JP Hawkins.

*Keynote from the Vision Summit 2016. Vision Summit 2016의 키노트를 보실수 있습니다


###Global Game Jam 2016 Submission

 Cannibroth에 있는 작은 부족을 방문한 탐험가가 되어 보세요. 이 부족은 오직 춤으로만 소통합니다. 그래서 게이머도 상황에 맞게 적절한 몸동작을 해야되죠. 만일 그러지 못하면 뜨거운 단지에 담기게되어 그들의 당근요리신세가 될 것입니다.
