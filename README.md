# FCAE-AD
The code in this repository implements the "FCAE-AD: Full Convolutional Autoencoder Based on Attention Gate for Hyperspectral Anomaly Detection".

We run this code with python 3.9, torch==2.4.0, and CUDA==11.8.

Please kindly cite our paper if this code is useful and helpful for your research. If you have any questions, please contact us at 3038808894@qq.com.

Wang X, Wang Y, Mu Z, Wang M, "FCAE-AD: Full convolutional autoencoder based on attention gate for hyperspectral anomaly detection," in Remote Sensing, 2023, doi:10.3390/rs15174263.

If you encounter any bugs while using this code, please do not hesitate to contact us.

The code in this article is divided into two parts. Firstly, you need to run the AD_main. py script in the FCAE file to generate differential image. Then, run the xxx_detection.mat file generated in the previous step in the main of the FP file to obtain the final detection result.
