# Insertion Sort Task
>#### Bu "Patika" da birlikte yürümek için aşağıdaki linkten ücretsiz ve kaliteli eğitimlere ulaşabilirsiniz...
> >
>># [Patika.Dev](https://app.patika.dev/referral/fatihtest)
#
>## Task Link
>
>>Proje linkine gitmek için tıklayınız. [Insertion Sort Prejisi Link](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje).
---
### [16,21,11,8,12,22] -> Merge Sort
1. **Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**


|     |     |     |     |     |     |     |     |     |     |     |     | 
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|     |     |     | 16  | 21  | 11  | 8   | 12  | 22  |     |     |     |
|     |     | 16  | 21  | 11  |     |     | 8   | 12  | 22  |     |     |
|     | 16  | 21  |     | 11  |     |     | 8   |     | 12  | 22  |     |
| 16  |     | 21  |     | 11  |     |     | 8   |     | 12  |     | 22  |
|     | 16  | 21  |     | 11  |     |     | 8   |     | 12  | 22  |     |
|     |     | 11  | 16  | 21  |     |     | 8   | 12  | 22  |     |     |
|     |     |     | 8   | 11  | 12  | 16  | 21  | 22  |     |     |     |

2**Big-O gösterimini yazınız.**

Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.