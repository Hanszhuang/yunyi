# DF 云移杯景区口碑

### nlp 新人
### 为大家提供思路，不定期更新~~~

### 环境
1. python2
2. keras 2.1.2
3. jieba 0.39
4. tensorflow-gpu 1.4.1

### 更新

1. 2018-02-08 
baseline cnn 版本 线上0.500左右 ，调参可到0.502

2. 2018-02-08
增加 rnn,cnn_rnn 模型，线上0.504~0.506

3. 2018-02-08
经过群上的大佬们指点，之前的找的停用词有点问题，换成 @Yin叔 提供的版本，感谢  @Yin叔

4. 2018-03-10
如果是python3  将 splitWord 中result 的 encode('utf-8')去掉，代码即可运行

##### score 线上线下不一致，但是loss 貌似还算一致，线下loss有降低，线上metric有提高，故 earlystop 看val_loss





