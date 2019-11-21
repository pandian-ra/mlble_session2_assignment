# mlble_session2_assignment

# LOGS
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 49s 819us/step - loss: 0.3579 - acc: 0.9129 - val_loss: 0.0689 - val_acc: 0.9826
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 44s 730us/step - loss: 0.1368 - acc: 0.9647 - val_loss: 0.0527 - val_acc: 0.9862
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 44s 730us/step - loss: 0.1025 - acc: 0.9728 - val_loss: 0.0445 - val_acc: 0.9869
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 44s 732us/step - loss: 0.0872 - acc: 0.9764 - val_loss: 0.0338 - val_acc: 0.9901
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 44s 735us/step - loss: 0.0743 - acc: 0.9791 - val_loss: 0.0310 - val_acc: 0.9900
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 44s 730us/step - loss: 0.0675 - acc: 0.9816 - val_loss: 0.0269 - val_acc: 0.9917
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 44s 732us/step - loss: 0.0636 - acc: 0.9818 - val_loss: 0.0232 - val_acc: 0.9940
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 44s 735us/step - loss: 0.0582 - acc: 0.9836 - val_loss: 0.0213 - val_acc: 0.9937
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 44s 734us/step - loss: 0.0553 - acc: 0.9848 - val_loss: 0.0236 - val_acc: 0.9930
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 44s 731us/step - loss: 0.0522 - acc: 0.9854 - val_loss: 0.0202 - val_acc: 0.9945
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 44s 731us/step - loss: 0.0498 - acc: 0.9859 - val_loss: 0.0222 - val_acc: 0.9941
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 44s 729us/step - loss: 0.0493 - acc: 0.9864 - val_loss: 0.0196 - val_acc: 0.9947
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 44s 726us/step - loss: 0.0475 - acc: 0.9862 - val_loss: 0.0185 - val_acc: 0.9949
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 44s 728us/step - loss: 0.0454 - acc: 0.9870 - val_loss: 0.0191 - val_acc: 0.9942
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 44s 731us/step - loss: 0.0431 - acc: 0.9878 - val_loss: 0.0194 - val_acc: 0.9944
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 44s 728us/step - loss: 0.0436 - acc: 0.9875 - val_loss: 0.0174 - val_acc: 0.9951
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 44s 738us/step - loss: 0.0416 - acc: 0.9875 - val_loss: 0.0191 - val_acc: 0.9944
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 45s 742us/step - loss: 0.0410 - acc: 0.9883 - val_loss: 0.0172 - val_acc: 0.9946
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 44s 735us/step - loss: 0.0401 - acc: 0.9886 - val_loss: 0.0187 - val_acc: 0.9947
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 44s 727us/step - loss: 0.0403 - acc: 0.9887 - val_loss: 0.0181 - val_acc: 0.9945
<keras.callbacks.History at 0x7f1624e63390>
# Accuracy
[0.018119178426603322, 0.9945]

# Strategy 
1. Increased the Dropout rate to 0.2 and used dropout after every connvolution except at the last layer. Not using Dropout layer at the last layer increased my model accuracy 
2. Tried to use like Batch( 3x3 convolution followed by 1x1 convolution) for few layer.
3. I've used MaxPooling only once to reduce parameters. Tried twice but the accuracy was not good.
