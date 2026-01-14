# Digital_Therapy_Baby - Baby Survey and Behavioral Dataset

## Seoul National University Developmental Cognitive Neuroscience Lab
PI: Sang Ah Lee

Sang-Eon Park, 
Jisu Chung



## 1. Overview
This repository contains de-identified survey and behavioral task data collected as part of a research study investigating emotional and attentional characteristics in children.


📖 About This Dataset

This dataset aims to address that gap by providing:

Standardized questionnaire data assessing depression, anxiety, and ADHD-related symptoms

Raw behavioral task data collected in controlled experimental settings



The dataset includes standardized questionnaire scores related to depression, anxiety, and ADHD symptoms, as well as raw task data files generated during experimental sessions.

Survey data including depression, anxiety, and ADHD symptom measures

Raw behavioral task files collected during experimental sessions

Fully de-identified participant information in compliance with ethical research standards

---

## 2. Data Information


### Dataset Contents

Standardized questionnaire data

Depression (CES-DC) : Weissman, M. M., Orvaschel, H., & Padian, N. (1980). Children’s Symptom and Social Functioning Self-Report Scales Comparison of Mothers’ and Children’s Reports. The Journal of nervous and mental disease, 168(12), 736-740.

Anxiety (STAI-CH) : Spielberger, C. D., Edwards, C. D., Montouri, J., & Lushene, R. (1973). State-Trait Anxiety Inventory for Children (STAI-CH)

ADHD symptoms (K-ARS) : DuPaul GJ. Parent and Techer Rating of ADHD Symptoms: Psychometric Properties in a Community-Based Sample;1991.

Raw behavioral task output files

Fully anonymized participant information, compliant with ethical research standards



### Data Collection

Data were collected between 2023 and 2024 at:

Gyeonggi Children’s Museum (M)

Seoul National University Developmental Cognitive Neuroscience Lab (L)

Participants completed caregiver-reported and self-reported questionnaires, as well as computerized behavioral tasks, administered by trained experimenters under standardized protocols.

De-identification
All data were fully anonymized prior to sharing.

No names, contact information, or direct personal identifiers are included

Subject IDs are randomly assigned and cannot be linked back to individuals

Location and experimenter identifiers are encoded to prevent re-identification



---

## 3. Dataset Description

### 3.1 Baby_Survey_Data.xlsx
This file contains subject-level demographic information and survey scores.

**Variables:**
- `sub_date`: Date of experiment + Subject ID
- `date`: Date of experiment
- `Sbj`: Anonymous subject ID
- `age_detail`: Detailed age information
- `age`: Age in years
- `sex`: Biological sex
- `location`: Data collection location (M : Children's Museum, L: Laboratory)
- `station`: Experimental station ID
- `Experimenter`: Experimenter ID
- `ces_dc`: CES-DC total score
- `depression`: CES-DC > 15 (1 = above cutoff)
- `stai_ch`: STAI-CH total score
- `anxiety`: 1: 39 ≤ STAI-CH < 43, 2: STAI-CH ≥ 43
- `Parent`: Parent-report indicator (1: Father / 2: Mother)
- `k_ars`: Korean ADHD Rating Scale total score
- `adhd`: k-ars Score above 19 : 1
- `inattention`: k_ars Inattention subscale score
- `hyperactivity`: k_ars Hyperactivity subscale score

---

## 4. Survey Measures
- **CES-DC (Center for Epidemiological Studies Depression Scale for Children):**  
  Measures depressive symptoms in children. Higher scores indicate greater depressive symptom severity.
  Weissman, M. M., Orvaschel, H., & Padian, N. (1980). Children’s Symptom and Social Functioning Self-Report Scales Comparison of Mothers’ and Children’s Reports. The Journal of nervous and mental disease, 168(12), 736-740.

- **STAI-CH (State-Trait Anxiety Inventory for Children):**  
  Assesses anxiety levels in children. Higher scores indicate greater anxiety.
  Spielberger, C. D., Edwards, C. D., Montouri, J., & Lushene, R. (1973). State-Trait Anxiety Inventory for Children (STAI-CH) [Database record]. APA PsycTests.
https://doi.org/10.1037/t06497-000

- **K-ARS (Korean ADHD Rating Scale):**  
  Evaluates ADHD-related behaviors. Higher scores indicate greater ADHD symptom severity.
  DuPaul GJ. Parent and Techer Rating of ADHD Symptoms: Psychometric Properties in a Community-Based Sample;1991.

---

## 5. Raw Data Structure

### /raw_data
This folder contains raw task data files generated during experimental sessions.

**File naming format:**

(yymmdd)(Sbject number)_(task name)_Main_YYYY_MM_DD_HHhmm.csv

Example:

240315012_Flanker_Main_2024_03_15_14h30.csv

Each file corresponds to a single participant’s task session and includes trial-level behavioral data.


⚙️ Data Processing and Missing Values

The dataset represents raw survey scores and raw task output files

Missing values may be present where participants did not complete specific items or trials

No imputation, normalization, or statistical preprocessing has been applied

Users are responsible for handling missing data according to their analytical needs.


⚖️ Ethical Considerations

The study protocol was reviewed and approved by an institutional review board (IRB).
Written informed consent was obtained from participants and/or their legal guardians prior to data collection.

📄 License

This dataset is shared under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
