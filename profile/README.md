

# 🚾 급똥
<img width="980" alt="techeermarkte" src="https://github.com/user-attachments/assets/26e435aa-71c1-4856-852c-13fac79f52d6">


<br>

# 🚽 Introduction

| 사용자 위치 기반 공공 화장실 정보 제공 서비스 🏃🏻‍♀️
#####  URL 
| 🖥️ https://app.geubddong.com/

<br>
<br>

# 📚 Tech Stack

| Frontend | Backend | Database&Storage | DevOps | 
| --- | --- | --- | --- | 
| <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"> <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white"> ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) <br>![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black) <img src="https://img.shields.io/badge/zustand-orange?style=for-the-badge&logo=zustand&logoColor=white"> ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) | <br> ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) <br> ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803.svg?style=for-the-badge&logo=typeorm&logoColor=white) <br> ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)<br> ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)<br> |<img src="https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=AmazonRds&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge&logo=PostgreSQL&logoColor=white"><br>![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) <br> |<br> ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat&logo=docker&logoColor=white) ![Amazon EC2 Badge](https://img.shields.io/badge/Amazon%20EC2-F90?logo=amazonec2&logoColor=fff&style=for-the-badge) <br> ![Amazon Route 53 Badge](https://img.shields.io/badge/Amazon%20Route%2053-8C4FFF?logo=amazonroute53&logoColor=fff&style=for-the-badge) <br> ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)<br>  | <br>


<br>

# ⚙️ System Architecture

![시스템아키텍쳐](https://github.com/user-attachments/assets/462bbcb6-c782-4695-b508-fd4290ef3475)

<br>

# ⛺️ ERD
![ERD](https://github.com/user-attachments/assets/423a027c-9031-473b-a814-a7c49c10e184)



<br>



<br>

# 💻 Installation Process

> 

```
git clone --recursive <https://github.com/GeubDDong/Frontend.git>
git clone --recursive <https://github.com/GeubDDong/Backend.git>
```

<br>

> <b>Set .env in the backend folder </b>
> 

```
DB_TYPE=
DB_HOST=
DB_PORT=
DB_USERNAME=
DB_PASSWORD=
DB_DATABASE=
DB_SYNCHRONIZE=

DB_LOGGING=
REDIS_HOST=
REDIS_PORT=

KAKAO_HOST_NAME=
KAKAO_REST_API_KEY=
KAKAO_SECRET_KEY=
KAKAO_REDIRECT_URI=

JWT_SECRET=
JWT_EXPIRE_IN=

REFRESH_JWT_SECRET=
REFRESH_JWT_EXPIRE_IN=

CORS_ORIGIN=

GOOGLE_REST_API_KEY=
GOOGLE_SECRET_KEY=
GOOGLE_REDIRECT_URI=

NAVER_REST_API_KEY=
NAVER_SECRET_KEY=
NAVER_REDIRECT_URI=
```

<br>


# 🖼️ Demo

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/00ede9cc-3987-4fbd-b1a0-9e6b5a2c233b" width="150"/><br/>
      <strong>로그인 페이지</strong><br/>
      JWT를 이용한 소셜 로그인
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c735a074-f5be-4f72-9f91-29cb7aa77ce2" width="150"/><br/>
      <strong>로그아웃 페이지</strong><br/>
      JWT를 이용한 로그아웃
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ca32682d-058f-4629-b793-230c1e1deb48" width="150"/><br/>
      <strong>닉네임 설정 페이지</strong><br/>
      회원가입 시 자동으로 랜덤한 닉네임 제공 (수정가능)
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/46cc2772-ee2c-4aba-a2d2-e9c7902f9cc8" width="150"/><br/>
      <strong>마이페이지</strong><br/>
      즐겨찾기 목록, 댓글 작성 목록 선택하여 확인하는 페이지 
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b06dfad7-cced-4d1b-96f3-821b24d68dd3" width="150"/><br/>
      <strong>메인페이지</strong><br/>
      geolocation을 활용하여 현위치를 기반으로 주변 화장실을 조회
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/5cc47434-4e93-476a-bcaf-b738586396ca" width="150"/><br/>
      <strong>메인페이지</strong><br/>
      주소 검색 기능
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/91051466-19e3-489f-8bb7-142622b4b110" width="150"/><br/>
      <strong>메인페이지</strong><br/>
      상세 필터 기능, 즐겨찾기 기능
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/aa79b021-3337-462e-b38f-9b6e7761378d" width="150"/><br/>
      <strong>상세정보 페이지</strong><br/>
      화장실의 상세정보(개방시간, 전화번호 등)와 리뷰 제공
    </td>
  </tr>
</table>


# API
![Image](https://github.com/user-attachments/assets/6180c881-06a9-46dd-ac18-4c105e004508)


# 👥 Member 
<table width="1000">
    <thead>
        <tr>
            <th width="150">Name</th>
            <th width="100">송승수</th>
            <th width="100">김유라</th>
            <th width="100">김재원</th>
            <th width="100">유진이</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center"><b>Profile</b></td>
            <td align="center">
                <a href="https://github.com/goldapple-ce">
                    <img src="https://github.com/user-attachments/assets/46d60b32-455f-444b-93b5-8b6624c332b6" width="60" height="60">
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jiyoon0701">
                     <img src="https://user-images.githubusercontent.com/97827316/215991544-021c3e7a-460b-41a3-a030-2dca6bb0ac20.png" width="60" height="60">
            </td>
            <td align="center">
                <a href="https://github.com/TMInstaller">
                    <img src="https://github.com/user-attachments/assets/a06ca6de-e891-446b-ae6e-6c7626f335d4" width="60" height="60">
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/yura0302">
                    <img src="https://github.com/user-attachments/assets/dfe39f17-4aae-462d-8f95-2ac83b3c88d6" width="60" height="60">
                </a>
            </td>
        </tr>
        <tr>
            <td align="center"><b>Role</b></td>
            <td align="center">Leader<br>Backend</td>
            <td align="center">Backend<br>DevOps</td>
            <td align="center">Frontend<br></td>
            <td align="center">Frontend</td>
        </tr>
        <tr>
            <td align="center"><b>GitHub</b></td>
            <td align="center">
                <a href="https://github.com/GNOSss">
                    <img src="http://img.shields.io/badge/GNOSss-green?style=social&logo=github"/>
                </a>
            </td>
            <td align="center">
                 <a href="https://github.com/yura0302">
                    <img src="http://img.shields.io/badge/yura0302-green?style=social&logo=github"/>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/wellbird">
                    <img src="http://img.shields.io/badge/wellbird-green?style=social&logo=github"/>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/YooJini">
                    <img src="http://img.shields.io/badge/YooJini-green?style=social&logo=github"/>
                </a>
            </td>
        </tr>
    </tbody>
</table>
