# keras_srcnn

### Overview
I created Super Resolution with Convolutional Neural networks(SRCNN) using python and keras.

### Experiment environment
- OS : Windows 10
- CPU : AMD Ryzen 5 3500 6-Core Processor 8GB
- GPU : NVIDIA GeForce RTX 2060 SUPER

### How to use
1. Create new folders which are `./train_data` and `./test_data`
   
   Storage train data in `./train_data` and test data in `./test_data`
2. Learning
```
main.py --mode srcnn
```
3. Evaluate
```
main.py --mode evaluate
```
### Result example
#### High Image
![High Image](result/high_0.jpg)

#### Low Image PSNR:36.46dB
![Low Image](result/low_0.jpg)
#### Pred Image PSNR:37.29dB
![Pred Image](result/pred_0.jpg)
