# 変更履歴 (CHANGELOG)

本ドキュメントは、株式会社オノコムが提供する全サービスの契約約款に関する変更履歴の統合ビューです。

各サービス約款の詳細な変更履歴については、それぞれの変更履歴ファイルをご参照ください。

---

## 📋 凡例

- **[メンバーズ]**: オノコムメンバーズ契約約款 (`services/onocomm-members/`)
- **[Mail Ver.2]**: メールサービスVer.2サービス利用条件・オンライン申込条件 (`services/onocomm-mail2/`)
- **[メール配送]**: メール配送サービスオンライン契約条件 (`services/onocomm-relay/`)
- **[基本約款]**: オノコムサービス契約約款 (`contract_jp.md`)
- **[AWS クラウド]**: AWS決済代行・新規発行オンライン契約条件 (`services/aws-cloud/`)
- **[AWS サポート]**: AWSサポートサービス契約約款 (`services/aws-support/`)
- **[AWS 構築]**: AWS構築支援サービス契約約款 (`services/aws-build/`)
- **[メールウイルス]**: メールウイルスチェックサービス利用規約 (`services/mail-virus-check/`)
- **[ペンジーくん]**: ペンジーくん AIエージェントフレームワーク利用約款 (`services/pengi-agent/`)
- **[アプモくん]**: アプモくん Observabilityダッシュボード利用約款 (`services/apmo-observability/`)

---

## 2026年

### 2026年11月14日
- **[AWS クラウド]** 新規オンライン契約条件第1版を制定。当社初期費用無料、統一割引なし、特別要件は別途契約。CloudSign正本の確認資料に基づき、料金・管理・終了条件、利用制限・保証金・責任上限・日本法及び大阪地裁の専属管轄を記載。原本の確認範囲は根拠対応表に記録。
  - 追加の実ユーザー回答から全4プラン受付、初期パスワードの本人限定Portal確認・初回変更必須、サポート初月無料・解約月非日割りを反映。初月はAWS作成JST月、翌月1日課金開始と具体化し、開始日前の終了は徴収しない。既存サポート約款第14条・第16条及びConsoleの月単位入力を照合し、既存契約は変更しない。
  - マネージドは最新CLI 3.1.110の単価表再確認と既存Invoice段階式に基づき、3〜20%の各帯切上げ・積上げと最低100,000円の高い方を表示・固定する。構築7日、事務24h・一般12h・本番4h及び個別の対応項目を列挙し、将来機能を自動包含する表現は使わない。CloudSign雛形の空欄を補う現行請求計算の明示と区別する。
  - 全申込3文書同意は実装設計として採用し、ユーザーが明示した受付・料金条件と出典を区別。既存サポート約款本文は変更せず、新規発行時のサポート用アクセス・本人IAM・MFA・Portal管理選択を専用条件で説明。
  - [根拠対応表](./services/aws-cloud/aws-cloud-source-map.md)に、出典、原本の確認範囲、既存約款との差異、検証範囲及び将来のフィードバック項目を記録。
- **[基本約款]** 第9版で新規AWS契約限定の優先例外を第3条第8項へ追加。第8版全文を保存し、既存Relay/Mail2等の本文及び過去同意を維持。
- **[メール配送]** 新規オンライン契約条件第1版を制定。基本料金・当面の従量単価0円（税別）、配送成功宛先数、自動承諾、本人初期管理者及び即日解約を規定。
- **[基本約款]** 第8版で新規Relayオンライン契約に限る優先関係を第3条第7項へ追加。第7版を保存し、既存契約・過去の同意・Mail Ver.2の条件を維持。

