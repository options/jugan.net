여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

###금주의 커뮤니티 소식
Taeyo.NET에서 [http://docs.asp.net]( http://docs.asp.net/)의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.
* [ASP.NET Core 보안 : 요구사항 처리기와 의존성 주입]( http://taeyo.net/Columns/GetArchive.aspx?SEQ=584&PSEQ=39)
* [ASP.NET Core 보안 : 리소스 기반 권한부여]( http://taeyo.net/Columns/GetArchive.aspx?SEQ=585&PSEQ=39)
* [ASP.NET Core 보안 : 뷰 기반 권한부여]( http://taeyo.net/Columns/GetArchive.aspx?SEQ=586&PSEQ=39)
* [ASP.NET Core 보안 : 스키마별 신원 제한]( http://taeyo.net/Columns/GetArchive.aspx?SEQ=587&PSEQ=39)

### On .NET 소식
[지난 주 On .NET]()에서는 도커 이미지를 통한 ASP.NET 실행 방법과 .NET Core .csproj 도구의 일부 변경 사항에 관해 이야기 나누었습니다.
//그림
[이번 주 On .NET]()에서는 Phil Haack와 함께 이야기 나누어보겠습니다. Phil은 이전에 ASP.NET MVC 프로그램 매니저였으며 현재는 GitHub을 위해 일하고 있습니다.

### 금주의 툴: BenchmarkDotNet
프로젝트가 성공적으로 마무리되어도 엔지니어들은 애플리케이션의 기능을 향상시키기 위해 수많은 솔루션을 비교∙분석하는 벤치마킹 작업을 수행합니다.
여러 벤치바킹 방법이 존재하지만 올바른 벤치마킹을 수행하려면 작업이 까다롭거나 반복적이기 마련입니다. 
BenchmarkDotNet은 개발자가 특정 코드의 수행시간, 실행된 횟수 등의 정보를 쉽게 확인할 수 있도록 많은 코드 라이브러리를 제공합니다. 또한 BenchmarkDotNet은 총 실행시간의 평균 시간 및 표준 편차 등 여러 통계 정보도 계산해주며, 이러한 정보를 바탕으로 다양한 형식의 보고서 작성도 지원합니다.

https://github.com/dotnet/BenchmarkDotNet

//코드

GitHub에 공유된 benchmark-net.cs 파일의 코드 내용

### 금주의 게임 : Magicka
Magicka는 노르웨이 신화를 배경으로 한 액션 어드벤처 게임입니다. 플레이어는 게임에서 세상을 혼란 속으로 빠트리려는 악의 마법사를 심판하는 성스러운 마법사 임무를 수행하게 됩니다.
게임 Magicka의 특징은 원소를 어떻게 조합하고 활용하는지에 따라 게임 플레이가 수월하거나 어려워 질 수 있습니다. 총 10개의 원소를 조합법에 따라 조합하면 더욱 특별한 마법을 시전할 수도 있으며, 특정 원소에 약점이 있는 몬스터에게는 치명적인 피해도 입힐 수 있습니다. Magicka는 최대 4명이서 멀티플레이가 가능합니다.

//그림 
Magicka는 Arrowhead Game Studios에서 C#과  XNA를 이용해 개발하였으며, 현재 Steam을 통해즐기실 수 있습니다.

### .NET 소식
* The .NET language strategy : Mads Torgersen이 닷넷 개발 언어의 특징과 전략을 설명합니다.
* Digging deeper into the Visual Basic language strategy : Anthony D. Green이 비주얼 베이직 언어의 특징과 전략을 소개합니다.
* Cross-platform drawing with SkiaSharp : Matthew Leibowitz가 구글의 2D 그래픽 라이브러리, SkiaSharp 활용 방법을 설명합니다.
* NuGet: introducing scoped API keys : Anand Gaurav이 NuGet의 scoped API key에 관해 설명합니다.
* How do .NET delegates work? : Matt Warren이 .NET의 델리게이트 타입에 관해 설명합니다.
* Application Insights telemetry processors : Maarten Balliauw가 Application Insight 원격진단 서비스를 소개합니다.
* Dissecting the new() constraint in C#: a perfect example of a leaky abstraction : Sergey Teplyakov가 C#의 new() 조건 키워드에 관해 설명합니다.
* Pattern matching in C# 7.0 case blocks : Tim Patrick이 C# 7.0의 case 문에 사용할 수 있는 새로운 패턴 매칭에 관해 소개합니다. 
* Tackling tuples: understanding the new C# 7 value type : Christian Gaetano가 C# 7.0의 새로운 타입인 ‘tuples’을 소개합니다.
* C# 7.0 out vars and ref returns : Christian Nagel이 C# 7.0의 새로운 기능 out vars, ref locals, ref returns에 관해 설명합니다.
* Dependency injection, logging and configuration in a .NET Core console application : Chad Ramos가 .NET Core 콘솔 애플리케이션에서 D/P(Dependency injection)를 이용한 애플리케이션 로깅 및 설정 방법에 관해 설명합니다.
* Stratis Bitcoin Full Node Daemon Alpha released : Cointelegraph에서 Stratis 비트코인의 Full Node Daemon 알파버전 출시 소식을 공유했습니다. 
* Building DockNetFiddle using Docker and .NET Core : Daniel Jimenez Garcia이 Docker에 대한 설명과 더불어 dotNetFiddle의 고유 버전을 구축하여 Docker 컨테이너에서 ASP.NET 핵심 응용 프로그램을 실행하는 방법을 공유하였습니다.
* Cross-Platform DevOps for .NET Core : Muhammad Rehan Saeed가 .NET Core 프로젝트에서 유용하게 사용할 수 있는 여러 툴을 소개합니다.
* Serverless C# on AWS Lambda (part 1) : Ryan Stelly가 서버 구축없이 AWS Lambda 서비스에서 C#을 사용하는 방법을 소개합니다.
* Using Docker env vars in .NET Core : Christian Melendez가 .NET Core에서 도커 환경변수에 접근하는 방법을 설명합니다.
* .Net Core, Roslyn and Code Generation : Carlos Mendible이 .Net Core 환경에서 Roslyn로 코드생성 프로젝트를 구현하는 방법을 소개합니다.
* Visualising my heart rate on stage using a Hue lamp and a heart rate sensor and .NET : Daniel Wertheim이 필립스의 휴램프(스마트 조명)과 심장박동 센서를 이용하여 심장 박동수를 시각화하는 프로젝트 구현방법을 공유하였습니다.
* Refactoring towards resilience: evaluating Stripe and SendGrid options : Jimmy Bogard가 코드 최적화를 위한 “(웹 결재 3rd party 시스템) Stripe API 옵션 처리방법"편과 “(메일 송신 서비스) SendGrid 옵션 처리방법"을 공유했습니다.
* .NET Core on ARM : Steve Desmond가 ARM 기반인 우분투 버전 16.04에서 .NET Core로 "Hello World" 애플리케이션을 테스트한 경험을 공유했습니다.
* C# IL Viewer for Visual Studio Code using Roslyn side project : Joseph Woodward가 Visual Studio Code에서 사용할 수 있는 C# IL Viewer를 소개합니다.

### ASP.NET 소식
* Logging using DiagnosticSource in ASP.NET Core : Andrew Lock이 ASP.NET Core환경에서 DiagnosticSource 객체를 이용한 로깅 방법을 설명합니다.
* Send form input via an Angular 2 component to ASP.NET Core Web API : Jon Hilton이 연재중인“ASP.NET Core과 Angular 2를 이용한 날씨확인 페이지 구현"의 마지막 시리즈가 블로그에 포스팅되었습니다.
* Middleware vs. filters (video) and Saving CPU cycles with static resource hashes : The ASP.NET Monsters에서 "Middleware와 filters의 비교"와 "정적 리소스 해쉬를 이용한 CPU 점유율 최적화 방법"를 공유했습니다.
* Using the ASP.NET Core Script TagHelper to polyfill the latest JavaScript features : Scott Sauber가 ASP.NET Core Script TagHelper를 이용한 폴리필(polyfill) 활용방법을 공유했습니다.

### F#
* Type driven domain modelling, part 1: types and property testing and part 2: evolving models with F# : Lucas Reis가 타입 기반 도메인 모델 "파트 1 : 타입과 속성 테스트" 와 "파트 2 :F#을 이용한 모델 구축"를 공유했습니다.
* F# Historical Acknowledgements : F#의 탄생 배경을 소개합니다.
* Railway Oriented Programming (Functional approach to error-handling, Honza Brestan가 Railway 지향 프로그래밍, 에러 처리에 대한 기능적 접근방법에 관해 설명합니다.
* Dependency Rejection : Mark Seemann이 Dependency Rejection을 소개합니다.
* Using R in Excel with NeXL Connector and F# RProvider : Adam Mlocek이 NeXL Connector과 F# Rprovider으로 엑셀에서 R언어를 활용하는 방법을 공유했습니다.
* Higher Kindended Types in F# – The Introduction, : Robert Kuzelj이 F#의 HKT(Higher Kindended Types) 타입을 소개합니다.

### Xamarin 소식
* Xamarin Stable Release: Cycle 8 Service Release 2 Xamarin Studio Refresh : 자마린 주요 릴리스를 소식을 전하는 Cycle 8 채널에서 Xamarin Studio에 대한 업데이트 소식을 전합니다. 
* Xamarin Beta Release: Cycle 9 RC Refresh Builds : Bri Brothers가 Cycle 9 RC 버전 빌드 소식을 공유했습니다.
* Enhanced device logging in Visual Studio : James Montemagno가 Visual Studio를 이용한 효과적인 디바이스 로깅 방법을 소개합니다.
* Native Facebook authentication with Azure App Service : Mike James가 Azure App Service로 네이트브 페이스북에 인증하는 방법을 소개합니다.
* #DocumentDB loves Xamarin: planet scale mobile app in five steps : Kirill Gavrylyuk가 Xamarin에서 고가용성 DocumentDB 구축 및 활용방법을 소개합니다.
* Tips for creating a smooth and fluid Android UI : Jon Douglas가 빠르고 부드러운 안드로이드 UI 를 구축하는 몇가지 팁을 공유했습니다.
* Round launcher icons in Android 7.1 : James Montemagno가 Android Nouget 7.1버전에서 업데이트된 애플리케이션 실행 아이콘을 활용하는 방법에 관해 소개합니다.
* Samsung releases new preview of Visual Studio Tools for Tizen : Samsung Tizen Team에서 Visual Studio Tools for Tizen 프리뷰 버전 출시 소식을 공유했습니다.
* Fall in love with Xamarin at an event near you this February : Jayme Singleton이 2월 Xamarin 교육 세미나 일정을 공유했습니다.
* Integrating in-app purchases in mobile apps : James Montemagno가 모바일 앱에 "인앱구매" 기능을 통합하는 방법을 공유했습니다.
* New HockeySDK releases for Xamarin and Unity : HockeyApp Team에서 Xamarin과 Unity에서 사용할 수 있는 새로운 HockeySDK 출시 소식을 공유했습니다. 
* The Xamarin Show 14: DocumentDB with Kirill Gavrylyuk & The Xamarin Show Snack Pack 8: visualizing XAML with the Xamarin.Forms previewer : James Montemagno가 연재중인 Xamarin Show의 14번째 시리즈,  ‘’DocumentDB 소개” 편과 Snack Pack의 8번째 시리즈,  “Xamarin.Forms previewer를 활용한 XAML 디자인" 편을 공유하였습니다.
* WebView rendering engine configuration, Xamarin Forms profiling, Tracking memory leaks in Xamarin with the profiler, & Using Xamarin Inspector with your live apps : Adam Pedley가 "WebView 랜더링 설정", "Xamarin Forms 프로파일링", "Xamarin 메모리 프로파일링", "실행중인 앱을 Xamarin Inspector로 프로파일링 하기"를 공유했습니다.
* The underestimated power of color in mobile app design : Nick Babich가 모바일 앱 디자인에서 색상, 색감의 중요성에 관해 설명합니다.
* New Xamarin.Forms item templates! : James Montemagno가 Xamarin.Forms item template에 관해 설명합니다.
* Creating a reusable styles assembly for Xamarin.Forms : John Miller가 Xamarin.Forms에서 재활용 가능한 스타일 리소스 어셈블리의 구현방법을 설명합니다.
* Supporting Xamarin.Forms tabbed page in Caliburn.Micro : Nigel Sampson이 Xamarin.Forms에서 Caliburn.Micro 라이브러리로 탭 페이지를 구성하는 방법을 설명합니다.
* Unable to connect or debug to Visual Studio Android Emulator with Visual Studio 2017 RC : Nick Randolph가 Visual Studio 2017 RC 버전에서 안드로이드 에뮬레이터가 정상적으로 디버거되지 않는 현상을 해결하는 방법을 공유했습니다.
* Visual Studio Emulator for Android : David Yardy가 Visual Studio 안드로이드 에뮬레이터를 소개합니다.
### Azure
* Event Hubs .NET Standard client is now generally available : John Taubensee가 .NET Standard 애플리케이션에서 Event Hub를 활용하는 방법을 공유했습니다.
* Creating documents in DocumentDB with Azure Functions HTTP API and Updating documents in DocumentDb : Adrian Hall이 Azure Functions HTTP API를 활용하여 DocumentDB를 생성하고 업데이트하는 방법을 설명합니다.
* Building Azure Functions: part 1 – creating and binding, part 2 – settings and references, and part 3 – coding concerns : Tim Murphy가 Azure Function을 이용한 활용 방법 "1편 : 생성과 바인딩하기", "2편 : 설정과 참조하기", "3편 : 코딩 고려사항"을 공유했습니다.
* Create a memory dump for your slow performing Web App : Benjamin Perkins이 웹 애플리케이션 성능 이슈를 분석하기 위해 메모리 덤프를 효과적으로 생성하는 방법을 소개합니다.

### UWP 소식
* Adding UWP features to your existing PC software : Stefan Wick기 기존 PC 프로그램에 UWP 기능을 추가하는 방법을 소개합니다.
* How to use Surface Dial with WPF applications : Ricardo Pons이 WPF 애플리케이션에서 Surface Dial 디바이스를 활용하는 방법을 설명합니다.
* VisualStateManager pitfalls : Martin Zikmund이 VisualStateManager 사용시 주의 사항을 공유했습니다.
* Primary Live Tile API – Windows 10 : Andrew Bares가 윈도우 10의 라이브 타일 API에 관해 소개합니다.
* Progress UI and data binding inside toast notifications – Windows 10 Creators Update : leixu2046에 토스트 알림 UI의 데이터 바인딩을 활용하여 작업 진행 상태를 나타내는 UI를 구현하는 방법을 설명합니다.

### Game 소식
* .GAME’s item system – part 1 challenge explained : Stacey Haffner가 Unity에서 마우스 클릭으로 3D 객체를 이동시키는 방법을 설명합니다.
* Inventory and store system – part 2 (scriptable objects) : Stacey Haffner가 Scriptable Objects로 아이템 시스템 기반을 구축하여 프로젝트를 진행하는 방법을 소개합니다.
* Against the burning hells: Diablo III’s road to redemption with Reaper of Souls : 디아블로 3 게임 감독, Joshua Mosqueira가 GDC 행사에서 디아블로에 제작과정에 대해 소개합니다. 
* [Unity 5] tutorial: how to create a split screen : Gamad에서 "분할 스크린(split screen)" 구현 방법을 설명합니다.
* Real Time Strategy in Unity – Unit02Games에서 단위 선택 GUI에 관해 소개합니다.

// 전무님 소개
