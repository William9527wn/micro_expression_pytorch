## micro-expression_pytorch
## Dataset 

This is code is based on CASME2 dataset:[CASME2](http://fu.psych.ac.cn/CASME/casme2-en.php)

## Method

- The short video in the CASME2 dataset is cropped into frames through OPENCV, and features are extracted through VGG and sent to LSTM for classification.When the number of frames of the short video is different, I use 0 for padding.

- To run it:

  ​    ``python main.py``

## Notes

- **This code can only be used as a reference**, using pytorch to run on the cpu. 
- Since I wrote it a long time ago, I forgot most of the content.**So please don't ask me questions, because I really forgot it**.
- **I don’t plan to continue to maintain this repository**.









