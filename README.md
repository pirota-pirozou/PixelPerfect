# ピクセルパーフェクト ドット絵変換ツール

## 概要
このツールは、おもにAIで出力されたドット絵のような画像をピクセルパーフェクトなドット絵に変換するWebアプリケーションです。バニラJavaScriptで実装されており、ブラウザ上で動作します。

## 主な機能
- 画像ファイルのアップロード
- デモ画像の自動生成
- ブロックサイズの自動推定
- ピクセルパーフェクトなドット絵への変換
- 変換後の画像のダウンロード

## 技術的な特徴
- バニラJavaScriptのみで実装（フレームワーク不使用）
- Canvas APIを使用した画像処理
- レスポンシブデザイン対応
- モダンなUI/UXデザイン

## 使用方法
1. 画像ファイルをアップロードするか、「デモ画像を生成」ボタンをクリック
2. 「変換」ボタンをクリックして画像を変換
3. 自動的にブロックサイズが推定され、ドット絵に変換
4. 「ダウンロード」ボタンで変換後の画像を保存

## 技術仕様
- 画像処理アルゴリズム
  - ブロックサイズの自動推定機能
  - 最頻値を使用した代表色の決定
  - ピクセルパーフェクトな変換処理

## 対応ブラウザ
- モダンブラウザ（Chrome, Firefox, Safari, Edge等）

## ライセンス
このプロジェクトは0BSDライセンスの下で公開されています。

```
BSD Zero Clause License

Copyright (c) 2024 PixelPerfect

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.
```

## 作成者
このプロジェクトは Claude 3.7 Sonnet によって作成されました。人間側の著作権は主張しません。