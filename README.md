# Insorting-sort
## [22,27,16,2,18,6] dizisinin sort turune gore asamalarını yaziniz.

Ilk asamada daginik dizide ki **en kucuk** elemani bulmamiz gerekiyor.
Dizide ki en kucuk elemanin **2** oldugunu goruyoruz ve en kucuk elemani dizinin basinda ki elemanla yer degistiriyoruz.

- Dizinin aldigi sekil [2,27,16,22,18,6] oluyor.

Sirali bir dizi olusturmak icin **kucukten buyuge dogru** elemanlarin yerlerini degistiriyoruz.
Dizide ki ikinci en kucuk elemanin **6** oldugunu goruyoruz ve bulunmasi gereken konumdaki elemanla yerini degistiriyoruz.

* Dizinin aldigi sekil [2,6,16,22,18,27] oluyor.

Bu iki islem sonrasında **16** sayısı dizide bulunması gereken konumda oluyor ve onun icin bir islem yapmamiza gerek kalmiyor.

Dizide islem yapilabilecek ucuncu en kucuk eleman ise **18** onu da yerini alan eleman ile degistiriyoruz.

- Dizini aldigi sekil [2,6,16,18,22,27]

En son da **22** ve **27** elemanlari kaldi fakat onlar zaten sirali bir sekilde duruyorlar bunun icin islem yapmamiza gerek yok.

Uc islem sonunda sirali bir dizi olusturmus oluyoruz.

## Big-O Gosterimi 

n(n+1)/2 O(n^2)

## Time Complexity

Average case: Aradigimiz sayinin ortada olmasi. Dizi siralandiktan sonra **18** sayisinin dizinin ortasinda oldugunu goruyoruz. Bu sonuc bize **18** sayisinin Avarage case kapsaminda oldugunu gosterir.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a gore ilk 4 adimi nasil olur ?

- [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
* [2,3,4,5,6,9,8,15,7]