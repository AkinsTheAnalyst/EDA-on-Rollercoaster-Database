# EDA-on-Rollercoaster-Database
In this project, I got my hands on a dataset on rollercoasters. This data contains information about over 1000 rollercoasters. Information was scraped from wikipedia on which I carried out Exploratory Data Analysis (EDA). Check it out.



# Exploratory Data Analysis Project

## Project Overview

This project demonstrates a practical **Exploratory Data Analysis (EDA)** workflow, covering the process of understanding, preparing, exploring, and analyzing a dataset to extract meaningful insights.

The analysis follows five key stages: **Data Understanding, Data Preparation, Feature Understanding, Feature Relationships, and Asking Questions of the Data.**

---

## Step 1: Data Understanding

The first stage focused on developing a clear understanding of the dataset and its overall structure.

We examined the **DataFrame shape, head and tail records, data types, and descriptive statistics**. These provided an initial overview of the dataset and helped us understand its characteristics.

This stage allowed us to identify:

* The number of rows and columns
* The structure of the dataset
* The types of data contained in each column
* General statistical characteristics of the dataset

This initial assessment provided the foundation for the subsequent stages of the analysis.

---

## Step 2: Data Preparation

The next stage focused on preparing the dataset for analysis. This involved identifying duplicate columns, removing irrelevant rows and columns, renaming columns, and creating new features where necessary.

The `.drop()` function was used to remove unwanted data. We also practiced **subsetting the dataset** by selecting the columns required for the analysis while excluding those that were not relevant.

The selected subset was then assigned to a new DataFrame using `.copy()`. This ensured that the subset was treated as an independent DataFrame rather than simply referencing the original dataset.

The preparation stage helped create a cleaner and more focused dataset for further analysis.

---

## Step 3: Feature Understanding

With the dataset prepared, we moved into **univariate analysis**, where individual features were examined independently.

This stage focused on understanding the distribution and characteristics of individual variables through different visualization techniques, including:

* Histograms
* Kernel Density Estimation (KDE)
* Boxplots

Using **Matplotlib**, we learned how to represent a single series, such as an individual column, visually. These plots helped us understand the distribution, spread, and general behavior of individual features.

---

## Step 4: Feature Relationships

The analysis then progressed to exploring relationships between multiple features.

At this stage, we introduced **Seaborn**, which provided additional visualization capabilities for examining relationships between two or more series.

These visualizations helped reveal patterns and relationships within the dataset and provided insights that could be used to answer analytical questions.

We also examined **correlation** between variables. An important point highlighted during this stage was that correlation analysis is applicable to **numerical variables**.

---

## Step 5: Asking a Question About the Data

The final stage focused on using the insights gained from the analysis to answer a specific question about the dataset.

The question explored was:

> **What are the locations with the fastest roller coasters?**

We analyzed the relevant data to answer this question and presented the result visually using a **horizontal bar chart**.

This final stage demonstrated how EDA can move beyond simply exploring a dataset and be used to answer specific questions and communicate findings clearly.

---

## Key Skills Practiced

Through this project, I practiced:

* Data understanding and exploration
* DataFrame inspection
* Data preparation and subsetting
* Removing irrelevant data
* Feature creation
* Univariate analysis
* Data visualization with Matplotlib
* Data visualization with Seaborn
* Histograms, KDE plots, and boxplots
* Correlation analysis
* Asking and answering data-driven questions
* Communicating analytical findings through visualizations

---

## Conclusion

This project provided a practical introduction to the **Exploratory Data Analysis workflow**, from understanding and preparing raw data to exploring individual features, examining relationships, and answering specific questions.

It demonstrates how Python visualization and data-analysis tools can be used to transform a dataset into meaningful insights.
