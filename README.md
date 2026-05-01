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
