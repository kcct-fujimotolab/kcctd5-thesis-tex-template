# 卒論テンプレート for TeX

学科指定の TeX スタイルファイル `abstract.sty` を含んでいます．

このリポジトリを複製し，各々のリポジトリ上で卒論を管理することを意図しています．

## 使い方


1. リモートリポジトリを作成する．

  [:pencil2: New repository](https://github.com/organizations/kcct-fujimotolab/repositories/new)

2. コマンドを叩く．
  
  ```
  git clone git@github.com:kcct-fujimotolab/thesis-tex-template.git <YOUR_DIRECTORY>
  cd <YOUR_DIRECTORY>
  git remote set-url origin <YOUR_REPOSITORY>
  git push
  ```
  
  - `<YOUR_DIRECTORY>`: clone 先ディレクトリパス
    - 1 で作成したリモートリポジトリ名を指定するとよいです．
  - `<YOUR_REPOSITORY>`: 1 で作成したリモートリポジトリの URL
    - e.g. `https://github.com/kcct-fujimotolab/hoge`, `git@github.com:kcct-fujimotolab/hoge.git`
