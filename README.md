# 화질 타임머신

사진을 2000년 첫 폰카부터 2026년까지 그 시절 화질로 바꿔 주는 웹 도구예요. 로그인이 필요 없고, 사진은 각자 기기 안에서만 처리돼요.

## 기능
- 연도 슬라이더 (2000~2026), 뭉개진 저화질 / 도트 픽셀 스타일, 과노출
- 문구 넣기 (외계어 변환), 얼굴 자동·직접 가리기
- 티셔츠·폰케이스·스티커 목업, 인쇄 점검
- 인쇄용 저장, 전후 비교 이미지, 변환 영상(MP4/WebM), 여러 장 ZIP 저장

## GitHub Pages로 올리기
1. 이 폴더의 파일을 저장소 맨 위(루트)에 그대로 올려요: `index.html`, `og.png`, `models/`, `vendor/`, `README.md`
2. 저장소의 Settings → Pages → Build and deployment에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 고르고 Save
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소 이름>/` 주소로 열려요

## 포함된 외부 코드
- `vendor/face-api.js`, `models/ssd_weights.json`: [@vladmandic/face-api](https://github.com/vladmandic/face-api) 1.7.15 (MIT 라이선스, `vendor/face-api-LICENSE.txt`)
- 글꼴: Google Fonts (Do Hyeon, Black Han Sans, Gaegu, Noto Sans KR, VT323 · OFL)
