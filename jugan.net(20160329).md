### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=v5YUoeFCoe8)는 쿨라우드 서비스 제공 업체인 Joyent 에서 엔지니어로 근무하고 계시는 Richard Kiene 를 모시고 CoreCLR 과 ASP.NET 을 이용하여 서비스를 개발한 경험에 대해 이야기를 나누었습니다. [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=OjNbBOjcLRk)는 John Kemnetz 님과 함께  VS Code의 C# extension에 대해서 알아보도록 하겠습니다.  On.NET 최초로 이번 주는 몇가지 데모를 포함해서 진행하겠습니다.

### 금주의 프로젝트 - Foundatio
Foundatio 는 느슨한 결합을 가지고 있는 분산 어플리케이션을 위한 오픈 소스 빌딩 블록 셋트입니다. 이 빌딩 블록은 분산 어플리케이션에서 많이 쓰이는 캐싱작업은 물론이고 큐, 병렬작업 시 데이터 잠금 관리, 메시징 작업, 작업(job), 파일 접근, metrics, 그리고 로깅까지 많은 기능의 인터페이스를 포함하고 있습니다. 제공되는 모든 인터페이스들은 인메모리(in-memory) 형태의 데이터 구조를 가지며 레디스(Redis) 라이브러리와 Azure 를 이용하여 구현되었습니다. 

