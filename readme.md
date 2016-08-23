# 3DModelWorld

メタセコイアモデルを飾れる 3D World エディタ
![edit.gif](https://raw.githubusercontent.com/elzup/3dmodel-space-exe/master/readme-res/edit.gif)

## KeyBind

| Key      | Action                            |
| ---      | ---                               |
| Esc      | 終了                              |
| w,s,a,d  | 前後左右の移動(Ctrl で高速)       |
| Space    | ジャンプ(Ctrl で高速)             |
| ホイール | スロット選択                      |
| r        | リソースパック選択                |
| e        | 編集モード                        |
| c        | TPS視点切り替え(Shift + c で戻す) |
| Ctrl + z | 戻る                              |
| F6       | セーブ                            |
| F7       | ロード                            |


## 編集モード KeyBind
| Key          | Action                            |
| ---          | ---                               |
| w,s,a,d      | 前後左右の移動(Ctrl で高速)       |
| Shift + w, s | 拡大縮小       |
| Shift + a, d | 回転       |

EDIT操作後のオブジェクトは一時的に当たり判定がなくなってしまいます
SAVE＆LOAD時に当たり判定が反映されます


## モデルについて
/pack/object/パック番号/モデル番号.mqo
にいくつか作ったメタセコイアファイルを設置

## スロット画像について
/pack/object/パック番号/slot.pngに
一つのパック７個まで
スロット画像のサイズは任意ですが
40*40を順番に横に７個
280*40のサイズのPNG
マップ画像相対パス
