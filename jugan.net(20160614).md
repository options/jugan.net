여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

###금주의 커뮤니티 소식
Taeyo.NET 에서 http://docs.asp.net 의 ASP.NET Core 문서를 한글화하여 연재하고 있습니다.

* [ASP.NET Core : Grunt 사용하기](http://taeyo.net/Columns/View.aspx?SEQ=534&PSEQ=39) 
* [ASP.NET Core MVC : SQL Server LocalDB로 작업하기](http://taeyo.net/Columns/View.aspx?SEQ=535&PSEQ=40) 

### On.NET 소식
[지난 On.NET 인터뷰](https://youtu.be/QJ93BMCo_XI)에서는 스위스의 GPU 프로그램 전문회사인 [QuantAlea](http://quantalea.com/)에 근무하고 계시는 Egloff 와 함께 C# 과 F# 을 이용해서 GPU 를 활용하는 방법에 대해서 이야기 나누었습니다. GPU 를 활용하여 대규묘의 병렬 처리를 할 수 있응며 CPU 의 한계를 뛰어넘는 성능을 낼 수 있습니다.

 //인터뷰 동영상 

이번 주 On.NET 인터뷰에는 [Pratap Lakshman](https://www.youtube.com/watch?v=TmLOLCAp1N8) 를 모시고 MS Test 에 대해 이야기 나누어 볼 예정입니다.

### 금주의 패키지- ELMAH
[ELMAH](https://elmah.github.io/)(Error Logging Modules and Handlers) 은 별도의 개발 없이도 동적으로 추가 및 제거가 가능한 플러그인 형태의 라이브러리로 애플리케이션에서 로깅 기능을 자동으로 수행할 수 있도록 도와줍니다. ELMAH 는 기존 코드에 추가적인 컴파일 및 배포 작업이 필요 없으며 이미 실행되고 있는 특정 ASP.NET 웹 어플리케이션이나 혹은 특정 머신내의 모든 ASP.NET 웹 애플리케이션에 기능을 적용할 수 있습니다.

설정만으로도 ELMAH 를 적용할 수 있기 때문에 실행중인 웹 애플리케이션의 소스코드를 수정할 필요가 없습니다. 처리되지 않은 모든 예외에 대한 로깅, 외부에서 볼 수 있는 로그요약 정보 페이지와 기존 ASP.NET 어플리케이션 에러 페이지에서 볼 수 있던 호출정보가 좀 더 시각화되어 포함된 로그상세 페이지 제공등의 기능이 포함되어 있습니다. 더불어 에러 발생시 이를 e-mail로  매번 알려주도록 알람을 설정할 수 있으며(web.config의 customErrors 값이 off 이더라도) RSS feed 기능도 지원되어 최근 마지막 발생한 15개 예외 정보의 로그를 feed 통해서 확인할 수 있습니다.

//그림

### 금주의 Xamarin 애플리케이션 - Expensya 

매번 해외 사례만 소개해드려 아쉬웠는데요, 처음으로 국내 사례를 소개해 드립니다! 인디개발팀인 엔스티지 팀에서 2015년 경 부터 Xamarin.Android로 만든 영어단어 학습앱 리모릭스를 시작으로, WPF로 된 Windows PC버전과 최근 iOS 버전도 개발하여 출시하였습니다.
서버는 WCF로 개발되어 Azure에서 호스팅 되고 있다고 합니다. 
* 명신 부장님께 Envicase 사례도 소개하는거 어떤지? 

//이미지 

### 금주의 게임 - Endless Space
[Endless Space](http://madewith.unity.com/games/endless-space)는 4X(eXplore, eXpand, eXploit, eXterminate) 전략 시뮬레이션 게임으로 2013년도에는 Unity Golden Cube 상과 Community Choice 상을 수상하기도 한 게임입니다. 게임에서 플레이어는 탐험하거나 확장하거나 다른사람의 자원을 착취하거나 적을 제거하며 그들의 문명을 통제하고 우주 먼지 공간을 식민지화합니다. 플레이어는 8 개의 문명 중 하나를 선택하고 수 백개의 은하계와 행성을 탐사하게 됩니다. 매번 무작위로 새로운 개임 정보와 은하계가 생성되기 때문에 지루할 틈이 없는 게임입니다. 

//그림

이 게임은 [Amplitude Studios](http://madewith.unity.com/profiles/amplitude-studios)에서 [Unity](http://unity3d.com/) 와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners) 을 이용하여 개발되었으며, 현재 Mac 과 Window 에서 플레이 하실 수 있습니다. 좀더 자세한 정보는 [링크](http://madewith.unity.com/games/endless-space)에서 확인하실 수 있습니다.

## .NET 소식

* [Visual Studio 2015 Update 3 RC](https://blogs.msdn.microsoft.com/visualstudio/2016/06/07/visual-studio-2015-update-3-rc/) : John Montgomery 가 안정성, 기능, 버그가 개선된 Visual Studio 2015 Update 3 RC 버전 소식을 공유했습니다.
* [A dotnetConf 2016 recap with links to all the talks](https://blogs.msdn.microsoft.com/dotnet/2016/06/09/thank-you-for-watching-dotnetconf-2016/) : Beth Massi 가 dotnetConf 2016 행사에서 있었던 주요 내용 및 각종 링크를 정리한 글을 공유해 주었습니다.
* [Announcing a new .NET and ASP.NET Core Bug Bounty](https://blogs.msdn.microsoft.com/webdev/2016/06/07/announcing-a-new-net-and-asp-net-core-bug-bounty/) : Barry Dorrans 가 7/7 부터 9/7 까지 3개월간 진행되는 .NET 및 ASP.NET Core 의 버그 바운트(버그 현상금 프로그램)을 소개해주었습니다.
* [Cake joins the .NET Foundation](http://cakebuild.net/blog/2016/06/cake-joins-dotnetfoundation), and [Cake v0.13.0 released](http://cakebuild.net/blog/2016/06/cake-v0-13-0-released) : 크로스 플랫폼용 빌드 자동화 시스템인 Cake(C# Make) 가 .NET Foundation 의 멤버가 되었으며, Cake v0.13.0 버전이 릴리즈 되었습니다.
* [.NET Platform Standard and the magic of “imports”](https://blogs.infosupport.com/net-platform-standard-and-the-magic-of-imports/) : Jonathan Mezach 가 .NET Core RC2 에서 등장하며 많은 사람들이 어려워하는 개념인 .NET Platform Standard 에 대해 설명해 주었습니다. 
* [Announcing MSTest Framework support for .NET Core RC2 / ASP.NET Core RC2](https://blogs.msdn.microsoft.com/visualstudioalm/2016/05/30/announcing-mstest-framework-support-for-net-core-rc2-asp-net-core-rc2/) : Pratap Lakshman 이 MSTest Framework 가 .NET Core RC2 / ASP.NET Core RC2 를 지원한다는 소식과 함께 사용방법을 소개해주었습니다.
* [Implementing a Markdown Engine for .NET](http://xoofx.com/blog/2016/06/13/implementing-a-markdown-processor-for-dotnet/) : Alexandre Mutel 이 .NET 에서 사용가능한 마크다운 엔진간의 성능을 비교하는 과정을 상세하게 소개해 주었습니다.
* [Designer Support for EF Core via Devart](http://thedatafarm.com/data-access/designer-support-for-ef-core-via-devart/) : Julie Lerman 가 Devart 에서 EF Core 를 위한 비주얼 스트디오 디자이너 기능을 지원한다는 소식을 공유해주었습니다.
* [Publishing your first .NET Core NuGet package with AppVeyor and MyGet](https://andrewlock.net/publishing-your-first-nuget-package-with-appveyor-and-myget/), and [Adding Travis CI builds to a .NET Core app](https://andrewlock.net/adding-travis-ci-to-a-net-core-app/) : Andrew Lock 이 AppVeyor 와 MyGet 을 이용한 .NET Core 용 NuGet 패키지를 만드는 방법과 Linux 및 Mac 에서 Travis CI 를 이용한 애플리케이션의 빌드 및 테스트 방법을 소개해 주었습니다.  
* [Announcing Scripty, an alternative to T4 for compile-time code generation using the power of Roslyn scripting](http://daveaglick.com/posts/announcing-scripty) : Dave Glick 이 컴파일 타임 코드 생성 엔진인 T4 대신에 사용할 수 있는 Scripty 를 소개해주었습니다. Scripty 는 오픈소스 프로젝트로 진행되고 있으며 Roslyn scripting 의 기술을 활용하여 개발 되었습니다.
* [A Peek into .NET Open Source Contributions](https://blogs.msdn.microsoft.com/webdev/2016/06/10/a-peek-into-net-open-source-contributions/) : Jeffrey T. Fritz 이 .NET 오픈소스 프로젝트의 지역별 참여자 정보를 공유해주었습니다.
* [Maybe null is not an option](http://www.westerndevs.com/Fsharp/Functional-programming/maybe-null-is-not-an-option/) : Amir Barylko 이 null 참조에 대한 예외 발생 가능성과 예방법을 공유했습니다.
* [Structured logging concepts in .NET part 1](http://nblumhardt.com/2016/06/structured-logging-concepts-in-net-series-1/) and [part 2](https://nblumhardt.com/2016/06/events-and-levels-structured-logging-concepts-in-net-2/) : Nicholas Blumhardt이 구조적으로 로그를 남기는 방법에 대해서 part 1 과 part 2 로 나누어 설명해 주었습니다. 
* [Tracking down a performance hit](https://codeblog.jonskeet.uk/2016/06/09/tracking-down-a-performance-hit/) : Jon Skeet 이 자신이 참여중인 오픈소스 프로젝트 라이브러리 [Noda Time](http://nodatime.org/) 의 문제점을 찾고 해결하여 성능을 개선했던 자신의 경험을 공유하였습니다.

### ASP.NET 소식
* [Deploying Docker containers running ASP.NET Core RC2 to Microsoft Azure Cloud](http://laurentkempe.com/2016/06/08/Deploying-Docker-containers-running-ASPNET-Core-RC2-to-Microsoft-Azure-Cloud/index.html) : Laurent Kempé 가 ASP.NET Core RC2 에서 Microsoft Azure Cloud 로 Docker 컨테이너를 배포하는 방법을 소개하였습니다. 
* [ASP.NET Core: No more worries about checking in secrets](http://www.jerriepelser.com/blog/aspnet-core-no-more-worries-about-checking-in-secrets) : Jerrie Pelser 가 DB 연결용 문자열이나 OAuth key 와 같은 민감한 정보를 관리하는 몇 가지 방법을 소개했습니다.
* [Setup ASP.NET Core 1.0 debugging on Ubuntu 16.04](http://zablo.net/blog/post/run-and-debug-asp-net-core-rc2-ubuntu-16-04) : Marcin Zabłocki 가 ASP.NET Core 1.0 애플리케이션을 Ubuntu 16.04 에서 디버깅하는 방법을 설명했습니다.  
* [Running ASP.NET Core 1.0-RC2 in Docker](https://www.sesispla.net/blog/language/en/2016/05/running-asp-net-core-1-0-rc2-in-docker/) : Sergio Sisternes 이 ASP.NET Core 1.0 RC2 웹 애플리케이션을 Docker 에서 실행하는 방법을 공유해주었습니다.

### F# 소식
* [Mastering .NET Machine Learning (book)](https://www.packtpub.com/big-data-and-business-intelligence/mastering-net-machine-learning) : Jamie Dixon 의 Mastering .NET Machine Learning(eBook) 이 출간되었습니다.
* [F# for Machine Learning Essentials (book)](https://www.packtpub.com/big-data-and-business-intelligence/f-machine-learning) :  Sudipta Mukherjee 의 F# for Machine Learning Essentials(eBook) 이 출간되었습니다.
* [F# in the real world](http://www.slideshare.net/theburningmonk/f-in-the-real-world-ndc/8-why_F) : Yan Cui 가 게임 개발업무에서 F# 을 사용하며 느낀 F# 의 장점, 특징을 소개해주었습니다.
* [F# the most highly paid tech worldwide in 2016, but it’s not just for finance](https://fsharp.tv/gazettes/f-the-most-highly-paid-tech-worldwide-in-2016/) : FSharp TV 에서 F# 개발자가 세계에서 제일 높은 임금을 받는것으로 조사됬다는 소식과 함께 F# 의 현재와 비전을 공유해주었습니다.
* [F# Gotchas for C# Developers](http://dobegin.com/fsharp-gotchas-for-csharp-devs/) : Daniel Lazarenko이 C# 개발자들 대상으로 F# 을 소개해주었습니다.
* [Suave CoreCLR Sample, a sample Suave.io hello world using .NET Core](https://github.com/SuaveIO/Suave-CoreCLR-sample) : .NET Core 를 이용한 Suave hello world 샘플이 소개되었습니다.

### Xamarin 소식
* [.NET Conf Day 2 Keynote (video)](https://channel9.msdn.com/Events/dotnetConf/2016/NET-Conf-Day-2-Keynote-Miguel-de-Icaza) : Miguel de Icaza 의 dotnetConf 2016 Day 2 키노트 동영상이 공개되었습니다.
* [Xamarin for Visual Studio 4.1 Preview](https://developer.xamarin.com/releases/vs/xamarin.vs_99/xamarin.vs_99.0/) : Xamarin for Visual Studio 4.1 Preview 버전에서 소개될 내용이 업데이트 되었습니다.
* [A detailed look at what’s new in Xamarin.iOS for Visual Studio](https://xamarinhelp.com/new-xamarin-ios-visual-studio/) : Adam Pedley 가 Visual Studio 의 Xamarin.iOS 업데이트 내용을 정리해주었습니다.
* [Fun with Expressions](http://blog.robmikh.com/xaml/uwp/composition/2016/04/28/fun-with-expressions.html) : Robert Mikhayelyan 이 Expressions 엔진을 예제와 함께 소개해주었습니다.
* [Global resources in Xamarin.Forms](http://jesseliberty.com/2016/05/19/global-resources-in-xamarin-forms/) : Jesse Liberty 가 Xamarin.Forms 에서 Global resources 를 선언하는 방법을 설명해주었습니다.

### Games 
* [How to Make a Game Like Bomberman](https://www.raywenderlich.com/125559/make-game-like-bomberman) : Eric Van de Kerckhove 가 미로에 폭탄을 설치하고 피하는 Bomberman 타입의 게임을 제작하는 방법을 공유하였습니다.
* [Tutorial: Save And Load system – How to save unity stuff in one file part #1 (Video)](https://www.youtube.com/watch?v=30gE2M8SCi0&feature=youtu.be) : Gamad 가 Unity 파일 정보를 저장하고 실행하는 방법을 소개해주었습니다.
* [Introducing C# Developers to Building Games with Unity – For the Hobby Developer (Video)](https://channel9.msdn.com/events/dotnetConf/2016/Introducing-C-Developers-to-Building-Games-with-Unity-For-the-Hobby-Developer) : Stacey Haffner 이 C# 개발자를 위해 Unity 를 이용하여 게임을 개발하는 방법을 소개합니다.

//이사님 소개
