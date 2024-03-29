# BCDiceコマンドガイド

このウェブサイトは日本で最も使われているTRPG用ダイスコマンドエンジン「BCDice」の公式ガイドです。
コマンドガイドでは、BCDiceのコマンドを入力時に共通するお約束事項と、どのゲームシステムを選んでも実行することができる汎用コマンドを詳しく解説します。

このガイドを読んで気になったことがあれば、ブラウザで手軽にBCDiceを実行できる**[Saipage][saipage]**を使って実際にコマンドを試してみてください！

## BCDiceとは…
BCDiceとは日本で最も使われている、TRPG用ダイスコマンドエンジンです。
かつて[どどんとふ][dodontof]で使われたことで広まり、現在は[ココフォリア][ccfolia]、[ユドナリウム][udonarium]、[TRPGスタジオ][trpg-studio]など様々なオンセツールで使われています。


## 汎用コマンド一覧

詳細な仕様は各コマンドの説明ページをご覧ください。

| コマンド名 | 例 |
| :----- | :----- |
| [加算ダイス](/command/add_dice.md) | `2D6+1>=7`, `5D6KH3` |
| [バラバラダイス](/command/barabara_dice.md) | `5B6` |
| [個数振り足しダイス](/command/reroll_dice.md) | `2R6[>3]>=5`, `2R6>=5@>3` |
| [上方無限ロール](/command/upper_dice.md) | `2U6[4]>=10`, `2U6>=10@4` |
| [集計ダイス](/command/tally_dice.md) | `8TY6`, `7TZ10` |
| [D66](/command/d66_dice.md) | `D66`, `D66A`, `D66D`, `D66N` |
| [計算コマンド](/command/calc.md) | `c1+2*3/4` |
| [チョイスコマンド](/command/choice.md) | `choice[A,B,Z]`, `choice(A,B,Z)`, `choice A B Z`|
| [繰り返しコマンド](/command/repeat.md) | `x5 2D6`, `rep5 2D6`, `repeat5 2D6` |
| [Versionコマンド](/command/version.md) | `BCDiceVersion` |

## 対応ゲームシステム

BCDiceは100以上のゲームシステムに対応しています。一覧は[対応ゲームシステム一覧](https://bcdice.org/systems/)をご覧ください。


## 問い合わせ先

本ドキュメントやコマンドに関する問い合わせは、Discordサーバー [bcdice-help][discord] にご連絡ください。


[dodontof]:https://megalodon.jp/2020-1231-1314-36/www.dodontof.com/index.php?option=com_content&view=article&id=570:good-by-dodontof&catid=12:dodontofnews&Itemid=150
[ccfolia]:https://ccfolia.com/
[udonarium]:https://udonarium.app/
[trpg-studio]:https://trpg-studio.com/
[saipage]:https://ysakasin.github.io/saipage/
[discord]:https://discord.gg/D5CazXH


