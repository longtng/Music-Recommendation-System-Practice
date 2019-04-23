# Music-Recommendation-System-Practice
The laboratory from Algorithmic Machine Learning Course at EURECOM

This repository included the Music Recommendation System Laboratory from the Algorithmic Machine Learning Course at EURECOM, which was conducted in a group with DANG Ngoc-Vien (Ngoc-Vien.Dang@eurecom.fr).

Furthermore, the Algorithmic Machine Learning Course was offered by Prof. Pietro Michiardi at EURECOM. The details of the course can be retrieved in here https://github.com/DistributedSystemsGroup/Algorithmic-Machine-Learning

## Course Description
The goal of this course is mainly to offer data science projects to students to gain hands-on experience. It nicely merges the theoretical concepts students can learn in our courses on machine learning and statistical inference, and systems concepts we teach in distributed systems.

Notebooks require to address several challenges, that can be roughly classified in:
- Data preparation and cleaning
- Building descriptive statistics of the data
- Working on a selected algorithm, e.g., for building a statistical model
- Working on experimental validation

## The Laboratory Description
The goal of this notebook is studying how to build a simple recommender system: we focus on music recommendations, and we use a simple algorithm to predict which items users might like, that is called ALS, alternating least squares.

### The Goals of this laboratory:
- Revisit (or learn) recommender algorithms
- Understand the idea of Matrix Factorization and the ALS algorithm
- Build a simple model for a real usecase: music recommender system
- Understand how to validate the results

### Next, an outline of the steps we will follow in this Notebook:
- Inspect the data using Pandas, and build some basic, but very valuable knowledge about the information we have at hand
- Formally define what is a sensible algorithm to achieve our goal: given the "history" of user taste for music, recommend new music to discover. Essentialy, we want to build a statistical model of user preferences such that we can use it to "predict" which additional music the user could like
- With our formal definition at hand, we will learn different ways to implement such an algorithm. Our goal here is to illustrate what are the difficulties to overcome when implementing an algorithm like Matrix Factorization
- We will focus on an existing implementation, available in ```Implicit```, which we will use out of the box to build a reliable statistical model
- Finally, one important topic we will cover in all our Notebooks is **how to validate the results we obtain**, and **how to choose good parameters to train models** especially when using an "opaque" library for doing the job. As a consequence, we will focus on the statistical validation of our recommender system.

