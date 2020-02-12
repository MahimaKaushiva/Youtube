**Analysing the impact of words to drive engagement on Youtube**



*Overview*


Content creators on Youtube face a two-fold challenge when it comes to building a dedicated audience. 

- How to use the right keywords to describe their content. This involves finding the most relevant words that would attract the right audience and keep them engaged. 

- How to choose the right category to upload their videos. Correct classification is important to appear in search by the relevant audience and avoid missed opportunities for views.


*Method*

This project aims to use **Natual Language Processing** and **Recurrent Neural Networks** to address the above challenges.

We use the Kaggle Dataset (https://www.kaggle.com/datasnaek/youtube-new) focusing on 120,000 top-trending videos in three countries - USA, Canada and Great Britain, between 2017 and 2018.

- To understand the role of text optimisation, we use a topic modeling technique called **Latent Dirichlet Allocation (LDA)** to create lists of words that occur in statistically meaningful ways, for each category, based on words used to describe the title of each video.
LDA creates clusters of the most salient words and how they occur together, for each topic. 

- To predict which category a video belongs to, we use a recurrent neural network called **LSTM** where videos are classified based on their titles.  



*Findings*

![](https://github.com/MahimaKaushiva/Youtube/blob/main/Images/Screen%20Shot%202020-02-12%20at%2017.15.21.png)
![](https://github.com/MahimaKaushiva/Youtube/blob/main/Images/Screen%20Shot%202020-02-12%20at%2017.15.32.png)
![](https://github.com/MahimaKaushiva/Youtube/blob/main/Images/Screen%20Shot%202020-02-12%20at%2017.15.41.png)
![](https://github.com/MahimaKaushiva/Youtube/blob/main/Images/Screen%20Shot%202020-02-12%20at%2017.15.57.png)



*Reference documents*

Master jupyternotebooks 

- Analysis.ipynb
- Analysis-2.ipynb
- Topic Modelling using LDA.ipynb


Presentation 

- Youtube.pdf
