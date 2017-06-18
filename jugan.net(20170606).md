주간닷넷 2017년 06월 06일

### On .NET 소식 : Brett Morrison

[지난 주 On .NET]()(링크)에는 사업가이자 기업 임원이면서 Microsoft 환경에서 .NET 플랫폼으로 직접 코딩및 개발하는 Brett Morrison와 함께 했습니다. 그는 Onestop(링크), eMemories 등의 스타트업 회사를 설립했으며 SpaceX(링크) 프로젝트에도 참여했습니다.

//그림

### 금주의 패키지: DateTime Extensions
어플리케이션에서 활용한 날짜관련 계산은 대부분 간단하며 그리 어렵지않습니다. "하지만 이번 한달 공휴일이 몇일인가?"와 같은 계산은 좀 복잡해집니다. 이런 경우 DateTime Extensions(링크) 프로젝트를 활용하면 도움을 받을 수 있습니다. 이 라이브러리는 현재 24개 문화권의 공휴일이 정확하게 설정되어 있으며 이를 바탕으로 계산에 응용할 수 있습니다.

//예제코드
DateTimeCultureInfo pt_ci = new DateTimeCultureInfo("pt-PT");
DateTime startDate = new DateTime(2011, 4, 21);

//21-04-2011 - start
//22-04-2011 - holiday
//23-04-2011 - Saturday
//24-04-2011 - Sunday
//25-04-2011 - holiday
//26-04-2011 - end

DateTime endDate = startDate.AddWorkingDays( 1, pt_ci);
Assert.IsTrue(endDate == startDate.AddDays(5));


* DateTime Extensions Web site
* DateTime Extensions on GitHub
* DateTime Extensions on NuGet
* Sample web site


### .NET 소식
* .NET Core and .NET Framework Working Together, Or: The Magic of .NET Standard : Jamie Taylor가 .NET Standard를 소개했습니다.
* Announcing Reactive Extensions for .NET 4.0 Preview 1! by Oren Novotny가 .NET 4.0 Preview 1버전의 Reactive 확장기능을 소개했습니다.
* The Coming .NET Renaissance : Aaron Stannard가 닷넷 플랫폼의 비전과 가능성을 설명했습니다.
* Choice amongst cross-platform .NET IDEs – VS Code, Visual Studio for Mac, JetBrains Rider : Scott Hanselman이 크로스플랫폼 .NET용 개발 개발툴(VS를 제외한)-VS Code, Visual Studio for Mac, JetBrains Rider를 소개했습니다.
* Array Pool : Christian Nagel이 .NET Core의 Array Pool을 소개했습니다.
* Creating a simple key-value logger for an object graph : Daniel Wertheim 오브젝트 그래프 정보를 표현하는 간단한 로깅기능 구현 방법을 설명했습니다.
* The Fraternal Twins of Equals and GetHashCode : Tim Patrick이 같으면서도 다른 Equals()과 GetHashCode() 메서드를 설명했습니다.
* .NET Core Support in dotConnect Providers and LinqConnect! : Devart에서 .NET Core환경에서 DB와 LINQ에서 사용할 수 있는 새로운 버전의  ADO.NET data provider의 릴리즈 했습니다. 
* Docker for .NET Developers (Part 1)An introduction to Docker for .NET developers : Steve Gordon이 "닷넷 개발자를 위한 도커(파트1)-도커 소개"를 공유했습니다. 
* Docker for .NET Developers (Part 2) Taking a look at our first dockerfile and building an image for an ASP.NET Core API service : Steve Gordon이 "닷넷 개발자를 위한 도커(파트1)-도커파일 다루어 보기와 ASP.NET Core API 서비스 이미지 만들기"를 공유했습니다. 
* Using Roslyn refactorings with OmniSharp and Visual Studio Code : Filip W가 OmniSharp과 Visual Studio Code환경에서 Roslyn의 리팩토링 기능 활용 방법을 설명했습니다.
* Refactoring dependencies with Autofac Aggregate Services : Cecil Phillip가 Aggregate Service를 쉽게 구현할 수 있도록 도와주는 오픈소스 Autofac 프로젝트를 소개했습니다.
* ClrMD Part 4 – What callbacks are called by my timers? : Nasarre Christophe와 Kevin Gosse가 "CLR MD" (Microsoft.Diagnostics.Runtime.dll)의 callbacks 함수 호출에 대해서 설명했습니다 

