# RGB_Superposition

자궁경부암의 단계를 구분하기 위해 중요하게 여겨지는 증상 중 하나인 아세토화이트를 자궁경부 영상으로부터 추출한 뒤, 추출한 영역을 바탕으로 RGB 중첩 기법을 활용하여 딥러닝 분류 모델의 성능을 향상시켰다.

단계는 다음과 같이 이루어진다.

1. 원본 영상으로부터 아세토화이트 영역 추출
2. 아세토화이트 영역을 마스크화
3. 마스크 이미지 1개와 원본 이미지 2개를 RGB 채널 중첩하여 새로운 이미지 생성

RGB 채널 중첩을 활용한 딥러닝 분류 모델의 경우, 원본 영상을 이용한 딥러닝 분류 모델보다 약 9% 향상된 성능을 보였다.
