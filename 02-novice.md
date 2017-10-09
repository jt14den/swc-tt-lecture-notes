---
title: "Novices and Formative Assessment"
author: "Tim Dennis"
date: 2017-04-23
---

## Novices and Formative Assessment

**set timer for 65 minutes**

* <https://carpentries.github.io/instructor-training/11-practice-teaching/>
* <https://carpentries.github.io/instructor-training/11-practice-teaching/>

## Pedagogical model

* aim is to teach computataion competence to learners
* we take an applied approach: we show learners how to solve specific problems with specific tools
* learners practice in real-time, get feedback & apply that feedback to next lesson
* workshop is an Interactive event! for learners and instructors
  - provide feedback to learners throughout the workshops in order to get them unstuckor provide a greater depth of understanding
  - iterative,feedback on stickies, able to see where learners are stuck, help un stick

## Acquisition of skill

* our appoach is based on work of researchers like Benner who studied how nurses progress from newbie to experts
* finds that through practice and formal instruction, learners acquire skills
* This model has three stages:
  1. **novice** is someone who doesn't know what they don't know
    * hasn't built a mental model of a domain or how elements of the domain relate
    * often reason by **analogy and guesswork**, misapply other parts of other domains to the new one
    * novice learner might never have heard of bash shell, or how it relates to file system and other programs on their computers
  2. **competent practitioner** has a mental model good enough for everyday purposes: Not completely accurate, but useful
    * might have used the **shell** before and understand how to move around
    * can do normal tasks with normal effort under normal circumstances
  3. **expert** can easily handle situations that are **non-normative**
    1. Problem solving and applying concepts to make a solution

## Cognitive Development & Mental Models

* Effective learning is facilitated by the **creation of mental models of a domain**
* But what do we mean by mental model? **Anybody have an idea?**
* MM is a collection of **concepts** and **facts**, along with **relationships** between those concepts relationships (whiteboard)
  - dataset, project, rows, columns, records, text facet, cluster, transformation, reconciliation
  * for instance: Long term resident of SA advanced understanding of the location of SA provinces, major cities and landmarks, weather patterns, regional economies
  * as well as relationships b/t these entities
  * those of you from SA's mental model of SA is more complex compared to say mine
  * I don't have any idea why joburg had rain yesterday and cape town is in drought conditions - i also am probably misapplying my understanding of weather in the US this Context.

>## (Exercise) Your mental models (in gdocs
>In the Etherpad, under your name write your primary research domain or area of expertise and some aspects of the mental model you use to frame and understand your work. What concepts/facts are included? What types of relationships are included?
> This discussion should take about 5 minutes.
>
> Me - Work in the library provide data services - help researchers and students with their research, provide instructions on tools that make them more productive, small town doctor - put up shingle, help researchers and students with data problems
>
>Review some of the models, get ppl to talk about them

* **key insight** from research on cognitive development: novices, competent practicioners, and experts need to be taught differently
  - in particular presenting novices with a pile of facts early on is counter-productive. **Why do you thing????**
  - they don't yet have a framework to put that into yet
  - can reinforce incorrect model
* **We assume most learners coming to SW/D/LC workshop are novices** and do not have strong mental models for the concepts we teach
* Our **primary goal** is not to teach syntax of code, but to *help novices construct a working mental model* so they have something to attach facts to. add 'text facet': invert, edit, count, etc.; cluster: key collision -> fingerprint, n-gram fingerprint; nearest neighbor methods
* teach people **how to think** about programming and data management
  * AND about using **computers in research** more generally

## WHY GO SLOW - Why we go slowly

> if someone feels it's too slow, they'll be a bit bored. if they feel it's too fast, they'll never come back to programming.
> - skunal marwaha, swc instructor

* Going from **novice to competent practitioners** involves the construction of right (enough) categories:
    * building a new mental model of this new intellectual domain
    * goal of education for novices is to help them form correct categories
    * **until** they've done that trying to load information on them **confuses more than educates**

* An example of the practical implications of this:
  * our Unix lesson only introduces **16 commands** and typically spends 2.5 hours to cover
  * **11 minutes per command** may seem very slow, but the lesson's real purpose is to teach learners about **paths, history, wildcards, pipes and filters, command-line arguments, redirection** and the other big ideas the shell depends on (and without which ppl can't understand how to use commands or even read the manual or help pages).
