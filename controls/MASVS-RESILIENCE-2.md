# MASVS-RESILIENCE-2

## コントロール

アプリは改竄防止メカニズムを実装しています。

## 説明

アプリはユーザーが制御するデバイス上で動作し、適切な保護がなければ改変版をローカルで実行したり (ゲームで不正行為をしたり、支払いなしでプレミアム機能を有効にするなど) 、バックドアをつけた版をサードパーティアプリストアにアップロードすることは比較的容易です。このコントロールではオリジナルのコードやリソースへの改変を防止することで、アプリの意図した機能の完全性を確保しようとするものです。