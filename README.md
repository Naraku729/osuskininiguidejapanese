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
| InputOverlayText | RGB | キー入力オーバーレイの数字の色 |
| MenuGlow | RGB | メインメニューのスペクトラムの色 |
| SliderBall | RGB | スライダーボールの色 |
| SliderBorder | RGB | スライダーの縁の色 |
| SliderTrackOverride | RGB | スライダー本体の色を固定する |
| SongSelectActiveText | RGB | 選択中のパネル文字色 |
| SongSelectInactiveText | RGB | 非選択のパネル文字色 |

---

## [Fonts] - フォント設定

| コマンド | 値 | 説明 |
| :--- | :--- | :--- |
| HitCirclePrefix | Text | ヒットサークル数字の接頭辞 |
| HitCircleOverlap | Integer | 数字同士の重なり(px) |
| ScorePrefix | Text | スコア数字の接頭辞 |
| ScoreOverlap | Integer | スコア数字の重なり(px) |
| ComboPrefix | Text | コンボ数字の接頭辞 |
| ComboOverlap | Integer | コンボ数字の重なり(px) |

---

## [Mania] - マニア設定
キー数ごとにセクションを作成する必要があります。

### 配置・レイアウト
- **Keys**: 設定するキー数 (必須)
- **ColumnStart**: 左端列の開始位置
- **ColumnWidth**: 各列の幅 (カンマ区切り)
- **ColumnSpacing**: 列間の隙間
- **HitPosition**: 判定ラインの高さ
- **UpsideDown**: 1でアップスクロール(上判定)
- **JudgementLine**: 判定ラインの表示/非表示

### 画像指定 (#は0からの列番号)
- **KeyImage#**: 通常時のキー画像
- **KeyImage#D**: 押下時のキー画像
- **NoteImage#**: ノート画像
- **NoteImage#H**: ロングノート頭画像
- **NoteImage#L**: ロングノート体画像
- **NoteImage#T**: ロングノート尻画像

---

## [CatchTheBeat] - キャッチ設定

- **HyperDash**: ハイパーダッシュ時のキャッチャー色
- **HyperDashFruit**: ハイパーダッシュ果実の枠色
- **HyperDashAfterImage**: ハイパーダッシュ後の残像色
