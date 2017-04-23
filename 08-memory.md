# Expertise and Memory 

* Experts’ mental models are much more densely connected than those of non-experts.
* Expert blind spot: knowing something so well that it seems easy when it’s not.
* Can represent mental models using concept maps.
* Relationships are as important as concepts.
* Long-term memory is large but slow, while short-term is fast but (very) small.
* Most adults can store 7±2 items in short-term memory for a few seconds before loss.
* Things seen together repeatedly are remembered (or mis-remembered) in chunks.
* Teaching consists of loading short-term memory and reinforcing it long enough for items to be transferred to long-term memory.
* Lesson episodes should not overload short-term memory.

* How can we describe the difference in learning between a novice and expert?
* How is memory a limiting factor in learning?

## Connectivity

* earlier we described the key differences between novices and competent practitioners
* What makes experts different from either?
  * answer: NOT that they know more facts:
  * Competent practicioners can memorize a lot of trivia without noteable improvement to their performance

To illustrate, imagine that we store knowledge as a graph:
* facts are nodes and relationships are arcs (Note: this is not how our brains work, but it's a metaphore.)
* key difference between experts and people who are "merely competent" is that experts have more connected nodes (their mental models are more densely connected)

**Think about driving around a city, comparing what it's like for the local and for the out-of-town driver.**

* This metaphore helps explain many observed aspects of expert behavior.

1. **EXPERTS** can jump directly from a problem to solution because there is a direct link between the two in their mind
  * where a competent practitioner would have to reason "A,B,C,D,E" the expert can go from A to E in a single step
  * We call this intuition and it isn't always a good thing:
  * when asked to explain her reasoning an expert often can't because she actually didn't go thru all the intermediate steps.
  _In our example above, the local probably doesn’t even think about which turns they’re making on their way to the grocery store. They can drive on “autopilot” without really thinking. If someone asks them to go to a different location, they immediately know what they should do next to get to the right place._
2. Experts are so familiar with a topic that they can no longer imagine what it's like to not see the world that way.
  * As a result, they are often less good at teaching the subject than ppl with less expertise who still remember what it's like to have to learn the things.
  * Expert blind spot
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
* this builds on our earlier idea of mental modesl - a mental model is a way to facilitate making connections between separate facts.

## Concept Maps

TOOL of choice to represent an expert's knowled graph is the *concept map*.

Concept map
: is simply a picture of someone's mental model of a domain - facts are bubbles, and connections are labelled arcs

* Important that they are labelled saying "X and Y are related" is only helpful if we explain what the relationship is.
  * YES, one person's fact may be another's connection, but by *externalizing cognition* (making these model's visable), concept maps help spark and focus discussion
  * **TIP** concepts maps are just one way to represent our understanding of a subject: flowcharts, decision trees, blueprints can be v. useful in diff. contexts
* To show what this looks like consider this simple **for** loop in Python:

~~~
for ch in "abc":
  print(2*ch)
~~~

Three key concpets in this loop are:

**for ch in "abc":
    print(2*ch)**

Loop variable, collection, loop body

* in this case it's easy to connect the concepts to concrete elemetns in the program, but that might not always be the case
* key relationships -- as important as the concepts themselves are:

loop variable > takes each value/in order > collection
loop vriable > changes each time loop body > runs for each > collection

**possible function in R instead**

dataframe pipe

* many concept maps can be larger than the recommended limit (7+-2), but that's not a bad thing
* after drawing a concept map for an entrie subject, the lesson designer can carve out a tightly-connected sub-graphs to make individual episodes

**Concept maps can be used in many ways:**

1. To aid solo design of a lesson by helping authors figure out what they're trying to teach. Crucially a concept map separates content from order: in our experience ppl rarely wind up teaching things in order in which they first drew them
2. they aid in communication with other lesson designers. Instructors with different ideas often pull their learners in different directions.
3. Concept maps help learners. When possible give learners a pre-drawn map at the beginning of a lesson for them to annotate, it's better to draw piece by piece while teaching to reinforce the ties betwtten what's in the map and what the instructor said.
4. concept maps are also uself formative assessment tool: have learners draw concept maps of what they think they just heard shows the instructor what was missed and what was mis-understood. (Reviewing concpets maps too time consuming for use in workshops, but v. useful in weekly lectures *once learners are familiar with the technique*: as Glass observed a new tool or technique initially slows ppl down.)

**Concept maps** are also useful for: team meetings -- give everyone a sheet of paper and have them draw a concept map of the project you're all working on -- separately. On the count of three, have everyone reveal their maps. Discuss!

**Concept maps** also a good way to organize one's thought before putting together a talk or writing a paper. They allow us to *externalize cognition*, i.e. get out thoughts out where we can see them - contradictions and all.

>##Concept mapping
>Create a hand drawn concept map for something you would teach in five minutes. (Possibly for the same subject that you used to create a multiple choice question before.) Trade with a partner, and critique each other’s maps. Do they present concepts or surface detail? Which of the relationships in your partner’s map do you consider concepts and vice versa?

>Take 10 minutes to draw the concept maps and share with your neighbor. Write done in the chat once you have finished.

## Seven Plus or Minus Two

>## Serial position Effect
>I'm going to read a list of items and want you to try and memorize the items in it:

>cat, apple, ball, tree, square, head, house, door, box, car, king, hammer, milk, fish, book, tape, arrow, flower, key, shoe

>In the etherpad, write down as many words from the list as you can. Compare to other members of the group. What words are remembered the most?

* Human memory can be divided into two different storage layers:
  * *long-term* or *persistent memory* - where we store things like password, our home address, and what the clown did at our eighth birthday party that scared us so much
  * it's unbounded (barring injury or disease, we will die before it fills up), but it is slow to access - too slow to help us handle hungry lions and disgruntled family members
* Evolution has given us a second system called *short-term* or *working memory*
  * it is much faster but smaller: in 1956 Miller estimated that the avg adult's working memory could hold 7+-2
  * this is why phone numbers are typically 7 or 8 digits
  * back when phones had dials not keyboards, that was the longest string of numbers most adults could remember accurately for as long as it took to dial to go round and round.
  * also why sports teams tend to have about half a dozen members or are broken into smaller groups (such as forwards and backs in rugby)
* when we memorize words in a list and are asked to immediately recall the, the works first presented will have the best chance to be transferred into long-term memory
* On the other hand, the items that are presented last might still bein short-term memory
* these are referred to as the primacy and recency effects, respectively and together form the *memory serial position*

## Chunking

* our minds can store larger numbers of facts in short-term memory by creating chunks
* most of us will remember a word we read as a single item, rather than as a sequence of letters
* pattern made by five spots on cards or dice is remembered as a whole rather than bits of info
* **chuncks** allow us to manage larger problems - but also can mislead us if we mis-identify something - see something wrong

* 7+-2 is probably the most important number in programming
* when writing code, programmer needs to keep a bunch of facts in memory -- eg what is this variable, what value does this hold here
* if the facts grow too larger her mental model of the program becomes too unweildy

* 7+-2 is also the most important number in teaching
* an instructor cannot push information directly into a learners long-term memory
* what she presents is first represented in the learners short-term memory and is only transfered to long-term membory after it has been held there and rehearsed
* if we present too much information too quickly the new will be displace the old before it has a chance to consolidate into long-term mem
* this is why using the conctep mapping is important before teaching, an instructor needs to identify just how many pieces of a separate informaion will need to be stored in membory as part of the lesson  LESS IS more

## Key Points

* Experts’ mental models are much more densely connected than those of non-experts.
* Expert blind spot: knowing something so well that it seems easy when it’s not.
* Can represent mental models using concept maps.
* Relationships are as important as concepts.
* Long-term memory is large but slow, while short-term is fast but (very) small.
* Most adults can store 7±2 items in short-term memory for a few seconds before loss.
* Things seen together repeatedly are remembered (or mis-remembered) in chunks.
* Teaching consists of loading short-term memory and reinforcing it long enough for items to be transferred to long-term memory.
* Lesson episodes should not overload short-term memory.
