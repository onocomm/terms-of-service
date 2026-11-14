# オノコムサービス契約約款

株式会社オノコムが提供するサービスの契約約款を公開するリポジトリです。

## 📋 概要

このリポジトリは、株式会社オノコムが提供する各種サービスの利用契約約款を公開し、透明性のある契約関係を維持することを目的としています。

- **最新版の約款を常時公開**
- **変更履歴の完全な記録**
- **過去バージョンとの比較が可能**
- **複数サービスの約款を一元管理**

## 📁 リポジトリ構成

```
terms-of-service/
├── README.md                          # 本ファイル(リポジトリの説明)
├── contract_jp.md                     # 基本約款(全サービス共通)
├── contract-jp-history.md             # 基本約款の詳細な変更履歴
├── CHANGELOG.md                       # 全サービスの変更履歴統合ビュー
├── archive/                           # 基本約款の過去バージョン
│   ├── v1_2010-08-01.md              # 第1版
│   ├── v2_2016-10-01.md              # 第2版
│   ├── v3_2018-07-01.md              # 第3版
│   ├── v4_2021-02-01.md              # 第4版
│   ├── v5_2025-11-01.md              # 第5版
│   ├── v6_2026-11-12.md              # 第6版
│   ├── v7_2026-11-13.md              # 第7版
│   └── v8_2026-11-14.md              # 第8版
│
└── services/                          # 個別サービス約款
    ├── aws-cloud/                    # AWS決済代行・新規発行オンライン契約
    │   ├── aws-cloud-contract.md     # 専用条件
    │   ├── aws-cloud-history.md      # 変更履歴
    │   └── aws-cloud-source-map.md   # 根拠対応表（約款本文ではない）
    ├── onocomm-relay/                 # メール配送の新規オンライン契約
    │   ├── onocomm-relay-contract.md  # 契約条件
    │   └── onocomm-relay-history.md   # 変更履歴
    ├── onocomm-mail2/                 # Mail Ver.2新規オンライン契約
    │   ├── onocomm-mail2-terms.md      # サービス利用条件
    │   ├── onocomm-mail2-online-terms.md # オンライン申込条件
    │   └── onocomm-mail2-history.md    # 変更履歴
    ├── onocomm-members/               # メンバーズ新規オンライン契約
    │   ├── onocomm-members-contract.md # 現行約款
    │   ├── onocomm-members-history.md  # 変更履歴・将来構想
    │   └── archive/                   # 過去バージョン保管
    ├── aws-support/                   # AWSサポートサービス
    │   ├── aws-support-contract.md    # 現行約款
    │   ├── aws-support-history.md     # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    ├── aws-build/                     # AWS構築支援サービス
    │   ├── aws-build-contract.md      # 現行約款
    │   ├── aws-build-history.md       # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    ├── apmo-observability/            # アプモくん Observabilityダッシュボード
    │   ├── apmo-observability-terms.md  # 現行利用約款
    │   ├── apmo-observability-history.md   # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    ├── pengi-agent/                   # ペンジーくん AIエージェントフレームワーク
    │   ├── pengi-agent-terms.md    # 現行利用約款
    │   ├── pengi-agent-history.md     # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    └── mail-virus-check/              # メールウイルスチェックサービス
        ├── mail-virus-check-terms.md        # 現行規約
        ├── mail-virus-check-history.md      # サービス固有の変更履歴
        └── archive/                         # 過去バージョン保管
```

## 📄 約款の種類

### 基本約款

**オノコムサービス契約約款** - 全サービス共通の基本約款

