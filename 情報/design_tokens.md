# デザイントークン — 採用試験・就職フェア LP

## フォント

| 役割 | フォント名 | ウェイト | 用途 |
|------|-----------|---------|------|
| 見出し | Kaisei Tokumin（Google Fonts） | 400 / 700 / 800 | H1・H2・カード見出し・ナビロゴ |
| 本文 | Noto Sans JP（Google Fonts） | 400 / 500 / 700 | 全本文・説明文・ボタン |

```html
<link href="https://fonts.googleapis.com/css2?family=Kaisei+Tokumin:wght@400;700;800&family=Noto+Sans+JP:wght@400;500;700&display=swap" rel="stylesheet">
```

---

## カラー変数

### ベース

| 変数名 | カラーコード | 用途 |
|--------|------------|------|
| `--cream` | `#FFF8EE` | ページ背景 |
| `--cream-card` | `#FFFCF7` | カード背景（一部） |
| `--white` | `#FFFFFF` | カード・ボタン背景 |

### セージグリーン系

| 変数名 | カラーコード | 用途 |
|--------|------------|------|
| `--sage-dark` | `#3A6652` | 見出しアクセント・CTAブロック背景 |
| `--sage` | `#578A71` | ブロブ装飾・ボーダー |
| `--sage-mid` | `#7BAF95` | 装飾・ブロブ |
| `--sage-light` | `#C4DFCF` | ボーダー・区切り線 |
| `--sage-pale` | `#EAF4EE` | セクション背景・バッジ背景 |

### アンバー（オレンジ）系

| 変数名 | カラーコード | 用途 |
|--------|------------|------|
| `--amber` | `#F07840` | CTAボタン・見出しアクセント下線 |
| `--amber-mid` | `#F4A070` | サブアクセント |
| `--amber-pale` | `#FEF3EC` | アイコン背景（2枚目カード） |
| `--terra` | `#C4503A` | 定義済み・現在未使用 |

### テキスト

| 変数名 | カラーコード | 用途 |
|--------|------------|------|
| `--text-dark` | `#2A201A` | 本文・フッター背景 |
| `--text-med` | `#604A3C` | 説明文・サブテキスト |
| `--text-soft` | `#9A8478` | 注釈・薄いテキスト |

---

## CSS 変数定義（コピー用）

```css
:root {
  --cream:       #FFF8EE;
  --cream-card:  #FFFCF7;
  --sage-dark:   #3A6652;
  --sage:        #578A71;
  --sage-mid:    #7BAF95;
  --sage-light:  #C4DFCF;
  --sage-pale:   #EAF4EE;
  --amber:       #F07840;
  --amber-mid:   #F4A070;
  --amber-pale:  #FEF3EC;
  --terra:       #C4503A;
  --text-dark:   #2A201A;
  --text-med:    #604A3C;
  --text-soft:   #9A8478;
  --white:       #FFFFFF;
  --radius-lg:   24px;
  --radius-pill: 999px;
}
```

---

## アイコン

Lucide Icons（CDN）を使用。

```html
<script src="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js"></script>
```

| 用途 | アイコン名 |
|------|----------|
| 日時 | `calendar` |
| 会場 | `map-pin` |
| 対象者 | `users` |
| 願書・書類 | `clipboard-list` |
| 作文試験 | `pencil-line` |
| ブース面接 | `building-2` |
| 交渉解禁日 | `calendar-check` |
| 持込・問合せ | `info` |
| ステップ矢印 | `chevron-right` |
