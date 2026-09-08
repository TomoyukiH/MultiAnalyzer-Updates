# MultiAnalyzer Updates

MultiAnalyzer専用のSparkle更新フィードと配布物を管理します。

- アプリ本体とは別の更新専用リポジトリです。
- 更新ZIPはMultiAnalyzer専用EdDSA鍵で署名します。
- `appcast.xml`へ署名と公開URLの揃った更新だけを追加します。
- 公開後は外部取得したZIPのSHA-256とローカル成果物を照合します。
