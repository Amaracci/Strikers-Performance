# Strikers-Performance

## Introduction

Football is all about big moments, and strikers make them happen. But what makes a striker stand out? For this project, "Segmenting and Classifying the Best Strikers," I analyzed a dataset of 500 strikers to uncover the patterns and traits that separate the elite from the rest.

## Project Overview

Using data analysis and machine learning, I explored key performance metrics to understand what makes a striker great. From visualizing stats to building predictive models, my goal was to classify strikers based on their impact on the game.

## Purpose

This project aims to create a structured, data-driven method for evaluating and categorizing strikers. This method can be useful for coaches, scouts, and analysts who want to make informed decisions about recruitment, team selection, and tactics.

## Data Source

The dataset for this project comes from a Udemy course I took as part of my graduation requirements. It contains detailed information on 500 strikers, including personal attributes and performance statistics.

## Dataset Breakdown

The dataset includes 500 strikers, covering both personal details and performance stats:
- Striker ID – Unique identifier for each player.
- Nationality – Country of origin.
- Footedness – Right or left-footed.
- Marital Status – Married or single.
- Goals Scored – Total goals netted.
- Assists – Total assists provided.
- Shots on Target – Accuracy in front of goal.
- Conversion Rate – Efficiency in turning shots into goals.
- Dribbling Success – Ability to beat defenders.
- Movement Off the Ball – How well they find space.
- Hold-up Play – Ability to retain possession.
- Aerial Duels Won – Performance in the air.
- Defensive Contribution – Pressing and defensive efforts.
- Big Game Performance – How they perform in high-pressure matches.

## Tool

Python - For Cleaning, EDA, and Machine Learning

## My Process

### Data Preprocessing

- Filled missing data using the median.
- Fixed incorrect data types.
.
- Scaled numerical features to optimize model performance.

### Exploratory Data Analysis (EDA)

- Pie charts to analyze right vs. left-footed strikers.
- Count plots to compare strikers by nationality.
- Scatter plot to view the linearity between hold-up play and consistency rate.

 ### Statistical Tests

 - Pearson Correlation Test: To find any significant correlation between strikers' Hold-up play and consistency rate.
 - Linear Regression: Checking if strikers' hold-up play significantly influences their consistency rate.

### Machine Learning Models

- Feature Engineering: Created a Total Contribution Score to evaluate overall performance.
- Encoded categorical data using Label Encoding.
- Created dummies for Nationality.
- KMeans Clustering: Used to segment the strikers into a cluster of two (2).
- Logistic Regression (LGR) – Used to analyze accuracy.




