# InterpretML
Démonstration Azure InterpretML

https://github.com/Microsoft/interpret

InterpretML is an open-source python package for training interpretable models and explaining blackbox systems. 
Interpretability is essential for:
- Model debugging - Why did my model make this mistake?
- Detecting bias - Does my model discriminate?
- Human-AI cooperation - How can I understand and trust the model's decisions?
- Regulatory compliance - Does my model satisfy legal requirements?
- High-risk applications - Healthcare, finance, judicial, ...

Historically, the most intelligible models were not very accurate, and the most accurate models were not intelligible. 
Microsoft Research has developed an algorithm called the Explainable Boosting Machine (EBM)* which has both high accuracy and 
intelligibility. 

EBM uses modern machine learning techniques like bagging and boosting to breathe new life into traditional 
GAMs (Generalized Additive Models). 
This makes them as accurate as random forests and gradient boosted trees, and also enhances their intelligibility and editability.

In addition to EBM, InterpretML also supports methods like LIME, SHAP, linear models, partial dependence, decision trees, and rule lists. 
The package makes it easy to compare and contrast models to find the best one for your needs.


Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
