# Graduation project Repo 
## ECE595 graduation project spring 2021.
=====================================================================================
- __Name:__ __Ahmed Gamal Abouelfadl Hassan AHmed__
- __std,no:__ o827619008
=========================================================================================
Name Entity matching is a classical challenge for data integration and find similar enities within two differnt data sources. 
the process for Entity matching stars with.

- 1- two differnt data sources,
- 2- Data preprocessing.
- 3- Blocking.
- 4- pairs comparison.
- 5- classification. 


================================================
In this project we will explore the final part of the process classification part and leave the first part as future work 
=================================================
We will try XLnet and 3 other variations of BERT to to exceed the penchmark of the other methods by propsing simpler and more feasable approach 
the reuslts were impressive regarding BERT varation although XLnet needs further research to adapt this task 
===============================================
 F1 Score | MG | DM | Ditto | Ours Best convbert | XLnet | Albert | DistilBert
 ---|---|---|---|---|---|---|---|
structured[google amazon] | 49.1 | 70.7 | 75.7 | 89.5 | 66.66 | 69.767 | 87.18
---|---|---|---|---|---|---|---|
textual [abt-buy] | 43.6 | 62.8 | 89.33 | 75.3 | 75.7 | 68.57 | 76.02
---|---|---|---|---|---|---|---|---|
dirty [walmart-amazon] | 37.4 | 53.8 | 85.69 | 91.16 | 69 | 69.4 | 83.24

