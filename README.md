# VillagerShop  
村人ショップ  
村人のCustomNameを参照してショップを開きます。    
ままたショップを作成しやすいようにいくつかアイテムが追加されています。    

+Commands*  
/villageShop shop create <ショップ名> - ショップを新しく作成します。  
/villageShop shop delete <ショップ名> - ショップを削除します  
/villageShop shop list - 作成済みのショップ一覧

/villageShop setting <ショップ名> add <販売アイテム> <個数> <コスト1> <個数>  
/villageShop setting <ショップ名> add <販売アイテム> <個数> <コスト1> <個数> <コスト2> <個数> <二つとも必要かどうか  
 -ショップにアイテムを追加します。空いているスロットに自動追加します。

/villageShop setting <ショップ名> set <スロットID> <販売アイテム> <個数> <コスト1> <個数>  
/villageShop setting <ショップ名> set <スロットID> <販売アイテム> <個数> <コスト1> <個数> <コスト2> <個数> <二つとも必要かどうか>  
 -ショップにアイテムを設定します。指定したスロットにセットします

/villageShop setting <ショップ名> remove <スロットID>  
 -ショップの指定したスロットを削除します

 /villageShop setting <ショップ名> clear  
 -ショップのアイテムを全て削除します。
