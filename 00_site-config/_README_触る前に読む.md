# ⚠️ このフォルダは「サイトの設定・仕様書」です

このフォルダ（`00_site-config/`）のファイルは、**サイト全体の設計・AIシステム仕様・運用ルール** を定義しています。
日常の記事制作では **基本的に編集しません**。以下のファイルは OS レベルで書き込みロックしています。

---

## 🔒 ロック中のファイル（編集・削除不可）

| ファイル | 役割 | 備考 |
|---|---|---|
| `handoff.md` | **新チャット起点**。必ず最初に読む | Claude への指示書 |
| `blog-ai-system.md` | AIシステム仕様・記事制作フロー・テンプレート | コア |
| `site-profile.md` | サイト設計・KW・カテゴリ構成 | コア |
| `article-pipeline.md` | 記事制作パイプライン（優先順位・進捗） | 定期更新対象 |
| `sns-strategy.md` | X（Twitter）運用戦略 | |
| `past-articles-archive.md` | 過去記事アーカイブ（リライト参考） | |

上記は `chflags uchg`（ユーザー不変フラグ）で保護されています。
**ファイル名は変更していません** — `handoff.md` 内のパス参照やClaude Codeの動作に影響しないためです。

---

## 🔓 編集が必要になったとき

どうしても編集する場合は、ロックを外してから編集し、編集後に再ロックします。

### ロック解除（1ファイルのみ）
```bash
chflags nouchg /Users/kimuraryouta/claude-blog/00_site-config/article-pipeline.md
```

### ロック解除（このフォルダ全部）
```bash
chflags nouchg /Users/kimuraryouta/claude-blog/00_site-config/*.md
```

### 編集後の再ロック
```bash
chflags uchg /Users/kimuraryouta/claude-blog/00_site-config/*.md
```

### 現在のロック状態を確認
```bash
ls -lO /Users/kimuraryouta/claude-blog/00_site-config/*.md
```
`uchg` と表示されているファイルがロック中です。

---

## 📂 日常の編集対象（ロックなし）

| フォルダ | 用途 |
|---|---|
| `01_pillar/` | ピラー記事 |
| `02_articles/` | 転職判断・収益比較記事 |
| `03_data/` | 決算分析・報酬改定ニュース記事 |
| `04_templates/` | テンプレート |
| `05_stock/` | ロングテール記事のストック |
| `06_assets/` | 画像・アイコン |

---

## 💡 Claude へ依頼するとき

- 仕様の変更（システム改定） → 「ロック外してから編集して」と伝える
- 記事制作 → そのまま依頼すればOK（上記ロックファイルは読み取りのみ使われる）

> ロックを解除すると `rm` や誤編集で失う危険が復活します。作業が終わったら必ず再ロックしてください。
