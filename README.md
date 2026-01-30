**NEW UPDATE:** After working on the data augmentation and through litterature, I learned that lung cancer was in many different places in the CT-scans. However, my previous data augmentation function didn't take into account the fact that the "crucial image point" wasn't necessarily in the final putput (due to scaling, rotations etc...). After reducing the weights of data augmentation variables the results were amazing: going from a **85.56% accuracy to a 93.02% accuracy**. 

**NOTE:** Though I've finished the "algorithm aspect" of this project, I am currently working on markdown cells explaining *methodology, hypothesis, and medical context*. There will also be a conclusion on the *clinical implications* and *false positive/negative analysis*, however I would like to present the results to my research mentor beforehand. (Expected Finish: Before the 31st of January)

Note that the results are "low" as this DL algorithm tries to predict the type of lung cancer, and not predict *if* the patient has lung-cancer. (See Confusion Matrix to understand the results better) 

I'm currently working on an improved fine-tuned model using EfficientNetV2-L architecture. Based on the current results I believe the metrics will exceed the current ones on this repo (Expected Finish: Before the 31st of January)

Personal Note: This computer vision project fascinated me all along. 
From fine-tuning the EfficientNet-based model to modifying class weights to deal with data imbalances in the lung cancer dataset, it was truly fascinating.
