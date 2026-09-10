# golddigger-img

골드디거(golddigger) 블로그의 이미지 저장소 — `scripts/imgstore.py`가 발행 때 `<date>/<slot>-<n>-<slug>.jpg`를 올리고 GitHub Pages로 서빙한다.

- 재호스팅이 금지된 소스(Unsplash — API 규약상 CDN 핫링크)는 여기에 저장되지 않는다. `images.json`의 `hotlink: true` 항목은 `published_url`이 그 CDN 주소다(2026-09-10, `scripts/imgsearch.py`).
- 파일명은 ASCII만(퍼센트 인코딩이 Blogger 이미지 프록시를 깨뜨린다).
