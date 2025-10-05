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

## 経歴概要

私は2009年から約15年間にわたり、エンジニアとして通信業界・小売業界・エンタメ業界での経験を積んできました。

1社目ではミッションクリティカルな通信業界でオンプレミス環境のインフラ運用・構築に従事、その後内製化を目指すIT子会社に転職。プライベートクラウドとパブリッククラウドのハイブリッドな環境において新規・既存双方のプロジェクトに関わり、更にエンジニアリングマネジャーに昇格しチームマネジメントも経験しました。

3社目となる現職には2017年8月にジョインし、toCサービスのバックエンドを支えるクラウドインフラ・ミドルウェアの設計・構築・運用に従事し、サービスの信頼性向上と効率化に寄与してきました。

### インフラエンジニア（SRE・クラウドエンジニア）としての経験

- クラウドインフラ（AWS, Google Cloud）による本番環境・検証環境の設計・構築・運用・コスト最適化
- コンテナ・ミドルウェア・CI/CDの設計・構築・運用・EoL対応・性能試験・リグレッションテスト
- IaC化・トイル削減などSREプラクティスの推進
- 監視設計・セキュリティ対応・インシデント対応
- データベース・DWH・検索基盤（Elasticsearch等）の運用・パフォーマンスチューニング・リプレース

### 組織・チームマネジメントの経験

- 開発チーム全体向けのプロセス整備・ドキュメント整備・MTGのファシリテーションを通じて、チーム全体の成長と効率化に寄与
- エンジニアリングマネージャー/インフラチームリーダーとして最大10人のチームをリード、経営層やグループ会社との協働経験あり

## 職務経歴

### 株式会社つみき

- **期間**: 2017年8月 - 現在 (8年2ヶ月)
- **職種**: インフラエンジニア (SRE, クラウドエンジニア)
- **チーム規模**: インフラチーム：4名 (正社員1名 + 業務委託3名), 開発チーム全体：20名程度

#### 業務内容

