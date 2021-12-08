---
title: "Word Clouds: All PC down here.. (maybe?)"
date: 2021-12-08T18:30:01+01:00
draft: false
description:
    "This is the home page to reveal the most awesome Wordclouds generated from the characters of South Park!"
---
Purpose:
---
This is the home page to reveal the most awesome Wordclouds generated from the characters of South Park!

We have generated wordclouds for a few categories.


Note: this section is rather meant to be engaging and **informal**. For a more formal in-depth analysis and the source code, one can check the notebook provided in
this [GitHub repository](https://github.com/TeoAndB/SouthPark_NetworkAnalysis) - Part_B_Data_Analysis (Section:
Networks and Visualization)


Wordclouds - Really good insight from just a cloud of words
---

By analysing the SP characters and attributes, we came up to the conclusion to generate insights from generating a few wordclouds for different categories

These include:
  - WordClouds for each gender category
  - Wordclouds for the top five generated communities
  - Wordcloud for the main male and female character respectively

#### So, are you excited to see the magic Wordclouds? Hmm, you are silent, then I will take it as a Yes.

Let's dive in. 

In order to reach from plain text from a website there is a very long and cumbersome process that is described more in depth in the explainer notebook.
However, I will quickly pass you through the steps. 
<ol>
  <li>We need to start with indepth web scraping in order to obtain characters data in a good format.</li>
  <li>Cleaning/refining the text for further processing
   <ul>
      <li>Applying regex functions</li>
      <li>Manual data cleaning</li>
     <li>Saving to text files</li>
    <li>Applying NLP tools like removing stopwords, lower-casing, lemmetization</li>
    </ul>
    </li>
  <li></li>
  <li>Applying TF-IDF Vectorization on the freshly cleaned text</li>
</ol>

### Genders 

We have identified three categories:
 - Male
 - Female
 - Unknown

Let us take a look at the resulting word clouds. 

![Word Cloud for each gender](/wordcloud_img/wordcloud_gender.png)