- **現行版**: [contract_jp.md](./contract_jp.md) (第9版 / 2026年11月14日施行)
- **旧版**: [archive/v8_2026-11-14.md](./archive/v8_2026-11-14.md) (第8版 / 2026年11月14日施行)
- **変更履歴**: [contract-jp-history.md](./contract-jp-history.md)
- **対象サービス**:
  - オノコムメンバーズ
  - 生成AI関連サービス
  - AWSクラウド関連サービス
  - ローコード開発アプモ
  - サーバーサービス
  - メールサービス
  - マネージドDNS NS53サービス
  - ドメイン名サービス
  - SSLサーバー証明書サービス
  - その他当社が指定するサービス

### 個別サービス約款

各サービス固有の詳細な利用条件を定めた約款です。基本約款と合わせてご確認ください。

#### AWSクラウドサービス決済代行・新規発行オンライン契約条件

Portalから新規に申し込み、当社が承諾するAWS決済代行・新規アカウント発行の条件です。既存のAWS契約、移管及び他サービスを変更しません。

- **専用条件**: [services/aws-cloud/aws-cloud-contract.md](./services/aws-cloud/aws-cloud-contract.md) (第1版 / 2026年11月14日施行)
- **変更履歴**: [services/aws-cloud/aws-cloud-history.md](./services/aws-cloud/aws-cloud-history.md)
- **根拠対応表**: [services/aws-cloud/aws-cloud-source-map.md](./services/aws-cloud/aws-cloud-source-map.md)（約款本文ではありません）
- **固定条件**: 当社初期費用無料、統一割引なし、特別要件は別途契約。初期費用無料を理由に、AWS利用料金や選択したプランのサポート料金を全て無料とはしません。
- **出典**: CloudSign契約書の確認資料を基に、料金算定、Organizations/root管理、請求・支払、契約期間、制限事項、保証金、責任上限及び終了条件を整理しています。確認範囲と既存文書との差異は根拠対応表に記録しています。
- **同意対象**: 無料プランを含む全申込で基本約款・AWS専用条件・AWSサポート約款の3文書に同意します。3文書構成は実装設計であり、ユーザーが明示した料金・受付条件とは出典を区別しています。既存AWSサポート約款は変更していません。
- **追加原文の反映**: RI/SP等の購入・利用、無料利用枠、Organizations/root及び顧客AWSサポートの制限と個別協議、保証金、責任上限、日本法・大阪地裁の第一審専属的合意管轄を反映済みです。本人IAM・MFA・Portal管理選択も最小限説明し、SCP等の新規実装要件にはしません。
- **申込・課金条件**: 全4プラン、初期パスワードの本人限定Portal確認・初回変更必須、サポート初月無料・解約月非日割りを定めています。初月はAWS作成日のJST月で、翌月1日課金開始、開始日前に終了した場合は徴収しません。マネージドは段階表・各帯切上げ・最低100,000円との比較、項目別の提供範囲を明示し、申込条件にも固定します。

#### メール配送サービスオンライン契約条件

2026年11月14日以降にPortalから新規成立する送信専用onocomm-relay契約向けです。メールVer.2とは独立して申し込めます。

- **契約条件**: [services/onocomm-relay/onocomm-relay-contract.md](./services/onocomm-relay/onocomm-relay-contract.md) (第1版 / 2026年11月14日施行)
- **変更履歴**: [services/onocomm-relay/onocomm-relay-history.md](./services/onocomm-relay/onocomm-relay-history.md)
- **料金**: 基本・当面の従量単価とも0円（税別）。配送成功した宛先数を対象とします。
- **申込・解約**: 自動承諾、本人初期管理者登録、固定版同意・控え。即日解約で新規受付を停止し、受付済み配送は継続します。既存契約・他サービスは変更しません。

#### メールサービスVer.2 サービス利用条件・オンライン申込条件

2026年11月13日以降にPortalから新規に申し込み、当社が承諾するVer.2標準契約向けの条件です。Ver.1、既存メール契約及び移行を対象にしません。

