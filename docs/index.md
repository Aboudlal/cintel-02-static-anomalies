# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
I used a pediatric clinic dataset stored in CSV format. Each row includes age in years and height in inches.

### Signals
I used the original signals `age_years` and `height_inches`. I also added a new column called `anomaly_type` to explain whether the anomaly was caused by age or height.

### Experiments
I modified the pipeline by adding a derived output column called `anomaly_type` while keeping the original anomaly detection logic.

### Results
The updated pipeline ran successfully and created an anomalies file with an additional column showing the reason for each anomaly.

### Interpretation
This modification improved the interpretability of the anomaly report by showing whether each anomaly was related to age or height.
