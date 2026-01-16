# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

Lofi BGM Player ブラウザ拡張機能のランディングページ。ビルドプロセスなしの静的HTML/CSSサイト。

## 開発

ローカルプレビュー:

```bash
python -m http.server 8000
# または
npx serve .
```

ブラウザで直接開く:

```bash
open index.html
```

## 構成

- **index.html** - メインランディングページ（ヒーロー、機能、料金セクション）
- **legal.html** - 特定商取引法に基づく表記
- **privacy.html** - プライバシーポリシー
- **style.css** - CSS変数によるテーマ管理

## デザインシステム

`:root` で定義されたCSS変数:

- カラー: `--color-bg`, `--color-accent` (#f4a261), `--color-purple` など
- フォント: `--font-display` (Space Mono), `--font-body` (Zen Maru Gothic)
- イージング: `--ease-out-expo`, `--ease-out-back`

## 拡張機能ストアURL

- Chrome: `https://chromewebstore.google.com/detail/lofi-bgm-player/jdcppdokgfbnhiacbeplahgnciahnhck`
- Edge: `https://microsoftedge.microsoft.com/addons/detail/lofi-bgm-player/dpeadccgpajindejnofmoomceaacijpi`
- Firefox: `https://addons.mozilla.org/firefox/addon/lofi-bgm-player/`
