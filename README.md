

De-identification
All data were fully anonymized prior to sharing.
No names, contact information, or direct identifiers are included.
Subject IDs are randomly assigned and cannot be linked back to individuals.



### Baby_Survey_Data.xlsx
This file contains subject information and survey scores

[ sub_date	/ date	/ Sbj /	age_detail /	age	/ sex /	location /	station	/ Experimenter /	ces_dc /	depression / stai_ch /	anxiety /	Parent /	k_ars /	adhd /	inattention /	hyperactivity ]

Survey Measures
- CES-DC: Center for Epidemiological Studies Depression Scale for Children.
  Higher scores indicate higher levels of depressive symptoms.
- STAI-CH: State-Trait Anxiety Inventory for Children.
  Higher scores indicate greater anxiety.
- K-ARS: Korean ADHD Rating Scale.
  Higher scores indicate greater ADHD-related symptoms.



### /raw_data
This fiolder contains raw files of current data set


File name format:

(yymmdd)(Sbject number)_(task name)_Main_YYYY_MM_DD_HHhmm.csv







# Digital_Therapy_Baby - Baby Survey and Behavioral Dataset

## Seoul National University Developmental Cognitive Neuroscience Lab
PI: Sang Ah Lee

Sang-Eon Park, 
Jisu Chung



## 1. Overview
This repository contains de-identified survey and behavioral task data collected as part of a research study investigating emotional and attentional characteristics in children.

The dataset includes standardized questionnaire scores related to depression, anxiety, and ADHD symptoms, as well as raw task data files generated during experimental sessions.

---

## 2. Data Collection
Data were collected between YYYY and YYYY at [institution or region, if applicable] as part of a behavioral neuroscience study involving child participants.

Participants completed caregiver- and self-reported questionnaires and computerized behavioral tasks administered by trained experimenters.

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
- `depression`: CES-DC Score above 15 : 1
- `stai_ch`: STAI-CH total score
- `anxiety`: 43 > STAI-CH Score >= 39 : 1 / STAI-CH Score >= 43 : 2 
- `Parent`: Parent-report indicator (1: Father / 2: Mother)
- `k_ars`: Korean ADHD Rating Scale total score
- `adhd`: k-ars Score above 19 : 1
- `inattention`: k_ars Inattention subscale score
- `hyperactivity`: k_ars Hyperactivity subscale score

---

## 4. Survey Measures
- **CES-DC (Center for Epidemiological Studies Depression Scale for Children):**  
  Measures depressive symptoms in children. Higher scores indicate greater depressive symptom severity.

- **STAI-CH (State-Trait Anxiety Inventory for Children):**  
  Assesses anxiety levels in children. Higher scores indicate greater anxiety.

- **K-ARS (Korean ADHD Rating Scale):**  
  Evaluates ADHD-related behaviors. Higher scores indicate greater ADHD symptom severity.

---

## 5. Raw Data Structure

### /raw_data
This folder contains raw task data files generated during experimental sessions.

**File naming format:**
