---
layout: post
title: OOP Week Twelve
---

## What did you do this past week?
This week, our class discussed inheritance in C++ and the usefullness of the keyword 'virtual'. I learned an importance lesson this week
about the behavior of a child class. When the default constructor of a child class is called, so is its parent's. This behavior is explained
due to refinement overriding. However, copy assignment does not exhibit refinement overriding, rather replacement. So when you define
the copy assignment for a child class, it's parent's copy assignment does not get invoked. 
Virtual is a nice keyword that allows an object to call the 'correct' method. (And it can only be applied to methods.) If a child class and
a parent class share a method, and you have instantiated an object of type parent with it's child (A a = new B, where B:A), then using
the virtual keyword on its shared methods will sort out which method should be called. (In this case, we want B's methods to be called). 
I could have this mixed up, hopefully not! The use of virtual in C++ allows for dynamic binding, or runtime binding.

I also spent a lot of time making little progress on a graphics assignment. I keep getting blocked as I work through the tasks and 
understanding why takes a lot of time.

## What's in your way?
This week is going to be rough and with little sleep. I have my Life assignment due on Thursday and a graphics assignment due on
Tuesday but I'll likely take an extra day. 

## What will you do next week?
Try to stay calm as I spend most of my time in the lab. I need to also get a solid understanding on the use of the Cell class in our
Life assignment. 

## Tip of the Week
Start studying for our final this weekend! It will be challenging after wrapping up an assignment, but we won't regret it. 
I will probably start reviewing the different types of casts have learned class. Here is a link (yes, top result in Google) to start
reviewing them!
[Casts] (https://www.tutorialspoint.com/cplusplus/cpp_casting_operators.htm)
