| Method | Metrics (Accuracy/F1/IoU) | Runtime_ms | Labels Needed | Interpretability |
| --- | --- | --- | --- | --- |
| Watershed | IoU=0.92, Dice=0.96 | 1.060 | None | High (transparent pipeline) |
| SVM | F1=0.99 | 409.873 | Region labels (≥50 total) | Medium–High (feature-based) |
| Random Forest | F1=1.00 | 15.408 | Region labels (≥50 total) | High (feature importances) |
| k-Means | Silhouette=0.29 | 91.599 | None (unsupervised) | Medium (cluster centers) |
| CNN | F1=0.99 | 445.862 | Patch labels (hundreds+), aug. | Lower (saliency/Grad-CAM) |
| U-Net | IoU=0.01, Dice=0.03 | 157.856 | Pixel masks (15–20 imgs), aug. | Medium (overlays/feature maps) |