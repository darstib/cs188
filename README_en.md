# cs188 - sp24

> [中文](README.md) | English

> [!warning]
>
> Based on the course code license, directly runnable code has been removed. Project explanation notes are retained.  No responsibility is taken for forked repositories.

## Introduction

[This repository](https://github.com/Darstib/cs188) contains notes and self-study materials for UC Berkeley's [CS 188 Spring 2024](https://inst.eecs.berkeley.edu/~cs188/sp24/).  Theoretically, all the materials you need to study this course can be found here and in the provided external links.  The projects are from [ai.berkeley.edu](http://ai.berkeley.edu).

- Notes: Primarily based on the original course notes[^1], with my own thoughts and formatting added. You can read these notes on [my blog](https://darstib.github.io/blog/note/CS188/). However, for a better viewing experience, it's recommended to use Obsidian. See Usage - Reading.
- Self-study materials: Since some of UC Berkeley's recent courses require [CalNet Authentication Service](https://auth.berkeley.edu/cas/login?service=https%3a%2f%2finst.eecs.berkeley.edu%2f%7ecs188%2fsp23%2f), for ease of future study, I've archived the materials I consider necessary for self-study in [this repository](https://github.com/Darstib/cs188).  Due to uncertainty about how to request permission for redistribution, if [this project](https://github.com/Darstib/cs188) has any adverse effects on the [original course](https://inst.eecs.berkeley.edu/~cs188/sp24/) and its related projects, please [contact me](https://darstib.github.io/blog/connect_me/) to remove it.
- If you are familiar with [search algorithms](https://oi-wiki.org/search/), have a good understanding of ML/DL/RL concepts, and wish to explore some small project files, you can directly work on the projects.

[^1]: Firstly, I cannot guarantee the accuracy of my translations. Secondly, reading on the web/Obsidian already allows the use of many plugins to aid reading, see [Reading/Writing Articles](https://darstib.github.io/blog/collection/Tools/#i4). Thirdly, my energy is limited, and I apologize for not being able to completely create a full Chinese reading environment for CS188.

## Table of Contents

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
    - project5/6 No explanation provided.
        - project 6 - Q7 code is complete, but the training results are very poor and there's nowhere to debug, so I gave up.

### materials

- course_page
    - The course website's calendar, for easy reference on how to self-study.
- disc
    - Relevant discussion problems and their solutions.
- origianl_note
    - The original course notes.  Theoretically, reading my notes above should suffice.
- project
    - original_zip
        - The original project source code.
    - intro_page
        - Archived page files of the lab documentation.
    - ~~[solution](https://github.com/Darstib/cs188/tree/main/project/solution)~~
        - Reference code (moved to `cs188/project/solution/`)
- [gradecode](https://www.gradescope.com/)
    - 4VK322.

Based on the course code license:

```
# Licensing Information:  You are free to use or extend these projects for
# educational purposes provided that (1) you do not distribute or publish
# solutions, (2) you retain this notice, and (3) you provide clear
# attribution to UC Berkeley, including a link to http://ai.berkeley.edu.
```

Directly runnable code has been removed. Project explanation notes are retained. No responsibility is taken for forked repositories.

## Usage

### Download

#### Using git

```shell
git clone https://github.com/Darstib/cs188.git
```

#### Download everything directly

![](attachments/README.png)

#### Partial Download

If you only want the notes, projects, or another individual folder, you can use [DownGit](https://download-directory.github.io/). Just enter the URL of the target folder within this git repository.

### Reading

>  For a good reading experience from scratch, you can look [here](https://darstib.github.io/blog/tutorial/begin/Obsidian_begin/#ii).  A simplified version for lower requirements is as follows:

1. Get [Obsidian](https://obsidian.md).
2. [Import Markdown](https://publish.obsidian.md/help-zh/import/markdown).
3. Click the top-right corner to enter reading view.

![](attachments/README-1.png)

