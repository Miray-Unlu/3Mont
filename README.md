The 3-Multi-omics integrative (3Mont) analyzes different levels of biological data (genes, proteins, methylation data, microRNAs, etc.) to obtain unique patterns within each subtype, phenotype or control/case status. 

These patterns provide us a deeper understanding of how each subtype operates at cellular level. This promising approach selects the potential features across biological data, groups them. The features like puzzle pieces functioning together are analyzed as a whole in the group.
The tool integrates various omics data by grouping them, upgrading to pro-groups and assigning scores to each pro-group using Feature importance scoring (FIS) component. 

Following that, constructing Machine Learning (ML) models based on the prominent pro-groups enables extracting promising biomarkers for distinguishing BRCA subtypes.
This approach empowers the users to analyze the collective behavior of features in each pro-group (biological groups) through ML methods. 

# Preparation of Biological Data

This workflow utilizes the KNIME Analytics Platform (https://www.knime.com/) to analyze data stored in  .table files. 
These files are a KNIME-specific format optimized for fast processing and efficient storage.

Data Structure:

- Rows: Represent individual samples, often identified by unique IDs.
- Columns: Represent features or characteristics measured for each sample.
- Last Column: Contains class labels, typically indicating control or case status.


# The 3Mont Workflow

 ![alt text](https://github.com/malikyousef/3Mont/blob/main/Images/Main_workflow.PNG?raw=true)

 # Key Feature Findings from 3Mont Analysis

When applied to BRCA molecular subtype datasets, 3Mont identifies distinct groups associated with the disease. This summary highlights the characteristics of the top 10 identified groups, including their associated genes.

3Mont offers a more comprehensive view of the results, allowing you to explore these groups from the perspective of miRNAs, CpGs, and genes.

 ![alt text](https://github.com/malikyousef/3Mont/blob/main/Images/Group_statistics.PNG?raw=true)
