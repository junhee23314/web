## **Let's promote Korea!**
![영상1](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/%EC%98%81%EC%83%811.gif)

주제는 "대한민국을 알리자!"로 대한민국의 아름다운 전통과 상징들을 알려주는 웹페이지를 만들어보았다😊

Language: `html`, `css`
## 프로젝트설명👾

### 코드 내용 설명

#### HTML 코드

1. **기본 설정**:

```
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Myeongjo&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>대한민국을 알리자!</title>
</head>
<body>
```  
    - `<!DOCTYPE html>`: HTML5 문서 타입을 선언.
   - `<html lang="ko">`: 문서의 언어를 한국어로 설정.
   - `<meta charset="UTF-8">`: 문서의 문자 인코딩을 UTF-8로 설정.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: 뷰포트 설정으로 반응형 웹 디자인 지원.
   - Google Fonts에서 "Nanum Myeongjo" 글꼴을 불러와 사용합니다.

2. **페이지 구조**:

   ```
     <img class="img-container" src="image/표지.png" >
   

    <div class="bg-image">
       <nav>
    
        <div>
            <!-- nav 적용  -->
            <ul class="nav">
                <li>
                    <a href="#">Home</a>
                </li>
                <li>
                    <a href="#">Link1</a>
                </li>
                <li>
                    <a href="#">Link2</a>
                </li>
                <li>
                    <a href="#">Link3</a>
                </li>
                <li >
                    <a href="#">Link4</a>
                </li>
                <li>
                    <a href="#">Link5</a>
                </li>
            </ul>
       </nav>
   ```
   - 상단에 대한민국을 소개하는 이미지 삽입.
   - 네비게이션 바를 통해 다양한 링크 제공.
---
    
```
  <!-- 텍스트 상자 -->
      <div style="padding: 50px;">

          <div class="text-box" >
          <h2>국기</h2>
            <p>흰색 바탕은 밝음과 순수, 평화를 사랑하는 민족성을 나타내며, 태극 문양은 음(파란색)과 양(빨간색)의 조화를 나타낸 것으로,<br>
            우주 만물이 음양의 조화로 인해 생명을 얻고 발전한다는 대자연의 진리를 표현해낸 것이다.</p>
            <p><a class="ap"href="https://www.mois.go.kr/chd/sub/a05/birth/screen.do">더 자세히 알아보기✨</a></p>
        </div>

      </div> 
```
   - 텍스트 상자를 통해 대한민국의 국기 정보를 제공.
---
  ```
<!-- 동그라미 이미지 -->
    
    <div class="circle-image">
        <img class="profile" src="https://emojis.wiki/thumbs/emojis/south-korea.webp">
            </div>
```
   - 원형 이미지를 통해 대한민국을 상징하는 이미지 제공.
---
```
 <div class="bg_image2" style= "margin:30px; height: 300px; overflow-y: auto ">
        
        <div style="height: 200px; padding: 5px;">
            <div class="box">
            <h2>국화🌺</h2>   
            
            <p> 법률상으로는 무궁화를 국화로 인정할 근거가 없으나, 행정안전부 홈페이지에서 한국의 국화라고 명시해 두었고, 
                1963년 제정된 나라문장에서 무궁화 형태가 반영되는 등 보편적으로 무궁화가 상징적인 꽃으로 인식된다.</p>
                <p><a class="ap"href="https://www.mois.go.kr/chd/sub/a05/mugunghwa1/screen.do">더 자세히 알아보기✨</a></p> </div>
```
   - 배경 이미지와 정보 상자를 통해 다양한 대한민국 문화 요소 소개.
   - 동일하게 적성 
---
![영상3](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/%EC%98%81%EC%83%813.gif)


**-> 요게 html만 넣은 모습입니다😶‍🌫️**









#### CSS 코드

1. **글로벌 스타일**:
   - 모든 요소에 기본 폰트와 스타일 설정.
   - 리스트 스타일과 텍스트 장식을 제거하고, 여백과 패딩을 0으로 설정.
```
    *{
  font-family: "Nanum Myeongjo", serif;
  font-weight: 400;
  font-style: normal;
  list-style: none;
  text-decoration: none;
  border-collapse: collapse;
  margin: 0px;
  padding: 0px;
  color:#000;
}
```
---
2.**이미지 컨테이너**:
  - img-container 클래스: 이미지 컨테이너의 너비를 뷰포트 너비의 100%, 높이를 뷰포트 높이의 60%로 설정.
```
.img-container {
  width: 100vw;
  height: 60vh;
  
}

<!-- ---------------------------------------------------------------------
vw(viewport width), vh(viewport height) 사용
%가 부모 요소의 길이를 기준으로 계산된다면,
vw, vh는 뷰포트의 길이를 기준으로 계산.

각각 뷰포트 가로길이의 몇% 인지와 세로길이의 몇% 인지를 적어주면 됩니다.
뷰포트란 해당 웹페이지를 실행하고 있는 기기(노트북, 스마트폰 등)의 화면크기를 말한다. -->
```
---
3. **링크 스타일**:
   - `ap` : 배경색과 텍스트 색상, 폰트 크기 설정.
