# flutter-makeqr

「QRカウンター」を生成するシンプルなFlutterアプリケーションです。ボタンを押すごとに、QRコードにエンコードされたURLがインクリメントされます。

このプロジェクトは [デンソーウェーブのQRコード](https://www.denso-wave.com/ja/adcd/fundamental/2dcode/qrc/index.html) を利用しています。

## 機能

- **動的なQRコード生成:** 文字列に基づいてQRコードを表示します。
- **インタラクティブなカウンター:** フローティングアクションボタンを押すと、QRコードにエンコードされたURL内の数値がインクリメントされます。

## 前提条件

- Flutter SDK: `>=2.16.1 <3.0.0`

## はじめに

1.  **リポジトリのクローン:**
    ```bash
    git clone https://github.com/your-username/flutter-makeqr.git
    cd flutter-makeqr
    ```

2.  **依存関係のインストール:**
    ```bash
    flutter pub get
    ```

3.  **アプリケーションの実行:**
    ```bash
    flutter run
    ```

アプリケーションが起動すると、URL `https://fukuno.jig.jp/0` のQRコードが表示されます。フローティングアクションボタンを押すと、URL内の数値がインクリメントされます（例: `.../1`、`.../2` など）。

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