### 2026年11月13日
- **[Mail Ver.2]** 新規オンライン契約用のサービス利用条件・オンライン申込条件を各第1版として制定
  - 基本500円（税別）・10GB、十進1GB単位切上げの超過10円、登録月の基本・容量無料を明記。
  - 任意の有料サポートは20,000円と200円×課金対象アカウント数の高い方とし、登録月も課金。個別作業は別途見積・合意とし、0円とは定めない。
  - 自動承諾、専用DNS TXT確認後の開通、本人の初期管理者招待、固定版文書への同意及び控えを規定。
  - TXT確認成功・明示同意後の提出時に契約成立。登録日・無料月はメールドメイン利用準備成功のJST日付で確定し、準備未完了期間を課金せず無料月も消費しない。初期管理者招待受諾待ちで課金開始を延ばさない。
  - 新規Ver.2契約だけ当月末解約を優先。Ver.1、既存契約、移行及び既存同意は変更しない。
  - 詳細: [services/onocomm-mail2/onocomm-mail2-history.md](./services/onocomm-mail2/onocomm-mail2-history.md)
- **[基本約款]** 第7版を制定
  - 第3条第6項にMail Ver.2新規オンライン契約限定の優先関係を追加。他の本文及びメンバーズの例外は変更しない。
  - 第6版全文をarchiveへ保存。過去の同意・証跡は差し替えない。
  - 詳細: [contract-jp-history.md](./contract-jp-history.md)

### 2026年11月12日
- **[メンバーズ]** 新規オンライン契約向け契約約款 第1版を制定
  - カジュアル・メンバーズ、初期0円、各申込月無料、翌月課金、初回申込月残日数＋12か月、12か月更新と年間拘束なし、初回課金月以降の当月末解約・満額を明記。
  - 独立した複数契約、重複警告、自動承諾、固定文書への同意、控え及び追記型履歴を規定。
  - 旧共通ひな形の支払・相互守秘・反社・未実施月料金・双方損害賠償・解除・譲渡・準拠法/管轄・協議を移植。既存署名済み契約を自動変更しない。
  - 公開前の請求運用照合を反映し、銀行振込は翌月末、口座振替は翌月の事前案内した指定日、カードは翌月の当社指定日の決済とカード会社に対する支払・引落日を区別。5営業日以内の請求書提出を維持。
  - ブースト及びプラン変更は現在の提供範囲にせず、履歴内の将来構想として記録。
  - 詳細: [services/onocomm-members/onocomm-members-history.md](./services/onocomm-members/onocomm-members-history.md)
- **[基本約款]** 第6版を制定
  - 第3条第5項に新規メンバーズオンライン契約限定の個別約款・仕様書優先の例外を追加。他サービスの条件は変更しない。
  - 第5版全文をarchiveへ保存。
  - 詳細: [contract-jp-history.md](./contract-jp-history.md)

