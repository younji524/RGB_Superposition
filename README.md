# RGB_Superposition
<br/>
자궁경부암의 단계를 구분하기 위해 중요하게 여겨지는 증상 중 하나인 아세토화이트를 자궁경부 영상으로부터 추출한 뒤, 추출한 영역을 바탕으로 RGB 중첩 기법을 활용하여 딥러닝 분류 모델의 성능을 향상시켰다. <br/>
<br/>
단계는 다음과 같이 이루어진다. <br/>
<br/>
1. 원본 영상으로부터 아세토화이트 영역 추출 <br/>
2. 아세토화이트 영역을 마스크화 <br/>
3. 마스크 이미지 1개와 원본 이미지 2개를 RGB 채널 중첩하여 새로운 이미지 생성 <br/>
<br/><br/>

**[ RGB 채널 중첩 이미지 생성 과정 ]**
  
![Figure 1](https://github.com/younji524/RGB_Superposition/assets/76142194/b65ee1b7-6c7b-4ecd-bccc-14c155da208a)

**[ 생성된 RGB 채널 중첩 이미지 ]**
  
![Figure 2](https://github.com/younji524/RGB_Superposition/assets/76142194/b49865fb-6c97-4701-9449-48fc55d6c240)

<br/><br/>

RGB 채널 중첩을 활용한 딥러닝 분류 모델의 경우, 원본 영상을 이용한 딥러닝 분류 모델보다 **약 9% 향상된 성능을 보였다.** <br/><br/>

**[ 사용한 딥러닝 모델 아키텍처 ]**
  
![Figure 3](https://github.com/younji524/RGB_Superposition/assets/76142194/7a68abcb-071c-4848-9682-6a7222f25a80)

<br/>

**[ 각 RGB 채널 중첩 영상별 딥러닝 분류 성능 ]**

![Table 1](https://github.com/younji524/RGB_Superposition/assets/76142194/9ea1f501-e6b1-4601-963d-feb36894e069)

<br/>

**[ 원본, 마스크 영상, RGB 채널 중첩 영상별 딥러닝 분류 성능 ]**

![Table 2](https://github.com/younji524/RGB_Superposition/assets/76142194/be653597-d333-49eb-a2c3-05c1ce003126)

<br/>
