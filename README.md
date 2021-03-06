# Response Generation 

Scripts to train Seq2Seq and Transformer models on the Amazon Topical-Chat Corpus. This code serves as the baseline for [DSTC9 Track 3](http://dialog.speech.cs.cmu.edu:8003/).

**To train**: `python3 train.py --use_knowledge --transformer --save_path transformer/`

**To test**: `python3 test.py --use_knowledge --transformer --save_path transformer/`

**To serve interactive model with TF-IDF based fact selection**: `python3 dynamic.py --use_knowledge --transformer --save_path transformer/`

# Data

The pre-processed data can be found in `data.zip`. If you would like to use a different pre-processing strategy, please download the original data from [here](https://github.com/alexa/alexa-prize-topical-chat-dataset/).

# Pre-trained models

The pre-trained models can be found at: https://drive.google.com/file/d/1fPB45RDs_BcJ8KZeYQiauK3W1RsdY2hM/view?usp=sharing

# Contact

If you experience any issues with this code, please contact me at mehrishikib@gmail.com
