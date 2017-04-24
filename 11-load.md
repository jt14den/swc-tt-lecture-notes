---
author: "Tim Dennis"
title: "Cognitive Load"
date: 2017-04-23
---

1. [Novices and Formative Assessment](02-novice) (20/45m)
2. [Expertise and Memory](08-memory) (30/15m)
3. **[Cognitive Load](11-load) (20/20m)**
4. [Live Coding](13-live) (30/45m)
5. [Lessons and Objectives](19-lessons) (30/20m)

**set timer for 40 minutes**

## Start

* Our final topic in educational psychology, we'll be learning about human memory -- specifically how to remove unnecessary 'load' in order to facilitate learning.

## Battling Theories

* In 2006, Kirschner, Sweller and clark published a paper titled “Why Minimal Guidance During Instruction Does Not Work: An Analysis of the Failure of Constructivist, Discovery, Problem-Based, Experiential, and Inquiry-Based Teaching”.
* They say (**READ**):

>Although unguided or minimally guided instructional approaches are very popular and intuitively appealing … these approaches ignore both the structures that constitute **human cognitive architecture** and evidence from empirical studies over the past half-century that consistently indicate that **minimally guided instruction** is less effective and less efficient than instructional approaches that place a strong emphasis on guidance of the student learning process. The advantage of guidance begins to recede only when learners have sufficiently high prior knowledge to provide “internal” guidance.

* This paper set off a minor academic scuffle:
    * Mainly b/c the authors were claiming **[inquiry-based learning](https://en.wikipedia.org/wiki/Inquiry-based_learning)** (sometimes also called **Problem-based learning**)-- allowing learners to ask their own questions, set their own goals, and find their own paths thru subjects -- doesn't work very well.
    * Kirshcher and authors' argument was that learners need to simultaneously master a **domain's factual content** and its **search and problem solving strategies**.
    * And although fostering creativity and independence is intuitively alluring, it doesn't mean that it works

  * Sweller (a co-author on the paper - *Why minimal guidance during instruction doesn't work*) proposed an alternative based on the theory of **[cognitive load](https://en.wikipedia.org/wiki/Cognitive_load)**
  * this theory postulates:
    1. **intrinsic load** is what they (learners) have to keep in mind in order to carry out a learning task
    2. **germane load** is (the desirable) mental effort required to create linkages between new information coming in and old information we already have (**germane load** is one of the things that distinguishes learning from **rote memorization**)
    3. **extraneous load** is everything else that distracts or gets in the way

  * **cognitive load theory's** proponents claim that eliminating extraneous cognitive load accelerates learning
      * it also has [been criticized](https://edtechdev.wordpress.com/2009/11/16/cognitive-load-theory-failure/), most particularly for being unfalsifiable or un-confirmable.
      * critics say that since there's no way to tell in advance of an experiment whether something is **germane or not**, any result can be justified after the fact just by labelling that hurt performance as "extraneous" and things that don't (or enhance/enable) as "germane".

**That said, some predictions *can* be made:**

* One example is Moreno and Mayer's work on the [split-attention effect](https://en.wikipedia.org/wiki/Split_attention_effect)
    * Linguistic and visual input are processed by different parts of the human brain, and linguistic and visual memories are stored separately too.
    * this means that correlating **different linguistic, auditory and visual streams of info takes cognitive work**:
        * when someone reads one thing while hearing something else spoken aloud, their brain can't help but check that it's getting the same info in both channels
    * differences between these channels increase cognitive load and stymie or decelerates learning
    * **THEREFORE** learning is more effective when information that is being presented simultaneously in different channels is the same
    * **for our workshops** this means the instructor should say out loud commands as they type them on the screen during live coding.

## Faded Examples

* Per **cognitive load theory**, searching for a solution strategy can be an extra burden on top of applying that strategy
* we can therefore accelerate learning by giving learners **worked examples** that show them a problem and a detailed **step-by-step solution**, followed by a series of ***faded examples***
* the first example presents a nearly-complete use of the same problem-solving strategy just demonstrated with a small number of blanks for the learner to fill in
* the next problem is also of the same type, but has more blanks, and *so on* until the learner is asked to solve the entire problem.

* **faded examples** work because they introduce the **problem-solving** strategy piece by piece
* each step learners have one new problem to tackle
* this is less intimidating than a blank screen or a blank sheet of paper
* it encourages learners to think about similarities and differences between various approaches, which helps create linkages in the mental model that is trying to be relayed

* For example, someone teaching in Python start by explaining this:

```python
#total_length(["red", "green", "blue"]) => 12
def total_length(words):
  total = 0
  for word in words:
    total += len(word)
  return total
```

* then **ask** learners to fill in the blanks in this:

```python
# word_lengths(["red", "green", "blue"]) => [3, 5, 4]
def word_lengths(words):
    lengths = ____
    for word in words:
        lengths ____
    return lengths
```
Another step of fading might be this:

```python
# concatenate_all(["red", "green", "blue"]) => "redgreenblue"
def concatenate_all(words):
    result = ____
    for ____ in ____:
        ____
    return result
```

and finally learners would be asked to do:

```python
# acronymize(["red", "green", "blue"]) => "RGB"
def acronymize(words):
    ____
```

* When using faded examples:
    * it's key to think about the **problem-solving strategy or solution pattern** that is meant to be taught
    * the example above is illustrating the ***accumulator pattern*** in which the results of **processing items in a collection** are repeatedly added to a single variable in some way to create the final result

>##Create a Faded Example from a Lesson
>The following exercise should be done in groups of 2-3.

>Pick a block of code from an existing Software or Data Carpentry lesson, or from another lesson you have taught recently.
>Replace 2-3 pieces of the code with a blank.
>Write a question to test the student’s ability to correctly fill in that blank.
>Take 10 minutes for this exercise.
>Paste your faded example in the Etherpad.

## Parson Problems

* Another way to reduce cognitive load is using **Parson Problems**
* In this case, learners are presented with jumbled parts of a solution and asked to put them in order
* Example: when learning a language students could be asked to order a set of words to create a grammatically correct response to a question
* Our learners can be given lines of the code needed to solve a problem and asked to arrange them.
* Then learners can be told they have all the lines they need **except one** and so forth.

* Here's a nice online Parson Problem interactive tool.

>## Parson Problems
>Pick a block of code from an existing Software or Data >2. Carpentry lesson, or from another lesson you have taught recently.
>3. Jumble the code
>4. Paste your jumbled code block into the etherpad
>5. Determine the correct order of your partner’s else’s code block
