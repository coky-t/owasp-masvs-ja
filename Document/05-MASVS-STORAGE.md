# MASVS-STORAGE: ストレージ

モバイルアプリケーションは個人を特定できる情報 (PII) 、暗号マテリアル、シークレット、API キーなど、多くの場合、ローカルに保存する必要があるさまざまな機密データを扱います。この機密データはアプリの内部ストレージなどのプライベートな場所に保存されることもあれば、ユーザーやデバイスにインストールされた他のアプリがアクセスできるパブリックフォルダに保存されることもあります。しかし、一般的には特定の API や、バックアップやログなどのシステム機能を使用することの副作用として、機密データがパブリックにアクセス可能な場所に意図せず保存されたり公開されることもあります。

このカテゴリはアプリによって意図的に保存される機密データがターゲットの場所に関係なく適切に保護されていることを開発者が確認できるように設計されています。また、API やシステム機能の不適切な使用により発生する可能性がある意図しない漏洩も対象となります。
