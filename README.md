# A Practical Introduction to LLMs:

## What is an LLM?
LLM stands for Large Language Model, a recent AI innovation popularized by ChatGPT in December 2022. Unlike traditional chatbots, LLMs exhibit unique emergent properties like zero-shot learning due to their large number of parameters. These models can perform tasks without specific training, setting them apart from previous AI paradigms.

## What Makes an LLM “Large”?
LLMs have 10–100 billion parameters, leading to emergent properties like zero-shot learning, enabling them to perform tasks without explicit training. This makes them significantly different from smaller language models, as they display advanced capabilities when they reach a certain size.

## How Do LLMs Work?
LLMs are trained using word prediction. When models reach around 10 billion parameters, they exhibit emergent abilities like zero-shot learning, making them versatile and powerful. This training method is similar to smaller models, but the scale of LLMs enables advanced features and capabilities.

## 3 Levels of Using LLMs

### Level 1: Prompt Engineering
Prompt engineering involves using LLMs out-of-the-box, either through user-friendly UIs like ChatGPT or directly via APIs for more customization. This method is accessible and economical but may lack advanced functionalities and scalability required for larger applications.

### Level 2: Model Fine-Tuning
Fine-tuning tweaks an existing LLM's parameters for specific tasks using high-quality labeled data, requiring more expertise and resources than prompt engineering. This approach allows for better optimization for particular use cases, providing improved performance over generic models.

### Level 3: Build Your Own LLM
Building an LLM from scratch involves creating custom training data and model parameters, demanding significant computational resources and expertise. This method offers ultimate flexibility and customization for specific applications but requires extensive time, budget, and technical skills.


# API Overview

##  What’s an API?
An API (Application Programming Interface) allows interaction with a remote application programmatically, akin to texting a friend for recommendations. APIs use programming languages like Python or JavaScript to automate information retrieval from external sources, essential for software development requiring external data.

##  OpenAI’s (Python) API
OpenAI’s API enables interaction with Large Language Models (LLMs) like ChatGPT via Python, providing access to powerful ML models without provisioning computational resources. It supports customizable system messages, input parameters, file inclusion, word embeddings, audio transcription, and model fine-tuning.

##  Getting Started (4 Steps)
To use OpenAI's API, follow these steps:

**1. Make an Account**-Sign up on the OpenAI API Overview page for a $5 API credit for the first three months. Existing ChatGPT users can log in.

**2. Add Payment Method**-If the free credit expires, add a payment method under the "Billing" tab in your profile.

**3. Set Usage Limits**-Set soft and hard usage limits under the "Billing" tab to control your spending.

**4. Get API Secret Key**-Generate a secret key under "View API keys" to authenticate your API calls.

##  Example Code: Chat Completion API
Learn to use OpenAI's Python library for chat completion, adjusting parameters like max tokens, number of responses, and temperature to optimize model outputs. This involves setting up system messages and utilizing user and assistant roles for context-specific responses.

