<img width="400" alt="image" src="https://user-images.githubusercontent.com/5380174/264984078-5805cbf5-7e64-4a0e-a2c0-1d9656b84dd6.png">

대충이렇게됨.

## 사용법

요약: [이거](https://gist.githubusercontent.com/hibiyasleep/9e54a4aacb014faa3dc96cd78a1ad2cc/raw/index.css?v=1.10) 복사해서 OBS 브라우저 속성에 CSS에다 던지세요

1. OBS에 브라우저를 추가하세요.
2. URL을 선생님의 티어표로 맞추세요.
3. (선택, 하면좋음) '상호작용'을 열어서 v-archive에 로그인하세요.
4. [여기 있는 CSS 코드](https://gist.githubusercontent.com/hibiyasleep/9e54a4aacb014faa3dc96cd78a1ad2cc/raw/index.css?v=1.10)를 싹 긁어서 복사하세요.
5. 브라우저 속성을 열고, '사용자 지정 CSS' 섹션에 통째로 붙여넣으세요.
6. (선택) 원하시는 대로 옵션 숫자나 폰트를 조정하시면 OK

![image](https://user-images.githubusercontent.com/5380174/264958921-183b781b-373e-4f5d-aac8-ba2a37f2b5ae.png)

대충뭐이렇게

![image](https://user-images.githubusercontent.com/5380174/265020134-f799e0f6-6f75-43de-89be-4fa3c49f89eb.png)

왼쪽위에 커서올리면 버튼전환이 떠요.

---

### 커스텀
`:`랑 `;` 사이 값을 조절하면 됩니다.

- font-size
  - 글자크기입니다. 기본 20px
- row-height
  - 한 줄 높이입니다. 기본 36px
- font
  - 폰트입니다. `'폰트명', '폰트명'` 식으로 작은따옴표로 묶어서 적으세요
- numeric-font
  - 숫자 폰트인데 어긋날수도 있음  
    왠만하면 바꾸지 말아보시고 바꾸실거면 Lato 부분만 바꾸세요
- color-뭐시기
  - 제곧내. `#rgba` `#rrggbbaa` `rgba(0, 0, 255, 1)` …
- order-뭐시기
  - 순서가 이 숫자를 바꿔줍니다. 아무 숫자나 괜찮음
- display-뭐시기
  - 특정 항목을 가려줍니다.  
    양옆의 `/*`와 `*/`를 지우면 그 항목이 가려짐  

## 면책조항

* 이 스타일시트는 v-archive.net 티어표를 방송용으로 예쁘게 표시하기 위한 것입니다.
* v-archive.net으로부터 허가/승인받은 것이 아니며, 그럴 필요도 크게 없고, 이 파일의 제작자가 그 쪽에 대해 아무런 관계나 책임은 없음을 이해해주세요.  
  = 그 쪽으로 민원 보내지 마세요!!
  
## 변경기록

* 1.10 (2023/09/04)
  * 이미지 상대경로로 가져오던 바보짓 수정
* 1.9 (2023/09/03)
  * `@import` 버그 수정
* 1.8 (2023/09/03)
  * NEW! 딱지 추가
* 1.7 (2023/09/02)
  * 코드 가져오기를 `@import`로 변경
* 1.6 (2023/09/02)
  * 레이팅 소수점 아래 끝전이 0인 경우에 대응
* 1.5 (2023/09/02)
  * 산정레벨 없는거 또 고장나서 수정
* 1.4 (2023/09/01)
  * 로그인 안 했을때 헤더 배경이 투명한 문제 수정
  * 버튼전환 추가
* 1.3 (2023/09/01)
  * OBS 브라우저(Chrome 103)에서 헤더 배경이 안 뜨는 문제 수정  
    이게 뭐하는 짓이지
* 1.2 (2023/09/01)
  * OBS 브라우저(Chrome 103)에서 '정식 레벨' 표시가 이상해지는 문제 수정 