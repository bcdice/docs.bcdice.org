# 集計ダイス <span style="font-size: 0.6em; font-weight: 500;">（3.5.0から）</span>

```
xTYy
xTZy
```

`y`面ダイスを`x`個ダイスロールして、それぞれの面が出た個数を集計して表示します。


## 実行例

```
[DiceBot]> 8TY6
(8TY6) ＞ 2,4,2,6,2,1,4,3 ＞ [1]×1, [2]×3, [3]×1, [4]×2, [6]×1
[DiceBot]> 8TZ6
(8TZ6) ＞ 6,5,6,5,1,5,6,1 ＞ [1]×2, [2]×0, [3]×0, [4]×0, [5]×3, [6]×3
```

出力 `[1]×1, [2]×3, [3]×1, [4]×2, [6]×1` はダイスロールの集計結果が、出目1が1個、出目2が3個、出目3が1個、出目4が2個、出目6が1個、であることを表します。

`TY`と`TZ`では同じ出目でも表示結果が変わります。`TY`では出現しなかった出目の表示が省略されます。`TZ`では出現した個数に関わらず、全ての面の個数が表示されます。

## 備考
- ダイスの面数`y`は20以下である必要があります。この制限は今後のアップデートで緩和される可能性があります。
- `TY` は集計を意味する英語 `tally` の略、`TZ` は `tally with zero` の略です。