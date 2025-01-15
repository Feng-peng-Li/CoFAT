# Source code of Core Feature-aware Adversarial Training (CoFAT)

Pytorch==1.12.1

kornia


# train CIFAR-10 and CIFAR-100 with ResNet-18 without core partners

```
python train.py --arch ResNet18 --data CIFAR10
```

```
python train.py --arch ResNet18 --data CIFAR100
```

# train CIFAR-10 and CIFAR-100 with ResNet-18 with core partners

```
python train_co.py --arch ResNet18 --data CIFAR10
```

```
python train_co.py --arch ResNet18 --data CIFAR100
```


# train_tiny for AT on Tiny-ImageNet with ResNet-18

```
python train_tiny.py --arch ResNet18
```