### 2026年6月18日
- **[アプモくん]** アプモくん Observabilityダッシュボード利用約款 第1版を制定
  - AWSを中心としたクラウド・AIエージェント等のセキュリティ/運用情報、テレメトリー、動作ログの可視化、ReadOnly収集、改善タスク管理、レポート管理に関する約款を新規作成
  - 当社SPP等に基づく専用AWSアカウント、標準時の直接ログイン非提供、Collector Role、STS AssumeRole、その他クラウド/AIエージェント連携、ReadOnly境界、標準保存期間1年、お客様データの権利留保を規定
  - ONOCOMM AI Gatewayのみを利用した固定AI診断、AI診断OFF、ペンジーくん AIエージェントフレームワークとの合算で月間5,000円(税別)相当のAIモデル無償枠、無償枠到達後の停止、継続利用時の別途契約を反映
  - 詳細: [services/apmo-observability/apmo-observability-history.md](./services/apmo-observability/apmo-observability-history.md#第1版---2026年6月18日)

- **[ペンジーくん]** ペンジーくん AIエージェントフレームワーク利用約款 第1版を制定
  - AIエージェント、チャット、タスク実行、スケジュール実行、成果物管理を行うフレームワークの利用約款を新規作成
  - バンドル、エージェント定義、アプリ定義、役割定義のインポート・エクスポートと、役割が内蔵固定ではなく導入済み定義により与えられることを規定
  - AI生成物、入力データ、外部AIプロバイダー、OAuth連携、GitHub連携、AWSクレデンシャル等の取扱いを規定
  - 当社SPP等に基づく専用AWSアカウント、標準時の直接ログイン非提供、部署別アクセス制御、標準保存期間1年、ONOCOMM AI Gateway利用時のAIモデル月間5,000円(税別)相当の無償枠、無償枠到達後の停止、継続利用時の別途契約、保存延長時の個別条件を反映
  - MIT Licenseの適用範囲、オノコムメンバーズ契約期間中の保守サポート、お客様データの権利留保、ONOCOMM AI Gateway利用時のデータ取扱いを追記
  - 保守サポートの範囲・方法・対応内容は、オノコムメンバーズの契約内容及び個別に合意した支援内容に従う形へ整理
  - 法人向け利用、オノコムメンバーズ契約に従う免責及び損害賠償の適用関係、データ権利、解約後処理、AI高影響操作の承認、汎用AIモデル学習目的で利用しない旨を整理
  - 詳細: [services/pengi-agent/pengi-agent-history.md](./services/pengi-agent/pengi-agent-history.md#第1版---2026年6月18日)

## 2025年

### 2025年11月1日
- **[基本約款]** 第5版を制定
  - サービス名称を「オノコムクラウドサービス」から「オノコムサービス」に簡略化
  - 提供サービスを大幅に刷新(オノコムメンバーズ、生成AI関連サービス等を追加)
  - 第21条(領収書)を新設 - キャッシュレス決済への対応
  - 条項の整理・簡素化を実施
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第5版---2025年11月1日)

## 2024年

### 2024年4月1日
- **[AWS サポート]** AWSサポートサービス契約約款 第1版を制定
  - Amazon Web Servicesのサポートサービスに関する約款を新規制定
  - 従量課金制の委託料計算方法を規定
  - 保証金制度を導入
  - 詳細: [services/aws-support/aws-support-history.md](./services/aws-support/aws-support-history.md#第1版---2024年4月1日)

- **[AWS 構築]** AWS構築支援サービス契約約款 第1版を制定
  - Amazon Web Servicesの構築作業支援に関する約款を新規制定
  - 準委託契約による受託形態
  - 検収期間の設定(作業完了から14日以内)
  - AWS決済代行サービス及びAWSサポートサービスとの連携が前提
  - 詳細: [services/aws-build/aws-build-history.md](./services/aws-build/aws-build-history.md#第1版---2024年4月1日)

## 2021年

### 2021年2月1日
- **[基本約款]** 第4版を制定
  - サービス内容を簡素化
  - 禁止事項を簡素化
  - 技術的な詳細条項を削除
  - 免責事項を簡素化
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第4版---2021年2月1日)

## 2018年

### 2018年7月1日
- **[基本約款]** 第3版を制定
  - サービス内容を再編(パブリッククラウド、コンテナサービス等)
  - メンテナンス時間を拡大(午前4時〜7時 → 午前0時〜7時)
  - データ消去条件を厳格化(6ヶ月 → 2ヶ月)
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第3版---2018年7月1日)

## 2016年

### 2016年10月1日
- **[基本約款]** 第2版を制定
  - サービス内容を大幅に拡充(マネージドVPN、データセンター等を追加)
  - 一部禁止事項を削除(カーネルアップデート、固定IP設定等)
  - 利用期間条項を簡素化
  - データ消去条件を厳格化(6ヶ月 → 2ヶ月)
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第2版---2016年10月1日)

