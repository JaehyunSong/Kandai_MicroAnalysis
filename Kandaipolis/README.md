# Kandaipolis Theme for {xaringan}

* 関西大学総合情報学部「ミクロ政治データ分析実習」および「マクロ政治データ分析実習」のスライド用テーマ
* {xaringan}使用を想定しています。
* Metropolisテーマをベースとしています。
* 使う際は、プロジェクトの`CSS`フォルダーに`.css`ファイルと`.js`を保存し、ヘッダーに以下のように定義します（以下は例）。

```yaml
---
title: "ミクロ政治データ分析実習"
subtitle: "第3回 Rの基本的な操作"
author: "宋財泫"
institute: "関西大学総合情報学部"
date: "2021/4/22 (updated: `r Sys.Date()`)"
output:
  xaringan::moon_reader:
    css: ["CSS/kandaipolis.css", "CSS/kandaipolis-fonts.css"]
    lib_dir: libs
    nature:
      beforeInit: ["CSS/kandaipolis-macro.js"]
      highlightStyle: github
      highlightLines: true
      highlightSpans: true
      countIncrementalSlides: false
    yolo: false
    seal: true
editor_options: 
  chunk_output_type: console
---
```

* `kandaipolis-macro.js`には画像サイズを指定するマクロが定義されています。
   * 画像サイズを%で指定する場合: `![:scale 100%](画像ファイルのパス)`
   * 画像サイズを幅を基準に指定する場合: `![:width 300px](画像ファイルのパス)`
   * 画像サイズを高さを基準に指定する場合: `![:height 200px](画像ファイルのパス)`
