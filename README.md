# cs188 - sp24

[![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=flat-square&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://zread.ai/darstib/cs188)

> 中文 | [English](README_en.md)

> [!warning]
> 
> 基于课程代码 license：
> 
> ```py
> # Licensing Information:  You are free to use or extend these projects for
> # educational purposes provided that (1) you do not distribute or publish
> # solutions, (2) you retain this notice, and (3) you provide clear
> # attribution to UC Berkeley, including a link to http://ai.berkeley.edu.
> ```
> 
> 撤去直接可运行代码，project 解释笔记保留，fork 仓库不予负责。

## 介绍

[这个仓库](https://github.com/Darstib/cs188)存放的是 UCB [CS 188 Spring 2024](https://inst.eecs.berkeley.edu/~cs188/sp24/) 的笔记&自学资料；理论上，你学习该课程所需要的全部资料都可以在这里及给出的外链中找到，项目来自 [ai.berkeley.edu](http://ai.berkeley.edu).

- 笔记：主体为原课程 notes[^1]，加入了自己的思考和排版，在[我的博客](https://darstib.github.io/blog/note/CS188/)上你可以阅读这些笔记；~~但为了更好的观感，建议使用 obsidian 查看~~[^2]，见使用-阅读。
- 自学资料：由于 UCB 近年的部分课程开始需要 [CalNet Authentication Service](https://auth.berkeley.edu/cas/login?service=https%3a%2f%2finst.eecs.berkeley.edu%2f%7ecs188%2fsp23%2f)，为了便于之后的学习，将我认为自学需要的资料存档于[本仓库](https://github.com/Darstib/cs188)；由于不清楚如何申请转载权限，故若[本项目](https://github.com/Darstib/cs188)对[原课程](https://inst.eecs.berkeley.edu/~cs188/sp24/)及其相关项目产生不良影响，请[联系我](https://darstib.github.io/blog/connect_me/) 删除。
- 如果对[搜索算法](https://oi-wiki.org/search/)了然于心、对 ML/DL/RL 知识较为熟悉且希望接触一些小的项目文件，大可直接做 project。

[^1]: 其一，我不能确保我的翻译正确性；其二，网页/obsidian 阅读已经能够借助很多插件辅组阅读，可参考[读 / 写文章](https://darstib.github.io/blog/collection/Tools/#i4)；其三，本人精力有限，恕不能完全打造一个 CS188 全中文阅读环境。

[^2]: 【20250319】更，现在通过插件转换已经使得 mkdocs 与 obsidian 能够直接衔接，直接阅读在线网站即可。

- 【20250619 更】本学期刚好选了一门统计机器学习的课程，感觉更加理解了之前学 cs188 时一知半解的东西，在 prerequisite 中添加了对应的链接（下面是一些介绍，与 cs188 没有直接联系；现在看来，cs188 更多像一个 toy，不过也是很符合课程名称的）
	- 一方面来自 [AI 算法工程师手册]()，是一个涉及面更加全、完整的中文资料；
	- 另一方面来自 [Data modeling and analysis](https://darstib.github.io/blog/note/DMA/ )，是我学习学校《数据建模与分析》课程时，借助 gemini 2.5 处理 ppt 后，自己边学边调整的笔记，我觉得讲的还是挺清晰的（在学这门课之前我的数理统计能力近乎高中水平）；
	- 同时部分难点参听了[王木头学科学](https://space.bilibili.com/504715181)，细致好理解，可惜 up 很久没更了。

## 目录

### note&project

- Intro
    - [01-Intro_to_AI_Rational_Agents](note/01-Intro_to_AI_Rational_Agents.md)
    - [project-0](project/project-0.md)
- Search
    - [02-State_Spaces_Uninformed_Search](note/02-State_Spaces_Uninformed_Search.md)
    - [03-Informed_Search_Astar_and_Heuristics](note/03-Informed_Search_Astar_and_Heuristics.md)
    - [04-Local_Search](note/04-Local_Search.md)
    - [project-1](project/project-1.md)
- Multi-Agent Search
    - [05-Trees_Minimax_Pruning](note/05-Trees_Minimax_Pruning.md)
    - [06-Expectimax_Monte_Carlo_Tree_Search](note/06-Expectimax_Monte_Carlo_Tree_Search.md)
    - [project-2](project/project-2.md)
- Logic and Classical Planning
    - [07-Propositional_Logic_and_Planning](note/07-Propositional_Logic_and_Planning.md)
    - [08-DPLL&ForwardChaining](note/08-DPLL&ForwardChaining.md)
    - [09-First_Order_Logic](note/09-First_Order_Logic.md)
    - [project-3](project/project-3.md)
- Ghostbusters
    - [10-Intro_to_Probability](note/10-Intro_to_Probability.md)
    - [11-Bayesian_Network_Intro](note/11-Bayesian_Network_Intro.md)
    - [12-Variable_Elimination](note/12-Variable_Elimination.md)
    - [13-Approximate_Inference](note/13-Approximate_Inference.md)
    - [14-Markov_Models](note/14-Markov_Models.md)
    - [15-Hidden_Marko_Models](note/15-Hidden_Marko_Models.md)
    - [16-PF-DN-VPI](note/16-PF-DN-VPI.md)
    - [17-Markov_Decision_Processes](note/17-Markov_Decision_Processes.md)
    - [project-4](project/project-4.md)
- Machine/Reinforcement Learning
    - [18-Iteration](note/18-Iteration.md)
	- [19-Navie_Bayes](note/19-Navie_Bayes.md)
	- [20-Perceptron](note/20-Perceptron.md)
	- [21-Regression](note/21-Regression.md)
	- [22-Neural_Networks](note/22-Neural_Networks.md)
	- [24-Reinforcement_Learnin](note/24-Reinforcement_Learnin.md)
	- project5/6 无讲解
		- project 6 - Q7 代码已完成，但是训练结果很差，无处调试，遂放弃。

### materials

- course_page
	- 课程网站的 calendar，便于查看如何自学；
- disc
	- 相关讨论题及其题解；
- origianl_note
	- 课程原笔记，理论上查看上述本人 note 足矣；
- project
      - original_zip
          - 原 project 源码；
    - intro_page
        - 保留的实验文档的页面文件。
    - ~~[solution](https://github.com/Darstib/cs188/tree/main/project/solution)~~
        - ~~参考代码（移动至 `cs188/project/solution/` 中）~~
        - 基于课程代码 license，撤去直接可运行代码
- [gradecode](https://www.gradescope.com/)
    - `4VK322`

## 使用

### 下载

#### 使用 git

```shell
git clone https://github.com/darstib/cs188.git
```

#### 直接全部下载

![](attachments/README.png)

#### 部分下载

如果只是想要 note 或者 project 部分或者其他单独一个文件夹，可以使用 [DownGit](https://download-directory.github.io/)，输入目标文件夹在此 git 仓库的 url 即可。

### 阅读

> 从头开始获取一个比较好的阅读体验可以看[这里](https://darstib.github.io/blog/tutorial/begin/Obsidian_begin/#ii)；要求不高的话简单版如下：

1. 获取 [obsidian](https://obsidian.md)；
2. [导入 markdown](https://publish.obsidian.md/help-zh/import/markdown)；
3. 点击右上角进入阅读视图即可。

![](attachments/README-1.png)
