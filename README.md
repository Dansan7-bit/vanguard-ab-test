# Vanguard Digital Experiment Analysis

Welcome to the Module 2 Project! In this project, you will apply the skills and knowledge acquired throughout the module, including EDA (Exploratory Data Analysis), data cleaning, performance metrics, hypothesis testing, experiment evaluation, and Tableau visualization. This README provides an overview of the project, the dataset, and how to get started.

## Project Overview

### Introduction
You are tasked with analyzing the results of a digital experiment conducted by Vanguard, a US-based investment management company. The experiment was designed to evaluate the impact of a new user interface (UI) and in-context prompts on client behavior during an online process. The key question is whether these changes led to higher process completion rates compared to the traditional interface.

### Project Context
As a newly hired data analyst on Vanguard's Customer Experience (CX) team, your first assignment is to assess the effectiveness of the new digital interface. The experiment was conducted over a period from 3/15/2017 to 6/20/2017 and involved two groups:
- **Control Group:** Clients interacted with Vanguard’s traditional online process.
- **Test Group:** Clients experienced the new, enhanced digital interface.

Both groups followed the same sequence: an initial page, three subsequent steps, and a final confirmation page. Your goal is to determine whether the new design improved the user experience and completion rates.

## Dataset Description

The analysis will be conducted using the following datasets:

1. **Client Profiles (df_final_demo):**
   - Contains demographic information such as age, gender, and account details of the clients.

2. **Digital Footprints (df_final_web_data):**
   - Tracks client interactions online. The data is divided into two parts (pt_1 and pt_2), which should be merged before analysis.

3. **Experiment Roster (df_final_experiment_clients):**
   - Lists the clients who participated in the experiment, indicating which group (control or test) they were assigned to.

## Project Structure

The project is structured as follows:

- **Data Preparation:**
  - Merge and clean the datasets for analysis.
  - Perform EDA to understand the distribution of the data and identify any anomalies or outliers.

- **Hypothesis Testing:**
  - Formulate and test hypotheses related to the impact of the new UI on completion rates.

- **Experiment Evaluation:**
  - Assess the overall effectiveness of the experiment, including statistical significance of the results.

- **Visualization:**
  - Create visualizations using Tableau to illustrate key findings and support the conclusions.

## Getting Started

### Prerequisites
To run the analysis, you need the following tools:
- Python (with pandas, numpy, scipy, and other relevant libraries)
- Jupyter Notebook
- Tableau (for creating visualizations)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/vanguard-experiment-analysis.git
