# Cytokine Concentrations in blood following ex vivo LPS 0, 70, 200, or 600 (some samples are non-incubated baseline)  Data from Biorepository

**ORIGINAL DATA (02/2023)**
RAW DATA Excel File
https://github.com/LizbethMrtn/LPS/blob/main/cytokine_data_merged_project_9_15_RAW.xlsx

RAW Data Transformed (not imputed, NAs remain)
https://github.com/LizbethMrtn/LPS/blob/main/TransposeRAWCytokineData.xlsx

Updated DATA Excel File; Includes Imputed Data
https://github.com/LizbethMrtn/LPS/blob/main/cytokine_data_merged_project_9_15_USE.xlsx
https://github.com/LizbethMrtn/LPS/blob/main/1.25.24cytokine_data_merged_project_9_15.xlsx

Quality Control Data Organization (r); Kelleigh H.
https://github.com/LizbethMrtn/LPS/blob/main/1.30.24%20Cytokine%20QC%20Analysis.Rmd

**ORGANIZE AND TRANSFORM CYTOKINE DATA**
Transpose Cytokine Concentration Data
https://github.com/LizbethMrtn/LPS/blob/63411365fb5d661d37319677cd06cc8c7ad8311d/TransposeRAWCytokineData.xlsx

LN Transform Cytokine Data
https://github.com/LizbethMrtn/LPS/blob/57116961fc09259ef8fbf8d94c094569d1abfd57/02b_Transpose_LNTransformed_AllLPS.xlsx

**Separate Baseline Cytokine Data from LPS-Stimulated Cytokine Data**
Scale Cytokine Data & Create Composite Scores
https://github.com/LizbethMrtn/LPS/blob/ce24f30cf7d16b914ab6a027df03c98d70cb9c3a/03a_LNscale_BaselineCytokine.xlsx

**Organize CoVariate Data: Experimental, Biological, Lifestyle Factors, Mood Factors**
https://github.com/LizbethMrtn/LPS/blob/43755e7a1d1ed6d6768a16e6b880a1b711fc18b3/03b_Scaled_Composite_Cytokines
Experimental Variability:
* Subject
* Visit number
* Project (data come from subjects initially enrolled in projects 9, 10, and 15)
* LPS_DOSE: whether the sample was incubated (LPS_0) or not (Non_LPS)
* silanized_LPS: whether the vial used was silanized or not
* Plate: which plate was used to measure cytokines from this specific sample

Biological Factors:
* Gender (biological sex)
* BMI (averaged across all visits for a subject)
* PulseRate
* Diastolic BP
* Systolic BP
* Approx Age

Lifestyle Factors: Medications, Caffeine or Nicotine use on the day of blood collection

https://github.com/LizbethMrtn/LPS/blob/fcf757e5123085d753fa054cf8d9ff46b24d595f/04a%20Mood_All_Var.xlsx
https://github.com/LizbethMrtn/LPS/blob/026bd399392bda6c6c5bae39dca5f293d2867df1/04b%20Mood_Factors_na.rm.xlsx

Mood Data: Individual items from GAD7; ISI; MASQ; PHQ9, PCL5_month, PHQ15
Sorted into 8 mood factors: 
* PTSD (19 variables from pcl5); 
* Positive Affect (high score = less positive affect; more symptomatic; includes 14 variables from MASQ)
* Sleep-Related Symptoms (includes 12 measures of sleep quality from a combination of PHQ15, PHQ9, PCL5, and ISI)
* Anxiety (includes 9 variables total: 7 from GAD7 and two from PHQ9)
* Anhedonia (7 variables from MASQ)
* Somatic Anxiety (includes: health9_heart; health8_faint, health7_dizzy, health6_chest)
* Suicideal Ideation (includes: dep2_down; dep9_dead, and MAS122_suicide)
* GI-Related Symptoms (includes: health12_constipation, health1_stomach, and health13_nausea)

**BaselineCytokineData with all covariates and mood factors**
https://github.com/LizbethMrtn/LPS/blob/78f2d66f98b68ffde563910b2694a4925a9b09a5/05a%20LNscale_Baseline_AllCoVars.xlsx

https://github.com/LizbethMrtn/LPS/blob/7f0482513497f43cc8246e6688e6f2a6aaf4b0d3/05b_FIGURES_BaselineCytokinesMoodData

**Linear Mixed Effects Regression with Baseline Cytokine Data**
https://github.com/LizbethMrtn/LPS/blob/7f0482513497f43cc8246e6688e6f2a6aaf4b0d3/06a_BaselineIFN_gammaLMER

https://github.com/LizbethMrtn/LPS/blob/7f0482513497f43cc8246e6688e6f2a6aaf4b0d3/06b_BaselineIL10_LMER

https://github.com/LizbethMrtn/LPS/blob/7f0482513497f43cc8246e6688e6f2a6aaf4b0d3/06c_Baseline_ML1_LMER

https://github.com/LizbethMrtn/LPS/blob/7f0482513497f43cc8246e6688e6f2a6aaf4b0d3/06d_Baseline_ML2_LMER


  

