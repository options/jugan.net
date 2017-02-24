### On .NET 소식

[지난 주 On .NET]()(링크)에는 [Phil Haack](링크)와 함께 GitHub(링크)에 대해서 얘기나누었습니다.

//그림

[이번 주 On .NET]에는 [ Beth Massi](링크)와 함께 .NET의 지난 15년을 정리해보려 합니다. 


### 금주의 패키지: Readline
라이브러리 Readline(링크)은 딱 한가지 작업만을 위한 개발 라이브러리입니다. 한가지 작업만을 위한것이지만 그한가지 작업을 아주 잘지원하고있습니다. 그리고 그작업은 이미 이름에서도 알수있듯이 콘솔 어플리케이션환경에서 사용자 입력 프롬프트 처리관련 모든작업입니다. 표준 키보드 단축키 지원, 명령 히스토리 지원, 사용자 설정으로 등록된 자동완성 명령기능등을 지원합니다. 기존의 GNU Readline(링크)의 닷넷 버전이라고 생각하시면 쉽게 이해가 가실겁니다.

//코드

GitHub에 공유된 rawreadline.cs 파일의 코드 내용

### .NET 소식
* Announcing .NET Core Tools updates in VS 2017 RC : Rich Lander가 VS 2017 RC 버전에서 사용할 수 있는 .NET Core Tool의 업데이트 소식을 공유했습니다.
* Welcoming Jon Galloway as the new Executive Director of the .NET Foundation : Jon Galloway가 .NET Foundation의 새로운 협회장이되었다는 소식을 Martin Woodward가  공유했습니다.
* .NET Renaissance : Mark Rendle이 (닷넷이 여러 산업에서 잘 활용되있는다는 내용의) "닷넷 부흥의 시대"라는 글을 포스팅 했습니다.
* Evolving the Visual Studio Test Platform – Part 4: Together, in the Open : Pratap Lakshman이 Visual Studio Test Platform 시리즈 " 파트 4: 오픈소스 참여" 편을 포스팅 했습니다.
* Trying out “dotnet new” template updates and csproj with VS2017 : Scott Hanselman이 VS2017 의 새롭게 추가된 “dotnet new” 템플릿 업데이트와 csproj 프로젝트 파일에 관련된 정보를 소개했습니다.
* Exploring the new dotnet cli : Shayne Boyer가 dotnet cli( command-line, 명령줄 인터페이스)를 소개 했습니다.
* The 68 things the CLR does before executing a single line of your code : Matt Warren이 개발자의 코드 한줄이 실행되기위해 CLR이 하는 68개의 선작업을 설명했습니다.
* Migrating existing .NET projects to SDK-based projects : Jonathan Mezach이 기존의  .NET 프로젝트를 SDK 기반 프로젝트로 전환하는 방법을 공유했습니다.
* The performance cost of boxing in .NET : Tom DuPont가 .NET 의 박싱/언방식 기술이 성능에 미치는 영향을 설명했습니다.
* .NET on Linux : Don Schenck이 리눅스 환경에서의 .NET 을 소개했습니다.
* Advanced email address validation in .NET : Gérald Barré가 .NET 환경에서 효과적인 이메일 주소 포멧의 유효성 검증방법을 소개했습니다. 
* NuGet2 and a DirectorySeparatorChar bug, Why is NuGet search in Rider so fast?, InvalidDataException in Process.GetProcesses, and A bug story about named mutex on Mono : Andrey Akinhin이 "NuGet2 에서 DirectorySeparatorChar 관련 버그정보"(링크), "Rider에서 NuGet  검색이 빠른이유"(링크), "Process.GetProcesses의 InvalidDataException"(링크),  "mutex on Mono 라는 이름의 버그 히스토리"(링크)를 소개했습니다.
* Serverless C# on AWS Lambda (part 2) – Handling HTTP Events : Ryan Stelly가 별도의 서버 구축없이 AWS Lambda 서비스에서 C#을 활용하는 방법 "파트 2: HTTP 이벤트 처리"을 설명했습니다.
* Upgraded SimplCommerce from project.json to csproj : Thien Nguyen이 기존 json 포멧에서 csproj 포멧으로 변경된  SimplCommerce  오픈 소스  프로젝트 정보를 공유했습니다.
* Creating solid classes with AutoFac : Benny Michielsen이 IOC컨테이너 AutoFac의 활용방법을 설명했습니다. 

