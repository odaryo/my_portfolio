+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Works Experience"
subtitle = "職歴・業務経験など"

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "オンライン指導塾のポータルサイト開発"
  company = ""
  date_start = "2022-01-01"
  date_end = ""
  description = """

エージェントを介してバックエンドメンバーとしてジョインしました。  
（2022年6月よりバックエンドチームのリーダー兼エンジニア）

オンライン指導塾のポータルサイトの開発を担当。 
講師と生徒の紐づけ、授業進捗の管理、宿題の管理などの機能を実装しています。  
2023年11月に大筋の開発が終わり、機能改修と新規機能開発を行っています。  
バックチームのリーダーとして、開発フローの見直しや、メンバーの能力向上のための勉強会開催なども行っています。  
8割方リモートワークのチームのため、SlackとZoomメインでのコミュニケーションがメインです。


主な業務内容

- DDD（ドメイン駆動設計）に沿ってドメインオーナーにヒアリングしながらモデリング、リポジトリパターンでの実装。たまに業務フローの提案
- PHP 8.0 から 8.2 （Laravel 8.x から 10.x）へのアップグレード
- 遅いAPIの高速化（悪い設計＆データの肥大化で8秒近くかかっていたAPIを1/10程度に高速化）
- コスト削減を目的としたインフラ環境の整理（ECS、RDSのスペックダウンに伴うAPIの負荷軽減を対応→インフラコスト4割減）
- 先生方の利便性向上や時間削減を目的にヒアリングし、情報の一元化などで入力の手間を削減し時間確保を実現 (一月あたりの生徒面談件数80件→100件)
- 軽量DDDの実装範囲をDDD実装パターンに改修
- PullRequestでのレビュー
- 社内勉強会の開催 (テーマ：オブジェクト指向、モデリング、Unitテスト、TDD)


<BR>

チームメンバー：9名 （うちバックエンド5名）: 2024/01現在

【Skills】  
- PHP8.0 -> 8.2 (Laravel 8.x -> 10.x) / PhpStan / Pint / PhpUnit
- Next.js 
- GitHub Actions 
- Docker
- AWS（ECS, RDS, EC2, teraform）
  """

[[experience]]
  title = "フードデリバリーアプリのサーバーサイド開発"
  company = ""
  date_start = "2021-04-12"
  date_end = "2021-12-31"
  description = """

サービス拡大に伴うバックエンド開発要因としてエージェントを介して参画。  
主にエンジニア業務を担当。

チームメンバー：10名（うちバックエンド3名）

【Skills】  
PHP7.4 / Slim Framework / PHPUnit / GCP / MySQL
  """

[[experience]]
  title = "マッサージサロン向けのWEBリプレース"
  company = ""
  date_start = "2020-06-01"
  date_end = "2020-10-01"
  description = """

個人請負で既存のHP & Blogをリプレース。

利用技術  
- HP：Nuxt.js(typescript) + Netlify  
- Blog：Nuxt.js(typescript) + WordPress（WP-REST−API） + Netlify  

リプレース前のWordPress資産を活かしつつ、JAMstackを使ったセキュリティ強化と速度改善に務める。  

BlogのCMSは使いやすさ重視でWordPressを利用。  
（Markdown未使用、絵文字利用といった用途に対応）  
WP-REST-API経由でデータ取得し、Netlifyで自動ビルドさせる。  

Nuxt.jsはアトミックパターンを採用し、コンポーネント分割と再利用性を高める。

【Skills】  
PHP7.4 / Nuxt.js 2.12 / Jest / WordPress 5.3 / SCSS / GitHUB
  """

[[experience]]
  title = "WordPressサイトへのREST API組み込み"
  company = ""
  date_start = "2020-07-01"
  date_end = "2020-10-01"
  description = """

WordPressで作成されたHPに、記事投稿やデータ登録のAPIを追加。  
WordPressのPHPファイルに独自 REST APIを実装。

メンバー：2名（フロントエンジニア、自分）

開発サービス
- 家具販売店のHPへ、基幹システムから商品データをインポートするAPI
- 美容院HPのブログへ、予約管理システムからのブログデータを投稿するAPI

(各工数は2～5人日程度)

【Skills】  
PHP7.3 / WordPress 5.3

  """

[[experience]]
  title = "食品卸業者向け発注システムの開発"
  company = ""
  date_start = "2018-10-01"
  date_end = "2021-04-01"
  description = """

準委任契約でプロジェクトに参加。  
業務効率化のための、卸先店舗向け商品発注システムと基幹システムへの連携バッチ機能を開発。

チームリーダーとして、顧客との打ち合わせから要件定義、基本/詳細設計、実装、テストなど一通りの開発業務。  
工程管理、開発環境の整備、新人教育などを担当。

(2019/11 納品、現在保守継続中)  
(2021/03 VPSからAWSへの移行作業を行う)

【Skills】  
PHP / Cakephp3.8 / PhpUnit / javascript / jQuery / SCSS / Apache / MySQL / Docker / AWS

  """

[[experience]]
  title = "マッサージサロンの施術支援ツール"
  company = ""
  date_start = "2018-03-01"
  date_end = ""
  description = """

受託でエステサロン向けの施術支援ツールを開発
（顧客管理、カルテ管理、教育支援、販売管理など）  

1人で打ち合わせから開発、保守まで担当（2020/06 保守継続中）

【Skills】  
PHP / Laravel5 / jQuery / SCSS / Nginx / MariaDB / Docker / Ubuntu / VPS
  """

[[experience]]
  title = "建築系の業務システムのリプレース"
  company = ""
  date_start = "2017-05-01"
  date_end = "2017-12-31"
  description = """
準委任契約でプロジェクトに参加  
COBOLベースのシステムのリプレース対応を行う

10人規模のプロジェクトで基本設計〜単体テストまでを担当

【Skills】  
VB.net / SQLServer 
  """

[[experience]]
  title = "フリーランスとして独立"
  company = ""
  date_start = "2016-04-01"
  date_end = ""
  description = """

  業務内容
  
- 受託案件や準委任でのシステム開発
- HP作成、SEOコンサルタント
- パソコン導入サポート
- サーバメンテナンス

など

屋号：UPネット
  """

[[experience]]
  title = "SIer入社"
  company = ""
  date_start = "2010-04-01"
  date_end = "2016-03-31"
  description = """
  主に社内受託プロジェクトを担当
  
- 交通系会社の勤怠管理システム開発
- 自動車リース会社のHP＆受注システム開発
- 色彩学習用Androidアプリ開発

など

2015年4月に取締役就任。  
経営参画や人材管理等を行う

【Skills】  
PHP / WordPress / Java / javascript / jQuery / SCSS / C# / VB.net / C++
  """

+++
