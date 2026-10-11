# adaptive-monitoring

長時間の処理を監視・待機する際に、過剰な状況確認とログの再読み込みを抑える Codex スキルです。
状態が安定したら確認間隔を延ばし、完了・異常・判断が必要な変化に対応します。

導入：このリポジトリを `~/.codex/skills/adaptive-monitoring` に clone してください。
使い方：Codex に「`$adaptive-monitoring を使って、この処理を監視して`」と依頼します。
