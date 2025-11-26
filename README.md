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

```python
ders_notu = 20
if ders_notu > 49:
    print("ogrenci dersten gecti")
else: 
    print("dersten kaldi")
```

```python
ad = input("bir isim giriniz")

if ad == "ali":
    print("hos geldin ali")
elif ad == "hasan":
    print("hos geldin hasan")
elif ad == "merve":
    print("hos geldin merve")
else:
    print("sizi tanimiyoruz")
```
