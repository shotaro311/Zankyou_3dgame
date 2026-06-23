# Zankyou 3D Game

深夜の音楽スタジオを舞台にした、Three.js製の3D脱出ゲームです。

## Play

- GitHub Pages: https://shotaro311.github.io/Zankyou_3dgame/
- Local: `index.html`をブラウザで開く

## Overview

プレイヤーはドラム練習のために地下二階の音楽スタジオへ向かいます。停電後、非常灯だけが戻った密室で、音と機材を手掛かりに脱出を目指します。

## Controls

- `W / A / S / D`: 移動
- `Mouse`: 視点操作
- `Click`: 調べる・使う
- `1`: 調べる
- `2-9`: アイテム選択
- `0 / Q`: 手ぶら
- `H`: ヒント
- `R`: 視点を戻す
- `Esc`: マウス解除

## Technical Notes

- 単体の`index.html`で動作します。
- Three.js本体はHTML内に含めています。
- ビルド手順やサーバー処理はありません。

## Verification

公開前に以下を確認します。

- `index.html`のJavaScript構文チェック
- ブラウザでの開始画面、導入シナリオ、本編開始の表示確認
- GitHub Pagesの公開URLでの表示確認
