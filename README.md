# skin.ini Reference for osu! (Japanese)

osu!のスキン設定ファイル `skin.ini` の各パラメータに関する日本語リファレンスです。

## 基本仕様
- **ケースセンシティブ**: 大文字・小文字を正確に記述してください。
- **真偽値**: `0` は無効、`1` は有効を意味します。
- **数値**:
  - Number: 整数または小数
  - Integer: 整数のみ
  - Positive Integer: 正の整数のみ
- **色指定**:
  - RGB: `R, G, B`
  - RGB(a): `R, G, B, a` (aは不透明度 0-255)

---

## [General] - 全般設定

| コマンド | 値 | 説明 |
| :--- | :--- | :--- |
| Name | Text | スキン名 |
| Author | Text | 制作者名 |
| Version | Number / latest | スキンバージョン (1.0, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.7, latest) |
| AnimationFramerate | Integer | 秒間のフレーム数。-1で全フレーム再生 |
| AllowSliderBallTint | 0 / 1 | コンボ色をスライダーボールに反映させるか |
| CursorCentre | 0 / 1 | カーソルの中心を画像の中心にするか |
| CursorExpand | 0 / 1 | クリック時にカーソルを拡大するか |
| CursorRotate | 0 / 1 | カーソルを常時回転させるか |
| HitCircleOverlayAboveNumber | 0 / 1 | 数字の上にオーバーレイを表示するか |
| SliderBallFlip | 0 / 1 | スライダー反転時にボールを水平反転させるか |

---

## [Colours] - 色設定
※ヘッダーは `[Colours]` と記述（Colorsは不可）

| コマンド | 値 | 説明 |
| :--- | :--- | :--- |
| Combo1 ~ 8 | RGB | 各コンボの色 |
| Input
