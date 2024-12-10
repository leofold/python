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
sayi1 = input("Lütfen bir sayi yazın: ")
sayi2 = input("Lütfen bir sayi daha yazın: ")
sayi1 = int(sayi1)
sayi2 = int(sayi2)
toplam = sayi1 + sayi2
print(toplam)
```


# DIZILER
```python
# isim = "Mahmut"
isimler = ["Ali", "Ayşe", "Fatma"]

# isimler.append("huseyin")
# isimler.pop() # sondaki degeri siler
isimler.remove("Ayşe") # ayse degerindeki kaydi siler.
print(isimler) # Fatma degerini ekrana yazar.
 
# diziler 0 dan baslayarak gider. ornegin 0. deger Ali'dir
```
