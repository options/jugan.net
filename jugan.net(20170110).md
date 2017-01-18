주간닷넷 2017년 01월 10일

### On .NET 소식

[지난 주 On .NET]()(링크)에는 지난 서밋에 참여한 MVP인 Reed Copsey와 함께 F# Software Foundation에 대해서 얘기 나누었습니다.

이번주에는  David Pine과 자신이 개발한 매직미러(magic mirror) 제작 과정에 대해서 얘기를 나누어 보겠습니다.

### 금주의 패키지: Ammy
WPF 개발자들이 잘 아는 XAML은 실은 클래스의 객체 인스턴스를 표현하기위한 마크업 언어입니다.  베이스 포멧으로는 XML을 사용하고 있기때문에 모든 상황에서 다 만족할수있는 포멧이라고 하기는 힘들며 툴을 이용하지않고 수작업으로 직접 수정/편집 할경우에는 매우 비효율적일수 있습니다. XAML의 기본 아이디어를 다른 파일 포멧으로도 구현하는것이 가능한데 Ammy는 그러한 포멧중에 하나입니다. Ammy는 JSON , Qt’s QML등의 영향을 받아서 탄생되었습니다. 따라서 경량이고 객체를 다양하게 표현하는것이 가능하며 확장또한 용이하다는 장점이 있습니다.

// 코드

### 금주의 툴: Concurrency Visualizer
Concurrency Visualizer는 다중 스래드 어플리케이션 개발자라면  꼭 한번 사용해 봐야 하는 유용한 Visual Studio 확장 툴입니다. 이툴을 이용해서 다중 스래드 어플리케이션의 성능을 확인할수있읍니다.  구체적인 기능으로는 실행 프로세스와 관련 코어의 동작 상태, 스래드 상태, anti-pattern 감지, (성능향상을 위한)제안등의 기능을 포함하고있습니다.

// 코드

### 금주의 게임 : Eco
Eco는 생태계 개념과 협업작업기능이 포함된 글로벌 생존게임입니다. 지구를 향해 접근하고있는 유성을 파괴하기위해 플레이어는 팀을 이루어 문명사회를  빠르게 진화시켜야 합니다. 하지만 생태계 밸런스가 깨지지 않도록  빠르게 않게 진화하는것도 중요합니다
Eco는 일반적인 생존 게임 장르이면서 플러이어의 행동 하나하나가 인간을 포함한 수많은 생명체에 영향을 줄 수 있는 생태계 개념이 적용한 고유한 게임 시스템을 기반으로 합니다. 만일 벨런스가 맞지 않으면 식량지원이 파괴되고 이로인해 모든 생명체가 죽음에 이를수 있습니다. 플레이어는 나라와 정부를 세우고 법질서를 통한 치안확입및 경제가 활성화 될 수 있도록하여 문명을 발전시켜야 합니다.

//그림

Eco(링크)는 Strange Loop Games(링크)에서 개발했으며 게임 클라이언트는 C#(링크)과  Unity(링크)이용하였으며 게임 웹사이트와 서버는 ASP.NET과 .NET Framework를 이용하여 개발되었습니다. 게임 Eco는 현재 알파버전으로 Steam(링크) 통해서 Windows, Mac, and Linux에서 즐기실 수 있습니다. 또한 Eco는 몇몇 학교에서 교육용으로 시범적으로 사용되고 있기도 합니다.

### .NET 소식
* Multi-targeting the world: a single project to rule them all : Oren Novotnyrk이 Visual Studio 2017의 더욱 다양해진 멀티 타겟팅 대상의 설정 방법을 설명했습니다.
* Understanding and updating package versions for .NET Core 1.0.3 : Andrew Lock이 작년 12월에 업데이트된  .NET Core 1.0.3 버전의 업데이트 내용과 패키지 버전에 대해서 설명했습니다.
* Exploring the.NET managed heap with ClrMD : Maarten Balliauw가 ClrMD (Microsoft.Diagnostics.Runtime)를 이용한 managed heap 정보를 탐색하는 방법을 설명했습니다.
* .NET Core command-line file watcher (dotnet watch) for MSBuild and MSBuild + .NET Core CLI Tools: Getting information about the project : Nate McMaster가 NET Core의 file watcher 명령창 컴맨드의 소개(링크)와 CLI를 이용하여 프로젝트 파일의 정보를 출력하는 예(링크)를 설명했습니다 
* Reactive Extensions (Rx) – Part 8 – Timeouts : Muhammad Rehan Saeed가 Rx시리즈 8 "Timeouts" 을 게시했습니다.
* Explaining .NET Standard Like I’m Five : Joe Petrakovich가 .NET Standard의 의미와 필요성을 설명했습니다.
* Understanding OutOfMemoryException : Szymon Warda가 자신이 경험한 OutOfMemoryException 의 발생 상황에 대한 경험을 공유했습니다.
* An efficient filtering DSL for Serilog : Nicholas Blumhardt가 로그 라이브러리 Serilog 를 이용하여 효과적으로 객체의 속성을 필터링하고 로깅하는 방법을 설명했습니다.
* Deploying a self contained .Net core application on Linux and run as a daemon process : Arindam Datta가 .Net core 어플리케이션을 리눅스의 데몬 프로세스 형태로 배포했던 경험을 공유했습니다.
* Breakpoints in Auto-Properties in Visual Studio 2015 : Rachel Hagerman이 Visual Studio 2015이상의 버전에서 사용할 수 있는 디버깅 중단점의 유용한 기능을 소개했습니다.

