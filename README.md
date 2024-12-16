# Binarysearchtree
Kodluyoruz Eğitimi kapsamında binary search tree ödevi
# Binary Search Tree (BST) Aşamaları: 
BST'nin temel özelliği, her düğümün solundaki değerlerin küçük, sağındaki değerlerin ise büyük olmasıdır. Aşağıda, dizinin elemanlarının sırayla Binary Search Tree (BST)'ye eklenme aşamalarını yazacağım.

Adım 1: İlk Eleman (7) - Root İlk eleman 7 dizisinin root elemanı olur.

Root: 7

Adım 2: 5 Ekleme 5, 7'den küçük olduğu için 7'nin soluna eklenir.

Root: 7 Sol Çocuk: 5

Adım 3: 1 Ekleme 1, 7'den küçük ve 5'ten de küçük olduğu için 5'in soluna eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1

Adım 4: 8 Ekleme 8, 7'den büyük olduğu için 7'nin sağına eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sağ Çocuk: 8

Adım 5: 3 Ekleme 3, 7'den küçük, 5'ten küçük, ancak 1'den büyük olduğu için 1'in sağına eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sağ Çocuk: 3 Sağ Çocuk: 8

Adım 6: 6 Ekleme 6, 7'den küçük, ancak 5'ten büyük olduğu için 5'in sağına eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sağ Çocuk: 3 Sağ Çocuk: 8 Sağ Çocuk: 6

Adım 7: 0 Ekleme 0, 7'den küçük, 5'ten küçük ve 1'den de küçük olduğu için 1'in soluna eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sol Çocuk: 0 Sağ Çocuk: 3 Sağ Çocuk: 8 Sağ Çocuk: 6

Adım 8: 9 Ekleme 9, 7'den büyük ve 8'den de büyük olduğu için 8'in sağına eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sol Çocuk: 0 Sağ Çocuk: 3 Sağ Çocuk: 8 Sağ Çocuk: 6 Sağ Çocuk: 9

Adım 9: 4 Ekleme 4, 7'den küçük, 5'ten büyük, ve 3'ten büyük olduğu için 3'ün sağına eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sol Çocuk: 0 Sağ Çocuk: 3 Sağ Çocuk: 8 Sağ Çocuk: 6 Sağ Çocuk: 9 Sağ Çocuk: 4

Adım 10: 2 Ekleme 2, 7'den küçük, 5'ten küçük, 1'den büyük, ve 3'ten küçük olduğu için 3'ün soluna eklenir.

Root: 7 Sol Çocuk: 5 Sol Çocuk: 1 Sol Çocuk: 0 Sağ Çocuk: 3 Sol Çocuk: 2 Sağ Çocuk: 8 Sağ Çocuk: 6 Sağ Çocuk: 9 Sağ Çocuk: 4

Sıralanan dizinin Binary Search Tree yapısı şu şekilde olacaktır:

```    7   ```
```   /  \ ```
```  5    8 ```
``` / \     \ ```
``` 1   6     9  ```
