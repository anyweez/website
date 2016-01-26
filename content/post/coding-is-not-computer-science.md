+++
date = "2016-01-19T22:26:14-07:00"
draft = true
tags = ['reflections']
title = "Coding is not computer science"
+++

A lot of people get caught up on "the right way to learn to code" and other variants of that question (what language they should learn, whether they should attend a bootcamp, whether they want to focus on frontend / backend / etc). I've recently seized the opportunity to move from the tech product world into coding education @ [The Iron Yard](http://theironyard.com/), and the experience has helped me form opinions on learning and teaching code.

## Dear computer scientists
My first big realization was that *learning to code is not the same as learning computer science.* As a computer scientist, I thoroughly appreciate the fact that learning more about computer science will make you better at coding the same way that learning more about architecture will make you a better builder. We don't, however, expect or probably even want every builder be an architect. 

There are a pile of articles across the internet (and lively debates in conferences like [SIGCSE](http://sigcse.org/sigcse/)) debating how to teach computer science to budding computer scientists. This is a tough question and there are a bunch of well-informed perspectives out there (including [one I've worked quite a bit on](http://cs10.org/)). Note that above all teaching *computer science* is like teaching architecture: a significant amount of time is required because you're focusing on foundational understanding versus strictly practical application.

When considering the debate around learning how to code, the difference between teaching people how to code and teaching people how to be computer scientists is all too often mixed together. Recognize that the goals and ambitions of each group are (at least on the outset) quite different and the paths most likely to lead to success may therefore be pretty different as well.

## Learning "to code"
In my experience, the average newcomer to the world of coding tends to have two questions: what *language* should I start with and what material should I use to learn about it. Before I jump into an answer to either of those, I want to emphasize that "learning to code" really means learning at least three different skills, only one of which has to do with programming languages:

  1. Learning to [think like a developer](http://skillcrush.com/2014/06/26/the-developer-mindset/) and developing a convincing notion of **why coding is an activity worth practicing.** This is your fuel.
  2. **How to learn effectively**, and how to enjoy learning (coding and otherwise). This is your engine.
  3. The **technical concepts behind computation and programming**, coupled with a programming language that demonstrate them. This is your cargo.

The right path to "learning to code" is the one that will most successfully help an individual learn these three skills because these are the skills that will put you in a position to grow over time. How much you know when you finish whatever degree, certificate, bootcamp, online tutorial, etc you're using matters less than what you're able to figure out in the days, months, and years after that.

Let's look for a minute at each of these and why they're important.

### The developer mindset
Code looks like gibberish when inexperienced eyes look at it, but the vocabulary of a given language is actually pretty limited. Learning the keywords, syntax, etc is an exercise that becomes easier (and usually less interesting) over time; learning how to convert a human problem into code is substantially more difficult (and usually more interesting). [Most people that I know who love coding love it for the latter](https://www.quora.com/Why-do-you-love-coding-so-much), and that requires fostering a developer's mindset.

The developer mindset is both hard to teach and critical to learn, but the first realization often comes in a burst (the lightbulb moment). Once your brain starts to be able to convert between human and machine, the way you view the world starts to change and your capabilities of as a developer rapidly accelerate. This is probably a familiar sensation for those who have their first dream in a non-native language.

The biggest challenge for most people is having a good reason to put up with the challenges; reaching your lightbulb moment is usually not easy and involves twisting your brain in some peculiar and uncomfortable ways. You need to have a good reason to chase it or you're going to stop once you realize it takes time to catch.

### Learning how to learn
Perhaps the biggest perk is the relentless dedication to learning that being an active developer equips you with. Many developers will need to learn multiple languages over their careers (and [there are many popular ones](http://githut.info/)), and many of these languages have [tens or hundreds of thousands of libraries available for them](http://www.modulecounts.com/). Not to mention all of the tooling, frameworks,  collaboration tools, etc that are part of your everyday routine.

You do not know everything you need to know right now, and that's a good thing. But it does mean that you're not done when you finish your bootcamp, degree, tutorial, etc. In fact in many ways it's opened doors for more things to not know. If you can get to a point to where that's a comfortable idea, you're on your way.

### Computation and programming
Last but not least comes the place where we began: learning the essence of what it means to program. It is true that the more you know, the better off you will be. If you know about memory management and garbage collection, that's amazing! If you know about why we have packet-switched networks and why the internet is architected the way it is, superb! Does your heart start racing when you get to discuss the trade-offs of various systems prescribed by the [CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem), the blockchain, or general purpose consensus protocols? How could it *not*?

**Claim #1:** the more you know, the better you will be.

**Claim #2:** you don't know everything yet.

**Claim #3:** if you wait to know everything you'll never get started.

Any line you draw saying "this topic yes, that topic no" is arbitrary, and more than anything it is important to get started. I do not believe you need to understand memory management to design a Wordpress template. I do believe that you'll learn a lot by actually designing a Wordpress template, and probably motivate future insights. Like software, if we look at learning as incremental we're going to be able to make a lot more happen and include a lot more people.

Let's briefly revisit the programming language question: I personally believe that the "right" programming language for someone to learn in is going to be the one that's most applicable to their interests; not because that's the only language they need to know, but because it'll be the shortest path from knowing nothing to knowing something that's interesting to you. Love math or finding patterns in huge datasets? Check out [Python](https://www.python.org/) or [Scala](http://www.scala-lang.org/). Or perhaps design, visualization, or human-computer interaction? Consider starting with [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript). Wanna make gizmos out of that Arduino you impulse bought six months ago? Go with C or C++. Interested in server software? You might like [Go](https://golang.org/), [Java](https://www.java.com/en/), or [.NET](https://www.microsoft.com/net).

Find something you want to do and *just starting working towards it.* Then keep going.

## Final notes
Many computer scientists will argue that you need to learn about memory allocation, byte ordering, and other low-level shenanigans in order to properly know how to code. There are certainly advantages to knowing this stuff (not to mention that it's pretty interesting regardless), but to argue that anyone who codes needs to understand memory management is quite a stretch. More than anything, the attitude reminds me more of fraternities hazing pledges because "that's what they had to do" than any well-informed educational or occupational evidence.

There is a very reasonable fear that a bunch of programmers who don't know anything about how computers and software actually work will create a bunch of mediocre / dangerous software. This is totally valid, but we shouldn't conflate a need to understand specific topics with an eagerness to learn. Among all of the fields of active practice, computing is one of those that is evolving most rapidly; certain roles and responsibilities will come with a list of topics that are "must have," a list of topics that are a "should have," and then all other possible topics as "good to have." The best developers will not be those that understand memory management the best, but those who are able to learn new shit at a moment's notice and fit it into their own personal view of the world, no matter how large or small that is.

The ultimate goal of learning to code is learning to think more effectively. For students: don't get caught up on particular languages, but focus on what will help code useful to you. For experienced developers: think about your favorite part of development and help spread that. If you love memory management, go for it. But in the off chance you find other things more interesting, help give others a 'why' and you'll help them more than any 'how' you could possibly provide.