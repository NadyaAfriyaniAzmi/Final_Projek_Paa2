Bubble Sort:

Worst Case: O(n^2)
Best Case: O(n)
Average Case: O(n^2)
Bubble Sort memiliki kompleksitas waktu terburuk (worst case) dan kompleksitas waktu rata-rata (average case) sebesar O(n^2), di mana n adalah jumlah elemen dalam array yang diurutkan. Hal ini terjadi ketika array dalam kondisi terbalik secara terurut. Dalam setiap iterasi, Bubble Sort membandingkan elemen-elemen bersebelahan dan menukar mereka jika urutannya salah. Algoritma ini perlu menjalankan beberapa iterasi dan melewati beberapa pasangan elemen sebelum array benar-benar terurut. Ketika array sudah dalam keadaan terurut, maka Bubble Sort memiliki kompleksitas waktu terbaik (best case) sebesar O(n), karena tidak perlu dilakukan pertukaran elemen.

Insertion Sort:

Worst Case: O(n^2)
Best Case: O(n)
Average Case: O(n^2)
Insertion Sort juga memiliki kompleksitas waktu terburuk (worst case) dan kompleksitas waktu rata-rata (average case) sebesar O(n^2), di mana n adalah jumlah elemen dalam array yang diurutkan. Pada setiap iterasi, Insertion Sort memilih satu elemen dari array yang belum terurut dan memasukkannya ke posisi yang sesuai dalam array yang sudah terurut sebelumnya. Pada kasus terburuk dan rata-rata, algoritma ini perlu menjalankan beberapa iterasi dan memindahkan beberapa elemen sebelum elemen yang dipilih dapat ditempatkan pada posisi yang benar. Ketika array sudah dalam keadaan terurut, maka Insertion Sort memiliki kompleksitas waktu terbaik (best case) sebesar O(n), karena tidak perlu dilakukan pergeseran elemen.

Dalam kedua algoritma ini, kompleksitas waktu terburuk dan rata-rata sama, yaitu O(n^2). Namun, dalam kasus terbaik, baik Bubble Sort maupun Insertion Sort memiliki kompleksitas waktu yang lebih baik dengan O(n) karena mereka dapat mengenali bahwa array sudah terurut dan menghentikan proses pengurutan lebih cepat.

Travelling Salesman Problem (TSP):
- Worst Case: O((n-1)!)
- Best Case: O((n-1)!)
- Average Case: O((n-1)!)

Dijkstra:
- Worst Case: O((V+E)logV)
- Best Case: O(V+E)
- Average Case: O((V+E)logV)

Pada algoritma TSP, kompleksitas waktu terburuk, terbaik, dan rata-rata adalah O((n-1)!), di mana n merupakan jumlah titik dalam graf. Ini disebabkan oleh pendekatan brute force yang digunakan untuk menghasilkan semua permutasi dari node dan menghitung jarak terpendek.

Pada algoritma Dijkstra, kompleksitas waktu terburuk adalah O((V+E)logV), di mana V adalah jumlah node (titik) dalam graf dan E adalah jumlah tepi (edge). Kompleksitas terbaik adalah O(V+E) saat melakukan pembaruan jarak terpendek untuk setiap node, dan kompleksitas rata-rata adalah O((V+E)logV).

Ini adalah analisis teoretis dari kompleksitas algoritma berdasarkan karakteristik masing-masing algoritma.
