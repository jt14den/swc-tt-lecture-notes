* <<< [01 Welcome](01-welcome)

### key points

* Novices: don’t know what they don’t know.
* Competent practitioners: have a usable mental model that’s good enough for everyday purposes.
* Expert: can handle edge cases.
* Goal when teaching novices is to help them construct a usable mental model.
* To do this, must clear up their misconceptions.
* Summative assessment: done at the end of teaching to see whether learning took place.
* Formative assessment: done during teaching to guide learning.
* Can use multiple choice questions (MCQs) as formative assessments to diagnose misconceptions.
previous episode


* Let's get started by learning some theory, how it relates to SWC and putting the theory into practice.

### Cognitive Development & Mental Models

* Effective learning is facilitated by the creation of mental models of a domain
* What do we mean by mental model?
  * One example: many of us learned that the ball-and-spring model of  molecules
  * molecules aren't balls and springs; their bonds not springs
  * but the model does a good job of helping people reason about molecules, chemical compounds and their reactions

>### Your mental models
>In the Etherpad, write your primary research domain or area of expertise and one mental model you use to frame and understand your work? This discussion should take about 5 minutes.
>> Me - Work in the library provide data services - help researchers and students with their research, provide instructions on tools that make them more productive

* one way to think about the difference b/t **novice and "competent practicioner"** is the existence of the **big picture** mental model
  * See: Brenner, who applied the [Dreyfus model of skill aquisition](https://en.wikipedia.org/wiki/Dreyfus_model_of_skill_acquisition) in studies on how nurses progress from novice -> expert
* This model has three stages:
  1. **novice** is someone who doesn't know what they don't know
    * has not built a mental model of a domain or how elements of the domain relate
    * often reason by analogy and guesswork, misapply other parts of other domains to the new one
    * signature of novice is their questions **aren't even wrong**
  2. **competent practicioner** has a mental model good enough for everyday purposes: Not completely accurate, but useful
    * e.g. average drivers mental model of a working car typically doesn't include the complexity of what a mechanic knows
    * can do normal tasks with normal effort under normal circumstances
  3. **expert** can easily handle situations that are nonnormative

* **We assume most learners coming to SW/D/LC workshop are novices** and do not have strong mental models for the concepts we teach
* Our **primary goal** is not to teach syntax of a particular programming language, but to teach people how to think about programming and data management
  * AND about using computers in research more generally

## WHY GO SLOW - Why we go slowly

* The transition from novice to competent practicioners involves the contstruction of right (enough) categories:
  * building a new mental model of this new intellectual domain
  * goal of edcuation for novices is to help them form correct categories
  * **until** they've done that trying to load information on them confuses more than educates

>## Manual v. Tutorials
>In the Etherpad, describe the difference between a manual and a tutorial in terms of the differences between novices and competent practitioners. Can one document do a good job of being both? This discussion should take about 5 minutes.
{: .discussion}

* one reason SW dev so frustrating
* Ref material is opaque to someone who doesn't know what they don't know (noviceo w/o a mental map).
* Likewise, tutorials that help build such a map are too slow and diffuse for people who already have one
  * it is poss. to make something that serves both groups, but often easier to address their needs separately
* An example of the practial implications of this: our Unix lesson only introduces 12 commands and typically spends 2.5 hours to cover
  * 12.5 minutes per command may seem very slow, but the lesson's real purpose is to teach learners about paths, history, wildcards, pipes and filters, command-line arguments, redirection and the other big ideas the shell depends on (and without which ppl can't understand how to use commands or read their manual pages).
  * That model also includes:
    * DRY - anything you repeat manually, you'll ultimately get wrong (so make the computer repeat things for you by using *tab* completion and the *history* command)
    * Lots of little tools, combined as needed are more productive than a handful of "kitchen sink" programs (motivates the pipe-and-filter model and segues to functions)

* Illustrates: Learning more than just building mental models & pouring in information
  * Creating linkages between concepts and facts is as important
  * Telling people not to repeat things, and they should think in terms of little pieces loosely joined
  * Both set the stage for introducing functions
  * Explicitly referring back to pipes and filters when introducting functions helps solidfy both ideas

## Building Useful Mental Models

* There are many **positive** strategies for building mental models: analogies, stories, role-play, and diagrams are ways to represent a structure that can be used as a model

* **However** there's a greater challenges to creating mental models:

> It ain't what you don't know that gets you into trouble.
> It's what you know for sure that just ain't so.  
> — Mark Twain

* Clearning up learners misconceptions is as important as presenting them with correct information.
* their misconceptions may fall into three categories:
  * Simple *factual errors*, such as believing that St. Louis is the capital of Missouri.These are simple to correct,
    but getting the facts right is not enough on its own.
    * *Broken models*, believing that motion and acceleration must be in the same direction. We can address these by having them reason through examples to see contradictions.
    * *Fundamental beliefs*, such as "the world is only a few thousand years old" or "human beings cannot be affecting the planet's climate". These usually cannot be addressed in class, since they are deeply connected to the learner's social identity
    and often cannot be reasoned away.
* 4 i's - insufficient, inappropriate, inaccurate  

* Since SW & D Carpentry are focused on novices, and helping build strong mental models, we're most interested in the middle category of misconceptions
* During teaching, we want to expose broken models so that we can diagnose and provide better ones.

