여러분들의 적극적인 참여를 기다리고 있습니다. 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분과 공유하도록 하겠습니다.

### On.NET 소식

이번 주 [On.NET 유튜브 동영상 인터뷰](...)는 Unity 3D팀의 Jonathan Chambers를 모시고 게임 엔진 이야기와 더불어 닷넷을 이용해 iOS, 안드로이드 및 웹을 대상으로 하는 프로그램을 만드는 방법에 관한 대화를 나눌 예정입니다. (.... 한국 발생 시점에는 이미 끝났을 예정이어서... 마무리 부탁드립니다.)


### 금주의 패키지 #1 – JSON.NET 8

과연 JSON.NET에 대한 설명이 필요할까요? 

* [JSON.NET](https://github.com/JamesNK/Newtonsoft.Json)

이미 많은 분들이 JSON을 .NET 객체로 직렬화/역직렬화하는 데 사용하는 라이브러리임을 알고 계실 것입니다. 최근 James Newton-King은 성능 향상과 함께 수많은 버그를 수정한 8.0 버전을 새롭게 공개했습니다. 그렇지 않아도 다른 라이브러리와 비교해 충분히 빨랐음에도 불구하고 James Newton-King은 더 빠른 성능을 얻기 위해 메모리 할당을 없애는 방법을 채택했습니다. 즉, 기존 버전은 필요할 때마다 버퍼를 할당하는 방식이었지만 8.0부터는 버퍼 풀을 사용하는 방법으로 바꾼 것입니다.

<section>
IList<int> value;

var serializer = new JsonSerializer();
using (var reader = new JsonTextReader(new StringReader(@"[1,2,3,4]")))
{
    // reader will get buffer from array pool
    reader.ArrayPool = JsonArrayPool.Instance;

    value = serializer.Deserialize<IList<int>>(reader);
}
</section>

버퍼 풀을 사용하는 기능은 아직은 실험 단계라서 현재로써는 IArrayPool 인터페이스를 구현한 풀 관리 클래스를 여러분이 직접 구현해 제공해야 합니다. 그에 관한 예제 코드는 새 버전의 [공지 페이지](http://james.newtonking.com/archive/2015/12/20/json-net-8-0-release-1-allocations-and-bug-fixes)에 실려 있습니다. 이후 버전에서는 IArrayPool을 구현한 클래스가 자체 내장될 예정입니다.

### 금주의 패키지 #2 – Colorful.Console

콘솔 응용 프로그램이 색상만 좀더 화려해진다면 금상첨화일 것입니다. Colorful.Console은 이런 면에서 닷넷의 기본 제공 클래스인 System.Console을 대체합니다. 

* [Colorful.Console](http://colorfulconsole.com/)

출력에 관한 색상을 지정할 수 있는 API뿐만 아니라 심지어 텍스트를 ASCII 그림으로 변환해 주는 기능도 포함하고 있습니다.

<section>
FigletFont font = FigletFont.Load("chunky.flf");
Figlet figlet = new Figlet(font);

Console.WriteLine(figlet.ToAscii("Belvedere"), ColorTranslator.FromHtml("#8AFFEF"));
Console.WriteLine(figlet.ToAscii("ice"), ColorTranslator.FromHtml("#FAD6FF"));
Console.WriteLine(figlet.ToAscii("cream."), ColorTranslator.FromHtml("#B8DBFF"));
</section>

[이미지](https://camo.githubusercontent.com/ac939db6a00a5639d3c257298dcb87432d83ecff/687474703a2f2f636f6c6f7266756c636f6e736f6c652e636f6d2f696d616765732f61736369695f78322e706e67)


### 커뮤니티 소식

### .NET 소식

* How to package a portable .NET library targeting .NET Core? : 스택 오버플로에 실린 Q&A 글입니다. 여러분이 만든 닷넷 라이브러리를 .NET Core 및 그 외의 다양한 환경을 위해 패키징할 수 있는 방법을 보여줍니다.
* Debugging and Profiling in Visual Studio 2015: 비주얼 스튜디오 2015에 제공되는 디버깅 및 프로파일링 관련 기능을 Manuel Meyer가 설명합니다.
* [How open source changed my life](http://blog.tonysneed.com/2015/12/19/how-open-source-changed-my-life/) : Tony Sneed는 오픈 소스에 참여한 그의 체험담을 공유했습니다.
* To base() or not to base(), that is the question : Jon Skeet은 자식 클래스에서 부모 클래스의 기본 생성자를 다루는 방법이 스펙 문서와 다를 수 있음을 지적하고 명시적인 base() 호출의 효과를 설명합니다.
* Evolution of C# : Kunal Chowdhury는 C# 1.0부터 6.0까지의 변화를 하나의 표로 만들어 공유해주었습니다.
* Functional Microservices : [.NET Rocks](http://www.dotnetrocks.com) 운영진은 jet.com의 Rachel Reese가 F#으로 마이크로서비스를 구축한 것에 대한 그녀의 경험담을 인터뷰했습니다.


### ASP.NET 소식

* Goodbye child actions, hello view components : Dave Paquette이 View Component를 이용해 재사용가능한 구성요소를 만드는 법을 소개합니다.
* Best practices for private config data and connection strings in configuration in ASP.NET and Azure : Scott Hanselman이 Azure 상의 ASP.NET 웹 응용 프로그램에서 연결 문자열과 같은 민감한 내부 데이터를 보관하기 위한 최적의 방법을 소개합니다.
* Real time translated chat with ASP.NET, Microsoft Translator and IP Messaging : Devin Rader는 [Microsoft Translator API](http://www.microsoft.com/en-us/translator/translatorapi.aspx)를 이용해 채팅 메시지를 실시간으로 번역해 주는 방법을 소개합니다.
* Building APIs with MVC 6 and OAuth : Filip Ekberg는 MVC 6과 OAuth를 결합시켜 API를 서비스하는 방법을 비디오로 만들어 유튜브에 공개했습니다.
* How to take an ASP.NET MVC web site down for maintenance : Jon smith는 ASP.NET MVC 웹 사이트 운영 도중 유지 보수를 위해 중지시켜야 할 경우, 어떤 식으로 처리해야 할 지에 대한 고민과 그 만의 처리 방식을 공유하고 있습니다.
* Experiments with Entity Framework 7 and ASP.NET MVC 6 : Damien Bod는 ASP.NET MVC 6와 Entity Framework 7을 함께 사용해 본 경험을 공유했습니다.  


### F# 소식

* Bryan Hunter의 Lean and Functional Programming
* Pierre Irrmann의 Visualizing F# Advent Calendar Contributors
* Eirik Tsarpalis의 Reconciling Stack Traces with Computation Expressions
* Craig Stuntz의 Presentations from CodeMash 2016

