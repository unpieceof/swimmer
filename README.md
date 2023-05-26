# Swimmer - twitter clone project

Vuejs + Firebase 학습을 위한 Twitter clone

![image](https://github.com/unpieceof/swimmer/assets/101758997/420b11ba-c660-4643-b09f-5da3202b9b39)


## Project setting

```bash
# Create vue-app
npm create vite@latest twitter-clone
cd twitter-clone
npm install
```

```bash
# Install tailwindscss, fontawesome
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
npm install fontawesome@latest
```

```bash
npm run dev
```

> tailwindcss 설치 참고 링크

[https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation)

## Trouble shooting

**2023-05-19** 사이드 메뉴 레이아웃 작성 중 flex를 줬는데도 적용되는 영역이 좁아지는 현상 발생  
(원인) vite로 create시 기본 세팅되는 style이 존재  
(조치) style.css의 모든 내용 삭제  
