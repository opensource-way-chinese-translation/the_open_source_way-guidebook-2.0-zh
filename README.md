# 请仔细阅读本文后再进行构建！！！

# the_open_source_way-guidebook-2.0-zh

Chinese Translation for the book: "THE OPEN SOURCE WAY 2.0"

《THE OPEN SOURCE WAY 2.0》一书的中文翻译

**本仓库遵循原书的 CC-BY-SA 4.0 协议**

## 翻译流程

对于本书翻译，请**严格**遵循下述流程并**及时关注**流程更新
1. 创建一个 GitHub 账号，并且 Fork 本仓库至自己的账户。
2. `the_open_source_way-guidebook-2.0-en.pdf` 以及 `the_open_source_way-guidebook-2.0-en.md` 两个文件均为英文源文，两个文件用于翻译&排版参考，不应该被编辑。
3. `the_open_source_way-guidebook-2.0-zh.md` 是本书中文译文，一般只在确定翻译稿之后编辑。`translation` 文件夹内使用 **`章节名称`** `->` *`子章节名称.md`* 的方式存储章节翻译，本书所有章节都已经被分开，在接取章节翻译后请直接在单独的子章节文件内进行翻译。`contributors.md` 和 `cover_and_table_of_contents` 暂时不要翻译。
4. 确保你即将要翻译的章节**没有**其他人正在翻译，具体方法是：
   1. 查看**下方 `章节` 部分**，没有打勾的章节是未被翻译完成的
   2. 查看 `Pull Request` 页面，你需要保证此章节没有 Pull Request 被打开（或处于 Draft 状态）
   3. 注意！一人一次只能认领两个小章节，我们希望大家的工作重点在提高质量而非数量上
5. 接下来，确认接取某章的翻译，在你 Fork 到你自己的用户下的仓库中，将对应章节的标题翻译，然后提出 Pull Request，**并将其转换为 Draft**，确保其他人知道你接取了本章节的翻译。Pull Request 标题必须为：`Translation: xxx`，`xxx` 替换为子章节的标题（也是文件的名称）。
6. 进行翻译，在翻译完成后，讲 `README.md` 对应章节前面的 `[ ]` 换成 `[x]` 确认本章已经翻译完成，然后将 Pull Reqeust 从 Draft 转换成 Ready to review，然后在 `Reviewers` 处添加校对人员
7. 在校对人员确认有问题的情况下进行更改，有需要的话进行讨论，最后将 Pull Request 合并入主仓库。
8. 本章翻译流程结束

提交 Pull Request 的时候注意以下几点：
- 我们的工作流程偏好一个 Pull Request **仅包含一个文件的编辑**
（下文中，一个章节代指一个小章节，即为一个单独的 markdown 文件）
- 如果 Pull Request 中出现未完成的内容（不管是否为本PR章节，当然多个章节在一起的这种情况早应避免），那么 Reviewer 可以以 “未完成”（`incomplete`）为理由关闭 Pull Request（如果在 Draft 状态下则不做处理）
- 你可以同时接取多个章节，但是请把每个章节分开独立的分支，避免 Pull Request 时提交多个章节的内容。如果仓库管理和其他拥有相关权限的人发现此情况，他们有权利以 “无效”（`invalid`）为理由关闭 Pull Request
- 如果你发现你编辑了英文源文，请及时回退，否则 Reviewer 可以以 “无效”（`invalid`）为理由关闭 Pull Request

翻译时还请注意：
- 虽然本书的大章节（`##` 标识的的二级标题）和小章节（`###` 标识的的三级标题）都已经被标识出来并分开。但是，你仍然需要参考pdf原文，确保被标识为粗体字（`**xxx**`）但实际上是四级/五级（使用四个或五个`#`标识）标题的文字被正确使用`#`标识。


## 章节

- [x] 开源之路的呈现  
   - [x] 事物的形状（换句话说，我们所做的假设）
   - [ ] Structure of This Guide.  
   - [ ] A Community of Practice Always Rebuilding Itself.  
- [ ] 开始
   - [ ] Community 101: Understanding, Joining, or Forming a New Community  
   - [ ] New Project Checklist.  
   - [ ] Creating an Open Source Product Strategy.  
- [x] 吸引用户  
   - [ ] Communication Norms in Open Source Software Projects.  
   - [ ] To Build Diverse Open Source Communities, Make Them Inclusive First.  
- [ ] Guiding Participants.  
   - [ ] Why Do People Participate in Open Source Communities?.  
- [ ] Growing Contributors.  
   - [ ] From Users to Contributors.  
   - [ ] What Is a Contribution?.  
   - [ ] Essentials of Building a Community.  
   - [ ] Onboarding.  
   - [ ] Creating a Culture of Mentorship  
   - [ ] Project and Community Governance.  
   - [ ] Community Roles.  
   - [ ] Community Manager Self-Care  
- [x] 如何衡量成功
   - [ ] Defining Healthy Communities.  
   - [ ] Understanding Community Metrics.  
   - [ ] Announcing Software Releases.  
- [ ] Contributors.  
   - [ ] Chapters writers.  
   - [ ] Project teams.  
