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
| **7.5** | アプリは可能性のある例外をキャッチし処理している。 | ✓ | ✓ |
| **7.6** | セキュリティコントロールのエラー処理ロジックはデフォルトでアクセスを拒否している。 | ✓ | ✓ |
| **7.7** | アンマネージドコードでは、メモリは安全に割り当て、解放、使用されている。 | ✓ | ✓ |
| **7.8** | スタック保護、PIEサポート、自動参照カウントなどコンパイラにより提供されるセキュリティ機能が有効化されている。 | ✓ | ✓ |
| **7.9** | JavaバイトコードはMinifyされている。 | ✓ | ✓ |

## 参考情報

OWASP モバイルセキュリティテストガイドには、このセクションに記載されている要件を検証するための詳細な手順を提供しており、モバイルオペレーティングシステムによるベストプラクティスも同様に記されています。

(...TODO... link this to v1.0 instead of master once tagged).

- Android - https://github.com/OWASP/owasp-mstg/blob/master/Document/Testcases/0x01f_OMTG-CODE_Android.md
- iOS - https://github.com/OWASP/owasp-mstg/blob/master/Document/Testcases/0x01f_OMTG-CODE_iOS.md

詳しくは以下の情報を参照してください。

- OWASP Mobile Top 10:  M7 - クライアントコード品質
- CWE: https://cwe.mitre.org/data/definitions/119.html
- CWE: https://cwe.mitre.org/data/definitions/89.html
- CWE: https://cwe.mitre.org/data/definitions/388.html
- CWE: https://cwe.mitre.org/data/definitions/489.html

## 参考情報（日本語）

- CWE: http://jvndb.jvn.jp/ja/cwe/CWE-119.html
- CWE: http://jvndb.jvn.jp/ja/cwe/CWE-89.html
