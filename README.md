# Build LLMs


## Stage 1 - Fine tune QWEN 2.5 on hindi Q/A data. 
- [Here is perplexity's pathway for going about this](https://www.perplexity.ai/search/i-have-a-dataset-of-question-a-.KEF.xg1RBalbdmizMWJVQ)
    - [x] Install hugging face transformers library
    - [ ] Use Hugging Face Trainer API to fine tune
        - OOM error on local training
        - [ ] Spin up GPU instances in jarvis and fine tune
    - [x] How to tokenize hindi ?
        - Using QWEN tokenizer for now, can checkout other tokenizers later
- No code approaches
    - [ ] https://huggingface.co/docs/autotrain/en/llm_finetuning
    - [ ] https://github.com/hiyouga/LLaMA-Factory


## Resources
- [Hindi BERT from 2020](https://mapmeld.medium.com/teaching-hindi-to-electra-b11084baab81)
    - Data - HIndMonoCorp, Oscar, Hindi CommonCrawl
    - Tokenizer -  (anoopkunchukuttan.github.io/indic_nlp_library/)
    - Model - Google electrca
    - Hindi IMDB reviews - https://github.com/sid573/Hindi_Sentiment_Analysis
- [Airvata](https://ai4bharat.github.io/airavata/)
    - https://arxiv.org/pdf/2401.15006