# Mirue

トラックパッドで気持ちよく操作できる、Mac 用の画像ビューワです。
画像は枠のない「浮いた 1 枚」として表示され、ピンチや回転に合わせてウィンドウごと大きさが変わります。無料です。

A trackpad-friendly image viewer for the Mac. Each image floats as a frameless sheet, and the window follows
as you pinch and rotate. Free. (The menus are in Japanese.)

## ダウンロード / Download

1. [最新のリリース](https://github.com/satoo3/Mirue-releases/releases/latest)から `Mirue-<バージョン>-mac.dmg` をダウンロードして開きます。
2. Mirue を「アプリケーション」フォルダへドラッグし、そこから開きます。

In English:

1. Download `Mirue-<version>-mac.dmg` from the [latest release](https://github.com/satoo3/Mirue-releases/releases/latest) and open it.
2. Drag Mirue to the Applications folder, then open it from there.

動作環境 / Requirements:

- macOS 12 Monterey 以降（Apple シリコン、Intel） / macOS 12 Monterey or later (Apple silicon and Intel)
- Developer ID で署名し、Apple の公証を受けています / Signed with Developer ID and notarized by Apple

## 操作 / Controls

| 操作 | 動き |
| --- | --- |
| 1 本指ドラッグ / 2 本指ドラッグ | ウィンドウを動かす（画面より大きいときは中の画像を動かす） |
| 2 本指ピンチ | 拡大縮小（ウィンドウも追従） |
| 2 本指回転 | 回転（90° 付近で吸着） |
| マウスホイール | 拡大縮小 |
| Shift + ホイール | 5° ずつ回転 |
| ダブルクリック | 回転と拡大をリセット |
| 右クリック（2 本指タップ） | メニュー |
| ← / → | 同じフォルダの前後の画像 |

そのほかの機能:

- タイトルバーを隠すモード
- アルファチャンネルのある画像や回転時の余白は、ウィンドウも透過（透明部分へのクリックは後ろのウィンドウに届きます）
- 開いたときに画面に合わせて最大化するか、画像のサイズを優先するかを選べます
- 画像の既定アプリを、形式を選んでまとめて Mirue に切り替え / 元に戻せます（「Mirue」メニュー）

## 対応形式 / Formats

PNG、JPEG、GIF、WebP、HEIC、AVIF、TIFF、BMP、ICO、ICNS、JPEG 2000、TGA、PSD、各社 RAW、SVG など、
macOS が読める画像全般。GIF・APNG・WebP のアニメーションも再生します。

## ライセンスと免責 / License and disclaimer

Mirue は無料でダウンロードして使えます。オープンソースではありません: © 2026 Ultrawarp, all rights reserved.
利用の条件と免責は [LICENSE.md](LICENSE.md) にあります。

Mirue is free to download and use. It is not open source: © 2026 Ultrawarp, all rights reserved.
The conditions of use, including the disclaimer of warranty, are in [LICENSE.md](LICENSE.md).

このリポジトリは配布専用で、ソースコードは含みません。
This repository is for distribution only and does not contain source code.
