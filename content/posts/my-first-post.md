+++
title = 'GitHub Pages + Hugo でブログ構築'
date = 2024-02-17T21:31:45+09:00
tags = ['技術ネタ']
draft = true
+++

# このブログは

このブログのコンテンツは大きく2つ：
1. 技術的なこと
2. 小説・web小説，そのほか映画作品等に関するレビュー
3. 日常で考えを巡らせたこと
    - 例：負けず嫌いって何だよ，など

について，綴っていく．

# ブログ構築の流れ

　大きな流れは，
1. Hugo のインストール（ローカル；必要か？）
2. Gitレポジトリ作成，Githubにpush
3. GitHub Pages の設定
4. 確認

という流れ．  
　あとで別エントリーに書こうと思うが，中古で購入した2015年製のMBA11インチを書き物専用マシンにするつもりなので，Hugoのインストールあたりで色々と追加でインストールが発生してちょっと苦労した．  
　あとは，GitHubの2段回認証が入ったため，アクセストークンを取得したりもちょっと戸惑ってしまった．時代に乗り遅れている．反省．

## 1.Hugoのインストール
基本的には，`brew`でいける．自分の場合は，`brew`のインストールと，どうしてもデフォルトの`zsh`に耐え難かったので，`fish`を軽い見通してインストールした結果，非力なことも手伝って結構時間がかかってしまった．

```
brew install hugo
mkdir <your_path_to_blog>
cd !$ # bash
```