### ASP.NET 소식
* ASP.NET Documentation Now on docs.microsoft.com : Wade Pickett이 ASP.NET 개발문서 정보를 제공하는 docs.microsoft.com 사이트를 소개했습니다.
* Exploring IStartupFilter in ASP.NET Core : Andrew Lock이 ASP.NET Core의 IStartupFilter  인테페이스를 설명했습니다.
* Migrating from .NET Framework to .NET Core : Steve Gordon이 기존의 ASP.NET Core  환경 어플리케이션을 .NET Core로 전환한 경험을 공유했습니다.
* Updating My Blog to Visual Studio 2017 and .csproj : Shawn Wildermuth가 자신의 블로그 사이트를 Visual Studio 2017 과 .csproj  프로젝트 타입으로 전환한 경험을 공유했습니다.
* ASP.NET Core Dependency Injection Deep Dive : Joonas Westlin이 ASP.NET Core의 DI(의존성 주입)을 설명했습니다.
* .Net Core Health Endpoint Monitoring Middleware : Carlos Mendible이 .Net Core용 Health Endpoint Monitoring Middleware의 구현방법을 설명했습니다.
* Empty SoapActions in ASMX Web Services : Rick Strahl이 ASMX 웹서비스에서 빈 SoapActions 의 응답결과에 대한 처리방법을 공유했습니다.
* Anti-Forgery Tokens and ASP.NET Core APIs : K. Scott Allen이 위조불가 인증 토근과 관련 ASP.NET Core API에 대해서 설명했습니다.


### F# 소식
* F# is in the top 3 for most-loved technology on StackOverflow : StackOverflow에서 F#이 3번째로 가장많이 사랑받는 기술로 선정되었습니다.
* Functional ASP.NET Core : Dustin Moris Gorski가 Suave.AspNetCore을 활용한 Functional ASP.NET Core 를 설명했습니다.
* A brief peek about Universal F#, : Jonathan Banashek이 Universal F#을 소개했습니다.
* DocumentDB Stored Procs in F# via Fable : Joerg Beekmann이 Fable 을 이용하여 DocumentDB 의 stored procedure를 F#으로 작성하는 방법을 설명했습니다.
* Introducing Type Providers : Isaac Abraham이 Type Provider를 설명했습니다.
* Creating an F# Azure Function from the Ground Up (Part 1), : Mathias Brandewinder이  F#을 이용한 Azure Function 작성 방법을 설명했습니다.

