# demandsignal-lp

DemandSignal（AIアセット #1）の公開LP。静的HTML 1枚（`index.html`・自己完結）。

- 正本の編集元: `ai-company-os/docs/lp/index.html`（CAT-35系）
- ホスティング: GitHub Pages（無料・商用可）
- 関連: Linear CAT-70（予算カード）/ CAT-56（Phase1 LP再公開）

## 現在の状態：ステージ（一時非公開）

設計のゲートB（公開承認）に従い、Phase 1 のGOまでは **private + Pages無効** で待機。

## 公開手順（Phase 1 GO時・ゲートB承認後）

1. リポを public 化: `gh repo edit nariken/demandsignal-lp --visibility public --accept-visibility-change-consequences`
2. Pages有効化: Settings → Pages → Source = `main` / root（または `gh api -X POST repos/nariken/demandsignal-lp/pages -f 'source[branch]=main' -f 'source[path]=/'`）
3. 公開URL: `https://nariken.github.io/demandsignal-lp/`
4. 独自ドメインを使う場合は `CNAME` を追加
