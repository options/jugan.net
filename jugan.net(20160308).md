### On.NET 소식
[지난번 On.NET 동영상 인터뷰] 지난주는 Rachel Reese를 모시고 F#과 F# 기반의 전자상거래 사이트인 Jet.com 웹사이트 개발에 대해서 얘기 나누었습니다. 이번주는 StackOverflow에 근무하는 Nick Craver와 함께 얘기 나누어 보려고 합니다. 웹사이트 StackOverflow는 닷넷 플렛폼의 C# 뿐 아니라 자바, Python등 여러 개발 언어를 지원하는 개발자 Q&A 사이트입니다. 국내에서도 잘 알려져서 많은 개발자분들이 자주 활용하는 웹사이트중 하나입니다. StackOverflow 사이트는 사이트가 잘 알려진것 많큼이나 하루 트랜잭션도 많은데요, 하루 약 2억건의 request와 또 3TB 크기의 정보가 서버로 수신될정도로(2016 2월 9일 기준) 개발자들이 많이 사용하는 인기있는 사이트 입니다. 이런 대형 웹사이트의 시스템 아키텍쳐와 그 구성등에 대해 개발자 관점에서 Nick Craver와 얘기 나누어 보도록 하겠습니다.

### Project of the week
비영리단체 Humanitarian Toolbox에서 진행하는 allReady 프로젝트는 재난대비/지원과 같은 인도주의적 봉사활동을 좀더 효과적으로  준비 할 수 있도록 도와주기 위해서 디자인된 프로젝트입니다. 현재 미국 적십자를 통해서 시카고 지역에 흡연 알람 장치 설치 캠페인에서 초기 테스트중이라고 합니다. 재난발생시 자원봉사자, 지원 물자등을 적절히 분배하고 효과적으로 관리하도록 도와줄 이 프로젝트는 현재 오픈소스 프로젝트으로 진행되고 있으며 ASP.NET Core 기반에 Entity Framework 7을 사용하고 있습니다. 개발자 분들이 재능기부 형태로 이 프로젝트에 많이 참여하고 있습니다.

### .NET 소식
*  리눅스용 SQL Server :  MS SQL Server 드디어 리눅스에서도 구동 가능할 예정이네요. 2017년 중순 정식 버전 릴리즈를 목표로 개발중이며 2016/3/7일 현재 SQL Server의 핵심기능의 프리뷰 버전단계까지 완성되었다고 합니다. 이 소식은 개발자들의 영원한 친구, 빨간티 개발자 Scott Guthrie가 알려왔습니다.

* .NET Framework Compatibility Diagnostics : .NET 팀의 Taylor Southwick가 .NET Framework 호환성 확인 툴을 소개했습니다. 비주얼 스트디오에서 빌드 타겟 버전을 바꿀 때 발생할 수 있는 여러 잠재적인 문제를 미리 알려주는 기능의 툴입니다. 이 툴은 nuget을 통해서 설치할수있는데 일종의 비주얼 스트디오 add on 형태로 사용가능 합니다. 확인 결과 한가지 옥의 티라면  framework version 4.0 이상의  호환성 체크만을 해준다는 것 입니다. 즉 예를 들면 프로젝트의 빌드 타겟 버전을 framework 4.0에서 framework 4.5 나 4.6으로 바꿀 때 발생할 이슈는 감지해 줄 수는 있지만 framework 3.5에서 framework 4.0으로의 호환성 체크는 안된다는 겁니다. 물론 이 툴의 호환성 체크 결과가 완벽할 수 는 없겠지만 그래도 한번쯤 참고하면 도움이 될것 같습니다.

* Bill Wagner가 다음버전 C#에 포함예정인(하지만 확정된것은 아니고 그래서 최종적으로는 제외될수도있는) 일부 기능에 대해서 공유했습니다 

* Daniel Wertheim이 JSON 라이브러인 Newtonsoft JSON.Net에서 Private Setters를 사용할수있도록 도와주는 확장 클래스를  NuGet에 공유했습니다.

