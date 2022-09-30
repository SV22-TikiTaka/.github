# Tiki-Taka
![horizontal_logo](https://user-images.githubusercontent.com/78634177/193130185-89066c4b-7159-4eec-ba8b-85b43bddb091.png)
<br>

## Introduction
인스타그램 스토리 공유를 기반으로 한 리액트 네이티브 앱 <br>
컨텐츠를 생성하고 스토리에 공유를 하며 내 인스타그램 친구들과 소통하는 플랫폼<br><br>
티키타카와 함께 무엇이든 말해봐
**아무도 모르게🤫**

Hey, Literally tell me anything! It's anonymous anyways 😏
## System Architecture
<img width="100%" height="100%" alt="SA" src="https://user-images.githubusercontent.com/96862049/192411588-3268a582-678c-4af8-b1e0-2591f2e26564.png">

<br>

## 📚 TECH STACKS

|Frontend|Backend|Monitoring|DevOps|
|:------:|:---:|:---:|:---:|
|<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"><br><img src="https://img.shields.io/badge/React Native-61DAFB?style=for-the-badge&logo=React&logoColor=white">|<img src="https://img.shields.io/badge/uvicorn-DD0031?style=for-the-badge&logo=Gunicorn&logoColor=white"><br><img src="https://img.shields.io/badge/FastAPi-009688?style=for-the-badge&logo=FastAPi&logoColor=white"><br><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><br><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"><br><img src="https://img.shields.io/badge/Swagger-85EA2D.svg?style=for-the-badge&logo=Swagger&logoColor=white">|<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white"><br><img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white">|<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"><br><img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon LightSail-F46800?style=for-the-badge&logo=Amazon LightSail&logoColor=white">| 

<br><br>



## Installation 

> Clone Repository
```
git clone https://github.com/SV22-TikiTaka/docker.git
```
<br>

> Set .env in the docker folder
```
TZ=Asia/Seoul
MYSQL_USER=
MYSQL_ROOT_PASSWORD=
MYSQL_PASSWORD=
MYSQL_HOST=db
MYSQL_PORT=3306
MYSQL_DATABASE=tikitaka
INSTA_APP_ID=
AWS_ACCESS_KEY_ID=
AWS_SECRET_KEY=
AWS_S3_BUCKET_NAME=tikitaka-s3
INSTA_APP_SECRET_ID=
```
<br>


>Run deployment env.
```
cd docker/frontend-web/
yarn install
cd ..
docker-compose up --build
```
<br>

## Features

<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
    <th>Login</th>
    <td width="450" align="center">
         <img width="70%" justify="center" src = 'https://user-images.githubusercontent.com/78634177/193348187-19189046-0ebb-43d5-b7d5-1370700e239f.gif'/>
    </td>
     <td width="450" align="center">
         인스타그램 로그인 API를 이용하여 앱 로그인 구현<br><br>
         토큰을 통해 로그인여부를 결정
    </td>
    </tr>
     <tr>
    <th>Create Contents</th>
    <td width="450" align="center">
         <img width="70%" justify="center" src = 'https://user-images.githubusercontent.com/78634177/193349174-c3b943e9-4010-48ca-b487-70214b553c1a.gif'/>
    </td>
     <td width="450" align="center">
         Anything, Challenge, Vote 세가지 형식으로 컨텐츠 생성기능 <br><br>
         컨텐츠 생성 후 인스타그램 스토리로 공유 가능
    </td>
    </tr>
    <tr>
    <th>History Page</th>
    <td width="450" align="center">
         <img width="70%" justify="center" src = 'https://user-images.githubusercontent.com/78634177/193348187-19189046-0ebb-43d5-b7d5-1370700e239f.gif'/>
    </td>
     <td width="450" align="center">
        인스타그램 스토리에 있는 컨텐츠의 링크를 통해 인스타그램 팔로워들로부터 받은 답변을 모아놓는 페이지
    </td>
    </tr>
     <tr>
    <th>DarkMode</th>
    <td width="450" align="center">
         <img width="70%" justify="center" src = 'https://user-images.githubusercontent.com/78634177/193352498-5649e744-950c-4153-943c-5d46d969017f.gif'/>
    </td>
     <td width="450" align="center">
         Settings 페이지에서 토글을 통해 타크모드 설정 가능 <br><br>
         앱 전역으로 모든 페이지에 다크모드 구현 
    </td>
    </tr>
     <tr>
    <th>Web Reply</th>
    <td height="450" align="center">
         <img width="100%" justify="center" src = 'https://user-images.githubusercontent.com/78634177/193355616-456b5f3b-b80d-4c41-b6c4-c1fddca6de24.PNG'/>
    </td>
     <td width="450" align="center">
         앱사용자가 공유한 컨텐츠의 링크를 통해 웹에서 답변 가능 <br><br>
         컨텐츠 공유 전 받는 답변의 형식 옵션 선택에 따라 웹 컴포넌트 
    </td>
    </tr>
    </tbody>
    </table>
  

## Our Team
<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>Pictures</th>
         <td width="100" align="center">
            <a href="https://github.com/yjshin229">
                <img src="https://user-images.githubusercontent.com/78634177/193137406-9d425c51-35f2-4768-9be8-0233a89dbdb4.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Leeseunghwan7305">
                <img src="https://user-images.githubusercontent.com/78634177/193137358-4e2d0f79-1fc7-4c2e-9eac-5091f4e85493.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/JeongHunHui">
                <img src="https://user-images.githubusercontent.com/78634177/193137351-ae31e1f6-47db-4220-82d1-bf4eed284f76.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/kjeongh">
                <img src="https://user-images.githubusercontent.com/78634177/193137560-ffc50297-28ee-4322-abe1-ceee1b8b5fe6.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/kimhalin">
                <img src="https://user-images.githubusercontent.com/78634177/193137395-c93317eb-b0e8-4228-b031-7bb95c6ec97d.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/dbrjs4594283">
                <img src="https://user-images.githubusercontent.com/78634177/193137343-4c6428e0-8079-4dbd-8f15-0d2d838c8715.png" width="60" height="60">
            </a>
        </td>
    </tr>
    <tr>
        <th>Name</th>
        <td width="100" align="center">신영진</td>
        <td width="100" align="center">이승환</td>
        <td width="100" align="center">정훈희</td>
        <td width="100" align="center">김정현</td>
        <td width="100" align="center">김하린</td>
        <td width="100" align="center">유건</td>
    </tr>
    <tr>
        <th>Position</th>
        <td width="150" align="center">
            Frontend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Backend<br>
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/yjshin229">
                <img src="http://img.shields.io/badge/yjshin229-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Leeseunghwan7305">
                <img src="http://img.shields.io/badge/Leeseunghwan7305-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/JeongHunHui">
                <img src="http://img.shields.io/badge/JeongHunHui-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/kjeongh">
                <img src="http://img.shields.io/badge/kjeongh-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/kimhalin">
                <img src="http://img.shields.io/badge/kimhalin-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/dbrjs4594283">
                <img src="http://img.shields.io/badge/dbrjs4594283-green?style=social&logo=github"/>
            </a>
        </td>
     </tr>
    </tbody>
</table>

---
