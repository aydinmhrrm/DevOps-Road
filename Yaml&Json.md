# Yaml'dan Json'a cevirme
- Yaml'da yazip sonra kaydetip, Json'a ceviriyoruz.
- Yaml'da yazdiktan sonra command+shift ve p tusuna basip sourch kismini aciyoruz.
- Convert to Json yazip, tikliyoruz.


# Yaml& Json ile instance ayagi kaldirma
- Yaml'da cfn-lite yaziyoruz
-Gerekli bilgileri dolduruyoruz.

![1b.jpeg](./Images/1b.jpeg)

- Discription'a aciklama yazabiliriz. Kullanan icinde ne oldugunu gorebilsin.
- Ayrica discrption'in adini degistirebiliriz.
- Resources kismina Ec2 instance yazarak menuyu seciyoruz.
- Her alani degil ama ilgili kisimlari dolduruyoruz.
- ImageID kismini Ec2 dan bakip kopyaliyoruz.

![1c.jpeg](./Images/1c.jpeg)

- InstanceType:t2.micro yaziyoruz.
- KeyName pem dosyamizin ismini yaziyoruz.
- SecurityGroups yazan yere 1b dekini yaziyoruz.
- Tag kismina ne advermek istiyorsan onu yaziyorsun.

```
- Concole dan cloudformation aratip aciyoruz.
- Stacks olusturma menusune gidiyoruz.
- ilk sayfadan upload kismini seciyoruz.
- Dosyamizi yukluyoruz.
- Next next devam edip kuruyoruz.
- Gunceleyerek kontrol ediyoruz,hatamiz var mi diye.
```