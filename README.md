| epoch | resnext50_32x4d | resnext50_32x4d_v2 |
| --- | --- | --- |
| 1 | 2.380 | 2.049 |
| 2 | 1.646 | 1.581 |
| 3 | 1.446 | 1.374 |
| 4 | 1.306 | 1.236 |
| 5 | 1.165 | 1.102 |
| 6 | 1.053 | 0.997 |
| 7 | 0.966 | 0.899 |
| 8 | 0.833 | 0.799 |
| 9 | 0.755 | 0.715 |
| 10 | 0.666 | 0.624 |






|model| acc | plane | car | bird | cat | deer | dog | frog | horse | ship | truck | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| resnext50_32x4d_v2 | 54 % | 56 % | 66 % | 45 % | 36 % | 47 % | 44 % | 65 % | 57 % | 71 % | 59 % | 
| resnext50_32x4d_v2 | 54 % | 61 % | 61 % | 42 % | 45 % | 32 % | 43 % | 64 % | 55 % | 70 % | 66 % | 



ssh://arron@10.103.241.247:22/home/arron/miniconda3/bin/python3 -u /home/arron/Documents/arron/cifar-resnetv2.py
cuda:0
Files already downloaded and verified
Files already downloaded and verified
[1] loss: 18.6534 lr: 0.01 | val_loss: 1.3596 acc: 11.26%
[2] loss: 6.1607 lr: 0.01 | val_loss: 0.6924 acc: 15.83%
[3] loss: 3.7297 lr: 0.01 | val_loss: 0.7116 acc: 19.46%
[4] loss: 3.3667 lr: 0.01 | val_loss: 0.5242 acc: 22.79%
[5] loss: 2.4235 lr: 0.01 | val_loss: 0.4564 acc: 25.88%
[6] loss: 2.9941 lr: 0.01 | val_loss: 0.6293 acc: 29.37%
[7] loss: 2.4843 lr: 0.01 | val_loss: 0.4521 acc: 31.6%
[8] loss: 2.2331 lr: 0.01 | val_loss: 0.3823 acc: 32.86%
[9] loss: 1.8912 lr: 0.01 | val_loss: 0.3812 acc: 35.32%
[10] loss: 1.9695 lr: 0.01 | val_loss: 0.3742 acc: 38.22%
[11] loss: 1.8903 lr: 0.01 | val_loss: 0.3891 acc: 37.9%
[12] loss: 1.7818 lr: 0.01 | val_loss: 0.3549 acc: 41.57%
[13] loss: 1.633 lr: 0.01 | val_loss: 0.3163 acc: 43.54%
[14] loss: 1.5076 lr: 0.01 | val_loss: 0.3041 acc: 45.73%
[15] loss: 1.4541 lr: 0.01 | val_loss: 0.289 acc: 48.03%
[16] loss: 1.3883 lr: 0.01 | val_loss: 0.2906 acc: 49.14%
[17] loss: 1.3407 lr: 0.01 | val_loss: 0.2767 acc: 51.33%
[18] loss: 1.2717 lr: 0.01 | val_loss: 0.2686 acc: 52.91%
[19] loss: 1.2244 lr: 0.01 | val_loss: 0.2607 acc: 54.24%
[20] loss: 1.1784 lr: 0.01 | val_loss: 0.2596 acc: 55.38%
[21] loss: 1.1438 lr: 0.01 | val_loss: 0.2523 acc: 56.08%
[22] loss: 1.0979 lr: 0.01 | val_loss: 0.2458 acc: 57.2%
[23] loss: 1.0589 lr: 0.01 | val_loss: 0.2376 acc: 57.79%
[24] loss: 0.9913 lr: 0.01 | val_loss: 0.2391 acc: 59.28%
[25] loss: 0.9511 lr: 0.01 | val_loss: 0.2339 acc: 60.93%
[26] loss: 0.8975 lr: 0.01 | val_loss: 0.2306 acc: 61.25%
[27] loss: 0.8577 lr: 0.01 | val_loss: 0.2289 acc: 61.19%
[28] loss: 0.819 lr: 0.01 | val_loss: 0.2354 acc: 60.59%
[29] loss: 0.7884 lr: 0.01 | val_loss: 0.2359 acc: 61.9%
[30] loss: 0.7586 lr: 0.01 | val_loss: 0.2371 acc: 62.43%
[31] loss: 0.7189 lr: 0.01 | val_loss: 0.2312 acc: 62.73%
[32] loss: 0.6562 lr: 0.01 | val_loss: 0.2247 acc: 63.77%
[33] loss: 0.6173 lr: 0.01 | val_loss: 0.2363 acc: 63.34%
[34] loss: 0.5691 lr: 0.01 | val_loss: 0.2364 acc: 64.27%
[35] loss: 0.5356 lr: 0.01 | val_loss: 0.2452 acc: 63.72%
[36] loss: 0.504 lr: 0.01 | val_loss: 0.2517 acc: 63.66%
[37] loss: 0.4587 lr: 0.01 | val_loss: 0.2591 acc: 63.35%
[38] loss: 0.4349 lr: 0.01 | val_loss: 0.2578 acc: 63.82%
[39] loss: 0.2476 lr: 0.001 | val_loss: 0.2803 acc: 66.6%
[40] loss: 0.1487 lr: 0.001 | val_loss: 0.316 acc: 66.17%
Finished Training
val_loss: 0.316 acc: 66.17%
plane | car | bird | cat | deer | dog | frog | horse | ship | truck | 
71 % | 79 % | 58 % | 47 % | 56 % | 55 % | 72 % | 70 % | 78 % | 72 % | 

Process finished with exit code 0
