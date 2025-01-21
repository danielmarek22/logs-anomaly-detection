# logs-anomaly-detection
Anomaly detection for suspicious server logs.

This repository contains my solution for the Roaring Success hackathon organised by ING. It is a simple SQL Log Anomaly Detection with DBSCAN and Sentence-BERT. Unfortunately this solution does not take into account the timestamp of a log, but it detects SQL-Injection and other suspicious activity. 

# Usage

Run the script with the following command:

```
python detect_anomalies.py <log_file_path> <output_file_path>
```

Arguments:

- log_file_path: Path to the CSV log file to process.
- output_file_path: Path to save the detected anomalies (Excel format).

Example:

```
python detect_anomalies.py logs.csv anomalies.xlsx
```

