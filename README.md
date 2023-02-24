# DCGAN


![dcgan archi](https://user-images.githubusercontent.com/106899647/221145101-8463513c-ead2-4ba3-b3eb-37fef1eabf9e.png)



DCGAN은 Deep Convolutional Generative Adversarial Network의 약자입니다. 심층 합성곱 신경망(CNN)을 사용하여 이미지를 학습하고 생성하는 일종의 생성 모델입니다.

DCGAN은 적대적 훈련을 사용하여 생성기 네트워크를 훈련하여 주어진 데이터 세트와 유사한 사실적인 이미지를 생성한다는 아이디어를 기반으로 합니다. 생성기 네트워크는 임의의 노이즈를 입력으로 사용하여 이미지를 생성하는 반면 판별기 네트워크는 실제 이미지와 가짜 이미지를 구별하려고 합니다.

DCGAN은 심층 합성곱 신경망을 사용하여 고품질 이미지를 생성하기 때문에 RBM(Restricted Boltzmann Machine) 및 DBN(Deep Belief Networks)과 같은 이전의 생성 모델보다 개선되었습니다. 이러한 네트워크는 데이터의 복잡한 기능과 구조를 학습할 수 있으므로 보다 사실적이고 상세한 이미지를 생성할 수 있습니다.

DCGAN은 이미지 합성, 이미지 초고해상도, 이미지 인페인팅 등 다양한 응용 분야에서 사용되고 있습니다. 또한 다른 기계 학습 모델을 교육하기 위한 합성 데이터를 생성하는 데 사용되었습니다.