- **サービス利用条件**: [services/onocomm-mail2/onocomm-mail2-terms.md](./services/onocomm-mail2/onocomm-mail2-terms.md) (第1版 / 2026年11月13日施行)
- **オンライン申込条件**: [services/onocomm-mail2/onocomm-mail2-online-terms.md](./services/onocomm-mail2/onocomm-mail2-online-terms.md) (第1版 / 2026年11月13日施行)
- **変更履歴**: [services/onocomm-mail2/onocomm-mail2-history.md](./services/onocomm-mail2/onocomm-mail2-history.md)
- **料金**: 基本500円（税別）・10GB、超過分は十進1GB単位切上げで10円。登録月の基本・容量料金は無料。有料サポートは任意で月額20,000円と200円×課金対象アカウント数の高い方、登録月も課金。
- **申込**: 自動承諾、専用DNS TXTによる管理権限確認後の開通、申込者本人の初期管理者招待及び受諾。
- **日付と課金**: TXT確認成功及び明示同意を検証した提出時に自動承諾し契約成立。登録日・無料月はメールドメイン利用準備成功の日本時間の日付で確定。未準備期間は課金せず、無料月も消費しません。準備成功後の初期管理者招待受諾待ちで課金開始を延期しません。
- **解約と適用範囲**: 本条件に同意して新規成立するVer.2契約だけ当月末解約。既存の契約条件・同意記録は変更しません。個別作業は別途見積・合意とし、0円とは定めません。

#### オノコムメンバーズ契約約款

Portalからの新規オンライン申込に適用する約款。既存署名済み契約を自動変更しません。

- **現行版**: [services/onocomm-members/onocomm-members-contract.md](./services/onocomm-members/onocomm-members-contract.md) (第1版 / 2026年11月12日施行)
- **変更履歴・将来構想**: [services/onocomm-members/onocomm-members-history.md](./services/onocomm-members/onocomm-members-history.md)
- **主な条件**: カジュアル・メンバーズの2プラン、初期0円、各申込月無料・翌月1日課金、初回は申込月残日数＋12か月、以後12か月更新。年間拘束なし、初回課金月以降は申出当月末解約・満額。
- **請求と支払**: 月末締め・5営業日以内に請求書提出。銀行振込は利用月の翌月末、口座振替は翌月の事前案内した指定日、カードは翌月の当社指定日に決済。カード会社に対する支払・口座引落日はカード会社との契約に従う。
- **申込と記録**: 同一請求アカウントの複数契約を警告のうえ許可。固定文書への明示同意、自動承諾、控え及び追記型履歴を保存。
- **適用関係**: サービス仕様書の具体的な定めを優先し、個別約款で補完。基本約款に対する例外は新規メンバーズオンライン契約に限定。
- **対象外**: Portalからのトライアル、ブースト追加及び既存契約のプラン変更。

#### AWSサポートサービス契約約款

Amazon Web Services (AWS) のサポートサービスに関する約款

- **現行版**: [services/aws-support/aws-support-contract.md](./services/aws-support/aws-support-contract.md) (第1版 / 2024年4月1日施行)
- **変更履歴**: [services/aws-support/aws-support-history.md](./services/aws-support/aws-support-history.md)
- **サービス内容**:
  - AWSアカウントのサポート
  - サービスプランに応じたサポート提供
  - AWS決済代行サービスとの連携

#### AWS構築支援サービス契約約款

Amazon Web Services (AWS) の構築作業支援に関する約款

- **現行版**: [services/aws-build/aws-build-contract.md](./services/aws-build/aws-build-contract.md) (第1版 / 2024年4月1日施行)
- **変更履歴**: [services/aws-build/aws-build-history.md](./services/aws-build/aws-build-history.md)
- **サービス内容**:
  - AWS構築作業の支援(準委託契約)
  - 検収期間: 作業完了から14日以内
  - AWS決済代行サービス及びAWSサポートサービスとの連携

#### メールウイルスチェックサービス利用規約

メールサービスのウイルス・スパム対策に関する利用規約