* [Foundatio](https://github.com/exceptionless/Foundatio)

아래는 Foundatio 를 이용해서 enqueue /dequeue 작업을 하는 예제입니다.

### 금주의 컨트롤 - Telerik’s ListView for UWP

Telerik 의 UWP 용 ListView 컨트롤인 RadListView 는 리스트를 사용하는 곳에서 다양하게 사용될 수 있는 가상화된 리스트 컴포넌트 입니다. 애플리케이션 개발에 필요한 기능인 데이터 가상화, 애니메이션, 그룹핑, 정렬, 필터링등의 다양한 기능도 포함하고 있습니다.

* [Telerik’s ListView control for UWP](http://docs.telerik.com/windows-universal/controls/radlistview/listview-overview)

image

### .NET 소식
* [On the efficiency of ValueTask](https://blog.i3arnon.com/2015/11/30/valuetask/) : Bar Arnon 이 실제로 적용하기전 검증해 보는 목적으로 만들어진 .NET Core 용 라이브러리인 [corefxlab](https://github.com/dotnet/corefxlab) 에 포함된 ValueTask<T> 를 설명했습니다. ValueTask<T> 를 이용하면 메모리 할당을 줄일 수 있을 뿐만 아니라 가비지 컬렉션의 오버해드 또한 감소시키는 효과를 가져옵니다. 

* [Parallelism on a Single Core – SIMD with C#](http://instil.co/2016/03/21/parallelism-on-a-single-core-simd-with-c/) : Eoin Mullan 이 SIMD(Single Instruction Multiple Data) 무엇인지 소개하고, .NET 개발자들이 이를 이용하여 성능을 향상시키는 방법을 살펴봅니다. 또한 SMID 를 이용하는 C# 코드 패턴도 함께 공유했습니다. 

* [Why Microsoft Open Source (podcast)](http://developer.telerik.com/topics/web-development/microsoft-open-source/) : Matt Millican 이 마이크로소프트의 오픈소스 전략과 앞으로의 방향성에 대해 이야기 한 내용이 podcast 로 공유되었습니다.

* [Cross-Platform Messaging for iOS, Android, and Windows](https://blog.xamarin.com/cross-platform-messaging-for-ios-android-and-windows/) : Pierce Boggan 이 Xamarin 및 윈도우 용 라이브러리를 소개합니다. 이를 이용해서 SMS 문자 보내기, 전화걸기, 이메일 보내기와 같은 기능 구현을 할 수 있는 멀티 플렛폼(iOS, Android, and Windows) Messaging Plugin의 사용 방법을 xamarin 개발자 블로그에 공유했습니다. 

* [How to create a multi architecture NuGet Package from a UWP class library](http://msicc.net/?p=4442) : Marco Siccardi 이 UWP(Universal Windows Platform) 클래스 라이브러리 NuGet 패키지 생성 방법을 각각의 단계별로 설명한 글을 자신의 블로그에 공유했습니다.

### ASP.NET 소식
* [Creating Step-wise Forms with ASP.NET MVC and Kendo UI](http://developer.telerik.com/featured/step-wise-forms-with-asp-net-mvc-and-kendo-ui/) : Ed Charbeneaurk 이 Kendo UI 와 ASP.NET MVC 용 Telerik UI 를 이용하여 step-wise 형식으로 복잡한 프로세스를 간단히 구현하는 방법을 소개합니다. 

* [Custom Model Binder in ASP.NET MVC](http://www.dotnetcurry.com/aspnet-mvc/1261/custom-model-binder-aspnet-mvc) : Mahesh Sabni 이 ASP.NET MVC 모델의 요청에 따라 데이터와 매핑할 수 있도록 메카니즘을 제공하는 Custom Model Binder 의 구현 방법을 소개했습니다.

* [Dependency Injection Conditional Registration in ASP.NET Core](http://www.elanderson.net/2016/03/dependency-injection-conditional-registration-in-asp-net-core/) : Eric L. Anderson 이 ASP.NET Core 에서 의존성주입(Dependency Injection)의 조건부 등록 방법을 자신의 블로그에 공유했습니다.

* [Social TagHelpers for ASP.NET Core](http://rehansaeed.com/social-taghelpers-for-asp-net-core/) : Muhammad Rehan Saeed 가 ASP.NET Core 에서 Facebook, Twitter, Google+, Pintrest 등의 사이트에서 페이지 공유시 사용되는 메타 태그에 대한 글을 공유했습니다.

* Subresource Integrity TagHelper Using ASP.NET Core [part 1](http://rehansaeed.com/subresource-integrity-taghelper-using-asp-net-core/) and [part 2](http://rehansaeed.com/subresource-integrity-taghelper-using-asp-net-core-part-2/) : Muhammad Rehan Saeed 가 ASP.NET Core 에서 하위 리소스 무결성(SRI, Subsource Integrity) 을 보장하기 위한 TagHelper 의 사용방법을 part 1과 part 2 로 나누어 설명했습니다.

* [Structured logging with Serilog in ASP.NET Core (video)](http://aspnetmonsters.com/2016/03/monsters-weekly%5Cep17/) : The ASP.NET Monsters 사이트에서 ASP.NET Core 에서 구조적으로 정리된 로그를 기록 하는 방법을 소개했습니다.

### F# 소식
* [F#, Azure, and the Web](https://www.youtube.com/watch?v=DZLSkWHLFII) : Isaac Abraham 이 F# 을 웹 프로그래밍과 클라우드에 이용하는 것을 유튜브에 공유했습니다.

* [Creating Visual Studio Code Plugins with F# and Fable](http://kcieslak.io/Creating-VS-Code-plugins-with-F-and-Fable/) : Krzysztof Cieslak 이 F# 과 Fable 을 이용하여 Visual Studio Code 용 플러그인을 만드는 방법을 소개했습니다. 

* [Kaggle Home Depot Competition Notes: Features](http://brandewinder.com/2016/03/26/kaggle-home-depot-features/) : Mathias Brandewinder 가 Kaggle 사이트의 Home Depot 문제해결에 참여했던 경험을 공유했습니다. (Kaggle 사이트는 일종의 문제해결경쟁 사이트로 Kaggle 회원사가 문제 해결을 요청하면 Kaggle 이 문제의 해결방법을 대회로 진행합니다. 대회 우승자에게는 일정의 상금과 경우 따라서는 라이선스 권한도 가지게 됩니다.)

* [Property-Based Testing in the Real World – Or How I Made My Package Manager Suck Less](http://www.navision-blog.de/blog/2016/03/21/property-based-testing-in-the-real-world/) : Steffen Forkmann 가 .NET/mono 의존성 관리 도구인 Paket 에서 버그를 발견하고 이 오류를 수정하면서 얻은 경험을 공유했습니다.

* [Sentiment Analysis in F#](https://automatagears.com/articles/sentiment-analysis-in-fsharp/) : Stephen Ireland 이 F# 에서 자연어 분석 도구인 [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) 를 이용하여 감정을 분석하는 방법을 공유했습니다.

* [History and Philosophy of Types](https://www.youtube.com/watch?v=ITIsxWqduE4) : Tomas Petricek 이 Lambda Days 2016 컨퍼런스에서 타입의 역사와 철학에 대해 발표했던 내용이 유튜브에 공유되었습니다.

* [A Brief History of Programming Languages](https://www.youtube.com/watch?v=3Z27n_ReTI8) : Andrea Magnorsky 가 Lambda Days 2016 컨퍼런스에서 프로그래밍 언어의 역사에 대해 발표한 내용이 유튜브에 공유되었습니다.
