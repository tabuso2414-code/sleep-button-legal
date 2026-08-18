# 睡眠ボタン — 公開文書

アプリ「睡眠ボタン」の**利用規約**と**プライバシーポリシー**を公開するためのリポジトリです。

| 文書 | URL |
| --- | --- |
| 利用規約 | https://tabuso2414-code.github.io/sleep-button-legal/terms.html |
| プライバシーポリシー | https://tabuso2414-code.github.io/sleep-button-legal/privacy.html |

## このリポジトリについて

- ここにあるのは **生成物** です。**本文の正はアプリのリポジトリ側**（`docs/legal/*.md`）にあります
- **`terms.html` / `privacy.html` / `index.html` を手で編集しないでください。**
  直すときはアプリのリポジトリの Markdown を直し、`node scripts/build-legal.mjs` で作り直します
- `.nojekyll` は GitHub Pages の Jekyll を通さないための空ファイルです

## 公開の設定

Settings → Pages → Source を **Deploy from a branch**、
Branch を **`main` / `(root)`** にすると、上の URL で公開されます。
