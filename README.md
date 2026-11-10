# 『Claude Codeでつくる 製造業の画像検査システム』実行教材

著者：西城戸 亮  
副題：Python・OpenCVによる実装から、検証・現場導入・運用まで

## 書籍（Amazon）

この教材の本：[『Claude Codeでつくる 製造業の画像検査システム』](https://www.amazon.co.jp/dp/B0HKSG1LWF)（Kindle版・ペーパーバック、Kindle Unlimited対象）

著者の他の本（製造業の技術書）：

- [『現場で使える製造業の画像検査自動化 第2版』](https://www.amazon.co.jp/dp/B0HJYJNHS6)：Python／OpenCVで、照明・判定・検証まで
- [『ラズパイとPythonでつくる 製造業の画像検査』](https://www.amazon.co.jp/dp/B0HKSGDZF2)：カメラ接続からOK／NG判定、記録・運用まで
- [『図解で学ぶ PLCプログラミング入門』](https://www.amazon.co.jp/dp/B0HMPS4P4M)：ラダーの基本から搬送・位置決め・PID・通信まで
- [『Pythonで始める 製造DXの実践』](https://www.amazon.co.jp/dp/B0HL5RK5H9)：現場データの収集・見える化から異常検知まで

## ダウンロード

[v1.1.0 の教材ZIPをダウンロード](https://github.com/sunnishi/claude-code-inspection-book-materials/releases/download/v1.1.0/claude_code_inspection_code.zip)

ブラウザーからログインせずに取得できます。書籍の2026年制作版に対応します。ZIPを展開すると `code` フォルダーがあります。`code/README.md` を開き、第3章の環境準備、第4章の初回実行へ進んでください。Releases画面では **claude_code_inspection_code.zip** を選びます。自動表示される Source code のZIPとは異なります。

## 内容と確認範囲

Pythonスクリプト、設定、7条件の合成画像、結果の記録例、ROI練習、帳票を収録しています。v1.1.0では、実践編（第21〜28章）で使うlabsのスクリプト（mutation_check.py、verify_extra.py、stress_map.py、compare_prompts.py）と、導入確認票（templates/claude_code_rollout.md）を追加しました。macOS / Python 3.10.19 / OpenCV 5.0.0.93 / NumPy 2.2.6で22項目とROI練習の検証を実施しました。追加テスト（26項目）と、39件のバグを入れた検出試験は、macOS / Python 3.12 / OpenCV 5.0.0.93 / NumPy 2.2.6で確認しています。labs/compare_prompts.pyはclaude -pを実行するため、Claude Codeの利用枠や利用料を使います。

7条件の期待結果は OK 1、NG 2、REVIEW 3、ERROR 1です。`07_corrupt.png` は意図的に壊した教材ファイルです。この画像を含む一括検査の終了コード2は想定どおりです。Windows、実カメラ、PLC、長時間運転、実工場の検査精度は未検証です。教材は設備へ接続しないオフライン学習用です。

## 利用について

コードと帳票は本書の学習・社内検討・改変に利用できます。依存するライブラリの権利と条件は各権利者に帰属します。本書はAnthropic、OpenCV、Amazon等の公式出版物ではありません。書籍本文と表紙はこの配布には含まれません。
