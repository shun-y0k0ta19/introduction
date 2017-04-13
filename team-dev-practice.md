<!-- $theme: gaia -->

# チーム開発実践入門勉強会

# ![](hyoshi.jpg)

#### Directed by [@y0k0ta19](https://github.com/y0k0ta19)


----
### 目的
* **チーム開発でのアンチパターンの学習**
	* 代表的なアンチパターンは確実にプロジェクトから排除できる
* **モダンな開発環境ツールの習得**
	* [github](https://github.com), [jenkins](https://jenkins.io/), [チケット管理ツール](https://ja.wikipedia.org/wiki/%E3%83%90%E3%82%B0%E7%AE%A1%E7%90%86%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0), [AWS](https://aws.amazon.com/jp/), [heroku](https://www.heroku.com/), [Docker](https://www.docker.com/), [Selenium](http://www.seleniumhq.org/) 等を普通に使えるようになる
* **チーム開発における作法習得と文化醸成**
	* 世界標準のS/Wエンジニアとなる(第一歩):clap:
	* 世界中のOSSにビビらずにプルリクを出せる:+1:

----
### 達成目標
* **git-flow, github-flowでの運用ができるようになる**
	* [git-flow](https://www.atlassian.com/ja/git/workflows#!workflow-gitflow), [github-flow](https://gist.github.com/Gab-km/3705015)を理解し、プロジェクトに応じて最適な運用を行える。
*  **自動テスト、自動ビルド、自動デプロイ環境を整備できる**
	* [jenkins](https://jenkins.io/)や各種CI環境を利用して、自動テスト、自動ビルド、自動デプロイ環境を構築できる。 
* **チケット管理ツールを運用できる**
	* 誰がどのタスクでどんな作業をしたかを全てトラッキングできる。
 
----
### 勉強会の進め方
* **輪講方式**
	* 各章ごとに担当を決め、概要を説明する
	* 参加者も事前にその回の範囲を読んでおく
	* 様々な議論をする
		* 参加者は事前に質問を書いておく？
* **チーム開発の実践**
	* 実際にツールを使ってチーム開発をしてみる
	* そこでの気付きや運用方法を議論に加える
	* **OSSとしてリリースする**

----
### 事前準備
* **「[チーム開発実践入門](http://gihyo.jp/book/2014/978-4-7741-6428-1)」の購入**
	* kindleないです:sweat_drops: 電子版は[技術評論社](https://gihyo.jp/dp/ebook/2014/978-4-7741-7015-2)から
* **[github](https://github.com)アカウントの作成・共有**
	* 持ってない人はすぐに作りましょう
	* [@y0k0ta19](https://github.com/y0k0ta19)をフォロー
	* [team-dev-practice ](https://github.com/team-dev-practice)へ参加(招待します)

----
日程   |    範囲   |担当| | 日程  |   範囲   | 担当
------|----------|----|-|------|----------|---
 4/25 | 2.1-2.3  | | | 7/11 | 5.2      |
 5/9  | 2.4-2.7  | | | 7/18 | 5.3      |
 5/16 | 3.1, 3.2 | | | 7/25 | 5.4      |
 5/23 | 3.3-3.5  | | | 8/1  | 5.5, 5.6 |
 5/30 | 3.6      | | | 8/8  | 6.1-6.3  |
 6/6  | 3.7-3.10 | | | 8/22 | 6.4      |
 6/13 | 4.1, 4.2 | | | 8/29 | 6.5      |
 6/20 | 4.3      | | | 9/5  | 6.6, 6.7 |
 6/27 | 4.4-4.7  | | | 9/12 | 7.1, 7.2 |
 7/4  | 5.1      | | | 9/19 | 7.3-7.6  |

----
### 作りたいもの・開発に必要なもの
* (例)[Visul studio code](https://www.microsoft.com/ja-jp/dev/products/code-vs.aspx)のExtension
	* [Electron](https://electron.atom.io/)開発環境
* (例) 何かのbot(笑)
	* テスト用デプロイ環境([heroku](https://www.heroku.com/)), DB([redis](https://redis.io/)) 