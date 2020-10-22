# 職務経歴書

# Table of contents
- [基本情報](#基本情報)
- [職務経歴（概要）](#職務経歴概要)
- [スキル](#スキル)
- [職務経歴](#職務経歴)

## 基本情報

| 項目 | |
|---|-----|
|Name|Jun Nakajima|
|Twitter|[@jnuank_](https://twitter.com/jnuank_)|
|Qiita|[@jnuank](https://qiita.com/jnuank)|
|Wantedly|[Wantedly](https://www.wantedly.com/users/64214659)|
|SpeakerDeck|[Jun Nakajima](https://speakerdeck.com/jnuank)|
|LAPRAS|[LAPRAS](https://lapras.com/public/BGBJDIV)|
|connpass|[NakajimaJun](https://connpass.com/user/NakajimaJun/)|
|Blog|[jnuank blog](https://jnuank.hatenablog.com/)|

## 職務経歴（概要）

### エンジニア 2016年10月〜

- 社内用のWebアプリケーションの開発
  - Python、Django REST framework、Vue.js
- 介護施設向け入居者請求システム開発
  - bash、Python、AWS Lambda
- 客先向けの小売基幹システムの開発
  - bash
- 広告代理店向けのプロジェクト管理支援ツールの開発
  - C#、ASP.NET MVC5

### エンジニア以前 2009年4月〜2016年9月
- 医療機器(レントゲン、アンギオグラフィー、CT、MRI、US）のメンテナンス、修理、据付
- 無線LAN機器のコールセンターのオペレーター

## スキル

### 言語
#### フロントエンド
- HTML、CSS、JavaScript
- Vue.js

#### バックエンド
- Python
- C#
- Java
- Shell(bash)

### データストア
- SQLServer、PostgreSQL

### フレームワーク
- ASP.NET MVC5、Bootstrap
- Django、Django REST framework
- Spring Boot
- jQuery
- Vuetify

### インフラ
#### AWS
- EC2、Elastic Beanstalk
- Lambda、APIGateway、SQS、SNS
- RDS、DynamoDB
- VPC、IAM、S3、CloudFormation、CloudWatch

#### オンプレ

- Apache

#### OS
- Windows、Windows Server
- macOS
- Linux(CentOS、Amazon Linux)

### その他

- GitHub、 GitHub Actions、 SVN
- Sentry、Selenium IDE、TestCafe、Cypress
- Docker
- Serverless Framework
- PlantUML
- Google Jamboard、miro

### 開発プロセスなど

- スクラム
- モブプログラミング
- ユーザーストーリーマッピング
- RDRA2.0
- [Event Storming](https://www.eventstorming.com/)
- ふりかえり
  - KPT、YWT、FDL、タイムライン、4Ls


## 強み

- チームで取り入れた方がプラクティスを、なぜ必要なのかを踏まえながら、チームへ浸透させていくこと
- ぼっちで始めること、人を巻き込むこと 
- モブ/ペアプログラミングを取り入れながら、互いに教えあう文化を作っていくこと

## やったことはないが興味があるもの

- Scala/Akka、リアクティブアーキテクチャ
- 関数型言語でのプロダクト開発
- 自立したチームをつくること
- チーム全体でのドメインモデル駆動での設計・開発
- エンジニアの評価、組織制度の制定、運用


## 職務経歴

### 2018/07 - 現在 : ハンズラボ株式会社

顧客向けのシステム開発の受託、親会社従業員が使用する社内システムのアプリケーション開発に従事しています。
少人数のチームで要件定義・設計・開発・テスト・運用と開発プロセスを一通り経験することにより、
要件を組み立ててステークホルダーと合意を取ることの大切さや、複雑な業務ロジックをどうコード上で表現するかについて興味を持つようになっていきました。

また、チームリーダーを担う機会もあり、各々が自立的に考え、よりよいソフトウェアを作る為に意見を交わせるような自立的なチームをつくるためにはどうしたらよいか、とも考えるようになっていきました。

#### 2020/04 - 現在： 社内システムのレガシーマイグレーション
役割: Webアプリケーションエンジニア（メンバー）
チーム：4人

- bashで作られた社内システムをPython、Django REST framework、Vue.jsに置き換えを実施
- 主にバックエンド側（Python Django REST framework)を担当。進捗によってはペアプロでフロントエンド側も実装。

- このときのプロジェクトの課題やどのように乗り換えっていったのかは、下記スライドで登壇
  - [対話から始めていく私たち開発チームのジャーニー](https://speakerdeck.com/jnuank/dui-hua-karashi-meteikusi-tatikai-fa-timufalsesiyani)

#### 2020/01 - 2020/03： 介護施設向け入居者請求システム開発
役割: Webアプリケーションエンジニア（メンバー）
チーム:3人

- 別拠点で導入されていたbashとHTMLで作られたシステムから、必要機能を抜粋したものを抜き出して開発し、システムの導入を1ヶ月で実施。
- その後のフェーズで、外部システムとの連携があるということで、PythonとAWS Lambdaで連携用バッチを作成。
  - 外部システムから渡されるCSVファイルのフォーマットの情報があやふやだったこともあり、データを受け取るところとデータを自システム用に変換する仕組みはロジックを分離
- そのときの知見をサンプルコードと合わせ記事を書いて社内共有をする
  - [CSV→スペース区切りに変換する処理でも、真面目に入出力とルールを分離をしてみる](https://qiita.com/jnuank/items/bbd46f5868d2ca723aa6)


#### 2018/07 - 2020/03： 小売基幹システムの保守運用
役割: Webアプリケーションエンジニア（メンバー　→　リーダー）
チーム：2〜3人

- 客先のオンプレサーバ(CentOS）、AWS上のサーバの保守・運用
- AWSの使用コスト削減の提案や改修案件の提案実施
- システムへの機能追加を要件定義から開発・保守運用まで実施
  - 賞味期限管理システム
  - 商談系システムの軽減税率対応

- チームリーダーとして、メンバーのオンボーディング、1on1の実施
  - 今までのキャリアで初のリーダー経験だったので、そのときの手探り感や得た知見を社内で共有
    - [「君、今日からリーダーね」と 言われた私が取り組み始めたこと](https://speakerdeck.com/jnuank/jun-jin-ri-kararidane-to-yan-waretasi-gaqu-rizu-mishi-metakoto)

#### 2019/05 - 2019/09： 商談系システムの軽減税率対応
役割: Webアプリケーションエンジニア（リーダー）
チーム：3人

#### 2018/07 - 2019/04： 賞味期限管理システム開発
役割: Webアプリケーションエンジニア（メンバー）
チーム：2人

### 2016/10 - 2018/06 : 株式会社Vヴィズリア

#### 2017/07 - 2019/04： 賞味期限管理システム開発



- 職務内容の詳細を箇条書きでかく


## 課外活動

### 運営に携わっているコミュニティ
* [DDD-Community-Jp](https://ddd-community-jp.connpass.com/)

### 直近の企画・運営歴
| Date | Event | 
|---|-----|
|2020/10/10|[エリック・エヴァンスのドメイン駆動設計 輪読会「第4章 ドメインを隔離する」](https://ddd-community-jp.connpass.com/event/190629/)|
|2020/09/26|[エリック・エヴァンスのドメイン駆動設計 輪読会「第3章 モデルと実装を結びつける」](https://ddd-community-jp.connpass.com/event/188787/)|
|2020/09/05|[エリック・エヴァンスのドメイン駆動設計 輪読会「第2章 コミュニケーションと言語の使い方」](https://ddd-community-jp.connpass.com/event/186935/)|
|2020/08/22|[エリック・エヴァンスのドメイン駆動設計 輪読会「第1章 知識をかみ砕く」](https://ddd-community-jp.connpass.com/event/185933/)|
|2020/08/08|[エリック・エヴァンスのドメイン駆動設計 輪読会 1回「序文、目次、索引」](https://ddd-community-jp.connpass.com/event/185352/)|
|2020/08/01|[TDD Boot Camp 2020 Online \#1 ](https://tddbc.connpass.com/event/181973/)|

### 過去の登壇資料

| Date | Event | Slide |
|---|-----|-----|
|2019/12/14|[カイゼンの旅、チームの旅。現場の軌跡を語ろうライトニングトーク回 \- DevLOVE](https://devlove.doorkeeper.jp/events/109556?utm_campaign=event_109556_130263&utm_medium=email&utm_source=not_replied_message)| [対話から始めていく私たち開発チームのジャーニー](https://speakerdeck.com/jnuank/dui-hua-karashi-meteikusi-tatikai-fa-timufalsesiyani) |
|2019/12/14|[レガシーをぶっつぶせ。現場でDDD！2nd 「インプット＜アウトプット！」第一部 ](https://genbade-ddd.connpass.com/event/156060/)|[モデリングで既存システムの可視化に臨んだ話](https://speakerdeck.com/jnuank/moderingudeji-cun-sisutemufalseke-shi-hua-nilin-ndahua) |

