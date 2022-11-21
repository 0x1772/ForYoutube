### **Soru:**

> ***If Else kullanarak basit bir kullanıcı doğrulama sistemi yapınız...***

---------------------------------------

<strong>Solution: </strong>

```python

age = int(input("Lütfen yaşınızı giriniz: "))
name = str(input("Lütfen isminizi giriniz: "))
last_name = str(input("Lütfen soy adınızı giriniz: "))
birth_year = int(input("Lütfen doğum yılınızı giriniz: "))
password = str(input("Lütfen bir şifrenizi giriniz: "))

if ((age == 19) and (name == "Ali") and (last_name == "Gümüş") and (password == "12345")):
    print("Kullanıcı başarıyla doğrulandı")
else:
    print("Lütfen tekrar deneyiniz")
```
----------------------------------------
