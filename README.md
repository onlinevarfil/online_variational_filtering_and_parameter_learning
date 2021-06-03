##  Variational Filtering

To run phi learning on linear gaussian (Fig1a)
```
python linear_gaussian_phi_learning.py
```
To run phi and theta learning on linear gaussian (Fig1b)
```
python linear_gaussian_model_learning.py
```
To run CTRNN experiment
```
python CTRNN_run_with_hydra.py
```
To run sequential VAE experiment
```
python dmlab.py
```

# Dependencies
    - pytorch
    - hydra (for hyperparameter config) https://github.com/facebookresearch/hydra
    - scipy
    - tqdm
