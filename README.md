# いろはde歴史® 公式サイト

[https://irohaderekishi.com](https://irohaderekishi.com)

いろは47文字＋「ん」で綴る、日本史学習カルタアプリの公式サイトです。

## 概要

- 原作：松井 聰
- 48枚のカルタで、縄文から平成までの日本史を学ぶ
- 3つの遊び方：かるた遊び・神経衰弱・時代クイズ
- 学習モード：16時代の物語 + 48枚のカルタ別詳細解説

## ディレクトリ構成

```
/
├── index.html          ← トップページ（ランディング）
├── app/
│   ├── app.html        ← 本体アプリ
│   ├── card_images/    ← 96枚のカード画像（表/裏）
│   └── mascot_*.mp4    ← 5色のマスコット動画
└── README.md
```

## デプロイ

- Hosting: Zeabur
- Domain: irohaderekishi.com (via GoDaddy DNS → CNAME)
- 静的サイトのため、Push to main で自動デプロイ

## URL構成

- `https://irohaderekishi.com/` — トップページ
- `https://irohaderekishi.com/app/` — アプリ本体

## ライセンス

© 2026 松井 聰 / いろはde歴史®. All rights reserved.
