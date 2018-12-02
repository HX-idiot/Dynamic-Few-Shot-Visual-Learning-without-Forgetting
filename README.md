# Dynamic-Few-Shot-Visual-Learning-without-Forgetting

pytorch simple implement for the CVPR 2018 paper [Dynamic Few Shot Visual Learning without Forgetting](https://arxiv.org/abs/1804.09458) in jupyter version.


### Set up the  dataset

 download the MiniImagenet dataset from [here](https://mega.nz/#!rx0wGQyS!96sFlAr6yyv-9QQPCm5OBFbOm4XSD0t-HlmGaT5GaiE) and modify the data root.

### Train the model

* Step 1 refers to pretrain Feature Extractor and cosine-based Classifier. In this process I set the epoch_num to 30. 
* Step 2 refers to continue train Classifier and attention-based Few-shot Weight Generatoe

### Evaluate

* We get similar result as published in paper.
