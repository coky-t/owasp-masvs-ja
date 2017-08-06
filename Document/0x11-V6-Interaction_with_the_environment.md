# V6: プラットフォーム相互作用要件

## 管理目標

アプリが安全な方法でプラットフォームAPIや標準コンポーネントを使用していることをこのグループのコントロールは確認します。また、コントロールはアプリ間通信(IPC)も扱います。

## セキュリティ検証要件

| # | 説明 | L1 | L2 |
| --- | --- | --- | --- |
| **6.1** | アプリは必要となる最低限の権限のみを要求している。 | ✓ | ✓ |
| **6.2** | 外部ソースおよびユーザーからの入力がすべて検証されており、必要に応じてサニタイズされている。これにはUI、インテントやカスタムURLなどのIPCメカニズム、ネットワークソースを介して受信したデータを含んでいる。 | ✓ | ✓ |
| **6.3** | アプリはメカニズムが適切に保護されていない限り、カスタムURLスキームを介して機密な機能をエクスポートしていない。 | ✓ | ✓ |
| **6.4** | アプリはメカニズムが適切に保護されていない限り、IPC機構を通じて機密な機能をエクスポートしていない。 | ✓ | ✓ |
| **6.5** | 明示的に必要でない限りWebViewでJavaScriptが無効にされている。 | ✓ | ✓ |
| **6.6** | WebViewは最低限必要なプロトコルハンドラのセットのみを許可するよう構成されている（理想的には、httpsのみがサポートされている）。file, tel, app-id などの潜在的に危険なハンドラは無効にされている。 | ✓ | ✓ |
| **6.7** | アプリのネイティブメソッドがWebViewに公開されている場合、WebViewはアプリパッケージ内に含まれるJavaScriptのみをレンダリングしている。 | ✓ | ✓ |
| **6.8** | オブジェクトシリアライズ化は安全なシリアライズ化APIを使用して実装されている。 | ✓ | ✓ |

## 参考情報

OWASP モバイルセキュリティテストガイドでは、このセクションに記載されている要件を検証するための詳細な手順を提供しています。

- Android - https://github.com/OWASP/owasp-mstg/blob/master/Document/0x05h-Testing-Platform-Interaction.md
- iOS - https://github.com/OWASP/owasp-mstg/blob/master/Document/0x06h-Testing-Platform-Interaction.md

詳しくは以下の情報を参照してください。

- OWASP Mobile Top 10: M1 - Improper Platform Usage: https://www.owasp.org/index.php/Mobile_Top_10_2016-M1-Improper_Platform_Usage
- CWE: https://cwe.mitre.org/data/definitions/20.html
- CWE: https://cwe.mitre.org/data/definitions/749.html

## 参考情報（日本語）

- OWASP Mobile Top 10: M1 - 不適切なプラットフォームの利用: https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M1-Improper_Platform_Usage.html
- CWE: http://jvndb.jvn.jp/ja/cwe/CWE-20.html