```
.ap {
  background-color: #FFFFE0;
  color: darkslategray ;
  font-size: 1.3em;
  text-decoration: none;
}

```

---
4. **배경 이미지**:
   - `bg-image`와 `bg_image2` 클래스: 각각 다른 배경 이미지를 설정.
```
.bg-image{
  background-image:url("image/뒷배경.jpg  ")
  
}

.bg_image2{
  background-image:url("image/뒷배경_.jpg  ")
}
```
---
5. **헤더와 네비게이션**:
   - `header` 클래스: 페이지 상단의 헤더 스타일 설정.
   - `nav`와 `nav ul li a` 클래스: 네비게이션 바와 링크 스타일 설정.
```
.header{
  width : 100%;
  height : 80px;
  background-color : blue;
  color :#ffffff;
  text-align : center;    
  line-height: 80px;
  
}

.nav{
  width : 100%;
  height : 40px;
  background-color : #D8C8B2;
  color :#ffffff;
  line-height: 40px;

}

nav ul li  a{
    float : left; padding : 0 10px;
  
  }     
```

---
6. **텍스트 상자**:
   - `text-box` 클래스: 국기 정보를 담는 상자의 스타일 설정.
```
.text-box {
   border: 5px;
   border-radius: 5px;
   padding: 30px;
   float: right;
   margin: 15px;
   margin-right: 300px;
   background-color: #ffffff;
}

```
---
7. **원형 이미지**:
   - `circle-image`와 `profile` 클래스: 원형 이미지와 프로필 이미지 스타일 설정.
```
.circle-image {
    
    width: 150px;
    height: 150px; 
    border-radius: 70%;
    overflow: hidden;

  }
.profile {
  
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```
---
8. **정보 상자**:
   - `box`, `box2`, `box3`, `box4`, `box5` 클래스: 각각 다른 배경색과 스타일을 가진 정보 상자 설정.
```
.box{
    
  width: 300px;
  background-color: #DDE7E7;
  margin-left: 10px;
  padding: 20px;
  border-radius: 5px;
  margin-left: auto;
  margin-right: auto;
  color: white;
  text-align: center;
   
}

--- `box2`, `box3`, `box4`, `box5`도 background-color만 바뀌고 나머지는 동일. ---
```
![영상1](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/%EC%98%81%EC%83%811.gif)
-> 처음에 보았던것 처럼 html에 css 입힌모습


__[텍스트 상자 & 정보 상자]__
![영상2](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/%EC%98%81%EC%83%812.gif)
링크를 걸어 클릭 시 해당 사이트로 이동.

### 핵심 내용 요약💡

1. **HTML 기본 구조**:
   - 문서 타입, 언어, 문자 인코딩, 뷰포트 설정.
   - 외부 리소스 (Google Fonts, CSS 파일) 불러오기.

2. **페이지 레이아웃**:
   - 상단 이미지, 네비게이션 바, 텍스트 상자, 원형 이미지, 정보 상자들로 구성.

3. **CSS 스타일**:
   - 기본 폰트와 스타일, 링크 스타일, 배경 이미지, 헤더와 네비게이션 바 스타일.
   - 텍스트 상자와 원형 이미지 스타일.
   - 정보 상자 스타일 (다양한 배경색 사용).


### 소감 및 느낀 점✏️
![ClipWindowsGIF](https://github.com/junhee23314/Let-s-promote-Korea/assets/127848243/8269a124-68b8-44c5-94d6-1b3f103f0c89)

확실히 처음 계획을 짜고 만들다 보니 어떻게 만들어야 하다가 일단 만들었는데 생각보다 훨씬 더 못 나오고 구려서 조금 속상했다.

이 경험을 통해 웹페이지를 보토대로 반응형 웹페이지 만들어야겠다는 생각이 들었다

어려웠던 점은 동그라미 이미지(태극기 이미지)와 텍스트 상자가 서로서로 너무 안 친해져서 문제점이 뭔지 한번 알아봐야겠고

이 웹페이지 만들면 서의 결론은 위치를 지정해 주는 게 아직 미숙해서 몹시 어려웠다. 비록 많이 부족한 나의 첫 웹페이지이다.🫨

**대한민국을 알리자!(반응형 웹페이지) 바로가기 ⬇️**
https://github.com/junhee23314/web/tree/main/%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%9D%84%20%EC%95%8C%EB%A6%AC%EC%9E%90!_%EB%B0%98%EC%9D%91%ED%98%95%20%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80
