## Prerequisites
- Python >= 3.6
- PyTorch == 2.1.0
- numpy 1.24.4
- tqdm
## data preparation
unzip datasets book_data.zip; gowalla_data.zip; rocket_data.zip in data/data

## TRAIN AND TEST of the proposed methods.
```python
DMIAFRec:  python main.py --data_name=rocket --mode=DMIAFRec --contrastive_ratio=0.1 --n_facets=10 --ra_loss=0.01 --time_decay=0.3

```


