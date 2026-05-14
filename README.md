# flutter-makeqr

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple Flutter application that generates a "QR Counter". The QR code's encoded URL increments with each button press.

This project uses [QR-Code by DENSO WAVE](https://www.denso-wave.com/ja/adcd/fundamental/2dcode/qrc/index.html).

## Features

- **Dynamic QR Code Generation:** Displays a QR code based on a string.
- **Interactive Counter:** A floating action button increments a number within the QR code's encoded URL.

## Prerequisites

- Flutter SDK: `>=2.16.1 <3.0.0`

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/flutter-makeqr.git
    cd flutter-makeqr
    ```

2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Run the application:**
    ```bash
    flutter run
    ```

The application will launch and display a QR code for the URL `https://fukuno.jig.jp/0`. Press the floating action button to increment the number in the URL (e.g., to `.../1`, `.../2`, and so on).

## License

MIT License — see [LICENSE](LICENSE).