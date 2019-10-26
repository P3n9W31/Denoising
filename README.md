# Denosing
![](https://img.shields.io/github/license/P3n9W31/Denoising?style=flat-square)

Image denosing with Convolutional neural network.

## Network
```
DnCNN(
  (dncnn): Sequential(
    (0): Conv2d(3, 10, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
    (1): ReLU(inplace=True)
    (2): Conv2d(10, 10, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
    (3): ReLU(inplace=True)
    (4): Conv2d(10, 10, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
    (5): ReLU(inplace=True)
    (6): Conv2d(10, 10, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
    (7): ReLU(inplace=True)
    (8): Conv2d(10, 3, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  )
)
```

## Result

![](https://github.com/P3n9W31/Denoising/blob/master/figures/0.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/1.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/2.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/3.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/4.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/5.png)

![](https://github.com/P3n9W31/Denoising/blob/master/figures/6.png)

## License
MIT


