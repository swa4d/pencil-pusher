# Pencil Pushers - AI SHORT STORY GENERATOR

### Description Of Product

Our team built multiple models based off of specific genres including: 

- Sci-Fi
- Fantasy
- Fairy Tale
- Horror
- Humor

These models are all different, but all of them are designed to create short stories for readers and authors alike! 

### Some Basic Features
- 10 different datasets, based on different authors ranging from H.P. Lovecraft to Dr. Seuss himself!
- 5 different genres to generate short stories with (listed above)
- A drop down menu with each model
- A simplistic design, and a user friendly interface.

### Techstack
Our team had built both our product and our website using the following: 
- Python
- CSS + HTML
- GPT-2
- Datasets found on Google and Kaggle

### Links to Datasets 

Fantasy Datasets: 
- [Short Stories from Project Guttenberg](https://www.kaggle.com/datasets/shubchat/1002-short-stories-from-project-guttenberg)
- [Russian Short Stories](https://www.kaggle.com/datasets/dmisky/best-russian-short-stories)
- [Wikipedia Movie Plots](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots)

Fairy Tale Datasets: 
- [Grimms Fairy Tales](https://www.kaggle.com/datasets/tschomacker/grimms-fairy-tales)

Sci-Fi Datasets: 
- [Sci-Fi Stories Text Corpus](https://www.kaggle.com/datasets/jannesklaas/scifi-stories-text-corpus)
- [Edgar Allen Poe's Corpus of Short Stories](https://www.kaggle.com/datasets/leangab/poe-short-stories-corpuscsv)

Humor Datasets:
- [Dr. Seuss](https://github.com/robertsdionne/rwet/blob/master/hw2/drseuss.txt)

Horror Datasets:
- [3500 Creepypastas](https://www.kaggle.com/datasets/thomaskonstantin/3500-popular-creepypastas)
- [H.P. Lovecraft Collection](https://www.kaggle.com/datasets/bennijesus/lovecraft-fiction)


### File Structure

The files/directories which you will need to edit are **bolded**, and the files you **may** need to edit are *italicized*.

**DO NOT TOUCH OTHER FILES. THIS MAY RESULT IN YOUR PROJECT BEING UNABLE TO RUN**

- .gitignore
- config.py
- Dockerfile
- READMD.md
- entrypoint.sh
- nginx_host
- host_config
- app/
     - **main.py**
     - *requirements.txt*
     - **utils.py**
     - templates/
          - **writer_home.html**
          - **Write-your-story-with-AI.html**
     - static/
          - **img/** 
          - **js/**
          - **css/**
          - favicon.ico  
     - model/
          - **TODO.txt** <- delete this file after following the directions. Important to note that you will only need an aitextgen.tokenizer.json file if you are custom training your own tokenizer and model.


### Files used for deployment ###

`config.py`
`Dockerfile`
`entrypoint.sh`
`nginx_host`
`host_config`
**Only modify `host_config`. Do not touch the other files.**

