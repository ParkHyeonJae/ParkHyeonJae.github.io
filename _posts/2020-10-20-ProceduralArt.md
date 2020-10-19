---
layout: post
title: "Procedural Art"
categories: misc

---



## Procedural Art (재생 오디오)



60분법에서는 원의 한 바퀴가 360도로 정의함

라디안으로는 원의 한 바퀴는 2파이



#### 오디오의 해부학

- pitch : 음정
- duration : 길이
- loudness : 크기
- Timbre 
- Sonic Texture : 소리의 질감
- Spatial Location : 공간의 위치



- Wave : 길이 -> 1초마다 
- frequency : 빈도





#### Sin 생성

![image-20201015171129401](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015171129401.png)

####  사각형 생성

![image-20201015170325906](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015170325906.png)



##### 삼각형 생성

![image-20201015170346188](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015170346188.png)



#### Sin Wave + Square Wave

- Sin Wave와 Square Wave가 서로 결합했을 때

![image-20201015170419633](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015170419633.png)



##### Sin Wave + Square Wave ->  Use Mathf.Clamp

- -1 부터 1까지 값의 제한을 뒀음

![image-20201015170613559](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015170613559.png)



##### DelayLine

![image-20201015170914973](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015170914973.png)



###### Distortion (왜곡)

- 기준선 (threshold)이 존재한다고 생각하고 접는것

![image-20201015171006569](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015171006569.png)



#### 공식적인 빈도(Frequency를 가져오는 함수)

![image-20201015173556644](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015173556644.png)

- 기본적인 음 (a)

![image-20201015173700807](C:\Users\md101\AppData\Roaming\Typora\typora-user-images\image-20201015173700807.png)



#### 말하기 (Speech)를 표현하는 법

- 각각의 소리마다 특정한 frequency가 존재하는데
  이것을 이용해서 speech를 표현이 가능하다





`` 수학을 창의적으로 사용하면 상당히 상상력이 풍부한 창의적인 것을 만들 수 있다. ``

`` 그렇다고 언어 공부를 소홀히 하지 맙시다 ``



