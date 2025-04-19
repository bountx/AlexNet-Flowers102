# AlexNet on 102 Category Flower Dataset
Code includes whole assignment and process of hypertuning the AlexNet in comparison to basic convolutional network.

**[Oxford 102 Flower Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)**

## What was the process?
- Testing basic CNN's
- Testing baseline AlexNet
- SGD vs Adam optimizer comparison
- Simplified hyperparameters grid search with early stopping mechanism
- Data augmentation

## Weights and biases reports
- [Report 1: Learning rates](https://wandb.ai/andrzej-pijanowski-uniwroc/flowers102-classification/reports/Report-1-Learning-rates--VmlldzoxMjMzOTI0NA?accessToken=dfcu97gwx5fbd1a9jhoi5vhaqmx6tuiej7sditc4051xict59v2smnenc8nx6zhr)
- [Report 2: Dropout rates](https://wandb.ai/andrzej-pijanowski-uniwroc/flowers102-classification/reports/Report-2-Dropout-rates--VmlldzoxMjM3MTg4MA?accessToken=bjdjeywzvmcug9n6pmh8dkra5nqcmz5c9b0wn0ui4e8oyb14h8t90q0m7au9qnsp)
- [Report 3: Weight decay](https://wandb.ai/andrzej-pijanowski-uniwroc/flowers102-classification/reports/Report-3-Weight-decay--VmlldzoxMjM3NTEwMw?accessToken=6dojuooxtack34nuocuxd3tlnpihvsi72ook9y80i8wquvo5lnlfry99ir1k5tpv)
- [Report 4: Data augmentation](https://wandb.ai/andrzej-pijanowski-uniwroc/flowers102-classification/reports/Report-4-Data-augmentation---VmlldzoxMjM3NTgyNA)

## Final results on test dataset
- **AlexNet: 51.97% accuracy (manually stopped after 100 epochs)**
- **Simple CNN: 20.81% accuracy**
![final_results](https://github.com/bountx/AlexNet-Flowers102/blob/main/Images/final_results.png?raw=true)
