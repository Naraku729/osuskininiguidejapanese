# osu! skin.ini 完全日本語リファレンス
# このファイルは Wiki の内容を忠実に日本語化したものです。

# ============================================================
# [General] - 全般設定
# ============================================================
[General]
Name: スキン名
Author: 制作者名
Version: スキンバージョン (1.0, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.7, または latest)

# --- アニメーション・表示 ---
AnimationFramerate: アニメーションの秒間フレーム数 (-1で全フレーム再生)
AllowSliderBallTint: スライダーの色をスライダーボールに反映させるか (0=No, 1=Yes)
ComboBurstRandom: コンボバースト画像をランダムに表示するか (0=No, 1=Yes)
CursorCentre: カーソルの中心を画像の真ん中にするか (0=左上, 1=中心)
CursorExpand: クリック時にカーソルを膨らませるか (0=No, 1=Yes)
CursorRotate: カーソルを常時回転させるか (0=No, 1=Yes)
CursorTrailRotate: カーソルトレールを常時回転させるか (0=No, 1=Yes)

# --- ヒットオブジェクト ---
HitCircleOverlayAboveNumber: 数字の上にオーバーレイを表示するか (1=数字を隠す)
LayeredHitSounds: ヒットノーマル音を常に重ねて鳴らすか (0=No, 1=Yes)
SliderBallFlip: 反転時にスライダーボールを左右反転させるか (0=No, 1=Yes)
SpinnerFadePlayfield: スピナー中に背景を暗くするか (0=No, 1=Yes)
SpinnerFrequencyModulate: スピンが続くほど音程を上げるか (0=No, 1=Yes)
SpinnerNoBlink: メーターの最高段を点滅させず表示し続けるか (0=No, 1=Yes)

# ============================================================
# [Colours] - 色設定 (RGB: 赤,緑,青 の順)
# ============================================================
[Colours]
# --- コンボ色 ---
Combo1: 255,192,0
Combo2: 0,202,0
Combo3: 18,124,255
Combo4: 242,24,57

# --- 特殊色 ---
InputOverlayText: 入力キー上の数字の色
MenuGlow: メインメニューのスペクトラムの色
SliderBall: スライダーボールの色 (Tintが無効な時)
SliderBorder: スライダーの縁の色
SliderTrackOverride: スライダー本体の色 (固定したい場合)
SongSelectActiveText: 選曲中のパネルの文字色
SongSelectInactiveText: 選曲していないパネルの文字色
SpinnerBackground: スピナー背景に加算される色
StarBreakAdditive: 休憩中の星(star2)の色

# ============================================================
# [Fonts] - フォント設定
# ============================================================
[Fonts]
HitCirclePrefix: ヒットサークル数字のファイル名接頭辞 (default)
HitCircleOverlap: 数字同士の重なり(ピクセル) ※負の値で隙間
ScorePrefix: スコア数字のファイル名接頭辞 (score)
ScoreOverlap: スコア数字の重なり
ComboPrefix: コンボ数字のファイル名接頭辞 (score)
ComboOverlap: コンボ数字の重なり

# ============================================================
# [CatchTheBeat] - キャッチ専用
# ============================================================
[CatchTheBeat]
HyperDash: ハイパーダッシュ時のキャッチャーの色
HyperDashFruit: ハイパーダッシュ果実の枠の色
HyperDashAfterImage: ハイパーダッシュ後の残像の色

# ============================================================
# [Mania] - マニア設定 (キー数ごとに記述)
# ============================================================
[Mania]
Keys: 4
ColumnStart: 左端の列の開始位置
ColumnWidth: 各列の幅 (例: 30,30,30,30)
ColumnSpacing: 列同士の隙間
ColumnLineWidth: 列の境界線の太さ
BarlineHeight: 小節線の太さ
HitPosition: 判定ラインの高さ (標準は402)
LightPosition: ステージライトの高さ (標準は413)
JudgementLine: 判定ラインを表示するか (0, 1)
SpecialStyle: 特殊スタイル (0=なし, 1=左端, 2=右端)
UpsideDown: アップスクロール(上判定)にするか (0=下, 1=上)
SeparateScore: 判定表示を各レーンで分けるか
NoteBodyStyle: ホールドノートの描画スタイル (0=伸ばす, 1=上から, 2=下から)

# --- マニアの色・画像 ---
Colour1: 1列目の背景色 (RGBa)
ColourLight1: 1列目のライティングの色 (RGB)
KeyImage0: 1列目のキー画像
NoteImage0: 1列目のノート画像
NoteImage0H: 1列目のホールドノート頭画像
NoteImage0L: 1列目のホールドノート体画像
NoteImage0T: 1列目のホールドノート尻画像
