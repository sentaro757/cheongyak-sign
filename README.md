# 청약서 서명

수기 청약용 웹앱. 청약서 PDF에 서명 칸을 잡고, 기기를 고객에게 넘겨 서명·성명을 받은 뒤 PDF로 저장합니다.

- 사용: https://sentaro757.github.io/cheongyak-sign/ — 태블릿·휴대폰에서 열고 "홈 화면에 추가"
- 고객 PDF와 서명은 기기 밖으로 나가지 않습니다. 이 저장소에는 앱 코드만 있습니다.
- 빌드 결과물입니다. 원본은 별도 저장소의 `src/cheongyak-sign.html` 이고 `npm run build` 로 만든 `app/` 을 그대로 올립니다.
- 포함 라이브러리: pdf.js (Apache-2.0, Mozilla), pdf-lib (MIT)
