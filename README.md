# Maulana-Alfazani-Fahreza-Setiawan
Tugas Dasar Pemrograman P1
#include <stdio.h> #include <string.h> #include <stdlib.h>
/* Tugas Dasar Pemrograman P1
Penjelasan mengenai program tersebut yang dimulai dengan pemenuhan kriteria
1. Mengambil 3 input terminal dari nama, makanan favorit, dan umur.
2. Menghasilkan ID yang unik minimal 10 karakter kombinasi huruf dan angka.
3. Menggunakan fungsi sprintf() untuk konkatenasi string dan mencakup minimal 2 operasi matematika.
4. Hanya menggunakan library standar #include <stdio.h>.
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
66
$7
59
50
51
*/
void
generateID(char id[)) {
char huruf[] = "ABCDEFGHIIKLARQeSSITYNYZ";
char
angka[] = "0123456789";
int i;
srand( (unsigned int) time (NULL) ));
for (i = 0; i < 10;
1++）｛
if
(1 % 2
== 0)
id[il = huruf[rand() % 26];
} else {
// huruf pada posisi genap
id[i] = angka[rand() % 10];
// angka pada posisi ganjil
id[10] = '10';
int
main() {
char nama [50]; char favorite_food [50];
int usia;
char id[100];
// 1. Mengambil
input dari pengguna
printf("Masukkan Nama: ");
scanf("%s" ,nama);
printf( "Masukkan Makanan Favorit: ");
scanf("%s", favorite_food);
printf( "Masukkan Umur: ");
scanf ("%d", &usia);
// 2. Membuat ID unik dengan kombinasi huruf dan angka (minimal 10
karakter)
generateID (id);
// 3. Menampilkan hasil dengan sprintf() dan operasi natematika
sprintf(id, "%s&d%s&d%s%d", nama, usia, favorite_food, usia+2, id[3]);
return 0;
printf(" \n=====
==\n");
printf(" ID Unik
: %s \n"
, id);
printf(" Nama
: %s\n", nama);

printf(" Favorite Food
: %s\n" favorite_foodd);
printf(" Usia
%d\n" sia)
printf("
===22ss
EEEEEE\n"）；
return 0;