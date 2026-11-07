<!-- ── SipurCodex BEGIN: public repository overview / 公開 Repo 說明 ── -->
# Minerva HC Thinking Skill

[繁體中文](#繁體中文) | [English](#english)

## 繁體中文

這是一個 Codex Skill，以 Minerva University 公開說明的 Habits of Mind and Foundational Concepts（HCs）為靈感，協助使用者把思考工具實際用在專案分析、課程設計、決策、審查與跨領域遷移。

它不重製完整 HC 清單，也不包含 Minerva 私有教材。Skill 只使用少量可由官方公開來源核對的概念，再加入原創的工作產物、transfer task 與 1–5 行為 rubric。

### 核心設計

- 四個能力領域：批判思考、創意思考、有效溝通、有效互動。
- 每次選 2–4 個真正會改變產出的 habits。
- 產出 evidence ledger、constraint table、stakeholder map 等可檢查 artifacts。
- 在第二個不同領域重做一次，驗證 transfer。
- 依可觀察行為評分，不依語氣、自信或術語數量評分。
- 簡單事實或機械式任務會通過 stand-down gate，不強行套框架。

### 安裝

~~~powershell
git clone https://github.com/sipurchen/Minerva_HC.git
Copy-Item -Recurse .\Minerva_HC\skills\minerva-hc-thinking "$env:CODEX_HOME\skills\minerva-hc-thinking"
~~~

macOS／Linux：

~~~bash
git clone https://github.com/sipurchen/Minerva_HC.git
cp -R Minerva_HC/skills/minerva-hc-thinking "${CODEX_HOME:-$HOME/.codex}/skills/minerva-hc-thinking"
~~~

使用方式：

~~~text
Use $minerva-hc-thinking to redesign this lesson for cross-domain transfer.
~~~

### Repository 結構

~~~text
skills/minerva-hc-thinking/
├── SKILL.md
├── agents/openai.yaml
└── references/hc-framework.md
~~~

相似 repo 與差異分析：[docs/SIMILAR_REPOS.md](docs/SIMILAR_REPOS.md)

### 公開來源

- [Minerva — An Introduction to Habits of Mind and Foundational Concepts](https://www.minerva.edu/public/media/enrollment-center/Minerva-HCs-Intro.pdf)
- [Minerva — Four-Year Curriculum](https://www.minerva.edu/four-year-curriculum/)

### 脫敏與來源邊界

- Repository 不收錄私有 workspace 路徑、使用者資料、session、token、密鑰或內部專案內容。
- 不宣稱本 Skill 是 Minerva 官方產品、現行完整課綱或官方 rubric。
- 公開來源內容以摘要、改寫與連結呈現；不複製非公開教材。

## English

This repository provides a Codex Skill inspired by Minerva University's public descriptions of Habits of Mind and Foundational Concepts. It applies a deliberately small set of transferable thinking tools to project analysis, curriculum design, decisions, reviews, and cross-domain practice.

The Skill is independent and unofficial. It does not reproduce a current or complete Minerva catalog. Its artifacts, transfer protocol, and behavioral rubric are original operational adaptations based on public sources.

See [skills/minerva-hc-thinking/SKILL.md](skills/minerva-hc-thinking/SKILL.md) for the entrypoint and [docs/SIMILAR_REPOS.md](docs/SIMILAR_REPOS.md) for related public work.

## License

[MIT](LICENSE)
<!-- ── SipurCodex END ── -->
