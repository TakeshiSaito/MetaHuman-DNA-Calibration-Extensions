# MetaHuman-DNA-Calibration-Extenensions

## 概要

MetaHuman関係の拡張ツールをまとめたリポジトリです。今現在はフェイシャル再生ツールのみあります。

リポジトリ直下の[run_maya202◯.ps1](run_maya2023.ps1)を実行すると、本ツールへパスが通った状態でMayaが起動します。

<br>

対応バージョンは以下の通りです。

- Maya 2022
- Maya 2023

---

## MetaHuman Facial Importer

### 概要

LiveLinkFaceから出力したCSVファイルを、maya上のメタヒューマンのフェイシャルリグへ適用します。

### 使い方

### 起動方法

メニューバーの「MetaHuman」から「MetaHuman Facial Importer」を選択します。

### フェイシャルアニメーション再生までの手順

1. DNAファイルを指定してリグつきメタヒューマンを読み込む。
2. CSVを指定してフェイシャルアニメーションを読み込む。

<br>

#### Import rig | リグのインポート

![img.png](.github/img.png)

フェイシャルアニメーション再生に必要なリグつきで、メタヒューマンを読み込むことができます。

1. "Import rig"のグループの入力フィールドに、DNAファイルのパスを入力します。
2. Importボタンを押下します。

<br>

#### Import facial animation | フェイシャルのインポート

![img.png](.github/img2.png)

フェイシャルリグつきメタヒューマンにcsvのアニメーションを適用します。

1. ”Import facial animation”グループの入力フィールドに、CSVファイルのパスを入力します。
2. Importボタンを押下します。
