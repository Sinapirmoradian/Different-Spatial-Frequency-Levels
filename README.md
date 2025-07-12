# Cognitive Neuroscience Face Morphing Task Analysis

This project analyzes behavioral data from a face morphing task to investigate the factors influencing the perception of facial identity. The analysis is implemented in a Python script that uses libraries such_ as `pandas`, `numpy`, `matplotlib`, and `scipy` for data manipulation, statistical analysis, and visualization.

## Project Overview

The core of the project is to analyze how different factors affect the recognition of faces that are morphed between two identities. The key areas of investigation include:

- **Modeling Perceptual Responses**: The script fits sigmoid and Gaussian sigmoid functions to the behavioral data to model the relationship between the morph level of a face and the participant's response. This helps in understanding the sensitivity of perception to changes in facial features.

- **Model Comparison**: To determine the best model for the data, the script calculates the Akaike Information Criterion (AIC) and the Bayesian Information Criterion (BIC). These metrics are used to compare the goodness of fit of the sigmoid and Gaussian sigmoid models, helping to identify the most appropriate model for the underlying cognitive processes.

- **Hypothesis Testing**: The project tests several hypotheses related to face perception. These include:
  - The effect of different spatial frequencies (low, high, and intermediate) on identity detection.
  - The influence of the gender of the participant and the face being viewed (conspecific vs. heterospecific).
  - The role of handedness (left vs. right) in performing the task, particularly in different spatial frequency bands.
  - The impact of using a dominant vs. non-dominant hand on task performance.
  - A comparison of the performance of male and female participants in the identity detection task.
  - The effect of trial type (mixed vs. same-gender blocks) on performance.

- **Statistical Analysis and Visualization**: The script uses z-tests to determine the statistical significance of the findings. The results are visualized using bar plots to show differences in sensitivity (beta values) and ROC curves to illustrate the trade-off between true positive and false positive rates.

## How to Run the Code

To run the analysis, you need to have a Python environment with the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `scikit-learn`

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib scipy scikit-learn
```

Once the dependencies are installed, you can run the main analysis script:

```bash
python cognitive_neuroscience_sina__pirmoradian_810101125_v2.py
```

The script will perform the data analysis and generate plots to visualize the results. Make sure that the data file (`data.csv` and `subjectInfo.csv`) is in the correct path as specified in the script. The script currently loads data from a Google Drive link, so you may need to update the path to your local data files.