> ## What Happens Next?
>
> An example of how solving problems can help people correct broken mental models,
> consider this problem from Epstein's *[Thinking Physics][amazon-thinking-physics]*.
> Imagine that you have placed a cake of ice in a bathtub
> and then filled the tub to the rim with water.
> When the ice melts,
> does the water level go up (so that the tub overflows),
> go down,
> or stay the same?
> The correct answer is that it stays the same;
> figuring out why helps people build a model of the relationship between weight, volume, and density.

## Accessing mental models

* How do we expose misconceptions, especially in how they related to mental models.???
* HOw can we do this in-class and know whether learners already understand the topic? (so we can move forward)
* and if not, what we need to address in their misconceptions?

* **Instructors** need feedback on learners' progress and insight into their mental models
* This is usually done through two kinds of assessments:
  * *summative assessment* is used to tell if the desired learning took place and wwhter the learner can move ahead
    * either fail for pass, e.g. driving exam that tells the rest of society whether someone can saftely drive
  * *formative assessment* takes place during teaching and learning
    * main purpose: to guide by telling both instructor and learner what to focus on
    * not pass or fail
    * e.g. a music teacher might ask a student to play a scale very slowly to see if she is breathing correctly and if not to correct  
    * secondary purpose is to prepare learners for summative assessments: don't test what wasn't in the lesson

* For us, we are mostly concerned with formative assessments
* This needs to e quick to administer and evaluate
* Most widely employed is multiple choice questions (MCQs)
  * if designed well these can do much more than measure how much someone knows
  * e.g. supposed we are teaching children multi-digit addition
  * a well designed MCQ could be:

  ~~~
  Q: what is: 27 + 15 ?
  a) 42
  b) 32
  c) 312
  d) 33
  ~~~

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

* each incorrect answer is a **plausible distrator** with **diagnostic power**
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

### tips
* instructors should use MCQs or some ofther kind of formative assessment at least every 10-15 min to insure the class is learning
* Since the average attention span is usually only this long, formative assessments help break up instruction time and re-focus attention
* formative assessmentscan also be used preemtively:
  * if you start a class with MCQ and everyone gets it, you can skip the part of the lecture
> ## Peer Instruction
>
> No matter how good a teacher is,
> she can only say one thing at a time.
> How then can she clear up many different misconceptions
> in a reasonable time?
>
> The best solution developed so far is a technique called
> *[peer instruction][wikipedia-peer-instruction]*.
> Originally created by Eric Mazur at Harvard,
> it has been studied extensively in a wide variety of contexts, including programming.
> Peer instruction combines formative assessment with student discussion and looks
> something like this:
>
> 1.  Give a brief introduction to the topic.
> 2.  Give students an MCQ that probes for misconceptions
>     (rather than simple factual knowledge).
> 3.  Have all the students vote on their answers to the MCQ.
>     1.  If the students all have the right answer, move on.
>     2.  If they all have the same wrong answer,
>         address that specific misconception.
>     3.  If they have a mix of right and wrong answers,
>         give them several minutes to discuss those answers with one another
>         in small groups (typically 2-4 students)
>        and then reconvene and vote again.
>
> As [this video][peer-instruction-video] shows,
> group discussion significantly improves students' understanding
> because it forces them to clarify their thinking,
> which can be enough to call out gaps in reasoning.
> Re-polling the class then lets the instructor know if they can move on,
> or if further explanation is necessary.
> A final round of additional explanation and discussion after the correct answer is presented
> gives students one more chance to solidify their understanding.
>
> Peer instruction is essentially a way to provide one-to-one mentorship in a scalable way.
> Despite this,
> we usually do not use it in our workshops because
> it takes people time to learn a new way to learn---time
> that we don't have in our compressed two-day format.

> ## Modeling Novice Mental Models
>
> Take 10 minutes to create a multiple choice question related to a topic you intend to teach.
> Type it into the Etherpad
> and explain the diagnostic power of each its distractors,
> i.e., what misconception is each distractor meant to identify?

> ## A Note on MCQ Design
>
> *   A good MCQ tests for conceptual misunderstanding rather than simple factual knowledge.
>     If you are having a hard time coming up with diagnostic distractors,
>     then either you need to think more about your learners' mental models,
>     or your question simply isn't a good starting point for an MCQ.
> *   When you are trying to come up with distractors,
>     think about questions that learners asked or problems they had
>     the last time you taught this subject.
>     If you haven't taught it before,
>     think about your own misconceptions
>     or ask colleagues about their experiences.
{: .callout}

> ## Concept Inventories
>
> The [Force Concept Inventory][wikipedia-fci]
> is a set of MCQs designed to gauge understanding of basic Newtonian mechanics.
> By interviewing a large number of respondents,
> correlating their misconceptions with patterns of right and wrong answers to questions,
> and then improving the questions,
> it's possible to construct a very precise diagnostic tool.
> However,
> it's very costly to do this,
> and students' ability to search for answers on the internet
> is an ever-increasing threat to its validity.

* Designing an MCQ with plausible distractors is useful even if it is never used in class
* it forces the instructor to think about the learners' mental models and how they might be broken---in short,
to put themselves into the learners' heads
and see the topic from their point of view.

> ## Other Kinds of Formative Assessment
>
> In the Etherpad, describe another kind of formative assessment you have seen or used
> and explain how it helps both the instructor and the learner figure out
> where they are and what they need to do next.
>
> This discussion should take about 5 minutes.
