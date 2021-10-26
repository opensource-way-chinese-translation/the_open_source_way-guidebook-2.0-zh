### 要构建多样化的开源社区，首先要具有包容性

**介绍**

Mere months after the COVID-19 pandemic forced most tech teams to work remotely or not at all,
the murder of George Floyd ignited a racial reckoning in the United States. This movement hit the
tech sector especially hard. While companies released statements in support of racial justice and
declaring that Black Lives Matter, their own representation—experience of Black employees—came
under scrutiny, both internally and externally.
在新冠疫情迫使大多数技术团队远程工作或根本不工作仅仅几个月后，乔治·弗洛伊德（George Floyd）的被谋杀在美国引发了种族游行。这场运动对科技行业的打击尤其严重。虽然各公司发表声反对种族歧视，并宣布黑人的命也是命，但他们自己的黑人员工受到了内部和外部的审查。

At first glance, open source seems immune to the multi-pronged problems with diversity and
inclusion plaguing technology companies. Open source ecosystems operate online; contributors
work across countries, languages, and timezones to power projects that drive technology forward.
In some cases, people contribute purely out of love for these projects, not for free beer and stock.
乍一看，开源似乎对困扰科技公司的多样性和包容性的多管齐下的问题免疫。开源生态系统在国际互联网上运行；贡献者跨越国家、语言和时区为推动技术进步的项目提供动力。
在某些情况下，人们捐款纯粹是出于对这些项目的热爱，而不是为了奖励

Given the prevalence of such altruistic intent, the thinking goes, open source is a true meritocracy, a
space where all can thrive regardless of their pronouns or the color of their skin. But if there’s one
thing that industry advocates love more than meritocracy, it’s data. And when the data shows who
contributes to the open source ecosystem, it paints a damning picture.
这种想法认为，鉴于这种利他主义意图的盛行，开源是一种真正的精英管理，在这个空间里，所有人都可以茁壮成长，而他们的肤色如何没有影响。但如果说有一件事是行业倡导者比精英管理更喜欢的，那就是数据。当数据显示谁为开源生态系统做出了贡献时，它描绘了一幅可怕的画面。

This chapter offers an overview of efforts by various open source communities to make projects
more diverse and inclusive. It also offers initial steps open source community managers and project
maintainers can take to begin building communities and projects that benefit from a diverse
contributor base. Most crucially, it argues that open source communities must practice inclusion
before trying to find contributors from underrepresented groups. Without trying to fix the systemic
barriers that prevent people from staying, efforts to diversify will keep failing in vain.
本章概述了各种开源社区为使项目更加多样化和包容性所做的努力。它还提供了开源社区管理者和项目维护者可以采取的初始步骤，以开始构建社区和项目，从不同的贡献者基础中获益。最关键的是，它认为开源社区在试图从代表性不足的群体中寻找贡献者之前，必须实践包容性。如果不设法解决阻碍人们留下来的系统性障碍，多样化的努力将继续徒劳无功。

**开源社区多样性的状态**

In 2019, the U.S. Bureau of Labor Statistics found that 28.7% of total employed managers in the
"Computer and Information Systems" sector were women. Of all managers in that sector, 9.6% were
Black or African American, 15.8% were Asian, and 4.7% were Hispanic or Latino.
2019年，美国劳工统计局（U.S.Bureau of Labor Statistics）发现，在美国，28.7%的总雇佣经理
“计算机和信息系统”部门是女性。在该行业的所有经理中，9.6%为黑人或非裔美国人，15.8%为亚裔，4.7%为西班牙裔或拉丁裔。

As this survey indicates, the managers in the technology industry in the United States are
predominantly White and/or men. The open source communities skew even more toward
contributors who are White and/or men. A 2017 GitHub survey of 6,000 open source users and
developers found that 95% of randomly selected respondents were men. Three percent were
women, and one percent were non-binary people.
正如这项调查所表明的，美国科技行业的管理者主要是白人/男性。开源社区更倾向于白人/男性的贡献者。2017年GitHub对6000名开源用户和开发人员的调查发现，随机选择的受访者中有95%是男性。3%是女性，1%是非二元性别人群。

