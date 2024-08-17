## Struktur Data Array di JavaScript

**Array** adalah struktur data yang paling umum digunakan dalam JavaScript. Ini adalah koleksi terurut dari elemen, yang dapat berupa nilai dari berbagai tipe data.

### Deklarasi Array

```js
let arrayName = [element1, element2, element3, ...];
```

### Akses Elemen

Elemen dalam array dapat diakses menggunakan indeks, dimulai dari 0.

```js
let numbers = [10, 20, 30];
console.log(numbers[0]); // Output: 10
```

### Modifikasi Elemen

Elemen dalam array dapat diubah dengan menetapkan nilai baru ke indeks tertentu.

```js
let fruits = ["apple", "banana", "orange"];
fruits[1] = "grape";
console.log(fruits); // Output: ["apple", "grape", "orange"]
```

### Panjang Array

Untuk mengetahui jumlah elemen dalam array, gunakan properti `length`.

```js
let numbers = [10, 20, 30];
console.log(numbers.length); // Output: 3
```

### Metode Array

Array memiliki banyak metode untuk manipulasi data:

- **push():** Menambahkan elemen ke akhir array.
- **pop():** Menghapus dan mengembalikan elemen terakhir dari array.
- **shift():** Menghapus dan mengembalikan elemen pertama dari array.
- **unshift():** Menambahkan elemen ke awal array.
- **splice():** Menghapus atau menambahkan elemen pada indeks tertentu.
- **slice():** Mengembalikan bagian dari array sebagai array baru.
- **concat():** Menggabungkan dua atau lebih array menjadi satu array baru.
- **join():** Menggabungkan semua elemen array menjadi sebuah string.
- **indexOf():** Mengembalikan indeks pertama kemunculan suatu elemen.
- **lastIndexOf():** Mengembalikan indeks terakhir kemunculan suatu elemen.
- **includes():** Mengembalikan true jika array berisi elemen tertentu.
- **forEach(), map(), filter(), reduce(), find(), findIndex(), every(), some()**: Metode untuk iterasi dan manipulasi array yang lebih kompleks.

### Contoh Penggunaan

```js
let numbers = [1, 2, 3, 4, 5];

// Menambahkan elemen
numbers.push(6);

// Menghapus elemen terakhir
let removed = numbers.pop();

// Menggabungkan array
let combined = numbers.concat([6, 7, 8]);

// Mencari elemen
let index = numbers.indexOf(3);

console.log(numbers);
console.log(removed);
console.log(combined);
console.log(index);
```

Array adalah struktur data yang sangat fleksibel dan sering digunakan dalam JavaScript untuk menyimpan dan mengelola data.