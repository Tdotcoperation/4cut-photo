# MOMENT4

사진 네 장을 하나의 순간으로 만드는 모바일 우선 웹앱입니다.

## 흐름

1. 사진 4장 선택
2. 프레임 선택
   - 기본 · 인생네컷 스타일
   - 프레임 없이
   - A4 출력 맞춤 (2480×3508, 동일 포토스트립 2개 + 절취선)
3. 날짜 / 문구 입력
4. 최종 결과 미리보기
5. **OK · 다운로드**로 고화질 PNG 저장

## 주요 기능

- JPG, PNG, WebP, AVIF, GIF, BMP 등 브라우저 지원 이미지
- HEIC / HEIF 자동 변환
- TIFF 자동 변환
- 확장자보다 실제 이미지 디코딩을 우선해 처리
- 사진 순서 변경 및 삭제
- 날짜 표시 ON/OFF
- 최대 40자 문구
- 더 크게 조정된 날짜·문구와 확대된 Canvas 미리보기
- A4 일반 프린터 출력용 레이아웃
- 최종 다운로드 이미지와 동일한 Canvas 미리보기
- 서버 업로드 없이 브라우저 내부에서만 사진 처리
- 모바일 우선 반응형 UI
- Wanted Sans Variable 적용

> 카메라 RAW처럼 브라우저와 포함된 디코더가 해석할 수 없는 특수 형식은 지원되지 않을 수 있습니다.

## 실행

별도 빌드 과정이 없는 정적 웹앱입니다. `index.html`을 정적 호스팅에 배포하면 됩니다.

GitHub Pages, Cloudflare Pages, Vercel, Netlify 등에서 바로 사용할 수 있습니다.

## Font

Wanted Sans Variable을 사용합니다.

- Wanted Sans: https://github.com/wanteddev/wanted-sans
- SIL Open Font License 1.1
