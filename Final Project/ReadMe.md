
# Deep Neural Network Based Image Compression Encoders
Lossy image compression has become a rising topic in the
community especially after deep learning is applied to it. As
proved by Strumpler et al [13], building robust DNN based
image compression encoders without needing modification
on the decoder end i.e. encoders that work with traditional
JPEG decoders is now a reality. We try to improve this work
with our contributions: 1. Implement MS-SSIM in the original loss function and experiment on optimal parameters. 2.
Replace VGG in the original network with ResNet. 3. Analyze inference time and influence of training steps. 4. Add
LSTM into the attention network.
