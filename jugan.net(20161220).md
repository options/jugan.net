

### On .NET 소식
[지난 주 On .NET]( https://channel9.msdn.com/Shows/On-NET/Karel-Zikmund-Wes-Haggard--Immo-Landwerth-NET-Core-Triage--Project-Management)에는 Immo Landwerth, Karel Zikmund, 그리고 Wes Haggard가 .NET Core 오픈소스 프로젝트 관련 리파지토리에 대한 .NET 팀의 관리 방안에 관해 이야기 나누었습니다.

[이번 주 On.NET]( https://channel9.msdn.com/Shows/On-NET/Steve-Smith)에서는 MVP Summit에 참가한 [ASPInsiders]( http://aspinsiders.com/)(Microsoft ASP.NET 외부 자문 그룹)의 창립 멤버 Steve Smith와 함께 인터뷰를 진행하였습니다.

### 금주의 App - ShareX
[ShareX]( https://getsharex.com/)는무료 캡처 프로그램입니다. 프로그램이 실행 중일 때 [Print Screen] 키 또는 Alt+[Print Screen] 키를 통한 동작은 시스템 기본 기능과 동일하게 수행하면서 더욱 편리한 여러 부가 기능을 수행할 수 있습니다. 예를 들어 블로깅을 위해 화면을 캡처해서 저장하고 싶다면 간단한 설정으로 캡처와 함께 지정한 디렉터리로 파일을 저장할 수 있습니다. 파일 저장뿐만 아니라 서버를 지정해 놓으면 자동 업로드 또한 수행해 주는 기능을 가지고 있습니다.
C# 기반으로 구현되었으며, [GitHub]( https://github.com/ShareX/ShareX)을 통해 소스가 공유되어 있으니 자유롭게 원하는 기능을 직접 개발할 수도 있습니다.
// 그림

### .NET 소식
* Code Style Configuration in the VS2017 RC Update : Kasey Uhlenhuth가 VS 2017 RC버전에 새롭게 추가된 기능 ‘Code Style Configuration’에 관해 소개합니다.
* Connect(“demos”); // 2016: BikeSharing360 on GitHub : Erika Ehrli Cabral이 Connect(); 2016 Keynote에서 선보였던 스마트 자전거 쉐어링 프로젝트 ‘BikeSharing360’를 GitHub에 공유하였습니다.
* Why is reflection slow? : Matt Warren이 reflection의 성능 저하 문제를 해결할 수 있는 다양한 솔루션을 제시합니다.
* Orleans and Midori : Midori(현재는 중단된 MS 차세대 운영체제 개발 프로젝트)에 참여했던 Sergey Bykov가 운영체제 개발 프로젝트의 경험을 바탕으로 Orleans (클라우드 기반 프로그래밍 모델)의 특징을 설명합니다.
* Using bit masks for high-performance calculations : Szymon Warda가 bit mask를 이용한 성능향상 방법을 설명했습니다.
* How to use Your GPU in .NET : D. Infuehr가 .NET 환경에서 GPU 기능 활용 방법을 소개합니다.
* A magic mirror application written with C#, UWP, and Microsoft Cognitive Services : David M Pine이 C#, UWP, Microsoft Cognitive Service로 개발한 애플리케이션 “mirror”를 GitHub에 공유하였습니다. 
* Visual Studio debugging and 64 Bit .NET Applications : Rick Strahl이 Visual Studio에서 64Bit 애플리케이션을 디버깅할때 알아두면 좋은 팁을 공유하였습니다.
* RavenDB 4.0 Alpha is out! : Ayende Rahien이 RavenDB 4.0 Alpha 버전 릴리즈 소식을 공유했습니다.
* Loading .NET assemblies out of seperate folders : Rick Strahl이 별도의 폴더에 있는 .NET 어셈블리를 동적으로 로딩하는 방법에 관해 설명합니다.
* Avoid referencing infrastructure in Visual Studio solutions : Steve Smith가 Visual Studio 솔루션에 어셈블리를 직접 참조하지 않고 동적으로 종속 어셈블리 참조를 구성하는 방법에 관해 설명합니다..
* Eliding async and await : Stephen Cleary가 async/await 키워드를 생략하는 방법을 공유하였습니다.
*QuickStart TOR in .NET Core : Ádám Ficsór가 .NET Core 환경에서 TOR 라이브러리를 사용 할 수 있는 방법을 공유하였습니다.
* Dealing with duplication in MediatR handlers : Jimmy Bogard가 DDD(Domain Driven Design) 패턴 환경에서 MediatR 사용시, 중복되는 객체를 처리하는 방법에 관해 설명합니다.
* Request and response with C# and NATS : Daniel Wertheim이 MyNatsClient에 request-response 메세지 패턴을 추가하는 방법에 관해 설명합니다.
* Performance exercise: minimum : Andrey Akinshin이 효과적으로 최소값을 탐색할 수 있는 팁을 공유하였습니다.

### ASP.NET 소식
* Announcing Microsoft ASP.NET WebHooks V1 : Henrik F Nielsen이 ASP.NET WebHooks V1의 출시 소식을 전합니다.
* Using a culture constraint and redirecting 404s with the URL culture provider : Andrew Lock이 URL에 다중언어(지역화) 정보를 포함하여 라우팅할때 발생하는 404 에러 처리에 관해 몇가지 주의사항을 공유하였습니다.
* Using Web Sockets with ASP.NET Core : Gérald Barré가 ASP.NET Core에 Web Socket 활용 방법을 설명합니다.
* How to set up Angular2 with DevExtreme from scratch using Asp.Net Core 1.1 : Viktor Kjartansson이 Asp.Net Core 1.1 환경에서 DevExtreme로 Angular2 프로젝트를 설정하는 방법을 소개합니다.
* Making Application Insights fast & secure : Muhammad Rehan Saeed가 Application Insight 기능을 효과적으로 설정하는 방법을 공유하였습니다. 
* ASP.NET Core response optimization : David M Pine이 ASP.NET Core의 응답 성능을 최적화하는 방법을 공유하였습니다. 
* Implementing a client white-list using ASP.NET Core middleware : Damien Bod가 ASP.NET Core의 미들웨어를 통해 화이트-리스트(블랙-리스트의 반대개념)를 구현하는 방법에 관해 소개합니다.
* MVC Areas with ASP.NET Core : Josh Morales가 ASP.NET Core에서 MVC Area를 활용할 수 있는 방법에 관해 설명합니다. 
* SEO friendly URLs for ASP.NET Core : Muhammad Rehan Saeed가 SEO(검색 엔진 최적화, search engine optimization)에 친화적인 URL 구성 방법을 설명합니다.
* HTTP/2 server push and ASP.NET MVC : Tomasz Pęczek가 ASP.NET MVC에 HTTP/2 server push 기능을 활용할 수 있는 방법을 소개합니다.
* Conditionally set sliding expiration time on authentication cookies in ASP.NET Core : Legogris가 ASP.NET Core에서 인증 쿠키 기한 연장을 조건부로 수행하도록 설정하는 방법을 소개합니다.
* Pragmatic web error handling in ASP.NET MVC : Dino Esposito가 ASP.NET의 예외 처리 방법을 설명합니다.
* Accessing HttpContext outside of framework components in ASP.NET Core : Filip W가 ASP.NET Core의 HttpContext를 외부 컴포넌트에서 접근하는 방법에 관해 설명합니다.

### F# 소식
* Project Springfield: a cloud service built entirely in F# : .NET Blog에서 F# 기반으로 만들어진 클라우드 서비스인"Project Springfield"에 관해 소개합니다.
* Why functional programming matters : John Hughes가 Functional programming의 필요성을 설명합니다.
* Some advice to F# beginners : Pierre Irrmann이 F# 초보자를 위한 학습 가이드를 공유했습니다.
* Working with SQL syntax trees in F# : Isak Sky가 F#을 이용한 SQL syntax tree 활용법을 공유하였습니다.
* Scripting in F# using Fake and Paket : Pierre-Luc Maheu가 Fake와 Paket을 이용한 F# 스크립팅에 관해 설명합니다.
### Xamarin 소식
* Xamarin Stable Release: Updated Cycle 8 Service Release 1 w/ Xcode 8.2 support & Xamarin Alpha Preview 5: Cycle 9 : Adrian Murphy가 Updated Cycle 8 Service Release 1과 Xamarin Alpha Preview 5: Cycle 9 버전 릴리즈 소식을 공유했습니다.
* Installing Xamarin made easy with offline installation : Mayur Tendulkar가 자신의 블로그에서 Visual Studio 2015를 사용하여 Xamarin용 오프라인 설치 미디어를 만드는 방법에 대해 설명합니다.
* Introducing the BikeRider Xamarin.Forms sample app : Pierce Boggan이 Xamarin.Forms 소개를 위한 예제로 애플리케이션 BikeRider을 소개합니다.
* Connect(“demos”); // 2016: BikeSharing360 on GitHub : Erika Ehrli Cabral이 Connect(); 2016 Keynote에서 선보였던 스마트 자전거 쉐어링 프로젝트 ‘BikeSharing360’를 GitHub에 공유하였습니다.
* Exploring our newest sample app, BikeSharing360 : Dmitry가 BikeSharing360 E2E 데모 스리즈를 공유한 Erika Ehrli과 함께 프로젝트 시나리오, 아키텍쳐 등에 관해 구체적으로 설명합니다.
* Infographic – How to design a growth strategy for your app : Mark Boyd가 애플리케이션 개발 후 운영 전략과 계획에 관해 인포그래픽으로 설명합니다.
* Bindable native views in XAML – with commands!?! : Matthew Soucoup가 연재하는 “XAML에서 Bindable Native Views 활용하기” 시리즈에서 "Command" 편이 게시되었습니다.
* Ahead of time compilation with Xamarin.Mac : Chris Hamons가 Xamarin.Mac에서 AOT(Ahead of time) 컴파일 기능을 설정하는 방법에 관해 소개합니다.
* Troubleshooting connecting to Xamarin Mac Agent : Adam Pedley가 Xamarin Mac Agent에 접속을 시도할 때 발생할 수 있는 오류와 이를 해결하는 방법에 관해 설명합니다.
* Xamarin Forms (Android): Why won’t it store my Azure B2C Auth Token? :John Wilson이 Xamarin Forms (Android)에서 Azure Active Directory B2C 서비스를 사용할 때 나타나는 인증 토큰 캐쉬에 대해 설명합니다.

### Azure 소식
* Writing HTTP CRUD in Azure Functions : Adrian Hall이 Azure Function에서 HTTP CRUD를 구현하는 예를 공유했습니다.

### Data 소식
* Entity Framework Core Extensions : ErikEJ가 Entity Framework Core 환경에서 사용 가능한 확장 컴포넌트 리스트를 공유했습니다.
* EF Core diagnosis and features with MS SQL Server : Damien Bod가 EF Core의 로깅(진단) 기능과 1.1 버전에 추가된 기능을 설명했습니다.
* Previewing the generated PostgreSQL SQL for a query in Marten : Jason Roberts가 Marten(.NET, PostgreSQL 기반의 Document DB) 서버를 사용할 때, C# LINQ 문이 실제 어떤 쿼리를 생성하는지 확인하는 방법에 관해 설명합니다.
* Page the Doctor! When Entity Framework paging goes rogue! : Rion Williams가 Entity Framework를 이용해 페이징 데이터를 조회할 때, SQL 서버 버전 호환성으로 인해 발생할 수 있는 오류를 해결하는 방법에 관해 설명합니다.
* Retrieving raw JSON data in Web API with Marten : Jason Roberts가 Marten(.NET, PostgreSQL 기반의 Document DB)서버 사용시 Web API의 LINQ 결과를 JSON 형식으로 얻는 방법을 공유했습니다.

// 전무님 소개
