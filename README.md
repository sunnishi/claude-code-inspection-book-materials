# 『Claude Codeでつくる 製造業の画像検査システム』実行教材

著者：西城戸 亮  
副題：Python・OpenCVによる実装から、検証・現場導入・運用まで

## ダウンロード

[v1.0.0 の教材ZIPをダウンロード](https://github.com/sunnishi/claude-code-inspection-book-materials/releases/download/v1.0.0/claude_code_inspection_code.zip)

ブラウザーからログインせずに取得できます。書籍の2026年制作版に対応します。ZIPを展開すると `code` フォルダーがあります。`code/README.md` を開き、第3章の環境準備、第4章の初回実行へ進んでください。Releases画面では **claude_code_inspection_code.zip** を選びます。自動表示される Source code のZIPとは異なります。

## 内容と確認範囲

Pythonスクリプト、設定、7条件の合成画像、結果の記録例、ROI練習、帳票を収録しています。macOS / Python 3.10.19 / OpenCV 5.0.0.93 / NumPy 2.2.6で22項目とROI練習の検証を実施しました。

7条件の期待結果は OK 1、NG 2、REVIEW 3、ERROR 1です。`07_corrupt.png` は意図的に壊した教材ファイルです。この画像を含む一括検査の終了コード2は想定どおりです。Windows、実カメラ、PLC、長時間運転、実工場の検査精度は未検証です。教材は設備へ接続しないオフライン学習用です。

## 利用について

コードと帳票は本書の学習・社内検討・改変に利用できます。依存するライブラリの権利と条件は各権利者に帰属します。本書はAnthropic、OpenCV、Amazon等の公式出版物ではありません。書籍本文と表紙はこの配布には含まれません。
