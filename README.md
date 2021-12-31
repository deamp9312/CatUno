# CatUno
2020년 1학기 프로젝트 수업중 만든 앱이다.


시연 영상
https://youtu.be/37dDiT4gG1g

#1 주제 선정


![image](https://user-images.githubusercontent.com/71180644/124303246-2d392400-db9d-11eb-9c01-407b725536cb.png)


-길고양이는 구자체에서 중성화및 개체수를 조절하여 보호하는 동물이다, 그런데에 반해 제대로 보호가 안 되며 요즘 개냥이라고 불릴정도로 최근 집근처에서 사람과 친하게 지내는 고양이들을 위한 어플




#2 기능 목표
-길고양이를 관리하고 사람들 간의 도움을 줄 수 있는 커뮤니티 생성 

- 유기묘들을 GPS와 얼굴인식으로 구별해 최근 상태를 이용자들이 공유할 수 있음
     (ex.식사 여부,위치,질병 등등)

- 지자체에서 고양이의 중성화 여부를 게시글과 보호 현황 등을 보고 더욱 쉽게 파악할 수 있다.



#3 시스템 구성도

![image](https://user-images.githubusercontent.com/71180644/124303845-e4ce3600-db9d-11eb-9f27-3df076fe1766.png)


![image](https://user-images.githubusercontent.com/71180644/124303956-04655e80-db9e-11eb-84a5-9844da84c3d0.png)



#4 결과

https://youtu.be/37dDiT4gG1g
https://youtu.be/pV-LkWzBzOk



![image](https://user-images.githubusercontent.com/71180644/124307187-69bb4e80-dba2-11eb-96ad-788bc8d5f0df.png)




#5 회고

-우선 팀장으로 맡은 역활은 고양이가 영역동물이라는 것을 이용해 공공데이터 포털에서 제공하는 고양이 사진 data및 gps를 이용해 본인 근처로 구자체에서 보호중인 고양이들의 대략적인 위치 출력,
 또한 가능하다면 opencv및 텐서플로우를 이용해 프로젝트 시작쯤에 막연하게 할수 있겠지라는 안일함으로 혼자 해보려 했지만... 한달 반의 기간은 너무짧았고,,, 대안으로 구글에서 제공하는 티처블머신을 이용한 이미지 구분 기능을 사용해 앱->웹으로 띄웠다.
 지도는 구글api맵을 이용해 마커를 이용해 공공데이터 포털에서 제공하는 data와 혼합해 이미지를 데스크탑에 저장하고 경로를 이용해 불러오는 식으로 하였다... 솔직히 AI 파이썬을 프로젝트 하면서 처음 써 보았고, 파이썬을 이용한 고양이 DATA수집을 위해 크롤링 기능또한 학습하였다,
