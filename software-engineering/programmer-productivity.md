When I was in college, my professor once told me that experience is nothing but pattern matching. The value of experience comes handy when a solution to a previous problem could be used in present context, rather than spending time in the whole loop of thinking about the solution from scratch, making mistakes and then correcting them.

Over the years, after working on multiple software projects, I have realized that there are some key patterns in what I consider unproductive days for a software developer and have highlighted the 5 key areas with highest ratio of productivity gains to time invested (i.e. low hanging fruits).

[*] Context Switching. The lesser effort in context switch, the better performance. Consistency is the key for this because it used shared understanding of brain.

### Software Specification

One of the major setback in a programmer's productivity is when the requirements of a project are unclear from the onset. This could happen either due to lack of clarity in the final deliverable itself or the approach taken to create it. Engineering teams are generally enthusiastic about making flexible software which can often lead to over-engineering. can get bogged down with too much flexibility with software or too much optimation on things which don't move the needle as much. product team or the technical teams are not aligned with product teams. Project specifications should be treated as type of code, and hence should be written very precicely.
clarity of deliverables
efficiency required ( response time, memory used ) are always detrimental to productivity
flexibility : the ability of the system to be quickly and easily reconfigured, such as the case of a general ledger system, which needs to be able to be adapted to differing charts of accounts. Flexible systems will take more effort to develop than rigid systems.

code has little value in of itself; only rarely is a block of code reusable in other contexts.

The second-system effect proposes that, when an architect designs a second system, it is the most dangerous system they will ever design, because they will tend to incorporate all of the additions they originally did not add to the first system due to inherent time constraints. Thus, when embarking on a second system, an engineer should be mindful that they are susceptible to over-engineering it.

Inner-platform effect: A system so customizable as to become a poor replica of the software development platform

### External Dependencies

The more communication required, the lesser the productivity.

It is not always helpful to add programmers. Depends upon two factors : (1) the task can be easily partitioned among all workers without changing overall effort, and (2) there is no communication or interface requirements between workers.
https://en.wikipedia.org/wiki/The_Mythical_Man-Month Brooks's law: Adding manpower to a late software project makes it later.
Therefore, assigning more programmers to a project running behind schedule will make it even later. This is because the time required for the new programmers to learn about the project and the increased communication overhead will consume an ever-increasing quantity of the calendar time available. When n people have to communicate among themselves, as n increases, their output decreases and when it becomes negative the project is delayed further with every person added.

### Tools Avalaible & Familiarity

- Availability of computer resources
  In a study by Thadani it was found that a decrease in response time from 2.2 seconds to .8 seconds increased programmer interaction by 60 percent, programmer output increased by 58 percent, and the code quality improved by more than a factor of two. (Thadani, 1984)

- Programming Tools & Resources

### Programming Methodology

High level languages are faster to write and easier to debug. On the other hand, low level languages offer performance benefits
Modular code is harder to create in starting, but is easier to maintain and reuse.

### Debugging

http://glench.com/LegibleMathematics/
Programmers have to imagine what each line does and how it does it. "Bugs" happen when this mental understanding doesn't match what's actually happening in the program, and because most current programming environments don't provide any feedback or tools for understanding program behavior, discovering and fixing bugs can be extremely difficult for experts and nearly impossible for beginners.

http://antirez.com/news/112
It is very easy to spend an enormous amount of work in order to find bugs. The sum of being good at gaining state about a bug, incrementally, in order to fix it with a rational set of steps, and the attitude of writing simple code that is unlikely to contain too many bugs, can have a great effect on the programmer efficiency.

To remove bugs — to correct misunderstandings of how programs work and make it much easier for beginners to learn — our programming environments need to take program behavior out of programmers' heads and make it visible, tangible, and explorable. In a word: legible.

Build times and

Cross platform frameworks allow developers to leverage there knowledge to reach more customers or solve problems faces by more people.
WebAssembly is in a unique position to be tackling this problem since modern web browsers already have sandboxed OS level access to cameras, microphones, desktop, bluetooth and hopefully GPUs.

Debuggers are not just for fixing bugs but are great for looking at other people code and seeing how it works.

Prettier
IDE Plugins
[Interactive debugging](https://repl.it/)
React boilerplate better suited to my needs (effective for indiehackers who work on creating a lot of different projects)
Writing test cases which makes it easier to come back to that code a year later and have to make changes to it, but have forgotten how it works, having all the tests pass with good coverage provides a significant (but not absolute) level of confidence that you didn't break anything.
If a debugger exists for your environment, use it instead of printing things. This is especially important if compiling or deploying your code takes a long time.

## Random

Plan out your work in some way before you do it. You could write a more formal design doc for large projects, or a short list of steps for smaller tasks. Here's an example for a typical task:
Create a Widget interface.
Write a SomeWidget class with a bare minimum implementation of Widget's API.
Manually test with small inputs to make sure the happy case works.
Write unit tests for SomeWidget.
Adjust code to handle edge cases.
Refactor OtherWidget and existing code that uses it to conform with Widget.
Oftentimes you won't have the mental energy to think deeply about your work. You'd rather just follow simple, clear instructions. This is where referring back to your plan makes things easier. You don't have to think about planning anymore, just following the steps.

I am still a junior developer and have a lot to learn about code review and system design.

> Note: Customize linters to reinforce coding principles of organizations

### Notes

https://www.andrews.edu/~vyhmeisr/papers/progprod.html