How does this continue to happen? Recent years have seen an influx of diversity and inclusion
(D&I) initiatives aimed at recruiting more diverse project contributors. The Linux Foundation has
devoted an entire section of programming at its Open Source Summits to sessions on D&I.
DrupalCon offers scholarships for attendees and speakers from underrepresented backgrounds.
Several mainstage keynotes at All Things Open 2019 discussed diversity. With so much attention
from community leaders, why does contributor data still paint such a stark picture?
这是如何继续发生的？近年来，多元化和包容性（D&I）计划大量涌入，旨在招募更多元化的项目贡献者。Linux基金会在其开源论坛上为D＆I的会议投入了整个编程部分。
DrupalCon为代表性不足的与会者和演讲者提供奖学金。2019年万事通公开赛的几场主流基调讨论了多样性。社区领袖如此关注，为什么贡献者数据仍描绘出如此区分鲜明的画面？

Relative lack of open source activity from women and underrepresented minorities (URMs) seems
surprising at first, but a closer look reveals some persistent problems regarding inclusion in open
source communities. Inclusion is often used as a synonym for diversity; in fact, it is its own
principle. To quote Meg Bolger, "Inclusion is about folks with different identities feeling and/or
being valued, leveraged, and welcomed within a given setting (e.g., your team, workplace, or
industry)." Some persistent, systemic barriers keep women and URMs from being included in open
source communities. Without addressing and rectifying these systemic problems, diversity in open
source won’t improve.
一开始，女性和代表性不足的少数民族（URM）相对缺乏开源活动似乎令人惊讶，但仔细观察就会发现，在开源社区的包容性方面存在一些持续存在的问题。包容经常被用作多样性的同义词；事实上，这是它自己的原则。引用Meg Bolger的话，“包容是指具有不同身份的人在给定的环境（例如，您的团队、工作场所或行业）中感受到和/或受到重视、受用和欢迎。”一些持续存在的系统性障碍阻止女性和URM被纳入开源社区。如果不解决和纠正这些系统性问题，开源的多样性就不会得到改善。

Let’s unpack three of those barriers: Lack of free time to contribute, a hostile online environment,
and lackluster documentation.
让我们来解开其中的三个障碍：缺乏贡献的自由时间，充满敌意的网络环境，以及平淡无奇的文档。

**缺少自由时间来贡献**

Globally, women continue to earn less than White men for performing the same professional roles.
They are also increasingly likely to be their homes' primary earners, and they’re more likely to do
unpaid labor in the form of housework, childcare, and other domestic tasks.
在全球范围内，女性与白人男性持续同工不同酬
但她们也越来越有可能成为家庭的主要收入来源，她们更有可能从事家务、托儿和其他家务等形式的无偿劳动。

As a result, they have less spare time to do even more unpaid work by contributing to open source
communities. When they do make those contributions, they often do so during work
hours—because they already work for organizations that let them do it.
因此，她们没有多少空闲时间通过贡献给开源社区，做更多无报酬的工作。当她们确实做出这些贡献时，她们通常是在工作时间做出贡献，因为她们在允许他们这样做的团队中工作。

Nisha Kumar (She/They) is the technical lead for container build, packaging, and distribution at the
Open Source Technology Center at VMware. She also serves as co-maintainer for the Tern project,
and a contributor to the SPDX and OCI communities. She juggles these projects with her role as her
child’s primary caregiver. To Kumar, these dual roles are nothing new; as a girl growing up in
India, she balanced schoolwork with chores, running errands, and caring for family members.
These endless tasks left no time for her to pursue passion projects.
尼沙·库马尔（Nisha Kumar）（她/他们）是VMware开源技术中心容器构建、打包和分发的技术负责人。她还担任Tern项目的共同维护者，以及SPDX和OCI社区的贡献者。她将这些项目与她作为孩子的监护人角色结合起来。对库马尔来说，这种双重角色并不是什么新鲜事；作为一个在印度长大的女孩，她平衡了学业与家务、跑腿和照顾家庭成员。这些没完没了的任务让她没有时间去追求她感兴趣的项目。

If not for her ability to work on open source during the day at VMware, she’s unsure if she could
contribute today. Kumar told me:
如果不是因为她白天在VMware从事开源工作的能力，她甚至不确定自己今天是否能有所贡献。库马尔告诉我：

```
"As a woman in tech contributing to open source in my day job and getting
compensated for it, I find that I still don’t have the time to contribute to
open source projects I am personally interested in or even volunteer for my
local open source communities because I need to also take care of my child
and household."
```
```
“作为一名从事技术工作的女性，在我的日常工作中为开源做出贡献并获得报酬，但我发现我仍然没有时间为我个人感兴趣的开源项目做出贡献，甚至没有时间为我当地的开源社区做志愿者，因为我还需要照顾我的孩子和家人。”
```
**敌意的网络环境**

