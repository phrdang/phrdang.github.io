---
layout: post
title: "Being a Summer Lecturer for CS 61A at UC Berkeley"
author: Rebecca Dang
---

In November 2024, I watched [*My Old Ass* (2024)](https://en.wikipedia.org/wiki/My_Old_Ass), a
coming-of-age comedy drama. Aside from being a hilarious and heartfelt movie that I highly recommend,
one of the scenes has still stuck with me after all these years.

It's a conversation between the main character, Elliott, and another character, Chad.
Elliott tells Chad about how she's sad about saying goodbye to her family and leaving their
farm behind to start college:

> **Chad**: Do you remember the last time you were a little kid and went to a friend's house and just like,
> played pretend all day?
>
> **Elliott**: I mean, I remember doing that a lot.
>
> **Chad**: Yeah, but can you remember the very *last* time you ever did it?
>
> *Elliott shakes her head no.*
>
> **Chad**: Isn't that sad? To think that there was a time we were just like, out riding bikes with
> our friends like imagining we were being chased by zombies. Covered in dirt and sweat,
> having the *best time*. And then we went home that night and put our bike in the garage and
> went to bed not realizing that was the last time we were ever gonna do that. But the thing about
> not saying goodbyes is that you also miss savoring when it might be last time you'll ever get do that thing.

In the past 2 years, I've had many of my own "lasts": The last day of an internship, the last day
of undergrad, the last day of my master's. 2 weeks ago was my last day in-person as a summer lecturer
for [CS 61A](https://cs61a.org): The Structure and Interpretation of Computer Programs on Thursday,
August 13, 2026.

My last day was relatively chill, since at that point we'd already administered the final exam
and finished grading it, and all that was left to do was publish final letter grades. I did some work
in the new Gateway building, said my goodbyes to some 61A staff, got lunch
with some friends at [Mezzo](https://maps.app.goo.gl/pu44PrRuAEnrfn1j9), and ended the day with a
celebratory dinner at [Jupiter](https://maps.app.goo.gl/w8sxB6FQe3eJ8QiT6)
in Downtown Berkeley with some other 61A staff. (Any Berkeley student will tell you these were
very quintessentially Berkeley things to do.)

![CS 61A staff dinner at Jupiter](../../../../assets/images/posts/summer-lecturer-2026/jupiter.jpeg)

## The journey to lecturer

Like hundreds of CS and EECS students, CS 61A was the first computer science
class I took at Berkeley and it has stayed near and dear to my heart. Despite being most
students' first Berkeley CS class, there is nothing particularly "introductory" about it:
It's more of a CS1.5 than a [CS1](https://dl.acm.org/doi/10.1145/1734263.1734335) class,
covering 3 programming languages (Python, Scheme, and SQL), recursion, and even some
data structures (linked lists and trees). Up until this point, I had only taught classes
I had never taken (it's a long story), so teaching 61A and being an official instructor
for the first time felt surreal and full circle.

In order to be a lecturer at Berkeley, you need to have a master's degree, which is the main reason
why I applied for [Berkeley's 5th Year MS in EECS program](https://eecs.berkeley.edu/academics/graduate/industry-programs/5yrms/)
in the first place. The timing worked out
quite nicely: The EECS department knew that they would need to hire someone new to teach CS 61A
in Summer 2026 and applications were opened as early as Fall 2025. I applied during winter break
(the application consisted of a teaching statement, cover letter, and references) and was
interviewed in Spring 2026. It also helped that I took [CS 302](https://cs302.org), a CS
education/pedagogy course which greatly prepared me for summer instructing.
I was officially hired a few weeks before the start of summer session C (when 61A would occur),
and the ball rolled on from there.

## The day-to-day job

As the sole instructor of the course, I was responsible for delivering all of the lectures
(every day Monday - Thursday from 5-6:30 pm in Li Ka Shing 245) and supervising a course staff
of 10 TAs and 10 tutors (many of whom were first-time course staff). Since I had more discretion
now as a lecturer, I made several changes to how the course was structured after discussion with my head TA, Sriya Kalyan:

- Removed all assignment and attendance drops (replaced with excused absences if they emailed us with a valid reason beforehand), because of how fast-paced the summer is and how important each assignment and section is to students' learning
- Added weekly quizzes (5 in all) through UC Berkeley's [computer-based testing facility (CBTF)](https://rtl.berkeley.edu/services-programs/computer-based-testing-facility-cbtf) and downweighted the number of points students received for completing assignments, since AI coding tools have made assignment completion a poor signal of students' actual understanding
- Partnered with Oindree Chatterjee to pilot a new assignment reminder tool, [Autoremind](https://autoremind.eecs.berkeley.edu/), for research purposes
- Partnered with Aaryan Mehta to pilot a new academic integrity tool, [Provenance](https://provenance.eecs.berkeley.edu/), during the [Cats](https://inst.eecs.berkeley.edu/~cs61a/su26/proj/cats/) project (the second 61A project which teaches recursion)
- Wrote the midterm and final exams with the help of TAs and tutors who volunteered to do so (usually the instructor(s) write the entire exam themselves)
- Added an [Exceptions II lecture](https://docs.google.com/presentation/d/1HjQgnHhNCTOYgL7c8xay3SIzNHktEaVfTJ98TIDDkwo/edit?usp=sharing) which included not only exception handling in Python, but also software engineering topics like unit testing, test coverage, and debugging
- Delivered 2 special topics lectures: [AI Coding Tools](https://docs.google.com/presentation/d/1nuNLFxCe_1MueTF26ClNISB6CQtKdaQxt_pu2cvyHyM/edit?usp=sharing) (with TA Amy Li) and [Web Applications](https://docs.google.com/presentation/d/1X1dsyyG4dwBmqvCGgt1aznZVwu5rRnRH7mRUZS1WF-0/edit?usp=sharing) (with DATA 6 instructor and friend Abby Brooks-Ramirez)

Generally I think these changes were positive and will continue for Fall 2026 (for example,
quizzes will continue and Provenance will likely be used for all assignments now,
not just Cats). Removing drops did cause some stress and additional overhead for the admin TAs,
who now had to field hundreds of emails from students who needed to be excused from lab or discussion
for one reason or another. Provenance was also a bit hard to use and setup for some students, and we
ended up waiving the requirement to submit a "bundle" (a `.zip` file generated by the Provenance
VS Code extension) for certain students. We also ended up announcing an overall quiz grade adjustment
for all students, which was replacing their lowest quiz score with the average of the remaining 4 quizzes.
(This was especially helpful for students given that they struggled on Quiz 4 more than other quizzes.)
Staff were very enthusiastic about exam writing given how rare it is for 61A staff to get this chance,
and I was very happy to provide structure and mentorship to ensure high-quality exams.

![First lecture in Li Ka Shing 245](../../../../assets/images/posts/summer-lecturer-2026/first_lecture.jpg)

Outside of these changes, 61A ran the same way it has for the past decade or so: We spend
most of the time teaching control, functions, higher-order functions, recursion, mutability, OOP,
and basic data structures in Python, then learn some functional programming and how interpreters work
in Scheme, and finally learn some declarative programming in SQL. I didn't realize until 2/3 of the way
through that this would be the last time 61A would be taught this way (more on that below).

I also didn't realize how much time being a lecturer would be. I remember thinking to myself, *Wow,
I'm going to have so much free time to hang out with friends, actually have a workout schedule,
and read some papers or novels.* What actually ended up happening is I would live and breathe 61A
from practically the moment I woke up to the moment I went to bed, with the exception of Fridays
and weekends. (Even then, I ended up working a bit on the weekends.) Lecture prep consisted of
watching Professor John DeNero's YouTube lecture videos, deciding which parts I wanted to keep
and which ones I wanted to add or put a spin on, making slides, and creating practice problems
and demos. It took me anywhere from 3-6 hours to put together a single lecture, and this was
for topics I had experience teaching (through DATA C88C). I still ended up with a bunch of typos,
which was very embarrassing whenever I'd catch them while presenting the lecture.

Aside from lecture, I also:

- Attended weekly 61A staff meetings
- Attended weekly summer instructor meetings with Professors Dan Garcia
and Michael Ball, the EECS summer session coordinators and my unofficial bosses. (My official boss
was the CS division chair, Professor John Wawrzynek.)
- Hosted weekly instructor office hours for answering course-related questions and "tea hours" (an idea I stole from my MS advisor, Professor Lisa Yan) for answering all other questions (e.g. career- or research-related)
- Reviewed the draft questions (and their variants) for the weekly CBTF quizzes
- Wrote exam questions, reviewed other people's problems, and finalized the exams overall

Up until this point, I had never been a TA during summer, so the 2x speed was quite relentless,
especially from the standpoint of exam writing. Week 1 was basically a bust since we were getting set up,
Week 2 we had our first CBTF quiz, and then by the end of Week 3 we needed to have the midterm exam
ready and printed so that we could proctor in the beginning of Week 4. This is probably the main
reason why the exam ended up being harder than it should have been, and we ended up giving everyone
a free 10% point boost to get the mean to ~60%.

I say all of this as if being a summer instructor was a horrible experience, but actually it
was a very fun, rewarding, and fulfilling job. I'll talk more about the fun stuff next, but I also think
it's important to acknowledge the "not so fun" parts of being an instructor: Dealing with
the bureaucracy involved in officially hiring course staff, handling academic misconduct,
handling the logistics of the move from Soda Hall to the new Gateway building, worrying about
my students' physical and mental health, and commuting all the way from San Jose
via BART in the last 2 weeks of summer session since my Berkeley lease ended on July 31
(shoutout to my parents and [Baypass](https://pt.berkeley.edu/public-transportation/baypass-information)).

## The fun stuff

Being a summer instructor was also super fun! Not only was everyone on course staff very competent
at their jobs, but they were also wonderful, funny, and social people. I must admit I was a bit
worried about "fitting in" given that I was somewhat of an outsider,
but it was clear after the first staff meeting that we'd get along quite well.

One of the TAs, Lavanya Shyamsundar, put together a "big-little" program, where first-time staff (littles)
were grouped together with more senior staff (bigs). Each big-little group competed to complete the most social activities.
Here's a photo of my big-little group (shoutout Sriya Kalyan, Rabia Chadha, and Richard Padilla)
when we got dinner at Crave Subs in Downtown Berkeley.

![Me, Sriya, Rabia, and Richard getting dinner at Crave Subs](../../../../assets/images/posts/summer-lecturer-2026/crave_subs.jpg)

I decided to get an [AMC Stubs A List](https://www.amctheatres.com/amcstubs/alist) subscription
after the staff convinced me of the benefits, and I [watched](https://letterboxd.com/phrdang/)
more movies in theaters than I ever have in my life this past summer: *Backrooms*,
*Supergirl*, *Toy Story 5*, *Disclosure Day*, *Obsession*, *The Odyssey* (3 times, 2 of which were
in IMAX 70mm), *The Invite*, *Spider-Man: Brand New Day*, and *The End of Oak Street*. One of my
favorite, diabolical things we did together as a staff was go see *The Odyssey* at 6 AM at
[AMC Metreon 16](https://maps.app.goo.gl/NxWbx4oj6pdiJtKH6), taking the BART from Downtown Berkeley
to San Francisco at 5 AM.

![CS 61A staff goes to see The Odyssey](../../../../assets/images/posts/summer-lecturer-2026/odyssey.jpg)

I also loved how silly 61A staff was. Many new 61A-nese terms, such as "fade fade fade," "nuke,"
"salutations," and "#imsorry," became part of my daily vernacular. During the AI Coding Tools
special topics lecture, some of the staff came up with a hilarious
[skit](https://youtu.be/O4Op7JgJvJI?si=cVTo86oBYSrDfZEi&t=4099) about the perils of
vibecoding in CS courses at Berkeley.

One big change that occurred over the summer was the move from Soda Hall (the old home of the EECS
department) into the new Gateway building. The company that built the building also sent emails
requesting volunteer photo models, and 61A staff often volunteered.
Additionally, Cal Dining opened a new campus restaurant, the [Gateway Cafe](https://maps.app.goo.gl/ArDS2k9eo8h8tHSq9).
Since we had a weekly staff breakfast before staff meetings on Mondays, we decided to crash
their grand opening and were the very first customers!

![CS 61A staff breakfast at the Gateway Cafe](../../../../assets/images/posts/summer-lecturer-2026/gateway_cafe.jpg)

On the weekends, another fun thing I did was learn how to drive (shoutout to my mom for teaching me).
Hopefully I'll pass my behind-the-wheel test in a few weeks!

## Fun stats

Here's some statistics about CS 61A I computed for the [last lecture](https://docs.google.com/presentation/d/17yYFCoy03oIXTHZUSQj4JsmxpSMjyCoKcy1EQtCuwSQ/edit?slide=id.g3f5f30bc286_0_0#slide=id.g3f5f30bc286_0_0):

- We went from ~265 students to ~168 students by the end. A lot of students dropped in the beginning because it was announced late that all EECS summer courses would be in-person only this summer (in the past, there have been remote options). Even more students dropped after the midterm and final exams (in summer, students can drop quite late in the term, and I suspect a lot of students were concerned about their grade).
- Students completed 238 required problems across all assignments and exams
- Students collectively ran the OkPy autograder 136,662 times
- Our grading staff processed 451+ assignment extensions
- Our content and infra staff made 179 commits to the 61A monorepo `master` branch
- Staff sent 37,832+ Slack messages
- The course inbox received 1,663+ emails

## Looking back and forward

Looking back at how the summer went, here are some miscellaneous reflections:

- Using [PollEv](https://www.polleverywhere.com/) was very useful for lecture interaction/engagement, and for encouraging students to discuss tricky problems with each other.
- It's very hard to get the timing right for lecture. I tried to spend the first hour doing direct instruction and PollEv questions, and the last 30 minutes doing guided coding practice. Often what ended up happening was I would have to rush through the practice problem solutions.
- I didn't realize until the end of the summer that the projector contrast was terrible, so even though I zoomed in and used the Dark High Contrast theme on VS Code, it was very hard to view the code whenever I did live coding. In the future, I'll probably need to switch to Light Mode High Contrast (or hopefully be in a lecture hall with a better projector).
- A lot of the time I spent working as a lecturer were spent doing "first time teacher" things, such as creating my own slides, fixing typos, etc. If I ever teach 61A again, it will probably be much smoother sailing.
- I wonder how much of the feedback we received (e.g. about exam difficulty or course policies) was due to the fact that 61A is often students' first Berkeley CS class and they haven't yet adjusted their expectations to how college courses are. For example, a significant portion of our students were visiting students and high schoolers.
- I should have been clearer with staff from the beginning of the summer what the expectations were for rehiring and promotion, because there was a lot of anxiety toward the end about Fall 2026 staff hiring.
- Thanks to a suggestion from Lavanya, we implemented a peer feedback Google Form to give staff a formal, structured way to self-reflect and provide written feedback about the staff they worked. I'm hoping this will continue in the future to make the rehiring/promotion process more fair and transparent.

Toward the end of the summer, I had the privilege of working with Professors John DeNero and Kay Ousterhout,
the CS 61A and DATA C88C instructors for Fall 2026, to provide feedback on the most significant curricular redesign
of those courses since CS 61A transitioned from being taught only in Scheme to being taught in Python, Scheme, and SQL.
Now the news is out: CS 61A will be replacing Scheme with a new functional programming language,
[Gleam](https://gleam.run/). Instead of the Scheme Interpreter, the final project will be Animator,
building an interpreter for a subset of the Gleam language and a web application that can render animations.
61A will explicitly teach more software engineering skills, including allowing the use of AI agents
in parts of the Animator project. Additionally, the legacy custom course infrastructure that has served
61A and C88C for the past decade or so will be deprecated, in favor of light-weight, modern alternatives
such as [GitHub Pages](https://docs.github.com/en/pages), [Jekyll](https://jekyllrb.com/),
and [uv](https://docs.astral.sh/uv/). We discussed much of this together with the returning 61A TAs
in a conference room in a part of the Gateway building not yet open to the public (as the photography
crew that asked for volunteer photo models tried to take candid photos of us).

![A fun photo break during the CS 61A Fall 2026 planning meeting, in the Gateway building](../../../../assets/images/posts/summer-lecturer-2026/fa26_planning.jpg)

## Thank you

Like Elliott and Chad say in *My Old Ass*, it's rare to have the opportunity to  know when you do
something for the last time, say your goodbyes, and savor the moment. I'm so lucky and grateful to have had the chance
to be a summer instructor at my alma mater, let alone be the instructor during such a pivotal moment
in the history of CS 61A. I couldn't have accomplished everything I did this summer without the
support of all of these people:

- My parents
- Berkeley EECS faculty (especially Professors Dan Garcia, Michael Ball, Justin Yokota, and Peyrin Kao) and staff (especially Faye Chou, Hamilton Chang, Glenna Anton, and Karla Thao) who have helped in various ways behind the scenes
- My awesome course staff (pictured below during our last staff meeting), especially head TA Sriya Kalyan and admin TAs Emma Zhong and Amy Li
- My wonderful students, whose curiosity and resilience are why I teach

![CS 61A Summer 2026 last staff meeting](../../../../assets/images/posts/summer-lecturer-2026/last_staff_meeting.jpg)
