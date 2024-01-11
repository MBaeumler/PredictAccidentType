# Predicting the type of road traffic accident for test scenario generation 
Code to predict the type of road traffic accident (turning) in police accident data.  
List of all turning accident types (page 11): https://www.udv.de/resource/blob/80022/89b4d80028aacf8cab649d3a3c6157a0/unfalltypenkatalog-data.pdf 

## Abstract
Automated driving systems should be able to avoid road traffic accidents and drive more safely than human drivers do. Test scenarios derived from real-world data such as police accident data can help assess the safety performance of automated driving systems. In many countries, police collect data and information about nearly every accident, resulting in a representative sample. However, the collected accident data often do not contain the exact conflicts that cause an accident. Therefore, we estimated the globally known three-digit accident type for German police accident data, describing accident-causing conflicts. The data supplemented by the estimated three-digit accident type can then be used in subsequent test scenario generation. Accordingly, this study presents the first classification model for predicting 30 types of turning accidents. We tested a CatBoost model and a large-language model called BERT, using different feature sets and model designs. Overall, the CatBoost model performed best when using accident descriptions and non-text features, such as collision type. Anomaly detection performed before model training revealed additional knowledge-driven miscoding in the police data collection. In conclusion, the model can predict common accident types, such as a left-turn with an oncoming straight-ahead driver. In contrast, the model fails to predict rare accident types, such as a left-turn (with a lit arrow sign) with oncoming traffic. Future studies should focus on optimizing the developed model and handling data imbalance.  

## Early pre-print
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4295798

## Reference 
Please cite the pre-print. 
