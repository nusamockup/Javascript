

**Selain penjumlahan, beberapa metode string juga dapat digunakan untuk memanipulasi string:**

- **concat():** Menggabungkan dua atau lebih string.
- **substring():** Mengekstrak bagian dari sebuah string.
- **indexOf():** Mencari posisi karakter atau substring dalam sebuah string.
- **replace():** Mengganti bagian dari sebuah string dengan string lain.

```js
let str = "Hello, world!"; 
let newStr = str.concat(" How are you?"); // Hasil: "Hello, world! How are you?" 
let subStr = str.substring(7, 12); // Hasil: "world" 
let index = str.indexOf("world"); // Hasil: 7 
let replacedStr = str.replace("world", "everyone"); // Hasil: "Hello, everyone!"
```

**`toUpperCase()` dan `toLowerCase()`:**
- Mengubah semua karakter dalam string menjadi huruf besar atau kecil.
- Contoh: 
  ```js
  let text = "Hello, World!"; 
  let upperCaseText = text.toUpperCase(); // "HELLO, WORLD!" 
  let lowerCaseText = text.toLowerCase(); // "hello, world!"
```

**`slice()` dan `substring()`:**

- Mengekstrak bagian dari sebuah string berdasarkan indeks.
- **Perbedaan:** `slice()` menerima indeks negatif untuk menghitung dari akhir, sedangkan `substring()` tidak.
- Contoh:

```js
let text = "Hello, World!"; 
let sliceText = text.slice(7, 12); // "World" 
let subStringText = text.substring(7, 12); // "World"
```


**`split()`:**

- Membagi sebuah string menjadi array berdasarkan pemisah yang ditentukan.
- Contoh:

```js
let text = "apple, banana, orange"; 
let fruits = text.split(","); // ["apple", "banana", "orange"]
```

**`join()`:**

- Menggabungkan elemen-elemen dalam sebuah array menjadi sebuah string dengan pemisah yang ditentukan.
- Contoh:

```js
let fruits = ["apple", "banana", "orange"]; 
let text = fruits.join("-"); // "apple-banana-orange"
```

**`indexOf()` dan `lastIndexOf()`:**

- Mencari indeks pertama atau terakhir kemunculan sebuah substring dalam sebuah string.
- Contoh:

```js
let text = "Hello, world!"; 
let index = text.indexOf("world"); // 7
```

**`replace()`:**

- Mengganti semua atau kemunculan pertama sebuah substring dengan substring lain.
- Contoh:

```js
let text = "Hello, world!"; 
let newText = text.replace("world", "everyone"); // "Hello, everyone!"
```

**Contoh Penggunaan Kombinasi Metode**

```js
let sentence = "This is a sample sentence."; 
let words = sentence.split(" "); // Membagi kalimat menjadi array kata 

// Mengubah huruf pertama setiap kata menjadi kapital 
let capitalizedWords = words.map(word => word.charAt(0).toUpperCase() + word.slice(1)); 

// Menggabungkan kata-kata menjadi kalimat baru 
let newSentence = capitalizedWords.join(" "); 

console.log(newSentence); // "This Is A Sample Sentence."
```

**Penjelasan:**

1. `trim()` menghapus spasi di awal dan akhir kalimat.
2. `split(" ")` membagi kalimat menjadi array kata-kata.
3. `map()` mengubah setiap kata menjadi huruf kapital di awal kata.
4. `join(" ")` menggabungkan kata-kata kembali menjadi kalimat baru.