The internet is not an equally hospitable place. Women, people of color, and LBGTQ+ people are
disproportionately targeted for online harassment, with women twice as likely to experience online
sexual harassment as men. And this was prior to 2020.
互联网并不是一个好客的地方。女性、有色人种和LBGTQ+人群是网络骚扰的不成比例的目标，女性遭受网络性骚扰的可能性是男性的两倍。（在2020年之前）

The year’s confluence of a global pandemic and mass civil unrest has led to increased attacks
against people of color, specifically Asian Americans and Black Americans. If attackers feel
emboldened to hurt people in the flesh, it’s no surprise that this occurs online as well. If you work
on open source projects with Black and Asian contributors, make no mistake: They are in pain.
2020年新冠大流行和大规模内乱（美国）的结合导致针对有色人种的袭击增加，特别是亚裔美国人和黑人。考虑到攻击者有胆量伤害人身安全，那么这种情况也会在网上发生也就不足为奇了。如果你与黑人和亚裔贡献者一起从事开源项目，不要搞错：他们正处于痛苦之中。

"I don’t see any acknowledgement that the internet, in general, is mostly inhabited by white men
who are hostile to women and URMs," Kumar says. "How would anyone expect folks who are in
general harassed on the internet to suddenly trust an open source community to not behave the
same way toward them, despite what its Code of Conduct document says?"
库马尔说：“我看不到任何人承认。总体而言，互联网上主要活跃着对女性和URM怀有敌意的白人男性”。“人们怎么会期望那些在互联网上受到普遍骚扰的人们突然信任一个开源社区，而不管它的行为准则文件是怎么说的，像是他们不会以同样的方式对待他们呢？”

Kumar’s concerns are well-founded. Open source communities don’t have a reputation for making
most feel welcome. For years, project maintainers have written calls for help, saying they "feel
drained, unappreciated, and even abused" on their worst days. A 2017 survey of 6,000 GitHub
contributors found that 21% left projects they were working on after experiencing negative
behavior. With the odds of such behavior that much higher for people from underrepresented
groups, it’s surprising they contribute to open source projects at all.
库马尔的担忧是有根据的。开源社区没有让大多数人感到受欢迎。多年来，项目维护人员一直写信寻求帮助，说他们在最糟糕的日子里“感到精疲力竭、不被赏识，甚至被虐待”。2017年，一项针对6000名GitHub贡献者的调查发现，21%的人在经历负面行为后离开了他们正在从事的项目。对于代表性不足的群体来说，这种行为发生的几率要高得多，令人惊讶的是，他们仍然为开源项目做出了贡献。

"Any time that I spend contributing to [open source communities] is time I could also be spending
volunteering to advance LGBTQ equality, fighting against police brutality, and other issues that I
care about, and that disproportionately affect underrepresented people—in fact, it’s what makes us
underrepresented in the first place," explains Perry Eising (He/They), who works as a community
manager at a for-profit tech company that hosts open source projects. "It’s challenging to justify to
myself to spend time being involved in (sometimes hostile-feeling) OS and tech debates when I have
so many causes that require my attention and efforts."
“我花在[开源社区]上的任何时间，都可以花在志愿服务上，以促进LGBTQ平等，打击警察暴行，以及其他我关心的问题上，而这些都会对代表性不足的人产生不成比例的影响。事实上，正是这些时间让我们代表性不足的人群得到帮助。”佩里·艾辛（Perry Eising）（他/他们）解释道，他在一家主持开源项目的盈利性科技公司担任社区经理。“当我有这么多需要我关注和努力的原因时，我很难向自己证明自己有理由花时间参与（有时是怀有敌意的）操作系统和技术辩论。”

**文档不完整、不充分**

The barriers above manifest in perhaps the biggest barrier of all: Open source projects' lack of
documentation. Quantitative data and qualitative interviews repeatedly share that most open
source projects don’t prioritize or reward documentation. As a result, outsiders often have no clue
how to help.
文档障碍现在可能是最大的障碍。开源项目往往缺乏文档。大量的数据和访谈一再表明，大多数开源项目并不优先考虑文档。因此，外人往往不知道如何提供帮助。

