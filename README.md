# Fine tuning a T5 Transformer for Text Summarization  #

For this project, I fine-tuned the T5 transformer for use in a NLP summarization app. 
You can find the model implemented using Gradio on HuggingFace Spaces: SamuelMiller/sum_it


## Goal: ##

The goal is to fine tune the T5 transformer for the task of summarizing text. 


## Data: ##

Find dataset [HERE](https://huggingface.co/datasets/samsum).

Sample of Data:
![Sample of Data:](https://user-images.githubusercontent.com/90416677/173693401-795e151f-a10a-4194-bb7d-976b6f36423f.png)


The SAMSum dataset contains about 16k messenger-like conversations with summaries. Conversations were created and written down by linguists fluent in English. Linguists were asked to create conversations similar to those they write on a daily basis, reflecting the proportion of topics of their real-life messenger convesations. The style and register are diversified - conversations could be informal, semi-formal or formal, they may contain slang words, emoticons and typos. Then, the conversations were annotated with summaries. It was assumed that summaries should be a concise brief of what people talked about in the conversation in third person. The SAMSum dataset was prepared by Samsung R&D Institute Poland and is distributed for research purposes (non-commercial licence: CC BY-NC-ND 4.0).


## Results: ##

In terms of the metrics, it could have done much better. I'll still be tweaking some stuff but some things I've noticed initially:

  - There are grammar issues. Code will be needed to smooth this out.
  - It shows a propensity for generating very small summaries where it could often benefit with a longer output. This will be my first area for     improvement as I go forward with this model.
  - The generated text could work well to extract keywords, as it already produces shorter, keyword-like summaries. Currently they're absurd and funny. Functional may be better.
