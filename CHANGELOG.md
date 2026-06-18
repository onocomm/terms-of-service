# 変更履歴 (CHANGELOG)

本ドキュメントは、株式会社オノコムが提供する全サービスの契約約款に関する変更履歴の統合ビューです。

各サービス約款の詳細な変更履歴については、それぞれの変更履歴ファイルをご参照ください。

---

## 📋 凡例

- **[基本約款]**: オノコムサービス契約約款 (`contract_jp.md`)
- **[AWS サポート]**: AWSサポートサービス契約約款 (`services/aws-support/`)
- **[AWS 構築]**: AWS構築支援サービス契約約款 (`services/aws-build/`)
- **[メールウイルス]**: メールウイルスチェックサービス利用規約 (`services/mail-virus-check/`)
- **[ペンジーくん]**: ペンジーくん AIエージェントフレームワーク利用約款 (`services/pengi-agent/`)
- **[アプモくん]**: アプモくん Observabilityダッシュボード利用約款 (`services/apmo-observability/`)

---

## 2026年

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
  - 詳細: [contract-jp-history.md](./contract-jp-history.md#第5版現行版---2025年11月1日)

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

**最終更新日**: 2026年6月18日
**管理者**: 株式会社オノコム
