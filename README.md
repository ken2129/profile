# Uchishiba Kensuke / 内芝 謙允

学歴、インターンシップ、研究・学会発表、技術スキルをまとめた日本語のプロフィールページです。

公開URL: https://ken2129.github.io/profile/

## 編集

- `index.html`: ページの本文とCSS。経歴を更新するときは本文と末尾の更新日を編集します。
- `.nojekyll`: HTMLをそのまま配信するための設定。

外部ライブラリ、外部フォント、アクセス解析は使用していません。

## デザイン

[tokkiwa/myprofile](https://github.com/tokkiwa/myprofile)の表示を参考に、グレーの背景・白いカード・青い見出し線とリンクボタンで構成。本文は本人の情報を使用しています。

## ローカルプレビュー

このフォルダで以下を実行し、ブラウザーで http://127.0.0.1:8765/ を開きます。

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

`index.html`を編集した後、ブラウザーを再読み込みすると変更が表示されます。サーバーはCtrl+Cで停止します。

## GitHub Pages

Settings → Pages で、Sourceを `Deploy from a branch`、Branchを `main`、フォルダを `/(root)` に設定します。設定後はmainへの反映で自動更新されます。

## 内容の出典

- 学歴・インターンシップ・主要技術：本人のAWS応募用レジュメ。
- 研究発表：[電子情報通信学会の発表情報](https://ken.ieice.org/ken/paper/20260316pcSj/)。
- PyTorch：本人の研究資料・レジュメ。

学科・専攻の所属は本人に確認済み（2026年10月7日）。正式名称は[早稲田大学の学部・研究科紹介](https://www.waseda.jp/fsci/about/departments/fundamental/)で確認し、「基幹理工学部 情報通信学科」「基幹理工学研究科 情報理工・情報通信専攻」と記載しています。
