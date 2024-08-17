
#### Object 

**Objek** adalah tipe data kompleks yang digunakan untuk menyimpan kumpulan data yang terkait. Ini adalah salah satu tipe data paling penting dalam JavaScript dan digunakan secara luas dalam pengembangan web. Struktur data yang menyimpan kumpulan pasangan kunci-nilai.

**Struktur Objek**

- **Properti:** Pasangan nama-nilai yang terkait dengan objek.
- **Metode:** Fungsi yang terkait dengan objek.

**Cara Membuat Objek**
  
  ```js
let person = {
  firstName: "John",
  lastName: "Doe",
  age: 30,
  city: "New York",
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};
```

```js
console.log(person.firstName); // Output: John
console.log(person.fullName()); // Output: John Doe
```


**Kesimpulan**

Objek adalah konsep yang sangat penting dalam JavaScript. Mereka memungkinkan Anda untuk mengelompokkan data dan fungsi terkait dalam satu unit, membuat kode lebih terorganisir dan mudah dikelola.


#### Array 

**Array** adalah tipe data yang digunakan untuk menyimpan koleksi elemen dalam urutan tertentu. Elemen-elemen dalam array dapat memiliki tipe data yang berbeda-beda. Koleksi terurut dari nilai-nilai, yang bisa berupa tipe data apa saja.
  
  ```js
let numbers = [1, 2, 3, 4, 5];
let fruits = ["apple", "banana", "orange"];
let mixedArray = [10, "hello", true, null];
```

**Akses Elemen**

Elemen dalam array dapat diakses menggunakan indeks, dimulai dari 0.

```js
let numbers = [10, 20, 30];
console.log(numbers[0]); // Output: 10
```

**Modifikasi Elemen**

Elemen dalam array dapat diubah dengan menetapkan nilai baru ke indeks tertentu.

```js
let numbers = [10, 20, 30];
numbers[1] = 25;
console.log(numbers); // Output: [10, 25, 30]
```

**Metode Array**

Array memiliki berbagai metode untuk manipulasi data:

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

Array adalah struktur data yang sangat penting dalam JavaScript dan digunakan dalam berbagai aplikasi.



