여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

지난 주에 소개한 "[NATS Client](https://github.com/nats-io/csnats)"를 기억하시나요? 이번 주 [On.NET 유튜브 동영상 인터뷰](...)는 [NATS](http://nats.io/)를 후원하고 있는 Apcera 회사 소속의 Brian Flannery와 Colin Sullivan씨와 함께 NATS 서비스에 대해 이야기를 합니다. 


### 금주의 패키지 – ASP.NET MVC Boilerplate

"ASP.NET MVC Boilerplate"는 ASP.NET MVC 프로젝트로 시작할 수 있는 다양한 유형의 응용 프로그램 템플릿을 제공합니다. 설치 후 비주얼 스튜디오의 프로젝트 템플릿을 선택할 수 있고 "Feature Selection" 마법사를 통해 여러분들이 만들고자 하는 웹 사이트 유형을 다양한 옵션 목록에서 선택해 시작할 수 있습니다.

* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate)

....이미지 링크....(https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate/raw/master/Images/ASP.NET%20MVC%20Boilerplate%20Feature%20Selection%20Wizard%201.png)

### 금주의 툴 - SemanticMerge

다른 부분을 찾고 병합하는 과정이 복잡한 리팩토링 과정 속에서 이뤄지다 보면 쉽지 않은 작업이 되어버리는데요. [SemanticMerge](https://www.semanticmerge.com/) 도구는 해석된 코드를 바탕으로 다른 부분을 찾아내는 방법을 사용함으로써 그러한 어려움을 해결했습니다. 

* [SemanticMerge](https://www.semanticmerge.com/)

즉, 코드의 문자열을 직접 비교하지 않고 코드가 해석된 구조 자체를 비교하는 것입니다. 현재 .NET 버전을 지원하고 있으며 향후 JavaScript도 추가될 예정입니다.

### 커뮤니티 소식

### .NET 소식

* 우주를 인터넷으로 볼 수 있게 해주는 WWT(WorldWide Telescope) 프로젝트를 마이크로소프트에서 수행한 적이 있습니다. 간단하게 말하자면 WWT는 닷넷 기반의 가상 망원경이라고 볼 수 있는데, 세계에서 가장 우수한 장비로 측정한 천문 데이터를 과학계의 연구 종사자뿐만 아니라 개인에게도 제공해주는 프로그램입니다. 최근에 이 프로젝트의 리더 역할을 미국 천문학 협의회(AAS: American Astronomical Society)에서 해주겠다는 고무적인 발표가 있었습니다. AAS 측의 협력에 힘입어 앞으로는 오픈소스 도구인 WWT 프로그램을 개발팀이 전일로 담당할 수 있게 되었습니다.
* [cross-platform IDE for C#](http://blog.jetbrains.com/dotnet/2016/01/13/project-rider-a-csharp-ide/) : [JetBrains](http://www.jetbrains.com/) 사가 크로스 플랫폼 용 C# 통합개발 환경을 발표했습니다.
* Tips for deploying your .NET project : Gregor Suttie는 닷넷 프로젝트를 배포했던 경험에 기반한 팁을 공유했습니다.
* [.NET Rocks](http://www.dotnetrocks.com/) 운영진이 이번 주에는 GitHub에서 일하고 있는 Phil Haack과의 인터뷰를 진행했습니다.
* Shared projects or PCL? : Miguel de Icaza는 공통 소스코드 관리를 PCL(Portable Class Library)로 해야 할지, 별도의 공유 프로젝트를 생성해야 할지에 대한 의견을 공유했습니다.



### ASP.NET 소식

* Configuration in ASP.NET Core MVC : James Chambers는 ASP.NET Core MVC 프로젝트에 도입된 새로운 설정 관리 방법을 설명합니다.
* FontAwesome fonts and MIME types in IIS and other web servers : 텍스트 방식으로 아이콘을 만들 수 있게 해주는 FontAwesome이라는 솔루션이 있습니다. 이것을 IIS와 다른 웹 서버에서 사용할 때 필요한 MIME 타입 설정에 대해 Rick Strahl이 설명합니다.
* Angular 2 quickstart with ASP.NET Core : Eric L. Anderson은 ASP.NET Core 프로젝트에서 현재 베타 단계를 거치고 있는 Angular 버전 2를 적용하는 방법을 설명합니다.
* ASP.NET Core logging using trace listeners and how to filter logs : Girish J Jain은 ASP.NET Core의 로깅 방식과 그것을 필터링하는 방법을 설명합니다.
* Dynamically adding meta tags : Thiyagu는 ASP.NET MVC 프로젝트에서 메타(<meta/>) 태그를 동적으로 추가하는 방법을 설명합니다.
* How to create a custom controller factory : Jose Mendez는 ASP.Net MVC 프로젝트에서 (IControllerFactory를 상속하는) 사용자 정의 컨트롤러 팩토리 클래스를 만드는 방법을 설명합니다.
* Common aspects of ASP.NET code in WebForms and MVC : Dino Esposito는 ASP.NET 웹 폼과 MVC간의 동작 방식을 비교하면서 핵심 구조는 다르지 않음을 설명합니다.
* Generate C# client API for ASP.NET WebAPI : Zijian은 ASP.NET Web API 서비스에 대해 클라이언트 측 호출 코드를 자동 생성해주는 [Strongly Typed Client API Generators for ASP.NET Web API](https://webapiclientgen.codeplex.com/)에 대한 사용법을 설명합니다.
* Handling request too large and identifying limits : Daniel Fisher는 대용량 요청을 처리하기 위한 설정 방법과 함께 그 최댓값을 넘어선 요청을 인식할 수 있는 방법을 설명합니다.


### F# 소식

* [가상 F# 컨퍼런스](http://fsharpconf.com/)가 2016년 3월 4일에 라이브-스트리밍 방식으로 진행될 예정입니다.
* [Xamarin Studio가 6.0 프리뷰 버전](http://developer.xamarin.com/releases/studio/xamarin.studio_6.0/xamarin.studio_6.0/#F_Enhancements)부터 F# PCL과 공유 프로젝트를 포함한 몇 가지 F# 지원을 추가했습니다.
* ....지난 주 On.NET 소식과 겹침...Don Syme was the guest on On.NET, sharing his thoughts on the future of F#, building an open source community, and more. 
* Running F# on Microsoft Azure : Isaac Abraham은 마이크로소프트 애저 클라우드 환경에서 F# 응용 프로그램을 호스팅하는 것에 관한 글을 공유했습니다.
* Using F# on Linux : Jonathan Curran은 리눅스 운영체제 환경에서 F# 응용 프로그램을 작성하는 것에 관한 글을 공유했습니다.
* Chart-tastic F# Goodness : Bear & Hammer는 FSharp.Charting 라이브러리를 이용해 다양한 차트를 다루는 F# 소스 코드를 공유했습니다.
* .NET: A Look Through F# Lenses : Jacqueline Homan은 F#을 통해 닷넷 플랫폼을 설명하는 글을 공유했습니다.



### .NET 게임 소식

[배너 이미지 링크: http://globalgamejam.org/sites/default/files/styles/responsive_large__wide/public/facebookheaderlarge.png]

Global Game Jam 행사가 열릴 예정인데... 국내와는 무관할 듯 싶은 행사라서 소개하기가 좀 그럴 것 같습니다.

We want to wish everyone participating in the Global Game Jam this coming weekend good luck and have fun! We'd love to play and show off some of the games created with .NET so send them our way once they're finished. You can either tweet them to Stacey Haffner (@yecats131) or leave a comment on the gist with the link.