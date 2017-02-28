여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On .NET 소식

[지난 주 On .NET]()(링크)에는 도커 이미지를 통한 ASP .NET의 실행과 .NET Core의 .csproj 프로젝트 타입에 관련된 변경사항에 대해서 알아보겠습니다.

//그림

[이번 주 On .NET]에는 [Phil Haack](링크)이 쇼에 참여합니다. Phil은 이전에 ASP.NET MVC 프로그램 매니저 였으며 현재는 GitHub를 위해서 일하고 있습니다. 

### 금주의 툴: BenchmarkDotNet
프로젝트가 성공적으로 마무리되고 어플리케이션의 성능을 향상시키기 위해서 엔지니어는 수많은  솔수션들을 비교 분석하는 벤치마킹 작업 하게됩니다. 벤치마킹을 위한 여러 방법들이 존재하지만 올바른 벤치마킹을 수행하려면 작업이 까다롭거나 반복적이기 마련입니다. 단순히 Stopwatch 객체를 통한 실행 시간을 측정하는 것만이 아닌 더 많은 작업이 요구됩니다.

BenchmarkDotNet은 특정 코드의 수행시간, 실행된 횟수등의 정보를 개발자가 쉽게 확인할 수 있도록 많은 코드 라이브러리를 제공해 줍니다. BenchmarkDotNet은 어플리케이션의 warmup및 cooldown 시간을 고려하도록 설정 할 수 있으며 총 실행시간의 평균, 표준 편차등 여러 통계정보도 계산해줍니다. 또 이러한 정보를 바탕으로 다양한 형식의 보고서 작성도 지원해줍니다.
 
https://github.com/dotnet/BenchmarkDotNet

//코드

GitHub에 공유된 benchmark-net.cs 파일의 코드 내용

### 금주의 게임 : Magicka
Magicka는 북유럽 신화를 배경으로한 액션 어드벤처 장르의 게임입니다. 플레이어는 게임에서 세상을 혼란속으로 빠트리려는 악의 마법사를 심판하는 성스러운 마법사 역할을 수행하게 됩니다. 게임 Magicka의 특징으로는 다양한 아이템들을 통해 마법사 주문을 조합할 수 있으며 최대 3명의 플레이어가 동시에 함께 즐기는 협동 플레이도 가능합니다.

//그림  

Magicka(링크)는 Arrowhead Game Studios(링크)에서 C#(링크)과   XNA(링크)를 이용하여 개발되었으며 현재 Steam을 통해서 즐기실 수 있습니다. 

### .NET 소식
* The .NET language strategy : Mads Torgersen이 닷넷 개발 언어의 특징과 전략을 설명했습니다.
* Digging deeper into the Visual Basic language strategy : Anthony D. Green이 비주얼 베이직 언어의 특징과 전략을 소개했습니다.
* Cross-platform drawing with SkiaSharp : Matthew Leibowitz가 구글의 2D 그래픽 라이브러리인 SkiaSharp의 활용법을 설명했습니다.
* NuGet: introducing scoped API keys : Anand Gaurav이 NuGet의 scoped API key를 설명했습니다.
* How do .NET delegates work? : Matt Warren이 .NET의 델리게이트 타입을 설명했습니다.
* Application Insights telemetry processors : Maarten Balliauw가 Application Insight 원격진단 서비스를 설명했습니다.
* Dissecting the new() constraint in C#: a perfect example of a leaky abstraction : Sergey Teplyakov가 C#의 new() 조건 키워드를 설명했습니다.
* Pattern matching in C# 7.0 case blocks : Tim Patrick이 C# 7.0의 case 문에 사용할 수 있는 새로운 패턴 매칭에 대해서 소개했습니다. 
* Tackling tuples: understanding the new C# 7 value type : Christian Gaetano가 C# 7.0의 새로운 값형식중 하나인 tuples 타입을 소개했습니다.
* C# 7.0 out vars and ref returns : Christian Nagel이 C# 7.0의 새로운 기능 out vars, ref locals, ref returns 을 설명했습니다.
* Dependency injection, logging and configuration in a .NET Core console application :Chad Ramos가 .NET Core 콘솔 어플리케이션에서 D/P(Dependency injection)를 이용한 어플리케이션 로깅 및 설정 방법을 설명했습니다.
* Stratis Bitcoin Full Node Daemon Alpha released : Cointelegraph에서 스트라티스 비트코인이의 Full Node Daemon의 알파버전 릴리즈 소식을 공유했습니다. 
* Building DockNetFiddle using Docker and .NET Core : Daniel Jimenez Garcia이 (간단히 사용할 수 있는  온라인 개발 IDE)dotNetFiddle과 같은 기능의 DockNetFiddle 사이트를 도커와  .NET Core를 이용하여 구축하는 방법을 공유했습니다.
* Cross-Platform DevOps for .NET Core : Muhammad Rehan Saeed가 .NET Core를 이용한 다중 플랫폼 프로젝트 진행시 유용하게 사용할 수 있는 여러 툴을 소개했습니다.
* Serverless C# on AWS Lambda (part 1) : Ryan Stelly가 별도의 서버 구축없이 AWS Lambda 서비스에서 C#을 활용하는 방법을 설명했습니다.
* Using Docker env vars in .NET Core : Christian Melendez가 .NET Core에서 도커 환경변수에 접근하는 방법을 설명했습니다.
* .Net Core, Roslyn and Code Generation : Carlos Mendible이 .Net Core 환경에서 Roslyn 을 이용한 코드생성 프로젝트 구현방법을 소개했습니다.
* Visualising my heart rate on stage using a Hue lamp and a heart rate sensor and .NET : Daniel Wertheim이 필립스의 휴램프와 휴브리지 그리고 심장박동 센서를 이용하여 자신의 심장 박동수를 표현하는 프로젝트의 구현방법을 공유했습니다.
* Refactoring towards resilience: evaluating Stripe and SendGrid options : Jimmy Bogard가 "코드 최적화 : (웹 결재  3rd party 시스템) Stripe API의 옵션의 처리방법"(링크)과 "코드 최적화 : (메일 송신 서비스)SendGrid 옵션의 처리방법"(링크) 을 포스팅 했습니다.
* .NET Core on ARM : Steve Desmond가 ARM 기반 우분투 버전 16.04에서 .NET Core를 이용한 "Hello World" 어플리케이션을 테스트한 경험을 공유했습니다.
* C# IL Viewer for Visual Studio Code using Roslyn side project : Joseph Woodward가 Visual Studio Cod에서 사용할 수 있는 C# IL Viewer를 소개했습니다.

