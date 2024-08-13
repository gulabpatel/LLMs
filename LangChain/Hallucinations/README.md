## Hallucinations
1. Hallucinations in AI refer to the generation of outputs that may sound plausible but are either factually incorrect or unrelated to the given context.
2. These outputs often emerge from the AI models's inherent biases, lack of real-world understanding, or training data limitations.
3. In other words, the AI system "hallucinates" information that it has not been explicitly trained on, leading to unreliable or misleading responses.


## Llama-3-Patronus-Lynx Hallucination models
One of the limitations of RAG systems is hallucinations, which is basically the model confidently making up totally wrong answers. What if I told you there was an open source LLM which was released just this month itself to specifically detect hallucinations in RAG responses?

Check out this illustration which showcases how to use this LLM released by Patronus AI, they call it Lynx, lets check out its details:

- Lynx is an open-source hallucination evaluation model
- It has both 8B and 70B variants
- It was fine-tuned on a mix of datasets including CovidQA, PubmedQA, DROP, RAGTruth
- It is a fine-tuned variant of the Llama 3 model from Meta

The model claims to outperform GPT-3.5-Turbo, GPT-4-Turbo, GPT-4o and Claude Sonnet for this task. Model details below.
![](https://github.com/gulabpatel/LLMs/blob/main/LangChain/Hallucinations/Llam_Lynx_hallucinations.PNG)
