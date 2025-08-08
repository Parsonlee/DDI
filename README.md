# CNN-Siam: Multimodal Siamese CNN-based deep learning approach for drug‒drug interaction prediction

- `DDI.ipynb`: The code for DDI prediction task.  
- `/Ranger-Optimizer`: Ranger optimizer sourece codes for PyTorch.  
- `/data`: Contains `event.db` file, which includes 572 drugs with chemical substructure(smile form), targets, enzyme and pathways.  

## About CNN-Siam:

- **Architecture**: Siamese 1-Dimensional CNN

- **Trick**:

  - Residual-connection,
  - Ranger(RAdam+LookAhead),
  - Mixup,
  - Focal-loss,
  - Sum embeddings of a pair of drug

- **Hyperparameters**:

  - batch_size=256,
  - lr=1e-3,
  - weight_decay=1e-3,
  - epochs=30,
  - mixup_alpha=0.2,
  - focal_gamma=2.0,
  - Tmax=epochs
