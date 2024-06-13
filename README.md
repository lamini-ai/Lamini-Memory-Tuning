<div align="center">
<img src="https://avatars.githubusercontent.com/u/130713213?s=200&v=4" width="110"><img src="https://huggingface.co/lamini/instruct-peft-tuned-12b/resolve/main/Lamini_logo.png?max-height=110" height="110">
</div>
<div align="center">
  
# Banishing LLM Hallucinations Requires Rethinking Generalization
## Johnny Li, Saksham Consul, Eda Zhou, James Wong, Naila Farooqui, Nithyashree Manohar, Zhuxiaona (Nina) Wei, Tian Wu, Ben Echols, Sharon Zhou, and Gregory Diamos
Despite their powerful chat, coding, and reasoning abilities, Large Language Models (LLMs) frequently hallucinate. Conventional wisdom suggests that hallucinations are a consequence of a balance between creativity and factuality, which can be mitigated, but not eliminated, by grounding the LLM in external knowledge sources. Through extensive systematic experiments, we show that these traditional approaches fail to explain why LLMs hallucinate in practice. Specifically, we show that LLMs augmented with a mixture of Millions of Memory Experts (MoME) can easily memorize large datasets of random numbers. We corroborate these experimental findings with a theoretical construction showing that simple neural networks trained to predict the next token hallucinate when the training loss is above a threshold as it usually does in practice when training on internet scale data. We interpret our findings by comparing against traditional retrieval methods for mitigating hallucinations. We use our findings to design a first generation model for removing hallucinations - Lamini-1 - that stores facts in a massive mixture of millions of memory experts that are retrieved dynamically.

### info@lamini.ai
</div>
