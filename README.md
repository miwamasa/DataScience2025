# DataScience2025


<div dir='rtl'>
産業技術大学院大学</br>
担当: 岩政</br>
2025年4月8日～6月3日
</div>


「データサイエンス特論」(2025/1Q)の講義用公開リポジトリです

講義スライドはmanabaにて配布します.

## 講義概要

- 講義日時：
  - 火曜6限(18:30～20:00)、金曜6限(18:30～20:00)
- 講義形式
  - ハイフレックス式
- 計算機環境
  - Google Colaboratory を使います
- テスト
  - 毎回、簡単なミニテストを行います
  - 中間レポート３回
  - 最終レポート

## 講義日程と実習用の jupyter notebookの配布

この講義では、計算機実習を Google Colaboratory を使って行います。以下の**Open in Colab**ボタンを押すとColaboratoryの画面に遷移します。このページを残したい場合は、右クリックで「新しいタブで開く」と新しいタブで開くこともできます。

![](https://colab.research.google.com/assets/colab-badge.svg)


- 講義スライドは manabaで提供します。
- 参考図書：[データサイエンス教本（第2版）、橋本・牧野](https://www.ohmsha.co.jp/book/9784274231148/)

|講義|日程|内容|Colabへのリンク|status|
|---|---|---|---|---|
|Lecture1|4/8(火) |はじめに||
|||Colaboratryのテスト| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture1.ipynb)|ok|
|||ColabでLLMを動かす(youri_7b)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture1_youri_7b_instruction_gptq.ipynb)|in preparation|
|||ColabでLLMを動かす(open_calm_3b)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture1_open_calm_3b.ipynb)|in preparation|
|Lecture2|4/11(金) |Python入門、統計の復習|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture2.ipynb)|in preparation|
|Lecture3|4/15(火) |データの取得と操作|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture3.ipynb)  |in preparation|
|||pandasの利用|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture3_pandas.ipynb) |in preparation|
|||実習| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture3_practice.ipynb)  |in preparation|
|Lecture4|4/18(金)|データの可視化| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture4_matplotlib.ipynb)|in preparation|
|||マンガで学ぶ..「1.棒グラフ」|[![Open In Colab]](https://colab.research.google.com/github/miwamasa/DataScience2025/blob/main/notebooks/lecture4_extra_1.ipynb)|  |in preparation|
|||Extra(アンケート結果)| |in preparation|
|Lecture5|4/22(火)|統計分布の基礎 ||in preparation|
|Lecture6|4/25(金)|回帰分析1| |in preparation|
|||事例(Game)| |in preparation|
|Lecture7|4/29(火)|回帰分析2| |in preparation|
|||重回帰分析（変数選択）| |in preparation|
|||重回帰分析（交絡因子）| |in preparation|
|||重回帰分析（ダミー変数）| |in preparation|
|Lecture8|5/9(金)|パターン認識1||in preparation|
|||SVMの例||ok|
|||SVMを最適化で解く||in preparation|
|Lecture9|5/13(火)|パターン認識2|
|||クラス分類| |in preparation|
|||クラスタリング| |in preparation|
|Lecture10|5/16(金)|動的システムの表現| |in preparation|
|Lecture11|5/20(火)|時系列||in preparation|
|Lecture12|5/23(金)|状態空間モデル||in preparation|
|||周波数分析||in preparation|
|Lecture13|5/27(火)|画像分析||in preparation|
|Lecture14|5/30(金)|LLM時代のデータサイエンスとは|
|||Transformer入門||in preparation|
|||テキスト生成||in preparation|
|||Q&A||in preparation|
|||OllamaでRAG||in preparation|
|||LLMでtitanic分析|  |in preparation|
|Lecture15|6/3(金)|発展的話題とまとめ|
|予備|6/6(火)|


<!-- |Lecture3|4/13(水)|データの可視化| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture3_matplotlib.ipynb)|in_progress|
|Lecture4|4/16(土)|統計分布の基礎 |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture4.ipynb)|in_progress|
|Lecture5|4/20(水)|回帰分析1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture5.ipynb)|in_progress|
|||重回帰分析|
|Lecture6|4/23(土)|回帰分析2|
|Lecture7|4/27(水)|パターン認識1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7.ipynb)|in_progress|
|||SVM|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7_SVM.ipynb)|in_progress|
|Lecture8|4/30(土)|パターン認識2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture8.ipynb)|in_progress| -->

## テスト
- ミニテスト：manabaで行います
- 中間レポート：manabaで行います
- 最終レポート：manabaで行います

## 連絡事項

<!-- - report1の例：[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2024/blob/main/notebooks/2023report1_sample.ipynb)

- report2の例：[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2024/blob/main/notebooks/2023report2_sample.ipynb) -->


