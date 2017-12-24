# PubgBot
PubgBotはPLAYERUNKNOWN'S BATTLEGROUNDS内の戦績を表示してくれるDiscord専用のBOTです。
## 導入方法
[ここから](https://discordapp.com/api/oauth2/authorize?client_id=393841382856458250&permissions=0&scope=bot)サーバーにBOTを追加してください。
## コマンド一覧
### !stat
!statはPUBGの戦績を表示するコマンドです。  
使い方は以下のコマンドをメッセージとして送信すると戦績を表示してくれます。
```
!stat [playername] [region] [mode]
```
※コマンド内の[ ]は入力しないでください。  
* [playername]  
playernameにはPUBGで使っているプレイヤー名を入力してください。
* [region]  
regionには戦績を確認したいサーバー名を入力してください。  
regionに入るのは以下です。

|region|サーバー名|  
|:--|:--|
|```na```|North America|
|```eu```|Europe|
|```as```|Asia|
|```oc```|Oceania|
|```sa```|South America|
|```sea```|South East Asia|
|```kr``` or ```jp```|Korea Japan|
|```all``` or ```agg```|Aggregate|
* [mode]  
modeには戦績を確認したいモードを入力してください。  
modeに入るのは以下です。

|mode|人数|
|:--|:--|
|```solo```|1人|
|```duo```|2人|
|```squad```|4人|

例えば、PUBGさんがSQUADの全サーバーの戦績を見たい時は以下のコマンドになります。
```
!stat PUBG agg squad
```
### !news
!newsコマンドはPUBGに関するニュースを取ってきてくれるコマンドです。  
このコマンドを使うと1分置きにニュースの更新がないか確認してくれます。  
ニュースの自動取得を中断する場合は!stopコマンドを使用してください。  
使い方は以下のコマンドをメッセージとして送信するとニュースを取ってきてくれます。
```
!news
```
### !stop
!stopコマンドはニュースの自動取得を中止するコマンドです。  
使い方は以下のコマンドをメッセージとして送信するとニュースの取得を中止します。
```
!stop
```