* Steve Wilkes가 메서드 호출이나 연산등의 코드를 tree 형태로 가지는 데이터 구조체인 Expression trees를 비주얼 스트디오에서 좀더 알아보기 쉽게 보여 주는 Debug Visualizers와 확장 메서드를 포함한 ReadableExpressions을 공개했습니다.

### ASP.NET 소식
* Simone Chiaretta가 ASP.NET Core 소개 비디오를 channel9에 공개했습니다. 
* Mike Brind가 ASP.NET Core에서 데이터 암호화/복호화 관련  API 사용 방법을 공유했습니다.
* Hossam Barakat이 ASP.NET Core의 Tag Helper기능의 단위테스트 방법과 ASP.NET Core MVC 프로젝트에서 프로젝트 폴더를 좀더 효과적으로 관리할 수 있는 방법을 공유했습니다.
*  SwaggerUI에서 IdentityServer 인증 서버의 ASP.Net용 WebAPI를 사용하는 방법을 공유했습니다.

### F# 소식
* F# 언어가 RFC 단계를 준비 하고 있습니다. F# Language Design RFC Github repo에서 F# 언어 기능에 대한 아이디어 제안, 투표에 참여해 보세요

* .NET Core에서 F#을 좀더 쉽게 사용할 수 있도록 기초 가이드와 셈플이 공개되었습니다. Check out this guide on Github 에서 확인하세요

* Don Syme과 Tomas Petricek이 Welcome to fsharpConf 비디오를 channel9에 공개했습니다.

*  Evelina Gabasova가 The F#orce Awakens (제목 자체는 스타워즈의 포스의 철자 Force와 F#의 F을 잘 섞은 센스있는 제목이네요. 비디오의 실제 내용은 F#의 데이터 분석과 데이터 비주얼라이즈 관련된 것입니다)비디오를 channel9에 공개했습니다.

* Rachel Reese가 Jet.com을 개발하면서 얻은 경험을 토대로  Patterns and Practices for Real-World Event-Driven Microservices 라는 비디오를 channel9에 공개했습니다.

* Sean Trelford가(초등 혹은 중등생정도의 어린 꼬마로 보이네요) Fun and Games with F#라는 제목으로 F# 라이브 코딩 비디오를 공유했습니다. 3D 큐브와 같은 기본적인 3D 객체 그리기에서부터 간단한 게임제작까지 데모를 진행했습니다.  

*  건축가 Goswin Rothenthal가 channel9에 3D CAD 프로그램 Rhino와  F#을 이용한 아부다비 루브르 박물관 설계 경험 사례를 The 3D Geometry of Louvre Abu Dhabi 비디오에 공유했습니다.

* Mark Seeman가 함수 기반언어인 F# 에서 OOP의 속성 개념을 적용해서 개발하는 내용의  Types + Properties = Software 비디오를 channel9에 공개했습니다. 
* Visual Studio code와 Atom editors에서 사용할 수 있는 Cross-platform F# 개발툴인 "Ionide"의 활용법을 이프로젝트의 개발팀 리더인 Krzysztof Cieślak가 비디오 Ionide and Cross-Platform F# Tools를 통해서 소개했습니다.

* Henrik Feldt가 F# Microservices with Logging, Tracing and More on Docker 비디오를 channel9에 공개했습니다.

* Chris Holt가 F#기반의 웹 테스트 라이브러리인 canopy에 대한 비디오 Web UI Automation with F# and Canopy를 channel9에 공유했습니다.

* Rachel Reese이  F# 기반으로 개발된 전자상거래 웹사이트 Jet.com 의 개발과정을 비디오로 channel9에 공유했습니다.

* Android Watch Gesture Recognition with Functional State Machines, by Faisal Waris.

* Alena Hall가 Docker환경에서 F#으로 Cassandra DB를 활용하는 방법을 비디오 F# Awesomeness에서 공유했습니다..

* Yukitoshi Suzuki가 일본의 F# 커뮤니티소식을 F# Community in Japan 비디오에서 소개했습니다.

* Felienne Hermans이 A Boardgame Night with Geeks 비디오를 channel9에 공유했습니다.


* David Stephens와 Tomas Petricek가 라이브 F# 비디오 Q&A를 진행했습니다..
