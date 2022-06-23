## Important papers and impelimentation

A. Graves, A. Mohamed, and G. Hinton, “Speech recognition with
deep recurrent neural networks,” in Proc. ICASSP, Vancouver, 2013.

J. Chorowski, D. Bahdanau, D. Serdyuk, K. Cho, and Y. Bengio,
“Attention-based models for speech recognition,” in Proc. NIPS, 2015.

### Deepcpeech2 (ICLR 2016)
 - [Paper](https://arxiv.org/abs/1512.02595)
 - [Official Code in Paddle(Baidu framework)](https://github.com/PaddlePaddle/PaddleSpeech)
 - [Tensorflow Deepcpeech2](https://github.com/tensorflow/models/blob/238922e98dd0e8254b5c0921b241a1f5a151782f/research/deep_speech)
 - [Simplified tutorial in keras.io](https://keras.io/examples/audio/ctc_asr/)
#### notes:
- "SortaGrad”: order utterances by length during first epoch.
- "Batchnorm"
- Using CTC loss