I speak from personal experience here. After speaking at the Open Source Summit in Vancouver
two years ago, I found the community so warm and welcoming that I resolved to find a project with
which I could help. Given my background as a writer of all stripes, I thought writing documentation
would be the perfect place to start and make a meaningful impact. So you can imagine how my face
fell when I created my first GitHub account, logged onto the platform, and was left totally lost by
where to go next. With no knowledge of how to fork, merge branches, or make pull requests, I had
no clue where to start—and knew the margin for error was high.
我在这里是根据个人经验说的。两年前在温哥华的开源峰会上发言后，我发现开源社区是如此热情和欢迎，所以我决定寻找一个我可以帮助到的项目。考虑到我作为一名各行各业作家的背景，我认为编写文档将是一个完美的起点，并会产生有意义的影响。所以你可以想象一下，当我创建了我的第一个GitHub帐户之后，登录到平台上，然后完全迷失在下一步该去哪里的时候，我感觉有多难受。由于不知道如何使用、合并分支或发出拉取请求，我完全不知道从哪里开始，并且意识到犯错误的可能性很大。

I’m fortunate to live in a city with an active tech community that hosts regular meetups for techies
of all interests, including tutorials aimed at beginners. I made my first pull request in person at a
conference, and then made most of my first several dozen GitHub contributions at in-person
events. Only after attending several free, accessible events over several months did I begin
contributing independently. Absent any of these privileges, I would not have spent hours alone
trying to learn how GitHub works to make a PR that might—or might not—get accepted.
我很幸运地生活在一个有着活跃的科技社区的城市里，这里定期为所有感兴趣的科技人员举办聚会，包括针对初学者的教程。我在一次会议上亲自提出了第一个请求，然后在亲自参加的活动中完成了最初几十个GitHub贡献的大部分。几个月来，我参加了几次免费、方便的活动后，才开始独立撰稿。如果没有这些特权，我就不会花几个小时独自学习GitHub如何制作一个可能被接受或不被接受的PR（贡献请求）了。

The same GitHub survey that found one in five open source contributors leave projects due to bad
behavior also found that incomplete or confusing documentation was the biggest challenge. 93% of
that survey’s respondents said they had encountered the problem, yet 60% said they rarely or
never contributed to documentation. As a result, it’s hard for project veterans to read their _own_
projects' documentation.
GitHub的调查发现，五分之一的开源贡献者是由于不良行为而离开项目，同时也发现不完整或混乱的文档是最大的挑战。93%的受访者表示他们遇到过这个问题，但60%的人表示他们很少或从未参与文档编制。因此，项目老手甚至很难亲自阅读自己的作品_项目文件_。

Imagine how this makes outsiders feel.
想象一下这会让局外人有什么感觉。

"Contributing to open source is not only a technical challenge but equally a social challenge,"
explains Nuritzi Sanchez (She/Her), a senior open source program manager at GitLab.
"Documentation is needed to enable remote asynchronous collaboration, which is how
communities work. If everything is stuck inside of people’s heads, that’s going to create an
atmosphere of confusion, frustration, and inefficiency." Documentation isn’t just essential for code;
it’s also a guide to understanding each project’s cultural and communication norms (refer to this
guidebook’s chapter on communication norms for more on this subject).
“推动开源不仅是一项技术挑战，同样也是一项社会挑战，”
GitLab的高级开源项目经理，努里齐·桑切斯（Nuritzi Sanchez）（她/她）解释道。
“实现远程异步协作需要文档，而这正是社区的工作方式。如果一切都停留在人们的头脑中，那将造成混乱、沮丧和效率低下的氛围。”文档不仅仅是代码的基本要素；
它也是理解每个项目的文化和沟通规范的指南（有关此主题的更多信息，请参阅本指南的沟通规范章节）。

Open source communities use asynchronous communication to work cohesively across disparate
time zones. Without clear documentation, prospective contributors won’t know how decisions are
made, where to contribute to the project, how teams collaborate, or why following certain
processes is important. For prospective contributors who are non-native English speakers and/or
have special needs, this lack of documentation makes contributing all but impossible. Inadequate
documentation has far-reaching consequences. It shows a lack of transparency that wastes time,
sows distrust, and prevents many open source communities from reaching their full potential.
开源社区使用异步通信跨不同的时区协调工作。如果没有清晰的文档，潜在的贡献者将不知道如何做出决策，在哪里为项目做出贡献，团队如何协作，或者为什么遵循某些流程很重要。对于非英语母语和/或有特殊需求的潜在投稿人，由于缺乏文档，投稿几乎不可能。文件不足会产生深远的后果。这会导致缺乏透明度，浪费时间，滋生不信任，并阻止许多开源社区充分发挥其潜力。


