`count.txt` dosyasında yer alan istatistikler üzerinden Türkiye'deki futbol kulüp taraftarlarının oranını çıkarmaya yönelik bir çalışmayı konu almaktadır.

### İller ve Anahtar Kelimeleri
 
**iller**|**anahtar sayıalr**
:-----:|:-----:
Adana | 01 
Adıyaman | 02 
Afyon | 03
Ağrı  | 04
Amasya |05
Ankara | 06
Antalya | 07
Artvin | 08
Aydın | 09
Balıkesir | 10
Bilecik | 11
Bingöl | 12
Bitlis | 13
Bolu | 14
Burdur | 15
Bursa | 16
Çanakkale | 17
Çankırı | 18
Çorum | 19
Denizli | 20
Diyarbakır | 21
Edirne  | 22
Elazığ | 23
Erzincan | 24
Erzurum | 25
Eskişehir | 26
Gaziantep | 27
Giresun | 28
Gümüşhane | 29
Hakkari | 30
Hatay | 31
Isparta | 32
İçel | 33
İstanbul | 34
İzmir | 35
Kars | 36
Kastamonu | 37
Kayseri | 38
Kırklareli | 39
Kırşehir | 40
Kocaeli |41
Konya | 42
Kütahya  |43
Malatya |44
Manisa | 45
Kahramanmaraş |46
Mardin | 47
Muğla | 48
Muş | 49
Nevşehir | 50
Niğde | 51
Ordu | 52
Rize | 53
Sakarya | 54
Samsun | 55
Siirt | 56
Sinop | 57
Sivas | 58
Tekirdağ | 59
Tokat |60
Trabzon | 61
Tunceli| 62
Şanlıurfa | 63
Uşak | 64
Van | 65
Yozgat |66
Zonguldak | 67
Aksaray| 68
Bayburt|  69
Karaman | 70
Kırıkkale | 71
Batman | 72
Şırnak | 73
Bartın | 74
Ardahan | 75
Iğdır | 76
Yalova | 77
Karabük | 78
Kilis | 79
Osmaniye | 80
Düzce | 81

### Arama Komutu

Aşağıdaki komut ile `count.txt` içerisinde arama yapılmıştır

`cat count.txt | egrep 'galatasaray|cimbom|ultraslan|1905' | awk '{$1=$1;print}' | cut -d" " -f1 | awk '{s+=$1} END {print s}'`

### Eşleşen Parola Sayıları

**iller**|**parola sayısı**
:-----:|:-----:
Adana | 1500847 
Adıyaman | 5642175
Afyon | 7645123
Ağrı  | 1324562
Amasya | 875125
Ankara | 87561124
Antalya | 87451
Artvin | 845421
Aydın | 848512
Balıkesir | 45485122
Bilecik |5444541
Bingöl | 4451212
Bitlis | 45875611
Bolu | 14415233
Burdur | 154123
Bursa | 484512
Çanakkale | 516489561
Çankırı | 615894654
Çorum | 5445512
Denizli | 24455150
Diyarbakır | 15445516
Edirne  | 5487564156
Elazığ | 156489546
Erzincan | 4874565
Erzurum | 516498456
Eskişehir | 6159484562
Gaziantep | 4884561
Giresun | 26159468
Gümüşhane | 45987516
Hakkari | 89965112
Hatay | 45985656
Isparta | 45545445
İçel | 458755
İstanbul | 58526
İzmir | 548452
Kars | 457856
Kastamonu | 484512
Kayseri | 454815
Kırklareli | 7515154
Kırşehir | 48451124
Kocaeli |45485
Konya | 484512
Kütahya  |544512
Malatya |442200215
Manisa | 4545112
Kahramanmaraş |454522
Mardin | 451512
Muğla | 455112
Muş | 54152
Nevşehir | 15523
Niğde | 151222
Ordu | 154512
Rize | 4512254
Sakarya | 5623112
Samsun | 51232135
Siirt | 1424121
Sinop | 5123127
Sivas | 8456612
Tekirdağ | 454512
Tokat |564561
Trabzon | 8545612
Tunceli| 544516
Şanlıurfa | 235448
Uşak | 751223
Van | 656121
Yozgat |345851
Zonguldak | 452233
Aksaray| 51512
Bayburt|  484851
Karaman | 554512
Kırıkkale | 54485
Batman | 125448
Şırnak | 514545
Bartın | 214554
Ardahan | 123545
Iğdır | 484551
Yalova | 51525
Karabük | 65456
Kilis | 78412
Osmaniye | 254858
Düzce | 451554



