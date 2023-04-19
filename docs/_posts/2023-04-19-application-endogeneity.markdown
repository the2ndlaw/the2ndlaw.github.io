---
title:  "Application endogeneity or the strange world of applied research"
layout: post
published: True
date:   2023-04-19 00:00:00 +0100

---


<div class="image-container">
  <img src="/images/nareeta-martin-_gFWc1J57Z4-unsplash.jpg" alt="Unsplash Image">
  <a href="https://unsplash.com/@splashabout?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText" target="_blank" class="credit"> Nareeta Martin on Unsplash</a>
</div>

As a machine learning engineer who left his PhD studies behind for the world of applied industry ML research, I've encountered a conundrum that often goes unaddressed: Application Endogeneity. In this blog post, I'll explain what I mean by this term and share personal experiences to illustrate its impact on applied research in machine learning including recent developments, such as ChatGPT.

## What is Endogeneity?

<!--more-->

Endogeneity is the property of being influenced within a system. In the context of applied research, the system is the product. This means that nothing is truly objective or can be held constant, as every component affects everything else. In my experience working on conversational AI, for example, this has significant implications.

When building a commoditized ML model for business users, the users themselves become part of the ML model as they train the virtual agent. A more accurate model may not always be better, as it could take longer to train, increasing the iteration cycle for users working on their virtual agents. This endogeneity, in turn, affects the overall problem of finding the highest productivity conversational AI platform. More or less time and money invested in training may result in a lower-quality AI agent, but it's essential to consider the trade-offs involved. Everything depends on everything else.

## The Breakdown of Science

Application endogeneity poses a serious challenge to applied research, as the whole system and application are endogenous. This often leads to poor quality research that's difficult to compare or generalize.

Indeed, in my experience, the most impactful research that actually does get applied in the industry is fundamental in nature. This is not only reflected in the scientific community, citation counts, but also in industry practice. A single landmark paper such as Vaswani et al.'s [*Attention is all you need*](https://arxiv.org/abs/1706.03762) has been far more relevant to my work than the deluge of applied papers around conversational AI and related NLP applications even if the research question is directly equivalent to a problem I faced in practice. This isn't because more applied research wouldn't be useful but importantly also because application endogeneity makes it challenging to produce high-quality, objective, and comparable science suitable for research in the scientfic community. For this reason, I have chosen not to publish and strongly advise anyone interested in doing so to invest in long-term, fundamental research. Huge swathes of ML research have become obsolete in the age of LLMs? This can only be a good thing. There are still huge questions both in theory and practice yet unanswered that require research efforts far beyond the short-term horizon of industry that deserve all our attention from machine thought to quantum computing.

## The Need for a Awareness of Application Endogeneity

Given these challenges, it's crucial for those in the applied research domain to either focus on fundamental research or become acutely aware of the implications of application endogeneity. By capturing relevant dimensions of this phenomenon in applied research, we can strive to produce work that is both impactful and scientifically sound. If you do publish and invest in applied research questions please go out of your way to take into account all relevant variables and dimensions of your research question. One often finds, however, that this would be a prohibitively expensive and impractical undertaking.

I believe this perspective sheds light on recent developments in generative AI. This cutting-edge technology embodied in ChatGPT has quickly moved from fundamental advances in open, collaborative science to closed-door, applied research and products used by millions of people. In this post, I argue that the resulting slowdown in publishing is not necessarily the result of ill incentives or intentions. Sure, lack of access to data and resources in academia as compared to industry further exacerbate the problem. But these are challenges that would and have been solved if it was not for a more fundamental problem. Instead, this development can be understood through the lens of Application Endogeneity as a natural situation where conventional beliefs about scientific research are challenged. This is illustrated by the fact that seemingly not a week goes by without a project claiming performance *on par* with OpenAI's ChatGPT in scientific benchmarks. When even a cursory evaluation of the model reveals such statements to be a far cry from the reality on the ground. ChatGPT is not only a model, it is a product; it is fully applied and as endogenous as it gets. Optimizing this objective function is as much an art as it is a science.

For better or worse, the key objective function of applied work is ultimately the market. I'm proud that my applied work has been consistently recognized by clients as well as independent analysts such as Gartner, [for example](https://www.cognigy.com/news/cognigy-ranked-in-first-place-for-all-use-cases-in-the-2023-gartner-critical-capabilities-for-enterprise-conversational-ai-platforms). In my opinion, the key to success is an approach that fiercely adheres to an objective, scientific ideal while being acutely aware of global optimisation problem, the limitations and context of application endogeneity.

**In conclusion, application endogeneity is a critical issue that often goes unnoticed in applied machine learning research. Recognizing and addressing this challenge will enable researchers and engineers to produce more valuable and relevant work, ultimately benefiting the industry and the progress of science.**