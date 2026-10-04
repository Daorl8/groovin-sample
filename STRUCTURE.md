# STRUCTURE · groovin-sample

```
groovin-sample/
├─ index.html              단일 파일 (CSS·JS 인라인, 손그림 SVG symbol 포함)
├─ wrangler.toml           name = groovin-sample → groovin-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html·gv-dog.png·미사용 webp 5개 배포 제외
├─ gv-caveatbrush.woff2    제목 (Caveat Brush)
├─ gv-shantell-400/700.woff2 본문 (Shantell Sans 고정 인스턴스)
├─ gv-poorstory.woff2      한글 (Poor Story)
├─ gv-dog.webp             강아지 낙서 로고 (투명 바깥, 흰 얼굴)
├─ gv-*.webp               사진 21컷 (히어로·시그니처 3·카운터 8·커피 2·공간 3 등)
├─ og-groovin.jpg          공유 썸네일 1200×630
├─ img/                    다올 제공 원본 (배포 제외)
├─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(스티키) → `#top` 히어로 + 흐르는 띠 → `#menu` Signatures → From the counter → `#coffee` 커피 + 강아지 스티커 → `#space` 공간 → `#visit` 오시는 길(구글 지도) → 푸터.

## 반응형
모바일 1열(카운터·공간 2열) / ≥720 시그니처 3열·카운터 4열·공간 3열 / ≥980 히어로·커피·오시는길 2단. 내비 링크는 ≤820에서 숨김(Shop online만).

## 텍스트 수정 시
폰트가 서브셋이라 새 글자를 넣으면 서브셋 재생성 필요. 화면 글자에 하이픈 쓰지 말 것(다올 지시).
