# face-antispoofing-summer-2022
1. run_dataset.ipnb getting local binary patterns(lbp) features for the datasets:
  
  https://drive.google.com/file/d/1uBH6JYkAgy1HHMxTTP39XdZOMtHWc2qG/view?usp=sharing
  
  https://drive.google.com/file/d/1uATAPZSwJBy5oj6AYLqQrEsy0dhJrI0Y/view?usp=sharing
  
  You need to load this files into your google drive
  
2. lbp features calculated by feature_extract.py from https://github.com/Elroborn/Face-anti-spoofing-based-on-color-texture-analysis

3. spoofing_classicML.ipnb build classic models from sklearn using features from step 2

4. classicML_metrics.ipnb calculate metrics and confusion matrix for best models from step 3



## Features:

zip file for data_128: features_128.zip

zip file for data_256: features_256.zip

## Classic ML models results: 

classicML_metrics.ipnb

classicML_results.zip
