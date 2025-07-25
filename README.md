# コーポレートサイト模写（Code-Jump 課題）

## 概要

[Code-Jump](https://code-jump.com/corporate2-menu/) の「コーポレートサイト 2（メニューあり）」をもとに、HTML/CSS のみでコーディングした模写作品です。企業のコーポレートサイトを想定し、構造の整理やレイアウト、レスポンシブ対応などの基本的な技術を学習目的として取り入れています。

## デザイン仕様

### コンテンツ幅

- メインビジュアル・About: 全幅
- その他セクション: 1000px

### ヘッダー

- 右上「お問い合わせ」ボタン: PC 版のみ表示

### レスポンシブ

- ブレークポイント: 900px
- モバイルファースト設計

### 各セクションの特徴

- News: 3 分割レイアウト + 罫線、time タグ使用
- About: 全幅、画像高さ 400px 固定
- Business: 高さをずらした横並び配置
- Company: 画像を上に重ねるレイアウト、画像高さ 400px 固定

## 使用技術

- HTML5
- CSS3（Flexbox、レスポンシブ対応）
- モバイルファースト設計
- Web フォントの導入

## 工夫した点
- デザインカンプをもとに、細部のマージンやフォントサイズを調整し、忠実な再現を目指しました。
- ヘッダーのナビゲーションはホバー時の動作も含めて再現。
- BEMの命名規則を意識し、保守性のあるCSS設計に取り組みました。
