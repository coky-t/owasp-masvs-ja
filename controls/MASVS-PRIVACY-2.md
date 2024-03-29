# MASVS-PRIVACY-2

## コントロール

アプリはユーザーの特定を防ぎます。

## 説明

ユーザーアイデンティティを保護することは極めて重要です。このコントロールでは、データ抽象化、匿名化、仮名化などのリンク解除技法を使用し、ユーザーの特定と追跡を防ぐことを重視しています。

このコントロールで扱うもう一つの重要な側面は、特定の目的で複雑な「フィンガープリントのような」シグナル (デバイス ID、IP アドレス、動作パターンなど) を採用する際に技術的障壁を確立することです。たとえば、不正検出のために使用されるフィンガープリントは分離すべきであり、アナリティクス SDK においてオーディエンス測定に再利用してはいけません。これにより、各データストリームがユーザーのプライバシーを危険にさらすことなく意図した機能を果たすことを確保します。
