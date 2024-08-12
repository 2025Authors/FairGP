FairGP 

see 
```
./run.sh
```

or

```
python run_models.py --gpu 0 --dataset "credit" --model "FairGP" --n_patch 50 --num_hidden 64 --nlayer 1 --nheads 2 --sens_attr region --pe_dim 2 --feat_norm "row" --label_number 6000 --metric 4
```


Note that pokec_z, pokec_n, and aminer_l are too large, please see the URL:

[pokec_z and pokec_n](https://github.com/EnyanDai/FairGNN/tree/main/dataset/pokec)
[aminer_l](https://drive.google.com/file/d/1wYb0wP8XgWsAhGPt_o3fpMZDM-yIATFQ/view)

download them in the data folder and rename the file according to the load_fair_dataset function.
