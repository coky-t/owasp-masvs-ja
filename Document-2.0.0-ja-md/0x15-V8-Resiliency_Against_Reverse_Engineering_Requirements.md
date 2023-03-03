# リバースエンジニアリングと改竄に対する耐性 (MASVS-RESILIENCE)

## 説明

このカテゴリでは、機密データや機能を処理したりアクセスを与えたりするアプリに推奨される多層防御施策を取り扱います。これらのコントロールのいずれかが欠如しても脆弱性を引き起こすことはありません。代わりに、リバースエンジニアリングや特定のクライアントサイド攻撃に対する耐性を高めることを意図しています。これらのコントロールは他の MASVS セキュリティ要件を満たしているアプリに、特定の脅威モデルに応じて脅威に特化した追加の保護コントロールを追加します。

## コントロール

| ID | 主文 |
|----|-----------|
| MASVS-RESILIENCE-1 | アプリはプラットフォームの完全性を検証します。 |
| MASVS-RESILIENCE-2 | アプリは改竄防止メカニズムを実装しています。 |
| MASVS-RESILIENCE-3 | アプリは静的解析防止メカニズムを実装しています。 |
| MASVS-RESILIENCE-4 | アプリは動的解析防止技法を実装しています。 |

## 参考情報

OWASP モバイルアプリケーションセキュリティテストガイドでは、このセクションに記載されている要件を検証するための詳細な手順を提供しています。

- Android: Testing Resiliency Against Reverse Engineering - <https://github.com/OWASP/owasp-mastg/blob/master/Document/0x05j-Testing-Resiliency-Against-Reverse-Engineering.md>
- iOS: Testing Resiliency Against Reverse Engineering - <https://github.com/OWASP/owasp-mastg/blob/master/Document/0x06j-Testing-Resiliency-Against-Reverse-Engineering.md>
