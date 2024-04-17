**SENG 637- Dependability and Reliability of Software Systems***

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction

# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 
For the second segment of our laboratory investigation, the RDC-11 worksheet and Macros were instrumental in processing and analyzing the provided failure data. Prior to plotting, essential calculations were executed, including the determination of cumulative failures and the time intervals between each failure. We assumed a uniform distribution of failures for this analysis, a standard practice in such assessments. The intricacies of these calculations are documented in the "Pre-Processing Raw Data" file.

In establishing the risk profile, key parameters were defined as follows:
| Parameter | Value |
|------------|-----------|
|Discrimination Ratio | 2 | 
|Developer's Risk | 0.05 | 
| User's Risk | 0.05 | 

The Mean Time to Failure (MTTF) values were derived using the formula: T/FC or 1/FIO.

The initial plot was generated using an MTTF of 0.3, which was determined based on a Failure Intervals Observation (FIO) of 90 failures within 31 intervals. Notably, this setting resulted in the majority of the graph falling within the reject zone, indicating suboptimal performance.

[Add Image]

Subsequently, the plot was recalibrated with an MTTFmin of 0.046, calculated from a dataset of 675 failures observed across 31 intervals.

[]Add Image]

Finally, the graph was refined further with an MTTF of 2*MTTFmin, equating to 0.092. This adjustment was derived from an analysis of 337.5 failures observed over the same 31 intervals. Despite these modifications, the majority of instances remained either within the realm of continuous testing or the reject zone, suggesting ongoing challenges in achieving desired reliability levels.

[Add Image]


# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
