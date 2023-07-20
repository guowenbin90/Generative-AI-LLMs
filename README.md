# Generative-AI-LLMs
- Zero-shot
- One-shot
- Few-shot

1. Autoencoding: masked language modeling (MLM), encoder-only
   - Sentiment analysis
   - Named entity recognition
   - Word classification
2. Autoregressive: causal language modeling (CLM), decoder-only
   - Text generation
   - Other emergent behavior
3. Seq-to-Seq: Span corruption, encoder-decoder
   - Translation
   - Text summarization
   - Question answering

1B parameters = 80GB @ 32-bit full precision, 80GB is the maximum memory for the Nvidia A100 GPU

## Fine-tuning LLMs
Scaling Instruction-Finetuned Language Models  

Model evaluation:
1. Rouge: text summarization; unigram, bigram, longest common subsequence(LCS)  
2. Bleu Score: text translation; n-gram
