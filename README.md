# coursemongowb
На виртулке wb установил докер, потому что в mirror нет mongodb&
В docker установил mongodb
```
for (var i = 0; i < randomCount; i++) {
 db[collectionName].insertOne({
         index: i,
         name: "Item " + i,
         value: Math.random() * 100,
         timestamp: new Date(),
         category: "Category " + (i % 5 + 1),
         active: Math.random() > 0.5
     });
}
```
Подсчет

```
print("Создана коллекция '" + collectionName + "' с " + randomCount + " документами");
Создана коллекция 'random_collection_1758882184210' с 53 документами
```
