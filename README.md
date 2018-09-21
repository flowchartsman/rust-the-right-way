# rust-the-right-way
A step-by-step guide to learning to be a proper, idiomatic Rust programmer
Inspired by https://twitter.com/AndreaPessino/status/1042120425415700480

## Goals
urrently, the repo is a simple unrolling of Andrea's original tweet thread for posterity. The eventual goal is to provide a living document which is single set of instructions that any developer can follow to learn Rust in as efficient and idiomatic of a way as possible at that point in time. It will ideally be:

* Efficient: a single path only with as few branches or optional routes as possible.
* Parsimonious: composed of only the best sources and exercises, in the best order, to provide the optimal path to learning based off of prior principles
* Accessible: favoring free sources whenever possible
* Democratic: community driven with issues being created on a point-by-point basis with discussion and voting on changes

## Unrolled thread
A THREAD ABOUT LEARNING THE RUST PROGRAMMING LANGUAGE @rustlang

Rust is a practical solution to concrete problems that have hindered progress in software development for the last two decades. It is a leap forward in potential performance, scalability and productivity.
When experienced coders try out a new language the process usually goes something like this: skim the docs as quickly as possible, go over some samples until one has “got the gist,” write some code; the expectation is that details and deep concepts will reveal themselves with use
and that writing code is going to be the quickest way to familiarize oneself with the new tool. If you are learning Python, Java, JS, C#, Go, etc. this approach works well, mostly because these languages are basically all the same. If, on the other hand, you approach Rust like
this you will probably be frustrated. There is nothing especially difficult about Rust (no more than C/C++, at least), but Rust combines novel concepts and refined ideas from other languages into a surprisingly innovative whole. Its design is cohesive, purposeful and visionary.
It is different enough to require actual studying.

At a glance Rust looks like a C++ cousin, but it really is not, and the resemblance might actually prove misleading for newcomers. This has nothing to do with ability or experience – you just need to put in the time to acquire
some new skills, otherwise before long you’ll end up on Twitter complaining about how you are “fighting the borrow checker.” 

So, here are a few suggestion on how to approach the language to ensure you have a greatest grasp in minimal time:

Step 1) First one is obvious: read
the official RUST PROGRAMMING LANGUAGE book. You can buy it printed on wood pulp or read it for free at https://doc.rust-lang.org/book/2018-edition/index.html (the 2018 edition is the live updated version of the book, the one that will continue to reflect changes to the language). This is the best introductory
text you can get – very easy to read, perfectly paced. Read the whole thing beginning to end, run and study the code samples, even when they seem trivial. IMPORTANT: when you are done reading this book you might think “I get it now” but really, you don’t. The official book does
not go nearly deep enough – it’s a great intro but after this you will be smack in the middle of the “got the gist” phase. You’ve got some more work to do.

Step 2) Read RUST BY EXAMPLE, available at https://doc.rust-lang.org/rust-by-example/ This is a great series of code snippets illustrating
most of the language components. All examples are short, can be run directly (and even modified) in the book’s pages and they each illustrate a specific aspect of Rust programming. This will not take long – study all of them, make sure you modify and play with each one, don’t
move on until you fully understand each chapter. After going through this, you’ll be in a good spot. Then it’ll be time to bring it all home.

Step 3) Read PROGRAMMING RUST, available printed or ebook at https://www.amazon.com/Programming-Rust-Fast-Systems-Development-ebook/dp/B077NSY211 This is a fantastic book and the perfect finishing
touch in your Rust education. It goes deeper than the previous two, and having the others under your belt beforehand will make it more effective and much easier to go through. You don’t really need to finish the book before moving on, just go over the first 6 to 8 chapters and
then start Step 4 while continuing to read the remaining chapters.

Step 4) This is where you start writing your own code. A few more bits of advice: 

- USE as basic a starting point as you can. The easiest way I’ve found is to use the crate “piston_window” the get a window
setup, drawing, receiving events, etc. You can also reference https://github.com/PistonDevelopers/piston-examples for more examples. Using these as a starting point you can get up and running with your own testbed app in a few minutes. 

- LEARN and use the Rust standard library. It is great and very
comprehensive. 

- AVOID binding to/integrating any existing non-Rust code, yours or otherwise. Your current code base will be useful eventually, but for now do everything from scratch and limit yourself to the Rust ecosystem. It’s probably better than anything else you’ve ever
used anyhow.

- TRY to write Rust code as idiomatic as you can. This is important in any language, but it is IMPERATIVE in Rust, where the language itself goes to great lengths and provides sophisticated tools to make sharing and integrating code with others as effective and
predictable as possible. Follow the recommended coding standard, use the formatting and linting tools Rust provides (rustfmt and clippy, for example). Correct the warnings, do not ignore them. Do things the Rust way – it’s the best way to start and you can always diverge later
on when you have enough experience to adequately assess the implications.

- Try to STOP thinking in terms of the patterns you are used to – do not try to replicate object oriented idioms with Rust. None of these abstractions are necessary or especially beneficial, and while they
have their place the early exploration of a language that does not specifically support them is not it. Start (or go back to) thinking in terms of data layout and interface design, instead of reducing problems to fixed patterns. 

- DON’T WORRY about debuggers or IDEs or
integrating Rust in some other environment. Build and run from a command prompt, do without a debugger – you will not need it for a good while.

And finally: give it time. It will take a while, but you will find that Rust was well worth the investment.
