### On.NET 소식
[지난 On.NET 인터뷰]에서는 On.NET 인터뷰 1회의 초대손님이었던 Miguel de Icaza 를 모시고 얘기 나누었습니다.

[이번 주 On.NET 인터뷰]에서는 .NET GC(가비지컬렉션)에 대해서 Maoni Stephens와 함께 얘기 하려 합니다.

### 금주의 패키지- Math.NET Symbolics
Math.NET은 수학 관련한 다재다능한 라이브러리입니다. 이미 몇주전에  이 라이브러리의 수치연산 부분을 소개해드린적이[4/12일자 주간닷넷 링크] 있습니다. Math.NET의 다양한 기능중 오늘은 수학적 기호를 표현하고 다룰 수 있게 도와주는 Symbolics 라이브러리에 대해 소개하려합니다. Symbolics  라이브러리를 이용하면 수학적 기호를 분석/파싱할 수 있으며, 수학적 기호의 포멧을 적용하고 표현식을 계산하는것이 가능합니다. 또한 이러한 수학적 기호들을 추가 개발 혹은 좀더 단순화하거나 차별화 하는등의 커스터마이징도 가능합니다.

아래의 예를 보실까요.

아래의 예는 기호 미분(symbolic differentiation)를 이용해여 주어진 각의 테일러 전개식(Taylor expansion) 표현을 완성한 경우입니다.[당췌 뭔소리인지….]
 
//코드

### 금주의 Xamarin 애플리케이션 - MRW
스페인의 유명 국제 탁송 회사인  MRW의 배송 기사들은 배송물건 인수, 주문 접수,  배송 일정 조율등의 작업을 하기위해 MRW에서 자체 개발한 안드로이드 어플을 이용합니다. 이 어플은 주요 기능으로는 로컬 저장공간을 사용한 오프라인 작업 기능, 멀티 스레드 지원, 바코드 리딩/출력기능, 위치추적 기능과 요금처리 기능등이 있습니다.
이러한 복잡한 기능에도 불구하고 MRW는 Xamarin을 이용하여 빠른 시일에 배송기사들을 위한 업무 어플을 개발 함으로서 기사분들의 업무에 많은 도움이 될수있었습니다.

//이미지  

### 금주의 게임 - Crashing Season
[Crashing Season]은 카툰(만화형식의) 단순 랜더링 형태의 액션/아케이드 장르 모바일 개임으로 동물을 이용한 재미있고 흥미로운 게임 플레이를 즐길수 있습니다. Crashing Season에서는 플레이어 레벨에 따라서  최대 총 15 종류의 동물을 컨트롤할수있습니다. 게임에서는 각 동물들은 고유의 특징을 가지며 이 특징을 잘 이용하여 상대방과 충돌하고 각 레벨 별 정해진 미션을 완수하는것이이 게임의 목표입니다. 또한 온라인상의 친구와 다중 플레이하는 것도 가능하며 이경우 추가 골드(포인트)도 획득 할 수 있습니다.

Crashing Season 은  Unity and C#을 이용해서 Koukoi Games 에서 만들었으며 iOS와 Android 모바일기기에서 5월 26일부터 플레이가 가능합니다.
좀 더 자세한 정보는 [Made With Unity] 페이지에서 확인하실 수 있습니다. 

//그림


### .NET 소식
* Changes to project.json : Scott Hunter이 기존 csproj 프로젝트와 project.json의 차이점을 설명하였습니다.
* Happy 25th birthday, VB : Anthony D. Green이 VB 25회 생일(2016/5/20 기준 비베가 일반인에게 배포된지 정확히 25년됩니다)을 축하하였습니다
* JSON.NET now works with RC2 without “import” directives : JSON.NET이 RC2 버전부터는 import 지시자 없이도 사용하는 것이 가능합니다.(실제 링크에는 그런내용 없네요...우짜지)
* Updating to RC2: Changes to EFCore, ASPNETCore, PostgreSQL driver & XUnit : Julie Lerman이 RC2로 업그레이드하기 전에 알아야 할 EFCore, ASPNETCore, PostgreSQL driver & Xunit의 주요 변경점을 공유했습니다.   
* .NET Core goes RC2 : Ed Charbeneau이 .NET Core RC2 버전에 대해서 설명하였습니다.
* How to debug .NET Core RC2 app with Visual Studio Code on Windows : Simone Chiaretta이 윈도우에서 Visual Studio Code를 이용한 .NET Core RC2 어플리케이션 디버깅 방법을 설명하였습니다.
* .NET Core, a call to action : Mark Rendle이 .NET Core의 개발 배경과 중요성을 설명하였습니다.  
* Using Windows Runtime in a .NET desktop application : jbe2277이 Windows Runtime API(Windows 8 부터 지원되는 일종의 runtime API)를 .NET 데스크톱 어플리케이션에서 사용하는 방법을 설명하였습니다.