**构建更具包容性的项目和社区的提示**

Despite these barriers to entry, there’s good news for maintainers: You hold enormous power to
improve your project’s culture by making it more inclusive. Community members, especially those
from underrepresented backgrounds, have discussed the lack of diversity and inclusion for years.
Now, it’s time for project maintainers to act by weaving inclusion throughout their project
strategies—not making it an afterthought.

"[Diversity and inclusion] keynotes might have lofty ideals designed to raise awareness and some
might even argue that they were useful at one point (maybe), but we’ve moved beyond that,"
argues Lisa-Marie Namphy [She/Her], who runs Cloud Native Containers, the world’s largest Cloud
Native Computing Foundation (CNCF) user group. "Our communities are saying that it’s time to act!
And action means a change of policies, fund initiatives, representation goals, so many things. The
communities are asking for accountability, from the foundations who run them to the corporations
who fund them."

If creating an inclusive community sounds overwhelming, remember that the community wants to
help. If you’re a project maintainer yourself, you don’t have to do this work alone. In fact, taking
the steps below with a trusted team will help improve your project for all.

**Step one: Stop saying you’re a meritocracy**

The first step to a more inclusive open source project involves understanding the meritocracy
myth: The more you believe in meritocracy, the more biased your project is likely to be.

Why? Purely meritocratic projects don’t acknowledge that people enter on unequal playing fields. If
an open source maintainer isn’t aware that women often have less time to contribute, or that
LGBTQ+ contributors are more likely to endure online abuse, they won’t take steps to make the
community more inclusive. As a result, they risk losing the diverse contributors they worked hard
to recruit.

Terri Oda (She/Her) volunteers for the Python Software Foundation and Google’s Summer of Code,
alongside her role as an open source security researcher at Intel. She says claims of meritocracy
make her cringe. Why? Such statements cause maintainers to ignore opportunities to get more
people involved in projects, even in cases where the open source community gathers in person.

"For example, say you’re running code sprints at a conference and want to increase the number of
women," Oda says. "If you’re thinking about merit and skills, you’re going to wind up offering more
intro to sprinting-type content. But if you look at the bigger picture, you might realize that the
conference offers childcare during the main conference, but it stops when sprints start. Or that the
venue isn’t in a safe area and the sprints run until after dark."

The first step to build a more inclusive environment is self-awareness. Open source contributors
enter projects with a range of lived experiences that affect how—and if—they show up. Sitting with
and reflecting on this fact is the first, most crucial step.

The next step is to take an honest look at your project’s current community, and take note of who
is—and isn’t—there. If your project contributors all, or even mostly, look like you, that’s a huge red
flag that an inclusive overhaul is in order.


**Step two: Prioritize your project’s documentation**

A 2019 Stack Overflow study found that about 41% of developers have less than five years of
experience. Between these new technologists and current emphasis on STEM education, there are
lots of opportunities to welcome new open source contributors. In order to do so, project
maintainers must lower barriers to entry—and clear, concise documentation is the first step.

Zach Corleissen (He/They) is the lead technical writer for The Linux Foundation (LF) who recently
revised a large architectural document for the LF Energy Foundation. He also serves as one of the
co-chairs for the Kubernetes documentation special interest group (SIG Docs). Kubernetes was his
first open source software project, and it quickly became one of the most prolific projects in
modern open source. Its rapid growth allowed Corleissen to own important aspects of its
documentation, and revise it to become more reader-friendly.

"Insisting that code is self-documenting is a form of gatekeeping [and] an example of an unhealthy
project culture," Corleissen says. "I think the devaluation often comes from developers who see a
static generator stack and think, 'How hard can it be?' One of my least favorite dismissive phrases:
'It’s just a pile of Markdown.' If only it were that easy! Documentation is code for an environment
where no chipsets are identical; kernel defaults are hostile; RAM is variable; storage is subject to
random external dependencies; and production regularly fails despite optimal conditions, or
inversely, succeeds in spite of obvious CI failures."

To track progress, the SIG Docs group does a quarterly review where they measure the progress of
their previous quarter’s goals and prioritize work for the upcoming quarter. One of their
community rules centers on ownership: In order to adopt a goal, a project needs a specific person
willing to drive it.

**Step three: Create and enforce a clear code of conduct**

