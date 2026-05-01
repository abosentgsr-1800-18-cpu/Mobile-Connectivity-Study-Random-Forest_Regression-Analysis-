## Mobile Usage and Digital Well-being Analysis
**Project Overview**


The primary objective of this project is to analyze how modern mobile connectivity patterns specifically screen time, notification frequency, and nighttime usage impact a user's stress level and sleep quality. 
By leveraging a comprehensive dataset of 15,000 individuals, this project identifies the tipping point where digital habits begin to negatively affect human health.

### Methodology

**Random Forest Regression**: Model was implemented for this study of 15,000 users because it effectively handles the messy, non-linear nature of real-world behavioral data better than simpler models.

### Prerequisites

#### To run the Jupyter Notebook, you will need the following Python libraries installed:

- pandas

- numpy

- scikit-learn

- matplotlib

- seaborn


### Dataset Description


The analysis is based on the sleep_mobile_stress_dataset_15000.csv, which includes:

- Sample Size: 15,000 observations.

  **Features**:

- Daily Screen Time (hours): Total active usage of mobile devices.

- Notifications Received: Frequency of digital interruptions per day.

- Usage Before Sleep (minutes): Exposure to screen light in the final hour before bed.

- Caffeine Intake (mg): Daily consumption levels used as a control variable.

- Physical Activity (minutes): Daily exercise levels.

**Target Variables**:

- Sleep Quality Score and Stress Level Score

## Conclusion

- This Project confirms a statistically significant and high-magnitude relationship between smartphone usage habits and mental well-being.

The analysis of 15,000 individuals demonstrates a significant correlation between daily digital habits and personal well-being. By utilizing a Random Forest regression model, the study successfully captured the non-linear "threshold effects" where moderate screen time may be manageable, but excessive usage (e.g., beyond the 8-hour mark) exponentially increases stress and degrades sleep quality.

- Generally this project concludes that effective health and stress management now require strict digital hygiene. While diet and exercise remain important, managing our interaction with mobile devices is the most critical step toward improving sleep quality and reducing mental fatigue in a connected world.

## Key Findings

- Daily Screen Time is the most important feature in the model, showing a direct linear-to-exponential impact on mental well being.

- The Inverse Correlation: My analysis confirms a clear relationshipas screen time increases, there is a consistent decrease in sleep quality and a sharp increase in stress levels.
  
- Dominance of Digital Habits: I found that Daily Screen Time had a much higher feature importance than traditional factors like Caffeine Intake. This indicates that digital connectivity is now a primary driver of mental well being.


## Limitation

**Fixed Range**: Random Forest cannot predict stress or sleep scores outside the dataset's specific limits.

**No Causality**: High screen time correlates with stress but doesn't prove it is the cause.

**Imbalanced Features**: Rare habits (like zero caffeine) provide less data for the model to learn.

**Demographic Gap**: Findings from these 15,000 subjects may not apply to children or the elderly.

**Sampling Bias**: The 15,000 individuals may not perfectly represent the global population, leading to a Generalization Error

