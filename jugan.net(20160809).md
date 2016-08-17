### On .NET 소식
지난 주 On .NET에서는 iPad용 개발 IDE 인 "Continuous C# and F# IDE"에 대해서 어플을 직접 개발한 Frank Krueger와 함께 알아봤습니다.

이번 주 On .NET에서는 Francisco Monteverde와 함께 PlasticSCM 에 대해서 얘기해볼 예정입니다.

### 금주의 패키지 - OxyPlot

[OxyPlot]()은 다중 플랫폼을 지원하는 오픈소스 plotting 라이브러리입니다. 

아래 예제는 유니버설 윈도우 어플리케이션에서  삼각함수 Cos 를 이용해서 plotting 하는 코드입니다.

// 코드

// 코드

// 코드

### 금주의 Tool - .NET API Catalog
[.NET API Catalog]() 는 .NET API를 쉽게 탐색하고 다양한 버전 ( .NET: .NET Framework, .NET Standard, Mono, or even Silverlight) 에서 API가 지원되는지 쉽게 확인할 수 있도록 도와줍니다.  이 사이트의 웹 URL은 실제 API의 Full Name을 반영하기 때문에 사용자가 쉽게 수정해서 접근하는것도 가능합니다.

.NET API Catalog은 Azure 환경에서 실행되며 메모리 객체로 구성된 Azure 의 Blob 저장소에 일정 주기로 자동 배포되며 매번 배포될 때마다 VSTS에 호스팅 되어있는 CoreFxTools, Git repo들의 자료를 바탕으로 API 구성 정보를 갱신합니다.

### 금주의 게임 - Dreamfall Chapters
[Dreamfall Chapters]()는 hit adventure game 게임으로서 The Longest Journey(링크), DreamFall: Longest Journey(링크) 시리즈의 최신 게임입니다. The Longest Journey 시리즈는 같은 시간에 연결된 서로 다른 두 세계, Stark라고 알려진 미래의 사이버펑크(cyberpunk) 지구와 Arcadia라는 마법 판타지 왕국를 배경으로 플레이하게 됩니다. 플레이어는 두 영웅중 하나의 역할 수행하게 되며 플레이어가 선택한 영웅은 서로 다른 스토리를 진행하며 두 우주를 구하는 긴 여정을 시작하게 됩니다. 플레이어는 자신인의 판단으로 전개되는 깊고 몰입도 있는 스토리를 경험하게 됩니다. 또한 스토리 전개상 실수하지 않는것이 중요합니다. 게임 진행중의 작은 실수들은 후반부에 커다란 변수가 될 수 있기때문입니다. Dreamfall Chapters은 총 5개의 에피소드로 나누어 구성되며 각각 에피소드는 플레이어가 게임 진행 중 결정한 다양한 선택에 따라서 서로의 스토리가 연결되게 됩니다. 

실수하지마라 : Dreamfall 시리즈는 "point-and-click" 어드벤처 장르의 최고의 게임으로 놀랍고 깊이있는 스토리 전개를 가지고 있기때문에 충분히 재미있고 꼭 해볼만한 게임입니다.

// 그림

