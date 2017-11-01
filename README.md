# study TensorFlow

## 1. download & install anaconda distribution > Python 3.6 version

https://www.anaconda.com/distribution/

## 2. install TensorFlow from Anaconda-Navigator

start Anaconda-Navigator

Environments > Create
作成した environment の 右矢印アイコンから、Open Terminal を選択。
anaconda は、bash にしか対応しておらず、デフォルトシェルを zsh にしている場合、エラーが出て進まない。Terminal の環境設定から、デフォルトシェルを、bash に変更しておく必要がある。

```
// インストール tensorflow
$ pip install tensorflow
```

```
// インストール確認
$ python
$ import tensorflow

$ exit()
$ exit
```