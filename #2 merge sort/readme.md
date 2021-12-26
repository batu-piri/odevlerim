# __*"Merge Sort"*__  Project

we have an array = [16,21,11,8,12,22];

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazalim.
Lets rearrange our given above array with stages in MERGE SORT:

* [16,21,11,8,12,22]
* [16,21,11] [8,12,22]
* [16,21] [11] [8,12] [22]
* [16] [21] [11] [8] [12] [22] 
BURAYA KADAR ELEMANLARIMIZI 1 OGEYE GELINCEYE KADAR BOLUSTURDUK! ŞİMDİ DE BİRLEŞTİRMEYE BAŞLIYORUZ! AMA BİRLEŞTİRİRKEN SIRALAMAYA DİKKAT EDİYORUZ!
* [16,21] [11] [8,12] [22]
* [11,16,21] [8,12,22]
* [8,11,12,16,21,22]
***
2. Big-O gösterimini yazalim. Lets write its "Big O Notation":

* Big O(n*logn);