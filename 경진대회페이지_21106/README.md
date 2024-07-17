## 경진대회웹페이지🖥️

![경진대회이미지(1)](https://github.com/junhee23314/web/blob/main/%EA%B2%BD%EC%A7%84%EB%8C%80%ED%9A%8C%ED%8E%98%EC%9D%B4%EC%A7%80_21106/%EA%B2%BD%EC%A7%84%EB%8C%80%ED%9A%8C%EC%9D%B4%EB%AF%B8%EC%A7%80(1).png)

이 웹페이지의 제목은 **"경진대회웹페이지"** 로 경진대회의 각종 설명들이 적여있는 나만의 가상 경진대회웹페이지 만들어보았다.

#### 사용된 기술🔧
- `HTML`
- `CSS`

## 코드설명
  
#### 전체코드
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>웨어러블 컴퓨터 경진대회</title>
<style>
* {
    box-sizing: border-box;
    text-align: center;
}
body {
    margin: 0;
    padding: 0;
}
ul, li {
    list-style: none;
    padding: 0;
    margin: 0;
}

#header {
    width: 765px;
    margin: 0 auto;
}

#menu {
    list-style-type: none;
    text-align: center;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

#menu li {
    margin-left: 5px;
    font-size: 20px;
    padding: 10px;
}

#bg_color_ {
    background-color: rgb(91, 168, 91);
}

#bg_color {
    background-color: gainsboro;
}

#main {
    width: 765px;
    margin: 0 auto;
    padding: 20px 0;
}

#main h1 {
    text-align: center;
}

#main p {
    border: 1px solid #000;
    width: 735px;
    margin: 10px auto;
    padding: 10px;
}

#main table {
    margin: 10px auto; 
    text-align: center;
    background-color: gainsboro;
    border-collapse: collapse;
    width: 400px;
}

#main table, #main th, #main td {
    border: 1px solid black;
}

#main th, #main td {
    padding: 10px;
}

#mission li {
    list-style: none;
    margin: 10px 0;
    padding-left: 40px;
    background-color: #ffffff;
    text-align: left;
}

#footer {
    text-align: center;
    background-color: blue;
    color: white;
    font-size: 15px;
    margin: 20px 0;
    padding: 10px 0;
}

</style>
</head>
<body>

<header id="header">
    <img src="image/경진대회표지.jpg" alt="경진대회표지">
</header>

<div id="bg_color_">
    <nav>
        <ul id="menu">
            <li><a href="#">행사개요 |</a></li>
            <li><a href="#">행사연혁 |</a></li>
            <li><a href="#">공지사항 |</a></li>
            <li><a href="#">자유게시판 |</a></li>
            <li><a href="#">참가접수 |</a></li>
        </ul>
    </nav>
</div>

<div id="bg_color">
    <section id="main">
        <h1>2024 제16회 웨어러블 컴퓨터 경진대회🖥️</h1>
        <h2>※대회 내용※</h2>
        <p>
            ※ 제시된 미션 중 한 가지를 골라 입는 컴퓨터를 직접 제작<br>
            본선 진출 팀에게는 시작품 제작비 100만원 지원<br>
            참가접수 기간 : 3.15 - 5.31
        </p>
        <h2>※대회 미션※</h2>
        <ul id="mission">
            <li>문화 : 문화생활을 즐기기 위한 웨어러블 컴퓨터</li>
            <li>교육 : 교육시장에서 사용될 웨어러블 컴퓨터</li>
            <li>건강 : 건강관리를 위한 웨어러블 컴퓨터</li>
        </ul>
        <h2>※시상 내역※</h2>
        <table>
            <tr>
                <th>순위</th>
                <th>상금</th>
            </tr>
            <tr>
                <td>대상</td>
                <td>500만원</td>
            </tr>
            <tr>
                <td>최우수상</td>
                <td>200만원</td>
            </tr>
            <tr>
                <td>우수상</td>
                <td>200만원</td>
            </tr>
        </table>
    </section>
</div>

<footer id="footer">
   성일정보 고등학교   
</footer>

</body>
</html>
```
