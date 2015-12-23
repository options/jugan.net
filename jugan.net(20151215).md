이번 주 .NET 팀의 [팀 블로그](http://blogs.msdn.com/b/dotnet/archive/2015/12/15/the-week-in-net-12-15-2015.aspx)에 한국에서 진행 중인 주간닷넷이 소개되었습니다. 
여러분의 많은 관심과 성원 덕분이라고 생각합니다. 감사합니다.

닷넷 관련 이벤트와 토픽을 매주 생생하게 전해드릴 수 있도록 [유튜브](https://www.youtube.com/)에 [On.NET](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw) 채널을 새롭게 개설했습니다. 첫번째 초대 손님으로 [Miguel de Icaza](https://en.wikipedia.org/wiki/Miguel_de_Icaza)를 모셨는데요. 국내에도 이미 모노 플랫폼의 창시자, [Xamarin](https://xamarin.com/) 회사의 창립자로 잘 알려진 분이기도 합니다. 이 분은 또한 Gnome의 창시자이며 MIT에서 1999년 올해의 혁신(Innovator of the Year 1999)상과 프리 소프트웨어 재단(Free Software)의 FSF 상을 수상하였으며, 심지어 타임(Time)지가 선정한 21세기 100 대 혁신가에 뽑히기도 했습니다. 알고 보니 정말 대단한 분이군요.

매주 나오게 될 On.NET 비디오에 관심 있다면 [채널 가입](https://www.youtube.com/channel/UCvtT19MZW8dq5Wwfu6B0oxw)을 통해 향후 새로운 동영상이 업데이트될 때마다 알림을 받을 수 있습니다.

여러분들의 다양한 의견을 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분들과 공유하도록 하겠습니다.

### 금주의 패키지 #1 - MBrace

MBrace 패키지는 일반적인 라이브러리 이상의 특징을 가지고 있습니다. 바로 F#을 위한 DSL(Domain-Specific Language: 도메인 특정 언어)라는 점인데요. 언어 자체에 클라우드를 위한 프로그래밍 환경을 통합하고 있다는 의미에서 패키지의 이름을 "클라우드를 포용한다."라는 의미의 "{em} brace the cloud"에서 따왔다고 합니다.

* [MBrace](http://mbrace.io/)

다음은 MBrace를 이용해서 클라우드 환경에 있는 큐(Queue)로부터 데이터를 가져오는 예제 코드입니다.

<section>
{{MBraceQueue.fs}} <script src="https://gist.github.com/bleroy/926452c406d2fcff327a.js"></script>
</section>

[Using Could Queues](http://mbrace.io/starterkit/HandsOnTutorial/8-using-cloud-queues.html)를 통해 이와 관련된 다양한 예제를 살펴 보실 수 있습니다.

### 금주의 패키지 #2 - Humanizer

이번주에는 [Dannief](https://gist.github.com/dannief)가 알려주신 Humanizer 패키지를 소개해 드리겠습니다.

* [Humanizer](https://github.com/Humanizr/Humanizer) 

이 패키지는 자연어 처리 시에 흔히 사용되는 기법들을 손쉽게 활용할 수 있도록 문자열 조작 메서드를 제공합니다. 

예를 들어, 다음의 코드는 개별 단어의 구성을 고려하여 부분 문자열을 취하는 Truncate 메서드의 사용법을 보여줍니다.

"Long text to truncate".Truncate(10)

이 코드의 반환 결과는 "Long text…"입니다. 

다음의 예제를 실행 해 보신다면, 이 패키지의 이름이 왜 Humanizer라는 이름을 갖게 되었는지 쉽게 짐작할 수 있을 것입니다.

<section>
{{HumanizerCollectionSample.cs}} <script src="https://gist.github.com/bleroy/66c03b69e5678376810c.js"></script>
</section>

### .NET 소식

* [Why .NET?](http://engineering.gopangea.com/2015/12/10/why-dot-net.html) : Pangea사의 Omar Khudeira는 이 글을 통해서 자사의 주요 개발 플랫폼으로 닷넷을 도입한 이유를 소개하였습니다.
* 며칠 전에 마이크로소프트 직원인 Ron Petrusha는 [The .NET Journey: Recapping the last year](http://blogs.msdn.com/b/visualstudio/archive/2015/12/10/the-net-journey-recapping-the-last-year.aspx) 글을 통해서 닷넷의 오픈 소스화 발표 이후 지난 1년 간의 회고록을 공개했습니다. 이에 대해 Matt Warren은 외부 개발자의 관점에서 바라본 변화를 [Open Source .NET – 1 year later](http://mattwarren.org/2015/12/08/open-source-net-1-year-later/)라는 글로 회답했습니다.
* [Support Ending for the .NET Framework 4, 4.5 and 4.5.1](http://blogs.msdn.com/b/dotnet/archive/2015/12/09/support-ending-for-the-net-framework-4-4-5-and-4-5-1.aspx) : Stacey Haffner는 닷넷 프레임워크 4, 4.5, 4.5.1 지원 종료가 가지는 의미에 대해 완벽히 정리했습니다. (참고로, 3.5, 4.5.2, 4.6, 4.6.1 버전은 계속 지원됩니다.)
* [Calling the Azure ARM API using plain REST](http://blog.davidebbo.com/2015/12/calling-arm-using-plain-rest.html) : David Ebbo는 ARM(Azure Resource Manager) API를 REST 방식으로 호출하는 방식에 대해 설명한 글을 공유했습니다.
* [The dedoublifier 1부](http://ericlippert.com/2015/11/30/the-dedoublifier-part-one/), [2부](http://ericlippert.com/2015/12/03/the-dedoublifier-part-two/), [3부](http://ericlippert.com/2015/12/07/the-dedoublifier-part-three/), [4부](http://ericlippert.com/2015/12/10/the-dedoublifier-part-four/) : Eric Lippert는 임의 정밀도(arbitrary precision)를 가진 형식에 관한 글을 공유했습니다.

### ASP.NET 5 소식

* [Building ASP.NET MVC 6 & Entity Framework 7 application using ASP.NET 5 RC](http://www.dotnetcurry.com/aspnet-mvc/1215/building-aspnet-mvc-6-entity-framework-7-app-using-aspnet-5) : Mahesh Sabnis는 ASP.NET 5 RC를 이용해 ASP.NET MVC 6과 Entity Framework 7을 사용하는 웹 응용 프로그램을 어떻게 제작할 수 있는지 공유했습니다.
* [ASP.NET 5 Web API: Faking It While Making It](http://dotnetliberty.com/index.php/2015/12/07/asp-net-5-web-api-faking-it-while-making-it/) : Armen Shimoon은 Bob Martin의 "Deferring Decisions" 패턴을 ASP.NET 5 Web API에 어떻게 적용했는지를 설명하고 있습니다.


### F# 소식

* [박사 학위가 필요없는 F#](https://medium.com/@jamiedixon/progressive-f-tutorials-london-2015-795d76c027da#.67vl10l5w) : Jamie Dixon은 F# 언어를 배우는 데 있어 박사 학위가 필요하지 않음을 F# 교육 과정에 참여한 경험담을 통해 소개하고 있습니다.
* [Disinherited Types](http://trelford.com/blog/post/Disinherited.aspx), [MSDNify Types](http://trelford.com/blog/post/MSDNify.aspx) : Phillip Trelford는 F#의 Type Provider를 이용해 인텔리센스를 보다 더 잘 사용하는 방법에 대해 2개의 흥미로운 글을 공유했습니다.

다음은 F# 커뮤니티에 공유된 글입니다.

* Isaac Abraham의 [F#, .NET and the Open Source situation](https://cockneycoder.wordpress.com/2015/12/08/f-net-and-the-open-source-situation/)
* Jonathan Wood의 [A Quick Look at F# In Visual Studio Code](http://www.wintellect.com/devcenter/jwood/a-quick-look-at-f-in-visual-studio-code)
* Reed Copsey, Jr의 [Christmas Trees in WPF using FSharp.ViewModule](http://reedcopsey.com/2015/12/09/christmas-trees-in-wpf-using-fsharp-viewmodule/)
* Peter Bayne의 [The trips and traps of creating a Generative Type Provider in F#](https://medium.com/@haumohio/the-trips-and-traps-of-creating-a-generative-type-provider-in-f-75162d99622c#.7saqnv2tb)
* Daniel Egloff의 [Algo Trading with F# and GPUs](http://blog.quantalea.com/?p=8391)
* @TeaDrivenDev의 [Making Busy Progress in F#](http://teadrivendev.github.io/2015/12/11/making-progress-fsharp/)
* Reid Evans의 [Providing Value with Trivial Abstraction in F#](http://reidev275.azurewebsites.net/providing-value-with-trivial-abstraction-in-f/)
* Eriawan Kusumawardho의 [What’s new in F# 4.0 in Visual Studio 2015](http://fsharpmonologue.blogspot.co.id/2015/12/whats-new-in-f-40-in-visual-studio-2015.html)
* Riccardo Terrell의 [Solving the Santa Claus Problem in F#](http://www.rickyterrell.com/?p=68)
* @lenadroid의 [Learn the machine!](https://lenadroid.github.io/posts/machine-learning-fsharp-accorddotnet.html)
