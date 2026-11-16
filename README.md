# JWS Portfolio

개인 디지털미디어·크리에이티브 포트폴리오. 네이비/블루 기반의 미니멀 랜딩 페이지와 카테고리별 독립 화면으로 구성했습니다.

## 카테고리

| 그룹 | 카테고리 | 주소 |
| --- | --- | --- |
| Portfolio | Home | `/#home` |
| Portfolio | About | `/#about` |
| Portfolio | Projects | `/#projects` |
| Activities | Research & Activities | `/#activities` |
| Activities | Certificates | `/#certificates` |
| Archive | Financial Atlas | `/#financial-atlas` |

**Financial Atlas는 다른 메뉴와 동일한 사이드바 크기/위계를 가집니다.** 기존 NAVER 데이터 분석은 별도 원본 사이트 [JW_NAVER](https://hsc-class02.github.io/JW_NAVER/)에서 보존되며 iframe 및 외부 링크로 연결합니다.

## 구성

- `docs/index.html` — CSS/JS가 내장된 정적 사이트 (별도 빌드 도구 불필요)
- `.github/workflows/pages.yml` — GitHub Pages 자동 배포
- `README.md` — 구성/배포 안내

## GitHub Pages

Settings → Pages → Build and deployment → **Source: GitHub Actions**.

GitHub Pages 주소는 저장소의 Pages 설정 및 Actions 실행 결과에 따라 결정됩니다.

## Certificate

UNESCO · LG AI Research / Coursera의 *Global MOOC on the Ethics of AI* 수료 정보가 게시되어 있습니다.

검증 URL: https://www.coursera.org/verify/FMAV25ER2071

현재 웹페이지는 **공식 검증 링크만 게시**합니다. 수료증 원본 PDF 바이너리는 업로드하지 않았습니다.

## 유지·확장

홈 첫 화면은 네이비 컬러의 심플한 풍경 SVG 일러스트입니다. 프로젝트/활동 기록은 검증 가능한 결과가 생길 때 추가하면 됩니다. 기존 OpenDART 자동 수집은 이 저장소에서 재구현하지 않았고 원본 [JW_NAVER](https://github.com/HSC-Class02/JW_NAVER) 프로젝트를 참조합니다.
