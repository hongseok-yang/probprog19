# CS492 Probabilistic Programming, Spring 2019, KAIST 

This is a webpage of the course "CS492 Probabilistic Programming", which is offered at the KAIST CS department in the spring of 2019. The webpage will contain links to lecture slides and other course-related materials.

Probabilistic programming refers to the idea of developing a programming language for writing and reasoning about probabilistic models from machine learning and statistics. Such a language comes with the implementation of several generic inference algorithms that answer various queries about the models written in the language, such as posterior inference and marginalisation. By providing these algorithms, a probabilistic programming language enables data scientists to focus on designing good models based on their domain knowledge, instead of building effective inference engines for their models, a task that typically requires expertise in machine learning, statistics and systems. Even experts in machine learning and statistics may get benefited from such a probabilistic programming system because using the system they can easily explore highly advanced models.

This course has two goals. The first is to help students to be a good user of an expressive probabilistic programming language.  Throughout the course, we will use a particular language, called [Anglican](http://probprog.ml/anglican/), but we will emphasise general principles that apply to a wide range of existing probabilistic programming systems. The second goal is to expose the students to recent exciting results in probabilistic programming, which come from machine learning, statistics, programming languages, and probability theory.  

## 1. Important Announcements

#### [February 25] [Homework0](https://github.com/hongseok-yang/probprog19/blob/master/Homework/Homework0/homework0.pdf) is out.

You don't have to submit your answer. But we strongly recommend you to try it. This homework will teach you how to run Anglican.

#### [February 25] Project group.

The group project is an important part of this course. Find your project partners by March 13 2018, and inform all of Hongseok, Hyunsu and Kwonsoo by email. Each group should consist of 3-4 students. Finally, if your group wants to go for Track B, contact Hongseok as early as possible by email. 

## 2. Logistics

#### Evaluation

* Final exam (40%). Project (40%). Homework (20%).

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com, office hours: 6:00pm - 7:00pm on Monday at the room 3403 in the E3-1 building)
* TA1: Kwonsoo Chae (email: kwonsoo.chae@gmail.com, office hours: to be announced)
* TA2: Hyunsu Kim (email: khszone02@kaist.ac.kr, office hours: to be announced)

#### Place and Time

* Place: room 111 in the N1 building
* Time: 1:00pm - 2:15pm on Monday and Wednesday from 25 February 2019 until 10 June 2019.
* Final exam: 1:00pm - 3:00pm on 10 June 2019 (Monday) at the room 111 in the N1 building.

#### Online Discussion

* We will use KLMS. 

## 3. Homework

Submit your solutions by putting them in the homework submission box in the third floor of the E3-1 building.

