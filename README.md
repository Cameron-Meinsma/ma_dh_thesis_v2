# MA Digital Humanities Thesis Version 2

**Cameron Meinsma (S6494935) | MA Digital Humanities Thesis V2 | 2025 - 2026**

## 1. The Research

The main research question is as follows: **'Are there differences in content between homosexual and heterosexual fan fiction published on Archive of Our Own as reflected through tags?'**

The sub-research questions are as follows:

1. _'Are there differences in content between the F/F and M/M fan fiction categories on Archive of Our Own?'_
2. _'To what extent does the media type of the source material influence the content of the fan fictions on Archive of Our Own?'_
3. _'Are there differences in content between homosexual and heterosexual fan fiction on Archive of Our Own, regarding variables such as the language, date published, or word count?'_

Included fandoms:

- DC's Legends of Tomorrow (TV)
  - Originally aired between January 21, 2016 and March 2, 2022.
  - 110 episodes.
  - 7 seasons.
  - 42 - 45 minutes per episode.
- Avatar: The Last Airbender (Cartoon 2005)
  - Originally aired between February 21, 2005 and July 19, 2008.
  - 61 episodes.
  - 3 seasons.
  - 23 minutes per episode.
- Spider-Man: Spider-Verse (Sony Animated Movies)
  - Spider-Man: Into the Spider-Verse:
    - Originally released on December 1, 2018
    - 117 minutes.
  - Spider-Man: Across the Spider-Verse:
    - Originally released on May 30, 2023
    - 140 minutes.

Included categories:

- F/F (Femslash): Female/Female romantic and/or sexual relationships
- M/M (Slash): Male/Male romantic and/or sexual relationships
- F/M (Het): Female/Male romantic and/or sexual relationships

## 2. The Notebooks

### 2.1 additional_tags.ipynb

This notebook has been used to calculate the amount of additional tags per fandom and relationship category. It furthermore, has been used to calculate descriptive statistics.

The _combined_metadata.jsonl_ dataset is available on the Hugging Face webpage of Trent M. Kelly: https://huggingface.co/datasets/trentmkelly/archiveofourown-meta.

### 2.2 scikit_classifiers.ipynb

In this notebook, I have tested the Scikit-Learn classification models using 5-fold cross validation. I ended up not using any of the nine classifiers tested in this notebook.

### 2.3 bert_base_uncased.ipynb

In this notebook, I have tested the BERT-base uncased model using 5-fold cross validation. I ended up using this classifier for all the automated classification tasks.

### 2.4 main_rq.ipynb

This notebook contains the tables and visualizations for the main research question.

### 2.5 sub_rq_1.ipynb

This notebook contains the tables and visualizations for sub-research question 1.

### 2.6 sub_rq_2.ipynb

This notebook contains the tables and visualizations for sub-research question 2.

### 2.7 sub_rq_3_language.ipynb

This notebook contains the tables and visualizations for the language portion of sub-research question 3.

### 2.8 sub_rq_3_date_published.ipynb

This notebook contains the tables and visualizations for the date published portion of sub-research question 3. While it says date published, for most of the analysis, this means specifically the year instead of the actual date.

### 2.9 sub_rq_3_word_count.ipynb

This notebook contains the tables and viualizations for the word count portion of sub_research question 3.
