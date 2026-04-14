We modified the YOLOv8n model by replacing standard convolutions in deep C2f bottleneck blocks (indices 6, 8, 12, 15, 18, 21) with SFS-Conv (Spatial-Frequency 
Selective Convolution), which splits channels into spatial (SPU with grouped residuals) and frequency (FPU with multi-scale/orientation FrGKConv Gabor kernels) 
streams, fused via CSU softmax weighting for noise-robust SAR features. Trained on the HRSID dataset (ship class, 640×640, 50 epochs), this preserved efficiency 
while synergizing local textures and edges. When trained from scratch for the same 50 epochs, the baseline YOLO achieved 86.9% accuracy, while the modified SFS-
YOLO achieved 88.4% accuracy, showing that the proposed model improved performance in complex maritime scenes.
