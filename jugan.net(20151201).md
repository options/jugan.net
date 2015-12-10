# 주간닷넷 2015년 12월 1일

며칠 전 마이크로소프트웨어 월간 잡지가 12월을 마지막으로 휴간에 들어간다는 소식을 들었습니다. 

30년이 넘는 IT 역사를 함께 한 잡지였던만큼 더욱 아쉬울 수 밖에 없는데요. 우연히도 마이크로소프트의 .NET 팀은 [팀 블로그]를 통해서 매주 닷넷 관련 소식을 전해드리기로 했고 이번이 첫 회입니다. 

전체적인 내용은 본사의 블로그 내용을 전해드리겠지만 국내 개발자 여러분들의 소식도 함께 전해 드리고자 합니다. 

혼자 알고 있기에는 너무나 아까운 글, 소스 코드, 라이브러리를 발견 하셨거나 혹은 직접 작성하셨다면 [Gist]를 통해서 알려주세요.
주간닷넷을 통해서 많은 분들과 공유하도록 하겠습니다.

### .NET Managed Language를 위한 .NET Core, .NET Framework 4.6.1, ASP.NET 5 RC, Visual Studio 2015 Update 1

지난 11월 18일 마이크로소프트는 개발자를 위한 연례 행사인 [Connect(); // 2015]를 개최하고 다양한 기술 정보를 공유하였습니다.(링크를 통해서 동영상을 살펴보실 수 있습니다.) 이 행사를 통해서 윈도우 뿐만 아니라 OS X 및 리눅스를 지원하는 .NET Core와 ASP.NET 5 RC가 “Go Live” 형식으로 발표되었습니다. 마이크로소프트의 “Go Live” 정책이란, 해당 제품으로 실제 업무용 프로젝트에 응용 프로그램을 배포할 수 있고 필요하다면 마이크로소프트의 지원을 요청할 수 있음을 의미합니다.

.NET Core와 ASP.NET에 대한 좀 더 자세한 정보는 [Announcing .NET Core and ASP.NET 5 RC] 에서 살펴보실 수 있습니다.
또한 ASP.NET만 별도로 다룬 [Announcing ASP.NET 5 Release Candidate 1] 글도 있습니다.

이어서 11월 30일에는 성능뿐만 아니라 안정성 및 개발 경험을 더욱 향상시킨 닷넷 프레임워크 4.6.1이 공개되었습니다. 이 버전의 상세한 소식은 [.NET Framework 4.6.1 is now available] 에서 볼 수 있습니다. 이와 함께 비주얼 스튜디오 2015의 첫번째 업데이트도 같은 날 공개되었습니다. 이번 업데이트에는 몇몇 새로운 IDE 기능과 Interactive C# 창, 새로운 코드 분석 관리 도구, 더 나은 비주얼 F# 언어 지원, Roslyn 오픈 소스 개발을 위한 F5(디버거 모드로 실행) 지원이 포함되었습니다. 보다 자세한 정보는 [What’s New in Visual Studio Update 1 for .NET Managed Languages] 를 살펴 보시기 바랍니다.

### 금주의 패키지

간혹 HTML 문서로부터 정보를 추출해야 할 때가 있습니다. XML 형식을 따르는 HTML 문서이기 때문에 이런 경우 가볍게 직접 파서(Parser)를 작성하거나 정규 표현식을 사용할 수 있는데 그보다는 역시 전문적인 HTML 파서로 DOM 쿼리를 이용해 추출하는 것이 더 나은 선택일 것입니다. 바로 이럴 때 선택할 수 있는 라이브러리가 HtmlAgilityPack입니다.

[HtmlAgilityPack]

<script src="https://gist.github.com/bleroy/c5e8f2ebdbd694e0913f.js"></script>

### 금주의 커뮤니티 소식

12월14일 ASP.NET 개발자 모임인 [ASP.NET Korea User Group]에서 연말 모임을 개최할 예정입니다. 자세한 내용은 [ASP.NET Korea 2015 연말 모임]을 확인 하세요.

### 금주의 블로그 글

Marc Gravell이 기존 작성된 닷넷 라이브러리를 .NET Core 용으로 어떻게 변환할 수 있는지를 소개하는 글을 3부에 걸쳐 공개했습니다.

* [The road to DNX – part 1]
* [The road to DNX - part 2]
* [The road to DNX – part 3]

영국의 IT 소식지인 The Register는 .NET Core가 마이크로소프트의 향후 개발 플랫폼에서 어떤 의미를 지니는지 전하는 글을 게재하였습니다.

* [Why Microsoft's .NET Core is the future of its development platform]

Nate Barbettini는 맥 운영체제에서 부트 캠프(BootCamp)와 패러렐즈(Parallels)를 이용해 어떻게 비주얼 스튜디오 개발 환경을 구성할 수 있는지에 대해 글을 작성했습니다.
* [The Ultimate Guide to Using Visual Studio on a Mac]

Mahmut Jomaa와 Shawn Wildermuth는 기존에 ASP.NET 5 베타 8으로 작성된 응용 프로그램을 RC1 버전으로 마이그레이션 하는 방법을 자신들의 블로그를 통해 공유 해 주었습니다.
* [Upgrading your ASP.NET 5 application from beta8 to RC1]
* [Upgrading ASP.NET 5 Beta 8 to RC1]

심지어 Armen Shimoon은 ASP.NET 5 베타 8과 RC1의 차이점을 “Diff” 기능을 이용해 소스코드 수준에서 분석한 글을 공개 했습니다.
* [ASP.NET 5 Beta 8 to RC1 Annotated Diff]

마지막으로 Shayne Boyer는 .NET Core의 CLI(명령행 인터페이스)와 관련된 사용법을 설명하는 글을 공개했습니다.
* [Preparing for dotnet cli]

[What’s New in Visual Studio Update 1 for .NET Managed Languages]: <http://blogs.msdn.com/b/dotnet/archive/2015/11/30/what-s-new-in-visual-studio-update-1-for-net-managed-languages.aspx>

[.NET Framework 4.6.1 is now available]: <http://blogs.msdn.com/b/dotnet/archive/2015/11/30/net-framework-4-6-1-is-now-available.aspx>

[Announcing ASP.NET 5 Release Candidate 1]: <http://blogs.msdn.com/b/dotnet/archive/2015/11/18/announcing-net-core-and-asp-net-5-rc.aspx>

[Announcing .NET Core and ASP.NET 5 RC]: <http://blogs.msdn.com/b/dotnet/archive/2015/11/18/announcing-net-core-and-asp-net-5-rc.aspx>

[Gist]: <https://gist.github.com/options/e9fc443b8c882157fe4a>
[팀 블로그]: <http://blogs.msdn.com/b/dotnet>
[F#/Analytics + IoT + Azure]: <http://www.meetup.com/TRINUG/events/225097782/>

[Announcing ASP.NET 5 RC]: <http://blogs.msdn.com/b/webdev/archive/2015/11/18/announcing-asp-net-5-release-candidate-1.aspx>
[Connect(); // 2015]: <https://channel9.msdn.com/Events/Visual-Studio/Connect-event-2015/>


[HtmlAgilityPack]: <https://www.nuget.org/packages/HtmlAgilityPack/>

[ASP.NET Korea 2015 연말 모임]:<https://www.facebook.com/groups/AspxKorea/events/>

[ASP.NET Korea User Group]:<https://www.facebook.com/groups/AspxKorea/>

[The road to DNX – part 1]:<http://blog.marcgravell.com/2015/11/the-road-to-dnx-part-1.html>
[The road to DNX - part 2]:<http://blog.marcgravell.com/2015/11/the-road-to-dnx-part-2.html>
[The road to DNX – part 3]:<http://blog.marcgravell.com/2015/11/the-road-to-dnxpart-3.html>

[Why Microsoft's .NET Core is the future of its development platform]: <http://www.theregister.co.uk/2015/11/20/microsoft_net_core_development_platform_fork/>

[The Ultimate Guide to Using Visual Studio on a Mac]:<https://stormpath.com/blog/ultimate-guide-to-using-visual-studio-on-a-mac/>

[Upgrading your ASP.NET 5 application from beta8 to RC1]: <http://mjomaa.com/computer-science/frameworks/asp-net-mvc/157-upgrading-your-asp-net-5-application-from-beta8-to-rc1>
[Upgrading ASP.NET 5 Beta 8 to RC1]: <http://wildermuth.com/2015/11/18/Upgrading_ASP_NET_5_Beta_8_to_RC1>

[ASP.NET 5 Beta 8 to RC1 Annotated Diff]: <http://dotnetliberty.com/index.php/2015/11/23/asp-net-5-beta-8-to-rc1-annotated-diff/>

[Preparing for dotnet cli]: <http://tattoocoder.com/preparing-for-dotnet-cli/>
