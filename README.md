# Parcel Bundler Basic

- Parcel 번들러를 활용해 개발시 필요한 프레임워크, 라이브러리 등의 결과를 변환관리에 대해 알아보았다.

<br/>

- **Parcel Plugin static files copy**
  - img, favicon 같은 변환이 필요하진 않지만 변환된 파일을 저장하는 dist 폴더에 들어가야 인식하므로, 자동으로 특정 파일을 복사해서 dist 폴더에 넣어주는 플러그인에 대해서 알아봄

<br/>

- **SCSS**
  - SCSS의 경우 parcel이 설치 되면 알아서 해당 변환 패키지를 설치하여 따로 설정이 필요하진 않았음

<br/>

- **PostCSS**
  - autoprefixer
  - CSS 전처리로 낮은 버전의 브라우저를 위한 CSS로서 venderperfix를 붙여주는 autoprefixer에 대해서 알아봄

<br/>

- **Babel**
  - ES5의 낮은 버전의 브라우저 JS 문법을 제공하는 경우를 위한 JS 파일 변환 작업으로 Babel에 대해서 알아봄
