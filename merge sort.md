# Proje 2: Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort
---
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

## ***Cevap 1:***
    [16,21,11] [8,12,22]
    [16,21] [11] [8,12] [22]
    [16] [21] [11] [8] [12] [22]
    [16,21] [11] [8,12] [22]
    [11,16,21] [8,12,22]
    [8,11,12,16,21,22]
---
### 2. Big-O gösterimini yazınız.

### ***Cevap 2:***
    O(n*Logn)