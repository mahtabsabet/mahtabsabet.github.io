---
layout: post
title: Why are Software Engineers so bad at estimating?
subtitle: And how can we get better at it?
image: /img/algebra-analyse-architect-architecture-159722.jpeg
---

Right now I'm preparing for a talk I'm going to be giving at [CUSEC 2018](http://2018.cusec.net/){:target="_blank"} 
and one of the things I'm researching is how bad we are at estimating, as an industry.

Turns out, the answer is we are all universally pretty terrible at estimating.

In my first few years working as a developer I just assumed I was so bad at it 
because I was young, inexperienced, naive, etc. But apparently I'm not alone!

According to [a paper by Jørgensen and Moløkken-Østvold](http://ieeexplore.ieee.org/document/1377193/){:target="_blank"}, 
"the average effort overrun of software projects seems to be in the range 30 to 40 percent". 
Think about the implications of this - if I say something will take an hour, and it takes me 1h20m, that may not be a 
huge deal. But if I say it will take me 12 months, and it takes me *3-5 more months* than that, that's pretty
significant.

So it looks like we're all pretty terrible at estimating how long things will take. How can we get better at it?
Here are some tips:

- **Get the requirements.**
   
   Let's say someone comes up to your desk and says "We want to build a website 
where users can see a calendar of events. How long would that take?" You need to make
sure you're on the same page with respect to what is being asked of you. Where are 
these events coming from? Are they being pulled from some other website? Are they hard-coded?
Who are the users? Do they need to be authenticated? Can all users see all events, or are there restrictions based on 
the type of user? Will users be able to interact with these events in any way, like signing up, or creating them, or deleting them?
Make sure the requirements are well-defined - you can't make a very good estimate if you don't know what is being asked of you.

- **Take your time.**
   
   They don't need an answer right this second. Tell them you'll need to think about it,
and that you'll get back to them with an estimate.

- **Think about dependencies.**
   
   You may be reliant on another person or team before you can proceed. It takes time for people to respond to emails, 
or complete tasks. Take this into account when making an estimate.

- **Use past experiences.**
   
   Have you done something like this before? How long did it take you? If you haven't done something like this before,
ask a coworker! 

- **Add a fudge factor.**
   
   Basically, take how long you think it'll take, and double it. Or multiply by 10.
   
   > Hofstadter's Law: It always takes longer than you expect, even when you take into account Hofstadter's Law.
   >
   > --<cite>Douglas Hofstadter</cite>

- **Look back at your previous estimates.**

   Keep track of how long you think something will take, then when it's done, go back and 
   note down how long it *actually* took. This will help you learn from your own mistakes! And after 
   enough data points, you'll begin to understand your own "fudge factor".
   
   
It can be easy to keep your nose to the grindstone and just focus on the fact that you got good work done in the end,
but remember that, given the endemic nature of misestimation in our business, if you can get a reputation for delivering things
when you say you will, you will stand out from the pack. Reliability trumps brilliance in the long run.