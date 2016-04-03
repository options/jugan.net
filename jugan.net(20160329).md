### On.NET 소식
지난 주에는 클라우드 서비스 회사인 Joyent의 엔지니어로 근무하고 계시는 Richard Kiene를 모시고 Joyent 에 적용된 .NET Core에 대해서 얘기했습니다. 이번 주에는  John Kemnetz 님과 함께  VS Code의 C# extension에 대해서 알아보도록 하겠습니다.  On.NET 최초로 이번 주는 몇가지 데모를 포함해서 진행하겠습니다.(역주: 코드 데모 아니면 또다른 의미의?? 아직 비디오가 공개되지 않은 관계로 확인 되지 않았습니다)

### 금주의 프로젝트 - Foundatio
Foundatio는 loosely-coupled 한 분산 어플리케이션을 위한 오픈 소스 빌딩 블록 셋트입니다. 이 빌딩 블록은 분산 어플리케이션에서 많이 쓰이는 케싱작업은 물론이고 큐, 병렬작업 시 데이터의 잠금 관리, 메시징 작업, 작업(job), 파일 접근, metrics, 그리고 로깅까지 많은 기능의 인터페이스를 포함하고 있습니다. 제공되는 모든 인터페이스들은 in-memory 형태의 데이터 구조를 가지며 레디스(Redis) 라이브러리와 Azure 환경을 이용하여서 구현되었습니다. 

아래는 Foundatio를 이용해서 enqueue /dequeue 작업을 하는 간단한 예입니다.



### 금주의 컨트롤 - Telerik’s ListView for UWP

Telerik의 ListView for UWP은 아이템목록을 보여주는 일종의 리스트 컨트롤입니다. 이 ListView 컨트롤은 어플리케이션 개발에 필요한 가상화, 애니메이션, 그룹핑, 정렬, 필터링등 다양한 많은 기능을 기본으로 포함하고 있습니다.


### .NET 소식
* On the efficiency of ValueTask : Bar Arnon이 .NET Core에 적용되기 전 검증해 보는 일종의 파일럿 형태의 gitbub 라이브러리 repo인 corefxlab repository 라이브러리에 포함된 ValueTask<T> 타입의 대해서 설명했습니다. (역주 : 따라서 현재 ValueTask<T>는 .NET Core에 포함된 정식 라이브러리는 아니지만 추후 경우에 따라서는 정식라이브러리로 추가될 수도 있습니다. )

* Parallelism on a Single Core – SIMD with C# : Eoin Mullan이 CPU 명령 집합 SIMD (Single Instruction Multiple Data) 을 이용한 병렬 작업의 속도 개선 방법과 이에 대한 개념적인 이해를 C# 코드와 함께 자신의 블로그에 공유했습니다. 

* Why Microsoft Open Source (podcast) : Matt Millican이 최근 MS의 오픈소스 확대에 대한 배경과 앞으로의 방향 그리고 ASP core등 관련된 기술적인 내용을 3rd party 컴포넌트 회사인 telerik 회사 개발자 podcast(오디오)로 공유 했습니다.

* Cross-Platform Messaging for iOS, Android, and Windows : Pierce Boggan이 xamarin을 이용해서 스마트폰의 일반적인 작업인 SMS 문자 보내기, 전화걸기, 이메일 보내기 기능 구현을 할 수 있는 멀티 플렛폼(iOS, Android, and Windows) Messaging Plugin의 사용 방법을 xamarin 개발자 블로그에 공유했습니다. 

* How to create a multi architecture NuGet Package from a UWP class library : Marco Siccardi이 UWP(유니버셜윈도플랫폼) 클래스 라이브러에 사용될 수 있는 NuGet Package 생성 방법을 따라하기쉽게 단계별 데모로 설명하여 자신의 블로그에 공유해 주었습니다.

