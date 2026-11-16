# 4호점 타로 점집 (chick-tarot)

병아리 상점가 4호점. 점술가 병아리 삐별이 카드 세 장으로 오늘의 마음을 읽어 줘요.

- 주소: https://piyo-shop.github.io/chick-tarot/
- 한국 시간 2026-11-23 00:00 전에는 "공사 중" 화면, `#preview`로 미리 들어갈 수 있어요.
- `#demo`: API 없이 정해진 카드(별빛 수정구·한밤의 달·가로등)와 풀이로 흐름을 자동 재생해요(녹화용, 기록 저장 안 함).
- 하루 한 번(새벽 4시 기준). 지난 점괘는 이 브라우저(localStorage `chick-tarot-v1`)에만 남아요. 고민 글은 저장하지 않아요.
- 풀이는 piyo-chef-worker의 `/tarot`에서 받아요. 실패하면 cards.json의 한 줄 의미를 엮은 기본 풀이로 대신해요.
- 글꼴: 갈무리11 (Galmuri11, © quiple, SIL Open Font License 1.1)
