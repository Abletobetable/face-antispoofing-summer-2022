# face-antispoofing-summer-2022

Facial anti-spoofing is the task of preventing false facial verification by using a photo, video, mask or a different substitute for an authorized person’s face. Some examples of attacks:

Print attack: The attacker uses someone’s photo. The image is printed or displayed on a digital device.

Replay/video attack: A more sophisticated way to trick the system, which usually requires a looped video of a victim’s face. This approach ensures behaviour and facial movements to look more ‘natural’ compared to holding someone’s photo.

Frameworks: Python, pytorch, wandb, opencv, numpy, pandas, sklearn

The best results:

ClassicML models on test dataset: SVM - 0.63, Random Forest - 0.57, MLP - 0.53

PytorchNet on test dataset: 0.78

PytorchNet on real data: 0.18

examples from real data: 

![image](https://user-images.githubusercontent.com/109301202/189068094-c8fd8143-9ded-4726-96e3-eaa27a660248.png)

1. run_dataset.ipnb getting local binary patterns(lbp) features for the datasets made by https://github.com/hairymax/Face-AntiSpoofing:
  
  https://drive.google.com/file/d/1uBH6JYkAgy1HHMxTTP39XdZOMtHWc2qG/view?usp=sharing
  
  https://drive.google.com/file/d/1uATAPZSwJBy5oj6AYLqQrEsy0dhJrI0Y/view?usp=sharing
  
  You need to load this files into your google drive
  
2. lbp features calculated by feature_extract.py from https://github.com/Elroborn/Face-anti-spoofing-based-on-color-texture-analysis

3. spoofing_classicML.ipnb build *classic models* from sklearn using features from step 2

4. classicML_metrics.ipnb calculate metrics and confusion matrix for best models from step 3

5. ClassicML dont't achieve good results, so there is *pytorch neural network* in AntospoofingNet.ipynb using the same features

6. to get frames from video - run fet_frames_from_vid.ipynb

7. to test or to make prediction on your folder with images you can use AntispoofingNet_demo.ipynb




## Features:

zip file for data_128: features_128.zip

zip file for data_256: features_256.zip

## Classic ML models results: 

classicML_metrics.ipnb

classicML_results.zip


#### feel free to contact with me:

https://t.me/abletobetable

abletobetable@mail.ru
