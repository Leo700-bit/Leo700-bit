# Leo700-bit

Computer vision · Machine learning · Control systems

I build experiments around visual recognition, image reconstruction, and feedback control.

## Featured project

### Video gesture recognition with CNN + Transformer

![Gesture recognition pipeline: sample 12 RGB frames, encode each frame with MobileNetV3-Small, and classify the sequence with a temporal Transformer.](assets/gesture-pipeline.png)

I built a PyTorch pipeline for four dynamic gestures and evaluated it on people held out from training. The project compares a temporal Transformer with mean-pooled CNN features and a wrist-motion baseline, then tests whether shuffling frames changes predictions.

[Explore the architecture and results →](projects/gesture-recognition.md)

## Other project areas

| Area | Project work |
| --- | --- |
| Image restoration | Compared FFT-based Tikhonov regularization with anisotropic total variation solved by ADMM for image deblurring. |
| Control systems | Worked with quadcopter–pendulum models and waypoint-tracking simulations in MATLAB and Simulink. |
