# Lyrics Generation using Language Models
 
![last commit](https://img.shields.io/github/last-commit/meraxes-99/Lyrics_Generation)
![repo size](https://img.shields.io/github/repo-size/meraxes-99/Lyrics_Generation)

<br>

Creativity might be the ultimate measure of Artificial Intelligence and one such creative field is Song Writing. 
In this project, our objective is to explore the capability of Language models to generate lyrics for songs.

#

The aim of this project is to:

1. Scrape and collect the lyrics of Billboard Hot-100 songs from 1960−2021 and select the songs belonging to **Pop, Rock and Rap**. Similarly, scrape and collect lyrics of songs of 5 artists from those 3 selected genres.
2. Perform Exploratory Data Analysis by plotting word clouds, exploring most frequent words, average line length, vocabulary richness, etc for each of the 3 selected genres.
3. Create different language models using **Vanilla LSTMs, RoBERTa and GPT-2** and train the language models on the lyrics for the 3 selected genres separately.
4. Select the best performing model for each of the genres based on the performance metrics and fine-tune the models on the lyrics of the selected artists. We finally have 15 models (3 genres x 5 artists) using which we can generate lyrics like each of those artists.

#

This repository contains,

1. A data folder which contains a main `Billboard Hot-100 dataset` using which mini datasets for the `Pop, Rock and Rap datasets` are created. This data folder contains subfolders for artists of each genre. Each of these subfolders contain lyrics of selected 5 artists from the 3 genres.
2. `Lyrics Generation using Language Models` jupyter notebook.

#

References:
1. [Deep Learning in Musical Lyric Generation: An LSTM-Based Approach (Gill et al., 2020)](https://elischolar.library.yale.edu/yurj/vol1/iss1/1/)
2. [GhostWriter: Using an LSTM for Automatic Rap Lyric Generation (Potash et al., 2015)](https://aclanthology.org/D15-1221.pdf)
3. [A melody-conditioned lyrics language model (Watanabe et al., 2018)](https://aclanthology.org/N18-1015.pdf)
