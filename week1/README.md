# HOMEWORK-WEEK1
### hw1.py:
```python
for i in range(0,3) :
    birincisayi = int(input("Birinci say�y� giriniz:"))
    ikincisayi = int(input("�kinci sayiyi giriniz:"))
    islem = input("Yapaca��n�z i�lemi se�iniz(+,-,/,*):")
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
        print("L�tfen belirtilen operat�rlerden birini giriniz")  
```
		
> ...
		
### � hw2.py:
```python
		a=0
		b=1
		sayi = int(input("�stedi�iniz say�n�n s�ras�n� giriniz:"))
		for i in range(0,sayi):
		print(b)
		c=a
		a=b
		b=c+b   
	
```
> ...
			
