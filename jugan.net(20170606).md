### On .NET 소식 : Brett Morrison

[지난 주 On .NET](https://sec.ch9.ms/ch9/1252/70aaceff-7bc2-4879-8480-421ec8f71252/onnet20170601brettmorrison_mid.mp4)에는 사업가이자 기업의 임원이면서 Microsoft .NET 플랫폼으로 개발하는 Brett Morrison과 함께 했습니다. 그는 [Onestop](http://onestop.com/), ememories 등의 스타트업 회사를 설립했으며 [SpaceX](http://www.spacex.com/)에서도 일한 경력이 있습니다.

//그림

### 금주의 패키지: DateTime Extensions

애플리케이션에서 사용하는 날짜와 관련된 계산은 대부분 간단하며 그리 복잡하지 않습니다. 하지만 "이번 달의 공휴일이 몇 일인가?"와 같은 계산은 조금 복잡합니다. 이런 경우 [DateTime Extensions](https://github.com/joaomatossilva/DateTimeExtensions/) 프로젝트를 활용하면 도움을 받을 수 있습니다. 이 라이브러리는 현재 24개 문화권의 공휴일이 정확하게 설정되어 있고, 이를 계산에 이용할 수 있습니다.

//예제코드

* [DateTime Extensions Web site](http://www.kspace.pt/DateTimeExtensions/)
* [DateTime Extensions on GitHub](https://github.com/joaomatossilva/DateTimeExtensions)
* [DateTime Extensions on NuGet](https://www.nuget.org/packages/DateTimeExtensions)
* [Sample web site](http://datetimeextensions.azurewebsites.net/)

### .NET 소식

* [.NET Core and .NET Framework Working Together, Or: The Magic of .NET Standard](https://dotnetcore.gaprogman.com/2017/06/01/net-core-and-net-framework-working-together-or-the-magic-of-net-standard/) : Jamie Taylor가 .NET Standard를 소개했습니다.
* [Announcing Reactive Extensions for .NET 4.0 Preview 1!](https://oren.codes/2017/05/27/announcing-reactive-extensions-for-net-4-0-preview-1/) : Oren Novotny가 .NET 4.0 Preview 1버전의 Reactive 확장기능을 소개했습니다.
* [The Coming .NET Renaissance](https://www.hanselman.com/blog/ChoiceAmongstCrossplatformNETIDEsVSCodeVisualStudioForMacJetBrainsRider.aspx) : Aaron Stannard가 .NET 플랫폼의 비전과 가능성을 설명했습니다.
* [Choice amongst cross-platform .NET IDEs – VS Code, Visual Studio for Mac, JetBrains Rider](https://www.hanselman.com/blog/ChoiceAmongstCrossplatformNETIDEsVSCodeVisualStudioForMacJetBrainsRider.aspx) : Scott Hanselman이 크로스 플랫폼 .NET용 개발 툴인 VS Code, Visual Studio for Mac, JetBrains Rider를 소개했습니다.
* [Array Pool](https://csharp.christiannagel.com/2017/05/31/arraypool/) : Christian Nagel이 .NET Core의 Array Pool을 소개했습니다.
* [Creating a simple key-value logger for an object graph](https://danielwertheim.se/creating-a-simple-key-value-logger-for-an-object-graph/) : Daniel Wertheim이 오브젝트 그래프 정보를 표현하는 간단한 로깅기능 구현 방법을 설명했습니다.
* [The Fraternal Twins of Equals and GetHashCode](https://visualstudiomagazine.com/articles/2017/04/01/fraternal-twins-gethashcode-equals-csharp-vb.aspx) : Tim Patrick이 같으면서도 다른 Equals()과 GetHashCode() 메서드를 설명했습니다.
* [.NET Core Support in dotConnect Providers and LinqConnect!](https://www.devart.com/news/2017/net-core-support.html) : Devart에서 .NET Core에서 DB와 LINQ에서 사용할 수 있는 새로운 버전의  ADO.NET data provider의 릴리즈 했습니다. 
* [Docker for .NET Developers (Part 1)An introduction to Docker for .NET developers](https://www.stevejgordon.co.uk/docker-dotnet-developers-part-1) : Steve Gordon이 ".NET 개발자를 위한 도커(파트1)-도커 소개"를 공유했습니다. 
* [Docker for .NET Developers (Part 2) Taking a look at our first dockerfile and building an image for an ASP.NET Core API service](https://www.stevejgordon.co.uk/docker-for-dotnet-developers-part-2) : Steve Gordon이 ".NET 개발자를 위한 도커(파트1)-도커파일 다루어 보기와 ASP.NET Core API 서비스 이미지 만들기"를 공유했습니다. 
* [Using Roslyn refactorings with OmniSharp and Visual Studio Code](https://www.strathweb.com/2017/05/using-roslyn-refactorings-with-omnisharp-and-visual-studio-code/) : Filip W가 OmniSharp과 Visual Studio Code에서 Roslyn의 리팩토링 기능 활용 방법을 설명했습니다.
* [Refactoring dependencies with Autofac Aggregate Services](http://cecilphillip.com/autofac-aggregate-services/) : Cecil Phillip가 Aggregate Service를 쉽게 구현할 수 있도록 도와주는 오픈소스 Autofac 프로젝트를 소개했습니다.
* [ClrMD Part 4 – What callbacks are called by my timers?](http://labs.criteo.com/2017/05/clrmd-part-4-callbacks-called-timers/) : Nasarre Christophe와 Kevin Gosse가 "CLR MD" (Microsoft.Diagnostics.Runtime.dll)의 callbacks 함수 호출에 대해서 설명했습니다 

### ASP.NET 소식

* [IdentityServer4: New & Improved for ASP.NET Core](https://channel9.msdn.com/Events/Techorama/Techorama-2017/BRK02) : Dominick Baier가 ASP.NET Core용 IdentityServer4 서버의 향상된 기능을 소개했습니다.
* [Installing Asp.Net Core Docker For Windows](http://sibeeshpassion.com/installing-asp-net-core-docker-for-windows/) : Sibeesh Passion가 윈도우에 ASP.NET Core Docker 설치방법을 설명했습니다.
* [Getting Started with ASP.NET Core JavaScript Services](http://www.codingflow.net/getting-started-with-asp-net-core-javascript-services/) : Jason Taylor가 ASP.NET Core JavaScript Services를 소개했습니다
* [The Microsoft.AspNetCore.All metapackage is huge, and that’s awesome, thanks to the .NET Core runtime store](https://andrewlock.net/the-microsoft-aspnetcore-all-metapackage-is-huge-and-thats-awesome-thanks-to-the-net-core-runtime-store-2/) : Andrew Lock이 .NET Core의 메타패키지(Microsoft.AspNetCore.All)를 설명했습니다.
* [Using ImageSharp to resize images in ASP.NET Core – Part 4: saving to disk](https://andrewlock.net/using-imagesharp-to-resize-images-in-asp-net-core-part-4-saving-to-disk/) : Andrew Lock이 "ASP.NET Core에서 ImageSharp을 이용한 이미지 resize 방법: 저장하기 - 파트4"를 공유했습니다.
* [Logging in ASP.NET Core – Connecting the pieces](https://codingblast.com/asp-net-core-logging/) : Ibrahim Šuta가 ASP.NET Core에서 여러가지 로깅 방법을 설명했습니다.
* [The end of request validation](https://www.jardinesoftware.net/2017/06/01/the-end-of-request-validation/) : James Jardine가 ASP.NET의 Request Validation을 설명했습니다.
* [Post-Redirect-Get and TempData with ASP.NET Core](https://www.meziantou.net/2017/06/05/post-redirect-get-and-tempdata-with-asp-net-core) : Gérald Barré가 ASP.NET Core의 Post-Redirect-Get(PRG) 패턴을 설명했습니다.
* [Conditional middleware based on request in ASP.NET Core](https://www.devtrends.co.uk/blog/conditional-middleware-based-on-request-in-asp.net-core) : Paul Hiles가 사용자 요청에 따라 다른 미들웨어 호출하는(요청타입별 미들웨어 설정)기능을 설명했습니다.
* [Bypassing IIS Error Messages in ASP.NET](https://weblog.west-wind.com/posts/2017/Jun/01/Bypassing-IIS-Error-Messages-in-ASPNET) : Rick Strahl이 IIS의 에러 메시지 원본의 출력 방법을 설명했습니다.
* [Using VS Code and ASP.NET Core?](https://wildermuth.com/2017/06/04/Using-VS-Code-and-ASP-NET-Core) : Shawn Wildermuth가 "VS Code 를 활용한 ASP.NET Core 애플리케이션 개발" 학습 시리즈 정보를 공유했습니다.
* [Owin middleware in .NET Standard for Application Insights – part 2](https://stapp.space/owin-middleware-in-net-standard-for-application-insights-part-2/) : Piotr Stapp가 ".NET Standard의 OWIN(Open Web Interface for .NET)미들웨어" - 파트2를 소개했습니다.
* [ASP.NET Core Utils – nuget package available](https://devblog.dymel.pl/2017/05/31/asp-net-core-utlis/) : Michal Dymel이 ASP.NET Core용 오픈소스 프로젝트 "AspNetCoreUtils"를 소개했습니다.
* [Implementing a silent token renew in Angular for the OpenID Connect Implicit flow](https://damienbod.com/2017/06/02/implementing-a-silent-token-renew-in-angular-for-the-openid-connect-implicit-flow/) : Damien Bowden이 Angular 환경의 클라이언트에서 OpenID 의 접속토큰 갱신 방법을 설명했습니다.

### C# 소식

* [Practical C# – Select in LINQ](http://www.andreaangella.com/2017/05/practical-c-videos-local-functions-ref-returns-and-locals/) : Andrea Angella가 학습 비디오 "C# 실무 : Select LINQ"를 공유했습니다.
* [Practical C# – Aggregate in LINQ](http://www.andreaangella.com/2017/06/practical-csharp-aggregate-in-linq/) : Andrea Angellaa가 학습 비디오 "C# 실무 : Aggregate LINQ"를 공유했습니다.
* [Practical C# – Sum in LINQ](http://www.andreaangella.com/2017/06/practical-csharp-sum-in-linq/) : Andrea Angellaa가 학습 비디오 "C# 실무 : Sum LINQ"를 공유했습니다.
* [Practical C# – Where in LINQ](http://www.andreaangella.com/2017/06/where-in-linq/) : Andrea Angellaa가 학습 비디오 "C# 실무 : Where LINQ"를 공유했습니다.
* [Strong Typing: a pattern for more robust and maintainable code](https://tech.winton.com/blog/2017/06/strong-typing-a-pattern-for-more-robust-code) : Jos Hickson이 Strong Typing 패턴을 소개했습니다.

### F# 소식

* [Introducing Fable.Remoting: Automated Type-Safe Client-Server Communication for Fable Apps](https://medium.com/@zaid.naom/introducing-fable-remoting-automated-type-safe-client-server-communication-for-fable-apps-e567454d594c) : Zaid Ajaj이 Fable.Remoting을 소개했습니다.
* [(Nearly) Everything You Ever Wanted to Know About F# Active Patterns](https://www.youtube.com/watch?v=I5dKFT_Z-fc&feature=youtu.be) : Hakka Labs에서 F#의 "Active Pattern" 학습 비디오를 공유했습니다.
* [F# Partiall-Applied Unions](https://amazingant.com/blog/2017/05/29/FSharp-Partially-Applied-Unions/) : Anthony Perez가 F#에서 Union을 부분적으로 적용하는 것에 대해 설명합니다.
* [Why you should use F#](https://blogs.msdn.microsoft.com/dotnet/2017/05/31/why-you-should-use-f/) : .NET 개발언어 팀의 Phillip Carter와 Mads Torgersen이 F#의 장점을 설명했습니다.
* [Using Polly with F# async workflows](http://blog.ploeh.dk/2017/05/30/using-polly-with-f-async-workflows/) : Mark Seemann이 비동기 애플리케이션에서 활용할 수 있는 Polly 라이브러리를 소개했습니다.
* [Encapsulation – C# vs F# vs Haskell, equivalent result](http://blog.stermon.com/articles/2017/05/31/encapsulation-csharp-vs-fsharp-vs-haskell-equivalent-result) : Ramón Soto Mathiesen이 C#, F#, Haskell 언어 각각의 "은닉화(Encapsulation)"기능을 공유했습니다.
* [Azure Functions tip: working locally with F# Scripts](http://brandewinder.com/2017/06/01/azure-functions-local-development-with-fsharp-scripts/) : Mathias Brandewinder가 로컬 F# 스크립트를 Azure Function에서 활용하는 방법을 공유했습니다.

### VB 소식
* [Simple .NET Core application using VB.NET](http://gunnarpeipman.com/2017/06/dotnet-core-vbnet/) : Gunnar Peipman이 .NET Core용 VB.NET 애플리케이션의 개발 과정을 공유했습니다.

### Xamarin 소식
* [Xamarin Stable Release: 15.2.2 Xamarin.Android, Xamarin.VS Hotfix](https://releases.xamarin.com/stable-release-15-2-2-xamarin-android-xamarin-vs-hotfix/) : Bri Brothers가 15.2.2 Hotfix 릴리즈 정보를 공유했습니다.
* [Xamarin University To Host Free Webinars in June](https://visualstudiomagazine.com/articles/2017/05/30/xamarin-university-free-webinars.aspx) : Michael Domingo가 6월에 진행되는 Xamarin University의 무료 웨비나 정보를 공유했습니다.
* [New & Upcoming Xamarin Dev Days](https://blog.xamarin.com/new-upcoming-xamarin-dev-days/) : Jayme Singleton이 Xamarin Dev Days 개발자 행사 정보를 공유했습니다.
* [Xamarin Podcast: Previewing Xamarin.Forms 3.0](https://blog.xamarin.com/podcast-previewing-xamarin-forms-3-0/) : Pierce Boggan이 Xamarin 팟케스트 "Xamarin.Forms 3.0 미리보기"편을 공유했습니다.
* [Introducing ELXF: A UI Framework for Concise, Maintainable & Fast Programmatic UI’s for Xamarin.Forms](http://www.leerichardson.com/2017/05/introducing-easylayout-for-xamarinforms.html) : Lee Richardson이 Xamarin.Forms에서 활용할 수 있는 오픈소스 라이브러리 ELXF(EasyLayout.Forms)를 소개했습니다.
* [Introduction to Rest Web Services in Xamarin](http://xamarinui.blogspot.com/2017/05/introduction-to-rest-web-services-in.html) : Asfend Yar가 Xamarin에서 Rest Web Services 활용 방법을 설명했습니다.
* [Shared Components In Xamarin Forms](http://xamarinui.blogspot.com/2017/05/shared-components-in-xamarin-forms.html) : Asfend Yar가 Xamarin Form 에서 컴포넌트 공유방법을 설명했습니다.
* [View Sizing In Xamarin Forms](http://xamarinui.blogspot.com/2017/05/view-sizing-in-xamarin-forms.html) : Asfend Yar가 모바일 환경의 View 크기설정에 대해서 설명했습니다.
* [A simple page-indicator for your android view-pager](http://xleon.net/xamarin/android/a-simple-page-indicator-for-your-android-viewpager.html) : Diego Ponce de León이 안드로이드 view-pager용 page-indicator 개발 방법을 설명했습니다.
* [Xamarin.Tip – Adding Dynamic Elevation to Your Xamarin.Forms Buttons](https://alexdunn.org/2017/05/30/xamarin-tips-adding-dynamic-elevation-to-your-xamarin-forms-buttons/) : Alex Dunn이 동적 그림자효과(그림자의 높이가 변하는)가 적용된 커스텀 버튼의 구현 방법을 설명했습니다.
* [Xamarin.Tip – Mvvm Light and Dependency Injection](https://alexdunn.org/2017/06/01/xamarin-tips-mvvm-light-and-dependency-injection/) : Alex Dunn이 Mvvm Light와 DI(Dependency Injection)의 활용방법을 공유했습니다.
* [Snack Pack 12: Getting Started with Visual Studio for Mac](https://channel9.msdn.com/Shows/XamarinShow/Snack-Pack-12-Getting-Started-with-Visual-Studio-for-Mac) : James Montemagno가 "Snack Pack 12: Visual Studio for Mac 사용하기" 동영상을 공유하였습니다.
* [Text and Icons in Master/Detail Reveal Button on iOS](https://codemilltech.com/text-and-icons-in-master-detail-pages-on-ios/) : Matthew Soucoup이 iOS 의 마스터/디테일 화면의 텍스트, 아이콘 구성방법을 설명했습니다.
* [Things I Think Are Cool: Merge Conflict Podcast](https://codemilltech.com/things-i-think-are-cool-mergeconflict-podcast/) : Matthew Soucoup이 기술 팟캐스트 "Merge Conflict"을 소개했습니다.
* [Use Camera To Take Photo In Xamarin Forms](https://xamarinhelp.com/use-camera-take-photo-xamarin-forms/) : Adam Pedley가 Xamarin Forms에서 사진을 찍기 위한 카메라 활용 방법을 설명했습니다.
* [Xamarin Mobile Apps Continuous Integration and Delivery with Jenkins and HockeyApp](https://www.junian.net/2017/05/xamarin-ci-cd-with-jenkins-and-hockeyapp.html) : Junian Triajianto가 Jenkins와 HockeyApp을 활용한 Xamarin 애플리케이션의 CI/CD 구성 방법을 설명했습니다.
* [Trying Out Xamarin Live Player](https://mindofai.github.io/Trying-Out-Xamarin-Live-Player/) : Bryan Anthony Garcia가 Xamarin Live Player를 소개했습니다.
* [Ambient Properties in Xamarin.Forms](https://nicksnettravels.builttoroam.com/post/2017/05/27/Ambient-Properties-in-XamarinForms.aspx) : Nick Randolph가 Xamarin.Forms의 "Ambient" 속성을 설명했습니다.
* [Toolbar Navigation in Xamarin Forms](https://jfarrell.net/2017/05/28/toolbar-navigation-in-xamarin-forms/) : Jason Farrell이 Xamarin Forms의 Toolbar 구성방법을 설명했습니다.

### Azure 소식
* [Solve production exceptions in no time with Application Insights Snapshots](https://www.patrickvankleef.com/2017/05/31/solve-production-exceptions-in-no-time-with-application-insights-snapshots/) : Patrick van Kleef가 Application Insights에서 새롭게 선보인 Snapshots 기능을 설명했습니다.
* [Azure SQL Data Sync Refresh](https://azure.microsoft.com/blog/azure-sql-data-sync-refresh/) : Joshua Gnanayutham이 Azure SQL Data Sync 를 소개했습니다.
* [Diagnose sudden changes in your app behavior with a click!](https://azure.microsoft.com/blog/diagnose-sudden-changes-in-your-app-behavior-with-a-click/) : Sharon Nakibly가 애플리케이션의 이상을 쉽고 빠르게 감지할 수 있는 Application Insights Analytics를 소개했습니다.
* [Streamlining Kubernetes development with Draft](https://azure.microsoft.com/blog/streamlining-kubernetes-development-with-draft/) : Microsoft Azure팀의 Gabe Monroy가 Kubernetes 클러스터에 활용할 수 있는 오픈소스툴 Draft를 소개했습니다.
* [Azure via C# – Create Azure Blobs](http://www.andreaangella.com/2017/06/azure-via-cs-create-azure-blobs/) : Andrea Angella가 "C#을 이용한 Azure 클라우드 서비스 파일 전송 방법" 학습 비디오를 공유했습니다.
* [Building a JAMstack site with Hugo and Azure Functions](http://conductofcode.io/post/building-a-jamstack-site-with-hugo-and-azure-functions/) : Henrik Lau Eriksson이 Hugo와 Azure Functions을 이용한 Serverless  웹 어플리케이션 개발을 소개했습니다.

### Data 소식

* [UWP and the evolution of touch development](https://blogs.windows.com/buildingapps/2017/05/25/uwp-evolution-touch-development/) : Windows Apps Team에서 UWP 애플리케이션의 터치 이벤트 개발 방법을 소개했습니다.
* [Toolkits, Toolkits, Toolkits!](https://blogs.windows.com/buildingapps/2017/06/02/toolkits-toolkits-toolkits/) : Windows Apps Team에서 UWP 용 오픈소스 툴킷(UWP Community Toolkit, Telerik UI for UWP) 을 소개했습니다.

// 전무님 소개
