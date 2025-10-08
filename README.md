# Residential Fire Accident Reports Dataset for Severity Prediction

This dataset contains 343 records of residential fire accidents in China, compiled and processed for data-driven risk analysis and accident severity prediction. The data is derived from official accident investigation reports and has been structured to facilitate machine learning research in the field of safety science.

This dataset was used in the study: "Predicting Fire Accident Severity through Semantic Analysis of Investigation Reports."

## About the Dataset

The data is a curated subset of the larger Fire Accident Report (FIREAR) corpus, which comprises over 2,000 publicly available fire accident investigation reports from various levels of Emergency Management Departments in China between 2015 and 2025. 

For this specific dataset, we performed the following processing steps:
1.  **Filtering**: We filtered the main corpus to isolate 343 reports specifically related to "residential fires."
2.  **Information Extraction**: Key information such as casualties, economic loss, and the full "accident cause analysis" text was extracted from each voluminous raw report.
3.  **Severity Labeling**: Each of the 343 accidents was labeled with a severity level (0: General, 1: Larger, 2: Major) according to Chinese national standards, based on the number of fatalities, injuries, and direct economic loss.
4.  **Risk Factor Engineering**: The "accident cause analysis" text was processed using a semantic chunking method to identify the presence or absence of 11 key risk factors. These are represented as binary flags (1 for present, 0 for absent).
