# MASVS-NETWORK: ネットワーク通信

セキュアネットワーキングはモバイルアプリセキュリティ、特にネットワーク上で通信するアプリにおいて、重要な側面です。転送中のデータの機密性と完全性を確保するために、開発者は一般的に TLS の使用などによるリモートエンドポイントの暗号化と認証に依存しています。しかし、開発者が誤ってプラットフォームの安全な既定値を無効にしたり、低レベル API やサードパーティライブラリを利用して完全にバイパスする方法が多数あります。

このカテゴリはモバイルアプリがいかなる状況でも安全な接続を設定することを確保するように設計されています。具体的には、アプリがネットワーク通信のために安全で暗号化されたチャネルを確立することを検証することに焦点をあてています。さらに、このカテゴリは開発者が特定の認証局 (CA) のみを信頼することを選択する可能性がある状況をカバーします。これは一般的に証明書ピン留めまたは公開鍵ピン留めと呼ばれます。
