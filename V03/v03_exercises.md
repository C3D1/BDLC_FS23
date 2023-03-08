# Exercises

If not done already, complete the following guides.

From last week:

- [V02 Exercise](../0V2/v02_exercises.md)

Guides this week:

- [Installing JupyterLab](../V03/install_jupyterlab.md)
- [Preparing Dataset](./preparing_dataset.md)
- [Setup JupyterLab](./jupyter_lab.md)
- [Tuning your Cluster](./tuning_yarn.md)
- [Installing MrJob](./install_mrjob.md)

## MRJob

For the rest of this exercise, we will use `MrJob`. To get a feeling how `MrJob` works open the [./v03_exercises_material/1_MRJob/MrJob.ipynb](./v03_exercises_material/1_MRJob/MrJob.ipynb) in your `JupyterLab` environment.

## Word Count

We will have three sub exercises in this section:

1. Reimplement the word-count we did last week with MrJob.
2. Enhance the word-count with a preprocessing.
3. Sort the results where the most frequent words are on top.

The `Jupyter` notebooks are located in the folder [./v03_exercises_material/2_WordCount/](./v03_exercises_material/2_WordCount/).

## Average with MapReduce

The goal is to calculate the average (the mean) with MapReduce given integers as input.

The `Jupyter` notebooks are located in the folder [./v03_exercises_material/3_Average/](./v03_exercises_material/3_Average/).

## Pi Estimation with Monte-Carlo-Simulation

You already did the Pi estimation with the hadoop examples. Now it is time to implement it for yourselves.

The notebook is in the folder [./v03_exercises_material/4_Pi-Estimation/](./v03_exercises_material/4_Pi-Estimation/)

## Anagram

> An anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.

From [Wikipedia](https://en.wikipedia.org/wiki/Anagram).

Your task is to implement this algorithm with MapReduce [./v03_exercises_material/5_Anagram/](./v03_exercises_material/5_Anagram/).

## Movies

We we load the [MovieLens dataset](https://grouplens.org/datasets/movielens/), do some cleaning and get the average ratings for all movies.

The material is located under [./v03_exercises_material/6_Movies/](./v03_exercises_material/6_Movies/).
