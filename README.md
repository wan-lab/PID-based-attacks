# PID-Based Approach to Adversarial Attacks
This repository contains the code for PID-Based Approach to Adversarial Attacks (AAAI2021).

Adversarial attack can misguide the deep neural networks (DNNs) with adding small-magnitude perturbations to normal examples, which is mainly determined by the gradient of the loss function with respect to inputs. Previously, various strategies have been proposed to enhance the performance of adversarial attacks. However, all these methods only utilize the gradients in the present and past to generate adversarial examples. Until now, the trend of gradient change in the future (i.e., the derivative of gradient) has not been considered yet. Inspired by the classic proportional-integral-derivative (PID) controller in the field of automatic control, we propose a new PID-based approach for generating adversarial examples. The gradients in the present and past, and the derivative of gradient are considered in our method, which correspond to the components of P, I and D in the PID controller, respectively.

Requirements

- Python 3.6.5
- Tensorflow 1.12.0 
- Numpy 1.15.4 
- Opencv2 3.4.2

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

