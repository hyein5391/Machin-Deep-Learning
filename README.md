# Machin-Deep-Learning
아나콘다 설치 
https://www.anaconda.com/ -> Anaconda Distribution다운

아나콘다 가상환경 설정 순서

![가상환경설정](https://user-images.githubusercontent.com/110071838/198503070-e1553967-d30f-4c67-9204-c388d1144d11.png)


![가상환경2](https://user-images.githubusercontent.com/110071838/198502955-e7b9da53-37ec-4609-897b-b8e04c9f93f0.png)


![가상환경 설정3](https://user-images.githubusercontent.com/110071838/198502964-2c96e91f-95d1-410a-9863-87ef025797d7.png)

쥬피터 노트북 가상환경에 별도 설치
![쥬피터 노트북 가상환경에 설치 별도 설치 필요](https://user-images.githubusercontent.com/110071838/198502982-8e092512-48e9-4001-aa65-c1cabd7eaa3f.png)


![가상환경설정 4](https://user-images.githubusercontent.com/110071838/198503790-7440282f-7788-4231-817d-2dcdea1d6a4f.png)





가상환경 탈출 루트

![아나콘다 가상환경 빠져나가는 명령어](https://user-images.githubusercontent.com/110071838/198503812-cb81857b-e5af-448a-b6c3-41845d2877bb.png)







★지도 학습과 비지도 학습





지도학습(supervised learning)   비지도 학습(unsupervised learning)   강화학습(reinforcement learning)
    


![untitled](https://user-images.githubusercontent.com/110071838/198443765-314b5e8d-6f84-407b-8188-13053c5bb470.png)



★CNN(Convolutional Newural Network)


![1_dELdy-RiGmcU5OamnAYWCQ](https://user-images.githubusercontent.com/110071838/198449542-db28b4f8-d2e0-4e3b-af08-5fa67b611c9b.png)


CNN은 ‘합성곱 신경망’으로 불리는데, 계산과정에서 합성곱(Convolution)을 사용하기 때문입니다. 이미지 데이터 분석을 예시로 합성곱 층(Convolution Layer)의 계산과정을 도식화해보면 아래와 같다

![1_AqoodQiRua99Y2JctctSbA](https://user-images.githubusercontent.com/110071838/198456148-1764b695-c6a7-4445-885d-dbb4c5fff0c7.png)



★RNN(Recurrent Neural Network)

![1_slQWvbM6hvQaWL1ZgmuuNQ](https://user-images.githubusercontent.com/110071838/198456973-9e040dbb-7293-42f6-9024-7d93306b4d3e.png)


순환신경망으로도 불리는 RNN은 시계열 데이터처럼 시간에 따라 변화하는 데이터를 학습시키기 위한 딥러닝

RNN의 기본 구조↓

![1_JluFN2aG9VvHP0I7kFVLqw](https://user-images.githubusercontent.com/110071838/198457348-de4fd0cc-621b-484a-a851-f34a4bdbc0c7.png)





★자동차에 대한 데이터 호출후 데이터셋 분포 결과

price(자동차가격), maint(자동차 유지 비용), doors(자동차 문 개수), persons(수용인원), lug_capacity(수하물 용량), safety(안전성)



Output(차상태) : 이 데이터는 ubacc(허용 불가능한 수준) 및 acc(허용 가능한 수준, 양호 및 매우 좋은 중 하나의 값을 갖습니다\


![캡처_2022_10_28_14_45_10_111](https://user-images.githubusercontent.com/110071838/198512260-72830c2b-62f1-44f6-bdce-39ebfc75c717.png)

![캡처_2022_10_28_14_45_20_380](https://user-images.githubusercontent.com/110071838/198512269-855c031c-3dd3-4928-bc0b-bfc21fb56cef.png)

결과:

대부분의 자동차(70%)는 허용 불가능한 상태에 있고 20%만 허용 가능한 수준이다
즉 양호한 상태의 자동차 비율이 매우 낮은 것을 볼수있다


원-핫 인코딩 적용후 ↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓

![캡처_2022_10_28_16_40_36_878](https://user-images.githubusercontent.com/110071838/198531870-534d3af0-412e-4b07-863a-d97cd424e86d.png)


![캡처_2022_10_28_16_40_48_54](https://user-images.githubusercontent.com/110071838/198531887-5d3804bc-877e-4238-ae82-299c5975adf2.png)


![캡처_2022_10_28_16_57_03_374](https://user-images.githubusercontent.com/110071838/198535162-febf4d00-1684-4547-a74e-e36d2fcaed8e.png)

![캡처_2022_10_28_17_01_08_620](https://user-images.githubusercontent.com/110071838/198536105-d45269c3-beb5-4e06-9d01-eb634e23d8cc.png)

![캡처_2022_10_28_17_02_58_588](https://user-images.githubusercontent.com/110071838/198536386-4acd9497-b563-4436-bb41-573bab6639dc.png)

acc : 는 학습한 데이터수치 ↑↑↑↑↑↑↑↑↑↑↑↑

val_acc:는 학습안한 데이터수치 ↑↑↑↑↑↑↑↑↑↑↑↑↑



![캡처_2022_10_28_17_12_23_970](https://user-images.githubusercontent.com/110071838/198538381-98e96737-fe36-48cf-9a9c-aad83b3e9060.png)












# SimpleRNN 구현

백신보관 냉장고 온도변화 센서 Data RNN구현

![캡처_2022_11_18_15_50_37_307](https://user-images.githubusercontent.com/110071838/202640028-826df941-1603-487d-8eb7-50504b7bef61.png)



![캡처_2022_11_18_15_50_45_455](https://user-images.githubusercontent.com/110071838/202640117-71a394ec-3851-4015-ab29-934ede87dcdf.png)
