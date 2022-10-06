---
layout: post
title: "CS 61A Exam Advice"
# categories:
author:
- Rebecca Dang
---

Are you a CS student at UC Berkeley taking CS 61A (or a DS student taking CS 88)? Want exam advice? Read this post to find out my tips and tricks.

# Studying Approaches

Take 2-3 practice midterms from previous semesters so you can get a feel for the pacing and types of questions that show up on exams. Do not take more than 5 because you will just end up stressing yourself out and becoming burnt out. Get plenty of sleep, rest, food, and water.

It may also help to study with other people (e.g. form a study group) so you can go over practice midterm solutions together. However, I recommend doing the entire practice midterm yourself so you know what you don't know and what you do know.

**Where can I find practice exams?**

Generally, the course website will have practice exams under the **Resources** tab. CS 61A sorts exams by semester and also by topic, so do whatever you think is best. Additionally, you may be able to find more exams on [HKN](https://hkn.eecs.berkeley.edu/exams) or [TBP](https://tbp.berkeley.edu/courses/)'s exam databases.

**Review Sessions**

Often, course staff, [CSM](https://csmentors.berkeley.edu), or [HKN](https://hkn.eecs.berkeley.edu) will host review sessions. Take advantage of those to review the material and also go over practice problems!

# Approaching Code Writing Questions

My general advice for approaching coding questions is:

## 1. Understand the problem

a) Read the problem text and annotate important stuff (e.g. parameter names, parameter types, what the function returns, the return type, whether the function mutates anything (you will learn mutation later)) on the template code.
b) Read at least 2 of the doctests and make sure you understand how input got turned into the output. This is helpful for catching edge cases and thinking about how you might implement the function.
c) You can usually tell what concept they're testing you on by reading the problem. Use this knowledge to recall common problem-solving strategies/patterns. For example, if it's a digit manipulation problem, you can probably put something like `n //= 10` somewhere (this is not guaranteed but is a good place to start).

## 2. Guesstimate and/or pseudocode

At this point, you should have a hopefully somewhat solid understanding of the problem, even if you're not 100% sure how to implement it. From here, you can usually do one of 2 things:

a) Look at the template code and guesstimate what goes in the blanks based on that, based on tip 1c, and based on the multiple choice options (if there are any).
b) OR you can ignore the template code entirely (especially if you find it distracting) and then try to pseudocode your own algorithm. Then go back to the template code and try to make it fit.

## 3. Verify your solution

Assuming you are not running very low on time, I highly recommend going back to 1 or 2 doctests and going through the code you wrote as if you were Pytutor. It might be helpful to draw an env diagram here too to make sure your solution works. This is a very important step because in the heat of writing the code, you might've missed an edge case or did an off-by-one error or some other silly mistake that you probably don't want to be banging your head over when you get the exam back.

Also, remember that you should be writing your code in the answer boxes provided, not necessarily the first blanks you see.

# After the Exam

Congratulations! You survived! It was probably very hard, possibly the hardest exam you've taken ever up until this point, but you made it. Celebrate with friends, go out for boba or some Little Gem waffles. (Sometimes, CSM or HKN will also hand out oreos or cotton candy.) Worrying over your score or what you put down for question 5a will not do much, so just sit back, relax, and wait for scores to come out. Catch up on sleep and work you missed due to studying. You got this!
