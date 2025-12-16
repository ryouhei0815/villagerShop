# VillagerShop
村人ショップ
村人のCustomNameを参照してショップを開きます。
ままたショップを作成しやすいようにいくつかアイテムが追加されています。

#Commands
/villageShop shop create <ShopName> - ショップを新しく作成します。
/villageShop shop delete <ShopName> - ショップを削除します
/villageShop shop list - 作成済みのショップ一覧

/villageShop setting <ShopName> add <販売アイテム> <個数> <コスト1> <個数>
/villageShop setting <ShopName> add <販売アイテム> <個数> <コスト1> <個数> <コスト2> <個数> <二つとも必要かどうか>
 -ショップにアイテムを追加します。空いているスロットに自動追加します。

/villageShop setting <ShopName> set <スロットID> <販売アイテム> <個数> <コスト1> <個数>
/villageShop setting <ShopName> set <スロットID> <販売アイテム> <個数> <コスト1> <個数> <コスト2> <個数> <二つとも必要かどうか>
 -ショップにアイテムを設定します。指定したスロットにセットします

/villageShop setting <ShopName> remove <スロットID> 
 -ショップの指定したスロットを削除します

 /villageShop setting <ShopName> clear
 -ショップのアイテムを全て削除します。
