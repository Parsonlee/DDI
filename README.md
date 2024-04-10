# CNN-Siam: Multimodal Siamese CNN-based deep learning approach for drug‒drug interaction prediction

_DDI.ipynb_: The code for the DDI task.  
_data.zip_: Contains event.db file, which includes 572 drugs with chemical substructure(smile form), targets, enzyme and pathways.  
_Ranger-Optimizer_: Ranger optimizer sourece codes for PyTorch.

About CNN-Siam:

- Architecture: Siamese 1-Dimensional CNN

- Trick:

  - Residual-connection,
  - Ranger(RAdam+LookAhead),
  - Mixup,
  - Focal-loss,
  - Sum embeddings of a pair of drug

- Hyperparameters:

  - batch_size=256,
  - lr=1e-3,
  - weight_decay=1e-3,
  - epochs=30,
  - mixup_alpha=0.2,
  - focal_gamma=2.0,
  - Tmax=epochs
