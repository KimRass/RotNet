# 2. Methodology
## 2) Choosing geometric transformations: Image Rotations
- Advantages:
    - Resize나 Scale과 다르게 모델이 추론함에 있어서 Trivial features를 배우는 데 사용할 수 있는 어떤 Low-level visual artifacts가 없습니다.
    - 4가지 각도 중 정답을 추론하는 데 있어서 이미지 상의 객체가 동그란 것들밖에 없다던가 하는 상황을 제외하고 애매모호한 경우가 없습니다. 즉 정답이 명확합니다.
# 3. Experimental Results
## 1) CIFAR Experiments
- Minibatch를 구성할 때, 하나의 이미지에 대해서 무작위로 4가지 각도 중 하나로 회전시킨 것을 포함시킬 때보다 4가지 각도 각각에 대해서 회전시킨 서로 다른 4개를 모두 포함시켰을 때 상당한 효과가 학습 효과가 있었습니다.
