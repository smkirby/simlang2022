This is the webpage for the Honours/MSc course Simulating Language, running in academic year 2020/2021. We will add links to materials (readings, videos, code) to this page; you will need to use Learn for electronic submission of your assessed work, and to keep an eye out for any course announcements.


## Course summary

In this course we are going to be using simulation models to study language. People use various types of models in linguistics for a number of purposes; in this course we are going to focus using models to study how processes of learning, communication and evolution shape linguistic systems, and we'll primarily be using agent-based Bayesian models (don't worry, we'll explain what that means!).

This is a practical course: you'll be running and tinkering with code for computational models written in python. You don't need to be programmer to take the course - no programming knowledge is assumed, and we are doing everything in the simplest way we can think of, building from the ground up. But you will be doing stuff with code, so you have to be prepared to give it a go, dive in, and try stuff out. Don't worry, we'll help you figure it out.

## The teaching team

[Simon Kirby](http://www.lel.ed.ac.uk/~simon/), [Kenny Smith](http://www.lel.ed.ac.uk/~kenny/) and [Matt Spike](https://sites.google.com/site/matspike/) are the main lecturers and lab demonstrators - the best way to get in touch with us is in one of the drop-in lab sessions, see below, or by messaging on Teams. In the drop-in labs we'll be assisted by Claire Graf, [Annie Holtz](https://www.ed.ac.uk/profile/annie-holtz) and Henry Conklin.

## Structure of the course

Each week there is a set reading (which you do in your own time), a lecture (live on Teams), and then a programming practical (which you attempt in your own time, and get help with in the drop-in labs).

### Readings

The week-by-week reading content is at the bottom of this page. The readings consist of our notes plus a mix of journal papers and book chapters. For some weeks also have associated quizzes or mini-tests so you can evaluate your own understanding.

For some of the lectures the reading is flagged up as being **pre-reading**, i.e. we will assume you have done this preparatory work prior to the lecture and will design the lecture accordingly (i.e. we might refer to stuff in the preparatory materials or ask you questions about it).

You should always complete the reading materials and attend/watch the lecture before attempting the programming practical or attending the drop-in lab classes - the practicals involve playing with models that implement the ideas covered in the readings and lecture recordings, so will make a lot more sense when you have that context.

Each week there is a designated academic lead, who sets the readings and presents the lecture - if you have content questions on a given week, the academic lead for that week should be one of your points of contact, but we are all familiar with all of the content so anyone you see at drop-in labs should be able to help!

### Lectures

- Lectures are live on Teams **Tuesdays 2pm-3pm**

Lectures start in week 2, i.e. the first lecture is Tuesday 19th January. Lectures will be recorded and appear on Teams, so if you can't attend (e.g. due to timezone) then you will be able to see what was said.

### Practicals and drop-in labs

You can attempt the programming practical on your own, but we will be providing drop-in labs at set times each week where you can come and get our help to figure out problems. You should come to the drop-in labs if you need help with a specific problem, but you are also welcome to just turn up in drop-in labs to hang out and work through things on your own with us in the background - some people find that having set times helps them focus.

You will be assigned a lab group that will take place at one of the following times in weeks 2-11:
- Thursdays, 9am-11am
- Thursdays, 1pm-3pm
- Fridays, 9am-11am
- Fridays, 2pm-4pm

The drop-in labs happen on gather.town. *You will be assigned a lab time and a tutor during week 1*, and you can find a link to gather.town from your lab group channel on Teams. You can drop in at any time during your session and ask questions, get help with the programming practicals, or just hang out. You can come as much or as little as you want: we'll be sad if we never see you, but you'll probably be sad if you see us too much.

### Chat on Teams

In addition to asking questions in lectures and drop-in labs, we will set up channels on Teams for you to ask questions. If you have a question that you can't ask live, Teams (rather than email) is our preferred way for you to get in touch.

## Assessment

Details to be confirmed, but there will be two assignments, with the following deadlines:

- 4th March at noon
- 8th April at noon

## Course Materials

### Week 1 (commencing 11th January): No class

But make an early start on the reading and preparatory materials for weeks 2 and 3 - note that for week 3 in particular there's a fairly chunky bit of preparatory work.

### Week 2 (commencing 18th January): Introduction
Lead: Kenny Smith
- Pre-lecture reading: [Introduction to modelling](simlang_reading_wk2.md)
- [Lecture slides](lecture_slides/simlang2021_lecture1.pdf)
- Programming practical: [Introduction to Python](simlang_lab_wk2.md)

### Week 3 (commencing 25th January): Concept learning
Lead: Kenny Smith
- Pre-lecture reading: [More on Bayes' Rule](simlang_reading_wk3.md)
- [Lecture slides](lecture_slides/simlang2021_lecture2.pdf)
- Programming practical: [Word learning](https://github.com/centre-for-language-evolution/simlang2021/blob/master/lab2.ipynb)
- Answers to Practical: [Word learning answers](https://github.com/centre-for-language-evolution/simlang2021/blob/master/lab2_answered.ipynb)

### Week 4 (commencing 1st February): Frequency learning and regularisation
Lead: Kenny Smith
- No new reading - catch up on the week 3 readings on Bayes, or read [Xu & Tenenbaum (2007)](https://psycnet-apa-org.ezproxy.is.ed.ac.uk/fulltext/2007-05396-002.html), covered in the week 3 lecture, for yourself.
- [Lecture slides](lecture_slides/simlang2021_lecture3.pdf)
- Programming practical: [Frequency learning and regularisation](https://github.com/centre-for-language-evolution/simlang2021/blob/master/lab3.ipynb)
- Answers to Practical: [Frequency learning and regularisation answers](https://github.com/centre-for-language-evolution/simlang2021/blob/master/lab3_answered.ipynb)

### Week 5 (commencing 8th February): Iterated Learning
Lead: Simon Kirby
- Post-lecture reading: [Bayesian iterated learning](simlang_reading_wk5.md)
- [Lecture slides](lecture_slides/simlang2021_lecture4.pdf)
  - [Video of uniform prior](lecture_slides/lecture4_videos/posterior_uniform.mp4)
  - [Video of regularity prior](lecture_slides/lecture4_videos/posterior_regularity.mp4)
  - [Code for generating these videos](lecture_slides/lecture4_videos/lecture4_figures.ipynb)
- Programming practical: [Bayesian iterated learning](https://github.com/centre-for-language-evolution/simlang2021/blob/master/lab4.ipynb)

### Free week (commencing 15th February): No classes

Catch up, read ahead, start the first assessment, or have a rest.

### Week 6 (commencing 22nd February): Communication and the RSA model
Lead: Kenny Smith
- Reading: The Rational Speech Act model
- Lecture slides
- Programming practical: The Rational Speech Act model

### Week 7 (commencing 1st March): Compositionality
Lead: Simon Kirby
- Reading: The evolution of compositionality
- Lecture slides
- Programming practical: Compositionality

### Week 8 (commencing 8th March): Hierarchical models and learning the prior
Lead: Kenny Smith
- Reading: Hierarchical models, learning to learn, and the shape bias
- Lecture slides
- Programming practical: Hierarchical learning

### Week 9 (commencing 15th March): Biological evolution
Lead: Simon Kirby
- Reading: Introduction to genetic algorithms
- Lecture slides
- Programming practical: Genetic algorithms

### Week 10 (commencing 22nd March): Gene-culture co-evolution
Lead: Simon Kirby
- Reading: Gene-culture co-evolution
- Lecture slides
- Programming practical: Co-evolutionary modelling

### Week 11 (commencing 29th March): This view of language
Lead: Simon Kirby
- Reading: Overview of this view of language
- Lecture slides
- Programming practical: None for this week, but labs open for catch up!


## Re-use

All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
