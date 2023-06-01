## JS'de ilkel veri türleri

- Number
- String 
- Boolean
- Null 
- Undefined
- Symbol 

Değiştirilemez veri türleridir.

## JS'de ilkel olmayan veri türleri

- Objects (nesneler)
- Array

Düzenlenebilir ve değiştirilebilir veri türleridir.


İlkel olmayan veri türlerini karşılaştıramayız. Dizileri (arrays), fonksiyonları (functions) veya nesneleri (objects) karşılaştırılmaz. Çünkü ilkel olmayan veri türleri değer yerine referans ile karşılaştırıldıkları için referans türü olarak adlandırılır. 


İki nesne yalnızca aynı temel nesneye atıfta bulunuyorsa kesinlikle eşittir.

```
let nums = [1,2,3]
let numbers = nums 

console.log(nums == numbers) //true
```

### Örnekler
#### 1. Örnek
```
const num = Math.floor(Math.random () * 11)
console.log(num)
```
0 ile 10 arası rastgele bir sayı oluşturur.

#### 2. Örnek

```
let randomNum = Math.random()
```
0 ile 0.99999999 arasında bir sayı üretir.


#### 3. Örnek

```
let randomNum = Math.random() //0 ile 0.999 arasında oluşturur.
let numBtn = randomNum * 11 

console.log(numBtn) // Sonuç : min 0 ve max 10..99

let randomNumFloor = Math.floor(numBtn) //yuvarlama yapar
console.log(randomNumFloor) // Sonuç : 0 ile 10 arası çıkar
```

## String

String Methotları

- toUpperCase()
- toLowerCase()
- substr()

```
- başlangıç indeksi ve silinecek karakter sayısı

let string = 'javascript'
console.log(string.substr(4,6)) //script
```
- substring()

```
- başlangıç indeksi ve durma indeksi alır

let string = 'javascript'
console.log(string.substring(0,4)) //java
```

- split()

```
- bir stringi belirtilen yerden bölmeyi sağlar, array olusturur

let string = '30 days of javascript'
console.log(stringçsplit(' ')) // boşluktan böl dedik 
- ["30", "days", "of", "javascript"]
```

- trim()

```
- stringin basında ve sonunda ki boşlukları silmeye yarar.

let string = '  30 days of javasciprt  '
console.log(string.trim(' ')) ya da 
console.log(string.trim()) - yinede boslukları silecektir
```
- includes()

```
- string içinde varlık kontrolü yapar. bulursa true bulamazsa false döner

let string = '30 days of javascript'
console.log(string.includes('days')) //true
```

- replace()

```
- string içerisinde değiştirme yapmamızı sağlar
```

- charAt()

```
- stringdeki indeksi belirttiğinizde o indeksin değerini yazdırır
```

- charCodeAt()

```
- string'teki vermiş olduğunuz index değerinin ASCII numarasını döndürür
```

- indexOf()

```
- belirtilen değerin indeksini verir. Değer bulunamazsa -1 sonucunu döndürür
```

- lastIndexOf()

```
- belirtilen değerin son değer indeksini verir. Değer bulunamazsa -1 sonucunu döndürür
```

- lastIndexOf()

```
- belirtilen değerin son değer indeksini verir. Değer bulunamazsa -1 sonucunu döndürür
```

