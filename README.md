# MIMO-for-CSE

## ENV

pytorch/0.4.0, python/3

## TRAIN MODEL

example commands for pretrain:

(all gates for LM, pretrain)
`python train.py --cuda --config 111000000 --model_name MIMO_BERT_LSTM --pretrain`

(all gates for POS, pretrain)
`python train.py --cuda --config 000111000 --model_name MIMO_BERT_LSTM --pretrain`

(all gates for LM and POS, pretrain)
`python train.py --cuda --config 111111000 --model_name MIMO_BERT_LSTM --pretrain`

example commands with multi-output:

(all gates for LM with multi-output)
`python train.py --cuda --config 111000000 --model_name MIMO_BERT_LSTM`

(all gates for POS with multi-output)
`python train.py --cuda --config 000111000 --model_name MIMO_BERT_LSTM`

(all gates for LM and POS, with multi-output)
`python train.py --cuda --config 111111000 --model_name MIMO_BERT_LSTM`


## DOWNLOAD

* The word embedding we use can be found [here](https://www.dropbox.com/sh/6yx1l8euehgw12k/AAB9mWc3m8H7niuEF7NBYUdRa?dl=0}{\underline{here}}\footnote{\url{https://www.dropbox.com/sh/6yx1l8euehgw12k/AAB9mWc3m8H7niuEF7NBYUdRa?dl=0}).

* The pre-trained language model we use can be found [here](https://www.dropbox.com/sh/q1kehix8q58sxmh/AADU35QFu1ZMuNQFTiEYWSxUa?dl=0}{\underline{here}}\footnote{\url{https://www.dropbox.com/sh/q1kehix8q58sxmh/AADU35QFu1ZMuNQFTiEYWSxUa?dl=0}}).

