### On.NET 소식
지난주에는 게임 프로젝트 진행시 PlayFab를 이용하여 클라우드에서 어떤 서비스의 도움을 얻을 수 있는지 알아보았습니다. 이번주는 3rd Party 컴포넌트 제작사인 Telerik과 이야기 나눠보는 자리를 가져볼까 합니다.

### 금주의 패키지- NUglify
Nuglify는 JavaScript와 CSS의 사용을 최소화 할 수 있도록 해주는 라이브러리입니다. 별도의 외부 라이브러리를 참조를 전혀 필요로 하지 않는 독립적인 라이브러리이며  .NET Core에서 동작합니다.

Code

### 금주의 Xamarin 애플리케이션 - Cinemark
Cinemark는 북미지역을 중심으로 인기 있는 영화 상영관 체인입니다.  년간 약 27억$(3조원)의 매출을 기록하며 약 5,600개의 상영관으로 이루어져 있습니다. 이 기업은 하이브리드 어플리케이션 프레임워크인 Appcelerator과 Sencha Touch에 기반한 자체 모바일 어플리케이션에 만족 하지 않고 새 어플리케이션 개발에 착수했으며 이때  Xamarin 개발 엔진을 선택했습니다. 그 결과 미국 최대 극장 회사에 어울리는 멋진 모바일 어플리케이션이 만들어졌으며 이 어플리케이션을 통한 영화 예약 및 결재 트랜잭션도 증가하였습니다. 

### 금주의 컴포넌트 - SharpDevelop’s WPF Designer
2015녀 10월을 기점으로 SharpDevelop의 WPF 디자이너는 어느 어플리케이션이라도 XAML 연동이 필요하다면 사용가능한  자제적인 독립 컴포넌트(다른 컴포넌트의 일 분분이 아닌)가 되었습니다. 또한 기존에 참조하였던 3rd Party들을 더 이상 사용하지 않음으로써 개발 및 배포 관리도 더욱 용이해졌습니다. 

### 금주의 게임 - Dungeon of the Endless
 Amplitude Studios에서 개발한 Dungeon of the Endless는 Unity 와 C#을 이용하여 개발되었으며 던전 방어 스타일의 게임으로 일종의 로그라이크(Rogue-Like)종류의 게임입니다. 게이머는 혼자 혹은 팀을 이루어 타워를 방어하며 팀을 조종합니다. RPG 형태의 로그라이크 케렉터와 아이템들이 아름답게 잘 구현되어져 있습니다. 플레이어는 Auriga 행성에 충돌한 우주선의 크리스털 파워를 보호하고 탈출의 길을 찾으면서 팀 영웅의 역할 수행을 합니다. Dungeon of the Endless의 각각의 스테이지에는 여러 종류의 몬스터와 악당들이 등장하여 플레이어를 괴롭힙니다 . 이들의 목적은 플레이어가 컨트롤하는 영웅과 우주선의 크리스털 파워를 죽이는 것이며 각각의 스테이지를 클리어 할 때마다  새로운 팀을 꾸릴 수 있는 기회가 주어집니다. 새롭게 구성된 팀으로 다른 던전을 계속 탐험하게 됩니다.

Dungeon of the Endless 은 Steam과 iTunes에서 사용가능하며 자세한 내용은 링크(dungeon-endless)를 확인하시기 바랍니다.


### .NET 소식
* What’s new for the .NET Native Compiler and Runtime in Visual Studio 2015 Update 2 : Stacey Haffner 와 Matthew Whilden가  Visual Studio 2015 Update 2에 포함된 .NET Native Compiler와 Runtime 의 새로운 기능에 대해서 소개했습니다.
*  Introducing the Microsoft .NET Framework Repair Tool Version 1.3 : Rakesh Ranjan Singh가  Microsoft .NET Framework Repair Tool Version 1.3을 소개했습니다.
* How to host your own NuGet server and package feed : Scott Hanselman이 NuGet 서버의 설치와 운영법을 공유했습니다.
* Moq on .NET Core : Armen Shimoon가 .NET Core에서 Moq의 활용법을 소개했습니다.
* Visual Studio Code 1.0 has been released! : Visual Studio Code 1.0 정식버전이 출시되었습니다.

### ASP.NET 소식
* An update on ASP.NET Core 1.0 RC2 : ASP.NET Core 1.0 RC2의 업데이트 정보를 Scott Hanselman이 공유했습니다.
* Notes from the ASP.NET Community Standup – April 12, 2016 : Jeffrey T. Fritz이 ASP.NET 커뮤니티 행사에서 있었던 내용을 정리했습니다.
* Shawn Wildermuth이 자신의 블로그 시스템을 .NET Core 기반으로 재 작성했으며 오픈소스로 공유하였습니다. 또한 RSS와 XML RPC 라이브러리도 개발했으며 역시 오픈소스로 공개했습니다.
* Enhancing Claims with Owin Middleware & Claims Transformation : Darren Hall이 Owin 미들웨어에서 인증 토근의 전환과 인증하는 방법에 대해서 공유했습니다.
* How to perform partial resource updates with JSON Patch and ASP.NET Core : Ben Foster이 ASP.NET Core 에서 JSON Patch를 이용하여 리소스를 부분적으로 업데이트 하는 방법을 공유했습니다.
* ASP.NET Core custom service based on request : Armen Shimoon이 ASP.NET Core환경에서 요청에 기반한 사용자 서비스구축 방법을 공유했습니다.
* Entity Framework Core: The Future of EF for ASP.NET Core (video) : Chris Caldwell이 ASP.NET Core에서의  EF 미래라는 제목의 동영상을 공유했습니다.
* ASP.NET Core on Nano Server Preview by Luke Latham: Luke Latham이 Nano Server용 ASP.NET Core의 프리뷰버전을 소개했습니다.
* Hooking up ASP.NET Core 1.0 RC1 web api with Auth0 bearer tokens : Hans Arne Vartdal가  ASP.NET Core 1.0 RC1 환경의 web api에서  Auth0 인증 토큰을 활용하는 방법을 공유하였습니다 .
* Using Cache in ASP.NET Core 1.0 RC1 : Shawn Wildermuth이 ASP.NET Core 1.0 RC1 환경에서 캐쉬사용 방법을 공유했습니다.
* Exploring Prefix: A Free ASP.NET Profiling Tool : Mike Brind 가 ASP.NET용 무료 프로파일링 툴을 공유했습니다.

### F# 소식
* F# eXchange 2016: F# eXchange 2016 컨퍼런스에서 발표된 다수의 세션이 공유 되었습니다.
* Happy F# Day! Growing and Getting Better Each Year : Scott Wlaschin 
* .NET Core support has been added to the Ionide extension for Atom and Visual Studio Code.
* Async as Surrogate IO, : Mark Seemann이 비동기와 Surrogate IO에 대해서 설명하였습니다.
* Optionals, : David Raab 이 Optionals 키워드와 개념에 대해서 설명했습니다.

* Functional Error Handling in F# by Example, : Leif Battermann이 F# 에서의 함수지향적 예외처리방법에 대해서 공유했습니다.
