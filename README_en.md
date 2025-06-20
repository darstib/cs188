# cs188 - sp24

> [中文](README.md) | English

> [!warning]
>
> Based on course code license:
>
> ```py
> # Licensing Information: You are free to use or extend these projects for
> # educational purposes provided that (1) you do not distribute or publish
> # solutions, (2) you retain this notice, and (3) you provide clear
> # attribution to UC Berkeley, including a link to http://ai.berkeley.edu.
> ```
>
> Direct runnable code has been removed. Project explanation notes are retained. The fork repository is not responsible.

## Introduction

[This repository](https://github.com/Darstib/cs188) contains notes & self-study materials for UCB's [CS 188 Spring 2024](https://inst.eecs.berkeley.edu/~cs188/sp24/). In theory, all the materials you need to study this course can be found here and in the external links provided. Projects are from [ai.berkeley.edu](http://ai.berkeley.edu).

-   Notes: The main body consists of the original course notes[^1], augmented with my own thoughts and formatting. You can read these notes on [my blog](https://darstib.github.io/blog/note/CS188/). ~~However, for a better viewing experience, Obsidian is recommended~~[^2]. See Usage - Reading.
-   Self-study materials: As some of UCB's courses in recent years require [CalNet Authentication Service](https://auth.berkeley.edu/cas/login?service=https%3a%2f%2finst.eecs.berkeley.edu%2f%7ecs188%2fsp23%2f), I have archived materials that I consider necessary for self-study in [this repository](https://github.com/Darstib/cs188) for easier future learning. Since I am unsure how to apply for reprint permission, if [this project](https://github.com/Darstib/cs188) negatively impacts [the original course](https://inst.eecs.berkeley.edu/~cs188/sp24/) and its related projects, please [contact me](https://darstib.github.io/blog/connect_me/) to remove it.
-   If you are already familiar with [search algorithms](https://oi-wiki.org/search/), comfortable with ML/DL/RL knowledge, and interested in exploring small project files, you can directly tackle the projects.

[^1]: Firstly, I cannot guarantee the accuracy of my translations. Secondly, reading on webpages/Obsidian can be aided by various plugins, refer to [Reading/Writing Articles](https://darstib.github.io/blog/collection/Tools/#i4). Thirdly, due to limited energy, I cannot create a completely Chinese-language reading environment for CS188.

[^2]: 【20250319】Update: Through plugin conversion, mkdocs and Obsidian can now connect directly. You can read the online website directly.

-   【20250619 Update】Coincidentally, I took a Statistical Machine Learning course this semester, which has deepened my understanding of concepts I only partially grasped during CS188. I have added corresponding links to the prerequisites (below are some introductions, not directly related to CS188; in retrospect, CS188 feels more like a toy, but it aligns well with the course title).
    -   On one hand, from the [AI Algorithm Engineer Handbook](https://github.com/OpenL-AI/AI-Algorithm-Engineer-Handbook), which is a more comprehensive and complete Chinese resource.
    -   On the other hand, from [Data modeling and analysis](https://darstib.github.io/blog/note/DMA/), which are my notes from studying the school's "Data Modeling and Analysis" course, adjusted as I learned, with the help of Gemini 2.5 processing PPTs. I believe it explains things quite clearly (before taking this course, my probability and statistics skills were close to high school level).
    -   Additionally, for some difficult points, I consulted [Wang Mutou Learning Science](https://space.bilibili.com/504715181), which is detailed and easy to understand, but unfortunately, the uploader hasn't updated in a long time.

## Table of Contents

### note&project

-   Intro
    -   [01-Intro_to_AI_Rational_Agents](note/01-Intro_to_AI_Rational_Agents.md)
    -   [project-0](project/project-0.md)
-   Search
    -   [02-State_Spaces_Uninformed_Search](note/02-State_Spaces_Uninformed_Search.md)
    -   [03-Informed_Search_Astar_and_Heuristics](note/03-Informed_Search_Astar_and_Heuristics.md)
    -   [04-Local_Search](note/04-Local_Search.md)
    -   [project-1](project/project-1.md)
-   Multi-Agent Search
    -   [05-Trees_Minimax_Pruning](note/05-Trees_Minimax_Pruning.md)
    -   [06-Expectimax_Monte_Carlo_Tree_Search](note/06-Expectimax_Monte_Carlo_Tree_Search.md)
    -   [project-2](project/project-2.md)
-   Logic and Classical Planning
    -   [07-Propositional_Logic_and_Planning](note/07-Propositional_Logic_and_Planning.md)
    -   [08-DPLL&ForwardChaining](note/08-DPLL&ForwardChaining.md)
    -   [09-First_Order_Logic](note/09-First_Order_Logic.md)
    -   [project-3](project/project-3.md)
-   Ghostbusters
    -   [10-Intro_to_Probability](note/10-Intro_to_Probability.md)
    -   [11-Bayesian_Network_Intro](note/11-Bayesian_Network_Intro.md)
    -   [12-Variable_Elimination](note/12-Variable_Elimination.md)
    -   [13-Approximate_Inference](note/13-Approximate_Inference.md)
    -   [14-Markov_Models](note/14-Markov_Models.md)
    -   [15-Hidden_Marko_Models](note/15-Hidden_Marko_Models.md)
    -   [16-PF-DN-VPI](note/16-PF-DN-VPI.md)
    -   [17-Markov_Decision_Processes](note/17-Markov_Decision_Processes.md)
    -   [project-4](project/project-4.md)
-   Machine/Reinforcement Learning
    -   [18-Iteration](note/18-Iteration.md)
    -   [19-Navie_Bayes](note/19-Navie_Bayes.md)
    -   [20-Perceptron](note/20-Perceptron.md)
    -   [21-Regression](note/21-Regression.md)
    -   [22-Neural_Networks](note/22-Neural_Networks.md)
    -   [24-Reinforcement_Learnin](note/24-Reinforcement_Learnin.md)
    -   project5/6 No lectures
        -   project 6 - Q7 Code is complete, but training results are poor. Debugging is not possible, so I've given up.

### materials

-   course_page
    -   Course website calendar, for easy self-study planning.
-   disc
    -   Related discussion questions and their solutions.
-   origianl_note
    -   Original course notes. Theoretically, the notes above should suffice.
-   project
    -   original_zip
        -   Original project source code.
    -   intro_page
        -   Retained page files for experiment documentation.
    -   ~~[solution](https://github.com/Darstib/cs188/tree/main/project/solution)~~
        -   ~~Reference code (moved to `cs188/project/solution/`)~~
        -   Direct runnable code removed based on course code license.
-   [gradecode](https://www.gradescope.com/)
    -   `4VK322`

## Usage

### Download

#### Using Git

```shell
git clone https://github.com/darstib/cs188.git
```

#### Direct Download All

![|600](attachments/README.png)

#### Partial Download

If you only want the notes, projects, or any other single folder, you can use [DownGit](https://download-directory.github.io/). Enter the URL of the desired folder within this git repository.

### Reading

> For a good reading experience from the beginning, you can refer [here](https://darstib.github.io/blog/tutorial/begin/Obsidian_begin/#ii). If you don't have high expectations, a simpler version is as follows:

1.  Get [Obsidian](https://obsidian.md).
2.  [Import Markdown](https://publish.obsidian.md/help-zh/import/markdown).
3.  Click the top-right corner to enter reading view.

![|600](attachments/README-1.png)