If your project doesn’t already have a code of conduct (CoC), it’s never too late to make one (refer to
this guidebook’s chapter on governance for tips of getting started). They are an expectation for
modern open source initiatives, from long-term projects to two-day conferences.

In my own research for this chapter, several open source contributors told me they won’t consider
joining new projects that lack clear CoCs. For these URMs, the risk of joining an unwelcoming if not
hostile community is too high. "Having a code of conduct would be big for me," explains Natalie
Zamani (She/Her), Senior Software Engineer at Apple. "And then something as seemingly unrelated
as not tolerating project contributors espousing racist/sexist/homophobic/transphobic ideas, even if
it’s not related to their project work. I wouldn’t feel comfortable working with individuals who hold
such views, full stop. And I’ve seen a few projects that would otherwise be interesting to me where
that’s tolerated."

As the former President and Chairperson of the Board of Directors for the GNOME Foundation,
Sanchez helped create GNOME’s event CoC. She says that while the Contributor’s Covenant is the
default code of conduct for a lot of open source communities, translating it to an events format took
some creative work—and a lot of feedback from the GNOME community.

"No matter the type of CoC you’re rolling out, having a transparent plan and timeline is key,"
Sanchez says. "At GNOME, we created a working group after one of our annual conferences to start
drafting a code of conduct. We passed the notion of a working group by the Board of Directors to


make sure that they were on board. They made a community-wide announcement letting people
know the process: A working group would be drafting the CoC, sending it to community for
revisions, the Board would then see the revised draft and vote, and then the membership would
vote at the Annual General Meeting."

Despite the key role of community feedback, Sanchez says the CoC should be owned by a governing
body within your project. CoCs remain a touchy subject in open source communities, and not all
open source contributors believe they’re necessary. A governing body (or at least a committee)
composed of diverse contributors that shares the creation process can help alleviate disagreements.
Once you’ve created your governing body, assign members to own specific tasks. These include a
chair who can break voter ties, moderators to enforce the code of conduct, and mentors to train the
community. It’s essential for all community members—especially URMs—to see project leaderships
protect their safety and integrity.

"I am a firm believer that signalling is very important, but that broken trust is difficult to repair,"
Eising explains. "Don’t signal to [underrepresented people] that you are ready to embrace them
before you actually are—that’s like inviting someone who uses a wheelchair to a party on [an
upper] floor with no elevator. That person won’t trust you again to think about their needs
appropriately. Organizations need to look within and really assess before making a reach-out."

**Step four: Reward contributions beyond code**

In her time working on open source, Sanchez says that most projects focus on attracting
contributors to a narrow set of project work: Engineering, design, translation, documentation, and
outreach. Despite how broad that sounds, she says the table below reflects many more roles and
types of contributions she’d like to see rewarded.

Use this table as part of your outreach efforts, focusing on specific career areas and development
goals. Help people to see themselves as part of the project, showing how their skills and experiences
in a career area can map to where they can contribute to the project.

_Table 1. Aligning project role to career goals and skillsets_

```
Career development target Teams within OSS orgs to
check out
```
```
Why
```
```
Sales and business development Fundraising, partnerships Both of these things require you
to pitch the value of the open
source community / project and
require you to develop your
communication and negotiation
skills, among other things.
```

**Career development target Teams within OSS orgs to
check out**

```
Why
```
Marketing skills Engagement, marketing, or
outreach teams

```
Some projects may not even
have this set up and are in need
of someone to help. Even if you
don’t have a lot of experience in
this, you may have more
experience than anyone else in
that community and it’s your
chance to build something from
scratch. This could look really
amazing on a resume!
```
Strategy skills Board of directors / governance
team, community team

```
It depends a bit on the maturity
of the organization, but
typically there’s a lot of room
for building your strategy skills
when on a board of directors.
You have a birds-eye view of
the project, typically have say
over project finances, and can
help define goals and move the
project forward at a whole new
level. Since you can’t get there
right away, leading initiatives
can help you build those skills
and there’s often a lot of room
for people to step in and own
big chunks on open source
community teams.
```
Data science skills Community team, board of
directors

```
What kind of data is being
collected to ensure that
initiatives are successful?
Measuring a community’s
health is something that more
and more people are interested
in and there’s a need for those
interested in data analysis to
help.
```

