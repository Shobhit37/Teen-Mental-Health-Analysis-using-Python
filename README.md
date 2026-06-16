# Teen Mental Health: Exploratory Data Analysis

## About the Dataset

This dataset contains anonymized records of teenagers' digital habits, lifestyle behaviors, and mental health indicators. It includes variables related to social media usage, screen time before sleep, sleep patterns, academic performance, stress, anxiety, addiction levels, digital wellbeing practices, and mental health risk scores.

The dataset is intended to support exploratory analysis of how behavioral and psychological factors interact in adolescent wellbeing.

**Dataset Size:** 1,200 rows × 16 columns

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## Initial Checks and Transformations

The following data quality checks were performed before analysis:

- Verified that all columns had appropriate data types.
- Checked for missing values and found none.
- Checked for duplicate records and found none.
- Reviewed categorical columns for invalid or unexpected values.
- Examined the distributions of numerical variables.
- Converted the `depression_label` column from `0` and `1` to more interpretable labels: `Yes` and `No`.

The dataset was found to be clean and required minimal preprocessing.

---

## Key Findings

### 1. Sleep Duration and Sleep Quality

Lower sleep duration was generally associated with poorer sleep quality.

<img width="942" height="579" alt="image" src="https://github.com/user-attachments/assets/f74963d4-5ac8-45d2-92ce-5b8224aed533" />


---

### 2. Mental Health Risk and Psychological Factors

Mental health risk score showed moderate positive associations with:

- Stress level
- Anxiety level
- Addiction level

Participants reporting higher levels of these psychological factors tended to have higher mental health risk scores.

<img width="1141" height="676" alt="image" src="https://github.com/user-attachments/assets/fd0705e1-3e5e-4ebe-89a2-80ebb94fca70" />


---

### 3. Digital Wellbeing and Usage Patterns

Digital wellbeing status was associated with differences in digital behavior.

Participants at risk showed higher values in:

- Daily social media usage
- Screen time before sleep

This suggests that digital wellbeing may be more reflective of technology-use habits than mental health outcomes.

<img width="981" height="596" alt="image" src="https://github.com/user-attachments/assets/8a72440b-2bfe-4e82-957e-bb5375deee55" />


---

### 4. Depression-Related Observations

Teenagers identified as depressed tended to exhibit:

- Higher daily social media usage
- Higher stress levels
- Higher anxiety levels
- Higher mental health risk scores
- Lower sleep duration

<img width="1030" height="167" alt="image" src="https://github.com/user-attachments/assets/1c087bec-e316-44c4-9d42-7f84e3b8a7e0" />

However, this finding should be interpreted with caution, as only 31 participants (approximately 2.6% of the dataset) belonged to the depressed subgroup. These observations are exploratory and should not be generalized to the broader population.

---

## Further Scope

Apart from the associations between psychological variables and mental health risk, and the relationship between digital wellbeing and digital usage behaviors, no substantial relationships were observed among the remaining variables.

Lifestyle and demographic factors such as social media usage, sleep duration, screen time before sleep, academic performance, physical activity, and age demonstrated negligible associations within this dataset.

These findings suggest that, in this dataset, mental health risk appears to be more closely related to psychological indicators than to broader lifestyle factors.

---

## Limitations

- This analysis is exploratory in nature and does not establish causal relationships.
- The depressed subgroup represents a very small proportion of the dataset, limiting the reliability of depression-related observations.
- The mental health risk score may have been derived using other psychological variables included in the dataset, which could partially explain the observed associations.
- The absence of strong relationships does not necessarily imply that such relationships do not exist in real-world populations; it only reflects the patterns present in this dataset.
