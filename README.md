# 💡 Topic
메카트로닉스 실습 && 경진대회 앱 개발(개인 프로젝트)

## 📝 Summary
최근 캠핑의 유행과 함께 자동차를 가지고 여행을 하는 차박의 수요와 급증하는 1인 가구로 인하여 혼자 여행을 하는 사람이 증가하였다. 
하지만 개인이 차박을 위하여 자동차를 사용하는 것은 금전적으로 부담이 돼서 저렴하고 접근성이 뛰어난 PMD를 개발하고자 프로젝트를 구상하였다. 또한, 발전하고 있는 모빌리티 산업에 혁신이 될 수 있다고 생각한다.

위 주제에 나의 역량을 더하기 위해 안드로이드 앱 개발도 함께 진행하였다. 

PMD Key는 PMD를 주행할 때 필요한 것을 지원해준다. 시동을 걸고 끌 때 위치 좌표를 지도에 마커로 찍어 자신의 PMD의 위치를 한눈에 확인할 수 있다. PMD를 주행하기 전에 안전수칙 4가지를 알림받는다. 또한, 오늘의 날씨를 확인하여 주행해도 괜찮을지 판단할 수 있다. 내비 기능도 지원되기 때문에 자신이 가고싶은 위치를 검색한 후 내비를 통해 주행할 수 있다.


## 📷 PMD Photos

<img width="30%" src="https://blog.kakaocdn.net/dn/lELdt/btrEOIlyN0v/pWNg0tPbaKRzj0gXJpqBSk/img.png">      <img width="30%" src="https://blog.kakaocdn.net/dn/dj6dqV/btrENHAFh07/A5I0PJXtghWQrysi45szWk/img.png">

## 👨‍🔧 PMD Demo Video
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/69571848/173570256-6f7934d8-aa4d-4cae-a325-2196d378f388.gif)


## 📖 Details of the app screens

- **메인 페이지 & PMD 연결 & 주변 날씨 정보**

<img width="30%" src="https://blog.kakaocdn.net/dn/bO0UpY/btrDFw09RDT/dS6UnFMDeIjQXMLXNlyl81/img.jpg">      <img width="30%" src="https://blog.kakaocdn.net/dn/s3S2a/btrDAkOG3Rp/r2UrO5h0qjrtweYT9qhZDk/img.jpg">


- **지도**



<img width="30%" src="https://blog.kakaocdn.net/dn/kJ4eC/btrDBtLoUCe/t0dZuzkzpWoBK3MhAKryqK/img.jpg">


- **나의 PMD 찾기**

<img width="30%" src="https://blog.kakaocdn.net/dn/6ej4L/btrDEiwgczh/jSZD7Hut7IT5IHBwOfQKP1/img.jpg">


- **검색 기능**


<img width="30%" src="https://blog.kakaocdn.net/dn/eutYRZ/btrDDrftGru/bay5CV3hhozDQ4HhZwu6R0/img.jpg"><img width="30%" src="https://blog.kakaocdn.net/dn/bxVqgG/btrDGKktAIK/NlLFUCntW6isA2jsTucnc1/img.jpg"><img width="30%" src="https://blog.kakaocdn.net/dn/cJKkdM/btrDGMCqEr9/oK6B2pfJqKkf7YyDRNZBk0/img.jpg">

 - **길 찾기**
 
<img width="30%" src="https://blog.kakaocdn.net/dn/0DT1H/btrDBuKhH4F/55CIxu0Y8hQflBtgBq3B31/img.jpg">


- **안전수칙**


<img width="30%" src="https://blog.kakaocdn.net/dn/n0hSG/btrDHeTba52/IiHth4ie4irKqzhbLX5E5k/img.jpg"><img width="30%" src="https://blog.kakaocdn.net/dn/thk7j/btrDE8zA5n0/73XEfUfJPyh2kNcJBO6VK0/img.jpg">
<img width="30%" src="https://blog.kakaocdn.net/dn/cQIIzV/btrDGacuEil/NJkxu3u6LpzpCZy8erLOS0/img.jpg">
<img width="30%" src="https://blog.kakaocdn.net/dn/oRjvI/btrDEQ0hzcM/PaGRwGHvJf3zpQkCrrIAt1/img.jpg">
<img width="30%" src="https://blog.kakaocdn.net/dn/uW9lL/btrDDtrie0d/duO3aX01O5DGHq6N1oqxI1/img.jpg">
<img width="30%" src="https://blog.kakaocdn.net/dn/blKhOj/btrDFwtkNnV/6vV9754DKO0oQQhjl1eLmk/img.jpg">

## 🛠️ ****Tech Stack****

- Kotlin
- Room
- Coroutine flow debounce 
- retrofit2
- Kakao map
- Kakao navi
- Kakao Local

## ****⚙️ Architecture****

- MVVM



## 📌 ****Part(Android)****

- Android와 Arduino 블루투스 연결 
- 주변 날씨 정보
- 공공 데이터 포털 오픈 API
- Kakao Map을 통해 지도 구현 및 주소 검색
- 시동을 껐을 때 자신의 PMD 위치 저장
- Kakao navi를 통해 길 찾기
- 안전수칙 4가지 알림

## 💡 ****Learned****

- **블루투스** 연결을 통해 PMD의 **시동**을 켜보려했지만 **모터 컨트롤러**를 제어하지 못해 **실패**하게 되었다.
- **retrofit2**을 통해 **공공 데이터 포털 오픈 API**와 **Kakao Map**의 데이터를 가져와 가공하였다.
- **Coroutine flow debounce** 학습하고 Coroutine에 대해 심도있게 알게 되었다.
