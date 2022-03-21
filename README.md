# Praktikum 2 - Pemrograman Web (CSS Dasar)

### Ananda Fatah - 312010186
### TI.20.A.1

## Langkah 1
Membuat sebuah dokumen html sebagai berikut:
![1](https://user-images.githubusercontent.com/72727701/159192156-dea38df3-8253-4aa2-afc2-2c7e40b68bbb.jpg)

## Langkah 2
Mendeklarasikan CSS internal dalam bagian `<head>` dokumen.
![2](https://user-images.githubusercontent.com/72727701/159192237-6200be9d-88ae-4278-a32c-fd12e365a581.jpg)

## Langkah 3
Mendeklarasikan inline CSS pada paragraf atau tag `<p>`.
![3](https://user-images.githubusercontent.com/72727701/159192247-aff4da36-d628-425e-b3aa-776242cc29bc.jpg)

## Langkah 4
Membuat CSS eksternal dan menambahkan tag `<link>` pada bagian `<head>` dalam dokumen html untuk memuat dokumen css eksternal tersebut.
![4](https://user-images.githubusercontent.com/72727701/159192243-0bf3b84c-496d-4796-8a15-2b1211a9bc3d.jpg)

Berikut hasilnya setelah browser direfresh.
![refresh](https://user-images.githubusercontent.com/72727701/159192306-8b06167e-6563-487c-898c-d8e09c585921.jpg)

## Langkah 5
Menambah CSS Selector dengan menggunakan ID dan Class Selector pada dokumen css eksternal.
![5](https://user-images.githubusercontent.com/72727701/159192246-3ddc69bd-23b1-4d03-9be7-0426e7a4b671.jpg)

# Pertanyaan dan Tugas
### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
* Saya melakukan beberapa eksperimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti background.
![PT 1](https://user-images.githubusercontent.com/72727701/159192330-34986bf3-62a5-4287-bcac-a581f118cf16.jpg)

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
* Pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.

### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Setelah saya mencoba, jika mendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Contohnya:
![PT 3 (1)](https://user-images.githubusercontent.com/72727701/159192331-2c0d4cb2-d794-4c55-9260-76f0e4a4ce60.jpg)
![PT 3 (2)](https://user-images.githubusercontent.com/72727701/159192334-1852530f-545f-4160-afd3-1dd29a55dbeb.jpg)

* Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.
![PT 3 (3)](https://user-images.githubusercontent.com/72727701/159192325-cce3c08f-7d5e-48f7-ad95-fe8f647d5038.jpg)

### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
![PT 4](https://user-images.githubusercontent.com/72727701/159192328-50ac43fc-9708-47f6-828b-9515dcb07d9a.jpg)
