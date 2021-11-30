# NJUSE-AutomatedTest


南京大学软件学院2021秋《自动化测试》课程 工具复现大作业


论文：Adversarial Policy Gradient for Deep Learning Image Augmentation

## 1. 运行环境

   - Python 3.8

   - PyTorch 1.0+

   - Torchvision

   - Numpy

   - Pandas

   - Tqdm

   - Fire

## 2. 数据集

   - 下载 [MURA](https://stanfordmlgroup.github.io/competitions/mura/) 数据集
   - 将数据集放置在 `./dataset`

## 3. 运行

   训练某个身体部位的所有模型 (以elbow为例):

   ```shell
   python apga_mura.py --seed 88 --body-part elbow --n-runs 1 --gpu-id 0 --train-cutout 1 --train-apga 1 --train-gradcam 1 --train-end2end 1
   ```

## 4.运行视频与ppt

见report文件夹