映画・ドラマ・アニメのレビューアプリ「Filmarks」のインフラエンジニアとして、月間700万UU, 1.36億PV （2022年8月現在。参考：[PR TIMES](https://prtimes.jp/main/html/rd/p/000000280.000008641.html)）規模のAWSインフラ基盤構築・運用およびサービスの信頼性向上に従事しました。

インフラ専任担当は1人という環境下で、サービスの安定性・信頼性向上（アラートの削減）のためにインフラ構成の最適化に取り組みました。また低コストなインフラ運用の徹底や、CI/CDパイプラインの改善、セキュリティ対策にも注力しました。開発チーム全体に関わるプロセス改善にも積極的に取り組み、インフラチーム増員後はチームをリードする立場も担いました。

#### 主なプロジェクト・実績

##### インフラ最適化

- 画像配信を外部SaaS（ImageFlux）に移行しアラート頻発を解消。更にレスポンス高速化・WebP対応・マルチデバイス最適化を実現
- EC2 Auto Scalingによる負荷調整自動化、定期的に「パフォーマンス確認会」を開催しボトルネック改善
- push通知送信や地上波テレビ番組放送によるトラフィック急増の事前対応・事後検証
- 運用性向上のためRDSからAurora MySQLへの移行 / Aurora MySQL メジャーバージョンアップに伴う移行計画策定と実行
- 年間AWS予算策定、および Saving Plans, Spot Instance, Fargate Spot を利用したコスト最適化
- RedshiftからBigQueryへのデータウェアハウス移行設計
- Elasticsearchクラスタの運用、スコア調整、安定性向上

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
- 開発チーム全体（Max 20名程度）で開催するスプリントレトロスペクティブのファシリテーション改善、オンボーディングプロセス整備
- インフラチーム増員に伴う業務委託メンバーのスキル基準を策定、レビューガイドライン策定などチーム内プロセスを整備

#### 技術スタック

- **クラウドサービス**: AWS (EC2, ECS, Fargate, Aurora MySQL, CloudFront, ElastiCache, SES, etc), GitHub Actions, CircleCI, etc
- **ミドルウェア・ツール**: nginx, Unicorn, Sidekiq, Elasticsearch, Redis, memcached, Docker, Terraform, Ansible, ecspresso, etc
- **言語**: Ruby, Python, Shell Script, Node.js
- **情報共有**: GitHub, esa, Notion, Slack, Google Docs, etc

### 株式会社アニメイトラボ

- **期間**: 2015年10月 - 2017年7月 (1年10ヶ月)
- **職種**: インフラエンジニア, エンジニアリングマネージャー
- **チーム規模**: 開発チーム全体：10名程度

#### 業務内容

アニメイトグループが新規に設立したIT子会社において、インフラ関係のみならずWebサービスの内製化や開発プロセスのモダナイゼーションにも関わりました。2016年8月からはエンジニアリングマネージャー（肩書きは開発部長）として、CTO指揮下にて10人程度のエンジニアチームのマネジメントも担当しました。

#### 主なプロジェクト・実績

- 外部開発会社からの内製化に伴うソースコードのGitHub移管、開発のGitHub flow化、コードレビュー実施
- 自社運営のWebサービス「アニメイトタイムズ」のサイト名・ドメイン名変更を2ヶ月で実現
- 新規サービスやキャンペーンのLP向けにAWSインフラ基盤の設計・構築
- 親会社が運用する既存プライベートクラウドの課題整理・改善や、パブリッククラウド移行などによる信頼性向上を協力会社と協働で実施
- オフィス移転時の移転先オフィス選定およびネットワーク設計・ハードウェア選定・工事立ち会い
- エンジニア各メンバーとの定期的な1on1ミーティング実施
- エンジニア組織の課題整理や評価実施、ビジネス職やグループ会社との橋渡し、経営MTG参加など会社運営全般に従事

**使用技術**: IDCF Private Cloud, AWS, MySQL, nginx, Apache, PHP, Ruby, Git 等

### ソフトバンクモバイル株式会社

- **期間**: 2009年4月 - 2015年9月 (6年6ヶ月)
- **職種**: 社内SE, インフラエンジニア

#### 業務内容

イーモバイルブランドの携帯電話サービスにおける情報システム部門にて、400万契約規模の顧客管理システムや料金計算システムを含む、複数システムのリプレースを社内SEおよびインフラ担当の立場から経験しました。途中、システム運用部門での24h365d体制のヘルプデスク業務にも従事しました。

#### 主なプロジェクト・実績

- OSSベース(Linux, PostgreSQL, etc)でのシステムリプレースによる保守費用90%削減
- 複数のOracle databaseをOracle Exadataへ集約・リプレース
- 大規模メンテナンスの手順書作成, リハーサル, 本番対応を複数回実施
- 社内外からシステム部門に対する問い合わせ対応, アラート対応, アカウント管理

**使用技術**: Linux, Solaris, Oracle, MySQL, PostgreSQL, Xen, KVM, DRBD, Apache 等

## 技術スタック

### クラウド・SaaS

- **AWS**
  - **Compute**: EC2, ECS (Fargate), Lambda
  - **Database & Storage**: RDS (Aurora), DynamoDB, Redshift, ElastiCache, S3, OpenSearch Service, Athena
  - **Networking & Others**: CloudFront, Route53, API Gateway, WAF, CloudWatch, DMS, SES, SNS, EventBridge
- **Google Cloud**: BigQuery, Cloud Storage, Cloud Run Functions
- **CI/CD**: GitHub Actions, CircleCI, AWS CodeDeploy
- **モニタリング**: Mackerel, NewRelic, Bugsnag
- **その他SaaS**: ImageFlux, Twilio, Docker Hub

### 言語・ミドルウェア

- **言語**: Python, Shell Script, Ruby, PHP
- **フレームワーク**: Ruby on Rails
- **IaC**: Terraform, Ansible
- **データベース**: MySQL, PostgreSQL, Oracle, Redis, memcached, Elasticsearch
- **ミドルウェア・ツール**: Docker, Nginx, td-agent (Fluentd), ecspresso, lambroll, Locust

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

2025年10月現在
