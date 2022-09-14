## Proje 3

### Soru

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

### Çözüm

**root = 2**

> **1.** 7, 2'den büyük olduğu için 2'nin sağına =>

            2
              \
                7

> **2.** 5, 2'den büyük 7'den küçük olduğu için 7'nin soluna,

            2
              \
                7
              /
            5

> **3.** 1, 2'den küçük olduğu için 2'nin soluna,

            2
          /   \
        1       7
               /
              5

> **4.** 8, 2 ve 7'den büyük olduğu için 7'nin sağına,

            2
              \
                7
               / \
              5   8

> **5.** 3, 2 ve 7'den büyük 5'den küçük olduğu için 5'in soluna,

            2
          /   \
        1       7
               / \
              5   8
             /
            3

> **6.** 6, 2'den büyük, 7'den küçük, 5'den büyük olduğu için 5'in sağına,

            2
          /   \
        1       7
               / \
              5   8
             / \
            3   6

> **7.** 0, 2 ve 1'den küçük olduğu için 1'in soluna,

            2
          /   \
        1       7
       /       / \
      0       5   8
             / \
            3   6

> **8.** 9, 2, 7 ve 8'den büyük olduğu için 8'in sağına,

            2
          /   \
        1       7
       /       / \
      0       5   8
             / \   \
            3   6   9

> **9.** 4, 2'den büyük, 7 ve 5'den küçük, 3'den büyük olduğu için 3'ün sağına yazılır.

            2
          /   \
        1       7
       /       / \
      0       5   8
             / \   \
            3   6   9
             \
              4

---

[Patika.dev Profil](https://app.patika.dev/fhusrev)
