### On .NET 소식

지난주에는 쇼가 진행되지 않았습니다. 하지만 이번주에는 2개의 쇼를 진행할 예정입니다.

//그림
Scott Hanselma이 Kasey Uhlenhuth, Maria Naggaga Nakanwagi, Donovan Brown, Mitch Muenster와 함께 토론을 진행할 예정입니다.

//그림
Patrick Smacchia와 함께 새로운 버전의 ndepend에 대해서 얘기 나누어 보겠습니다.

### 금주의 패키지: Adafruit Class Library for Windows IoT Core
메이커 운동(maker movement, DIY와 비슷하지만 조금 다른)에 조금이라도 관심이 있는 사람이라면 에이다프루트(Adafruit) 브랜드가 익숙할것입니다. 오픈소스 지지자이면서 취미용 전자기기 업체 에이다프루트의 창립자이기도 한 Limor Fried는 풍부한 제품 사용학습서(링크)와 오픈소스 제품을 기반으로 회사를 성공적으로 이끌어왔습니다.

에이다프루트는 최근에 자사의 제품을 포함한 Windows IoT Core기반 IoT 장비(예를 들면 라즈베리파이 Pi)들을 제어할 수 있는 여러클레스로 구성된 Adafruit Class Library for Windows IoT Core와 관련 사용 학습서를 공개했습니다.

아래의 코드 예는 GPS의 좌표정보가 업데이트 될 때마다 새로운 고도, 경도, 위도를 표시하는 GPS의 이벤트 핸들러의 코드입니다.

// 코드


### 금주의 게임 : Floor Plan
Floor Plan은 VR용 퍼즐 어드벤처 게임입니다. 플레이어는 Floor Plan에서 엘리베이터를 타면서 게임중 만나는 아이템을 획득하고 이를 통해 다양한 퍼즐을 풀어야 합니다.  엘리베이터를 통해서 층에서 층으로 이동하면서 다양하고 신기한 케릭터들을 만나게 될것입니다.

//그림  

Floor Plan(링크)는 Turbo Button(링크)에서 C#(링크)과  XNA를이용하여 개발되었습니다. 현재 Gear VR, Oculus Rift, Daydream을 통해서 즐기실 수 있습니다. 

### .NET 소식
* Open sourcing the VS Test platform : Brian Harry가 VS 유닛 테스트 오픈소스 프로젝트 VSTest를 소개했습니다.
* .NET Core image processing : Bertrand Le Roy가 .NET Core 플랫폼에서 이미지를 처리 방법(이미지 크기 조절과 같은)을 설명했습니다.
* Custom project templates using dotnet new : Muhammad Rehan Saeed가 dotnet new 컴맨드이용한 커스텀 프로젝트 템플릿의 사용 방법을 설명했습니다.
* Creating .NET bindings for C libraries with ObjectiveSharpie : Miguel de Icaza가 iOS의 Objective-C API를 .NET 환경에 자동 맵핑해주는 라이브러리 ObjectiveSharpie를 소개했습니다.
* Project.json to MSBuild conversion guide : Nate McMaster가 Project.json 프로젝트 타입을 MSBuild 형태(*.csproj)로 변환하는 방법을 설명했습니다.
* Working with Multiple .NET Core SDKs – both project.json and msbuild/csproj : Scott Hanselman이 복수개의 다른 버전  .NET Core SDK를 하나의 개발 PC에서 동시에 사용하는 방법을 설명했습니다.
* Exploring Intermediate Language (IL) with ReSharper and dotPeek : Maarten Balliauw가 ReSharper와 dotPeek을 이용한 IL 코드 탐색방법을 설명했습니다.
* Essential MSBuild: A Build Engine Overview for .NET Tooling : Mark Michaelis가 닷넷 빌드툴 "MSBuild :  build engine overview for .NET tooling"을 설명했습니다
* New code coverage highlighting in dotCover 2016.3 : Alexey Totin가 jetbrains의 코드 커버리지( Code Coverage)툴 dotCover 2016.3 의 버전은 소개했습니다.
* Introduction to Akka.Cluster.Sharding in Akka.NET : Bartosz Sypytkowski가 Akka.NET 의 플러그인 Akka.Cluster.Sharding를 소개했습니다.
* The .NET Core 2 Wave : Ed Charbeneau가 2017년중 발표될 것으로 기대되는 .NET Core 2의 새로운 기능에 대해서 전망했습니다.

### ASP.NET 소식
* Error handling in ASP.NET Core : Dustin Moris Gorski가 ASP.NET Core에서의 효과적인 예외처리방법을 설명했습니다.
* How to pass parameters to a view component : Andrew Lock이 view component에 인자를 전달하는 방법을 설명했습니다.
* Defensive logging on ASP.NET Core : Gunnar Peipman이 ASP.NET Core 에서의 로그 수준별로 로깅하는 방법을 설명했습니다.
* Inside compiled views in the Razor view engine : the ASP.NET Monsters에서 Razor view engine 의 런타임, 디버깅 타임 동작 원리를 설명했습니다.

