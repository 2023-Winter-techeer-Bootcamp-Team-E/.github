<style>
  .highlighted-text {
    text-align: center;
    font-size: 22px; /* 원하는 크기로 조절하세요 */
    color: #87CEEB; /* 하늘색으로 변경 */
    /*font-family: 'Comic Sans MS'*/
  }
</style>

<h1 align="center">
    🐹 HaruCalendar 🐹
</h1>


<div align="center" style="font-size:18px"> 
<b>Let’s Share Diaries and Decorate Together! </b> </div>
<p align="center">

</p>

<p align="center">
  <img width="500" alt="image" src="./images/intro.webp">
</p>


## 🎨 Introduce

<table width="1200px">
    <thead>
    </thead>
    <tbody>
    <tr>
         <td width="600" align="center">
            <img width="300" alt="image" src="./images/intro2.png">
        </td>
        <td width="600" align="center">
            <div align="left">
<br/>
              
<p class="highlighted-text">🌤️그날의 생각, 감정, 경험을 공유하며 다른 사람들과 하루를 연결해보세요!🌤️</p>

<br><br>“하루연결”은 서로가 실시간으로 연결되어 하나의 일기장에서 각자의 일기를 남기고 다양한 스티커로 일기를 꾸밀 수 있는 웹 플랫폼입니다.
<br><br>작성한 일기 내용에서 키워드를 추출하여 AI 스티커를 활용해 일기장을 꾸밀 수 있습니다.
<br><br>어떤 글을 작성하는지, 어떤 스티커로 일기장을 꾸미는지를 실시간으로 확인할 수 있습니다. 
<br/><br/>




</br>
</div>
</tr>
</tbody>
</thead>
</table>

<br>
<br>
<br>


## 🌈 Feature

### 회원가입 및 로그인 <br>
<p align="left">


<img width="700" alt="image" src="./images/signup.gif">
<img width="700" alt="image" src="./images/login.gif">
<br>
<br>

###   캘린더 꾸미기 및 다이어리 생성
- 제공 되어지는 기본스티커로 캘린더를 꾸밀 수 있습니다
- 웹소켓 이용 gif 들어 갈 예정

<img width="700" alt="image" src="./images/calendarcreate.gif"> <br>

- 다이어리 작성 아이콘을 누르면 다이어리 배경지 및 친구와 다이어리를 공유할 수 있는 링크가 생성됩니다. 

<img width="700" alt="image" src="./images/diarycreate.gif">

<br>
<br>

###  다이어리 꾸미기 및 다이어리 작성<br>
- 공유한 링크를 친구들에게 보내 친구와 함께 세상에 하나밖에 없는 다이어리를 작성 해 보세요~!

<img width="700" alt="image" src="./images/diary.gif">

<br>

- 친구들과 다이어리를 작성 후 제공되어지는 기본스티커를 이용하여 다이어리를 꾸미고 "저장"을 누르면 기본적인 작성이 완료가 됩니다.

<img width="700" alt="image" src="./images/diary.gif">
<br>
<br>

### 스티커 붙히기<br>
- 다이어리에 작성되어진 키워드를 AWS Comprehend가 자연어 처리를 통하여 가장 많이쓰인 키워드 2개를 뽑아줍니다.
- 뽑아진 키워드를 바탕으로 Dall-e 3 가 세상에 하나 밖에 없는 스티커를 만들어 드립니다.

  
<img width="700" alt="image" src="./images/stickerscreate.gif">
</p>
<br>
<br>


<!-- ## 📹 [Demo](<(https://www.youtube.com/watch?v=RCUEUDk4sVw)>) -->

<br>
<br>

## 🛠 ️System Archtecture
<p align="left">
<img width="700" src="./images/archtecture.jpg">
</p>

## 🔑 ERD
<p align="left">
<img width="700" src="./images/ERD.png">
</p>

## 💻 Tech Stack

<div align =center>

