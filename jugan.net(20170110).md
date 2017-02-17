주간닷넷 2017년 01월 10일

### On .NET 소식

[지난 주 ON.NET]( https://channel9.msdn.com/Shows/On-NET/Reed-Copsey-Jr-F-Software-Foundation/)에서는 F# 소프트웨어 재단의 수석 이사인 Reed Copsey, Jr과 함께 재단에서 진행하는 멘토링 및 발표자 프로그램에 관해 이야기 나누었습니다.

[이번 주 ON.NET]( https://channel9.msdn.com/Shows/On-NET/David-Pine-Magic-mirror-on-the-wall-who-is-the-fairest-one-of-all)에서는 [David Pine]( https://twitter.com/davidpine7)과 함께 Azure IoT Hub를 이용하여 개발한 스마트 거울인 [magic mirror]( https://ievangelist.github.io/blog/building-a-magic-mirror/)의 제작 과정에 관해 이야기 나누어보겠습니다.

### 금주의 패키지: Ammy
[XAML]( https://msdn.microsoft.com/en-us/library/cc295302.aspx)은 마이크로소프트가 구조값과 객체를 초기화하는데 사용하려고 만든 선언형 XML 기반 언어입니다. XAML은 단순히 XML 기반이므로 개발자들과 디자이너들은 컴파일하지 않아도 그들 사이에서 콘텐츠를 자유로이 공유하고 편집할 수 있다는 장점이 있지만 툴을 이용하지 않고 수작업으로 직접 콘텐츠를 수정/편집할 경우에는 매우 비효율일 수 있습니다. 하지만 XAML이 구현하는 것과 같은 아이디어는 다른 포맷으로도 완벽하게 구현될 수 있습니다.
[Ammy]( http://www.ammyui.com/)는 JSON, [Qt’s QML]( https://en.wikipedia.org/wiki/QML) 등의 영향을 받아서 탄생하였습니다. 따라서 경량이고 객체를 다양하게 표현하는 것이 가능하며 확장 또한 쉽다는 장점이 있습니다.
// 코드

### 금주의 툴: Concurrency Visualizer
[Concurrency Visualizer]( https://docs.microsoft.com/en-us/visualstudio/profiling/concurrency-visualizer)는 다중 스레드 응용 프로그램 성능을 시각화하는데 도움이 되는 Visual Studio의 중요한 확장 기능입니다. Concurrency Visualizer을 이용해서 다중 스레드 애플리케이션의 성능을 확인할 수 있으며, 주요 기능으로는 실행 프로세스와 관련 코어의 동작 상태, 스레드 상태, anti-pattern 감지, (성능향상을 위한) 제안 등이 포함되어 있습니다.
// 코드
Sergey Teplyakov가 [Concurrency Visualizer를 사용하여 다른 GC 모드를 이해하는데 도움이 되는 내용]( https://blogs.msdn.microsoft.com/seteplia/2017/01/05/understanding-different-gc-modes-with-concurrency-visualizer/)을 포스팅 하였습니다. 
### 금주의 게임 : Eco
[Eco]( https://www.strangeloopgames.com/eco/)는 생태계와 협업에 중점을 둔 글로벌 생존 게임입니다. 플레이어는 팀을 이루어 문명을 구축해야 하며, 지구를 향해 접근하고 있는 유성을 파괴하기 위해 팀과 협동하여 문명사회를 빠르게 발전시켜야 합니다. 하지만 생태계 균형이 깨지지 않도록 발전하는 것도 중요합니다.
Eco는 현실적인 생존 게임으로 플레이어의 행동 하나하나가 인간을 포함한 수많은 생명체에 영향을 줄 수 있는 지구 생태계 시스템을 게임의 기반으로 하였습니다. 만일 생태계 균형이 맞지 않으면 식량 또는 자원이 파괴되고 이로 인해 모든 생명체가 죽음에 이를 수 있습니다. 또한 플레이어는 국가와 정부를 세우고 법과 질서를 통해 치안을 유지하고 경제가 활성화될 수 있도록 문명을 끊임없이 발전시켜야 합니다.
//그림

[Eco]( https://www.strangeloopgames.com/eco/)는 [Strange Loop Games]( https://www.strangeloopgames.com/)에서 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)과 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2017/01/10/the-week-in-net-on-net-with-reed-copsey-jr-orchard-harvest-ammy-concurrency-visualizer-eco/unity3d.com)로 개발하였으며, 게임 웹사이트와 서버는 ASP.NET과 .NET Framework로 구축하였습니다. 현재 [알파버전]( https://ecoauth.strangeloopgames.com/home)으로 Steam통해 Windows, Mac, and Linux에서 즐기실 수 있습니다. 또한 Eco는 몇몇 학교에서 교육 목적으로 사용되고 있습니다.

### .NET 소식
* Multi-targeting the world: a single project to rule them all : Oren Novotnyrk이 Visual Studio 2017의 다양해진 멀티 타겟팅 설정 방법에 관해 설명합니다.
* Understanding and updating package versions for .NET Core 1.0.3 : Andrew Lock이 .NET Core 1.0.3의 핵심 업데이트 내용을 소개합니다.
* Exploring the.NET managed heap with ClrMD : Maarten Balliauw가 managed heap 정보를 탐색하는데 유용한 ClrMD (Microsoft.Diagnostics.Runtime)에 관해 설명합니다.
* .NET Core command-line file watcher (dotnet watch) for MSBuild and MSBuild + .NET Core CLI Tools: Getting information about the project : Nate McMaster가 MSBuild에서 dotnet-watch 사용 방법과 팁 그리고 project.json API를 MSBuild 타켓으로 대체하는 방법을 소개합니다.
* Reactive Extensions (Rx) – Part 8 – Timeouts : Muhammad Rehan Saeed가 연재하는 Rx 강좌의 8번째 시리즈인 “"Timeouts"가 게시되었습니다.
* Explaining .NET Standard Like I’m Five : Joe Petrakovich가 .NET 개발자로서 .NET Standard의 필요성에 관해 이야기합니다.
* Understanding OutOfMemoryException : Szymon Warda가 지금껏 경험한 OutOfMemoryException 의 발생 상황 경험담을 공유했습니다.
* An efficient filtering DSL for Serilog : Nicholas Blumhardt가 로그 라이브러리 Serilog를 이용하여객체의 속성을 효과적으로 필터링하고 로깅하는 방법을 소개합니다.
* Deploying a self contained .Net core application on Linux and run as a daemon process : Arindam Datta가 .Net core 애플리케이션을 리눅스의 데몬 프로세스 형태로 배포했던 경험을 공유했습니다.
* Breakpoints in Auto-Properties in Visual Studio 2015 : Rachel Hagerman이 Visual Studio 2015이상 버전에서 사용할 수 있는 디버깅 중단점의 유용한 기능들을 소개합니다.

### ASP.NET 소식
* Having a merry, geeky Christmas… creating an Alexa skill with ASP.Net Web API : Andy Butland가 알랙사(아마존 AI)의 AI기능을 ASP.Net Web API와 함께 연동하는 방법을 소개합니다.
* Custom Tag Helper: Toggling Visibility On Existing HTML elements : Scott Sauber가 서버 사이드의 (변수)상태에 따라 HTML 요소의 Visibility 속성을 토글 할 수 있도록 해주는 커스텀 Tag Helper의 구현방법을 설명합니다.
* Using MongoDB with ASP.NET Core – Part I (Setup) and Using MongoDB with ASP.NET Core – Part II (Implementation) : Janak shrestha가 ASP.NET Core에서 MongoDB의 활용방법을 Part I 와 Part II로 나누어 설명합니다.
* Response Caching in ASP.Net Core 1.1 : Talking Dotnet에서 ASP.Net Core 1.1의 응답 캐시에 관해 설명합니다.
* Prefix: A lightweight ASP.NET profiler helping you write better software : Matt Watson이 ASP.NET 프로파일러 "Prefix"에 관해 소개합니다.
* Caching static resources forever with ASP.NET Core : Gérald Barré가 ASP.NET Core의 캐시 기능 소개와 활용방법 등을 공유하였습니다.
### F# 소식
* Testimonial on Using F# by Microsoft’s Project Springfield Team : Pierre-Luc Maheu via InfoQ에서 마이크로소프트 클라우드를 기반으로 한 버그 탐지 툴 개발 프로젝트인 "Springfield"에 F#을 적용한 사례를 공유하였습니다.
* Pong in F# : Josh Miles가 F#을 이용해 탁구게임을 구현한 경험담을 공유하였습니다.
* Getting Emotional with Affectiva, F#, and Emgu : Boris Kogan이 구글의 어펙티바(Affectiva) SDK, F#,Emgu 를 이용한 감성 인식 구현 방법을 공유하였습니다.
* Decoupling application errors from domain models : Mark Seemann이 애플리케이션 에러를 도메인 모델간 격리(디커플)하는 방법을 소개합니다.
* F# Type Providers : Chris Gardner가 F#의 Type Provider에 관해 설명했습니다.

### Azure 소식
* Hello world! Welcome to AzureCAT Guidance! : Ed Price가 AzureCAT(Azure 고객 자문팀, Azure Customer Advisory Team)의 가이던스 서비스를 공유했습니다.
* Streamlining a search experience with ASP.NET Core and Azure Search : Matías Quaranta가 Azure Search 클라우드 검색 서비스를 ASP.NET Core에 적용하는 방법에 관해 설명합니다.
* Enable System.Net tracing on Azure App Service : Benjamin Perkins가 Azure App Service에서 System.Net tracing 기능을 설정 방법과 기록된 로그를 확인하는 방법 설명했습니다.
* Azure Functions preview versioning update : Chris Anderson이 Azure Function의 프리뷰 버전 업데이트 소식을 공유하였습니다.
* Create and deploy an ASP.NET Core Web API to Azure Windows : Benjamin Perkins가 ASP.NET Core Web API 애플리케이션을 Azure Windows에 생성 및 배포하는 방법에 관해 설명합니다.

### UWP 소식
* Using text to speech in your Windows Holographic apps : Abhijit이 홀로렌즈용 애플리케이션에서 TTS(텍스트 음성 변환) 구현방법을 소개합니다.
* Beautiful, cross-device, feature-rich and functional Universal Windows Platform app samples : Nikola Metulev가 UWP의 유용한 크로스플랫폼 샘플들을 공유했습니다.
* Web Real-Time Communications samples for the Universal Windows Platform : James Cadd가 UWP에서 테스트 및 사용할 수 있는 WebRTC(Web Real-Time Communications) 샘플들을 공유했습니다.

### Game 소식
* Game Design Deep Dive: Creating believable crowds in Planet Coaster : Owen Mc Carthy가 게임 Planet Coaster에 나타나는 사람들의 표정 디자인 과정을 소개합니다.
* Basics of Unity : Stacey Haffner가 유니티 학습 과정을 공유했습니다.
* Unity3D analog style Synthesizer Tutorial : Dano Kablamo가 Unity3D를 이용한 음향 컨트롤 방법을 소개합니다.
* Fading Sprites in Unity 5 by Alan Zucconi
* How to make a Sniper Scope Effect – Unity FPS Tutorial : Brackeys가 유니티에서 FPS 게임의 저격수의 망원 렌즈 효과 구현 방법을 공유하였습니다.
* Draw Normals Script : WaterfordSS가 3D 객체의 면의 방향을 표시(Draw Normal)하는 스크립트를 작성했습니다.
* [Unity 5] Tutorial: How to make an inventory system – part 4 : Gamad에서 연재중인 “[Unity 5] Tutorial”의 스리즈인 "인벤토리 시스템 구현"의 4번째 파트 영상이 공유되었습니다.
* Adam – VFX In the Real-Time Short Film : Zdravko Pavlov가 GDC 2016에서 소개된 아담 데모의 구현 과정을 공유하였습니다.

// 전무님 소개
