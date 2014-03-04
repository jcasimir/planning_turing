# Week 1

See the ongoing [TODO list](https://github.com/JumpstartLab/turing/issues/1).

## Premise

Everything starts off with LOTS of small, focused
tutorials and exercises that all pretty much build on each other. We're
ditching several of the early tutorials (microblogger, event manager,
encryptor), but

1. We'll keep them on hand as things that students who are fast, doing
well, ahead of the game can go do in their off-time. It will help keep
them interested.
2. We can mine them for things that can be turned into small, focused
exercises.

We're ditching the focus week. In many ways weeks 1-4 are continuous
focus weeks.

## Goals

In this week we're trying to:

1. Establish focus and work patterns
2. Build confidence through quick wins
3. Lay a strong foundation with drills/exercises and lots of repetition
4. Start the progression to higher-order skills

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
white, and that says sparkly things.

The Intro to CSV is a whole set of tutorials/exercises. It's 2 layers
(I & II), five exercises in each (A, B, C, D, E).

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
* KO: Agreed. I would love to see these overhauled to remove some of the wilder "exploratory" aspects, though (perhaps leaving the safari stuff for faster students who need more excitement). I simply haven't had the time to go through them yet.
* JC: How much of "Ruby Fundamentals" exists? Can we take advantage of existing resources (ours, outside)?
* KO: Lots! The (ruby-exercises)[https://github.com/JumpstartLab/ruby-exercises] repository is pretty-much the equivalent of Ruby in 100 Minutes, but in a style that makes them actually _think_ about how things work and make hypotheses about why they work that way, and then revise those hypotheses when things go badly. It's a lot like the Koans, except that the Koans give you the answer if you bother to read the error messages. Here you have to actually make a guess before you get to see the real answer, and I find that this is more engaging. I've gone through several of these things with several of the students.
* JC: We need to make sure that, for the scheduling of future groups at the same time, these stay in blocks no more than three hours in the classroom per day.

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
* KO: Is there any sort of real-world problem that we can have them solve CLI-style? Especially if we can give them a gem to use for the complicated stuff. Just getting the pieces to talk together on their own without any guidance would be really good at this point.
* JC: What are the learning goals for this week? What does CSV II teach them?
* KO: CSV-I is very basic objects/methods, good design/code arrangement, using tests at different levels (unit, acceptance), and practicing core ruby stuff and enumerables. CSV-II is an incredibly simplified version of SalesEngine -- two CSV files where the data is linked via an ID, and building the code (using tests) that make it possible to access the data.
* KO: I'd like to start them on the [CLI tutorial](http://tutorials.jumpstartlab.com/topics/cli.html) as early as possible, because it has some serious potential to let them feel like they kick ass. Perhaps the tutorial part can be in the first week, before even starting with the CSV stuff, or perhaps Monday in week 2 so they have time to rest a bit over the weekend before having their mind blown (albeit with "hello world". But still). The CLI exercises at the end that build on CSV-II could be a nice way to bring the CLI stuff back in after a break from it, and warm them up for the next project, which is EventReporter.

# Week 3

## Premise

This week centers around the first real independent project, EventReporter. The project is expanded to 9 work days and the students have significantly more foundation/background and should be more successful than previous classes.

## Goals

## Plan

### Monday

* Intro to CLI

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

* Wednesday-Thursday - Event Reporter (project)
* Ideabox Independent Project (design, features, extensions), demo Thursday afternoon

## Additional Resources

## To-Dos

* KO: Should we have them do the event reporter separately from the ideabox
independent project? A lot of the students got very frustrated by having to
focus on multiple things at once, and if we let them finish one first and them
let them loose on the second, they might feel a little bit less frazzled.
* KO: 9 days for EventReporter seems like a lot. I anticipate that everyone
will be able to finish the project in two or three days, and that it will
seem pretty straight-forward to them.
* KO: The EventReporter tutorial needs to be overhauled to provide a standard
CLI rather than a REPL. It's very easy to write tests for a normal CLI using
aruba, which would give us a way to validate the projects. We can write
multiple tests -- core behavior vs extensions, letting the students use these
tests as a guide for how to get working code, without guiding them in any way
in terms of code structure.
* KO: The Intro to CLI tutorial is mostly written, but needs polish. I don't
have exercises for it, other than that we can make them put a CLI in front of
all the CSV-II exercises.
* KO: We have some content about fundamental debugging practices, but we
need to develop exercises for it so that they can practice the
things that we talk about and get comfortable with the ideas (for Tuesday).

The pieces they need to know to do Event Reporter have all been covered
in this new version of the curriculum: All the enums exercises, Intro to
CSV tutorials (levels I & II) and Intro to CLI, and the Ideabox (CLI)
project all prepare the students for this.

# Week 4

## Premise

## Goals

## Plan

### Monday

### Tuesday

### Wednesday

### Thursday

### Friday

## Additional Resources

## To-Dos

## To Be Processed

Now they've completed the basic CSV-CLI project, we're going to up the
ante and add a layer of complexity.

Monday - ?

Tuesday - Intro to SalesEngine, then "Connecting Two Verticals", then
project work.

Intro to Sales Engine is a talk-session.

The Connecting Two Verticals is a tutorial (not yet written) that walks
the students through starting the Sales Engine project and how to solve
the fundamental problem of connecting two related bits of data from two
different CSV files. They've already accomplished this in the CSV-II
exercises, but this gives them the same problem with a larger scope.

The Sales Engine project is basically 3 layers and 7 verticals. Once
you've solved 3 layers for 2 verticals, it's all a matter of doing the
same thing over and over again.

# Week 5

## Premise

## Goals

## Plan

### Monday

### Tuesday

### Wednesday

### Thursday

### Friday

## Additional Resources

## To-Dos

## To Be Processed

Sales Engine project work.

I imagine that we might have some instructor-led sessions to help flesh
out things that they're feeling unsure of, but I don't see any
particularly critical sessions here.

# Week 6

## Premise

## Goals

## Plan

### Monday

### Tuesday

### Wednesday

### Thursday

### Friday

## Additional Resources

## To-Dos

## To Be Processed

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

## Resources

### Ruby Fundamentals

* [intro to tdd](http://tutorials.jumpstartlab.com/academy/workshops/intro-to-tdd.html)
* [objects and methods - tutorial](http://tutorials.jumpstartlab.com/academy/workshops/objects_and_methods.html)
* [ruby exercises](https://github.com/JumpstartLab/ruby-exercises) (core types, comparisons, shovel/shift, command-query, mythical creatures, objects and methods)
* [enumerables exercises](https://github.com/JumpstartLab/enums-exercises/tree/master/exercises)

### Small Application Exercises

* [objects and data I - tutorial](http://tutorials.jumpstartlab.com/academy/workshops/csv/i.html)
* [objects and data II - tutorial](http://tutorials.jumpstartlab.com/academy/workshops/csv/ii.html)
* [objects and data - repository](https://github.com/JumpstartLab/csv-exercises)
* [scripting and command-line](http://tutorials.jumpstartlab.com/topics/cli.html)