```
Career development target Teams within OSS orgs to
check out
```
```
Why
```
```
Graphic design skills Marketing team, technical
projects
```
```
There’s a lot of need for graphic
design for brand and marketing
initiatives, and in general to
help make the project more
mature. Some projects may not
even have established brand
guidelines, and there’s a big
need for more designers in
general.
Project management and
program management skills
```
```
Engagement, marketing,
outreach, documentation,
community teams
```
```
There is a huge need for highly
organized people who can
create processes and structure.
Many initiatives fall to the side
because there isn’t someone to
help push it along and make it
happen.
Product management skills Any technical project, new
initiatives, website, newcomers
initiatives
```
```
Product managers (PM) are
essential at companies, and yet
it’s something that isn’t always
easily found within open source
software. There’s a lot of room
for PMs to jump in to help
create more innovative
products and help bridge the
gap between communities and
businesses, helping to expand
each project’s reach.
Legal skills Board of directors or
community team
```
```
There’s a growing need for
more people who are able to
navigate open source related
legal matters. Lawyers may get
a lot of great experience
working on community teams
or sitting on the Board of
Directors.
HR/people skills Board of directors, community
team, newcomers initiatives
```
```
We need people who care about
people and want to make the
community awesome.
```
This list isn’t exhaustive, nor is it applicable to all projects. For more on this topic, refer to this
guidebook’s chapter on the range of roles in open source projects. The goal is to look at your own
open source project’s holistic needs in the short and long terms, then recruit contributors to fill
specific gaps. Doing so allows you to create a governing board with representatives that own
specific aspects of the project and contribute to its growth.


Nithya Ruff (She/Her) leads the Open Source Program Office for Comcast and serves as Chair of The
Linux Foundation Board. In more than two decades of open source work, she has seen how
ignoring crucial skills—including legal issues such as copyrights and trademarks—can keep a
project from achieving long-term success. Recruiting and rewarding diverse contributions also
plays a key role in preventing burnout, which project maintainers have been increasingly vocal
about.

"It is unfair to expect the maintainer or the developer who started the project or leads the project to
care for all of these issues, [or] have the skills to do it," Ruff says. "All forms of contribution need to
be valued [because this] brings diversity of people into the project, which makes the project more
vibrant and innovative. Foundations like the Apache Software Foundation [and] Linux Foundation
bring all of these contributions to the table for their hosted projects. This allows the project to more
successfully build a broader ecosystem."

**Step five: Mentor new talent to grow and lead the project**

Eleven years after co-founding Redis, Salvatore Sanfilippo announced plans to step down as Project
Maintainer of the NoSQL database. He named Yossi Gottlieb and Oran Agra as his successors to
maintain the Redis project. In doing so, the Redis governance model got a refresh.

Rather than keeping Redis’s prior BDFL style, Gottlieb and Agra built a new, lighter governance
model. It involves electing a small group of longtime Redis developers to act as core contributors
and uphold the project’s Code of Conduct.

Regardless of your own project’s governance model, you must include a way to train key
contributors to assume leadership roles. This achieves three key goals:

1. Helping new contributors learn how they can grow
2. Rewarding contributors who own key aspects of the project
3. Preventing maintainer burnout

This last point is noteworthy: Sanfilippo said when he stepped down from Redis that despite his
passion for coding, he never aspired to maintain a project. Without new leaders to step up—and
documentation sharing how contributors can assume such roles—maintainers risk either working
on projects when they no longer want to or having the project stall. Likewise, the project risks
missing an opportunity to give interested contributors a chance to step up.

The act of building and maintaining a mentorship program is inclusive in itself. Several open
source leaders interviewed for this book said they see a clear need for more mentorship in open
source at large, and a desire to do it themselves. In some cases, open source contributors believe so
much in the power of mentorship that they restructured their contributions to include it. And,
because they were mindful of their own time limitations, they offered flexibility to new leaders as
well.

"My open source contributions definitely changed even before I became a parent," explains Oda.
"As the coordinator for a global mentoring program that happens in the summer, I had to plan
some years ahead to build a volunteer team that could do everything I do. So, I handed off some of
my other projects more completely and never went back to them.


"Since new moms typically get less than one hour of free time per day, the key for me has been
aligning the open source I want to do with the open source that work wanted to pay me for. I
worked to take [the] CVE Binary Tool open source after I returned from maternity leave, and
worked with my boss to make sure I could have time to mentor students as part of my maintainer
role."

To build your own mentorship program, Sanchez says to focus on four actions and initiatives:

