---
layout: default
title: K-NN(k-최근접 이웃)
parent: Artificial Intelligence
---

# K-Neighbor Nearest
{: .no_toc}

· K-최근접 이웃 (K-Nearest Neighbor) 알고리즘은 지도학습 알고리즘 중 하나입니다. 분류 및 회귀 문제 모두에 사용될 수 있지만 주로 분류 문제에서 사용됩니다. 

<div style="text-align:center">
    <img src="/docs/assets/images/knn/knn_img.png" alt="KNN" width="400" height="300">
  <p>
    출처: towardsdatascience
  </p>
</div>

· 그림에는 분류되지 않은 데이터(빨간 점)과 Class A로 분류가 된 데이터(노란 점)와 Class B로 분류가 된 데이터(보라 점)가 있습니다. 이제 분류가 되지 않은 데이터 (빨간 점)를 어떤 Class로 분류할 지 생각해보아야 합니다. K-최근접 이웃(K-Nearest Neighbor) 알고리즘은 주변에 있는 점을 하나 씩 거리를 측정해가며 가장 가까운 'k'개의 데이터(즉, 이웃)를 찾습니다. 거리는 주로 유클리드 거리로 측정되지만 다른 거리 측정 방법도 사용될 수 있습니다. KNN이 작동하는 기본 원리는 다음과 같습니다.

1. 'k'를 3으로 정하게 된다면, 그림에서 보다시피 Class B(보라색 점)이 Class A(노란색 점)보다 더 많다는 것을 알 수 있습니다. 그러면 분류되지 않은 데이터(빨간 점)은 Class B(보라색 점)으로 분류되게 됩니다.
2. 'k'를 6으로 정하게 된다면, 그림에서 Class A(노란색 점)의 분포가 더 많은 것을 알 수 있습니다. 그러면 분류되지 않은 데이터(빨간 점)은 Class A(노란 점)으로 분류되게 됩니다.

· KNN은 'k'를 어떻게 정하냐에 따라 결과 값이 바뀔 수 있습니다. 'k'가 너무 작아서도 안 되고, 너무 커서도 안 됩니다. k의 default 값은 5입니다. 일반적으로 'k'는 동점이 되는 것을 피하기 위해 홀수를 사용합니다.

· 분류 문제에서 KNN은 선택된 'k' 개의 이웃 중 가장 흔한 클래스 레이블로 예측됩니다.


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

## Distance Calculation

### 1. Euclidean Distance

​<div style="text-align:center">
    <img src="/docs/assets/images/knn/euclidean_img.png" alt="KNN" width="400" height="150">
  <p>
    출처: datamahadev
  </p>
</div>



### 2. Manhattan Distance

---

## Code

---

## References

---

