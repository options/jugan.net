첫번째 주간닷넷을 올리고 나서 불과 3일만에 2,000명이 넘는 분께서 주간닷넷 페이지를 방문 해 주셨습니다. 다시한번 여러분의 성원에 감사드립니다. 

지난호의 내용을 살펴보시고 싶으신 분들도 계실 것 같아 페이스북에 조그만 페이지를 하나 만들어 주간닷넷 내용만을 공유 하려고 합니다. 관심 있으신 분들은 [주간닷넷 페이지](https://www.facebook.com/jugan.net)를 방문하셔서 '좋아요'를 누르시면 됩니다.
 
또한 혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. .NET 관련 동호회 소식도 알려주시면 주간닷넷을 통해 많은 분들과 공유하도록 하겠습니다.

### 금주의 패키지 #0 - AngleSharp

지난 호에서 소개해 드린 HtmlAgilityPack을 보시고 몇몇 분들이 유사한 라이브러리로 AngleSharp을 사용한다고 덧글을 달아 주셨습니다. AngleSharp 라이브러리는 XPath 방식을  사용하는 HtmlAgilityPack과는 달리 CSS 쿼리를 지원하며 활발한 업데이트로 인해 최근의 기술을 보다 더 잘 지원하고 있습니다.

* [AngleSharp](https://www.nuget.org/packages/AngleSharp/)

다음의 코드는 지난 주에 HtmlAgilityPack 라이브러리를 이용해 작성했던 기능을 AngleSharp으로 구현해 본 것입니다.

<section>
{{gist}} <script src="https://gist.github.com/bleroy/ca1499fee30581358e9e.js"></script>
</section>

### 금주의 패키지 #1 - Bogus

TDD(Test Driven Development)를 위해 테스트 케이스를 만들다 보면 심심치 않게 임시 데이터가 필요한 순간이 옵니다. 변수 이름 짓는 것만 해도 곤혹스러운데 가짜 데이터까지 그럴 듯 하게 만들어야 하는 것은 개발자 입장에서 또 다른 부담일 수 밖에 없는데요. 바로 이럴 때 사용할 수 있는 라이브러리가 Bogus입니다.

* [Bogus](https://www.nuget.org/packages/Bogus/) 

Bogus는 [Brian Chavez](https://github.com/bchavez)가 만든 라이브러리로 클래스의 인스턴스를 생성 할 때, 텍스트나 이미지와 같은 다양한 데이터 타입의 값을 실제와 유사한 정보로 채우는 기능을 갖고 있습니다. 다음은 Bogus 라이브러리를 이용해 임의의 사용자 데이터를 생성하는 예제 코드입니다.

<section>
{{gist}} <script src="https://gist.github.com/bleroy/d596de64caeeab352795.js"></script>
</section>

### 금주의 .NET Core 소식

[Joe Audette](https://github.com/joeaudette)는 IMAP, POP3, SMTP 등의 기능을 구현한 오픈 소스 라이브러리인 MailKit이 .NET Core를 지원한다는 소식을 전해 주셨습니다. 자세한 내용은 [Mailkit now supports .NET Core](https://github.com/jstedfast/MailKit/issues/212)를 확인 하세요. 

이 라이브러리를 이용하면 .NET Core를 이용하여 메일 송수신과 같은 기능을 쉽게 구현할 수 있습니다.

아울러 Brian Chavez는 RethinkDB용 닷넷 드라이버도 .NET Core를 지원한다고 알려주셨습니다. 자세한 내용은 [.NET driver for RethinkDB](https://www.nuget.org/packages/RethinkDb.Driver)를 살펴 보십시오.

### F# 소식

이번 주부터는 F# 커뮤니티의 소식도 함께 전달해 드리겠습니다. 그 첫번째로 Sergey Tihon과 David Stephens이 아래의 링크들을 소개해 주셨습니다.
Krzysztof Cieślak이 비주얼 스튜디오 코드에서 F# 언어를 지원하는 [Ionide 확장 패키지](http://blogs.msdn.com/b/dotnet/archive/2015/12/03/guest-post-announcing-f-support-in-visual-studio-code-with-ionide.aspx)를 발표했습니다.


F# 커뮤니티에서는 한해 동안의 포스팅 계획을 담은 [F# Advent Calendar](https://sergeytihon.wordpress.com/2015/10/25/f-advent-calendar-in-english-2015/)를 제공하고 있는데요. 그 중에서 몇 가지를 소개해드립니다.

* Scott Wlaschin의 [Thirteen ways of looking at a turtle 1부](http://fsharpforfunandprofit.com/posts/13-ways-of-looking-at-a-turtle/)와 [2부](http://fsharpforfunandprofit.com/posts/13-ways-of-looking-at-a-turtle-2/)
* Sean Trelford의 [No 1 at Christmas](https://seantrelfordblog.wordpress.com/2015/12/05/no1s/)
* Andrea Magnorsky의 [Computation expressions and microphones](http://www.roundcrisis.com/2015/12/06/Computation-expressions-in-practice/)
* Christopher Atkins의 [F# 2015 Advent Cookies](http://www.roundcrisis.com/2015/12/06/Computation-expressions-in-practice/)
* Sergey Tihon의 [Application contracts with Swagger powered APIs for .NET or Why SwaggerProvider](https://sergeytihon.wordpress.com/2015/12/07/application-contracts-with-swagger-powered-apis-for-net-or-why-swaggerprovider/)
* Aaron Powell의 [What's the time Mr Wolf?](http://www.aaron-powell.com/posts/2015-12-07-whats-the-time-mr-wolf.html)

### 금주의 커뮤니티 소식

12월16일 ASP.NET 개발자 모임인 [TAEYO.NET](http://taeyo.net/)에서 송년 번개를  개최할 예정입니다. 자세한 내용은 [2015 굿바이 송년벙개 예고:12월 16일](http://taeyo.net/Forum/Content.aspx?SEQ=36672&TBL=TALK)을 확인 하세요.

### 금주의 블로그 글

* [Support Ending for .NET Framework 4, 4.5 and 4.5.1](http://blogs.msdn.com/b/dotnet/archive/2015/12/09/support-ending-for-the-net-framework-4-4-5-and-4-5-1.aspx) : 2016년 1월 12일 부터 .NET Framework 4, 4.5, 4.5.1에 대한 보안 업데이트, 기술 지원, 핫픽스 등의 지원이 종료 된다는 내용을 담은 글입니다. 이 글은 2015년 8월 7일에 공지한 [Moving to the .NET Framework 4.5.2](http://blogs.msdn.com/b/dotnet/archive/2014/08/07/moving-to-the-net-framework-4-5-2.aspx)를 재확인 하는 내용입니다.
* [ASYNC-AWAIT - On The Efficiency Of ValueTask](http://blog.i3arnon.com/2015/11/30/valuetask/) : Bar Arnon이 CoreFX 라이브러리에 새롭게 추가된 ValueTask&lt;T&gt; 타입에 대해 설명하고 있습니다.
* [Functional Monadic Parsers ported to C#](http://blog.leifbattermann.de/2015/11/23/functional-monadic-parsers-ported-to-c/) : 함수형 프로그래밍의 대가인 Erik Meijer가 온라인 강의 사이트인 eDX를 통해서  연재한 [Introduction to Functional Programming](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x-0)를 보면 모나드를 이용하여 파서를 제작하는 방법을 설명하고 있는 부분이 있습니다. Leif Battermann은 이를 C#으로 어떻게 포팅할 수 있는지에 대해 소개하고 그 소스코드를 GitHub를 통해  공개했습니다.
* [Six Essential Tips for Async](https://channel9.msdn.com/Series/Three-Essential-Tips-for-Async) : 비록 2년 전에 작성된 오래된 동영상이긴 하지만 Lucian Wischik 만큼 Async에 대해 멋지게 설명한 동영상을 쉽게 찾으실 수는 없을 겁니다. (아쉽게도 한글 자막은 제공되지 않습니다.)
