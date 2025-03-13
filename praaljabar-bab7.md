# Bab 7: Sistem Persamaan Linear

## Daftar Isi
- [Pendahuluan](#pendahuluan)
- [Sistem dengan Timbangan](#sistem-dengan-timbangan)
- [Menyeimbangkan dengan Substitusi](#menyeimbangkan-dengan-substitusi)
- [Menulis Sistem Persamaan](#menulis-sistem-persamaan)
- [Mensubstitusi Kelompok](#mensubstitusi-kelompok)
- [Mengisolasi dan Mensubstitusi](#mengisolasi-dan-mensubstitusi)
- [Strategi Substitusi](#strategi-substitusi)
- [Timbangan Pengurangan](#timbangan-pengurangan)
- [Eliminasi](#eliminasi)
- [Perkalian untuk Eliminasi](#perkalian-untuk-eliminasi)
- [Latihan Soal](#latihan-soal)

## Pendahuluan

Sistem persamaan linear adalah kumpulan dua atau lebih persamaan linear dengan variabel yang sama. Pada bab ini, kita akan mempelajari cara menyelesaikan sistem persamaan linear menggunakan berbagai metode seperti substitusi dan eliminasi.

## Sistem dengan Timbangan

Konsep sistem persamaan dapat divisualisasikan dengan timbangan. Timbangan merepresentasikan kesetaraan antara dua sisi persamaan.

Misalnya, jika kita memiliki timbangan dengan 3 apel di sisi kiri dan 2 pisang di sisi kanan dan timbangan tersebut seimbang, maka:

$$3 \text{ apel} = 2 \text{ pisang}$$

Jika kita memiliki timbangan lain dengan 1 apel dan 1 pisang di sisi kiri, dan 5 jeruk di sisi kanan:

$$1 \text{ apel} + 1 \text{ pisang} = 5 \text{ jeruk}$$

Kedua persamaan ini membentuk sistem persamaan yang dapat kita selesaikan untuk mencari nilai dari setiap buah.

## Menyeimbangkan dengan Substitusi

Substitusi adalah teknik di mana kita mengganti suatu ekspresi dengan ekspresi lain yang setara. Dalam konteks sistem persamaan, kita menggunakan informasi dari satu persamaan untuk mensubstitusikan variabel dalam persamaan lainnya.

Contoh:

Jika terdapat sistem persamaan:
$$x + y = 10 \quad (1)$$
$$2x - y = 5 \quad (2)$$

Kita dapat menyelesaikannya dengan substitusi:

1. Dari persamaan (1), kita dapatkan: $y = 10 - x$
2. Substitusi nilai $y$ ke persamaan (2):
$$2x - (10 - x) = 5$$
$$2x - 10 + x = 5$$
$$3x - 10 = 5$$
$$3x = 15$$
$$x = 5$$
3. Substitusi $x = 5$ kembali ke persamaan (1):
$$5 + y = 10$$
$$y = 5$$

Jadi, solusinya adalah $x = 5$ dan $y = 5$.

## Menulis Sistem Persamaan

Untuk menulis sistem persamaan dari masalah verbal, ikuti langkah-langkah berikut:

1. Identifikasi variabel yang tidak diketahui
2. Buat persamaan berdasarkan informasi yang diberikan
3. Verifikasi bahwa persamaan tersebut merepresentasikan masalah dengan benar

Contoh:

*Jumlah dua bilangan adalah 20, dan selisihnya adalah 6. Carilah kedua bilangan tersebut.*

Misalkan bilangan pertama adalah $x$ dan bilangan kedua adalah $y$.
- Jumlah kedua bilangan: $x + y = 20$
- Selisih kedua bilangan: $x - y = 6$

## Mensubstitusi Kelompok

Terkadang, beberapa variabel dapat dikelompokkan dan disubstitusi sebagai satu kesatuan.

Contoh:

Jika terdapat sistem persamaan:
$$3(2x + y) + z = 12 \quad (1)$$
$$2x + y = 4 \quad (2)$$
$$z = 3 \quad (3)$$

Kita dapat mensubstitusi kelompok $(2x + y)$ dari persamaan (2) ke dalam persamaan (1):

$$3(4) + z = 12$$
$$12 + z = 12$$
$$z = 0$$

Namun karena $z = 3$ dari persamaan (3), sistem ini tidak memiliki solusi.

## Mengisolasi dan Mensubstitusi

Langkah-langkah untuk menyelesaikan sistem persamaan dengan metode substitusi:

1. Pilih salah satu persamaan dan selesaikan untuk satu variabel
2. Substitusi hasil tersebut ke persamaan lainnya
3. Selesaikan persamaan yang dihasilkan untuk menemukan nilai variabel
4. Substitusi kembali untuk menemukan nilai variabel lainnya

Contoh:

Selesaikan sistem persamaan:
$$3x - 2y = 11 \quad (1)$$
$$x + y = 5 \quad (2)$$

Langkah 1: Mengisolasi variabel $x$ dari persamaan (2)
$$x = 5 - y$$

Langkah 2: Substitusi ke persamaan (1)
$$3(5 - y) - 2y = 11$$
$$15 - 3y - 2y = 11$$
$$15 - 5y = 11$$
$$-5y = -4$$
$$y = \frac{4}{5}$$

Langkah 3: Substitusi nilai $y$ ke persamaan $x = 5 - y$
$$x = 5 - \frac{4}{5} = \frac{25 - 4}{5} = \frac{21}{5}$$

Jadi, solusinya adalah $x = \frac{21}{5}$ dan $y = \frac{4}{5}$.

## Strategi Substitusi

Beberapa strategi untuk menggunakan metode substitusi secara efektif:

1. Pilih persamaan yang paling sederhana untuk mengisolasi variabel
2. Pilih variabel yang mudah untuk diisolasi (koefisien 1 atau -1)
3. Jika semua koefisien tidak sederhana, pertimbangkan untuk menggunakan metode eliminasi

## Timbangan Pengurangan

Konsep pengurangan dalam sistem persamaan dapat divisualisasikan dengan mengurangkan satu timbangan dari timbangan lainnya.

Jika kita memiliki dua timbangan:
- Timbangan 1: $3x + 2y = 12$
- Timbangan 2: $x + 2y = 8$

Kita dapat mengurangkan timbangan 2 dari timbangan 1 untuk mendapatkan:
$$3x + 2y - (x + 2y) = 12 - 8$$
$$2x = 4$$
$$x = 2$$

## Eliminasi

Metode eliminasi digunakan untuk menghilangkan salah satu variabel dengan menambahkan atau mengurangkan dua persamaan.

Langkah-langkah metode eliminasi:
1. Pastikan koefisien salah satu variabel memiliki nilai yang sama (atau berlawanan) di kedua persamaan
2. Tambahkan atau kurangkan persamaan tersebut untuk mengeliminasi salah satu variabel
3. Selesaikan untuk variabel yang tersisa
4. Substitusi kembali ke salah satu persamaan awal untuk menemukan nilai variabel lainnya

Contoh:

Selesaikan sistem persamaan:
$$2x + y = 7 \quad (1)$$
$$x - y = 1 \quad (2)$$

Langkah 1: Tambahkan kedua persamaan untuk mengeliminasi $y$
$$2x + y = 7$$
$$x - y = 1 \quad +$$
$$3x = 8$$
$$x = \frac{8}{3}$$

Langkah 2: Substitusi nilai $x$ ke persamaan (1)
$$2(\frac{8}{3}) + y = 7$$
$$\frac{16}{3} + y = 7$$
$$y = 7 - \frac{16}{3} = \frac{21 - 16}{3} = \frac{5}{3}$$

Jadi, solusinya adalah $x = \frac{8}{3}$ dan $y = \frac{5}{3}$.

## Perkalian untuk Eliminasi

Terkadang koefisien variabel tidak tepat sama atau berlawanan. Dalam kasus ini, kita perlu mengalikan satu atau kedua persamaan dengan faktor yang sesuai.

Contoh:

Selesaikan sistem persamaan:
$$3x + 2y = 7 \quad (1)$$
$$2x + 5y = 3 \quad (2)$$

Untuk mengeliminasi $x$, kita kalikan persamaan (1) dengan 2 dan persamaan (2) dengan 3:
$$2(3x + 2y) = 2(7) \Rightarrow 6x + 4y = 14 \quad (3)$$
$$3(2x + 5y) = 3(3) \Rightarrow 6x + 15y = 9 \quad (4)$$

Kurangkan persamaan (4) dari persamaan (3):
$$6x + 4y - (6x + 15y) = 14 - 9$$
$$-11y = 5$$
$$y = -\frac{5}{11}$$

Substitusi nilai $y$ ke persamaan (1):
$$3x + 2(-\frac{5}{11}) = 7$$
$$3x - \frac{10}{11} = 7$$
$$3x = 7 + \frac{10}{11} = \frac{77 + 10}{11} = \frac{87}{11}$$
$$x = \frac{29}{11}$$

Jadi, solusinya adalah $x = \frac{29}{11}$ dan $y = -\frac{5}{11}$.

## Latihan Soal

1. Selesaikan sistem persamaan:
   $$4x + 3y = 10$$
   $$2x - y = 5$$

2. Umur Budi 5 tahun lebih tua dari umur Andi. Jumlah umur mereka adalah 25 tahun. Berapa umur masing-masing?

3. Sebuah konser menjual tiket reguler seharga Rp100.000 dan tiket VIP seharga Rp150.000. Jika terjual 200 tiket dengan total pendapatan Rp25.000.000, berapa banyak tiket reguler dan tiket VIP yang terjual?
```
