# 서울 강남·잠실 백화점 픽업 대행 (댈구)

지방 거주자를 위한 **서울 백화점 픽업·대리구매 안내 랜딩 페이지**입니다.
온라인 품절 상품, 신세계 강남·에비뉴엘 잠실·코엑스 등 서울 단독 매장·팝업 재고를
매장에서 직접 구매한 뒤 영수증·실물·포장 사진과 함께 전국 택배로 발송하는 서비스를 소개합니다.

- 라이브: https://minjaeun.github.io/seoul-pickup/
- 문의: 카카오 1:1 오픈채팅 https://open.kakao.com/o/sMTEqpVi

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 단일 페이지 랜딩 (모바일 우선, 인라인 CSS) |
| `robots.txt` | 검색 색인 허용 + sitemap 위치 |
| `sitemap.xml` | 단일 URL 사이트맵 |
| `assets/hero.jpg` | 히어로 일러스트 |
| `assets/og-image.jpg` | Open Graph 공유 이미지 (1200×630) |
| `assets/favicon.svg` | 파비콘 |

## 검색·AI 노출 (GEO)

- `Service` + `FAQPage` 구조화 데이터(JSON-LD) — 본문 FAQ 6문항과 문구가 100% 일치
- 명확한 `title` / `meta description` / Open Graph / Twitter 카드
- 시맨틱 HTML5(`header`·`main`·`section`·`article`), 모바일 우선 반응형

## 배포

GitHub Pages (branch `main`, root). `index.html`을 수정해 푸시하면 자동 반영됩니다.

```bash
git add -A && git commit -m "update" && git push
```

## 확정 조건 (요약)

- 수고비 50,000원 (물품대금·배송비 별도)
- 배송비: 우체국·편의점 일반택배 실비 (약 4,000원대), 픽업 당일 또는 다음 영업일 발송
- 퀵 요청 시 매장 출발 카카오퀵 실비
- 기본 권역(평일 점심 11:00~13:00 / 17:00 이후) — 현대 무역센터·스타필드 코엑스
- 기본 권역(평일 17:00 이후) — 신세계 강남, 롯데 잠실·강남, 에비뉴엘 잠실, 현대 압구정·천호
- 그 외 서울 지역(성수·한남·여의도·명동 등)은 거리·접근도에 따라 추가 비용, 오픈채팅 사전 문의
- 오픈런·장시간 웨이팅 대행 없음, 매장 재고 확인은 고객 몫