### ASP.NET 소식
* Having a merry, geeky Christmas… creating an Alexa skill with ASP.Net Web API : Andy Butland가 알랙사(아마존 AI)의 AI기능을 ASP.Net Web API와 함께 연동하는 방법을 소개했습니다.
* Custom Tag Helper: Toggling Visibility On Existing HTML elements : Scott Sauber가 서버 사이드의 (변수)상태에 따라서 HTML 요소의 Visibility 속성을 토글 할 수 있도록 해주는 커스텀 Tag Helper의 구현방법을 설명했습니다.
* Using MongoDB with ASP.NET Core – Part I (Setup) and Using MongoDB with ASP.NET Core – Part II (Implementation) : Janak shrestha가 ASP.NET Core에서 MongoDB 의 활용방법을 Part I(링크)와 Part II (링크)로 나누어 설명했습니다.
* Response Caching in ASP.Net Core 1.1 : Talking Dotnet에서 ASP.Net Core 1.1의 응답 캐시에 대해서 설명했습니다.
* Prefix: A lightweight ASP.NET profiler helping you write better software : Matt Watson이 ASP.NET 프로파일러 "Prefix"를 소개했습니다.
* Caching static resources forever with ASP.NET Core : Gérald Barré가 ASP.NET Core의 캐시기능의 설명과 활용방법을 공유했습니다.
### F# 소식
* Testimonial on Using F# by Microsoft’s Project Springfield Team : Pierre-Luc Maheu via InfoQ에서 MS의 클라우드기반 버그 탐지툴 프로젝트 "Springfield"에 F#을 적용한 사례를 소개했습니다. 
* Pong in F# : Josh Miles가 F#을 이용해서 퐁게임(1세대 흑백 탁구게임)을 구현한 경험을 설명했습니다.
* Getting Emotional with Affectiva, F#, and Emgu : Boris Kogan이 구글의 어펙티바(Affectiva) SDK, F#,Emgu 를 이용한 감성인식 방법을 소개했습니다.
* Decoupling application errors from domain models : Mark Seemann이 어플리케이션 에러를 도메인 모델간 격리(디커플)하는 방법을 소개했습니다.
* F# Type Providers : Chris Gardner가 F#의 Type Provider를 설명했습니다.

### Azure 소식
* Hello world! Welcome to AzureCAT Guidance! : Ed Price가 AzureCAT(Azure 고객 자문팀, Azure Customer Advisory Team)의 가이던스를 공유했습니다.
* Streamlining a search experience with ASP.NET Core and Azure Search : Matías Quaranta가 Azure Search 클라우드 검색 서비스를  ASP.NET Core에 적용하는 방법을 설명했습니다.
* Enable System.Net tracing on Azure App Service : Benjamin Perkins가 Azure App Service에서 System.Net tracing 기능을 설정하는 방법과 기록된 로그를 확인하는 방법 설명했습니다.
* Azure Functions preview versioning update : Chris Anderson이 Azure Function의 프리뷰 버전의 업데이트 정보를 소개했습니다.
* Create and deploy an ASP.NET Core Web API to Azure Windows : Benjamin Perkins가  ASP.NET Core Web API 어플리케이션을 Azure Window에 생성 배포하는 방법을 설명했습니다.

### UWP 소식
* Using text to speech in your Windows Holographic apps : Abhijit이 홀로렌즈용 어플리케이션에서 TTS(텍스트 음성 변환) 구현방법을 설명했습니다.
* Beautiful, cross-device, feature-rich and functional Universal Windows Platform app samples : Nikola Metulev가 UWP의 여러 유용한 크로스플랫폼 샘플정보를 공유했습니다.
* Web Real-Time Communications samples for the Universal Windows Platform : James Cadd가 UWP에서 사용할 수 있는 WebRTC(Web Real-Time Communications) 샘플을 공유했습니다.

### Game 소식
* Game Design Deep Dive: Creating believable crowds in Planet Coaster : Owen Mc Carthy가 게임 Planet Coaster에 표현되는 사람들의 현실감있는 표현 및 디자인과정을 설명했습니다.
* Basics of Unity : Stacey Haffner가 유니티 학습 동영상을 공유했습니다.
* Unity3D analog style Synthesizer Tutorial : Dano Kablamo가 Unity3D를 이용한 음향제어 방법을 설명했습니다.
* Fading Sprites in Unity 5 by Alan Zucconi
* How to make a Sniper Scope Effect – Unity FPS Tutorial : Brackeys가 유니티에서 FPS 게임의 저격수의 망원 렌즈 효과를 구현하는 방법을 설명했습니다.
* Draw Normals Script : WaterfordSS가 3D 객체의 면의 방향을 표시(Draw Normal)하는 스크립트를 작성했습니다.
* [Unity 5] Tutorial: How to make an inventory system – part 4 : Gamad에서 "[Unity 5] Tutorial" 시리즈 "인벤토리 시스템 구현" part 4 동영상을 공유했습니다.
* Adam – VFX In the Real-Time Short Film : Zdravko Pavlov가 GDC 2016에서 소개된 아담 데모의 구현과정을 소개했습니다.

// 전무님 소개
