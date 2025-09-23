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

## 強み・アピールポイント

- **フルスタックなインフラ知識**: ネットワーク層からアプリケーション層まで幅広い実装経験
- **長期的な技術選定能力**: 7年間のサービス成長を支える技術選定と移行戦略の実績
- **IaCの実践経験**: Terraformを活用した大規模インフラのコード化
- **セキュリティ対応力**: DDoS攻撃やセキュリティインシデントへの迅速な対応経験
- **問題解決能力**: 障害発生時の原因分析と根本解決への取り組み
- **チーム貢献**: レトロスペクティブファシリテーション、技術勉強会開催、オンボーディング支援

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

## 職務経歴

### 株式会社つみき

**インフラエンジニア / SRE**
*2017年8月 - 現在 (約7年間)*

#### 業務内容

映画・ドラマレビューサービス「Filmarks」（月間700万UU, 1.36億PV規模）のインフラ基盤構築・運用およびサービスの信頼性向上に従事。サービスの成長に合わせてインフラアーキテクチャの設計・実装・最適化を主導。
AWSとGoogle Cloudを活用した大規模サービスのインフラ設計・構築から、DevOpsプロセスの改善、セキュリティ対策まで幅広く担当。

※数値は2022年8月現在。参考：[PR TIMES](https://prtimes.jp/main/html/rd/p/000000280.000008641.html)

#### 主な実績と取り組み

##### インフラモダナイゼーション・基盤構築 (2017年 - 現在)

- RDSからAuroraへの移行計画策定と実行、Auto Scalingによる負荷対応自動化
- Terraformによる大規模インフラのIaC化推進
- データパイプライン基盤構築（ログ収集、S3/Redshift連携、外部API連携）
- GitHub ActionsによるCI/CDパイプライン設計・実装

**使用技術**: Terraform, AWS, GCP, GitHub Actions, Fluentd, Docker

##### セキュリティ・運用自動化 (2024年 - 現在)

- DDoS攻撃対応とAWS WAFルール設計による不正アクセス対策
- 包括的監視システム構築（Mackerel、CloudWatch、NewRelic連携）
- リリースプロセス自動化、EC2定期更新プロセス改善
- インシデント対応手順整備、ポストモーテム文化定着

**使用技術**: AWS WAF, Mackerel, CloudWatch, Ansible, git-pr-release

##### 開発効率化・チーム支援 (2024年 - 現在)

- ECS Fargate/Spotを活用したコンテナ基盤最適化、検証環境コスト70%削減
- MySQL 8.0バージョンアップ計画
- AI開発ツール導入支援、pre-commit品質チェック体制構築
- 技術勉強会開催、新メンバーオンボーディング支援

**使用技術**: ECS, Aurora MySQL, BigQuery, Claude Code, pre-commit, mise

### 株式会社アニメイトラボ

**職種**: インフラエンジニア, エンジニアリングマネージャー (2016年8月 - 2017年7月)
**期間**: 2015年10月 - 2017年7月

#### アニメイトラボでの業務内容

アニメイトグループが新規に設立したIT子会社において、インフラ関係を中心にWebサービスの内製化や開発プロセスの近代化に携わった。途中から開発部長の肩書きがつき、CTO指揮下にて10人程度のエンジニアチームのマネジメントも担当。

#### アニメイトラボでの主な実績と取り組み

- 外部開発会社からの内製化に伴うPHPコードのレビューや開発のGitHub flow化
- 自社運営のWebサービス「アニメイトタイムズ」のサイト名・ドメイン名変更を2ヶ月で実現
- AWSを活用したインフラ基盤の設計・構築・運用

**使用技術**: IDCF Private Cloud, AWS, Linux, MySQL, nginx, Apache, PHP,
Ruby, Git, Mercurial 等

### ソフトバンクモバイル株式会社

**職種**: インフラエンジニア, 社内SE
**期間**: 2009年04月 - 2015年9月

#### ソフトバンクモバイルでの業務内容

イーモバイルブランドの携帯電話サービスにおける情報システム部門において、基幹システムを含む複数システムのインフラ構築・運用を担当。会社買収や組織再編に伴うシステム統合やインフラ運用の統合にも携わった。

#### ソフトバンクモバイルでの主な実績と取り組み

- 基幹システムを含む複数システムのOracle databaseをOracle Exadataへ移行・集約
- OSSベース(Linux, PostgreSQL, etc)でのシステムリプレースによる保守費用削減
- 大規模メンテナンスの手順書作成, リハーサル, 本番実施
- 社内外からシステム部門に対する問い合わせ対応, アラート対応, アカウント管理

**使用技術**: OS (Linux, Windows Server, Solaris, HP-UX),
DB (Oracle, MySQL, PostgreSQL), Xen, KVM, DRBD, Apache,
Java (Tomcat, WebLogic), Xymon 等

## 対外発表・ブログ・業務外活動

- [スパイクアクセスに立ち向かうFilmarksの高トラフィック対策 - SRE Magazine 009号](https://sre-magazine.net/articles/9/karia/)
  (2025/08/01)
- [映画レビューアプリ「Filmarks」へのImageFlux導入によるメリットと課題 - Imageflux Meetup #3](https://speakerdeck.com/karia/filmarkshefalseimagefluxdao-ru-niyorumeritutotoke-ti)
  (2019/03/15)
- [ISUCON7 予選参加 チーム成績43位](https://karia.hatenablog.jp/entry/2017/10/23/030749) (2017/10/22)

## 資格

- ORACLE MASTER Bronze Oracle Database 11g (2013年03月合格)
- ネットワークスペシャリスト試験 (2009年11月合格)

---

最終更新日: 2025年9月24日
