This repository contains the code for PID-Based Approach to Adversarial Attacks.


Requirements

- Python 3.6.5
- Tensorflow 1.12.0 
- Numpy 1.15.4 
- cv2 3.4.2

Running the code


 python nid_fgsm.py:  generate adversarial examples for Inception_V3 using NID-FGSM.
 
 
 python si_ti_di_nid_fgsm.py:  generate adversarial examples for Inception_V3 using SI-TI-DI-NID-FGSM.


Models

Inception_V3 
http://download.tensorflow.org/models/inception_v3_2016_08_28.tar.gz

Inception_V4 
http://download.tensorflow.org/models/inception_v4_2016_09_09.tar.gz

Inception_ResNet_V2 
http://download.tensorflow.org/models/inception_resnet_v2_2016_08_30.tar.gz

ResNet_V2_152 
http://download.tensorflow.org/models/resnet_v2_152_2017_04_14.tar.gz




Example usage

- Generate adversarial examples:
python nid_fgsm.py