### ASP.NET 소식
* Creating Step-wise Forms with ASP.NET MVC and Kendo UI : Ed Charbeneaurk이 Telerik의 Kendo UI 라이브러리를 이용한  Step-wise Forms 형식의 화면 구현 방법을  ASP.NET MVC 데모 프로젝트를 이용해서 설명했으며 이를 Telerik 개발자 블로그 사이트에 공유했습니다.

* Custom Model Binder in ASP.NET MVC : Mahesh Sabnis이 ASP.NET MVC에서 사용할 수 있는 Custom Model Binder의 구현 방법과 구현 배경을 dotnetcurry 사이트에 공유했습니다.

* Dependency Injection Conditional Registration in ASP.NET Core : Eric L. Anderson이  ASP.NET Core환경에서 의존성주입(Dependency Injection)의 조건부 등록 방법을 자신의 블로그에 공유했습니다.

* Social TagHelpers for ASP.NET Core : Muhammad Rehan Saeed이 ASP.NET Core에서 Facebook, Twitter, Google+, Pintrest 등의 사이트에서 사용할 수 있는 SNS용 TagHelpers 클래스 사용방법과 다운로드 정보를 자신의 블로그에 공유했습니다.

* Subresource Integrity TagHelper Using ASP.NET Core part 1 and part 2 : Muhammad Rehan Saeed이  ASP.NET Core 환경에서 사용할 수 있는 Subresource Integrity(리소스 통합) TagHelper 클래스의 사용방법을 part 1과 part 2 로 나누어 설명하고 이 클래스를 포함한 라이브러리 다운로드 정보를 자신의 블로그에 공유했습니다.

* Structured logging with Serilog in ASP.NET Core (video) : the ASP.NET Monsters 사이트에 ASP.NET Core 환경에서 구조적으로 정리된 로그를 기록 하는 방법을 ASP.NET Monsters 사이트에 비디오로 공유했습니다.

### F# 소식
* F#, Azure, and the Web : Isaac Abraham이 F#을 이용한 웹 프로그래밍과 Azure Cloud 프로그래밍에 대한 설명을 유튜브 비디오로 공유했습니다.

* Creating Visual Studio Code Plugins with F# and Fable : Krzysztof Cieslak이 F#을 JavaScript으로 변환해주는 오픈소스 컴파일러인 Fable을 이용한 Visual Studio Code용 플러인 구현방법을 자신의 블로그에 공유했습니다.

* Kaggle Home Depot Competition Notes: Features : Mathias Brandewinder이 Kaggle 사이트의 Home Depot 문제해결에 참여했던 경험을 자신의 블로그에 공유했습니다. (역주 : Kaggle 사이트는 일종의 문제해결경쟁 사이트로 Kaggle 회원사가 문제 해결을 요청하면 Kaggle은 이 문제의 해결방법을 대회로 진행합니다. 대회 우승자에게는 일정의 상금과 경우 따라서는 라이선스 권한도 가지게 되며 Mathias Brandewinder는 Home Depot회사가 요청한 문제 해결에 참여했습니다.)

* Property-Based Testing in the Real World – Or How I Made My Package Manager Suck Less : Steffen Forkmann가  .NET/mono 에 포함된 dependency manager 라이브러리인 “Paket"에서 특정 버그를 발견하고 이 오류를 수정하면서 얻은 경험과 또 유사한 버그를 미리 사전에 인지할 수 있는 테스트 방법을 공유했습니다.

* Sentiment Analysis in F# : Stephen Ireland이 F#과 FsLab 라이브러리를 이용한 감정 분석  방법을 공유했습니다.

* History and Philosophy of Types : Tomas Petricek이 Lambda Days 2016 컨퍼런스에서 프로그래밍 언어관점에서 본 "타입의 역사와 개념" 이란 제목으로 세션을 진행했으며 녹화된 세션 동영상이 유튜브에 공유되었습니다.


* A Brief History of Programming Languages, : Andrea Magnorsky Lambda Days 2016 컨퍼런스에서 "프로그래밍 언어의 역사"라는 제목으로 세션을 진행했으며 녹화된 세션 동영상이 유튜브에 공유되었습니다.
