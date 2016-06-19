### On.NET 소식
[지난 On.NET 인터뷰] 스위스에 위치한 GPU프로그램 전문회사 QuantAlea에 근무하는 Egloff 과 함께 .NET의 C#, F#을 이용해서 GPU를 활용하는 방법에 대해서 얘기해 봤습니다. GPU를 효과적으로 활용하면 대량의 병렬 처리가 가능하며 CPU의 한계를 뛰어넘는 성능을 구축할 수 있습니다.

 //인터뷰 동영상 

이번 주의 인터뷰 손님으로는 Pratap Lakshman님 이며 MS Test에 대해 얘기해볼 예정입니다.

### 금주의 패키지- ELMAH
ELMAH (Error Logging Modules and Handlers) 은 별도의 개발자 구현 없이도 동적 추가/제거가 가능한 완벽한 플러그인 형태의 라이브러리로서 어플리케이션 수준에서 로깅 기능을 자동으로 수행할 수 있도록 도와줍니다.  ELMAH는 기존 코드의 추가적인 컴파일 작업이나 재 배포가 필요 없으며 이미 실행되고 있는 특정 ASP.NET 웹 어플리케이션이나 혹은 특정 머신내의 모든 ASP.NET 웹 어플리케이션에 기능을 적용할 수 있습니다.

ELMAH의 적용은 설정을 통해서 이루어질 수 있으며 따라서 이미 실행되고 있는 웹 어플리케이션의 소스코드는 단 한 줄도 수정할 필요가 없습니다. 처리되지 않은 모든 예외에 대한 로깅, 외부에서 볼 수 있는 로그요약 정보 페이지와 기존 ASP.NET 어플리케이션 에러 페이지에서 볼 수 있던 호출정보가 좀더 시각화되어 포함된 로그상세 페이지 제공등의 기능이 포함되어 있습니다. 더불어 에러 발생시 이를 e-mail로  매번 알려주도록 알람을 설정할 수 있으며(web.config의 customErrors 값이 off 이더라도) RSS feed기능도 지원되어 최근 마지막 발생한 15개 예외 정보의 로그를 feed 통해서 확인할 수 있습니다.

//그림

### 금주의 게임 - Endless Space
Endless Space는 4X(eXplore, eXpand, eXploit, eXterminate) 턴제 전략 시뮬레이션(TBS, Turn Based Strategy Game, 한번씩 돌아가면서 하는 전략 시뮬레이션) 장르 게임으로서 2013 Unity Golden Cube상과 Community Choice상을 수상한 게임입니다. Endless Space의 플레이어는 탐험, 확장, 활용, 전투를 하며 은하계에 자신의 영역을 넓히는 동시에 은하계 화폐의 일종인 Dust를 많이 확보 하는 것이 목적인 게임입니다. 플레이어는 은하계 8개의 문명중 하나를 선택할 수 있으며 수백개의 은하시스템과 행성을 탐사하게 됩니다. Endless Space는 무작위로 매번 새로운 개임 정보와 은하계정보가 끊임없이 생성될 수 있기  때문에  따라서 한번 사용된 게임 컨텐츠가 다시 재 사용될 일은 없습니다.

//그림

Endless Space는 [ Amplitude Studios]에서 Unity와 C#을 이용해서 개발되었으며, 현재 Mac과 Window에서 플레이 하실 수 있습니다.
좀더 자세한 정보는 [링크]에서 확인하실 수 있습니다.

## .NET 소식

