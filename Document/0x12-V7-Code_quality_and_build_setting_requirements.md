# V7: コード品質とビルド設定要件

## 管理目標

アプリの開発で基本的なセキュリティコーディングプラクティスに従っており、コンパイラが提供する「フリー」のセキュリティ機能が有効になっていることを確認することがこのコントロールの目標です。

## セキュリティ検証要件

| # | 説明 | L1 | L2 |
| --- | --- | --- | --- |
| **7.1** | アプリは有効な証明書で署名およびプロビジョニングされている。 | ✓ | ✓ |
| **7.2** | アプリはリリースモードでビルドされている。リリースビルドに適した設定である。（非デバッグなど） | ✓ | ✓ |
| **7.3** | デバッグシンボルはネイティブバイナリから削除されている。 | ✓ | ✓ |
| **7.4** | デバッグコードは削除されており、アプリは詳細なエラーやデバッグメッセージを記録していない。 | ✓ | ✓ |
| **7.5** | モバイルアプリで使用されるライブラリ、フレームワークなどのすべてのサードパーティコンポーネントを把握し、既知の脆弱性を確認している。 | ✓ | ✓ |
| **7.6** | アプリは可能性のある例外をキャッチし処理している。 | ✓ | ✓ |
| **7.7** | セキュリティコントロールのエラー処理ロジックはデフォルトでアクセスを拒否している。 | ✓ | ✓ |
| **7.8** | アンマネージドコードでは、メモリは安全に割り当て、解放、使用されている。 | ✓ | ✓ |
| **7.9** | バイトコードの軽量化、スタック保護、PIEサポート、自動参照カウントなどツールチェーンにより提供されるフリーのセキュリティ機能が有効化されている。 | ✓ | ✓ |

## 参考情報

OWASP モバイルセキュリティテストガイドでは、このセクションに記載されている要件を検証するための詳細な手順を提供しています。

- Android - https://github.com/OWASP/owasp-mstg/blob/master/Document/0x05i-Testing-Code-Quality-and-Build-Settings.md
- iOS - https://github.com/OWASP/owasp-mstg/blob/master/Document/0x06i-Testing-Code-Quality-and-Build-Settings.md

詳しくは以下の情報を参照してください。

- OWASP Mobile Top 10:  M7 - Poor Code Quality: https://www.owasp.org/index.php/Mobile_Top_10_2016-M7-Poor_Code_Quality
- CWE: https://cwe.mitre.org/data/definitions/119.html
- CWE: https://cwe.mitre.org/data/definitions/89.html
- CWE: https://cwe.mitre.org/data/definitions/388.html
- CWE: https://cwe.mitre.org/data/definitions/489.html

## 参考情報（日本語）

- OWASP Mobile Top 10:  M7 - 脆弱なコード品質: https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M7-Poor_Code_Quality.html
- CWE: http://jvndb.jvn.jp/ja/cwe/CWE-119.html
- CWE: http://jvndb.jvn.jp/ja/cwe/CWE-89.html
