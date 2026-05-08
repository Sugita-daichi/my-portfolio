# Daichi Sugita Portfolio

静岡大学大学院 修士1年生 杉田大知のポートフォリオサイトです。
自身の研究成果、受賞歴、開発プロジェクト、およびスキルセットを公開しています。

[本サイト](https://sugita-daichi.github.io/)

---

## 自己紹介

- **所属**: 静岡大学大学院 総合科学技術研究科 情報学専攻 莊司研究室（修士1年）
- **研究テーマ**: 画像生成AIにおける追加学習モデル（LoRA）の検索および統合手法
- **関心領域**: 情報検索, 画像処理, 機械学習, 自然言語処理

現在、**LINEヤフー株式会社様との共同研究**に従事しており、実社会の課題解決に向けた大規模モデルの活用技術を開発しています。

## 主な研究実績

### 国際会議 (Accepted)
- **Which LoRA Should Be Merged Next? Retrieving an Additional LoRA from a Target Image**
  - *ICMR 2026* (The 16th ACM International Conference on Multimedia Retrieval) にて採択。

### 国内発表
- **DEIM 2026**: モデルのトークンエンベディングによる目標画像を生成するためにマージすべきLoRAの検索
- **WebDB 2025**: 目標画像と使用中のLoRAを入力とするマージすべきLoRAアダプタの検索

### 受賞
- **東海関西データベースワークショップ2025**: 優秀賞

## 🛠 技術スタック

- **Framework**: Astro (Static Site Generator)
- **Styling**: CSS (Custom Properties / Dark Mode Support)
- **Deployment**: GitHub Pages
- **Development**: Python (Machine Learning / Deep Learning), PyTorch, Linux (Ubuntu)

## プロジェクト構成

```text
├── public/          # 静的ファイル（faviconなど）
├── src/
│   ├── assets/      # プロフィール画像、プロジェクト画像
│   ├── components/  # 共通パーツ（Header, Footer, ThemeIconなど）
│   ├── pages/       # 各ページ（Profile, Researches, Awards, Projects）
│   └── styles/      # グローバルCSS
└── astro.config.mjs # Astro設定ファイル
