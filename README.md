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
│   └── v4_2021-02-01.md              # 第4版
│
└── services/                          # 個別サービス約款
    ├── aws-support/                   # AWSサポートサービス
    │   ├── aws-support-contract.md    # 現行約款
    │   ├── aws-support-history.md     # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    ├── aws-build/                     # AWS構築支援サービス
    │   ├── aws-build-contract.md      # 現行約款
    │   ├── aws-build-history.md       # サービス固有の変更履歴
    │   └── archive/                   # 過去バージョン保管
    └── mail-virus-check/              # メールウイルスチェックサービス
        ├── mail-virus-check-terms.md        # 現行規約
        ├── mail-virus-check-history.md      # サービス固有の変更履歴
        └── archive/                         # 過去バージョン保管
```

## 📄 約款の種類

### 基本約款

**オノコムサービス契約約款** - 全サービス共通の基本約款

- **現行版**: [contract_jp.md](./contract_jp.md) (第5版 / 2025年11月1日施行)
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

## 📚 変更履歴

### 統合変更履歴

全サービスの約款変更を時系列で確認できます。

**ドキュメント**: [CHANGELOG.md](./CHANGELOG.md)

### サービス別変更履歴

各サービスの約款の詳細な変更履歴:

- **基本約款**: [contract-jp-history.md](./contract-jp-history.md)
- **AWSサポートサービス**: [services/aws-support/aws-support-history.md](./services/aws-support/aws-support-history.md)
- **AWS構築支援サービス**: [services/aws-build/aws-build-history.md](./services/aws-build/aws-build-history.md)
- **メールウイルスチェックサービス**: [services/mail-virus-check/mail-virus-check-history.md](./services/mail-virus-check/mail-virus-check-history.md)

## 🔍 約款の適用関係

### 基本約款と個別サービス約款の関係

1. **基本約款 (contract_jp.md)** が全サービスに共通して適用されます
2. **個別サービス約款** は、各サービスの詳細条件を定めます
3. 個別サービス約款と基本約款の内容が矛盾する場合、個別サービス約款が優先されます

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

- 基本約款: [archive/](./archive/) ディレクトリ内の `v1_`, `v2_`, `v3_`, `v4_` ファイル
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
- **第5版** (2025年11月1日) - 現行版
- **第4版** (2021年2月1日)
- **第3版** (2018年7月1日)
- **第2版** (2016年10月1日)
- **第1版** (2010年8月1日)

### AWSサポートサービス契約約款
- **第1版** (2024年4月1日) - 現行版

### AWS構築支援サービス契約約款
- **第1版** (2024年4月1日) - 現行版

### メールウイルスチェックサービス利用規約
- **第1版** (2016年9月20日) - 現行版

---

**最終更新日**: 2024年4月1日
**管理者**: 株式会社オノコム
