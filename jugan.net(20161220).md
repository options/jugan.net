
### On .NET 소식

[지난 주 On .NET]()(링크)에는 Immo Landwerth, Karel Zikmund, Wes Haggard와 함께  .NET Core 오픈소스 프로젝트와 관련 리포들을 어떻게 관리하는지 얘기 나누었습니다

이번주부터 내년초까지 크리스마스와 년말 년시 시즌으로 인터뷰 계획은 없을 예정입니다.

### 금주의 App  -  ShareX
ShareX는 이미지와 동영상 캡쳐를 동시에 지원하며 캡쳐된 결과물을 인기있는 파일 공유 서비스에 바로 업로드하는 기능을 포함하고있는 스크린 캡쳐 툴입니다. 오픈소스 프로젝트이며 C#을 기반으로 구현되었습니다.

// 그림

### .NET 소식
* Code Style Configuration in the VS2017 RC Update : Kasey Uhlenhuth가 VS2017 RC버전에 추가된 새로운 기능 Code Style Configuration을 소개했습니다.
* Connect(“demos”); // 2016: BikeSharing360 on GitHub : Erika Ehrli Cabral이 Connect 2016 행사에 키노츠에 시연되었던 BikeSharing360 데모가 GitHub 에 공유되었습니다.
* Why is reflection slow? : Matt Warren이 reflection기능 사용이 성능이 영향을 주는 이유를 설명했습니다.
* Orleans and Midori : Sergey Bykov가 Midori (현재는 중단된 MS 차세대 OS 개발 프로젝트)프로젝트의 경험을 바탕으로 올리언즈(클라우드기반 프로그래밍 모델)의 특징을 설명했습니다.
* Using bit masks for high-performance calculations : Szymon Warda가 bit mask를 이용한 성능향상 방법을 설명했습니다.
* How to use Your GPU in .NET : D. Infuehr가 .NET 환경에서 GPU 기능을 활용하는 방법을 설명했습니다.
* A magic mirror application written with C#, UWP, and Microsoft Cognitive Services : David M Pine이 C#, UWP, Microsoft Cognitive Service를 활용한 어플 개발 예를 소개했습니다.
* Visual Studio debugging and 64 Bit .NET Applications : Rick Strahl이 Visual Studio에서  64 Bit 어플리케이션을 디버깅할때 알아두면 도움이되는 몇가지 사항을 공유했습니다.
* RavenDB 4.0 Alpha is out! : Ayende Rahien이 RavenDB 4.0 Alpha 버전의 릴리즈 소식을 공유했습니다.
* Loading .NET assemblies out of seperate folders : Rick Strahl이 별도의 폴더에 있는.NET  어셈블리를 동적으로 로딩하는 방법을 설명했습니다.
* Avoid referencing infrastructure in Visual Studio solutions : Steve Smith가 Visual Studio 솔루션에 어셈블리를 직접 참조하지 않고 동적으로 종속 어셈블리참조를 구성하는 방법을 설명했습니다.
* Eliding async and await : Stephen Cleary가 async/await 키워드를 생략하는 방법을 소개했습니다.
* QuickStart TOR in .NET Core : Ádám Ficsór가 .NET Core 환경에서 Tor 라이브러리(https://www.torproject.org)를 사용하는 방법을 설명했습니다.
* Dealing with duplication in MediatR handlers : Jimmy Bogard가 DDD(Domain Driven Design) 패턴의 환경에서 MediatR 사용시 중복객체의 처리방법을 설명했습니다.
* Request and response with C# and NATS : Daniel Wertheim이 C#,NATS을 이용한 Request, response 기능구현 가이드를 소개했습니다.
* Performance exercise: minimum : Andrey Akinshin이 문서 "성능향상 팁 : 효과적으로 최소값 탐색하기"를 게시했습니다.

### ASP.NET 소식
* Announcing Microsoft ASP.NET WebHooks V1 : Henrik F Nielsen이 ASP.NET WebHooks V1이 릴리즈된 소식을 공유했습니다.
* Using a culture constraint and redirecting 404s with the URL culture provider : Andrew Lock이 URL에 다중언어(지역화)정보를 포함하여 라우팅하는 경우 404 에러 처리에 관한 개발주의사항을 설명했습니다.
* Using Web Sockets with ASP.NET Core : Gérald Barré가 ASP.NET Core에서 Web Socket의 활용법을 설명했습니다.
* How to set up Angular2 with DevExtreme from scratch using Asp.Net Core 1.1 : Viktor Kjartansson이 DevExtreme을 이용한 개발환경에서 Angular2 프로젝트의 설정방법을 소개했습니다.
* Making Application Insights fast & secure : Muhammad Rehan Saeed가 Application Insight 기능을 빠르고 안전하게 설정하는 방법을 소개했습니다.
* ASP.NET Core response optimization : David M Pine이 ASP.NET Core의 응답 성능 최적화 방법을 설명했습니다.
* Implementing a client white-list using ASP.NET Core middleware : Damien Bod가 ASP.NET Core의 미들웨어를 통해서 화이트-리스트(블랙-리스트의 반대개념)의 구현방법을 설명했습니다.
* MVC Areas with ASP.NET Core : Josh Morales가 ASP.NET Core에서 MVC Area의 활용방법을 설명했습니다.
* SEO friendly URLs for ASP.NET Core : Muhammad Rehan Saeed가 SEO(검색 엔진 최적화,search engine optimization)에 친화적인 URL 구성 방법을 설명했습니다.
* HTTP/2 server push and ASP.NET MVC : Tomasz Pęczek가  ASP.NET MVC에서 HTTP/2 server push 기능 활용법을 설명했습니다.
* Conditionally set sliding expiration time on authentication cookies in ASP.NET Core : Legogris가 ASP.NET Core에서 인증 쿠기의 시간만료 연장 설정을 조건부로 수행되도록 설정하는 방법을 설명했습니다.
* Pragmatic web error handling in ASP.NET MVC : Dino Esposito가 ASP.NET의 예외처리방법을 설명했습니다.
* Accessing HttpContext outside of framework components in ASP.NET Core : Filip W가  ASP.NET Core 의 HttpContext 를 외부 컴포넌트에서 접근하는 방법을 설명했습니다.

### F# 소식
* Project Springfield: a cloud service built entirely in F# : F# 기반으로 만들어진 클라우드 서비스 "Project Springfield"가 소개되었습니다.
* Why functional programming matters  : John Hughes가 functional programming의 필요성을 설명했습니다.
* Some advice to F# beginners : Pierre Irrmann이 F# 초보자를 위한 학습 가이드를 공유했습니다.
* Working with SQL syntax trees in F# : Isak Sky가 F# 을 이용한 SQL syntax tree의 활용법을 설명했습니다.
* Scripting in F# using Fake and Paket : Pierre-Luc Maheu가 Fake,Paket을 이용한 F# 스크립팅을 설명했습니다.

### Xamarin 소식
* Xamarin Stable Release: Updated Cycle 8 Service Release 1 w/ Xcode 8.2 support & Xamarin Alpha Preview 5: Cycle 9 : Adrian Murphy가 Updated Cycle 8 Service Release 1(링크)와 Xamarin Alpha Preview 5: Cycle 9(링크) 버전 릴리즈 소식을 공유했습니다.
* Installing Xamarin made easy with offline installation : Mayur Tendulkar가 Xamarin을 오프라인으로 인스톨및 설정하는 방법을 소개했습니다.
* Introducing the BikeRider Xamarin.Forms sample app : Pierce Boggan이 Xamarin.Forms 샘플 어플 BikeRider 를 소개했습니다.
* Connect(“demos”); // 2016: BikeSharing360 on GitHub : Erika Ehrli Cabral이 Connect 2016 행사에 키노츠에 시연되었던 BikeSharing360 데모가 GitHub에 오픈되었다는 소식을 공유했습니다.
* Exploring our newest sample app, BikeSharing360 : Visual Studio Toolbox에서 Connect 2016 -  BikeSharing360 데모를 설명했습니다.
* Infographic – How to design a growth strategy for your app : Mark Boyd가 어플 개발후 운영전략과 계획에 대해서 인포그래픽으로 설명했습니다.
* Bindable native views in XAML – with commands!?! : Matthew Soucoup가 XAML에서 Bindable Native Views 활용하기 : "Command" 편을 게시했습니다.
* Ahead of time compilation with Xamarin.Mac : Chris Hamons가 Xamarin.Mac에서 AOT(Ahead of time) 컴파일 기능 설정에 대해서 설명했습니다.
* Troubleshooting connecting to Xamarin Mac Agent : Adam Pedley가 Xamarin Mac Agent 접속 시도시 발생할수있는 오류와 이에대한 해결방법을 설명했습니다.
* Xamarin Forms (Android): Why won’t it store my Azure B2C Auth Token? :John Wilson이 Xamarin Forms (Android)에서 Azure Active Directory B2C 서비스 사용시 인증토큰 케쉬에 대한 설명을 공유했습니다.  
* My UICollectionView doesn’t refresh on new items(https://marcoscobena.wordpress.com/2016/12/12/my-uicollectionview-doesnt-refresh-on-new-items/) : Marcos Cobeña Morián이 UICollectionView(좀더 정확히는 MvxCollectionView)의 데이터소스에 아이템이  추가되어도 UI에 반영되지않는 이상 동작에 대해 해결한 경험을 공유했습니다.

### Azure 소식
* Writing HTTP CRUD in Azure Functions : Adrian Hall이 Azure Function에서 HTTP CRUD를 구현하는 예를 공유했습니다.

### Data 소식
* Entity Framework Core Extensions : ErikEJ가 Entity Framework Core환경에서 사용가능한 확장 컴포넌트 리스트를 공유했습니다.
* EF Core diagnosis and features with MS SQL Server : Damien Bod가 EF Core의 로깅(진단)기능과 1.1 버전에 추가된 기능을 설명했습니다.
* Previewing the generated PostgreSQL SQL for a query in Marten : Jason Roberts가 Marten(.NET, PostgreSQL 기반의 Document DB)서버 사용시 C# LINQ 문이 실제 어떤 쿼리를 생성하는지 확인하는 방법을 설명했습니다.
* Page the Doctor! When Entity Framework paging goes rogue! : Rion Williams가 Entity Framework를 이용한 페이징 데이터(주로 웹페이지의 게시판 형태의 데이터) 조회시 SQL 서버 버전간 호환성으로인해 발생항수있는 오류를 해결하는 방법을 설명했습니다.
* Retrieving raw JSON data in Web API with Marten : Jason Roberts가  Marten(.NET, PostgreSQL 기반의 Document DB)서버 사용시 Web API 의 LINQ 결과를 JSON 형식으로 얻어오는 방법을 공유했습니다.

// 전무님 소개