### Xamarin 소식
* Xamarin Pre-release: Xamarin.Forms 2.3.4.192-pre2 : David Ortinau가 Xamarin.Forms 2.3.4.192-pre2 버전 릴리즈 소식을 공유했습니다.
* Xamarin Release Candidate: Cycle 9 RC Refresh : Bri Brothers가 Xamarin Cycle 9 RC 버전정보를 공유했습니다.
* Cross-Platform Drawing with SkiaSharp : Matthew Leibowitz이 구글의 다중 플랫폼용 2D 그래픽 라이브러리 SkiaSharp의 활용방법을 설명했습니다.
* Announcing Project Rome Android SDK : Carmen Forsmann이 Project Rome을 위한 안드로이드 SDK를 소개했습니다.
* Xamarin Forms DataTemplateSelector & Xamarin Forms Toolbar : Adam Pedley가 "Xamarin Form의 DataTemplateSelector"(링크)와 "Xamarin Forms Toolbar"(링크)를 설명했습니다.
* Keeping DRY with PropertyChanged.Fody for Xamarin.Forms & Working with Effects in Xamarin.Forms : Gerald Versluis가 "Xamarin.Forms에서 PropertyChanged.Fody 의 활용법"(링크), "Xamarin.Form의 효율적인 활용법"(링크)를 설명했습니다.
* Getting Device-Specific When Customizing a Xamarin Forms App : Wallace McClure가 Xamarin Forms App에서 모바일 디바이스의 특정정보(안드로이드 버전, 색상, 테마등) 에 접근하는 방법을 설명했습니다.
* 5 Helpful Xamarin.Forms Developer Tips : Sam Basu가 Xamarin.Forms 개발자를 위한 5가지 유용한 팁을 공유했습니다.
* Xamarin.Android – Things : Jon Douglas가 Xamarin.Android  구조를 설명했습니다.
* Get familiar with Xamarin Workbooks, Create UI Tests with Xamarin Test Recorder, & Xamarin Forms with MVVM Light : Daniel Krzyczkowski가  "Xamarin Workbook 소개"(링크), "Xamarin Test Recorder를 이용한 UI 테스트"(링크), "Xamarin Forms에서 MVVM Light 활용"(링크) 자료를 공유했습니다.
* Developing Universal/Cross-Platform Apps with MVVM – VI : Can Bilgin이 Windows Runtime과 Xamarin android 환경에서 MVVM을 이용한 App 개발 방법을 설명했습니다.
* The Role Of Empty States In User Onboarding : Nick Babich이 모바일 App의 사용자 UX 디자인에 관한  포스팅을 공유했습니다.
* Problem adding Microsoft Emotion API to a Xamarin app : Anders Poulsen이 Xamarin app에 Microsoft Emotion API용 nuget package를 설치하다 실패한 경험을 공유했습니다.
* Build action ‘EmbeddedResource’, Visual Studio 2017–IOS Build Debug Error, & Xamarin: Unable to Debug Android Application : David Yardy가 "Build action 'EmbeddedResource' "(링크),  "VS2017에서 IOS 빌드시 에러 상황과 해결방법"(링크), "Android  App 디버깅 불가 상황과 해결방법"(링크)에 대한 정보를 공유했습니다.
* Announcing ReactiveUI virtual community meetups : Geoffrey Huntley가 ReactiveUI 사용자 커뮤니티 미팅 정보를 공유했습니다.
* Yet Another Podcast #167 – Charles Petzold : Jesse Liberty가 Charles Petzold와 함께 진행한 팟케스트를 공유했습니다.
* Sending Files to a Xamarin.Forms App – Part 1: iOS : Matthew Soucoup이 Xamarin.Forms App에 파일 전송하기 "1편: iOS"를 포스팅 했습니다.

### UWP 소식
* Universal Windows Platform (UWP) docs are now on Docs.Microsoft.com : Martin Ekuan이 UWP 개발 정보를 포함한 문서포털 사이트 Docs.Microsoft.com를 소개했습니다.
* Recap Windows Developer Day: Creators Update : Kevin Gallo가 Windows Developer Day 행사 내용을 정리했습니다.
* Telerik UI for UWP Now Open Source : Dobrin Grancharov가 "Telerik UI for UWP" 개발 라이브러리가  오픈 소스 프로젝트로 진행된다는 소식을 공유했습니다.
* Using SQLite databases in UWP apps : Gautam Kanumuru가 UWP apps에서 SQLite DB를 활용하는 방법을 설명했습니다.
* Announcing UWP Community Toolkit 1.3 : David Catuhe 와 Giorgio Sardo가 UWP Community Toolkit 1.3 릴리즈 정보를 공유했습니다.

### Game 소식
* Getting Started with SadConsole : Stacey Haffner가 MonoGame 3.5기반의 게임 라이브러리인 SadConsole의 활용 방법을 설명했습니다.
* Lessons Learned from VR Prototyping : GDC 행사에 있었던 "VR Prototyping 가이드" 관련 세션 동영상이 공유되었습니다.
* [Unity 5.5] Tutorial: How to create a JetPack by Gamad
* A* Pathfinding (E10: threading) : Sebastian Lague가 별도의 스레드를 활용한 경로 탐색 구현 방법을 공유했습니다.
* iProfiler – Free Script to Display Profiling Stats on Screen in Unity : 게임의 메모리 소모및  비디오 화면 fps등의 정보를 Unity 화면에 표시해주는 무료 프로파일링 툴인 iProfiler 가 소개 되었습니다.

### Data 소식
* Working with Enumerated Values in Entity Framework : Peter Vogel이 Entity Framework에서 열거형 값을 처리하는 방법을 설명했습니다.
