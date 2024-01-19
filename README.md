# Swift Değişken Tanımlama ve Veri Tipleri

Uygulamanızın içerisinde sabit bir değeriniz var ise bunu **_let_** ile tanımlayabiliriz.
Uygulama içerisinde değişen bir değerimiz var ise bunu **_var_**	ile tanımlayabiliriz.
```swift
let sabitdegisken="sabit degisken" //string
var dinamikdegisken=123456 //int
```
Burada sabitdesigken değeri **_string_**, var değeri ise **_int_** olarak belirlenmiştir.
Peki bunların  tiplerini nasıl göreceğim.
XCode üzerinde ALT tuşuna basıp değişkenin üzerine geldiğimizde değişkenin tipini görebilmekteyiz.
> ### Integer(int)
> Integer tipi tamsayıları ifade eder.
> Integer’lar -2,147,483,648 ile 2,147,483,647 arasındadır.
>```swift
>let gecenYil: Int = 2023
>let gecenYil: 2023
>``` 
Yukarıdaki gibi iki şekilde de tanımlama yapılabilir. **_Birinci kullanım ideal._**
>### Double ve Float
>Double ve Float ondalık sayıları ifade etmek için kullanılır.
>Farkları ; **_double 64 bit sayıları float ise 32 bit sayıları_** ifade eder.
>```swift
>var floatdeger:Float=21.03
>var doubledeger:22.01
>```
>>### Boolean
>Boolean mantıksal değerleri ifade etmek için kullanılır.
> **true veya false** değerleri ifade eder.
> Aşağıda basit bir kullanımı gösteren kod bloğu mevcuttur.
>```swift
>var sayiciftmi:Bool=true
>if sayiciftmi {
>     printf("Sayi çifttir")
>}
>else
>{
>      printf("Sayi tektir.")
>}
>```
>### String ve Char Tipi
>String , karakter dizilerinden oluşan bir yapıdır. Peki karakter nedir ? diye düşünüyorsanız , bunu bir örnek ile açıklamak daha doğru olacaktır. Örneğin, “?” bir karakterdir , “a” bir karakterdir ama “nasılsın ?” bir stringtir ve içinde n,a,s,ı,l,s,ı,n, ,? karakterlerini barından bir veri tipidir.Burda dikkatinizi çekmek istediğim bir hususta karakterleri yazarken boşluğuda bir karakter olarak virgülle ayırmam. Boşlukta bir karakterdir.
>```swift
>var benimAdim = "Harun" 
>var benimSoyAdim: String = "ÖKNEL"
>print(benimAdim+benimSoyAdim) // Ekrana yazdırma
>```

>```swift
>var isim= "deneme" 
>print(Merhaba benim adım \(isim)) // Ekrana yazdırma
>```
>**Boş String Oluşturma**
>```swift
>var bosString = ""
>var bosString2 = String()
>```
>>>**String'e ## Character Ekleme**
>```swift
>var haberBasligi = "Şimdi Haberler"
>haberBasligi.append("!")
>```


