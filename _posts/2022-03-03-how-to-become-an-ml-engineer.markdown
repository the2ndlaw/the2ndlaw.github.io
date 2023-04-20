---
title:  "How to become an ML Engineer?"
date:   2022-03-03 00:00:00 +0100
categories: engineering
author_profile: true
read_time: true
comments: true
share: true
related: true
published: true

layout: post
header:
  image: /images/connections.jpeg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"

---


{:toc}

# Introduction

<div class="image-container">
  <img src="/images/connections.jpeg" alt="Unsplash Image">
  <a href="https://unsplash.com/" target="_blank" class="credit">Photo credit: Unsplash</a>
</div>


Both internally and externally, with potential hires for example, the question of what to learn and how to become an ML Engineer comes up. Now there's almost unlimited amount of material and advise out there.

In the face of this information overload there's still a bit of a contribution to make here. I'd like to share what actually mattered and impacted myself. To give a bit of a shortcut, or direction, say "trust me", stop searching, pick this book or approach, do this and get to work, you'll be awesome.

<!--more-->

## What is ML Engineering?

ML Engineering = Machine Learning + Software Engineering

Therefore it's prudent to acquire a strong foundation in machine learning as well as software engineering. They come together in applied production ML involving ability to design a ML system, understand its development lifecycle and master the DevOps or MLOps infrastructure around it.

For each of the subjects below I tried to distill three simple ingredients: a sure-fire way towards mastery of the subject, a trusty reference book and a brilliant online course to get you started:

- [Machine Learning](#machine-learning)
  - [Foundations](#foundations)
  - [Deep learning](#deep-learning)
  - [NLP and Transformer models](#nlp-and-transformer-models)
- [Software Engineering](#software-engineering)
  - [Algorithms and data structures](#algorithms-and-data-structures)
  - [Engineering work best practices](#engineering-work-best-practices)
  - [Advanced engineering topics such as concurrency](#advanced-engineering-topics-such-as-concurrency)
- [Production ML](#production-ml)


**🙌 Best way to learn**

The best way to learn usually involves putting in the hard work and hours.

**📘 Book**

A good book is still one of the best ways to acquire deep knowledge, set the bar in terms of best practice. I try to recommend a good book you can trust as a reference and spend your time on delving deeper into the topic.

** 🧑‍🏫 Course**

I would recommend to use courses as a structured starting point of your learning. Remember they are only the start. They equip you with the necessary foundation to commence with the "best way to learn" in earnest.



# Machine Learning

## Foundations

It's important to have a decent grasp mathematical and theoretical foundations of ML.

🙌 Best way to learn

To acquire math/stats foundations the best way to learn is to do the exercises and problem sets. Equivalent to what you need to do to pass exams at master level of a relevant degree in ML, Physics, Statistics, Econometrics etc.

📘 Book

You can pick any technical subject with a dose of linear algebra to do the exercises. Might as well pick a ML book and pick the classic [The Elements of Statistical Learning by Hastie et al.](https://hastie.su.domains/ElemStatLearn/) which covers the field very well.

🧑‍🏫 Course

Coursera's [Mathematics for Machine Learning: Linear Algebra](https://www.coursera.org/learn/linear-algebra-machine-learning) and [Andrew Ng's](https://www.coursera.org/learn/machine-learning) are still a good start.

## Deep learning

🙌 Best way to learn

The best way to learn is to implement papers/models yourself from scratch and get a trainable, working model.

📘 Book

[Deep Learning from Goodfellow & Bengio](https://www.deeplearningbook.org/).

🧑‍🏫 Course

Let's go with [FastAI Practical Deep Learning for Coders](https://course.fast.ai/).

## NLP and Transformer models

🙌 Best way to learn

Similar to the above, implement papers/models yourself from scratch and get a trainable, working model as well as higher level applications in NLP such as a small sentiment analysis project.

📘 Book

The field is so new and evolving so fast there's no standard reference yet. Read papers, [Attention Is All You Need by Vaswani et al. (2017)](http://arxiv.org/abs/1706.03762) started it. Often blogs like [illustrated transformer](https://jalammar.github.io/illustrated-transformer/) or [illustrated Bert](https://jalammar.github.io/illustrated-bert/) are a great resource.

🧑‍🏫 Course

[CS224n: Natural Language Processing with Deep Learning](https://web.stanford.edu/class/cs224n/).


# Software Engineering

## Algorithms and data structures

ML applications often have interesting problems and demanding performance requirements. In general, for any kind of software engineering job it helps to be an effective software engineer.

🙌 Best way to learn

Similarly to math foundations, you have to do the work and solve exercises and problems. If you want to have fun, [Project Euler](https://projecteuler.net/) will teach you the difference knowing your algorithms and data structures makes. You can also just hit [Leetcode](https://leetcode.com/) and improve your code fluency while sharpening your algorithmic thinking.

📘 Book

[Cormen's Introduction to Algorithms](https://web.iiit.ac.in/~pratik.kamble/storage/Algorithms/Cormen_Algorithms_3rd.pdf), 

🧑‍🏫 Course

I recommend [courses at educative.io like the Python for Programmers series](https://www.educative.io/path/python-for-programmers).



## Engineering work best practices

This covers everything from version control, how to create and write great PRs to how you refactor code. In general, I'd say this is less important for ML engineering as compared to normal engineering as the complexity and size of the codebase and project is somewhat limited by the inherent complexity of ML.

🙌 Best way to learn

Best way to learn is to actively work in a team with a strong engineering culture. What you can always do is immerse yourself in the wider industry community. Read [hacker news](https://news.ycombinator.com/), check out open source projects, read blogs and books.

📘 Book

[Here's a list of popular books which are definitely worth their salt](https://thesmartcoder.dev/10-must-read-books-for-software-engineers/).

🧑‍🏫 Course

As this is very applied and concerns how you work I'm not sure there can be a good course which can teach this. If you have a suggestion let me know.


## Advanced engineering topics such as concurrency

Beyond the fundamentals and general best practices there's a vast field of advanced topics that you'll sooner or later have to deal with also in ML Engineering. Concurrency being a big one. But what is a memory mapped file, for example, and how does it work? Again this is often very important in practice.

🙌 Best way to learn

On the job. If the topic comes up make sure you learn and know your shit :)

📘 Book

Books are challenging because they quickly get stale. Read the standard library documentation, for example, instead.

🧑‍🏫 Course

[Check out the educative.io advanced concepts in Python course](https://www.educative.io/module/advanced-concepts-in-python)

# Production ML

Putting it all together. You want to end-to-end engineer and design a production ML system. Understand its development lifecycle, how you go about executing this in a structured manner down from clearly defining your problem, picking the right metrics and model, designing for scale to mastering the DevOps or MLOps infrastructure around it.

🙌 Best way to learn

Short of doing it in practice: think of problems that could or have been solved in ML. How would you design a solution? How is it actually engineered in practice? There are engineering blogs and a growing set of resources to teach you how to do this.

📘 Book

Andrew Ng's [Machine Learning Yearning](https://www.deeplearning.ai/wp-content/uploads/2021/01/andrew-ng-machine-learning-yearning.pdf) is the closest I've seen coming to applied industry reality and what ML Engineering job is actually like.

🧑‍🏫 Course

[Chip Huyen](https://huyenchip.com/) is bearing the torch here with [CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/). Check out her site for many more resources.
