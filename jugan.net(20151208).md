#주간닷넷 2015년 12월 8일

… 한국 마이크로소프트의 소식이라든가… 
혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견하셨거나 혹은 직접 작성하셨다면 [Gist](https://gist.github.com/options/e9fc443b8c882157fe4a)를 통해 알려주세요. 주간닷넷을 통해 많은 분들과 공유하도록 하겠습니다.

### 금주의 패키지 #1 - AngleSharp

지난 번 소개해 드린 HtmlAgilityPack을 보고 몇몇 분들이 그와 같은 목적의 라이브러리로 AngleSharp을 사용한다고 덧글을 달아주셨습니다. 새로운 AngleSharp 라이브러리는 XPath 방식의 HtmlAgilityPack과는 달리 CSS 쿼리를 지원하며 활발한 업데이트로 인해 최근의 기술을 보다 더 잘 지원하고 있습니다.

* [AngleSharp](https://www.nuget.org/packages/AngleSharp/)

다음의 코드는 지난 주에 HtmlAgilityPack 라이브러리를 이용해 작성했던 기능을 AngleSharp으로 동등하게 구현해 본 것입니다.

<section>
{{gist}} <script src="https://gist.github.com/bleroy/ca1499fee30581358e9e.js"></script>
</section>

### 금주의 패키지 #2 - Bogus

TDD(Test Driven Development)로 인해 테스트 케이스를 만들다 보면 심심치 않게 임시 데이터가 필요한 순간이 옵니다. 변수 이름 짓는 것만 해도 곤혹스러운데 가짜 데이터까지 그럴 듯 하게 만들어야 하는 것은 개발자 입장에서 또 다른 부담일 수 밖에 없는데요. 바로 이럴 때 사용할 수 있는 라이브러리가 Bogus입니다.

* [Bogus](https://www.nuget.org/packages/Bogus/) 

Brian Chavez가 만든 것으로 클래스의 인스턴스 생성 시 텍스트, 이미지와 같은 다양한 데이터 타입의 값을 실제와 유사한 정보로 채우는 기능을 갖고 있습니다. 다음은 Bogus 라이브러리를 이용해 임의의 사용자 데이터를 생성하는 예제 코드입니다.

<section>
{{gist}} <script src="https://gist.github.com/bleroy/d596de64caeeab352795.js"></script>
</section>

### .NET Core 소식

IMAP, POP3, SMTP 등의 기능을 구현한 오픈 소스 라이브러리인 MailKit이 .NET Core를 지원한다는 소식을 Joe Audette이 전해 주었습니다. 따라서 이제부턴 .NET Core 기반의 응용 프로그램에서도 메일 전송과 관련된 기능을 아주 쉽게 구현할 수 있게 되었습니다.
아울러 이미 위에서 소개한 Bogus 라이브러리를 만든 Brian Chavez의 또 다른 라이브러리인 RethinkDB 용 닷넷 드라이버도 .NET Core를 지원한다고 합니다.

### F# 소식

이번 주부터는 F# 커뮤니티의 소식도 함께 전달해 드리겠습니다. 그 첫번째로 Sergey Tihon과 David Stephens이 아래의 링크들을 소개해 주었습니다.
Krzysztof Cieślak이 비주얼 스튜디오 코드에서 F# 언어를 지원하는 [Ionide 확장 패키지](http://blogs.msdn.com/b/dotnet/archive/2015/12/03/guest-post-announcing-f-support-in-visual-studio-code-with-ionide.aspx)를 발표했습니다.
F# 커뮤니티에서는 한해 동안의 포스팅 계획을 담은 “F# Advent Calendar”를 제공하고 있는데요. 그 중에서 몇 가지를 소개해드립니다.

* 12월 5일: Scott Wlaschin의 [Thirteen ways of looking at a turtle 1부](http://fsharpforfunandprofit.com/posts/13-ways-of-looking-at-a-turtle/)와 [2부](http://fsharpforfunandprofit.com/posts/13-ways-of-looking-at-a-turtle-2/)
* 12월 5일: Sean Trelford의 [No 1 at Christmas](https://seantrelfordblog.wordpress.com/2015/12/05/no1s/)
* 12월 6일: Andrea Magnorsky의 [Computation expressions and microphones](http://www.roundcrisis.com/2015/12/06/Computation-expressions-in-practice/)
* 12월 6일: Christopher Atkins의 [F# 2015 Advent Cookies](http://www.roundcrisis.com/2015/12/06/Computation-expressions-in-practice/)
* 12월 7일: Sergey Tihon의 [Application contracts with Swagger powered APIs for .NET or Why SwaggerProvider](https://sergeytihon.wordpress.com/2015/12/07/application-contracts-with-swagger-powered-apis-for-net-or-why-swaggerprovider/)
* 12월 7일: Aaron Powell의 [What's the time Mr Wolf?](http://www.aaron-powell.com/posts/2015-12-07-whats-the-time-mr-wolf.html)


### 개발자 커뮤니티 소개

### 금주의 블로그 글

* [ASYNC-AWAIT - On The Efficiency Of ValueTask](http://blog.i3arnon.com/2015/11/30/valuetask/) : Bar Arnon이 CoreFX 라이브러리에 새롭게 추가된 ValueTask<T> 타입에 대해 설명하고 있습니다.
* [Functional Monadic Parsers ported to C#](http://blog.leifbattermann.de/2015/11/23/functional-monadic-parsers-ported-to-c/) : Erik Meijer의 “Introduction to Functional Programming”이라는 온라인 강의에서 다루고 있는 파서를 Leif Battermann이 C#으로 어떻게 포팅할 수 있는지에 대한 소개와 그 소스코드를 GitHub에 공개했습니다.
* [Six Essential Tips for Async](https://channel9.msdn.com/Series/Three-Essential-Tips-for-Async) : 비록 2년 전에 작성된 Lucian Wischik의 오래된 동영상 강의지만 Async에 대해 이만큼 멋지게 설명한 것을 쉽게 찾을 순 없을 것입니다. (아쉽게도 한글 자막은 제공되지 않습니다.)
