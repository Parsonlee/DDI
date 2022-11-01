# DDI

- Architecture: SiameseCNN
- Trick: Residual-connection, Ranger(RAdam+LookAhead), Mixup, Focal-loss, Sum embeddings of durg pair
- Hyperparameters: batch_size=256, lr=1e-3, weight_decay=1e-3, epochs=100, mixup_alpha=0.2, focal_gamma=2.0, Tmax=epochs