```
Create learning opportunities often. Find ways to help people learn what
you do and how you do it. Don’t just wait for formal internship or
mentorship programs, but take advantage of those if you can. Consider
recording videos, holding AMAs, participating in events, etc. Be open to
communicating with people informally in order to build relationships and
trust so that you can help develop those with potential. Cast your net wide
and you’ll probably find those gem contributors who are ready to step in to
help bring your project to a whole new level.
```
```
Be a connector. Try to have a mental map of prominent contributors in your
community and their strengths. Share the mentorship by introducing
newcomers to several people. Burnout is real on the mentor side and you
want to make sure that there are other people your mentee can reach if you
need to take a break or just get busy.
```
```
Make sure that there’s a chat tool specifically for community interactions. In
order to build trust, people need private spaces. Chat facilitates
conversations and collaboration, and also allows people to message you
directly. To avoid burnout, you may want to have a chat tool available just
for your community / work conversations and a chat tool just for your
personal life. That way, you can turn off all notifications on one tool if you
need a break, or just simply have that mental separation thanks to
differences in UX.
```
```
Connect through events. Events provide a powerful opportunity for you to
connect with potential mentees. At these events, try to plan fun activities
that are designed to help people connect informally. This may mean having
a people-bingo where people have to ask each other questions to enter a
raffle, or it could be a city tour, or a game night. Fun activities throughout
the year can facilitate authentic relationships, which can also help people
overcome fear of contribution.
```
For more ideas around mentoring in open source communities, refer to this guidebook’s chapter on
building a culture of mentorship.


**Step six: Commit to continuous improvement**

The work of inclusion is never done: It’s ongoing. As your project grows, you will find new gaps to
fill, questions to document, and additions to your Code of Conduct. As your community becomes
more inclusive, it might feel like you’re finding more ways you’ve fallen short. Uncomfortable as
this is, it’s actually a good thing. It means you’ve done the hard work of committing to keep on
getting better. And, if you’ve done the work of building an inclusive team, you won’t do this work
alone. Instead, you’ll share the work with your community, giving everyone the chance to share
their feedback.

To keep the dialogue ongoing and open, give your community options to leave feedback on their
experiences. This can range from quarterly surveys to giving contributors the freedom to create
channels in your project’s communication platforms to chat about mental health, being a person of
color, how to handle negotiations, etc. Such channels give contributors ways to connect socially,
which is crucial for increasing asynchronous collaboration. It also gives you new ways to support
contributors so they can contribute more fully.

"I am hearing-impaired, and I requested that the All Things Open conference consider [hearing
impairment] when in larger venues where keynotes were speaking and there were no specific
adaptations [in the venue] for those of us who were not able to hear," explains Don Watkins
(He/Him), a community correspondent for OpenSource.com who has been active in the Linux
community for two decades. "Specific adaptations were added [by All Things Open] for those us
were not able to hear."

"I was particularly impressed when attending the Creative Commons Global Summit in Toronto in
2018, where nearly all presentations were accompanied by folks who signed and also provided
simultaneous closed captioning of all speakers."

Inclusion isn’t a one-time pull request: It’s an ongoing, important activity. Without building and
sustaining inclusive communities, there’s no hope of improving diversity of open source
contributors. To recruit new talent, prevent maintainer burnout, and create affirming online
environments, open source maintainers should commit to inclusion. Change starts from within,
and when technology contributors from a variety of backgrounds see your inclusive efforts, they
will be much more likely to join.

"Make it easy for people to get involved and to contribute back," says Ruff. "The mark of a good
project is not how complex it is, but how easy it is to get involved."

[ 2 ] For a sample style guide, see PEP 8 — Style Guide for Python Code or the style guide for contributing to Mozilla Firefox, a project
that employs multiple programming languages in its development.
[ 3 ] https://www.drupal.org/about accessed June 22, 2020 05:43 CET
[ 4 ] Kubernetes home page, https://kubernetes.io/, accessed June 22, 2020 05:57 CET
[ 5 ] The authors are grateful for the work of Kent C.Dodds and Sara Drasner in their article An Open Source Etiquette Guidebook,
accessed 24 June 2020 12:52 CET.
[ 6 ] Gaia Vince, Evolution explains why we act differently online
[ 7 ] _https://producingoss.com/en/producingoss-letter.pdf, page 64, accessed 24 June 2020 11:46 CET
[ 8 ] _https://www.dreamwidth.org/legal/diversity_ accessed 2 July 2020 13:37 CET (and how leet it is :)
