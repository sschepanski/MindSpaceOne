# Exploring the Effects of Hypnotherapy and Aromatherapy via MindspaceOne

## Introduction

The **MindspaceOne** project investigates the effects of combining hypnotherapy and aromatherapy, delivered via a smartphone-based platform, on individuals' ability to achieve targeted states of relaxation or concentration. As modern life becomes increasingly stressful, particularly among younger individuals, there is a growing need for accessible interventions to support mental health and well-being. This project evaluates whether pairing hypnotherapy with aromatherapy through classical conditioning enhances the effectiveness of these interventions.

In this controlled, randomized experimental pilot study, participants are assigned to one of four groups: (I) Hypnotherapy + Aromatherapy, (II) Hypnotherapy alone, (III) Aromatherapy alone, or (IV) a control group. Over a 4-week period, participants engage with the assigned treatment daily, followed by a 1-week test phase to assess conditioning effects in selected groups.

## Objective

The primary objective is to assess whether daily hypnotherapy sessions, with or without aromatherapy, improve participants' relaxation and concentration as measured by the **Multidimensional Mood Questionnaire (MDBF)** subscales. Secondary objectives include evaluating whether hypnotherapy effects can be conditioned to aromatherapy and exploring influences of age, gender, and stress levels.

## Hypotheses

### Primary Hypothesis (H1):
- Hypnotherapy, delivered via a smartphone-based platform, enhances relaxation and concentration, as indicated by improvements on the MDBF subscales from baseline to the end of the 4-week intervention.

### Secondary Hypotheses:
1. Aromatherapy combined with hypnotherapy enhances the conditioning effect, allowing aromatherapy alone to trigger relaxation or concentration effects.
2. Exploratory analysis will examine effects on perceived stress (**PSS**) and well-being (**WHO-5**), as well as moderating influences of age, gender, and socioeconomic status.

## Project Structure

- **`data/`**: Contains the dataset used in the analysis.
- **`scr/`**: R scripts for data exploration, preprocessing, modeling, and assumption testing.
- **`graphs/`**: Contains visual outputs generated during the analysis.

## Scripts

- **Analysis.ipynb**: This script conducts the core statistical analyses, including data preprocessing, hypothesis testing, and visualization of results.

## Acknowledgements

We extended our gratitude to **Priv.-Doz. Dr. Michael Teut** for his invaluable contribution to the execution of this study. We also express gratitude to the entire research group of **[Prof. Dr. med. Seifert](https://kinderonkologie.charite.de/forschung/ag_seifert/team/)** and all participants for their invalubale contributions to this study as well as thanks to the funding agencies. Statistical analysis was conducted by **Dr. Steven Schepanski**, who also oversaw this notebook.

## Getting Started

1. **Clone this repository:**

   ```bash
   git clone https://github.com/sschepanski/MindSapceOne.git
   ```
2. **Set up your R environment:**
   Ensure that R is installed and configured. All required packages are integrated directly in the respective R scripts. When running a script, any missing packages will be prompted for installation.
3. **Run the provided R scripts:**
   Execute the R scripts found in the scr/ directory for data preprocessing, modeling, and assumption testing. Set your working directory to the root of the project to ensure smooth execution of the scripts.

## Contributions

This project analysis was conducted by **Dr. Steven Schepanski** and represents a comprehensive study into the effects of hypnotherapy and aromatherapy on relaxation outcomes. It is part of the manuscript by Bogdanski et al.

## License

This project is licensed under the MIT License.