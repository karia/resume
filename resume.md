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

私は2009年から約15年間にわたり、インフラエンジニアとして通信業界・小売業界・エンタメ業界での経験を積んできました。直近8年間は大規模クラウドインフラ・ミドルウェアの設計・構築・運用に従事し、サービスの信頼性向上と効率化に寄与してきました。

### インフラエンジニア（SRE・クラウドエンジニア）としての経験

- クラウドインフラ（AWS, Google Cloud）およびCI/CDの設計・構築・運用・コスト最適化
- コンテナ・ミドルウェアの構築・運用
- IaC化・トイル削減などSREプラクティスの推進
- 監視設計・セキュリティ対応・インシデント対応
- データベース・検索基盤運用（MySQL, Aurora, Elasticsearch, BigQuery等）およびパフォーマンスチューニング

### 組織・チームマネジメントの経験

- 開発チーム内のプロセスやドキュメント整備・MTGのファシリテーションを通じて、チーム全体の成長と効率化に寄与
- エンジニアリングマネージャー/インフラチームリーダーとして最大10人のチームをリード、経営層やグループ会社との連携経験あり

## 職務経歴

### 株式会社つみき

- **期間**: 2017年8月 - 現在
- **職種**: インフラエンジニア (SRE, クラウドエンジニア)

#### 業務内容

映画・ドラマレビューサービス「Filmarks」（月間700万UU, 1.36億PV ※2022年8月現在。参考：[PR TIMES](https://prtimes.jp/main/html/rd/p/000000280.000008641.html)）のインフラエンジニアとして、AWSおよびGoogle Cloudのインフラ基盤構築・運用およびサービスの信頼性向上に従事。

#### 主な実績と取り組み

##### インフラ最適化

- RDSからAurora MySQLへの移行 / Aurora MySQL メジャーバージョンアップに伴う移行計画策定と実行
- 画像配信を外部SaaS（ImageFlux）に移行し、レスポンス高速化・WebP対応・マルチデバイス最適化を実現
- キャパシティプランニング, EC2 Auto Scalingによる負荷調整自動化
- 年間AWS予算策定、および Reserved Instances, Saving Plans, Spot Instance を利用したコスト最適化
- RedshiftからBigQueryへのデータウェアハウス移行設計

##### 自動化・コード化

- Lambda関数による社外からのファイル授受システム構築
- 運用効率化・トイルの排除（リリースプロセス自動化、EC2定期更新プロセス改善など）
- Terraformによる大規模インフラのIaC化推進
- CI/CDパイプライン設計・実装、CircleCIのスペック最適化やジョブ分割によるエラー率改善

##### セキュリティ・モニタリング改善

- AWSサービス (WAF等)・ミドルウェアを活用したDDoS攻撃・不正アクセス対策
- Mackerel、CloudWatch、NewRelicを活用した監視設計
- Twilioを活用した低コストな監視アラート通知システム構築
- インシデント対応手順整備、ポストモーテム文化定着

##### 開発チーム支援

- AI開発エージェント (Devin, Claude Code) のPoC実施、チームへの導入支援
- スプリントレトロスペクティブのファシリテーション改善、オンボーディングプロセス整備
- インフラチーム増員に伴う業務委託メンバーのスキル基準を策定し4名を受け入れ、レビューガイドライン策定などチーム内プロセスを整備

#### 技術スタック

- クラウドサービス: AWS (EC2, ECS, Aurora MySQL, CloudFront, etc), GitHub Actions
- ミドルウェア・ツール: nginx, Elasticsearch, Redis, Docker, Terraform
- 言語: Ruby, Python, Shell Script, JavaScript

### 株式会社アニメイトラボ

- **期間**: 2015年10月 - 2017年7月
- **職種**: インフラエンジニア, エンジニアリングマネージャー

#### 業務内容

アニメイトグループが新規に設立したIT子会社において、インフラ関係を中心にWebサービスの内製化や開発プロセスのモダナイゼーションに携わった。2016年8月からはエンジニアリングマネージャー（開発部長）として、CTO指揮下にて10人程度のエンジニアチームのマネジメントも担当。

#### 主な実績と取り組み

- 外部開発会社からの内製化に伴うソースコードのGitHub移管、開発のGitHub flow化、コードレビュー実施
- 自社運営のWebサービス「アニメイトタイムズ」のサイト名・ドメイン名変更を2ヶ月で実現
- 新規サービス向けにAWSを活用したインフラ基盤の設計・構築、既存プライベートクラウドの運用整理やAWS移行による信頼性向上
- エンジニア各メンバーとの定期的な1on1ミーティング実施
- エンジニア組織の課題整理や評価実施、ビジネス職やグループ会社との橋渡し、経営MTG参加など会社運営全般に従事

**使用技術**: IDCF Private Cloud, AWS, MySQL, nginx, Apache, PHP, Ruby, Git 等

### ソフトバンクモバイル株式会社

- **期間**: 2009年4月 - 2015年9月
- **職種**: インフラエンジニア, 社内SE

#### 業務内容

イーモバイルブランドの携帯電話サービスにおける情報システム部門において、基幹システムを含む複数システムのインフラ構築・運用を担当。会社買収や組織再編に伴うシステム統合やインフラ運用の統合にも携わった。

#### 主な実績と取り組み

- 400万契約規模の顧客管理・料金計算システムを含む複数のOracle databaseをOracle Exadataへ集約・リプレース
- OSSベース(Linux, PostgreSQL, etc)でのシステムリプレースによる保守費用90%削減
- 大規模メンテナンスの手順書作成, リハーサル, 本番実施
- 社内外からシステム部門に対する問い合わせ対応, アラート対応, アカウント管理

**使用技術**: Linux, Solaris, Oracle, MySQL, PostgreSQL, Xen, KVM, DRBD, Apache 等

## 技術スタック

この項目はClaude Codeにより自動生成しております。

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
- 普通自動車運転免許 (2003年9月取得)

---

最終更新日: 2025年9月25日
