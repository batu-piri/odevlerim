# __*"Insertion Sort"*__  Project

we have an array = [22,27,16,2,18,6];

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazalim.
Lets rearrange our given above array with stages in INSERTION SORT:

* [22,27,16,2,18,6]
* [2,27,16,22,18,6]    22 & 2
* [2,6,16,22,18,27]    27 & 6
* [2,6,16,22,18,27]    stayes the same
* [2,6,16,18,22,27]    22 & 18;

***
2. Big-O gösterimini yazalim. Lets write its "Big O Notation":

* n tane sayinin toplami ve onun da dominant sayisi esas alinacagindan dolayi:
* Big O(n^2);

3. Time Complexity: Average case: Aradığımız sayının ortada olması (16, 18),Worst case: Aradığımız sayının sonda olması (22, 27), Best case: Aradığımız sayının dizinin en başında olması (2, 6).

4. Dizi siralandiktan sonra "18" sayisi "Average Case" kapsamian girer!