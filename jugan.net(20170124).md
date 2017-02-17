여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 Gist나 주간닷넷 페이지를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On .NET 소식
지난주에는 쇼가 진행되지 않았습니다. 이번 주 ON,NET에서는 2개의 쇼가 진행되었습니다.

//그림
Scott Hanselma이 Kasey Uhlenhuth, Maria Naggaga Nakanwagi, Donovan Brown, Mitch Muenster와 함께 스튜디오에서 기술 토론을 진행하였습니다.
//그림
Patrick Smacchia가 .NET 관리 코드를 위한 정적 분석 도구인 [ndepend]( http://www.ndepend.com/)의 새로운 버전을 소개합니다.

### 금주의 패키지: Adafruit Class Library for Windows IoT Core
[Adafruit]( https://www.adafruit.com/)는 메이커 무브먼트로 유명한 브랜드입니다. 훌륭한 사업가이자 오픈 소스 옹호자인 Limor Fried는 [고품질 제품 튜토리얼]( https://www.adafruit.com/)과 [오픈소스 제품을 기반으로 회사]( https://www.adafruit.com/categories)를 성공적으로 이끌어왔습니다.
Adafruit는 최근에 자사의 제품을 포함한 [Windows IoT Core기반 IoT 장비(예를 들면 라즈베리파이 Pi)들을 제어할 수 있는 일련의 클래스]( https://learn.adafruit.com/adafruit-class-library-for-windows-iot-core/overview)로 구성된 Windows IoT Core 전용 Adafruit 클래스 라이브러리 튜토리얼을 공개하였습니다.

아래 예제 코드는 [GPSHAT]( https://www.adafruit.com/product/2324) 정보가 업데이트될 때마다 새로운 고도, 경도, 위도를 표시하는 GPS 이벤트 핸들러 코드입니다.

// 코드


### 금주의 게임 : Floor Plan
[Floor Plan]( http://www.turbo-button.com/games/floorplan)은 엘리베이터 내부에서 진행되는 VR용 퍼즐 어드벤처 게임입니다. 플레이어는 엘리베이터 각 층을 방문하며 아이템을 찾고, 다양한 캐릭터를 만나 힌트를 얻어 다양한 퍼즐을 풀어야 합니다.

//그림 

[Floor Plan]( http://www.turbo-button.com/games/floorplan)는 [Turbo Button]( http://www.turbo-button.com/about/)에서 [C#]( https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)과 [Unity]( https://blogs.msdn.microsoft.com/dotnet/2017/01/24/the-week-in-net-adafruit-class-library-for-windows-iot-core/unity3d.com)를 이용하여 개발되었습니다. 현재 Gear VR, Oculus Rift, Daydream로 게임을 즐기실 수 있습니다. 

### .NET 소식
* Open sourcing the VS Test platform : Brian Harry가 VS 유닛 테스트 오픈소스 프로젝트인 VSTest에 관해 소개합니다.
* .NET Core image processing : Bertrand Le Roy가 .NET Core 플랫폼에서 이미지를 처리 방법(이미지 크기 조절과 같은)에 관해 설명합니다.
* Custom project templates using dotnet new : Muhammad Rehan Saeed가 Dotnet new 커맨드를 사용하여 사용자 지정 프로젝트 템플릿을 제작하는 방법을 설명합니다.
* Creating .NET bindings for C libraries with ObjectiveSharpie : Miguel de Icaza가 iOS의 Objective-C API를 .NET 환경에 자동 맵핑해주는 라이브러리, ObjectiveSharpie에 관해 소개합니다.
* Project.json to MSBuild conversion guide : Nate McMaster가 Project.json 프로젝트 타입을 MSBuild 형태(*.csproj)로 변환하는 방법을 설명합니다.
* Working with Multiple .NET Core SDKs – both project.json and msbuild/csproj : Scott Hanselman이 여러 버전 .NET Core SDK를 하나의 PC에서 동시에 사용하는 방법을 설명합니다.
* Exploring Intermediate Language (IL) with ReSharper and dotPeek : Maarten Balliauw가 ReSharper와 dotPeek을 이용한 IL 코드 탐색 방법을 설명합니다.
* Essential MSBuild: A Build Engine Overview for .NET Tooling : Mark Michaelis가 .NET Tooling Suite 내에서 MSBuild를 활용할 수 있는 방법을 소개합니다. 
* New code coverage highlighting in dotCover 2016.3 : Alexey Totin가 dotCover 2016.3에서 코드 적용 범위 강조 표시를 활성화하는 방법을 공유하였습니다.
* Introduction to Akka.Cluster.Sharding in Akka.NET : Bartosz Sypytkowski가 Akka.NET의 플러그인, Akka.Cluster.Sharding에 관해 소개합니다.
* The .NET Core 2 Wave : Ed Charbeneau가 2017년에 발표될 것으로 기대하고 있는 .NET Core 2의 새로운 기능들을 소개합니다.

### ASP.NET 소식
* Error handling in ASP.NET Core : Dustin Moris Gorski가 ASP.NET Core에서 효과적으로 예외처리하는 방법을 설명합니다.
* How to pass parameters to a view component : Andrew Lock이 view component에 인자를 전달하는 방법을 설명합니다.
* Defensive logging on ASP.NET Core : Gunnar Peipman이 ASP.NET Core에서 로그를 수준별로 로깅하는 방법에 관해 설명합니다.
* Inside compiled views in the Razor view engine : The ASP.NET Monsters 블로그에서 Razor view engine 의 런타임, 디버깅 타임 동작 원리를 설명합니다.

### F# 소식
* F# for Azure Notebooks : F#을 사용할 수 있는 Azure Notebook을 소개합니다.
* Security testing in the cloud with F# and Project Springfield : Azure 클라우드 힘으로 코드에서 심각한 보안 문제를 찾을 수 있도록 도와주는 Project Springfield에 관해 소개합니다.
* ASP.NET Monsters #85: Suave Web Services : ASP.NET Monster 블로그에서 F#을 위한 웹 개발 라이브러리, Suave에 관해 소개합니다.
* F# Unit Test Simplified – Expecto with Visual Studio Code : Tomr Prior가 F# 단위테스트 프레임워크인 Expecto 사용방법을 설명합니다.
* Experimenting with data in F# : Chris Alexander가 Visual Studio Code에서 F# FsLab 라이브러리로 쉽게 데이터 스크립팅 환경을 설정하는 방법을 소개합니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 9 RC builds : Adrian Murphy가 RC 빌드 베타 채널을 통해 Cycle 9라고 불리는 Xamarin 주요 업데이트 소식을 전합니다.
* Try the next major Xamarin release candidate : Joseph Hill이 major Xamarin의 최신 기능을 테스트해볼 수 있는 ‘Xamarin Release Candidate’ 버전을 소개합니다.
* New Xamarin.Forms Pre-release 2.3.4.184-pre1: quality improvements, bindable picker : David Ortinau가 Xamarin.Forms 2.3.4.184-pre1 프리 릴리즈 버전을 소개합니다.
* Xamarin podcast: designing mobile apps : Pierce Boggan이 Suave F # 웹 프레임워크를 사용하여 간단한 서비스를 작성하는 방법을 소개합니다.
* What Xamarin developers ought to know to start 2017 & How to build & ship an app in a week with Xamarin.Forms : James Montemagno가 Xamarin 개발자들이 2017년에 알아야 할 팁와 Xamarin.Forms로 일주일만에 애플리케이션 만드는 방법을 공유하였습니다.
* The Xamarin Show 13: MVVM Helpers : James Montemagno가 연재중인 Xamarin Show의 13번째 시리즈, MVVM Helper가 업로드되었습니다. 
* You too can build Xamarin apps with F# : Greg Shackles가 F#과 Xamarin을 이용한 애플리케이션 개발 방법을 공유하였습니다.
* Xamarin Forms WebView advanced series, Xamarin Forms WebView bindable actions, & Xamarin Forms WebView executing JavaScript : Adam Pedley가 Xamarin Forms의 WebView 고급 기능 활용 시리즈, bindable actions, JavaScript 실행 방법을 소개합니다.
* Codemash and Xamarin.Forms : Jason Farrell가 북미지역 기술 컨퍼런스, Codemash의 Xamarin.Forms 세션 소식을 공유하였습니다.
* ReactiveUI v7.1.0 released : Geoffrey Huntley가 ReactiveUI v7.1.0 릴리즈 소식을 공유했습니다.
* Attached properties – what are they good for? : Matthew Soucoup가 Attached property에 관해 설명합니다.

### UWP 소식
* Announcing “UWPDesktop” NuGet package version 14393 : Vladimir Postel이 “UWP Desktop” NuGet package 14393버전 발표 소식을 공유하였습니다.
* Windows 10 development for beginners (free course) : Richard Hay가 초보 Windows 10 개발자를 위한 학습 가이드를 공유했습니다.
* Dragging holograms with gaze and tapping them in place on a surface : Joost van Schaik가 홀로렌즈를 이용해 가상의 물체를 이동 시키거나 선택 반응 구현방법을 설명합니다.
* windows.updatetask – The hidden gem in UWP : Martin Suchan이 잘 알려지지는 않았지만 UWP 애플리케이션에서 유용하게 사용할 수 있는 windows.updatetask에 관해 설명합니다.
* Open tab items dynamically with UWP : Christian Nagel이 UWP 애플리케이션에서 Dependency Injection과 MVVM을 이용하여 동적으로 탭 아이템을 오픈하는 방법을 설명합니다.

### Game 소식
* Unity Navigation – Part 2 by Stacey Haffner : Anthony G가 point and click 스타일 동작에 마무리 터치를 추가하는 방법을 설명합니다.
* Building a 3D game engine with .NET Core : Eric Mellino가 .NET Core환경에서 클라이언트용 3D 게임 엔진, 에디터를 만든 과정을 공유했습니다.
* (Unity) Live Session: localization Tools : 이 실습 예제에서는 다른 언어로 텍스트 지역화 작업의 필요성에 관해 알아봅니다.
* Simple LODs in Unity – Unity 5.xx : James Arndt이 Unity의 LOD(Level Of Detail) 활용 방법을 설명합니다.
* Circle loading animation in Unity3D : Salus Games가 Unity에서 간단히 구현할 수 있는 애니메이션(윈도의 모래시계와 같은)을 소개합니다.

test
