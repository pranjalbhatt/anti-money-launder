# Scotiabank Anti-Money Laundering Competition 
This is part of UofT AI Competition by Scotibank. 

## Literature Review
Anti-Money Laundering is a problem which is being tackeled with state of the art models in AI and Machine Learning. Research for the model development has been hightened with recent advances in supervised and unsupervised leanrings. 

Research Papers: 

[Detecting money laundering transactions with machine learning](https://www.emerald.com/insight/content/doi/10.1108/JMLC-07-2019-0055/full/html): This paper provides a model to identify the transaction to be mannually investigated. The data used are three kinds: 
- “normal” legal transactions;
- those flagged as suspicious by the bank’s internal alert system;
- potential money laundering cases reported to the authorities

How AI and Machine Learning Help Prevent Money Laundering? 
[Machine learning techniques for anti-money laundering (AML) solutions in suspicious transaction detection: a review](https://link.springer.com/article/10.1007/s10115-017-1144-z): This paper provides a review of machine learning algorithms and methods applied to detect suspicious transactions. It also provides the initial phase of data preparation and analytics.
Deep learning based models are relevant for us. 


[AML blog for features] (https://towardsdatascience.com/the-art-of-engineering-features-for-a-strong-machine-learning-model-a47a876e654c:
Look for velocity change feature

[Review on DS techniques used for AML](https://ieeexplore.ieee.org/abstract/document/7881560?casa_token=-dfSYU_sPAwAAAAA:rYkfKdzR1fttvZOyOKkDJ2KTttcCb6gbIGK5XSnP2PBAQczCHM3ShhsufHdu5cwm-yOMn8bZ)
Models:  Decision trees, SVMs, ANNs, PNNs, and BBNs

[Scotiabank's director's interview on AML ](https://www.mckinsey.de/~/media/McKinsey/Business%20Functions/Risk/Our%20Insights/Scotiabanks%20chief%20risk%20officer%20on%20the%20state%20of%20anti%20money%20laundering/Scotiabanks-chief-risk-officer-on-the-state-of-anti-money-laundering.pdf)

 [Application of Data Mining for Anti-money Laundering Detection: A Case Study] (https://ieeexplore.ieee.org/abstract/document/5693349?casa_token=Vbc9KThheXMAAAAA:xH_PHZkHArkwE0eD_eUmXe-U4kzwVoVuoU1aYl6ReutN4wPNbK8YEZ8KduNkJILvvXV4BLj6)
 Genetic Algorithm + MLP (to improve weight learning time) -- check references on clustering + MLP combination (reference 14)

https://ieeexplore.ieee.org/abstract/document/4635778?casa_token=QDU23-FaYNgAAAAA:vyxO-T8oJ-YIADTmbqdoenPCROtk4uRto_JsTiOb284ah-oePq2A_jN5RlUEweBDuHHJiELx

### Resources
- [H2O.ai Meetup: Detecting Money Laundering Networks Using Machine Learning](https://www.youtube.com/watch?v=Cl-dCqHiYfg&ab_channel=H2O.ai): using H2O.ai binary classifier
- [Slideshare report on AML using ML](https://www.slideshare.net/NaveenGrover6/using-machine-learning-in-anti-money-laundering-part-2-91819781) 
- 

## Ideas for Implementation 

### Flags / Metric for AML
For tracking many small transactions, using In-Out Amount and counts

### Unsupervised Learning Techniques
for unlabelled data in big folder, exploration of unsupervised techniques, GMM, clustering, ... 

### From Supervised data to predict unsupervised 
Supervsed algorithms for 3 classes

- Multi-class classification: F1 score (for binary to multi-class classification) 






