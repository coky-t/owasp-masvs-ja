# 認証と認可 (MASVS-AUTH)

## 説明

多くの場合、リモートサービスへのユーザーログインはモバイルアプリアーキテクチャ全体の不可欠な要素です。ロジックの大半はエンドポイントで発生しますが、MASVS ではクライアント側と生体認証などの他のローカル認証メカニズムからも考慮すべきいくつかの基本的な要件を定義します。

## コントロール

| ID | 主文 |
|----|-----------|
| MASVS-AUTH-1 | アプリは安全な認証および認可のプロトコルを使用し、関連するベストプラクティスに従います。 |
| MASVS-AUTH-2 | アプリはプラットフォームのベストプラクティスに従ってローカル認証を安全に実行します。 |
| MASVS-AUTH-3 | アプリは追加の認証で機密性の高い操作を保護します。 |

## 参考情報

OWASP モバイルアプリケーションセキュリティテストガイドでは、このセクションに記載されている要件を検証するための詳細な手順を提供しています。

- General: Authentication and Session Management - <https://github.com/OWASP/owasp-mastg/blob/master/Document/0x04e-Testing-Authentication-and-Session-Management.md>
- Android: Testing Local Authentication - <https://github.com/OWASP/owasp-mastg/blob/master/Document/0x05f-Testing-Local-Authentication.md>
- iOS: Testing Local Authentication - <https://github.com/OWASP/owasp-mastg/blob/master/Document/0x06f-Testing-Local-Authentication.md>
