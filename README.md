# 🐱 Sleeping Cat for Windows

A peaceful desktop companion for Windows. The cat sleeps on your screen with a gently swaying tail.

macOS版は[こちら](https://github.com/daiokawa/SleepingCat)

![Sleeping Cat Icon](icon_original.png)

## ✨ Features

- 🌙 Adorable sleeping cat animation
- 🪶 Transparent window that floats on your desktop
- 🎯 Drag to move anywhere on screen
- 💤 Realistic tail movement animation
- 🖱️ Right-click to quit

## 📥 Download

最新版のインストーラーを[Releases](https://github.com/daiokawa/SleepingCat-Windows/releases)からダウンロードしてください。

## 🎮 Usage

1. インストーラーを実行してインストール
2. スタートメニューまたはデスクトップショートカットから起動
3. ドラッグで好きな位置に移動
4. 右クリックで終了

## 🛠 開発者向け

### 必要なもの
- Node.js 16以上
- Windows 10/11

### セットアップ
```bash
# リポジトリをクローン
git clone https://github.com/daiokawa/SleepingCat-Windows.git
cd SleepingCat-Windows

# 依存関係のインストール
npm install

# 開発モードで起動
npm start
```

### ビルド
```bash
# Windows用インストーラーの作成
npm run build-win
```

`dist`フォルダに`.exe`インストーラーが作成されます。

## 🖥 System Requirements

- Windows 10/11 (64-bit)
- 100MB以上の空き容量

## 📝 License

MIT License - See [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- Original concept from [SleepingCat for macOS](https://github.com/daiokawa/SleepingCat)
- Built with Electron
- Hand-drawn artwork

---

Made with ❤️ for cat lovers on Windows