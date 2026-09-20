---
layout: page
title: LLM-Based Generative Retrieval
description: Using large language models to generate structured item IDs directly for large-scale recommendation and advertising.
img: assets/img/6.jpg
importance: 1
category: industry
---

Conventional recommendation retrieval embeds users and items into a shared space and searches it with approximate nearest neighbors. **Generative retrieval** takes a different route: represent each item as a sequence of discrete semantic tokens, and have a model _generate_ the identifier of the item to recommend, the way a language model generates text.

During my internship with the Commerce Ads Technology team at **ByteDance**, I worked on a generative retrieval branch for large-scale recommendation over a candidate space of billions of items, built on hierarchical Semantic IDs.

## Contributions

- Built and scaled **full-parameter supervised fine-tuning pipelines** for LLMs over millions of user behavior sequences, systematically studying prompt construction, model scale, training objectives, and semantic grounding.
- Designed **trie-constrained beam search** so decoding can only produce valid Semantic IDs, eliminating malformed generations at inference time.
- Improved retrieval quality by roughly **5.9% Recall@1 and 29.9% Recall@50**, while increasing output diversity and mitigating the output collapse and over-concentration that generative retrievers are prone to.

_Work conducted during an industry internship; described here at the level of publicly shareable methods and outcomes._
