# VRChat Picture Organizer

VRChatのスクリーンショットを撮影年月日別のフォルダに仕分けするアプリ

![image](https://user-images.githubusercontent.com/29051777/145747865-8be61d1d-17fc-42c8-bc66-6d3b7bc4517c.png)

## これはなに？

VRChat Picture Organizerは、
VRChat 2021.4.1(Build 1149)以降で撮影したVRカメラやスクリーンショットの画像を、
ファイル名の撮影年月日別のフォルダに仕分けするアプリです。

次の例のように仕分けされます。

```
./VRChat/2021-11
  VRChat_2880x1620_2021-11-14_22-31-57.884.png
  VRChat_2880x1620_2021-11-14_22-32-41.342.png
  VRChat_2880x1620_2021-11-14_22-33-30.948.png
  VRChat_2880x1620_2021-11-14_22-33-32.559.png
  VRChat_2880x1620_2021-11-14_23-27-07.475.png
  （略）
  VRChat_2880x1620_2021-11-15_22-16-21.436.png
  VRChat_2880x1620_2021-11-15_22-17-49.637.png
  VRChat_2880x1620_2021-11-15_22-17-54.821.png
  VRChat_2880x1620_2021-11-15_22-19-03.908.png
  VRChat_2880x1620_2021-11-15_22-21-41.524.png

↓

./VRChat/2021-11
├─2021-11-14
│      VRChat_2880x1620_2021-11-14_22-31-57.884.png
│      VRChat_2880x1620_2021-11-14_22-32-41.342.png
│      VRChat_2880x1620_2021-11-14_22-33-30.948.png
│      VRChat_2880x1620_2021-11-14_22-33-32.559.png
│      VRChat_2880x1620_2021-11-14_23-27-07.475.png
│      （略）
│
└─2021-11-15
       VRChat_2880x1620_2021-11-15_22-16-21.436.png
       VRChat_2880x1620_2021-11-15_22-17-49.637.png
       VRChat_2880x1620_2021-11-15_22-17-54.821.png
       VRChat_2880x1620_2021-11-15_22-19-03.908.png
       VRChat_2880x1620_2021-11-15_22-21-41.524.png
       （略）
```

## 対応OS

Windowsのみ対応しています。（そもそもVRChatはWindowsのみ対応）  
開発自体はWindows10で行っていますが、それ以外のWindowsでも動作は可能と思われます。

## ダウンロードリンク

[こちら](https://github.com/nano-nano/vrc_pictures_organizer/releases)からどうぞ

## 使い方

[Wiki](https://github.com/nano-nano/vrc_pictures_organizer/wiki)に記載しています。

## ライセンス

プログラム本体については [MIT License](https://github.com/tcnksm/tool/blob/master/LICENCE) です。

## 作者

Nano-Nano
[@nano2_aloerina](https://twitter.com/nano2_aloerina)

---

## 開発者向け情報

### 開発ツールのバージョン

- Yarn: v1.22.11
- node.js: v14.17.5
- npm: v6.14.14

- Electron Forge: v6.0.0-beta.61
- Electron: v15.3.1

### 各種コマンド

``` bash
# 依存関係のインストール
$ yarn install

# 開発用モードで起動
$ yarn start

# リリース用ビルド
$ yarn make
```
