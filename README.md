You  can use this code to train the model.
```
!python train.py --batch_size 16 --train_annotation './train_data_13536.json' --attack 'pgd' --loss 'focal_loss'
```

And you can use this code to calculate f1 score.
```
!python f1.py --test_annotation './test_data_179.json' --ckpt_file "your path"
```