* [Homework0](https://github.com/hongseok-yang/probprog19/blob/master/Homework/Homework0/homework0.pdf) - Don't submit.

## 4. Tentative Plan

* 02/25 (Mon) - Introduction. [Slides](https://github.com/hongseok-yang/probprog19/blob/master/Lectures/Lecture1/Lecture1.pdf). [Homework0](https://github.com/hongseok-yang/probprog19/blob/master/Homework/Homework0/homework0.pdf).
* 02/27 (Wed) - Basics of Clojure and Tiny Bit of Anglican. 
* 03/04 (Mon) - Basics of Clojure and Tiny Bit of Anglican. 
* 03/06 (Wed) - Posterior Inference, Basics of Anglican, and Importance Sampling. 
* 03/11 (Mon) - Posterior Inference, Basics of Anglican, and Importance Sampling. 
* 03/13 (Wed) - Generative Modelling with Anglican. 
* 03/18 (Mon) - Generative Modelling with Anglican. 
* 03/20 (Wed) - Markov Chain Monte Carlo. 
* 03/25 (Mon) - Markov Chain Monte Carlo. 
* 03/27 (Wed) - Markov Chain Monte Carlo. 
* 04/01 (Mon) - Implementing Inference Algorithms for Probabilistic Programs. 
* 04/03 (Wed) - Group Project Pitch.
* 04/08 (Mon) - Implementing Inference Algorithms for Probabilistic Programs.
* 04/10 (Wed) - Implementing Inference Algorithms for Probabilistic Programs. 
* __**04/15 (Mon), 04/17 (Wed) - NO LECTURES. Midterm Exam.**__
* 04/22 (Mon) - Implementing Inference Algorithms for Probabilistic Programs.
* 04/24 (Wed) - Stochastic Variational Inference. 
* 04/29 (Mon) - Stochastic Variational Inference. 
* 05/01 (Wed) - Amortised Inference. 
* __**05/06 (Mon) - NO LECTURE. Children's Day.**__
* 05/08 (Wed) - Amortised Inference.
* 05/13 (Mon) - Group presentation 1: Causality.
* 05/15 (Wed) - Group presentation 2: Pyro and its internals.
* 05/20 (Mon) - Denotational Semantics of Probabilistic Programs.
* __**05/22 (Wed) - NO LECTURE very likely. Graduate Admission.**__ 
* 05/27 (Mon) - Denotational Semantics of Probabilistic Programs. 
* 05/29 (Wed) - Denotational Semantics of Probabilistic Programs. 
* 06/03 (Mon) - Student Presentation
* 06/05 (Wed) - Student Presentation
* __**06/10 (Mon), 06/12 (Wed) - NO LECTURES. Final Exam.**__

## 5. Studying Materials

Studying the lecture slides and notes and the homework exercises of the course is likely to be the most time-efficient way to catch up with this course. Also, at each lecture, we will give students pointers to the related papers. If a student does not understand a certain concept, we encourage him or her to look it up in the Internet. We typically do this when we encounter a similar problem. In our case, Wikipedia, lecture notes or survey articles have helped us the most.

The next best option is to read the following draft book on probabilistic programming:

1. "[An Introduction to Probabilistic Programming](https://arxiv.org/abs/1809.10756)" by Jan-Willem van de Meent, Brooks Paige, Hongseok Yang and Frank Wood. Reading this book will give a broader view on probabilistic programming and much deeper understanding into its inference algorithms and their implementations.

If a student feels that she or he lacks background knowledge on machine learning, we recommend him or her to have a look at the following online materials.

2. The online book "[Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)" describes Bayesian Machine Learning using a probabilistic programming system called PyMC. Hongseok found this book easy to follow and good at explaining basics and intuitions. 

3. A more standard reference on machine learning is Bishop's book "Pattern Recognition and Machine Learning".

Two good ways to understand probabilistic programming are to try a wide range of examples and to understand common implementation techniques for probabilistic programming languages. The following documents provide such examples or explain those techniques.

4. [Anglican website](https://probprog.github.io/anglican/index.html). In particular, students will learn a lot by trying examples in the site.

5. [Forestdb.org](http://forestdb.org/) is a great source of interesting probabilistic programs. 

6. [Edward tutorial website](http://edwardlib.org/tutorials/) and [Pyro example website](http://pyro.ai/examples/). Edward and Pyro are so called deep probabilistic programming languages that attempt to combine deep learning and probabilistic programming. These web pages contain interesting examples that one can try using these languages. 

7. Goodman and Stuhlmuller's book "[The Design and Implementation of Probabilistic Programming Languages](http://dippl.org/)". This web-based book describes the implementation of [WebPPL](http://webppl.org/), a probabilistic programming language on top of JavaScript. Many techniques in the book are general and apply to other probabilistic programming languages.

Frank Wood taught a graduate-level course on probabilistic programming at UBC. It emphasises on actually building efficient runtimes for probabilistic programming languages. Here is a link to his course.

8. Wood's [graduate-level course](https://www.cs.ubc.ca/~fwood/CS532W-539W/) at UBC.

## 6. Group Project

A group project is a crucial part of this course. 3-4 students will form a project group, and they will carry out a project in Track A or in Track B:

1. **Track A**: A group develops an interesting application of Anglican or other probabilistic programming languages. The members of the group may attempt to find an efficient encoding of a highly complex probabilistic model (such as sequence memoizer) in Anglican,  or they may develop a new probabilistic model for a complex data set and analyse the data set, or they may try to find a novel use of probabilistic programming for solving well-known existing problems (such as figuring out secret key in some security protocol).

2. **Track B**: At most two groups will be on this track. The goal of a group in this case is to study an advanced research topic on probabilistic programming or machine learning, to gain deep understanding about it, and to help fellow students acquire the same level of understanding. Specifically, a group performs an in-depth study on one of two advanced hot topics, causality and Pyro. Then, the group in this track has to teach what it learnt to other students in the course. By teaching, we mean (i) a presentation on the studied topic and (ii) a preparation of reading material and exercise problems. Also, the group has to submit a report on what they learnt. We recommend the report to be 2-to-4 pages long, although it can be longer if needed. Further information about causality and Pyro is given at the end of this webpage.

#### Group (Track A)

#### Group (Track B)

#### Concrete Tasks

1. **[Deadline: midnight on 13 March (Wed)]** Form a group and inform us by email (Hongseok, Hyunsu and Kwonsoo). 
2. **[3 April (Wed)]** Presentation of each group about its topic.
3. **[13 May (Mon)]** Presentation on causality by a group on track B.
4. **[15 May (Wed)]** Presentation on Pyro and its internals by a group on track B.
5. **[3 June (Mon), 5 June (Wed)]** Presentation of group projects.
6. **[Deadline: midnight on June 7 (Fri)]** Submit a report on the project. We recommend each report to be 2-to-4 pages long, although it is fine to write a longer report if needed.

#### Two Topics in Track B

##### **1. Causality** 

Causality refers to attempts for discovering the cause-and-effect relationship among various factors (or variables) from data (and a given set of assumptions), reasoning about the consequence of an intervention (such as medical treatment), and deriving useful information about counterfactuals. It is one of the emerging topics in machine learning, with a lot of blessings from Judea Pearl, a pioneer in the probabilistic approach to machine learning. In particular, bringing deep learning and causality together is one of the active research areas. 

So far causality has not been studied seriously by researchers in the probabilistic programming community, although it may be explained more clearly in the context of probabilistic programming. An ultimate goal of this survey-style group project is to fill in this gap slightly, find out a way of bringing causality and probabilistic programming together, and help students to see the benefits of doing it. Of course, this is a challenging goal, and it is ok to fail. But having such a goal is likely to help students in this project to understand causality better.

Here are a few references on causality.   

  1. Ferenc Husz\'ar's blog articles are good introduction to causality. ([article1](https://www.inference.vc/untitled/), [article2](https://www.inference.vc/causal-inference-2-illustrating-interventions-in-a-toy-example/), [article3](https://www.inference.vc/causal-inference-3-counterfactuals/)). One of the comments of the first article also lists recent papers that attempt to bring deep learning and causality together.

  2. Judea Pearl has been working on causality for many years. [His interview](https://www.quantamagazine.org/to-build-truly-intelligent-machines-teach-them-cause-and-effect-20180515/) gives you a glimpse into the reason for his dedication to this topic. We heard that his recent general-science book "[The Book of Why](https://www.amazon.com/Book-Why-Science-Cause-Effect/dp/046509760X)" was very readable and provided good informal overview on this topic. Pearl's book "[Causality: Models, Reasoning and Inference](https://www.amazon.com/Causality-Reasoning-Inference-Judea-Pearl/dp/052189560X/ref=pd_lpo_sbs_14_img_0?_encoding=UTF8&psc=1&refRID=2Q592JDB4F5N9XZQXH7W)" is the
standard reference. 

The lack of further reference does not mean the lack of related papers. Rather it means that this is an active research topic that we ourselves just started to look at recently.

##### **2. Pyro and its internals** 

Pyro is a probabilistic programming language from Uber, which attempts to bring deep learning and probabilistic programming together. It is still in the middle of being developed. Its design and implementations are not finalised yet, and change constantly. Pyro runs on top of pytorch.

Pyro contains novel language primitives, such as plate, random module and tensor shape for distribution object, which help programmers or data scientists to express their intentions more clearly. Also, its implementation uses interesting techniques, such as poutine, automatic guide generation, and selective marginalisation of discrete random variables using the broadcasting mechanism. These techniques enable efficient probabilistic inference. Finally, there are cool Pyro examples, such as Attend-Infer-Repeat, that use neural networks and probabilistic programming together.   

The goal of this project is to study all of these apsects of Pyro (language design, implementation techniques, and cool examples and libraries), and explain these to the other students. 

   1. The main reference is [Pyro's webpage](http://pyro.ai/). We recommend students in this project to study [the section on examples](http://pyro.ai/examples/) closely. It contain information about examples, languages, implementation techniques, and other libraries. The section even contains [information](http://pyro.ai/examples/minipyro.html) about how to implement a baby version of Pyro.
 
   2. There are language design decisions and implementation techniques shared between Pyro and Edward from Google. The following papers on Edward contain information about how to implement deep probabilistic programming languages. They may help students to grasp what go on in Pyro. However, we advise students to prioritise the study of Pyro's webpage over reading the following papers.  
      
      1. "[Simple, distributed, and accelerated probabilistic programming](https://papers.nips.cc/paper/7987-simple-distributed-and-accelerated-probabilistic-programming.pdf)" by Tran et al. at NeurIPS'18.
      2. "[TensorFlow Distributions](https://arxiv.org/abs/1711.10604)" by Dillon et al. 
