# iPad単体運用アプリ

このフォルダには、iPadのSafariで使う単一HTMLアプリを置く。

## ファイル

- `index.html`
  - 人名タップで入退室記録
  - ローカル保存
  - 日次/月次集計
  - PMS006互換 `xlsx` 出力

## 使い方

1. `index.html` をSafariで開く
2. 設定で名前を入れる
3. `入室` または `退室` を選ぶ
4. 対象者のボタンをタップする
5. 月次画面から `xlsx` を出力する

## 現時点の前提

- 保存は `localStorage`
- 画面点灯中の手動運用
- オフライン動作

## 既存ESP32案との関係

`attendance_device` フォルダの成果物は残してあるが、現在の正本仕様は `attendance_ipad_only_spec.md` とこのフォルダのアプリ。
