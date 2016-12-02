# GitLab/GitLab.com 勉強会 第二回

## GitLab の概要

#### 2016/12/3(土)

##### 福留　誠二

---

## 自己紹介
- 職業:SE
- 最近の動向
  - チームがかわり去年あたりからOSSに触れ始める
  - 楽しいが英語力がないため辛い
- 現在の仕事:社内サーバにあるGitLab CEを社内流行らせる啓蒙活動

---

アジェンダ
- GitLab とは?
- 主要となる機能の紹介
- GitHub との違い
- サービス版の GitLab.com と OSS 版の GitLab CE との違い

---

# GitLabとは？

---
# の前に・・・
---

### 詳しい内容は

2015年12月にありました

## [GitLab/GitLab.com 勉強会](https://kagoben.doorkeeper.jp/events/35948)

の

## [政倉さんのスライド](https://masakura.github.io/gitlab-slide)

### を見てください！

わかりやすいです。

今回の発表は個人的な感想が多めです。

GitLab,GitHubの料金で変更があった分は今回ご紹介します。

---

### 改めまして、GitLabとは？

---

### GitLabとは
- gitリポジトリのホスティングサービス
- GitLab は GitHub のクローン(パクリ)
  - なのでGitHubの基本的な機能はそのまま使える

[GitLabisGitHubClone](./resources/gitlabisclone.png)

---

### GitLabとは

利用形態を選べます。

- クラウド版 GitLab.com `無償`（有償サポートも有り）
  - プライベートリポジトリ有り！ １プロジェクト10GBまで！
- オンプレミス GitLab CE(Community Edition) OSS `無償`
- オンプレミス GitLab EE(Enterprise Edition) 機能強化 `有償`

### とにかく使ってみたい人はGitLab.comを利用してみてください

---

アジェンダ
- GitLab とは?
- `主要となる機能の紹介`
- GitHub との違い
- サービス版の GitLab.com と OSS 版の GitLab CE との違い

---

主要となる機能の紹介
- Issue Tracking System
- Groups (GitHubでいう Oragnization)
- Markdown
- Merge Requests (GitHubでいう Pull Request)

---

#### Issue Tracking System
- バグや機能提案や要望等の管理を行う

[Issue Tracking System](./resources/issues.png)

---

#### Issue Tracking System
- 課題について議論することができる

[Issue Tracking System Community](./resources/issuescomment.png)


---
#### Issue Tracking System

課題管理だけに使うのは勿体無い

- ソフトウェアのバグレポート
- 作者に相談したいこと、聞きたいこと
- 今後、実施する予定のタスクの書き出し
- 飲み会の場所決め

プロジェクト活動などでは不確定な要素や不安ごと書き出していき、議論する場を設ければ、自然と目を逸らしていた課題に全員が向き合えるようになります。

---
#### Groups
- 誰でも作れる
- プロジェクトをグループ化
- 複数のプロジェクトに一度にユーザーを割り当てることができる

[Groups](./resources/groups.png)

---
#### Groups

個人のプロジェクトでもメンバーを追加すれば問題ないのでは？

---
#### Groups

- 個人プロジェクト
  - プロジェクトを作った人がメンバーから抜けたら
  - １つの企画で複数のプロジェクトを作る場合かなり面倒
- Groups
  - 作った人が抜けてもOK
  - １回の操作で複数プロジェクトにメンバーを追加できる

## 多人数でモノ作りならGroups機能はおすすめ

---

#### Markdown
- 軽量マークアップ言語
- 表示はマークアップなので簡単な記法でプレーンテキストより豊富な表現力
[Markdown](./resources/markdown.png)

---
#### Markdown

GitLabでMarkdownを表現出来る場所
- comments
- issues
- merge requests
- milestones
- snippets (the snippet must be named with a .md extension)
- wiki pages
- `markdown documents inside the repository`

### GitLabの基本の文章はMarkdown!

---
#### Markdown

