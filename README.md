# Zabaglione

レトロPCのエミュレーター開発・Web移植を中心に、昔のコンピューターを今の環境で動かし、プログラムを書いて楽しむためのソフトウェアを制作しています。Unity向けの開発ツールやLooking Glass向けの非公式SDKも公開しています。

## レトロPCエミュレーター

| 機種 | プロジェクト | 概要 |
| --- | --- | --- |
| National JR-100 | [pyjr100emu](https://github.com/zabaglione/pyjr100emu) | ブラウザー／デスクトップで動くエミュレーター。BASIC・PROG形式、BEEP音、仮想キーボード、ゲームパッドに対応。 |
| National JR-200 | [jr200-web-emulator](https://github.com/zabaglione/jr200-web-emulator) | FIND氏のVJR-200を土台にした非公式Web移植。CJRカセットの読み書きやCJR・WAV変換に対応。 |
| National JR-800 | [jr800-web-emulator](https://github.com/zabaglione/jr800-web-emulator) | BASICの操作や機械語プログラムの調査に使うWebエミュレーターと機械語アプリ開発環境。開発中の実験版。 |
| SHARP MZ-2500 | [mz2500-web-emulator](https://github.com/zabaglione/mz2500-web-emulator) | C++／WebAssemblyによるブラウザーエミュレーター。D88ディスクイメージやCP/M Plusの起動に対応。 |

**ブラウザーで試す：** [JR-100](https://zabaglione.github.io/pyjr100emu/) · [JR-200](https://zabaglione.github.io/jr200-web-emulator/) · [JR-800](https://zabaglione.github.io/jr800-web-emulator/) · [MZ-2500](https://zabaglione.github.io/mz2500-web-emulator/)

ROMなどの必要データ、対応範囲、動作確認状況は各プロジェクトのREADMEを参照してください。移植元のあるプロジェクトでは、原作者・ライセンス・出典を各リポジトリに記載しています。

## Unity向けツール

| プロジェクト | 概要 |
| --- | --- |
| [PLATEAU Area Downloader](https://github.com/zabaglione/plateau-area-downloader) | 施設名や地図から範囲を選び、CityGMLと参照データを取得するUnity Editor用UPMパッケージ。取得データを公式PLATEAU SDK for Unityでインポートできます。 |
| [ViewWeave](https://github.com/zabaglione/ViewWeave) | Looking Glass向けの非公式Unity SDK。URP／HDRPシーンから多視点Quiltを生成し、プレビュー・キャプチャー・ディスプレイ出力を支援します。実験版として公開中。実機出力には公式Looking Glass Bridgeが必要です。 |

## 関連プロジェクト

- [JR100_openFPGA](https://github.com/zabaglione/JR100_openFPGA) — JR100_MiSTerを基にしたAnalogue Pocket／openFPGA向けJR-100コアの移植。
- [cpm-mz2500](https://github.com/zabaglione/cpm-mz2500) — MZ-2500向けCP/M関連プロジェクト。

## Links

[X / @z_zabaglione](https://x.com/z_zabaglione) · [LinkedIn](https://www.linkedin.com/in/yuichi-ishii-83357336/)
