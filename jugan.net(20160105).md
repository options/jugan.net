여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

이번 주 [On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw)는 [Mads Torgersen과 주로 C#에 대해 이야기](https://www.youtube.com/watch?v=pwdxfY2Y2Ow)하는 시간을 가질 예정입니다. (.... 한국 발생 시점에는 이미 끝났을 예정이어서... 마무리 부탁드립니다.)


### 금주의 패키지 #1 – ReactiveUI

ReactiveUI는 [Reactive Extensions](http://reactivex.io/) for .NET을 기반으로 테스트 가능한 사용자 인터페이스를 만드는 데 사용합니다. 

* [ReactiveUI](http://reactiveui.net/)

기본적으로 WPF, 윈도우 폼과 UWP 등 윈도우 운영체제의 다양한 UI 형식을 지원하며 Xamarin과의 호환으로 인해 Xamarin.iOS, Xamarin.Android, Xamarin.Mac, Xamarin Forms에서도 사용할 수 있습니다. 

활용예를 한번 볼까요? 예를 들어, 텍스트 상자에 사용자가 값을 입력하면 Enter 키를 치지 않아도 검색 서비스에 HTTP 쿼리를 전송해 자동으로 검색 결과를 보여주도록 구현하는 경우가 있습니다. 물론 사용자가 텍스트를 입력하는 매 순간마다 발생시키기 보단 1초 정도의 여유를 두고 그 시간에 변경이 없다면, 즉 사용자가 입력을 완전히 마쳤다고 판단이 되면 검색 쿼리를 발생시켜야 하는데요. 바로 이것을 ReactiveUI로 구현하면 다음과 같은 코드로 작성할 수 있습니다.

<section>
WhenAnyValue(x => x.SearchQuery)
    .Throttle(TimeSpan.FromSeconds(1), RxApp.MainThreadScheduler)
    .InvokeCommand(this, x => x.Search);
</section>

위의 예제 코드는 [ReactiveUI 사이트](http://reactiveui.net/)의 첫번째 소개 페이지에 실려 있습니다.

ReactiveUI 커뮤니티는 Github를 통해 참여를 기다리고 있습니다.

### 금주의 패키지 #2 – TypedRouting

ASP.NET MVC의 마법같은 라우팅 관련 문자열 용법이 마음에 들지 않는다면 TypedRouting이 적절한 대안으로 고려해 볼 수 있습니다.

* [ReactiveUI](https://github.com/ivaylokenov/AspNet.Mvc.TypedRouting)

다음은 TypedRouting을 이용해 GET 요청을 HomeController.Index(int)로 전달하는 코드입니다.

<section>
routes.Get("MyRoute/{id}", route =>
    route.ToAction<HomeController>(a => a.Index(With.Any<int>())));
</section>

코드에서 보는 바와 같이, Controller와 Action 메서드의 이름과 그 인자 목록까지 제네릭(generic) 구문을 통해 전달함으로써 컴파일 시간에 미리 오류 검사를 할 수 있습니다. 따라서 향후 코드 파일에서 Controller와 Action 메서드의 구문이 바뀌더라도 에러를 쉽게 인식할 수 있습니다.

TypedRouting은 라우팅 기능뿐만 아니라 이를 기반으로 관련 유틸리티 성격의 메서드를 함께 제공하고 있습니다. 가령, 위의 코드에서 정의한 라우팅 정보를 바탕으로 링크도 구성할 수 있습니다.

<section>
urlHelper.Action<HomeController>(c => c.Index(1));
</section>

### 커뮤니티 소식

### .NET 소식

* Fast shared Array, Buffer and Circular Buffer / Ring Buffer for .NET IPC with Memory Mapped Files : 닷넷에서 프로세스 간에 배열, 버퍼, 링 버퍼 자료 구조를 공유할 수 있는 SharedMemory 라이브러리에 대해 Justin Stenning이 소개하고 있습니다. 내부적으로 사용된 IPC 기법은 메모리-맵입니다.
* Having a Look at dotnet CLI Tool and .NET Native Compilation in Linux : 지난 주에는 Scott Hanselman이 "dotnet" 명령행 도구의 사용법을 소개하는 글을 썼었는데요. 이번 주에는 Tugberk Ugurlu가 닷넷 네이티브 컴파일까지 할 수 있는 "dotnet" 도구의 또 다른 사용법을 리눅스 운영체제 상에서 설명하고 있습니다.
* Introducing NBench - an Automated Performance Testing Framework for .NET Applications : 닷넷 응용 프로그램의 자동화된 성능 테스트 프레임워크인 NBench에 대해 Petabridge가 설명하고 있습니다.
* Do One Thing And Do It Well : Mark Rendle이 리눅스에서 닷넷과 Node.js를 사용한 경험을 공유합니다. 아울러 "Azure Storage SDK for .NET" 라이브러리에 대한 개선점과 함께!

### ASP.NET 소식

* Complex Custom Tag Helpers in MVC 6 : 2주 전에 [Marius Schulz가 쓴 사용자 정의 Tag Helpers 글](https://blog.mariusschulz.com/2015/12/14/tag-helpers-in-asp-net-mvc-6)을 기억하시나요? 이번에는 Dave Paquette이 쓴 글을 소개합니다.
* How to unit test ASP.NET MVC 6 ModelState : 단위 테스트 시 ModelState를 검증하는 방법을 Armen Shimoon이 소개합니다.


### F# 소식

* The F# Software Foundation의 Welcome to 2016 - A Call to Action
* Pierre Irrmann의 Visualizing F# Advent Calendar Contributors
* Tamizh Vendan의 Implementing API Gateway in F# Using Rx and Suave
* Tomas Petricek의 Happy New Year 2016 Around the World
