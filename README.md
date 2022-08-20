<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=YukiTominaga&show_icons=true&theme=radical&count_private=true" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YukiTominaga&show_icons=true&theme=radical" />
</a>

# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|富永 裕貴 (Yuki Tominaga)|

## 資格
- Google Certified Professional Cloud Architect **(2017/12 ~ 2021/12)**
- Google Certified Professional Data Engineer   **(2018/01 ~ 2022/1)**
- Google Certified Professional Cloud Developer **(2019/01 ~ 2021/1)**
- Google Certified Associate Cloud Engineer     **(2018/08 ~ 2020/8)**
- Google Certified Security Engineer            **(2019/01 ~ 2021/1)**
- Google Certified Professional DevOps Engineer **(2019/01 ~ 2021/1)**
- Certified Kubernetes Application Developer    **(2019/03 ~)**
- Certified Kubernetes Administrator            **(2019/12 ~)**
- Google Cloud Authorized Trainer               **(2018/05 ~)**

## スキル
### プログラミング言語

- TypeScript/JavaScript(他人のコードをレビューできる)
- Go(書き捨てのコードで使う)
- Java(主にApache Beamで使用した程度)
- Python(やりたくない)
- PHP(やりたくない)
- Rust(競技プログラミングで遊んだことしかない)

### その他

- Angular
- Google Cloud Platform
- Kubernetes
- Istio
- Helm
- Docker

## 言語

- 日本語
  - ネイティブ
- 英語
  - 英語の技術本にほとんど抵抗が無いレベルの読解

## 強み

- GCPへの深い知識
- パブリッククラウド技術の追い方
- 人前で話すのが超得意
- FFXIV 8000時間以上プレイ
- 習得すべきことに対して `空き時間の全てを費やす` という姿勢
- 技術レベルの多様性を認めること

## やったことはないが興味があるもの

- エンジニア組織の形成

## 職務経歴

### 2020/04 - 現在 : 株式会社スクウェア・エニックス 情報システム部 Global Infrastructure for Online Gaming

職務: 大規模オンラインゲーム及び関連サイトのインフラエンジニア

### 2017/11 - 2020/03 : クラウドエース株式会社

職務: Lead Engineer

#### Cloud Speech to Textを用いた日報の音声入力

- NodeJS
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

#### Google Cloud Platform 認定トレーナー業務

- [Architecting](https://www.coursera.org/specializations/gcp-architecture)
- [Data Engineering](https://www.coursera.org/programs/google-cloud-authorized-trainer-program-ngnti?collectionId=FTUIQ&productId=D6Ap6_7hEeaRogry0hUlXg&productType=s12n&showMiniModal=true)
- [Kubernetes](https://www.coursera.org/learn/google-kubernetes-engine)

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

### 社内ブログ記事
https://apps-gcp.com/author/tominaga/

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
* NodePort ingressgatewayとGCPのHTTP負荷分散を用いたマルチリージョンへの展開(動作検証中)

### Terraform
* localsを利用したマルチ環境への適用を考慮したコーディング
* terraform moduleを利用した定義ファイルの集約

### Angular
* SOLID原則を意識した設計
* 単体テストのコーディング

## できそうに見られるけどできないこと
* 複雑なSQLの記述
* windowsでの開発

## その他
GCPのトレーニングでは、ArchitectとData Engineeringの両方を務めているので、GCP内のほぼ全ての製品に対して基礎は確実に抑えています。
実務レベルで使ったことの無い主なサービスは、`Dataproc`, `Cloud Router`, `Bigtable`, `Spanner`, `各種相互接続`, `IoT Core`, `最近出てきたAutoML`です。