- **現行版**: [services/mail-virus-check/mail-virus-check-terms.md](./services/mail-virus-check/mail-virus-check-terms.md) (第1版 / 2016年9月20日制定)
- **変更履歴**: [services/mail-virus-check/mail-virus-check-history.md](./services/mail-virus-check/mail-virus-check-history.md)
- **サービス内容**:
  - オノコムサービス利用者向けオプションサービス
  - Trend Micro社のウイルス・マルウェア対策
  - スパムメール判定機能

#### ペンジーくん AIエージェントフレームワーク利用約款

AIエージェント、チャット、タスク実行、スケジュール実行、成果物管理、外部サービス連携を行うフレームワークの利用条件に関する約款

- **現行版**: [services/pengi-agent/pengi-agent-terms.md](./services/pengi-agent/pengi-agent-terms.md) (第1版 / 2026年6月18日施行)
- **変更履歴**: [services/pengi-agent/pengi-agent-history.md](./services/pengi-agent/pengi-agent-history.md)
- **フレームワーク内容**:
  - AIエージェントとのチャット及びマルチユーザーチャット
  - バンドル、エージェント定義、アプリ定義、役割定義のインポート・エクスポート
  - タスク型エージェントによるタスク実行、成果物生成、プレビュー
  - Google Workspace、Microsoft 365、GitHub、AIプロバイダー等との外部サービス連携
- **主な条件**:
  - オノコムメンバーズ契約期間中は、別途定めがない限り追加のシステム利用料なし
  - オノコムメンバーズ契約期間中は保守サポートを提供し、内容はオノコムメンバーズの契約内容・個別に合意した支援内容に従う
  - 専用AWSアカウントは当社がSPP等に基づき発行・管理し、標準ではお客様の直接ログインを提供せず、保存データの権利はお客様又は正当な権利者に留保
  - 標準的な専用AWSアカウント費用は無償提供とし、お客様がAWSアカウントアクセスやデータ取得等を希望する場合は協議の上、実利用分又は個別条件に基づき請求
  - 標準保存期間は1年間
  - ONOCOMM AI Gateway利用時、アプモくんAI診断と合算して月間5,000円(税別)相当までのAIモデル利用を無償アクセス枠として提供し、無償枠到達後は停止、継続利用は別途契約が必要
  - MIT Licenseの適用が明示された公開ソースコード部分はMIT Licenseに基づき利用可能
  - AIエージェントの役割は内蔵固定ではなく、導入済みバンドルや定義により与えられる

#### アプモくん Observabilityダッシュボード利用約款

クラウド・AIエージェント等のセキュリティ/運用情報の可視化、ReadOnly収集、改善タスク管理、固定AI診断に関する約款

- **現行版**: [services/apmo-observability/apmo-observability-terms.md](./services/apmo-observability/apmo-observability-terms.md) (第1版 / 2026年6月18日施行)
- **変更履歴**: [services/apmo-observability/apmo-observability-history.md](./services/apmo-observability/apmo-observability-history.md)
- **ダッシュボード内容**:
  - AWS Security Hub、GuardDuty、Inspector、WAF、Backup、Health、Config、CloudTrail等を中心とした可視化
  - その他クラウド、AIエージェント、業務システムのテレメトリー、動作ログ、監査ログ等の取り込み
  - ReadOnly Collector Role等による対象アカウント・対象システムの収集状態・検出結果の整理
  - ONOCOMM AI Gatewayのみを利用した所定のAIセキュリティ診断レポート生成
