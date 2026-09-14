# ROPPONGI SURVIVOR — スコアカード

ゲームのリザルトに出る QR の行き先。問い合わせ文字列だけ読んで、その場でスコア入りのカードを描く
1 枚の HTML（サーバも DB も無し）。

```
https://pincool-riki.github.io/rs/?v=1&sc=2128&kv=kv_c
```

| 名前 | 中身 |
|---|---|
| `v`  | 問い合わせ文字列の版（いま 1） |
| `sc` | スコア |
| `kv` | 下地（`kv_a`〜`kv_d`）。ゲームがランごとに引いた結果 |

元は TokyoSurvivor リポジトリの `Tools/sharepage/`。**版面はゲーム側と 1 対 1**なので、
片方を動かしたら両方直すこと。

© 2025 Initiate Games Inc. / Developed by PinCool, Inc.