* Visual Studio 2015 Update 3 RC : John Montgomery이 Visual Studio 2015 Update 3 RC 버전 소식을 공유했습니다.
* A dotnetConf 2016 recap with links to all the talks : Beth Massi이 dotnetConf 2016 행사에서 있었던 주요내용을 정리해 주었습니다.
* Announcing a new .NET and ASP.NET Core Bug Bounty : Barry Dorrans이  .NET and ASP.NET Core 의 7/7~9/7까지 진행될 버그 바운트(버그 현상금 프로그램)을 소개해주었습니다
* Cake joins the .NET Foundation, and Cake v0.13.0 released : Cake 이 .NET Foundation의 멤버가 되었으며 Cake v0.13.0 버전이 릴리즈 되었습니다.
* .NET Platform Standard and the magic of “imports” : Jonathan Mezach이 .NET Core RC2에서 .NET Platform Standard의 개념에 대해서 설명해 주었습니다. 
* Announcing MSTest Framework support for .NET Core RC2 / ASP.NET Core RC2 : Pratap Lakshman이 MSTest Framework이 .NET Core RC2 / ASP.NET Core RC2환경의 지원한다는 소식과 함께 MSTest Framework을 소개 해주었습니다.
* Implementing a Markdown Engine for .NET : Alexandre Mutel이 .NET 환경에서 사용할 수 있는 마크다운 엔진들의 성능 비교와 마크다운 엔진의 실제 구현 방법을 소개해 주었습니다.
* Designer Support for EF Core via Devart : Julie Lerman가 EF용 3rd party 툴인 Devart가 EF Core를 지원하며 비주얼스트디오 개발툴 디자이너기능을 지원한다는 소식을 공유해주었습니다.
* Publishing your first .NET Core NuGet package with AppVeyor and MyGet, and Adding Travis CI builds to a .NET Core app : Andrew Lock.이 AppVeyor와  MyGet을 이용하여 .NET Core용 NuGet 패키지를 만드는 방법과 Linux와 Mac 환경에서 Travis CI를 이용한 어플리케이션의 빌드및 테스트 방법에 대해서 설명해 주었습니다.  
* Announcing Scripty, an alternative to T4 for compile-time code generation using the power of Roslyn scripting : Dave Glick이 기존의 컴파일 타임 코드 생성 엔진인 T4대신 사용할 수 있는 오픈소스 프로젝트인 Scripty를 소개해주었습니다. Scripty는 Roslyn scripting의 기술을 활용하여 개발 되었습니다.
* A Peek into .NET Open Source Contributions : Jeffrey T. Fritz이 .NET관련 오픈소스 프로젝트의 지역별 참여자 정보를 분석하여 공유해주었습니다.
* Maybe null is not an option : Amir Barylko이 null 참조에 대한 예외 발생가능성과 예방법등을 공유했습니다.
* Structured logging concepts in .NET part 1 and part 2 : Nicholas Blumhardt이 구조적인 로깅 방법의 개념에 대해서 part 1와 part 2 나누어 설명해 주었습니다. 
* Tracking down a performance hit : Jon Skeet이 Linux와 Windows 환경에서 자신이 참여중인 오픈소스 프로젝트 라이브러리 [Noda Time] (http://nodatime.org/) 의 성능을 비교하며 문제점을 찾고 이를 해결한 자신의 경험을 공유하였습니다.

### ASP.NET 소식
* Deploying Docker containers running ASP.NET Core RC2 to Microsoft Azure Cloud : Laurent Kempé이 ASP.NET Core RC2 에서 Microsoft Azure Cloud로 Docker containers 를 배포하는 방법을 소개하였습니다. 
* ASP.NET Core: No more worries about checking in secrets : Jerrie Pelser이 DB 연결문자열 암호나 OAuth key와 같은 민감한 정보가 소스컨트롤에서 관리되지 않도록 하는 몇가지 방법을 소개했습니다.
* Setup ASP.NET Core 1.0 debugging on Ubuntu 16.04 : Marcin Zabłocki  ASP.NET Core 1.0 어플리케이션을  Ubuntu 16.04 환경에서 디버깅할 수 있는 방법을 설명하였습니다.  
* Running ASP.NET Core 1.0-RC2 in Docker : Sergio Sisternes 이 Running ASP.NET Core 1.0-RC2 웹 어플리케이션을 Docker 환경에서 실행 하도록 하는 step-by-step 가이드를 공유해주었습니다.

### F# 소식
* Mastering .NET Machine Learning (book) : Jamie Dixon의 "Mastering .NET Machine Learnin" eBook 이 출간되었습니다.
* F# for Machine Learning Essentials (book) :  Sudipta Mukherjee의 "F# for Machine Learning Essentials" eBook 이 출간되었습니다.
* F# in the real world, : Yan Cui 이 게임 개발업무에서 F#을 사용한 자신의 경험을 바탕으로 F#의 장점, 특징등을 공유해주었습니다.
* F# the most highly paid tech worldwide in 2016, but it’s not just for finance. – FSharp TV가 F# 개발자가 세계에서 제일 높은 임금을 받는것으로 조사됬다는 [2016 Stack Overflow Developer Survey](https://fsharp.tv/gazettes/f-the-most-highly-paid-tech-worldwide-in-2016/) 소식과 함께 F#의 현재와 미래의 비전을 공유해주었습니다.
* F# Gotchas for C# Developers, : Daniel Lazarenko이 C# 개발자를 위한 F#언어를 소개해주었습니다.
* Suave CoreCLR Sample, a sample Suave.io hello world using .NET Core : .NET Core를 이용한 Suave hello world 샘플이 소개되었습니다.

### Xamarin 소식
* .NET Conf Day 2 Keynote (video) : Miguel de Icaza의 dotnetConf 2016 키노츠 동영상이 공개 되었습니다.
* Xamarin for Visual Studio 4.1 Preview : Xamarin for Visual Studio 4.1 Preview  내용이 업데이트 되었습니다.
* Integrating MixPanel Analytics into your Xamarin.iOS app : Mark Gibaud이 사용자 분석 라이브러리인 MixPanel 를 Xamarin.iOS 어플에 적용하는 방법을 공유했습니다.
* A detailed look at what’s new in Xamarin.iOS for Visual Studio : Adam Pedley가  Visual Studio용 Xamarin.iOS의 업데이트 내용을 정리해주었습니다.
* Fun with Expressions : Robert Mikhayelyan이 Expressions 엔진의 이해와 레이아웃에서 이를 적용한 애니메이션의 사용을 설명해 주었습니다.
* Global resources in Xamarin.Forms : Jesse Liberty이 Xamarin.Forms 의 Global resources에 대해 설명해주었습니다.

### Games 
* How to Make a Game Like Bomberman : Eric Van de Kerckhove이 붐버맨 타입의 개임 제작 방법을 공유하였습니다.
* Tutorial: Save And Load system – How to save unity stuff in one file part #1 (Video) : Gamad이 게임의 실행도중 게임의 정보를 파일로 저장/읽는 방법을 소개해주었습니다.
* Introducing C# Developers to Building Games with Unity – For the Hobby Developer (Video) : Stacey Haffner이 C# 개발자를 위한 Unity 의 개임 개발 방법을 소개해 주었습니다.

//이사님 소개
