2015년의 마지막 주간닷넷 소식입니다. 이번으로 벌써 5회차를 맞이하였는데요, 꾸준한 관심과 성원에 감사드립니다. 
언제나처럼 이번 주에도 많은 분들께서 보내주신 링크와 팁을 포함하였습니다. 도움을 주신 모든 분께 감사의 말씀을 드립니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### 금주의 패키지 – ImageProcessor

이미지 처리를 서버 측에서 하는 것이 더 좋을 때가 종종 있습니다. 가령 이미지에 임의로 워터마크(watermark)를 넣는다거나, 섬네일(thumbnail)을 즉석에서 만드는 경우를 들 수 있습니다. 또는 갤러리에 있는 이미지 파일들을 흑백으로 처리해서 보여줘야 할 때도 있는데요. 결국 서버 측에서 동적으로 이미지를 처리해 줄 도구가 필요하게 됩니다. 이러한 경우 서버 측에서 처리하기 떄문에 기본적으로 고속이어야하고, 기왕이면 다중 CPU 코어 자원을 효율적으로 사용할 수 있으면 더 좋습니다.

이런 경우 James South가 만든 ImageProcessor 라이브러리가 해결책이 될 수 있습니다. 오픈 소스인데다 경량화되어 있어 빠르고 간단하며, 멀티 스레딩을 고려한 확장성있는 라이브러리이기 때문입니다. 심지어 .NET Core까지도 지원하고 있습니다. (따라서 윈도우 운영체제의 GDI+에 종속성이 없습니다.)

* [ImageProcessor](http://imageprocessor.org/)

아래의 코드는 JPEG 이미지 파일을 읽어 가로 150 픽셀, 세로 크기는 비율에 맞게 조절하여 별도의 메모리 스트림에 저장하는 방법을 보여줍니다.

<section>
{{ImageProcessorSample.cs}} <script src="https://gist.github.com/bleroy/7c062d39dd1344459d5a.js"></script>
</section>

이 외에도 ImageProcessor가 제공하는 다양한 메서드 목록을 [문서](http://imageprocessor.org/imageprocessor/imagefactory/)를 통해 확인하실 수 있습니다.

### .NET 소식

* [Exploring the new .NET "dotnet" Command Line Interface (CLI)](http://www.hanselman.com/blog/ExploringTheNewNETDotnetCommandLineInterfaceCLI.aspx) : Scott Hanselman이 .NET Core와 함께 새롭게 등장한 명령행 도구([dotnet](https://github.com/dotnet/cli))의 기본적인 사용법을 간략하게 소개합니다.
* [Mono's Cooperative Mode for SGen GC](http://tirania.org/blog/archive/2015/Dec-22.html) : 모노 플랫폼에 새로운 GC 모드가 추가되었습니다. 이로써 모노는 기존의 Preemptive 모드 방식과 함께 2가지 유형의 GC 운영 방식을 지원하게 됩니다. Miguel de Icaza가 이를 소개합니다.
* [Cross Platform Build Automation with VSTS / TFS 2015](https://channel9.msdn.com/Events/APAC-Influencer-Hero-2015/Singapore-Influencer-Showcase/01-Punit-Ganshani-DevOps-Build-Automation-with-VSTS--TFS-2015) : Punit Ganshani가 크로스 플랫폼 환경을 위한 TFS 2015와 비주얼 스튜디오로 빌드 자동화하는 방법에 대해 17분에 걸쳐 설명한 동영상을 채널 9에 올렸습니다. 
* [Cross Platform Build Automation with VSTS / TFS 2015, by Packaging Libraries with NuGet](https://channel9.msdn.com/Events/APAC-Influencer-Hero-2015/Singapore-Influencer-Showcase/01-Punit-Ganshani-Packaging-your-libraries-with-NuGet) : 바로 위에서 소개된 Punit Ganshani가 이번에는 NuGet에 여러분들의 라이브러리를 올리는 방법을 약 33분여의 동영상을 통해 설명합니다.


### ASP.NET 소식

* [Publishing a ASP.NET 5 Web-Application to IIS Locally](http://blogs.msdn.com/b/abhinaba/archive/2015/12/22/publishing-a-asp-net-5-web-application-to-iis-locally.aspx) : Abhinaba Basu가 로컬 IIS 서버에 ASP.NET 5 웹 응용 프로그램을 배포하는 방법을 설명합니다.
* [ASP.NET 5 scoped dependencies](http://dotnetliberty.com/index.php/2015/12/28/asp-net-5-scoped-dependencies/) : Armen Shimoon이 ASP.NET 5에 기본 내장된 DI(Dependency Injection) 기능 중 Scoped 방식에 대해 자세하게 설명합니다.

### F# 소식

* Steffen Forkmann의 [Automatic Re-build and Background Tasks for Suave.io Websites](http://www.navision-blog.de/blog/2015/12/21/adding-background-tasks-to-suave-io-websites/)
* Tomasz Heimowski의 [Property-based Testing XSLT](http://theimowski.com/blog/2015/12-21-property-based-testing-xslt/index.html)
* Mathias Brandewinder의 [Hacking Together @wbfacts, a World Bank Twitter Bot](http://www.clear-lines.com/blog/post/hacking-together-wbfacts-a-World-Bank-Twitter-Bot.aspx)
* Chad Boyer의 [F# Advent Calendar 2015](http://www.cylentware.com/blog/post/F-Advent-Calendar-2015)
* Carsten König의 [Some Fun with Lambda Calculus](http://gettingsharper.de/2015/12/23/f-advent-2015-some-fun-with-lambda-calculus/)
* Troy Kershaw의 [Getting Started with SignalR Using F# and OWIN](http://troykershaw.com/blog/getting-started-with-signalr-fsharp-owin/)
* Matthew Sottile의 [Comparing Trees, Functionally](http://syntacticsalt.com/2015/12/24/comparing-trees-functionally/)
* Craig Stuntz의 [Designing for Problems Too Big to Test](http://blogs.teamb.com/craigstuntz/2015/12/23/38890/)
* Richard Griffiths의 [Monogame Snowflakes](http://soulfiremage.github.io/Advent2015.html)
* Louie Bacaj의 [F# Powered Real-time Dashboard](http://coding.fitness/f-powered-realtime-dashboard/)
* Adam Granicz의 [WebSharper - A Year in Review](http://websharper.com/blog-entry/4665/websharper-a-year-in-review)
* Chris Dobson의 [F#, Minecraft, and a Raspberry Pi](http://www.chrisdobby.com/?p=34)
* Taylor Wood의 [Generating Markov Text from YouTube Comments](http://taylorwood.github.io/2015/12/27/youtube-comment-markov.html)
* Indy Garcia의 [Twitter Local](https://indy9000.github.io/twitter-local.html)

