# OWASP MASVS 2.0.0 ja (spreadsheet version)

This is draft for the Japanese translation of the [OWASP Mobile Application Security Verification Standard (MASVS) 2.0.0](https://docs.google.com/spreadsheets/d/1MZIvJ5Aze-zpyzLvQZVwyzF0bKWRPfnEd7nqFeH2PfA/edit?usp=sharing).

### Originator

- Document File - <https://docs.google.com/spreadsheets/d/1MZIvJ5Aze-zpyzLvQZVwyzF0bKWRPfnEd7nqFeH2PfA/edit?usp=sharing>

## OWASP モバイルアプリケーションセキュリティ検証標準 2.0.0 日本語版

### MASVS-STORAGE v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-STORAGE-1 | アプリは機密データを安全に保存します。 | アプリはユーザー、バックエンド、システムサービス、デバイス上の他のアプリなどの多くのソースからの機密データを扱い、通常はローカルに保存する必要があります。保存場所はアプリにとってプライベート (内部ストレージなど) の場合もあれば、パブリック (ダウンロードなどのパブリックフォルダなど) であるためユーザーや他の一緒にインストールされたアプリからアクセス可能な場合もあります。このコントロールによりアプリが意図的に保存する機密データはターゲットの場所とは関係なく適切に保護されます。 | MSTG-STORAGE-1, MSTG-STORAGE-2, MSTG-STORAGE-11, MSTG-STORAGE-14 |
| MASVS-STORAGE-2 | アプリは機密データの漏洩を防ぎます。 | 特定の API や、バックアップやログなどのシステム機能を使用する副作用として、機密データが意図せずに保存されたり、一般的にアクセスできる場所に公開されることがあります。このコントロールはこのような意図しない漏洩を対象とし、開発者は実際にそれを防ぐ方法を持っています。 | MSTG-STORAGE-3, MSTG-STORAGE-4, MSTG-STORAGE-5, MSTG-STORAGE-8 |

### MASVS-CRYPTO v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-CRYPTO-1 | アプリは最新の強力な暗号を採用し、業界のベストプラクティスに従ってそれを使用します。 | 暗号はユーザーのデータを保護する上で特に重要な役割を果たします。攻撃者がユーザーのデバイスに物理的にアクセスすることが想定されるモバイル環境ではなおさらです。このコントロールは一般的な暗号のベストプラクティスを対象にしています。これらは通常は外部の標準で定義されています。 | MSTG-CODE-1, MSTG-CRYPTO-1, MSTG-CRYPTO-2, MSTG-CRYPTO-3, MSTG-CRYPTO-4, MSTG-CRYPTO-6 |
| MASVS-CRYPTO-2 | アプリは業界のベストプラクティスに従って鍵管理を実行します。 | どんなに強力な暗号でも鍵管理が不十分であれば危険にさらされます。このコントロールは鍵の生成、保管、保護など、暗号鍵のライフサイクル全体にわたる管理を対象としています。 | MSTG-CRYPTO-1, MSTG-CRYPTO-5, MSTG-RESILIENCE-10, MSTG-STORAGE-1 |

### MASVS-AUTH v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-AUTH-1 | アプリは安全な認証および認可のプロトコルを使用し、関連するベストプラクティスに従います。 | リモートエンドポイントに接続するほとんどのアプリではユーザー認証が必要であり、なにかしらの認可も実施します。これらのメカニズムはリモートエンドポイントで実施する必要がありますが、アプリでも関連するすべてのベストプラクティスに従い、関連するプロトコルを安全に使用する必要があります。 | MSTG-AUTH-1, MSTG-AUTH-3, MSTG-AUTH-4, MSTG-AUTH-9 |
| MASVS-AUTH-2 | アプリはプラットフォームのベストプラクティスに従ってローカル認証を安全に実行します。 | 多くのアプリではユーザーは生体認証またはローカル PIN コードによる認証が可能です。これらの認証メカニズムは正しく実装する必要があります。さらに、アプリによってはリモートエンドポイントを持たず、ローカルアプリ認証に完全に依存していることがあります。 | MSTG-AUTH-1, MSTG-AUTH-8, MSTG-AUTH-8, MSTG-AUTH-12 |
| MASVS-AUTH-3 | アプリは追加の認証で機密性の高い操作を保護します。 | アプリ内の機密性の高いアクションにはなにかしらの追加の認証形式が望ましいことがよくあります。これはさまざまな方法 (生体認証、PIN、多要素認証コードジェネレータ、電子メール、ディープリンクなど) で実行可能であり、すべて安全に実装する必要がります。 | MSTG-AUTH-9, MSTG-AUTH-10 |

### MASVS-NETWORK v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-NETWORK-1 | アプリは最新のベストプラクティスに従ってすべてのネットワークトラフィックを保護します。 | 転送中のデータのプライバシーと完全性を確保することは、ネットワーク上で通信するあらゆるアプリにとって重要です。これはTLS が行うように、一般的にはデータを暗号化し、リモートエンドポイントを認証することで行われます。しかし、開発者がプラットフォームの安全な既定値を無効にしたり、低レベル API やサードパーティライブラリを使用して完全にバイパスする方法が多数あります。このコントロールではどのような状況でもアプリが実際に安全な接続を設定していることを確保します。 | MSTG-NETWORK-1, MSTG-NETWORK-2, MSTG-NETWORK-3, MSTG-NETWORK-6, MSTG-RESILIENCE-13 |
| MASVS-NETWORK-2 | アプリは開発者の管理下にあるすべてのリモートエンドポイントに対して ID ピン留めを実行します。 | フレームワークやデバイスのデフォルトルート CA をすべて信頼するのではなく、このコントロールでは非常に特定の CA のみを信頼するようにします。この方法は一般的に証明書ピン留めまたは SSL ピン留めと呼ばれます。 | MSTG-NETWORK-4 |

### MASVS-PLATFORM v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-PLATFORM-1 | アプリは IPC メカニズムを安全に使用します。 | | MSTG-PLATFORM-1, MSTG-PLATFORM-2, MSTG-PLATFORM-3, MSTG-PLATFORM-4, MSTG-STORAGE-6, MSTG-STORAGE-6 |
| MASVS-PLATFORM-2 | アプリは WebView を安全に使用します。 | | MSTG-PLATFORM-5, MSTG-PLATFORM-6, MSTG-PLATFORM-7, MSTG-PLATFORM-10 |
| MASVS-PLATFORM-3 | アプリはユーザーインターフェイスを安全に使用します。 | | MSTG-PLATFORM-2, MSTG-PLATFORM-9, MSTG-PLATFORM-11, MSTG-STORAGE-7, MSTG-STORAGE-9, MSTG-STORAGE-9 |

### MASVS-CODE v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-CODE-1 | アプリは最新バージョンのプラットフォームを要求します。 | | |
| MASVS-CODE-2 | アプリはアプリの更新を強制する仕組みがあります。 | | MSTG-ARCH-9 |
| MASVS-CODE-3 | アプリは既知の脆弱性のないソフトウェアコンポーネントのみを使用します。 | | MSTG-CODE-5 |
| MASVS-CODE-4 | アプリは信頼できないすべての入力を検証してサニタイズします。 | | MSTG-CODE-8, MSTG-CODE-9, MSTG-PLATFORM-8 |

### MASVS-RESILIENCE v2.0.0

| MASVS-ID | Control | Description | MASVS v1.5.0 Coverage |
| -------- | ------- | ----------- | --------------------- |
| MASVS-RESILIENCE-1 | アプリはプラットフォームの完全性を検証します。 | | MSTG-RESILIENCE-1, MSTG-RESILIENCE-5 |
| MASVS-RESILIENCE-2 | アプリは改竄防止メカニズムを実装しています。 | | MSTG-CODE-1, MSTG-RESILIENCE-3, MSTG-RESILIENCE-6 |
| MASVS-RESILIENCE-2 | アプリは静的解析防止メカニズムを実装しています。 | | MSTG-CODE-3, MSTG-CODE-4, MSTG-RESILIENCE-3, MSTG-RESILIENCE-9, MSTG-RESILIENCE-11, MSTG-RESILIENCE-12 |
| MASVS-RESILIENCE-2 | アプリは動的解析防止技法を実装しています。 | | MSTG-CODE-2, MSTG-CODE-4, MSTG-RESILIENCE-2, MSTG-RESILIENCE-4, MSTG-RESILIENCE-8 |

## License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

## Author (日本語訳)

[Koki Takeyama](https://github.com/coky-t)