### ASP.NET 소식
* Logging using DiagnosticSource in ASP.NET Core : Andrew Lock이 ASP.NET Core환경에서 DiagnosticSource 객체를 이용한 로깅 방법을 설명했습니다.
* Send form input via an Angular 2 component to ASP.NET Core Web API : Jon Hilton이 "ASP.NET Core과 Angular 2를 이용한 날씨확인 페이지 구현"의 시리즈 6번째인 마지막 블로그를 포스팅 했습니다.
* Middleware vs. filters (video) and Saving CPU cycles with static resource hashes : the ASP.NET Monsters에서 "Middleware와 filters의 비교"(링크)와 "정적 리소스 해쉬를 이용한 CPU 점유율 최적화 방법"(링크)를 공유했습니다.
* Using the ASP.NET Core Script TagHelper to polyfill the latest JavaScript features : Scott Sauber가  ASP.NET Core Script TagHelper를 이용한 폴리필(polyfill) 활용방법을 공유했습니다.


### F#
* Type driven domain modelling, part 1: types and property testing and part 2: evolving models with F# : Lucas Reis가 타입 기반 도메인 모델 "파트 1 : 타입과 속성 테스트" (링크)와 "파트 2 :F#을 이용한 모델 구축"(링크)를 공유했습니다.
* F# Historical Acknowledgements : F#의 탄생 배경을 소개했습니다.
* Railway Oriented Programming (Functional approach to error-handling, by Honza Brestan
* Dependency Rejection : Mark Seemann이 Dependency Rejection을 소개했습니다.
* Using R in Excel with NeXL Connector and F# RProvider  : Adam Mlocek이 NeXL Connector 와 F# Rprovider를 활용하여 엑셀에서 통계 패키지 R을 활용하는 방법을 공유했습니다.
* Higher Kindended Types in F# – The Introduction, : Robert Kuzelj이 F#의 HKT(Higher Kindended Types) 타입정보를 공유했습니다.

### Xamarin 소식
* Xamarin Stable Release: Cycle 8 Service Release 2 Xamarin Studio Refresh : Bri Brothers가 Cycle 8 Service Release 2 Xamarin Studio 소식을 공유했습니다.
* Xamarin Beta Release: Cycle 9 RC Refresh Builds : Bri Brothers가 Cycle 9 RC 버전 빌드 소식을 공유했습니다.
* Enhanced device logging in Visual Studio : James Montemagno가 Visual Studio를이용한 효과적인 디바이스 로깅 방법을 소개했습니다.
* Native Facebook authentication with Azure App Service : Mike James가 Azure App Service를 활용한 페이스북 인증방법을 소개했습니다.
* #DocumentDB loves Xamarin: planet scale mobile app in five steps : Kirill Gavrylyuk가 Xamarin환경에서 고가용성의 DocumentDB 의 구축 및 활용방법을 소개했습니다.
* Tips for creating a smooth and fluid Android UI : Jon Douglas가 빠르고 부드러운 안드로이드 UI 구축에 도움이 되는 팁을 공유했습니다.
* Round launcher icons in Android 7.1 : James Montemagno가 안드로이드 7.1의 원형 모양 외관 아이콘 활용방법에 대해서 설명했습니다.
* Samsung releases new preview of Visual Studio Tools for Tizen : Samsung Tizen Team에서 삼성이 타이젠을 위한 Visual Studio Tools for Tizen의 프리뷰 버전 릴리즈 소식을 공유했습니다. 
* Fall in love with Xamarin at an event near you this February : Jayme Singleton이 02월 Xamarin관련 행사 정보를 공유했습니다..
* Integrating in-app purchases in mobile apps : James Montemagno가 모바일 앱에 "인앱구매" 기능을 통합하는 방법을 공유했습니다.
* New HockeySDK releases for Xamarin and Unity : HockeyApp Team에서 Xamarin and Unity에서 활용할 수 있는 새 버전 HockeySDK의 릴리즈 소식을 공유했습니다.
* The Xamarin Show 14: DocumentDB with Kirill Gavrylyuk & The Xamarin Show Snack Pack 8: visualizing XAML with the Xamarin.Forms previewer : James Montemagno가 "Xamarin Show 14 : DocumentDB  소개"(링크)와 "Xamarin Show Snack Pack 8: Xamarin.Forms previewer를 활용한 XAML 디자인"(링크)를 공유했습니다.
* WebView rendering engine configuration, Xamarin Forms profiling, Tracking memory leaks in Xamarin with the profiler, & Using Xamarin Inspector with your live apps : Adam Pedley가 "WebView 랜더링 설정"(링크), "Xamarin Forms 프로파일링"(링크), " Xamarin 메모리 프로파일링"(링크), "실행중인 앱을 Xamarin Inspector로 프로파일링 하기"(링크)를 공유했습니다.
* The underestimated power of color in mobile app design : Nick Babich가 모바일 앱에서 색상,색감의 디자인 중요성을 설명했습니다.
* New Xamarin.Forms item templates! : James Montemagno가 Xamarin.Forms item template을 설명했습니다.
* Creating a reusable styles assembly for Xamarin.Forms : John Miller가 Xamarin.Forms에서 재활용 가능한 스타일 리소스 어셈블리의 구현방법을 설명했습니다.
* Supporting Xamarin.Forms tabbed page in Caliburn.Micro : Nigel Sampson이 Xamarin.Forms에서 Caliburn.Micro 라이브러리를 활용한 탭 페이지의 구성방법을 설명했습니다.
* Unable to connect or debug to Visual Studio Android Emulator with Visual Studio 2017 RC : Nick Randolph가 Visual Studio 2017 RC 버전에서 안드로이드 에뮬레이터에 디버거 연결을 실패한 경험과 해결 방법을 공유했습니다.
* Visual Studio Emulator for Android : David Yardy가 안드로이드 에뮬레이터를 소개했습니다.

### Azure
* Event Hubs .NET Standard client is now generally available : John Taubensee가 .NET Standard 어플리케이션에서 Event Hub를 활용하는 방법을 공유했습니다.
* Creating documents in DocumentDB with Azure Functions HTTP API and Updating documents in DocumentDb : Adrian Hall이 Azure Functions HTTP API를 활용하여 DocumentDB를 생성하고 업데이트하는 방법을 설명했습니다.
* Building Azure Functions: part 1 – creating and binding, part 2 – settings and references, and part 3 – coding concerns : Tim Murphy가 Azure Function을 이용한 활용 방법 "1편 : 생성과 바인딩하기"(링크), "2편 : 설정과 참조하기"(링크), "3편 : 코딩 고려사항"(링크)을 설명했습니다.
* Create a memory dump for your slow performing Web App : Benjamin Perkins이 웹 어플리케션의 성능이슈를 분석하기위한 메모리 덤프의 생성을 효과적으로 하는 방법을 소개했습니다. 

### UWP 소식
* Adding UWP features to your existing PC software : Stefan Wick기 기존 PC 프로그램에 UWP 기능을 추가하는 방법을 소개했습니다.
* How to use Surface Dial with WPF applications : Ricardo Pons이 WPF 어플리케이션에서 Surface Dial 디바이스를 활용하는 방법을 설명했습니다.
* VisualStateManager pitfalls : Martin Zikmund이 VisualStateManager 사용시 주의할 만한 사항을 공유했습니다.
* Primary Live Tile API – Windows 10 : Andrew Bares가 윈도우 10의 라이브 타일 API를 설명했습니다.
* Progress UI and data binding inside toast notifications – Windows 10 Creators Update : leixu2046에서 토스트 알림 UI에서 데이터 바인딩을 이용한 작업 진행 상태 UI의 구현 방법을 설명했습니다.

### Game 소식
* .GAME’s item system – part 1 challenge explained by Stacey Haffner.
* Inventory and store system – part 2 (scriptable objects) by Stacey Haffner.
* Against the burning hells: Diablo III’s road to redemption with Reaper of Souls by GDC.
* [Unity 5] tutorial: how to create a split screen : Gamad에서 "분할 창(split screen)" 구현 방법을 설명했습니다.
* Real Time Strategy in Unity – unit selection GUI by Unit02Games.

// 전무님 소개