### ASP.NET 소식
* IdentityServer4: New & Improved for ASP.NET Core : Dominick Baier가 ASP.NET Core용 IdentityServer4 서버의 향상된 기능을 소개했습니다.
* Installing Asp.Net Core Docker For Windows : Sibeesh Passion가 윈도우 Asp.Net Core Docker를 설치방법을 설명했습니다.
* Getting Started with ASP.NET Core JavaScript Services : Jason Taylor가 ASP.NET Core JavaScript Services를 소개했습니다
* The Microsoft.AspNetCore.All metapackage is huge, and that’s awesome, thanks to the .NET Core runtime store : Andrew Lock이  .NET Core의  메타패키지(Microsoft.AspNetCore.All)를 설명했습니다.
* Using ImageSharp to resize images in ASP.NET Core – Part 4: saving to disk : Andrew Lock이 "ASP.NET Core에서 ImageSharp 을 이용한 이미지 resize 방법: 저장하기 - 파트4"를 공유했습니다.
* Logging in ASP.NET Core – Connecting the pieces : Ibrahim Šuta가 ASP.NET Core 환경에서의 여러 로깅 방법을 설명했습니다.
* The end of request validation : James Jardine가 ASP.NET의 Request Validation을 설명했습니다.
* Post-Redirect-Get and TempData with ASP.NET Core : Gérald Barré가 ASP.NET Core의 Post-Redirect-Get (PRG) 패턴을 설명했습니다.
* Conditional middleware based on request in ASP.NET Core : Paul Hiles가 사용자 요청에 따라 다른 미들웨어 호출하는(요청타입별 미들웨어 설정)기능을 설명했습니다.
* Bypassing IIS Error Messages in ASP.NET : Rick Strahl이 IIS의 에러 메시지 원본의 출력 방법을 설명했습니다.
* Using VS Code and ASP.NET Core? : Shawn Wildermuth가  "VS Code 를 활용한 ASP.NET Core 어플리케이션 개발" 학습 시리스 정보를 공유했습니다.
* Owin middleware in .NET Standard for Application Insights – part 2 : Piotr Stapp가 ".NET Standard의 OWIN(Open Web Interface for .NET)미들웨어"-파트2를 소개했습니다.
* ASP.NET Core Utils – nuget package available : Michal Dymel이 ASP.NET Core용 오픈소스 프로젝트 "AspNetCoreUtils"를 소개했습니다.
* Implementing a silent token renew in Angular for the OpenID Connect Implicit flow : Damien Bowden이 Angular 환경의 클라이언트에서 OpenID 의 접속토큰 갱신 방법을 설명했습니다.

### C# 소식
* Practical C# – Select in LINQ : Andrea Angella가 학습 비디오 "C# 실무 : Select LINQ"를 공유했습니다.
* Practical C# – Aggregate in LINQ by Andrea Angellaa가 학습 비디오 "C# 실무 : Aggregate LINQ"를 공유했습니다.
* Practical C# – Sum in LINQ by Andrea Angellaa가 학습 비디오 "C# 실무 : Sum LINQ"를 공유했습니다.
* Practical C# – Where in LINQ by Andrea Angellaa가 학습 비디오 "C# 실무 : Where LINQ"를 공유했습니다.
* Strong Typing: a pattern for more robust and maintainable code : Jos Hickson이 Strong Typing 패턴을 소개했습니다.

### F# 소식
* Introducing Fable.Remoting: Automated Type-Safe Client-Server Communication for Fable Apps : Zaid Ajaj이 Fable.Remoting을 소개했습니다.
(Nearly) Everything You Ever Wanted to Know About F# Active Patterns : Hakka Labs에서  F#의 "Active Pattern" 학습 비디오를 공유했습니다.
* F# Partiall-Applied Unions by Anthony Perez.
* Why you should use F# : .NET 개발언어 팀의 Phillip Carter와 Mads Torgersen이 F#의 장점을 설명했습니다.
* Using Polly with F# async workflows by Mark Seemann : Mark Seemann이 비동기 어플리케이션에서 활용할 수 있는 Polly 라이브러리를 소개했습니다.
* Encapsulation – C# vs F# vs Haskell, equivalent result : Ramón Soto Mathiesen이 C#, F#, Haskell 언어 각각의 "은익화(Encapsulation)"기능을 공유했습니다..
* Azure Functions tip: working locally with F# Scripts : Mathias Brandewinder가 로컬 F# 스크립을 Azure Function에서 활용하는 방법을 공유했습니다.

### VB 소식
* Simple .NET Core application using VB.NET : Gunnar Peipman이 .NET Core용 VB.NET 어플리케이션의 개발 과정을 공유했습니다.


