# OWASP MASVS ja

This is the unofficial Japanese translation of the [OWASP Mobile Application Security Verification Standard (MASVS)](https://github.com/OWASP/masvs).

- Document Site - <https://coky-t.gitbook.io/owasp-masvs-ja/>
- Document Repository - <https://github.com/coky-t/owasp-masvs-ja>

### Originator

- MAS Official Site - <https://mas.owasp.org/>
- Project Site - <https://owasp.org/www-project-mobile-app-security/>
- Project Repository - <https://github.com/OWASP/www-project-mobile-app-security>
- Document Site - <https://mas.owasp.org/MASVS/>
- Document Repository - <https://github.com/OWASP/masvs>

## OWASP モバイルアプリケーションセキュリティ検証標準 v1 日本語版

* v1 - <https://github.com/coky-t/owasp-masvs-ja/tree/v1.5.0>

## OWASP モバイルアプリケーションセキュリティ検証標準 v2 日本語版

### はじめに

* [序文](Document/01-Foreword.md)
* [本標準について](Document/02-Frontispiece.md)
* [モバイルアプリケーションセキュリティ検証標準](Document/03-Using_the_MASVS.md)
* [監査と認定](Document/04-Assessment_and_Certification.md)
* [モバイルアプリケーションセキュリティモデル](Document/Mobile_App_Security_Model.md)

### MASVS-STORAGE: ストレージ

* [MASVS-STORAGE: ストレージ](Document/05-MASVS-STORAGE.md)
  * [MASVS-STORAGE-1](controls/MASVS-STORAGE-1.md) アプリは機密データを安全に保存します。
  * [MASVS-STORAGE-2](controls/MASVS-STORAGE-2.md) アプリは機密データの漏洩を防ぎます。

### MASVS-CRYPTO: 暗号

* [MASVS-CRYPTO: 暗号](Document/06-MASVS-CRYPTO.md)
  * [MASVS-CRYPTO-1](controls/MASVS-CRYPTO-1.md) アプリは最新の強力な暗号を採用し、業界のベストプラクティスに従ってそれを使用します。
  * [MASVS-CRYPTO-2](controls/MASVS-CRYPTO-2.md) アプリは業界のベストプラクティスに従って鍵管理を実行します。

### MASVS-AUTH: 認証と認可

* [MASVS-AUTH: 認証と認可](Document/07-MASVS-AUTH.md)
  * [MASVS-AUTH-1](controls/MASVS-AUTH-1.md) アプリは安全な認証および認可のプロトコルを使用し、関連するベストプラクティスに従います。
  * [MASVS-AUTH-2](controls/MASVS-AUTH-2.md) アプリはプラットフォームのベストプラクティスに従ってローカル認証を安全に実行します。
  * [MASVS-AUTH-3](controls/MASVS-AUTH-3.md) アプリは追加の認証で機密性の高い操作を保護します。

### MASVS-NETWORK: ネットワーク通信

* [MASVS-NETWORK: ネットワーク通信](Document/08-MASVS-NETWORK.md)
  * [MASVS-NETWORK-1](controls/MASVS-NETWORK-1.md) アプリは最新のベストプラクティスに従ってすべてのネットワークトラフィックを保護します。
  * [MASVS-NETWORK-2](controls/MASVS-NETWORK-2.md) アプリは開発者の管理下にあるすべてのリモートエンドポイントに対して ID ピン留めを実行します。

### MASVS-PLATFORM: プラットフォーム連携

* [MASVS-PLATFORM: プラットフォーム連携](Document/09-MASVS-PLATFORM.md)
  * [MASVS-PLATFORM-1](controls/MASVS-PLATFORM-1.md) アプリは IPC メカニズムを安全に使用します。
  * [MASVS-PLATFORM-2](controls/MASVS-PLATFORM-2.md) アプリは WebView を安全に使用します。
  * [MASVS-PLATFORM-3](controls/MASVS-PLATFORM-3.md) アプリはユーザーインターフェイスを安全に使用します。

### MASVS-CODE: コード品質

* [MASVS-CODE: コード品質](Document/10-MASVS-CODE.md)
  * [MASVS-CODE-1](controls/MASVS-CODE-1.md) アプリは最新バージョンのプラットフォームを要求します。
  * [MASVS-CODE-2](controls/MASVS-CODE-2.md) アプリはアプリの更新を強制する仕組みがあります。
  * [MASVS-CODE-3](controls/MASVS-CODE-3.md) アプリは既知の脆弱性のないソフトウェアコンポーネントのみを使用します。
  * [MASVS-CODE-4](controls/MASVS-CODE-4.md) アプリは信頼できないすべての入力を検証してサニタイズします。

### MASVS-RESILIENCE: リバースエンジニアリングと改竄に対する耐性

* [MASVS-RESILIENCE: リバースエンジニアリングと改竄に対する耐性](Document/11-MASVS-RESILIENCE.md)
  * [MASVS-RESILIENCE-1](controls/MASVS-RESILIENCE-1.md) アプリはプラットフォームの完全性を検証します。
  * [MASVS-RESILIENCE-2](controls/MASVS-RESILIENCE-2.md) アプリは改竄防止メカニズムを実装しています。
  * [MASVS-RESILIENCE-3](controls/MASVS-RESILIENCE-3.md) アプリは静的解析防止メカニズムを実装しています。
  * [MASVS-RESILIENCE-4](controls/MASVS-RESILIENCE-4.md) アプリは動的解析防止技法を実装しています。

### MASVS-PRIVACY: プライバシー

* [MASVS-PRIVACY: プライバシー](Document/12-MASVS-PRIVACY.md)
  * [MASVS-PRIVACY-1](controls/MASVS-PRIVACY-1.md) アプリは機密データやリソースへのアクセスを最小限に抑えます。
  * [MASVS-PRIVACY-2](controls/MASVS-PRIVACY-2.md) アプリはユーザーの特定を防ぎます。
  * [MASVS-PRIVACY-3](controls/MASVS-PRIVACY-3.md) アプリはデータの収集と使用について透明性があります。
  * [MASVS-PRIVACY-4](controls/MASVS-PRIVACY-4.md) アプリはユーザーが自分のデータを制御できます。

## License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

## Translator (Japanese)

[Koki Takeyama](https://github.com/coky-t)

- Document Site - <https://coky-t.gitbook.io/owasp-docs-ja/>
- Document Repository - <https://github.com/coky-t/owasp-docs-ja>
