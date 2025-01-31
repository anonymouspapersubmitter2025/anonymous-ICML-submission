# Organization: 

bbhFiles - Contains subdirectory for each task in BBH as well as the json files containing the questions. Each subdirectory contains the sampled LLM responses and problem information (such as graph, reasons post embedding etc..)

humanEval - Contains the spreadsheets for the correlation analysis. Three stages analyzed: pre-embed, post-embed  c_ij as well as q_ij.

# Hyperparameters:

Hyperparameters used for the main results (Figure 2): 
```
{'linearSensitivity': 3.5341, 'threshParam': 2.4602, 'riskParam': 0.3890, 'weight': 2}
```
Hyperparameters used for correlation study (Appendix C)
```
{'linearSensitivity': 53.1543, 'threshParam': -1.9090, 'riskParam': 1.3713, 'weight': 2}
```

