### 宣发软件

**介绍**

One of any open source project’s functions is releasing software with the goal of reaching as many
users as possible. To help projects succeed, you’ll need to ensure that you distribute news of your
release in a timely fashion, to the widest relevant audience, and with the right information.
任何开源项目的功能之一就是宣发软件，目的是让尽可能多的用户了解。
为了帮助项目成功，你需要确保及时向最广泛的相关受众发布你的发行消息，并提供准确的消息。


遵循一些发布公告的基本准则，可以确保你出色的工作不会在一片混乱中被浪费。记住，这些只是指南；你所在社区的做法可能有所不同。

**一般准则**

- 不要为周五或重要假日设定任何发布日期。覆盖面最大的理想发布日期是星期二。
- 如果可能的话，请将重要发布与相关会议和活动相协调。
- 定制发布公告和博客，以鼓励对软件的使用以及对其的贡献。
- 讲述一个项目如何为用户带来益处；而不是专注于技术细节。

**方针：对主版本的待定版本和最终发布（X.0）**

对主版本（X.0）遵循或顺应如下流程:

1. 距离发布日期不少于三周:
    a、创建一个协作文档（Etherpad，Google Doc）来凸显功能，包括发布公告、新闻稿和博客文章。
2. 发布日期于两周以内。
    a、生成一份更新日志，概述需要记录并包含在主更新日志文件中的，此次发布的显著变化。记录并包含在主更新日志文件中。
    b、将更新后的更新日志中的任何相关内容合并发布到公告、新闻稿和博客文章中。

```
c、创建新闻稿，并发送给你的组织的媒体关系团队进行审核。
```

3. 发布日期于一周以内：
    a、在发布日期之前、期间和之后安排社交媒体内容的分发。
4. 距发布日期三天：
    a、确认发布经理和总工程师已经签署并发布了公告和博客文章。
    b、确认媒体关系人员已经签署了新闻发布。
5. 距发布日期两天：
    a、完成所有最终的质量保证（QA）/冒烟测试(smoke tests)。
    b、在适当的服务器上搭建架构。
    c、将所有的文件分阶段进行审查，以显出其问题。
6. 距发布日期一天
    a、向相关媒体发送新闻稿副本。
7. 发布日：
    a、将所有的代码和文档开放。
    b、开始发布预定的社交媒体和博客文章材料。
    c、在新闻媒体上发布新闻稿（与媒体关系团队合作）。

**方针：使用 X.Y 版本号发行待定版本或最终版本**

遵循或顺应这个过程，进行Y版本点发布（X.Y）：

1. 距发布日期不少于两周:
    a、创建一个协作文档（Etherpad，Google Doc）来凸显功能，包括发布公告、新闻稿和博客文章。
2. 距发布日期一周
    a、在发布日期之前、期间和之后安排社交媒体内容的发布。
    b、生成一份更新日志，概述需要记录并包含在主更新日志文件中的，此次发布的显著变化。记录并包含在主更新日志文件中。
    c、将更新的更新日志中的任何相关内容合并发布到公告和博客文章中。
3. 距发布日期两天：
    a、确认发布经理和总工程师已经签署并发布了公告和博客文章。
    b、完成所有最终的质量保证（QA）/冒烟测试(smoke tests)。
    c、在适当的服务器上搭建架构。
    d、将所有的文件分阶段进行审查，以显出其问题。

    

4. 发布日：


    ```
    a、将所有的代码和文档开放。
    b、开始发布预定的社交媒体和博客文章材料。
    c、向相关媒体发送新闻稿副本。
    ```
**方针：次要版本点X.Y.Z的最终发布**

遵循或顺应这个过程来完成对较小的Z版本点的发布 （X.Y.Z）:

1. No less than one week from release date:
    a.Schedule social media content for distribution before, during, and after release date.
    b. Generate a changelog outlining notable changes to the release that will need to be
    documented and included within the main changelog file.
    c. Merge any relevant content from the updated changelog into the release announcement and
       blog post.
1. 距发布日期不小于一周：
    a、在发布日期之前、期间和之后，安排社交媒体内容的发布。
    b、生成一份更新日志，概述需要记录并包含在主更新日志文件中的，此次发布的显著变化。记录并包含在主更新日志文件中。
    c、将更新的更新日志中的任何相关内容合并发布到公告和博客文章中。
2. 距发布日期两天
    a、确认发布经理和总工程师已经签署并发布了公告和博客文章。
    b、完成所有最终的质量保证（QA）/冒烟测试(smoke tests)。
    c、在适当的服务器上搭建架构。
    d、将所有的文件分阶段进行审查，以显出其问题。
3. Day of release:
    a.Make all release artifacts and documentation visible to the world, if not already (release
       may be synced to mirrors ahead of actual release announcement).
3. 发布日：
    a、将所有的代码和文档开放，如果还没有的话。（发布版本可以在实际发布前同步到镜像上）。
    b、开始发布预定的社交媒体和博客材料。

**在所有主要版本点和重要版本点发布之后**

1. 进行一次回顾，看看有什么可以做的，以改善下一个发布周期。

**撰写新闻稿/发布公告**

Writing and distributing a release announcement would seem relatively straightforward; however,
some strategies for doing this work are more effective than others. Specifically, you should write
your release announcement in a way that makes it most likely for a media outlet to pick it up.
撰写和发布发布公告似乎相对简单；但是，做这项工作的一些策略比其他策略更有效。具体来说，你应该以一种使媒体最有可能接受它的方式来写你的发布公告。

下面是一个发布公告的模板，其中有一些指南。请注意，这只是一个指南；完全照搬这里的内容可能对你的项目没有效果。


对你在公开声明中分享的信息要直接和符合事实。避免夸大其词（"有史以来最好的项目！！"）和臆测（"唯一能做到这一点的项目"）。媒体很快就会无视这种夸张的说法，并可能完全避免传播你发布的消息。

发布公告不是炒作你项目的机会（尽管以此为目的而使用它们可能很诱人）。你可以而且应该利用这个机会感谢你努力工作的社区。这样可以把功劳归于那些做了工作的人，并强调项目的免费和开源性质。

要清楚、简洁。用事实支持你的主张。这将有助于使你的公告得到更广泛的传播。

**新闻稿/发布公告**

```
Project X, the [main purpose of project: goals, functions, governance...]
project, today announced the general availability of Project X x.y, a
community-driven [description of project]. This latest community release
includes several new features, including [list of newest features].
```
```
项目X，[项目的主要目的：目标、功能、管理...]项目今天宣布了Project X x.y的普遍可用性，这是一个由社区驱动的[项目描述]。这个最新的社区版本有几个新功能，包括[最新功能列表]。
```

```
由全球社区开发的X项目是一个[详细的段落，其中包括该项目是什么，它能做什么，以及任何其他相关的信息应包括在这里]。
```

项目X x.y版本的显著增强包括：

[描述第一个主要功能的详细段落]

[描述第二个主要功能的详细段落]

[描述第三个主要功能的详细段落]
```

```
项目X x.y功能的完整列表可在项目X社区发布公告页面[URL]看到。项目X x.y [详细描述两到三个额外的功能]。
```

```
[如果可能的话，请在这里添加一位著名的社区成员或技术负责人关于新版本的引言。］
```

```
**附加资源**

- 阅读更多关于X项目x.y版本的亮点[URL]。
- 在推特上获得更多的X项目更新[URL]。
- 阅读更多关于Project X社区活动的信息[URL]。

**关于项目X**

```
X项目是[对该项目是什么,以及它能做什么的非常详细的描述]。
```