# AI-engineer

[Reference](https://roadmap.sh/ai-engineer)

## Introduction

### AI Engineering

**AI Engineering** is the process of designing and implementing AI systems using pre-trained models and existing AI tools to solve practical problems. They work to ensure AI systems are efficient, scalable, distinguishing their role from AI Researchers and ML Engineers, who concentrate more on creating new models or advancing AI theory.

**References**

- [AI Engineering](https://en.wikipedia.org/wiki/Artificial_intelligence_engineering)
- [AI vs ML](https://www.youtube.com/watch?v=4RixMPF4xis)

### AI Engineer vs ML Engineer

**References**

- [What does an AI Engineer do](https://www.codecademy.com/resources/blog/what-does-an-ai-engineer-do/)

## Common Terminology

### AGI vs AI

### Inference

- In AI, inference refers to the process where a trained ML model makes predictions or draws conclusions from new, unseen data.
- Unlike training, inference involves the model applying what it has learned to make decisions without needing examples of the exact result.
- In essence, inference is the AI model actively functioning. For example, a self-driving car recognizing a stop sign on a road it has never encountered before demonstrates inference.
- The model identifies the stop sign in a new setting, using its learned knowledge to make a decision in real-time.

**References**

- [Inference vs Training](https://www.cloudflare.com/learning/ai/inference-vs-training/)
- [ML Inference](https://hazelcast.com/glossary/machine-learning-inference/)
- [An Intro to Inference Approaches](https://www.datacamp.com/blog/what-is-machine-learning-inference)

### Training

**References**

- [What is Model Training](https://oden.io/glossary/model-training/)
- [ML Model Training : What is it and why is it important](https://domino.ai/blog/what-is-machine-learning-model-training)
- [Training ML Models](https://docs.aws.amazon.com/machine-learning/latest/dg/training-ml-models.html)

### Embeddings

**References**

- Embeddings are dense, continuous vector representations of data, such as words, sentences, or images, in a lower-dimensional space.
- They capture the semantic relationships and patterns in the data, where similar items are placed closer together in the vector space.
- In machine learning, embeddings are used to convert complex data into numerical form that models can process more easily.
- For example, word embeddings represent words based on their meanings and contexts, allowing models to understand relationships like synonyms or analogies.

- [Embeddings](https://www.cloudflare.com/en-gb/learning/ai/what-are-embeddings/)
- [Word Embeddings](https://www.youtube.com/watch?v=wgfSDrqYMJ4)

### Vector Databases

- Vector databases are specialized systems designed to store, index, and retrieve high-dimensional vectors, often used as embeddings that represent data like text, images, or audio.
- Vector databases excel at managing unstructured data by enabling fast similarity searches, where vectors are compared to find those that are most similar to a query.
- This makes them essential for tasks like semantic search, recommendation systems, and content discovery, where understanding relationships between items is crucial.
- Vector databases use indexing techniques such as approximate nearest neighbor (ANN) search to efficiently handle large datasets, ensuring quick and accurate retrieval even at scale.

### AI Agents

- In AI engineering, "agents" refer to autonomous systems or components that can perceive their environment, make decisions, and take actions to achieve specific goals.
- Agents often interact with external systems, users, or other agents to carry out complex tasks.
- They can vary in complexity, from simple rule-based bots to sophisticated AI-powered agents that leverage machine learning models, natural language processing, and reinforcement learning.

- [Building an AI Agent](https://python.langchain.com/docs/tutorials/agents/)
- [AI Agents & their types](https://play.ht/blog/ai-agents-use-cases/)
- [Beginners guide to building AI Agents](https://youtu.be/MOyl58VF2ak?si=-QjRD_5y3iViprJX)

### RAG (Retrieval Augmented Generation)

- Retrieval-Augmented Generation (RAG) is an AI approach that combines information retrieval with language generation to create more accurate, contextually relevant outputs.
- It works by first retrieving relevant data from a knowledge base or external source, then using a language model to generate a response based on that information.
- This method enhances the accuracy of generative models by grounding their outputs in real-world data, making RAG ideal for tasks like question answering, summarization, and chatbots that require reliable, up-to-date information.

### Prompt Engineering

- Prompt engineering is the process of crafting effective inputs (prompts) to guide AI models, like GPT, to generate desired outputs.
- It involves strategically designing prompts to optimize the model’s performance by providing clear instructions, context, and examples.
- Effective prompt engineering can improve the quality, relevance, and accuracy of responses, making it essential for applications like chatbots, content generation, and automated support.
- By refining prompts, developers can better control the model’s behavior, reduce ambiguity, and achieve more consistent results, enhancing the overall effectiveness of AI-driven systems.

- [Prompt Engineer Roadmap](https://roadmap.sh/prompt-engineering)
- [What is Prompt Engineering](https://www.youtube.com/watch?v=nf1e-55KKbg)

## Pre-trained Models

### Benefits of Pre-trained Models

## AI Safety and Ethics

### Prompt Injection Attacks

- Prompt injection attacks are a type of security vulnerability where malicious inputs are crafted to manipulate or exploit AI models, like language models, to produce unintended or harmful outputs.
- These attacks involve injecting deceptive or adversarial content into the prompt to bypass filters, extract confidential information, or make the model respond in ways it shouldn't.
- For instance, a prompt injection could trick a model into revealing sensitive data or generating inappropriate responses by altering its expected behavior.

- [Prompt Injection in LLMs](https://www.promptingguide.ai/prompts/adversarial-prompting/prompt-injection)
- [What is a Prompt Injection Attack](https://www.wiz.io/academy/prompt-injection-attack)

## Resources

- [ML Intro Course](https://mlcourse.ai/book/topic01/topic01_intro.html)
- [Practical Deep Learning](https://course.fast.ai/)
- [LLM Course by HuggingFace](https://huggingface.co/learn/llm-course/chapter0/1?fw=pt)
- [HuggingFace Learn](https://huggingface.co/learn)

**Huggingface** : Repository of Open Source ML Models
