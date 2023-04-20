---
title:  "A look at state-of-the-art natural language understanding"
date:   2018-12-19 08:33:24 +0100
categories: external
author_profile: true
read_time: true
comments: true
share: true
related: true
link: https://medium.com/cognigyai/a-look-at-state-of-the-art-natural-language-understanding-5bad18a00fb7

layout: single
---

<div class="image-container">
  <img src="https://miro.medium.com/v2/resize:fit:4800/0*9Tmp6FOTvRPB0-MD" alt="Unsplash Image">
  <a href="https://unsplash.com/@franki?utm_source=medium&amp;utm_medium=referral" target="_blank" class="credit">Photo Credit: Franki Chamaki on Unsplash</a>
</div>



In this article we want to take a closer look at intent classification. 

<!--more-->




At Cognigy it’s our mission to enable all devices and applications to intelligently communicate with their users via naturally spoken or written dialogue. With Cognigy 3.2 we released Cognigy NLU 2.0, our all new natural language understanding technology.
What is intent classification?

Intent classification is the art of understanding what the user wants.
A customer asks to speak to a human supervisor. He might say something like “I want to talk to the manager”. With Cognigy’s new handover feature we could readily accommodate such a request.
How do we identify this intent in a natural conversation?

When you design a conversation you create a list of intents, each with a number example sentences that represent what a user might say to express his intent. Based on this information the AI learns to classify the intent of any possible input sentence.
How to evaluate intent classification?

A good AI system is able to map new input sentences correctly to an intent even if it has never encountered them before. By creating a test set of unfamiliar sentences it is possible to benchmark and evaluate different chatbot and conversational AI platforms.

In 2017, computer scientists from the Technical University of Munich have published a paper “Evaluating Natural Language Understanding Services for Conversational Question Answering Systems" — it has become the most authoritative benchmark in the field.
What do we evaluate?

The paper presents three data sets or Corpora: Chatbot, Ask Ubuntu and Web Applications. The data is sourced from real-life users and has been manually labeled by the researchers. Each data set is increasingly complicated and harder to classify for the machine, we have:

    Chatbot
    This set is based on data from a mobile transportation chatbot. It has two intents:
    — users ask for transport connection from A to B
    — users ask for the arrival or departure time of the next train or bus
    The training example sentence set is relatively large with 100 sentences and highly repetitive.
    Ask Ubuntu
    The data set has been scraped from the Stack Overflow Ask Ubuntu Q&A forum. For example, one intent revolves around setting up a printer. The data set has about half the number of example sentences with 53 and a larger number of 5 intents.
    Web Applications
    Like Ask Ubuntu this data set is based on Stack Overflow. It is designed to be most challenging, with only 30 example sentences and a total of 8 intents.

Overview of Chatbot, Ask Ubuntu, Web Application data sets

With Cognigy NLU 2.0 we’re pleased to achieve the first near human-level performance also on the most challenging Web Applications data set with a noticeable difference to competing platforms.

F1-Score on Web Applications

Overall, Cognigy NLU 2.0 achieves state-of-the art performance:

F1-Score by data set and overall after micro-averaging
