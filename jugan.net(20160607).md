### On.NET 소식
[지난 On.NET 인터뷰]에서는 마이크로스프트의 주요 언어의 프로그램 메니저이면서 동시성 부분의 전문가(concurrency expert) 인 [Lucian Wischik](https://twitter.com/lwischik)과 함께 이야기 나누어 보았습니다

//인터뷰 동영상 

[이번 주 On.NET 인터뷰]에는 Daniel Egloff 과 함께 .NET에서 GPU 기능 활용방법에 대해서 알아보겠습니다.

### 금주의 패키지- Markdig
.NET용 마크다운(markdown) 라이브러리는 사실 많지 않습니다. 하지만 Markdig는 기능 확장이 가능하고 CommonMark 표준 따르는 고성능(빠른속도 + 메모리 최적)의 가진 마크다운 라이브러리입니다. 

//코드
var result = Markdown.ToHtml("This is a text with some *emphasis*");

### 금주의 Xamarin 애플리케이션 - Expensya 
Expensya는 유럽, 아프리카, 호주에서 주로 사용하는 유명한 경비처리 보고서 어플입니다 . Expensya는 C#으로 구현되었으며 Azure 클라우드환경을 사용하도록 설계되었습니다. 이 회사의 개발자팀은 Xamarin의 많은 장점, 즉 높은 코드공유기능, 팀원의 기존 기술 재사용(이미 알고있는 C#), 다중 플랫폼지원(윈도우, android, iOS), 쉬운 업무로직 단위테스트구현(클라이언트<->서버), 그리고 네이티브 수준의 성능등을 고려하여 모바일 어플 개발 툴을 Xamarin으로 결정하였습니다. 그결과 3가지 메인 플렛폼(윈도우, android, iOS)에서 동작하는 완벽한 모바일 어플을 불과 몇개월만에 성공적으로 완성 할 수 있었습니다. 

고마워 Xamarin!!
(Thanks to Xamarin!!)

//이미지  
### 금주의 게임 - McDroid
게임 McDroid는 타워디펜스게임(tower defense game)의 일종으로 게임안에서 플레이어는 McDroid 역할을 수행하게 됩니다, 
McDroid는 귀여운 안드로이드(로봇)로 행성 충돌로 불시착한한 우주선의 수리와 수리가 끝날때까지 외계인의 공격을 방어하는 책임을 지고 있습니다.
플레이어는 기본 방어 라인을 구축하여 수리에 필요한 자원의 안정적인 수확과 주기적인 외계인의 공격을 막아내야 합니다. 게임에서 단계별 미션을 완수하고 다음 단계로 가기 위해 무엇보다 중요한 것은 효율적 시간관리 입니다. 게임 McDroid는 켐페인 스토리, 생존 그리고 다중 플레이어 게임모드를 제공합니다.

//그림

McDroid는  Grip Digital에서 Unity와 C#을 이용해서 구현되었으며 현재 PlayStation 4, Xbox One 그리고 Windows (via Steam)를 통해서 즐기실 수 있습니다.
좀더 자세한 정보는 [링크]를 통해서 확인할 수 있습니다.

### .NET 소식
* Inline IL ASM in C# with Roslyn : Alexandre Mutel이 Roslyn을 이용한 C# Inline IL ASM 에 대해 설명 하였습니다.
* Strings and the CLR – a Special Relationship : Matt Warren이 C#의 기본 타입인 문자열이 CLR에서 어떻게 다루어지고 있는지 설명 하였습니다.
* Use project.lock.json to troubleshoot dotnet restore problems : Andrew Lock이 project.json 프로젝트에서 dotnet restore명령을 이용하여 NuGet 패키지를 다시 로드할때 발생하는 문제를 해결한 경험을 공유하였습니다.
* Windows 10 Anniversary Update Preview–Composition and the CompositionBackdropBrush : 영국의 유명한 .NET 기술 개발자인 Mike Taulty가 Windows 10 Anniversary Update 에 포함예정인 Composition API(UI Layer관련 새로운 API)에 대한 정보를 공유해주었습니다.
* ASP.NET Core – problems and fixes : Michal Dymel이 기존 ASP.NET 프로젝트를 ASP.NET Core RC2로 전환하면서 경험한 문제와 이에 대한 해결방법을 공유하였습니다.
* MSBuild Structured Log: record and visualize your builds : Scott Hanselman이 MSBuild Structured Log 툴을 이용하여 MSBuild 작업 진행과정을 쉽게 확인 할 수 있는 방법을 소개하였습니다.
* Storing C# app settings with JSON : Piotr Gankiewicz이 기존 XML 포멧의 config 파일 대신 JSON 포멧의 config 파일을 사용할 수 있는 방법을 소개하였습니다.
* Async Programming : Unit Testing Asynchronous Code : Stephen Cleary이 보통의 단위 테스트 방법으로 테스트하기 까다로운 (Async and Await) 비동기 코드의 단위 테스트 방법을 소개하였습니다.
* Imageflow: Respect the pixels, accelerate the web (Kickstarter) : Nathanael Jones이 고성능 이미지 프로세싱 Kickstarter 프로젝트인 Imageflow를 소개하였습니다.
* The .NET CLI Decoded : Sam Basu가  윈도우, 애플 OSX 그리고 리눅스 환경에서 공통적으로 사용 가능한 NET CLI 커맨드라인 명령에 대해서 공유해주었습니다.

### ASP.NET 소식
* Publishing and Running ASP.NET Core Applications with IIS : Rick Strahl이 IIS를 이용한 ASP.NET Core용 어플리케이션 개발과 배포 방법을 설명하였습니다.
* Introduction to integration testing with xUnit and TestServer in ASP.NET Core : Andrew Lock이 TestServer와 xUnit을 이용한 통합 테스트 방법을 공유하였습니다.
* Authorizing your .NET Core MVC6 API requests with OpenIddict and Identity : Kerry Ritter이 .NET Core MVC6에서 OpenIddict(OAuth, OpenID관련 기능의 오픈소스 라이브러리)와 이와 관련하여 Identity를 사용하는 방법을 설명하였습니다.
* Cloudscribe.Web.Localization – more flexible localization for ASP.NET Core : Joe Audette이 ASP.NET Core의 지역화(Localization)기능을 제공하는 오픈소스 프로젝트인 Cloudscribe.Web.Localization 를 소개하였습니다. 
* ASP.NET Core RC2 (migration guide) : David Pine이  ASP.NET Core RC1 어플리케이션을 ASP.NET Core RC2로 전환하는 가이드를 공개하였습니다.

### F# 소식
* Using XAML in F# Xamarin Forms – A Screencast, : Jonathan Wood이 F# Xamarin Forms에서 XAML을 사용하는 방법을 공유해주었습니다.
* Custom error handling and logging in Suave, : Dustin Moris Gorski이 사용자정의 예외 처리및 이를 로깅하는 방법을 공유해주었습니다.
* Upcoming F# events – learn Suave, FsLab & more!, : Tomas Petricek이 앞으로 진행될 자신의 F#관련 세미나 정보를 공유하였습니다
* Fable: Super Fable Mario (Mario clone using HTML5 canvas) : HTML5 canvas를 이용한 마리오 게임 캐릭터의 기본 움직임을 구현한 소스의 구현을 공유해주었습니다.

### Xamarin 소식
* Join the Xamarin Team for dotNetConf : Joseph Hill이 최근 있었던 가상 온라인 세미나인 dotNetConf에 Xamarin Team멤버들의 참여 소식을 전해주었습니다.
* Xamarin DevOps with VSTS – Setup a Cross Platform Build Agent on OSX, and [Xamarin DevOps with VSTS – Setup a Cross Platform Build Agent on Windows] (http://www.blogaboutxamarin.com/xamarin-devops-with-vsts-setup-a-cross-platform-build-agent-on-windows/) : Richard Woollcott이 Xamarin 개발을 위해서 애플 OSX에  Cross Platform Build Agent를 구성하는 방법을 공유해주었습니다. 
* ASP.NET Core 1.0 RC2 support in Xamarin Studio : Matt Ward이 Xamarin Studio을 이용하여 ASP.NET Core 1.0 RC2 어플리케이션을 개발및 디버그 하는 방법을 공유해주었습니다.
* Watch Kent Boogaart code WorkoutWotch from start to end : Kent Boogaart이 개발한 iOS용 어플인 WorkoutWotch의 개발 과정이 유튜브에 공유되었습니다.
* Xamarin DevOps with VSTS – Getting Started : Richard Woollcott이 Xamarin DevOps 초보자들을 위한 가이드를 제공해 주었습니다.
* Xamarin Forms UI Snippets : Xamarin관련 UI 공유 사이트가 소개 되었습니다


### Games 
* Serialization, Monobehavior Constructors and Unity 5.4 : Lukasz Paczkowski이 constructors/field 초기화 과정에서 Unity API 호출시 발생할 수 있는 부작용과 이를 방지하기 위해 Unity5.4에서 추가된 예외에 대해서 설명해주었습니다.
* Breakout! How to Stop An Infinite Loop in a Unity C# Script : Peter Andreasen이 Unity 어플리케이션 디버깅시 개발자 C# Script에 의해서 실행된 무한루프를 강제로 정지시키는 방법을 공유해주었습니다.
* Build a Unity Game Part 4 – Video, : Stacey Haffner이 Unity Game개발 동영상 가이드 Part 4를 소개해 주었습니다

* Unity Linear Interpolation, : Indiedevart이 Unity의 Linear Interpolation기능에 대해서 소개해 주었습니다.
