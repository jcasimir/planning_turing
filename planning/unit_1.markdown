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

## To-Dos

* JC: I think I'd still like to make space for some of the pulled projects like Encryptor that can synthesize learnings from the smaller activities
* JC/KO: How much of "Ruby Fundamentals" exists? Can we take advantage of existing resources (ours, outside)?
* JC/KO: We need to make sure that, for the scheduling of future groups at the same time, these stay in blocks no more than three hours in the classroom per day.

# Week 2

## Premise

With some grip of fundamental Ruby programming, Week 2 starts to build more significant projects and applications. They approach something you might want to actually build instead of just learning exercises.

## Goals

## Plan

### Monday

* How TDD Works (lecture/discussion)
* Intro to TDD with Ideabox I
* Working with Enumerables (lecture/discussion)
* Enumerables Exercises
  https://github.com/JumpstartLab/enums-exercises (paired tutorial)

Ideabox I replaces previous Intro to TDD tutorials and focuses on building the business logic behind what will eventually become the Ideabox web application. This segment is guided tutorial, and the students
should be able to work through it on their own.

The Enumerables exercises (https://github.com/JumpstartLab/enums-exercises)
are a collection of drills. With Q&A support, the students should be able to
work through this on their own.

### Tuesday

* Intro to Git
* Intro to CSV II (A)

The Intro to CSV II adds a new layer of complexity to the familiar
exercises from Intro to CSV I. Again (A) is a full tutorial that walks
the students through each step.

### Wednesday & Thursday

Intro to CSV II (B-E) the exercises that repeat the concepts and with
progressive release of responsibility giving the student less and less
boilerplate.

## Additional Resources

## To-Dos

* JC: I'm not sure about where to learn about Git. I'd like to see it in the first week, but I don't want it to be a distraction. Maybe in Week 1 we cover the true essentials with something like try.github.com, then in Week 2 dive more deeply into how Git works. That could start with Jim Weirich's conference talk about designing source control then follow with Git Immersion. I wish there were some kind of "capture the flag"-like game for learning/practicing git.
* JC: Wednesday/Thursday of this week would be a good opportunity to bring skills together into a small project. Maybe Encryptor? We could reframe the concepts into more of an independent project that practices TDD and Enumerations.
* JC: What are the learning goals for this week? What does CSV II teach them?

# Week 3

## Premise

This week centers around the first real independent project, EventReporter. The project is expanded to 9 work days and the students have significantly more foundation/background and should be more successful than previous classes.

## Goals

## Plan

### Monday

* Intro to CLI (A - E)

CLI means Command Line Interface. Up until now we've only written
programs that are consumed by the program itself. There's no way for a
human to interact with the program, you just kick it off and get the
results.

With CLI we introduce the idea of an interactive program, but not with
the web, just a simple text-interface in the terminal.

### Tuesday

* Ideabox II (CLI)
* Debugging
* Intro to Event Reporter

The Ideabox II (CLI) is a small project where the students are asked to
take what they learned in the Intro tutorial/exercises, and add a CLI to
their Ideabox program from the Ideabox I (TDD) tutorial.

This would be a full morning session 9-12, and then if they're not done
they can work on it from home.

The Intro to EventReporter is a talk-session where we introduce the
first real project.

### Wednesday

### Thursday

## Additional Resources

## To-Dos

* KO: I haven't written the Intro to CLI set of exercises, but again (A) is
going to be a tutorial that walks the students through every step of the
exercise, and then (B-E) are exercises where we give them less help,
boilerplate and hand-holding.
* KO: We have some content about fundamental debugging practices, but we
need to develop exercises for it so that they can practice the
things that we talk about and get comfortable with the ideas (for Tuesday).

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
