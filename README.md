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
## kosullu ifadeler if, else, elif

```python
ders_notu = 20         # ders_notu degiskenine 20 degeri atar. 
if ders_notu > 49:     # ders_notu > 49 dan buyuk ise alt satirdakilerini yap
    print("ogrenci dersten gecti") # ekrana ogrenci dersten gecti yazar
else: # kosulumuz yanlis ise alt satirdakileri yap
    print("dersten kaldi") # ekrana dersten kaldi yazar
```

```python
ad = input("bir isim giriniz") # bir isim giriniz yazar ve yaninda bir kutucuk belirir. 

if ad == "ali":
    print("hos geldin ali")
elif ad == "hasan":
    print("hos geldin hasan")
elif ad == "merve":
    print("hos geldin merve")
else:
    print("sizi tanimiyoruz")
```

### bir liste olusturup icindeki elemani tespit etme.

```python
anlatanlar = ["deniz", "yusuf", "eyup"]
isim = input("bir isim giriniz")
if isim in anlatanlar:
    print("bu kisi listede var")
else:
    print("bu kisi listede yok")
```

```python
# DONGULER (while, for)

# while dongusu
sayi = 4

while sayi <= 7:
    print(sayi)
    sayi += 1
 
```

```python
# listeler ile dongunun kullanimi
liste = ["elma", "armut", "mandalina"]
for eleman in liste:
    print(eleman + " bir meyvedir...")
```