### ASP.NET 소식
* Migrating ASP.NET 5 RC1 apps to ASP.NET Core : Christos Sakell이 ASP.NET 5 RC1 에서 개발된 어플리케이션을 ASP.NET Core버전으로 전환하는 방법을 설명하였습니다.
* Converting an ASP.NET Core RC1 Project to RC2 : Shawn Wildermuth이 ASP.NET Core RC1 프로젝트를 RC2 버전 프로젝트로 변환하는 방법을 설명하였습니다.
* Using EF6 with ASP.NET MVC Core 1.0 : Tony Sneed가 ASP.NET MVC Core 1.0에서 엔티티프레임워크6(EF6)을 사용하는 방법을 공유하였습니다.
* Strongly Typed Configuration Settings in ASP.NET Core : Rick Strahl가 ASP.NET Core에서 강력한 타입의 설정파일(외부 설정 파일의 각 항목들이 코드에서 특정 클레스의 멤버로 억세스 가능하도록하는)을 사용하는 방법을 공유하였습니다.
* How to use the IOptions pattern for configuration in ASP.NET Core RC2, and How to add default security headers in ASP.NET Core using custom middleware : Andrew Lock이 ASP.NET Core RC2 환경에서 IOptions pattern을 이용한 설정 방법과 ASP.NET Core에서 사용자 미들웨어를 이용하여 기본 security header를 추가하는 방법을 설명하였습니다.
* Building a Static File Server in ASP.NET Core RC2 with the CLI : Bobby Johnson가 ASP.NET Core RC2 에서 CLI를 이용한 정적 파일서버의 구성방법을 공유하였습니다. 
* Templates for building React.js front-ends in ASP.NET Core and MVC5 : Jon Smith이 ASP.NET Core MVC5 환경에서 React.js용 프론트앤드 개발 템플릿을 공유해주었습니다.
* ASP.NET Core: Watching Code : Shane Boyer가 운영환경에서 프로젝트 소스의 변화를 감지해주는 여러 모니터링 도구들을 소개해주었습니다.
* ASP.NET Core distributed cache tag helper : David Paquette가 ASP.NET Core distributed cache tag helper에 대해 설명했습니다. 

### F# 소식
* A Dive into Cloud<`T> : Eirik Tsarpalis이  Cloud<`T>에 대해서 설명하였습니다.
* Getting Started with Fable and Webpack, : Krzysztof Cieślak이  Fable(F#을 JavaScript으로 변경해주는 컴파일러)과 Webpack을 소개하였습니다.
* Setting up your environment to build an Android app with Xamarin.Forms, : Kimserey Lam이 안드로이드용 어플을 만들기위한 Xamarin.Forms 개발 환경 설정을 소개하였습니다.
* Dynamic Recursive API with F#, : Lauri Taimila이 F#의 동적 재귀함수(Dynamic Recursive) API를 설명하였습니다

### Xamarin 소식
* 10 Developer Takeaways from Xamarin Evolve : Sam Basu가 지난 Xamarin Evolv 기술 행사에서 있었던 주요내용중 개발자가 꼭 알아야 할 10가지 항목을 공유해주었습니다.
* James Montemagno interviews Joseph Hill, Xamarin co-founder, and VP of developer relations, on the Xamarin Podcast : Xamarin 공동 설립자이자 개발자지원 부사장인 Joseph Hill의 인터뷰가  Xamarin Podcast에 소개되었습니다.
* The many flavors of HttpClient : Kerry W. Lothrop가 HttpClient 의 다양한 활용법을 소개하였습니다.
* Embedding Native Controls into Xamarin.Forms : James Montemagno가 Xamarin.Forms에서 Native Control의 사용방법을 공유하였습니다.
* Xamarin.Forms Workbooks, and Xamarin Workbooks with Nugets : Craig Dunn이 Xamarin.Forms Workbooks의 소개(링크)와  Workbooks을 Nugets과 함께 활용하는 방법(링크)을 공유하였습니다.

### Games 
* CRYENGINE 5.1 is here : CRYENGINE 5.1이 릴리즈 되었습니다.
* Unity Development with VS Code : Visual Studio Code를 이용해서 Unity 개임을 개발해보세요.
* Build A Unity Game Part 3 – Video, : What Up Games 의 공동 대표이자 개발자인 Stacey Haffnerrk 가 Unity 에서 게임을 개발하는 방법 파트3을 소개했습니다.

* (Unity 5) Let’s Make Rust! [Episode 01 – Introduction] – Video, : Gabe Kutuzov이 3차원 1인칭 생존게임장르인 Rust 형태의 게임을 Unity로 구현하는 방법을 소개했습니다.
