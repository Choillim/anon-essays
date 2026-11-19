# 안온 밤의 글 묶음

안온(An;on) iOS 앱이 읽어 가는 글 묶음이에요. GitHub Pages로 내보내요.

- 주소: https://choillim.github.io/anon-essays/essays.json
- 형식: `{ "version": YYYYMMDDHHMM, "digest": "...", "count": N, "essays": [ { id, title, moods, writer, text, lastLine } ] }`
- 앱은 번들보다 `version`이 높고 기분 6가지가 다 들어 있을 때만 이 묶음으로 바꿔요.

이 저장소는 직접 고치지 않아요. 원고는 앱 저장소의 `docs/essays/`에서 검토를 거쳐 만들고, `python3 docs/essays/publish_feed.py`로 올려요.

글은 모두 안온이 직접 쓴 창작 에세이예요. 무단 전재와 재배포를 하지 말아 주세요.