- **主な条件**:
  - オノコムメンバーズ契約期間中は、別途定めがない限り追加のシステム利用料なし
  - 専用AWSアカウントは当社がSPP等に基づき発行・管理し、標準ではお客様の直接ログインを提供せず、保存データの権利はお客様又は正当な権利者に留保
  - 標準的な専用AWSアカウント費用は無償提供とし、お客様がAWSアカウントアクセスやデータ取得等を希望する場合は協議の上、実利用分又は個別条件に基づき請求
  - 標準保存期間は1年間
  - AI診断はOFFにすることが可能
  - アプモくんAI診断とペンジーくん AIエージェントフレームワークのONOCOMM AI Gateway利用を合算して、月間5,000円(税別)相当までのAIモデル利用を無償アクセス枠として提供し、無償枠到達後は停止、継続利用は別途契約が必要

## 📚 変更履歴

### 統合変更履歴

全サービスの約款変更を時系列で確認できます。

**ドキュメント**: [CHANGELOG.md](./CHANGELOG.md)

### サービス別変更履歴

各サービスの約款の詳細な変更履歴:

- **基本約款**: [contract-jp-history.md](./contract-jp-history.md)
- **メール配送**: [services/onocomm-relay/onocomm-relay-history.md](./services/onocomm-relay/onocomm-relay-history.md)
- **メールサービスVer.2**: [services/onocomm-mail2/onocomm-mail2-history.md](./services/onocomm-mail2/onocomm-mail2-history.md)
- **オノコムメンバーズ**: [services/onocomm-members/onocomm-members-history.md](./services/onocomm-members/onocomm-members-history.md)
- **AWSサポートサービス**: [services/aws-support/aws-support-history.md](./services/aws-support/aws-support-history.md)
- **AWS構築支援サービス**: [services/aws-build/aws-build-history.md](./services/aws-build/aws-build-history.md)
- **メールウイルスチェックサービス**: [services/mail-virus-check/mail-virus-check-history.md](./services/mail-virus-check/mail-virus-check-history.md)
- **ペンジーくん AIエージェントフレームワーク**: [services/pengi-agent/pengi-agent-history.md](./services/pengi-agent/pengi-agent-history.md)
- **アプモくん Observabilityダッシュボード**: [services/apmo-observability/apmo-observability-history.md](./services/apmo-observability/apmo-observability-history.md)

## 🔍 約款の適用関係

### 基本約款と個別サービス約款の関係

1. **基本約款 (contract_jp.md)** が全サービスに共通して適用されます
2. **個別サービス約款** は、各サービスの詳細条件を定めます
3. 個別サービス約款と基本約款の内容が矛盾する場合、各文書に定める適用関係を確認します
4. 2026年11月12日以降の新規メンバーズオンライン契約では、個別約款及び参照するサービス仕様書の具体的な定めを基本約款に優先します。仕様書を優先し、個別約款で補完します。この例外は他サービス及び既存署名済み契約の条件を変更しません
5. 2026年11月13日以降にPortalから新規に申し込み、当社が承諾するMail Ver.2契約では、オンライン申込条件、サービス利用条件、基本約款の順で具体的な定めを優先します。この例外もVer.1、既存メール契約、移行及び他サービスの条件・過去の同意内容を変更しません
6. 2026年11月14日以降にPortalから新規成立するメール配送onocomm-relay契約では、メール配送サービスオンライン契約条件の具体的な定めを基本約款に優先します。既存契約・他サービス・過去の同意は変更しません
7. 第9版では、新規AWS決済代行・新規発行オンライン契約だけに専用条件を優先する例外を追加しています。既存契約や他サービスの条件を変更しません

### 約款の確認手順

サービスを利用する際は、以下の順序で約款をご確認ください:

1. [基本約款 (contract_jp.md)](./contract_jp.md) を確認
2. 該当する個別サービス約款(例: [AWSサポートサービス](./services/aws-support/aws-support-contract.md))を確認
3. 両方の約款の内容を理解した上でサービスを利用

## 📖 約款の閲覧方法

### 最新版を確認する

1. 基本約款: [contract_jp.md](./contract_jp.md) を開く
2. 個別サービス: `services/[サービス名]/` ディレクトリ内の約款を開く
3. マークダウン形式で整形された約款を確認

