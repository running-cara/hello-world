## Git入门手册 - Hello World项目
在计算机编程世界里，Hello World是历史悠久的传统。当你开始学习计算机相关的东西，Hello World通常是一个最简单的入门实践。让我们学习Github的Hello World项目。

通过这个项目，你会学到：
- 如何创建和使用一个仓库(repo)
- 开始使用和管理一个分支(branch)
- 改变文件，并提交
- 创建PR(pull request)和合并PR(pull request)

### GitHub是什么
GitHub是一个版本控制和协作的代码管理平台。世界各地的人都可以基于它一起工作。
该手册会介绍GitHub的基本概念，例如仓库、分支、提交和PR。你会创建自己的Hello World仓库，学习GitHub的PR流程（一种流行的创建和评审代码的流程）。

完成该手册，你只需要联网和可用的GitHub的帐号，你无需知道任何代码，命名行工具甚至安装Git.

### 第一步： 创建仓库
一个仓库通常管理一个单独的项目。仓库可以包含目录，文件，图片，视频，表格，数据集合等等项目需要的所有东西。我们建议项目包含README（包含你项目信息的一个文件）。GitHub帮助你在创建新的仓库的同时很方面的创建该文件。证书（License）和其他一些通用文件也可以一样创建。
hello-world仓库就是我们存储我们想法和资源，分享给其他人并和其他人讨论东西的地方。
依据以下步骤创建：
1.  右上角，你的头像旁边，点击’+‘， 选择‘New repository’
2. “Repository name”配置为‘hello-world’
3. 填写‘Description (optional)’为‘Github Hello World项目： 10分钟Github入门’
4. 选择‘Initialize this repository with a README‘
5. 点击‘Create repository.’

### 第二步：创建分支
分支是在一个仓库的不同版本上同时工作的一种方法。
默认，仓库中会有一个叫master的权威分支。我们利用不同分支区提交我们的实验代码提交评审，最后合并到权威分支中。
当你从权威分支上创建分支，你是基于当前结点的权威分支创建了一个复制或者镜像。当你在你所创建的分支上工作时，权威分支有了任何更新，你都应该更新你的镜像。

如下图所示：
1. 我们的权威分支
2. 一个新的命令为‘feature’的分支，则feature分支在合并到权威分支之前的历程为：
在feature分支中提交变化->被评审->通过评审->合并到权威分支

你曾经是否有过通过命名不同的文件名来保存文件不同版本的经历，例如：
```
story.txt
story-joe-edit.txt
story-joe-edit-reviewed.txt
```
在Github仓库中，分支帮助我们达到相似的目标：
在Github中，我们的开发人员和设计者利用独立于权威分支的分支去进行问题解决和新功能的工作，等这些分支没有问题的时候，则将其合并的主分支。

让我们按照以下步骤创建分支：

1. 打开你的hello-world项目的主界面
2. 点击'branch:master'的下拉列表
3. 在新的分支的输入框内填写一个新的分支名字为‘readme-edits’
4. 点击‘Create ....’

这样我们就有了两个分支，一个分支为权威分支，另一个为read-edits分支。到目前为止，它们是一样的。

### 第三步： 更新以及提交更新

在GitHub上，被保存的变化称为提交。每个提交都有相应的提交信息，解释了为什么会有这个提交，然后其他的人会知道你做了什么和为什么这么做。

让我们按照以下步骤来创建和提交更新;
1. 点击README.md文件
2. 点击右上角的铅笔符号
3. 在显示的编辑文本里，写一些关于自己的信息
4. 在页面的下方的填写commit message和description
5. 点击‘Commit changes’

这些更新仅仅存在'readme-edits'分支，至此，我们的'readme-edits'分支和权威分支出现了不同。
### 第四步：创建一个PR
PR是基于GitHub的合作的核心。当你创建了一个PR，也就意味着你提交了你的更新，要求其他人评审和接受你的更新并最终合并到权威分支。PR会展示两个分支的不同。
一旦你提交了你的更新，你就可以创建一个PR，并开始讨论。Github提供了@mention功能，我们还可以去@特定的人去评审我们的代码。
你还可以在你自己的仓库创建PR，并且自己合并。

让我们按照以下步骤为我们刚才的更新创建PR：
1. 点击导航栏的‘Pull requests’
2. 点击‘New Pull Request’
3. 点击‘Compare:base’，选择其为‘Compare:readme-edits’
4. 确定不同和我们预期的一致，
5. 为你的PR编写简要说明
6. 点击‘Create pull request’

### 第五步：合并PR
等你的PR评审通过了，项目负责人，这个时候是你，就可以点击‘Merge pull request’则完成分支的合并。

