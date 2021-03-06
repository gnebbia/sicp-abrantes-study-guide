# My personal study guide for SICP

## 1 What is this GitHub repository?

This is my attempt to systematize my study of one of the best computer science
books of all time (some say "the best"), the **[Structure and Interpretation of
Computer Programs (SICP)](http://mitpress.mit.edu/sites/default/files/sicp/index.html)**,
written by Hal Abelson, Jerry Sussman and Julie Sussman.

This book was created for the mythical [6.001 Massachusetts Institute of Technology
(MIT) discipline](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/index.htm), which for 27 years (1980 to 2007) was considered the highest-level
programming discipline in existence. More than [100 universities around the world
have adopted this book](http://mitpress.mit.edu/sites/default/files/sicp/adopt-list.html).

In fact, from the point of view of MIT teachers, you could not be considered a "true"
computer scientist if you did not understand the content discussed in the SICP. Some
quotes to support that vision:

> I've only ever seen one great book on the subject of computer programming: Structure
and Interpretation of Computer Programs (Abelson and Sussman; MIT Press). If you're
already a great programmer, it will take you an evening to read the first few chapters
and you'll discover a precision vocabulary for discussing what you've spent 10 years
learning the hard way. If you're not already a great programmer, I would have thought
that these few chapters would save you from having to spend years flailing around in
the dark. Unfortunately, there doesn't seem to be a substitute for
practical experience.
> Sidenote: the authors used to have a review wall outside their
offices at MIT. University professors from around the world writing in
scientific journals said "finally I understand what all this computer
science stuff is about; this is the most brilliant book ever. I'm glad
that we're using it to teach freshmen now." In the center was a review
from *Byte* magazine: "I didn't understand any of this book."
> - [Philip Greenspun (The Bookshelf of a well-read Web Nerd)](http://philip.greenspun.com/wtr/bookshelf.html)

> The best computer science book in the world.
> - [Brian Harvey](https://people.eecs.berkeley.edu/~bh/)

> MIT set the bar very high for these courses, creating a required course (6.001)
and a textbook (Abelson & Sussman’s Structure and Interpretation of Computer Programs)
which were used at dozens or even hundreds of top CS schools as the de facto introduction
to computer science. (You can, and should, watch an older version of the lectures online.)
> - [Joel Spolsky (The Perils of JavaSchools)](https://www.joelonsoftware.com/2005/12/29/the-perils-of-javaschools-2/)

> The book should be read by every self-respecting computer scientist. Because of its
clarity, simplicity, and wit, this work is highly recommended to anyone seeking an
understanding of the emerging paradigms of computer science.
> - Mitchell Wand (American Scientist)

> Structure and Interpretation of Computer Programs (SICP) is one of the true programming
classics. It's a well-deserved position; SICP is simply the best programming book I've ever
read. I made my first pass through it a year ago but deliberately postponed my review;
reading SICP completely changed the way I approach programming. [...] SICP is one of the
most important books in our field.
> - [Adam Tornhill (SICP Book Review)](https://www.adamtornhill.com/reviews/sicp.htm)

> The book should be obligatory for anyone involved in teaching computer science at
degree level: it will convince them that inside computer science there really is a true
science trying to get out.
> - David Barron (The Times Higher Education Supplement)

Although there are also [criticisms of the SICP](http://cs.brown.edu/~sk/Publications/Papers/Published/fffk-htdp-vs-sicp-journal/),
many programmers are now returning to study it and saying that it has not yet been overcome
([What I Have (Re)-learned From SICP](https://code-and-cocktails.herokuapp.com/blog/2014/07/06/what-i-have-re-learned-from-sicp/)).

A quick Google search for "sicp study guide" will show dozens and more dozens of recent
reports from individual SICP studies, even if MIT itself is [no longer offering this
discipline in its new curriculum](https://mitadmissions.org/blogs/entry/the_end_of_an_era_1/).

This GitHub repository is my individual study guide for SICP. I'm starting now in, February
2019, and I intend to finish within 1-2 years. Feel free to use the materials and codes I will
put here and send me suggestions and criticisms (abrantesasf at gmail dot com).

Have a nice SICP!




## 2 Initial difficulty: how to study?

The main difficulty I had, before starting, was to define a method, a plan for
the study that used the resources available on the internet beyond the book itself.
I spent almost 2 months looking for material on the internet,
and here's the problem: there is a *lot of material* from SICP and MIT 6.001 on
the internet, but all of this stuff is completely disorganized, not systemized,
with many different versions depending on the year/term when 6.001 was taught
at MIT, and so on. The main sources that I found were:

* The main source of material for SICP and MIT 6.001 is [MIT OpenCourseWare 6.001](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/index.htm),
  which provides materials, a reading list, suggested calendar, lecture notes, exams
  and projects. All this resources were derived from MIT 6.001 as the course was taught
  in the Spring/2005, at MIT.
* Video lectures: there are [twenty video lectures](http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/)
  by Hal Abelson and Gerald Jay Sussman, from a presentation of the course to
  Hewlett-Packard employees, on 1986. The [MIT OpenCourseWare 6.001 uses these video
  lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/) and provides a transcript in PDF of everything the teacher said.
  All video lectures are [available for download on the Internet Archives](https://archive.org/details/MIT_Structure_of_Computer_Programs_1986).
* In the original class at MIT there were 2 recitations per week, where the
  students interacted with assistant teachers to solve exercises and clarify
  concepts of the lectures. Much of this stuff has been lost, but there are still
  some on the internet:
  * [6.001 recitation notes, Fall 2005](http://people.csail.mit.edu/fredo/Classes/6001Fall05/), from Frédo Durand
  * [6.001 recitation sections, Spring 2003](http://people.csail.mit.edu/rcm/6001/), from Rob Miller
  * [6.001 recitation, Fall 1997](https://people.csail.mit.edu/dnj/teaching/6001/1997/), from Daniel Jackson
  * [6.001 recitation, Fall 1999](https://people.csail.mit.edu/dnj/teaching/6001/1999/), from Daniel Jackson
  * [6.001 recitation notes, Spring 2004](https://www.cs.rpi.edu/~cutler/6.001/S04/index.html), from Barb Cutler
  * [6.001 recitation notes, Spring 2005](https://www.cs.rpi.edu/~cutler/6.001/S05/index.html), from Barb Cutler
* Various materials, problem sets, lecture notes, handouts, quizzes, and other
  resources, from the years 1996, 1997 and 1998, are available in
  [https://groups.csail.mit.edu/mac/classes/6.001/](https://groups.csail.mit.edu/mac/classes/6.001/).
* The entire original text of the SICP is available under a Creative
   Commons license for online reading in
   [http://mitpress.mit.edu/sites/default/files/sicp/index.html](http://mitpress.mit.edu/sites/default/files/sicp/index.html).
   * There are other versions on internet:
     * A beautifull [HTML5 version](http://sarabander.github.io/sicp/), created by Andres Raba;
     * A beutifull [PDF version](https://github.com/sarabander/sicp-pdf/raw/master/sicp.pdf), created by Andres Raba; and
     * An online [Interactive version](https://xuanji.appspot.com/isicp/index.html), created by Li Xuanji.
   * And, of course, there are the printed versions:
     * SICP on: [Amazon](https://www.amazon.com/Structure-Interpretation-Computer-Programs-Engineering-dp-0262011530/dp/0262011530), [MIT Press](https://mitpress.mit.edu/books/structure-and-interpretation-computer-programs-second-edition)
     * Instructor's Manual to SICP on: [Amazon](https://www.amazon.com/Instructors-Structure-Interpretation-Computer-Programs/dp/0262692201/), [MIT Press](https://mitpress.mit.edu/books/instructors-manual-ta-structure-and-interpretation-computer-programs-second-edition)

Other usefull resources founded:
* The [Ars Digita University (ADUni)](http://www.aduni.org/courses/sicp/) archive
  contains material, videos, handouts, and other resources related to SICP.
* A former "summary" course of the SICP, MIT 6.037, is available on
  [https://web.mit.edu/alexmv/6.037/](https://web.mit.edu/alexmv/6.037/).
* An introductory course to the SICP, MIT 6.090, is available:
  [MIT OpenCourseWare
  6.090](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-090-building-programming-experience-a-lead-in-to-6-001-january-iap-2005/).
* The Berkeley University uses a Python-based version of SICP in its
  _CS 61A: Structure and Interpretation of Computer Program_
  course. Professor John DeNero "rewrote" SICP in Python for Berkeley
  students, and published the book for free on [Composing
  Programs](http://composingprograms.com/). The [CS61A official
  website](https://cs61a.org/) has a lot of material and useful
  resources for study! The Composing Programs book contains links to
  video lectures that accompany each chapter and/or section. A
  complete collection of videos is available on the [The Internet
  Archives](https://archive.org/details/ucberkeley-webcast-PL6879A8466C44A5D5). Uma
  versão mais antiga do curso, ainda baseada em Scheme, pode ser
  encontrada no site da [CS61A de 2011](http://inst.eecs.berkeley.edu/~cs61a/sp11/).

The main difficulties I encountered when starting my studies were the
following:

* MIT OCW x Video Lectures: since the lessons available at MIT OCW are from 2005
  and the video lectures from 1986, the lessons (and also the lecture notes) do
  not exactly match the videos. This creates a reasonable difficulty: you have to
  match the new lessons with the old videos, and this is not always
  obvious. Some old videos are covered in two or more new classes, and
  vice versa. You will have to adapt yourself to this.
* The version of Scheme used in 6.001 classes is Scheme 7.5.1, already very old. The most
  [current version of Scheme is 10.1](https://www.gnu.org/software/mit-scheme/) and this may cause incompatibility
  problems with the original code.

For all these difficulties there is no optimal recipe for the individual study
of SICP. Everyone needs to find the method that works best for themselves.
My study plan is as follows:

1. From the features of MIT OCW, try to follow the suggested schedule as follows:
  * [Read the material in advance](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/readings/)
  * [Watch video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/) (with transcripts)
  * Study the corresponding [lecture notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/lecture-notes/)
2. Study the material of the recitations available on the internet (see above),
  concerning the content of the readings and videos.
3. Answer the problem sets and projects available at MIT OCW and the internet (see above)
4. Answer the problems on SICP book (and on Instructor's Manual).

Files created during my study will be organized into subdirectories that will
indicate the chapter and the corresponding section of the book.




## 3 Summary

As my study progresses, I will add here links to files and codes.
Please note: the content listed below is much larger than the content that was
originally used in MIT 6.001, as the original course had 1 semester (13-16 weeks)
duration. I'm not in a hurry and so I included more stuff.

* **Getting Started**
  * *Step 1: From MIT OCW 6.001*
      * Read the [course home page](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/index.htm)
      * Read the [syllabus](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/syllabus)
      * Familiarize yourself with the [calendar](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/calendar)
      * Familiarize yourself with the [reading list](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/readings)
      * Familiarize yourself with the [lecture notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/lecture-notes)
      * Familiarize yourself with the [video lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures). Download to your computer!
      * Familiarize yourself with the [recitations](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/recitations)
      * Familiarize yourself with the [exams](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/exams)
      * Familiarize yourself with the [projects](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/projects)
      * Familiarize yourself with the [tools](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/tools)
      * Familiarize yourself with the [related resources](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/related-resources)
      * Download the [course materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/download-course-materials) to a directory on your computer
  * *Step 2: From internet, familiarize yourself with recitations resources:*
      * [6.001 recitation, Fall 1997](https://people.csail.mit.edu/dnj/teaching/6001/1997/), from Daniel Jackson
      * [6.001 recitation, Fall 1999](https://people.csail.mit.edu/dnj/teaching/6001/1999/), from Daniel Jackson
      * [6.001 recitation sections, Spring 2003](http://people.csail.mit.edu/rcm/6001/), from Rob Miller
      * [6.001 recitation notes, Spring 2004](https://www.cs.rpi.edu/~cutler/6.001/S04/index.html), from Barb Cutler
      * [6.001 recitation notes, Spring 2005](https://www.cs.rpi.edu/~cutler/6.001/S05/index.html), from Barb Cutler
      * [6.001 recitation notes, Fall 2005](http://people.csail.mit.edu/fredo/Classes/6001Fall05/), from Frédo Durand
  * *Step 3: From internet, familiarize yourself with the the great amount of resources available in
    [https://groups.csail.mit.edu/mac/classes/6.001/](https://groups.csail.mit.edu/mac/classes/6.001/):*
      * [6.001 Spring 1996](https://groups.csail.mit.edu/mac/classes/6.001/ST96/)
      * [6.001 Fall 1996](https://groups.csail.mit.edu/mac/classes/6.001/FT96/)
      * [6.001 Spring 1997](https://groups.csail.mit.edu/mac/classes/6.001/ST97/)
      * [6.001 Fall 1997](https://groups.csail.mit.edu/mac/classes/6.001/FT97/)
      * [6.001 Spring 1998](https://groups.csail.mit.edu/mac/classes/6.001/ST98/index.adp)
      * [6.001 Fall 1998](https://groups.csail.mit.edu/mac/classes/6.001/FT98/index.adp)
  * *Step 4: From MIT OCW, read the [Don't Panic: An Introductory Guide to 6.001 Computer System](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/tools/dontpanicnew.pdf)*
      * Note: there is also a new version (2019) of this document, for *MIT 6.945 Adventures in
        Advanced Symbolic Programming*: [MIT 6.945 Don't Panic](https://groups.csail.mit.edu/mac/users/gjs/6.945/dont-panic/).
        This new version uses Scheme 10.1.5 and provides some utilities to configure
        Emacs or Edwin, and can be very helpfull.
  * *Step 5: Install a recent version of [Emacs](https://www.gnu.org/software/emacs/) and learn how to use it*
  * *Step 6: Install a recent version of [MIT GNU/Scheme](https://www.gnu.org/software/mit-scheme/)*
      * Note: there is also the possibility to use some other Lisp dialect, like
        [Racket](https://racket-lang.org/). You'll have to experiment with this.
  * *Step 7: Learn how to use the [Emacs interface for Scheme](https://www.gnu.org/software/mit-scheme/documentation/mit-scheme-user/GNU-Emacs-Interface.html)*
  * *Step 8: Learn how to use [Edwin](https://www.gnu.org/software/mit-scheme/documentation/mit-scheme-user/Edwin.html)*
  * *Step 9: Get, or buy, a copy of SICP book (see above)*
  * *Step 10: If possible, buy a copy of SICP Instructor's Manual (see above)*
  * *Step 11: Initial readings:*
    * From SICP, read: Foreword, Preface to the First Edition, Preface to the
      Second Edition, Acknowledgments
    * From SICP Instructor's Manual, read: Preface, Acknowledgments
  * *Step 12: You are ready! Let's start!*
* **Chapter 1: Building Abstractions with Procedures**
  * *Section 1.1: The Elements of Programming*
    * Watch the video lecture "[1A: Overview and Introduction to Lisp](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/1a-overview-and-introduction-to-lisp/)"
      and use the [PDF transcript](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/1a-overview-and-introduction-to-lisp/2Op3QLzMgSY.pdf) if necessary
    * Read "[Lecture 1 notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/lecture-notes/lecture1webhand.pdf)"
    * Read "[SICP Chapter 1 Introduction](http://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-9.html)" (pages 1-4)
    * Read "[SICP Section 1.1](http://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-10.html)" (pages 4-31), but do not do the exercises now
    * Read "SICP Instructor's Manual (SICP-IM) Section 1.1" (pages 1-17), but do not do exercises now
    * Clarify concepts with recitations, and do the recitations exercises:
      * [Daniel, 1997: Basics](https://people.csail.mit.edu/dnj/teaching/6001/1997/recitation-1/index.htm)
      * [Daniel, 1999: Interpreters & Evaluation](https://people.csail.mit.edu/dnj/teaching/6001/1999/recitation-01.html)
      * [Rob, 2003: Expressions](http://people.csail.mit.edu/rcm/6001/rec2.html)
      * [Barb, 2004: Scheme Expressions](https://www.cs.rpi.edu/~cutler/6.001/S04/recitation_1.txt)
      * [Barb, 2005: Scheme Expressions](https://www.cs.rpi.edu/~cutler/6.001/S05/recitation_1.html)
      * [Frédo, 2005: Basic Scheme Expressions](http://people.csail.mit.edu/fredo/Classes/6001Fall05/Presentation1.pdf)
    * Do [Problem Set 0, from Fall/1998](https://groups.csail.mit.edu/mac/classes/6.001/FT98/psets/ps0web/),
      and also do [Project 0](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/projects/project0.pdf)
    * Read "[Lecture 2 notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/lecture-notes/lecture2webhand.pdf)" and "[A Story about using Lisp in a Startup Company](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/lecture-notes/lecture2lispstor.pdf)"
    * Clarify concepts with recitations, and do the recitations exercises:
      * [Daniel, 1997: Substitution Model](https://people.csail.mit.edu/dnj/teaching/6001/1997/recitation-2/index.htm)
      * [Daniel, 1999: Kinds of Expression, Evaluation](https://people.csail.mit.edu/dnj/teaching/6001/1999/recitation-02.html)
      * [Barb, 2004: Lambda & Rules for Application](https://www.cs.rpi.edu/~cutler/6.001/S04/recitation_2.txt)
      * [Barb, 2005: Lambda & Rules for Application](https://www.cs.rpi.edu/~cutler/6.001/S05/recitation_2.html)
      * [Barb, 2004: Substition Model](https://www.cs.rpi.edu/~cutler/6.001/S04/recitation_3.txt)
      * [Barb, 2005: Substition Model, Recursion](https://www.cs.rpi.edu/~cutler/6.001/S05/recitation_3.html)
      * [Frédo, 2005: Lambda](http://people.csail.mit.edu/fredo/Classes/6001Fall05/Presentation2.pdf)
    * Do [Problem Set 1, from Spring/1998](https://groups.csail.mit.edu/mac/classes/6.001/ST98/psets/ps1web/)
      and also do [Problem Set 1, from Fall/1998](https://groups.csail.mit.edu/mac/classes/6.001/FT98/psets/ps1web/).
      You can also take a look at other [problem sets from other years](https://groups.csail.mit.edu/mac/classes/6.001/).
    * Do the exercises from SICP, Section 1.1.
    * Do the exercises from SICP-IM, Section 1.1.
  * Section 1.2: Procedures and the Processes They Generate
  * Section 1.3: Formulating Abstractions With Higher-Order Procedures
* **Chapter 2: Building Abstractions with Data**
  * Section 2.1: Introduction to Data Abstraction
  * Section 2.2: Hierarchical DAta and the Closure Property
  * Section 2.3: Symbolic Data
  * Section 2.4: Multiple Representations for Abstract Data
  * Section 2.5: Systems with Generic Operations
* **Chapter 3: Modularity, Objects, and State**
  * Section 3.1: Assignment and Local State
  * Section 3.2: The Environment Model of Evaluation
  * Section 3.3: Modeling with Mutable Data
  * Section 3.4: Concurrency: Time Is of the Essence
  * Section 3.5: Streams
* **Chapter 4: Metalinguistic Abstraction**
  * Section 4.1: The Metacircular Evaluator
  * Section 4.2: Variations on a Scheme - Lazy Evaluation
  * Section 4.3: Variations on a Scheme - Nondeterministic Computing
  * Section 4.4: Logic Programming
* **Chapter 5: Computing with Register Machines**
  * Section 5.1: Designing Register Machines
  * Section 5.2: A Register-Machine Simulator
  * Section 5.3: Storage Allocation and Garbage Collection
  * Section 5.4: The Explicit-Control Evaluator
  * Section 5.5: Compilation
  
