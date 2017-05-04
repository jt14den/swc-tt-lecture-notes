---
title: "Live Coding"
author: "Tim Dennis"
date: 2017-04-23
---

1. [Novices and Formative Assessment](02-novice) (20/45m)
2. [Expertise and Memory](08-memory) (30/15m)
3. [Cognitive Load](11-load) (20/20m)
4. **[Live Coding](13-live) (30/45m)**
5. [Lessons and Objectives](19-lessons) (30/20m)

* Don't use slides in our teaching, but we work through the lesson via live coding.
* We plug into a projector and ask the learners to follow along.
* In this section we'll go over a how it works and give some tips for doing effective live coding.

## Why live coding?

But first a question for everyone:

>##Up and down
>What do you think some **advantages and challenges** of live coding are from both a learner's and an instructors point of view? (5min)
{: .discussion}

**It's advantages are:**

* more compelling watching someone buidl a program than watching someone run through slides
* It's easier to entertain "what if?" questions. **slide decks** can be like a **railway track**
  * A student might want to subset a data object by different conditions - with live coding you can cna "try stuff"
* **lateral knowledge transfer**: people learn more than we realize we were teaching by watching how instructors do things
    **think about how you learned to drive?** watching
* **slows the instructor down** - typing slows you down, taking what you are typing slows even more.
* make mistakes and ***how to diagnose and correct them.*** Beginners spend a lot of time making mistakes and can benefit from how to recover or debug mistakes.

If you aren't used to live coding you will have to practice at thinking out loud while coding in front of people, but most say it's no more difficult than talking wiht slides.

Many instructors use **two devices when teaching**
: a laptop plugged into the projector for learners and a tablet beside it on which they can view their notes/etherpad session.

>## Bad and the good
>Watch this video of [live coding done poorly](https://youtu.be/bXxBeNkKmJE) and this video of [live coding done right](https://youtu.be/SkPmwe_WjeY) as a group and then summarize your feedback on both in the Etherpad. Use the two x two rubric for feedback we discussed earlier.
In the videos, the bash shell `for` loop is taught, and it is assumed learners are familiar with how to use a variable, the `head` command and the content of the `basilisk.dat unicorn.dat` files.

>Note: Sometime sounds in the room can be poor. Turning on closed captioning by pressing the cc button will improve the accessibility of these videos.

>This exercise should take about 15 minutes.
{: .challenge}

## Live Coding Top 10

Here're are some tips to help you get started with live coding:

### 1. Be Seen and Heard

* If you can stand for a couple of hours, do it when teaching
    * ask for a high table/standing desk or lecturn
* Move around, point something out on the screen, draw on whiteboard
* Consider a microphone to save your voice

### 2. Take it slow

* Say out loud everything you type while typing
* Then point to the command and output and go over again
* gives learners time to keep up
* keep code on screen or scroll back up
* etherpad

### 3. Mirror your learner's environment as much as possible

* don't use your theme and plugins for bash, learners won't have this
* create a dummy user or revert to the out of box style

### 4. Use the screen wisely

* big fonts, max window, black on white works better light on dark
* be aware that the bottom of the window might be too low, so pull it up so ppl in back can see
* Use a second screen if you can get - show etherpad

### 5. Use illustrations

* use the illustrations in the lessons, drag over your tab or view the image
* whiteboard the illustrations/diagrams as you progress
    * i've used with Git and worked well, progressively sketched the working directory, then staging (git add), the draw commit repo (git commit) and finally show remotes and collaborating github

### 6. Avoid being disturbed

* turn off phone, IM, text, slack, desktop notifications, news alerts, prior to teaching

### 7. Stick to the lesson material

* lessons have been tried and tests through many iterations and versions
* it's solid stuff
* resist the urge to show a 'neat trick' that might land you in a hole
* if you want to add something test it out prior

### 8. Leave no learner behind

* sticky notes signalling typically red and green
* status flags - red means stuck on something and need help, green 'all done'
    * better than hand raising: more discreet (more likely to be done)
    * they can keep working with a flags
    * instructor can see them and direct helpers


### 9. Embrace mistakes

* you'll start looking forward to mistakes
* allows learners to see instructors mistakes and how to diagnose/correct

### 10. Have fun

* personalize the intruction

Challenge -
See Then Do
Pair up.
Teach 3-4 minutes of your chosen lesson episode using live coding to a fellow trainee, then swap and watch while that person live codes for you. Don’t record the live coding sessions. Give each other feedback using the two x two rubric we discussed previously and enter your feedback in the GDoc. Explain in advance to your fellow trainee what you will be teaching and what the learners you teach it to are expected to be familiar with.

This exercise should take about 20 minutes.

---
## maybe ask this instead of getting to put in gdoc.

* What felt different about live coding (vs. standing up and lecturing)? What was harder/easier?
* Did you make any mistakes? If so, how did you handle them?
* Did you talk and type at the same time, or alternate?
* How often did you point at the screen? How often did you highlight with the mouse?
* What will you try to do differently next time?

## Wrap up talk

Ok, to wrap up this section, we've found in SWC:
* that watching instructors write software is more compelling and informative than being presented with a finished product.
* that Live coding allows instructors to follow learners.
* The mistakes are the pedagogy.
