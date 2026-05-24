# 03_data/chosei-hoshu-kaitei

調剤報酬改定に関する一次資料・データ保管フォルダ。

## フォルダ構成

```
raw-pdf/
  ├ (改定資料 PDF)
  └ gigi-kaishaku/  … 各改定年の疑義解釈その1 PDF
```

## 保存済みPDF（raw-pdf/）

| ファイル名 | 内容 | 出典 |
|---|---|---|
| 総-2_調剤報酬点数表_改正前後比較.pdf | 令和8年改正 調剤報酬点数表（傍線が改正部分） | 厚労省 |
| 総-1_個別改定項目.pdf | 中医協 個別改定項目（短冊） | 厚労省 |
| 調剤報酬改定概要.pdf | 令和8年度改定概要スライド【調剤】 | 厚労省 |
| 調剤点数表_告示.pdf | 令和8年厚生労働省告示第69号 | 厚労省 |
| 調剤点数表_留意事項.pdf | 保医発0305第6号（留意事項通知） | 厚労省 |
| 疑義解釈その1_令和8年3月23日.pdf | 令和8年 疑義解釈その1 | 厚労省 |
| 疑義解釈その2_令和8年3月31日.pdf | 令和8年 疑義解釈その2 | 厚労省 |

## 保存済みPDF（raw-pdf/gigi-kaishaku/）　疑義解釈 各年度その1

| ファイル名 | 対象年度 | 施行 |
|---|---|---|
| R6_その1_令和6年3月28日.pdf | 令和6年（2024年） 診療報酬改定 | 2024年6月 |
| R4_その1_令和4年3月31日.pdf | 令和4年（2022年） 診療報酬改定 | 2022年6月 |
| R2_その1_令和2年3月31日.pdf | 令和2年（2020年） 診療報酬改定 | 2020年4月 |
| H30_その1_平成30年3月30日.pdf | 平成30年（2018年） 診療報酬改定 | 2018年4月 |
| H28_その1_平成28年3月31日.pdf | 平成28年（2016年） 診療報酬改定 | 2016年4月 |

> ※疑義解釈ページ（九州厚生局）: https://kouseikyoku.mhlw.go.jp/kyushu/iryo_shido/shinryohoshu_gigikaisyaku.html

## テキスト抽出済み（直下）

| ファイル名 | 内容 |
|---|---|
| 調剤報酬点数表_改正前後テキスト.txt | 総-2のテキスト全文（pdfminer抽出） |
| 個別改定項目テキスト.txt | 総-1のテキスト全文 |
| 疑義解釈テキスト_H28.txt | H28年 疑義解釈その1 全文 |
| 疑義解釈テキスト_H30.txt | H30年 疑義解釈その1 全文 |
| 疑義解釈テキスト_R2.txt | R2年 疑義解釈その1 全文 |
| 疑義解釈テキスト_R4.txt | R4年 疑義解釈その1 全文 |
| 疑義解釈テキスト_R6.txt | R6年 疑義解釈その1 全文 |
| 調剤関連疑義解釈まとめ.txt | H28〜R6 調剤関連Q&Aの抜粋まとめ |

## WordPress記事との対応

| 記事 | WP ID | スラッグ | ステータス |
|---|---|---|---|
| 全体マップ記事（2024vs2026比較） | 336 | chosei-hoshu-2024-2026-hikaku | 下書き |
| 調剤基本料 詳細解説 | 338 | chosei-kihonryo-kaisetsu | 下書き |
| 薬剤調製料 詳細解説 | 未作成 | yakuzai-chosei-ryo-kaisetsu | 予定 |
| 調剤管理料 詳細解説 | 未作成 | chosei-kanri-ryo-kaisetsu | 予定 |
| 服薬管理指導料 詳細解説 | 未作成 | fukuyaku-kanri-shido-ryo-kaisetsu | 予定 |
| 在宅患者訪問薬剤管理指導料 詳細解説 | 未作成 | zaitaku-yakuzai-kanri-shido-kaisetsu | 予定 |
| その他薬学管理料 詳細解説 | 未作成 | yakugaku-kanri-ryo-others-kaisetsu | 予定 |

## 主要URLソース

### 厚生労働省（一次資料）
- 令和8年度改定（法令・告示・通知・Q&A）: https://www.mhlw.go.jp/stf/newpage_67729.html
- 令和8年度改定 説明資料: https://www.mhlw.go.jp/stf/newpage_71068.html
- 中医協総会 議事録・資料: https://www.mhlw.go.jp/stf/shingi/shingi-chuo_128154.html

### 製薬会社・業界
- 日医工 Stu-GE（改定資料一覧）: https://stu-ge.nichiiko.co.jp/mpi_documents/mpi_categories/1
- 管理薬剤師.com 令和8年改定まとめ: https://kanri.nkdesk.com/houshu/r8.php
