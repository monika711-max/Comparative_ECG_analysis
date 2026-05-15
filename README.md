# Comparative_ECG_analysis
# Comparative ECG Feature Analysis

This project explores ECG-derived physiological features using records from the publicly available MIT-BIH Arrhythmia Database.

Using Python libraries such as WFDB, NeuroKit2, Pandas, and Plotly, I processed ECG signals from selected male and female subjects with relatively stable sinus rhythms and extracted features such as:

* BPM (heart rate)
* Mean RR interval
* RR variability
* Mean R-wave amplitude

After comparing average values across the selected groups, I observed that BPM and mean RR interval values were relatively similar, while RR variability and mean R-wave amplitude showed more noticeable differences within the sampled records.

This project was exploratory in nature and helped me better understand:

* ECG signal processing
* R-peak detection
* Feature extraction
* Biomedical data analysis workflows
* Physiological signal visualization

Working on this project also made me more interested in how physiological differences can influence biomedical analysis and healthcare research.

## Tools & Libraries Used

* Python
* WFDB
* NeuroKit2
* Pandas
* NumPy
* Plotly

## Dataset

MIT-BIH Arrhythmia Database:
https://physionet.org/content/mitdb/

## Note

The MIT-BIH dataset contains arrhythmia patients and individuals with varying cardiac conditions. Therefore, this analysis should be interpreted as exploratory rather than representative of the general population.
