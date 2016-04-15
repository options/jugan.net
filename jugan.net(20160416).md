### On.NET 소식
이번주 인터뷰에서는 게임 어플리케이션 개발에 도움을 줄 수 있는 PlayFab에 대해서 알아보겠습니다. PlayFab을 이용해서 멋진 게임 어플리케이션과 게임 서비스를 얼마나 쉽게 만들 수 있는지 인터뷰에서 확인해보겠습니다.

### 금주의 프로젝트 - Math.NET Numerics
오픈소스 수학 라이브러리 Math.NET은 일반적인 수치연산, 대수학 기하학, (영상)신호처리에 대한 풍부한 라이브러리를 포함하고있습니다. 이번주는 Math.NET에 대해서 알아보는 첫시간으로 수치연산에 관련된 라이브러리 기능을 알아보겠습니다.

아래의 코드는 Math.NET를 이용해서 수학적 행열과 백터의 선언및 연산하는 방법을 보여주고 있습니다.

code

위의 코드에서 선언된 백터를 자세히 보면 백터의 좌표가 단순 숫자가 아닌 표현식으로 정의되었음을 알 수 있습니다.
또한 방정식의 해법을 찾는데도 Math.NET를 이용할 수 있으며 통계, 확률 계산및 fit curves(??)에도 사용 가능합니다.  
수학적 계산이 필요한 곳에서는 정말 보물과 같은 라이브러리입니다.

이 패키지에는 라이브러리사용에 도움을 줄수있는 C#, F#, VB언어로 작성된 많은 샘플을 포함하고 있습니다 .


### 이번주의 Xamarin 어플 : Storyo

Storyo는 사용자의 사진과 사진에 포함된 메타데이터(시간및 장소정보)및 여러의미있는 정보들을 바탕으로 아름답고 공유가능한 비디오 스토리를 자동으로 만들어 주는 어플입니다. 이 어플의 개발환경에 Xamarin을 사용했으며 Xamarin 을 이용함으로서 개발팀은 iOS,  Android 두가지 개발 플랫폼의 기술적인 복잡도를 혁신적으로 줄일 수 있었다고 합니다.  결과적으로 개발 기간을 단축시킬 수 있었고 약 170개국에 자신의 어플을 좀 더 빠르게 발표할 수 있었습니다.

### 이번주의 컨트롤 : SideDrawer (UWP / Xamarin)
Telerik의 SideDrawer는 슬라이드 내비게이션기능이 포함된 모바일 어플리케이션용 컨트롤입니다. 이 컨트롤은 UWP과 Xamarin 환경에서 동작하며 Android, iOS, Windows 모바일 플랫폼 어플 개발프로젝트에서 사용 가능합니다.

### .NET 소식

* 이제 트위터를 통해서도 Github의 .NET 소식을 접하는것이 가능해졌습니다.: Core CLR, Core FX and Core FX Lab, Roslyn, ASP.NET, and Entity Framework
* Moving to Cake (C# Make) : Laurent Kempé이 C# 빌드 엔진인 Cake에 대한 사용 경험을 공유했습니다.
* Nick Landry on .NET Framework and .NET Core (video) : Nick Landry이 David Giard.과 함께  .NET Framework과 .NET Core의 차이점을 공유하고 MS가 .NET Core 만들게 된 배경과 어느 상황에 이것을 써야 하는지 설명해주었습니다. 
* Survey Report: Who is the .NET Developer of 2016? by Nora Georgieva.
* Visual Studio “15”: Installing Just What You Need by Cathy Sullivan.
* Robert Sundström started a nice minimalist HTTP Listener for .NET Core and UWP that will actually work on a Raspberry Pi running Windows 10 for IoT.
* Detecting and Solving Memory Problems in .NET (free E-Book) : Alexey Totin.이 메모리 문제를 검출하고 해결하는 방법을 e-book에 공유했습니다.
* Automatically create and publish a NuGet package using VSTS : Mauricio Avilés Diaz.이 VSTS 를 이용해서 NuGet 패키지를 자동으로 생성/배포하는 방법을 공유했습니다.
* What I think is and is not better about .Net OSS these days, and its follow-up post : Jeremy D. Miller이 최근 .NET OSS 기반 기술 방향에 대한 자신의 생각을 공유했습니다.
* Biometric Authentication with Microsoft Passport and The Xamarin Promise – Realized! by Sam Basu.
* Idempotent Aggregates : Derek Comartin.
* Closure-based State: C# : Ted Neward

### ASP.NET 소식
최신 ASP.NET Community Standup 소식을 유트브를 통해서 확인할수있읍니다. 이와 더불어 .NET Web Development and Tools Blog에서 관련내용을 문서도로 확인할수있습니다. 
* The New Configuration Model in ASP.NET Core : Julio Avellaneda가 ASP.NET Core에 새롭게 적용된 Configuration Model 에 대한 설명을 공유했습니다.
* Inline Route Constraints in ASP.NET Core MVC by Marius Schulz.
* Creating Dynamic PDFs in ASP.NET MVC using iTextSharp by Jonathan Danylko.
* Understanding The Role of Startup.cs File In ASP.NET Core Project by Sunny Sharma.
* Configuring ASP.NET and IIS Request Length for POST Data by Rick Strahl.
* Encryption and Decryption in ASP.NET Core by Mike Brind.
* Performance competition is a good thing by TechEmpower.
* Developing in Docker Containers by Steve Lasker.
* Secure file download using Identity Server 4, Angular 2, and ASP.NET Core by Damien Bod.
* Emails using Mailgun in ASP.NET Core by Eric L. Anderson.
* IdentityServer 4 on Docker by Ankit Sinha.
* Ensure your ASP.NET actions aren’t missing authorization with unit tests by Eli Weinstock-Herman.
* Predefined Namespaces And Custom Base View Page in ASP.NET Core 1.0 MVC by Filip W.
.

### F# 소식
* The F# Software Foundation has launched the F# Speakers Program
* From Community to Cloud with F#, by Don Syme
* Designing with Capabilities for Fun and Profit, by Scott Wlaschin
* Hosting Suave in the Azure App Service, by Isaac Abraham
* Deploying an F# Web Application with Suave, by Tomas Petricek
* Hopac: Getting Started with Jobs, by Marcus Griep

### Games
* Developing The New Input System Together With You, by Rune Skovbo Johansen.

* Basic Unity Tutorial for Steam VR & Vive (Setting up HMD and controllers) – Video, by Sean Lee.
