`count.txt` dosyasında yer alan istatistikler üzerinden Türkiye'deki futbol kulüp taraftarlarının oranını çıkarmaya yönelik bir çalışmayı konu almaktadır.

### Kulüpler ve Anahtar Kelimeleri

**kulup**|**anahtar kelime**
:-----:|:-----:
Sivasspor | sivas sivasspor svs58 yigido58 5858
Galatasaray| galatasaray cimbom 1905 ultraslan
Fenerbahce | fenerbahce fener kanarya 1907 gencfb 1907
Besiktas|1903 besiktas karakartal 1903 carsi
Trabzonspor|1967 trabzonspor 1967 1461
Bursaspor| 1963 bursaspor teksas
Eskisehir| 1965 eskisehir eses
Karsiyaka| 1912 karsiyaka ksk1912
Goztepe| 1925 goztepe gozgoz
Samsunspor| 1965 samsunspor
Ankaragucu|1910 ankaragucu gecekondu jilet 
Konyaspor| 1922 konyaspor
Adanaspor| 1954 adanaspor turbeyler
Sakaryaspor| 1965 sakaryaspor tatanga adapazarı 
Kayserispor| 1966 kayserispor
Kocaelispor| 1966 kocaelispor hodrimeydan
Denizli| 1966 denizlispor
Antalyaspor| 1966 antalyaspor
Malatyaspor| 1986 malatyaspor
Kasimpasa| 1921 kasimpasa 
Giresunspor| 1967 giresunspor
Adanademirspor| 1940 adanademir mavisimsek
Erzurumspor|2005 erzurumspor
Gaziantep|1969 antepspor
Karagumruk| 1926 karagumruk 
Rizespor| 1953 rizespor
Genclerbirligi| 1923 genclerbirligi
Ümraniye | 1938 ümraniye ümraniyeliler 


### Arama Komutu

Aşağıdaki komut ile `count.txt` içerisinde arama yapılmıştır

`cat count.txt | egrep 'galatasaray|cimbom|ultraslan|1905' | awk '{$1=$1;print}' | cut -d" " -f1 | awk '{s+=$1} END {print s}'`

### Eşleşen Parola Sayıları

**takim**|**parola sayısı**
:-----:|:-----:
galatasaray|150848
fenerbahce|140523
besiktas|85493
trabzonspor|40332
bursaspor|7199
eskisehir|6054
karsiyaka|2041
goztepe|1701
samsunspor|1588
ankaragucu|1308
sivasspor|1104
konyaspor|785
adanaspor|781
sakaryaspor|774
altay|765
kayserispor|701
kocaelispor|696
denizli|555
antalyaspor|417
malatyaspor|350
kasimpasa|324
giresunspor|213
adanademirspor|194
erzurumspor|163
gaziantep|140
karagumruk|109
rizespor|105
genclerbirligi|36




