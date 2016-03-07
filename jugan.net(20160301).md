이번 주에는 Xamarion 의 새로운 2D 그래픽 API 인 SkiaShar 라이브러리를 소개합니다. 완성도있는 문서 자동화를 도와주는 도구인 Docfx 에 대한 소식도 눈에 뛰는군요. 지난 호를 살펴보시려면 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 방문해 보시기 바랍니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)나 [주간닷넷 페이지](https://www.facebook.com/jugan.net/)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식
[지난번 On.NET 동영상 인터뷰](https://www.youtube.com/watch?v=WuqrfuJLbgk)는 마이크로소프트의 Principal Program Manager 이신 Scott Hanselman 을 모시고 이야기 나누었습니다. [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=4DJWQP2Uxps)는 Rachel Reese 를 모시고 F# 을 이용하여 백앤드를 개발하고 있는 스타트업인 Jet.com 과 F# 에 대해서 이야기 나누었습니다.  

### 금주의 패키지 – SkiaSharp
Xamarin 이 구글의 그래픽 엔진인 Skia 라이브러리를 기반으로한 새로운 2D 그래픽 API 인 SkiaShar 를 발표했습니다. Skia 라이브러리는 Chrome, Firefox, 그리고 Android 의 그래픽 엔진입니다. Skia 라이브러리 기반의 SkiaSharp 은 이식성이 뛰어난 portable 라이브러리이며 OS X, Android, iOS, Mono, 그리고 .NET Framework 을 지원합니다.

<section>
{{SkiaSharp.cs}}<script src="https://gist.github.com/bleroy/c11d7cb37885d3ea39c1.js"></script>
</section>


### 금주의 툴 – Docfx
개발자들을 위해 .NET 은 초기버전부터 XML 주석을 이용한 문서 자동화 기능을 제공해왔습니다. XML 주석은 클레스 정의서와 같은 프로젝트 문서 산출물이나 개발자를 위한 웹 사이트를 자동으로 만들어 주는데 쓰이기도 합니다. 그러나 자동화된 문서의 품질은 전반적으로 뛰어나지 않습니다. 하지만 Docfx 툴을 이용하여 좀 더 완성도 있는 문서자동화 작업을 할 수 있습니다. Docfx 는 간단하면서 강력한 마크업언어인 [Markdown](http://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html) 과 [YAML](http://dotnet.github.io/docfx/spec/metadata_format_spec.html#3-work-with-metadata-in-markdown-) 을 사용합니다. 이는 [cross-reference](http://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#cross-reference) 를 가능하게 합니다. 또한 [문서에 예제코드를 포함](http://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#code-snippet)할 수 있게 함으로서 사용자들이 쉽고 정확하게 코드의 사용법을 익힐 수 있습니다.

* [Docfx](http://dotnet.github.io/docfx/) 

[그림]

### .NET 소식
* [Scott Guthrie welcomes the Xamarin team to Microsoft](https://weblogs.asp.net/scottgu/welcoming-the-xamarin-team-to-microsoft) & [Nat Friedman gives the Xamarin point of view](https://blog.xamarin.com/a-xamarin-microsoft-future) : Scott Guthrie 가 Xamarin 의 마이크로소프트 합류를 축하했습니다. Xamarin 의 Nat Friedman 는 Xamarin 과 마이크로소프트의 미래에 대한 생각을 공유했습니다.
* [StackOverflow, the architecture 2016 edition](http://nickcraver.com/blog/2016/02/17/stack-overflow-the-architecture-2016-edition/) : Nick Craver 가 Stack Overflow 사이트의 최신 사용량 통계와 2016년의 아키텍처를 공유했습니다. 2013년에 비해 처리량이 증가했음에도 불구하고 성능이 향상된 ASP.NET 에 대해 언급했습니다.
* [Saying “Goodbye” to DNX and “Hello!” to the .NET Core CLI (video)](https://vimeo.com/153212604) : Damian Edwards 와 David Fowler 가 NDC 콘퍼런스에서 .NET Core CLI 를 소개했습니다. 
* [Introduction to Microsoft.Data.Sqlite](http://www.c-sharpcorner.com/UploadFile/ranjancse/net-co-introduction-to-microsoft-data-sqlite/) : Ranjan Dailata 가 .NET Core 용 오픈소스 라이브러리인 Sqlite 를 소개했습니다.
* [New Toolchain For .NET – Dotnet CLI](http://bleedingnedge.com/2016/02/04/new-toolchain-dotnet-cli/) : Paweł Grudzień 가 .NET 의 새로운 툴 체인을 소개했습니다. 
* [Plugging the CoreCLR’s JIT into CPython](https://github.com/Microsoft/Pyjion) : Cpyton 에 사용될수있는 CoreCLR 기반의 JIT 플러그인을 소개합니다.  
* 멀티쓰레드에 관심있는 개발자라면 누구나 한번은 읽어봐야하는 Vance Morrison 의 [What Every Dev Must Know About Multithreaded Apps](http://blogs.msdn.com/b/vancem/archive/2016/02/27/encode-presentation-what-every-dev-must-know-about-multithreaded-apps.aspx) 와 [Understand the Impact of Low-Lock Techniques in Multithreaded Apps](http://blogs.msdn.com/b/vancem/archive/2016/02/27/encore-presentation-understand-the-impact-of-low-lock-techniques-in-multithreaded-apps.aspx) 라는 글이 그의 블로그에 pdf 버전으로 공유되었습니다. 
* [NBench testing garbage collection](http://www.dotnetalgorithms.com/2016/02/nbench-testing-garbage-collection/) : Andrea Angella 가 Nbench 를 이용한 Garbage collection 테스트 방법을 공유했습니다.
* [ConditionalWeakTable and dynamic properties in .NET 4+](https://www.simple-talk.com/blogs/2016/02/26/conditionalweaktable-and-dynamic-properties-in-net-4/) : Chris Whitworth 가 .NET Framework 4.0 에서 등장한 ConditionalWeakTable<TKey, TValue> 클래스에 대해 소개합니다. 
* Ayende Rahien가 비동기프로그램 개발에 도움이 되는 [Fun async tricks for getting better performance](https://ayende.com/blog/173473/fun-async-tricks-for-getting-better-performance) 과 의존성 관리에 대한 내용을 담은 [Dependency management in a crisis](https://ayende.com/blog/173377/dependencies-management-in-a-crisis?Key=1d4d9b27-fc86-451d-bd4f-2da16b5cfad3) 문서를 자신의 블로그에 공유했습니다.

### ASP.NET 소식
* David Paquette, James Chambers, Simon Timms 가 Channel 9 의  ASP.NET Monsters 채널에서 [ASP.NET Core 를 이용한 애플리케이션 개발 방법](https://channel9.msdn.com/Series/aspnetmonsters?sort=recent#tab_sortBy_recent) 시리즈를 연재합니다.
* [Keeping POST and GET Separated](https://www.simple-talk.com/dotnet/asp.net/keeping-post-and-get-separated/) : Dino Esposito 가 HTTP 의 POST 와 GET 을 분리하는 PRG(Post-Redirect-Get) 패턴에 관한 글을 자신의 블로그에 공유했습니다.
* [Using Let’s Encrypt with IIS on Windows](http://weblog.west-wind.com/posts/2016/Feb/22/Using-Lets-Encrypt-with-IIS-on-Windows) : Rick Strahl 가 오픈소스 인증서인 [Let's Encrypt](https://letsencrypt.org/) 를 소개합니다. 

### F# 소식
* [fsharpConf 2016](http://fsharpconf.com/) is live on Channel 9 on March 4th : F# 컨퍼런스인 fsharpConf 2016가 3월 4일 Channel 9 에서 라이브 중계됩니다. 지금 발표자들을 확인해 보세요!
* [F# on the Desktop](https://www.youtube.com/watch?v=T8R-g_E1VFg) : Phil Trelford 가 F# 을 이용한 데스크탑 애플리케이션 개발 방법을 대한 내용을 담은 비디오를 공유했습니다.
* [Type Providers from the Ground Up](https://www.youtube.com/watch?v=pXT0li6zxKQ) : Michael Newton 가 Type Providers 개발 방법에 대한 내용을 담은 비디오를 공유했습니다.
* [.NET: A Look Through F# Lenses](https://www.pluralsight.com/blog/software-development/tutorial-f-sharp?utm_medium=affiliate&utm_source=314743) : Jacqueline Homan 가 F# 을 통해 바라본 .NET Framework 를 소개합니다. 
* [Converting a DSL to Executable F# Code On-the-Fly](http://brandewinder.com/2016/02/20/converting-dsl-to-fsharp-code-part-1/) : Mathias Brandewinder 가 DSL(domain-specific language) 로 작성한 코드를 F# 실행코드로 변환하는 방법을 블로그에 소개했습니다.
* [Double Cone Design](https://medium.com/@bryanedds/double-cone-design-ddc8e5f23432#.yekr1a8zw) : Bryan Edds 가 Double Cone Design 방식을 적용하여 소프트웨어를 설계하는 방법을 소개했습니다.  

