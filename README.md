# Adversial-Point-Cloud
### For FGSM attack on point net 
```cd PointNet/``` <br/>
```python3 fgsm_attack.py ``` <br/>
Run the python notebook ```pointnet_fgsm.ipynb```

### For running Saliency Map/FGSM on DGCNN
```cd DGCNN/``` <br/>
```python saurabh_dgcnn.py --exp_name=cls_1024_eval --eval=True --model_path=model.cls.1024.t7 --attack_type='jsma' --alpha=1 --kl=5 --num_drop=300```

