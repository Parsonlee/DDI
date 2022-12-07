# CNN-Siam: Multimodal Siamese CNN-based deep learning approach for drug‒drug interaction prediction

*DDI.ipynb*: The code for the DDI task.  
*data.zip*: Contains event.db file, which includes 572 drugs with chemical substructure(smile form), targets, enzyme and pathways.  
*Ranger-Optimizer*: Ranger optimizer sourece codes for PyTorch.

About CNN-Siam: 
- Architecture: Siamese 1-Dimensional CNN
- Trick: 
  - Residual-connection, 
  - Ranger(RAdam+LookAhead), 
  - Mixup, 
  - Focal-loss, 
  - Sum embeddings of durg pair
- Hyperparameters: 
  - batch_size=256, 
  - lr=1e-3, 
  - weight_decay=1e-3, 
  - epochs=100, 
  - mixup_alpha=0.2, 
  - focal_gamma=2.0, 
  - Tmax=epochs