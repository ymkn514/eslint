# ESLintの世界へようこそ

PRレビューを出して, 同僚に「console.logが残っています」のコメントをさせるのは心苦しい.  
スペースを開ける/開けない, 改行のルール, それらを整えるだけでも, コードのメンテナンス性は向上するでしょう.


プロジェクトの数ほどコーディング規約は存在しますが, ここではそれぞれのルールに詳しい解説があるAirbnb社のコーディング規約をベースにしました.


[airbnb/javascript](https://github.com/airbnb/javascript)  
[Javacript-style-guide by mitsuruog（日本語訳）](https://mitsuruog.github.io/javascript-style-guide/)

## 使い方

### 1. インストール

```
$ yarn install
または
$ npm install
```

※ PCにNode環境が揃っていない場合はNodeをインストールして下さい


### 2. Let's ESLint
ルート配下にある target/ フォルダに検証したいファイルをコピーします.

```
$ yarn eslint
または
$ npm run eslint
```

コーディング規約に違反している箇所が出るので修正します.  
`-- fix` オプションをつけて実行するとESLint側で直せるものは自動修正されますが, 自分でも確認をしたほうが良いでしょう.
