# Insertion Sort Task
>#### Bu "Patika" da birlikte yürümek için aşağıdaki linkten ücretsiz ve kaliteli eğitimlere ulaşabilirsiniz...
> >
>># [Patika.Dev](https://app.patika.dev/referral/fatihtest)
#
>## Task Link
>
>>Proje linkine gitmek için tıklayınız. [Insertion Sort Prejisi Link](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje).
---
### [22,27,16,2,18,6] -> Insertion Sort
1. **Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**


| [22, 27, 16, 2, 18, 6] | 
|------------------------|
|                        | 
| [22, 27, 16, 2, 18, 6] | 
|                        | 
| [22, 16, 27, 2, 18, 6] | 
| [16, 22, 27, 2, 18, 6] | 
|                        | 
| [16, 22, 2, 27, 18, 6] | 
| [16, 2, 22, 27, 18, 6] | 
| [2, 16, 22, 27, 18, 6] | 
|                        | 
| [2, 16, 22, 18, 27, 6] | 
| [2, 16, 18, 22, 27, 6] | 
| [2, 16, 18, 22, 27, 6] | 
| [2, 16, 18, 22, 27, 6] | 
|                        | 
| [2, 16, 18, 22, 6, 27] | 
| [2, 16, 18, 6, 22, 27] | 
| [2, 16, 6, 18, 22, 27] | 
| [2, 6, 16, 18, 22, 27] | 
| [2, 6, 16, 18, 22, 27] | 

---
2. **Big-O gösterimini yazınız.**

   O(n^2)
---
3. **Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

    Average case
---
4. **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**


    [7, 3, 5, 8, 2, 9, 4, 15, 6]
    [3, 7, 5, 8, 2, 9, 4, 15, 6]
    [3, 5, 7, 8, 2, 9, 4, 15, 6]
    [3, 5, 7, 2, 8, 9, 4, 15, 6]
    [3, 5, 2, 7, 8, 9, 4, 15, 6]
