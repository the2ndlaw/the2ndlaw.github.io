---
title:  "Cognigy's Universal Language Understanding: A look into the AI black box"
date:   2021-12-17 00:00:00 +0100
categories: external
layout: post
published: True
read_more: False
link: https://www.cognigy.com/blog/cognigys-universal-language-understading-model

---

<div style="background: hsl(0, 0%, 97%);;
border-top: 1px solid rgba(0, 0, 0, 0.1);;" class="l-screen">

<div class="l-page">
<figure style="text-align: center; padding: 15px">
<img src="/assets/image/visualization2.png" style="border:1px solid #bbb; width: 90%; margin: 0 auto; text-align: center"/>
        <figcaption style="text-align:left">
            t-SNE plots of representations from layers of LASER (top) and M-BERT (bottom), where layer 0 corresponds to the non-contextualized token embeddings.<br/>
            Source: Rochelle Choenni and Ekaterina Shutova: What does it mean to be language-agnostic? Probing multilingual sentence encoders for typological properties<br/>
        </figcaption>
    
</figure>
    </div>
</div>


Multi-lingual ability in humans is a familiar trait. More than half the world population speaks at least two languages. This allows humans to do amazing transformations, like reading this article in English and then reproducing the gist of it fluently in another language. Quite a surprising and amazing feat if you think about it.


<!-- 

How does this work? When you think of a "quick brown fox jumping over a fence" it's still the same brown fox in your head - no matter if you speak to you in German, Dutch or English. Such human-like multilingual fluency seems far-fetched for machines - but an effective technology for multi-lingual natural language understanding is readily available.

Cognigy NLU correctly maps inputs to intents in a variety of input languages (right pane) even when example sentences are only provided in English (middle pane).

How does this work? First, a big disclaimer is in order that theory is lagging behind the practice of modern machine learning. No one claims to fully understand how, why and what is exactly going on in a model architecture that has taken NLU by storm since 2017 called Transformer models. Without going into the details: What follows is a crude attempt at explaining what they do.
How AI training transfers meaning across languages

If you consider a sentence like the "quick brown fox jumping over a fence" then somehow the whole is more than the sum of its parts. In order to arrive at such a meaningful representation, you take every word in the sentence and put it into context with the other words in the sentence. You throw your words in a blender, that blender is called the “attention mechanism” inside a transformer where every word can "interact" with every other word. To make that blender produce a meaningful sentence soup and not a bunch of gibberish, you train it. For that you ask the machine learning transformer model to always predict the next word in a sentence, and let it run across large text corpus units like Wikipedia, and other meaningful collections that you can get your hands on.

Now with multi-lingual language models, you train on a very large corpus of text in different languages. The way that multi-lingual transformer language models transfer across languages is suggestive of the fact that they really do build up some cross-lingual, more abstract meaningful representations internally. The same intent meaning or concept maps to the same internal representation no matter which language you use. This is also why these models are so useful in helping us predict intents and other natural language tasks in the first place. The result of which is what you see in Cognigy.AI in the above screenshot.
Acdemic research on cross-lingual representations in AI

Researchers have begun investigating the phenomenon. Chi, Hewitt, and Manning (2020) for example find evidence to suggest that multi-lingual LMs learn certain linguistic universals. As illustrated in one of their visualizations of clustering of syntactic dependency labels across languages:

visualization

t-SNE visualization of head-dependent dependency pairs belonging to selected dependencies in English and French, projected into a syntactic subspace of Multilingual BERT, as learned on English syntax trees. Colors correspond to gold UD dependency type labels.

Source: Ethan A. Chi, John Hewitt, and Christopher D. Mannin: Finding Universal Grammatical Relations in Multilingual BERT

Choenni and Shutova (2020) investigate how multi-lingual sentence representations cluster across layers of increasing depth in multilingual models. This following graphic shows clustering of embedding representations across neural network layers of increasing depth. They are initially well separated by language. In subsequent layers inside the network the representations coalesce into common representations detached from the original language. The separation into languages towards output layers in the second row is due to a different training regime.

visualization2

t-SNE plots of representations from layers of LASER (top) and M-BERT (bottom), where layer 0 corresponds to the non-contextualized token embeddings.

Source: Rochelle Choenni and Ekaterina Shutova: What does it mean to be language-agnostic? Probing multilingual sentence encoders for typological properties
What is the impact on conversational AI in practice?

While multi-lingual models are great, we still recommend for the main languages the virtual agent to use the main language. First of all, some information might get lost in translation so to speak. Well-written German example sentences will generally still outperform intents written in another language for German inputs. While you can also write multi-lingual intents for the universal model there are still practical considerations that yield advantage to the monolingual approach. Knowing many languages comes with a trade-off and a significant overhead. They are more challenging to train, are as a result larger, slower, and may not always benefit from the latest innovations. -->
