# 職務経歴書

## 基本情報

- **氏名**: 久松佳之
- **メールアドレス**: karia [at] side2.net / karia2nd [at] gmail.com
- **居住地**: 東京都
- **最終学歴**: 東京農工大学大学院 工学府 情報工学専攻 博士前期課程 修了

### SNSアカウント

| プラットフォーム | URL |
|---|---|
| GitHub | [https://github.com/karia](https://github.com/karia) |
| Zenn | [https://zenn.dev/karia](https://zenn.dev/karia) |
| Blog | [https://karia.hatenablog.jp/](https://karia.hatenablog.jp/) |
| X (Twitter) | [https://twitter.com/karia2nd](https://twitter.com/karia2nd) |

## 概要

私は約15年間にわたり、インフラエンジニアとして通信業界・小売業界・エンタメ業界での経験を積んできました。特に、直近8年間はAWSおよびGoogle Cloudを活用した大規模クラウドインフラ・ミドルウェアの設計・構築・運用に従事し、サービスの信頼性向上と効率化に寄与しました。

- **インフラエンジニア（SRE・クラウドエンジニア）としての経験**
  - AWSインフラ（特にEC2, ECS, Fargate, Aurora MySQL, Lambda など）の設計・構築・運用・コスト最適化
  - Docker, nginx, MySQL, Elasticsearchなどのミドルウェアの構築・運用
  - Terraform, Ansibleを用いたIaC化
  - GitHub Actions, CircleCIを用いたCI/CDパイプラインの構築・改善・運用自動化
  - 監視設計・セキュリティ対応・アラート一次対応からポストモーテム実施までの一連のインシデント対応
- **組織・チームマネジメントの経験**
  - レトロスペクティブのファシリテーション、新メンバーのオンボーディング整備など、チーム全体の成長と効率化に寄与
  - エンジニアリングマネージャーとして10人程度のチームをリードした経験（1年弱）

## 職務経歴

### 株式会社つみき

- **期間**: 2017年8月 - 現在
- **職種**: インフラエンジニア (SRE)

#### 業務内容

映画・ドラマレビューサービス「Filmarks」（月間700万UU, 1.36億PV）のインフラエンジニアとして、AWSおよびGoogle Cloudのインフラ基盤構築・運用およびサービスの信頼性向上に従事。

※数値は2022年8月現在。参考：[PR TIMES](https://prtimes.jp/main/html/rd/p/000000280.000008641.html)

#### 主な実績と取り組み

##### インフラモダナイゼーション・基盤構築

- RDSからAurora MySQLへの移行 / Aurora MySQL メジャーバージョンアップに伴う移行計画策定と実行
- 画像配信を外部SaaS（ImageFlux）に移行し、EC2負荷軽減・WebP対応・マルチデバイス対応を同時に実現
- キャパシティプランニング, EC2 Auto Scalingによる負荷調整自動化
- 年間AWS予算策定、および Reserved Instances, Saving Plans, Spot Instance を利用したコスト最適化
- Lambda関数による社外からのファイル授受システム構築
- RedshiftからBigQueryへのデータウェアハウス移行設計
- 運用効率化・トイルの排除（リリースプロセス自動化、EC2定期更新プロセス改善など）
- Terraformによる大規模インフラのIaC化推進
- CI/CDパイプライン設計・実装・改善

##### セキュリティ・モニタリング改善

- AWSサービス (WAF等)・ミドルウェアを活用したDDoS攻撃・不正アクセス対策
- Mackerel、CloudWatch、NewRelicを活用した監視設計
- Twilioを活用した低コストな監視アラート通知システム構築
- インシデント対応手順整備、ポストモーテム文化定着

##### 開発チーム支援

- AI開発エージェント (Devin, Claude Code) のPoC実施、チームへの導入支援
- スプリントレトロスペクティブのファシリテーション改善、オンボーディングプロセス整備

#### 技術スタック

- クラウドサービス: AWS (EC2, ECS, Aurora MySQL, CloudFront, etc), GitHub Actions
- ミドルウェア・ツール: nginx, Elasticsearch, Redis, Docker, Terraform
- 言語: Ruby, Python, Shell Script, JavaScript

### 株式会社アニメイトラボ

- **期間**: 2015年10月 - 2017年7月
- **職種**: インフラエンジニア, エンジニアリングマネージャー

#### 業務内容

アニメイトグループが新規に設立したIT子会社において、インフラ関係を中心にWebサービスの内製化や開発プロセスの近代化に携わった。2016年8月からはエンジニアリングマネージャー（開発部長）として、CTO指揮下にて10人程度のエンジニアチームのマネジメントも担当。

#### 主な実績と取り組み

- 外部開発会社からの内製化に伴うPHPコードのレビューや開発のGitHub flow化
- 自社運営のWebサービス「アニメイトタイムズ」のサイト名・ドメイン名変更を2ヶ月で実現
- AWSを活用したインフラ基盤の設計・構築・運用

**使用技術**: IDCF Private Cloud, AWS, MySQL, nginx, Apache, PHP, Ruby, Git 等

### ソフトバンクモバイル株式会社

- **期間**: 2009年4月 - 2015年9月
- **職種**: インフラエンジニア, 社内SE

#### 業務内容

イーモバイルブランドの携帯電話サービスにおける情報システム部門において、基幹システムを含む複数システムのインフラ構築・運用を担当。会社買収や組織再編に伴うシステム統合やインフラ運用の統合にも携わった。

#### 主な実績と取り組み

- 基幹システムを含む複数システムのOracle databaseをOracle Exadataへ移行・集約
- OSSベース(Linux, PostgreSQL, etc)でのシステムリプレースによる保守費用削減
- 大規模メンテナンスの手順書作成, リハーサル, 本番実施
- 社内外からシステム部門に対する問い合わせ対応, アラート対応, アカウント管理

**使用技術**: Linux, Solaris, Oracle, MySQL, PostgreSQL, Xen, KVM, DRBD, Apache 等

## 技術スタック

### インフラ・クラウド

- **AWS**: EC2, ECS (Fargate), RDS (Aurora MySQL), S3, CloudFront, WAF, Lambda, CloudWatch
- **Google Cloud Platform**: BigQuery, Cloud Storage
- **IaC**: Terraform, Ansible
- **Monitoring**: Mackerel, NewRelic, CloudWatch, td-agent (Fluentd)

### 開発・CI/CD

- **CI/CD**: GitHub Actions, CircleCI
- **Container**: Docker, AWS ECS, ECR
- **Languages**: Python, Shell Script, Ruby, JavaScript
- **Quality**: pre-commit, tflint, yamllint, shellcheck, ruff
- **Package Management**: mise, bundler, npm

### データ・アプリケーション

- **Database**: MySQL 5.7/8.0, Aurora MySQL, Redis, Elasticsearch
- **Data Warehouse**: Amazon Redshift, Google BigQuery
- **Web**: Nginx, Unicorn, Sidekiq

## 対外発表・ブログ・業務外活動

- [スパイクアクセスに立ち向かうFilmarksの高トラフィック対策 - SRE Magazine 009号](https://sre-magazine.net/articles/9/karia/)
  (2025/08/01)
- [映画レビューアプリ「Filmarks」へのImageFlux導入によるメリットと課題 - Imageflux Meetup #3](https://speakerdeck.com/karia/filmarkshefalseimagefluxdao-ru-niyorumeritutotoke-ti)
  (2019/03/15)
- [ISUCON7 予選参加 チーム成績43位](https://karia.hatenablog.jp/entry/2017/10/23/030749) (2017/10/22)

## 資格

- ORACLE MASTER Bronze Oracle Database 11g (2013年3月合格)
- ネットワークスペシャリスト試験 (2009年11月合格)

---

最終更新日: 2025年9月24日
