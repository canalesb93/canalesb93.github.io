---
layout: post
title:  "Interview prep"
subtitle: "What I've learned about interviewing"
date:   2015-10-07 23:56:45
categories: [tools, tech, productivity]
---

# Introduction
I spent a large part of my summer preparing for tech interviews so I could spend my last summer at an internship. I prepared for different companies such as `Facebook`, `Microsoft` and `Google`. As of October 6, I've recieved an internship offer at Facebook and Microsoft is looking to fly me to Seattle for onsite interviews this weekend(**UPDATE[10/23]**: recieved offer). I'm not a interviewee expert but here's what I can share from my experience.

---

# Material

## [Cracking the Coding Interview <i class="fa fa-link"></i>](http://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X)
I knew for a while that I was gonna get a Facebook interview so I started by preparing for that one. I started by reading [Cracking the Coding Interview](http://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X) by **Gayle Laakmann**. A lot of people asked me if I solved all the problems, I did not *solve* them all, however I did make sure I understood them all. Problems are pretty well chosen and even though you may think you won't get *that* problem, the topics they cover are important. I personally think it's a good idea to buy a notebook and start doing some of the problems in there. I organized by topic and wrote solutions to problems I think are important and also approaches about the topic that are pretty common in problems.

###Topics I read from the book include:

* Linked Lists
* Binary Trees
* Stacks
* Queues
* Vectors/Arrays
* Hash Tables
* Graphs
* Bit Manipulation
* Recursion
* Dynamic Programming
* Big-O Time
* Breadth First Search
* Depth First Search
* Binary Search
* Merge Sort

The book also has a really nice part about each company, which will help you understand how their interviews differ from each other.


## [Leetcode <i class="fa fa-link"></i>](http://leetcode.com)
After I was done with the book, I started doing problems from [Leetcode](http://leetcode.com). I started with easy ones, and eventually I made the good habit of simply opening the page and choosing a random problem and try to solve it.

## [Glassdoor <i class="fa fa-link"></i>](http://glassdoor.com)
Looking for interview questions at [Glassdoor](http://glassdoor.com) helped me find popular problems that *facebook* was using and getting a general idea of how difficult the problem may be.

## Mock Interviews
Simulating interviews with friends helped me a lot. This is probably the step most people skip before actually interviewing. I practiced interviewing with 2 friends about 10 to 15 times. **The 3 of us got internship offers.** Seriously, just grab a friend and a whiteboard and start throwing problems at each other.

## [Pramp <i class="fa fa-link"></i>](http://www.pramp.com)
After my first interview with *Facebook* I recieved positive feedback and was told I'd have my second round in 2 weeks. I decided to double my effort and started scheduling practice interviews at [Pramp](http://www.pramp.com). Pramp will schedule an interview with someone else who is also interviewing. You will both interview each other and then give feedback. This step is a hard one, interviews are stressful, and I decided scheduled 3 at Pramp before my actual interview. It's tiring but pramp gave me a wider perspective and helped me understand what aspects I needed to improve.

Interviewing with strangers is different than interviewing with a friend. Usually you will know nothing about your who will be your interviewer. So Pramp will help you get used to this.

## Pseudo Code
I've used psuedo code in most of my interviews, it helps me structure the code before actually getting to program it. It helps to practice before actually trying it in an interview. It's also important to know how specific your psuedo code will be, the faster you can write it the better. Here is an example of how I'd do it.

{% highlight ruby %}
sortWithAlphabet(word, alphabet)
  generate map with alphabet
  return sortWithMap(word, alphabet, map)
end

sortWithMap(word, alphabet, map)
  generate array of numbers with map
  sort array of numbers
  generate array of numbers to chars from alphabet
  return result
end
{% endhighlight %}

## Questions
Prepare a couple of questions to ask your interviewer. Here are some examples:

* What would make me really successful as an intern at [company name]?
* What's your favorite/least-favorite thing about working at [company name]?
* What's an intersting challenge you've faced while working at [company name] or at project [project name]?

The questions you ask are important. I think it shows how interesting you are for working at company X.

---

# Good luck

Good luck preparing and remember to have fun!

## Resources
<div class="link-box"><a href="http://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X"><span></span>Cracking the Coding Interview [Amazon]</a></div>
<div class="link-box"><a href="http://leetcode.com"><span></span>Leetcode [Site]</a></div>
<div class="link-box"><a href="http://glassdoor.com"><span></span>Glassdoor [Site]</a></div>
<div class="link-box"><a href="http://pramp.com"><span></span>Pramp [Site]</a></div>