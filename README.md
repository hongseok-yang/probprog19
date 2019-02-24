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
* 04/01 (Mon) - Group Project Pitch.
* 04/03 (Wed) - Implementing Inference Algorithms for Probabilistic Programs. 
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

2. **Track B**: At most two groups will be on this track. The goal of a group in this case is to study an advanced research topic on probabilistic programming or machine learning, to gain deep understanding about it, and to help fellow students acquire the same level of understanding. Specifically, a group performs an in-depth study on one of two advanced hot topics, causality and Pyro. Then, the group in this track has to teach what it learnt to other students in the course. By teaching, we mean (i) a presentation on the studied topic and (ii) a preparation of reading material and exercise problems. Also, the group has to submit a 2-page report on what they learnt. Further information about causality and Pyro is given at the end of this webpage.

#### Group (Track A)

#### Group (Track B)

#### Concrete Tasks

1. **[Deadline: midnight on March 13 (Tue)]** Form a group and inform us by email (Hongseok and Kwonsoo). 
2. **[April 5 (Thu)]** Presentation of each group about its topic.
3. **[May 10 (Thu)]** Presentation on automatic differentiation by a group on track B.
4. **[May 15 (Tue)]** Presentation on normalising flow by a group on track B.
5. **[June 5 (Tue), June 7 (Thu)]** Presentation of group projects.
6. **[Deadline: midnight on June 8 (Fri)]** Submit a report on the project. We recommend each report to be 2-to-4 pages long, although it is fine to write a longer report if needed.

#### Two Topics in Track B

So far the former is not directly related to probabilistic programming, but it may become so in the future. Some machine-learning experts predict that causality would become the next big thing. The second topic is Pyro, a probabilistic programming language being developed by Uber. Pyro aims at brining probabilistic programming and deep learning together. The language includes novel language primitives and its implementation uses interesting techniques and optimisations. 

1. **(Reverse-mode) Automatic Differentiation** Automatic differentiation is one of the main driving technologies behind neural nets and deep probabilistic programming languages. Supporting it has been one of the main objectives of Tensorflow and PyTorch, two popular platforms for building neural nets and other machine-learning related software systems. Automatic differentiation is based on nontrivial mathematics; it originates from a non-standard interpretation of mathematical analysis, and its modern generalisation has sometimes been formalised using tools from differential geometry. Pyro, ProbTorch, Edward and Stan heavily use automatic differentiation. A group will have to understand reverse-mode automatic differentiation and explain how it has been or can be used to implement inference algorithms for probabilistic programming languages. Here are a few references that will help a group to find relevant papers.
   1. [Rahul's blog article](https://alexey.radul.name/ideas/2013/introduction-to-automatic-differentiation/). 
   2. [Blog article in Rufflewind's scratchpad](https://rufflewind.com/2016-12-30/reverse-mode-automatic-differentiation).
   3. Baydin et al.'s ["Automatic Differentiation in Machine Learning: a Survey"](https://arxiv.org/pdf/1502.05767.pdf).
   4. Conal Elliott's PEPM18 talk [slides and video](https://github.com/conal/talk-2018-essence-of-ad/blob/master/readme.md).
   5. Automatic differentiation in [PyTorch](http://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html) and [Tensorflow](https://www.tensorflow.org/versions/r0.12/api_docs/python/train/gradient_computation). There is a short [paper](https://openreview.net/pdf?id=BJJsrmfCZ) about the implementation in PyTorch.
   6. [Autograd](https://github.com/HIPS/autograd) aims at implementation a very flexible version of automatic differentation for python.
   7. [Diffsharp](http://diffsharp.github.io/DiffSharp/) is another well-known implementation for automatic differentation for the F# language.

2. **Normalising Flow** Normalising flow is a powerful technique for building an approximating distribution in variational inference. It has been proposed in the context of solving general machine learning problems, but it has become an important construct, called bijector, in recent probabilistic programming languages Edward and Pyro. Here are a few references that will help a group to start its study on this subject:
   1. Eric Jang's blog articles, [first](https://blog.evjang.com/2018/01/nf1.html) and [second](https://blog.evjang.com/2018/01/nf2.html).
   2. Dillon et al.'s paper ["Tensorflow Distribution"](https://arxiv.org/abs/1711.10604) explains the bijector implementation of normalising flow in the probabilistic programming language Edward. 
   3. [Documentation](http://docs.pyro.ai/en/0.1.2-release/transformed_dist.html#) on bijector and inverse autoregressive flow in Pyro.
   4. Rezende and Mohamed's original paper ["Variational Inference with Normalizing Flows"](https://arxiv.org/abs/1505.05770).
   5. Kingma et al.'s paper ["Improved Variational Inference with Inverse Autoregressive Flow"](http://papers.nips.cc/paper/6581-improved-variational-inference-with-inverse-autoregressive-flow).
   6. Germain et al.'s paper ["MADE: Masked Autoencoder for Distribution Estimation"](https://arxiv.org/abs/1502.03509)
