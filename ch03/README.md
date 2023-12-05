# CHAPTER 3: 신경망

```
📦ch03
 ┣ 📜mnist.show.py
 ┣ 📜neuralnet_mnist.py
 ┣ 📜neuralnet_mnist_batch.py
 ┣ 📜relu.py
 ┣ 📜sample_weight.pkl
 ┣ 📜sigmoid.py
 ┣ 📜sig_step_compare.py
 ┗ 📜step_function.py
```

## 정리
- 신경망에서는 활성화 함수로 시그모이드 함수와 ReLU 함수 같은 매끄럽게 변화하는 함수를 이용한다.
- 넘파이의 다차원 배열을 잘 사용하면 신경망을 효율적으로 구현할 수 있다.
- 기계학습 문제는 크게 회귀와 분류로 나눌 수 있다.
- 출력층의 활성화 함수로는 회귀에서는 주로 항등 함수를, 분류에서는 주로 소프트맥스 함수를 이용한다.
- 분류에서는 출력층의 뉴런 수를 분류하려는 클래스 수와 같게 설정한다.
- 입력 데이터를 묶은 것을 배치라 하며, 추론 처리를 이 배치 단위로 진행하면 결과를 훨씬 빠르게 얻을 수 있다.