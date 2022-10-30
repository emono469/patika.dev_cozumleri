[Patika.dev](https://www.patika.dev/tr)

# Insertion Sort Projesi

#### 1) [22,27,16,2,18,6] dizisinin Insertion Sort türüne göre aşamaları:

    [22,16,27,2,18,6]
    [16,22,27,2,18,6]
    [16,22,2,27,18,6]
    [16,2,22,27,18,6]
    [2,16,22,27,18,6]
    [2,16,22,18,27,6]
    [2,16,18,22,27,6]
    [2,16,18,22,6,27]
    [2,16,18,6,22,27]
    [2,16,6,18,22,27]
    [2,6,16,18,22,27]
    
#### 2) Big-O gösterimi:

    O(n^2)
      
#### 3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?:

    (Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması,
    Best case: Aradığımız sayının dizinin en başında olması.) bilgileri ışığında:
    
    Dizimiz [2,6,16,18,22,27] olduğu için Average case kapsamına girer.
