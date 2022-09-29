# Discord: campi#0009

# npmjs: https://npmjs.com/package/campi.db

# campi.db
* Last Version: 0.0.8
campi.db açık kaynak kodlu bir database modülüdür,
ve yeterli olan tüm özellikleri barındırmaktadır.


## Kurulum
```bash
npm i campi.db@latest
```

Bunu yazdıktan sonra modülün indirilmesini bekleyiniz. Modül kurulunca main dosyanıza aşağıdaki kodu ekleyin. Benim tercihim kodun en üstüne yazın 💖

```javascript
const db = require("campi.db")
```

Eğer modül kendisi database.json dosyası oluşturmazsa elinizle database.json dosyası açın.
Ardından içine {} yazıp bırakınız.

## 0.0.8 Patch Note(s).

* Artık database başlatıldığında konsola [campi.db] I am ready yazıyor.


## Fonksiyonlar

```javascript
    yaz => set
    db.set('prefix', '!')
    <DB>.yaz('prefix', '!')
```

```javascript
    depola => push
    db.push('prefix', '!')
    <DB>.depola('prefix', '!')
```
    
```javascript
    bul => fetch/get 
    db.fetch('prefix')
    <DB>.bul('prefix')
```

```javascript
    kontrol => has
    db.has('prefix')
    <DB>.kontrol('prefix')
```

```javascript
    sil => delete/remove
    db.delete('prefix')
    <DB>.sil('prefix')
```

```javascript
    yedekle => backup
    db.backup('veri.json')
    <DB>.yedekle('veri')
```
    
```javascript
    topla => add
    db.add('puan', 5)
    <DB>.topla('puan', 5)
```

```javascript
    çıkar => substr
    db.substr('puan', 5)
    <DB>.çıkar('puan', 5)
```

```javascript
    sıfırla => -
    <DB>.sıfırla()
```
