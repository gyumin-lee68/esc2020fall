Background
----------------------
Main task: language modeling, machine translation

기존 모델들의 한계
1. Seq2Seq

![seq2seq](C:/Users/minzz/Desktop/1.jpg)

Bottleneck 문제: encoder 정보가 하나의 hidden state로 압축됨 -> 정보 손실

2. Attention

* Recurrent models(RNN, LSTM, GRU, etc)

병렬적인 연산 처리가 어려움 (sequential computation)

* CNN based models(ConvS2S, etc)

먼 거리의 단어 간 관계 파악이 어려움

**이러한 기존 모델들의 한계를 벗어난 transformer!**