### 2016年9月20日
- **[メールウイルス]** メールウイルスチェックサービス利用規約 第1版を制定
  - オノコムサービス利用者向けオプションサービスとして制定
  - Trend Micro社のウイルス・マルウェア対策クラウドサービスを使用
  - スパムメール判定機能を提供
  - メールアドレス数申請の義務化
  - 詳細: [services/mail-virus-check/mail-virus-check-history.md](./services/mail-virus-check/mail-virus-check-history.md#第1版---2016年9月20日)

## 2010年

### 2010年8月1日
- **[基本約款]** 第1版を制定
  - オノコムクラウドサービス契約約款の初版を制定
  - 全30条から構成される詳細な約款
  - 技術的な禁止事項を含む包括的な規定
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第1版---2010年8月1日平成22年8月1日)

---

## 📚 関連ドキュメント

### 基本約款
- 現行版: [contract_jp.md](./contract_jp.md)
- 変更履歴: [contract-jp-history.md](./contract-jp-history.md)
- 過去バージョン: [archive/](./archive/)

### 個別サービス約款
- **メール配送**
  - 契約条件: [services/onocomm-relay/onocomm-relay-contract.md](./services/onocomm-relay/onocomm-relay-contract.md)
  - 変更履歴: [services/onocomm-relay/onocomm-relay-history.md](./services/onocomm-relay/onocomm-relay-history.md)

- **メールサービスVer.2**
  - サービス利用条件: [services/onocomm-mail2/onocomm-mail2-terms.md](./services/onocomm-mail2/onocomm-mail2-terms.md)
  - オンライン申込条件: [services/onocomm-mail2/onocomm-mail2-online-terms.md](./services/onocomm-mail2/onocomm-mail2-online-terms.md)
  - 変更履歴: [services/onocomm-mail2/onocomm-mail2-history.md](./services/onocomm-mail2/onocomm-mail2-history.md)

- **オノコムメンバーズ**
  - 現行版: [services/onocomm-members/onocomm-members-contract.md](./services/onocomm-members/onocomm-members-contract.md)
  - 変更履歴: [services/onocomm-members/onocomm-members-history.md](./services/onocomm-members/onocomm-members-history.md)
- **AWS決済代行・新規発行オンライン契約**
  - 専用条件: [services/aws-cloud/aws-cloud-contract.md](./services/aws-cloud/aws-cloud-contract.md)
  - 変更履歴: [services/aws-cloud/aws-cloud-history.md](./services/aws-cloud/aws-cloud-history.md)
  - 根拠対応表: [services/aws-cloud/aws-cloud-source-map.md](./services/aws-cloud/aws-cloud-source-map.md)

- **AWSサポートサービス**
  - 現行版: [services/aws-support/aws-support-contract.md](./services/aws-support/aws-support-contract.md)
  - 変更履歴: [services/aws-support/aws-support-history.md](./services/aws-support/aws-support-history.md)

- **AWS構築支援サービス**
  - 現行版: [services/aws-build/aws-build-contract.md](./services/aws-build/aws-build-contract.md)
  - 変更履歴: [services/aws-build/aws-build-history.md](./services/aws-build/aws-build-history.md)

- **アプモくん Observabilityダッシュボード**
  - 現行版: [services/apmo-observability/apmo-observability-terms.md](./services/apmo-observability/apmo-observability-terms.md)
  - 変更履歴: [services/apmo-observability/apmo-observability-history.md](./services/apmo-observability/apmo-observability-history.md)

- **ペンジーくん AIエージェントフレームワーク**
  - 現行版: [services/pengi-agent/pengi-agent-terms.md](./services/pengi-agent/pengi-agent-terms.md)
  - 変更履歴: [services/pengi-agent/pengi-agent-history.md](./services/pengi-agent/pengi-agent-history.md)

- **メールウイルスチェックサービス**
  - 現行版: [services/mail-virus-check/mail-virus-check-terms.md](./services/mail-virus-check/mail-virus-check-terms.md)
  - 変更履歴: [services/mail-virus-check/mail-virus-check-history.md](./services/mail-virus-check/mail-virus-check-history.md)

---

**最終更新日**: 2026年11月14日
**管理者**: 株式会社オノコム
