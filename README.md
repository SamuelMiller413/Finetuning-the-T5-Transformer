# Fine tuning a T5 Transformer for Text Summarization  #

For this project, I fine-tuned the T5 transformer for use in a NLP summarization app. 
You can find the model implemented using Gradio on HuggingFace Spaces: SamuelMiller/sum_it


## Goal: ##

The goal is to fine tune the T5 transformer for the task of summarizing text. 


## Data: ##

Find dataset [HERE](https://huggingface.co/datasets/samsum).

    SAMPLE
    
   ![](/../main/assets/data_sample)

The SAMSum dataset contains about 16k messenger-like conversations with summaries. Conversations were created and written down by linguists fluent in English. Linguists were asked to create conversations similar to those they write on a daily basis, reflecting the proportion of topics of their real-life messenger convesations. The style and register are diversified - conversations could be informal, semi-formal or formal, they may contain slang words, emoticons and typos. Then, the conversations were annotated with summaries. It was assumed that summaries should be a concise brief of what people talked about in the conversation in third person. The SAMSum dataset was prepared by Samsung R&D Institute Poland and is distributed for research purposes (non-commercial licence: CC BY-NC-ND 4.0).


Results:


