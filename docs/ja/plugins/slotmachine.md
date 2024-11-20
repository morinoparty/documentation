# Slot Machine

- [Spigot](https://www.spigotmc.org/resources/slot-machine.22023/)

## 概要

スロットマシンを作成することができます。

## 使い方

コンフィグで設定されているアイテム(default: ブレイズロッド)を持ち、ブロックをクリックします。

### スロットマシンの作成

## コマンド

コマンド: `/openmachine <player> <machine uuid>`
説明: スロットのGUIを開きます。

コマンド: `/tpmachine <entity uuid>`
説明: 自分の位置にスロットマシンをテレポートします。

コマンド: `/givetoken <player> <amount> [token id]`
説明: プレイヤーにトークンを与えます。

コマンド: `/slotmachinetoken list`
説明: トークンのリストを表示します。

コマンド: `/slotmachinetoken add <name>`
説明: トークンを追加します。 nameはuniqueである必要があります。

コマンド: `/smreload`
説明: プラグインをリロードします。

コマンド: `/smcooldown <target> <machine uuid|all> reset`
説明: クールダウンをリセットします。

コマンド: `/smbackup`
説明: バックアップを作成します。

コマンド: `/smsavetodisk`
説明: データを強制的にディスクに保存します。基本的には1分ごとに自動で保存されます。

コマンド: `/smupdatelanguages`
説明: 言語ファイルを更新します。

## 権限

### 管理用

### プレイヤー用
