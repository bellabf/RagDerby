# Multilingual Roller Derby QA System using Aya Expanse

#### Competition Status
🏆 Finalist in Cohere's Competition - Demonstrating Aya Expanse's multilingual capabilities


## Motivation

Remember when language barriers didn't matter in understanding each other? A smile, a gesture, and suddenly we're all on the same page. But when it comes to technical documentation, rulebooks, and specialized knowledge, these natural bridges often fall short. We all hope information will flow freely. Yet, for many specialized domains, language remains a significant barrier to access and understanding. What if we could recreate that natural, intuitive understanding across languages using AI? 

In this repo, we are using AI to reduce in the **language barriers** in sports using **roller derby** as study case.

### Filling in the Gaps with AI
This is where Aya Expanse comes in. Instead of just translating words, we're translating understanding. Our system doesn't just bridge languages – it bridges comprehension, making technical information accessible regardless of the language barrier.

## More About Aya Expanse

Aya Expanse is Cohere For AI's latest breakthrough in multilingual language model. If you want to know more about it, please check out these resources:

* [Official Announcement on X](https://x.com/CohereForAI/status/1849435983449587796)
* [LinkedIn Announcement](https://www.linkedin.com/posts/cohere-for-ai_today-we-introduce-aya-expanse-an-open-weights-activity-7255201464317366274-YRbC)
* [Hugging Face Blog Post](https://huggingface.co/blog/aya-expanse)
* [Cohere Blog: Aya Expanse - Connecting Our World](https://cohere.com/blog/aya-expanse-connecting-our-world)

## Project Overview
This project demonstrates the capabilities of Cohere's Aya Expanse model in building a multilingual question-answering system focused on Roller Derby rules and gameplay. Selected as a finalist in Cohere's competition, this implementation showcases the model's ability to handle queries across multiple languages while maintaining context and accuracy.

## Key Features
- Language Detection: Automatically identifies the input language
- Cross-lingual Translation: Translates queries to English and responses back to the original language
- RAG Implementation: Uses FAISS for efficient document retrieval
- Contextual Compression: Employs Cohere's reranking for improved response relevance
- Few-shot Learning: Implements example-based prompting for better translations

## Technical Components
- Custom Cohere LLM Wrapper
- FAISS-based Vector Search
- Contextual Compression Retriever
- Multi-stage Pipeline Architecture:
  1. Language Detection
  2. Query Translation
  3. RAG-based Answer Generation
  4. Response Translation

## Getting Started
1. Set up environment variables (COHERE_API_KEY)
2. Install required dependencies
3. Load your document base
4. Run queries through the multilingual pipeline

## Example Usage
```python
query = "Como é a pista de roller derby?"
process_derby_query(query)
```
