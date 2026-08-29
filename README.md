# Exploring the Effects of Hypnotherapy and Aromatherapy via MindspaceOne

## Introduction

The **MindspaceOne** project investigates whether a fully digital relaxation intervention combining guided hypnotherapy with essential-oil aromatherapy can improve subjective relaxation. The intervention was designed as a low-threshold, smartphone-based approach that combines auditory and olfactory stimuli and examines whether repeated pairing of hypnotherapy with a scent can produce a conditioned relaxation response.

The study was conducted as a four-arm randomized controlled trial with 504 participants. Participants were assigned to one of four groups: (I) Hypnotherapy + Aromatherapy, (II) Hypnotherapy alone, (III) Aromatherapy alone, or (IV) a control condition. During the 4-week intervention period, participants completed self-guided sessions every 2 days. A fifth test week was conducted in the combined and aromatherapy-only groups to examine whether the scent alone could elicit a conditioned relaxation response.

## Objective

The primary objective was to assess whether digital hypnotherapy, with or without aromatherapy, improves **subjective calmness** after the 4-week intervention. Calmness was assessed using the calmness–restlessness subscale of the **Multidimensional Mood Questionnaire (MDBF)**.

Secondary objectives included examining whether repeated pairing of hypnotherapy and aromatherapy produces a conditioned relaxation effect, as well as evaluating changes in perceived stress using the **Perceived Stress Scale (PSS-10)** and well-being using the **WHO-5 Well-Being Index**.

## Hypotheses

### Primary Hypothesis (H1):
- Participants receiving hypnotherapy, either alone or in combination with aromatherapy, were expected to show greater improvements in subjective calmness from baseline to post-intervention than participants in the control condition.

### Secondary Hypotheses:
1. Repeated pairing of aromatherapy with hypnotherapy was expected to produce a conditioning effect, such that subsequent exposure to the scent alone would elicit increased relaxation.
2. Exploratory analyses examined intervention-related changes in perceived stress (**PSS-10**) and well-being (**WHO-5**), alongside additional descriptive and sensitivity analyses reported in the accompanying analysis notebook.

## Project Structure

- **`data/`**: Contains the cleaned analysis datasets and imputed datasets used for the statistical analyses.
- **`data/Collection/`**: Contains the original survey exports, codebook, variable definitions, value codes, and related source files used during preprocessing.
- **`scr/`**: Contains the reproducible R notebooks for data preprocessing and statistical analysis.
- **`graphs/`**: Contains figures generated during the analysis.

## Scripts

- **`Data Preprocessing.ipynb`**: Imports the original study data from `data/Collection/`, performs the required data cleaning, recoding, and variable preparation steps, and writes the cleaned analysis datasets to `data/`.
- **`Analysis.ipynb`**: Conducts the statistical analyses reported for the study, including outcome scoring, multiple imputation, intention-to-treat and per-protocol analyses, conditioning analyses, multiple-testing correction, and visualization of results.

## Main published finding

At post-intervention, the MindSpaceOne group showed greater subjective calmness than control (β = 2.08, 95% CI 0.50–3.65, p = 0.010, d = 0.38), as did the hypnotherapy-only group (β = 1.80, 95% CI 0.24–3.37, p = 0.024, d = 0.33). No evidence for a conditioned relaxation response to the scent alone was observed at week 5. See the publication for the complete results and interpretation.


## Acknowledgements

We extended our gratitude to all participants for their invalubale contributions to this study. Statistical analysis was conducted by **Dr. Steven Schepanski**, who also oversaw this notebook. This project was published:

**Ngandeu Schepanski, S., Bogdanski, M., Siegfried, K. K., Schulz, S., Czakert, J., Kandil, F., Teut, M., Siewert, J., & Seifert, G. (2026).** Promoting relaxation through essential oil-enhanced digital hypnotherapy: A randomized controlled trial. *Psychological Medicine, 56*, e80, 1–12. [https://doi.org/10.1017/S0033291726103778](https://doi.org/10.1017/S0033291726103778)

The article is Open Access under CC BY 4.0. The repository is the reproducibility resource referenced in the article's data-availability statement.


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

This project analysis was conducted by **Dr. Steven Ngandeu Schepanski** and represents a comprehensive study into the effects of hypnotherapy and aromatherapy on relaxation outcomes.

## License

This project is licensed under the MIT License.