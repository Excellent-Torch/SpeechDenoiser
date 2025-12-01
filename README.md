# SpeechDenoiser
According to the original author: 

"This's a simple and effective solution for real-time speech denoising using an ONNX model. This repository contains everything you need to get started with enhancing audio quality by reducing noise, making it perfect for improving voice recordings and live communication.

Supports 48kHz and 16kHz. The 48kHz model uses DeepFilterNet3, while the 16kHz model uses GTCRN. Both models are streaming, but the 48kHz model has higher real-time requirements. I believe that a Snapdragon 865 should be sufficient for real-time inference. The 16kHz model has lower real-time requirements, and I think the Raspberry Pi 4B might be capable. However, the 48kHz model takes raw audio as input, while the 16kHz model takes STFT features as input, which could make implementation on edge devices a bit more challenging."

$\color{Red}{\textsf{This is a fork from the original Author yuyun2000 for Testing Purposes or Enhancements if Applicable}}$
Original Repo 👉 <a href="https://github.com/yuyun2000/SpeechDenoiser">SpeechDenoiser</a> 
---
## References:

https://github.com/Xiaobin-Rong/gtcrn

https://github.com/Rikorose/DeepFilterNet

https://github.com/grazder/DeepFilterNet/tree/torchDF-changes

```
@inproceedings{schroeter2022deepfilternet,
  title={{DeepFilterNet}: A Low Complexity Speech Enhancement Framework for Full-Band Audio based on Deep Filtering}, 
  author = {Schröter, Hendrik and Escalante-B., Alberto N. and Rosenkranz, Tobias and Maier, Andreas},
  booktitle={ICASSP 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year={2022},
  organization={IEEE}
}
