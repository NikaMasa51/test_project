# ディープラーニングによる雑草の画像分類モデル



## By whom?

勘崎秀門 石井昌範

東京大学フィールドフェノミクス研究拠点


## What is it?

- 雑草分類に関する深層学習のチュートリアル。
- Google Colaboratoryベースのノートブックです。 必要なのは、インターネット接続、Google Chromeブラウザ、およびGoogleアカウントだけです。 **クリックでGPU学習環境！**
- ノートブックを開くには、各セクションの ![image](https://colab.research.google.com/assets/colab-badge.svg)をクリックします。 コードのカスタマイズと保存には、GoogleアカウントにログインしてローカルのGoogleドキュメントフォルダーにipynbをコピーすることをお勧めします。
## Note

- このノートブックの目的は、非情報学者向けに植物科学と農業でディープラーニングを実行する方法の概要を取得することです。
- バックグラウンドでTensorflowが動作するKerasは、ノートブックで使用されるメインのディープラーニングフレームワークです。

## Notebooks Open

### 01　雑草の生育期間を区別せずに分類器を作る(2020/5/25)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_training_01.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間（芽生え・生育済み）を区別せずに分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>

### 02　雑草の生育期間を区別して分類器を作る（芽生え）(2020/5/25)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_training_02.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間が芽生えのデータを用いて分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>

### 03　雑草の生育期間を区別して分類器を作る（生育済み）(2020/5/25)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_training_03.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>

### 04　科目が同じ品種をグループにして分類器を作る（生育済み）(作成中)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_training_04.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
ハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類の雑草のうち科目が同じのものを一つのclassにまとめるます。イネ科（イヌビエ、メヒシバ、オヒシバ）、キク科（ハキダメギク、コセンダングサ）とその他5種類に分けて分類器を作成します。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>

### 05　イネ科、ツル植物（マメアサガオ）、広葉雑草の3種類にクラスの分けして分類器を作る（生育済み）(作成中)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_training_05.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
ハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類の雑草をイネ科、ツル植物（マメアサガオ）、広葉雑草の3種類に分けて分類器を作成します。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>

<!--
### VGG16をファインチューニングして雑草分類（アンサンブル学習）(2020 5/9)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikaMasa51/test_project/blob/master/notebook/weed_VGG16_fine_tuning_cls09_2_1.ipynb) <br>

![badge](https://img.shields.io/badge/type-classification-blue.svg) ![badge](https://img.shields.io/badge/tag-CNN-green.svg)  ![badge](https://img.shields.io/badge/tag-Transfer_Learning-green.svg) ![badge](https://img.shields.io/badge/tag-Fine_Tuning-green.svg)

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
ハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類の雑草をイネ科、ツル植物（マメアサガオ）、広葉雑草の3種類に分けて分類器を作成します。
さらに今回は3つのtrainデータを作成しアンサンブル学習を行いました。

![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。

<br>
-->

