# ミクロ政治データ分析実習
関西大学総合情報学部「ミクロ政治データ分析実習」サポートページ

## 講義情報
* 担当教員: 宋財泫 (そん じぇひょん; SONG JAEHYUN)
  * 関西大学総合情報学部 准教授
  * E-mail: song [at] kansai-u.ac.jp
  * Homepage: https://www.jaysong.net
* 春学期 木曜日 第4時限 (14:40～16:10)
* TC304教室（高槻キャンパス C棟 304教室）
* オフィスアワー: 毎週火曜日 14:00〜16:00 A棟 TA227研究室

## 講義資料
NIIオンライン分析システムの起動: [![NII](https://binder.cs.rcos.nii.ac.jp/badge_logo.svg)](https://jupyter.cs.rcos.nii.ac.jp/) (初期設定が必要)

* スライドはPDFであり、動的な要素（動画、JavaScriptを利用した表、タイマーなど）は正しく表示されません。ただし、講義内容の理解に影響を与える問題ではございません。
  * <u>資料をダウンロードする</u>際は、以下のリスト上の資料クリックして表示される画面で「Download」、または「Raw」を右クリックして保存してください。
* 第4回以降は実習用資料（`.Rmd`）をダウンロードし、穴埋め形式でスライドを作成して頂くことになります。
  * 第4回以降のスライドは授業から3日後に公開します。

|回|題目|スライド|データ|参考資料|
|:-:|:-|:-:|:-:|:-:|
| 1|ガイダンス| [DL](Slide/Slide01.pdf) | - | - |
| 2|RとRStudioの導入| [DL](Slide/Slide02.pdf) | - | - | [教科書第2章](https://www.jaysong.net/RBook/aboutR.html) <br/> [教科書第3章](https://www.jaysong.net/RBook/installation.html)  |
| 3|Rの基本的な操作| [DL](Slide/Slide03.pdf) | [Micro02_01.csv](Data/Micro02_02.csv) <br/> [Micro02_01.xlsx](Data/Micro02_01.xlsx) | [教科書第7章](https://www.jaysong.net/RBook/rbasic.html) |
| 4|R Markdownと再現可能な研究| [DL](Slide/Slide04.pdf) | - | [教科書第25章](https://www.jaysong.net/RBook/rmarkdown.html) |
| 5|データ型| [DL](Slide/Slide05.pdf) | - | [教科書第9章](https://www.jaysong.net/RBook/datatype.html) |
| 6|データ構造| [DL](Slide/Slide06.pdf) | [Micro06.csv](Data/Micro06.csv) | [教科書第10章](https://www.jaysong.net/RBook/datastructure.html) |
| 7|Rプログラミング基礎| [DL](Slide/Slide07.pdf) | - | [教科書第11章](https://www.jaysong.net/RBook/programming.html) <br/> [教科書第12章](https://www.jaysong.net/RBook/functions.html) |
| 8|データハンドリング（1）| [DL](Slide/Slide08.pdf) | [Micro08.csv](Data/Micro08.csv) | [教科書第13章](https://www.jaysong.net/RBook/datahandling1.html) <br/> [教科書第14章](https://www.jaysong.net/RBook/datahandling2.html) <br/> [教科書第15章](https://www.jaysong.net/RBook/factor.html) <br/> [教科書第16章](https://www.jaysong.net/RBook/tidydata.html)|
| 9|データハンドリング（2）| DL | - | 同上 |
|10|データハンドリング（3）| DL | - | 同上 |
|11|可視化（1）| DL | DL | [教科書第17章](https://www.jaysong.net/RBook/visualization1.html) <br/> [教科書第18章](https://www.jaysong.net/RBook/visualization2.html) <br/> [教科書第19章](https://www.jaysong.net/RBook/visualization3.html) <br/>  |
|12|可視化（2）| DL | - | 同上 |
|13|可視化（3）| DL | - | 同上 |
|14|データ収集とデータ分析のプロセス| DL | - | - |

---

## NIIオンライン分析システム

関大LMSに動画資料のURLがあります。詳細は動画を参照してください。
* **注意:** 初期設定は1回のみです。複数回行うと、初期設定の度に新しいサーバーが立ち上がります。


* 初期設定（1回のみ）
   1. https://binder.cs.rcos.nii.ac.jp へアクセス
   2. 「GitHub repository name or URL」欄に`https://github.com/JaehyunSong/Binder_R`を入力
   3. 「launch」をクリック
* 2回目以降
   1. https://jupyter.cs.rcos.nii.ac.jp/ へアクセス
   2. Named Seversリストから前回使用した分析環境を選択

---

## 教科書

* [Song Jaehyun・矢内勇生.『私たちのR: ベストプラクティスの探求』Web-book](https://www.jaysong.net/RBook)

## 参考書

* [浅野正彦・矢内勇生. 2018.『Rによる計量政治学』オーム社](https://www.amazon.co.jp/dp/4274223132)
* [Hadley Wickham・Garrett Grolemund. 2017.『Rではじめるデータサイエンス』オライリージャパン](https://www.amazon.co.jp/dp/487311814X)
  * 原著（英語）は無料で公開 (https://r4ds.had.co.nz/)
