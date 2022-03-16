---
title: Simulating Language
description: Academic year 2021/2022
---

This is the webpage for the Honours/MSc course Simulating Language, running in academic year 2021/2022. We will add links to materials (readings, videos, code) to this page; you will need to use Learn for electronic submission of your assessed work, and to keep an eye out for any course announcements.


## Course summary

In this course we are going to be using simulation models to study language. People use various types of models in linguistics for a number of purposes; in this course we are going to focus using models to study how processes of learning, communication and evolution shape linguistic systems, and we'll primarily be using agent-based Bayesian models (don't worry, we'll explain what that means!).

This is a practical course: you'll be running and tinkering with code for computational models written in python. You don't need to be programmer to take the course - no programming knowledge is assumed, and we are doing everything in the simplest way we can think of, building from the ground up. But you will be doing stuff with code, so you have to be prepared to give it a go, dive in, and try stuff out. Don't worry, we'll help you figure it out.

## The teaching team

[Simon Kirby](http://www.lel.ed.ac.uk/~simon/) is the lecturer for this course, and Asha Sato is in charge of labs and assessements. The best way to get in touch with us is in one of the drop-in lab sessions, see below, or by messaging on Teams. Please don't email.

## Structure of the course

The course is based around a series of ten lectures, which take place one per week. Each lecture is followed by a programming practical, which you attemt in your own time, and get help with in a drop-in lab session. Each lecture may have readings associated with it.

### Readings

The week-by-week reading content is at the bottom of this page. The readings consist of our notes plus a mix of journal papers and book chapters.

For some of the lectures the reading is flagged up as being **pre-reading**, i.e. we will assume you have done this preparatory work prior to the lecture and will design the lecture accordingly (i.e. we might refer to stuff in the preparatory materials or ask you questions about it).

You should always complete the reading materials and attend/watch the lecture before attempting the programming practical or attending the drop-in lab classes - the practicals involve playing with models that implement the ideas covered in the readings and lecture recordings, so will make a lot more sense when you have that context.


### Lectures

- Lectures are **Fridays 2.10pm-3pm** in F.21, 7 George Square

Lectures start in week 1, i.e. the first lecture is Friday 21st January. Lectures will be recorded and appear on Learn. We will aim to have the lectures in person, but if this is not possible they will be held live on Teams.

### Practicals and drop-in labs

- Labs are in 4.02, Appleton Tower

You can attempt the programming practical on your own, but we will be providing drop-in labs at set times each week where you can come and get our help to figure out problems. You should come to the drop-in labs if you need help with a specific problem, but you are also welcome to just turn up in drop-in labs to hang out and work through things on your own with us in the background - some people find that having set times helps them focus.

You will be assigned a lab group that will take place at one of the following times starting in week 2:
- Mondays, 11.10am-1pm
- Wednesdays, 1.10pm-3pm
- Thursdays, 1.10pm-3pm

The drop-in labs happen in person if possible, and if this is not possible on Gather. *You will be assigned a lab time and a tutor during week 1*. You can drop in at any time during your session and ask questions, get help with the programming practicals, or just hang out. You can come as much or as little as you want: we'll be sad if we never see you, but you'll probably be sad if you see us too much.

### Chat on Teams

In addition to asking questions in lectures and drop-in labs, we will set up channels on Teams for you to ask questions. If you have a question that you can't ask live, Teams (rather than email) is our preferred way for you to get in touch.

## Assessment

The two assignments involve a mix of practical work and written sections and have the following deadlines:

- 10th March at noon (released 17th February)
- 7th April at noon (released 24th March)

The assignments will be available on Learn to start working on after the last lab that relates to the content being assessed. This will usually be two weeks in advance of the deadline. You will submit your answers on turnitin as usual.

*IMPORTANT* we will not be answering any questions about the assessments! This might seem harsh, but we have learned from painful experience that answering questions about the assessments after they have been handed out causes very serious problems, both in terms of workload for tutors and in terms of being fair for everyone working on the assessments. For example, it strongly disadvantages anyone who starts working on the assessments early, before all the questions have been answered. The only practical and equitable way of dealing with this is to have a perfectly level playing field and not answer any questions until all the assessments have been completed. Think about them more like take-home exams. (N.B. this restriction does not apply if you have a specific adjustment on your student record that allows for clarification on assessment questions. If so, please get in touch with Asha.)

## Course Materials

Dates for lectures and labs shown in brackets.

### 1. Introduction

- Pre-lecture reading: [Introduction to modelling](simlang_reading_1.md)
- [Lecture slides](lecture_slides/lecture1.pdf) (Jan 21)
- Programming practical: [Introduction to Python](simlang_lab_1.md) (Jan 24, 26, 27)

### 2. Concept learning

- Pre-lecture reading: [More on Bayes' Rule](simlang_reading_2.md)
- [Lecture slides](lecture_slides/lecture2.pdf) (Jan 28)
- Programming practical: [Word learning](https://github.com/smkirby/simlang2022/blob/master/lab2.ipynb) (Jan 31, Feb 2, 3)
- Answers to Practical: [Word learning answers](https://github.com/smkirby/simlang2022/blob/master/lab2_answered.ipynb)

### 3. Frequency learning and regularisation

- No new reading - catch up on the readings on Bayes, or read [Xu & Tenenbaum (2007)](https://psycnet-apa-org.ezproxy.is.ed.ac.uk/fulltext/2007-05396-002.html), covered in the previous lecture, for yourself.
- [Lecture slides](lecture_slides/lecture3.pdf) (Feb 4)
- Programming practical: [Frequency learning and regularisation](https://github.com/smkirby/simlang2022/blob/master/lab3.ipynb) (Feb 7, 9, 10)
- Answers to Practical: [Frequency learning and regularisation answers](https://github.com/smkirby/simlang2022/blob/master/lab3_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_3_walkthrough/1_1pyq2qg1)

### 4. Iterated Learning

- Post-lecture reading: [Bayesian iterated learning](simlang_reading_4.md)
- [Lecture slides](lecture_slides/lecture4.pdf) (Feb 11)
  - [Video of uniform prior](lecture_slides/lecture4_videos/posterior_uniform.mp4)
  - [Video of regularity prior](lecture_slides/lecture4_videos/posterior_regularity.mp4)
  - [Code for generating these videos](lecture_slides/lecture4_videos/lecture4_figures.ipynb)
- Programming practical: [Bayesian iterated learning](https://github.com/smkirby/simlang2022/blob/master/lab4.ipynb) (Feb 14, 16, 17, 28, Mar 2, 3)
- Answers to practical [Bayesian iterated learning](https://github.com/smkirby/simlang2022/blob/master/lab4_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_4_walkthrough/1_kv20uefj)
- *Logarithms for the concerned*: a supplementary walkthrough in three parts
  - [online slides](https://centre-for-language-evolution.github.io/simlang2021/LogExplainer.slides.html#/)
  - [notebook](https://github.com/smkirby/simlang2022/blob/master/LogExplainer.ipynb)

### 5. Communication and the RSA model

- Reading: [The Rational Speech Act model](simlang_reading_5.md)
- [Lecture slides](lecture_slides/lecture5.pdf) (Mar 4)
- Programming practical: [The Rational Speech Act model](https://github.com/smkirby/simlang2022/blob/master/lab5.ipynb) (Mar 7, 9, 10)
- Answers to Practical: [The Rational Speech Act model](https://github.com/smkirby/simlang2022/blob/master/lab5_answered.ipynb)

### 6. Compositionality

- Reading: [The evolution of compositionality](simlang_reading_6.md)
- [Lecture slides](lecture_slides/lecture6.pdf) (Mar 11)
- Programming practical: [Compositionality](https://github.com/smkirby/simlang2022/blob/master/lab6.ipynb) (Mar 14, 16, 17)
- Answers to Practical: [Compositionality](https://github.com/smkirby/simlang2022/blob/master/lab6_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_6_walkthrough/1_cv3bptoq)


### 7. Hierarchical models and learning the prior **Cancelled due to industrial action**

- Reading: [Hierarchical models and learning to learn](simlang_reading_7.md)
- [Lecture slides](lecture_slides/lecture7.pdf) 
- Programming practical: [Hierarchical learning](https://github.com/smkirby/simlang2022/blob/master/lab7.ipynb)
- Answers to Practical: [Hierarchical learning](https://github.com/smkirby/simlang2022/blob/master/lab7_answered.ipynb)

### 8. Innateness and culture

- Reading: [Innateness and culture in the evolution of language](simlang_reading_8.md)
- [Lecture slides](lecture_slides/lecture8.pdf) (Mar 18)
- Programming practical: [Convergence to the prior](https://github.com/smkirby/simlang2022/blob/master/lab8.ipynb) (Mar 28, 30, 31)
- Answers to Practical: [Convergence to the prior](https://github.com/smkirby/simlang2022/blob/master/lab8_answered.ipynb)


### 9. Biological and cultural evolution together

- Reading: [Gene-culture co-evolution](simlang_reading_9.md)
- [Lecture slides](lecture_slides/lecture9.pdf) (Apr 1)
- Programming practical: [Co-evolutionary modelling](https://github.com/smkirby/simlang2022/blob/master/lab9.ipynb) (Apr 4, 6, 7)
- Answers to Practical: [Co-evolutionary modelling](https://github.com/smkirby/simlang2022/blob/master/lab9_answered.ipynb)


### 10. This view of language

- Reading: [Overview of this view of language](simlang_reading_10.md)
- [Lecture slides](lecture_slides/lecture10.pdf) (Apr 8)


## Re-use

This page was written by Simon Kirby, based on https://centre-for-language-evolution.github.io/simlang2021/, written by Kenny Smith and Simon Kirby. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).