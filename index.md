---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

---


# Welcome to Amphibioscope, your one-stop-shop for amphibian horoscopes
<br/>

## What's your sign? Find out [here](https://tarvinlab.github.io/amphibioscope/find-your-sign) 
<br/>


## About Amphibioscope  

Amphibioscope is a project of the [Tarvin Lab @ UC Berkeley](https://www.tarvinlab.org). Our group decided to spend 2020 summer lab meetings building a bot that somehow blended daily horoscopes with information about amphibians from [AmphibiaWeb](https://www.amphibiaweb.org). First, we looked through all amphibian families and grouped them into eight sets, each of which has some common characteristics. Then we assigned each group different constellations from the [International Astronomical Union](https://www.iau.org/public/themes/constellations/) based on how we imagined each group of amphibians could be represented symbolically. The symbols for each constellation were designed by Denis Moskowitz, who generously made his artwork available to the public domain ([here](https://www.suberic.net/~dmm/astro/constellations.html)). We wrote descriptions for each sign with the help of a professional astrologer and assigned them dates starting on Earth Day, which was April 22 in 2020. 

To produce daily horoscope text, first we attempted to simply replace some words in a horoscope with words from AmphibiaWeb, but phrases generated that way did not make much sense. We decided instead to use the [OpenAI Generative Pretrained Transformer 2](https://openai.com/blog/better-language-models/), which is a language model that can produce mostly intelligible text and can be trained to produce custom content. Using the [gpt-2-simple wrapper](https://github.com/minimaxir/gpt-2-simple), we trained the model on several datasets, one including a lot of horoscopes and eight including species accounts from AmphibiaWeb containing amphibian life history information from each group of amphibians. The daily horoscope for each sign contains some text from the horoscope model and some text from the model trained on the specific group of amphibians corresponding to each sign, prompted with the randomly selected Amphibian Spiritual Guide of that day. Hence, **we note that the amphibian information included in daily horoscopes is written by a computer program and meant to look real -- but it is not**. 

Version 1 of amphibioscope was launched on xx August 2020. The contributors include, in alphabetical order: Tyler Douglas, Kate Montana, María José Navarette, Kannon Pearson, Valeria Ramírez-Castañeda, Rebecca Tarvin, Connor Tumelty, and Lawrence Uricchio.
<br/><br/><br/>

### If you have comments, questions, or concerns about amphibioscope, please contact Rebecca Tarvin at rdtarvin [at] gmail . com
