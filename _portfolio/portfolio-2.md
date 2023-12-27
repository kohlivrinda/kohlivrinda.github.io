---
title: "Shakespeare-GPT"
excerpt: "A barebones generative transformer trained from scratch for text generation. Generated text takes the form of Shakespearean style writing"
collection: portfolio
---
<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
This project is a barebones generative transformer model trained for a few epochs on the tiny shakespeare dataset. All the components (including but not limited to the tokenizer, attention module and overall architecture) have been coded from scratch using Python and Pytorch. 

There are a bunch of things pertaining to this project that I would like to experiment with in future.
- Currently the model works on word-level, thus the sentences generated may appear nonsensical. The next thing for me is to explore more advanced tokenization methods.
- Try out SentencePiece

### Sample output:

![Image of sample output](/images/shakespeare.png  "shakespeare-gpt-output")

### Link: 
[Github](https://github.com/kohlivrinda/shakespeare-gpt)