先ほどの`markdown documents inside the repository`

markdownファイル(.md)をリポジトリに入れたらマークアップで表現してくれる
[repository in markdown](./resources/reposmarkdown.png)

---

#### Markdown
- GitLabはリポジトリのルートフォルダにREADME.mdを作るとプロジェクトトップページに表示されます。
- README.mdはMarkdownなのでプロジェクトトップページが華やかになります。
[REAME](./resources/readmemarkdown.png)
---

#### Markdown

プロジェクトトップページにMarkdownを用いれば

- なんの為のプロジェクトなのか
- 開発環境の構築
- 現在のバージョン
- 使い方
- 関係者

等の情報を見やすく載せることができ、プロジェクトの目的やメンバー追加時の導線を常に確認することができます。

---

#### Markdown

GitLabの為だけではない Qiita はてなブログ等も対応

ちなみに今回のスライドもMarkdownで作っています。

---

#### Merge Requests
相手に自分の変更分ブランチの取り込みを依頼する

[Merge Requests](./resources/mergerequests.png)


---
#### Merge Requests
- Merge RequestsはIssueと同じで議論ができる
- Merge Requestsされた資産に対してコメントも出来る

[Merge Requests Community](./resources/mergerequestscomment.png)

---

## Merge Requestsは個人的にすごく良いと思います。

---

#### Merge Requestsをすると何が起きるのか
- 人に依頼するのでコミットの単位が綺麗になる
- ついでにコミットメッセージがわかりやすくなる
- コメントが直接書けるのでソースレビューがやりやすい
- ブランチを分けることで機能に集中できる
- 二人以上いればお互いにレビューし合える

#### おすすめです


---

アジェンダ
- GitLab とは?
- 主要となる機能の紹介
- `GitHub との違い`
- サービス版の GitLab.com と OSS 版の GitLab CE との違い

---
#### GitHubとの違い

## GitLab CE 価格

[GitLab | Products](https://about.gitlab.com/products/)

| 製品 | 価格 (年額) | 単価 (一人)
| ---- | ----: | ----:
| GitHub Enterprise | $2,500 (10 users) | $250
| GitLab CE <!-- .element: style="background-color: #666600" --> | Free <!-- .element: style="background-color: #aa0000" --> | Free <!-- .element: style="background-color: #aa0000" -->
| GitLab EE <!-- .element: style="background-color: #666600" --> | $390 (10 users) | $39

---
#### GitHubとの違い

## GitLab.comの価格

[GitLab | About ](https://about.gitlab.com/gitlab-com/)

| 製品 | 価格
| ---- | ----:
| GitHub (Public) | Free <!-- .element: style="background-color: #aa0000" -->
| GitHub Private (Personal) | $7
| GitHub Private (Organization ) | $9 ($25/mo first 5 users)
| GitLab.com (Public) <!-- .element: style="background-color: #666600" --> | Free <!-- .element: style="background-color: #aa0000" -->
| GitLab.com (Private) <!-- .element: style="background-color: #666600" --> | Free <!-- .element: style="background-color: #aa0000" -->
| GitLab.com (Private/Bronze) | $199.80 (20 users)

---

#### GitHubとの違い
- 無償でプライベートリポジトリが作れる！
- 無償OSSのオンプレミス版がある
  - インストールも簡単！
  - Raspberry Piにも入れられる！
- 標準でBord(看板)がある！
- CIはGitHubは外部を利用するがGitLabはGitLab CIで統合されているサービスを利用

---

#### GitHubとの違い
- GitLab CEにはgithabpagesみたいなのがない・・・
- GitLabにはSNS機能がない・・・
- やはりサービスはGitHubが豊富

---

アジェンダ
- GitLab とは?
- 主要となる機能の紹介
- GitHub との違い
- `サービス版の GitLab.com と OSS 版の GitLab CE との違い`

---
#### サービス版の GitLab.com と OSS 版の GitLab CE との違い
基本的なこと


---
----
