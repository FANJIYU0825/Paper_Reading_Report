# Paper_Reading_Report
My name is CHI YU. The repo is my paper reading report.
## 1. Open-Domain Aspect-Opinion Co-Mining with Double-Layer Span Extraction (KDD 2022)
![img](fig/ODAO.jpg)
### Introduction
1. Using the rule-based parser tree to label where Aspect & Opinion spans are possible in a sentence
2. Aspect & Opinion Extraction uses the two-layer 
3. First layer only extract a single Aspect or Opinion
4. Second layer extract the pair of Aspect & Opinion
5. Use the first and second layer for cross-validation
6. Loss is the cross Entropy, & Calculate correlation with each of the model outputs
7. Self-train: Use the train data that is predicted correctly (in four models)

## 3. PromptDA: Label-guided Data Augmentation for Prompt-based Few-Shot Learners
![img](fig/PromptDA_Label.jpg)
