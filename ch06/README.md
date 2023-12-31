# 학습 관련 기술

```
📦ch06
 ┣ 📜batch_norm_test.py
 ┣ 📜hyperparameter_optimization.py
 ┣ 📜optimizer_compare_mnist.py
 ┣ 📜optimizer_compare_naive.py
 ┣ 📜overfit_droput.py
 ┣ 📜overfit_weight_decay.py
 ┣ 📜weight_init_activation_histogram.py
 ┗ 📜weight_init_compare.py
```

## 정리
- 매개변수 갱신 방법에는 확률적 경사 하강법(SGD) 외에도 모멘텀, AdaGrad, Adam 등이 있다.
- 가중치 초깃값을 정하는 방법은 올바른 학습을 하는 데 매우 중요하다.
- 가중치의 초깃값으로는 'Xavier 초깃값'과 'He 초깃값'이 효과적이다.
- 배치 정규화를 이용하면 학습을 빠르게 진행할 수 있으며, 초깃값에 영향을 덜 받게 된다.
- 오버피팅을 억제하는 정규화 기술로는 가중치 감소와 드롭아웃이 있다.
- 하이퍼파라미터 값 탐색은 최적 값이 존재할 법한 범위를 점차 좁히면서 하는 것이 효과적이다.
