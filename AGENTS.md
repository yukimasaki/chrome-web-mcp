# chrome-web-mcp（yukimasaki のフォーク）

このリポジトリは [kuraneko1/chrome-web-mcp](https://github.com/kuraneko1/chrome-web-mcp) を yukimasaki でフォークしたもの。
手元の不具合を直して使うために持っている。

## 上流には何も出さない

- **上流（kuraneko1/chrome-web-mcp）には、PR も Issue もコメントも一切出さない。** 上流のためになりそうな修正でも出さない
- 修正はこのフォークの中だけで完結させる。push 先は `origin`（yukimasaki/chrome-web-mcp）だけにする
- `upstream` remote は更新を取り込むため（`git fetch upstream`）だけに使う
- 「上流に PR や Issue を出す」を選択肢として提案しない

**Why:** AI が好き放題に PR を出し、メンテナがレビューに疲弊していて、良く思われていない（2026-10-02、ftsmasaki）。
