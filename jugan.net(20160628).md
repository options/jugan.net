### On.NET 소식
[지난 On.NET 인터뷰]](https://www.youtube.com/watch?v=ZppqEMegCAA)에서는 Jeremy Kuhne를 모시고 .NET 에서 길이가 긴 경로를 지원하는 방식에 대해 이야기 나누어 보았습니다

[이번 On.NET 인터뷰]에서는 Scott Hunter를 모시고  .NET Core 1.0 release 특집으로 구성 할 예정입니다. 언제나 그렇듯이 궁금한 점은 방송중 실시간으로 직접 질문하실 수도 있습니다.  

### 금주의 패키지- MyTested.AspNetCore.Mvc – Fluent testing framework for ASP.NET Core MVC
기본적으로 ASP.NET MVC가 테스트 가능하도록 디자인되었지만 그럼에도 불구하고 라우팅과 컨트롤러의 테스트를 좀더 효과적으로 할 수 있도록 도와주는 라이브러리가 있다면 도움이 될 것입니다. 
MyTested.AspNetCore 라이브러리는 이같은 테스트코드를 쉽고 재미있게 작성할 수 있도록 도와줄 수 있는 테스트 라이브러리입니다.

아래의 코드는 MyTested.AspNetCore 라이브러리를 이용해서 라우트를 호출하고 컨트롤러가 올바른 모델과 함께 정상적으로 동작하는지 확인하는 테스트 코드입니다.

//코드

그리고 아래는 컨트롤러 동작을 확인하는 테스트 코드입니다.

//코드

### 금주의 Xamarin 애플리케이션 - ParentLove

ParentLove는 초보맘을 위한 iOS, Android, Windows Phone용 육아 어플리케이션입니다. 모유 수유 시간, 분유·이유식 시간, 기저귀 교체 시간, 수면 시간등 아기에 대한 모든 것을 관리할 수 있으며 Xamarin을 기반으로 만들어 졌습니다.

//그림

## .NET 소식
* Announcing .NET Core 1.0 : Rich Lander가  .NET Core 1.0의 릴리즈 소식과 관련 정보를 공유하였습니다. 
* Wired: Microsoft Says It’s in Love With Linux. Now It’s Finally Proving It : Klint Finley이 마이크로소프트가 .NET Core 1.0을 릴리즈함으로서 윈도우뿐 아니라  Linux와 Max OS X 에도 .NET 을 지원한다는 소식을 공유하였습니다.
* Ars Technica: .NET Core 1.0 released, now officially supported by Red Hat : Peter Bright가  .NET Core 1.0 릴리즈 뉴스와 공식적으로 Red Hat 을 지원한다는 소식을 공유했습니다.
* Reactive and Interactive Extensions for .NET 3.0 : Oren Novotny이 이벤트 기반 비동기 라이브러리 오픈 소스인 Reactive and Interactive Extensions의 버전 3.0 릴리즈 식과 .NET Platform Standard 1.0 을 지원한다는 소식을 공유했습니다.
* NDepend – the king of code metrics : Piotr Gankiewicz이 코드분석 툴 NDepend를 소개하였습니다.
* Portable- is dead, long live NetStandard : Oren Novotny이 .NET Platform Standard 1.0이 발표됨으로써 향후 크로스 플랫폼으로서의 닷넷의 의미와 이로인해 기존 PCL(Portable Class Library)의 개발은 더 이상 많지 않을것이라는 정보를  공유주었습니다.
* More on Inking with Wet Ink & Custom Rulers : Mike Taulty가 잉크 프로그램 구현방법을 공유해 주었습니다.

### ASP.NET 소식
* Announcing ASP.NET Core 1.0 : Jeffrey T. Fritz가 ASP.NET Core 1.0의 릴리즈 소식과 관련 정보를 공유하였습니다. 
* Adding a Custom Inline Route Constraint in ASP.NET Core 1.0 : Scott Hanselman이  ASP.NET Core 1.0 환경에서 사용자 정의 라우팅 조건을 추가하는 방법을 공유했습니다.
* Upgrading to ASP.NET Core RTM from RC2 : Rick Strahl이 ASP.NET Core RC2 프로젝트를 RTM 버전으로 업그레이드하는 방법을 가이드해주였습니다.
* Reloading strongly typed Options on file changes in ASP.NET Core RC2 : Andrew Lock이 ASP.NET Core RC2의 웹 어플리케이션 configuration 파일이 수정되어 다시 로드될경우 사용할 수 있는 strongly typed Options 기능을 소개했습니다.
* Building REST APIs using ASP.NET Core and Entity Framework Core : Christos Sakell이 Entity Framework Core와 ASP.NET Core를 이용한 REST API의 구현하는 방법을 공유하였습니다.
* Basics of Middleware in ASP NET Core (video) : ProCoder가 ASP NET Core의 Middleware 기능을 공유해주었습니다.
* Cross Platform Time Zone Handling for ASP.NET Core by Joe Audette가 ASP.NET Core에서 Cross Platform환경에서 시간/닐짜관련 Time Zone 처리에 대한 이슈 및 해결방법을 공유했습니다.

### F# 소식
* Understanding Parser Combinators: a Deep Dive, : Scott Wlaschin이 F#을 이용한 Parser Combinator의 구현 방법을 공유하였습니다.
* Three is a crowd – Actor based, : Frank Joppe이 Akka.Net 세미나를 진행중 C# 데모 "Three is a crowd"를 F# 버전으로 전환하여 발표한 경험을 공유하였습니다.
* Patterns and Practices for Real-World, Event-Driven Microservices, : Rachel Reese가 F#을 이용한 쇼핑몰 개발 사례인 Jet.com 소개와 개발 경험을 공유했습니다.
* Fsharp.Interop.ComProvider – F# type provider for COM interop :  닷넷의 TypeLibConverter 클래스를 이용한 F#용 COM interop type provider 구현 오픈 소스 프로젝트를 소개했습니다.
* F# gotchas for C# developers : Daniel Lazarenko가 C# 개발자를 대상으로 F#언어를 소개해주었습니다.
* F# Implementation of The Elm Architecture : Anthony Lloyd이 F#으로 "The Elm Architecture" 패턴을 구현 하는 방법을 소개했습니다.

### Xamarin 소식
* Adding Facial Recognition to Your Mobile Apps : Pierce Boggan이 모바일 어플에 안면인식 기능을 추가하는 방법을 소개하였습니다.
* Using ModernHttpClient with Azure Mobile Apps : Adrian Hall가 Azure Mobile App에서 ModernHttpClient을 이용하는 방법을 소개하였습니다.
* Xamarin DevOps with VSTS (series) : Richard Woollcott가 Xamarin개발 프로젝트에서 VSTS를 이용한 데브옵스(DevOps) 방법을 소개하였습니다.
* Xamarin Technology Stack, Merged Dictionaries with Xamarin Forms, App Discovery and Deep Linking Series, and Contributing to Xamarin Forms : Adam Pedley이 Xamarin의 다양한 정보를 공유해 주었습니다.  Xamarin 전체적인 기술 스택, Xamarin에서 Merged Dictionaries 사용 방법, App Discovery(사용자에게 쉽게 어플을 효과적으로 노출시기는 방법 )와 Deep Linking Series(어플의 특정 페이지를 바로 실행시기는 방법), 그리고 자신이  Xamarin Forms 오픈소스 프로젝에 PR(Pull Request) 함으로서 참여하게 된 소식등을 전해주었습니다.



//이사님 소개
