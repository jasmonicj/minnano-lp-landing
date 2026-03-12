# みんなのLP屋さん — サービスLP

LINEで修正依頼を送るだけでLPが即時反映される、中小企業・個人事業主向けLP制作・保守サービスのランディングページです。

## ファイル構成

```
/
├── index.html       # サービスLP（HTML・CSS・JS 1ファイル完結）
├── thanks.html      # Stripe決済完了後リダイレクト先
├── vercel.json      # Vercelルーティング設定
├── docs/            # サービスドキュメント一式
└── README.md
```

## 技術仕様

- HTML / CSS / JavaScript のみ（フレームワーク不使用）
- Google Fonts: Zen Maru Gothic, Shippori Mincho, Space Mono
- モバイルファースト・レスポンシブ対応
- SVGイラスト（画像ファイル不使用）
- Intersection Observer によるスクロールアニメーション

## デプロイ

```bash
vercel --prod
```

## リンク

- LINE公式アカウント: https://lin.ee/89T6DTw
- 運営: MODALAVA株式会社
