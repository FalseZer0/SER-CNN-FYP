# SER-CNN-FYP
Speech emotion recognition with Convolutional neural networks
## Results
Evaluation was done using 10 fold cross validation and stratified 10 fold cross validation. The task which is being addressed is speaker-dependent speech classifications. IEMOCAP involves 4 common classes with happy and excitement emotions merged and Emo-DB has all 7 emotion classes. 
### IEMOCAP
| Model name | Accuracy | F1 |
| --- | --- | --- |
| CNN 2d | 64.68955| 64.25217 |
| CNN 2d strat| 65.52160| 65.39586 |
| LSTM | 52.30488 | 51.51344 |
| LSTM strat| 52.93819 | 52.19731 |
| CNN2d + LSTM | 62.8815 | 62.72817 |
| CNN2d + LSTM strat| 62.50174 | 62.22613 |
| Resnet 50 | 49.9185 | 49.82717 |
| Resnet 50 strat| 49.77431 | 49.71265 |
| resnet custom | 62.7192 | 62.30440 |
| resnet custom strat| 62.88204 | 62.53373 |
| 1dcnn with augmented data | 77.95155 | 78.018637 |
| 1dcnn with augmented data stratified | 76.13443 | 76.15381 |
| 1dcnn lstm with augmented data | 70.58842 | 70.56233 |
| 1dcnn lstm with augmented data strat | 70.665281 | 70.623133 |
| 1dcnn without augmented data | 56.048335 | 55.872315 |
| 1dcnn without augmented data strat | 51.2020418 | 51.054161 |
| 1dcnn lstm without augmented data | 51.2029 | 51.023452 |
| 1dcnn lstm without augmented data strat | 51.38365 | 51.10143 |
### Emo-DB
| Model name | Accuracy | F1 score |
| --- | --- | --- |
| CNN 2d  | 73.6477 | 72.7837 |
| CNN 2d strat | 71.4185 | 70.0033 |
| 1dcnn w/o aug | 69.7239 | 69.11377 |
| 1dcnn w/o aug strat | 67.8476 | 66.73677 |
| 1dcnn+lstm w/o aug | 45.7966455 | 44.94652 |
| 1dcnn+lstm w/o aug strat | 45.450733 | 44.7580966 |
| 1dcnn with aug | 96.91588819 | 96.92714 |
| 1dcnn with aug strat  | 96.028038 | 96.0221888 |
| 1dcnn-lstm with aug | 88.130840 | 88.16275 |
| 1dcnn-lstm with aug strat | 85.65420567 | 85.68387697 |
## Inspired by:
<ol>
  <li>arXiv:1608.04363v2</li>
  <li>https://doi.org/10.1016/j.bspc.2020.101894</li>
  <li>https://arxiv.org/abs/2112.05666</li>
  <li>https://doi.org/10.1145/3267935.3267948</li>
  <li>https://www.coursera.org/learn/convolutional-neural-networks</li>
</ol>
