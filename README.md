# 테스팩 웹사이트 수정 안내

- `dist/index.html`에서 홈 소개, 설비 카드, 문의 문구를 수정합니다.
- `dist/guide.html`에서 설비별 설명과 사양 확인 항목을 수정합니다.
- `dist/styles.css`에서 색상, 글자 크기, 화면 배치를 조정합니다.
- `dist/images/`의 JPG 파일을 같은 이름으로 교체하면 코드 수정 없이 사진이 바뀝니다.

| 파일 | 표시 위치 |
| --- | --- |
| hero.jpg | 홈페이지 대표 사진 |
| proof.jpg | 내압시험설비 |
| burst.jpg | 파열시험 챔버 |
| leak-equipment.jpg | 기밀시험설비 |
| buffer-high.jpg | 고압 버퍼탱크 사진 |
| buffer-low.png | 저압 버퍼탱크 사진 |
| manual-pump.jpg | 수동가압설비 고압 핸드펌프 |
| manual-logger.jpg | 수동가압설비 압력·온도 측정장비 |
| chamber-analysis.png | 안전 구조 계산 및 해석 대표 이미지 |
| wall-thickness.jpg | 용기 벽두께 계산시트 |

설비별 사진은 홈페이지 카드와 매뉴얼에서 공통으로 사용합니다. 사진을 교체할 때 두 HTML 파일의 이미지 설명(`alt`)도 확인하세요. 각 설비 카드와 매뉴얼 목차가 연결되므로 제목만 바꿀 때는 기존 `id` 값을 유지합니다.

`dist/index.html`을 브라우저에서 열어 변경 사항을 확인할 수 있습니다. 온라인 사이트에 적용하려면 같은 Sites 프로젝트에 새 버전을 배포합니다.
