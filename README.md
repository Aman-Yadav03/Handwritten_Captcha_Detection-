# Handwritten_Captcha_Detection-
## Overview
The program is a sophisticated machine learning application that converts handwritten captchas, which consist of English letters and emojis assigned to specific numbers, into plain text. By utilizing deep learning techniques, particularly convolutional neural networks (CNNs), the program is able to accurately recognize and translate the characters in the captchas. OpenCV is employed for advanced image processing tasks, such as resizing, normalization, noise reduction, and binarization, ensuring that the input images are in the optimal format for the CNN to process. This combination of deep learning and image processing allows the program to effectively decipher handwritten captchas with high accuracy.

## Captcha Components
* Emojis: Captchas may contain the following emojis, each mapped to a specific number:
    Checkmark (✅): 1
    Cloud (☁️): 2
    Croissant (🥐): 3
    Heart (❤️): 4
    Laugh (😄): 5
    Smile (😊): 6
    Sun (☀️): 7
* Letters: Captchas may contain the following English letters:
    A, B, C, D, E, F, G, H, J, K, M, P, R, T, W, X, b, e, h

## Approach
### Segmentation of Letters
  ->Utilized OpenCV for image processing, leveraging the img_cleaning() and read() segmentation code.
  ->Successfully extracts letters from both digital and handwritten images.
  ->Proficient in reading colorful images, handling shadows, and mitigating the impact of noise.
### Model Training
  ->Utilizes Convolutional Neural Networks (CNN) for efficient learning.
  ->Evaluates loss using Cross Entropy loss, ensuring effective model training.
  ->Optimizes model parameters using the Adam optimizer for rapid convergence.
