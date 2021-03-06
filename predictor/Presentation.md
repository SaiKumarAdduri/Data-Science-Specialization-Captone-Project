DATA SCIENCE SPECIALIZATION - Capstone Project - Word Predictor
========================================================
author: Sai Kumar Adduri
date: 8/29/2020
autosize: true

========================================================

## Introduction

* The goal of this exercise is to create a product to highlight the prediction algorithm that you have built and to provide an interface that can be accessed by others.
* A slide deck consisting of no more than 5 slides created with R Studio Presenter (https://support.rstudio.com/hc/en-us/articles/200486468-Authoring-R-Presentations) for pitching the algorithm and app.

========================================================

## Objective

This is the Capstone project for the Coursera Data Science specialization, which involved developing a word predicting application in R/Shiny. We were provided a Corpus of Text from Blogs, Twitter and News from HC Corpora which is a collection of corpora for various languages freely available to download. However we were required to use only The English texts.

This project is conducted with the support of the Johns Hopkins University and in cooperation with SwiftKey.

========================================================

## App Development

The application uses natural language processing, namely, n-grams, Markov model, and Katz's back-off model to perform text prediction.

The series of steps to build the model were:

* Cleaning and preparing the data
* Exploratory Analysis
* Build n-grams from the data corpus
* Build frequencies from the n-grams
* Build the prediction model

The application predicts the next word in a phrase/sentence. Up to four possible next word predictions are available, and you have the option to click on any of them. The word selected will be added to your text then application continues on predicting the next following word.

========================================================

## Application

* Shiny App:
<https://saikumaradduri.shinyapps.io/predictor/>


## Thank you
