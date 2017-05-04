---
title: "Expertise and Memory"
author: "Tim Dennis"
date: 2017-04-23
---

1. [Novices and Formative Assessment](02-novice) (20/45m)
2. **[Expertise and Memory](08-memory) (30/15m)**
3. [Cognitive Load](11-load) (20/20m)
4. [Live Coding](13-live) (30/45m)
5. [Lessons and Objectives](19-lessons) (30/20m)

**SET timer for 45 minutes**

## START

* Returning to educational psychology, we now discuss what distinguishes expertise from **earlier stages of learning** (novice and competent practitioner)
  * AND how expertise can be both helpful and get in the way of learning
* We'll also cover concept maps - a tool that can help expose expertise (and can be used for many things)

## Connectivity

* Earlier we described the key differences between novices and competent practitioners
* What makes experts different from either?
    * The answer: **NOT that they know more facts**
    * Competent practitioners (& novices) can memorize a lot of trivia without notable improvement to their performance

**To illustrate**, imagine that we store knowledge as a graph:
* facts are nodes and relationships are arcs (Note: this is not how our brains work, but it's a metaphor)
* key difference between experts and people who are "merely competent" is that experts have more connected nodes (their mental models are more densely connected)

**Think about driving around a city, comparing what it's like for the local and for the out-of-town driver.**

* This metaphor will help us explain many observed aspects of expert behavior.

1. **EXPERTS** can jump directly from a problem to solution because there is a direct link between the two in their mind
  * where a competent practitioner would have to reason "A to B to C to D to E" the expert can go from A to E in a single step
  * We call this *intuition* and it isn't always a good thing:
  * When asked to explain her reasoning an expert often can't because she actually didn't go thru all the intermediate steps.
  _In our example above, the local probably doesn’t even think about which turns they’re making on their way to the grocery store. They can drive on “autopilot” without really thinking. If someone asks them to go to a different location, they immediately know what they should do next to get to the right place._
2. Experts are so familiar with a topic that they can no longer imagine what it's like to not see the world that way.
  * As a result, they are often less good at teaching the subject than people with less expertise who still remember what it's like to have to learn the things.
  * **Expert blind spot**
  * Can be overcome with training -- but why world famous researchers are often poor lectures
  * _Local driver forgets to tell out-of-towner that the bridge is under construction, or that there's a train at 3:00, b/c it's been like that for years. The local driver will tell the out-of-towner to turn 'where the gas station used to be'_
3. Densely connected knowledge graphs also explains fluid representations, e.g., expert mathematicians' ability to switch effortlessly between algebraic and geometric views of a problem
  * _Local driver probably can use either the names of streets or landmarks when giving directions. The out-of-towner only has street labels. -- Baker example_
4. Finally, this metaphor also explains why experts are better at diagnosis than competent practitioners: more linkages between facts makes it easier to reason backward from symptoms to causes.
  * _When out of towner finally calls their local friend, saying "well we just passed Sycamore Street and we can see 'Nellie's Cafe', the local can more easily figure out where the out-of-towner is, and how to get to their destination"_

## J word

* experts often betray their blind spot by using the word "just" in explanations, as in, "Oh, it's easy, you *just* fire up a new VM and then you just install these four patches to Ubuntu and then you just re-write your entire program in a pure functional style -- easy peasy".
* as we discuss later, the J word (also sometimes called the passive submissive adverb) is banned in our workshops b/c using it gives learners the very clear signal that the instructor thinks their problem is trivial and that they therefore must be dumb

* the Graph view of knowledge explains why helping learners make connections is as important as introducing them to facts.
  * the more people you know in a group, the more likely you are to remain part of that group.
  * the more connections a fact has to other facts, the more likely it will be remembered
* this builds on our earlier idea of mental models - **a mental model is a way to facilitate making connections between separate facts.**

## Concept Maps

A TOOL of choice to represent an expert's knowledge graph is the ***concept map***.

**Concept map**
: is simply a picture of someone's mental model of a domain - facts are bubbles, and connections are labelled arcs

* It's important that the arcs are labelled:  saying "X and Y are related" is only helpful if we explain what the relationship is.
  * YES, one person's fact may be another's connection, but by *externalizing cognition* (making these model's visable), concept maps help spark and focus discussion
  * **TIP** concepts maps are just one way to represent our understanding of a subject: flowcharts, decision trees, blueprints can be v. useful in diff. contexts
* To show what this looks like consider this map of dataframe piping in R (tidyverse):

* <https://awwapp.com/b/ufqzvm01v/> (teacher copy)
* <https://awwapp.com/b/sidndlp8o> (each will get copy)

* <https://s3.amazonaws.com/aww-imagedata/11006a44-252a-4cd5-bf0d-8f7eedafddf1.png> (image)

* There are 13 concepts in this map:  pipeline, filters, processes, pip command, input, output, stdin, stdout, file, output
* Then we 10 relationships.
* This gives us a total of 23, which is more than our ideal size for a single episode.
* This map should probably be broken up into two graphs and further developed.
* For instance, we can see that we need to introduce filters and processes before piping - this probably need an episode by themselves

* many concept maps can be larger than the recommended limit (7+-2), but that's not a bad thing [Set and Dict example](https://swcarpentry.github.io/instructor-training/fig/dict-set.png)
* after drawing a concept map for an entire subject, the lesson designer can carve out a tightly-connected sub-graphs to make individual episodes

**Concept maps can be used in many ways:**

1. To aid **solo design** of a lesson by helping authors **figure out what they're trying to teach**. Crucially a concept map **separates content from order**: in our experience ppl rarely wind up teaching things in order in which they first drew them
2. They aid in communication with other lesson designers. Instructors with different ideas often pull their learners in different directions.
3. Concept maps **help learners**. When possible give learners a pre-drawn map at the beginning of a lesson for them to annotate, it's better to draw piece by piece while teaching to reinforce the ties between what's in the map and what the instructor said.
4. Concept maps are also useful **formative assessment tool**: have learners draw concept maps of what they think they just heard shows the instructor what was missed and what was mis-understood. often too long in time for swc workshops


### other uses

**Concept maps** are also useful for: team meetings -- give everyone a sheet of paper and have them draw a concept map of the project you're all working on -- separately. On the count of three, have everyone reveal their maps. Discuss!

**Concept maps** also a good way to organize one's thought before putting together a talk or writing a paper. They allow us to *externalize cognition*, i.e. get out thoughts out where we can see them - contradictions and all.

>##(EXERCISE) Concept mapping (<https://goo.gl/279azG>)
>Create a hand drawn concept map for something you would teach in five minutes. (Possibly for the same subject that you used to create a multiple choice question before.) Trade with a partner, and critique each other’s maps. Do they present concepts or surface detail? Which of the relationships in your partner’s map do you consider concepts and vice versa?

>Take 10 minutes to draw the concept maps and share with your neighbor. Write done in the chat once you have finished.
> ASk how it went? 

## Seven ± Two

>## Serial position Effect
>I'm going to read a list of items and want you to try and memorize the items in it:

>cat, apple, ball, tree, square, head, house, door, box, car, king, hammer, milk, fish, book, tape, arrow, flower, key, shoe

>In the etherpad, write down as many words from the list as you can. Compare to other members of the group. What words are remembered the most?

* Human memory can be divided into two different storage layers:
    * *long-term* or *persistent memory* - where we store things like password, our home address, and what the clown did at our eighth birthday party that scared us so much
    * it's **unbounded** (barring injury or disease, we will die before it fills up), but it is slow to access - too slow to help us handle hungry lions and disgruntled family members
* Evolution has given us a second system called *short-term* or *working memory*
    * it is much faster but smaller: in 1956 George Miller estimated that the average adult's working memory could hold [7±2](https://en.wikipedia.org/wiki/The_Magical_Number_Seven,_Plus_or_Minus_Two)
    * this is why phone numbers have a limit of  typically 7 or 8 digits
    * back when phones had dials not keyboards, that was the longest string of numbers most adults could remember accurately for as long as it took to dial to go round and round.
    * also why sports teams tend to have about half a dozen members or are broken into smaller groups (such as forwards and backs in rugby)
* when we memorize words in a list and are asked to immediately recall items, the items first presented will have the best chance to be transferred into long-term memory
* On the other hand, the items that are presented last might still be in short-term memory
* these are referred to as the **primacy and recency effects**, respectively and together form the *memory serial position*

## Chunking

* Our minds can store larger numbers of facts in short-term memory by **creating chunks**
* Most of us will remember a **word we read as a single item**, rather than as a sequence of letters
* Pattern made by five spots on cards or dice is remembered as a whole rather than bits of info
* **chunks** allow us to **manage larger problems** - but also can mislead us if we mis-identify something - see something wrong

### 7±2: Programming and Teaching

* **7±2** is probably the most **important number in programming**
    * When writing code, programmer needs to keep a bunch of facts in memory, for example, what is this variable, what value does this hold here
    * If the facts grow too large, her **mental model of the program** becomes too unwieldy


* 7±2 is also the most **important number in teaching**
    * an instructor cannot **push information directly into a learners long-term memory**
    * what she presents is **first represented** in the learners short-term memory and is only transferred to long-term memory after it has been held there and **rehearsed** and **reinforced**
    * if we present too much information too quickly the **new will displace** the old before it has a chance to **consolidate into long-term memory**
    * this is why using the concept mapping is important before teaching, an instructor needs to **identify just how many pieces of a separate information** will need to be stored in memory as part of the lesson -- LESS IS more

## Key Points

* Experts’ mental models are much more **densely connected** than those of non-experts.
* **Expert blind spot**: knowing something so well that it seems easy when it’s not.
* Can represent **mental models** using **concept maps**.
* **Relationships** are as important as concepts.
* **Long-term memory** is large but slow, while **short-term** is fast but (very) small.
* Most adults can store **7±2** items in short-term memory for a few seconds before loss.
* Things seen together repeatedly are remembered (or mis-remembered) in **chunks**.
* Teaching consists of **loading short-term memory** and **reinforcing it long enough** for items to be transferred to long-term memory.
* Lesson episodes should not **overload short-term memory**.


[abela-presentation]: http://extremepresentation.typepad.com/blog/2006/09/choosing_a_good.html
[amazon-glass]: http://www.amazon.com/Facts-Fallacies-Software-Engineering-Robert/dp/0321117425/
[macnamara-practice]: http://pss.sagepub.com/content/25/8/1608
[memory-test]: http://cat.xula.edu/thinker/memory/working/serial
[wikipedia-7]: https://en.wikipedia.org/wiki/The_Magical_Number_Seven,_Plus_or_Minus_Two
[wikipedia-serial-position]: https://en.wikipedia.org/wiki/Serial_position_effect
