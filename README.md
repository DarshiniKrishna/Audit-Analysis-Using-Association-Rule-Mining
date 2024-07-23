# Audit-Analysis-Using-Association-Rule-Mining

Applied association rule mining to enhance fraud detection and ensure compliance with financial control policies in the write-off process.

### Key features: 
Roles of individuals involved in sign-offs ((clerks, managers, financial controllers), transaction amounts, dates.

## Applying Association Rule Mining:
### Group Data: 
Identified frequent transaction groups (e.g., specific clerks and managers in high-value write-offs).

### Measure Strength:
Support: Proportion of transactions with specific sign-off combinations.
Confidence: Likelihood of a write-off given specific individuals' involvement.
Lift: Frequency of the combination occurring compared to random chance.

### Identifying Irregularities:
Detected high-support, high-confidence, and high-lift patterns, indicating strong associations between certain individuals and write-offs.
Notable finding: Frequent high-value write-offs authorized by the same combination of clerks and managers, suggesting potential collusion.
Review and Investigation:

### Investigated flagged transactions to ensure adherence to policy:
For amounts >$5,000: Required one clerk, one manager, and one financial controller.
For amounts ≤$5,000: Required two clerks and one manager or one clerk and two managers.

### Enhancing Controls and Compliance:
Strengthened internal controls and monitoring systems to flag unusual patterns in real-time.

## Snippet

![Example Image](https://github.com/DarshiniKrishna/Audit-Analysis-Using-Association-Rule-Mining/blob/e23a2ebe7526ec943bf94bf4357ed0d411ead0b7/association%20rule_audit%20writeoff.png)
