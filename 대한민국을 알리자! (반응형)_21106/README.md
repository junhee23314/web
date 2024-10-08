# 대한민국을 알리자!
![gif(1)](https://github.com/junhee23314/web/blob/main/%EB%B0%98%EC%9D%91%ED%98%95%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EB%A7%8C%EB%93%A4%EA%B8%B0_21106/gif(1).gif)

이 프로젝트는 대한민국의 다양한 문화적 요소들을 소개하기 위한 웹 페이지입니다. 이 반응형 웹 페이지는 대한민국의 대한 정보를 제공합니다.

## 프로젝트 구조⚙️


### 사용된 기술🔧

- `html`
- `css`


### 코드 핵심내용✨

**1.** css
```
@media (max-width: 768px) {
  .text-box, .box, .box2, .box3, .box4, .box5 {
    width: 95%;
    padding: 15px;
  }

  .nav ul {
    flex-direction: column;
  }

  .nav ul li a {
    padding: 10px 0;
  }
  .box img, .box2 img, .box3 img, .box4 img, .box5 img {
    max-width: 100%;
    height: auto;
  }
}

```
다양한 화면 크기에 맞춰 레이아웃을 조정하여 모바일 친화적인 웹 페이지를 만듭니다. 이 코드는 작은 화면에서 각 요소가 잘 보이도록 합니다.

![gif(2)](https://github.com/junhee23314/web/blob/main/%EB%B0%98%EC%9D%91%ED%98%95%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EB%A7%8C%EB%93%A4%EA%B8%B0_21106/gif(2).gif)
- **max-width**: 768px는 화면 너비가 768픽셀 이하일 때 적용됨을 의미합니다.
- `.text-box`, `.box`, `.box2`, `.box3`, `.box4`, `.box5` 요소들의 너비를 95%로 설정하고, 패딩을 15px로 줄였습니다.
- `.nav ul`의 방향을 수평에서 수직으로 바꾸었습니다.
- `.nav ul li a`의 패딩을 상하 10px로 조정하여 항목 간의 간격을 더 넓혔습니다.
- `.box img`, `.box2 img`, `.box3 img`, `.box4 img`, `.box5 img`의 너비를 100%로 설정하고, 높이를 자동으로 조정하여 이미지가 부모 요소에 맞게 줄어들도록 했습니다.

---

**2.** css
```
.box, .box2, .box3, .box4, .box5 {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 80%;
  max-width: 300px;
  margin: 50px auto;
  padding-inline: 120px;
  padding-top: 20px;
  padding-bottom: 20px;
  border-radius: 15px;
  color: white;
  text-align: center;
}

.box { background-color: #DDE7E7; }
.box2 { background-color: #D77964; }
.box3 { background-color: #EBBC6B; }
.box4 { background-color: #6979BB; }
.box5 { background-color: #733E7F; }

```
각 콘텐츠 박스에 스타일을 부여하여 일관된 디자인을 유지합니다.

- **공통 스타일링**: .box, .box2, .box3, .box4, .box5 클래스에 대해 공통적으로 적용되는 스타일을 정의합니다. 이를 통해 레이아웃의 일관성을 유지합니다.

- **개별 스타일링**: 각 상자에 대해 다른 배경색을 적용하여 시각적인 구분을 줍니다.

---

**3.** html
```
<div class="dropdown">
  <span><img src="image/국화.png" alt="무궁화"></span>
  <div class="dropdown-content">
    <p>법률상으로는 무궁화를 국화로 인정할 근거가 없으나, 행정안전부 홈페이지에서 한국의 국화라고 명시해 두었고,
    1963년 제정된 나라문장에서 무궁화 형태가 반영되는 등 보편적으로 무궁화가 상징적인 꽃으로 인식된다.
    <p><a class="custom-link" href="https://www.mois.go.kr/chd/sub/a05/mugunghwa1/screen.do">더 자세히 알아보기✨</a></p>
    </p>
  </div>
</div>

```
드롭다운 메뉴는 인터랙티브 요소로서 중요한 역할을 합니다.

![gif(3)](https://github.com/junhee23314/web/blob/main/%EB%B0%98%EC%9D%91%ED%98%95%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EB%A7%8C%EB%93%A4%EA%B8%B0_21106/gif(3).gif)
- **드롭다운 구조**: div 태그를 사용하여 드롭다운 메뉴를 구성합니다.
- **드롭다운 내용**: .dropdown-content 클래스 안에 표시될 내용을 정의합니다.
- **호버 효과**: CSS에서 display: none으로 숨겨둔 내용을 hover 상태에서 보이게 설정합니다.


### 소감 및 느낀 점✏️

 `대한민국을 알리자!`라는 웹페이지를 만들어 그 웹페이지를
 반응형 웹페이지로 변경하여 웹을 만든다는 게 엄청 재미있었고 신선했습니다.
 일단 코드를 만들 때 기본적으로 tcp 스쿨(웹사이트), chatgpt를 사용하였고
 색상을 사용할 때면 한국 전통 색상 코드표를 참고하였습니다.
 어려웠던 점은 코드를 아직 낯설다 보니 몹시 어려웠고 헤매는 것 같습니다
 그렇지만 미디어 쿼리에 대해 알게 되었습니다.
```
@media (조건) {
  <!-- ====================스타일====================  -->
}
```
이와 같이 스타일 부분에는 일반적인 CSS 코드가 들어가는데, 조건 부분이 만족할 때는 스타일이 적용되고, 만족하지 않을 때는 스타일이 무시하게 됩니다. 아직 많이 부족하지만, 이 과정을 통해 더 알아갔던 것 같던 것 같아, 좋았습니다.
물론 아쉬웠던 점도 있습니다. 화면을 줄였을 때 밑에 이미지 때문에 잘리는 버튼이 좀 아쉬웠습니다.
보완할 방법을 생각해 봐야겠습니다.
![이미지1](https://github.com/junhee23314/web/blob/main/%EB%B0%98%EC%9D%91%ED%98%95%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EB%A7%8C%EB%93%A4%EA%B8%B0_21106/%EC%9D%B4%EB%AF%B8%EC%A7%801.png)

역시 많이 부족하지만 하나하나 알아가며 반응형 웹페이지 만드니까 굉장히 재미있었다.

**[대한민국을 알리자!(초안 웹페이지) 바로가기](https://github.com/junhee23314/web/tree/main/%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%9D%84%20%EC%95%8C%EB%A6%AC%EC%9E%90!_21106)**

