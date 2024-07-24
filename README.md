# Write-off Control Analysis using Association Rule Mining

Applied association rule mining to enhance fraud detection and ensure compliance with financial control policies in the write-off process.

### Key features: 
Roles of individuals (clerks, managers, financial controllers) involved in sign-offs, transaction amounts, and dates.

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

### Investigated flagged transactions to ensure adherence to policy:
For amounts >$5,000: Required one clerk, one manager, and one financial controller.
For amounts ≤$5,000: Required two clerks and one manager or one clerk and two managers.

### Enhancing Controls and Compliance:
Strengthened internal controls and monitoring systems to flag unusual patterns in real-time.

## Snippet

![Example Image](https://github.com/DarshiniKrishna/Audit-Analysis-Using-Association-Rule-Mining/blob/e23a2ebe7526ec943bf94bf4357ed0d411ead0b7/association%20rule_audit%20writeoff.png)

# Audit Analysis Using Association Rule Mining

## Snippet 

![Example Image](https://github.com/DarshiniKrishna/Audit-Analysis-Using-Association-Rule-Mining/blob/676bd761bb9fa52c6fd073fbd40f0123f7bb0fb9/association%20rule_use%20cases.png)
