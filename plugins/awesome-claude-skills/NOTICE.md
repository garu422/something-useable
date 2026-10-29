# 개인용 복사본 안내 / Personal copy notice

이 폴더는 [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)를 개인적으로 쓰려고 복사한 것입니다. 원작자와 관계없고 원작자의 보증도 받지 않았습니다.

## 라이선스

- 저장소 전체: Apache License 2.0 (원본 README 기준). 전문은 이 폴더의 `LICENSE` 파일에 있습니다.
- 스킬마다 라이선스가 다를 수 있습니다. 각 스킬 폴더의 `LICENSE.txt`와 `SKILL.md` 맨 위 `license:` 항목을 확인하세요.
  - 예: `twitter-algorithm-optimizer`는 AGPL-3.0입니다.

## 원본에서 바꾼 것

1. **`document-skills/`(docx, pdf, pptx, xlsx) 폴더를 기록 전체에서 뺐습니다.**
   - 이 4개는 Anthropic 소유("© 2025 Anthropic, PBC. All rights reserved.")입니다.
   - 라이선스가 복사와 재배포를 금지해서, git 기록까지 모두 걸러낸 뒤 가져왔습니다.
   - 그래서 원본 README와 `composio-skills/.claude-plugin/marketplace.json`에 남은 document-skills 링크는 동작하지 않습니다.
2. **파일을 3개 추가했습니다.**
   - `.claude-plugin/plugin.json`: 범용 스킬 27개를 하나의 플러그인으로 묶었습니다.
   - `LICENSE`: Apache-2.0 전문. 원본 `skill-creator/LICENSE.txt`와 같은 내용입니다.
   - 이 `NOTICE.md` 파일
3. **위 2번 외에 원본 파일은 고치지 않았습니다.**

---

This folder is an unofficial personal copy of ComposioHQ/awesome-claude-skills, not affiliated with or endorsed by its authors. Changes from upstream:

- `document-skills/` (Anthropic-owned, redistribution prohibited) was removed from the imported history.
- Added `.claude-plugin/plugin.json`, `LICENSE` (Apache-2.0 text) and this `NOTICE.md`.
- No other upstream file was modified.
