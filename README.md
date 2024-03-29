# 職務経歴書

|key|value|
|---|-----|
|Name|富永 裕貴 (Yuki Tominaga)|

## 資格
|Certificate|valid|
|---|---|
|絶バハムート討滅戦|済|
|絶アルテマウェポン破壊作戦|済|
|絶アレキサンダー討滅戦|済|
|絶竜詩戦争|済|
|絶オメガ検証戦|済|
|Google Certified Professional Cloud Architect|2017/12 ~ |
|Google Certified Professional Data Engineer|2018/01 ~ |
|Google Certified Professional Cloud Developer|2019/01 ~ |
|Google Certified Professional DevOps Engineer|2019/01 ~ |
|Google Certified Professional Database Engineer|2023/09 ~ |
|Certified Kubernetes Administrator|2019/12 ~ |
|Google Cloud Authorized Trainer|2018/05 ~ |
|Linux Foundation 認定トレーナー|2023/12 ~ |
|Google Certified Associate Cloud Engineer|2018/08 ~ 2020/08|
|Google Certified Security Engineer|2019/01 ~ 2021/01|
|Certified Kubernetes Application Developer|2019/03 ~ 2022/03|


## スキル
### プログラミング言語

- TypeScript/JavaScript(他人のコードをレビューできる)
- Go(書き捨てのコードで使う)
- Java(Apache Beamでのみ利用する)
- Python(やりたくない)
- PHP(やりたくない)

### その他

- LangChain
- Angular
- Next.js
- NestJS
- GraphQL
- gRPC
- Google Cloud Platform
- Kubernetes
- Istio
- Helm
- Docker
- Hasura
- Firebase (主にWeb向け)

### コメント
ただ機能を開発するだけではなく、アベイラビリティ、レイテンシ、セキュリティ、トイルの撲滅といったSREと呼ばれている領域について考慮ができます。
ビジネス上必要であればSLOを定め、計測し、エラーバジェットをデプロイの判断とすることも可能です。
もちろん、Google Cloudを利用できる前提です。

## 言語

- 日本語
  - ネイティブ
- 英語
  - 英語の技術本にほとんど抵抗が無いレベルの読解

## 強み

- Google Cloud Platformへの深い知識
- パブリッククラウド技術の追い方
- 人前で話す場や顧客との折衝で明るく振る舞う
- FFXIV 9000時間以上プレイ
- 習得すべきことに対して `空き時間の全てを費やす` という姿勢
- 技術レベルの多様性を認めること

## 職務経歴

### 2022/04 ~ 現在 : クラウドエース株式会社 システム開発統括部 Expert

職務: チームのテクニカルマネジメント、Google Cloudのコンサルティング及び開発とそれらに伴うプロジェクトリード

### 2020/04 - 2022/03 : 株式会社スクウェア・エニックス 情報システム部 Global Infrastructure for Online Gaming

職務: 大規模オンラインゲーム及び関連サイトのインフラエンジニア

### 2017/11 - 2020/03 : クラウドエース株式会社

職務: Lead Engineer

#### Cloud Speech to Textを用いた日報の音声入力

- Node.js
- Angular
- Kubernetes

#### [Schoo](https://schoo.jp/class/4923)に出演

#### KubernetesにデプロイしたDBへの負荷試験検証

- Cassandra
- Redis
- Kuberentes

#### 外部API利用による手書き文字認識Webアプリケーション開発

- Angular

#### Cloud Speech to Textを利用したコールセンター向け通話音声の文字化アプリケーション

- Python
- Angular
- Firebase

#### 建設現場で利用する出退勤アプリケーション

- Kubernetes
- Angular

#### 大手ゲーム会社への半常駐

- Terraform

#### DRを考慮した金融系システム

- Kubernetes
- Istio
- Helm
- Terraform
- helmfile

#### Google Cloud 認定トレーナー業務

クラウドインフラストラクチャからデータ分析と機械学習まで幅広く対応可能

### 2016/04 - 2017/10 : 株式会社トライビート

職務: PHPプログラマ

#### 採用系ウェブアプリケーションの保守開発

- PHP
- MySQL
- Vagrant開発環境のDocker化、及びdocker-compose化

## 登壇歴
### Google Cloud OnBoard 大阪 名古屋
### その他たくさんのGoogle Cloud認定トレーニング講師
### 翔泳社主催 Codezine Academy
- https://event.shoeisha.jp/cza/20190927

### 受賞歴
* AUTHORIZED TRAINER OF THE YEAR'18

### 執筆歴

* [ネットメディアの記事](https://www.atmarkit.co.jp/ait/articles/1808/20/news024.html)
* Software Design 2019年9月号 GCP特集
* GCPの教科書II

## 各OSS/製品に対して業務レベルで取り組めること

### Kubernetes(GoogleKubernetesEngineを含む)
* Podを起動する各リソースのデプロイ
* 想定クエリ/リクエスト量に対する各コンテナへのresroucesの検証と設定
** これに伴うNodeのマシンタイプの設計
* taint, affinity, priorityを利用したPodの配置戦略
* PodSecurityPolicyの策定
* RBACの設定とGoogleアカウントとの連携
* Helmを用いたマニフェストファイル共通化の取り組み
* helmfileを用いたマニフェストファイルのマルチ環境化
* その他GKEにまつわるIAPやWorkroadIdentityの設定

### Istio
**もう忘れたので最新バージョンへの追従と思い出しが必要**
* virturalservice, gateway, destinationruleなど基本要素の理解とマニフェストファイルの作成
* circuit-breakerの動作検証
* NodePort ingressgatewayとGCPのHTTP負荷分散を用いたマルチリージョンへの展開

### Terraform
* localsを利用したマルチ環境への適用を考慮したコーディング
* terraform moduleを利用した定義ファイルの集約 (できますが、個人的には個々の案件に対してmoduleを開発する意義は限りなく薄いと考えています)

### Angular
* SOLID原則を意識した設計
* 単体テストのコーディング

## できないこと
* 複雑なSQLの記述
* 数学的知識を前提とした機械学習モデルへの理解
* Go言語を用いた開発
