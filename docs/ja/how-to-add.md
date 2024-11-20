# ドキュメントを追加するには


## プラグインのドキュメントを変更する場合

`ja/plugins`配下にあるプラグインごとのファイルを編集してください。

## プラグインのドキュメントを追加する場合

`ja/plugins`配下に新しいファイルを作成してください。
ファイル名は`/pl`コマンドで表示されるプラグイン名を小文字化したものにしてください。
タイトルは`/pl`コマンドで表示されるプラグイン名をそのまま使ってください。

### 例 : CoreProtect

`/pl`コマンドを実行してください。

```bash
[00:00:00 INFO]: Server Plugins (7):
[00:00:00 INFO]: Bukkit Plugins:
[00:00:00 INFO]:  - CoreProtect, JukeBox, LuckPerms, MineStamp, NoteBlockAPI, ProtocolLib, SlotMachine
```

このようにいくつかのプラグインが表示されます。
`CoreProtect`が表示されたので、`ja/plugins`に`coreprotect.md`というファイルを作成してください。

```markdown title="ja/plugins/coreprotect.md"
# CoreProtect
## 概要
## 使い方
## コマンド
## 権限
### 管理用
### プレイヤー用
```

このようにファイルを作成した後、内容を記述してください。

## プラグインを削除した場合

`ja/plugins`配下にあるプラグインごとのファイルは残しておいてください。
`ja/list`配下にあるサーバーごとのファイルから削除してください。

もし、代用のプラグインを導入した場合は、以前のプラグインのファイルにその旨を記述してください。

### 例 : CMIを削除し、EssentialsXを導入した場合

`ja/plugins/cmi.md`の内容を以下のように変更してください。

```markdown title="ja/plugins/cmi.md"
# CMI

!!! note
    このプラグインは削除されました。
    代わりに[EssentialsX](./essentialsx.md)が導入されました。 #入れ替えたものがある場合

## 概要

このプラグインは...
```

`ja/plugins/essentialsx.md`を作成してください。 ※入れ替えたものがある場合

```markdown title="ja/plugins/essentialsx.md"
# EssentialsX
## 概要
...
```

listを編集します

```diff title="ja/list/main.md"
## プラグイン一覧

...
+ - [EssentialsX](../plugins/essentialsx.md) #入れ替えたものがある場合
- - [CMI](../plugins/cmi.md)
...
```