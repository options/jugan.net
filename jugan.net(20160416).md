### On.NET 소식
[이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=hDDd_Pjtbx8)는 단일이며 규모 조정이 쉬운 백앤드 플랫폼을 무료로 제공하는 [PlayFab](https://playfab.com/) 에서 근무하고 계시는 Melissa Benua 와 Matt Augustine 과 이야기 나누었습니다. 클라우드 서비스를 이용하여 놀라운 게임을 쉽게 만드는 방법에 대해 이야기 나누었습니다.  

### 금주의 프로젝트 - Math.NET Numerics
Math.NET 은 .NET에서 수학적인 계산을 제공하는 오픈소스 라이브러리 입니다. 일반적인 수치연산, 대수학, 기하학, (영상)신호처리에 대한 풍부한 라이브러리를 포함합니다. 이번주에는 수치연산 라이브러리를 알아보겠습니다.

아래의 코드는 Math.NET를 이용해서 행렬과 벡터를 선언하는 방법 및 연산하는 법, 그리고 연산을 수행하는 방법을 소개합니다.  

code

위의 코드에서 선언된 백터를 살펴보면 백터의 좌표가 단순 숫자가 아닌 표현식으로 정의되었음을 알 수 있습니다.
또한 방정식의 해법을 찾거나 확률 및 통계, 그리고 데이터를 적합한 곡선으로 근사시키는 fit curve 에도 Math.NET를 이용할 수 있습니다.  
수학적 계산이 필요한 곳에서 정말 유용한 라이브러리입니다.
이 패키지에는 라이브러리사용에 도움을 줄수있는 C#, F#, VB 로 작성된 많은 샘플도 포함되어 있습니다. 

### 이번주의 Xamarin 애플리케이션 - Storyo
[Storyo](http://www.storyoapp.com/) 는 사용자의 사진과 사진에 포함된 메타데이터(시간 및 장소정보)를 포함한 여러 의미있는 정보들을 바탕으로 아름답고, 함께 볼 수 있는 비디오 스토리를 자동으로 만들어 주는 애플리케이션입니다. Xamarin 을 사용하였기 때문에 비디오 랜더링 부분에 대한 솔루션을 [iOS](https://itunes.apple.com/pt/app/storyo/id891398402?l=en&mt=8) 및 [Android](https://play.google.com/store/apps/details?id=com.StoryMatik.Storyo&hl=en) 두가지 플랫폼에서 공유함으로써 기술적인 복잡도를 줄일 수 있었습니다.  결과적으로 개발 기간을 단축시켜 약 170개의 나라의 사용자들에게 더욱 빠르게 애플리케이션을 발표할 수 있었습니다.

### 이번주의 컨트롤 - SideDrawer (UWP / Xamarin)
Telerik 의 SideDrawer 는 애플리케이션에서 선택할 수 있는 메뉴를 보여주는 모바일 애플리케이션 컨트롤입니다. 이 컨트롤은 UWP 와 Xamarin 환경에서 모두 동작하기 때문에 Android, iOS, Windows 을 포함한 어떠한 모바일 플랫폼에서도 사용하실 수 있습니다. 

### .NET 소식
* 이제 트위터를 통해서도 Github의 .NET 소식을 접하는것이 가능해졌습니다 : [Core CLR](https://twitter.com/coreclrissues), [Core FX](https://twitter.com/corefxissues) and [Core FX Lab](https://twitter.com/corefxlabissues), [Roslyn](https://twitter.com/roslynissues), [ASP.NET](https://twitter.com/aspnetissues), and [Entity Framework](https://twitter.com/efissues)
* [Moving to Cake (C# Make)](http://laurentkempe.com/2016/04/05/Moving-to-Cake-CSharp-Make/) : Laurent Kempé  이 C# 빌드 엔진인 Cake 를 사용한 경험을 공유했습니다.
* [Nick Landry on .NET Framework and .NET Core (video)](https://channel9.msdn.com/Blogs/Technology-and-Friends/tf420) : Nick Landry 와 David Giard 가 .NET Framework 및 .NET Core 의 차이점에 대해 의논하고, 마이크로소프트가 .NET Core 를 만들게 된 배경과 사용 예제를 설명해주었습니다. 
* [Survey Report: Who is the .NET Developer of 2016?](http://www.telerik.com/blogs/survey-report-the-dotnet-developer-of-2016) : Nora Georgieva 가 .NET 개발자들을 대상으로 설문조사한 결과를 공유했습니다. 
* [Visual Studio “15”: Installing Just What You Need](https://blogs.msdn.microsoft.com/visualstudio/2016/04/05/visual-studio-15-installing-just-what-you-need/) : Cathy Sullivan 가 마이크로소프트의 새로운 개발환경 Visual Studio “15” 의 달라진 점을 소개합니다. 
* Robert Sundström 가 [.NET Core 와 UWP 용 HTTP 리스너 프로젝트](https://github.com/robertsundstrom/HttpListener)를 소개합니다. IoT를 위해 만들어졌고, 윈도우 10이 설치된 라즈베리 파이에서 동작합니다. 
* [Detecting and Solving Memory Problems in .NET (free E-Book)](http://blog.jetbrains.com/dotnet/2016/04/04/detecting-and-solving-memory-problems-in-net-ebook/) : Alexey Totin 이 메모리 문제를 발견하고 해결하는 방법이 안내된 e-book 을 소개했습니다.
* [Automatically create and publish a NuGet package using VSTS](https://technologies.live/2016/04/01/automatically-create-and-publish-a-nuget-package/) : Mauricio Avilés Diaz 가 VSTS 를 이용해서 NuGet 패키지를 자동으로 생성하고 배포하는 방법을 공유했습니다.
* [What I think is and is not better about .Net OSS these days](https://jeremydmiller.com/2016/04/07/what-i-think-is-and-is-not-better-about-net-oss-these-days/) and [its follow-up post](https://jeremydmiller.com/2016/04/11/a-quick-followup-to-my-opinions-on-net-oss/) : Jeremy D. Miller 이 최근 .NET OSS 기반 기술 방향에 대한 자신의 생각을 공유했습니다.
* [Biometric Authentication with Microsoft Passport](http://developer.telerik.com/featured/powering-apps-microsoft-passport/) and [The Xamarin Promise – Realized!](http://developer.telerik.com/featured/xamarin-promise-realized/) : Sam Basu 가 Microsoft Passport 에서 사용하는 생체 인증 및 마이크로소프트의 자마린 무료배포 소식을 공유했습니다. 
* [Idempotent Aggregates](http://codeopinion.com/idempotent-aggregates/) : Derek Comartin 이 여러번 적용하여도 결과가 달라지지 않는 멱등법칙(Idempotent) 집계함수에 대해 소개합니다.
* [Closure-based State: C#](http://blogs.tedneward.com/patterns/ClosureBasedState-CSharp/) : Ted Neward 이 C# 에서의 Closure-based State 를 구현하는 방법을 예제와 함께 소개합니다.

### ASP.NET 소식
최신 [ASP.NET Community Standup](https://www.youtube.com/playlist?list=PL0M0zPgJ3HSftTAAHttA3JQU4vOjXFquF) 소식을 유트브에서 확인하실 수 있습니다. [.NET Web Development and Tools Blog](https://blogs.msdn.microsoft.com/webdev/tag/communitystandup/) 에서도 관련된 내용을 문서로 확인할 수 있습니다. 
* [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/) : Julio Avellaneda 가 ASP.NET Core 에 새롭게 적용된 Configuration Model 을 설명했습니다. 
* [Inline Route Constraints in ASP.NET Core MVC](https://blog.mariusschulz.com/2016/03/31/inline-route-constraints-in-asp-net-core-mvc) : Marius Schulz 가 ASP.NET Core 와 Web API 2 에 새롭게 추가된 속성 라우팅을 소개합니다. 
* [Creating Dynamic PDFs in ASP.NET MVC using iTextSharp](http://www.danylkoweb.com/Blog/creating-dynamic-pdfs-in-aspnet-mvc-using-itextsharp-EV) : Jonathan Danylko 가 ASP.NET MVC 에서 iTextSharp 를 이용하여 Dynamic PDF 를 만드는 방법을 공유했습니다. 
* [Understanding The Role of Startup.cs File In ASP.NET Core Project](http://www.c-sharpcorner.com/article/understanding-the-role-of-startup-cs-file-in-Asp-Net-core/) : Sunny Sharma 가 ASP.NET Core 프로젝트에서 Startup.cs 파일의 역할을 설명합니다. 
* [Configuring ASP.NET and IIS Request Length for POST Data](http://weblog.west-wind.com/posts/2016/Apr/06/Configuring-ASPNET-and-IIS-Request-Length-for-POST-Data) : Rick Strahl 이 POST data에 ASP.NET 설정과 IIS 요청 길이를  
* [Encryption and Decryption in ASP.NET Core](http://www.mikesdotnetting.com/article/295/encryption-and-decryption-in-asp-net-core) : Mike Brind 가 ASP.NET Core 에서 암호화 및 복호화 방법을 설명합니다. 
* [Performance competition is a good thing](https://www.techempower.com/blog/2016/02/24/performance-competition-is-a-good-thing/) : TechEmpower 블로그에서 ASP.NET 팀의 사례를 들면서 성능 비교를 장려하는 글을 공유했습니다. 
* [Developing in Docker Containers](https://blogs.msdn.microsoft.com/stevelasker/2016/02/18/f5-developing-in-docker-containers-version-0-10-of-docker-tools-for-visual-studio/) : Steve Lasker 가 
* [Secure file download using Identity Server 4, Angular 2, and ASP.NET Core](http://damienbod.com/2016/03/14/secure-file-download-using-identityserver4-angular2-and-asp-net-core/) : Damien Bod 가 Identity Server 4, Angular 2, 그리고 ASP.NET Core 에서 안전하게 파일을 다운로드 받은 방법을 소개합니다. 
* [Emails using Mailgun in ASP.NET Core](http://www.elanderson.net/2016/02/emails-using-mailgun-in-asp-net-core/) : Eric L. Anderson 가 ASP.NET Core 에서 사용할 수 있는 이메일 서비스인 Mailgun 에 대해 설명합니다. 
* [IdentityServer 4 on Docker](https://ankitbko.github.io/2016/03/IdentityServer4-on-Docker/) : Ankit Sinha 가 Docker 에서 ASP.NET Core 로 개발된 IndentifyServer 를 사용하는 방법을 소개했습니다. 
* [Ensure your ASP.NET actions aren’t missing authorization with unit tests](http://blogs.lessthandot.com/index.php/webdev/asp-net-ensure-your-actions-arent-missing-authorization-with-unit-tests/) : Eli Weinstock-Herman 이 단위테스트를 통해 인증을 놓치는 부분이 없도록 하는 방법을 공유했습니다. 
* [Predefined Namespaces And Custom Base View Page in ASP.NET Core 1.0 MVC](http://www.strathweb.com/2016/04/predefined-namespaces-and-custom-base-view-page-in-asp-net-core-1-0-mvc/) : Filip W 가 ASP.NET Core 에서 미리 정의된 이름과 사용자 뷰페이지를 소개했습니다.  
.

### F# 소식
* F# 소프트웨어 재단이 [F# 강연자 프로그램](http://foundation.fsharp.org/speakers_program_launch)을 새로 만들었습니다. 
* [From Community to Cloud with F#](https://vimeo.com/162061772?ref=tw-share) : Don Syme 이 커뮤니티에서 
* [Designing with Capabilities for Fun and Profit](https://vimeo.com/162209391) : Scott Wlaschin 이 재미있고 수익성도 있는 
* [Hosting Suave in the Azure App Service](https://cockneycoder.wordpress.com/2016/04/08/hosting-suave-in-the-azure-app-service/) : Isaac Abraham 이 Azure 앱 서비스 에서 Sauve를 호스팅한 경험을 공유했습니다. 
* [Deploying an F# Web Application with Suave](https://www.youtube.com/watch?v=JgAY7BVzUD8) : Tomas Petricek 이 F# 웹 애플리케이션을 배포했던 경험을 공유했습니다. 
* [Hopac: Getting Started with Jobs](https://neoeinstein.github.io/blog/2016/04-08-hopac-getting-started-with-jobs/index.html) : Marcus Griep 가 

### Games
* [Developing The New Input System Together With You](http://blogs.unity3d.com/2016/04/12/developing-the-new-input-system-together-with-you/) : Rune Skovbo Johansen 가 새로운 Input System 을 제작하는 방법을 설명했습니다. 
* [Basic Unity Tutorial for Steam VR & Vive (Setting up HMD and controllers) – Video](https://www.youtube.com/watch?v=LZTctk19sx8) : Sean Lee 가 VR 과 Vive 를 이용하는 기본 유니티 튜토리얼을 설명합니다. 
