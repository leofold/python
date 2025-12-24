# bilisim teknolojileri python notlari 

telefonunuza "Pydroid 3" veya benzeri bir uygulama kurun.
bilgisayarlariniza "python" kurulumu yaptiktan sonra "VS Code" uygulamasini kurun. 
Jupyter Notebook ile de python kodlarinizi calistirabilirsiniz.

```python
sayi = 2  # sayi degisikenine 2 degeri atar.
yas = 13  
print(sayi + yas) # sayi ile yas degiskeninin icindeki degerleri toplar ve ekrana yazar. 
```

```python
ad = "ahmet" # ad degiskenine ahmet degerini atar.
print(ad) # ad degiskenini ekrana yazar. 
print(ad + " bugun okula gelmedi") # ekrana ahmet bugun okula gelmedi yazar.
print(ad + " uykusunu almamis")
```

```python
ad = "ozgur"        # string -> str
yas = 16            # integer -> int
ondalik = 2.5       # float -> float
vatandas_mi = False  # boolean -> bool
telefon = None       # NoneType
```

```python
ad: str = "ozgur"        # string -> str
yas: int = 16            # integer -> int
ondalik: float = 2.5       # float -> float
vatandas_mi: bool = False  # boolean -> bool
telefon: None = None       # NoneType
```

```python
# MATEMATIK OPERATORLERI
# + - * / = 

# MANTIKSAL OPERATORLER
# VE, VEYA, DEGIL
# AND, OR, NOT
ad == "ozgur" or yas == 15 # CIKTI: True
ad == "ozgur" or yas == 16 # CIKTI: True
ad == "ozgur" and yas == 15 # CIKTI: False
vatandas_mi == True and ondalik == 2.5 # CIKTI: True
```

# ikinci sinav icin sorumlu olacaginiz alan: 

# girinti nedir?
Python'da girinti, bir kod satırının hangi bloğa ait olduğunu belirtir.


## kosullu ifadeler if, else, elif

```python
ders_notu = 20                         # ders_notu degiskenine 20 degeri atar. 
if ders_notu > 49:                     # ders_notu > 49 dan buyuk ise alt satirdakilerini yap
    print("ogrenci dersten gecti")     # ekrana ogrenci dersten gecti yazar
else:                                  # kosulumuz yanlis ise alt satirdakileri yap
    print("dersten kaldi")             # ekrana dersten kaldi yazar
```

```python
ad = input("bir isim giriniz")  # bir isim giriniz yazar ve yaninda bir kutucuk belirir. 

if ad == "ali":                 # eger ad degiskenin degeri "ali" ise alt satirdaki kod calisir.
    print("hos geldin ali")     # ekrana "hos geldin ali" yazar
elif ad == "hasan":             # eger ad degiskeninin degeri "hasan" ise alttaki satirdaki kod calisir
    print("hos geldin hasan")   # ekrana "hos geldin hasan" yazar
elif ad == "merve":             # eger ad degiskeninin degeri "merve" ise alttaki satirdaki kod calisir
    print("hos geldin merve")   # ekrana "hos geldin merve" yazar
else:                           # yukardaki kosullar gerceklesmezse alt satirdaki kod calisir
    print("sizi tanimiyoruz")    
```

### bir liste olusturup icindeki elemani tespit etme.

```python
anlatanlar = ["deniz", "yusuf", "eyup"]     # bir liste olusturur ve anlatanlar degiskenine atanir.
isim = input("bir isim giriniz")            # bir isim giriniz yazip yanina bir kutucuk olusturur.
if isim in anlatanlar:                      # isim degiskenindeki degeri anlatanlar ismindeki listede var mi bakar.  
    print("bu kisi listede var")            # ekrana "bu kisi listede var" yazar
else:                                       # eger kosul yanlissa alttaki satir calisir.
    print("bu kisi listede yok")            # ekrana "bu kisi listede yok" yazar
```

```python
# DONGULER (while, for)

# while dongusu
sayi = 4                 # sayi degiskenine 4 degerini atar.

while sayi <= 7:         # sayi <= 7 kosulumuz dogru oldugu surece alt satirdakileri yapar.
    print(sayi)          # ekrana sayi degiskeninin degerini yazar.
    sayi += 1            # sayi degiskeninin degerini 1 arttirir.
 
```

```python
# listeler ile dongunun kullanimi
liste = ["elma", "armut", "mandalina"]     # bir liste olusturur ve liste degiskenine atar: icindeki degerler: "elma, armut ve mandalina" 
for eleman in liste:                       # bir dongu olusturur ve liste degiskenindekileri sirayla eleman degiskenine atar
    print(eleman + " bir meyvedir...")     # ekrana eleman degiskeninin degerini ve yanina bir meyvedir yazar
```
