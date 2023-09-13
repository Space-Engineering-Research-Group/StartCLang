# C言語プログラミング

## 開発環境

- Visual Stadio Code (エディタ)
- gcc compiler (コンパイラー)

## 環境構築

- Visual Studio Codeを[ダウンロード](https://code.visualstudio.com/)
- GCCを[ダウンロード](https://www.mingw-w64.org/downloads/)

### GCCダウンロード手順

1\. ここをクリック
![GCCのダウンロード場所](img/Screenshot%202023-09-10%20151403.png)

![GCCダウンロード](img/mingw_install_20221028_2.png)

![GCCインストーラーをダウンロード](img/mingw_install_20221028_3.png)

2\. ダウンロードしたインストーラーをダブルクリック

![GCCinstall](img/Screenshot%202023-09-10%20160006.png)

3\. インストール手順

アーキテクチャを**x86_64**にする

![GCCinstall](img/Screenshot%202023-09-10%20160156.png)

インストールするフォルダーをこのように変更する

![GCCinstall](img/Screenshot%202023-09-10%20160249.png)

Nextを押してインストール完了

### GCCがインストールできたら

1\. 環境変数を変更する
![EditEnvironmentVariables](img/Screenshot%202023-09-10%20161558.png)

![EditEnvironmentVariables](img/Screenshot%202023-09-10%20161837.png)

![EditEnvironmentVariables](img/Screenshot%202023-09-10%20162100.png)

新規をクリックし

`C:\Program Files\mingw-w64\bin`

![EditEnvironmentVariables](img/Screenshot%202023-09-10%20162714.png)

コピペして**OK**をクリックして環境変数の設定は完了

### コマンドプロンプトで確認

1\. コマンドプロンプトを起動

2\. `gcc -v`と打つ

3\. 正しく表示されたら完了