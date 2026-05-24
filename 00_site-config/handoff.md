# handoff.md
# 薬剤師キャリアナビ｜引き継ぎ・タスク管理

> **新チャット開始時は必ずこのファイルを最初に読むこと**
> 次に `blog-ai-system.md` → `site-profile.md` の順で読んで全体把握をしてから作業を開始する

---

## 📁 フォルダ構成

```
claude-blog/
├── 00_site-config/
│   ├── handoff.md          ← このファイル（毎回ここから読む）
│   ├── blog-ai-system.md   ← AIシステム仕様・記事制作フロー・テンプレート
│   ├── site-profile.md     ← サイト設計・KW・カテゴリ構成
│   └── sns-strategy.md     ← X（Twitter）運用戦略
├── 01_pillar/              ← ピラー記事（月1〜2本）
├── 02_articles/            ← 転職判断・収益比較記事
├── 03_data/                ← 決算分析・報酬改定ニュース記事
├── 04_templates/           ← 記事テンプレート
├── 05_stock/               ← ロングテール記事
│   └── choozai-yakkyoku-shourai-sei/
│       ├── draft.md        ← 公開済み記事の原稿
│       └── draft.html      ← HTML版
└── 06_assets/
    └── icons/
        ├── profile-icon-400x400.png    ← WP著者プロフィール・Xアイコン用
        └── callout-icon-100x100.png    ← SWELL吹き出しアイコン用
```

---

## ✅ 完了済みタスク（前チャットまで）

### サイト基盤
- [x] サイト設計・コンセプト策定（site-profile.md）
- [x] AIブログ制作システム仕様書作成（blog-ai-system.md）
- [x] WordPress構築・SWELL設定
- [x] カテゴリ・パーマリンク設定
- [x] WPコメント欄を非表示に設定（2026-04-02）
- [x] 著者プロフィール設定（薬剤師 辻 / 2026-04-02）
  - 表示名：薬剤師 辻
  - 自己紹介文：現役調剤薬局薬剤師。収益構造と調剤報酬データをもとに、薬剤師の年収・転職判断を解説しています。
  - カスタムアバター：profile-icon-400x400.png 設定済み
- [x] 過去ブログ22記事インプット・記事パイプラインに統合（2026-04-02）
  - `00_site-config/past-articles-archive.md`
  - `00_site-config/article-pipeline.md`
- [x] WP上の不要記事・固定ページ削除（2026-04-02）

### 記事制作
- [x] 1本目記事執筆・SWELL装飾・公開
  - タイトル：あなたの薬局は10年後も存在するか｜収益構造と2026年改定で判断する将来性の見極め方
  - スラッグ：`choozai-yakkyoku-shourai-sei`
  - カテゴリ：調剤薬局薬剤師のキャリア
  - URL：https://pharmirai.com/choozai-yakkyoku-shourai-sei/
  - SEOタイトル・メタディスクリプション設定済み

### デザイン・アセット
- [x] アイキャッチ画像作成（Canva・1200×630px）
- [x] プロフィールアイコン作成（ナノバナナ→Canva）
  - `06_assets/icons/profile-icon-400x400.png`
  - `06_assets/icons/callout-icon-100x100.png`

### SNS戦略
- [x] X（Twitter）アカウント作成済み
- [x] SNS運用戦略ドキュメント作成（sns-strategy.md）

---

## 🔴 未完了タスク（次チャット以降でやること）

### 優先度：高（すぐやる）

- [ ] **サイトアイコン（favicon）設定**
  - WP管理画面 → 外観 → カスタマイズ → サイト基本情報 → サイトアイコン
  - `06_assets/icons/profile-icon-400x400.png` またはロゴ画像を使用

- [ ] **Google Search Console 連携**
  - Site Kit プラグインから設定
  - サイトマップ（/sitemap.xml）を送信

- [ ] **Google Analytics 連携**
  - Site Kit プラグインから設定

- [ ] **SEO PACK 基本設定**
  - サイト名・OGP・Twitter Card の設定確認

- [ ] **SWELL吹き出しアイコンを設定する**
  - `06_assets/icons/callout-icon-100x100.png` をSWELL吹き出し設定でアップロード
  - キャラクター名：薬剤師 辻

### 優先度：中（今週中）

- [ ] **X（Twitter）プロフィールを最適化する**
  - アイコン：`06_assets/icons/profile-icon-400x400.png` をアップロード
  - ヘッダー画像：Canvaで1500×500px作成（サイトカラー・サイト名・キャッチコピー）
  - 表示名：`薬剤師 辻｜薬剤師キャリアナビ`
  - bio：sns-strategy.md の「プロフィール設計」セクション参照
  - 固定ツイート：sns-strategy.md の「固定ツイートの内容」参照
  - URL：pharmirai.com

- [ ] **X 初投稿（自己紹介ツイート）**
  - Claudeに投稿文を作成依頼してから投稿する

- [ ] **2本目記事制作（クオールHD企業分析）**
  - `00_site-config/article-pipeline.md` の「記事A」参照
  - 過去記事ID:264の素材を活用

### 優先度：低（記事20本公開後）

- [ ] アフィリエイトURL設置（マイナビ薬剤師・ファルマスタッフ）
- [ ] CTAウィジェット有効化
- [ ] 内部リンク設置（関連記事が増えてから）

---

## 📊 現在の進捗

| 指標 | 現状 |
|---|---|
| 公開記事数 | 1本 |
| Xフォロワー | ほぼ0（運用開始前） |
| アフィリエイト | 未設置（20本後に設置予定） |
| Google Search Console | 要確認 |
| Google Analytics | 要確認 |

---

## 🌐 サイト情報

| 項目 | 内容 |
|---|---|
| サイトURL | https://pharmirai.com |
| WP管理画面 | https://pharmirai.com/wp-admin |
| WPユーザー名 | yakugaku |
| テーマ | SWELL |
| Xアカウント | 作成済み（ハンドル確認のこと） |

---

## 📦 過去記事アーカイブ

前ブログ（旧pharmirai.com）の非公開・下書き記事22本＋固定ページをインプット済み。
→ `00_site-config/past-articles-archive.md` を参照

**pharmirai.comで優先活用すべきもの**:
- クオールHD・アインHD企業分析（→ 03_data/ 大手薬局分析シリーズ）
- キャリアアップ構成メモ・年収1000万記事（→ 02_articles/ リライト素材）
- かかりつけ薬剤師記事（→ 調剤報酬×収益記事の素材）

---

## 📝 次のチャットへの指示テンプレート

```
以下のファイルを順番に読んで現状を把握してください：
1. 00_site-config/handoff.md（まず最初に）
2. 00_site-config/blog-ai-system.md
3. 00_site-config/site-profile.md

把握できたら「確認しました」と未完了タスクの優先度リストを報告してから作業を開始してください。
```

---

## 更新履歴

| 更新日 | 内容 |
|---|---|
| 2026-04-01 | 初版作成 |
| 2026-04-02 | アイコン作成・ファイル整理後の状態に更新 |