### F# 소식
* F# for Azure Notebooks : F#을 사용할수있는 Azure Notebook를 소개했습니다.
* Security testing in the cloud with F# and Project Springfield : 보안 버그와  취약점을 찾아주는 Project Springfield 클라우드 서비스와 F#을 이용한 보안 테스트를 소개했습니다.
* ASP.NET Monsters #85: Suave Web Services : ASP.NET Monster 에서 F#을 위한 웹 개발 라이브러리인 Suave를 소개했습니다.
* F# Unit Test Simplified – Expecto with Visual Studio Code : Tomr Prior가 F# 단위테스트 프레임워크인 Expecto의  사용방법을 설명했습니다.
* Experimenting with data in F# : Chris Alexander가 Visual Studio Code에서 라이브러리 FsLab를 이용한 데이터 활용 방법을 설명했습니다.

### Xamarin 소식
* Xamarin Beta Release: Cycle 9 RC builds : Adrian Murphy가 베타 릴리즈 : 사이클 9 RC 버전을 소개했습니다. 
* Try the next major Xamarin release candidate : Joseph Hill이 다음 버전 Xamarin RC 버전을 소개했습니다.
* New Xamarin.Forms Pre-release 2.3.4.184-pre1: quality improvements, bindable picker : David Ortinau가 Xamarin.Forms 프리 릴리즈  2.3.4.184-pre1 버전을 소개했습니다.
* Xamarin podcast: designing mobile apps : Pierce Boggan이 팟 케스트 : "모바일 어플 디자인"을 공유했습니다.
* What Xamarin developers ought to know to start 2017 & How to build & ship an app in a week with Xamarin.Forms : James Montemagno가 Xamarin 개발자가 2017년 에 알아두면 도움이 되는 정보(링크)와 Xamarin.Forms 를 통해서 일주일만에 모바일 어플을 개발/배포 할 수 있는 방법(링크)를 공유했습니다.
* The Xamarin Show 13: MVVM Helpers : James Montemagno가 Xamarin Show 13편 : MVVM Helper를 설명했습니다.
* You too can build Xamarin apps with F# : Greg Shackles가 F#과 Xamarin을 이용한 어플 개발 방법을 설명했습니다.
* Xamarin Forms WebView advanced series, Xamarin Forms WebView bindable actions, & Xamarin Forms WebView executing JavaScript : Adam Pedley가 Xamarin Forms의 WebView 고급기능 활용 시리즈(링크)., bindable actions(링크), 자바 스크립트 실행 방법(링크)등의 설명을 공유했습니다. 
* Codemash and Xamarin.Forms : Jason Farrell가 북미지역 기술 컨퍼런스  Codemash에서 자신이  Xamarin.Forms에 관한 세션을 진행한다는 소식을 고유했습니다.
* ReactiveUI v7.1.0 released : Geoffrey Huntley가 ReactiveUI v7.1.0 릴리즈 소식을 공유했습니다.
* Attached properties – what are they good for? : Matthew Soucoup가 Attached property를 설명했습니다.

### UWP 소식
* Announcing “UWPDesktop” NuGet package version 14393 : Vladimir Postel이 UWPDesktop NuGet package 버전 14393이 공유되었습니다.
* Windows 10 development for beginners (free course) : Richard Hay 가 윈도우 10 초보 개발자를 위한 학습 가이드를 공유했습니다.
* Dragging holograms with gaze and tapping them in place on a surface : Joost van Schaik가 홀로렌즈를 이용해서 가상의 물체를 이동 시키거나 선택 혹은 두두리는 동작의 구현방법을 설명했습니다.
* windows.updatetask – The hidden gem in UWP : Martin Suchan이 잘알려지지는 않았지만 UWP 어플에서 유용하게 사용할 수 있는 windows.updatetask을 설명했습니다.
* Open tab items dynamically with UWP : Christian Nagel이 UWP 어플에서 Dependency Injection 과 MVVM을 이용하여 탭 아이탬을 동적으로 오픈하는 방법을 설명했습니다.

### Game 소식
* Unity Navigation – Part 2 by Stacey Haffner.
* Building a 3D game engine with .NET Core : Eric Mellino가 .NET Core환경에서 클라이언트용 3D 게임 엔진, 에디터를 만든 과정을 공유했습니다.
* (Unity) Live Session: localization Tools.
* Simple LODs in Unity – Unity 5.xx : James Arndt이 Unity의  LOD(Level Of Detail) 활용 방법을 설명했습니다.
* Circle loading animation in Unity3D : Salus Games에서 간단히 구현할수있는 작업진행중 에니메이션(윈도우의 모래시계와 같은)을 설명했습니다.

// 전무님 소개
