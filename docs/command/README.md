# 汎用コマンド

BCDiceのコマンドを大まかに分類すると、どのゲームシステムでも使える**汎用コマンド**と、特定のゲームシステムの処理に特化した**専用コマンド**の2種類に分けられます。

ここではどのゲームシステムを選択しても使える**汎用コマンド**を解説していきます。**専用コマンド**の説明は、各ゲームシステムのヘルプメッセージをご覧ください。

## コマンド一覧

| コマンド名 | 例 |
| :----- | :----- |
| [加算ダイス](/command/add_dice.md) | `2D6+1>=7`, `5D6KH3` |
| [バラバラダイス](/command/barabara_dice.md) | `5B6` |
| [個数振り足しダイス](/command/reroll_dice.md) | `2R6[>3]>=5`, `2R6>=5@>3` |
| [上方無限ロール](/command/upper_dice.md) | `2U6[4]>=10`, `2U6>=10@4` |
| [D66](/command/d66_dice.md) | `D66A`, `D66D`, `D66D` |
| [計算コマンド](/command/calc.md) | `c1+2*3/4` |
| [チョイスコマンド](/command/choice.md) | `choice[A,B,Z]`, `choice(A,B,Z)`, `choice A B Z`|
| [繰り返しコマンド](/command/repeat.md) | `x5 2D6`, `rep5 2D6`, `repeat5 2D6` |
| [Versionコマンド](/command/version.md) | `BCDiceVersion` |