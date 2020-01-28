
# 参考情報

## V1: アーキテクチャ、設計、脅威モデリング要件

- OWASP Mobile Top 10 2016: M10 (余計な機能) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M10-Extraneous_Functionality.html>
- OWASP Security Architecture cheat sheet - <https://jpcertcc.github.io/OWASPdocuments/CheatSheets/ApplicationSecurityArchitecture.html>

- NIST SP 800-57 Part 1 Rev.4 - <https://www.ipa.go.jp/files/000055490.pdf>
- NIST SP 800-57 Part 3 Rev.1 - <https://www.ipa.go.jp/files/000055491.pdf>

## V2: データストレージとプライバシー要件

- OWASP Mobile Top 10 2016: M2 (安全でないデータストレージ) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M2-Insecure_Data_Storage.html>
<!-- - CWE 117 (Improper Output Neutralization for Logs) - <https://jvndb.jvn.jp/ja/cwe/CWE-117.html> -->
- CWE 200 (情報漏えい) - <https://jvndb.jvn.jp/ja/cwe/CWE-200.html>
- CWE 276 (不適切なデフォルトパーミッション) - <https://jvndb.jvn.jp/ja/cwe/CWE-276.html>
- CWE 311 (重要なデータの暗号化の欠如) - <https://jvndb.jvn.jp/ja/cwe/CWE-311.html>
- CWE 312 (重要な情報の平文保存) - <https://jvndb.jvn.jp/ja/cwe/CWE-312.html>
<!-- - CWE 316 (Cleartext Storage of Sensitive Information in Memory) - <https://jvndb.jvn.jp/ja/cwe/CWE-316.html> -->
<!-- - CWE 359 (Exposure of Private Information ('Privacy Violation')) - <https://jvndb.jvn.jp/ja/cwe/CWE-359.html> -->
- CWE 522 (認証情報の不十分な保護) - <https://jvndb.jvn.jp/ja/cwe/CWE-522.html>
<!-- - CWE 524 (Information Exposure Through Caching) - <https://jvndb.jvn.jp/ja/cwe/CWE-524.html> -->
<!-- - CWE 530 (Exposure of Backup File to an Unauthorized Control Sphere) - <https://jvndb.jvn.jp/ja/cwe/CWE-530.html> -->
- CWE 532 (ログファイルからの情報漏えい) - <https://jvndb.jvn.jp/ja/cwe/CWE-532.html>
- CWE 534 (デバッグログファイルからの情報漏えい) - <https://jvndb.jvn.jp/ja/cwe/CWE-534.html>
<!-- - CWE 634 (Weaknesses that Affect System Processes) - <https://jvndb.jvn.jp/ja/cwe/CWE-634.html> -->
- CWE 798 (ハードコードされた認証情報の使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-798.html>
<!-- - CWE 921 (Storage of Sensitive Data in a Mechanism without Access Control) - <https://jvndb.jvn.jp/ja/cwe/CWE-921.html> -->
- CWE 922 (重要な情報のセキュアでない格納) - <https://jvndb.jvn.jp/ja/cwe/CWE-922.html>

## V3: 暗号化要件

- OWASP Mobile Top 10 2016: M5 (不十分な暗号化) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M5-Insufficient_Cryptography.html>
- CWE 310 (暗号の問題) - <http://jvndb.jvn.jp/ja/cwe/CWE-310.html>
- CWE 321 (ハードコードされた暗号鍵の使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-321.html>
- CWE 326 (不適切な暗号強度) - <https://jvndb.jvn.jp/ja/cwe/CWE-326.html>
- CWE 327 (不完全、または危険な暗号アルゴリズムの使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-327.html>
- CWE 329 (BC モードにおけるランダムな初期化ベクトルの不使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-329.html>
- CWE 330 (不十分なランダム値の使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-330.html>
<!-- - CWE 337 (Predictable Seed in PRNG) - <https://jvndb.jvn.jp/ja/cwe/CWE-337.html> -->
- CWE 338 (暗号における脆弱な PRNG の使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-338.html>

- CRYPTREC - <https://www.cryptrec.go.jp/>

## V4: 認証とセッション管理要件

- OWASP Mobile Top 10 2016: M4 (安全でない認証) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M4-Insecure_Authentication.html>
- OWASP Mobile Top 10 2016: M6 (安全でない認可) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M6-Insecure_Authorization.html>
- CWE 287 (不適切な認証) - <http://jvndb.jvn.jp/ja/cwe/CWE-287.html>
- CWE 307 (過度な認証試行の不適切な制限) - <https://jvndb.jvn.jp/ja/cwe/CWE-307.html>
<!-- - CWE 308 (Use of Single-factor Authentication) - <https://jvndb.jvn.jp/ja/cwe/CWE-308.html> -->
- CWE 521 (脆弱なパスワードの要求) - <https://jvndb.jvn.jp/ja/cwe/CWE-521.html>
<!-- - CWE 604 (Use of Client-Side Authentication) - <https://jvndb.jvn.jp/ja/cwe/CWE-604.html> -->
- CWE 613 (不適切なセッション期限) - <https://jvndb.jvn.jp/ja/cwe/CWE-613.html>

## V5: ネットワーク通信要件

- OWASP Mobile Top 10 2016: M3 (安全でない通信) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M3-Insecure_Communication.html>
- CWE 295 (不正な証明書検証) - <https://jvndb.jvn.jp/ja/cwe/CWE-295.html>
<!-- - CWE 296 (Improper Following of a Certificate's Chain of Trust) - <https://jvndb.jvn.jp/ja/cwe/CWE-296.html> -->
- CWE 297 (ホストの不一致による証明書の不適切な検証) - <https://jvndb.jvn.jp/ja/cwe/CWE-297.html>
<!-- - CWE 298 (Improper Validation of Certificate Expiration) - <https://jvndb.jvn.jp/ja/cwe/CWE-298.html> -->
<!-- - CWE 308 (Use of Single-factor Authentication) - <https://jvndb.jvn.jp/ja/cwe/CWE-308.html> -->
- CWE 319 (重要な情報の平文での送信) - <https://jvndb.jvn.jp/ja/cwe/CWE-319.html>
- CWE 326 (不適切な暗号強度) - <https://jvndb.jvn.jp/ja/cwe/CWE-326.html>
- CWE 327 (不完全、または危険な暗号アルゴリズムの使用) - <https://jvndb.jvn.jp/ja/cwe/CWE-327.html>
<!-- - CWE 780 (Use of RSA Algorithm without OAEP) - <https://jvndb.jvn.jp/ja/cwe/CWE-780.html> -->
<!-- - CWE 940 (Improper Verification of Source of a Communication Channel) - <https://jvndb.jvn.jp/ja/cwe/CWE-940.html> -->
<!-- - CWE 941 (Incorrectly Specified Destination in a Communication Channel) - <https://jvndb.jvn.jp/ja/cwe/CWE-941.html> -->

## V6: プラットフォーム連携要件

- OWASP Mobile Top 10 2016: M1 (不適切なプラットフォームの利用) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M1-Improper_Platform_Usage.html>
- OWASP Mobile Top 10 2016: M7 (脆弱なコード品質) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M7-Poor_Code_Quality.html>
- CWE 20 (不適切な入力確認) - <http://jvndb.jvn.jp/ja/cwe/CWE-20.html>
- CWE 79 (クロスサイトスクリプティング) - <https://jvndb.jvn.jp/ja/cwe/CWE-79.html>
- CWE 200 (情報漏えい) - <https://jvndb.jvn.jp/ja/cwe/CWE-200.html>
<!-- - CWE 250 (Execution with Unnecessary Privileges) - <https://jvndb.jvn.jp/ja/cwe/CWE-250.html> -->
- CWE 672 (有効期限後または解放後のリソースの操作) - <https://jvndb.jvn.jp/ja/cwe/CWE-672.html>
- CWE 749 (危険なメソッドや機能の公開) - <https://jvndb.jvn.jp/ja/cwe/CWE-749.html>
- CWE 772 (有効なライフタイム後のリソースの解放の欠如) - <https://jvndb.jvn.jp/ja/cwe/CWE-772.html>
<!-- - CWE 920 (Improper Restriction of Power Consumption) - <https://jvndb.jvn.jp/ja/cwe/CWE-920.html> -->
<!-- - CWE 925 (Improper Verification of Intent by Broadcast Receiver) - <https://jvndb.jvn.jp/ja/cwe/CWE-925.html> -->
<!-- - CWE 926 (Improper Export of Android Application Components) - <https://jvndb.jvn.jp/ja/cwe/CWE-926.html> -->
<!-- - CWE 927 (Use of Implicit Intent for Sensitive Communication) - <https://jvndb.jvn.jp/ja/cwe/CWE-927.html> -->
<!-- - CWE 939 (Improper Authorization in Handler for Custom URL Scheme) - <https://jvndb.jvn.jp/ja/cwe/CWE-939.html> -->

## V7: コード品質とビルド設定要件

- OWASP Mobile Top 10 2016: M7 (脆弱なコード品質) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M7-Poor_Code_Quality.html>
- CWE 20 (不適切な入力確認) - <http://jvndb.jvn.jp/ja/cwe/CWE-20.html>
- CWE 89 (SQLインジェクション) - <http://jvndb.jvn.jp/ja/cwe/CWE-89.html>
<!-- - CWE 95 (Improper Neutralization of Directives in Dynamically Evaluated Code ('Eval Injection')) - <http://jvndb.jvn.jp/ja/cwe/CWE-95.html> -->
- CWE 119 (バッファエラー) - <http://jvndb.jvn.jp/ja/cwe/CWE-119.html>
<!-- - CWE 215 (Information Exposure through Debug Information) - <http://jvndb.jvn.jp/ja/cwe/CWE-215.html> -->
- CWE 388 (エラー処理) - <http://jvndb.jvn.jp/ja/cwe/CWE-388.html>
<!-- - CWE 489 (Leftover Debug Code) - <http://jvndb.jvn.jp/ja/cwe/CWE-489.html> -->
- CWE 502 (信頼性のないデータのデシリアライゼーション) - <http://jvndb.jvn.jp/ja/cwe/CWE-502.html>
<!-- - CWE 511 (Logic/Time Bomb) - <http://jvndb.jvn.jp/ja/cwe/CWE-511.html> -->
<!-- - CWE 656 (Reliance on Security through Obscurity) - <http://jvndb.jvn.jp/ja/cwe/CWE-656.html> -->
<!-- - CWE 676 (Use of Potentially Dangerous Function)  - <http://jvndb.jvn.jp/ja/cwe/CWE-676.html> -->
<!-- - CWE 937 (OWASP Top Ten 2013 Category A9 - Using Components with Known Vulnerabilities) - <http://jvndb.jvn.jp/ja/cwe/CWE-937.html> -->

## V8: 耐性要件

- OWASP Mobile Top 10 2016: M8 (コード改竄) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M8-Code_Tampering.html>
- OWASP Mobile Top 10 2016: M9 (リバースエンジニアリング) - <https://coky-t.github.io/owasp-mobile-top10-2016-ja/Mobile_Top_10_2016-M9-Reverse_Engineering.html>

- OWASP Reverse Engineering and Code Modification Prevention - <https://www.owasp.org/index.php/%E3%83%AA%E3%83%90%E3%83%BC%E3%82%B9_%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%83%AA%E3%83%B3%E3%82%B0%E3%82%84%E4%B8%8D%E6%AD%A3%E3%81%AA%E3%82%B3%E3%83%BC%E3%83%89%E5%A4%89%E6%9B%B4%E3%81%AE%E6%8A%80%E8%A1%93%E7%9A%84%E3%83%AA%E3%82%B9%E3%82%AF>

# 付録 B: 参考情報

- OWASP Reverse Engineering and Code Modification Prevention - <https://www.owasp.org/index.php/%E3%83%AA%E3%83%90%E3%83%BC%E3%82%B9_%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%83%AA%E3%83%B3%E3%82%B0%E3%82%84%E4%B8%8D%E6%AD%A3%E3%81%AA%E3%82%B3%E3%83%BC%E3%83%89%E5%A4%89%E6%9B%B4%E3%81%AE%E6%8A%80%E8%A1%93%E7%9A%84%E3%83%AA%E3%82%B9%E3%82%AF>

- PCI Security Standards Council - <https://ja.pcisecuritystandards.org/minisite/en/>
- PCI Data Security Standard (DSS) v3.0 Requirements and Security Assessment Procedures - <https://ja.pcisecuritystandards.org/_onelink_/pcisecurity/en2ja/minisite/en/docs/PCI_DSS_v3.pdf>