* That model also includes:
    1. DRY - anything you **repeat manually**, you'll ultimately get wrong (so make the computer repeat things for you by using **tab completion**, **history command** and **for loops**)
    1. **Lots of little tools**, combined as needed, are more productive than a handful of "kitchen sink" programs (motivates the pipe-and-filter model and segues to functions) than a handful of "kitchen sink" programs (motivates the pipe-and-filter model and segues to functions)

* These two examples illustrates something else as well.
* Learning consists of more than **just** building **mental models & pouring in information**
* THAT **creating linkages between concepts** and facts is as important
* Telling people not to repeat things, and they should think in terms of little pieces loosely joined
* Both set the stage for **introducing functions**
* Explicitly referring back to **pipes and filters** when introducing functions helps solidify both ideas

## How knowledge gets in the way

* There are many **positive** strategies for building mental models: analogies, stories, role-play, and diagrams are ways to represent a structure that can be used as a model

* **However** there's a greater challenges to creating mental models:

![Twain](https://static1.squarespace.com/static/56eddde762cd9413e151ac92/t/570cb8885bd33022b93a181b/1460466440544/intaintwhatyouknow.jpg)

> It ain't what you don't know that gets you into trouble.
> It's what you know for sure that just ain't so.
> — Mark Twain

* Clearing up **learners misconceptions** is as important as presenting them with correct information.
* Their misconceptions may fall into three categories:
    * Simple **factual errors**, such as believing that Joburg is the capital of SA (it's Pretoria(executive), bloemfontein judicial, cape town legislative). These are simple to correct, but getting the facts right is not enough on its own.
    * **Broken models**, believing that motion and acceleration must be in the same direction. We can address these by having them reason through examples to see contradictions.
    * **Fundamental beliefs**, such as "the world is only a few thousand years old" or "human beings cannot be affecting the planet's climate". These usually cannot be addressed in class, since they are deeply connected to the learner's social identity and often cannot be reasoned away.

>> teaching R -> Stata
> driving on the wrong side of the road here -- looking the wrong way crossing the street, getting in wrong side.
>
>Do you have any examples of "broken or misapplied models" you'd like to share? Do you remember how it got corrected?

* Since SW & D Carpentry are focused on novices, and helping build strong mental models, we're most interested in the middle category of misconceptions (broken models)
* During teaching, we want to **expose broken models** so that we can diagnose and provide better ones.

## Identifying and correcting misconceptions

### ask the questions?
* What do you think we can do to **surface these misconceptions**, especially in how they related to mental models?
* How can we do this in-class so we know whether learners already understand the topic?

* **we as instructors** need feedback on learners' progress and insight into their mental models
* This is usually done through two kinds of assessments:
    * *summative assessment* is used to tell if the desired learning took place and whether the learner can move ahead
        * either fail for pass, e.g. driving exam that tells the rest of society whether someone can safely drive
        * Other examples?
    * *formative assessment* takes place during teaching and learning
        * main purpose: to guide by telling both instructor and learner what to focus on
        * not pass or fail
        * e.g. a music teacher might ask a student to play a scale very slowly to see if she is breathing correctly and if not correct
        * another purpose is to prepare learners for summative assessments: don't test what wasn't in the lesson
        * v. important in telling learners what they don't know - something that is often hard for learners to determine (mass study - cramming, rereading, highlighting)
        * any examples?

* For us, we are **mostly concerned** with formative assessments
* This needs to quick to administer and evaluate
* Most widely employed is **multiple choice questions (MCQs)**
  * if designed well these can do much more than measure how much someone knows
  * e.g. supposed we are teaching children multi-digit addition
  * a well designed MCQ could be:

PUT in doc:

## Q: what is: 27 + 15 ?

1. 42
2. 32
3. 312
4. 33

  * the correct answer is 42, but each of the other answers provides valuable insight

> ## Find the Bug
>
> Choose one wrong answer and write in the Etherpad what the misconception is associated with that wrong answer.
> This discussion should take about 10 minutes.
{: .discussion}

> ## Solution
>
> *   If the child answers 32, she is throwing away the carry completely.
> *   If she answers 312, she knows that she can't just discard the carried '1',
>     but doesn't understand that it's actually a ten
>     and needs to be added into the next column.
>     In other words,
>     she is treating each column of numbers as unconnected to its neighbors.
> *   If she answers 33 then she knows she has to carry the 1,
>     but is carrying it back into the same column it came from.

* each incorrect answer is a **plausible distractor** with **diagnostic power**
* **plausible** means it looks like it could be right
    * instructors often use supposedly silly answers like "a fish" on MCQs, but:
        * (a) they don't provide insight
        * (b) learners actually don't find them funny
* **diagnostic power** means that each of the distractors helps the instructor figure out what to explain to that learner next

> ## Handling Outcomes
>
> Formative assessments allow us as instructors to adapt our instruction to our audience.
> What should we do as instructors if the class votes for:
>
> 1. mostly one of the wrong answers?
> 2. mostly the right answer?
> 3. an even spread among options?
>
> For one of the above, enter your answer in the Etherpad.
> This discussion should take about 10 minutes.

* if the majority of the class votes for a single wrong answer, you should go back and work on correcting that misconception
* if most vote for right answer, it's probably safe to move on
* if answers are pretty evenly split between options, learners are probably randomly guessing and it's good to go back to where everyone was on the same page

### TIPs in SWC

1. instructors should use MCQs or some of the kind of formative assessment (coding challenge) at least every 10-15 min to insure the class is learning
2. when you give an exercise in S/D/L carpentry, circle the room or have your helpers - use the sticky notes to find folks having difficulty - typically there's a pattern -- talk with your helpers, share
3. formative assessments can also be used preemptively:
4. if you start an episode or section with an MCQ and everyone gets it, you can skip the part of the lecture - studies have shown this acts to prime the pump on your brain to being receptive learning -- getting things wrong critical to learning

> ## (Exercise) Modeling Novice Mental Models
>
> Take 10 minutes to create a multiple choice question related to a topic you intend to teach.
> Type it into the GDoc
> and explain the diagnostic power of each its distractors,
> i.e., what misconception is each distractor meant to identify?

> ### A Note on MCQ Design
>
> *   A good MCQ tests for conceptual misunderstanding rather than simple factual knowledge.
>     If you are having a hard time coming up with diagnostic distractors,
>     then either you need to think more about your learners' mental models, or your question simply isn't a good starting point for an MCQ.
> *   When you are trying to come up with distractors,
>     think about questions that learners asked or problems they had
>     the last time you taught this subject.
>     If you haven't taught it before,
>     think about your own misconceptions
>     or ask colleagues about their experiences.
{: .callout}

#### Concept Inventories The [Force Concept Inventory][wikipedia-fci]
is a set of MCQs designed to gauge understanding of basic Newtonian mechanics. Others exist.

## MCQ to determine learners POV
* Designing an MCQ with plausible distractors is useful even if it is never used in class
* it forces the instructor to think about the learners' mental models and how they might be broken---
* in short,
to put themselves into the learners' heads
and see the topic from their point of view.

> ## Other Kinds of Formative Assessment
>
> What other kinds of formative assessment you have seen or used? Can you think
> how it helps both the instructor and the learner figure out where they are and what they need > to do next?
>
> This discussion should take about 5 minutes.

* Other formative assessments:
    * Concept maps
    * Have students write their understanding
    * Muddiest point: "what is the muddiest point in today's class"
    * Clarity grid - ask waht concepts make the most sense, what is muddy.

### key points

  * Novices: **don’t know what they don’t know**
  * Competent practitioners: have a **usable mental model** that’s good enough for everyday purposes.
  * Expert: can handle **edge cases**.
  * Goal when teaching novices is to help them **construct a usable mental model**.
  * To do this, must **clear up their misconceptions** in their prior knowledge.
  * **Summative assessment**: done at the end of a class to see whether learning took place.
  * **Formative assessment**: done during teaching to guide learning.
  * Can use **multiple choice questions (MCQs)** as formative assessments to diagnose misconceptions.
