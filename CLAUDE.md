# 프로젝트 소개
포트폴리오 사이트입니다. 파일은 index.html, css/style.css, js/script.js, img/로 구성되어 있습니다.

# 스타일 작업 규칙
- 스타일은 css/style.css에만 쓰고, 내가 말하지 않으면 HTML은 바꾸지 않는다.
- 내가 요청한 영역과 요소의 스타일만 쓴다. 요청하지 않은 class(예: .blind)는 HTML에 있어도 규칙을 추가하지 않는다.
- 선택자가 여러 개여도 한 줄로 쓰고, 규칙 사이에 빈 줄을 넣지 않는다.
- HTML의 class 이름과 태그 구조는 바꾸지 않는다.
- transition, :hover, box-shadow, 고정(fixed) Header 같은 효과는 내가 요청하지 않으면 쓰지 않는다.
- @media(반응형)는 내가 요청할 때만 쓴다.
- 내가 요청하지 않은 CSS · JS 파일은 새로 만들지 않는다.

# 키 규칙
- secret 키(sb_secret_…)와 service_role 키는 코드에 쓰지 않는다. 화면(브라우저)에는 공개용 키만 쓴다.