### 変更履歴を確認する

1. 統合ビュー: [CHANGELOG.md](./CHANGELOG.md) で全サービスの変更を時系列で確認
2. サービス別: 各サービスの `[サービス名]-history.md` で詳細な変更内容を確認
3. 過去バージョン: `archive/` ディレクトリ内のファイルを確認

### 過去バージョンを確認する

- 基本約款: [archive/](./archive/) ディレクトリ内の `v1_`, `v2_`, `v3_`, `v4_`, `v5_`, `v6_`, `v7_`, `v8_` ファイル
- 個別サービス: 各サービスの `archive/` ディレクトリ(今後追加される改訂版を格納)

## 🆕 新しいサービス約款の追加方法

新しいサービスの約款を追加する際は、以下の構造に従ってください:

```
services/
└── [サービス識別子]/
    ├── [サービス識別子]-contract.md    # 現行約款
    ├── [サービス識別子]-history.md     # 変更履歴
    └── archive/                          # 過去バージョン
        └── v[N]_YYYY-MM-DD.md           # 過去の改訂版
```

例:
- `services/email-service/email-service-contract.md` と `email-service-history.md`
- `services/dns-ns53/dns-ns53-contract.md` と `dns-ns53-history.md`

## ⚖️ 約款の適用

本約款は、株式会社オノコムと契約者との間において、当社が提供するサービスの利用に係わる一切の関係に適用されます。

- サービス利用前に必ず内容をご確認ください
- サービスの利用は、本約款の内容を承諾していることを前提とします
- 詳細な仕様や料金については、[当社WEBサイト](http://www.onocomm.jp/) をご確認ください

## 📝 申請フォーム

オノコムサービスのご利用に関連する各種手続きの申請フォームをご案内しています。

**📄 [申請フォーム一覧 (application.md)](./application.md)**

以下の申請フォームをご利用いただけます:
- オノコムポータルサイトアカウント申請
- オノコム請求アカウント申請
- ドメイン名の申請
- JPRS証明書の発行依頼
- メール送受信の調査依頼

詳細は [application.md](./application.md) をご確認ください。

## 📮 お問い合わせ

約款に関するご質問やお問い合わせは、株式会社オノコムまでご連絡ください。

**株式会社オノコム**
- WEBサイト: http://www.onocomm.jp/

---

## 📊 改訂履歴サマリー

### 基本約款
- **第9版** (2026年11月14日) - 現行版
- **第8版** (2026年11月14日)
- **第7版** (2026年11月13日)
- **第6版** (2026年11月12日)
- **第5版** (2025年11月1日)
- **第4版** (2021年2月1日)
- **第3版** (2018年7月1日)
- **第2版** (2016年10月1日)
- **第1版** (2010年8月1日)

### オノコムメンバーズ契約約款
- **第1版** (2026年11月12日) - 新規オンライン契約向け現行版

### メールサービスVer.2 サービス利用条件・オンライン申込条件
- **各第1版** (2026年11月13日) - 新規オンライン契約向け現行版

### メール配送サービスオンライン契約条件
- **第1版** (2026年11月14日) - 新規オンライン契約向け現行版

### AWSクラウドサービス決済代行・新規発行オンライン契約条件
- **第1版** (2026年11月14日) - 新規オンライン契約向け現行版

### AWSサポートサービス契約約款
- **第1版** (2024年4月1日) - 現行版

### AWS構築支援サービス契約約款
- **第1版** (2024年4月1日) - 現行版

### アプモくん Observabilityダッシュボード利用約款
- **第1版** (2026年6月18日) - 現行版

### ペンジーくん AIエージェントフレームワーク利用約款
- **第1版** (2026年6月18日) - 現行版

### メールウイルスチェックサービス利用規約
- **第1版** (2016年9月20日) - 現行版

---

**最終更新日**: 2026年11月14日
**管理者**: 株式会社オノコム
