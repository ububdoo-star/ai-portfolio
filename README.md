# 🤖 AI Portfolio — ちいさなロボと、つくる毎日。

AIで作ったアプリ・ツールの実績をまとめた個人開発ポートフォリオサイトです。
パステルカラー × かわいいロボットマスコットの、スマホファーストな1ページ構成。

🔗 **公開URL**: https://ububdoo-star.github.io/ai-portfolio/

## 構成

| セクション | 内容 |
|---|---|
| Hero | マスコット＋キャッチコピー＋CTA |
| About | 自己紹介 |
| Gallery | 作品スクショのカードグリッド |
| Skills | 使用技術タグ |
| Contact | SNS・連絡先リンク |

## 技術

- 素の HTML / CSS（フレームワークなし・1ファイル完結）
- Google Fonts（Zen Maru Gothic / M PLUS Rounded 1c / Quicksand）
- マスコット・favicon・OGP画像はすべて SVG で内製

## 作品スクショの差し替え方

1. `images/` フォルダに正方形〜16:10程度のスクショ画像を入れる
2. `index.html` のギャラリーカード内 `<div class="thumb tN">Screenshot</div>` を
   `<img src="images/xxxx.png" alt="アプリ名">` に置き換える
3. アプリ名・説明・タグ・リンクを各カードで更新する

## ローカル確認

```bash
python3 -m http.server 8000
# http://localhost:8000 を開く
```

---
made with 🤖 & 💗 by Claude Code
