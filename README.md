# AI Text Generation
The goal of this project was to train an artificial intelligence model to generate text.

## AI Model: The Works of H.P. Lovecraft
This model was trained using the works of the American writer of weird fiction and horror fiction, H.P. Lovecraft. The training corpus consisted of 502,786 words. The prompt used to generate new text is from his "Commonplace Book" - a listing of story ideas, concepts, and other elements which he might at some point include in his stories. The goal was to generate text that builds on entry 111 from 1923 -

> *"Ancient ruin in Alabama swamp—voodoo."*

## Technology
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

This project uses the Python package [aitextgen](https://docs.aitextgen.io) using OpenAI's GPT-2 architecture.

> aitextgen is a Python package that leverages PyTorch, Hugging Face Transformers and pytorch-lightning with specific optimizations for text generation using GPT-2, plus many added features.

## Results
While both models produced some interesting content, it required curation to find usable results. Per the aitextgen website -

> Not all AI generated text will be good, hence why human curation is currently a necessary strategy for many finetuned models. In testing, only 5% — 10% of generated text is viable. One of the design goals of aitextgen is to help provide tools to improve that signal-to-noise ratio.
