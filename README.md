# 데이터 분석 기반 영화 콘텐츠 추천 서비스

데이터 분석 과정을 거쳐 도출한 인사이트를 기반으로 기획, 개발하게 된 **사용자 맞춤형 영화 콘텐츠 추천 서비스**입니다.

### [시연영상](https://blog.naver.com/confettimimy/222075548664)  👈🏻😃   

(자세한 내용은 발표자료, 최종 보고서 참고)

#

### 로그인 or 회원가입을 진행합니다.

<img src="./readme_img/01 소개.PNG">    

### 사용자의 정보를 토대로 개개인이 선호할 만한 맞춤형 영화들을 추천해줍니다.  

<img src="./readme_img/02 소개.PNG">    

### **추천받은 영화들 중 선호하는 영화를 클릭하면 해당 영화와 비슷한 줄거리의 영화까지 추천받을 수 있습니다.**   

<img src="./readme_img/03 소개.PNG">    

---

## 시스템 설계도

[demo]

---


## 웹 구동하기

웹 호스팅 서비스를 사용하지 않고 구현하여 로컬환경에서 구동해야 합니다.

```python
# 해당 디렉토리로 이동
cd 해당 디렉토리
   
# 서버 파일 실행
python server.py
```

###### *해당 웹 서비스를 구동시키기 위해 flask, pandas, sklearn 등과 같은 라이브러리 설치 필요