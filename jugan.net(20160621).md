### On.NET 소식
[지난 On.NET 인터뷰]에서는 [Pratap Lakshman](https://www.youtube.com/watch?v=TmLOLCAp1N8)와 함께 MS Test 에 대해 얘기해 보았습니다.

이번주는 Jeremy Kuhne와 윈도우시스템의 디렉토리 경로, 그중에서도 아주 긴 경로를 .NET에서 어떻게 지원하고 있는지 "long path support"를 주제로 얘기해 보도록 하겠습니다.

### 금주의 패키지- Stuntman
유저에따라서 서로다른 권한, 기능등 정의된 시나리오로 테스트및 디버깅 하는것은 정말 쉽지 않은 작업입니다. 테스트 환경에서 대상 사용자를 쉽고 빠르게 바꿀수 있어야 효과적으로 테스트하는 것이 가능 합니다. Stuntman은 개발 환경에서 사용자를 가장(impersonate)해줌으로서 .NET의 사용자 계정 전환 작업에 도움을 주는 라이브러리입니다. 

//그림

### 금주의 컨트롤 - Telerik DataForm for Xamarin
Telerik DataForm for Xamarin 컨트롤은 모바일 화면을 풍부해줄 컨트롤들로 구성되어 있습니다. 유효성검증 기능이 포함되어 있고 확대/축소가 가능한 그룹구성 컨트롤 그리고 커스텀 에디터 컨트롤등이 포함 되어있습니다.

//그림

### 금주의 서적 - Machine Learning Projects for .NET Developers by Mathias Brandewinder

//그림

Machine Learning Projects for .NET Developers에서 개발자는 간단한 몇가지 알고리즘들과 기술들을 적용하고 데이터를 학습하여 실세계의 다양한문제를 해결할 수 있는 스마트한 어플리케이션을 구현할수있는 방법을 배울 수 있습니다. 개발 언어는 F#을 이용하여 머신런닝 코드를 구현하게되며 개발 툴로는 이미 익숙한 비주얼 스트디오를 활용하게 됩니다.  만약 독자가 F# 언어 초보자라면 이 서적은 F#을 처음 시작하는데 도움을 줄수있는 완벽한 구성을 가지고있습니다. 혹은 독자가 이미 F#에 익숙하다면 이 서적을 통해서 F#을 이용한 새로운 개발 영역에 도전해 볼수있는 기회를 접하게 될것이다.

### 금주의 게임 - Smashy Brick

Smashy Brick은 신새대 버전의 블록 격파게임으로 99개의 아름답고 조화로은 레벨로 이루어져 있습니다. 게임조작은  기존 오락실 게임처럼 벽돌을 깨기 위해서 좌우 이동을 다이얼 패들을 이용하는것이 아니고 게이머가 정확한 길이와 각도를 염두하고 선을 직접 그려야 합니다. Smashy Brick은 최대 12 개의 고유한 능력을 가진 케릭터를 이용할 수 있습니다. 하지만 귀여운 케릭터와 아름다운 배경에 현혹되지 마십시요. 단계가 올라갈수록 각 레벨의 수준도 점점 어려워 집니다.

//그림

Smashy Brick 게임은 Bulldozer Games에서 [Unity](http://unity3d.com/) 와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners) 을 이용하여 개발되었으며, 현재  iOS와 Android에서 무료로 플레이할 수 있습니다.  좀 더 자세한 정보는 Smashy Brick 페이지에서 확인하실 수 있습니다.

## .NET 소식
* NUnit 3 Tests for .NET Core RC2 and ASP.NET Core RC2 : Rob Prouse이 .NET Core RC2와 ASP.NET Core RC2버전을 지원하는 NUnit 3의 두번째 알파버전에 대해 소개했습니다.  
* Taking the MSTest Framework forward with “MSTest V2” : Pratap Lakshman이 MSTest와  .NET Core RC2 / ASP.NET Core RC2 환경을 지원하는 MSTest  V2 버전에 대해서 소개했습니다.
* Visualising the .NET Garbage Collector : Matt Warren이 .NET Garbage Collector의 이벤트와 데이터를 시각화 하는 방법에 대해서 소개했습니다.
* What’s new in .NET Core RC2 (podcast) by the Eat Sleep Code Podcast : .NET Core RC2 의 변화된 기능에 대한 포드 케스트가 공유되었습니다.
* Rise of the IAsyncStateMachines : Szymon Kulec이 C#의 비동기 키워드인 async/await 을 사용할 경우 컴파일러가 자동 생성해주는 여러 코드들에 포함된 IAsyncStateMachines 인터페이스에 대해서 설명해 주었습니다. 
* IDisposable trumps APM : Bar Arnon이 Asynchronous Programming Model (APM)에서 Idisposable의 중요성에 대해서 설명하였습니다.
* How should a class expose a collection? : jbe2277가 클래스 설계시 컬렉션 속성 구성 방법에 대해서 설명하였습니다. 
* TreeLib: Balanced Binary Trees – Rank Augmented, for .NET : Programmaton에 TreeLib 오픈프로젝트가 소개 되었습니다.
* IDisposable and Marshal.ReleaseCOMObject and dynamic in C# : Andrei Ignat가 COM 오브젝트 활용시 주의 해야 할 점을  공유해 주었습니다.
* ASP.NET Core and .NET Core Overview : Rick Strahl이 ASP.NET Core와 .NET Core의 Overview를 공유하였습니다.

### ASP.NET 소식
* Creating a custom ConfigurationProvider in ASP.NET Core to parse YAML : Andrew Lock이  ASP.NET Core 에서 YAML  문법 분석을 이용한 사용자 ConfigurationProvider의 구현 방법을 소개하였습니다.
* Free HTTPS certificates for Docker containers running ASP.NET Core RC2 on Microsoft Azure : Laurent Kempé가 Microsoft Azure 클라우드의 ASP.NET Core RC2 에서 도커 컨테이너용 무료 HTTPS 인증서를 활용하는 방법을 소개하였습니다.
* Asp.Net Core RC1, OpenIdConnect, JWT and Angular 2 SPA – Part 1 and part 2 by Andrej Medic이 Asp.Net Core RC1, OpenIdConnect, JWT 그리고Angular 2 SPA에 대해서  Part 1과 part 2로 나누어 설명하였습니다. 
* Authenticating a user with LinkedIn in ASP.NET Core : Jerrie Pelser이 ASP.NET Core에서 LinkedIn 의 인증을 공유하는 방법을 소개하였습니다.
* Hybrid model binding in ASP.NET Core 1.0 RC2 : Bill Boga이  ASP.NET Core 1.0 RC2의 MVP 프로젝트에서 하이브리드 모델 바인딩을 구현하는 방법을 공유하였습니다.
* How to create Rest API(Web API) with ASP.NET Core 1.0 : Jalpesh Vadgama이  ASP.NET Core 1.0에서 Rest API(Web API)를 구현하는 방법을 공유하였습니다.

### F# 소식
* F# for the Practical Developer (video) : Phillip Carter가 F#을 처음 접하는 일반 업무 개발자를 위해 F# 언어를 소개해 주었습니다.
* Types from data: Making structured data first-class citizens in F#, : Tomas Petricek이  F#의 구조적 데이터 구현에 관련된 "Types from data" 슬라이드를 공유해주었습니다.
* An F# web API in Azure Container, : M Sheik Uduman Ali 가 Azure 컨테이너 환경에서 F#을 이용한 web API의 구성방법을 공유해주었습니다
* Updated: Getting started with Fable and Webpack, : Krzysztof Cieśla이 초보자를 위한 Fable과 Webpack의 가이드를 제공해 주었습니다.
* Paket 3 Released! : Paket 3가 릴리즈 되었습니다

### Xamarin 소식
* Xamarin.Forms UI Designer is in Beta 1 : Michael Davis이 Xamarin.Forms용 UI 디자이너인 XenForms의 베타 1버전을 소개해주었습니다. 
* Workbooks & Inspector 0.9.0 Released : Aaron Bockover가 Workbooks 과 Inspector의 0.9.0 버전 릴리즈 소식을 공유해주었습니다.
* NuGet Support in Xamarin Studio 6.0 : Matt Ward가 Xamarin Studio 6.0 에서 NuGet 을 활용하는 방법을 소개해 주었습니다.
* ASP.NET Core 1.0 RC2 support in Xamarin Studio : Matt Ward가 Xamarin Studio가 ASP.NET Core 1.0 RC2을 지원한다는 소식을 공유해 주었습니다.
* Password-protected Encryption Provider for Akavache : Kent Boogaart가 Akavache라이브러리에서 사용할 수 있는 password 암호 프로바이더의 구현 방법을 소개해 주었습니다.
* Preview iOS simulator for Windows : Adrian Murphy가 윈도우용 iOS simulator Preview 버전을 소개하였습니다.
* Xamarin.Forms UI designer beta released : Michael Davis가 Xamarin.Forms용 UI 디자이너인 XenForms의 베타 버전 릴리즈 소식을 공유해 주었습니다
ㅍFlip through items with Xamarin.Forms CarouselView : James Montemagno가 Xamarin.Forms의 CarouselView 기능을 설명 하였습니다.
* Xamarin.Forms Behaviors: FadeAction : David Britch가 Xamarin.Forms의 Behaviors: FadeAction 을 설명해주었습니다.

### Games 
* Shaders Case Study – Hearthstone Golden Cards (Video) : Makin’ Stuff Look Good이 Hearthstone 게임의 Golden Cards 효과를   낼 수 있는 Shaders  프로그램 기법을 설명하였습니다. 
* F# Kit by Noobtuts : Unity에서 F#을 사용할 수 있게 해주는 F# Kit가 공개 되었습니다.
* DotNetCore Tutorial for Unity3d for Absolute Noobs : Nicholas Ventimiglia가 Unity3d 초보자를 위한 DotNetCore Tutorial를 공유하였습니다.
* Creating a 2D Platformer (Video) : Sebastian Lague가 슈퍼마리오와 같은 장르의 게임인 2D Platformer(PLATFORM GAME) 게임 구현 방법을 공유하였습니다.


//이사님 소개
