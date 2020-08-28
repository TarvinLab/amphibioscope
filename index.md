---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

---

![header](constellations/Header.png)
# Welcome to Amphibioscope, your one-stop-shop for amphibian horoscopes
<br/>

## What's your sign? Find out [here](https://tarvinlab.github.io/amphibioscope/find-your-sign) 
<br/>


## About Amphibioscope  

Amphibioscope is a daily horoscope bot that infuses AI-generated amphibian life-history data based on AmphibiaWeb species accounts with AI-generated horoscopes for science communication and entertainment purposes. **We note that the amphibian information and horoscopes included in amphibioscope is written by a computer program and meant to look real – but it is not**.

Amphibioscope is a project of the [Tarvin Lab @ UC Berkeley](https://www.tarvinlab.org). Our group decided to spend our summer 2020 lab meetings building a bot that blended daily horoscopes with information about amphibians from [AmphibiaWeb](https://www.amphibiaweb.org). First, we looked through all amphibian families and grouped them into eight sets based on common characteristics. Then, we assigned each group different constellations from the [International Astronomical Union](https://www.iau.org/public/themes/constellations/) based on how we imagined each group of amphibians could be represented symbolically. The symbols for each constellation were designed by Denis Moskowitz, who generously made them available to the public domain ([here](https://www.suberic.net/~dmm/astro/constellations.html)). The amphibian illustrations for each sign were drawn in ink by Kannon Pearson and digitized by Connor Tumelty. We wrote descriptions for each sign and assigned them dates starting on Earth Day, April 22 (in 2020).

To produce daily horoscope text, first we attempted to replace some words in a horoscope with words from AmphibiaWeb, but phrases generated that way did not make much sense. We decided instead to use the [OpenAI Generative Pretrained Transformer 2](https://openai.com/blog/better-language-models/), which is a language model that can produce mostly intelligible text and can be trained to produce custom content. Using the [gpt-2-simple wrapper](https://github.com/minimaxir/gpt-2-simple), we trained one model on many pre-written horoscopes. Then we created eight additional models based on subsets of species accounts from [AmphibiaWeb](https://www.amphibiaweb.org) corresponding to each of the eight groups of amphibians. The resulting daily horoscope for each sign contains some text from the horoscope model and some text from the species accounts model for each sign, voiced by the Amphibian Spiritual Guide for that sign that day. Amphibian Spiritual Guides are chosen randomly for each sign every day from a list of species included in each of the eight amphibian groups.  Moreover, we selected a list of “celebrities” composed of outstanding scientists and science-related celebrities that were born under each sign. Finally, our team proofreads every daily horoscope to be certain that the AI-generated text is appropriate for all ages.  

Version 1 of Amphibioscope was launched on 31 August 2020. The contributors include, in alphabetical order: Tyler Douglas, Kate Montana, María José Navarette, Kannon Pearson, Valeria Ramírez-Castañeda, Rebecca Tarvin, Connor Tumelty, and Lawrence Uricchio.
<br/><br/><br/>

### If you have comments, questions, or concerns about amphibioscope, please contact Rebecca Tarvin at rdtarvin [at] gmail . com
