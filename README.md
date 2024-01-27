# reference
predicateのreferenceに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】referenceで作業を簡単にする【predicate】](https://natsumake.com/reference/)』を参考にしてください。

<h3>使い方</h3>

導入後、```/execute if predicate sample:reference run give @a diamond 1```を実行することで、平野にいる場合はダイヤモンドを貰えます。<br>
（location_checkで平野にいることを条件としているpredicateをreferenceで指示しています）

また、本データパックでは進捗とルートテーブルにもreferenceを指示したものを実装しています。<br>
そのため平野でインベントリに変化が起こると進捗を解除するほか、平野でゾンビを倒すと石をドロップします。
