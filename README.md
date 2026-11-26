# Monifactory 0.14.0 日本語化パック（非公式）

Monifactory 0.14.0 用の日本語化ファイル一式です。
クエストブック全体と、アイテム・ブロック・UI のうち日本語訳がなかったものを翻訳しています。
用語は [GTNH 日本語化パック](https://github.com/mimimizuki18/gtnh-ja-translations) と [GTL 日本語化パック](https://github.com/mimimizuki18/gtl-ja-translations) に揃えています（電気高炉、組立ライン、入力ハッチ／バス、粉砕した〜鉱石 など）。

## 対象バージョン

- Monifactory **0.14.0**（Minecraft 1.20.1 / Forge 47.4 / FTB Quests 2001.4.22）

## 内容

| 対象 | 内容 |
|---|---|
| クエストブック | 全15チャプターと、モード別（Normal / Hard / Expert）の Genesis チャプター（約3,000項目） |
| アイテム・UI | 165 の名前空間、約35,000キー（GTCEu、Monifactory 独自アイテム、Ender IO、Thermal、AE2 アドオン、Chipped、Chisels & Bits、Project Red、JourneyMap など） |

MOD にもともとある日本語訳は残したうえで、明らかな誤訳は修正しています（Mercury「水星」→「水銀」、Wolframite「黒鉛鉄鉱」→「鉄マンガン重石」、Quantum Flux「量子もつれ」→「量子フラックス」など）。

## 導入方法

1. ゲームを終了します。
2. **元のファイルをバックアップしておきます**（`minecraft/config/ftbquests` と `minecraft/config-overrides`）。
3. このリポジトリの `minecraft` フォルダを、インスタンスの `minecraft`（または `.minecraft`）フォルダに上書きコピーします。
   - `resourcepacks/Monifactory-Japanese` … アイテム・UI の翻訳（リソースパック）
   - `config/ftbquests/quests` … 日本語化したクエストブック
   - `config-overrides/*/ftbquests/quests/chapters/genesis.snbt` … モード切り替え用の Genesis チャプター
4. ゲームを起動し、言語を「日本語」にします。
5. 「オプション → リソースパック」で **Monifactory-Japanese** を有効にします（一番上に置いてください）。

## 注意

- この FTB Quests のバージョンはクエストの言語ファイルに対応していないため、**クエストファイルそのものを日本語版に置き換えます**。言語設定を英語にしてもクエストは日本語のままです。英語に戻したいときは、バックアップしたファイルを戻してください。
- Monifactory を更新するとクエストファイルが英語版に戻ります。また、別バージョンのクエストファイルを上書きすると、クエストの内容がずれるおそれがあります。必ず対象バージョンで使ってください。
- 装飾ブロック（Chipped など）の名前は直訳ぎみのものがあります。
- 誤訳や抜けを見つけたら Issue で教えてください。

## ライセンス

Monifactory は **LGPL-3.0** で配布されているため、そのクエストファイルを改変したものを含むこのパックも同じ **LGPL-3.0** で配布します（[LICENSE](LICENSE)）。
Monifactory と各 MOD の名称や原文の権利は、それぞれの作者に帰属します。

翻訳の作成には AI（Claude）を利用しています。
