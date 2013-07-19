---
layout: default
root: .
title: 採用事例(国内)
---

## 採用事例(国内)

このページでは、国内のScala採用事例の一部について紹介します。

### [株式会社 システムアート](http://www.sysart.jp/)

業務システムにScalaを導入しています。

* 2010年～ クラウド就業システム
	* 大学/病院/製造/放送を含む10社以上
	* 個社別の細かい要求に対応、日本語コーディング
* 2010年～ PDF署名サービス
	* Javaシステムを機能追加毎にScalaへ部分移行
	* Springなど既存JavaフレームワークとScalaコードの共存
* 2011年～ 会計EDI
	* 国税・地方税を申告するためのサーバー機能
	* Flexクライアント、および国税局等が配布しているクライアントとXML連携
* 2012年～ VB6パーサー
	* レガシーシステムのマイグレーションで利用
	* JavaCCパーサーをScalaパーサーコンビネーターへ移植

### [GMOメディア株式会社](http://www.gmo-media.jp/)

* [リワード広告システム](https://docs.google.com/leaf?id=0B3gzkyf0Dd_5M2QzMGRkOTUtYTJlNC00YWZhLTg4ODgtOTlmYTg1M2NiNWU3)
* [タイムラインシステム](http://www.slideshare.net/hitoasa/mongodb-13561725)

上記のリンク先のスライドでは、MongoDBの話が多く、Scalaの部分の詳細には触れていませんが、Scalaに関しては

* [kestrel](https://github.com/robey/kestrel),
* [casbah](https://github.com/mongodb/casbah),
* [scalatra](https://github.com/scalatra/scalatra),
* [lift(lift-jsonの部分のみ)](https://github.com/lift/framework),
* [grabby-hands](https://github.com/twitter/grabby-hands),
* [configgy](https://github.com/robey/configgy)

など、twitter社がopen sourceで提供しているライブラリなどを使用しています。

* レコメンデーションシステムのバックエンド  
Scala から MySQL にアクセスするために [querulous](http://github.com/twitter/querulous) というライブラリを使用するなど

### [株式会社パテントビューロ](http://www.patentbureau.co.jp/)

* [astamuse](http://astamuse.com/) （知財メディア）
* [転職ナビ](http://robots-job.com/) （転職サイト – 独自CSM内蔵）
* その他多数

### [有限会社ITプランニング](http://www.itpl.co.jp/)

某社のサービス用APIとデータ管理WebインターフェイスをScala + LiftでGAE上に構築しました。APIはXMLを応答する仕様であり、ScalaのXMLリテラルによって、応答すべきXMLとScalaのプログラムとをシームレス/簡潔に記述できた点は、他言語ではできなかった良さでした。また、LiftのBox型とfor構文の活用により、APIパラメーターの妥当性チェックと異常系応答処理の記述がシンプルに書けた点も優れていました。約44個のScalaファイル、合計3800行程の開発規模です。

某Android用アプリケーションをScalaで記述しました。利用できる資産との兼ね合いでJavaを使った部分もありましたが、そのような状況でもScalaの高い記述力を部分的にでも活かせる点は興味深かったです。

[NGMS](http://sourceforge.jp/projects/ngms/)と呼んでいるネットワーク管理支援システムを名古屋大学様、SRA様と共同でScalaを中心に開発しました。CUIインターフェイスの特性から文字列のパースを行う機会が多く、Scalaのパーサーコンビネーターが開発効率に大きく寄与しました。4万行を超える中規模システムですが、Scalaコンパイラが大きな問題となったことはありません。

### [エムスリー株式会社](http://corporate.m3.com/)

いくつかのサービスやシステムを Scala で開発・運用しています。
社内のデータ集計や運用のためのツールなどにも Scala を利用しています。
その他、公開可能なものは [GitHub](https://github.com/m3dev) に置いています。

* コンテンツ配信システム（Play 20 Scala）
* 会員向けサービス（Scalatra）
* 社内向け API サーバ（Unfiltered）
* アクセスログ集計などの社内共通ライブラリ
* その他 [GitHub](https://github.com/m3dev) で公開しているもの

### [芸者東京エンターテインメント株式会社](http://www.geishatokyo.com/)

スマートフォン、フィーチャーフォン向けのソーシャルアプリの企画、開発、運用を行なっており、
以下のサービスをscala2.7.7+Lift(webアプリケーションフレームワーク)で構築しています。

サービス一覧

* おみせやさんforGREE (GREE)
* おみせやさん2 (mixiゲーム)
* お金持ちさん(GREE)
* お金持ちさんDX(mixiアプリ)

### [NECビッグローブ株式会社](http://www.biglobe.ne.jp/)

友達とおすすめのアプリを教えあうサービス[Let’s App!のサーバ](http://letsapp.jp/)が
[Play Framework 2.0 + Scala 2.9.1で書かれている](http://engineer.biglobe.ne.jp/201207/article_1.html)とのことです。
