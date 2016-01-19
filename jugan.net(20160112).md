2015년 12월 1일 첫 번째 주간닷넷을 시작으로 어느덧 일곱 번째 주간닷넷입니다. 지속적인 관심을 보내주신 덕분에 주간닷넷의 누적 조회 수가 10,000을 돌파했습니다. 감사합니다. 여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

[지난번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=pwdxfY2Y2Ow)에는 Mads Torgersen을 모시고 C#언어에 관해 이야기 나누는 시간을 가졌습니다. [이번 On.NET 유튜브 동영상 인터뷰](https://www.youtube.com/watch?v=B0yWmVL8hF0)는 [Unity 3D](http://unity3d.com/)팀의 Jonathan Chambers를 모시고 게임 엔진 이야기와 더불어 닷넷을 이용한 iOS, 안드로이드 및 웹 프로그램을 만드는 방법을 이야기할 예정입니다. 

### 금주의 패키지 #1 – JSON.NET 8

과연 JSON.NET에 대한 설명이 필요할까요? 

* [JSON.NET](https://github.com/JamesNK/Newtonsoft.Json)

이미 많은 분이 JSON을 .NET 객체로 직렬화/역직렬화하는 데 사용하는 라이브러리로 알고 계실 것입니다. 최근 James Newton King은 성능향상뿐만 아니라 수많은 버그를 수정한 8.0 버전을 공개했습니다. 다른 라이브러리와 비교했을 때 충분히 속도가 빠름에도 불구하고 James는 성능을 향상하기 위해 메모리 할당을 하지 않는 방식을 제시했습니다. 기존 버전은 버퍼를 필요할 때마다 할당하는 방식이었지만 8.0부터는 버퍼 풀을 사용하는 방법으로 바꾼 것입니다.

<section>
{{JsonNetArrayPool.cs}} <script src="https://gist.github.com/bleroy/784f9c6d439fca8b3812.js"></script>
</section>

버퍼 풀을 사용하는 기능은 아직 실험 단계라서 현재로는 여러분이 직접 IArrayPool 인터페이스를 구현한 풀 관리 클래스를 구현해야 합니다. 그에 관한 예제 코드는 새 버전의 [공지 페이지](http://james.newtonking.com/archive/2015/12/20/json-net-8-0-release-1-allocations-and-bug-fixes)에 실려 있습니다. 이후 버전에서는 IArrayPool을 구현한 클래스가 내장될 예정입니다.

### 금주의 패키지 #2 – Colorful.Console

콘솔 응용 프로그램의 색상이 좀 더 화려해진다면 금상첨화일 것입니다. Colorful.Console은 이런 면에서 닷넷의 기본 제공 클래스인 System.Console을 대체합니다. 

* [Colorful.Console](http://colorfulconsole.com/)

출력 색상을 지정할 수 있는 API뿐만 아니라 심지어 텍스트를 ASCII 그림으로 변환해 주는 기능도 포함하고 있습니다.

<section>
{{ColorfulConsoleAsciiArt.cs}} <script src="https://gist.github.com/bleroy/4f09cf8dc7419cda5ba5.js"></script>
</section>

[이미지](https://camo.githubusercontent.com/ac939db6a00a5639d3c257298dcb87432d83ecff/687474703a2f2f636f6c6f7266756c636f6e736f6c652e636f6d2f696d616765732f61736369695f78322e706e67)

### .NET 소식

* [How to package a portable .NET library targeting .NET Core?](https://stackoverflow.com/questions/34611919/how-to-package-a-portable-net-library-targeting-net-core) : 스택 오버플로에 실린 Q&A 글입니다. 여러분이 만든 닷넷 라이브러리를 .NET Core 및 그 외의 다양한 환경에서 패키징할 수 있는 방법을 소개합니다.
* [Debugging and Profiling in Visual Studio 2015](https://www.simple-talk.com/dotnet/visual-studio/debugging-and-profiling-in-visual-studio-2015/) : Manuel Meyer가 비주얼 스튜디오 2015에 제공되는 디버깅 및 프로파일링 기능을 설명합니다.
* [How open source changed my life](http://blog.tonysneed.com/2015/12/19/how-open-source-changed-my-life/) : Tony Sneed는 오픈 소스에 참여한 경험을 공유했습니다.
* [To base() or not to base(), that is the question](http://codeblog.jonskeet.uk/2016/01/08/to-base-or-not-to-base-that-is-the-question/) : Jon Skeet은 자식 클래스에서 부모 클래스의 기본 생성자를 다루는 방법이 스펙 문서와 다를 수 있음을 지적하고 명시적인 base() 호출의 효과를 설명합니다.
* [Evolution of C#](http://www.kunal-chowdhury.com/2016/01/csharp-basics.html) : Kunal Chowdhury는 C# 1.0부터 6.0까지의 변화를 하나의 표로 정리했습니다.
* [Functional Microservices](http://www.dotnetrocks.com/default.aspx?ShowNum=1240) : [.NET Rocks](http://www.dotnetrocks.com) 운영진은 jet.com의 F#으로 마이크로서비스를 구축한 Rachel Reese의 경험담을 인터뷰했습니다.


### ASP.NET 소식

* [Goodbye child actions, hello view components](http://www.davepaquette.com/archive/2016/01/02/goodbye-child-actions-hello-view-components.aspx) : Dave Paquette이 View Component를 이용해 재사용 가능한 구성요소를 만드는 법을 소개합니다.
* [Best practices for private config data and connection strings in configuration in ASP.NET and Azure](http://www.hanselman.com/blog/BestPracticesForPrivateConfigDataAndConnectionStringsInConfigurationInASPNETAndAzure.aspx) : Scott Hanselman이 Azure 상의 ASP.NET 웹 응용 프로그램에서 연결 문자열과 같은 민감한 내부 데이터를 보관하기 위한 최적의 방법을 소개합니다.
* [Real time translated chat with ASP.NET, Microsoft Translator and IP Messaging](https://www.twilio.com/blog/2015/12/hola-ip-messaging-real-time-translated-chat-with-asp-net-microsoft-translator-and-ip-messaging.html) : Devin Rader는 [Microsoft Translator API](http://www.microsoft.com/en-us/translator/translatorapi.aspx)를 이용해 실시간으로 채팅 메시지를 번역하는 방법을 소개합니다.
* [Building APIs with MVC 6 and OAuth](https://www.youtube.com/watch?v=vqcAVic4Ej0) : Filip Ekberg는 MVC 6과 OAuth를 결합해 API를 서비스하는 방법을 비디오로 만들어 유튜브에 공개했습니다.
* [How to take an ASP.NET MVC web site down for maintenance](https://www.simple-talk.com/dotnet/asp.net/how-to-take-an-asp.net-mvc-web-site-down-for-maintenance/) : Jon smith는 유지 보수를 위해 ASP.NET MVC 웹 사이트 운영을 잠시 중단해야 하는 경우, 처리 방법에 대한 고민과 자신만의 비법을 공유했습니다.
* [Experiments with Entity Framework 7 and ASP.NET MVC 6](http://damienbod.com/2016/01/07/experiments-with-entity-framework-7-and-asp-net-5-mvc-6/) : Damien Bod는 ASP.NET MVC 6와 Entity Framework 7을 함께 사용한 경험을 공유했습니다.  


### F# 소식

* Bryan Hunter의 [Lean and Functional Programming](https://vimeo.com/album/3452190/video/131189623#t=2m04s)
* Pierre Irrmann의 [Visualizing F# Advent Calendar Contributors](http://www.pirrmann.net/visualizing-f-advent-calendar-contributors/)
* Eirik Tsarpalis의 [Reconciling Stack Traces with Computation Expressions](https://eiriktsarpalis.wordpress.com/2015/12/27/reconciling-stacktraces-with-computation-expressions/)
* Craig Stuntz의 [F# Presentations from CodeMash 2016](http://blogs.teamb.com/craigstuntz/2015/11/09/38883/)

