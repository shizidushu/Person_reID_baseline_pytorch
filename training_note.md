## 训练

```bash
# prepare data
python prepare.py
# training
python train.py --gpu_ids 0 --name ft_ResNet50 --train_all --batchsize 32  --data_dir /mnt/d/0-Datasets/public/Person-Re-Identification-Datasets/Market-1501-v15.09.15/pytorch
# test
python test.py --gpu_ids 0 --name ft_ResNet50 --test_dir /mnt/d/0-Datasets/public/Person-Re-Identification-Datasets/Market-1501-v15.09.15/pytorch  --batchsize 32 --which_epoch 060
```