분야| 사용 기술|
:--------:|:------------------------------:|
**Fronted** | <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/zustand-F3DF49?style=for-the-badge&logo=zustand&logoColor=white"> <img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=black"> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=Prettier&logoColor=white"/> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=ESLint&logoColor=white"/> 
**Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/channels-092E20?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Daphne-009639?style=for-the-badge&logo=&logoColor=white">
**DevOps** |<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=amazon%20rds&logoColor=black"> <img src="https://img.shields.io/badge/Amazon Comprehend-527FFF?style=for-the-badge&logo=amazon%20rds&logoColor=black"> <img src="https://img.shields.io/badge/Dalle 3-412991?style=for-the-badge&logo=OpenAi%20rds&logoColor=black"> <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white">
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src = "https://img.shields.io/badge/cadvisor-1478FF?style=for-the-badge&logoColor=black"> ![node-exporter](https://img.shields.io/badge/node_exporter-37D100?style=for-the-badge&logoColor=black) ![Elastic Stack](https://img.shields.io/static/v1?style=for-the-badge&message=Elastic+Stack&color=005571&logo=Elastic+Stack&logoColor=FFFFFF&label=)
**etc** | ![Slack](https://img.shields.io/static/v1?style=for-the-badge&message=Slack&color=4A154B&logo=Slack&logoColor=FFFFFF&label=) ![Notion](https://img.shields.io/static/v1?style=for-the-badge&message=Notion&color=000000&logo=Notion&logoColor=FFFFFF&label=) ![Figma](https://img.shields.io/static/v1?style=for-the-badge&message=Figma&color=F24E1E&logo=Figma&logoColor=FFFFFF&label=) ![Postman](https://img.shields.io/static/v1?style=for-the-badge&message=Postman&color=FF6C37&logo=Postman&logoColor=FFFFFF&label=) ![GitKraken](https://img.shields.io/static/v1?style=for-the-badge&message=GitKraken&color=179287&logo=GitKraken&logoColor=FFFFFF&label=) <img src="https://img.shields.io/badge/Zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=white">
)
</div>

***


| **Category**           | **Technologies**                                           |
|------------------------|------------------------------------------------------------|
| **Frontend**           | Vite, JavaScript, React, Zustand, Styled-Components, Prettier, Eslint |
| **Backend**            | Django, MySQL, Redis, Channels, Daphne                     |
| **Web Server**         | Nginx                                                      |
| **Asynchronous**       | Celery, Rabbitmq                                           |
| **Database**           | AWS RDS, AWS S3 Bucket MySQL, Redis                        |
| **AI**                 | AWS Comprehend, Dall-E 3                                    |
| **Deployment**         | AWS EC2, Docker                                             |
| **API Test**           | Postman                                                    |
| **API Documentation**  | Swagger                                                    |
| **Others**             | Github, Notion, Zoom, Slack, Figma                         |




<br>
<br>
<br>

## 📗 API

### 일기, 유저 관련 API

<img width="1212" alt="image" src="./images/swagger.png"><br>

| Calendars API | Diaries API |Members API|Static API|                                                                                                                                                                             
|---------------|-------------|--|----|
| api/v1/calendars/ : 캘린더 조회 <br>api/v1/calendars/stickers : 캘린더 꾸미기 및 캘린더 생성  |   api/diaries/: 일기 배경지 선택 및 생성<br>api/diaries/link: 작성중인 일기 및 일기링크 조회.<br>api/diaries/save: 일기 최종저장.<br>api/diaries/stickers: 텍스트박스에서 키워드 추출 후 스티커 생성<br>api/diaries/<int:diary_id>: 일기 목록 조회          |api/v1/members/login : 사용자 정보 확인, 로그인<br>api/v1/members/logout: 로그아웃<br>api/v1/members/signuo : 회원가입|api/v1/static/stickers : 캘린더 및 다이어리 기본 배경지 조회|

                                                                                                                                                                      |
  <br>

## 🐳 How to start

### 1. clone the repository



<br>
<br>
<br>

## 👨‍💻 Members


| [정우희](https://github.com/Joy0w0)         | [정유진](https://github.com/GaBaljaintheroom)  | [조진우](https://github.com/alswlfl29)          | [이동우](https://github.com/gs0428)            | [이도경]()                                     | [강정현]()                                     | [김우성]()                                     
|------------------------------------------|---------------------------------------------|----------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| <img width=520  src="./images/jwh.jpeg"> | <img width = "520" src ="./images/jyj.jpg"> | <img width = "520" src ="./images/jjw.jpeg"> | <img width = "520" src ="./images/ldw.png"> | <img width = "520" src ="./images/ldg.png"> | <img width = "520" src ="./images/gjh.jpg"> | <img width = "520" src ="./images/kws.JPG"> |
| Leader, frontend, DevOps                 | frontend                                    | frontend                                     | Backend, DevOps                             | Backend                                     | Backend                                     | Backend                                     |

