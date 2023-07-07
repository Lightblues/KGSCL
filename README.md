# KGSCL
Offical repository for paper: Knowledge-Guided Semantically Consistent Contrastive Learning for Sequential Recommendation.

## Datasets
In our experiments, the Toys, Grocery, Home and Sports datasets are from http://jmcauley.ucsd.edu/data/amazon/. The interaction data is generated from user review records, and the substitute and complementary relations are extracted from item mata data.
## Quick Start
You can run KGSCL with the following code:
```
python runKGSCL.py --dataset toys --train_batch 512 --lamda1 0.1 --lamda2 1.0 --insert_ratio 0.2 --substitute_ratio 0.7
```
