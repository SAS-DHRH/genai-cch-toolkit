---
section: Definitions
nav_order: 2
title: Models
topics: foundation models, LLMs
---

## Models 

#### ℹ️ Foundation models
**Foundation models**, also known as ‘general-purpose AI’ or ‘GPAI’, are general-purpose AI systems trained on broad data (generally using self-supervision at scale) and designed to produce a wide and general variety of outputs, including compelling text, images, videos, speech, music, and more. They can be standalone systems or can be used as a ‘base’ (hence “foundation”) on which other applications can be built and thus adapted to a wide range of downstream tasks.

[This is in contrast to many other AI systems, which are specifically trained and then used *for a particular purpose*.] 

The term was introduced in 2021 by [Stanford and the Stanford Center for Research on Foundation Models (CRFM)]( arXiv:2108.07258).

- A foundation model can be accessed by other companies (downstream in the supply chain) that can build AI applications ‘on top’ of a foundation model, using a local copy or an application programming interface (API). In this context, **‘downstream’** refers to activities post-launch of the foundation model that build on a foundation model.  Additionally, the foundation model provider will often allow downstream companies to create a customised version of the foundation model using a process called **‘fine-tuning’** – which describes when new data is added to a foundation model to ‘fine-tune’ its performance and capabilities on specific tasks.

- Because **foundation models** can be built ‘on top of’ to develop different applications for variouds purposes, this makes them difficult to regulate. When foundation models act as a base for a range of applications, any errors / issues at the foundation-model level may impact any applications built on top of (or ‘fine-tuned’) from that foundation model.
  
- Some foundation models are capable of taking inputs in **a single ‘modality**’ – such as text – while others are **‘multimodal’** and are capable taking multiple modalities of input at once, for example, text, image, video, etc., and then generating multiple types of output, (such as generating images, summarising text, answering questions) based on those inputs.

- A defining characteristic of foundation models is the **scale of data and computational resources** involved in building them.

*At present, “foundation model” is often used roughly synonymously with **“large language model**” because language models are currently the clearest example of systems with broad capabilities that can be adapted for specific purposes. “Large language models” specifically refers to **language-focused systems**, while “foundation model” is attempting to stake out a **broader function-based concept**, which could stretch to accommodate new types of systems in the future.

#### ℹ️ Large Language Models

**Large Language Models (LLMs)** are a specialized type of AI system using machine learning (NLP) and trained on text data that can generate humanlike text-based content in response to a wide range of inputs and prompts.

LLMs are the text-generating part of generative AI, specifically designed for handling language-related tasks. The **“large”** part of the term describes the trend towards training cutting-edge language models with hundreds of millions of parameters, which are pre-trained using billions of words of text and use a transformer neural network architecture (Transformers are neural networks that learn context and understanding through sequential data analysis).

- Not all generative AI tools are built on LLMs, but all LLMs are a form of genAI.
- Increasingly, LLMs are multimodal – that is, can use multiple inputs and generate multiple outputs. For example, while GPT-4 is primarily text-based and gives only text-based outputs, it can use both text and images simultaneously as an input. Similarly, Google’s PaLM , an embodied multimodal language model, is also capable of visual and robotics tasks

Typical examples of LLMs include:

- OpenAI’s **GPT-3 >>GPT-4** (Generative Pre-trained Transformer 3 -4)
- Google’s **PaLM 2** (Pre-trained AutoRegressive Language Model 2)
- Meta’s **LLaMA - 2** (Large Language Model Meta AI)
