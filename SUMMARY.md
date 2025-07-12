# Summary of Cognitive Neuroscience Face Morphing Task Analysis

This document provides a detailed summary of the analysis of behavioral data from a face morphing task. The project investigates how various factors, such as spatial frequency, gender, and handedness, influence the perception of facial identity.

## Key Findings

### 1. Modeling Perceptual Responses

The analysis began by modeling the relationship between the morph level of faces and the participants' responses. Two types of functions were fitted to the data:
- **Sigmoid Function**: A standard logistic function to model the probability of identifying a face as one of the target identities.
- **Gaussian Sigmoid Function**: A modified sigmoid function that incorporates a Gaussian cumulative distribution function, which can sometimes provide a better fit for psychometric data.

The models were fitted for two main identity continua: "Abbas-Hasan" (AbHa) and "Mahnaz-Goli" (MahGol). The sensitivity parameter (beta) of these functions was estimated to quantify how sharply the perception of identity changes with the morph level.

### 2. Model Comparison using AIC and BIC

To determine which model (sigmoid or Gaussian sigmoid) best explains the data, the Akaike Information Criterion (AIC) and the Bayesian Information Criterion (BIC) were calculated. These metrics help in model selection by penalizing models with more parameters, thus balancing goodness of fit with model complexity.

- For the "Hasan" responses, the Gaussian sigmoid model generally provided a better fit, as indicated by lower AIC and BIC values compared to the simple sigmoid model.
- Similarly, for the "Goli" responses, the Gaussian sigmoid model was found to be superior.

This suggests that the relationship between morph level and identity perception is better captured by a model that allows for more flexibility in its shape, such as the Gaussian sigmoid.

### 3. Hypothesis Testing

Several hypotheses were tested to explore the factors influencing face identity detection. The key findings from these tests are summarized below:

#### a. Effect of Spatial Frequency

- The analysis compared sensitivity to identity in different spatial frequency bands: Intermediate Frequency (IF), Low Frequency (LF), and High Frequency (HF).
- The results showed that sensitivity (beta) was highest in the **High Frequency (HF)** band, suggesting that fine details are crucial for accurate identity detection.
- Z-tests confirmed that the differences in performance between the frequency bands were statistically significant.

#### b. Identifying Conspecific vs. Heterospecific Gender

- The study investigated whether participants were more sensitive to faces of the same gender (conspecific) or the opposite gender (heterospecific).
- The results indicated that participants showed **higher sensitivity to conspecific faces**. This suggests a perceptual advantage for identifying faces that match one's own gender.
- The difference in performance was statistically significant, as confirmed by a z-test.

#### c. Role of Handedness in Different Frequency Bands

- The analysis explored whether the hand used to respond (left or right) affected performance, particularly in different spatial frequency bands. This is relevant to the hemispheric specialization of the brain, with the right hemisphere being dominant for face processing.
- In the **Low Frequency (LF)** and **Intermediate Frequency (IF)** bands, the **left hand** (controlled by the right hemisphere) was associated with higher sensitivity.
- In the **High Frequency (HF)** band, the **right hand** (controlled by the a left hemisphere) showed slightly better performance, although the difference was less pronounced.

#### d. Dominant vs. Non-Dominant Hand Performance

- The study also examined whether using the dominant hand led to better performance.
- The results showed that the **dominant hand** was associated with higher sensitivity across all spatial frequency bands, with the most significant advantage observed in the **High Frequency (HF)** band.

#### e. Gender Differences in Identity Detection

- A direct comparison of performance between male and female participants was conducted.
- The analysis revealed that **females were significantly better** at the identity detection task than males, showing higher sensitivity (beta) and a better-defined ROC curve.

#### f. Effect of Trial Type (Mixed vs. Same-Gender Blocks)

- The experiment included blocks where faces were of the same gender and blocks where they were mixed.
- Performance was **significantly better in the same-gender blocks** compared to the mixed-gender blocks. This suggests that the cognitive load is lower when the task involves less switching between different gender categories.

## Conclusion

The analysis of the face morphing task data provides several key insights into the cognitive processes of facial identity perception. The findings highlight the importance of high-frequency information, the advantage of processing conspecific faces, and the influence of handedness and gender on performance. The superiority of the Gaussian sigmoid model suggests that the underlying perceptual mechanisms are complex and not always captured by simple models. These results contribute to a deeper understanding of how the human brain processes faces and the various factors that modulate this ability.
