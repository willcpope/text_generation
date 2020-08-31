# AI Text Generation
The goal of this project was to train artificial intelligence models to generate text.

## AI Model 1: The Works of H.P. Lovecraft
This model was trained using the works (502,786 words) of the American writer of weird fiction and horror fiction, H.P. Lovecraft. The prompt used to generate text is from his "Commonplace Book" - a listing of story ideas, concepts, and other elements which he might at some point include in his stories. The goal was to generate text that builds on entry 111 from 1923 -

> *"Ancient ruin in Alabama swamp—voodoo."*

## AI Model 2: Destiny Flavor Text
This model was trained using flavor text (44,491 words) from items in the video game, Destiny 2. The goal of this model was to generate interesting in-universe items.

## Technology
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

This project uses the Python package [aitextgen](https://docs.aitextgen.io) using OpenAI's GPT-2 architecture.

> aitextgen is a Python package that leverages PyTorch, Hugging Face Transformers and pytorch-lightning with specific optimizations for text generation using GPT-2, > plus many added features.

## Results
It's important to note that

Not all AI generated text will be good, hence why human curation is currently a necessary strategy for many finetuned models. In testing, only 5% — 10% of generated text is viable. One of the design goals of aitextgen is to help provide tools to improve that signal-to-noise ratio.

### H.P. Lovecraft Model

### Destiny Model


