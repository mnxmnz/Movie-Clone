<p align="center">
  <a href="https://github.com/mnxmnz/Movie-Clone">
    <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FqJB0z%2FbtqRpuCA14P%2FVh1ORgAJz16aSGGpNPRN1K%2Fimg.png" alt="Logo" width="100" height="100">
  </a>

  <h2 align="center">Movie Clone</h2>
</p>

## 📑 레포 소개

- Nomad Coders - ReactJS로 영화 웹 서비스 만들기 강의 실습 코드 정리 레포입니다.
- React와 Axios를 이용해서 API와 통신하는 실습을 진행했습니다.

## ✨ 주요 기능

![Movie Clone Web Main Page](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbanEuC%2FbtqQZxgKm8I%2FU35TCUDS5uG3s3P7UAWl60%2Fimg.png)

💡 HOME

  - [1] 실시간 랭킹 1위 ~ 10위 영화의 제목, 연도, 장르, 소개 정보 제공

💡 DETAIL

  - [1] HOME에서 영화를 클릭하면 해당 영화의 상세 정보 제공

💡 ABOUT

  - [1] 홈페이지 소개 글

## 🗂 프로젝트 구조

```
src
 ┣ components
 ┃ ┣ Movie.css
 ┃ ┣ Movie.js
 ┃ ┣ Navigation.css
 ┃ ┗ Navigation.js
 ┣ routes
 ┃ ┣ About.css
 ┃ ┣ About.js
 ┃ ┣ Detail.js
 ┃ ┣ Home.css
 ┃ ┗ Home.js
 ┣ App.css
 ┣ App.js
 ┗ index.js
```

## 🛠 사용 기술 및 라이브러리

| Front-End | Front-Server |
| --- | --- |
| React<br>Axios<br>React Router | Github Pages |

```
"@babel/core": "^7.12.9",
"@babel/preset-env": "^7.12.7",
"@testing-library/jest-dom": "^5.11.4",
"@testing-library/react": "^11.1.0",
"@testing-library/user-event": "^12.1.10",
"axios": "^0.21.1",
"gh-pages": "^3.1.0",
"prop-types": "^15.7.2",
"react": "^17.0.1",
"react-dom": "^17.0.1",
"react-router-dom": "^5.2.0",
"react-scripts": "4.0.1"
```

## 🖥 Local 실행 방법

#### [1] Yarn 설치

[Yarn 설치 바로가기](https://classic.yarnpkg.com/en/docs/install#windows-stable)

#### [2] Clone the Repo

```sh
git clone https://github.com/mnxmnz/Movie-Clone.git
```

```sh
cd Movie-Clone
```

#### [3] Install Packages

```sh
yarn
```

#### [4] Run the Project

```sh
yarn start
```

#### :open_file_folder: 참고

- [ReactJS로 영화 웹 서비스 만들기](https://nomadcoders.co/react-fundamentals)
