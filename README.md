# Merge-sort-project

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

#Merge Sort Adımları

1. Bölme (Dividing) Aşaması
Dizi, ortadan ikiye bölünür ve bu işlem alt diziler tek eleman kalana kadar tekrarlanır.

İlk bölme: [16, 21, 11] ve [8, 12, 22]

Sol alt dizi: [16, 21, 11]

Bölme: [16] ve [21, 11]

[21, 11] tekrar bölünür: [21] ve [11]

Sağ alt dizi: [8, 12, 22]

Bölme: [8] ve [12, 22]

[12, 22] tekrar bölünür: [12] ve [22]

2. Birleştirme (Merging) Aşaması

Alt diziler sıralı şekilde birleştirilir.

[21] ve [11] birleştirilir: [11, 21]

[16] ve [11, 21] birleştirilir: [11, 16, 21]

[12] ve [22] birleştirilir: [12, 22]

[8] ve [12, 22] birleştirilir: [8, 12, 22]

Son olarak, iki büyük alt dizi [11, 16, 21] ve [8, 12, 22] birleştirilir:

[11, 16, 21] ve [8, 12, 22] birleştirilir: [8, 11, 12, 16, 21, 22]

#Big-O Gösterimi

Merge Sort'un zaman karmaşıklığı her durumda 
𝑂(𝑛log𝑛) dir Çünkü dizi her defasında ikiye bölünür ve her birleştirme aşamasında 
𝑛 eleman üzerinden işlem yapılır. Bu yüzden:
Bölme işlemi: 
𝑂(log𝑛)
Birleştirme işlemi: 
𝑂(𝑛)

Time Complexity:
𝑂(𝑛log𝑛)







