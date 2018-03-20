# HOMEWORK-WEEK1
### hw1.py:
```python
for i in range(0,3) :
    birincisayi = int(input("Birinci sayýyý giriniz:"))
    ikincisayi = int(input("Ýkinci sayiyi giriniz:"))
    islem = input("Yapacaðýnýz iþlemi seçiniz(+,-,/,*):")
    if islem == "+" :
        print (birincisayi+ikincisayi)
    elif islem == "-" :
        print (birincisayi-ikincisayi)
    elif islem == "*" :
        print (birincisayi*ikincisayi)
    elif islem =="/" :
        print (birincisayi/ikincisayi)
    elif islem == "exit":
        break
    else:
        print("Lütfen belirtilen operatörlerden birini giriniz")  
```
		
> ...
		
### • hw2.py:
```python
		a=0
		b=1
		sayi = int(input("Ýstediðiniz sayýnýn sýrasýný giriniz:"))
		for i in range(0,sayi):
		print(b)
		c=a
		a=b
		b=c+b   
	
```
> ...
			
