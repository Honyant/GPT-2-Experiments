# GPT-2 Experiments
In 2021, I became really interested in GPT-2, so I tried a few experiments based off of the notebook, "Train a GPT-2 Text-Generating Model w/ GPU For Free" by [Max Woolf](http://minimaxir.com)

## GPT-2 for music generation
I didn't know it at the time, but using transformers for music generation had already been done many times, but I was interested, so I converted from midi to text and trained it on GPT-2 to see what I could get. The results weren't very good, but it was a good learning experience, especially for data processing.

## Train GPT-2 For a Discord Chatbot
As GPT-2 is an autoregressive lanugage model, which means it predicts the next word in a sequence based on previous words, I decided to include it as a feature for a discord bot I am working on with @neilsong, which can be found here: ![Word Counter Bot repo](https://github.com/neilsong/word-counter-bot)
