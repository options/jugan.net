2016년에도 어김없이 주간닷넷이 돌아왔습니다. 이번 주에도 흥미로운 패키지들과 유용한 포스트들을 담았습니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

지난 [On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw)에서는 현재 마이크로소프트에서 C# 팀을 이끌고 있는 [Mads Torgersen를 모시고 C#에 대해 이야기](https://www.youtube.com/watch?v=pwdxfY2Y2Ow) 나누는 시간을 가졌습니다. 


### 금주의 패키지 #1 – ReactiveUI

ReactiveUI를 이용하면 .NET 용 [Reactive Extensions](http://reactivex.io/)을 기반으로 미려하고 테스트가 간편한 사용자 인터페이스를 만들 수 있습니다. 

* [ReactiveUI](http://reactiveui.net/)

WPF, 윈도우 폼, UWP 앱과 같이 윈도우 운영체제에서 수행되는 다양한 UI 형식을 지원할 뿐 아니라, Xamarin과도 호환되므로 Xamarin.iOS, Xamarin.Android, Xamarin.Mac, Xamarin Forms에서도 사용할 수 있습니다. 

활용 예를 한번 살펴볼까요? 예를 들어, 검색창에 사용자가 값을 입력하면 Enter 키를 입력하지 않아도 검색 서비스에 HTTP 쿼리를 전송해 자동으로 결과를 보여주어야 하는 경우가 있습니다. 사용자가 텍스트를 입력하는 순간마다 매번 쿼리를 전송하기 보다는 1초 정도의 여유를 두어 사용자가 입력을 완전히 마쳤다고 판단될 때 쿼리를 전송하는 것이 좋습니다. ReactiveUI를 이용하면 다음과 같이 작성하실 수 있습니다.

<section>
{{ReactiveUISearchThrotting.cs}} <script src="https://gist.github.com/bleroy/57b52f0bd91c0f03ca84.js"></script>
</section>

위의 예제 코드는 [ReactiveUI 사이트](http://reactiveui.net/)의 첫 번째 소개 페이지에 실려 있습니다.

ReactiveUI 커뮤니티는 Github를 통해 여러분의 참여를 기다리고 있습니다. [현재의 문제점](https://github.com/reactiveui/ReactiveUI/labels/up-for-grabs)들을 확인하실 수 있고, [초보자를 대상으로 하는 태그](https://github.com/reactiveui/ReactiveUI/labels/first-timers-only)도 있습니다.  

### 금주의 패키지 #2 – TypedRouting

ASP.NET MVC의 마법 같은 라우팅 관련 문자열 용법이 마음에 들지 않는다면 TypedRouting을 대안으로 고려해 볼 수 있습니다.

* [TypedRouting](https://github.com/ivaylokenov/AspNet.Mvc.TypedRouting)

다음은 TypedRouting을 이용해 GET 요청을 HomeController.Index(int)로 전달하는 코드입니다.

<section>
{{TypedRoutingCreateRoute.cs}} <script src="https://gist.github.com/bleroy/5e321b733fffdef0f576.js"></script>
</section>

Controller와 Action 메서드의 이름과 인자 목록까지 제네릭(generic) 구문을 통해 전달되기 때문에 컴파일 타임에 미리 오류 검사가 가능합니다. 따라서 향후 코드에서 Controller와 Action 메서드의 구문이 바뀌더라도 에러를 쉽게 찾을 수 있습니다.

TypedRouting은 라우팅 기능뿐만 아니라 유틸리티 성격의 메서드도 함께 제공합니다. 가령, 위의 코드에서 정의한 라우팅 정보를 바탕으로 링크를 구성할 수도 있습니다.

<section>
{{TypedRoutingGetUrl.cs}} <script src="https://gist.github.com/bleroy/93986659567963cd2a9c.js"></script>
</section>

### .NET 소식

* [Fast shared Array, Buffer and Circular Buffer / Ring Buffer for .NET IPC with Memory Mapped Files](http://spazzarama.com/2015/12/31/fast-shared-array-buffer-and-circular-buffer-ring-buffer-for-dotnet-ipc-with-memory-mapped-files/) : Justin Stenning이 닷넷에서 여러 프로세스 간 배열, 버퍼, 링 버퍼와 같은 자료 구조를 공유할 수 있는 SharedMemory 라이브러리를 소개합니다. 내부적으로 사용된 IPC 기법은 메모리-맵입니다.
* [Having a Look at dotnet CLI Tool and .NET Native Compilation in Linux](http://www.tugberkugurlu.com/archive/having-a-look-at-dotnet-cli-tool-and--net-native-compilation-in-linux) : 지난 주에는 Scott Hanselman이 [명령행 도구(dotnet)](https://github.com/dotnet/cli)의 사용법을 소개하였는데요. 이번 주에는 Tugberk Ugurlu가 [닷넷 네이티브 컴파일까지 가능한 도구(dotnet)](https://github.com/dotnet/cli)의 사용법을 리눅스 운영체제상에서 설명합니다.
* [Introducing NBench - an Automated Performance Testing Framework for .NET Applications](https://petabridge.com/blog/introduction-to-nbench/) : Petabridge가 닷넷 응용 프로그램의 자동화된 성능 테스트 프레임워크인 NBench에 대해 설명합니다.
* [Do One Thing And Do It Well](https://blog.rendle.io/do-one-thing-and-do-it-well/) : Mark Rendle이 리눅스에서 닷넷과 Node.js를 사용해본 경험을 공유합니다. 아울러 "Azure Storage SDK for .NET" 라이브러리에 대한 개선점도 다루고 있습니다. 

### ASP.NET 소식

* [Complex Custom Tag Helpers in MVC 6](http://www.davepaquette.com/archive/2015/12/28/complex-custom-tag-helpers-in-mvc-6.aspx) : 2주 전에 Marius Schulz가 쓴 [사용자 정의 Tag Helpers 글](https://blog.mariusschulz.com/2015/12/14/tag-helpers-in-asp-net-mvc-6)을 기억하시나요? 이번에는 Dave Paquette이 쓴 글을 소개합니다.
* [How to unit test ASP.NET MVC 6 ModelState](http://dotnetliberty.com/index.php/2016/01/04/how-to-unit-test-asp-net-5-mvc-6-modelstate/) : Armen Shimoon이 단위 테스트 시에 ModelState를 검증하는 방법을 소개합니다.
* [Fast ASP.NET 5 Integration Testing with xUnit](http://dotnetliberty.com/index.php/2015/12/31/fast-asp-net-5-integration-testing-with-xunit/) : Armen Shimoon는 또한  Xunit을 이용하여 ASP.NET 5 통합 테스트를 빠르게 수행하는 방법을 소개합니다.


### F# 소식

* The F# Software Foundation의 [Welcome to 2016 - A Call to Action](http://foundation.fsharp.org/call_to_action)
* Pierre Irrmann의 [Visualizing F# Advent Calendar Contributors](http://www.pirrmann.net/visualizing-f-advent-calendar-contributors/)
* Tamizh Vendan의 [Implementing API Gateway in F# Using Rx and Suave](http://blog.tamizhvendan.in/blog/2015/12/29/implementing-api-gateway-in-f-number-using-rx-and-suave/)
* Tomas Petricek의 [Happy New Year 2016 Around the World](http://tomasp.net/blog/2015/happy-new-year-tweets/)
