# R-BERT
Implementation of R-BERT (Wu et al. 2019) model from the paper [Enriching Pre-trained Language Model with Entity Information for Relation Classification](https://arxiv.org/pdf/1905.08284.pdf)

This implementation requires tensorflow 1.14 to be able to run properly.

### Model architecture:

![](https://cdn1.imggmi.com/uploads/2019/9/13/6f114ba19c2e296046a023311ef754c4-full.png)

For more details about the model, please refer to the paper.

### Hyper-parameters

| Parameter  |  Value |
|---|---|
| batch size  |  16 |
| Max sentence length  |  128 |
|  Adam learning rate |  2e-5 |
|  Number of epochs |  5 |
|  Dropout rate |  0.1 |


### Performance
I have reviewed the paper for few times and tried to implement the model as close as possible to the paper but the result I got is far below the result reported in the paper:
* This implementation: **88.19** F1 score
* Reported by the paper: **89.25** F1 score

So I guess I made some mistakes here. Any comments, pull requests are welcomed.
