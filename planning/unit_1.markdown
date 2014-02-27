# Week 1

## Premise

Everything starts off with LOTS of small, focused
tutorials and exercises that all pretty much build on each other. I'm
ditching several of the early tutorials (microblogger, event manager,
encryptor), but

1) We'll keep them on hand as things that students who are fast, doing
well, ahead of the game can go do in their off-time. It will help keep
them interested.

2) I will probably mine them for things that can be turned into small,
focused exercises.

I've ditched the focus week, because I think that in many ways weeks 1-4
are continuous focus weeks.

## Goals

In this week we're trying to:

1. Establish focus and work patterns
2. Build confidence through quick wins
3. Lay a strong foundation with drills/exercises and lots of repetition
4. Starting the progression to higher order skills

## Plan

### Monday

* Kickoff 
* Team-building with improv exercises, building desks, scavenger hunt, etc
* Intro to the Lab Book
* Scavenger Hunt

### Tuesday

* Deliver the laptops
* Environment Setup
* Ruby Fundamentals
* Intro to OS X / command line / text editor

### Wednesday

* [Intro to TDD](http://tutorials.jumpstartlab.com/academy/workshops/intro-to-tdd.html)
* Finishing Ruby Fundamentals
* Intro to CSV, 1A.

Intro to TDD is a 2 hour (or so) instructor-led session that walks through the
TDD process for a very simple object - a unicorn that has a name, is usually
white, and which says sparkly things.

The Intro to CSV is a whole set of tutorials/exercises. It's 3 layers
(I, II, and III), five exercises in each (A, B, C, D, E).

### Thursday

* Continuing Intro to CSV I B-E (instructor led at first, transitioning to independent)
* How Git Works (lecture/discussion)
* Intro to Git with Code School and Git Immersion (independent work)

Intro to CSV I(A) is a tutorial that walks the students through
each and every step of solving the exercise, then B-E all are
very similar exercises (different data, different names,
exact same problem), and they provide progressively less hand-holding.

The students can basically work independently on these, and should be
able to mostly help each other.

## Additional Resources

Fast-moving students can work on:

* Microblogger
* EventManager
* Encryptor
* Ruby in 100 Minutes

### Lost Pieces

* How TDD Works (lecture/discussion)
* Intro to TDD: Ideabox I (paired tutorial)
* Working with Enumerations (lecture/discussion)
* Enumerables Exercises
  https://github.com/JumpstartLab/enums-exercises (paired tutorial)
* Intro to CSV II A-E

## To-Dos

* JC: I think I'd still like to make space for some of the pulled projects like Encryptor that can synthesize learnings from the smaller activities
* JC/KO: How much of "Ruby Fundamentals" exists? Can we take advantage of existing resources (ours, outside)?
* JC/KO: We need to make sure that, for the scheduling of future groups at the same time, these stay in blocks no more than three hours in the classroom per day.

#### JC WORK MARKER

# Week 2

Monday: - Intro to TDD, then Enumerables Exercises

This session's Intro to TDD turned out to be very confusing. I've
rewritten a tutorial that I think is much better, called "Ideabox I".

Ideabox is/was a tutorial/project that we have done with the students to
introduce the web, but I'm breaking it apart into much smaller pieces
and then using it to introduce smaller topics on an ongoing basis.

This is a tutorial where every step is written out, and the students
should be able to work through it on their own.

The Enumerables exercises (https://github.com/JumpstartLab/enums-exercises)
are something I've been working on for the past few weeks
-- drills, essentially. The students should be able to
work through a lot of this on their own, with instructors present
for Q&A and clarification.

Tuesday: Intro to Git, then Intro to CSV II (A)

I don't yet know how to do the git thing. We're doing a terrible job of
it currently, and this needs a better approach.

The Intro to CSV II adds a new layer of complexity to the familiar
exercises from Intro to CSV I. Again (A) is a full tutorial that walks
the students through each step.

Wednesday-Thursday:

Intro to CSV II (B-E) the exercises that repeat the concepts and with
progressive release of responsibility giving the student less and less
boilerplate.

# Week 3

Monday - Intro to CLI (A-E)

CLI means Command Line Interface. Up until now we've only written
programs that are consumed by the program itself. There's no way for a
human to interact with the program, you just kick it off and get the
results.

With CLI we introduce the idea of an interactive program, but not with
the web, just a simple text-interface in the terminal.

I haven't written the Intro to CLI set of exercises, but again (A) is
going to be a tutorial that walks the students through every step of the
exercise, and then (B-E) are exercises where we give them less help,
boilerplate and hand-holding.

Tuesday: Ideabox II (CLI), then Debugging, then Intro to Event Reporter

The Ideabox II (CLI) is a small project where the students are asked to
take what they learned in the Intro tutorial/exercises, and add a CLI to
their Ideabox program from the Ideabox I (TDD) tutorial.

This would be a full morning session 9-12, and then if they're not done
they can work on it from home.

We have some content about fundamental debugging practices, but we
need to develop exercises for it so that they can practice the
things that we talk about and get comfortable with the ideas.

The Intro to EventReporter is a talk-session where we introduce the
first real project. It's a project that we gave them a full week to
finish in the current class, and only a handful of people finished. Most
people were completely overwhelmed and confused, and we spent a LOT of
time helping/answering questions/reassuring the students.

The pieces they need to know to do Event Reporter have all been covered
in this new version of the curriculum: All the enums exercises, Intro to
CSV tutorials (levels I & II) and Intro to CLI, and the Ideabox (CLI)
project all prepare the students for this.

I anticipate that everyone will be able to finish the project in two
days, and that it will seem pretty straight-forward to them.

* Wednesday-Thursday - Event Reporter (project)
* Ideabox Independent Project (design, features, extensions), demo Thursday afternoon

# Week 4

Now they've completed the basic CSV-CLI project, we're going to up the
ante and add a layer of complexity.

Monday - Intro to CSV III (A-E)

None of this has been prepared yet, but the basic idea is that we'll
give them multiple CSV files that are related, rather than a single CSV
file.

Tuesday - Intro to SalesEngine, then "Connecting Two Verticals", then
project work.

Intro to Sales Engine is a talk-session.

The Connecting Two Verticals is a tutorial (not yet written) that walks
the students through starting the Sales Engine project and how to solve
the fundamental problem of connecting two related bits of data from two
different CSV files.

The Sales Engine project is basically 3 layers and 7 verticals. Once
you've solved 3 layers for 2 verticals, it's all a matter of doing the
same thing over and over again.

# Week 5

Sales Engine project work.

I imagine that we might have some instructor-led sessions to help flesh
out things that they're feeling unsure of, but I don't see any
particularly critical sessions here.

# Week 6

Introducing the Web.

Monday - Web Guesser, then Ideabox III (Sinatra w/Capybara)

These are both fairly independent tutorials, and the students can finish
them at home if they don't finish during the day.

Tuesday-Thursday - Ideabox Project

Here we give them 3 days to create the Ideabox website, which involves
doing some design, adding some features that we haven't given them the
step-by-step recipes for. Demo on Thursday afternoon.

That's it. Then we're up to week 7 and 8 which would be much like what
we did this session.