Dreamfall Chapters는  Red Thread Games가 [Unity](http://unity3d.com/)와 [C#](https://channel9.msdn.com/Series/C-Sharp-Fundamentals-Development-for-Absolute-Beginners)을 이용하여 개발하였습니다. 또한 온라인 서버는 Azure를 사용합니다. Dreamfall Chapters는  Good Old Games(링크) 과 Steam(링크)를 통해서 Windows, Mac OS X and Linux에서 플레이 가능하며  PS4에서도 즐기실 수 있습니다.

### .NET 소식
* Announcing .NET Framework 4.6.2 : Stacey Haffner가 .NET Framework 4.6.2의 릴리즈 소식을 전해주었습니다.
* Compile your changes on the fly with .NET Core Watch : Jon Hilton가 .NET Core의 Watch 기능을 이용하여 개발 어플리케이션의 소스가 변경될 때마다 해당 소스 프로젝트가 자동으로 빌드 되도록 구성하는 방법을 공유했습니다 
* Entity Framework Core 1.0 – Table Valued Functions and LINQ Composition : Christos Matskas가 Entity Framework Core 1.0의 기능을 설명했습니다 
* Announcing Machine.Specifications (MSpec) 0.11 for .NET Core, .NET CLI and .NET Standard : Ivan Zlatev가  .NET Core, .NET CLI, .NET Standard 1.3을 지원하는 Machine.Specifications (MSpec) 0.11 버전의 정보를 공유했습니다.
* NSubstitute 2.0.0 (RC) released with .NET Core compatibility : David Tchepak가 .NET Core에서 실행가능한 NSubstitute 2.0.0 (RC) 의 릴리즈 소식을 전했습니다.
* .NET thread-pool threads and CLR worker threads : Changhong Fu가 .NET의 thread-pool의 스레드와와 CLR의 작업 스레드( worker threads)를 설명했습니다.
* Fast Deep Copy by Expression Trees (C#) : Frakon가 Expression Tree를 이용한 빠른  Deep Copy 방법을 공유했습니다.
* Throttling to improve responsiveness : jbe2277가 Throttling을 이용한 성능 개선 방법에 대해서 공유했습니다.
* Exploring Entity Framework Core 1.0.0 RTM Changes by Steve Gordon이 Entity Framework Core 1.0.0 RTM 버전의 변경내용을 공유했습니다.

### ASP.NET 소식
* ASP.NET Core Kestrel – The Need for Speed : Mark Downie가 ASP.NET Core용 크로스플랫폼 웹서버인 Kestrel에 대해서 소개했습니다. 
* ASP.NET Core Dependency Injection : Shawn Wildermuth가 ASP.NET Core의 DI(Dependency Injection)에 대해 설명했습니다.
* Add HTTP headers to static files in ASP.​NET Core : Jürgen Gutsch가  ASP.​NET Core 에서 JavaScript, CSS 파일과 같은 정적 파일의 요청을 개발자가 코드를 이용해서 처리하는 방법을 공유했습니다.
* Integration testing your ASP.NET Core middleware using TestServer : Joseph Woodward가 TestServer 를 이용한 ASP.NET Core의 미들웨어 통합테스트에 대해서 설명했습니다.
* Simulating Latency in ASP.NET Core : Marius Schulz가 ASP.NET Core 어플리케이션 로컬 개발시 로컬 서버의 응답시간을 원격 서버 접속때와 유사하게(느리게) 시뮬레이션 할 수 있는 방법을 공유했습니다.
* Forking the pipeline – adding tenant-specific files with SaasKit in ASP.NET Core : Andrew Lock이 ASP.NET Core에서 SaasKit 을 이용할 때 tenant가 필요로 하는 특정 파일을 추가하는 방법을 공유했습니다.

### F# 소식
* Walmart Rewrites Its E-Commerce Strategy With $3.3 Billion Deal for Jet.com : Leslie Picker와 Rachel Abrams이 미국 대형마트인 월마트가  온라인 유통회사인 아마존에 대항하기 위해 제트닷컴을 33억달러(3조6316억원)에 인수한다는 소식을 전했습니다.
* F# in Numbers: A Look at the Annual F# Survey Results : Tomas Petricek이 fsharpWorks에서 올해 4월에 진행한 F# 개발자 대상 설문의 결과를 정리해서 공유했습니다.
* F# for Fun and Profit is Available as a Gitbook  :  fsharpforfunandprofit.com 사이트의 eBook 버전인 Gitbook 페이지가 소개되었습니다.
* Comparing Scala to F# : Mikhail Shilkov가 F#과 Scala 언어를 비교해주었습니다.
* F# for Scala Developers (slides) : Alfonso Garcia-Caro가 Scala 개발자를 대상으로 F#을 소개했습니다.
* TypeShape: Practical Generic Programming for F#, a new library : Erik Tsarpalis가 F# 오픈소스 라이브러리인 TypeShape를 소개했습니다.
* F# to Javascript with Tomas Petricek (podcast) : Tomas Petricek이 F# 을 Javascript으로 변환해주는 컴파일러 프로젝트인 Fabel 에 대한 podcast를 진행했습니다.
* Perspectives on Clojure and F# (video) : Clojure 개발자 Rich Hickey와 F# 컴파일러 개발자인 Joe Pamer가 각각 자신들의 개발언어를 소개하고 특징을 비교했습니다(링크된 영상은 2010년것으로 이때부터 F#이 뜨는 개발 언어로 주목받고 있었네요).
* If you’re not live-codeing, you’re dead-coding (video) : Jeremy Chassaing이  live-codeing이라는 주제로 F# 기술 세션을 진행했습니다.
* Fable |> React Native – Native apps with F# : Steffen Forkmann이 Fable 과 React Native 라이브러리를 이용한 F#의 모바일 어플 개발 방법을 공유했습니다.
* Incremental construction of DFA in F# : Vyacheslav Chernykh가 F#으로 구현한 DFA의 Incremental construction 알고리즘을 공유했습니다.
* Building an OData service in F# using Entity Framework and Suave : Tamizh Vendan이 Entity Framework와 F#의 웹 개발 라이브러리 Suave을 이용한 F# OData 서비스 구현방법을 공유했습니다.

### Xamarin 소식
* Xamarin.Forms 2.3.1-stable : Bryan Hunter이 "Xamarin.Forms 2.3.1" 버전의 설치 및 변경된 내용을 업데이트 했습니다.
* Using Speech Recognition in iOS 10 : Greg Shackles이 iOS 10에서 음성인식 기능의 사용방법을 공유했습니다.
* .NET Standard Library Support for Xamarin and Creating and Consuming .NET Standard Libraries in Xamarin and Xamarin.Forms (video) : James Montemagno가 .NET Standard Library를 Xamarin 에서 활용하는 방법(링크)과 Xamarin과 Xamarin.Forms에서 .NET Standard Libraries를 활용및 구현하는 방법을 소개했습니다.
* .NET Standard Library with Xamarin Forms and .NET Standard with Xamarin Forms Gotchas : Adam Pedley가 Xamarin Forms에서 .NET Standard Library를 활용하는 방법(링크)와 .NET Standard의 장점등을(링크) 설명했습니다.
* Integrating Azure Active Directory B2C into Xamarin Mobile App : Hossam Barakat이 Azure Active Directory B2C를 Xamarin 어플과 연동하는 방법을 소개했습니다.
* Using the ContainerView to Share Views – aka Fragments in Xamarin.iOS : Richard Woollcott이 Xamarin.iOS 에서 ContainerView 의 활용방법을 소개했습니다.

### Games
* IL2CPP Optimizations: Faster Virtual Method Calls : Josh Peterson 가 가상함수 호출시 성능을 효과적으로 향상할 수 있는 개발 방법을 공유했습니다.
* Hex Map 3: Elevation : Catlike Coding에서 퍼즐형 게임에 많이 활용되는 6각형 맵의 구현 및 활용 과정을 소개해 주셨습니다.[셀의 고도(높이)]
* 1.2 Unity Tower defense tutorial – Tile types  : inScope Studios에서 타워 디펜스 게임 구현 방법에 대해 설명했습니다.
* Unity and C# Tutorial 4 – Finish Rock Paper Scissors Console : Craig Hinrichs가 C#을 이용한 Unity 프로그램 개발의 기초를 설명했습니다.
* C# Monogame RPG Made Easy Tutorial 3 – Xml Serialization : CodingMadeEasy에서 Microsoft XNA framework 기반 게임 엔진인 MonoGame을 이용하여 RPG 게임을 구현하는 방법에 대해 설명하였습니다.


// 전무님 소개