### Xamarin 소식
* Xamarin Stable Release: 15.2.2 Xamarin.Android, Xamarin.VS Hotfix : Bri Brothers가 15.2.2 Hotfix 릴리즈 정보를 공유했습니다.
* Xamarin University To Host Free Webinars in June : Michael Domingo가 6월에 진행되는 Xamarin University의 무료 웨비나 정보를 공유했습니다.
* New & Upcoming Xamarin Dev Days : Jayme Singleton이 Xamarin Dev Days 개발자 행사 정보를 공유했습니다.
* Xamarin Podcast: Previewing Xamarin.Forms 3.0 : Pierce Boggan이 Xamarin 팟케스트 "Xamarin.Forms 3.0 미리보기"편을 공유했습니다.
* Introducing ELXF: A UI Framework for Concise, Maintainable & Fast Programmatic UI’s for Xamarin.Forms : Lee Richardson이 Xamarin.Forms에서 활용할 수 있는 오픈소스 라이브러리 ELXF(EasyLayout.Forms)을 소개했습니다
* Introduction to Rest Web Services in Xamarin : Asfend Yar가 Xamarin환경에서 Rest Web Services 활용 방법을 설명했습니다.
* Shared Components In Xamarin Forms : Asfend Yar가 Xamarin Form 개발 환경에서 컴포넌트 공유방법을 설명했습니다.
* View Sizing In Xamarin Forms by Asfend Yar가 모바일 환경의 View 크기설정에  대해서 설명했습니다.
* A simple page-indicator for your android view-pager : Diego Ponce de León이 안드로이드 view-pager용 page-indicator 개발 방법을 설명했습니다.
* Xamarin.Tip – Adding Dynamic Elevation to Your Xamarin.Forms Buttons : Alex Dunn이 동적 그림자효과(그림자의 높이가 변하는)가 적용된 커스텀 버튼의 구현 방법을 설명했습니다.
* Xamarin.Tip – Mvvm Light and Dependency Injection : Alex Dunn이 Mvvm Light 과 DI(Dependency Injection)의 활용방법을 공유했습니다.
* Snack Pack 12: Getting Started with Visual Studio for Mac :  James Montemagno 가 "Snack Pack 12: Visual Studio for Mac 사용하기" 동영상을 공유하였습니다.
* Text and Icons in Master/Detail Reveal Button on iOS : Matthew Soucoup이 iOS 의 마스터/디테일 화면의 텍스트,아이콘 구성방법을 설명했습니다.
* Things I Think Are Cool: Merge Conflict Podcast : Matthew Soucoup이 기술 팟케스트 "Merge Conflict"을 소개했습니다.
* Use Camera To Take Photo In Xamarin Forms : Adam Pedley가 Xamarin Forms에서 사진을 찍기 위한 카메라 활용 방법을 설명했습니다.
* Xamarin Mobile Apps Continuous Integration and Delivery with Jenkins and HockeyApp : Junian Triajianto가 Jenkins와 HockeyApp을 활용한 Xamarin 어플리케이션의 CI/CD 개발 방법을 설명했습니다.
* Trying Out Xamarin Live Player : Bryan Anthony Garcia가 Xamarin Live Player를 소개했습니다.
* Ambient Properties in Xamarin.Forms : Nick Randolph가 Xamarin.Forms의 "Ambient" 속성을 설명했습니다.
* Toolbar Navigation in Xamarin Forms : Jason Farrell이 Xamarin Forms의 Toolbar 구성방법을 설명했습니다.

### Azure 소식
* Solve production exceptions in no time with Application Insights Snapshots : Patrick van Kleef가 Application Insights에서 새롭게 선보인 Snapshots 기능을 설명했습니다.
* Azure SQL Data Sync Refresh : Joshua Gnanayutham이 Azure SQL Data Sync 를 소개했습니다.
* Diagnose sudden changes in your app behavior with a click! : Sharon Nakibly가 어플리케이션의 이상을 빠르고 쉽게 감지할 수 있는 Application Insights Analytics을 소개했습니다.
* Streamlining Kubernetes development with Draft : Microsoft Azure팀의 Gabe Monroy가 Kubernetes 클러스터에 활용할 수 있는  오픈소스툴 Draft를 소개했습니다.
* Azure via C# – Create Azure Blobs : Andrea Angella가 "C#을 이용한 Azure 클라우드 서비스 파일 전송 방법" 학습 비디오를 공유했습니다.
* Building a JAMstack site with Hugo and Azure Functions : Henrik Lau Eriksson이 Hugo와 Azure Functions을 이용한 Serverless  웹 어플리케이션 개발을 소개했습니다.

### Data 소식
* UWP and the evolution of touch development : Windows Apps Team에서 UWP 어플리케이션의 터치 이벤트 개발 방법을 소개했습니다.
* Toolkits, Toolkits, Toolkits! : Windows Apps Team에서 UWP 용 오픈소스 툴킷(UWP Community Toolkit, Telerik UI for UWP) 을 소개했습니다.

// 전무님 소개
