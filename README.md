# bilisim teknolojileri python notlari 

telefonunuza "Pydroid 3" veya benzeri bir uygulama kurun

## degiskenler
```python
# str() parantez icine yazilan degiskeni metinsel ifadeye cevirir
plaka = 65
plaka = str(plaka) # metinsel ifadeye donusturdu.
# plaka = "65"
print(plaka + "1")
```

```python
# int() parantez icine yazilan degiskeni sayisal ifadeye cevirir
yas = "15"
yas = int(yas)
print(yas + 1)
```

```python
# kullanicidan veri alip degiskene atama
#kullanicinin girmis oldugu sayiyi sayi1 degiskenine atar.
sayi1 = input("Lütfen bir sayi yazın: ")

#kullanicinin girmis oldugu sayiyi sayi2 degiskenine atar.
sayi2 = input("Lütfen bir sayi daha yazın: ")

# sayi1 degiskenini metinsel bir ifadeden sayisal bir ifadeye cevirir
sayi1 = int(sayi1)
sayi2 = int(sayi2)
toplam = sayi1 + sayi2
print(toplam)
```


# DIZILER
```python
# isim = "Mahmut"
isimler = ["Ali", "Ayşe", "Fatma"]

# isimler.append("huseyin") #isimler listesine huseyin i ekler.
# isimler.pop() # sondaki degeri siler
isimler.remove("Ayşe") # ayse degerindeki kaydi siler.
print(isimler) # Fatma degerini ekrana yazar.
 
# diziler 0 dan baslayarak gider. ornegin 0. deger Ali'dir
```

# DONGULER

```python
dizi = range(10) # [0,1,2,3,4,5,6,7,8,9]
dizi[1]
```

```python
isimler = ["Ali", "Ayşe", "Fatma"]
for i in isimler:
    print("merhaba, " + i) # ekrana merhaba ve i degiskenini yaz.
```

```python
for index in range(10):            # asagidaki ifadeyi 10 kez yaz
    print(f"merhaba, {index}") # ekrana merhaba ve index degiskenini yaz.
```



