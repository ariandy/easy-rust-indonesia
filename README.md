## Update
![example workflow name](https://github.com/Dhghomon/easy_rust/workflows/github%20pages/badge.svg)

2 April 2021: [Added BuyMeACoffee link](https://www.buymeacoffee.com/mithridates) for those who would like to buy me a coffee.

1 February 2021: [Sekarang bisa dilihat di YouTube!](https://www.youtube.com/playlist?list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk) 2 bulan kemudian: semua video selesai pada 1 April 2021, dengan total sebanyak 186 video (kurang lebih berdurasi total 23 jam).

22 December 2020: mdBook bisa dilihat [di sini](https://dhghomon.github.io/easy_rust).

28 November 2020: [Sekarang tersedia juga dalam bahasa simplified Chinese](https://github.com/kumakichi/easy_rust_chs) thanks to [kumakichi](https://github.com/kumakichi)!



![](Easy_Rust_sample_image.png)

## Introduction

Rust adalah bahasa baru yang telah memiliki textbook yang mumpuni. Namun terkadang textbooknya sendiri cukup sulit untuk dipahami karena textbook tersebut ditulis untuk native-English speaker. Sekarang, beberapa perusahaan dan individu mempelajari Rust, dan mereka mungkin saja mempelajarinya lebih cepat dengan textbook yang bahasa Inggrisnya lebih mudah. Untuk itulah textbook ini diperuntukkan bagi mereka yang ingin mempelajari Rust dengan bahasa Inggris yang sederhana.

Rust merupakan bahasa pemrograman yang tergolong baru, namun sudah sangat populer. Ia populer karena memberikan Anda kecepatan dan kontrol sebagaimana C atau C++ namun juga memberikan keamanan memori sebagaimana seperti pemrograman yang baru seperti Python. Ia juga hadir dengan idea yang baru, yang mana terkadang berbeda dari bahasa pemrograman lainnya. Yang artinya ada hal-hal yang baru yang mesti dipelajari dan anda tidak bisa begitu saja "memahaminya sambil berjalan" (tidak seperti bahasa Python atau JS yang mana kita bisa dengan mudah memahaminya sambil mengerjakan project-project hands-on). Rust adalah bahasa yang harus Anda pikirkan sejenak untuk dipahami. Tetapi masih terlihat cukup familiar jika Anda tahu bahasa lain dan hal itu dibuat untuk membantu Anda menulis kode yang baik.

## Who am I?

Saya adalah seorang Canadian yang tinggal di Korea, dan Saya menulis Easy Rust sembari memikirkan bagaimana caranya membuat Rust menjadi mudah dipelajari untuk perusahaan-perusahaan yang baru mulai menggunakannya. Saya harap negara-negara lain yang tidak menggunakan bahasa Inggris sebagai bahasa utamanya juga bisa menggunakan textbook ini.

## Catatan dari translator

Hai, saya adalah [Ariandy](https://github.com/ariandy)/[1kb](https://1kilobyte.github.io/). Translasi ini saya lakukan dari tanggal 15 April 2021 s/d 23 May 2021.
Meskipun translasi ini telah rampung, namun bisa saja ada kesalahan disana-sini, entah mungkin karena ada typo, translasi yang kurang cocok (atau bahkan mungkin salah translasi), ataupun tulisan yang tidak sesuai dengan EYD. Oleh karenanya, saya ingin memberitahukan bahwa hasil translasi ini masih ditahap proofreading.

Jika Anda menemukan kesalahan-kesalahan tersebut, Anda bisa menghubungi saya via [LinkedIn](https://www.linkedin.com/in/ariandy-noviar-a126a5188/).

### Saran
- Saya menyarankan Anda untuk sambil menonton video di [kanal YouTube](https://www.youtube.com/playlist?list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk) yang disediakan oleh [Dave MacLeod](https://www.linkedin.com/in/davemacleod) karena banyak detil-detil penting di video-video tersebut yang tidak tertulis di buku ini. Videonya merupakan suplemen yang baik untuk mendapatkan pemahaman yang lebih baik tentang Rust.
- Jika Anda telah selesai membaca buku ini, ada baiknya Anda membaca Official Rust Book. Setelah membaca buku ini, mungkin membaca Official Rust Book akan menjadi lebih mudah.
- Sebelum membaca buku ini, ada baiknya apabila sebelumnya Anda telah menggunakan bahasa pemrograman yang lain. Karena ada beberapa istilah teknis yang tetap saya biarkan saja. Karena bagi saya akan lebih mudah dipahami jika term tersebut dibiarkan begitu saja dibandingkan setelah diterjemahkan. Beberapa contohnya, saya tidak akan menerjemahkan "method", "closure", "statement", "trait" atau juga "compiler", dll. Akan aneh rasanya di saat saya menerjemahkan "compiler" menjadi "kompilator".

### Catatan lain
- Proses translasi yang saya lakukan benar-benar spontan, sehingga ada beberapa terjemahan yang sifatnya tidak konsisten. Contohnya, terkadang saya membiarkan "return" tidak diterjemahkan. Sedangkan di tempat lainnya saya terjemahkan menjadi "kembalian". Begitu juga dengan "print". Di beberapa tulisan, saya biarkan ia tetap tertulis "print", namun di tulisan yang lain, saya menerjemahkannya dengan "cetak". Saya masih memikirkan apakah ke depannya ini perlu diseragamkan (jika diterjemahkan, semuanya ikut diterjemahkan, dan sebaliknya), ataukah tetap dibiarkan seperti itu saja.
- Karena saya menerjemahkannya dan menuliskannya secara spontan pula, banyak penulisan yang melanggar kaidah EYD. Contohnya, ada beberapa bagian saya menulis "di" yang semestinya dipisah menjadi "di" yang disambung . Hal ini pun akan saya perbaiki.
- Judul dari setiap bab akan saya biarkan dalam bahasa Inggris

Selamat membaca!

## Writing Rust in Easy English

*Rust in Easy English* ditulis dari Juli sampai dengan Agustus 2020, dan memiliki panjang 400 halaman. Anda bisa menghubungi saya disini atau melalui [LinkedIn](https://www.linkedin.com/in/davemacleod) atau [Twitter](https://twitter.com/mithridates) jika Anda memiliki pertanyaan. Jika Anda melihat ada yang salah atau ingin membuat pull request, silahkan beri tahu saya. Lebih dari 20 orang telah membantu berpartisipasi dengan cara memperbaiki typo dan problem pada codenya, dan kamu juga bisa berpartisipasi seperti itu. Saya bukanlah ahli Rust terbaik di dunia, jadi saya selalu suka dan terbuka untuk mendengarkan ide-ide baru atau mengetahui apa saja yang saya harus saya lakukan untuk membuat textbook ini menjadi lebih baik.



- [Part 1 - Rust in your browser](#part-1---rust-in-your-browser)
  - [Rust Playground](#rust-playground)
  - [🚧 and ⚠️](#-and-️)
  - [Comments](#comments)
  - [Types](#types)
    - [Primitive types](#primitive-types)
  - [Type inference](#type-inference)
    - [Floats](#floats)
  - [Printing 'hello, world!'](#printing-hello-world)
    - [Declaring variables and code blocks](#declaring-variables-and-code-blocks)
  - [Display and debug](#display-and-debug)
    - [Smallest and largest numbers](#smallest-and-largest-numbers)
  - [Mutability (changing)](#mutability-changing)
    - [Shadowing](#shadowing)
  - [The stack, the heap, and pointers](#the-stack-the-heap-and-pointers)
  - [More about printing](#more-about-printing)
  - [Strings](#strings)
  - [const and static](#const-and-static)
  - [More on references](#more-on-references)
  - [Mutable references](#mutable-references)
    - [Shadowing again](#shadowing-again)
  - [Giving references to functions](#giving-references-to-functions)
  - [Copy types](#copy-types)
    - [Variables without values](#variables-without-values)
  - [Collection types](#collection-types)
    - [Arrays](#arrays)
  - [Vectors](#vectors)
  - [Tuples](#tuples)
  - [Control flow](#control-flow)
  - [Structs](#structs)
  - [Enums](#enums)
    - [Enums to use multiple types](#enums-to-use-multiple-types)
  - [Loops](#loops)
  - [Implementing structs and enums](#implementing-structs-and-enums)
  - [Destructuring](#destructuring)
  - [References and the dot operator](#references-and-the-dot-operator)
  - [Generics](#generics)
  - [Option and Result](#option-and-result)
    - [Option](#option)
    - [Result](#result)
  - [Other collections](#other-collections)
    - [HashMap (and BTreeMap)](#hashmap-and-btreemap)
    - [HashSet and BTreeSet](#hashset-and-btreeset)
    - [BinaryHeap](#binaryheap)
    - [VecDeque](#vecdeque)
  - [The ? operator](#the--operator)
    - [When panic and unwrap are good](#when-panic-and-unwrap-are-good)
  - [Traits](#traits)
    - [The From trait](#the-from-trait)
    - [Taking a String and a &str in a function](#taking-a-string-and-a-str-in-a-function)
  - [Chaining methods](#chaining-methods)
  - [Iterators](#iterators)
    - [How an iterator works](#how-an-iterator-works)
  - [Closures](#closures)
    - [|_| in a closure](#_-in-a-closure)
    - [Helpful methods for closures and iterators](#helpful-methods-for-closures-and-iterators)
  - [The dbg! macro and .inspect](#the-dbg-macro-and-inspect)
  - [Types of &str](#types-of-str)
  - [Lifetimes](#lifetimes)
  - [Interior mutability](#interior-mutability)
    - [Cell](#cell)
    - [RefCell](#refcell)
    - [Mutex](#mutex)
    - [RwLock](#rwlock)
  - [Cow](#cow)
  - [Type aliases](#type-aliases)
    - [Importing and renaming inside a function](#importing-and-renaming-inside-a-function)
  - [The todo! macro](#the-todo-macro)
  - [Rc](#rc)
  - [Multiple threads](#multiple-threads)
  - [Closures in functions](#closures-in-functions)
  - [impl Trait](#impl-trait)
  - [Arc](#arc)
  - [Channels](#channels)
  - [Reading Rust documentation](#reading-rust-documentation)
    - [assert_eq!](#assert_eq)
    - [Searching](#searching)
    - [[src] button](#src-button)
    - [Information on traits](#information-on-traits)
  - [Attributes](#attributes)
  - [Box](#box)
  - [Box around traits](#box-around-traits)
  - [Default and the builder pattern](#default-and-the-builder-pattern)
  - [Deref and DerefMut](#deref-and-derefmut)
  - [Crates and modules](#crates-and-modules)
  - [Testing](#testing)
    - [Test-driven development](#test-driven-development)
  - [External crates](#external-crates)
    - [rand](#rand)
    - [rayon](#rayon)
    - [serde](#serde)
    - [regex](#regex)
    - [chrono](#chrono)
  - [A tour of the standard library](#a-tour-of-the-standard-library)
    - [Arrays](#arrays-1)
    - [char](#char)
    - [Integers](#integers)
    - [Floats](#floats)
    - [Bool](#bool)
    - [Vec](#vec)
    - [String](#string)
    - [OsString and CString](#osstring-and-cstring)
    - [Mem](#mem)
    - [Prelude](#prelude)
    - [Time](#time)
    - [Other-macros](#other-macros)
  - [Writing macros](#writing-macros)
- [Part 2 - Rust on your computer](#part-2---rust-on-your-computer)
  - [Cargo](#cargo)
  - [Taking_user_input](#taking-user-input)
  - [Using files](#using-files)
  - [Cargo doc](#cargo-doc)
  - [The end?](#the-end?)

# Part 1 - Rust in your browser

Buku ini memiliki 2 bagian. Di Part 1, Anda akan mempelajari Rust dengan browser yang Anda miliki. Anda sebenarnya bisa mempelajari hampir semua yang perlu anda ketahui tanpa menginstall Rust, jadi Part 1 sangatlah panjang. Dan, bagian akhirnya adalah Part 2. Bagian ini jauh lebih pendek, dan bagian ini memerlukan Rust yang terinstall pada komputer. Bagian ini adalah dimana Anda akan mempelajari segala hal yang perlu Anda tahu, namun hanya bisa dipelajari setelah menginstall Rust di komputer anda. Contohnya: berurusan dengan file, mengambil input dari user, grafik, dan personal settings. Semoga dengan berakhirnya Part 1 Anda cukup tertarik untuk menginstall Rust di komputer Anda. Dan jika tidak, juga tidak masalah - karena Part 1 sudah memberikan Anda gambaran yang banyak dan cukup baik tentang Rust.

## Rust Playground
**[See this chapter on YouTube](https://youtu.be/-lYeJeQ11OI)**

Mungkin Anda tidak ingin menginstall Rust sekarang, dan itu tidak apa. Anda bisa ke [https://play.rust-lang.org/](https://play.rust-lang.org/) dan mulai menulis Rust hanya dengan sebuah browser. Anda bisa menuliskan code disitu dan meng-klik Run untuk melihat hasilnya. Anda bisa menjalankan hampir semua contoh code di buku ini di dalam Playground yang Anda buka di browser. Hanya pada bagian menjelang akhir, Anda akan melihat beberapa contoh code yang tidak bisa dijalankan di Playground (seperti membuka files).

Ini adalah beberapa tips di saat menggunakan Rust Playground:

- Jalankan code menggunakan Run
- Ubah Debug ke Release jika Anda menginginkan code anda menjadi lebih cepat. Debug: compile lebih cepat, run lebih lambat, dan menampilkan debug information. Release: compile lambat, run lebih cepat, debug information dihilangkan.
- Klik Share untuk mendapatkan URL link. Anda bisa menggunakan itu untuk membagikan code Anda jika saja Anda memerlukan bantuan. Setelah Anda mengklik share, Anda bisa klik pada `Open a new thread in the Rust user forum` untuk menanyakan ke orang lain agar mendapatkan bantuan.
- Tools: Rustfmt akan memformat code Anda agar menjadi rapi.
- Tools: Clippy akan memberi Anda informasi lanjutan tentang bagaimana untuk membuat code Anda menjadi lebih baik lagi.
- Config: disini Anda bisa mengubah theme ke dark mode sehingga mata anda bisa bekerja dengan aman di malam hari, dan juga konfigurasi yang lainnya.

Jika Anda ingin menginstall Rust, silahkan ke [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install) dan ikuti instruksinya. Biasanya Anda akan menggunakan `rustup` untuk keperluan instalasi dan memperbarui Rust.

## 🚧 and ⚠️

Terkadang code yang menjadi contoh pada textbook ini tidak berjalan. Jika code tersebut tidak berjalan, ia akan menunjukkan tanda 🚧 atau ⚠️ di Playground tersebut. 🚧 itu seperti "under construction": yang berarti bahwa code yang ditulis tidak lengkap. Rust memerlukan sebuah `fn main()` (main function) untuk berjalan, tapi terkadang kita merasa hanya perlu untuk menuliskan bagian kecil dari code sehingga beranggapan bahwa kita tidak memerlukan `fn main()`. Code seperti itu memanglah benar, tapi tentu saja tetap memerlukan sebuah `fn main()` untuk menjalankannya. Dan beberapa contoh code menujukkan sebuah problem yang mana akan kita perbaiki. Untuk code yang mungkin telah memiliki `fn main()` namun menghasilkan error, maka ia akan menggunakan simbol ⚠️.

## Comments
**[See this chapter on YouTube](https://youtu.be/fJ7jBZG_Rpo)**

Comments / Komentar berguna untuk dibaca oleh programmer, bukan untuk komputer. Adalah hal yang baik untuk menulis komentar agar orang lain menjadi mudah untuk membaca code yang telah dibuat. Hal ini juga bagus untuk membantu diri kita sendiri mengerti code yang telah kita buat. (Banyak orang yang sudah menulis code programnya dengan mantap, namun seiring waktu berjalan, dan dia mulai membaca lagi code yang sudah lama sudah tidak dia sentuh, mereka lupa mengapa mereka menulis bagian tersebut.)

Untuk menulis komentar di Rust, anda biasanya menggunakan `//`:

```rust
fn main() {
    // Program Rust dimulai dengan fn main()
    // Kita menuliskan codenya di dalam sebuah block. Block diawali dengan { dan diakhiri dengan }
    let some_number = 100; // Kita bisa menulis sebanyak yang kita mau disini dan compiler tidak akan membacanya
}
```

Apabila anda menjalankan code tersebut, compiler akan mengabaikan apapun yang tertulis setelah `//`. 

Adapula cara berbeda untuk menulis komentar, yaitu dengan cara menulis `/*` pada bagian awalnya dan `*/` pada bagian akhirnya. Cara menulis komentar seperti ini sangat berguna apabila kita ingin menulis komentar pada bagian tengah dari code anda.

```rust
fn main() {
    let some_number/*: i16*/ = 100;
}
```

Bagi compiler, `let some_number/*: i16*/ = 100;` terlihat sama dengan `let some_number = 100;`.

Format `/* */` juga sangat berguna untuk komentar yang panjang (lebih dari 1 baris). Pada contoh ini, anda bisa melihat bahwa anda perlu menuliskan `//` untuk setiap baris. Namun jika anda menggunakan `/*`, apa yang ditulis setelahnya akan tetap dianggap komentar, sampai ia ditutup dengan `*/`.

```rust
fn main() {
    let some_number = 100; /* Let me tell you
    a little about this number.
    It's 100, which is my favourite number.
    It's called some_number but actually I think that... */

    let some_number = 100; // Let me tell you
    // a little about this number.
    // It's 100, which is my favourite number.
    // It's called some_number but actually I think that...
}
```

## Types

Rust memiliki beberapa type, entah berupa angka, karakter, dan yang lainnya. Beberapanya sederhana, sedangkan yang lainnya lebih kompleks, dan bahkan anda bisa membuat type anda sendiri.

### Primitive types
**[See this chapter on YouTube](https://youtu.be/OxTPU5UGMhs)**

Rust memiliki type sederhana yang biasanya disebut sebagai **primitive types** (primitive = paling dasar). Kita akan memulainya dengan integer dan `char` (karakter). Integer adalah semua angka yang tidak berkoma. Ada 2 type integer:

- Signed integers (Integer bertanda),
- Unsigned integers (Integer tidak bertanda).

Bertanda artinya `+` (tanda tambah) dan `-` (tanda minus), maka integer bertanda bisa jadi positif atau negatif (contohnya, +8, -8). Namun, integer tidak bertanda hanyalah bilangan bulat positif, karena ia tidak memiliki tanda.

Ini adalah type-type integer bertanda: `i8`, `i16`, `i32`, `i64`, `i128`, dan `isize`.
Sedangkan ini adalah type-type integer tidak bertanda: `u8`, `u16`, `u32`, `u64`, `u128`, dan `usize`.

Angka setelah i ataupun u adalah panjang bit yang digunakan untuk menyimpan bilangan, jadi semakin besar angkanya, semakin banyak pula bit yang digunakan. 8 bit = 1 byte, jadi `i8` adalah 1 byte, `i64` sama dengan 8 byte, dan seterusnya. Type dengan panjang bit yang lebih lebar bisa menyimpan angka yang lebih besar. Contohnya, `u8` bisa menyimpan sampai dengan 255, sedangakn `u16` bisa menyimpan sampai dengan 65535. Juga `u128` bisa menyimpan sampai dengan 340282366920938463463374607431768211455.

Apa itu `isize` dan `usize`? Itu artinya compiler akan mencocokkan ukuran bit dengan arsitektur komputer anda. (Lebar bit pada komputer anda biasanya disebut sebagai **arsitektur**.) Jadinya `isize` dan `usize` pada komputer 32-bit adalah `i32` dan `u32`, juga `isize` dan `usize` pada komputer 64-bit adalah `i64` dan `u64`.

Ada banyak alasan mengapa ada banyak sekali type dari integer. Salah satu alasanya adalah performa: angka yang menggunakan byte yang kecil lebih cepat untuk diproses. Contohnya, angka -10 pada `i8` representasi binernya adalah `11110110`, namun pada `i128` representasi binernya adalah `11111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111110110`. Selain itu, ini juga adalah alasan lainnya:

Karakter di Rust disebut sebagai `char`. Setiap `char` memiliki angka: huruf `A` memiliki nilai 65, sedangkan karakter `友` ("kawan" dalam Bahasa Mandarin) memiliki nilai 21451. Angka-angka ini disebut sebagai "Unicode". Unicode yang menggunakan angka yang lebih kecil diperuntukkan bagi karakter yang sering digunakan, seperti A sampai Z, atau digit 0 sampai 9, maupun spasi.

```rust
fn main() {
    let first_letter = 'A';
    let space = ' '; // Sebuah spasi di antara ' ' juga adalah sebuah char
    let other_language_char = 'Ꮔ'; // Thanks to Unicode, bahasa lain seperti Cherokee juga tampil dengan baik
    let cat_face = '😺'; // Emojis juga adalah char
}
```

Karakter yang seringkali digunakan tersebut kebanyakan memiliki nilai dibawah dari 256. Dan ia cocok dan muat apabila disimpan ke dalam `u8`. Ingat, `u8` bisa menyimpan dari 0 sampai dengan 255, yang artinya, totalnya adalah 256. Ini artinya Rust bisa dengan aman melakukan **cast** dari `u8` ke `char`, menggunakan `as`. ("Cast `u8` ke `char`" artinya "perlakukan `u8` sebagai `char`")

Melakukan Cast menggunakan `as` sangatlah berguna karena Rust benar-benar sangat ketat. Rust selalu perlu untuk mengetahui type yang digunakan dan tidak akan membiarkan kita menggunakan tipe data yang berbeda meskipun masih sama-sama integer. Pada contoh dibawah ini, codenya tidak akan berjalan:

```rust
fn main() { // main() adalah dimana program Rust mulai berjalan. Sedangkan codenya dituliskan di dalam {} (curly brackets)

    let my_number = 100; // Kita tidak menuliskan type dari integer tersebut,
                         // sehingga Rust memilih i32. Rust selalu
                         // memilih i32 untuk integer apabila kita tidak
                         // memberitahukan compiler untuk menggunakan type yang berbeda.

    println!("{}", my_number as char); // ⚠️
}
```

Alasannya adalah sebagai berikut:

```text
error[E0604]: only `u8` can be cast as `char`, not `i32`
 --> src\main.rs:3:20
  |
3 |     println!("{}", my_number as char);
  |                    ^^^^^^^^^^^^^^^^^
```

Untungnya, kita bisa dengan mudah memperbaiki ini dengan `as`.Kita tidak bisa melakukan cast  `i32` sebagai `char`, tapi kita bisa cast `i32` sebagai `u8`. Dan karena itu, kita bisa melakukan yang sama pada `u8` ke `char`. Jadi pada satu baris kita menggunakan `as` untuk membuat my_number menjadi `u8`, dan kemudian mengubahnya lagi menjadi `char`. Compile code ini, dan ia akan berjalan:

```rust
fn main() {
    let my_number = 100;
    println!("{}", my_number as u8 as char);
}
```

Ia akan mencetak `d`, karena itu merupakan `char` yang bernilai 100.

Atau bisa juga dengan cara yang lebih mudah, caranya, kita beri tahu saja ke Rust bahwa `my_number` itu adalah `u8`. Begini caranya:

```rust
fn main() {
    let my_number: u8 = 100; //  ubah my_number ke my_number: u8
    println!("{}", my_number as char);
}
```

Jadi, itu adalah 2 alasan mengapa ada banyak sekali type integer di Rust. Ini adalah alasan lainnya: `usize` adalah type dimana Rust menggunakannya untuk keperluan *indexing*. (Indexing artinya "yang mana item yang pertama", "yang mana item yang kedua", dan seterusnya.) `usize` adalah type yang cocok untuk indexing, karena:

- Sebuah index tidak bisa negatif, jadi yang diperlukan adalah bilangan tidak bertanda (u)
- Ia harus berukuran besar, karena terkadang kita perlu untuk meng-index banyak hal, tapi
- Kita tidak bisa menggunakan u64 dikarenakan komputer 32-bit tidak bisa menggunakan u64.

Jadi Rust menggunakan, `usize` sehingga nantinya biarkan komputer kita yang menentukan integer terbesar yang mampu dijangkau oleh komputer kita.



Mari kita pelajari lebih lanjut tentang `char`. Kita bisa lihat bahwa `char` selalu berisi hanya 1 karakter, dan menggunakan `''`, bukan `""`.

Semua `chars` menggunakn 4 byte memori, karena sejauh ini 4 bytes cukup untuk menampung hampir semua karakter apapun yang ada sekarang.:
- Huruf-huruf dasar dan simbol biasanya memerlukan 1 dari 4 byte: `a b 1 2 + - = $ @`
- Aksara lainnya seperti German Umlauts memerlukan 2 dari 4 byte: `ä ö ü ß è é à ñ`
- Aksara Korea, Jepang atau Mandarin memerlukan 3 atau 4 byte: `国 안 녕`

Di saat menggunakan karakter sebagai bagian dari sebuah string, maka string akan di-encode untuk menggunakan sesedikit mungkin memori yang dibutuhkan untuk setiap karakter.

Kita bisa menggunakan `.len()` untuk melihat ini:

```rust
fn main() {
    println!("Size of a char: {}", std::mem::size_of::<char>()); // 4 bytes
    println!("Size of string containing 'a': {}", "a".len()); // .len() memberikan ukuran string dalam satuan byte
    println!("Size of string containing 'ß': {}", "ß".len());
    println!("Size of string containing '国': {}", "国".len());
    println!("Size of string containing '𓅱': {}", "𓅱".len());
}
```

Ia akan mencetak:

```text
Size of a char: 4
Size of string containing 'a': 1
Size of string containing 'ß': 2
Size of string containing '国': 3
Size of string containing '𓅱': 4
```

Anda bisa melihat bahwa `a` memerlukan 1 byte, aksara Jerman `ß` memerlukan 2 byte, aksara Jepang `国` memerlukan 3 byte, dan aksara Mesir kuno `𓅱` memerlukan 4 byte.

```rust
fn main() {
    let slice = "Hello!";
    println!("Slice is {} bytes.", slice.len());
    let slice2 = "안녕!"; // Korean for "hi"
    println!("Slice2 is {} bytes.", slice2.len());
}
```

Ia akan mencetak:

```text
Slice is 6 bytes.
Slice2 is 7 bytes.
```

`slice` memiliki 6 panjang 6 karakter dan memerlukan 6 byte, namun `slice2` memiliki panjang 3 karakter dan memerlukan 7 byte.

Jika `.len()` memberikan informasi tentang size dalam satuan byte, bagaimana tentang ukuran dalam satuan panjang karakter? Kita akan mempelajari tentang method ini nanti, tapi Anda bisa mengingat bahwa method `.chars().count()` bisa digunakan untuk itu. `.chars().count()` menjadikan apa yang kita tulis menjadi karakter dan menghitung berapa banyak karakternya.


```rust
fn main() {
    let slice = "Hello!";
    println!("Slice is {} bytes and also {} characters.", slice.len(), slice.chars().count());
    let slice2 = "안녕!";
    println!("Slice2 is {} bytes but only {} characters.", slice2.len(), slice2.chars().count());
}
```

Ia akan mencetak:

```text
Slice is 6 bytes and also 6 characters.
Slice2 is 7 bytes but only 3 characters.
```

## Type inference
**[See this chapter on YouTube](https://youtu.be/q1D2vpy3kEI)**

Type inference artinya adalah, jika anda tidak memberitahukan type yang anda gunakan, tapi compiler bisa memilihkannya, maka compiler yang nantinya akan memilihkan typenya. Compiler Rust selalu perlu mengetahui type dari sebuah variabel, namun anda tidak selalu perlu untuk memberitahukannya. Dan sebenarnya, biasanya anda memang tidak perlu memberitahukannya. Sebagai contoh, pada chapter sebelumnya, untuk `let my_number = 8`, `my_number` akan menjadi `i32`. Ini dikarenakan compiler secara default akan memilih i32 untuk integer jika anda tidak memberitahukannya. Namun jika anda memberitahukannya, seperti `let my_number: u8 = 8`, maka itu akan membuat `my_number` bertype `u8`, karena anda memberitahu ke compiler untuk menggunakan type `u8`.

Jadi, sebenarnya compiler bisa memilihkan typenya untuk kita. Tapi terkadang kita perlu memberitahukannya ke compiler, karena 2 alasan berikut:

1) Kita membuat sesuatu yang lumayan kompleks dan compiler tidak tahu type yang kita inginkan.
2) Kita menginginkan type yang berbeda (contohnya, anda ingin `i128`, bukan `i32`).

Untuk menambahkan type, tambahkan colon (titik dua) setelah nama variabel dan juga type yang anda perlukan.

```rust
fn main() {
    let small_number: u8 = 10;
}
```

Untuk angka, anda bisa menyebutkan typenya setelah angka. Anda sama sekali tidak memerlukan spasi. Cukup dituliskan tepat setelah angkanya.

```rust
fn main() {
    let small_number = 10u8; // 10u8 = 10 of type u8
}
```

Anda juga bisa menambahkan `_` jika anda ingin membuat angkanya menjadi mudah untuk dibaca.

```rust
fn main() {
    let small_number = 10_u8; // Ini menjadi lebih mudah untuk dibaca
    let big_number = 100_000_000_i32; // 100 juta menjadi mudah dibaca dengan _
}
```

Underscore (`_`) tidak akan mengubah nilainya. Ia berguna sekedar untuk mempermudah kita dalam pembacaan code. Dan sama sekali tidak masalah seberapa `_` yang kita gunakan:

```rust
fn main() {
    let number = 0________u8;
    let number2 = 1___6______2____4______i32;
    println!("{}, {}", number, number2);
}
```

Ia akan mencetak `0, 1624`.

### Floats

Floats adalah angka berkoma (memiliki decimal points). 5.5 adalah float, dan 6 adalah integer. 5.0 juga adalah sebuah float, dan 5. itu juga adalah float.

```rust
fn main() {
    let my_float = 5.; // Rust melihat ada . dan tahu bahwa itu adalah sebuah float
}
```

Namun, di Rust type ini bukan disebut sebagai `float`, mereka disebut sebagai `f32` dan `f64`. Ini sama seperti integer, yaitu angka setelah `f` menunjukkan panjang bit yang digunakan. Jika anda tidak menuliskan typenya, Rust akan memilihkan `f64`.

Tentu saja, hanya float dengan type yang sama yang bisa digunakan bersama-sama. Jadi kita tidak bisa menambahkan `f32` ke `f64`.

```rust
fn main() {
    let my_float: f64 = 5.0; // Ini adalah f64
    let my_other_float: f32 = 8.5; // Ini adalah f32

    let third_float = my_float + my_other_float; // ⚠️
}
```

Jika anda coba untuk menjalankan ini, compiler Rust akan mengatakan:

```text
error[E0308]: mismatched types
 --> src\main.rs:5:34
  |
5 |     let third_float = my_float + my_other_float;
  |                                  ^^^^^^^^^^^^^^ expected `f64`, found `f32`
```

Compiler memberitahukan "expected (type), found (type)" di saat Anda menggunakan type yang salah (tidak sesuai). Compiler akan memproses code anda seperti yang dituliskan pada komentar program dibawah ini:

```rust
fn main() {
    let my_float: f64 = 5.0; // Compiler melihat sebuah variabel f64
    let my_other_float: f32 = 8.5; // Compiler melihat sebuah f32. Ini merupakan type yang berbeda.
    let third_float = my_float + // Anda ingin menambahkan my_float dengan sesuatu, maka semestinya adalah f64 ditambahakan dengan f64. Maka, sekarang compiler berekspektasi bahwa ia akan ditambahkan dengan f64...
    let third_float = my_float + my_other_float;  // ⚠️ namun compiler justru menemukan f32. Sehingga compiler tidak bisa menambahkan keduanya.
}
```

Jadi, saat kita melihat "expected (type), found (type)", kita harus menemukan mengapa compiler berekspektasi/membutuhkan type yang berbeda.

Tentu saja, dengan float yang sederhana, code tersebut akan mudah untuk diperbaiki. Anda bisa melakukan cast `f32` sebagai `f64` dengan menggunakan `as`:

```rust
fn main() {
    let my_float: f64 = 5.0;
    let my_other_float: f32 = 8.5;

    let third_float = my_float + my_other_float as f64; // my_other_float as f64 = gunakan my_other_float seperti type f64
}
```

Atau dengan cara yang lebih mudah, hapus pendeklarasian typenya. ("pendeklarasian type" = "memberitahukan compiler Rust untuk menggunakan type yang dituliskan") Rust akan memilihkan typenya sehingga keduanya bisa melakukan operasi penjumlahan.

```rust
fn main() {
    let my_float = 5.0; // Rust akan memilih f64
    let my_other_float = 8.5; // Di bagian ini, Rust juga akan memilih f64

    let third_float = my_float + my_other_float;
}
```

Compiler Rust cukup cerdas dalam hal ini. Dan dia tidak akan memilih f64 jika kita memerlukan f32:

```rust
fn main() {
    let my_float: f32 = 5.0;
    let my_other_float = 8.5; // Biasanya, Rust akan memilih f64,

    let third_float = my_float + my_other_float; // tapi sekarang compiler Rust tahu bahwa kita perlu menambahkannya ke sebuah f32. Maka, compiler Rust akan memilih f32 untuk variabel my_other_float
}
```

## Printing 'hello, world!'
**See this chapter on YouTube: [Video 1](https://youtu.be/yYlPHRl2geQ), [Video 2](https://youtu.be/DTCSfBJJZb8)**

Apabila kita memulai sebuah program Rust yang baru, maka code awalnya akan selalu terlihat seperti ini:

```rust
fn main() {
    println!("Hello, world!");
}
```

- `fn` artinya adalah function/fungsi,
- `main` adalah fungsi yang memulai sebuah program,
- `()` artinya adalah, kita tidak memberikan variabel apapun ke fungsi untuk memulai program.

`{}` disebut sebagai **code block**. Ini adalah tempat dimana code akan ditulis.

`println!` adalah sebuah **macro** yang akan melakukan print ke console. Sebuah **macro** sama seperti sebuah fungsi yang akan menuliskan code untuk kita. Macro memiliki `!` setelah nama macronya dituliskan. Kita akan mempelajari tentang membuat macro di chapter-chapter selanjutnya. Tapi untuk sekarang, cukup diingat bahwa `!` itu artinya adalah sebuah macro.

Untuk mempelajari tentang `;`, terlebih dahulu kita buat fungsi yang lain. Pertama, di dalam `main`, kita akan mencetak angka 8:

```rust
fn main() {
    println!("Hello, world number {}!", 8);
}
```

`{}` pada `println!` artinya "letakkan variabelnya ke dalam sini". Maka dicetaklah `Hello, world number 8!`.


Kita bisa meletakkan lebih banyak `{}`, seperti yang kita lakukan sebelumnya:

```rust
fn main() {
    println!("Hello, worlds number {} and {}!", 8, 9);
}
```

Maka tercetak `Hello, worlds number 8 and 9!`.

Sekarang, ayo membuat sebuah fungsi.

```rust
fn number() -> i32 {
    8
}

fn main() {
    println!("Hello, world number {}!", number());
}
```

Ini juga akan mencetak `Hello, world number 8!`. Di saat Rust melihat ke `number()`, Rust akan melihatnya sebagai sebuah fungsi. Adapun fungsi ini:

- Tidak mengambil nilai dari variabel manapun (karena ia memiliki `()`)
- Me-return/mengembalikan `i32`. Tanda `->` (disebut sebagai "skinny arrow") menunjukkan apa yang fungsi akan kembalikan.

Di dalam fungsi tersebut, hanya ada `8`. Karena tidak ada `;`, maka itu adalah value yang akan di-return. Jika ada `;`, maka ia tidak akan me-return apapun (compiler akan me-return `()`). Rust tidak akan meng-compile ini jika terdapat sebuah `;`, karena returnnya bertype `i32` dan `;` me-return `()`, bukan `i32`:

```rust
fn main() {
    println!("Hello, world number {}", number());
}

fn number() -> i32 {
    8;  // ⚠️
}
```

```text
5 | fn number() -> i32 {
  |    ------      ^^^ expected `i32`, found `()`
  |    |
  |    implicitly returns `()` as its body has no tail or `return` expression
6 |     8;
  |      - help: consider removing this semicolon
```

Ini artinya "kamu beri tahu saya bahwa `number()` akan mengembalikan `i32`, tapi kamu tambahkan `;`, sehingga tidak bisa mengembalikan/me-return apapun". Oleh karena itu compiler menyarankan untuk menghapus semicolon/titik koma.

Kita juga bisa menulis `return 8;` tapi di Rust adalah normal untuk menghapus `;` dan juga `return`.

Apabila Anda ingin memasukkan variabel ke dalam sebuah fungsi, letakkan ia di dalam `()`. Anda perlu memberi variabel tersebut sebuah nama dan juga menuliskan typenya.

```rust
fn multiply(number_one: i32, number_two: i32) { // Dua buah i32 akan masuk ke fungsi. Kita akan menyebutnya sebagai number_one dan number_two.
    let result = number_one * number_two;
    println!("{} times {} is {}", number_one, number_two, result);
}

fn main() {
    multiply(8, 9); // Kita bisa memberikan angkanya secara langsung
    let some_number = 10; // Atau kita bisa mendeklarasikan 2 variabel
    let some_other_number = 2;
    multiply(some_number, some_other_number); // dan kita masukkan keduanya ke dalam fungsi
}
```

Kita juga bisa me-return `i32`. Cukup hilangkan semicolon pada bagian akhirnya:

```rust
fn multiply(number_one: i32, number_two: i32) -> i32 {
    let result = number_one * number_two;
    println!("{} times {} is {}", number_one, number_two, result);
    result // ini adalah variabel result yang bertype i32, yang akan kita return
}

fn main() {
    let multiply_result = multiply(8, 9); // Kita menggunakam multiply() untuk mencetak dan memberikan hasilnya ke variabel multiply_result
}
```

### Declaring variables and code blocks

Gunakan `let` untuk mendeklarasikan sebuah variabel (mendeklarasikan sebuah variabel = memberitahu Rust untuk membuat sebuah variabel).

```rust
fn main() {
    let my_number = 8;
    println!("Hello, number {}", my_number);
}
```

Variabel dimulai dan diakhiri di dalam sebuah code block `{}`. Pada contoh ini, `my_number` berakhir sebelum kita memanggil `println!`, karena ia berada di dalam code blocknya sendiri.

```rust
fn main() {
    {
        let my_number = 8; // my_number dimulai di sini.
                           // my_number berakhir di sini!
    }

    println!("Hello, number {}", my_number); // ⚠️ di bagian ini tidak ada my_number dan
                                             // println!() tidak bisa menemukannya
}
```

Anda bisa menggunakan code block untuk me-return sebuah value/nilai:

```rust
fn main() {
    let my_number = {
    let second_number = 8;
        second_number + 9 // Tidak ada semicolon, sehingga code block me-return 8 + 9.
                          // Ini bekernya mirip seperti sebuah fungsi
    };

    println!("My number is: {}", my_number);
}
```

Jika kamu menambahkan sebuah semicolon ke dalam block, maka ia akan mengembalikan `()` (tidak ada apapun):

```rust
fn main() {
    let my_number = {
    let second_number = 8; // deklarasi second_number,
        second_number + 9; // tambah 9 ke second_number
                           // namun kita tidak mengambalikannya!
                           // second_number hangus dibagian ini
    };

    println!("My number is: {:?}", my_number); // my_number menghasilkan ()
}
```

Lantas, mengapa kita menuliskan `{:?}` dan bukan `{}`? Saatnya kita membicarakan tentang itu.

## Display and debug
**[See this chapter on YouTube](https://youtu.be/jd3pC248c0o)**

Variabel sederhana di Rust bisa di-print/dicetak menggunakan `{}` di dalam `println!`. Namun  beberapa variabel tidak bisa, dan Anda perlu menggunakan **debug print**. Debug print adalah print untuk keperluan si programmer, karena debug print biasanya memunculkan lebih banyak informasi. Terkadang Debug tidak terlihat indah ataupun rapi, karena ia memiliki informasi ekstra untuk membantu Anda.

Bagaimana kita mengetahui jika kita membutuhkan `{:?}` dan bukan `{}`? Compiler akan memberi tahukannya untuk Anda. Sebagai contoh:

```rust
fn main() {
    let doesnt_print = ();
    println!("This will not print: {}", doesnt_print); // ⚠️
}
```

Jika kita menjalankan ini, compiler akan mengatakan:

```text
error[E0277]: `()` doesn't implement `std::fmt::Display`
 --> src\main.rs:3:41
  |
3 |     println!("This will not print: {}", doesnt_print);
  |                                         ^^^^^^^^^^^^ `()` cannot be formatted with the default formatter
  |
  = help: the trait `std::fmt::Display` is not implemented for `()`
  = note: in format strings you may be able to use `{:?}` (or {:#?} for pretty-print) instead
  = note: required by `std::fmt::Display::fmt`
  = note: this error originates in a macro (in Nightly builds, run with -Z macro-backtrace for more info)
```

Banyak sekali informasi yang diberikan oleh compiler. Tapi bagian terpentingnya adalah: `you may be able to use {:?} (or {:#?} for pretty-print) instead`. Ini artinya anda bisa mencoba `{:?}`, dan juga `{:#?}`. `{:#?}` disebut juga sebagai "pretty printing". Ini seperti `{:?}` namun mencetak dengan format yang berbeda.

Jadi, Display artinya mem-print/mencetak dengan `{}`, dan Debug artinya mem-print dengan `{:?}`.

Satu hal lagi: Anda juga bisa menggunakan `print!` tanpa `ln` jika anda tidak menghendaki  new line/baris baru.

```rust
fn main() {
    print!("This will not print a new line");
    println!(" so this will be on the same line");
}
```

Maka hasilnya adalah `This will not print a new line so this will be on the same line`.

### Smallest and largest numbers

Jika Anda ingin melihat angka yang terkecil dan yang terbesar, Anda bisa menggunakan MIN dan MAX. `std` artinya "standard library" dan memiliki semua fungsi-fungsi yang umum digunakan di Rust. Kita akan mempelajari tentang standard library kemudian. Tapi untuk sekarang ini, Anda bisa mengingat bahwa inilah cara mendapatkan angka terkecil dan juga angka terbesar dari sebuah type.

```rust
fn main() {
    println!("The smallest i8 is {} and the biggest i8 is {}.", std::i8::MIN, std::i8::MAX); // catatan: mencetak std::i8::MIN artinya "mencetak MIN yang berada di dalam bagian i8 pada standard library"
    println!("The smallest u8 is {} and the biggest u8 is {}.", std::u8::MIN, std::u8::MAX);
    println!("The smallest i16 is {} and the biggest i16 is {}.", std::i16::MIN, std::i16::MAX);
    println!("The smallest u16 is {} and the biggest u16 is {}.", std::u16::MIN, std::u16::MAX);
    println!("The smallest i32 is {} and the biggest i32 is {}.", std::i32::MIN, std::i32::MAX);
    println!("The smallest u32 is {} and the biggest u32 is {}.", std::u32::MIN, std::u32::MAX);
    println!("The smallest i64 is {} and the biggest i64 is {}.", std::i64::MIN, std::i64::MAX);
    println!("The smallest u64 is {} and the biggest u64 is {}.", std::u64::MIN, std::u64::MAX);
    println!("The smallest i128 is {} and the biggest i128 is {}.", std::i128::MIN, std::i128::MAX);
    println!("The smallest u128 is {} and the biggest u128 is {}.", std::u128::MIN, std::u128::MAX);

}
```

Beginilah hasilnya:

```text
The smallest i8 is -128 and the biggest i8 is 127.
The smallest u8 is 0 and the biggest u8 is 255.
The smallest i16 is -32768 and the biggest i16 is 32767.
The smallest u16 is 0 and the biggest u16 is 65535.
The smallest i32 is -2147483648 and the biggest i32 is 2147483647.
The smallest u32 is 0 and the biggest u32 is 4294967295.
The smallest i64 is -9223372036854775808 and the biggest i64 is 9223372036854775807.
The smallest u64 is 0 and the biggest u64 is 18446744073709551615.
The smallest i128 is -170141183460469231731687303715884105728 and the biggest i128 is 170141183460469231731687303715884105727.
The smallest u128 is 0 and the biggest u128 is 340282366920938463463374607431768211455.
```

## Mutability (changing)
**[See this chapter on YouTube](https://youtu.be/Nyyd6qn7dZY)**

Di saat Anda mendeklarasikan sebuah variabel dengan `let`, maka secara default (otomatis), ia akan immutable (tidak bisa diubah).

Pada contoh ini, codenya tidak akan berjalan:

```rust
fn main() {
    let my_number = 8;
    my_number = 10; // ⚠️
}
```

Compiler akan mengatakan: `error[E0384]: cannot assign twice to immutable variable my_number`. Ini dikarenakan variabelnya adalah immutable jika kita hanya menulis `let`.

Tapi terkadang kita ingin mengganti value dari variabel yang kita gunakan. Untuk membuat variabel yang bisa kita ubah valuenya, tambahkan `mut` setelah `let`:

```rust
fn main() {
    let mut my_number = 8;
    my_number = 10;
}
```

Dan sekarang menjadi tidak ada masalah.

Namun, kamu tidak bisa mengganti typenya: meskipun menggunakan `mut`, namun Rust tidak akan memperbolehkan Anda untuk melakukan hal tersebut. Sebagai contoh, code di bawah ini tidak akan berjalan:

```rust
fn main() {
    let mut my_variable = 8; // my_variable menggunakan type i32. Dan itu tidak dapat diubah
    my_variable = "Hello, world!"; // ⚠️
}
```

Anda akan melihat pesan "expected" dari compiler: `expected integer, found &str`. `&str` adalah sebuah type string yang sebentar lagi akan kita pelajari.

### Shadowing
**[See this chapter on YouTube](https://youtu.be/InULHyRGw7g)**

Shadowing artinya menggunakan `let` untuk mendeklarasikan variabel baru dengan nama yang sama sebagai variabel yang berbeda. Hal ini terlihat seperti mutability (bisa diubah), tapi ini adalah hal yang sama sekali berbeda. Beginilah bentuk dari Shadowing:

```rust
fn main() {
    let my_number = 8; // Typenya adalah i32
    println!("{}", my_number); // cetak 8
    let my_number = 9.2; // ini bertype f64 dengan nama yang sama. Tapi ini bukan merupakan variabel my_number yang pertama. - ini sama sekali berbeda!
    println!("{}", my_number) // cetak 9.2
}
```

Kita bisa menyebutnya sebagai "shadowed"/"menyembunyikan" `my_number` dengan sebuah "let binding" yang baru.

Lantas, apakah `my_number` yang ada di awal hangus/hancur? Tidak, namun di saat kita memanggil `my_number`, kita sekarang mendapatkan `my_number` yang bertype `f64`. Dan karena mereka berada pada scope block yang sama (`{}` yang sama), kita jadi sama sekali tidak bisa lagi melihat `my_number` yang pertama.

Tapi jika mereka ada di block yang berbeda, kita bisa melihat keduanya. Contohnya:

```rust
fn main() {
    let my_number = 8; // Typenya adalah i32
    println!("{}", my_number); // cetak 8
    {
        let my_number = 9.2; // Typenya adalah f64. It is not my_number (yang berada di awal)- keduanya berbeda!
        println!("{}", my_number) // Cetak 9.2
                                  // Tapi "shadowed variable" my_number telah hangus dibagian ini.
                                  // my_number yang pertama masih hidup!
    }
    println!("{}", my_number); // cetak 8
}
```

Jadi, di saat Anda men-shadow sebuah variabel, Anda tidak menghancurkannya it. Lebih tepatnya, Anda mem**block**nya.

Jadi, apa sebenarnya kegunaan dari shadowing? Shadowing tepat digunakan apabila anda perlu untuk mengubah sebuah variabel lebih sering. Bayangkan dimana anda ingin melakukan banyak operasi matematis menggunakan variabel:

```rust
fn times_two(number: i32) -> i32 {
    number * 2
}

fn main() {
    let final_number = {
        let y = 10;
        let x = 9; // mula-mula, x bernilai 9
        let x = times_two(x); // x di-shadow dengan nilai yang baru: 18
        let x = x + y; // x di-shadow lagi dengan nilai baru: 28
        x // me-return x: final_number sekarang bernilai x
    };
    println!("The number is now: {}", final_number)
}
```

Tanpa shadowing, kita harus memikirkan nama yang berbeda-beda, meskipun anda tidak peduli dengan x:

```rust
fn times_two(number: i32) -> i32 {
    number * 2
}

fn main() {
    // Anggaplkah kita menggunakan Rust tanpa shadowing
    let final_number = {
        let y = 10;
        let x = 9; // mula-mula, x bernilai 9
        let x_twice = times_two(x); // nama kedua untuk x
        let x_twice_and_y = x_twice + y; // nama ketiga x!
        x_twice_and_y // sayang sekali kita tidak menggunakan shadowing - padahal kita bisa saja langsung menggunakan x jika kita menggunakan shadowing
    };
    println!("The number is now: {}", final_number)
}
```

Intinya, kita bisa melihat shadowing di Rust pada kasus ini. Ia digunakan dimana kita ingin secara cepat mengambil sebuah variabel, melakukan operasi pada variabel tersebut, dan melakukan operasi lanjutan lainnya lagi. Dan Anda biasanya menggunakan shadowing ini untuk  quick variable yang dimana sebenarnya tidak begitu Anda pedulikan penamaannya.

## The stack, the heap, and pointers

Stack, heap, dan pointer sangatlah penting di Rust.

Stack dan heap adalah 2 tempat untuk menyimpan memori di komputer. Perbedaannya yang menonjol adalah sebagai berikut:

- Stack sangat cepat, sedangkan heap tidak terlalu cepat. Bukan berarti heap terlalu lambat, hanya saja stack selalu lebih cepat. Sayangnya, kita kita tidak bisa hanya menggunakan stack setiap saat, karena:
- Rust perlu untuk mengetahui ukuran sebuah variabel pada saat compile time. Sehingga variabel sederhana seperti `i32` akan ditaruh di stack, karena kita tahu berapa ukuran mereka secara tepat. Anda pasti mengetahui bahwa sebuah `i32` akan menggunakan 4 bytes, karena 32 bits = 4 byte. Jadinya `i32` bisa selalu ditaruh pada stack.
- Tapi ada beberapa type yang tidak bisa kita ketahui ukurannya pada compile time. Sedangkan stack perlu tahu berapa ukurannya secara tepat. Jadi apa yang kita lakukan? Pertama, kita taruh datanya pada heap, karena heap bisa menyimpan data dengan berbagai macam ukuran. Dan setelahnya, pointer (alamat dimana data diletakkan pada heap) disimpan ke stack. Cara ini sangatlah masuk akal karena kita selalu tahu ukuran dari sebuah pointer. Jadi, pada dasarnya komputer akan menuju ke stack, baca pointernya (mecari alamat dari data yang ada di heap), dan menuju ke heap dimana data tersebut disimpan.

Pointer terdengar rumit, padahal itu sebenarnya adalah konsep yang sederhana. Pointer itu seperti sebuah daftar isi dari sebuah buku. Bayangkan buku seperti di bawah ini:

```text
MY BOOK

DAFTAR ISI

Chapter                        Page
Chapter 1: My life              1
Chapter 2: My cat               15
Chapter 3: My job               23
Chapter 4: My family            30
Chapter 5: Future plans         43
```

Jadi, buku di atas tersebut seakan memiliki 5 buah pointer. Anda bisa membaca mereka dan mencari informasi yang mereka tuliskan pada halaman tersebut. Ada dimanakah chapter tentang "My life"? Ia ada di halaman 1 (it *points*/*mengarahkan* to page 1). Ada dimanakah chapter tentang "My job?" Ia ada di halaman 23.

Pointer yang biasa Anda lihat pada Rust biasa disebut sebagai **reference**. Ini adalah bagian terpenting untuk diketahui: sebuah reference akan mengarahkan kita ke memori dari sebuah value/nilai. Reference artinya kita *borrow*/*meminjam* value, tapi kita tidak memilikinya. Ini persis sama seperti buku yang kita bayangkan sebelumnya: daftar isi tidak memiliki informasi apapun. Setiap chapterlah yang justru memiliki informasi. Pada Rust, reference menggunakan tanda `&` di bagian depannya. Sehingga:

- `let my_variable = 8` akan membuat sebuah variabel biasa, sedangkan
- `let my_reference = &my_variable` akan membuat reference.

Anda bisa membaca `my_reference = &my_variable` seperti berikut: "my_reference adalah sebuah reference ke my_variable". Atau: "my_reference mengacu/menunjuk pada my_variable".

Ini berarti bahwa `my_reference` hanya sekedar melihat data dari `my_variable`. `my_variable` tetap menjadi pemilik atas data tersebut.

Anda juga bisa memiliki sebuah reference ke sebuah reference, ataupun ke sejumlah reference.

```rust
fn main() {
    let my_number = 15; // Ini bertype i32
    let single_reference = &my_number; //  Ini bertype &i32
    let double_reference = &single_reference; // Ini bertype &&i32
    let five_references = &&&&&my_number; // Ini bertype &&&&&i32
}
```

Kesemuanya itu adalah type yang berbeda. Jika dianalogikan, ini mirip seperti -> "teman dari temannya si X" berbeda dengan "temannya si X".

## More about printing

Di Rust, Anda bisa mem-print sesuatu dengan cara apapun yang Anda inginkan. Ini adalah yang harusnya diketahui tentang printing.

Menambahkan `\n` akan membuat sebuah new line, dan `\t` akan membuat sebuah tab:

```rust
fn main() {
    // Catatan: ini adalah print!, bukan println!
    print!("\t Start with a tab\nand move to a new line");
}
```

Ini akan mem-print:

```text
         Start with a tab
and move to a new line
```

Di dalam `""` Anda bisa menulis banyak baris tanpa ada masalah, tapi berhati-hatilah dengan spacing:

```rust
fn main() {
    // Catatan: Setelah menulis baris pertama, Anda perlu memulai lanjutannya pada bagian ujung kiri.
    // Jika Anda menulis langsung di bawah println!, maka ia akan menambahkan spasi
    println!("Inside quotes
you can write over
many lines
and it will print just fine.");

    println!("If you forget to write
    on the left side, the spaces
    will be added when you print.");
}
```

Berikut adalah hasil printnya:

```text
Inside quotes
you can write over
many lines
and it will print just fine.
If you forget to write
    on the left side, the spaces
    will be added when you print.
```

Jika anda ingin mencetak karakter seperti `\n` (biasa disebut dengan "escape characters"), Anda bisa menambahkan ekstra `\`:

```rust
fn main() {
    println!("Here are two escape characters: \\n and \\t");
}
```

Ini adalah hasilnya:

```text
Here are two escape characters: \n and \t
```

Terkadang kita menulis terlalu banyak `"` dan escape characters, dan menginginkan Rust untuk mengabaikan semua itu. Untuk melakukan hal ini, Anda bisa menambahkan `r#` pada bagian awal dan `#` pada bagian akhir.

```rust
fn main() {
    println!("He said, \"You can find the file at c:\\files\\my_documents\\file.txt.\" Then I found the file."); // Kita menggunakan \ 5 kali pada baris ini
    println!(r#"He said, "You can find the file at c:\files\my_documents\file.txt." Then I found the file."#)
}
```

Keduanya akan mencetak keluaran yangsama, namun dengan menggunakan `r#` membuat codenya menjadi lebih mudah dibaca oleh kita.

```text
He said, "You can find the file at c:\files\my_documents\file.txt." Then I found the file.
He said, "You can find the file at c:\files\my_documents\file.txt." Then I found the file.
```

Jika anda perlu mencetak sebuah `#` di dalamnya, maka Anda bisa memulainya `r##` dan mengakhirinya dengan `##`. Dan jika Anda memerlukannya lebih dari 1, Anda bisa menambahkan 1 lagi # pada setiap sisinya.

Ini adalah 4 buah contoh yang kita buat:

```rust
fn main() {

    let my_string = "'Ice to see you,' he said."; // single quotes
    let quote_string = r#""Ice to see you," he said."#; // double quotes
    let hashtag_string = r##"The hashtag #IceToSeeYou had become very popular."##; // Memiliki 1 buah #, sehingga kita memerlukan ## di setiap sisinya
    let many_hashtags = r####""You don't have to type ### to use a hashtag. You can just use #.""####; // Memiliki ###, sehingga kita memerlukan #### di setiap sisinya

    println!("{}\n{}\n{}\n{}\n", my_string, quote_string, hashtag_string, many_hashtags);

}
```

Ini adalah hasil cetakannya:

```text
'Ice to see you,' he said.
"Ice to see you," he said.
The hashtag #IceToSeeYou had become very popular.
"You don't have to type ### to use a hashtag. You can just use #."
```

`r#` memiliki kegunaan lainnya: dengan ini Anda bisa menggunakan keyword (seperti `let`, `fn`, dsb.) sebagai nama variable.

```rust
fn main() {
    let r#let = 6; // Nama variabelnya adalah let
    let mut r#mut = 10; // Nama variabelnya adalah mut
}
```

`r#` memiliki kegunaan seperti ini karena versi Rust yang lebih tua memiliki lebih sedikit keyword daripada Rust yang sekarang. Sehingga, dengan `r#` Anda bisa menghindari kesalahan dengan penamaan variabel yang mana sebelumnya ia bukan keywords.

Atau mungkin untuk alasan tertentu Anda *benar-benar* membutuhkan sebuah fungsi yang harus diberi nama `return`. Maka Anda bisa menuliskannya seperti ini:

```rust
fn r#return() -> u8 {
    println!("Here is your number.");
    8
}

fn main() {
    let my_number = r#return();
    println!("{}", my_number);
}
```

Maka hasilnya adalah seperti berikut:

```text
Here is your number.
8
```

Bisa jadi Anda sama sekali tidak memerlukannya, namun jika anda benar-benar perlu untuk menggunakan sebuah keyword untuk menjadi sebuah variable maka Anda bisa menggunakan `r#`.



Jika Anda ingin mencetak nilai byte dari sebuah `&str` atau `char`, Anda cukup menuliskan `b` sebelum stringnya ditulis. Ini bekerja untuk semua karakter ASCII. Ini adalah semua karakter ASCII:

```text
☺☻♥♦♣♠♫☼►◄↕‼¶§▬↨↑↓→∟↔▲▼123456789:;<=>?@ABCDEFGHIJKLMNOPQRSTUVWXYZ[\]^_`abcdefghijklmnopqrstuvwxyz{|}~
```

Sehingga di saat Anda mem-print code dibawah ini:

```rust
fn main() {
    println!("{:?}", b"This will look like numbers");
}
```

Beginilah hasilnya:

```text
[84, 104, 105, 115, 32, 119, 105, 108, 108, 32, 108, 111, 111, 107, 32, 108, 105, 107, 101, 32, 110, 117, 109, 98, 101, 114, 115]
```

Untuk sebuah `char`, ini disebut sebagai *byte*, dan untuk `&str` biasanya disebut sebagai *byte string*.


Anda juga bisa menggunakan `b` dan `r` bersamaan jika Anda memerlukannya:

```rust
fn main() {
    println!("{:?}", br##"I like to write "#"."##);
}
```

Dan ini adalah hasil printnya `[73, 32, 108, 105, 107, 101, 32, 116, 111, 32, 119, 114, 105, 116, 101, 32, 34, 35, 34, 46]`.



Dan ada juga Unicode escape yang akan mencetak karakter Unicode di dalam sebuah string: `\u{}`. Untuk mencetak hal tersebut, nilai hexadesimal ditulis di dalam `{}`. Berikut adalah contoh singkat tentang bagaimana cara untuk mendapatkan nilai Unicode, dan mencetaknya kembali dengan nilai hexadesimal yang didapatkan.

```rust
fn main() {
    println!("{:X}", '행' as u32); // Cast char sebagai u32 untuk mendapatkan nilai hexadesimal
    println!("{:X}", 'H' as u32);
    println!("{:X}", '居' as u32);
    println!("{:X}", 'い' as u32);

    println!("\u{D589}, \u{48}, \u{5C45}, \u{3044}"); // Cetak hexadesimal menggunakan unicode escape \u
}
```



Kita tahu bahwa `println!` bisa mencetak sesuatu menggunakan `{}` (untuk Display) dan `{:?}` (untuk Debug), juga `{:#?}` untuk pretty printing. Tapi masih ada banyak cara untuk melakukan print.

Sebagai contoh, jika Anda memiliki reference, Anda bisa menggunakan `{:p}` untuk mencetak *alamat pointer*. Alamat pointer adalah lokasi pada memori komputer Anda.

```rust
fn main() {
    let number = 9;
    let number_ref = &number;
    println!("{:p}", number_ref);
}
```

Program di atas akan mencetak `0xe2bc0ffcfc` atau alamat yang lain. Resultnya akan selalu berbeda setiap saat, tergantung dimana komputer Anda menyimpannya.

Anda juga bisa mencetak biner, hexadesimal dan oktal seperti berikut:

```rust
fn main() {
    let number = 555;
    println!("Binary: {:b}, hexadecimal: {:x}, octal: {:o}", number, number, number);
}
```

Hasilnya adalah `Binary: 1000101011, hexadecimal: 22b, octal: 1053`.

Anda juga bisa menambahkan angka untuk mengubah urutannya. Variabel pertama akan menjadi index ke-0, selanjutnya di index ke-1, dan seterusnya.

```rust
fn main() {
    let father_name = "Vlad";
    let son_name = "Adrian Fahrenheit";
    let family_name = "Țepeș";
    println!("This is {1} {2}, son of {0} {2}.", father_name, son_name, family_name);
}
```

`father_name` ada pada posisi ke-0, `son_name` ada pada posisi ke-1, dan `family_name` ada pada posisi ke-2. Maka kode tersebut akan mencetak `This is Adrian Fahrenheit Țepeș, son of Vlad Țepeș`.


Mungkin juga Anda memiliki sebuah string yang sangat rumit untuk dicetak dengan terlalu banyaknya variabel di dalam `{}`. Atau mungkin Anda perlu mencetak sebuah variabel lebih dari 1 kali. Itu bisa dilakukan dengan cara menambahkan nama ke dalam `{}`:

```rust
fn main() {
    println!(
        "{city1} is in {country} and {city2} is also in {country},
but {city3} is not in {country}.",
        city1 = "Seoul",
        city2 = "Busan",
        city3 = "Tokyo",
        country = "Korea"
    );
}
```

Hasilnya adalah seperti berikut:

```text
Seoul is in Korea and Busan is also in Korea,
but Tokyo is not in Korea.
```


Melakukan printing yang begitu kompleks juga sangat memungkinkan dilakukan di Rust jika Anda ingin menggunakannya. Beginilah cara menggunakannya:

{variable:padding alignment minimum.maximum}

Untuk memahami hal ini, perhatikan poin-poin berikut:

1) Apakah Anda menginginkan sebuah nama variabel? Tuliskan itu dibagian awal, seperti saat kita menulis {country} pada contoh di atas.
(Kemudian tambahkan sebuah `:` setelahnya jika Anda ingin melakukan hal yang lain)
2) Apakah Anda menginginkan sebuah padding character? Sebagai contoh, 55 dengan tiga buah "padding zeros" akan terlihat seperti 00055.
3) Alignment seperti apa yang diperlukan untuk padding tersebut (left / middle / right)?
4) Apakah Anda memerlukan panjang minimum? (cukup tuliskan angkanya)
5) Apakah Anda memerlukan panjang maximum? (tuliskan `.` setelah angka minimum beserta dengan angka maximumnya)

Sebagai contoh, kita ingin menulis "a" dengan lima buah karakter ㅎ di bagian kiri dan lima karakter ㅎ di bagian kanan:

```rust
fn main() {
    let letter = "a";
    println!("{:ㅎ^11}", letter);
}
```

Maka inilah hasil cetaknya `ㅎㅎㅎㅎㅎaㅎㅎㅎㅎㅎ`. Lihat kembali poin 1) sampai 5) untuk memahami bagaimana compiler membaca format ini.

- Apakah Anda menginginkan nama variabel? Di `{:ㅎ^11}` tidak ada nama variabel. Tidak ada apapun yang ditulis sebelum `:`.
- Apakah Anda menginginkan sebuah padding character? `{:ㅎ^11}` Ya. ㅎ ditulis setelah `:` dan memiliki sebuah `^`. `<` artinya lakukan padding dengan meletakkan karakter disebelah kiri, `>` berarti lakukan padding dengan meletakkan karakter disebelah kanan, dan `^` artinya karakter akan diletakkan di tengah.
- Apakah Anda memerlukan panjang minimum? `{:ㅎ^11}` Ya: Disitu tertulis angka 11.
- Apakah Anda memerlukan panjang maximum? `{:ㅎ^11}` Tidak: tidak ada `.` setelah minimum dan juga angka setelahnya.

Berikut adalah contoh dari berbagai cara untuk melakukan formatting.

```rust
fn main() {
    let title = "TODAY'S NEWS";
    println!("{:-^30}", title); // tidak ada nama variabel, pad menggunakan -, letakkan dibagian tengah, dengan panjang 30 karakter
    let bar = "|";
    println!("{: <15}{: >15}", bar, bar); // tidak ada nama variabel, pad menggunakan space, masing-masing 15 karakter di kiri dan juga kanan
    let a = "SEOUL";
    let b = "TOKYO";
    println!("{city1:-<15}{city2:->15}", city1 = a, city2 = b); // city1 dan city2 sebagai nama variabel, pad menggunakan -, satu ke kiri, dan satu lagi ke kanan
}
```

Berikut adalah hasil cetaknya:

```text
---------TODAY'S NEWS---------
|                            |
SEOUL--------------------TOKYO
```

## Strings
**[See this chapter on YouTube](https://youtu.be/pSyaGzGg26o)**

Rust memiliki 2 type strings yang umum: `String` dan `&str`. Apa perbedaannya?

- `&str` adalah sebuah string yang simple. Jika Anda menulis `let my_variable = "Hello, world!"`, Anda baru saja membuat `&str`. `&str` sangatlah cepat.
- `String` adalah string yang agak rumit. Ia cenderung lambat, namun memiliki banyak kegunaan. `String` adalah pointer, dengan data yang ditaruh pada heap.

Perlu dicatat bahwa `&str` memiliki `&` dibagian depannya karena Anda perlu sebuah reference untuk menggunakan `str`. Hal itu dikarenakan oleh hal yang sebelumnya telah kita bahas:  stack perlu tahu ukuran dari data. Oleh karena itu, kita berikan ia `&` yang membuat ia tahu ukurannya, dan voila, semuanya baik-baik saja. Dan juga, karena kita menggunakan `&` untuk berinteraksi dengan `str`, **you don't own it** (Anda tidak bisa memiliki valuenya, melainkan hanya sekedar meminjam untuk melihat valuenya). Sedangkan `String` adalah ***owned* type**. Secepatnya kita akan mempelajari tentang mengapa hal ini sangatlah penting untuk diketahui.

`&str` dan `String` keduanya menggunakan UTF-8. Sebagai contoh, anda bisa menulis:

```rust
fn main() {
    let name = "서태지"; // Ini adalah nama Korea. KArakter Korea muncul tanpa ada masalah, karena &str menggunakan UTF-8.
    let other_name = String::from("Adrian Fahrenheit Țepeș"); // Ț dan ș pun adalah UTF-8.
}
```

Anda bisa melihat pada `String::from("Adrian Fahrenheit Țepeș")` bahwa sangatlah mudah membuat sebuah `String` dari `&str`. Kedua type ini sangat erat terkait satu sama lain, meskipun keduanya berbeda.

Bahkan kita juga bisa menuliskan emoji, thanks to UTF-8.

```rust
fn main() {
    let name = "😂";
    println!("My name is actually {}", name);
}
```

Komputer Anda tentunya akan mencetak `My name is actually 😂` kecuali command line di komputer Anda tidak bisa mencetaknya. Maka ia akan mencetak `My name is actually �`. Akan tetapi Rust tidak memiliki problem dengan emojis atau Unicode lainnya.

Untuk memastikan bahwa kita telah paham tentang `&str`, mari kita lihat alasan lain tentang mengapa kita menggunakan `&` untuk `str`.

- `str` itu adalah dynamically sized type (dynamically sized = ukurannya bisa berubah-ubah). Contohnya, nama Korea "서태지" dan "Adrian Fahrenheit Țepeș" tentu memiliki ukuran yang tidak sama:

```rust
fn main() {

    println!("A String is always {:?} bytes. It is Sized.", std::mem::size_of::<String>()); // std::mem::size_of::<Type>() akan memberikan Anda informasi tentang ukuran yang digunakan oleh suatu type dalam satuan byte
    println!("And an i8 is always {:?} bytes. It is Sized.", std::mem::size_of::<i8>());
    println!("And an f64 is always {:?} bytes. It is Sized.", std::mem::size_of::<f64>());
    println!("But a &str? It can be anything. '서태지' is {:?} bytes. It is not Sized.", std::mem::size_of_val("서태지")); // std::mem::size_of_val() akan memberikan Anda informasi tentang ukuran yang digunakan oleh suatu variabel dalam satuan byte
    println!("And 'Adrian Fahrenheit Țepeș' is {:?} bytes. It is not Sized.", std::mem::size_of_val("Adrian Fahrenheit Țepeș"));
}
```

Beginilah hasilnya:

```text
A String is always 24 bytes. It is Sized.
And an i8 is always 1 bytes. It is Sized.
And an f64 is always 8 bytes. It is Sized.
But a &str? It can be anything. '서태지' is 9 bytes. It is not Sized.
And 'Adrian Fahrenheit Țepeș' is 25 bytes. It is not Sized.
```

Ini sebabnya kita membutuhkan &, karena `&` menghasilkan pointer, dan Rust tahu ukuran dari pointer. Sehingga pointer ditaruh di stack. Jika kita menulis `str` saja, Rust tidak tahu apa yang harus dilakukan karena ia tidak tahu ukurannya.



Ada banyak cara untuk membuat `String`. Ini adalah beberapa caranya:

- `String::from("This is the string text");` Ini adalah cara membuat String yang mana mengambil text (`&str`) dan membuatnya menjadi String.
- `"This is the string text".to_string()`. Ini adalah cara lain untuk mengubah &str menjadi String.
- Macro `format!`. Mirip seperti `println!`, hanya saja, yang berbeda adalah ia akan membuat String daripada melakukan printing. Jadi, anda bisa melakukan hal ini:

```rust
fn main() {
    let my_name = "Billybrobby";
    let my_country = "USA";
    let my_home = "Korea";

    let together = format!(
        "I am {} and I come from {} but I live in {}.",
        my_name, my_country, my_home
    );
}
```

Sekarang kita memiliki String yang bernama *together*, akan tetapi ia tidak diprint.

Cara lain untuk membuat String adalah menggunakan method `.into()`, akan tetapi ini agak sedikit berbeda karena `.into()` tidak hanya digunakan untuk membuat `String`. Beberapa type  bisa dengan mudah dikonversi ke dan dari type yang lainnya menggunakan `From` dan `.into()`. Atau dengan kata lain, jika kita punya `From`, maka kita juga punya `.into()`. `From` sangatlah jelas karena kita telah mengetahui typenya: kita tahu bahwa `String::from("Some str")` adalah `String` yang dikonversi dari `&str`. Tapi, dengan `.into()`, terkadang compiler tidak tahu kita ingin mengubahnya menjadi type apa:

```rust
fn main() {
    let my_string = "Try to make this a String".into(); // ⚠️
}
```

Rust tidak tahu type apa yang Anda inginkan, karena banyak type bisa dibuat dari `&str`. Compiler akan menegur kita dengan berkata, "Aku bisa mengkonversi type `&str` ke banyak type lainnya. Anda mau yang mana?"

```text
error[E0282]: type annotations needed
 --> src\main.rs:2:9
  |
2 |     let my_string = "Try to make this a String".into();
  |         ^^^^^^^^^ consider giving `my_string` a type
```

Untuk menyelesaikan error tersebut, Anda bisa menggunakan cara seperti ini:

```rust
fn main() {
    let my_string: String = "Try to make this a String".into();
}
```

Voila! Akhirnya anda bisa membuat String menggunakan `.into()`.

## const and static
**[See this chapter on YouTube](https://youtu.be/Ky3HqkWUcI0)**

Ada 2 cara lain untuk mendeklarasikan variabel, tidak hanya dengan `let`. Yaitu dengan menggunakan `const` dan `static`. Juga, Rust tidak akan menggunakan type inference untuk kedua cara ini: Anda perlu menulis type untuk keduanya. Pendeklarasian dengan cara ini berguna untuk mendeklarasikan variabel yang nilainya tidak berubah (`const` artinya constant/konstanta). Yang membuat keduanya berbeda adalah:

- `const` mirip seperti `let`, hanya saja valuenya yang tidak berubah,
- `static` sama seperti `const`, akan tetapi ia memiliki lokasi memori yang tetap (fixed) dan bisa berlaku sebagai global variable.

Jadi, bisa dibilang bahwa keduanya hampir sama. Meskipun Rust programmers hampir sering menggunkana `const`.

Keduanya ditulis dengan HURUF_KAPITAL, dan biasanya ditulis di luar `main`, sehingga mereka tidak hangus diseluruh bagian code program.

Baginilah contohnya: `const NUMBER_OF_MONTHS: u32 = 12;` dan `static SEASONS: [&str; 4] = ["Spring", "Summer", "Fall", "Winter"];`

## More on references
**[See this chapter on YouTube](https://youtu.be/R13sQ8SNoEQ)**

Reference sangat penting di Rust. Rust menggunakan reference untuk memastikan bahwa semua akses ke memori bebanr-benar aman. Kita tahu bahwa kita menggunakan `&` untuk membuat reference:

```rust
fn main() {
    let country = String::from("Austria");
    let ref_one = &country;
    let ref_two = &country;

    println!("{}", ref_one);
}
```

Hasil cetaknya adalah `Austria`.

Pada code tersebut, `country` bertype `String`. Kemudian kita membuat 2 references ke `country`. Keduanya memiliki type `&String`, yang mana Anda bisa menyebutnya dengan "reference ke sebuah String". Kita bisa membuat tiga reference ataupun ratusan reference ke `country`, dan itu sama sekali tidak masalah.

Tapi untuk kasus yang ini, tentunya akan menjadi masalah:

```rust
fn return_str() -> &str {
    let country = String::from("Austria");
    let country_ref = &country;
    country_ref // ⚠️
}

fn main() {
    let country = return_str();
}
```

Fungsi `return_str()` membuat sebuah String, kemudian ia membuat reference ke String tersebut. Sesudah itu, reference yang tadi dibuat akan di-return. Akan tetapi, String `country` hanya hidup (bisa diakses) pada fungsi tersebut, dan kemudian ia mati (hancur/hangus). Setelah variabel tersebut mati, komputer akan membersihkan memori dan menggunakannya untuk hal lain. Jadi, setelah fungsi tersebut selesai, `country_ref` mereferensi ke memori yang sebenarnya sudah menghilang, dan itu berbahaya. Rust mencegah kita dari membuat kesalahan pada memori, salah satunya adalah kesalahan yang seperti ini.

Ini adalah bagian terpenting tentang "owned" type yang kita sebut-sebut di atas. Karena Anda memiliki `String`, Anda bisa memindahkan kepemilikannya. Hanya saja, `&String` akan mati jika `String`nya mati, jadinya Anda tidak bisa memindahkan "ownership" dengan cara seperti ini.

## Mutable references
**[See this chapter on YouTube](https://youtu.be/G48z6Rv76vc)**

Jika Anda ingin menggunakan reference untuk mengubah data, Anda bisa menggunakan mutable reference. Untuk mengunakan mutable reference, Anda hanya perlu menuliskan `&mut` menggantikan `&`.

```rust
fn main() {
    let mut my_number = 8; // jangan lupa untuk menuliskan mut disini!
    let num_ref = &mut my_number;
}
```

Jadi, apa type keduanya? `my_number` menggunakan type `i32`, dan `num_ref` bertype `&mut i32` (kita bisa menyebutnya "mutable reference ke sebuah type`i32`").

Mari kita gunakan num_ref untuk menambahkan 10 ke my_number. Tapi Anda tidak bisa menulis `num_ref += 10`, karena value dari `num_ref` tidak bertype `i32`, melainkan `&i32`. Value yang asli, ia berada pada `i32`. Untuk mengakses tempat dimana value aslinya tersimpan, kita menggunakan `*`. `*`, yang berarti "Saya tidak mau referencenya, yang saya inginkan adalah value aslinya". Dengan kata lain, setiap `*` adalah lawan dari `&`. Dan juga, setiap penggunaan `*` akan menghapus sebuah `&`.

```rust
fn main() {
    let mut my_number = 8;
    let num_ref = &mut my_number;
    *num_ref += 10; // Use * to change the i32 value.
    println!("{}", my_number);

    let second_number = 800;
    let triple_reference = &&&second_number;
    println!("Second_number = triple_reference? {}", second_number == ***triple_reference);
}
```

Hasilnya adalah seperti berikut:

```text
18
Second_number = triple_reference? true
```

Karena di saat kita menggunakan `&` disebut sebagai "referencing", maka menggunakan `*` disebut sebagai "**de**referencing".

Rust memiliki 2 aturan untuk mutable dan immutable reference. Aturan ini sangatlah penting, dan juga mudah diingat karena aturan ini sangatlah masuk akal.

- **Aturan 1**: Jika kita hanya memiliki immutable references, kita bisa memilikinya sebanyak yang kita mau. 1, boleh. 3, juga boleh. 1000, juga tidak apa. Tidak masalah.
- **Aturan 2**: Jika Anda memiliki mutable reference, Anda hanya boleh memiliki 1 saja. Juga, Anda tidak bisa memiliki sebuah immutable reference **dan** sebuah mutable reference sekaligus.

Ini dikarenakan mutable references bisa mengubah data. Anda bisa saja mendapatkan problem jika Anda mengubah data di saat  references yang lain sedang membaca data tersebut.


Cara yang baik untuk memahami hal ini adalah dengan cara membayangkan tentang presentasi Powerpoint.

Situasi pertama ini adalah tentang kasus **hanya 1 mutable reference**.

Situasi pertama: Seorang pegawai sedang membuat presentasi Powerpoint. Ia ingin Managernya membantunya untuk membuatnya. Pegawai tersebut memberikan memberikan informasi login komputernya ke Managernya, dan meminta bantuan pada Manager tersebut untuk mengedit presentasinya. Sekarang Managernya memiliki sebuah "mutable reference" yang merujuk kepada presentasi si pegawai. Si Manager bisa membuat perubahan yang dia inginkan di presentasi tersebut, dan logout dari komputer tersebut setelahnya. Hal ini boleh dilakukan, karena tidak ada orang lain yang sedang melihat presentasi tersebut.

Situasi kedua ini adalah tentang kasus **yang ada hanya immutable references**.

Situasi kedua: Si Pegawai menunjukkan presentasinya 100 orang. Semua 100 orang ini tentunya bisa melihat presentasi si Pegawai. Mereka semua memiliki "immutable reference" yang merujuk kepada presentasi si pegawai. Hal ini boleh dilakukan, karena mereka bisa melihatnya namun tidak ada seorang pun yang bisa mengubah presentasi tersebut.

Situasi ketiga ini adalah dimana **datangnya masalah**.

Situasi ketiga: Si pegawai memberikan akses login komputernya ke Managernya. Managernya sekarang memiliki "mutable reference". Kemudian si Pegawai tadi menujukkan presentasinya ke 100 orang, di saat manager masih login di komputer tersebut . Ini sama sekali tidak baik, karena manager masih dalam kondisi login dan bisa melakukan apapun. Bisa saja si manager lupa bahwa ia sedang menggunakan komputer orang lain dan tidak sengaja sedang menulis email untuk ibunya! Jika itu terjadi, maka 100 orang yang sedang melihat presentasi tadi justru melihat si Manager menulis email tersebut. Hal seperti inilah yang tidak kita harapkan.

Ini adalah contoh code yang mana ada mutable borrow (mutable reference) sekaligus dengan immutable borrow (immutable reference) yang merujuk ke satu variabel:

```rust
fn main() {
    let mut number = 10;
    let number_ref = &number;
    let number_change = &mut number;
    *number_change += 10;
    println!("{}", number_ref); // ⚠️
}
```

Maka compiler akan mencetak pesan yang cukup membantu untuk menunjukkan kita letak masalahnya.

```text
error[E0502]: cannot borrow `number` as mutable because it is also borrowed as immutable
 --> src\main.rs:4:25
  |
3 |     let number_ref = &number;
  |                      ------- immutable borrow occurs here
4 |     let number_change = &mut number;
  |                         ^^^^^^^^^^^ mutable borrow occurs here
5 |     *number_change += 10;
6 |     println!("{}", number_ref);
  |                    ---------- immutable borrow later used here
```

Akan tetapi, code dibawah ini berjalan. Kira-kira kenapa?

```rust
fn main() {
    let mut number = 10;
    let number_change = &mut number; // buat sebuah mutable reference
    *number_change += 10; // gunakan mutable reference untuk menambahkan 10
    let number_ref = &number; // buat sebuah immutable reference
    println!("{}", number_ref); // cetak immutable reference
}
```

Dan tercetak `20` tanpa ada problem apapun. Ini bisa bekerja karena compiler cukup cerdas untuk mengerti code yang kita tulis. It knows that we used `number_change` to change `number`, but didn't use it again. So here there is no problem. We are not using immutable and mutable references together.

Pada versi awal Rust, code seperti ini akan menghasilkan error, namun sekarang ini compiler Rust jauh lebih cerdas. Ia tidak hanya memahami apa yang kita tuliskan, tapi juga paham bagaimana kita menuliskannya secara keseluruhan.

### Shadowing again

Masih ingat di saat kita menyebutkan bahwa shadowing tidak akan **menghancurkan** sebuah value, akan tetapi **memblocknya**? Sekarang kita bisa menggunakan references untuk melihatnya.

```rust
fn main() {
    let country = String::from("Austria");
    let country_ref = &country;
    let country = 8;
    println!("{}, {}", country_ref, country);
}
```

Yang mana yang merupakan hasil cetaknya? `Austria, 8` atau `8, 8`?
Jawabannya adalah `Austria, 8`. Pertama, kita deklarasikan `String` yang bernama `country`. Kemudian kita membuat reference `country_ref` yang merujuk ke string tersebut. Kemudian kita shadow variabel country menggunakan 8, yang mana ia bertype `i32`. Variabel `country` yang pertama tidak hangus, jadinya `country_ref` tetap berisi "Austria", bukan "8". Di bawah ini adalah code yang sama dengan komentar yang menunjukkan bagaimana code tersebut bekerja:

```rust
fn main() {
    let country = String::from("Austria"); // Sekarang kita memiliki String yang bernama country
    let country_ref = &country; // country_ref adalah reference ke String yang kita buat tadi. Dan ini tidak akan berubah
    let country = 8; // Sekarang kita memiliki variabel yang bernama country lagi dengan type i8. Tapi variabel ini tidak berhubungan dengan variabel country yang ada di awal, ataupun dengan variabel country_ref
    println!("{}, {}", country_ref, country); // country_ref tetap me-refer (merujuk) ke data String::from("Austria").
}
```

## Giving references to functions
**See this chapter on YouTube: [immutable references](https://youtu.be/mKWXt9YTavc) and [mutable references](https://youtu.be/kJV1wIvAbyk)**

Reference sangat berguna untuk function (fungsi). Aturan di Rust tentang value adalah: setiap value hanya bisa dimiliki oleh satu owner (pemilik).

Code dibawah ini tidak akan berjalan:

```rust
fn print_country(country_name: String) {
    println!("{}", country_name);
}

fn main() {
    let country = String::from("Austria");
    print_country(country); // akan mencetak "Austria"
    print_country(country); // ⚠️ Kita coba cetak sekali lagi!
}
```

Code di atas tidak berjalan karena `country` telah hangus. Begini penjelasannya:

- Step 1: Kita membuat `String` bernama `country`. `country` adalah pemiliknya (owner).
- Step 2: Kita berikan `country` ke fungsi `print_country`. `print_country` tidak memiliki `->`, sehingga ia tidak me-return apapun. Setelah `print_country` selesai, `String` yang kita buat sekarang hangus.
- Step 3: Kita mencoba untuk memberikan `country` ke `print_country`, akan tetapi kita sudah melakukannya sebelumnya. Sehingga kita tidak memiliki `country` lagi untuk diberikan ke fungsi `print_country`.

Kita bisa membuat `print_country` memberikan kembali `String`, namun cara ini terlihat agak aneh.

```rust
fn print_country(country_name: String) -> String {
    println!("{}", country_name);
    country_name // ini adalah kembaliannya
}

fn main() {
    let country = String::from("Austria");
    let country = print_country(country); // sekarang kita mesti menggunakan let disini untuk mengambil kembali String
    print_country(country);
}
```

Ini adalah hasil cetaknya:

```text
Austria
Austria
```

Ada cara yang lebih baik untuk memperbaiki hal ini, yaitu dengan cara menambahkan `&`.

```rust
fn print_country(country_name: &String) {
    println!("{}", country_name);
}

fn main() {
    let country = String::from("Austria");
    print_country(&country); // hasil cetaknya adalah "Austria"
    print_country(&country); // Kita cetak lagi! Voila! hasilnya juga keluar
}
```

`print_country()` adalah fungsi yang mengambil reference ke `String`: atau dengan kata lain `&String`. Oleh karena itu, kita berikan ia reference ke country dengan menulis `&country`. Atau bisa dibilang bahwa `String` berkata ke `print_country()`, "Ini saya pinjamkan `&country`. Kamu bisa liat isinya, tapi tetap aku yang punya datanya".

Sekarang saatnya kita lakukan sesuatu yang serupa dengan mutable reference. Ini adalah contoh dari sebuah fungsi yang menggunakan variabel yang mutable.

```rust
fn add_hungary(country_name: &mut String) { // pertama fungsi akan mengambil mutable reference sebagai parameternya
    country_name.push_str("-Hungary"); // push_str() menambahkan &str ke String
    println!("Now it says: {}", country_name);
}

fn main() {
    let mut country = String::from("Austria");
    add_hungary(&mut country); // kita juga perlu memberikannya sebuah mutable reference.
}
```

Maka beginilah hasilnya `Now it says: Austria-Hungary`.

Maka, kesimpulannya adalah sebagai berikut:

- `fn function_name(variable: String)` mengambil `String` dan mengambil kepemilikannya it. Jika ia tidak me-return apapun, maka variabelnya akan mati di dalam fungsinya.
- `fn function_name(variable: &String)` meminjam `String` dan hanya bisa melihat isi dari variabel tersebut
- `fn function_name(variable: &mut String)` meminjam `String` dan bisa merubah isinya

Ini adalah contoh yang terlihat seperti sebuah mutable reference, tapi sebenarnya berbeda.

```rust
fn main() {
    let country = String::from("Austria");  // country tidak mutable, tapi kita mendapatkan hasil print Austria-Hungary.
                                            // Bagaimana bisa?
    adds_hungary(country);
}

fn adds_hungary(mut country: String) { // Inilah sebabnya: adds_hungary mengambil String dan mendeklarasikannya sebagai mutable!
    country.push_str("-Hungary");
    println!("{}", country);
}
```

Kenapa hal ini bisa terjadi? Ini dikarenakan `mut country` bukan sebuah reference: sekarang `adds_hungary` yang memiliki value dari `country`. (Ingat, yang ia ambil adalah `String`, bukan `&String`). Di saat Anda memanggil `adds_hungary`, ia menjadi pemilik sepenuhnya. Sekarang `country` bukan lagi pemilik dari `String::from("Austria")`. Jadinya `adds_hungary` bisa mengambil `country` sebagai mutable, dan hal seperti ini sangatlah aman untuk dilakukan.

Masih ingat dengan permisalan tentang pegawai dan managernya yang kita ceritakan di atas? Pada case ini, ini seperti pegawai tersebut memberikan komputer miliknya, beserta akses dan juga datanya ke si manager. Si pegawai tidak lagi bisa menyentuh komputer tersebut (karena kepemilikan komputer tersebut telah berpindah), sehingga si manager bisa melakukan apa saja yang ia inginkan pada komputer tersebut.

## Copy types

Beberapa type di Rust benar-benar sangat simple. Mereka biasa disebut sebagai **copy types**. Simple types ini semuanya disimpan pada stack, dan compiler tahu ukuran mereka. Yang artinya bahwa mereka bisa dengan mudah untuk di-copy, jadi compiler selalu meng-copy di saat Anda mengirimnya ke sebuah function. Ia selalu meng-copy karena mereka cukup kecil dan mudah sehingga tidak ada alasan untuk tidak meng-copynya. Jadi Anda tidak perlu khawatir tentang ownership pada type-type ini.

Type-type yang dimaksud ini adalah: integer, float, boolean (`true` dan `false`), dan `char`.

Bagaimana kita bisa tahu jika sebuah type **mengimplementasikan** copy? (implementasi = menerapkan) Kita bisa periksa hal ini pada dokumentasi. Contohnya, ini adalah dokumentasi untuk char:

[https://doc.rust-lang.org/std/primitive.char.html](https://doc.rust-lang.org/std/primitive.char.html)

Pada bagian kiri dari dokumentasi tersebut, anda bisa menemukan section **Trait Implementations**. Di situ, Anda akan melihat contoh implementation seperti **Copy**, **Debug**, dan **Display**. Dari dokumentasi itu, kita jadi tahu bahwa `char`:

- akan melakukan copy di saat Anda mengirimnya ke function (**Copy**)
- bisa melakukan print dengan menggunakan `{}` (**Display**)
- bisa melakukan print dengan menggunakan `{:?}` (**Debug**)

```rust
fn prints_number(number: i32) { // Pada fungsi ini, tidak ada -> sehingga ia tidak me-return apapun
                             // Jika number bukan copy type, ia akan mengambilnya dan kita tidak bisa menggunakannya lagi
    println!("{}", number);
}

fn main() {
    let my_number = 8;
    prints_number(my_number); // Cetak 8. prints_number mengambil copy dari my_number
    prints_number(my_number); // Cetak 8 lagi.
                              // Tidak ada problem, karena my_number adalah copy type!
}
```

Tapi jika kita melihat dokumentasi dari String, ia bukanlah copy type.

[https://doc.rust-lang.org/std/string/struct.String.html](https://doc.rust-lang.org/std/string/struct.String.html)

Pada bagian kiri dari dokumentasi tersebut **Trait Implementations**, Anda bisa melihatnya secara alphabetical order. A, B, C... dan di sana tidak ada **Copy** di C. Yang ada di sana justru adalah **Clone**. **Clone** mirip dengan **Copy**, tapi biasanya memerlukan memori yang lebih. Juga, anda perlu memanggilnya menggunakan method `.clone()` - ia tidak akan melakukan clone dengan sendirinya.

Di contoh ini, `prints_country()` akan mencetak nama negara, yang mana adalah sebuah `String`. Kita ingin mencetaknya 2 kali, tapi kita tidak bisa melakukannya:

```rust
fn prints_country(country_name: String) {
    println!("{}", country_name);
}

fn main() {
    let country = String::from("Kiribati");
    prints_country(country);
    prints_country(country); // ⚠️
}
```

Tapi sekarang kita mengerti mengapa pesan ini muncul.

```text
error[E0382]: use of moved value: `country`
 --> src\main.rs:4:20
  |
2 |     let country = String::from("Kiribati");
  |         ------- move occurs because `country` has type `std::string::String`, which does not implement the `Copy` trait
3 |     prints_country(country);
  |                    ------- value moved here
4 |     prints_country(country);
  |                    ^^^^^^^ value used here after move
```

Bagian terpentingnya adalah `which does not implement the Copy trait`. Sedangkan di dokumentasi kita bisa lihat bahwa mengimplementasikan trait (sifat) `Clone`. Jadi kita bisa menambahkan `.clone()` ke code tersebut. Hal ini akan membuat sebuah clone, dan kita kirimkan clone tersebut ke function. Sekarang `country` tetap hidup, sehingga kita bisa menggunakannya.

```rust
fn prints_country(country_name: String) {
    println!("{}", country_name);
}

fn main() {
    let country = String::from("Kiribati");
    prints_country(country.clone()); // buat clonenya berikan clone tersebut ke function. Hanya clonenya saja yang masuk ke function, dan variabel country tetap hidup
    prints_country(country);
}
```

Dan tentu saja, jika `String` sangat besar, `.clone()` bisa menggunakan banyak memory. Satu `String` bisa saja panjangnya sama seperti isi buku, dan setiap kita menggunakan `.clone()`, ia akan menyalin buku tersebut. Jadi, menggunakan `&` untuk membuat reference jauh lebih cepat, kalau memang bisa dilakukan. Contohnya, code di bawah akan melakukan `.push_str()` sebuah `&str` ke dalam `String` dan kemudian membuat clone setiap ia digunakan oleh function:

```rust
fn get_length(input: String) { // mengambil ownership dari String
    println!("It's {} words long.", input.split_whitespace().count()); // lakukan split untuk menghitung jumlah kata
}

fn main() {
    let mut my_string = String::new();
    for _ in 0..50 {
        my_string.push_str("Here are some more words "); // push kalimat (&str)
        get_length(my_string.clone()); // buat clonenya setiap saat (setiap ia digunkan oleh fungsi)
    }
}
```

It prints:

```text
It's 5 words long.
It's 10 words long.
...
It's 250 words long.
```

Cara di atas menggunakan 50 clone, dimana clonenya dilakukan setelah melakukan push. Sehingga, setiap iterasi selalu memakan memori dua kali lebih besar dari panjang `my_string`. Ini adalah cara dimana kita menggunakan reference untuk melakukan hal yang sama, dimana cara yang ini lebih baik daripada melakukan clone:

```rust
fn get_length(input: &String) {
    println!("It's {} words long.", input.split_whitespace().count());
}

fn main() {
    let mut my_string = String::new();
    for _ in 0..50 {
        my_string.push_str("Here are some more words ");
        get_length(&my_string);
    }
}
```

Alih-alih membuat 50 clone seperti cara sebelumnya, code yang ini justru sama sekalitidak perlu melakukan salinan.



### Variables without values

Variabel tanpa sebuah value disebut sebagai "uninitialized" variable. Uninitialized artinya "tidak diinisialisasi" atau "belum dimulai". Cukup mudah untuk membuatnya: cukup tuliskan `let` dan nama variabelnya:

```rust
fn main() {
    let my_variable; // ⚠️
}
```

Namun Anda tidak bisa menggunakannya untuk saat ini, dan Rust tidak bisa meng-compilenya apabila ada sesuatu yang uninitialized.

Tapi terkadang mereka sangat berguna. Contohnya adalah di saat Anda menemukan kasus seperti:

- Anda memiliki code block dan di dalam code block tersebut terdapat variabel yang memiliki value, dan
- Variabel tersebut perlu untuk tetap hidup di luar dari code block.

```rust
fn loop_then_return(mut counter: i32) -> i32 {
    loop {
        counter += 1;
        if counter % 50 == 0 {
            break;
        }
    }
    counter
}

fn main() {
    let my_number;

    {
        // Anggap saja kita memerlukan code block pada bagian ini
        let number = {
            // Anggap saja pada bagian ini adalah proses untuk memproses angka
            // Dan dari proses ini, akhirnya kita mendapatkan hasil akhirnya
            57
        };

        my_number = loop_then_return(number);
    }

    println!("{}", my_number);
}
```

Maka program tersebut akan mencetak `100`.

Anda bisa melihat bahwa `my_number` dideklarasikan di dalam fungsi `main()`, jadinya ia akan tetap hidup sampai akhir program. Akan tetapi, ia mengambil valuenya dari dalam loop. Namun, value tersebut (hasil dari fungsi loop) akan tetap hidup selama `my_number` juga tetap hidup, karena `my_number` yang memiliki valuenya. Dan jika Anda justru menulis `let my_number = loop_then_return(number)` di dalam block tersebut, maka valuenya akan mati (hangus).

Untuk membantu mempermudah Anda membayangkannya, kita buat satu contoh kasus lagi. Kita sama-sama tahu bahwa`loop_then_return(number)` memberikan result 100, jadi kitaa hapus saja fungsi tersebut dan kita ganti menjadi `100`. Juga, sekarang kita tidak memerlukan `number` jadinya kita hapus juga variabelnya. Maka, sekarang codenya akan terlihat seperti ini:

```rust
fn main() {
    let my_number;
    {
        my_number = 100;
    }

    println!("{}", my_number);
}
```

Jadi, cara kerjanya hampir mirip seperti dengan `let my_number = { 100 };`.

Dan juga, yang perlu dicatat adalah `my_number` bukan `mut`. Kembali ke contoh yang sebelumnya (yang menggunakan fungsi loop), kita tidak memberikan value apapun sampai akhirnya kita memberikannya angka berkelipatan 50, jadi sebenarnya nilainya tidak pernah berubah. Pada akhirnya, code dari `my_number` itu hanya `let my_number = 100;`, hanya saja pada kasus uninitialized variable ini, `my_number` menunggu untuk diinisialisasi.

## Collection types

Rust memiliki banyak type untuk membuat collection. Collection berguna di saat Anda memerlukan lebih dari 1 value pada 1 variabel. Contohnya, Anda bisa memiliki informasi yang berisi semua nama-nama kota di dalam 1 variabel. Kita akan memulainya dengan array, yang mana ia adalah yang tercepat dalam hal seperti ini, namun juga memiliki kegunaan yang paling sedikit. Array ini mirip seperti `&str`, yang mana ia adalah yang paling cepat, namun kegunaannya pun juga yang paling sedikit.

### Arrays

Array adalah data yang dituliskan di dalam square bracket: `[]`. Syaratnya:

- Array tidak boleh mengubah ukurannya,
- Array hanya boleh berisi type yang sama.

Seperti yang tadi kita sebutkan, meskipun terbatas, ia sangat cepat.

Type pada array adalah: `[type; number]`. Contohnya, type dari `["One", "Two"]` adalah `[&str; 2]`. Ini artinya, bahkan 2 buah array pun bisa saja memiliki type yang berbeda. Begini contohnya:

```rust
fn main() {
    let array1 = ["One", "Two"]; // Type dari array1 adalah [&str; 2]
    let array2 = ["One", "Two", "Five"]; // Tapi untuk array2 ini typenya adalah [&str; 3]. Keduanya memiliki type yang berbeda!
}
```

Ini adalah saran yang baik: untuk mengetahui type dari sebuah variabel, Anda bisa "bertanya" ke compiler dengan cara memberikannya instruksi yang asal-asalan. Contohnya:

```rust
fn main() {
    let seasons = ["Spring", "Summer", "Autumn", "Winter"];
    let seasons2 = ["Spring", "Summer", "Fall", "Autumn", "Winter"];
    seasons.ddd(); // ⚠️
    seasons2.thd(); // ⚠️ as well
}
```

Compiler akan menegur kita, "What? There's no `.ddd()` method for seasons and no `.thd()` method for seasons 2 either!!" persis seperti yang bisa kita lihat lewat pesan berikut:

```text
error[E0599]: no method named `ddd` found for array `[&str; 4]` in the current scope
 --> src\main.rs:4:13
  |
4 |     seasons.ddd(); // 
  |             ^^^ method not found in `[&str; 4]`

error[E0599]: no method named `thd` found for array `[&str; 5]` in the current scope
 --> src\main.rs:5:14
  |
5 |     seasons2.thd(); // 
  |              ^^^ method not found in `[&str; 5]`
```

Compiler akan menuliskan `` method not found in `[&str; 4]` ``, yang mana typenya adalah yang ada di dalam square bracket.

Jika Anda ingin array dengan value yang sama, Anda bisa mendeklarasikannya seperti ini:

```rust
fn main() {
    let my_array = ["a"; 10];
    println!("{:?}", my_array);
}
```

Hasilnya adalah `["a", "a", "a", "a", "a", "a", "a", "a", "a", "a"]`.

Cara ini kebanyakan digunakan untuk untuk membuat buffer (inisialisasi array dimana semua value di dalamnya bernilai 0). Contohnya, `let mut buffer = [0; 640]` akan membuat array yang berisi 640 angka 0 di dalamnya. Kemudian kita bisa mengubah 0 menjadi angka yang lain untuk keperluan menambah data.

Anda bisa mengambil/menarik index pada array menggunakan []. Index yang paling awal adalah [0], yang kedua adalah [1], dan seterusnya.

```rust
fn main() {
    let my_numbers = [0, 10, -20];
    println!("{}", my_numbers[1]); // cetak 10
}
```

Anda bisa mengambil slice (potongan) pada array. Pertama-tama, Anda memerlukan `&`, karena compiler tidak mengetahui ukurannya. Kemudian Anda gunakan `..` untuk menunjukkan rangenya.

Contohnya, kita gunakan array ini: `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`.

```rust
fn main() {
    let array_of_ten = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

    let three_to_five = &array_of_ten[2..5];
    let start_at_two = &array_of_ten[1..];
    let end_at_five = &array_of_ten[..5];
    let everything = &array_of_ten[..];

    println!("Three to five: {:?}, start at two: {:?}, end at five: {:?}, everything: {:?}", three_to_five, start_at_two, end_at_five, everything);
}
```

Ingat ini:

- Index selalu dimulai dari 0 (bukan 1)
- Index ranges bersifat **eksklusif** (ia tidak akan memasukkan angka terakhir)

Jadinya `[0..2]` artinya adalah index yang pertama dan yang kedua (0 and 1). Atau Anda bisa menyebutnya dengan index ke-0 dan ke-1. Ia tidak memiliki item ke-3, karena ia tidak memsukkan index ke-2.

Anda juga bisa menggunakan range yang sifatnya **inklusif**, yang artinya ia akan mengikutkan angka yang terakhir juga. Untuk melakukan ini, tambahkan `=` untuk menuliskan `..=` untuk menggantikan `..`. Sehingga, `[0..2]` kita ganti menjadi `[0..=2]` jika Anda menginginkan item pertama, kedua, dan ketiga.

## Vectors
**[See this chapter on YouTube](https://youtu.be/Eh-DsRnDKmw)**

Sebagaimana kita memiliki `&str` dan `String`, kita pun memiliki array dan juga vector. Array lebih cepat namun dengan sedikit kegunaan, dan vector sangat lambat, tapi memiliki banyak kegunaan. (Tentu saja, Rust selalu sangat cepat, sehingga vector tidaklah lambat, hanya saja ia *lebih lambat* dibadingkan array.) Typenya adalah `Vec`, dan Anda bisa menyebutnya cukup dengan "vec".

Ada 2 cara untuk mendeklarasikan vector. Yang pertama, mirip seperti `String` menggunakan `new`:

```rust
fn main() {
    let name1 = String::from("Windy");
    let name2 = String::from("Gomesy");

    let mut my_vec = Vec::new();
    // Jika kita menuliskan programnya hanya sampai sini dan menjalankannya, compiler akan memberikan error.
    // Karena ia tidak tahu type dari vec.

    my_vec.push(name1); // Now it knows: it's Vec<String>
    my_vec.push(name2);
}
```

Anda bisa melihat bahwa `Vec` selalu memiliki sesuatu di dalamnya, dan itulah kegunaan dari `<>` (angle brackets). `Vec<String>` adalah vector dengan 1 atau banyak `String`. Anda juga bisa menggunakan lebih dari 1 type di dalamnya. Contohnya:

- `Vec<(i32, i32)>` adalah `Vec` dimana setiap itemnya adalah tuple: `(i32, i32)`.
- `Vec<Vec<String>>` adalah `Vec` dimana setiap itemnya adalah `Vec` dari `String`. Sebagai contoh, anggap saja Anda menginginkan untuk menyimpan daftar nama-nama buku favorit Anda ke dalam `Vec<String>`. Kemudian, Anda lakukan itu lagi dengan nama-nama buku lainnya, dan Anda mendapatkan `Vec<String>` lagi. Untuk menyimpan kedua daftar buku-buku ini, Anda tentunya akan meletakkannya ke dalam `Vec` lagi dan ia akan menjadi `Vec<Vec<String>>`.

Alih-alih menggunakan `.push()` untuk membuat Rust memilihkan typenya, Anda bisa juga langsung mendeklarasikan typenya.

```rust
fn main() {
    let mut my_vec: Vec<String> = Vec::new(); // Compiler mengetahui typenya
                                              // maka tidak akan ada error pada code ini.
}
```

Anda bisa melihat bahwa item-item yang ada di dalam vectors harus memiliki type yang sama.

Cara mudah lainnya untuk membuat suatu vector adalah dengan menggunakan macro `vec!`. Ini mirip seperti pendeklarasian array, namun dengan `vec!` di depannya.

```rust
fn main() {
    let mut my_vec = vec![8, 10, 10];
}
```

Typenya adalah `Vec<i32>`. Anda bisa menyebutnya sebagai "Vec dari i32". Dan `Vec<String>` adalah "Vec dari string". Dan `Vec<Vec<String>>` adalah "Vec dari vec dari string".

Anda juga bisa melakukan slice pada vector, sama seperti yang kita lakukan pada array.

```rust
fn main() {
    let vec_of_ten = vec![1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
    // Everything is the same as above except we added vec!.
    let three_to_five = &vec_of_ten[2..5];
    let start_at_two = &vec_of_ten[1..];
    let end_at_five = &vec_of_ten[..5];
    let everything = &vec_of_ten[..];

    println!("Three to five: {:?},
start at two: {:?}
end at five: {:?}
everything: {:?}", three_to_five, start_at_two, end_at_five, everything);
}
```

Karena vec lebih lambat dibandingkan dengan array, kita bisa menggunakan suatu cara untuk membuatnya menjadi cepat. Vector memiliki **kapasitas**, yang artinya adalah ruang yang diberikan kepada vector. Di saat Anda push item baru ke dalam vector, ia akan mendekati dan terus mendekati ke batas kapasitasnya. Maka, jika Anda batas kapasitasnya, maka ia akan membuat kapasitasnya menjadi dua kali lipat dan menyalin semua item di dalamnya ke dalam ruang yang baru. Ini biasa disebut sebagai reallocation. Kita akan menggunakan method `.capacity()` untuk melihat kapasitas dari vector saat kita menambahkan item ke dalamnya.

Berikut contohnya:

```rust
fn main() {
    let mut num_vec = Vec::new();
    println!("{}", num_vec.capacity()); // 0 element: kapasitasnya 0
    num_vec.push('a'); // tambah 1 karakter
    println!("{}", num_vec.capacity()); // 1 element: kapasitasnya 4. Vec dengan 1 item selalu mulai dengan kapasitas 4
    num_vec.push('a'); // tambah satu lagi
    num_vec.push('a'); // tambah satu lagi
    num_vec.push('a'); // tambah satu lagi
    println!("{}", num_vec.capacity()); // 4 element: kapasitasnya tetap 4.
    num_vec.push('a'); // tambah satu lagi
    println!("{}", num_vec.capacity()); // cetak 8. Kita memiliki 5 element, namun ia melipatgandakan kapasitasnya yang semula 4 menjadi 8 untuk membuat ruang yang lebih
}
```

Hasil printnya adalah sebagai berikut:

```text
0
4
4
8
```

Vector pada program di atas memiliki 2 reallocation: Dari 0 ke 4, dan dari 4 ke 8. Kita bisa membuatnya lebih cepat:

```rust
fn main() {
    let mut num_vec = Vec::with_capacity(8); // Kita langsung tulis bahwa program memerlukan kapasitas 8
    num_vec.push('a'); // tambah satu karakter
    println!("{}", num_vec.capacity()); // kapasitasnya 8
    num_vec.push('a'); // tambah satu lagi
    println!("{}", num_vec.capacity()); // kapasitasnya 8
    num_vec.push('a'); // tambah satu lagi
    println!("{}", num_vec.capacity()); // kapasitasnya 8.
    num_vec.push('a'); // tambah satu lagi
    num_vec.push('a'); // tambah satu lagi // Sekarang kita memiliki 5 element
    println!("{}", num_vec.capacity()); // kapasitasnya tetap 8
}
```

Vector pada program ini memiliki 0 reallocation, yang mana ini lebih baik. Jadi jika Anda berfikir bahwa Anda mengetahui seberapa banyak element yang Anda perlukan, Anda bisa menggunakan `Vec::with_capacity()` untuk membuatnya lebih cepat.

Anda juga harus mengingat bahwa Anda bisa menggunakan `.into()` untuk membuat `&str` menjadi `String`. Anda juga bisa menggunakannya untuk membuat array menjadi `Vec`. Anda harus memberi tahu kepada `.into()` bahwa Anda menginginkan `Vec`, tapi Anda tidak harus memilih type untu `Vec`nya. Jika Anda tidak ingin memilih typenya, Anda bisa menulis `Vec<_>`.

```rust
fn main() {
    let my_vec: Vec<u8> = [1, 2, 3].into();
    let my_vec2: Vec<_> = [9, 0, 10].into(); // Vec<_> artinya "pilihkan type Vec-nya untuk saya"
                                             // Maka Rust akan memilihkan Vec<i32>
}
```

## Tuples
**[See this chapter on YouTube](https://youtu.be/U67Diy6SlTg)**

Tuple di Rust menggunakan `()`. Kita sudah sering melihat tuple yang kosong, karena *parameter kosong* pada function sebenarnya adalah sebuah tuple kosong:

```text
fn do_something() {}
```

sebenarnya adalah kependekan dari:

```text
fn do_something() -> () {}
```

Function tidak menerima apapun (tuple kosong), dan tidak mengembalikan apapun juga (tuple kosong). Sehingga kita sebenarnya sudah berkali-kali menggunakan tuple di tutorial ini. Jika Anda tidak me-return apapun pada function, maka sebenarnya Anda me-return tuple kosong.

```rust
fn just_prints() {
    println!("I am printing"); // Menambahkan ; berarti kita me-return sebuah tuple kosong
}

fn main() {}
```

Tuples bisa menyimpan banyak data, dan bisa menyimpan type yang berbeda pula. Item-item di dalam tuple juga di-index menggunakan angka 0, 1, 2, dan seterusnya. Untuk mengakses index pada array, kita menggunakan `[]`, sedangkan pada vector kita menggunakan `.`. Mari kita coba untuk memasukkan bermacam-macam type ke dalam sebuah tuple.

```rust
fn main() {
    let random_tuple = ("Here is a name", 8, vec!['a'], 'b', [8, 9, 10], 7.7);
    println!(
        "Inside the tuple is: First item: {:?}
Second item: {:?}
Third item: {:?}
Fourth item: {:?}
Fifth item: {:?}
Sixth item: {:?}",
        random_tuple.0,
        random_tuple.1,
        random_tuple.2,
        random_tuple.3,
        random_tuple.4,
        random_tuple.5,
    )
}
```

Hasil printnya adalah:

```text
Inside the tuple is: First item: "Here is a name"
Second item: 8
Third item: ['a']
Fourth item: 'b'
Fifth item: [8, 9, 10]
Sixth item: 7.7
```

Type dari tuple di atas adalah `(&str, i32, Vec<char>, char, [i32; 3], f64)`.


Anda bisa menggunakan tuple untuk membuat banyak variabel. Kita lihat code berikut ini:

```rust
fn main() {
    let str_vec = vec!["one", "two", "three"];
}
```

`str_vec` memiliki 3 item di dalamnya. Bagaimana jika kita ingin menarik mereka keluar? Inilah dimana kita bisa menggunakan tuple.

```rust
fn main() {
    let str_vec = vec!["one", "two", "three"];

    let (a, b, c) = (str_vec[0], str_vec[1], str_vec[2]); // memberi mereka nama sebagai a, b, dan c
    println!("{:?}", b);
}
```

Hasil printnya adalah `"two"`, yang mana itu adalah isi dari `b`. Cara sepertin ini biasa dinamanakan sebagai *destructuring*. Karena variabel awalnya berada di dalam struktur, namun di saat kita memecahnya menjadi variabel `a`, `b`, dan `c`, variabel-variabel tersebut tidak lagi ada di dalam struktur tersebut.

Jika Anda perlu melakukan destructure tapi tidak menginginkan semua variabelnya, Anda bisa menggunakan `_`.

```rust
fn main() {
    let str_vec = vec!["one", "two", "three"];

    let (_, _, apple) = (str_vec[0], str_vec[1], str_vec[2]);
}
```

Pada code di atas, ia hanya membuat sebuah variabel bernama `apple`, tapi tidak membuat variabel untuk yang lainnya.

Masih ada banyak lagi type collection, dan masih banyak lagi cara untuk menggunakan array, vec, dan tuple. Kita juga akan mempelajari lebih lanjut tentang mereka semua, akan tetapi, pertama-tama kita belajar terlebih dahulu tentang control flow.

## Control flow
**See this chapter on YouTube: [Part 1](https://youtu.be/UAymDOpv_us) and [Part 2](https://youtu.be/eqysTfiiQZs)**

Control flow artinya kita memberi tahu code untuk melakukan sesuatu pada kondisi yang berbeda. Control flow yang paling sederhana adalah `if`.

```rust
fn main() {
    let my_number = 5;
    if my_number == 7 {
        println!("It's seven");
    }
}
```

Juga perlu dicatat bahwa Anda menggunakan `==` dan bukan `=`. `==` digunakan untuk membandingkan, `=` digunakan untuk *assign* (memberikan value pada sebuah variabel). Perhatikan juga bahwa kita menuliskan `if my_number == 7` dan bukan `if (my_number == 7)`. Anda tidak memerlukan bracket untuk pengkondisian `if` di Rust.

`else if` dan `else` akan memberikan Anda keleluasaan untuk membuat control flow yang lebih kompleks:

```rust
fn main() {
    let my_number = 5;
    if my_number == 7 {
        println!("It's seven");
    } else if my_number == 6 {
        println!("It's six")
    } else {
        println!("It's a different number")
    }
}
```

Hasil cetaknya adalah `It's a different number` karena ia tidak sama dengan 7 ataupun 6.

Anda bisa menambahkan kondisi menggunakan `&&` (and) dan `||` (or).

```rust
fn main() {
    let my_number = 5;
    if my_number % 2 == 1 && my_number > 0 { // % 2 artinya angka yang tersisa setelah variabelnya dibagi dengan 2 (modulus)
        println!("It's a positive odd number");
    } else if my_number == 6 {
        println!("It's six")
    } else {
        println!("It's a different number")
    }
}
```

Hasil printnya adalah `It's a positive odd number` karena di saat Anda membagi `my_number` dengan 2, maka akan tersisa 1, dan `my_number` lebih besar daripada 0.


Terlalu banyak `if`, `else`, dan `else if` bisa membuat code menjadi sulit untuk dibaca. Pada kasus seperti ini, Anda bisa menggunakan `match` (kecocokan), yang mana membuat code terlihat menjadi lebih bersih dan rapi. Hanya saja, Anda harus melihat setiap kemungkinan resultnya. Contohnya, code di bawah ini tidak akan berjalan:

```rust
fn main() {
    let my_number: u8 = 5;
    match my_number {
        0 => println!("it's zero"),
        1 => println!("it's one"),
        2 => println!("it's two"),
        // ⚠️
    }
}
```

Compiler akan memberikan pesan:

```text
error[E0004]: non-exhaustive patterns: `3u8..=std::u8::MAX` not covered
 --> src\main.rs:3:11
  |
3 |     match my_number {
  |           ^^^^^^^^^ pattern `3u8..=std::u8::MAX` not covered
```

Ini artinya "Kamu beri tahu aku tentang kondisi 0 sampai dengan 2, tapi `u8` bisa sampai dengan 255. Bagaimana tentang 3? Bagaimana tentang 4? Bagaimana tentang 5 dan seterusnya?". Jadinya Anda bisa menambahkan `_` yang artinya "kondisi yang lainnya".

```rust
fn main() {
    let my_number: u8 = 5;
    match my_number {
        0 => println!("it's zero"),
        1 => println!("it's one"),
        2 => println!("it's two"),
        _ => println!("It's some other number"),
    }
}
```

Hasil printnya adalah `It's some other number`.

Ingatlah ini di saat Anda menggunakan match:

- Anda menulis `match` dan kemudian membuat `{}` code block.
- Tuliskan *pattern* pada sebelah kiri dan gunakan `=>` (fat arrow) untuk menuliskan apa yang harus dilakukan apabila kondisinya matches (cocok).
- Setiap baris di dalam block match disebut sebagai "arm".
- Letakkan comma di antara setiap arm (bukan semicolon).

Anda bisa mendeklarasikan value dengan menggunakan match:

```rust
fn main() {
    let my_number = 5;
    let second_number = match my_number {
        0 => 0,
        5 => 10,
        _ => 2,
    };
}
```

`second_number` akan bernilai 10. Apakah Anda melihat keberadaan semicolon pada bagian akhir block match? Hal itu dikarenakan, setelah match telah selesai, kita sebenarnya memberitahukan kepada compiler hal ini: `let second_number = 10;`


Anda juga bisa menggunakan match pada hal-hal yang lebih rumit. Anda bisa menggunakan tuple untuk melakukannya.

```rust
fn main() {
    let sky = "cloudy";
    let temperature = "warm";

    match (sky, temperature) {
        ("cloudy", "cold") => println!("It's dark and unpleasant today"),
        ("clear", "warm") => println!("It's a nice day"),
        ("cloudy", "warm") => println!("It's dark but not bad"),
        _ => println!("Not sure what the weather is."),
    }
}
```

Hasil cetaknya adalah `It's dark but not bad`, karena value "cloudy" dan "warm" cocok dengan value dari `sky` dan `temperature`.

Bahkan Anda bisa menambahkan `if` di dalam `match`. Ini biasanya disebut sebagai "match guard":

```rust
fn main() {
    let children = 5;
    let married = true;

    match (children, married) {
        (children, married) if married == false => println!("Not married with {} children", children),
        (children, married) if children == 0 && married == true => println!("Married but no children"),
        _ => println!("Married? {}. Number of children: {}.", married, children),
    }
}
```

Hasilnya adalah `Married? true. Number of children: 5.`

Anda bisa menggunakan _ sebanyak yang Anda inginkan pada match. Pada match yang berhubungan dengan warna di bawah ini, kita memiliki 3 warna namun hanya diperiksa kecocokannya satu per satu.

```rust
fn match_colours(rbg: (i32, i32, i32)) {
    match rbg {
        (r, _, _) if r < 10 => println!("Not much red"),
        (_, b, _) if b < 10 => println!("Not much blue"),
        (_, _, g) if g < 10 => println!("Not much green"),
        _ => println!("Each colour has at least 10"),
    }
}

fn main() {
    let first = (200, 0, 0);
    let second = (50, 50, 50);
    let third = (200, 50, 0);

    match_colours(first);
    match_colours(second);
    match_colours(third);

}
```

Hasilnya adalah:

```text
Not much blue
Each colour has at least 10
Not much green
```

Program di atas juga menunjukkan bagaimana statement `match` bekerja, karena pada contoh pertama ia hanya menampilkan `Not much blue`. Padahal variabel `first` juga tidak memenuhi syarat warna hijau (g == 0). Statement `match` selalu berhenti di saat ia menemukan kecocokan, dan tidak akan memeriksa sisanya. Ini juga adalah contoh yang baik dimana ia menunjukkan bahwa code dicompile dengan baik, hanya saja code ini berjalan tidak seperti yang kita inginkan.

Anda bisa membuat statement `match` yang lebih besar dan rumit untuk mengatasi masalah ini, tapi akan lebih baik jika kita menggunakan loop `for`. Kita akan membicarakan tentang loop di chapter selanjutnya.

Match harus me-return type yang sama. Jadinya Anda tidak bisa melakukan hal ini:

```rust
fn main() {
    let my_number = 10;
    let some_variable = match my_number {
        10 => 8,
        _ => "Not ten", // ⚠️
    };
}
```

Compiler akan memberikan pesan seperti ini:

```text
error[E0308]: `match` arms have incompatible types
  --> src\main.rs:17:14
   |
15 |       let some_variable = match my_number {
   |  _________________________-
16 | |         10 => 8,
   | |               - this is found to be of type `{integer}`
17 | |         _ => "Not ten",
   | |              ^^^^^^^^^ expected integer, found `&str`
18 | |     };
   | |_____- `match` arms have incompatible types
```

Code di bawah ini juga tidak berjalan, dengan sebab yang sama seperti yang di atas:

```rust
fn main() {
    let some_variable = if my_number == 10 { 8 } else { "something else "}; // ⚠️
}
```

Akan tetapi bekerja dengan normal, karena ini bukan `match` sehingga Anda memiliki statement `let` yang berbeda setiap saat:

```rust
fn main() {
    let my_number = 10;

    if my_number == 10 {
        let some_variable = 8;
    } else {
        let some_variable = "Something else";
    }
}
```

Anda juga bisa menggunakan `@` untuk memberikan nama ke value dari sebuah ekspresi `match`, dan Anda bisa menggunakannya. Pada contoh ini kita mencocokkan input `i32` ke dalam function. Jika ia bernilai 4 atau 13, kita ingin menggunakan angka teresebut ke dalam statement `println!`. Sebaliknya, kita tidak perlu untuk menggunakannya.

```rust
fn match_number(input: i32) {
    match input {
    number @ 4 => println!("{} is an unlucky number in China (sounds close to 死)!", number),
    number @ 13 => println!("{} is unlucky in North America, lucky in Italy! In bocca al lupo!", number),
    _ => println!("Looks like a normal number"),
    }
}

fn main() {
    match_number(50);
    match_number(13);
    match_number(4);
}
```

Hasilnya adalah:

```text
Looks like a normal number
13 is unlucky in North America, lucky in Italy! In bocca al lupo!
4 is an unlucky number in China (sounds close to 死)!
```

## Structs
**See this chapter on YouTube: [Part 1](https://youtu.be/W23uQghBOFk) and [Part 2](https://youtu.be/GSVhrjLCuNA)**

Dengan struct, Anda bisa membuat type Anda sendiri. Di Rust, Anda akan menggunakan struct sepanjang waktu karena ia mudah untuk digunakan. Struct dibuat dengan keyword `struct`. Nama dari sebuah struct harus berformat UpperCamelCase (Huruf Capital untuk setiap huruf di awal kata, tanpa spasi). Jika Anda menulis sebuah struct dengan format lowercase, compiler akan memberi tahu Anda.

Ada 3 jenis structs. Yang pertama adalah "unit struct". Unit artinya "tidak memiliki apapun". Untuk unit struct, Anda cukuk menuliskan nama dan semicolon.

```rust
struct FileDirectory;
fn main() {}
```

Selanjutnya ada tuple struct, atau biasa disebut unnamed struct. Disebut "unnamed" karena Anda hanya perlu menuliskan type, tanpa ada nama fieldnya. Tuple struct sangat cocok untuk digunkan apabila Anda membutuhkan sebuah struct sederhana dan tidak perlu untuk mengingat namanya.

```rust
struct Colour(u8, u8, u8);

fn main() {
    let my_colour = Colour(50, 0, 50); // membuat warna RGB (red, green, blue)
    println!("The second part of the colour is: {}", my_colour.1);
}
```

Hasilnya adalah `The second part of the colour is: 0`.

Jenis ketiga adalah named struct. Mungkin ini adalah jenis struct yang biasanya paling sering digunakan. Pada struct jenis ini, Anda perlu mendeklarasikan nama field dan juga typenya di dalam `{}` code block. Sebagai catatan, bahwa Anda tidak perlu menuliskan semicolon setelah named struct, karena ada code block yang ditulis setelahnya.

```rust
struct Colour(u8, u8, u8); // Deklarasikan Colour tuple struct 

struct SizeAndColour {
    size: u32,
    colour: Colour, // Dan kita masukkan ke dalam named struct
}

fn main() {
    let my_colour = Colour(50, 0, 50);

    let size_and_colour = SizeAndColour {
        size: 150,
        colour: my_colour
    };
}
```

Anda harus memisahkan field dengan menggunakan koma dan begitu juga pada named struct. Untuk field yang terakhir, Anda boleh menambahkan koma atau tidak - itu terserah Anda. `SizeAndColour` memiliki koma setelah `colour`:

```rust
struct Colour(u8, u8, u8); // Deklarasikan Colour tuple struct

struct SizeAndColour {
    size: u32,
    colour: Colour, // Dan kita masukkan ke dalam named struct
}

fn main() {}
```

Sebenarnya Anda tidak memerlukan koma tersebut. Namun adalah ide yang bagus untuk selalu memberikan koma pada bagian akhir field, karena terkadang Anda akan mengubah urutan dari field-field tersebut:

```rust
struct Colour(u8, u8, u8); // Deklarasikan Colour tuple struct

struct SizeAndColour {
    size: u32,
    colour: Colour // Tidak ada koma disini
}

fn main() {}
```

Kemudian kita memutuskan untuk mengubah urutannya...

```rust
struct SizeAndColour {
    colour: Colour // ⚠️ Oops! Sekarang bagian ini tidak berkoma. Dan ini akan memberikan error jika dijalankan.
    size: u32,
}

fn main() {}
```

Tapi itu tidak terlalu penting sehingga Anda dapat memilih apakah akan menggunakan koma atau tidak.


Okay. Mari kita buat struct `Country` sebagai contoh. Struct `Country` memiliki field `population`, `capital`, dan `leader_name`.

```rust
struct Country {
    population: u32,
    capital: String,
    leader_name: String
}

fn main() {
    let population = 500_000;
    let capital = String::from("Elista");
    let leader_name = String::from("Batu Khasikov");

    let kalmykia = Country {
        population: population,
        capital: capital,
        leader_name: leader_name,
    };
}
```

Apakah Anda sadar bahwa kita menuliskan sesuatu yang sama 2 kali? Kita menulis `population: population`, `capital: capital`, dan `leader_name: leader_name`. Sebenarnya, Anda tidak perlu melakukan hal seperti itu. Jika nama field dan nama variable adalah sama, maka Anda tidak perlu menuliskannya 2 kali.

```rust
struct Country {
    population: u32,
    capital: String,
    leader_name: String
}

fn main() {
    let population = 500_000;
    let capital = String::from("Elista");
    let leader_name = String::from("Batu Khasikov");

    let kalmykia = Country {
        population,
        capital,
        leader_name,
    };
}
```

## Enums
**See this chapter on YouTube: [Part 1](https://youtu.be/SRnqNTJUgjs), [Part 2](https://youtu.be/F_EcbWM63lk), [Part 3](https://youtu.be/2uh64U9JesA) and [Part 4](https://youtu.be/LOHVUYTc5Us)**

`enum`adalah kependekan dari enumerations. Ia terlihat mirip seperti struct, tapi sebenarnya berbeda. Inilah perbedaannya:

- Gunakan `struct` apabila Anda menginginkan satu hal **DAN** juga hal lainnya.
- Gunakan `enum` apabila Anda memilih satu hal **ATAU** hal yang lainnya.

Jadi, struct digunakan untuk menyimpan **banyak hal** secara bersamaan, sedangkan enum digunakan untuk memilih **banyak pilihan** secara bersamaan.

Untuk mendeklarasikan enum, tulis `enum` dan gunakan code block beserta pilihan-pilihan di dalamnya, dan pisahkan pilihan-pilihan tersebut menggunakan koma. Sama seperti `struct`, bagian akhir dari enum boleh memiliki koma atau tidak. Kita akan membuat enum dengan nama `ThingsInTheSky`:

```rust
enum ThingsInTheSky {
    Sun,
    Stars,
}

fn main() {}
```

Ini adalah enum karena Anda hanya bisa melihat salah satu, `Sun` (matahari di siang hari), **atau** `Stars` (bintang di malam hari): Anda harus memilih salah satunya. Pilihan-pilihan ini biasa disebut sebagai **variants**.

```rust
// membuat enum dengan 2 pilihan
enum ThingsInTheSky {
    Sun,
    Stars,
}

// Dengan function ini, kita bisa menggunakan i32 untuk membuat ThingsInTheSky.
fn create_skystate(time: i32) -> ThingsInTheSky {
    match time {
        6..=18 => ThingsInTheSky::Sun, // Antara jam 6 dan 18, kita bisa melihat Matahari
        _ => ThingsInTheSky::Stars, // Sebaliknya, kita bisa melihat bintang
    }
}

// Dengan function ini, kita bisa menggunakan match untuk melakukan sesuatu terhadap 2 pilihan yang ada pada ThingsInTheSky.
fn check_skystate(state: &ThingsInTheSky) {
    match state {
        ThingsInTheSky::Sun => println!("I can see the sun!"),
        ThingsInTheSky::Stars => println!("I can see the stars!")
    }
}

fn main() {
    let time = 8; // jam 8 pagi
    let skystate = create_skystate(time); // create_skystate akan me-return ThingsInTheSky
    check_skystate(&skystate); // Berikan reference dari skystate, sehingga function check_skystate bisa membaca isi dari variabel skystate
}
```

Dan hasilnya adalah `I can see the sun!`.

Anda juga bisa menambahkan data pada enum.

```rust
enum ThingsInTheSky {
    Sun(String), // Sekarang setiap variant memiliki sebuah string
    Stars(String),
}

fn create_skystate(time: i32) -> ThingsInTheSky {
    match time {
        6..=18 => ThingsInTheSky::Sun(String::from("I can see the sun!")), // Tuliskan stringnya disini
        _ => ThingsInTheSky::Stars(String::from("I can see the stars!")),
    }
}

fn check_skystate(state: &ThingsInTheSky) {
    match state {
        ThingsInTheSky::Sun(description) => println!("{}", description), // Memberikan string sebuah nama deskripsi, sehingga kita bisa menggunakannya
        ThingsInTheSky::Stars(n) => println!("{}", n), // Atau Anda juga bisa menamakannya dengan n. Atau dengan nama lain semau Anda - itu tidak masalah
    }
}

fn main() {
    let time = 8; // jam 8 pagi
    let skystate = create_skystate(time); // create_skystate akan me-return ThingsInTheSky
    check_skystate(&skystate); // Berikan reference dari skystate, sehingga function check_skystate bisa membaca isi dari variabel skystate
}
```

Program di atas akan mencetak hal yang sama: `I can see the sun!`

Anda bisa juga melakukan "import" kepada enum, sehingga Anda tidak perlu mengetik terlalu banyak. Ini adalah contoh dimana kita harus menuliskan `Mood::` setiap kita menuliskan variant dari enum `Mood` di dalam sebuah match:

```rust
enum Mood {
    Happy,
    Sleepy,
    NotBad,
    Angry,
}

fn match_mood(mood: &Mood) -> i32 {
    let happiness_level = match mood {
        Mood::Happy => 10, // Kita harus menuliskan Mood:: setiap saat
        Mood::Sleepy => 6,
        Mood::NotBad => 7,
        Mood::Angry => 2,
    };
    happiness_level
}

fn main() {
    let my_mood = Mood::NotBad;
    let happiness_level = match_mood(&my_mood);
    println!("Out of 1 to 10, my happiness is {}", happiness_level);
}
```

Hasil cetaknya adalah `Out of 1 to 10, my happiness is 7`. Saatnya kita gunakan `import` sehingga kita bisa mengetik lebih sedikit. Untuk meng-import semua yang ada di enum, tuliskan `*`. Catatan: meskipun ini `*` adalah simbol yang sama dengan yang digunakan dereferencing, tapi ini benar-benar berbeda.

```rust
enum Mood {
    Happy,
    Sleepy,
    NotBad,
    Angry,
}

fn match_mood(mood: &Mood) -> i32 {
    use Mood::*; // Kita meng-import semua yang ada di dalam Mood. Sekarang kita cukup menuliskan Happy, Sleepy, dsb.
    let happiness_level = match mood {
        Happy => 10, // Kita tidak perlu lagi menuliskan Mood::
        Sleepy => 6,
        NotBad => 7,
        Angry => 2,
    };
    happiness_level
}

fn main() {
    let my_mood = Mood::Happy;
    let happiness_level = match_mood(&my_mood);
    println!("Out of 1 to 10, my happiness is {}", happiness_level);
}
```


`enum` juga bisa direpresentasikan sebagai integer. Ini dikarenakan Rust memberikan angka pada setiap variant di `enum` yang dimulai dengan 0. Anda bisa melakukan hal ini jika enum yang Anda buat tidak memiliki type apapun dalamnya.

```rust
enum Season {
    Spring, // Jika Anda menuliskan Spring(String) atau suatu type yang lainnya, maka ia tidak akan berjalan
    Summer,
    Autumn,
    Winter,
}

fn main() {
    use Season::*;
    let four_seasons = vec![Spring, Summer, Autumn, Winter];
    for season in four_seasons {
        println!("{}", season as u32);
    }
}
```

Berikut adalah hasilnya:

```text
0
1
2
3
```

Anda juga bisa merepresentasikannya menggunakan angka yang lain, jika Anda menginginkannya. Rust tidak begitu peduli dalam hal ini dan Anda bisa menampilkannya dengan cara yang sama. Cukup tambahakan `=` juga angka yang Anda inginkan ke variant yang ingin Anda representasikan dengan angka. Anda tidak perlu merepresentasikan semua variant tersebut dengan angka. Namun jika Anda tidak menuliskan representasi integernya secara manual, Rust akan mengambil nilai representasi integer dari variant yang sebelumnya, menambahkannya dengan 1, dan hasilnya dijadikan representasi pada variant yang tidak direpresentasikan secara manual tersebut.

```rust
enum Star {
    BrownDwarf = 10,
    RedDwarf = 50,
    YellowStar = 100,
    RedGiant = 1000,
    DeadStar, // Coba pikirkan hal ini. Angka berapa yang menjadi representasi integernya?
}

fn main() {
    use Star::*;
    let starvec = vec![BrownDwarf, RedDwarf, YellowStar, RedGiant];
    for star in starvec {
        match star as u32 {
            size if size <= 80 => println!("Not the biggest star."), // Ingat: "size" tidaklah berarti apapun. Ia hanya sebuah nama yang kita pilih, sehingga kita bisa mencetaknya
            size if size >= 80 => println!("This is a good-sized star."),
            _ => println!("That star is pretty big!"),
        }
    }
    println!("What about DeadStar? It's the number {}.", DeadStar as u32);
}
```

Berikut adalah hasilnya:


```text
Not the biggest star.
Not the biggest star.
This is a good-sized star.
This is a good-sized star.
What about DeadStar? It's the number 1001.
```

`DeadStar` semestinya direpresentasikan dengan angka 4, tapi sekarang ia berangka 1001.

### Enums to use multiple types

Kita mengetahui bahwa item di dalam `Vec`, array, dan yang lainnya, diisi dengan type yang sama (hanya tuples yang berbeda). Tapi sebenarnya Anda bisa menggunakan enum untuk dimasukkan type yang beragam. Bayangkan kita ingin memiliki sebuah `Vec` dengan type `u32` atau `i32`. Tentu saja, anda bisa membuat `Vec<(u32, i32)>` (vec dengan tuple `(u32, i32)`) namun kita hanya menginginkan salah satunya saja. Jadi disini Anda bisa menggunakan enum. Begini contohnya:

```rust
enum Number {
    U32(u32),
    I32(i32),
}

fn main() {}
```

Jadi pada enum tersebut terdapat 2 variant: variant `U32` degnan type `u32`di dalamnya, dan `I32` dengan variant `i32` di dalamnya. `U32` dan `I32` hanyalah sebuah nama yang kita buat. Ia bisa saja bernama `UThirtyTwo` atau `IThirtyTwo` atau apapun itu.

Sekarang, jika kita masukkan enum `Number` tersebut ke dalam `Vec` kita akan memiliki `Vec<Number>`, dan compiler akan menjalankannya dengan aman karena typenya sama semua (semuanya menggunakan type `Number`). Compiler tidak peduli bahwa kita memiliki `u32` ataupun `i32` karena kedua type tersebut dibungkus di dalam sebuah type bernama `Number`. Dan karena `Number` adalah sebuah enum, Anda mesti memilih salah satunya, yang tentunya adalah type yang kita inginkan. Kita akan menggunakan method `.is_positive()` untuk menentukan typenya. Jika `true` Maka kita akan pilih `U32`, dan jika `false` maka kita akan memilih `I32`.

Codenya adalah sebagai berikut:

```rust
enum Number {
    U32(u32),
    I32(i32),
}

fn get_number(input: i32) -> Number {
    let number = match input.is_positive() {
        true => Number::U32(input as u32), // ganti typenya menjadi u32 jika ia positive
        false => Number::I32(input), // sebaliknya, cukup masukkan angkanya saja karena secara default typenya adalah i32
    };
    number
}


fn main() {
    let my_vec = vec![get_number(-800), get_number(8)];

    for item in my_vec {
        match item {
            Number::U32(number) => println!("It's a u32 with the value {}", number),
            Number::I32(number) => println!("It's an i32 with the value {}", number),
        }
    }
}
```

Dan, voila! Hasilnya sesuai dengan yang kita inginkan:

```text
It's an i32 with the value -800
It's a u32 with the value 8
```


## Loops

Dengan menggunakan loops (perulangan), Anda bisa memberitahukan Rust untuk terus-menerus melakukan sesuatu sampai Anda menginginkannya untuk berhenti. Anda menggunakan `loop` untuk memulai perulangan yang tidak akan berhenti, kecuali Anda memberitahukannya kapan untuk berhenti menggunakan `break`.

```rust
fn main() { // Program ini tidak akan pernah berhenti
    loop {

    }
}
```

Jadi, kita beritahukan compiler kapan ia harus berhenti.

```rust
fn main() {
    let mut counter = 0; // inisialisasi nilai counternya menjadi 0
    loop {
        counter +=1; // tambahakan value counter dengan 1
        println!("The counter is now: {}", counter);
        if counter == 5 { // hentikan perulangan saat counter == 5
            break;
        }
    }
}
```

Hasilnya adalah sebagai berikut:

```text
The counter is now: 1
The counter is now: 2
The counter is now: 3
The counter is now: 4
The counter is now: 5
```

Jika Anda memiliki loop di dalam loop, Anda bisa memberikan mereka nama. Dengan menggunakan nama, kita bisa memberitahukan Rust loop yang mana yang inign kita `break`. Gunakan `'` ("tick") dan sebuah `:` untuk memberikannya nama:

```rust
fn main() {
    let mut counter = 0;
    let mut counter2 = 0;
    println!("Now entering the first loop.");

    'first_loop: loop {
        // Berikan nama kepada loop yang pertama
        counter += 1;
        println!("The counter is now: {}", counter);
        if counter > 9 {
            // Buat loop kedua di dalam loop ini
            println!("Now entering the second loop.");

            'second_loop: loop {
                // sekarang kita berada pada 'second_loop
                println!("The second counter is now: {}", counter2);
                counter2 += 1;
                if counter2 == 3 {
                    break 'first_loop; // Hentikan 'first_loop sehingga kita bisa keluar dari program
                }
            }
        }
    }
}
```

Hasilnya adalah:

```text
Now entering the first loop.
The counter is now: 1
The counter is now: 2
The counter is now: 3
The counter is now: 4
The counter is now: 5
The counter is now: 6
The counter is now: 7
The counter is now: 8
The counter is now: 9
The counter is now: 10
Now entering the second loop.
The second counter is now: 0
The second counter is now: 1
The second counter is now: 2
```

Loop `while` adalah loop yang terus-menerus melakukan sesuatu selama kondisinya `true`. Setiap loop, Rust akan memeriksa apakah kondisinya masih `true`. jika kondisinya menjadi `false`, Rust akan menghentikan loopnya.

```rust
fn main() {
    let mut counter = 0;

    while counter < 5 {
        counter +=1;
        println!("The counter is now: {}", counter);
    }
}
```

Loop `for` mempersilahkan Anda untuk memberitahu Rust apa yang harus dilakukan setiap saat. Pada loop `for`, loop akan berhenti setelah selesai mengulang dari suatu angka sampai dengan angka tertentu. Loop `for` sering menggunakan **ranges** (jarak). Anda menggunakan `..` dan `..=` untuk membuat rangenya.

- `..` akan membuat **exclusive** range: `0..3` creates `0, 1, 2`.
- `..=` akan membuat **inclusive** range: `0..=3` = `0, 1, 2, 3`.

```rust
fn main() {
    for number in 0..3 {
        println!("The number is: {}", number);
    }

    for number in 0..=3 {
        println!("The next number is: {}", number);
    }
}
```

Hasilnya adalah:

```text
The number is: 0
The number is: 1
The number is: 2
The next number is: 0
The next number is: 1
The next number is: 2
The next number is: 3
```

Perhatikan juga bahwa `number` menjadi nama variabel untuk 0..3. Kita beisa menyebutnya sebagai `n`, atau `i_loop`, atau apapun. Bahakn kita bisa menggunakan nama tersebut di dalam `println!`.

Jika Anda tidak memerlukan nama variabel, gunakan `_`.

```rust
fn main() {
    for _ in 0..3 {
        println!("Printing the same thing three times");
    }
}
```

Ini akan mencetak:

```text
Printing the same thing three times
Printing the same thing three times
Printing the same thing three times
```

`_` karena kita tidak memerlukan angka untuk untuk diprint setiap saat.

Dan sebenarnya, jika Anda memberikan nama variabel dan tidak menggunakannya, Rust akan memberitahumu:

```rust
fn main() {
    for number in 0..3 {
        println!("Printing the same thing three times");
    }
}
```

Ia akan mencetak hasil yang sama seperti pada program yang sebelumnya. Rus menjalankan programnya dengan baik, akan tetapi Rust akan mengingatkan Anda bahwa Anda tidak menggunakan `number`:

```text
warning: unused variable: `number`
 --> src\main.rs:2:9
  |
2 |     for number in 0..3 {
  |         ^^^^^^ help: if this is intentional, prefix it with an underscore: `_number`
```

Rust menyarankan Anda untuk `_number` daripada menuliskan `_`. Menulis `_` di depan nama variabel berarti "munkin nanti Saya akan membutuhkannya". Tapi kalau Anda hanya menggunakan `_` artinya "Saya sama sekali tidak peduli dengan variabel ini". Jadi Anda bisa menambahkan `_` di depan nama variabel jika mungkin Anda akan menggunakannya kemudian dan tidak ingin compiler memberikan warning tentang itu.

Anda juga bisa menggunakan `break` untuk me-return value. Anda menuliskan valuenya tepat setelah `break` dan menggunakan `;`. Ini adalah contoh `loop` dan break yang mengisi value ke variabel `my_number`.

```rust
fn main() {
    let mut counter = 5;
    let my_number = loop {
        counter +=1;
        if counter % 53 == 3 {
            break counter;
        }
    };
    println!("{}", my_number);
}
```

Hasilnya adalah `56`. `break counter;` berarti "break dan kembalikan value dari variabel counter". Dan karena loop block tersebut dimulai dengan `let`, maka `my_number` diisi dengan value tersebut.

Sekarang kita tahu bagaimana caranya menggunakan loop. Tapi jangan lupa bahwa masih ada satu problem yang belum kita selesaikan pada chapter tentang match. Oleh karena itu, ini adalah solusi yang lebih baik untuk menyelesaikan problem tersebut. Kita menyebutnya solusi yang lebih baik dikarenakan kita ingin membandingkan semua warnanya, dan loop `for` bisa digunakan untuk keperluan itu.

```rust
fn match_colours(rbg: (i32, i32, i32)) {
    println!("Comparing a colour with {} red, {} blue, and {} green:", rbg.0, rbg.1, rbg.2);
    let new_vec = vec![(rbg.0, "red"), (rbg.1, "blue"), (rbg.2, "green")]; // Taruh warna-warna tersebut ke dalam vec, yang isinya merupakan tuple yang berisi nama warna dan nilainya
    let mut all_have_at_least_10 = true; // Kita mulai dengan true. Kita akan ubah menjadi false jika value dari warnanya di bawah 10
    for item in new_vec {
        if item.0 < 10 {
            all_have_at_least_10 = false; // Sekarang nilainya false
            println!("Not much {}.", item.1) // Dan kita cetak nama warnanya.
        }
    }
    if all_have_at_least_10 { // Periksa apakah ia masih bernilai true, jika ya, lakukan print
        println!("Each colour has at least 10.")
    }
    println!(); // Tambahkan satu line
}

fn main() {
    let first = (200, 0, 0);
    let second = (50, 50, 50);
    let third = (200, 50, 0);

    match_colours(first);
    match_colours(second);
    match_colours(third);
}
```

Hasilnya adalah:

```text
Comparing a colour with 200 red, 0 blue, and 0 green:
Not much blue.
Not much green.

Comparing a colour with 50 red, 50 blue, and 50 green:
Each colour has at least 10.

Comparing a colour with 200 red, 50 blue, and 0 green:
Not much green.
```

## Implementing structs and enums

Ini adalah dimana kita bisa mulai untuk memberikan *kekuatan* kepada structs dan enums. Untuk memanggil fungsi pada `struct` atau `enum`, kita bisa menggunakan block `impl`. Fungsi ini biasanya disebut sebagai **methods**. Ada 2 macam method di dalam block `impl`.

- Regular methods: ia menggunakan **self** (atau **&self** atau juga **&mut self**). Regular methods menggunakan `.` (period/titik). `.clone()` adalah contoh dari sebuah regular method.
- Associated methods (atau "static" methods): ia tidak menggunakan self. Associated berarti "berhubungan dengan". Ia ditulis dengan cara yang berbeda, yaitu menggunakan `::`. `String::from()` adalah contoh dari associated method, dan begitu juga dengan `Vec::new()`. Anda biasanya melihat associated methods digunakan untuk membuat variabel baru.

Pada contoh yang kita gunakan ini kita akan membuat impl Animal dan membuatg hasil printnya.

Untuk `struct` atau `enum` yang baru dibuat, Anda perlu memberikannya **Debug** jika Anda ingin menggunakan `{:?}` untuk mencetaknya. Jika kita menuliskan `#[derive(Debug)]` pada line sebelum ditulisnya struct atau enum, maka kita bisa mencetaknya dengan `{:?}`. Pesan yang ditulis dengan `#[]` disebut sebagai **attributes**. Kita terkadang bisa menggunakannya untuk memberitahukan compiler untuk memberikan kemampuan kepada struct agar bisa menggunakan `Debug`. Ada banyak sekali attribute dan kita akan mempelajarinya kemudian. Tapi, `derive` mungkin adalah attribute yang paling umum dan biasa Anda lihat pada bagian sebelum struct dan enum dideklarasikan.

```rust
#[derive(Debug)]
struct Animal {
    age: u8,
    animal_type: AnimalType,
}

#[derive(Debug)]
enum AnimalType {
    Cat,
    Dog,
}

impl Animal {
    fn new() -> Self {
        // Self ini adalah Animal.
        // Kita juga bisa menulisnya Animal bila kita tidak ingin menulisnya sebagai Self

        Self {
            // Saat kita menulis Animal::new(), kita akan selalu mendapatkan Kucing yang berusia 10 tahun
            age: 10,
            animal_type: AnimalType::Cat,
        }
    }

    fn change_to_dog(&mut self) { // Karena kita berada pada scope Animal, maka &mut self artinya adalah &mut Animal
                                  // gunakan .change_to_dog() untuk mengubah animal_typenya dari kucing, menjadi anjing
                                  // dengan menggunakan &mut self, kita bisa mengubahnya
        println!("Changing animal to dog!");
        self.animal_type = AnimalType::Dog;
    }

    fn change_to_cat(&mut self) {
        // gunakan .change_to_cat() untuk mengubahnya dari anjing, menjadi kucing
        // dengan menggunakan &mut self, kita bisa mengubahnya
        println!("Changing animal to cat!");
        self.animal_type = AnimalType::Cat;
    }

    fn check_type(&self) {
        // kita ingin membaca isi dari self
        match self.animal_type {
            AnimalType::Dog => println!("The animal is a dog"),
            AnimalType::Cat => println!("The animal is a cat"),
        }
    }
}



fn main() {
    let mut new_animal = Animal::new(); // Associated method untuk membuat animal yang baru
                                        // Secara default, ia adalah kucing yang berusia 10 tahun
    new_animal.check_type();
    new_animal.change_to_dog();
    new_animal.check_type();
    new_animal.change_to_cat();
    new_animal.check_type();
}
```

This prints:

```text
The animal is a cat
Changing animal to dog!
The animal is a dog
Changing animal to cat!
The animal is a cat
```


Perlu diingat, bahwa Self (type Self) dan self (variabel self) merupakan abreviasi. (abreviasi = singkatan / cara terpendek untuk menulis sesuatu)

Jadi, pada code kita, Self = Animal. Juga, `fn change_to_dog(&mut self)` berarti `fn change_to_dog(&mut Animal)`.

Ini adalah satu contoh tambahan. Untuk contoh yang ini, kita akan menggunakan `impl` pada `enum`:

```rust
enum Mood {
    Good,
    Bad,
    Sleepy,
}

impl Mood {
    fn check(&self) {
        match self {
            Mood::Good => println!("Feeling good!"),
            Mood::Bad => println!("Eh, not feeling so good"),
            Mood::Sleepy => println!("Need sleep NOW"),
        }
    }
}

fn main() {
    let my_mood = Mood::Sleepy;
    my_mood.check();
}
```

Hasil cetaknya adalah `Need sleep NOW`.

## Destructuring

Mari kita lihat lebih lanjut tentang destructuring. Anda bisa mendapatkan value dari struct atau enum dengan menggunakan `let` secara terbalik. Kita telah mempelajari bahwa hal seperti ini disebut sebagai `destructuring`, karena nantinya kita akan mendapatkan variable yang mana adalah bukan bagian dari struktur (entah struktur tersebut adalah struct atau enum). Atau dengan kata lain, kita mendapatkan valuenya secara terpisah. Berikut adalah contohnya:

```rust
struct Person { // membuat struct sederhana untuk person
    name: String,
    real_name: String,
    height: u8,
    happiness: bool
}

fn main() {
    let papa_doc = Person { // membuat variabel papa_doc
        name: "Papa Doc".to_string(),
        real_name: "Clarence".to_string(),
        height: 170,
        happiness: false
    };

    let Person { // destructure papa_doc
        name: a,
        real_name: b,
        height: c,
        happiness: d
    } = papa_doc;

    println!("They call him {} but his real name is {}. He is {} cm tall and is he happy? {}", a, b, c, d);
}
```

Hasilnya adalah: `They call him Papa Doc but his real name is Clarence. He is 170 cm tall and is he happy? false`

Bisa kita lihat, kita menggunakan `let` secara terbalik. Pertama, kita menuliskan `let papa_doc = Person { fields }` untuk membuat sebuah struct. kemudian kita menuliskan `let Person { fields } = papa_doc` untuk melakukan destructure pada `papa_doc`.

Anda tidak perlu menuliskan `name: a` - Anda cukup menuliskan `name`. Tapi disini kita menulis `name = a` karena kita ingin menggunakan variabel dengan nama `a`.

Kita masuk ke contoh yang lebih besar dari sebelumnya. Pada contoh kali ini kita memiliki struct `City`. Kita berikan implementasikan function `new` untuk membuatnya. Kemudian kita memiliki function `process_city_values` untuk melakukan sesuatu terhadap valuenya. Di dalam function tersebut, kita hanya membuat sebuah `Vec`, namun Anda bisa lihat bahwa kita bisa melakukan banyak hal setelah kita melakukan destructure kepada parameter `city`.

```rust
struct City {
    name: String,
    name_before: String,
    population: u32,
    date_founded: u32,
}

impl City {
    fn new(name: String, name_before: String, population: u32, date_founded: u32) -> Self {
        Self {
            name,
            name_before,
            population,
            date_founded,
        }
    }
}

fn process_city_values(city: &City) {
    let City {
        name,
        name_before,
        population,
        date_founded,
    } = city;
        // sekarang kita memiliki value yang digunakan secara terpisah
    let two_names = vec![name, name_before];
    println!("The city's two names are {:?}", two_names);
}

fn main() {
    let tallinn = City::new("Tallinn".to_string(), "Reval".to_string(), 426_538, 1219);
    process_city_values(&tallinn);
}
```

Dan hasilnya adalah `The city's two names are ["Tallinn", "Reval"]`.


## References and the dot operator

Kita telah mempelajari bahwa di saat kita memiliki sebuah reference, Anda perlu menggunakan `*` untuk mendapatkan valuenya. Sebuah reference adalah type yang berbeda dari variabel aslinya, sehingga hal yang dicontohkan seperti hal di bawah ini tidak akan berjalan:

```rust
fn main() {
    let my_number = 9;
    let reference = &my_number;

    println!("{}", my_number == reference); // ⚠️
}
```

Dan compiler akan menyampaikan pesan berikut:

```text
error[E0277]: can't compare `{integer}` with `&{integer}`
 --> src\main.rs:5:30
  |
5 |     println!("{}", my_number == reference);
  |                              ^^ no implementation for `{integer} == &{integer}`
```

Sehingga kita mengganti line 5 menjadi `println!("{}", my_number == *reference);` dan sekarang outputnya adalah `true` karena kondisinya sekarang adalah `i32` == `i32`, bukan `i32` == `&i32`. Hal seperti ini biasa disebut sebagai dereferencing.

Namun di saat Anda menggunakan method, Rust akan melakukan dereference secara otomatis. Tanda `.` pada method biasa disebut sebagai dot operator, dan ia akan langsung melakukan dereferencing.

Pertama, kita buat sebuah struct dengan 1 field bertype `u8`. Kemudian kita akan membuat sebuah reference ke field yang berada di dalam struct tersebut, dan mencoba untuk meng-comparenya (membandingkannya/mengkomparasinya). Dari contoh yang sebelumnya, bisa prediksikan bahwa hasilnya akan gagal :

```rust
struct Item {
    number: u8,
}

fn main() {
    let item = Item {
        number: 8,
    };

    let reference_number = &item.number; //  type dari reference_number adalah &u8

    println!("{}", reference_number == 8); // ⚠️ &u8 dan u8 tidak bisa dikomparasi
}
```

Untuk membuatnya bekerja, kita perlu untuk melakukan dereference: `println!("{}", *reference_number == 8);`.

Namun dengan menggunakan dot operator, kita tidak lagi perlu untuk menggunakan `*`. Contohnya:

```rust
struct Item {
    number: u8,
}

fn main() {
    let item = Item {
        number: 8,
    };

    let reference_item = &item;

    println!("{}", reference_item.number == 8); // kita tidak perlu untuk menuliskan *reference_item.number
}
```

Sekarang kita akan membuat sebuah method untuk `Item` yang membandingkan `number` dengan angka lainnya. Kita sama sekali tidak memerlukan `*` dimanapun:

```rust
struct Item {
    number: u8,
}

impl Item {
    fn compare_number(&self, other_number: u8) { // ambil reference dari self
        println!("Are {} and {} equal? {}", self.number, other_number, self.number == other_number);
            // Kita tidak perlu lagi menuliskan *self.number
    }
}

fn main() {
    let item = Item {
        number: 8,
    };

    let reference_item = &item; // ini bertype &Item
    let reference_item_two = &reference_item; // ini bertype &&Item

    item.compare_number(8); // method ini bisa berjalan
    reference_item.compare_number(8); // method yang ini juga berjalan
    reference_item_two.compare_number(8); // dan begitu pula pada bagian ini

}
```

Jadi, cukup ingat hal ini: di saat Anda menggunakn `.` (dot operator), Anda tidak lagi perlu mengkhawatirkan tentang `*`.




## Generics

Pada function, Anda biasanya menuliskan apa type yang akan diambil sebagai input:

```rust
fn return_number(number: i32) -> i32 {
    println!("Here is your number.");
    number
}

fn main() {
    let number = return_number(5);
}
```

Tapi bagaimana apabila kita juga ingin mengambil inputnya selain dari type `i32`? Kita bisa menggunakan generics untuk hal ini. Generics artinya "mungkin satu type, atau mungkin juga type yang lain".

Untuk menggunakan generics, kita menggunakan angle brackets dengan menuliskan type didalamnya, seperti ini: `<T>`. Ini artinya "type apa pun yang Anda masukkan ke dalam function". Biasanya, generics menggunakan type dengan satu huruf besar (T, U, V, dsb.), meskipun sebenarnya Anda tidak harus hanya menggunakan satu huruf saja.

Contoh berikut menunjukkan bagaimana cara untuk mengubah sebuah function menjadi generic type:

```rust
fn return_number<T>(number: T) -> T {
    println!("Here is your number.");
    number
}

fn main() {
    let number = return_number(5);
}
```

Bagian terpentinya adalah `<T>` yang ditulis setelah nama function. Tanpa ini, Rust akan berpikir bahwa T adalah concrete type (concrete = bukan generic), seperti `String` atau `i8`.

Ini lebih mudah untuk dimengerti jika kita menuliskan sebuah nama type. Lihatlah apa yang terjadi saat kita mengubah `T` menjadi `MyType`:

```rust
fn return_number(number: MyType) -> MyType { // ⚠️
    println!("Here is your number.");
    number
}
```

Seperti yang kita lihat, `MyType` adalah concrete, bukan generic. Sehingga kita perlu untuk menuliskan ini untuk menjadikannya generic:

```rust
fn return_number<MyType>(number: MyType) -> MyType {
    println!("Here is your number.");
    number
}

fn main() {
    let number = return_number(5);
}
```

Jadi, huruf tunggal `T` itu adalah untuk memudahkan "mata" programmer untuk mengetahui bahwa itu adalah generic. Sedangkan bagian yang ditulis setelah nama function `< >` adalah untuk "mata" compiler Rust. Tanpa itu, maka ia bukanlah generic.

Sekarang kita kembali ke type `T`, karena code yang ditulis pada Rust biasanya menggunakan `T`.

Anda akan mengingat bahwa beberapa type yang ada di Rust memiliki trait **Copy**, beberapanya memiliki trait **Clone**, beberapa lagi memiliki **Display**, **Debug**, dan seterusnya. Dengan **Debug**, kita bisa melakukan print menggunakan `{:?}`. Jadi sekarang kita bisa melihat bahwa kita memiliki sebuah problem jika kita ingin mencetak output `T`:

```rust
fn print_number<T>(number: T) {
    println!("Here is your number: {:?}", number); // ⚠️
}

fn main() {
    print_number(5);
}
```

`print_number` memerlukan **Debug** untuk mencetak `number`. Tapi, apakah `T` adalah type yang memiliki trait `Debug`? Mungkin tidak. Mungkin ia tidak memiliki `#[derive(Debug)]`, siapa yang tahu. Bahkan compiler pun tidak bisa mengetahuinya, sehingga hal ini akan memberikan pesan error:

```text
error[E0277]: `T` doesn't implement `std::fmt::Debug`
  --> src\main.rs:29:43
   |
29 |     println!("Here is your number: {:?}", number);
   |                                           ^^^^^^ `T` cannot be formatted using `{:?}` because it doesn't implement `std::fmt::Debug`
```

T tidak mengimplementasikan trait **Debug**. Jadi, apakah kita akan mengimplementasikan Debug untuk T? Tidak, karena kita pun tidak tahu apa sebenarnya T tersebut. Tapi kita bisa memberitahu function tersebut: "Jangan khawatir, karena apapun type T yang berada pada function ini akan memiliki Debug".

```rust
use std::fmt::Debug; // Debug berada pada std::fmt::Debug. Jadi sekarang kita cukup menulisnya 'Debug'.

fn print_number<T: Debug>(number: T) { // <T: Debug> adalah bagian terpenting
    println!("Here is your number: {:?}", number);
}

fn main() {
    print_number(5);
}
```

Jadi sekarang compiler tahu: "Okay, type T ini akan memiliki Debug". Sekarang codenya berjalan, karena `i32` memiliki Debug. Sekarang kita bisa memberikan inputan dari beberapa type, seperti: `String`, `&str`, dan seterusnya, karena mereka semua memiliki Debug.

Sekarang kita bisa membuat struct dan memberinya Debug dengan #[derive(Debug)], sehingga sekarang kita bisa mencetaknya juga. Function kita bisa mengambil `i32`, struct Animal, dan lainnya:

```rust
use std::fmt::Debug;

#[derive(Debug)]
struct Animal {
    name: String,
    age: u8,
}

fn print_item<T: Debug>(item: T) {
    println!("Here is your item: {:?}", item);
}

fn main() {
    let charlie = Animal {
        name: "Charlie".to_string(),
        age: 1,
    };

    let number = 55;

    print_item(charlie);
    print_item(number);
}
```

Dan hasilnya adalah:

```text
Here is your item: Animal { name: "Charlie", age: 1 }
Here is your item: 55
```

Terkadang kita memerlukan lebih dari satu type pada generic function. Kita perlu untuk menuliskan setiap nama typenya, dan memikirkan tentang bagaimana kita ingin menggunakannya. Pada contoh ini, kita ingin menggunakan 2 type. Pertama kita ingin untuk mencetak statement pada type T. Print menggunakan `{}` terlihat lebih bagus, jadinya kita memerlukan `Display` untuk `T`.

Selanjutnya adalah type U, dan 2 variablel (`num_1` dan `num_2`) menggunakan type U (U adalah semacam angka). Kita akan membandingkan keduanya, sehingga kita menggunakan `PartialOrd`. Trait ini memperbolehkan kita untuk menggunakan operator seperti `<`, `>`, `==`, dan yang lainnya. Dan kita ingin ingin mencetaknya juga, jadi kita juga memerlukan `Display` untuk type `U`.

```rust
use std::fmt::Display;
use std::cmp::PartialOrd;

fn compare_and_display<T: Display, U: Display + PartialOrd>(statement: T, num_1: U, num_2: U) {
    println!("{}! Is {} greater than {}? {}", statement, num_1, num_2, num_1 > num_2);
}

fn main() {
    compare_and_display("Listen up!", 9, 8);
}
```

Hasil cetaknya adalah `Listen up!! Is 9 greater than 8? true`.

Jadi `fn compare_and_display<T: Display, U: Display + PartialOrd>(statement: T, num_1: U, num_2: U)` seakan mengatakan bahwa:

- Nama functionnya adalah `compare_and_display`,
- Type pertama adalah T, dan ia adalah generic. Ia haruslah type yang bisa melakukan print menggunakan {}.
- Type kedua adalah U, and ia pula adalah generic. Ia haruslah type yang bisa melakukan print menggunakan {}. Juga, ia haruslah type yang bisa melakukan perbandingan/komparasi (menggunakan `>`, `<`, dan `==`).

Sekarang kita bisa memberikan `compare_and_display` type yang berbeda. `statement` bisa saja sebuah `String`, bisa saja `&str`, atau apapun yang memiliki trait Display.

Untuk membuat generic function menjadi lebih mudah untuk dibaca, kita bisa juga menuliskannya seperti dibawah ini menggunakan `where` tepat sebelum penulisan code block:

```rust
use std::cmp::PartialOrd;
use std::fmt::Display;

fn compare_and_display<T, U>(statement: T, num_1: U, num_2: U)
where
    T: Display,
    U: Display + PartialOrd,
{
    println!("{}! Is {} greater than {}? {}", statement, num_1, num_2, num_1 > num_2);
}

fn main() {
    compare_and_display("Listen up!", 9, 8);
}
```

Menggunakan `where` adalah ide yang bagus apabila Anda memiliki lebih dari satu generic type.

Dan juga, perlu diingat:

- Jika Anda memiliki variabel dengan type T dan type lainnya juga T, maka keduanya pasti sama.
- Jika Anda memiliki variabel dengan type T dan type lainnya adalah U, maka keduanya bisa berbeda. Namun keduanya juga bisa sama.

Sebagai contoh:

```rust
use std::fmt::Display;

fn say_two<T: Display, U: Display>(statement_1: T, statement_2: U) { // Type T memerlukan Display, type U juga memerlukan Display
    println!("I have two things to say: {} and {}", statement_1, statement_2);
}

fn main() {

    say_two("Hello there!", String::from("I hate sand.")); // Type T adalah &str, namun type U adalah String.
    say_two(String::from("Where is Padme?"), String::from("Is she all right?")); // Keduanya bertype String.
}
```

Hasilnya adalah:

```text
I have two things to say: Hello there! and I hate sand.
I have two things to say: Where is Padme? and Is she all right?
```

## Option and Result

Kita telah mengerti enums dan generics, sehingga kita bisa mengerti `Option` dan `Result`. Rust menggunakan 2 enum ini dengan tujuan untuk membuat code menjadi lebih safe.

Kita mulai dengan `Option`.

### Option

Kita menggunakan `Option` apabila kita memiliki sebuah value yang mungkin saja ada (exist), atau bisa juga tidak. Di saat sebuah value exist, ia akan mengembalikan `Some(value)` dan jika tidak, maka ia mengembalikan `None`. Ini adalah contoh dari code yang buruk yang nantinya bisa kita perbaiki dengan menggunakan `Option`.

```rust
    // ⚠️
fn take_fifth(value: Vec<i32>) -> i32 {
    value[4]
}

fn main() {
    let new_vec = vec![1, 2];
    let index = take_fifth(new_vec);
}
```

Di saat kita menjalankan codenya, ia akan menunjukkan pesan "panics". Berikut adalah pesannya:

```text
thread 'main' panicked at 'index out of bounds: the len is 2 but the index is 4', src\main.rs:34:5
```

Panic artinya adalah program berhenti sebelum problemnya terjadi. Rust melihat bahwa function menginginkan sesuatu yang tidak mungkin untuk dilakukan (impossible), dan menghentikannya. Problem yang dimaksud disini adalah "unwinds the stack" (mengambil value dari stack) dan memberitahu Anda, "Maaf, aku tidak bisa melakukannya".

Jadi sekarang kita akan mengubah type kembaliannya dari `i32` ke `Option<i32>`. Ini berarti "Beri aku `Some(i32)`, jika ada valuenya. Dan beri aku `None` jika tidak ada valuenya". Kita bisa juga menyebut bahwa `i32` "wrapped"/"dibungkus" didalam `Option`, yang berarti bahwa ia berada didalam `Option`. Anda perlu melakukan sesuatu untuk mendapatkan valuenya.

```rust
fn take_fifth(value: Vec<i32>) -> Option<i32> {
    if value.len() < 5 { // .len() akan memberikan panjang dari sebuah vec.
                         // Dan setidaknya, panjangnya haruslah 5.
        None
    } else {
        Some(value[4])
    }
}

fn main() {
    let new_vec = vec![1, 2];
    let bigger_vec = vec![1, 2, 3, 4, 5];
    println!("{:?}, {:?}", take_fifth(new_vec), take_fifth(bigger_vec));
}
```

Hasilnya adalah `None, Some(5)`. Ini adalah hal yang baik, karena sekarang compiler tidak lagi panic. Tapi bagaimana caranya ia mendapatkan value 5 dari `Some(5)`?

Kita bisa mengembil value di dalam Option menggunakan `.unwrap()`, namun berhati-hatilah dengan `.unwrap()`. Itu sama seperti melakukan unwrapping/membuka bungkus dari sebuah kotak yang kita tidak tahu apa isinya: mungkin saja isinya adalah sesuatu yang baik, atau mungkin saja isinya adalah belasan ekor ular. Anda sebaiknya hanya menggunakan `.unwrap()` di saat Anda yakin bahwa "kotak" yang Anda ingin buka tidaklah berbahaya. Jika Anda melakukan unwrap pada value `None`, maka program akan panic.

```rust
// ⚠️
fn take_fifth(value: Vec<i32>) -> Option<i32> {
    if value.len() < 5 {
        None
    } else {
        Some(value[4])
    }
}

fn main() {
    let new_vec = vec![1, 2];
    let bigger_vec = vec![1, 2, 3, 4, 5];
    println!("{:?}, {:?}",
        take_fifth(new_vec).unwrap(), // yang satu ini adalah None. .unwrap() akan membuat program panic!
        take_fifth(bigger_vec).unwrap()
    );
}
```

Berikut adalah pesan panicnya:

```text
thread 'main' panicked at 'called `Option::unwrap()` on a `None` value', src\main.rs:14:9
```

Tapi kita tidak harus menggunakan `.unwrap()`. Kita juga bisa menggunakan `match`. Kemudian kita bisa mencetak value dari Option yang returnya adalah `Some`, dan sama sekali tidak menyentuh yang `None`. Berikut contohnya:

```rust
fn take_fifth(value: Vec<i32>) -> Option<i32> {
    if value.len() < 5 {
        None
    } else {
        Some(value[4])
    }
}

fn handle_option(my_option: Vec<Option<i32>>) {
  for item in my_option {
    match item {
      Some(number) => println!("Found a {}!", number),
      None => println!("Found a None!"),
    }
  }
}

fn main() {
    let new_vec = vec![1, 2];
    let bigger_vec = vec![1, 2, 3, 4, 5];
    let mut option_vec = Vec::new(); // Buat vec baru untuk menyimpan option
                                     // Type dari vec tersebut adalah: Vec<Option<i32>>. Yang artinya adalah vec dari Option<i32>.

    option_vec.push(take_fifth(new_vec)); // Ini akan melakukan push value "None" ke dalam vec
    option_vec.push(take_fifth(bigger_vec)); // Ini akan melakukan push value "Some(5)" ke dalam vec

    handle_option(option_vec); // handle_option akan memeriksa setiap option yang berada di dalam vec.
                               // Ia akan mencetak value jika itu adalah Some. Dan sama sekali tidak disentuh apabila itu adalah None.
}
```

Hasil cetaknya adalah:

```text
Found a None!
Found a 5!
```

Karena kita telah mengetahui generics, maka kita bisa membaca code dengan `Option` dibawah ini. Berikut codenya:

```rust
enum Option<T> {
    None,
    Some(T),
}

fn main() {}
```

Poin penting yang harus diingat: dengan `Some`, Anda memiliki value dengan type `T` (type apapun). Juga dicatat, bahwa angle bracket setelah nama `enum` (yang mengurung `T`) memberitahukan compiler bahwa ia generic. Ia tidak memiliki trait seperti `Display` atau apapun yang membatasinya, sehingga ia bisa bertype apapun. Tapi, dengan `None`, Anda tidak mendapatkan apapun.

Jadinya, di dalam `match` statement untuk Option, Anda tidak bisa menuliskan:

```rust
// 🚧
Some(value) => println!("The value is {}", value),
None(value) => println!("The value is {}", value),
```

karena `None` tetaplah `None`.

Tentu saja, ada cara yang lebih mudah untuk menggunakan Option. Pada code ini, kita akan menggunakan sebuah method bernama `.is_some()` untuk memberi tahu kita jika ia adalah `Some`. (Ya, ada juga method dengan nama `.is_none()`.) Dengan cara yang lebih mudah ini, kita tidak lagi memerlukan function `handle_option()`. Kita juga tidak memerlukan sebuah vec untuk menyimpan value dari Option.

```rust
fn take_fifth(value: Vec<i32>) -> Option<i32> {
    if value.len() < 5 {
        None
    } else {
        Some(value[4])
    }
}

fn main() {
    let new_vec = vec![1, 2];
    let bigger_vec = vec![1, 2, 3, 4, 5];
    let vec_of_vecs = vec![new_vec, bigger_vec];
    for vec in vec_of_vecs {
        let inside_number = take_fifth(vec);
        if inside_number.is_some() {
            // .is_some() mengembalikan true jika kita mendapatkan Some, false jika kita mendapatkan None
            println!("We got: {}", inside_number.unwrap()); // tentunya akan aman menggunakan .unwrap() karena kita telah melakukan pemeriksaan
        } else {
            println!("We got nothing.");
        }
    }
}
```

Ini adalah hasilnya:

```text
We got nothing.
We got: 5
```

### Result

Result mirip dengan Option, namun ini adalah perbedaannya:

- Option berurusan tentang `Some` atau `None` (ada valuenya atau tidak ada valuenya),
- Result berurusan tentang `Ok` atau `Err` (hasilnya sesuai, atau menghasilkan error).

Jadi `Option` itu seakan kita berpikir: "Mungkin ada sesuatu, dan mungkin juga tidak ada.". Sedangkan `Result` itu seakan kita berpikir: "Mungkin ini akan error/gagal."

Untuk membandingkannya, ini adalah perbedaan antara Option dan Result.

```rust
enum Option<T> {
    None,
    Some(T),
}

enum Result<T, E> {
    Ok(T),
    Err(E),
}

fn main() {}
```

Result memiliki value didalam `Ok`, dan value didalam `Err`. Ini dikarenakan errors biasanya berisi informasi yang mendeskripsikan errornya.

`Result<T, E>` artinya Anda perlu untuk memikirkan apa yang ingin Anda return di saat ia `Ok`, dan apa yang ingin Anda return di saat ia `Err`. Sebenarnya, Anda bebas untuk menentukan apapun, bahkan melakukan hal yang seperti dilakukan pada contoh di bawah ini pun:

```rust
fn check_error() -> Result<(), ()> {
    Ok(())
}

fn main() {
    check_error();
}
```

`check_error` mengatakan "return `()` jika kita mendapatkan `Ok`, dan return `()` jika kita mendapatkan `Err`". Maka, kita me-return `Ok` dengan `()`.

Compiler akan memberikan kita warning yang menarik:

```text
warning: unused `std::result::Result` that must be used
 --> src\main.rs:6:5
  |
6 |     check_error();
  |     ^^^^^^^^^^^^^^
  |
  = note: `#[warn(unused_must_use)]` on by default
  = note: this `Result` may be an `Err` variant, which should be handled
```

Ini benar: kita hanya mengembalikan `Result` tapi bisa jadi itu adalah `Err`. Maka, kita perlu tangani errornya , meskipun kita tidak melakukan apapun.

```rust
fn give_result(input: i32) -> Result<(), ()> {
    if input % 2 == 0 {
        return Ok(())
    } else {
        return Err(())
    }
}

fn main() {
    if give_result(5).is_ok() {
        println!("It's okay, guys")
    } else {
        println!("It's an error, guys")
    }
}
```

Code di atas akan mencetak `It's an error, guys`. Jadinya, kita telah menangani error pertama kita pada Result.

Diingat, ada empat method untuk melakukan pengecekan secara mudah, yaitu `.is_some()`, `is_none()`, `is_ok()`, dan `is_err()`.


Terkadang sebuah function dengan Result akan menggunakan `String` untuk `Err` valuenya. Ini bukanlah cara terbaik untuk digunakan, namun ini adalah sedikit lebih baik daripada apa yang sejauh ini sudah kita lakukan.

```rust
fn check_if_five(number: i32) -> Result<i32, String> {
    match number {
        5 => Ok(number),
        _ => Err("Sorry, the number wasn't five.".to_string()), // Ini adalah pesan error yang kita buat
    }
}

fn main() {
    let mut result_vec = Vec::new(); // Buat vec baru untuk resultnya

    for number in 2..7 {
        result_vec.push(check_if_five(number)); // push setiap result ke dalam vec
    }

    println!("{:?}", result_vec);
}
```

Berikut adalah isi dari vec tersebut:

```text
[Err("Sorry, the number wasn\'t five."), Err("Sorry, the number wasn\'t five."), Err("Sorry, the number wasn\'t five."), Ok(5),
Err("Sorry, the number wasn\'t five.")]
```

Sama seperti Option, melakukan `.unwrap()` pada `Err` akan menyebabkan panic.

```rust
    // ⚠️
fn main() {
    let error_value: Result<i32, &str> = Err("There was an error"); // Buat sebuah Result yang valuenya adalah Err
    println!("{}", error_value.unwrap()); // lakukan unwrap
}
```

Hasilnya, program panics, dan mencetak:

```text
thread 'main' panicked at 'called `Result::unwrap()` on an `Err` value: "There was an error"', src\main.rs:30:20
```

Informasi ini membantu kita untuk memperbaiki code. `src\main.rs:30:20` artinya "di dalam main.rs di direktori src, pada line 30 dan column 20". Sehinggan Anda bisa ke bagian tersebut untuk melihat codenya dan memperbaiki masalahnya.

Anda juga bisa membuat type error Anda sendiri. Function Result pada standard library dan code Rust yang ditulis oleh orang lain biasanya menggunakan ini. Contohnya adalah function dari standard library ini:

```rust
// 🚧
pub fn from_utf8(vec: Vec<u8>) -> Result<String, FromUtf8Error>
```

Function ini mengambil byte dari vector (`u8`) dan mencoba untuk membuatnya menjadi `String`. Maka Ok-case pada Result adalah `String` dan Error-casenya adalah `FromUtf8Error`. Anda dapat memberikan error type Anda menggunakan nama apa pun yang Anda inginkan.

Menggunakan `match` dengan `Option` dan `Result` terkadang membutuhkan code yang lebih panjang. Contohnya, method `.get()` mengembalikan `Option` pada `Vec`.

```rust
fn main() {
    let my_vec = vec![2, 3, 4];
    let get_one = my_vec.get(0); // 0 untuk mengambil angka pertama
    let get_two = my_vec.get(10); // Return None
    println!("{:?}", get_one);
    println!("{:?}", get_two);
}
```

Hasilnya adalah:

```text
Some(2)
None
```

Jadi sekarang kita bisa menggunakan match untuk mendapatkan valuenya. Mari kita gunakan range dari 0 sampai dengan 10 untuk melihat apakah ia cocok dengan angka-angka di dalam `my_vec`.

```rust
fn main() {
    let my_vec = vec![2, 3, 4];

    for index in 0..10 {
      match my_vec.get(index) {
        Some(number) => println!("The number is: {}", number),
        None => {}
      }
    }
}
```

Ini bagus, namun kita tidak melakukan apapun pada kondisi `None` karen kita tidak peduli pada case itu. Nah, kita bisa membuat codenya menjadi lebih singkat dengan menggunakan `if let`. `if let` artinya "lakukan sesuatu jika ia cocok, dan tidak usah lakukan apapun jika tidak cocok". `if let` digunakan apabila anda tidak merasa perlu untuk menuliskan apa yang harus dilakukan pada semua kondisi matching.

```rust
fn main() {
    let my_vec = vec![2, 3, 4];

    for index in 0..10 {
      if let Some(number) = my_vec.get(index) {
        println!("The number is: {}", number);
      }
    }
}
```

**Yang perlu untuk diingat**: `if let Some(number) = my_vec.get(index)` artinya "Jika Anda mendapat `Some(number)` dari `my_vec.get(index)`".

Juga perlu dicatat: ia menggunakan `=`. Ini bukanlah boolean.

`while let` bisa dikatakan sebagai while loop yang dimodifikasi dengan `if let`. Anggap saja kita memiliki data dari stasiun cuaca seperti ini:

```text
["Berlin", "cloudy", "5", "-7", "78"]
["Athens", "sunny", "not humid", "20", "10", "50"]
```

Kita ingin mendapatkan angkanya saja, dan tidak menginginkan kata-kata yang berada di dalamnya . Untuk mengambil angkanya, kita bisa menggunakan method bernama `parse::<i32>()`. `parse()` adalah method, and `::<i32>` adalah typenya. Ia akan mencoba untuk mengubah `&str` menjadi `i32`, dan akan memberikannya ke kita jika memang bisa dilakukan. Ia akan mengembalikan `Result`, karena mungkin saja ia gagal melakukannya (misalnya, Anda ingin melakukan parse pada "Billybrobby", dan tentu saja akan gagal - karena ia bukan angka).

Kita juga akan menggunakan `.pop()`. Ia akan mengambil item terakhir pada sebuah vector.

```rust
fn main() {
    let weather_vec = vec![
        vec!["Berlin", "cloudy", "5", "-7", "78"],
        vec!["Athens", "sunny", "not humid", "20", "10", "50"],
    ];
    for mut city in weather_vec {
        println!("For the city of {}:", city[0]); // Di dalam data kita, setia item pertama adalah nama kota
        while let Some(information) = city.pop() {
            // Ini berarti: tetap jalankan instruksi di dalam while sampai pada kondisi dimana tidak bisa melakukan pop lagi
            // Di saat vector mencapai pada 0 item, ia akan me-return None
            // dan ia akan berhenti.
            if let Ok(number) = information.parse::<i32>() {
                // Mencoba untuk melakukan parse pada variabel yang kita namakan information
                // Ia akan mengembalikan Result. Jika hasilnya adalah Ok(number), ia akan mencetaknya
                println!("The number is: {}", number);
            }  // Kita tidak menulis apapun pada bagian ini karena kita tidak melakukan apapun jika mendapatkan error.
               // Dengan kata lain, kita throw/buang semua error tersebut 
        }
    }
}
```

Hasilnya adalah sebagai berikut:

```text
For the city of Berlin:
The number is: 78
The number is: -7
The number is: 5
For the city of Athens:
The number is: 50
The number is: 10
The number is: 20
```

## Other collections

Rust memiliki beberapa jenis collection. Kita bisa melihatnya di https://doc.rust-lang.org/beta/std/collections/ pada standard library. Laman tersebut dengan baik menjelaskan tentang mengapa kita menggunakan suatu jenis collection, jadi pergilah ke laman tersebut jika Anda tidak tahu type apa yang Anda inginkan. Collections ini semuanya berada di dalam `std::collections` pada standard library. Cara terbaik untuk menggunkannya adalah dengan menggunakan statement `use`, seperti yang kita lakukan pada `enums` yang kita buat sebelumnya. Kita akan mulai dengan `HashMap`, yang mana ia adalah collection yang paling umum.

### HashMap (and BTreeMap)

HashMap adalah collection yang terbuat dari *keys* dan *values*. Anda menggunakan key untuk melihat value yang cocok dengan keynya. Anda bisa membuat sebuah  `HashMap` yang baru dengan menggunakan `HashMap::new()` dan juga `.insert(key, value)` untuk memasukkan item ke dalamnya.

`HashMap` tidaklah berurutan, sehingga jika Anda mencetak setiap key yang berada pada `HashMap` secara bersamaan, ia akan tercetak dengan urutan yang berbeda-beda. Kita bisa melihat hal tersebut pada contoh di bawah ini:

```rust
use std::collections::HashMap; // Ini ditulis sehingga kita bisa menuliskannya hanya dengan "HashMap" daripada menuliskan std::collections::HashMap setiap saat

struct City {
    name: String,
    population: HashMap<u32, u32>, // population akan memiliki tahun dan jumlah populasi pada tahun tersebut
}

fn main() {

    let mut tallinn = City {
        name: "Tallinn".to_string(),
        population: HashMap::new(), // Sejauh ini HashMap masih kosong
    };

    tallinn.population.insert(1372, 3_250); // masukkan 3 data
    tallinn.population.insert(1851, 24_000);
    tallinn.population.insert(2020, 437_619);


    for (year, population) in tallinn.population { // HashMapnya bertype HashMap<u32, u32> sehingga ia akan akan mengembalikan dua item setiap saat
        println!("In the year {} the city of {} had a population of {}.", year, tallinn.name, population);
    }
}
```

Hasil cetaknya adalah:

```text
In the year 1372 the city of Tallinn had a population of 3250.
In the year 2020 the city of Tallinn had a population of 437619.
In the year 1851 the city of Tallinn had a population of 24000.
```

Atau bisa juga seperti ini:

```text
In the year 1851 the city of Tallinn had a population of 24000.
In the year 2020 the city of Tallinn had a population of 437619.
In the year 1372 the city of Tallinn had a population of 3250.
```

Anda bisa melihat bahwa ia ditampilkan secara tidak berurutan dan sering berubah-ubah.

Jika Anda ingin `HashMap` yang berurutan, Anda bisa menggunakan `BTreeMap`. Sebenarnya mereka itu mirip satu sama lain, sehingga kita bisa dengan cepat mengubah `HashMap` kita ke `BTreeMap`. Anda bisa melihat code yang dituliskan pun benar-benar hampir sama.

```rust
use std::collections::BTreeMap; // Cukup ubah HashMap ke BTreeMap

struct City {
    name: String,
    population: BTreeMap<u32, u32>, // Cukup ubah HashMap ke BTreeMap
}

fn main() {

    let mut tallinn = City {
        name: "Tallinn".to_string(),
        population: BTreeMap::new(), // Cukup ubah HashMap ke BTreeMap
    };

    tallinn.population.insert(1372, 3_250);
    tallinn.population.insert(1851, 24_000);
    tallinn.population.insert(2020, 437_619);

    for (year, population) in tallinn.population {
        println!("In the year {} the city of {} had a population of {}.", year, tallinn.name, population);
    }
}
```

Dan ia akan selalu mencetak:

```text
In the year 1372 the city of Tallinn had a population of 3250.
In the year 1851 the city of Tallinn had a population of 24000.
In the year 2020 the city of Tallinn had a population of 437619.
```

Sekarang kita kembali lagi ke `HashMap`.

Anda bisa mengambil value di dalam `HashMap` cukup dengan menuliskan keynya di dalam `[]` square brackets. Pada contoh selanjutnya kita akan memberikan value pada key `Bielefeld`, yang mana valuenya adalah `Germany`. Namun berhati-hatilah, karena programnya akan crash jika keynya tidak ditemukan. Sebagai contoh, jika Anda menulis `println!("{:?}", city_hashmap["Bielefeldd"]);` maka ia akan crash, karena key `Bielefeldd` tidak ditemukan.

Jika Anda tidak yakin apakah keynya ada atau tidak, Anda bisa menggunakan `.get()` yang mana akan mengembalikan `Option`. Jika keynya ada, ia akan mengembalikan `Some(value)`. Dan jika tidak, maka ia akan mengembalikan `None` alih-alih membuat programnya menjadi crash. Itulah mengapa `.get()` adalah cara teraman untuk mendapatkan value dari `HashMap`.

```rust
use std::collections::HashMap;

fn main() {
    let canadian_cities = vec!["Calgary", "Vancouver", "Gimli"];
    let german_cities = vec!["Karlsruhe", "Bad Doberan", "Bielefeld"];

    let mut city_hashmap = HashMap::new();

    for city in canadian_cities {
        city_hashmap.insert(city, "Canada");
    }
    for city in german_cities {
        city_hashmap.insert(city, "Germany");
    }

    println!("{:?}", city_hashmap["Bielefeld"]);
    println!("{:?}", city_hashmap.get("Bielefeld"));
    println!("{:?}", city_hashmap.get("Bielefeldd"));
}
```

Hasilnya adalah:

```text
"Germany"
Some("Germany")
None
```

Ini dikarenakan ada kunci yang bernama *Bielefeld*, namun kunci bernama *Bielefeldd* tidak ditemukan.

Jika `HashMap` telah memiliki key di saat Anda mencoba untuk memasukkan Hashmap value yang baru, maka ia akan meng-overwrite valuenya:

```rust
use std::collections::HashMap;

fn main() {
    let mut book_hashmap = HashMap::new();

    book_hashmap.insert(1, "L'Allemagne Moderne");
    book_hashmap.insert(1, "Le Petit Prince");
    book_hashmap.insert(1, "섀도우 오브 유어 스마일");
    book_hashmap.insert(1, "Eye of the World");

    println!("{:?}", book_hashmap.get(&1));
}
```

Ia akan mencetak `Some("Eye of the World")`, karena value tersebut adalah value yang terakhir dimasukkan menggunakan `.insert()`.

Adalah hal yang mudah untuk memeriksa apakah sebuah entry exist atau tidak, karena Anda bisa memeriksanya dengan menggunakan `.get()` yuang mana iak akan memberikan kita `Option`:

```rust
use std::collections::HashMap;

fn main() {
    let mut book_hashmap = HashMap::new();

    book_hashmap.insert(1, "L'Allemagne Moderne");

    if book_hashmap.get(&1).is_none() { // is_none() returns a bool: true if it's None, false if it's Some
        book_hashmap.insert(1, "Le Petit Prince");
    }

    println!("{:?}", book_hashmap.get(&1));
}
```

Ia akan mencetak `Some("L\'Allemagne Moderne")` karena kita telah memiliki key `1`, sehingga kita tidak perlu untuk memasukkan memasukkan `Le Petit Prince`.

`HashMap` memiliki method yang menarik, namanya `.entry()`, yang mana pastinya membuat Anda ingin mencobanya. Dengan method ini, Anda bisa mencoba untuk membuat sebuah entry dan menggunakan method lain seperti `.or_insert()` untuk memasukkan value jika tidak ada keynya. Bagian menariknya adalah ia juga akan memberikan mutable reference sehingga Anda bisa mengubahnya jika Anda menginginkannya. Ini adalah contoh pertama dimana kita memasukkan `true` setiap kita memasukkan judul buku ke dalam `HashMap`.

Anggaplah kita memiliki perpustakaan dan kita ingin memantau buku-buku yang kita miliki.

```rust
use std::collections::HashMap;

fn main() {
    let book_collection = vec!["L'Allemagne Moderne", "Le Petit Prince", "Eye of the World", "Eye of the World"]; // Eye of the World muncul dua kali

    let mut book_hashmap = HashMap::new();

    for book in book_collection {
        book_hashmap.entry(book).or_insert(true);
    }
    for (book, true_or_false) in book_hashmap {
        println!("Do we have {}? {}", book, true_or_false);
    }
}
```

Hasilnya adalah:

```text
Do we have Eye of the World? true
Do we have Le Petit Prince? true
Do we have L'Allemagne Moderne? true
```

Namun hasil tersebut tentunya bukanlah yang kita inginkan. Mungkin akan lebih baik jika jumlah bukunya juga dihitung sehingga kita tahu bahwa kita memiliki 2 copy dari *Eye of the World*. Pertama-tama, kita lihat terlebih dahulu apa yang `.entry()` lakukan, dan apa yang `.or_insert()` lakukan. `.entry()` sebenarnya mengembalikan sebuah `enum` yang disebut dengan `Entry`:

```rust
pub fn entry(&mut self, key: K) -> Entry<K, V> // 🚧
```


[Ini adalah laman yang menjelaskan tentang Entry](https://doc.rust-lang.org/std/collections/hash_map/enum.Entry.html). Dibawah ini adalah versi singkat dari codenya. `K` adalah key dan `V` adalah value.

```rust
// 🚧
use std::collections::hash_map::*;

enum Entry<K, V> {
    Occupied(OccupiedEntry<K, V>),
    Vacant(VacantEntry<K, V>),
}
```

Kemudian di saat kita menggunakan method `.or_insert()`, ia akan memeriksa enum yang dikembalikan dan menentukan apa yang harus dilakukan.

```rust
fn or_insert(self, default: V) -> &mut V { // 🚧
    match self {
        Occupied(entry) => entry.into_mut(),
        Vacant(entry) => entry.insert(default),
    }
}
```

Bagian menariknya adalah ia me-return `mut` reference: `&mut V`. Yang berarti Anda bisa menggunakan `let` untuk memasukkan valuenya ke variabel, dan mengubah valuenya yang tersimpan di dalam `HashMap`. Jadinya, untuk setiap buku, kita akan memasukkan 0 jika memang belum ada entry apapun sebelumnya. Dan jika sebelumnya sudah ada satu entry, kita akan gunakan `+= 1` pada reference untuk menambahkan angkanya. Maka, sekarang ia akan terlihat seperti ini:

```rust
use std::collections::HashMap;

fn main() {
    let book_collection = vec!["L'Allemagne Moderne", "Le Petit Prince", "Eye of the World", "Eye of the World"];

    let mut book_hashmap = HashMap::new();

    for book in book_collection {
        let return_value = book_hashmap.entry(book).or_insert(0); // return_value adalah mutable reference. Jika belum ada entrynya, maka valuenya 0
        *return_value +=1; // Sekarang, return_value setidaknya bernilau 1. Dan apabila jika sebelumnya entry bukunya sudah ada, maka jumlahnya akan bertambah 1
    }

    for (book, number) in book_hashmap {
        println!("{}, {}", book, number);
    }
}
```


Bagian terpentingnya adalah `let return_value = book_hashmap.entry(book).or_insert(0);`. Jika Anda tidak menggunakan `let`, maka yang Anda dapatkan adalah `book_hashmap.entry(book).or_insert(0)`. Tanpa `let`, ia tidak akan bisa melakukan apapun: ia akan memasukkan 0, dan tidak ada variabel yang mengambil mutable referencenya yang bernilai 0. Sehingga kita lakukan bind pada value tersebut ke `return_value` sehingga kita bisa menyimpan nilai 0 tersebut. Kemudian kita tambahkan nilainya dengan 1, yang mana memberikan kita nilai bahwa jumlah pada setiap buku di dalam `HashMap` setidaknya bernilai 1. Kemudian ketika `.entry()` melihat *Eye of the World* lagi, ia tidak akan meng-insert apapun, tapi ia akan memberikan kita mutable 1. Kemudian kita tambahkan valuenya sehingga menjadi 2, dan itu sebabnya hasil dari program tersebut adalah seperti berikut:

```text
L'Allemagne Moderne, 1
Le Petit Prince, 1
Eye of the World, 2
```


Anda juga bisa melakukan hal lain dengan `.or_insert()` seperti insert ke vec dan kemudian melakukan push ke dalam vec. Anggap saja kita bertanya kepada laki-laki dan perempuan tentang apa yang mereka pikirkan dari seorang politisi. Mereka akan memberi rating dari 0 sampai 10. Kemudian kita ingin memasukkan angka tersebut ke dalam satu tempat untuk melihat apakah si politisi ini lebih populer dikalangan laki-laki atau perempuan. Berikut codenya:


```rust
use std::collections::HashMap;

fn main() {
    let data = vec![ // Ini adalah data mentah
        ("male", 9),
        ("female", 5),
        ("male", 0),
        ("female", 6),
        ("female", 5),
        ("male", 10),
    ]; // tuple dengan type (&str, i32)

    let mut survey_hash = HashMap::new();

    for item in data { 
        survey_hash.entry(item.0).or_insert(Vec::new()).push(item.1); // melakukan pushes item.1 (i32) ke dalam Vec
    }

    for (male_or_female, numbers) in survey_hash {
        println!("{:?}: {:?}", male_or_female, numbers);
    }
}
```

Hasil cetaknya adalah:

```text
"female", [5, 6, 5]
"male", [9, 0, 10]
```

Line terpenting pada code tersebut adalah: `survey_hash.entry(item.0).or_insert(Vec::new()).push(item.1);`. Jika ia melihat "female", ia akan memeriksa untuk melihat apakah sudah ada key "female" di dalam `HashMap`. Jika tidak, ia akan melakukan insert `Vec::new()`, kemundian melakukan push angkanya ke dalam vec yang sudah dibuat. Apabila ia menemukan bahwa "female" sudah ada di dalam `HashMap`, ia tidak akan membuat Vec baru, dan hanya akan melakuan push angka tersebut ke dalam Vec yang sudah ada.

### HashSet and BTreeSet

`HashSet` sebenarnya adalah `HashMap` yang hanya memiliki key. Pada [laman tentang HashSet](https://doc.rust-lang.org/std/collections/struct.HashSet.html) bagian awalnya memberikan penjelasan seperti berikut:

`A hash set implemented as a HashMap where the value is ().` Sehingga ia adalah `HashMap` dengan keys, tanpa values.

Anda sering menggunakan `HashSet` jika Anda hanya ingin tahu apakah sebuah key ada atau tidak.

Bayangkan Anda memiliki 100 angka random, dan setiap angkanya di antara 1 dan 100. Jika Anda melakukannya seperti code di bawah ini, beberapa angka mungkin akan muncul lebih dari sekali, sementara yang lainnya tidak muncul sama sekali. Jika Anda menaruhnya di dalam `HashSet` maka Anda akan memiliki daftar semua nomor yang muncul.

```rust
use std::collections::HashSet;

fn main() {
    let many_numbers = vec![
        94, 42, 59, 64, 32, 22, 38, 5, 59, 49, 15, 89, 74, 29, 14, 68, 82, 80, 56, 41, 36, 81, 66,
        51, 58, 34, 59, 44, 19, 93, 28, 33, 18, 46, 61, 76, 14, 87, 84, 73, 71, 29, 94, 10, 35, 20,
        35, 80, 8, 43, 79, 25, 60, 26, 11, 37, 94, 32, 90, 51, 11, 28, 76, 16, 63, 95, 13, 60, 59,
        96, 95, 55, 92, 28, 3, 17, 91, 36, 20, 24, 0, 86, 82, 58, 93, 68, 54, 80, 56, 22, 67, 82,
        58, 64, 80, 16, 61, 57, 14, 11];

    let mut number_hashset = HashSet::new();

    for number in many_numbers {
        number_hashset.insert(number); // Ia hanya akan mengambil angka yang unik, sehingga angka yang sama tidak dimasukkan lebih dari sekali
    }

    let hashset_length = number_hashset.len(); // Panjang dari number_hashset memberi tahu kita berapa banyak angka di dalam HashSet tersebut
    println!("There are {} unique numbers, so we are missing {}.", hashset_length, 100 - hashset_length);

    // Akan kita cari tahu angka berapa saja yang tidak terdaftar pada HashSet tersebut
    let mut missing_vec = vec![];
    for number in 0..100 {
        if number_hashset.get(&number).is_none() { // Jika .get() mengembalikan None,
            missing_vec.push(number);
        }
    }

    print!("It does not contain: ");
    for number in missing_vec {
        print!("{} ", number);
    }
}
```

Hasilnya adalah:

```text
There are 66 unique numbers, so we are missing 34.
It does not contain: 1 2 4 6 7 9 12 21 23 27 30 31 39 40 45 47 48 50 52 53 62 65 69 70 72 75 77 78 83 85 88 97 98 99
```

`BTreeSet` mirip dengan `HashSet` sama seperti `BTreeMap` yang mirip dengan `HashMap`. Jika kita cetak setiap item di dalam `HashSet`, kita tidak tahu bagaimana urutannya saat dicetak:

```rust
for entry in number_hashset { // 🚧
    print!("{} ", entry);
}
```

Mungkin saja ia akan mencetak seperti ini: `67 28 42 25 95 59 87 11 5 81 64 34 8 15 13 86 10 89 63 93 49 41 46 57 60 29 17 22 74 43 32 38 36 76 71 18 14 84 61 16 35 90 56 54 91 19 94 44 3 0 68 80 51 92 24 20 82 26 58 33 55 96 37 66 79 73`. Tapi jika Anda melakukan print untuk kedua, ketiga, dan kesekian kalinya, ia hampir tidak pernah mencetaknya dengan urutan yang sama lagi.

Nah ini dia, tentu saja akan lebih mudah apabila `HashSet` diubah menjadi `BTreeSet` jika Anda merasa perlu untuk menampilkannya secara berurutan. Pada code kita, kita hanya perlu mengganti yang semula menggunakan `HashSet` menjadi menggunakan `BTreeSet`.

```rust
use std::collections::BTreeSet; // Ubah HashSet ke BTreeSet

fn main() {
    let many_numbers = vec![
        94, 42, 59, 64, 32, 22, 38, 5, 59, 49, 15, 89, 74, 29, 14, 68, 82, 80, 56, 41, 36, 81, 66,
        51, 58, 34, 59, 44, 19, 93, 28, 33, 18, 46, 61, 76, 14, 87, 84, 73, 71, 29, 94, 10, 35, 20,
        35, 80, 8, 43, 79, 25, 60, 26, 11, 37, 94, 32, 90, 51, 11, 28, 76, 16, 63, 95, 13, 60, 59,
        96, 95, 55, 92, 28, 3, 17, 91, 36, 20, 24, 0, 86, 82, 58, 93, 68, 54, 80, 56, 22, 67, 82,
        58, 64, 80, 16, 61, 57, 14, 11];

    let mut number_btreeset = BTreeSet::new(); // Ubah HashSet ke BTreeSet

    for number in many_numbers {
        number_btreeset.insert(number);
    }
    for entry in number_btreeset {
        print!("{} ", entry);
    }
}
```

Sekarang ia akan mencetaknya secara berurutan: `0 3 5 8 10 11 13 14 15 16 17 18 19 20 22 24 25 26 28 29 32 33 34 35 36 37 38 41 42 43 44 46 49 51 54 55 56 57 58 59 60 61 63 64 66 67 68 71 73 74 76 79 80 81 82 84 86 87 89 90 91 92 93 94 95 96`.

### BinaryHeap

`BinaryHeap` adalah jenis collection yang menarik, karena sebagian besar tidak berurutan tetapi sedikit bagiannya berurutan. Ia menyimpan item terbesar di bagian depan, tetapi item yang lain ada dalam urutan apapun (terkadang acak, terkadang berurutan).

Kita akan menggunakan list yang berbeda sebagai contoh.

```rust
use std::collections::BinaryHeap;

fn show_remainder(input: &BinaryHeap<i32>) -> Vec<i32> { // Function ini menunjukkan sisa di dalam BinaryHeap. Sebenarnya iterator
                                                         // lebih cepat daripada function - kita akan mempelajari tentang ini nanti.
    let mut remainder_vec = vec![];
    for number in input {
        remainder_vec.push(*number)
    }
    remainder_vec
}

fn main() {
    let many_numbers = vec![0, 5, 10, 15, 20, 25, 30]; // Vector angka ini berurutan

    let mut my_heap = BinaryHeap::new();

    for number in many_numbers {
        my_heap.push(number);
    }

    while let Some(number) = my_heap.pop() { // .pop() akan me-return Some(number) jika masih ada angka yang masih bisa di pop, None jika tidak. Ia akan melakukan pop dari depan
        println!("Popped off {}. Remaining numbers are: {:?}", number, show_remainder(&my_heap));
    }
}
```

Hasilnya adalah:

```text
Popped off 30. Remaining numbers are: [25, 15, 20, 0, 10, 5]
Popped off 25. Remaining numbers are: [20, 15, 5, 0, 10]
Popped off 20. Remaining numbers are: [15, 10, 5, 0]
Popped off 15. Remaining numbers are: [10, 0, 5]
Popped off 10. Remaining numbers are: [5, 0]
Popped off 5. Remaining numbers are: [0]
Popped off 0. Remaining numbers are: []
```

Anda bisa melihat bahwa angka pada index ke-0 selalu angka yang terbesar: 25, 20, 15, 10, 5, kemudian 0. Namun yang lainnya diurutkan secara berbeda.

Kasus yang cocok untuk menggunakan `BinaryHeap` adalah untuk membuat sebuah To-do list dengan fitur skala prioritas. Kita akan menggunakan type `BinaryHeap<(u8, &str)>` dimana `u8` adalah angka prioritas yang menunjukkan seberapa pentingnya sebuah task untuk dikerjakan. `&str` adalah deskripsi tentang task apa saja yang harus dilakukan.

```rust
use std::collections::BinaryHeap;

fn main() {
    let mut jobs = BinaryHeap::new();

    // Tambahkan task yang akan dikerjakan hari ini
    jobs.push((100, "Write back to email from the CEO"));
    jobs.push((80, "Finish the report today"));
    jobs.push((5, "Watch some YouTube"));
    jobs.push((70, "Tell your team members thanks for always working hard"));
    jobs.push((30, "Plan who to hire next for the team"));

    while let Some(job) = jobs.pop() {
        println!("You need to: {}", job.1);
    }
}
```

Ia akan selalu mencetak:

```text
You need to: Write back to email from the CEO
You need to: Finish the report today
You need to: Tell your team members thanks for always working hard
You need to: Plan who to hire next for the team
You need to: Watch some YouTube
```

### VecDeque

`VecDeque` adalah `Vec` yang mana ia bisa melakukan pop entah dari depan ataupun dari belakang. Rust memiliki `VecDeque` dikarenakan `Vec` sangat baik dalam hal melakukan pop dari belakang (item terakhir), tapi tidak begitu baik untuk melakukan pop dari depan. Saat Anda melihat `.pop()` pada `Vec`, ia hanya mengambil item terakhir (ujung paling kanan) dan tidak ada posisi dari element vec yang berpindah. Namun jika Anda melakukannya dari arah sebaliknya (melakukan pop di ujung kiri), semua item yang berada di sebelah kanan akan bergeser 1 langkah ke kiri. Anda bisa melihat ini pada deskripsi tentang `.remove()`:


```text
Removes and returns the element at position index within the vector, shifting all elements after it to the left.
```

Sehingga, jika kamu menggunakannya:

```rust
fn main() {
    let mut my_vec = vec![9, 8, 7, 6, 5];
    my_vec.remove(0);
}
```

ia akan menghapus `9`. `8` yang berada pada index ke-1 akan berpindah ke index ke-0, `7` yang berada pada index ke-2 akan berpindah ke index ke-1, dan seterusnya. Bayangkan sebuah tempat parkir mobil dimana setiap satu mobil keluar dari tempat parkir tersebut, maka antrian parkiran dibelakangnya akan bergerak maju ke depan.

Sebagai contoh, code dibawah ini *banyak* menyita kinerja komputer. Faktanya, jika Anda menjalankan ini pada Rust Playground, ada kemungkinan Playground akan menyerah karena cara ini benar-benar memakan banyak resource.

```rust
fn main() {
    let mut my_vec = vec![0; 600_000];
    for i in 0..600000 {
        my_vec.remove(0);
    }
}
```

Program di atas menggunakan `Vec` dengan 600,000 element yang mana elementnya adalah 0. Setiap kali kita menggunakan `remove(0)` pada vector tersebut, ia akan menggeser setiap 0 ke kiri sebanyak satu langkah. Dan hal ini secara berulang dilakukan sebanyak 600,000 kali.

Anda tidak perlu mengkhawatirkan hal tersebut jika Anda menggunakan `VecDeque`. Ia biasanya memanglah lebih lambat daripada `Vec`, namun jika Anda perlu melakukan sesuatu pada kedua ujung `VecDeque` tersebut (contohnya pop) maka ia relatif lebih cepat. Anda cukup menggunakan `VecDeque::from` pada `Vec` untuk membuatnya. Code sebelumnya kita ubah menjadi seperti ini:

```rust
use std::collections::VecDeque;

fn main() {
    let mut my_vec = VecDeque::from(vec![0; 600000]);
    for i in 0..600000 {
        my_vec.pop_front(); // pop_front sama seperti .pop hanya saja dilakukan dari depan
    }
}
```

Sekarang ia menjadai lebih cepat, dan pada Playground ia dijalankan pada hitungan detik alih-alih terhenti ditengah jalan.

Pada contoh selanjutnya, kita memiliki `Vec` yang berisi list to-do. Kemudian kita buat sebuah `VecDeque` dan menggunakan `.push_front()` meletakkan mereka dari depan, jadinya item pertama yang kita tambahkan akan berada di sebelah kanan. Tapi setiap item yang kita push typenya adalah `(&str, bool)`: `&str` adalah deskripsi dan `false` berarti tasknya belum dikerjakan. Kita buat dan gunakan function `done()` untuk melakukan pop item yang berada di belakang, namun kita tidak ingin menghapusnya. Alih-alih menghapusnya, kita ubah `false` menjadi `true` dan mem-pushnya ke bagian depan sehingga kita masih tetap menyimpannya.

Codenya seperti berikut:

```rust
use std::collections::VecDeque;

fn check_remaining(input: &VecDeque<(&str, bool)>) { // Setiap item bertype (&str, bool)
    for item in input {
        if item.1 == false {
            println!("You must: {}", item.0);
        }
    }
}

fn done(input: &mut VecDeque<(&str, bool)>) {
    let mut task_done = input.pop_back().unwrap(); // pop element yang berada di belakang
    task_done.1 = true;                            // sekarang jadikan statusnya sebagai done - ganti menjadi true
    input.push_front(task_done);                   // letakkan ia dibagian depan menggunakan .push_front()
}

fn main() {
    let mut my_vecdeque = VecDeque::new();
    let things_to_do = vec!["send email to customer", "add new product to list", "phone Loki back"];

    for thing in things_to_do {
        my_vecdeque.push_front((thing, false));
    }

    done(&mut my_vecdeque);
    done(&mut my_vecdeque);

    check_remaining(&my_vecdeque);

    for task in my_vecdeque {
        print!("{:?} ", task);
    }
}
```

Hasilnya adalah:

```text
You must: phone Loki back
("add new product to list", true) ("send email to customer", true) ("phone Loki back", false)
```

## The ? operator

Ada cara yang lebih pendek untuk menghandle `Result` (dan `Option`), lebih pendek daripada `match` dan bahkan lebih pendek daripada `if let`. Ia biasa disebut sebagai "question mark operator", dan Anda benar-benar hanya cukup menuliskan `?`. Setelah menuliskan function yang me-return sebuah result, Anda bisa menambahkan `?`. Ia akan melakukan:

- me-return apa yang ada di dalam `Result` jika ia `Ok`
- Lewati saja jika ia `Err`

Dengan kata lain, `?` melakukan hampir segalanya untuk Anda.

Kita bisa mencoba menggunakannya menggunakan `.parse()`. Kita akan menuliskan sebuah function bernama `parse_str` yang mana akan mencoba mengubah `&str` menjadi `i32`. Codenya seperti ini:

```rust
use std::num::ParseIntError;

fn parse_str(input: &str) -> Result<i32, ParseIntError> {
    let parsed_number = input.parse::<i32>()?; // Disinilah `?` digunakan
    Ok(parsed_number)
}

fn main() {}
```

Function ini akan mengambil `&str`. Jika ia `Ok`, ia akan mengembalikan `i32` yang terbungkus dengan `Ok`. Jika ia adalah `Err`, ia akan mengembalikan `ParseIntError`. Kemudian kita mencoba untuk melakukan parsing ke angka, dan menggunakan `?`. Yang artinya "periksa apakah ia sebuah error, dan berikan kami hasilnya jika isinya aman". Jika status kembaliannya tidak Ok, ia akan mengembalikan error dan selesai. Tapi jika Ok, ia akan ke baris yang selanjutnya. Pada baris selanjutnya adalah angka yang terbungkus dengan `Ok()`. Kita perlu membungkusnya dengan `Ok` karena returnnya adalah `Result<i32, ParseIntError>`, bukan `i32`.

Sekarang, kita bisa menggunakan function yang telah kita buat. Mari kita liha tapa yang ia lakukan terhadap vec dengan element `&str`.

```rust
fn parse_str(input: &str) -> Result<i32, std::num::ParseIntError> {
    let parsed_number = input.parse::<i32>()?;
    Ok(parsed_number)
}

fn main() {
    let str_vec = vec!["Seven", "8", "9.0", "nice", "6060"];
    for item in str_vec {
        let parsed = parse_str(item);
        println!("{:?}", parsed);
    }
}
```

Hasilnya adalah:

```text
Err(ParseIntError { kind: InvalidDigit })
Ok(8)
Err(ParseIntError { kind: InvalidDigit })
Err(ParseIntError { kind: InvalidDigit })
Ok(6060)
```

Bagaimana kita menemukan `std::num::ParseIntError`? Salah satu cara termudahnya adalah dengan cara "menanyakannya" kepada compiler.

```rust
fn main() {
    let failure = "Not a number".parse::<i32>();
    failure.rbrbrb(); // ⚠️ Compiler: "Apa itu rbrbrb()???"
}
```

Compiler tidak memahami code tersebut, dan mengatakan:

```text
error[E0599]: no method named `rbrbrb` found for enum `std::result::Result<i32, std::num::ParseIntError>` in the current scope
 --> src\main.rs:3:13
  |
3 |     failure.rbrbrb();
  |             ^^^^^^ method not found in `std::result::Result<i32, std::num::ParseIntError>`
```

Jadinya `std::result::Result<i32, std::num::ParseIntError>` adalah signature yang kita perlukan.

Kita tidak perlu menuliskan `std::result::Result` karena `Result` selalu "in scope" (in scope = siap untuk digunakan / siap pakai). Rust melakukan ini ke semua type yang sering kita gunakan, sehingga kita tidak perlu lagi menulis `std::result::Result`, `std::collections::Vec`, dan seterusnya.

Kita belum berurusan dengan program yang mengharuskan kita menghandle file, oleh karena itu operator `?` belum terlalu terlihat berguna untuk sekarang ini. Namun ini adalah contoh singkat (yang sedikit kurang berguna) yang menunjukkan bagaimana Anda bisa menggunakannya dalam satu baris. Alih-alih hanya membuat`i32` menggunakan `.parse()`, justru kita melakukan hal yang agak lebih rumit lagi. Kita membuatnya ke `u16`, dan mengubahnya lagi ke `String`, kemudian diubah ke `u32`, kemudian ke `String` lagi, dan akhirnya diubah ke `i32`.

```rust
use std::num::ParseIntError;

fn parse_str(input: &str) -> Result<i32, ParseIntError> {
    let parsed_number = input.parse::<u16>()?.to_string().parse::<u32>()?.to_string().parse::<i32>()?; // Tambahkan ? setiap mengecek dan pass ke method selanjutnya
    Ok(parsed_number)
}

fn main() {
    let str_vec = vec!["Seven", "8", "9.0", "nice", "6060"];
    for item in str_vec {
        let parsed = parse_str(item);
        println!("{:?}", parsed);
    }
}
```

Program ini juga mencetak hal yang sama, tapi untuk yang ini kita meng-handle tiga `Result` dalam satu baris. Nantinya kita akan menggunakan cara ini saat berurusan dengan file, karena hal yang berurusan dengan file akan selalu me-return `Result` karena banyak sekali kemungkinan untuk melakukan kesalahan.

Bayangkan hal ini: Anda ingin membuka sebuah file, menulis sesuatu di file tersebut, dan menutupnya. Pertama-tama, Anda perlu berhasil menemukan filenya (tentunya ini memerlukan `Result`). Kemudian Anda harus berhasil menuliskan sesuatu didalamnya (dan ini juga `Result`). Dengan `?` Anda bisa melakukannya dengan satu baris saja.

### When panic and unwrap are good

Rust memiliki macro `panic!` yang mana bisa Anda gunakan untuk membuat panic. Ia cukup mudah untuk digunakan:

```rust
fn main() {
    panic!("Time to panic!");
}
```

Pesan `"Time to panic!"` muncul saat Anda menjalankan programnya: `thread 'main' panicked at 'Time to panic!', src\main.rs:2:3`

Anda akan mengingat bahwa `src\main.rs` adalah nama folder dan file, dan `2:3` adalah baris and kolom. Dengan informasi ini, Anda bisa menemukan codenya dan memperbaikinya.

`panic!` adalah macro yang baik digunakan untuk memastikan bahwa Anda tahu bahwa ada sesuatu yang berubah. Contohnya, function yang bernama `prints_three_things` selalu mencetak index [0], [1], dan [2] dari sebuah vector. Semuanya baik-baik saja karena kita selalu memberikan vector dengan tiga item:

```rust
fn prints_three_things(vector: Vec<i32>) {
    println!("{}, {}, {}", vector[0], vector[1], vector[2]);
}

fn main() {
    let my_vec = vec![8, 9, 10];
    prints_three_things(my_vec);
}
```

Program tersebut akan mencetak `8, 9, 10` dan semuanya baik-baik saja.

Tapi bayangkan bahwa kemudian kita menulis code menjadi lebih panjang, dan melupakan bahwa `my_vec` tepatnya hanya untuk vec dengan panjang 3 element. Sekarang `my_vec` pada code dibawah ini memiliki 6 element:

```rust
fn prints_three_things(vector: Vec<i32>) {
  println!("{}, {}, {}", vector[0], vector[1], vector[2]);
}

fn main() {
  let my_vec = vec![8, 9, 10, 10, 55, 99]; // Sekarang my_vec memiliki 6 element
  prints_three_things(my_vec);
}
```

Tentu saja tidak terjadi errorapapun, karena [0] dan [1] dan [2] mampu dicapai oleh `Vec` yang lebih panjang. Namun bagaimana jika menjadi sangat penting untuk tetap menggunakan `Vec` dengan panjang tiga elemen? Kita pun tidak tahu bahwa ini adalah sebuah masalah karena compiler pun tidak memberikan panic. Untuk menyelesaikan problem ini, kita harus melakukan hal seperti berikut:

```rust
fn prints_three_things(vector: Vec<i32>) {
    if vector.len() != 3 {
        panic!("my_vec must always have three items") // akan panic jika panjang elementnya bukan 3
    }
    println!("{}, {}, {}", vector[0], vector[1], vector[2]);
}

fn main() {
    let my_vec = vec![8, 9, 10];
    prints_three_things(my_vec);
}
```

Sekarang kita akan tahu apabila vectornya memiliki panjang 6 element karena ia akan memberikan pesan panic seperti yang kita tuliskan:

```rust
    // ⚠️
fn prints_three_things(vector: Vec<i32>) {
    if vector.len() != 3 {
        panic!("my_vec must always have three items")
    }
    println!("{}, {}, {}", vector[0], vector[1], vector[2]);
}

fn main() {
    let my_vec = vec![8, 9, 10, 10, 55, 99];
    prints_three_things(my_vec);
}
```

Pesan yang diberikan oleh program tersebut adlaah `thread 'main' panicked at 'my_vec must always have three items', src\main.rs:8:9`. Bersyukurlah dengan adanya `panic!`, sekarang kita mengingat bahwa `my_vec` seharusnya hanya berisi tiga element saja. Jadinya `panic!` adalah macro yang baik untuk membuat pengingat pada code yang Anda buat.

Ada 3 macro lainnya yang mirip dengan `panic!` yang akan sering Anda gunakan pada saat melakukan testing. Mereka adalah: `assert!`, `assert_eq!`, dan `assert_ne!`.

Berikut adalah penjelasannya:

- `assert!()`: jika sesuatu yang berada di dalam `()` bukanlah true, program akan panic.
- `assert_eq!()`: 2 buah item di dalam `()` harus sama.
- `assert_ne!()`: 2 buah item di dalam `()` harus tidak sama. (*ne* artinya not equal / tidak sama)

Contohnya:

```rust
fn main() {
    let my_name = "Loki Laufeyson";

    assert!(my_name == "Loki Laufeyson");
    assert_eq!(my_name, "Loki Laufeyson");
    assert_ne!(my_name, "Mithridates");
}
```

Program di atas tidak akan melakukan, karena semua macro assertnya sesuai. (Inilah yang kita inginkan)

Anda juga bisa menambahkan pesan jika Anda menginginkannya.

```rust
fn main() {
    let my_name = "Loki Laufeyson";

    assert!(
        my_name == "Loki Laufeyson",
        "{} should be Loki Laufeyson",
        my_name
    );
    assert_eq!(
        my_name, "Loki Laufeyson",
        "{} and Loki Laufeyson should be equal",
        my_name
    );
    assert_ne!(
        my_name, "Mithridates",
        "You entered {}. Input must not equal Mithridates",
        my_name
    );
}
```

Pesan yang ditulis tersebut hanya akan muncul apabila programnya panic. Sehingga jika Anda menjalankan ini:

```rust
fn main() {
    let my_name = "Mithridates";

    assert_ne!(
        my_name, "Mithridates",
        "You enter {}. Input must not equal Mithridates",
        my_name
    );
}
```

Ia akan menampilkan:

```text
thread 'main' panicked at 'assertion failed: `(left != right)`
  left: `"Mithridates"`,
 right: `"Mithridates"`: You entered Mithridates. Input must not equal Mithridates', src\main.rs:4:5
```

Jadi, compiler mengatakan "Kamu bilang bahwa kiri != kanan, tapi hasilnya justru kiri == kanan". Dan ia memunculkan pesan yang telah kita tuliskan, `You entered Mithridates. Input must not equal Mithridates`.

`unwrap` juga bagus di saat Anda menulis code dan membuatnya crash apabila ada problem pada code tersebut. Kemudian, di saat code yang Anda tulis telah selesai, ada baiknya mengubah `unwrap` ke sesuatu yang lainnya yang tidak menybabkan crash pada program.

Anda juga bisa menggunakan `expect`, yang mana mirip seperti `unwrap`, namun agak lebih baik, karena Anda bisa memnentukan sendiri apa pesan errornya. Textbooks pun biasanya memberika saran seperti ini: "Jika Anda banyak menggunakan `.unwrap()`, setidaknya gunakan `.expect()` untuk pesan error yang lebih baik."

Program di bawah ini akan crash:

```rust
   // ⚠️
fn get_fourth(input: &Vec<i32>) -> i32 {
    let fourth = input.get(3).unwrap();
    *fourth
}

fn main() {
    let my_vec = vec![9, 0, 10];
    let fourth = get_fourth(&my_vec);
}
```

Pesan errornya adalah `thread 'main' panicked at 'called Option::unwrap() on a None value', src\main.rs:7:18`.

Sekarang kita tuliskan pesannya menggunakan `expect`:

```rust
   // ⚠️
fn get_fourth(input: &Vec<i32>) -> i32 {
    let fourth = input.get(3).expect("Input vector needs at least 4 items");
    *fourth
}

fn main() {
    let my_vec = vec![9, 0, 10];
    let fourth = get_fourth(&my_vec);
}
```

Tentu saja program yang inipun akan crash juga, namun dengan pesan error yang lebih baik: `thread 'main' panicked at 'Input vector needs at least 4 items', src\main.rs:7:18`. `.expect()` sedikit lebih baik daripada `.unwrap()` karena hal ini, tapi ia akan tetap panic saat membuka `None`. Sekarang, kita akan mencontohkan sebuah bad practice, yaitu function yang mencoba untuk melakukan unwrap dua kali. Ia mengambil `Vec<Option<i32>>` sebagai parameter, sehingga mungkin beberapa bagiannya akan menghasilkan `Some<i32>` atau juga `None`.

```rust
fn try_two_unwraps(input: Vec<Option<i32>>) {
    println!("Index 0 is: {}", input[0].unwrap());
    println!("Index 1 is: {}", input[1].unwrap());
}

fn main() {
    let vector = vec![None, Some(1000)]; // Vector ini menghasilkan None, sehingga ia akan panic
    try_two_unwraps(vector);
}
```

Pesan errornya adalah: ``thread 'main' panicked at 'called `Option::unwrap()` on a `None` value', src\main.rs:2:32``. Kita tidak yakin apakah errornya muncul dari `.unwrap()` yang pertama ataukah `.unwrap()` yang kedua sampai kita memeriksa baris codenya. Ini akan lebih baik apabila kita melakukan pengecekan terhadap panjang vectornya dan juga tidak melakukannya dengan unwrap. Dengan `.expect()` setidaknya program kita akan menjadi *sedikit* lebih baik. Inilah contoh codenya apabila kita menggunakan `.expect()`:

```rust
fn try_two_unwraps(input: Vec<Option<i32>>) {
    println!("Index 0 is: {}", input[0].expect("The first unwrap had a None!"));
    println!("Index 1 is: {}", input[1].expect("The second unwrap had a None!"));
}

fn main() {
    let vector = vec![None, Some(1000)];
    try_two_unwraps(vector);
}
```

Sehingga errornya menjadi lebih baik: `thread 'main' panicked at 'The first unwrap had a None!', src\main.rs:2:32`. Kita diberikan informasi tentang unwrap yang mana yang menghasilkan error sehingga kita bisa dengan mudah menemukannya dan memperbaikinya.


Anda juga bisa menggunakan `unwrap_or` jika Anda ingin selalu memiliki nilai yang ingin Anda pilih. Jika Anda melakukan ini maka ia tidak akan pernah panic. Yang perlu dicatat adalah:

- 1) Ini bagus karena program menjadi tidak akan panic, namun
- 2) Mungkin saja tidak bagus apabila Anda menginginkan program menjadi panic jika terdapat problem pada code tersebut.

Tapi biasanya kita tidak ingin program yang kita buat menjadi panic, jadinya `unwrap_or` adalah cara yang baik untuk digunakan.

```rust
fn main() {
    let my_vec = vec![8, 9, 10];

    let fourth = my_vec.get(3).unwrap_or(&0); // Jika .get tidak bekerja, kita akan membuat value &0.
                                              // .get mengembalikan sebuah reference, sehingga kita perlu &0, bukan 0
    println!("{}", fourth);                   // Anda bisa menulis "*fourth" jika Anda ingin fourth menjadi
                                              // 0 dan bukan &0, tapi disini kita hanya mencetaknya saja, sehingga hal itu tidaklah penting
}
```

Ia akan mencetak `0` karena `.unwrap_or(&0)` memberikan 0 meskipun `.get()` memberikan `None`.

## Traits

Sebelumnya kita telah melihat beberapa trait: `Debug`, `Copy`, `Clone` semuanya adalah trait. Untuk memberikan trait ke sebuah type, Anda perlu mengimplementasiaknnya. Karena `Debug` dan yang lainnya sangatlah umum, kita memiliki attribute yang secara otomatis akan melakukannya. Itulah yang terjadi di saat Anda menuliskan `#[derive(Debug)]`: secara otomatis Anda mengimplementasikan `Debug`.

```rust
#[derive(Debug)]
struct MyStruct {
    number: usize,
}

fn main() {}
```

Tapi traits yang lainnya lebih sulit lagi, karena Anda perlu mengimplementasikannya secara manual menggunakan `impl`. Contohnya, `Add` (berada pada `std::ops::Add`) digunakan untuk menambahkan 2 hal. Tapi Rust tidak tahu persis bagaimana Anda ingin menambahkan sesuatu, jadi Anda harus memberitahukannya kepada compiler.

```rust
struct ThingsToAdd {
    first_thing: u32,
    second_thing: f32,
}

fn main() {}
```

Kita bisa menambahkan `first_thing` dan `second_thing`, namun kita perlu untuk memberikan informasi lebih lanjut. Mungkin kita ingin hasilnya adalah `f32`, sehingga ditulis seperti ini:

```rust
// 🚧
let result = self.second_thing + self.first_thing as f32
```

Atau mungkin kita menginginkan integer sebagai hasilnya, maka seperti inilah codenya:

```rust
// 🚧
let result = self.second_thing as u32 + self.first_thing
```

Atau mungkin kita ingin sekedar meletakkan `self.first_thing` disebelah `self.second_thing` dan mengatakan pada compiler bahwa ini adalah cara kita ingin melakukan penambahannya. Sehingga jika kita menambahkan 55 dan 33.4, kita ingin hasil akhirnya adalah 5533.4, bukan 88.4.

Jadi, pertama, kita lihat terlebih dahulu bagaimana cara membuat trait. Yang terpenting untuk diingat dari `trait` adalah bahwa ia menyangkut tentang behaviour/sifat/watak. Untuk membuat trait, tuliskan `trait` dan kemudian buatkan functionnya.

```rust
struct Animal { // struct sederhana - Animal yang hanya memiliki nama
    name: String,
}

trait Dog { // Dog trait memberikan beberapa functionality/kegunaan
    fn bark(&self) { // Ia bisa menggonggong
        println!("Woof woof!");
    }
    fn run(&self) { // dan Ia bisa berlari
        println!("The dog is running!");
    }
}

impl Dog for Animal {} // Sekarang, Animal memiliki trait/sifat/watak dari Dog

fn main() {
    let rover = Animal {
        name: "Rover".to_string(),
    };

    rover.bark(); // Sekarang Animal bisa menggunakan bark()
    rover.run();  // dan juga bisa menggunakan run()
}
```

Programnya berjalan, namun kita tidak ingin mencetak "The dog is running". Anda bisa mengubah method yang diberikan `trait` jika Anda menginginkannya, tapi Anda harus memiliki type yang sama. Itu berarti ia perlu mengambil hal yang sama, dan mengembalikan hal yang sama pula. Contohnya, kita bisa mengubah method `.run()`, namun kita harus mengikuti signaturenya. Berikut signaturenya:

```rust
// 🚧
fn run(&self) {
    println!("The dog is running!");
}
```

`fn run(&self)` berarti "fn `run()` mengambil `&self`, dan tidak me-return apapun". Sehingga Anda tidak bisa melakukan hal seperti ini:

```rust
fn run(&self) -> i32 { // ⚠️
    5
}
```

Compiler Rust akan mengatakan:

```text
   = note: expected fn pointer `fn(&Animal)`
              found fn pointer `fn(&Animal) -> i32`
```

Tapi kita bisa melakukan hal seperti ini:

```rust
struct Animal { // struct sederhana - Animal yang hanya memiliki nama
    name: String,
}

trait Dog { // Dog trait memberikan beberapa functionality/kegunaan
    fn bark(&self) { // Ia bisa menggonggong
        println!("Woof woof!");
    }
    fn run(&self) { // dan Ia bisa berlari
        println!("The dog is running!");
    }
}

impl Dog for Animal {
    fn run(&self) {
        println!("{} is running!", self.name);
    }
}

fn main() {
    let rover = Animal {
        name: "Rover".to_string(),
    };

    rover.bark(); // Sekarang Animal bisa menggunakan bark()
    rover.run();  // dan juga bisa menggunakan run()
}
```

Sekarang ia akan mencetak `Rover is running!`. Programnya berjalan karena kita me-return `()` (tidak ada apapun), yang mana itu adalah signature traitnya.


Saat Anda membuat sebuah trait, Anda bisa menuliskan hanya function signaturenya saja (tanpa ada instruksi apapun). Namun jika Anda melakukan hal itu, user (programmer lainnya) yang nantinya menggunakannya haruslah menuliskan functionnya. Mari kita coba. Sekarang kita ubah `bark()` dan `run()` hanya dengan menuliskannya dengan `fn bark(&self);` dan `fn run(&self);`. Ini bukanlah function yang utuh (hanya sekedar signature), sehingga user yang ingin menggunakannya harus menuliskan function utuhnya di `impl`.

```rust
struct Animal {
    name: String,
}

trait Dog {
    fn bark(&self); // bark() mengatakan bahwa ia memerlukan &self dan tidak me-return apapun
    fn run(&self); // run() mengatakan bahwa ia memerlukan &self dan tidak me-return apapun.
                   // Sehingga sekarang kita harus menuliskan fungsinya sendiri.
}

impl Dog for Animal {
    fn bark(&self) {
        println!("{}, stop barking!!", self.name);
    }
    fn run(&self) {
        println!("{} is running!", self.name);
    }
}

fn main() {
    let rover = Animal {
        name: "Rover".to_string(),
    };

    rover.bark();
    rover.run();
}
```

Jadi saat Anda membuat sebuah trait, Anda harus memikirkan: "Function yang mana yang harus Aku tulis? Dan function yang mana yang harus ditulis sendiri oleh user?" Jika Anda berfikir bahwa user akan menggunakan function yang sama setiap saat, maka tuliskan saja functionnya. Jika Anda berfikir bahwa user akan menggunakannya secara berbeda, maka cukup tuliskan function signaturenya saja.

Jadi, mari kita coba implementasikan trait Display pada struct yang kita buat ini. Pertama-tama, kita akan membuat struct yang sederhana:

```rust
struct Cat {
    name: String,
    age: u8,
}

fn main() {
    let mr_mantle = Cat {
        name: "Reggie Mantle".to_string(),
        age: 4,
    };
}
```

Sekarang kita ingin mencetak `mr_mantle`. Debug sangat mudah diimplementasikan menggunakan derive:

```rust
#[derive(Debug)]
struct Cat {
    name: String,
    age: u8,
}

fn main() {
    let mr_mantle = Cat {
        name: "Reggie Mantle".to_string(),
        age: 4,
    };

    println!("Mr. Mantle is a {:?}", mr_mantle);
}
```

namun Debug print bukanlah cara "tercantik" untuk melakukan print, karena ia akan terlihat seperti ini.

```text
Mr. Mantle is a Cat { name: "Reggie Mantle", age: 4 }
```

Sehingga kita perlu untuk mengimplementasikan `Display` pada `Cat` jika kita ingin hasil cetaknya terlihat lebih baik. Pada [https://doc.rust-lang.org/std/fmt/trait.Display.html](https://doc.rust-lang.org/std/fmt/trait.Display.html) kita bisa melihat informasi tentang Display, dan juga satu contoh yang telah disediakan. Contohnya mirip seperti ini:

```rust
use std::fmt;

struct Position {
    longitude: f32,
    latitude: f32,
}

impl fmt::Display for Position {
    fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(f, "({}, {})", self.longitude, self.latitude)
    }
}

fn main() {}
```

Pada code di atas, ada beberapa bagian yang belum bisa kita pahami, seperti `<'_>` dan apa yang `f` lakukan. Tapi kita paham tentang struct `Position`: struct yang berisi dua buah field yang keduanya bertype `f32`. Kita juga mengerti bahwa `self.longitude` dan `self.latitude` adalah field dari struct. Jadi mungkin kita bisa menggunakan code ini untuk struct yang kita buat, yaitu dengan `self.name` dan `self.age`. Juga, `write!` terlihat mirip dengan `println!` sehingga kita cukup familiar. Sehingga kita bisa menuliskannya seperti ini:

```rust
use std::fmt;

struct Cat {
    name: String,
    age: u8,
}

impl fmt::Display for Cat {
    fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(f, "{} is a cat who is {} years old.", self.name, self.age)
    }
}

fn main() {}
```

Mari kita tambahkan `fn main()`. Sekarang code kita terlihat seperti ini:

```rust
use std::fmt;

struct Cat {
    name: String,
    age: u8,
}

impl fmt::Display for Cat {
  fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
      write!(f, "{} is a cat who is {} years old.", self.name, self.age)
  }
}

fn main() {
    let mr_mantle = Cat {
        name: "Reggie Mantle".to_string(),
        age: 4,
    };

    println!("{}", mr_mantle);
}
```

Voila! Berhasil. Sekarang saat kita menggunakan `{}` untuk melakuka print, kita mendapatkan `Reggie Mantle is a cat who is 4 years old.`. Ini terlihat lebih baik.


Ah ya, jika Anda mengimplementasikan `Display` maka Anda secara otomatis mendapatkan trait `ToString`. Itu terjadi karena Anda menggunakan macro `format!` untuk function `.fmt()`, yang memungkinkan Anda membuat `String` dengan `.to_string()`. Jadi kita bisa melakukan hal seperti ini dimana kita melakukan pass pada `mr_mantle` ke function yang memerlukan `String`, atau yang lainnya.

```rust
use std::fmt;
struct Cat {
    name: String,
    age: u8,
}

impl fmt::Display for Cat {
    fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(f, "{} is a cat who is {} years old.", self.name, self.age)
    }
}

fn print_cats(pet: String) {
    println!("{}", pet);
}

fn main() {
    let mr_mantle = Cat {
        name: "Reggie Mantle".to_string(),
        age: 4,
    };

    print_cats(mr_mantle.to_string()); // ubah mr_mantle yang semula adalah Cat menjadi String
    println!("Mr. Mantle's String is {} letters long.", mr_mantle.to_string().chars().count()); // ubah ia menjadi char dan hitung total charnya
}
```

Hasilnya adalah:

```text
Reggie Mantle is a cat who is 4 years old.
Mr. Mantle's String is 42 letters long.
```




Hal yang perlu diingat tentang trait adalah bahwa trait itu adalah behaviour/sifat dari sesuatu. Bagaimana `struct` Anda bertindak? Tindakan apa saja yang bisa dilakukannya? Untuk itulah trait ada. Jika Anda memikirkan tentang beberapa trait yang telah kita lihat sejauh ini, semuanya adalah tentang perilaku/sifat/watak: `Copy` adalah sesuatu yang bisa dilakukan oleh sebuah type. `Display` juga adalah sesuatu yang bisa dilakukan oleh sebuah type. `ToString` adalah trait lainnya, dan ia juga adalah sesuatu yang bisa dilakukan oleh sebuah type: ia bisa mengubah sesuatu menjadi `String`. Pada trait `Dog`, kata *dog* bukan berarti adalah sesuatu yang Anda lakukan, tapi lebih tepatnya adalah memberikannya satu atau beberapa method yang memungkinkannya untuk melakukan sesuatu. Anda juga bisa mengimplementasikannya pada `struct Poodle` atau `struct Beagle` dan mereka semua diberikan method yang berada di trait `Dog`.

Mari kita melihat pada contoh lain yang lebih berhubungan tentang perilaku. Kita akan membayangkan sebuah game fantasi dengan beberapa karakter sederhana. Salah satu karakternya adalah `Monster`, dan yang lainnya adalah `Wizard` dan `Ranger`. `Monster` hanya memiliki `health` sehingga kita bisa menyerangnya. Sementara dua karakter lainnya belum kita berikan apapun. Tapi kita buat dua buah trait. Yang satu bernama `FightClose`, yang memungkinkan Anda bertarung dari jarak dekat. Trait yang lainnya adalah `FightFromDistance`, yang membuat Anda bisa bertarung jarak jauh. Hanya `Ranger` yang bisa menggunakan `FightFromDistance`. Berikut adalah codenya:

```rust
struct Monster {
    health: i32,
}

struct Wizard {}
struct Ranger {}

trait FightClose {
    fn attack_with_sword(&self, opponent: &mut Monster) {
        opponent.health -= 10;
        println!(
            "You attack with your sword. Your opponent now has {} health left.",
            opponent.health
        );
    }
    fn attack_with_hand(&self, opponent: &mut Monster) {
        opponent.health -= 2;
        println!(
            "You attack with your hand. Your opponent now has {} health left.",
            opponent.health
        );
    }
}
impl FightClose for Wizard {}
impl FightClose for Ranger {}

trait FightFromDistance {
    fn attack_with_bow(&self, opponent: &mut Monster, distance: u32) {
        if distance < 10 {
            opponent.health -= 10;
            println!(
                "You attack with your bow. Your opponent now has {} health left.",
                opponent.health
            );
        }
    }
    fn attack_with_rock(&self, opponent: &mut Monster, distance: u32) {
        if distance < 3 {
            opponent.health -= 4;
        }
        println!(
            "You attack with your rock. Your opponent now has {} health left.",
            opponent.health
        );
    }
}
impl FightFromDistance for Ranger {}

fn main() {
    let radagast = Wizard {};
    let aragorn = Ranger {};

    let mut uruk_hai = Monster { health: 40 };

    radagast.attack_with_sword(&mut uruk_hai);
    aragorn.attack_with_bow(&mut uruk_hai, 8);
}
```

Hasilnya adalah:

```text
You attack with your sword. Your opponent now has 30 health left.
You attack with your bow. Your opponent now has 20 health left.
```

Kita pass `self` di dalam trait yang kita buat setiap saat, tapi kita tidak bisa melakukan banyak hal dengan `self` untuk sekarang ini. Itu karena Rust tidak tahu type apa yang akan menggunakannya. Bisa saja `Wizard` yang menggunakannya, bisa juga `Ranger`, atau mungkin juga struct baru yang kita beri nama dengan `Toefocfgetobjtnode` atau apapun itu. Untuk memberikan beberapa fungsionalitas kepada `self`, kita bisa menambahkan sifat-sifat lain yang diperlukan pada trait, atau dalam kata lain, kita bisa menambahkan trait ke trait lainnya. Jika kita ingin melakukan print menggunakan `{:?}` sebagai contoh, maka kita memerlukan `Debug`. Anda bisa menambahkannya ke trait hanya dengan menuliskannya setelah `:` (colon). Sekarang codenya terlihat seperti ini:


```rust
struct Monster {
    health: i32,
}

#[derive(Debug)] // Sekarang Wizard memiliki Debug
struct Wizard {
    health: i32, // Sekarang Wizard memiliki health
}
#[derive(Debug)] // Begitu juga dengan Ranger
struct Ranger {
    health: i32, // Begitu juga dengan Ranger
}

trait FightClose: std::fmt::Debug { // Sekarang type memerlukan Debug untuk menggunakan FightClose
    fn attack_with_sword(&self, opponent: &mut Monster) {
        opponent.health -= 10;
        println!(
            "You attack with your sword. Your opponent now has {} health left. You are now at: {:?}", // Kita sekarang bisa mencetak self menggunakan {:?} karena kita memiliki Debug
            opponent.health, &self
        );
    }
    fn attack_with_hand(&self, opponent: &mut Monster) {
        opponent.health -= 2;
        println!(
            "You attack with your hand. Your opponent now has {} health left.  You are now at: {:?}",
            opponent.health, &self
        );
    }
}
impl FightClose for Wizard {}
impl FightClose for Ranger {}

trait FightFromDistance: std::fmt::Debug { // Kita juga bisa melakukan hal seperti ini pada trait, `FightFromDistance: FightClose` , karena FightClose sudah menggunakan Debug, tapi ini adalah hal yang berbeda karena dengan cara ini Ranger bisa mengakses trait Wizard.
    fn attack_with_bow(&self, opponent: &mut Monster, distance: u32) {
        if distance < 10 {
            opponent.health -= 10;
            println!(
                "You attack with your bow. Your opponent now has {} health left.  You are now at: {:?}",
                opponent.health, self
            );
        }
    }
    fn attack_with_rock(&self, opponent: &mut Monster, distance: u32) {
        if distance < 3 {
            opponent.health -= 4;
        }
        println!(
            "You attack with your rock. Your opponent now has {} health left.  You are now at: {:?}",
            opponent.health, self
        );
    }
}
impl FightFromDistance for Ranger {}

fn main() {
    let radagast = Wizard { health: 60 };
    let aragorn = Ranger { health: 80 };

    let mut uruk_hai = Monster { health: 40 };

    radagast.attack_with_sword(&mut uruk_hai);
    aragorn.attack_with_bow(&mut uruk_hai, 8);
}
```

Hasil printnya adalah sebagai berikut:

```text
You attack with your sword. Your opponent now has 30 health left. You are now at: Wizard { health: 60 }
You attack with your bow. Your opponent now has 20 health left.  You are now at: Ranger { health: 80 }
```

Di dalam real game, akan lebih baik untuk menulis ulang ini untuk setiap typenya, karena `You are now at: Wizard { health: 60 }` terlihat agak aneh. Itu juga mengapa method di dalam trait biasanya ditulis dengan simple, karena kita tidak tahu type apa yang akan menggunakannya. Sebagai contoh, Anda tidak bisa menuliskan hal seperti `self.0 += 10`. Tapi contoh ini menujukkan bahwa kita bisa menggunkan trait lain di dalam trait yang kita buat. Dan di saat kita melakukan hal itu, kita mendapatkan beberapa methods yang bisa kita gunakan.



Satu cara lain untuk menggunakan trait adalah dengan cara yang biasa disebut sebagai `trait bounds`. Yang artinya "pembatasan oleh trait". Trait bounds sangatlah mudah karena trait sebenarnya tidak perlu dimasukkan method apapun, ataupun hal-hal lainnya. Mari kita tuliskan ulang code kita di atas dengan sesuatu yang serupa tapi berbeda. Untuk kali ini, trait kita tidak memiliki method apapun, tapi kita memiliki function lain yang memerlukan trait untuk menggunakannya.

```rust
use std::fmt::Debug;  // Kita tidak perlu menuliskan std::fmt::Debug setiap saat

struct Monster {
    health: i32,
}

#[derive(Debug)]
struct Wizard {
    health: i32,
}
#[derive(Debug)]
struct Ranger {
    health: i32,
}

trait Magic{} // Tidak ada method yang dituliskan didalam trait-trait ini. Mereka hanyalah trait bounds
trait FightClose {}
trait FightFromDistance {}

impl FightClose for Ranger{} // Setiap type mendapatkan FightClose,
impl FightClose for Wizard {}
impl FightFromDistance for Ranger{} // tapi hanya Ranger yang mendapatkan FightFromDistance
impl Magic for Wizard{}  // dan hanya Wizard yang mendapatkan Magic

fn attack_with_bow<T: FightFromDistance + Debug>(character: &T, opponent: &mut Monster, distance: u32) {
    if distance < 10 {
        opponent.health -= 10;
        println!(
            "You attack with your bow. Your opponent now has {} health left.  You are now at: {:?}",
            opponent.health, character
        );
    }
}

fn attack_with_sword<T: FightClose + Debug>(character: &T, opponent: &mut Monster) {
    opponent.health -= 10;
    println!(
        "You attack with your sword. Your opponent now has {} health left. You are now at: {:?}",
        opponent.health, character
    );
}

fn fireball<T: Magic + Debug>(character: &T, opponent: &mut Monster, distance: u32) {
    if distance < 15 {
        opponent.health -= 20;
        println!("You raise your hands and cast a fireball! Your opponent now has {} health left. You are now at: {:?}",
    opponent.health, character);
    }
}

fn main() {
    let radagast = Wizard { health: 60 };
    let aragorn = Ranger { health: 80 };

    let mut uruk_hai = Monster { health: 40 };

    attack_with_sword(&radagast, &mut uruk_hai);
    attack_with_bow(&aragorn, &mut uruk_hai, 8);
    fireball(&radagast, &mut uruk_hai, 8);
}
```

Hasil print dari program tersebut adalah seperti berikut:

```text
You attack with your sword. Your opponent now has 30 health left. You are now at: Wizard { health: 60 }
You attack with your bow. Your opponent now has 20 health left.  You are now at: Ranger { health: 80 }
You raise your hands and cast a fireball! Your opponent now has 0 health left. You are now at: Wizard { health: 60 }
```

Jadinya Anda bisa melihat ada banyak cara untuk melakukan hal yang sama di saat Anda menggunakan trait. Itu semua tergantung pada apa yang paling masuk akal untuk program yang sedang Anda tulis.

Sekarang mari kita lihat bagaimana mengimplementasikan beberapa trait utama yang akan Anda gunakan di Rust.

### The From trait

*From* adalah trait yang mudah untuk digunakan, dan Anda mengetahui ini karena Anda sudah sering melihatnya. Dengan *From* Anda tidak hanya bisa membuat `String` dari `&str`, bahkan Anda dapat membuat banyak type dari berbagai type lainnya. Sebagai contoh, Vec menggunakan *From* untuk hal-hal berikut ini:

```text
From<&'_ [T]>
From<&'_ mut [T]>
From<&'_ str>
From<&'a Vec<T>>
From<[T; N]>
From<BinaryHeap<T>>
From<Box<[T]>>
From<CString>
From<Cow<'a, [T]>>
From<String>
From<Vec<NonZeroU8>>
From<Vec<T>>
From<VecDeque<T>>
```

Banyak sekali `Vec::from()` yang belum kita coba. Mari kita buat beberapa dan lihat apa yang terjadi.

```rust
use std::fmt::Display; // Kita akan membuat generic function unktuk mencetaknya, sehingga kita memerlukan Display

fn print_vec<T: Display>(input: &Vec<T>) { // Ambil Vec<T> jika type T memiliki Display
    for item in input {
        print!("{} ", item);
    }
    println!();
}

fn main() {

    let array_vec = Vec::from([8, 9, 10]); // mencoba menggunakannya pada array
    print_vec(&array_vec);

    let str_vec = Vec::from("What kind of vec will I be?"); // array dari sebuah &str? Ini cukup menarik
    print_vec(&str_vec);

    let string_vec = Vec::from("What kind of vec will a String be?".to_string()); // juga dari String
    print_vec(&string_vec);
}
```

Hasilnya adalah sebagai berikut:

```text
8 9 10
87 104 97 116 32 107 105 110 100 32 111 102 32 118 101 99 32 119 105 108 108 32 73 32 98 101 63
87 104 97 116 32 107 105 110 100 32 111 102 32 118 101 99 32 119 105 108 108 32 97 32 83 116 114 105 110 103 32 98 101 63
```

Jika Anda melihat typenya, vector yang kedua dan ketiga adalah `Vec<u8>`, yang mana artinya ia berisi byte dari `&str` dan `String`. Jadi Anda bisa melihat bahwa `From` sangatlah fleksibel dan sering digunakan. Mari kita coba dengan type yang kita buat sendiri.

Kita akan membuat dua struct dan kemudian mengimplementasikan `From` ke salah satu dari struct tersebut. Satu struct akan kita beri nama `City`, dan yang satu lagi akan kita beri nama `Country`. Kita ingin bisa melakukan hal seperti ini: `let country_name = Country::from(vector_of_cities)`.

Codenya seperti berikut:

```rust
#[derive(Debug)] // agar kita bisa melakukan debug print untuk City
struct City {
    name: String,
    population: u32,
}

impl City {
    fn new(name: &str, population: u32) -> Self { // hanya new function
        Self {
            name: name.to_string(),
            population,
        }
    }
}
#[derive(Debug)] // Country juga perlu untuk diprint
struct Country {
    cities: Vec<City>, // vektor yang berisi nama-nama kota dimasukkan ke sini
}

impl From<Vec<City>> for Country { // Catatan: kita tidak harus menulis From<City>, kita juga bisa menulis
                                   // From<Vec<City>>. Sehingga kita juga bisa mengimplementasikannya pada type
                                   // yang tidak kita buat
    fn from(cities: Vec<City>) -> Self {
        Self { cities }
    }
}

impl Country {
    fn print_cities(&self) { // function untuk melakukan print kota-kota yang ada di dalam Country
        for city in &self.cities {
            // & karena Vec<City> bukanlah Copy
            println!("{:?} has a population of {:?}.", city.name, city.population);
        }
    }
}

fn main() {
    let helsinki = City::new("Helsinki", 631_695);
    let turku = City::new("Turku", 186_756);

    let finland_cities = vec![helsinki, turku]; // Ini adalah Vec<City>
    let finland = Country::from(finland_cities); // Sekarang kita bisa menggunakan From

    finland.print_cities();
}
```

Hasilnya adalah:

```text
"Helsinki" has a population of 631695.
"Turku" has a population of 186756.
```

Anda bisa melihat bahwa `From` sangatlah mudah untuk diimplementasikan dari type-type yang tidak kita buat seperti `Vec`, `i32`, dan seterusnya. Ini ada satu contoh lagi dimana kita membuat sebuah vector yang di dalamnya memiliki 2 vector. Vector yang pertama berisi angka-angka genap, dan vector yang kedua berisi angka-angka ganjil. Dengan `From` Anda bisa memberikannya vector bertype `i32` dan ia akan mengembalikannya dalam bentuk `Vec<Vec<i32>>`: vector yang berisi vector bertype `i32`.

```rust
use std::convert::From;

struct EvenOddVec(Vec<Vec<i32>>);

impl From<Vec<i32>> for EvenOddVec {
    fn from(input: Vec<i32>) -> Self {
        let mut even_odd_vec: Vec<Vec<i32>> = vec![vec![], vec![]]; // Vec dengan dua vec kosong didalamnya
                                                                    // Ini adalah value kembalian, tapi pertama-tama kita harus mengisinya
        for item in input {
            if item % 2 == 0 {
                even_odd_vec[0].push(item);
            } else {
                even_odd_vec[1].push(item);
            }
        }
        Self(even_odd_vec) // Selesai, sehingga kita me-returnnya sebagai Self (Self = EvenOddVec)
    }
}

fn main() {
    let bunch_of_numbers = vec![8, 7, -1, 3, 222, 9787, -47, 77, 0, 55, 7, 8];
    let new_vec = EvenOddVec::from(bunch_of_numbers);

    println!("Even numbers: {:?}\nOdd numbers: {:?}", new_vec.0[0], new_vec.0[1]);
}
```

Hasilnya adalah:

```text
Even numbers: [8, 222, 0, 8]
Odd numbers: [7, -1, 3, 9787, -47, 77, 55, 7]
```

Type seperti `EvenOddVec` mungkin akan lebih baik apabila ditulis sebagai generic `T`, sehingga kita bia menggunakan banyak type angka. Anda bisa mencoba untuk membuat contoh dengan menggunakan generic jika Anda ingin mempelajarinya.

### Taking a String and a &str in a function

Terkadang Anda menginginkan sebuah function yang bisa mengambil value dari `String` dan juga `&str`. Anda bisa melakukan ini menggunakan generic dan menggunakan trait `AsRef`. `AsRef` digunakan untuk memberikan reference dari satu type ke type yang lainnya. Jika Anda lihat pada dokumentasi untuk `String`, Anda bisa melihat bahwa ia memiliki `AsRef` untuk berbagai macam type:

[https://doc.rust-lang.org/std/string/struct.String.html](https://doc.rust-lang.org/std/string/struct.String.html)

Ini adalah beberapa function signaturenya.

`AsRef<str>`:

```rust
// 🚧
impl AsRef<str> for String

fn as_ref(&self) -> &str
```

`AsRef<[u8]>`:

```rust
// 🚧
impl AsRef<[u8]> for String

fn as_ref(&self) -> &[u8]
```

`AsRef<OsStr>`:

```rust
// 🚧
impl AsRef<OsStr> for String

fn as_ref(&self) -> &OsStr
```

Anda bisa melihat bahwa ia akan mengambil `&self` sebagai parameter dan memberikan return berupa reference ke type yang lain. Ini artinya bahwa jika kita memiliki generic type T, kita bisa mengatakan bahwa ia memerlukan `AsRef<str>`. Jika Anda melakukan itu, maka ia bisa mengambil `&str` dan `String`.

Kita mulai dengan generic function. Code dibawah ini tidak akan bekerja:

```rust
fn print_it<T>(input: T) {
    println!("{}", input) // ⚠️
}

fn main() {
    print_it("Please print me");
}
```

Rust mengatakan `error[E0277]: T doesn't implement std::fmt::Display`. Jadi kita memerlukan T untuk diimplementasikan dengan Display.

```rust
use std::fmt::Display;

fn print_it<T: Display>(input: T) {
    println!("{}", input)
}

fn main() {
    print_it("Please print me");
}
```

Sekarang codenya bekerja dan mencetak `Please print me`. Itu bagus, tapi tetap saja T itu bertype apapun. Bisa saja ia `i8`, `f32` dan type apapun yang memiliki `Display`. Sehingga kita menambahkan `AsRef<str>`, dan sekarang T memerlukan 2 trait, yaitu `AsRef<str>` dan `Display`.

```rust
use std::fmt::Display;

fn print_it<T: AsRef<str> + Display>(input: T) {
    println!("{}", input)
}

fn main() {
    print_it("Please print me");
    print_it("Also, please print me".to_string());
    // print_it(7); <- Ini tidak akan tercetak
}
```

Sekarang ia tidak bisa mencetak type `i8`.
Jangan lupa bahwa Anda bisa menggunakan `where` untuk menulis function dengan cara yang berbeda di saat ia mulai panjang. Jika kita menambahkan Debug, maka ia menjadi `fn print_it<T: AsRef<str> + Display + Debug>(input: T)` yang mana ini terlalu panjan untuk ditulis dalam 1 baris. Jadi kita bisa menuliskannya seperti ini:

```rust
use std::fmt::{Debug, Display}; // tambahkan Debug

fn print_it<T>(input: T) // Sekarang baris ini menjadi mudah untuk dibaca
where
    T: AsRef<str> + Debug + Display, // dan trait-trait ini pun menjadi mudah juga untuk dibaca
{
    println!("{}", input)
}

fn main() {
    print_it("Please print me");
    print_it("Also, please print me".to_string());
}
```

## Chaining methods

Rust adalah systems programming language seperti C dan C++, dan codenya dapat ditulis sebagai perintah terpisah di baris yang terpisah, tapi ia juga memiliki functional style. Kedua style ini oke-oke saja, tapi functional style biasanya dituliskan jauh lebih pendek. Ini adalah contoh dari non-functional style (yang biasa disebut sebagai "imperative style") untuk membuat `Vec` dari 1 sampai 10:

```rust
fn main() {
    let mut new_vec = Vec::new();
    let mut counter = 1;

    while counter < 11 {
        new_vec.push(counter);
        counter += 1;
    }

    println!("{:?}", new_vec);
}
```

Ia mencetak `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`.

Dan ini contoh untuk mencetak hal serupa menggunakan functional style:

```rust
fn main() {
    let new_vec = (1..=10).collect::<Vec<i32>>();
    // Atau Anda bisa menuliskannya seperti ini:
    // let new_vec: Vec<i32> = (1..=10).collect();
    println!("{:?}", new_vec);
}
```

`.collect()` bisa membuat collections dari berbagai type, sehingga kita perlu untuk menyebutkan apa typenya.

Dengan functional style, Anda bisa melakukan chain methods. "Chaining methods" artinya menggunakan banyak method sekaligus didalam sebuah statement. Ini adalah contoh dari banyak method yang digunakan secara bersamaan/berantai:

```rust
fn main() {
    let my_vec = vec![0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

    let new_vec = my_vec.into_iter().skip(3).take(4).collect::<Vec<i32>>();

    println!("{:?}", new_vec);
}
```

Ini akan membuat sebuah Vec yang berisi `[3, 4, 5, 6]`. Pada code tersebut, terlalu banyak hal yang dituliskan dalam satu baris, sehingga untuk membuatnya lebih rapi kita bisa membuat memisahkan setiap methodnya per baris. Mari kita lakukan ini agar codenya menjadi lebih mudah dibaca:

```rust
fn main() {
    let my_vec = vec![0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

    let new_vec = my_vec
        .into_iter() // lakukan "iterate" pada setiap element (iterate/iterasi = melakukan sesuatu pada setiap element di dalamnya). into_iter() memberikan  owned value, bukan reference
        .skip(3) // lewati 3 item: 0, 1, dan 2
        .take(4) // ambil 4 item selanjutnya: 3, 4, 5, dan 6
        .collect::<Vec<i32>>(); // letakkan hasilnya di Vec<i32>

    println!("{:?}", new_vec);
}
```

Anda bisa menggunakan functional style secara maksimal apabila Anda mengerti closure dan juga iterator, yang mana akankita pelajari selanjutnya.

## Iterators

Iterator adalah konstruksi yang dapat memberi Anda item yang berada dalam collection, satu demi satu. Sebenarnya, kita telah menggunakan iterator berkali-kali: `for` loop memberikan Anda iterator. Saat Anda ingin menggunakan iterator di lain waktu, Anda harus memilih apa jenis iteratornya:

- `.iter()` untuk iterator yang didapatkan dari references
- `.iter_mut()` untuk iterator yang didapatkan dari mutable references
- `.into_iter()` untuk iterator yang langsung didapatkan dari valuenya (bukan references)

`for` loop sebenarnya hanyalah iterator yang akan memiliki (owns) valuenya. Itulah kenapa `for` loop bisa membuatnya mutable dan kemudian Anda bisa mengubah valuenya di saat Anda menggunakannya.

Anda bisa menggunakan iterator seperti ini:

```rust
fn main() {
    let vector1 = vec![1, 2, 3]; // kita akan menggunakan .iter() dan .into_iter() pada vector1
    let vector1_a = vector1.iter().map(|x| x + 1).collect::<Vec<i32>>();
    let vector1_b = vector1.into_iter().map(|x| x * 10).collect::<Vec<i32>>();

    let mut vector2 = vec![10, 20, 30]; // kita akan menggunakan .iter_mut() pada vector2
    vector2.iter_mut().for_each(|x| *x +=100);

    println!("{:?}", vector1_a);
    println!("{:?}", vector2);
    println!("{:?}", vector1_b);
}
```

Hasilnya adalah:

```text
[2, 3, 4]
[110, 120, 130]
[10, 20, 30]
```

Pada dua contoh dari vector 1, kita menggunakan method bernama `.map()`. Method ini akan melakukan sesuatu ke setiap element, dan kemudian di pass ke method selanjutnya. Pada vector2 kita menggunakan `.for_each()`. Method ini juga akan melakukan sesuatu ke setiap element, namun dengan cara yang berbeda. `.iter_mut()` plus `for_each()`, sebenarnya sama dengan `for` loop. Di dalam setiap method kita bisa memberikan sebuah nama kepada setiap element (kita menyebutnya dengan `x`) dan menggunakannya untuk mengubah isinya. Hal ini dikenal dengan nama closure dan kita akan mempelajarinya pada bagian selanjutnya.

Mari kita bahas lagi tentang itereator, satu per satu.

Pertama-tama, kita menggunakan `.iter()` pada `vector1` untuk mendapatkan reference. Kita menambahkan 1 pada setiap elementnya, dan membuatnya menjadi Vec yang baru. `vector1` tetap hidup, karena kita hanya menggunakan referencenya: kita sama sekali tidak mengambil valuenya. Sekarang kita memiliki `vector1`, dan sebuah Vec baru bernama `vector1_a`. Karena `.map()` hanya sekedar melakukan pass, maka kita perlu untuk menggunakan `.collect()` untuk membuatnya menjadi `Vec`.

Kemudian kita menggunakan `into_iter` untuk mendapatkan iterator berdasarkan value dari `vector1`. Ini membuat `vector1` hancur/hangus, karena memang begitulah cara `into_iter()` bekerja. Jadinya, setelah kita membuat `vector1_b`, kita tidak bisa lagi menggunakan `vector1`.

Akhirnya, kita menggunkan `.iter_mut()` pada `vector2`. Ia mutable, sehingga kita tidak perlu untuk menggunakan `.collect()` untuk membuat Vec baru. Alih-alih membuat Vec baru, kita bisa mengubah value di Vec yang sama dengan menggunakan mutable references. Jadi, `vector2` tetap hidup. Karena kita tidak perlu Vec yang baru, kita cukup menggunakan `for_each`: ia mirip seperti `for` loop.


### How an iterator works

Sebuah iterator bekerja dengan menggunakan method bernama `.next()`, yang mana ia akan mengembalikan `Option`. Di saat Anda menggunakan an iterator, Rust selalu menggunakan `next()` berulang-ulang. Jika ia mendapatkan `Some`, ia akan berlanjut. Jika ia mendapatkan `None`, ia akan berhenti.

Apa Anda masih mengingat tentang macro `assert_eq!`? Jika Anda sering membuka dokumentasi, Anda akan selalu melihatnya. Code dibawah ini menunjukkan bagaimana iterator bekerja.

```rust
fn main() {
    let my_vec = vec!['a', 'b', '거', '柳']; // Hanya Vec biasa

    let mut my_vec_iter = my_vec.iter(); // Sekarang typenya menjadi Iterator, tapi kita belum bisa melakukan call (memanggilnya) sekarang

    assert_eq!(my_vec_iter.next(), Some(&'a'));  // Panggil (call) element pertama menggunakan .next()
    assert_eq!(my_vec_iter.next(), Some(&'b'));  // panggil element selanjutnya
    assert_eq!(my_vec_iter.next(), Some(&'거')); // Lagi
    assert_eq!(my_vec_iter.next(), Some(&'柳')); // Lagi
    assert_eq!(my_vec_iter.next(), None);        // Tidak ada yang tersissa: kembaliannya adalah None
    assert_eq!(my_vec_iter.next(), None);        // Anda tetap bisa menggunakan .next(), namun hasilnya tetaplah None
}
```

Mengimplementasikan `Iterator` untuk struct atau enum yang kita buat tidaklah terlalu sulit. Pertama-tama, kita akan membuat tentang perpustakaan.

```rust
#[derive(Debug)] // kita ingin melakukan print dengan {:?}
struct Library {
    library_type: LibraryType, // ini adalah enum yang kita buat
    books: Vec<String>, // daftar buku
}

#[derive(Debug)]
enum LibraryType { // perpustakaan bisa jadi adalah perpustakaan kota atau perpustakaan negara
    City,
    Country,
}

impl Library {
    fn add_book(&mut self, book: &str) { // kita menggunakan add_book untuk menambahkan buku
        self.books.push(book.to_string()); // kita mengambil &str dan mengubahnya menjadi String, dan menambahkannya ke dalam Vec
    }

    fn new() -> Self { // membuat Library yang baru
        Self {
            library_type: LibraryType::City, // pada umumnya, perpustakaan yang baru adalah selalu perpustakaan kota, sehingga kita pilih City
            books: Vec::new(),
        }
    }
}

fn main() {
    let mut my_library = Library::new(); // buat perpustakaan baru
    my_library.add_book("The Doom of the Darksword"); // tambahkan beberapa buku
    my_library.add_book("Demian - die Geschichte einer Jugend");
    my_library.add_book("구운몽");
    my_library.add_book("吾輩は猫である");

    println!("{:?}", my_library.books); // kita bisa print daftar dari buku-buku yang ada di perpustakaan tersebut
}
```

Code di atas berjalan dengan baik. Sekarang kita ingin mengimplementasikan `Iterator` pada perpustakaan tersebut, jadinya kita akan menggunakan `for` loop. Sekarang, jika kita menggunakan `for` loop, ia tidak berjalan:

```rust
for item in my_library {
    println!("{}", item); // ⚠️
}
```

Dan compiler akan mengatakan:

```text
error[E0277]: `Library` is not an iterator
  --> src\main.rs:47:16
   |
47 |    for item in my_library {
   |                ^^^^^^^^^^ `Library` is not an iterator
   |
   = help: the trait `std::iter::Iterator` is not implemented for `Library`
   = note: required by `std::iter::IntoIterator::into_iter`
```

Tapi kita bisa membuat library tersebut menjadi sebuah iterator dengan `impl Iterator for Library`. Informasi tentang trait `Iterator` bisa dilihat pada dokumentasi standard library: [https://doc.rust-lang.org/std/iter/trait.Iterator.html](https://doc.rust-lang.org/std/iter/trait.Iterator.html)

Pada bagian kiri-atas di laman tersebut, ada tulisan: `Associated Types: Item` dan `Required Methods: next`. "Associated type" berarti "type yang berjalan bersama". Associated type (type yang akan berjalan bersama iterator kita) adalah `String`, karena kita ingin iterator memberikan kita String sebagai kembaliannya.

Pada laman tersebut ada contoh code yang terlihat seperti berikut:

```rust
// iterator yang hasilnya berada di antara Some dan None
struct Alternate {
    state: i32,
}

impl Iterator for Alternate {
    type Item = i32;

    fn next(&mut self) -> Option<i32> {
        let val = self.state;
        self.state = self.state + 1;

        // jika ia genap, kembalikan Some(i32). else None
        if val % 2 == 0 {
            Some(val)
        } else {
            None
        }
    }
}

fn main() {}
```

Anda bisa melihat bahwa di bawah `impl Iterator for Alternate` ada `type Item = i32`. Itulah associated type. Iterator kita adalah daftar buku, yang mana bertype `Vec<String>`. Di saat kita memanggil next, ia akan memberikan kita `String`. Sehingga kita akan menuliskan `type Item = String;`. Itulah associated item.

Untuk mengimplementasikan `Iterator`, Anda perlu menuliskan function `fn next()`. Ini adalah dimana Anda menentukan apa yang harus dilakukan oleh iterator. Untuk `Library` yang kita buat, kita ingin ia menampilkan buku yang terakhir ditampilkan di awal. Jadinya, kita akan lakukan `match` dengan `.pop()` yang mana akan mengambil element terakhir jika ia adalah `Some`. Kita juga ingin mencetak " is found!" untuk setiap item/element. Sekarang codenya terlihat seperti berikut:

```rust
#[derive(Debug, Clone)]
struct Library {
    library_type: LibraryType,
    books: Vec<String>,
}

#[derive(Debug, Clone)]
enum LibraryType {
    City,
    Country,
}

impl Library {
    fn add_book(&mut self, book: &str) {
        self.books.push(book.to_string());
    }

    fn new() -> Self {
        Self {
            library_type: LibraryType::City,
            books: Vec::new(),
        }
    }
}

impl Iterator for Library {
    type Item = String;

    fn next(&mut self) -> Option<String> {
        match self.books.pop() {
            Some(book) => Some(book + " is found!"), // Rust memperbolehkan String + &str
            None => None,
        }
    }
}

fn main() {
    let mut my_library = Library::new();
    my_library.add_book("The Doom of the Darksword");
    my_library.add_book("Demian - die Geschichte einer Jugend");
    my_library.add_book("구운몽");
    my_library.add_book("吾輩は猫である");

    for item in my_library.clone() { // sekarang kita bisa menggunakan for loop. Kita gunakan clone agar Library tidak hangus/hancur
        println!("{}", item);
    }
}
```

Hasilnya adalah:

```text
吾輩は猫である is found!
구운몽 is found!
Demian - die Geschichte einer Jugend is found!
The Doom of the Darksword is found!
```

## Closures

Closures seperti bentuk pendek dari function yang tidak diberikan nama. Terkadang mereka juga disebut sebagai lambda. Closures sangat mudah ditemukan karena mereka menggunakan `||` daripada menggunakan `()`. Closure sangat umum digunakan di Rust, dan sekali Anda belajar untuk menggunakannya, Anda akan merasa ketergantungan untuk terus menggunakannya. :D

Anda bisa mengikat (bind) closure ke sebuah variable, dan kemudian saat Anda menggunakannya, ia terlihat persis seperti fungsi pada umumnya:

```rust
fn main() {
    let my_closure = || println!("This is a closure");
    my_closure();
}
```

Jadi, closure yang di atas tidak mengambil apapun: `||` dan mencetak pesan: `This is a closure`.

Di antara `||` kita bisa menambahkan variabel input dan typenya, seperti yang kita tuliskan di antara `()` saat menuliskan sebuah function:

```rust
fn main() {
    let my_closure = |x: i32| println!("{}", x);

    my_closure(5);
    my_closure(5+5);
}
```

Hasil cetaknya adalah:

```text
5
10
```

Di saat closure menjadi lebih rumit, Anda bisa menambahkan code block. Maka ia bisa dituliskan sepanjang yang Anda inginkan.

```rust
fn main() {
    let my_closure = || {
        let number = 7;
        let other_number = 10;
        println!("The two numbers are {} and {}.", number, other_number);
          // Closure ini bisa dibuat sepanjang yang Anda inginkan, sama seperti function.
    };

    my_closure();
}
```

Tapi closure sangat spesial karena mereka bisa mengambil variabel yang berada di luar closure bahkan jika Anda hanya menuliskan `||`. Sehingga Anda bisa melakukan hal berikut ini:

```rust
fn main() {
    let number_one = 6;
    let number_two = 10;

    let my_closure = || println!("{}", number_one + number_two);
    my_closure();
}
```

Program di atas mencetak `16`. Anda tidak perlu untuk menaruh apapun di antara `||` karena ia hanya mengambil `number_one` dan `number_two` dan menjumlahkannya.

Dari situlah nama **closure** berasal, karena ia mengambil variabel dan "enclose" (menyertakan) variabel tersebut di dalamny. Dan jika Anda menginginkan penjelahan yang lebih benar:

- `||` yang tidak menyertakan variable dari luar adalah "anonymous function". Anonymous artinya "tidak memiliki nama". Ia bekerja mirip seperti function pada umumnya. Inilah yang biasanya disebut sebagai Lambda.
- `||` yang menyertakan variabel dari luar adalah "closure". Ia "encloses"/"menyertakan" variabel di sekitarnya untuk digunakan.

Tapi banyak orang biasa menyebut fungsi yang ditulis dengan `||` sebagai closure, jadi Anda tidak perlu khawatir apapun namanya. Kita akan menyebutnya sebagai "closure" untuk semua yang ditulis menggunakan `||`, tapi harus diingat bahwa itu juga bisa berarti adalah "anonymous function"/lambda.

Mengapa ada baiknya untuk mengetahui keduanya? Karena sebuah anonymous function sebenarnya membuat machine code yang sama sebagaimana function yang memiliki nama. Anonymous function terdengar seperti bahasa yang sangat tinggi, sehingga terkadang banyak orang berpikir bahwa machine codenya pastilah sangat rumit. Tetapi machine code yang dibuat Rust sama cepatnya seperti fungsi biasa.


Mari kita lihat beberapa hal lagi yang bisa dilakukan oleh closure. Anda juga bisa melakukan ini:

```rust
fn main() {
    let number_one = 6;
    let number_two = 10;

    let my_closure = |x: i32| println!("{}", number_one + number_two + x);
    my_closure(5);
}
```

Closure pada contoh di atas mengambil `number_one` dan `number_two`. Kita juga memberikannya variabel `x` dan mengatakan bahwa `x` adaalh 5. Kemudian menjumlahkan semua variabel tersebut untuk mencetak `21`.

Biasanya, Anda melihat closure di Rust di dalam method, karena closure memanglah sangat nyaman untuk digunakan. Kita melihat closure (di chapter sebelumnya) dengan `.map()` dan `.for_each()`. Di bagian dimana kita menuliskan `|x|` untuk memasukkan element berikutnya ke dalam iterator, dan itu adalah closure.

Ini adalah contoh lainnya: method `unwrap_or` yang telah kita ketahui sebelumnya, bisa Anda gunakan untuk meberikan value jika `unwrap` tidak berfungsi. Sebelumya, kita menuliskan: `let fourth = my_vec.get(3).unwrap_or(&0);`. Tapi ada juga method `unwrap_or_else` yang memiliki closure di dalamnya. Sehingga Anda bisa menuliskannya seperti berikut:

```rust
fn main() {
    let my_vec = vec![8, 9, 10];

    let fourth = my_vec.get(3).unwrap_or_else(|| { // mencoba untuk melakukan unwrap. Jika ia tidak berhasil,
        if my_vec.get(0).is_some() {               // periksa apakah my_vec memiliki sesuatu pada index [0]
            &my_vec[0]                             // Berikan angka yang berada pada index ke-0 jika elementnya memang ada
        } else {
            &0 // jika tidak ada, berikan &0
        }
    });

    println!("{}", fourth);
}
```

Tentu saja, closure bisa ditulis dengan sangat simple. Contohnya, Anda bisa menulis `let fourth = my_vec.get(3).unwrap_or_else(|| &0);`. Anda tidak selalu harus menggunakan `{}` dan menuliskan code yang rumit hanya karena ia adalah sebuah closure. Asalkan Anda menuliskan `||`, compiler akan tahu bahwa Anda menggunakan closure.

Method closure yang paling sering digunakan, mungkin adalah `.map()`. Mari kita lihat lagi. Inilah salah satu cara untuk menggunakannya:

```rust
fn main() {
    let num_vec = vec![2, 4, 6];

    let double_vec = num_vec        // ambil num_vec
        .iter()                     // lakukan iterasi pada vec tersebut
        .map(|number| number * 2)   // untuk setiap each item, kalikan dengan 2
        .collect::<Vec<i32>>();     // kemudian, buat sebuah Vec baru dari vec yang sudah di pass melalui chaining method
    println!("{:?}", double_vec);
}
```

Contoh bagus lainnya adalah dengan `.for_each()` setelah `.enumerate()`. Method `.enumerate()` memberikan iterator dengan nomor index dan item/element. Sebagai contoh: `[10, 9, 8]` menjadi `(0, 10), (1, 9), (2, 8)`. Type untuk setiap elemenet ini adalah `(usize, i32)`. Sehingga Anda bisa melakukan hal ini:

```rust
fn main() {
    let num_vec = vec![10, 9, 8];

    num_vec
        .iter()      // lakukan iterasi pada num_vec
        .enumerate() // ambil (index, number)
        .for_each(|(index, number)| println!("Index number {} has number {}", index, number)); // lakukan sesuatu untuk setiap hasil enumerate
}
```

Hasilnya adalah:

```text
Index number 0 has number 10
Index number 1 has number 9
Index number 2 has number 8
```

Pada contoh yang ini, kita menggunakan `for_each`, bukan `map`. `map` digunakan untuk **melakukan sesuatu ke setiap item** dan kemudian lakukan pass pada hasilnya. Sedangkan `for_each` adalah **langsung melakukan sesuatu saat mendapatkan setiap item**. Juga, `map` tidak melakukan apapun kecuali jika Anda menggunakan method seperti `collect`.

Sebenarnya, ada yang menarik dari iterator. Jika Anda mencoba untuk menggunakan `map` tanpa method seperti `collect`, compiler akan memberitahukan Anda bahwa ia tidak melakukan apapun. Ia tidak panic, namun compiler akan sekedar memberitahumu bahwa ia sama sekali tidak melakukan apapun.

```rust
fn main() {
    let num_vec = vec![10, 9, 8];

    num_vec
        .iter()
        .enumerate()
        .map(|(index, number)| println!("Index number {} has number {}", index, number));

}
```

Compiler mengatakan:

```text
warning: unused `std::iter::Map` that must be used
 --> src\main.rs:4:5
  |
4 | /     num_vec
5 | |         .iter()
6 | |         .enumerate()
7 | |         .map(|(index, number)| println!("Index number {} has number {}", index, number));
  | |_________________________________________________________________________________________^
  |
  = note: `#[warn(unused_must_use)]` on by default
  = note: iterators are lazy and do nothing unless consumed
```

Ini merupakan **warning**, jadi ia bukanlah error: yang artinya, program tetap berjalan dengan baik meskipun ada teguran. Tapi mengapa num_vec tidak melakukan apapun? Kita bisa melihat typenya untuk mengetahui mengapa hal itu terjadi.

- `let num_vec = vec![10, 9, 8];` Sekarang typenya adalah `Vec<i32>`.
- `.iter()` membuat typenya menjadi `Iter<i32>`. Sehingga sekarang typenya adalah iterator dengan element bertype `i32`.
- `.enumerate()` membuat typenya menjadi `Enumerate<Iter<i32>>`. Dan typenya menjadi `Enumerate` yang berasal dari `Iter` dengan element `i32`.
- `.map()` menjadikan typenya menjadi `Map<Enumerate<Iter<i32>>>`. Dan akhirnya menjadi type `Map` dari `Enumerate` yang berasal dari `Iter` dengan element`i32`.

Apa yang kita lakukan membuat struktur dari typenya menjadi kompleks dan semakin kompleks. Sehingga `Map<Enumerate<Iter<i32>>>` ini adalah struktur yang siap digunakan, tetapi hanya jika kita memberi tahu apa yang harus dilakukan. Rust melakukan ini karena ia perlu menjalankan sesuatu dengan cepat. Rust tidak ingin melakukan hal seperti ini:

- iterasi semua `i32` yang berada di dalam Vec
- kemudian enumerate `i32` yang berada dalam iterator
- kemudiap map semua `i32` yang telah di-enumerate

Rust hanya ingin melakukannya dalam 1 langkah, bukan 2, 3 ataupun berkali-kali seperti itu. Sehingga ia hanya membuat strukturnya saja dan menunggu struktur tersebut digunakan. Kemudian jika kita menuliskan `.collect::<Vec<i32>>()` ia tahu apa yang harus dilakukan, dan mulai mengerjakannya. Inilah apa yang dimaksud dengan `iterators are lazy and do nothing unless consumed`. Iterator tidak melakukan apapun sampai Anda "mengkonsumsinya" (menggunakannya).


Bahkan Anda bisa membuat sesuatu yang lumayan rumit seperti `HashMap` menggunakan `.collect()`, sehingga ia sangatlah powerful. Ini adalah contoh bagaimana menjadikan 2 buah vec menjadi `HashMap`. Pertama kita buat dua vector, dan kemudian akan kita gunakan `.into_iter()` pada vector tersebut untuk mendapatkan value dari iterator. Kemudian kita gunakan method `.zip()`. Method ini mengambil dua iterator dan menyatukannya, seperti zipper. Dan terakhir, kita gunakan `.collect()` untuk membuat `HashMap`.

Berikut ini adalah codenya:

```rust
use std::collections::HashMap;

fn main() {
    let some_numbers = vec![0, 1, 2, 3, 4, 5]; // Vec<i32>
    let some_words = vec!["zero", "one", "two", "three", "four", "five"]; // Vec<&str>

    let number_word_hashmap = some_numbers
        .into_iter()                 // sekarang ia adalah iter
        .zip(some_words.into_iter()) // di dalam .zip() kita letakkan iter yang lain. Dan sekarang ia tergabung menjadi satu.
        .collect::<HashMap<_, _>>();

    println!("For key {} we get {}.", 2, number_word_hashmap.get(&2).unwrap());
}
```

Hasilnya adalah:

```text
For key 2 we get two.
```

Anda bisa melihat bahwa kita menuliskan `<HashMap<_, _>>` karena itu adalah informasi yang cukup untuk Rust menentukan apap typenya (yaitu `HashMap<i32, &str>`). Anda bisa menuliskan `.collect::<HashMap<i32, &str>>();` jika Anda menginginkannya, atau Anda dapat menuliskannya seperti ini jika Anda mau:

```rust
use std::collections::HashMap;

fn main() {
    let some_numbers = vec![0, 1, 2, 3, 4, 5]; // Vec<i32>
    let some_words = vec!["zero", "one", "two", "three", "four", "five"]; // Vec<&str>
    let number_word_hashmap: HashMap<_, _> = some_numbers  // Karena kita memberitahukan typenya disini...
        .into_iter()
        .zip(some_words.into_iter())
        .collect(); // maka kita tidak perlu menuliskannya disini
}
```

Ada method lain seperti `.enumerate()` yang berguna untuk `char`, yaitu `char_indices()`. (Indices artinya "banyak index"). Anda menggunakannya dengan cara yang sama. Anggaplah kita memiliki string besar yang terbuat dari 3 digit angka.

```rust
fn main() {
    let numbers_together = "140399923481800622623218009598281";

    for (index, number) in numbers_together.char_indices() {
        match (index % 3, number) {
            (0..=1, number) => print!("{}", number), // print angkanya jika masih ada sisanya
            _ => print!("{}\t", number), // sebaliknya, print angkanya menggunakan tab space
        }
    }
}
```

Hasilnya adalah `140     399     923     481     800     622     623     218     009     598    281`.


### |_| in a closure

Terkadang Anda akan menemukan `|_|` pada sebuah closure. Ini artinya bahwa closure tersebut memerlukan argument/parameter (seperti `x`), tetapi Anda tidak ingin menggunakannya. Jadinya, `|_|` berarti "Okay, closure ini mengambil argument, tapi saya tidak memberikannya nama karena saya tidak peduli tentang hal itu".

Ini adalah contoh dimana akan mucul error saat Anda tidak melakukan hal tersebut:

```rust
fn main() {
    let my_vec = vec![8, 9, 10];

    println!("{:?}", my_vec.iter().for_each(|| println!("We didn't use the variables at all"))); // ⚠️
}
```

Rust akan memberikan pesan ini:

```text
error[E0593]: closure is expected to take 1 argument, but it takes 0 arguments
  --> src\main.rs:28:36
   |
28 |     println!("{:?}", my_vec.iter().for_each(|| println!("We didn't use the variables at all")));
   |                                    ^^^^^^^^ -- takes 0 arguments
   |                                    |
   |                                    expected closure that takes 1 argument
```

Compiler sebenarnya memberikan Anda bantuan/saran berupa pesan seperti berikut:

```text
help: consider changing the closure to take and ignore the expected argument
   |
28 |     println!("{:?}", my_vec.iter().for_each(|_| println!("We didn't use the variables at all")));
```

Ini merupakan saran yang baik. Jika Anda mengganti `||` dengan `|_|` maka programnya akan berjalan.

### Helpful methods for closures and iterators

Rust akan menjadi bahasa yang menyenangkan untuk dipelajari setelah Anda merasa nyaman dengan closures. Dengan closure Anda bisa melakukan method berantai (chain method) satu sama lain dan melakukan banyak hal dengan code yang sangat sedikit. Berikut merupakan beberapa closure dan metode yang digunakan dengan closure yang belum kita lihat.

`.filter()`: Ini memungkinkan Anda menyimpan item dalam iterator yang ingin Anda simpan. Mari kita filter bulan dalam setahun.

```rust
fn main() {
    let months = vec!["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];

    let filtered_months = months
        .into_iter()                         // membuat sebuah iter
        .filter(|month| month.len() < 5)     // Kita menginginkan nama bulan yang panjangnya kurang dari 5 bytes.
                                             // Kita tahu bahwa setiap huruf itu adalah 1 byte, sehingga kita bisa menggunakan .len()
        .filter(|month| month.contains("u")) // Juga kita hanya mencari nama bulan yang di dalamnya terdapat huruf u
        .collect::<Vec<&str>>();

    println!("{:?}", filtered_months);
}
```

Hasilnya adalah `["June", "July"]`.



`.filter_map()`. Ia disebut `filter_map()` karena ia melakukan `.filter()` dan `.map()`. Closurenya haruslah mengembalikan `Option<T>`, dan kemudian `filter_map()` mengambil value untuk setiap `Option` jika ia adalah `Some`. Jadi, jika misalnya Anda melakukan `.filter_map()` pada `vec![Some(2), None, Some(3)]`, kembaliannya adalah `[2, 3]`.

Kita akan membuat contoh dengan struct `Company`. Setiap company memiliki field `name` yang bertype `String`, tapi CEO dari company tersebut mungkin saja baru saja keluar. Sehingga field `ceo` typenya adalah `Option<String>`. Kita akan menggunakan `.filter_map()` pada beberapa company untuk menyimpan nama CEOnya.

```rust
struct Company {
    name: String,
    ceo: Option<String>,
}

impl Company {
    fn new(name: &str, ceo: &str) -> Self {
        let ceo = match ceo {
            "" => None,
            name => Some(name.to_string()),
        }; // ceo ditentukan dengan match, dan kemudian kita return Self
        Self {
            name: name.to_string(),
            ceo,
        }
    }

    fn get_ceo(&self) -> Option<String> {
        self.ceo.clone() // return clone dari CEO (struct bukanlah Copy)
    }
}

fn main() {
    let company_vec = vec![
        Company::new("Umbrella Corporation", "Unknown"),
        Company::new("Ovintiv", "Doug Suttles"),
        Company::new("The Red-Headed League", ""),
        Company::new("Stark Enterprises", ""),
    ];

    let all_the_ceos = company_vec
        .into_iter()
        .filter_map(|company| company.get_ceo()) // filter_map memerlukan Option<T>
        .collect::<Vec<String>>();

    println!("{:?}", all_the_ceos);
}
```

Hasilnya adalah `["Unknown", "Doug Suttles"]`.

Kita tahu bahwa `.filter_map()` memerlukan `Option`, bagaimana kalau `Result`? Tidak apa-apa: ada method bernama `.ok()` yang akan mengubah `Result` menjadi `Option`. Ia dinamakan `.ok()` karena semua yang ia kirimkan adalah result `Ok` (informasi `Err` dihilangkan). Kita ingat bahwa `Option` adalah `Option<T>`, sedangkan `Result` adalah `Result<T, E>` dengan informasi mengenai `Ok` dan juga `Err`. Jadi di saat Anda menggunkaan `.ok()`, semua `Err` akan menghilang dan menjadi `None`.

Menggunakan `.parse()` adalah contoh mudah untuk hal ini, dimana kita mencoba untuk melakukan parse input dari user. `.parse()` ini akan mengambil `&str` dan mencoba mengubahnya menjadi `f32`. Ia akan me-return `Result`, namun kita menggunakan `filter_map()`, jadi kita hanya membuang errornya saja. Semua yang `Err` akan dijadikan `None` dan selanjutnya akan difilter oleh `.filter_map()`.

```rust
fn main() {
    let user_input = vec!["8.9", "Nine point nine five", "8.0", "7.6", "eleventy-twelve"];

    let actual_numbers = user_input
        .into_iter()
        .filter_map(|input| input.parse::<f32>().ok())
        .collect::<Vec<f32>>();

    println!("{:?}", actual_numbers);
}
```

Hasilnya adalah `[8.9, 8.0, 7.6]`.

Kebalikan dari `.ok()` adalah `.ok_or()` dan `ok_or_else()`. Ini akan mengubah `Option` menjadi `Result`. Ia disebut `.ok_or()` karena `Result` memberikan `Ok` **or** sebuah `Err`, sehingga perlu bagi Anda untuk memberikan apa value `Err`-nya nantinya. Ini dikarenakan `None` pada `Option` tidak memiliki informasi apapun. Juga, Anda bisa melihat bahwa bagian *else* pada nama method yang lainnya berarti bahwa ia memiliki closure.

Kita bisa mengambil `Option` dari struct `Company` dan mengubahnya menjadi `Result` dengan cara ini. Untuk error handling jangka panjang, ada baiknya apabila Anda membuat type error Anda sendiri. Namun untuk sekarang ini, kita cukup memberikannya pesan error, sehingga ia menjadi `Result<String, &str>`.

```rust
// Semua yang ditulis sebelum main() masih sama seperti program sebelumnya
struct Company {
    name: String,
    ceo: Option<String>,
}

impl Company {
    fn new(name: &str, ceo: &str) -> Self {
        let ceo = match ceo {
            "" => None,
            name => Some(name.to_string()),
        };
        Self {
            name: name.to_string(),
            ceo,
        }
    }

    fn get_ceo(&self) -> Option<String> {
        self.ceo.clone()
    }
}

fn main() {
    let company_vec = vec![
        Company::new("Umbrella Corporation", "Unknown"),
        Company::new("Ovintiv", "Doug Suttles"),
        Company::new("The Red-Headed League", ""),
        Company::new("Stark Enterprises", ""),
    ];

    let mut results_vec = vec![]; // Anggap saja kita perlu mengumpulkan hasil errornya juga

    company_vec
        .iter()
        .for_each(|company| results_vec.push(company.get_ceo().ok_or("No CEO found")));

    for item in results_vec {
        println!("{:?}", item);
    }
}
```

Baris yang ini mengalami banyak perubahan:

```rust
// 🚧
.for_each(|company| results_vec.push(company.get_ceo().ok_or("No CEO found")));
```

Ini artinya: "untuk setiap company, gunakan `get_ceo()`. Jika Anda mendapatkannya, maka pass valuenya ke dalam `Ok`. dan jika Anda tidak mendapatkannya, pass  "No CEO found" ke dalam `Err`. Kemudian push `Result` tersebut ke dalam vec."

Sehingga, saat kita mencetak `results_vec`, kita mendapatkan ini:

```text
Ok("Unknown")
Ok("Doug Suttles")
Err("No CEO found")
Err("No CEO found")
```

Sehingga kita sekarang memiliki 4 entry. Sekarang, mari kita coba `.ok_or_else()` agar kita bisa menggunakan closure dan mendapatkan pesan error yang lebih baik. Disini kita bisa menggunkan `format!` untuk membuat sebuah `String`, dan menaruh nama company di dalamnya. Kemudian kita return `String`-nya.

```rust
// Semua yang ditulis sebelum main() masih sama seperti program sebelumnya
struct Company {
    name: String,
    ceo: Option<String>,
}

impl Company {
    fn new(name: &str, ceo: &str) -> Self {
        let ceo = match ceo {
            "" => None,
            name => Some(name.to_string()),
        };
        Self {
            name: name.to_string(),
            ceo,
        }
    }

    fn get_ceo(&self) -> Option<String> {
        self.ceo.clone()
    }
}

fn main() {
    let company_vec = vec![
        Company::new("Umbrella Corporation", "Unknown"),
        Company::new("Ovintiv", "Doug Suttles"),
        Company::new("The Red-Headed League", ""),
        Company::new("Stark Enterprises", ""),
    ];

    let mut results_vec = vec![];

    company_vec.iter().for_each(|company| {
        results_vec.push(company.get_ceo().ok_or_else(|| {
            let err_message = format!("No CEO found for {}", company.name);
            err_message
        }))
    });

    for item in results_vec {
        println!("{:?}", item);
    }
}
```

Hasil program tersebut adalah:

```text
Ok("Unknown")
Ok("Doug Suttles")
Err("No CEO found for The Red-Headed League")
Err("No CEO found for Stark Enterprises")
```


`.and_then()` adalah method yang sangat membantu yang mana ia akan mengambil `Option`, kemudian membuat Anda bisa melakukan sesuatu terhadap valuenya dan pass valuenya. Jadi, inputnya adalah `Option`, dan outputnya pula adalah `Option`. Ini sama seprti "unwrap, kemudian lakukan sesuatu, kemudian wrap lagi" dengan cara yang lebih aman.

Contoh mudahnya adalah sebuah angka yang kita dapatkan dari sebuah vec menggunakan `.get()`, karena kembaliannya adalah `Option`. Sekarang kita bisa melakukan pass valuenya ke `and_then()`, dan melakukan perhitungan matematis padanya jika ia adalah `Some`. Jika ia adalah `None`, maka `None` yang akan di-pass.

```rust
fn main() {
    let new_vec = vec![8, 9, 0]; // vec yang berisi angka-angka

    let number_to_add = 5;       // gunakan ini untuk melakukan operasi matematis
    let mut empty_vec = vec![];  // resultnya akan dimasukkan ke sini


    for index in 0..5 {
        empty_vec.push(
            new_vec
               .get(index)
                .and_then(|number| Some(number + 1))
                .and_then(|number| Some(number + number_to_add))
        );
    }
    println!("{:?}", empty_vec);
}
```

Hasil cetaknya adalah `[Some(14), Some(15), Some(6), None, None]`. Anda bisa melihat bahwa `None` tidak difilter (dibuang keluar), ia ikut di-pass ke dalam vector.




`.and()` semacam `bool` pada `Option`. Anda bisa mencocokkan banyak `Option` ke `Option` yang lainnya, dan jika mereka semua adalah `Some` maka ia akan mengembalikan `Some` yang terakhir. Dan jika salah satunya adalah `None`, maka ia akan mengembalikan `None`.

Pertama-tama, ini adalah contoh `bool` untuk membantu Anda mendapatkan gambarannya. Anda bisa melihat bahwa jika Anda menggunakan `&&` (and), meskipun hanya ada satu `false` maka hasilnya akan `false`.

```rust
fn main() {
    let one = true;
    let two = false;
    let three = true;
    let four = true;

    println!("{}", one && three); // prints true
    println!("{}", one && two && three && four); // prints false
}
```

Hal ini juga berlaku pada `.and()`. Bayangkan kita melakukan 5 operasi `.and()` dan menaruh hasilnya ke dalam Vec<Option<&str>>.

```rust
fn main() {
    let first_try = vec![Some("success!"), None, Some("success!"), Some("success!"), None];
    let second_try = vec![None, Some("success!"), Some("success!"), Some("success!"), Some("success!")];
    let third_try = vec![Some("success!"), Some("success!"), Some("success!"), Some("success!"), None];

    for i in 0..first_try.len() {
        println!("{:?}", first_try[i].and(second_try[i]).and(third_try[i]));
    }
}
```

Program di atas akan menunjukkan index mana saja yang selalu mendapatkan `Some` dari 3 vec tersebut. Hasilnya adalah:

```text
None
None
Some("success!")
Some("success!")
None
```

Pada index ke-0 hasilnya adalah `None` karena ada `None` pada index ke-0 di vec `second_try`. Index ke-1 adalah `None` karena ada `None` pada vec `first_try`. Selanjutnya, hasilnya adalah `Some("success!")` karena tidak ada `None` pada vec `first_try`, `second try`, ataupun `third_try`.



`.any()` dan `.all()` sangat mudah digunakan dalam iterator. Ia mengembalikan `bool` tergantung dari inputan Anda. Pada contoh ini kita membuat vec yang sangat besar (sekitar 20,000 item/element) dengan menggunakan karakter dari `'a'` sampai `'働'`. Kemudian kita buat sebuah function untuk memeriksa apakah ada karakter di dalamnya.

selanjutnya kita buat sebuah vec yang lebih kecil and dan memeriksa apakah semuanya adalah alphabet (dengan menggunakan method `.is_alphabetic()`). Kemudian kita tanyakan apakah semua karakter kurang dari karakter Korea `'행'`.

Perhatikan juga bahwa Anda menggunakan reference, karena `.iter()` memberikan reference dan Anda menggunakan `&` untuk dibandingkan dengan `&` lainnya.

```rust
fn in_char_vec(char_vec: &Vec<char>, check: char) {
    println!("Is {} inside? {}", check, char_vec.iter().any(|&char| char == check)); // reference destructure 
}

fn main() {
    let char_vec = ('a'..'働').collect::<Vec<char>>();
    in_char_vec(&char_vec, 'i');
    in_char_vec(&char_vec, '뷁');
    in_char_vec(&char_vec, '鑿');

    let smaller_vec = ('A'..'z').collect::<Vec<char>>();
    println!("All alphabetic? {}", smaller_vec.iter().all(|&x| x.is_alphabetic())); // reference destructure 
    println!("All less than the character 행? {}", smaller_vec.iter().all(|&x| x < '행')); // reference destructure 
}
```

Hasilnya adalah:

```text
Is i inside? true
Is 뷁 inside? false
Is 鑿 inside? false
All alphabetic? false
All less than the character 행? true
```

Ah ya, `.any()` hanya memeriksa sampai menemukan satu item yang cocok, lalu berhenti. Ia tidak akan memeriksa semuanya jika sudah menemukan kecocokan. Jika Anda menggunakan `.any()` pada `Vec`, mungkin adalah ide yang bagus untuk push item yang mungkin cocok ke bagian depan. Atau Anda bisa menggunakan `.rev()` setelah `.iter()` untuk me-reverse (membalik) iteratornya. Contohnya seperti ini:

```rust
fn main() {
    let mut big_vec = vec![6; 1000];
    big_vec.push(5);
}
```

`Vec` di atas memilik 1000 buah `6` yang kemudian diisi dengan sebuah `5`. Anggap saja kita ingin menggunakan `.any()` untuk melihat apakah ia berisi 5. Pertama, kita pastikan dulu bahwa `.rev()` berjalan dengan benar. Diingat lagi, sebuah `Iterator` selalu memiliki `.next()` yang memungkinkan Anda memeriksa apa yang dilakukannya setiap saat.

```rust
fn main() {
    let mut big_vec = vec![6; 1000];
    big_vec.push(5);

    let mut iterator = big_vec.iter().rev();
    println!("{:?}", iterator.next());
    println!("{:?}", iterator.next());
}
```

Hasilnya adalah:

```text
Some(5)
Some(6)
```

Yup, program kita berjalan dengan benar. Ada satu `Some(5)` dan 1000 `Some(6)` setelahnya. Jadinya kita menulisnya seperti ini:

```rust
fn main() {
    let mut big_vec = vec![6; 1000];
    big_vec.push(5);

    println!("{:?}", big_vec.iter().rev().any(|&number| number == 5));
}
```

Dan karena ia menggunakan `.rev()`, ia hanya memanggil `.next()` sekali saja dan berhenti. Jika kita tidak menggunakan `.rev()` maka ia akan memanggil `.next()` 1001 kali sebelum programnya berhenti. Codenya seperti ini:

```rust
fn main() {
    let mut big_vec = vec![6; 1000];
    big_vec.push(5);

    let mut counter = 0; // Mulai menghitung
    let mut big_iter = big_vec.into_iter(); // ubah big_vec menjadi Iterator

    loop {
        counter +=1;
        if big_iter.next() == Some(5) { // tetap memanggil .next() sampai kita mendapatkan Some(5)
            break;
        }
    }
    println!("Final counter is: {}", counter);
}
```

Hasilnya adalah `Final counter is: 1001`, sehingga kita tahu bahwa ia akan memanggil `.next()` 1001 kali sebelum ia menemukan 5.




`.find()` memberitahu kita jika iterator memiliki sesuatu, dan `.position()` memberi tahu kita dimana lokasinya. `.find()` berbeda dari `.any()` karena ia mengembalikan `Option` dengan value di dalamnya (atau `None`). Sedangkan `.position()` juga adalah `Option` beserta angka yang merepresentasikan posisinya, atau `None`. Dengan kata lain:

- `.find()`: "Saya akan mencoba mencarikannya untuk Anda"
- `.position()`: "Saya akan mencoba menemukan dimana tempatnya untuk Anda"

Berikut adalah contohnya:

```rust
fn main() {
    let num_vec = vec![10, 20, 30, 40, 50, 60, 70, 80, 90, 100];

    println!("{:?}", num_vec.iter().find(|&number| number % 3 == 0)); // method find mengambil reference, sehingga kita berikan ia &number
    println!("{:?}", num_vec.iter().find(|&number| number * 2 == 30));

    println!("{:?}", num_vec.iter().position(|&number| number % 3 == 0));
    println!("{:?}", num_vec.iter().position(|&number| number * 2 == 30));

}
```

Ia akan mencetak:

```text
Some(30) // This is the number itself
None // No number inside times 2 == 30
Some(2) // This is the position
None
```



Dengan menggunakan `.cycle()` Anda bisa membuat iterator yang terus menerus melakukan loop. Iterator seperti ini bekerja dengan baik dengan method `.zip()` untuk membuat sesuatu yang baru, seperti pada contoh ini yang mana akan membuat `Vec<(i32, &str)>`:

```rust
fn main() {
    let even_odd = vec!["even", "odd"];

    let even_odd_vec = (0..6)
        .zip(even_odd.into_iter().cycle())
        .collect::<Vec<(i32, &str)>>();
    println!("{:?}", even_odd_vec);
}
```

Jadi meskipun method `.cycle()` semestinya tidak berhenti, iterator yang lain hanya menjalankannya 6 kali di saat melakukan zip antara vec `even_odd` dan iterator `0..6`. Itu berarti bahwa iterator yang dibuat oleh `.cycle()` tidak lagi memanggil `.next()`, sehingga ia selesai setelah dipanggil sebanyak 6 kali. Outputnya adalah seperti berikut:

```
[(0, "even"), (1, "odd"), (2, "even"), (3, "odd"), (4, "even"), (5, "odd")]
```

Hal serupa dapat dilakukan dengan pada range yang tidak memiliki akhir. Jika Anda menuliskan `0..` maka Anda membuat sebuah range yang tidak berhenti. Anda bisa menggunakannya dengan sangat mudah, seperti ini:

```rust
fn main() {
    let ten_chars = ('a'..).take(10).collect::<Vec<char>>();
    let skip_then_ten_chars = ('a'..).skip(1300).take(10).collect::<Vec<char>>();

    println!("{:?}", ten_chars);
    println!("{:?}", skip_then_ten_chars);
}
```

Keduanya akan mencetak 10 characters, namun pada cetakan kedua ia melakukan skip sebanyak 1300, dan mencetak 10 huruf dalam aksara Armenia.

```
['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
['յ', 'ն', 'շ', 'ո', 'չ', 'պ', 'ջ', 'ռ', 'ս', 'վ']
```


Method terkenal lainnya adalah `.fold()`. Method ini sering digunakan untuk menjumlahkan elemen-elemen yang berada di dalam iterator, tapi tidak hanya itu saja, Anda juga bisa melakukan hal lain. Method ini mirip dengan `.for_each()`. Pada `.fold()`, Pertama-tama Anda menambahkan value awalan (jika Anda ingin menjumlahkan setiap element, maka valuenya 0), kemudian tuliskan koma, dan selanjutnya tuliskan closure. Closure memberikan Anda 2 hal, yaitu total (yang dihitung sejauh iterator dijalankan), dan element selanjutnya. Dibawah ini adalah contoh menggunakan `.fold()` untuk menjumlahkan setiap element di dalam vec.

```rust
fn main() {
    let some_numbers = vec![9, 6, 9, 10, 11];

    println!("{}", some_numbers
        .iter()
        .fold(0, |total_so_far, next_number| total_so_far + next_number)
    );
}
```

Jadi, berikut penjelasannya:

- Pada langkah 1, ia dimulai dengan 0 dan menambahkannya dengan angka selanjutnya, yaitu 9.
- Kemudian diambillah 9 dan ditambahkan dengan element selanjutnya, yaitu 6: totalnya 15.
- Kemudian diambillah 15, dan ditambahkan dengan element selanjutnya, yaitu 9: totalnya 24.
- Kemudian diambillah 24, dan ditambahkan dengan element selanjutnya, yaitu 10: totalnya 34.
- Dan terakhir, diambillah 34, dan ditambahkan dengan 11: sehingga hasil akhirnya adalah 45. Jadinya ia akan mencetak `45`.


Tidak hanya untuk hal seperti itu, ini adalah contoh dimana kita bisa menambahakan '-' ke setiap karakter untuk membuat `String`.

```rust
fn main() {
    let a_string = "I don't have any dashes in me.";

    println!(
        "{}",
        a_string
            .chars() // sekarang ia sudah menjadi iterator
            .fold("-".to_string(), |mut string_so_far, next_char| { // mulai dengan String "-". Jadiak ia sebagai mutable setiap saat bersama dengan karakter berikutnya
                string_so_far.push(next_char); // Push terlebih dahulu charnya, kemudian '-'
                string_so_far.push('-');
                string_so_far} // Jangan lupa untuk pass hasilnya ke loop selanjutnya
            ));
}
```

Hasilnya adalah:

```text
-I- -d-o-n-'-t- -h-a-v-e- -a-n-y- -d-a-s-h-e-s- -i-n- -m-e-.-
```



Dan masih banyak method yang mudah untuk digunakan seperti:

- `.take_while()` yang mana akan mengambil value dari iterator selama kondisinya selalu `true` (contohnya `take while x > 5`)
- `.cloned()` yang mana akan membuat clone didalam iterator.Ini akan mengubah reference menjadi value.
- `.by_ref()` yang mana membuat sebuah iterator mengambil reference. Ini bagus untuk memastikan bahwa Anda bisa menggunakan sebuah `Vec` (atau sesuatu yang serupa) setelah Anda menggunakannya untuk membuat iterator.
- Method `_while` lainnya: `.skip_while()`, `.map_while()`, dan seterusnya
- `.sum()`: menjumlahkan apapun yang ada di dalamnya.



`.chunks()` dan `.windows()` adalah dua cara untuk memotong vector menjadi ukuran sesuai yang Anda inginkan. Anda tuliskan ukuran yang Anda inginkan di dalam bracket. Katakanlah, Anda memiliki vector yang berisi 10 item, dan Anda ingin ukurannya adalah 3. Ia akan bekerja seperti ini:

- `.chunks()` akan memberikanmu 4 potong: [0, 1, 2], kemudian [3, 4, 5], kemudian [6, 7, 8], dan terakhir [9]. Jadinya, ia akan mencoba untuk membuat sebuah potongan dari 3 item, tapi jika ia tidak mencapai 3 buah, ia tidak panic. Ia hanya akan memberi apa yang tersisa.

- `.windows()` pertama-tama akan memberimu potongan [0, 1, 2]. Kemudian ia akan berpindah maju selangkah dan memberi Anda potongan [1, 2, 3]. Ia akan melakukan itu sampai akhirnya ia mencapai potongan terakhir yang anggotanya 3 item, dan kemudian berhenti.

So let's use them on a simple vector of numbers. It looks like this:

```rust
fn main() {
    let num_vec = vec![1, 2, 3, 4, 5, 6, 7, 8, 9, 0];

    for chunk in num_vec.chunks(3) {
        println!("{:?}", chunk);
    }
    println!();
    for window in num_vec.windows(3) {
        println!("{:?}", window);
    }
}
```

Hasilnya adalah:

```text
[1, 2, 3]
[4, 5, 6]
[7, 8, 9]
[0]

[1, 2, 3]
[2, 3, 4]
[3, 4, 5]
[4, 5, 6]
[5, 6, 7]
[6, 7, 8]
[7, 8, 9]
[8, 9, 0]
```

Perlu diketahui, `.chunks()` akan panic jika Anda tidak memberikannya apapun. Anda bisa menulis `.chunks(1000)` untuk sebuah vector yang hanya memiliki satu item, tapi Anda tidak bisa menulis `.chunks()` dengan sesuatu yang panjangnya 0.



`.match_indices()` memungkinkan Anda menarik semua yang ada di dalam sebuah `String` atau `&str` yang cocok dengan input yang Anda berikan, dan ia akan memberikan Anda indexnya juga. Ini mirip seperti `.enumerate()` karena ia memberikan return berupa tuple yang berisi dua item.

```rust
fn main() {
    let rules = "Rule number 1: No fighting. Rule number 2: Go to bed at 8 pm. Rule number 3: Wake up at 6 am.";
    let rule_locations = rules.match_indices("Rule").collect::<Vec<(_, _)>>(); // Ini adalah Vec<usize, &str>, tapi kita biarkan Rust yang akan menentukannya
    println!("{:?}", rule_locations);
}
```

Hasilnya adalah:

```text
[(0, "Rule"), (28, "Rule"), (62, "Rule")]
```



`.peekable()` memungkinkan Anda membuat iterator di mana Anda dapat melihat (mengintip) item berikutnya. Ini seperti memanggil `.next()` (yang mana ia akan memberikan `Option`), hanya saja iteratornya tidak bergerak, sehingga Anda dapat menggunakannya sebanyak yang Anda inginkan. Anda sebenarnya dapat menganggap peekable ini sebagai "stoppable", karena Anda dapat berhenti selama yang Anda inginkan. Berikut adalah contoh dimana kita menggunakan `.peek()` tiga kali pada setiap item. Kita bisa menggunakan `.peek()` selamanya sampai kita menggunakan `.next()` untuk pindah ke item berikutnya.

```rust
fn main() {
    let just_numbers = vec![1, 5, 100];
    let mut number_iter = just_numbers.iter().peekable(); // Ini sebenarnya membuat type iterator yang biasa disebut sebagai Peekable

    for _ in 0..3 {
        println!("I love the number {}", number_iter.peek().unwrap());
        println!("I really love the number {}", number_iter.peek().unwrap());
        println!("{} is such a nice number", number_iter.peek().unwrap());
        number_iter.next();
    }
}
```

Hasilnya adalah:

```text
I love the number 1
I really love the number 1
1 is such a nice number
I love the number 5
I really love the number 5
5 is such a nice number
I love the number 100
I really love the number 100
100 is such a nice number
```

Ini adalah contoh lain dimana kita menggunakan `.peek()` untuk mencocokka sebuah item. Setelah kita selesai menggunakannya, kita panggil `.next()`.


```rust
fn main() {
    let locations = vec![
        ("Nevis", 25),
        ("Taber", 8428),
        ("Markerville", 45),
        ("Cardston", 3585),
    ];
    let mut location_iter = locations.iter().peekable();
    while location_iter.peek().is_some() {
        match location_iter.peek() {
            Some((name, number)) if *number < 100 => { // .peek() memberikan kita reference, sehingga kita memerlukan *
                println!("Found a hamlet: {} with {} people", name, number)
            }
            Some((name, number)) => println!("Found a town: {} with {} people", name, number),
            None => break,
        }
        location_iter.next();
    }
}
```

Outputnya:

```text
Found a hamlet: Nevis with 25 people
Found a town: Taber with 8428 people
Found a hamlet: Markerville with 45 people
Found a town: Cardston with 3585 people
```

Dan terakhir, ini adalah contoh dimana kita juga bisa menggunakan `.match_indices()`. Pada contoh ini, kita meletakkan nama ke dalam `struct` tergantung pada jumlah spasi di `&str`.

```rust
#[derive(Debug)]
struct Names {
    one_word: Vec<String>,
    two_words: Vec<String>,
    three_words: Vec<String>,
}

fn main() {
    let vec_of_names = vec![
        "Caesar",
        "Frodo Baggins",
        "Bilbo Baggins",
        "Jean-Luc Picard",
        "Data",
        "Rand Al'Thor",
        "Paul Atreides",
        "Barack Hussein Obama",
        "Bill Jefferson Clinton",
    ];

    let mut iter_of_names = vec_of_names.iter().peekable();

    let mut all_names = Names { // buat sebuah struct Names yang kosong
        one_word: vec![],
        two_words: vec![],
        three_words: vec![],
    };

    while iter_of_names.peek().is_some() {
        let next_item = iter_of_names.next().unwrap(); // kita bisa menggunakan .unwrap() karena kita tahu bahwa ia adalah Some
        match next_item.match_indices(' ').collect::<Vec<_>>().len() { // Buat sebuah vec menggunakan .match_indices dan periksa panjangnya
            0 => all_names.one_word.push(next_item.to_string()),
            1 => all_names.two_words.push(next_item.to_string()),
            _ => all_names.three_words.push(next_item.to_string()),
        }
    }

    println!("{:?}", all_names);
}
```

Ia akan mencetak:

```text
Names { one_word: ["Caesar", "Data"], two_words: ["Frodo Baggins", "Bilbo Baggins", "Jean-Luc Picard", "Rand Al\'Thor", "Paul Atreides"], three_words:
["Barack Hussein Obama", "Bill Jefferson Clinton"] }
```


## The dbg! macro and .inspect

`dbg!` adalah macro yang sangat berguna yang mencetak quick information. Ini adalah alternatif yang baik dari `println!` karena ia sangat singkat untuk ditulis dan memberikan lebih banyak informasi:

```rust
fn main() {
    let my_number = 8;
    dbg!(my_number);
}
```

Maka ia mencetak `[src\main.rs:4] my_number = 8`.

Tapi sebenarnya, Anda bisa meletakkan `dbg!` di tempat lainnya, dan bahkan membungkus code didalamnya. Lihat code ini sebagai contoh:

```rust
fn main() {
    let mut my_number = 9;
    my_number += 10;

    let new_vec = vec![8, 9, 10];

    let double_vec = new_vec.iter().map(|x| x * 2).collect::<Vec<i32>>();
}
```

Code ini membuat sebuah angka yang mutable dan mengubahnya. Kemudian membuat sebuah vec, dan menggunakan `iter` dan `map` dan `collect` untuk membuat vec yang baru. Kita bisa meletakkan `dbg!` hampir di segala macam tempat di code ini. `dbg!` menanyakan kepada compiler: "Apa yang Anda lakukan saat ini?" dan memberitahukannya kepada Anda.

```rust
fn main() {
    let mut my_number = dbg!(9);
    dbg!(my_number += 10);

    let new_vec = dbg!(vec![8, 9, 10]);

    let double_vec = dbg!(new_vec.iter().map(|x| x * 2).collect::<Vec<i32>>());

    dbg!(double_vec);
}
```

Ia akan mencetak:

```text
[src\main.rs:3] 9 = 9
```

dan:

```text
[src\main.rs:4] my_number += 10 = ()
```

dan:

```text
[src\main.rs:6] vec![8, 9, 10] = [
    8,
    9,
    10,
]
```

dan ini, yang bahkan menunjukkan value dari sebuah ekspresi:

```text
[src\main.rs:8] new_vec.iter().map(|x| x * 2).collect::<Vec<i32>>() = [
    16,
    18,
    20,
]
```

dan:

```text
[src\main.rs:10] double_vec = [
    16,
    18,
    20,
]
```

`.inspect` agak mirip dengan `dbg!`, namun Anda menggunakannya seperti `map` di dalam sebuah iterator. Ia memberikan Anda item dari iterator dan Anda bisa mencetaknya atau melakukan apapun yang Anda inginkan. Sebagai contoh, mari kita lihat `double_vec` lagi.

```rust
fn main() {
    let new_vec = vec![8, 9, 10];

    let double_vec = new_vec
        .iter()
        .map(|x| x * 2)
        .collect::<Vec<i32>>();
}
```

Kita ingin mengetahui lebih banyak informasi tentang apa yang dilakukan code tersebut. Jadi kita tambahkan `inspect()` di dua tempat:

```rust
fn main() {
    let new_vec = vec![8, 9, 10];

    let double_vec = new_vec
        .iter()
        .inspect(|first_item| println!("The item is: {}", first_item))
        .map(|x| x * 2)
        .inspect(|next_item| println!("Then it is: {}", next_item))
        .collect::<Vec<i32>>();
}
```

Outputnya adalah:

```text
The item is: 8
Then it is: 16
The item is: 9
Then it is: 18
The item is: 10
Then it is: 20
```

Dan karena `.inspect` mengambil sebuah closure, kita bisa menulisnya sebanyak yang kita inginkan:

```rust
fn main() {
    let new_vec = vec![8, 9, 10];

    let double_vec = new_vec
        .iter()
        .inspect(|first_item| {
            println!("The item is: {}", first_item);
            match **first_item % 2 { // first_item adalah &&i32, jadinya kita menggunakan **
                0 => println!("It is even."),
                _ => println!("It is odd."),
            }
            println!("In binary it is {:b}.", first_item);
        })
        .map(|x| x * 2)
        .collect::<Vec<i32>>();
}
```

Outputnya adalah:

```text
The item is: 8
It is even.
In binary it is 1000.
The item is: 9
It is odd.
In binary it is 1001.
The item is: 10
It is even.
In binary it is 1010.
```

## Types of &str

Ada lebih dari satu jenis `&str`. Kita punya:

- String literals: Anda membuat jenis ini di saat Anda menuliskan `let my_str = "I am a &str"`. Mereka akan hidup sampai akhir program, karena mereka ditulis langsung dalam bentuk binary. String literal memiliki type `&'static str`. `'` itu adalah lifetime, dan string literal memiliki lifetime yang disebut `static`.
- Borrowed str: Ini adalah `&str` reguler yang tidak menggunakan lifetime `static`. Jika Anda membuat sebuah `String` dan mendapatkan reference dari `String` tersebut, Rust akan mengkonversinya menjadi `&str` jika Anda memerlukannya. Contohnya:

```rust
fn prints_str(my_str: &str) { // ia bisa menggunakan &String seperti &str
    println!("{}", my_str);
}

fn main() {
    let my_string = String::from("I am a string");
    prints_str(&my_string); // kita memberikan function prints_str sebuah &String
}
```

Jadi, apa itu lifetime? Kita akan mempelajarinya sekarang.

## Lifetimes

Lifetime berarti "seberapa lama variabel akan hidup". Anda hanya perlu untuk memikirkan tentang lifetime jika kita berbicara soal reference. Ini karena reference tidak bisa hidup lebih lama daripada objek asalnya. Sebagai contoh, function ini tidak akan berjalan:

```rust
fn returns_reference() -> &str {
    let my_string = String::from("I am a string");
    &my_string // ⚠️
}

fn main() {}
```

Problem adalah bahwa `my_string` hanya hidup di dalam `returns_reference`. Kita coba untuk mengembalikan `&my_string`, tetapi `&my_string` tidak bisa exist tanpa `my_string`. Sehingga compiler akan mengatakan tidak.

Code ini juga tidak akan bekerja:

```rust
fn returns_str() -> &str {
    let my_string = String::from("I am a string");
    "I am a str" // ⚠️
}

fn main() {
    let my_str = returns_str();
    println!("{}", my_str);
}
```

Tapi ia hampir berjalan. Compiler mengatakan:

```text
error[E0106]: missing lifetime specifier
 --> src\main.rs:6:21
  |
6 | fn returns_str() -> &str {
  |                     ^ expected named lifetime parameter
  |
  = help: this function's return type contains a borrowed value, but there is no value for it to be borrowed from
help: consider using the `'static` lifetime
  |
6 | fn returns_str() -> &'static str {
  |                     ^^^^^^^^
```

`missing lifetime specifier` artinya adalah kita perlu untuk menambahkan `'` dengan lifetime. Kemudian ia mengatakan bahwa ia `contains a borrowed value, but there is no value for it to be borrowed from`. Itu artinya adalah `I am a str` tidak  dipinjam (borrowed) dari manapun. Ia mengatakan `consider using the 'static lifetime` dengan  cara menuliskan `&'static str`. Jadi menurut compiler, kita harus mencoba mengatakan bahwa ini adalah string literal.

Sekarang codenya bekerja:

```rust
fn returns_str() -> &'static str {
    let my_string = String::from("I am a string");
    "I am a str"
}

fn main() {
    let my_str = returns_str();
    println!("{}", my_str);
}
```

Itu dikarenakan kita mengembalikan sebuah `&str` menggunakan lifetime `static`. Sedangkan, `my_string` hanya bisa dikembalikan sebagai `String`: kita tidak bisa mengembalikan sebuah reference dari `String` tersebut karena ia akan hangus pada baris berikutnya.

Jadi, `fn returns_str() -> &'static str` meberitahukan kepada Rust: "Jangan khawatir, kita hanya akan mengembalikan sebuah string literal". String literals tetap hidup pada seluruh bagian program, sehingga Rust akan menerimanya. Anda akan menyadari bahwa lifetime sebenarnya mirip dengan generic. Saat kita memberitahukan compiler sesuatu seperti `<T: Display>`, kita membuat semacam janji kepada compiler bahwa kita hanya akan menggunakan inputan dengan trait `Display`. Lifetime juga sama: kita tidak mengubah lifetime dari variabel apapun. Kita hanya memberi tahu compiler bahwa akan menjadi seperti apa lifetime dari inputan tersebut.

Namun `'static` bukanlah satu-satunya lifetime. Sebenarnya, setiap variabel memiliki lifetime, tapi biasanya kita tidak perlu untuk menuliskannya. Compiler Rust sangat cerdas dan biasanya bisa mengetahuinya sendiri. Kita hanya perlu menuliskan lifetimenya saat compiler tidak mengetahuinya.

Ini adalah contoh lain dar lifetime. Bayangkan kita ingin membuat sebuah struct `City` dan memberikannya `&str` untuk field name. Kita mungkin ingin melakukan hal seperti itu karena ingin memberikan performa yang lebih cepat daripada menggunakan `String`. Sehingga kita menuliskannya seperti ini, meskipun code dibawah ini tentunya tidak berhasil:

```rust
#[derive(Debug)]
struct City {
    name: &str, // ⚠️
    date_founded: u32,
}

fn main() {
    let my_city = City {
        name: "Ichinomiya",
        date_founded: 1921,
    };
}
```

Compiler akan mengatakan:

```text
error[E0106]: missing lifetime specifier
 --> src\main.rs:3:11
  |
3 |     name: &str,
  |           ^ expected named lifetime parameter
  |
help: consider introducing a named lifetime parameter
  |
2 | struct City<'a> {
3 |     name: &'a str,
  |
```

Rust memerlukan lifetime untuk `&str` karena `&str` adalah sebuah reference. Apa yang terjadi apabila value yang merujuk kepada `name` menghilang/hangus/hancur? Tentu saja itu tidak aman (unsafe).

Bagaimana tentang `'static`, apakah ia menjadi bisa dijalankan? Kita telah menggunakannya sebelumnya, oleh karenanya mari kita coba di contoh yang ini:

```rust
#[derive(Debug)]
struct City {
    name: &'static str, // ubah &str ke &'static str
    date_founded: u32,
}

fn main() {
    let my_city = City {
        name: "Ichinomiya",
        date_founded: 1921,
    };

    println!("{} was founded in {}", my_city.name, my_city.date_founded);
}
```

Okay, programnya berjalan. Dan mungkin inilah yang Anda inginkan untuk struct. Namun, perhatikan bahwa kita hanya bisa mengambil "string literals", bukan reference ke value tertentu. Sehingga code dibawah ini tidak akan bekerja:

```rust
#[derive(Debug)]
struct City {
    name: &'static str, // hidup di seluruh bagian program
    date_founded: u32,
}

fn main() {
    let city_names = vec!["Ichinomiya".to_string(), "Kurume".to_string()]; // city_names tidak hidup di seluruh program

    let my_city = City {
        name: &city_names[0], // ⚠️ Ini adalah &str, bukan &'static str. Ini merupakan reference ke sebuah value di dalam city_names
        date_founded: 1921,
    };

    println!("{} was founded in {}", my_city.name, my_city.date_founded);
}
```

Compiler akan mengatakan:

```text
error[E0597]: `city_names` does not live long enough
  --> src\main.rs:12:16
   |
12 |         name: &city_names[0],
   |                ^^^^^^^^^^
   |                |
   |                borrowed value does not live long enough
   |                requires that `city_names` is borrowed for `'static`
...
18 | }
   | - `city_names` dropped here while still borrowed
```

Hal ini sangatlah penting untuk dipahami, karena reference yang kita berikan itu sebenarnya memiliki masa hidup yang cukup lama. Tapi, kita berjanji kepada compiler bahwa kita hanya akan memberikan `&'static str`, dan itulah letak masalahnya.

Jadinya, sekarang kita ingin mencoba apa yang compiler sarankan sebelumnya. Ia menyarankan untuk menulis `struct City<'a>` dan `name: &'a str`. Ini berarti bahwa compiler hanya akan mengambil reference untuk `name` jika ia hidup sama panjangnya dengan `City`.

```rust
#[derive(Debug)]
struct City<'a> { // City memiliki lifetime 'a
    name: &'a str, // dan name juga memiliki lifetime 'a.
    date_founded: u32,
}

fn main() {
    let city_names = vec!["Ichinomiya".to_string(), "Kurume".to_string()];

    let my_city = City {
        name: &city_names[0],
        date_founded: 1921,
    };

    println!("{} was founded in {}", my_city.name, my_city.date_founded);
}
```

Juga harus diingat bahwa kita bisa menuliskan apapun selain `'a` jika Anda mau. Ini sama seperti generic dimana kita menulis `T` dan `U`, namun sebenarnya bisa digantikan dengan apapun.

```rust
#[derive(Debug)]
struct City<'city> { // lifetimenya sekarang bernama 'city
    name: &'city str, // dan name sekarang memiliki lifetime 'city
    date_founded: u32,
}

fn main() {}
```

Jadi biasanya Anda akan menuliskan `'a, 'b, 'c`, dst. karena itu lebih cepat dan merupakan cara yang paling umum digunakan untuk menuliskannya. Tapi Anda selalu bisa menggantinya jika Anda ingin. Salah satu tips yang baik adalah mengubah lifetime menjadi nama yang "human-readable", yang mana bisa membantu Anda membaca code jika code tersebut sangant rumit.

Mari kita lihat lagi trait untuk generic. Contohnya:

```rust
use std::fmt::Display;

fn prints<T: Display>(input: T) {
    println!("T is {}", input);
}

fn main() {}
```

Di saat Anda menuliskan `T: Display`, itu berarti "tolong ambil T jika ia memiliki Display".
Bukan berarti: "Saya berikan trait Display ke T".

Hal yang sama pula berlaku pada lifetimes. Di saat Anda menulis 'a pada program dibawah ini:

```rust
#[derive(Debug)]
struct City<'a> {
    name: &'a str,
    date_founded: u32,
}

fn main() {}
```

Itu berarti "tolong hanya ambil inputan dari `name` jika ia hidup setidaknya sepanjang `City`".
Bukan berarti: "Saya akan membuat inputan dari `name` sama panjangnya dengan `City`".

Sekarang kita bisa mempelajari tentang `<'_>` yang kita lihat sebelumnya. Ini disebut dengan "anonymous lifetime" dan ini adalah indikator bahwa referencenya sedang digunakan. Sebagai contoh, Rust akan menyarankannya kepada Anda di saat Anda mengimplementasikan struct. Pada contoh di bawah ini, ada satu struct yang hampir bisa berjalan (dengan kata lain, belum bisa dijalankan):

```rust
    // ⚠️
struct Adventurer<'a> {
    name: &'a str,
    hit_points: u32,
}

impl Adventurer {
    fn take_damage(&mut self) {
        self.hit_points -= 20;
        println!("{} has {} hit points left!", self.name, self.hit_points);
    }
}

fn main() {}
```

Jadinya kita melakukan apa yang kita perlu lakukan untuk `struct`: Pertama-tama, kita mengatakan bahwa `name` datang dari `&str`. Itu berarti kita perlu lifetime, jadi kita perlu memberikannya `<'a>`. Kemudian kita melakukan hal yang sama pada `struct` untuk menunjukkan bahwa mereka memiliki lifetime yang sama panjangnya. Tapi kemudian Rust memberi tahu kita untuk melakukan hal ini:

```text
error[E0726]: implicit elided lifetime not allowed here
 --> src\main.rs:6:6
  |
6 | impl Adventurer {
  |      ^^^^^^^^^^- help: indicate the anonymous lifetime: `<'_>`
```

Ia ingin kita menambahkan anonymous lifetime untuk menunjukkan bahwa disitu ada reference yang sedang digunakan. Sehingga jika kita menuliskannya, compilernya berjalan dengan mulus:

```rust
struct Adventurer<'a> {
    name: &'a str,
    hit_points: u32,
}

impl Adventurer<'_> {
    fn take_damage(&mut self) {
        self.hit_points -= 20;
        println!("{} has {} hit points left!", self.name, self.hit_points);
    }
}

fn main() {}
```

Anonymous lifetime dibuat agar Anda tidak selalu menuliskan hal-hal seperti `impl<'a> Adventurer<'a>`, karena structnya sendiri telah menunjukkan lifetimenya.

Lifetime terkadang bisa menjadi sulit juga rumit di Rust, tapi berikut ini adalah beberapa tips untuk menghindari kebingungan di saat berurusan dengan lifetime:

- Anda tetap bisa menggunakan owned types, menggunakan clone dll. jika Anda ingin menghindarinya untuk saat ini. (melakukan refactor kemudian)
- Seringkali, di saat compiler menginginkan lifetime, Anda akan menuliskan <'a> "dimana-mana" dan kemudian codenya berjalan. Jangan bingung jika code Anda dipenuhi dengan `<'a>`. Itu hanya cara untuk mengatakan kepada compiler bahwa "Jangan khawatir, Compiler, Saya tidak akan memberikan apapun yang masa hidupnya tidak cukup lama".
- Anda bisa mengeksplorasi mengenai lifetime sedikit demi sedikit. Tulis code menggunakan owned values, kemudian ubah ia menjadi reference. Compiler akan mulai menegur Anda, tapi juga memberikan beberapa saran. Dan jika dirasa terlalu rumit, maka cukup batalkan perubahan tersebut dan coba lagi di lain waktu.

Mari lakukan ini pada code kita dan lihat apa yang compiler katakan. Pertama-tama, kita akan kembali ke awal dan membuang semua lifetimenya. Dan juga mengimplementasikan `Display`. `Display` hanya akan mencetak nama dari `Adventurer`.

```rust
// ⚠️
struct Adventurer {
    name: &str,
    hit_points: u32,
}

impl Adventurer {
    fn take_damage(&mut self) {
        self.hit_points -= 20;
        println!("{} has {} hit points left!", self.name, self.hit_points);
    }
}

impl std::fmt::Display for Adventurer {
        fn fmt(&self, f: &mut std::fmt::Formatter<'_>) -> std::fmt::Result {
            write!(f, "{} has {} hit points.", self.name, self.hit_points)
        }
}

fn main() {}
```

Teguran pertama yang kita terima adalah seperti berikut:

```text
error[E0106]: missing lifetime specifier
 --> src\main.rs:2:11
  |
2 |     name: &str,
  |           ^ expected named lifetime parameter
  |
help: consider introducing a named lifetime parameter
  |
1 | struct Adventurer<'a> {
2 |     name: &'a str,
  |
```

Compiler menyarankan untuk melakukan: menulis `<'a>` setelah Adventurer, dan `&'a str`. Jadi kita akan melakukan saran tersebut:

```rust
// ⚠️
struct Adventurer<'a> {
    name: &'a str,
    hit_points: u32,
}

impl Adventurer {
    fn take_damage(&mut self) {
        self.hit_points -= 20;
        println!("{} has {} hit points left!", self.name, self.hit_points);
    }
}

impl std::fmt::Display for Adventurer {
        fn fmt(&self, f: &mut std::fmt::Formatter<'_>) -> std::fmt::Result {
            write!(f, "{} has {} hit points.", self.name, self.hit_points)
        }
}

fn main() {}
```

Sekarang, bagian yang sebelumnya dikomplain oleh compiler sudah berjalan dengan baik, tapi kemudian compiler akan menanyakan kita perihal block `impl`. Compiler ingin kita menyebutkan bahwa impl tersebut sedang menggunakan reference:

```text
error[E0726]: implicit elided lifetime not allowed here
 --> src\main.rs:6:6
  |
6 | impl Adventurer {
  |      ^^^^^^^^^^- help: indicate the anonymous lifetime: `<'_>`

error[E0726]: implicit elided lifetime not allowed here
  --> src\main.rs:12:28
   |
12 | impl std::fmt::Display for Adventurer {
   |                            ^^^^^^^^^^- help: indicate the anonymous lifetime: `<'_>`
```

Okay, akan kita tuliskan apa yang disarankan tersebut... dan sekarang codenya bekerja! Sekarang kita bisa membuat `Adventurer` dan melakukan sesuatu terhadapnya.

```rust
struct Adventurer<'a> {
    name: &'a str,
    hit_points: u32,
}

impl Adventurer<'_> {
    fn take_damage(&mut self) {
        self.hit_points -= 20;
        println!("{} has {} hit points left!", self.name, self.hit_points);
    }
}

impl std::fmt::Display for Adventurer<'_> {

        fn fmt(&self, f: &mut std::fmt::Formatter<'_>) -> std::fmt::Result {
            write!(f, "{} has {} hit points.", self.name, self.hit_points)
        }
}

fn main() {
    let mut billy = Adventurer {
        name: "Billy",
        hit_points: 100_000,
    };
    println!("{}", billy);
    billy.take_damage();
}
```

Hasilnya adalah:

```text
Billy has 100000 hit points.
Billy has 99980 hit points left!
```

Jadi, Anda bisa melihat bahwa lifetimes yang dituliskan itu adalah hal dimana compiler seringkali hanya ingin memastikan seberapa lama suatu variabel hidup. Dan compiler biasanya cukup cerdas untuk menebak hampir semua lifetime yang Anda inginkan, dan hanya perlu Anda memberitahukannya sehingga lifetimenya bisa dipastikan.

## Interior mutability

### Cell

**Interior mutability** berarti kita memiliki mutability di dalam sebuah bagian kecil dari struktur tertentu. Ingat bagaimana di Rust Anda perlu menggunakan `mut` untuk mengubah variabel? Ada juga beberapa cara untuk mengubah sesuatu tanpa keyword `mut`. Ini dikarenakan Rust memiliki beberapa cara untuk memungkinkan Anda mengubah value dengan aman di dalam struct yang tidak dapat diubah. Masing-masing mengikuti beberapa aturan yang memastikan bahwa perubahan value tersebut masih aman untuk dilakukan.

Pertama, mari kita lihat contoh sederhana di mana kita ingin melakukan ini. Bayangkan sebuah `struct` bernama `PhoneModel` yang memiliki beberapa field:

```rust
struct PhoneModel {
    company_name: String,
    model_name: String,
    screen_size: f32,
    memory: usize,
    date_issued: u32,
    on_sale: bool,
}

fn main() {
    let super_phone_3000 = PhoneModel {
        company_name: "YY Electronics".to_string(),
        model_name: "Super Phone 3000".to_string(),
        screen_size: 7.5,
        memory: 4_000_000,
        date_issued: 2020,
        on_sale: true,
    };

}
```

Tentu saja akan lebih baik apabila `PhoneModel` bersifat immutable, karena kita tidak ingin datanya berubah. Contohnya, `date_issued` dan `screen_size` tidak pernah berubah.

Tapi di dalam struct tersebut ada satu field bernama `on_sale`. Mula-mula, telefon dengan model tersebut statusnya adalah dijual (`true`), namun kemudian, perusahaan tersebut memutuskan untuk tidak lagi menjualnya. Bisakah kita membuat hanya satu field menjadi mutable? Karena kita tidak ingin menuliskan `let mut super_phone_3000`. Jika kita menuliskan hal tersebut, maka setiap field akan menjadi mutable.

Rust memiliki banyak cara untuk melakukan safe mutability di dalam sesuatu yang sifatnya immutable. Cara yang paling mudah untuk dilakukan adalah menggunakan `Cell`. Pertama-tama, kita menuliskan `use std::cell::Cell`, sehingga kita cukup menuliskan `Cell` daripada menuliskan `std::cell::Cell` berkali-kali.

Kemudian kita mengubah `on_sale: bool` ke `on_sale: Cell<bool>`. Sekarang, ia bukan lagi bool: melainkan sebuah `Cell` yang menyimpan type `bool`.

`Cell` memiliki method yang bernama `.set()` dimana Anda bisa mengganti valuenya. Kita menggunakan `.set()` untuk mengubah `on_sale: true` menjadi `on_sale: Cell::new(true)`.

```rust
use std::cell::Cell;

struct PhoneModel {
    company_name: String,
    model_name: String,
    screen_size: f32,
    memory: usize,
    date_issued: u32,
    on_sale: Cell<bool>,
}

fn main() {
    let super_phone_3000 = PhoneModel {
        company_name: "YY Electronics".to_string(),
        model_name: "Super Phone 3000".to_string(),
        screen_size: 7.5,
        memory: 4_000_000,
        date_issued: 2020,
        on_sale: Cell::new(true),
    };

    // 10 tahun kemudian, super_phone_3000 tidak lagi diproduksi/dijual
    super_phone_3000.on_sale.set(false);
}
```

`Cell` bekerja pada semua jenis type, namun ia bekerja dengan baik pada Copy types yang sederhana, karena Copy type yang sederhana memberikan value, bukan references. `Cell` juga memiliki method bernama `get()` yang hanya bisa digunakan pada Copy type.

Type lainnya yang bisa Anda gunakan adalah `RefCell`.

### RefCell

`RefCell` adalah cara lain untuk mengubah value tanpa perlu mendeklarasikan `mut`. `RefCell` adalah singkatan dari "reference cell", dan ia mirip seperti `Cell` namun menggunakan reference, alih-alih menggunakan copynya.

Kita akan membuat sebuah struct bernama `User`. Sejauh ini, Anda bisa melihat bahwa ia mirip seperti `Cell`:

```rust
use std::cell::RefCell;

#[derive(Debug)]
struct User {
    id: u32,
    year_registered: u32,
    username: String,
    active: RefCell<bool>,
    // field-field yang lainnya
}

fn main() {
    let user_1 = User {
        id: 1,
        year_registered: 2020,
        username: "User 1".to_string(),
        active: RefCell::new(true),
    };

    println!("{:?}", user_1.active);
}
```

Hasil cetaknya adalah `RefCell { value: true }`.

Ada banyak method yang bisa digunakan untuk `RefCell`. Dua di antaranya adalah `.borrow()` dan `.borrow_mut()`. Dengan menggunkan method ini, Anda bisa melakukan hal yang sama seperti yang Anda lakukan terhadap `&` dan `&mut`. Aturannya pun tetap sama:

- Many borrows (&), aman.
- Satu mutable borrow (&mut), juga aman.
- Namun, mutable dan immutable secara bersama-sama tentu saja tidak diperbolehkan.

Jadinya, mengubah value yang berada di dalam `RefCell` itu sangatlah mudah:

```rust
// 🚧
user_1.active.replace(false);
println!("{:?}", user_1.active);
```

Dan masih ada method lain untuk mengubahnya, seperti `replace_with` yang menggunakan closure:

```rust
// 🚧
let date = 2020;

user_1
    .active
    .replace_with(|_| if date < 2000 { true } else { false });
println!("{:?}", user_1.active);
```

Namun Anda haruslah berhati-hati di saat menggunakan `RefCell`, karena ia akan memeriksa peminjaman di saat runtime, bukan pada saat compilation time. Runtime berarti di saat program sedang berjalan (setelah kompilasi). Sehingga, ia akan tetap melakukan kompilasi, meskipun terdapat kesalahan dalam menggunakan `RefCell`:

```rust
use std::cell::RefCell;

#[derive(Debug)]
struct User {
    id: u32,
    year_registered: u32,
    username: String,
    active: RefCell<bool>,
    // Field-field lainnya
}

fn main() {
    let user_1 = User {
        id: 1,
        year_registered: 2020,
        username: "User 1".to_string(),
        active: RefCell::new(true),
    };

    let borrow_one = user_1.active.borrow_mut(); // mutable borrow yang pertama - okay
    let borrow_two = user_1.active.borrow_mut(); // mutable borrow yang kedua - not okay
}
```

Tapi di saat Anda menjalankannya, program akan langsung panic.

```text
thread 'main' panicked at 'already borrowed: BorrowMutError', C:\Users\mithr\.rustup\toolchains\stable-x86_64-pc-windows-msvc\lib/rustlib/src/rust\src\libcore\cell.rs:877:9
note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace
error: process didn't exit successfully: `target\debug\rust_book.exe` (exit code: 101)
```

`already borrowed: BorrowMutError` adalah bagian penting yang harus diperhatikan. Jadi, saat Anda menggunakan `RefCell`, baiknya lakukan compile **dan** jalankan programnya untuk memeriksa apakah ada kesalahan.

### Mutex

`Mutex` adalah cara lain untuk mengubah value tanpa mendeklarasikan `mut`. Mutex adalah singkatan dari `mutual exclusion`, yang berarti "hanya satu di satu waktu". Ini sebabnya pula mengapa `Mutex` itu aman, karena Mutex hanya memperbolehkan satu proses perubahan di satu waktu saja. Untuk melakukan ini, ia menggunakan `.lock()`. `Lock` ini seperti mengunci pintu dari dalam. Anda masuk ke sebuah kamar, kunci pintunya dari dalam, dan sekarang Anda bisa mengubah apapun yang berada di dalam kamar tersebut. Tidak ada orang lain yang bisa masuk ke kamar tersebut dan menghentikan Anda untuk mengubah kondisi kamar tersebut, karena Anda telah mengunci pintunya.

`Mutex` lebih mudah dipahami lewat contoh dibawah ini.

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5); // Membuat sebuah Mutex<i32>. Kita tidak perlu mendeklarasikannya sebagai mut
    let mut mutex_changer = my_mutex.lock().unwrap(); // mutex_changer adalah MutexGuard
                                                     // Ia harus mutable karena kita akan mengubahnya
                                                     // Sekarang ia memiliki akses ke Mutex
                                                     // Mari kita cetak my_mutex untuk melihatnya:

    println!("{:?}", my_mutex); // Ia akan mencetak "Mutex { data: <locked> }"
                                // Sehingga sekarang kita tidak bisa mengakses data di dalam my_mutex,
                                // kita hanya bisa mengaksesnya lewat mutex_changer

    println!("{:?}", mutex_changer); // Hasil cetaknya adalah 5. Mari kita ubah nilainya ke 6.

    *mutex_changer = 6; // mutex_changer bertype MutexGuard<i32>, jadinya kita menggunakan * untuk mengubah i32

    println!("{:?}", mutex_changer); // Sekarang hasilnya adalah 6
}
```

Tetapi `mutex_changer` tetap terkuci setelah kita melakukan perubahan. Bagaimana cara kita menghentikan pengunciannya? `Mutex` akan terbuka (unlocked) secara otomatis di saat `MutexGuard` keluar dari scope (goes out of scope). "Go out of scope" berarti code blocknya telah selesai. Contohnya:

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);
    {
        let mut mutex_changer = my_mutex.lock().unwrap();
        *mutex_changer = 6;
    } // mutex_changer keluar dari scope - sekarang ia menghilang. Ia tidak lagi terkunci

    println!("{:?}", my_mutex); // Outputnya adalah: Mutex { data: 6 }
}
```

Jika Anda tidak ingin menggunakan code block `{}` yang berbeda, Anda bisa menggunakan `std::mem::drop(mutex_changer)`. `std::mem::drop` berarti "buat dia menjadi keluar dari scope".

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);
    let mut mutex_changer = my_mutex.lock().unwrap();
    *mutex_changer = 6;
    std::mem::drop(mutex_changer); // drop mutex_changer - ia menghilang
                                   // dan my_mutex kembali unlocked

    println!("{:?}", my_mutex); // Hasilnya adalah: Mutex { data: 6 }
}
```

Anda harus berhati-hati di saat menggunakan `Mutex`, karena jika ada variabel lain yang mencoba untuk menguncinya (menggunakan `lock`), ia akan menunggu:

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);
    let mut mutex_changer = my_mutex.lock().unwrap(); // mutex_changer yang memiliki lock-nya
    let mut other_mutex_changer = my_mutex.lock().unwrap(); // other_mutex_changer juga ingin melakukan lock
                                                            // maka programnya akan selalu menunggu
                                                            // dan menunggu
                                                            // dan selamanya akan tetap menunggu.

    println!("This will never print...");
}
```

Satu method lainnya adalah `try_lock()`. Ia akan sekali mencoba untuk melakukan lock, dan jika ia tidak bisa melakukan lock, ia akan menyerah. Jangan pernah mencoba menggunakan `try_lock().unwrap()`, karena ia akan panic jika try_lock menyerah. Akan lebih baik untuk menggunakan `if let` atau `match` untuk kasus seperti ini:

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);
    let mut mutex_changer = my_mutex.lock().unwrap();
    let mut other_mutex_changer = my_mutex.try_lock(); // try to get the lock

    if let Ok(value) = other_mutex_changer {
        println!("The MutexGuard has: {}", value)
    } else {
        println!("Didn't get the lock")
    }
}
```

Juga, Anda tidak perlu untuk membuat sebuah variabel untuk mengubah `Mutex`. Anda bisa melakukannya seperti ini:

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);

    *my_mutex.lock().unwrap() = 6;

    println!("{:?}", my_mutex);
}
```

`*my_mutex.lock().unwrap() = 6;` berarti "buka kunci my_mutex dan ubah nilainya menjadi 6". Tidak ada variabel yang menyimpan MutexGuardnya, sehingga Anda tidak perlu untuk menggunakan `std::mem::drop`. Anda bisa melakukannya ratusan kali jika Anda mau - tidak ada masalah:

```rust
use std::sync::Mutex;

fn main() {
    let my_mutex = Mutex::new(5);

    for _ in 0..100 {
        *my_mutex.lock().unwrap() += 1; // locks dan unlocks sebanyak 100 kali
    }

    println!("{:?}", my_mutex);
}
```

### RwLock

`RwLock` kependekan dari "read write lock". Ia mirip seperti `Mutex` namun juga mirip seperti `RefCell`. Anda menggunakan `.write().unwrap()` menggantikan `.lock().unwrap()` untuk mengubah valuenya. Anda juga bisa menggunakan `.read().unwrap()` untuk mendapatkan read access. Ini seperti `RefCell` karena ia mengikuti aturan sebagai berikut:

- banyak variabel `.read()`, boleh,
- satu variabel `.write()`, juga boleh,
- tapi, lebih dari satu `.write()`, tidak boleh
- `.read()` bersamaan dengan `.write()` juga tidak boleh.

Program akan terus berjalan jika Anda mencoba menggunakan `.write()` disaaat Anda tidak mendapatkan akses:

```rust
use std::sync::RwLock;

fn main() {
    let my_rwlock = RwLock::new(5);

    let read1 = my_rwlock.read().unwrap(); // one .read() is fine
    let read2 = my_rwlock.read().unwrap(); // two .read()s is also fine

    println!("{:?}, {:?}", read1, read2);

    let write1 = my_rwlock.write().unwrap(); // uh oh, now the program will wait forever
}
```

Jadi kita menggunakan `std::mem::drop`, sama seperti yang kita lakukan pada `Mutex`.

```rust
use std::sync::RwLock;
use std::mem::drop; // kita akan menggunakan drop() berkali-kali

fn main() {
    let my_rwlock = RwLock::new(5);

    let read1 = my_rwlock.read().unwrap();
    let read2 = my_rwlock.read().unwrap();

    println!("{:?}, {:?}", read1, read2);

    drop(read1);
    drop(read2); // kita drop keduanya, sehingga kita bisa menggunakan .write() sekarang

    let mut write1 = my_rwlock.write().unwrap();
    *write1 = 6;
    drop(write1);
    println!("{:?}", my_rwlock);
}
```

Dan Anda bisa menggunakan `try_read()` dan juga `try_write()`.

```rust
use std::sync::RwLock;

fn main() {
    let my_rwlock = RwLock::new(5);

    let read1 = my_rwlock.read().unwrap();
    let read2 = my_rwlock.read().unwrap();

    if let Ok(mut number) = my_rwlock.try_write() {
        *number += 10;
        println!("Now the number is {}", number);
    } else {
        println!("Couldn't get write access, sorry!")
    };
}
```

## Cow

Cow adalah enum yang cukup membantu. Ia singkatan dari "clone on write" dan memungkinkan Anda mengembalikan `&str` jika Anda tidak membutuhkan `String`, dan mengembalikan `String` jika Anda memerlukannya. (Ia juga bisa melakukan hal yang sama pada array vs. Vecs, dan lainnya.)

Untuk memahami ini, mari kita lihat signaturenya. Seperti ini:

```rust
pub enum Cow<'a, B>
where
    B: 'a + ToOwned + ?Sized,
 {
    Borrowed(&'a B),
    Owned(<B as ToOwned>::Owned),
}

fn main() {}
```

Anda langsung mengetahui bahwa `'a` artinya ia bekerja dengan reference. Trait `ToOwned` artinya bahwa ia adalah type yang bisa diubah menjadi sebuah owned type. Contohnya, `str` biasanya adalah reference (`&str`) dan Anda bisa mengubahnya menjadi owned type seperti `String`.

Selanjutnya adalah `?Sized`. Ini berari "mungkin Sized, mungkin juga bukan". Hampis semua type di dalam Rust adalah Sized, namun type seperti `str` adalah bukan. Itulah mengapa kita memerlukan `&` untuk `str`, karen compiler tidak mengetahui sizenya. Sehingga, jika Anda menginginkan sebuah trait yang bisa menggunakan sesuatu seperti `str`, Anda tambahkan `?Sized.`

Selanjutnya adalah variant `enum`nya. Yaitu `Borrowed` dan `Owned`.

Bayangkan, Anda memiliki function yang mengembalikan `Cow<'static, str>`. Jika Anda memberitahu function untuk mengembalikan `"My message".into()`, ia akan memeriksa pada typenya: "My message" adalah `str`. Ini merupakan type `Borrowed`, jadi ia memilih `Borrowed(&'a B)`. Sehingga ia menjadi `Cow::Borrowed(&'static str)`.

Dan jika Anda memberikan `format!("{}", "My message").into()`, ia pun akan memeriksa typenya. Dan ini merupakan `String`, karena `format!` membuat sebuah `String`. Sehingga untuk kali ini ia akan memilih "Owned".

Ini adalah contoh untuk melakukan test pada `Cow`. Kita akan meletakkan sebuah angka ke dalam function yang mengembalikan `Cow<'static, str>`. Kita akan membuat sebuah `&str` atau `String`, tergantung dari angkanya. Kemudian ia menggunakan `.into()` untuk mengubahnya menjadi `Cow`. Di saat Anda melakukan hal tersebut, ia akan memilih antara `Cow::Borrowed` atau `Cow::Owned`. Kemudian kita gunakan match untuk melihat yang mana yang akan dipilih oleh `Cow`.

```rust
use std::borrow::Cow;

fn modulo_3(input: u8) -> Cow<'static, str> {
    match input % 3 {
        0 => "Remainder is 0".into(),
        1 => "Remainder is 1".into(),
        remainder => format!("Remainder is {}", remainder).into(),
    }
}

fn main() {
    for number in 1..=6 {
        match modulo_3(number) {
            Cow::Borrowed(message) => println!("{} went in. The Cow is borrowed with this message: {}", number, message),
            Cow::Owned(message) => println!("{} went in. The Cow is owned with this message: {}", number, message),
        }
    }
}
```

Hasilnya adalah:

```text
1 went in. The Cow is borrowed with this message: Remainder is 1
2 went in. The Cow is owned with this message: Remainder is 2
3 went in. The Cow is borrowed with this message: Remainder is 0
4 went in. The Cow is borrowed with this message: Remainder is 1
5 went in. The Cow is owned with this message: Remainder is 2
6 went in. The Cow is borrowed with this message: Remainder is 0
```

`Cow` memiliki method yang lain seperti `into_owned` atau `into_borrowed` sehingga Anda bisa menggantinya jika Anda merasa perlu melakukannya.

## Type aliases

Type alias artinya "memberikan nama baru ke type lain". Type alias bisa dilakukan dengan sangat mudah. Biasanya Anda menggunakannya di saat Anda mempunya type yang panjang dan tidak ingin untuk menulisnya setiap saat. Ini juga bagus saat Anda ini memberikan nama yang lebih baik pada sebuah type yang mana membuatnya menjadi lebih mudah untuk diingat. Ini adalah dua contoh penggunaan type alias.

Ini adalah type yang tidak begitu rumi, namun Anda ingin membuat codenya menjadi mudah untuk dipahami oleh orang lain (dan juga untuk diri kita sendiri):

```rust
type CharacterVec = Vec<char>;

fn main() {}
```

Ini adalah type yang sulit untuk dibaca:

```rust
// type yang dikembalikan benar-benar sangat panjang
fn returns<'a>(input: &'a Vec<char>) -> std::iter::Take<std::iter::Skip<std::slice::Iter<'a, char>>> {
    input.iter().skip(4).take(5)
}

fn main() {}
```

Sehingga Anda bisa mengubahnya menjadi seperti ini:

```rust
type SkipFourTakeFive<'a> = std::iter::Take<std::iter::Skip<std::slice::Iter<'a, char>>>;

fn returns<'a>(input: &'a Vec<char>) -> SkipFourTakeFive {
    input.iter().skip(4).take(5)
}

fn main() {}
```

Tentu saja, Anda juga bisa melakukan import itemnya untuk menuliskan typenya menjadi lebih pendek:

```rust
use std::iter::{Take, Skip};
use std::slice::Iter;

fn returns<'a>(input: &'a Vec<char>) -> Take<Skip<Iter<'a, char>>> {
    input.iter().skip(4).take(5)
}

fn main() {}
```

Sehingga Anda bisa menentukan yang mana yang terlihat lebih baik pada code Anda, tergantung dari yang Anda suka.

Perlu diingat bahwa cara ini tidaklah membuat sebuah type yang baru. Ia hanyalah sebuah nama yang digunakan sebagai wakil dari type yang sebenarnya. Jadi jika Anda menulis `type File = String;`, compiler hanya melihatnya sebagai `String`. Sehingga program dibawah ini akan mencetak `true`:

```rust
type File = String;

fn main() {
    let my_file = File::from("I am file contents");
    let my_string = String::from("I am file contents");
    println!("{}", my_file == my_string);
}
```

Jadi bagaimana jika Anda ingin membuat type baru yang sebenarnya?

Jika Anda ingin membuat type file yang baru yang mana compiler akan melihatnya sebagai `File`, Anda bisa memasukkannya ke dalam struct:

```rust
struct File(String); // File adalah pembungkus String

fn main() {
    let my_file = File(String::from("I am file contents"));
    let my_string = String::from("I am file contents");
}
```

Namun code di bawah ini tidak berjalan, karena keduanya adalah type yang berbeda:

```rust
struct File(String); // File adalah pembungkus String

fn main() {
    let my_file = File(String::from("I am file contents"));
    let my_string = String::from("I am file contents");
    println!("{}", my_file == my_string);  // ⚠️ tidak bisa membandingkan File dengan String
}
```

Jika Anda ingin membandingkannya dengan String didalamnya, Anda bisa menggunakan my_file.0:

```rust
struct File(String);

fn main() {
    let my_file = File(String::from("I am file contents"));
    let my_string = String::from("I am file contents");
    println!("{}", my_file.0 == my_string); // my_file.0 adalah String, sehingga hasilnya adalah true
}
```

### Importing and renaming inside a function

Biasanya Anda menulis `use` pada bagian atas program, seperti ini:

```rust
use std::cell::{Cell, RefCell};

fn main() {}
```

Tapi kita juga melihat bahwa kita bisa melakukan ini dimana saja, terutama di dalam functions dengan enums yang memiliki nama yang panjang. Ini adalah contohnya.

```rust
enum MapDirection {
    North,
    NorthEast,
    East,
    SouthEast,
    South,
    SouthWest,
    West,
    NorthWest,
}

fn main() {}

fn give_direction(direction: &MapDirection) {
    match direction {
        MapDirection::North => println!("You are heading north."),
        MapDirection::NorthEast => println!("You are heading northeast."),
        // Masih banyak yang harus diketik...
        // ⚠️ karena kita tidak menuliskan setiap variantnya
    }
}
```

Jadi sekarang kita akan meng-import MapDirection ke dalam function. Yang berarti bahwa di dalam function, Anda bisa menuliskannya cukup seperti `North` dan seterusnya.

```rust
enum MapDirection {
    North,
    NorthEast,
    East,
    SouthEast,
    South,
    SouthWest,
    West,
    NorthWest,
}

fn main() {}

fn give_direction(direction: &MapDirection) {
    use MapDirection::*; // Import semua yang ada di dalam MapDirection
    let m = "You are heading";

    match direction {
        North => println!("{} north.", m),
        NorthEast => println!("{} northeast.", m),
        // Ini cara penulisan yang lebih baik
        // ⚠️
    }
}
```

Kita telah melihat bahwa `::*` berarti "import semua yang ada setelah ::". Pada kasus kita, itu berarti adalah `North`, `NorthEast`...dan seterusnya sampai dengan `NorthWest`. Di saat Anda melakukan import terhadap code yang dibuat oleh orang lain, Anda juga bisa melakukannya. Namun bila codenya sangatlah besar, mungkin Anda akan mendapatkan masalah. Bagaimana jika code tersebut memiliki beberapa item yang sama seperti yang ada pada code Anda? Jadi, biasanya jalan terbaiknya adalah dengan tidak selalu menggunakan `::*` setiap saat, kecuali Anda yakin. Seringkali Anda melihat bagian yang disebut sebagai `prelude` pada code orang lain yang berisi semua item utama yang mungkin Anda perlukan. Maka Anda biasanya akan menggunakannya seperti ini: `name::prelude::*`. Kita akan membicarakan ini lebih lanjut pada bagian tentang `modules` dan `crates`.

Anda juga bisa menggunakan `as` untuk mengganti namanya. Sebagai contoh, mungkin Anda sedang menggunakan code orang lain dan Anda tidak bisa mengganti nama variant yang ada di dalam enum:

```rust
enum FileState {
    CannotAccessFile,
    FileOpenedAndReady,
    NoSuchFileExists,
    SimilarFileNameInNextDirectory,
}

fn main() {}
```

Maka, Anda bisa 1) import semuanya dan 2) mengganti namanya:

```rust
enum FileState {
    CannotAccessFile,
    FileOpenedAndReady,
    NoSuchFileExists,
    SimilarFileNameInNextDirectory,
}

fn give_filestate(input: &FileState) {
    use FileState::{
        CannotAccessFile as NoAccess,
        FileOpenedAndReady as Good,
        NoSuchFileExists as NoFile,
        SimilarFileNameInNextDirectory as OtherDirectory
    };
    match input {
        NoAccess => println!("Can't access file."),
        Good => println!("Here is your file"),
        NoFile => println!("Sorry, there is no file by that name."),
        OtherDirectory => println!("Please check the other directory."),
    }
}

fn main() {}
```

Sehingga sekarang Anda bisa menuliskan `OtherDirectory` daripada menulisnya dengan `FileState::SimilarFileNameInNextDirectory`.

## The todo! macro

Terkadang Anda ingin menulis code secara general (menggunakan pseudocode) untuk membantu Anda membayangkan proyek Anda. Sebagai contoh, bayangkan sebuah proyek sederhana untuk melakukan sesuatu yang berhubungan dengan buku. Kira-kira, mungkin seperti inilah yang Anda pikirkan:

```rust
struct Book {} // Okay, pertama, saya memerlukan sebuah struct bernama Book.
               // Belum ada apapun di dalamnya - kita akan menambahkannya kemudian

enum BookType { // Sebuah buku bisa dalam bentuk hardcover ataua softcover, sehingga kita tambahkan enum
    HardCover,
    SoftCover,
}

fn get_book(book: &Book) -> Option<String> {} // ⚠️ get_book mengambil &Book dan mengembalikan Option<String>

fn delete_book(book: Book) -> Result<(), String> {} // delete_book mengambil Book sebagai inputannya dan mengembalikan Result...
                                                    // TODO: block impl dan buat sebuah method dengan function ini ...
fn check_book_type(book_type: &BookType) { // Mari kita pastikan bahwa statement matchnya bekerja
    match book_type {
        BookType::HardCover => println!("It's hardcover"),
        BookType::SoftCover => println!("It's softcover"),
    }
}

fn main() {
    let book_type = BookType::HardCover;
    check_book_type(&book_type); // Okay, kita periksa function ini!
}
```

Tapi Rust akan memberikan teguran pada function `get_book` dan `delete_book`. Compiler mengatakan:

```text
error[E0308]: mismatched types
  --> src\main.rs:32:29
   |
32 | fn get_book(book: &Book) -> Option<String> {}
   |    --------                 ^^^^^^^^^^^^^^ expected enum `std::option::Option`, found `()`
   |    |
   |    implicitly returns `()` as its body has no tail or `return` expression
   |
   = note:   expected enum `std::option::Option<std::string::String>`
           found unit type `()`

error[E0308]: mismatched types
  --> src\main.rs:34:31
   |
34 | fn delete_book(book: Book) -> Result<(), String> {}
   |    -----------                ^^^^^^^^^^^^^^^^^^ expected enum `std::result::Result`, found `()`
   |    |
   |    implicitly returns `()` as its body has no tail or `return` expression
   |
   = note:   expected enum `std::result::Result<(), std::string::String>`
           found unit type `()`
```

Tapi untuk sekarang ini kita belum begitu peduli dengan function `get_book` dan `delete_book`. Inilah dimana kita bisa menggunakan `todo!()`. Jika kita menambahkannya pada function, Rust tidak akan menganggapnya sebagai error, dan programnya dikompilasi tanpa hambatan apapun.

```rust
struct Book {}

fn get_book(book: &Book) -> Option<String> {
    todo!() // todo means "I will do it later, please be quiet"
}

fn delete_book(book: Book) -> Result<(), String> {
    todo!()
}

fn main() {}
```

Sekarang codenya bisa di-compile dan Anda bisa melihat hasil dari function `check_book_type`: `It's hardcover`.

Tapi, bukan berarti saat codenya ter-compile maka Anda bisa menggunakan functionnya. Anda tidak bisa menggunakannya. Jika Anda panggil function yang berisi `todo!()` didalamnya, maka ia akan panic.

Juga, function `todo!()` tetap memerlukan type pada input dan outputnya. Jika Anda menuliskannya seperti dibawah ini, maka ia tidak akan ter-compile:

```rust
struct Book {}

fn get_book(book: &Book) -> WorldsBestType { // ⚠️
    todo!()
}

fn main() {}
```

Compiler akan memberikan pesan:

```text
error[E0412]: cannot find type `WorldsBestType` in this scope
  --> src\main.rs:32:29
   |
32 | fn get_book(book: &Book) -> WorldsBestType {
   |                             ^^^^^^^^^^^^^^ not found in this scope
```

`todo!()` sebenarnya sama seperti macro yang `unimplemented!()`. Programmers sangat sering menggunakan `unimplemented!()`, namun ia terlalu panjang untuk diketik. Jadinya, dibuatlah `todo!()` dimana ia adalah versi pendeknya.

## Rc

Rc adalah singkatan dar "reference counter". Kita semua sejauh ini sama-sama tahu, bahwa setiap variabel di Rust hanya bisa memiliki satu owner. Oleh karena hal itu, code dibawah ini tidak akan bekerja:

```rust
fn takes_a_string(input: String) {
    println!("It is: {}", input)
}

fn also_takes_a_string(input: String) {
    println!("It is: {}", input)
}

fn main() {
    let user_name = String::from("User MacUserson");

    takes_a_string(user_name);
    also_takes_a_string(user_name); // ⚠️
}
```

Setelah `takes_a_string` mengambil `user_name`, kita sama sekali tidak bisa menggunakannya lagi. Kita bisa saja menggunakan alternatif ini: Anda bisa memberi function tersebut dengan `user_name.clone()`. Tapi, terkadang sebuah variabel adalah bagian dari sebuah struct, dan mungkin Anda tidak bisa melakukan clone terhadap struct. Atau mungkin juga `String`nya terlampau panjang dan Anda tidak ingin menggunakan clone (karena menguras memori). Nah, alasan-alasan seperti inilah mengapa `Rc` digunakan, yang memungkinan Anda untuk memiliki lebih dari satu owner. `Rc` bisa dianalogikan seperti petugas yang mencatat kepemilikan: `Rc` siapa saja yang menulis ownership, dan seberapa banyak. Kemudian, setelah jumlah owner telah menjadi 0, variabel tersebut bisa menghilang.

Ini adalah bagaimana kita bisa menggunakan `Rc`. Pertama, bayangkan dua struct: satu bernama `City`, dan yang satunya bernama `CityData`. `City` memiliki informasi satu kota, dan `CityData` memasukkan semua kota ke dalam `Vec`s.

```rust
#[derive(Debug)]
struct City {
    name: String,
    population: u32,
    city_history: String,
}

#[derive(Debug)]
struct CityData {
    names: Vec<String>,
    histories: Vec<String>,
}

fn main() {
    let calgary = City {
        name: "Calgary".to_string(),
        population: 1_200_000,
           // Anggap saja String city_history ini sangat panjang
        city_history: "Calgary began as a fort called Fort Calgary that...".to_string(),
    };

    let canada_cities = CityData {
        names: vec![calgary.name], // Ini menggunakan calgary.name, yang mana lebih pendek
        histories: vec![calgary.city_history], // String yang ini sangatlah panjang
    };

    println!("Calgary's history is: {}", calgary.city_history);  // ⚠️
}
```

Tentu saja, code di atas tidak berjalan karena `canada_cities` yang memiliki datanya dan `calgary` tidak lagi memilikinya. Berikut adalah pesan errornya:

```text
error[E0382]: borrow of moved value: `calgary.city_history`
  --> src\main.rs:27:42
   |
24 |         histories: vec![calgary.city_history], // But this String is very long
   |                         -------------------- value moved here
...
27 |     println!("Calgary's history is: {}", calgary.city_history);  // ⚠️
   |                                          ^^^^^^^^^^^^^^^^^^^^ value borrowed here after move
   |
   = note: move occurs because `calgary.city_history` has type `std::string::String`, which does not implement the `Copy` trait
```

Kita bisa menggunakan clone untuk bagian nama: `names: vec![calgary.name.clone()]`. Tapi kita tidak ingin menggunakan clone untuk `city_history`, karena ia terlalu panjang. Jadi kita bisa menggunakan `Rc`.

Tambahkan deklarasi `use`:

```rust
use std::rc::Rc;

fn main() {}
```

Kemudian letakkan `Rc` untuk membungkus type `String`.

```rust
use std::rc::Rc;

#[derive(Debug)]
struct City {
    name: String,
    population: u32,
    city_history: Rc<String>,
}

#[derive(Debug)]
struct CityData {
    names: Vec<String>,
    histories: Vec<Rc<String>>,
}

fn main() {}
```

Untuk menambahkan reference yang baru, Anda perlu melakukan `clone` terhadap `Rc`. Tapi, tunggu dulu, bukankah kita menghindari untuk menggunakan `.clone()`? Tidak sepenuhnya tepat: kita tidak ingin melakukan clone terhadap seluruh Stringnya. Tetapi yang di-clone adalah `Rc`nya. Clone dari `Rc` sebenarnya adalah melakukan clone terhadap pointer - yang mana itu benar-benar menghemat memori. Ini seperti menempelkan sticker nama (yang mana adalah nama setiap pemilik) ke sebuah kotak berisi buku-buku, untuk menunjukkan bahwa ada 2 orang yang memilikinya, daripada menggunakan kotak yang berbeda.

Kita bisa melakukan clone terhadap `Rc` yang bernama `item` dengan menggunakan `item.clone()` atau `Rc::clone(&item)`. Jadinya, calgary.city_history memiliki 2 owners. Kita bisa mengetahui berapa banyak ownernya menggunakan `Rc::strong_count(&item)`. Dan juga, kita coba untuk tambahkan owner baru. Sekarang codenya akan terlihat seperti ini:

```rust
use std::rc::Rc;

#[derive(Debug)]
struct City {
    name: String,
    population: u32,
    city_history: Rc<String>, // String di dalam Rc
}

#[derive(Debug)]
struct CityData {
    names: Vec<String>,
    histories: Vec<Rc<String>>, // Vec dari Strings yang dibungkus dengan Rc
}

fn main() {
    let calgary = City {
        name: "Calgary".to_string(),
        population: 1_200_000,
           // Anggap saja String city_history ini sangat panjang
        city_history: Rc::new("Calgary began as a fort called Fort Calgary that...".to_string()), // Rc::new() untuk membuat Rc
    };

    let canada_cities = CityData {
        names: vec![calgary.name],
        histories: vec![calgary.city_history.clone()], // .clone() untuk menambah ownernya
    };

    println!("Calgary's history is: {}", calgary.city_history);
    println!("{}", Rc::strong_count(&calgary.city_history));
    let new_owner = calgary.city_history.clone();
}
```

Hasil cetaknya adalah `2`. Dan `new_owner` bertype `Rc<String>`. Jika kita menggunakan `println!("{}", Rc::strong_count(&calgary.city_history));`, maka ownernya sekarang adalah `3`.

Apa maksud kata `strong` dari `Rc::strong_count`? Pada contoh kasus `Rc` yang kita lihat di atas, kita sebenarnya membuat sebuah strong pointer. Dan `Rc::strong_count` itulah yang berguna untuk menghitung banyaknya strong pointer yang ada di suatu program.

Jika ada strong pointer, apakah ada yang dinamakan dengan weak pointer? Jawabannya, ya. Ada yang namanya weak pointer. Weak pointers sangatlah berguna karena jika ada 2 buah `Rc` yang merujuk satu sama lain, maka keduanya tidak bisa mati. Ini biasa disebut sebagai "reference cycle". Jika item 1 memiliki sebuah Rc ke item 2, dan item 2 memiliki sebuah Rc ke item 1, maka ownernya tidak bisa ke-0 (ownernya tidak bisa berkurang). Pada kasus seperti inilah kita ingin menggunakan weak references. `Rc` menghitung referencenya, jika ia hanya memiliki weak reference maka ia akan mati (owner = 0). Anda bisa menggunakan `Rc::downgrade(&item)` sebagai pengganti `Rc::clone(&item)` untuk membuat weak references. Juga, Anda harus menggunakan `Rc::weak_count(&item)` untuk melihat banyak weak referencenya.

## Multiple threads

Jika kita menggunakan multiple threads, Anda bisa melakukan banyak hal dalam waktu yang bersamaan. Komputer modern memiliki lebih dari satu core sehingga mereka bisa melakukan lebih dari satu task pada waktu yang bersamaan, dan Rust memungkinkan Anda untuk menggunakannya. Rust menggunakan threads yang biasa disebut dengan "OS threads". OS thread artinya bahwa operating system membuat threadnya pada core yang berbeda. (Beberapa bahasa pemrograman lainnya menggunakan "green threads", yang mana itu kurang begitu powerful)


Kita membuat threadnya menggunakan `std::thread::spawn` dan kemudian menuliskan closure untuk memberitahu compiler tentang apa yang dilakukan oleh thread tersebut. Threads sangatlah menarik karena mereka berjalan pada waktu yang sama, dan Anda bisa mencobanya untuk melihat apa yang sebenarnya terjadi. Ini adalah contoh sederhananya:

```rust
fn main() {
    std::thread::spawn(|| {
        println!("I am printing something");
    });
}
```

Jika Anda menjalankan code di atas, ia akan berbeda-beda setiap saat. Terkadang ia mencetak hasilnya, dan terkadang juga tidak mencetak apapun (ini tergantung pada kecepatan komputer Anda). Ini karena terkadang `main()` selesai sebelum threadnya selesai. Dan jika `main()` selesai, tentunya program berakhir. Akan lebih mudah melihatnya apagila kita meletakkan threadnya di dalam `for` loop:

```rust
fn main() {
    for _ in 0..10 { // buat sebanyak 10 threads
        std::thread::spawn(|| {
            println!("I am printing something");
        });
    }   // Sekarang threadnya mulai berjalan.
}       // Berapa banyak thread yang selesai dijalankan sebelum main() berakhir disini?
```

Biasanya ada 4 thread yang melakukan print sebelum `main` berakhir, namun hasil ini akan selalu berbeda. Jika komputer Anda lebih cepat, maka mungkin thread tidak akan mencetak apapun. Juga, terkadang threadnya akan panic:

```text
thread 'thread 'I am printing something
thread '<unnamed><unnamed>thread '' panicked at '<unnamed>I am printing something
' panicked at 'thread '<unnamed>cannot access stdout during shutdown' panicked at '<unnamed>thread 'cannot access stdout during
shutdown
```

Ini adalah error saat thread mencoba untuk melakukan sesuatu tepat di saat program dimatikan.

Anda bisa memberikan sesuatu kepada komputer agar programnya tidak langsung mati. Setidaknya kita membuat komputer menjadi sibuk, sehingga thread bisa menyelesaikan tugasnya:

```rust
fn main() {
    for _ in 0..10 {
        std::thread::spawn(|| {
            println!("I am printing something");
        });
    }
    for _ in 0..1_000_000 { // buat program mendeklarasikan "let x = 9" sebanyak 1 juta kali
                            // Program harus menyelesaikan ini sebelum akhirnya ia bisa keluar dari function main()
        let _x = 9;
    }
}
```

Tetapi, cara di atas itu adalah cara yang konyol silly way untuk memberikan waktu kepada threads untuk menyelesaikan task-tasknya. Cara yang agak lebih baik adalah mem-binding threads tersebut ke sebuah variable. Jika Anda menambahkan `let`, maka Anda akan membuat sesuatu yang bertype `JoinHandle`. Anda bisa melihat ini di dalam signature dari method `spawn`:

```text
pub fn spawn<F, T>(f: F) -> JoinHandle<T>
where
    F: FnOnce() -> T,
    F: Send + 'static,
    T: Send + 'static,
```

(`f` adalah closure - Nantinya kita akan mempelajari bagaimana untuk meletakkan closures ke dalam function yang kita buat)

Sehingga sekarang kita memiliki `JoinHandle` setiap saat.

```rust
fn main() {
    for _ in 0..10 {
        let handle = std::thread::spawn(|| {
            println!("I am printing something");
        });

    }
}
```

`handle` sekarang bertype `JoinHandle`. Apa yang akan kita lakukan dengan `JoinHandle`? Kita akan menggunakan method yang bernama `.join()`. Method ini berarti "tunggu sampai semua threads selesai" (ia akan menunggu thread untuk bergabung). Jadi sekarang kita hanya cukup menuliskan `handle.join()` dan ia akan menunggu setiap thread selesai dikerjakan.

```rust
fn main() {
    for _ in 0..10 {
        let handle = std::thread::spawn(|| {
            println!("I am printing something");
        });

        handle.join(); // tunggu semua thread selesai dikerjakan
    }
}
```

Sekarang kita akan mempelajari tentang 3 type dari closure. Tiga type tersebut adalah:

- `FnOnce`: mengambil valuenya
- `FnMut`: mengambil mutable reference
- `Fn`: mengambil regular reference

Closure akan mencoba untuk mengambil `Fn` jika ia bisa. Tapi, jika ia perlu untuk mengganti valuenya, ia akan menggunakan `FnMut`, dan jika ia perlu untuk mengambil valuenya sepenuhnya, ia akan menggunakan `FnOnce`. `FnOnce` adalah nama yang bagus karena ia menjelaskan apa yang ia lakukan: ia mengambil valuenya sekali, dan kemudian tidak akan (dan juga tidak bisa) mengambilnya lagi.

Ini adalah contohnya:

```rust
fn main() {
    let my_string = String::from("I will go into the closure");
    let my_closure = || println!("{}", my_string);
    my_closure();
    my_closure();
}
```

`String` bukanlan `Copy`, sehingga `my_closure()` adalah `Fn`: ia mengambil referencenya.

Jika melakukan perubahan pada `my_string`, ia akan menjadi `FnMut`.

```rust
fn main() {
    let mut my_string = String::from("I will go into the closure");
    let mut my_closure = || {
        my_string.push_str(" now");
        println!("{}", my_string);
    };
    my_closure();
    my_closure();
}
```

Hasil cetaknya adalah:

```text
I will go into the closure now
I will go into the closure now now
```

Dan jika Anda mengambil valuenya, maka ia akan menjadi `FnOnce`.

```rust
fn main() {
    let my_vec: Vec<i32> = vec![8, 9, 10];
    let my_closure = || {
        my_vec
            .into_iter() // into_iter mengambil ownership
            .map(|x| x as u8) // ubah setiap elementnya menjadi u8
            .map(|x| x * 2) // kalikan dengan 2
            .collect::<Vec<u8>>() // taruh semua hasilnya ke dalam Vec
    };
    let new_vec = my_closure();
    println!("{:?}", new_vec);
}
```

Kita mengambil valuenya, sehingga kita tidak bisa menjalankan `my_closure()` lebih dari sekali. Dari sana nama `FnOnce` berasal.

Jadi, sekarang kita kembali ke threads. Mari kita coba untuk menggunakan sebuah value dari luar thread:

```rust
fn main() {
    let mut my_string = String::from("Can I go inside the thread?");

    let handle = std::thread::spawn(|| {
        println!("{}", my_string); // ⚠️
    });

    handle.join();
}
```

Compiler akan mengatakan bahwa ini tidak bekerja.

```text
error[E0373]: closure may outlive the current function, but it borrows `my_string`, which is owned by the current function
  --> src\main.rs:28:37
   |
28 |     let handle = std::thread::spawn(|| {
   |                                     ^^ may outlive borrowed value `my_string`
29 |         println!("{}", my_string);
   |                        --------- `my_string` is borrowed here
   |
note: function requires argument type to outlive `'static`
  --> src\main.rs:28:18
   |
28 |       let handle = std::thread::spawn(|| {
   |  __________________^
29 | |         println!("{}", my_string);
30 | |     });
   | |______^
help: to force the closure to take ownership of `my_string` (and any other referenced variables), use the `move` keyword
   |
28 |     let handle = std::thread::spawn(move || {
   |                                     ^^^^^^^
```

Ini merupakan pesan error yang panjang, tetapi sangat membantu: ia menyarankan untuk ``use the `move` keyword`` (menggunakan keyword `move`). Masalahnya adalah kita bisa melakukan apapun terhadap `my_string` di saat thread sedang menggunakannya, namun tidak memiliki kepemilikan atas value tersebut. Hal seperti tentulah samas sekali tidak aman.

Mari kita, lagi-lagi, membuat program yang tidak bisa dijalankan :D :

```rust
fn main() {
    let mut my_string = String::from("Can I go inside the thread?");

    let handle = std::thread::spawn(|| {
        println!("{}", my_string); // sekarang my_string digunakan sebagai reference
    });

    std::mem::drop(my_string);  // ⚠️ Kita mencoba untuk melakukan drop pada my_string disini. Namun threadnya masih memerlukan my_string.

    handle.join();
}
```

Sehingga Anda perlu untuk mengambil valuenya menggunakan `move`. Dan sekarang programnya safe:

```rust
fn main() {
    let mut my_string = String::from("Can I go inside the thread?");

    let handle = std::thread::spawn(move|| {
        println!("{}", my_string);
    });

    std::mem::drop(my_string);  // ⚠️ kita tidak bisa melakukan drop disini, karena variabel handle memilikinya. Jadi ini tidak akan berjalan

    handle.join();
}
```

Jadinya kita hapuskan `std::mem::drop`, dan sekarang programnya berjalan. `handle` mengambil `my_string` dan code kita menjadi safe.

```rust
fn main() {
    let mut my_string = String::from("Can I go inside the thread?");

    let handle = std::thread::spawn(move|| {
        println!("{}", my_string);
    });

    handle.join();
}
```

Jadi cukup diingat: jika Anda memiliki value di dalam thread yang berasal dari luar thread, Anda perlu menggunakan `move`.



## Closures in functions

Closure memanglah powerful. Jadi bagaimana kita memasukkannya ke dalam function yang kita buat sendiri?

Anda bisa membuat function Anda sendiri yang mana ia bisa diberi input berupa closure. Tapi meletakkannya di dalam function membuatnya menjadi kurang leluasa dan Anda perlu untuk menentukan typenya. Di luar dari function closure bida menenetukan typenya sendiri di antara `Fn`, `FnMut` dan `FnOnce`, Namun, di dalam function, Anda perlu memilih salah satunya. Cara terbaik untuk memahaminya adalah dengan melihat beberapa function signature. Di bawah ini merupakan function signature dari `.all()`. Kita ingat bahwa ia memeriksa iterator untuk melihat apakah semua element bernilai `true` (tergantung pada apa yang Anda putuskan, apakah `true` atau `false`). Bagian dari signaturenya adalah seperti ini:


```rust
    fn all<F>(&mut self, f: F) -> bool    // 🚧
    where
        F: FnMut(Self::Item) -> bool,
```

`fn all<F>`: ini memberi tahu Anda bahwa ada generic type `F`. Closure selalu berupa generic karena ia memiliki type yang berbeda setiap saat.

`(&mut self, f: F)`: `&mut self` memberi tahu Anda bahwa ia adalah sebuah method. `f: F` adalah apa yang biasa Anda lihat pada closure: ini adalah nama variabel dan typenya.  Tentu saja, tidak ada yang spesial tentang `f` dan `F`, dan mereka bisa ditulis dengan nama yang berbeda. Anda bisa menulis `my_closure: Closure` jika Anda menginginkannya - itu tidak masalah. Namun di dalam penulisan signature, Anda akan sering melihat `f: F`.

Selanjutnya adalah bagian tentanya closurenya: `F: FnMut(Self::Item) -> bool`. Di signature tersebut, dipilihlah bahwa type yang dipilih untuk closurenya adalah `FnMut`, jadi ia bisa mengubah valuenya (lewat mutable reference). Ia mengubah value dari `Self::Item`, yang mana itu adalah iterator yang ia ambil. Dan kembaliannya adalah `true` atau `false`.

Ini adalah contoh closure di dalam closure yang lebih sederhana:

```rust
fn do_something<F>(f: F)    // 🚧
where
    F: FnOnce(),
{
    f();
}
```

Signature di atas menyatakan bahwa ia mengambil closure, yang mana closure tersebut mengambil kepemilikan dari value (`FnOnce` = mengambil valuenya), dan tidak mengembalikan apapun. Jadi sekarang kita bisa memanggil closure ini, yang mana parameternya tidak mengambil apapun dan melakukan apapun yang kita mau. Kita akan membuat sebuah `Vec` dan kemudian meng-iterate-nya untuk menunjukkan apa yang bisa kita lakukan sekarang.

```rust
fn do_something<F>(f: F)
where
    F: FnOnce(),
{
    f();
}

fn main() {
    do_something(|| {
        let some_vec = vec![9, 8, 10];
        some_vec
            .iter()
            .for_each(|x| println!("The number is: {}", x));
    })
}
```

Untuk contoh yang lebih nyata, kita akan membuat struct `City` lagi. Untuk kali ini, struct `City` memiliki lebih banyak data, yaitu tentang tahun dan populasi. Typenya adalah `Vec<u32>` untuk semua tahun, dan `Vec<u32>` untuk semua populasi.

`City` memiliki dua function: `new()` untuk membuat `City` yang baru, dan `.city_data()` yang mana adalah closure. Di saat kita menggunakan `.city_data()`, ia memberikan kita tahunnya, populasi dan closure, sehingga kita bisa melakukan apa yang kita inginkan dengan data tersebut. Type dari closurenya adalah `FnMut` sehingga kita bisa mengubah datanya. Codenya adalah seperti berikut:

```rust
#[derive(Debug)]
struct City {
    name: String,
    years: Vec<u32>,
    populations: Vec<u32>,
}

impl City {
    fn new(name: &str, years: Vec<u32>, populations: Vec<u32>) -> Self {

        Self {
            name: name.to_string(),
            years,
            populations,
        }
    }

    fn city_data<F>(&mut self, mut f: F) // Kita gunakan self dan juga. Namun hanya f yang generic (F). f adalah closure

    where
        F: FnMut(&mut Vec<u32>, &mut Vec<u32>), // Closure mengambil vector dari u32 yang bersifat mutable 
                                                // yang mana keduanya itu adalah vector tahun dan populasi
    {
        f(&mut self.years, &mut self.populations) // Dan, ini adalah functionnya. Function tersebut mengatakan
                                                  // "gunakan closure pada self.years dan self.populations"
                                                  // Kita bisa melakukan apapun yang kita inginkan dengan menggunakan closure
    }
}

fn main() {
    let years = vec![
        1372, 1834, 1851, 1881, 1897, 1925, 1959, 1989, 2000, 2005, 2010, 2020,
    ];
    let populations = vec![
        3_250, 15_300, 24_000, 45_900, 58_800, 119_800, 283_071, 478_974, 400_378, 401_694,
        406_703, 437_619,
    ];
    // Sekarang kira bisa membuat City
    let mut tallinn = City::new("Tallinn", years, populations);

    // Sekarang kita memiliki method .city_data() yang memiliki closure. Kita bisa melakukan apa yang kita mau.

    // Pertama-tama, ambil data dari 5 tahun pertama yang ada di vec years dan juga population, gabung menjadi satu dan cetak.
    tallinn.city_data(|city_years, city_populations| { // kita bisa menuliskan inputnya/parameternya dengan apapun yang kita mau
        let new_vec = city_years
            .into_iter()
            .zip(city_populations.into_iter()) // satukan years dengan population menggunakan zip
            .take(5)                           // tapi ambil hanya 5 data pertama
            .collect::<Vec<(_, _)>>(); // Beritahukan Rust untuk memutuskan type yang harus digunakan untuk tuple
        println!("{:?}", new_vec);
    });

    // sekarang, kita tambahakan data untuk tahun 2030
    tallinn.city_data(|x, y| { // kali ini kita hanya menggunakan inputan/parameter x dan y
        x.push(2030);
        y.push(500_000);
    });

    // Kita tidak lagi menginginkan data di tahun 1834, sehingga kita akan menghapusnya
    tallinn.city_data(|x, y| {
        let position_option = x.iter().position(|x| *x == 1834);
        if let Some(position) = position_option {
            println!(
                "Going to delete {} at position {:?} now.",
                x[position], position
            ); // konfirmasi bahwa kita menghapus item yang tepat
            x.remove(position);
            y.remove(position);
        }
    });

    println!(
        "Years left are {:?}\nPopulations left are {:?}",
        tallinn.years, tallinn.populations
    );
}
```

Code di atas akan mencetak semua hasil dibawah ini, yang mana semuanya dihasilkan dari method `.city_data().` :

```text
[(1372, 3250), (1834, 15300), (1851, 24000), (1881, 45900), (1897, 58800)]
Going to delete 1834 at position 1 now.
Years left are [1372, 1851, 1881, 1897, 1925, 1959, 1989, 2000, 2005, 2010, 2020, 2030]
Populations left are [3250, 24000, 45900, 58800, 119800, 283071, 478974, 400378, 401694, 406703, 437619, 500000]
```


## impl Trait

`impl Trait` mirip seperti generics. Kita semua ingat bahwa generics menggunakan type `T` (atau nama lainnya) yang kemudian akan ditentukan saat program dikompilasi. Pertama, kita lihat dulu sebuah concrete type:

```rust
fn gives_higher_i32(one: i32, two: i32) {
    let higher = if one > two { one } else { two };
    println!("{} is higher.", higher);
}

fn main() {
    gives_higher_i32(8, 10);
}
```

Hasilnya adalah: `10 is higher.`.

Tapi ia hanya akan mengambil `i32`, jadi kita akan membuatnya menjadi generic. Kita perlu untuk membandingkan dan kita perlu mencetaknya menggunakan `{}`, sehingga type T memerlukan `PartialOrd` dan `Display`. Ingat, ini berarti "hanya mengambil type yang sudah memiliki `PartialOrd` dan `Display`".

```rust
use std::fmt::Display;

fn gives_higher_i32<T: PartialOrd + Display>(one: T, two: T) {
    let higher = if one > two { one } else { two };
    println!("{} is higher.", higher);
}

fn main() {
    gives_higher_i32(8, 10);
}
```

Sekarang mari kita lihat `impl Trait`, yang mana mirip dengan generic. Alih-alih menggunakan type `T`, kita bisa membawa traitnya menggunakan type `impl Trait`. Kemudian ia akan mengambil type yang mengimplementasikan trait tersebut. Penggunaan keduanya benar-benar hampir sama:

```rust
fn prints_it(input: impl Into<String> + std::fmt::Display) { // Ambil apapun yang kembaliannya bisa diubah menjadi String dan memiliki Display
    println!("You can print many things, including {}", input);
}

fn main() {
    let name = "Tuon";
    let string_name = String::from("Tuon");
    prints_it(name);
    prints_it(string_name);
}
```

Bagian menariknya adalah kita bisa me-return `impl Trait`, dan ini memungkinkan kita untuk me-return closure karena function signatures mereka adalah trait. Anda bisa melihat ini pada beberapa signature di method tertentu. Contohnya, ini adalah signature dari method `.map()`:

```rust
fn map<B, F>(self, f: F) -> Map<Self, F>     // 🚧
    where
        Self: Sized,
        F: FnMut(Self::Item) -> B,
    {
        Map::new(self, f)
    }
```

`fn map<B, F>(self, f: F)` berarti bahwa ia mengambil dua type generic. `F` adalah function yang mengambil satu item dari container yang mengimplementasikan `.map()` dan `B` adalah type kembalian dari function tersebut. Kemudian setelah `where` kita melihat trait bound. ("Trait bound" berarti "ia haruslah memiliki trait tersebut".) Self haruslah bertype `Sized`, dan selanjutnya adalah closure signature. Ia haruslah bertype `FnMut`, dan menggunakan closurenya pada `Self::Item`, yang mana adalah iterator yang kita berikan. Kemudian ia me-return `B`.

Jadi, kita bisa melakukan sesuatu yang sama untuk me-return sebuah closure. Untuk me-return closure, gunakan `impl` dan kemudian closure signaturenya. Setelah Anda me-return hal itu, Anda bisa menggunakannya persis seperti function. Ini adalah contoh kecil dari function yang memberi Anda sebuah closure tergantung pada text yang Anda masukkan. Jika Anda memasukkan "double" atau "triple" ke dalamnya, maka ia akan mengalikannya dengan 2 atau 3, dan sebaliknya ia akan memberimu angka yang sama. Karena ini adalah closure, kita bisa melakukan apapun yang kita mau, termasuk mencetap outputnya.

```rust
fn returns_a_closure(input: &str) -> impl FnMut(i32) -> i32 {
    match input {
        "double" => |mut number| {
            number *= 2;
            println!("Doubling number. Now it is {}", number);
            number
        },
        "triple" => |mut number| {
            number *= 40;
            println!("Tripling number. Now it is {}", number);
            number
        },
        _ => |number| {
            println!("Sorry, it's the same: {}.", number);
            number
        },
    }
}

fn main() {
    let my_number = 10;

    // buat 3 buah closure
    let mut doubles = returns_a_closure("double");
    let mut triples = returns_a_closure("triple");
    let mut quadruples = returns_a_closure("quadruple");

    doubles(my_number);
    triples(my_number);
    quadruples(my_number);
}
```

Ini contoh yang agak lebih panjang. Bayangkan ada sebuah game di mana karakter Anda menghadapi monster yang lebih kuat di malam hari. Kita bisa membuat sebuah enum bernama `TimeOfDay` sebagai representasi waktu. Karakter Anda bernama Simon dan memiliki angka yang bernama `character_fear`, yang bertype `f64`. Nilainya akan meningkat di malam hari dan akan turun pada siang hari. Kita akan membuat function `change_fear` yang nantinya akan mengubah ketakutannya, namun juga melakukan hal lain, seperti melakukan print. Codenya seperti berikut:


```rust
enum TimeOfDay {
    Dawn,
    Day,
    Sunset,
    Night,
}

fn change_fear(input: TimeOfDay) -> impl FnMut(f64) -> f64 { // Function mengambil TimeOfDay sebagai parameternya dan ia mengembalikan closure.
                                                             // Kita menggunakan impl FnMut(64) -> f64 untuk mengatakan bahwa ia perlu mengubah
                                                             // nilainya dan juga mengembalikan type yang sama
    use TimeOfDay::*; // Kita hanya tinggal menulis Dawn, Day, Sunset, Night
                      // Daripada TimeOfDay::Dawn, TimeOfDay::Day, dst.
    match input {
        Dawn => |x| { // Ini adalah variabel character_fear yang akan kita berikan sebagai inputan
            println!("The morning sun has vanquished the horrible night. You no longer feel afraid.");
            println!("Your fear is now {}", x * 0.5);
            x * 0.5
        },
        Day => |x| {
            println!("What a nice day. Maybe put your feet up and rest a bit.");
            println!("Your fear is now {}", x * 0.2);
            x * 0.2
        },
        Sunset => |x| {
            println!("The sun is almost down! This is no good.");
            println!("Your fear is now {}", x * 1.4);
            x * 1.4
        },
        Night => |x| {
            println!("What a horrible night to have a curse.");
            println!("Your fear is now {}", x * 5.0);
            x * 5.0
        },
    }
}

fn main() {
    use TimeOfDay::*;
    let mut character_fear = 10.0; // Inisialisasi nilai ketakutan Simon dengan 10

    let mut daytime = change_fear(Day); // Buat empat buah closure disini, sehingga bisa dipanggil setiap kita ingin mengubah nilai ketakutan Simon.
    let mut sunset = change_fear(Sunset);
    let mut night = change_fear(Night);
    let mut morning = change_fear(Dawn);

    character_fear = daytime(character_fear); // Panggil closurenya pada variabel ketakutan Simon's. Ia akan memberikan pesan dan mengubah angkanya.
                                              // Pada umumnya, kita akan memiliki struct Character dan menggunakannya sebagai method,
                                              // seperti ini: character_fear.daytime()
    character_fear = sunset(character_fear);
    character_fear = night(character_fear);
    character_fear = morning(character_fear);
}
```

Hasilnya adalah:

```text
What a nice day. Maybe put your feet up and rest a bit.
Your fear is now 2
The sun is almost down! This is no good.
Your fear is now 2.8
What a horrible night to have a curse.
Your fear is now 14
The morning sun has vanquished the horrible night. You no longer feel afraid.
Your fear is now 7
```

## Arc

Anda ingat bahwa kita menggunakan `Rc` untuk memberi variabel lebih dari owner. Jika kita melakukan hal yang sama di dalam thread, kita memerlukan `Arc`. `Arc` singkatan dari "atomic reference counter". Atomic berarti bahwa ia menggunakan prosesor di komputer sehingga datanya hanya ditulis sekali setiap waktu. Ini penting karena jika dua thread menulis data pada waktu yang sama, Anda akan mendapatkan hasil yang salah. Contohnya, bayangkan jika Anda bisa melakukan ini di Rust :

```rust
// 🚧
let mut x = 10;

for i in 0..10 { // Thread 1
    x += 1
}
for i in 0..10 { // Thread 2
    x += 1
}
```

Jika Thread 1 dan Thread 2 berjalan bersamaan, mungkin hal seperti ini akan terjadi:

- Thread 1 melihat 10, maka ia menuliskan 11. Kemudian Thread 2 melihat 11, maka ia menulis 12. Tidak ada masalah sejauh ini.
- Thread 1 melihat 12. Pada waktu yang sama, Thread 2 melihat 12. Thread 1 menulis 13. Dan Thread 2 menulis 13. Sekarang kita memili 13, padahal seharusnya adalah 14. Ini adalah masalah yang cukup berbahaya.

`Arc` menggunakan prosesor untuk memastikan hal seperti ini tidak terjadi, jadi ini adlaah cara yang harus Anda gunakan di saat Anda menggunakan banyak thread. Anda tidak perlu memakai `Arc` jika hanya menggunakan satu thread saja, karena `Rc` sedikit lebih cepat dibandingkan dengan `Arc`.

Anda tidak bisa mengubah datanya hanya dengan menggunakan `Arc`. jadi Anda harus membungkus datanya menggunakan `Mutex`, dan membungkus `Mutex` dengan `Arc`.

Mari kita gunakan `Mutex` di dalam `Arc` untuk mengubah nilai dari sebuah angka. Pertama-tama, kita gunakn satu thread:

```rust
fn main() {

    let handle = std::thread::spawn(|| {
        println!("The thread is working!") // melakukan test terhadap thread
    });

    handle.join().unwrap(); // Buat threadnya menunggu sampai semuanya selesai
    println!("Exiting the program");
}
```

Sejauh ini, ia akan mencetak:

```text
The thread is working!
Exiting the program
```

Bagus. Sekarang kita masukkan loop `for` dengan iterasi `0..5`:

```rust
fn main() {

    let handle = std::thread::spawn(|| {
        for _ in 0..5 {
            println!("The thread is working!")
        }
    });

    handle.join().unwrap();
    println!("Exiting the program");
}
```

Sejauh ini programnya masih bekerja. Ini adalah hasilnya:

```text
The thread is working!
The thread is working!
The thread is working!
The thread is working!
The thread is working!
Exiting the program
```

Sekarang, kita buat satu thread lagi. Setiap thread Akan melakukan hal yang sama. Anda bisa melihat bahwa thread bekerja pada waktu yang bersamaan. Terkadang ia akan mengatakan `Thread 1 is working!` terlebih dahulu, namun dilain waktu, `Thread 2 is working!` yang akan dimunculkan terlebih dahulu. Inilah yang dinamakan sebagai **concurrency**, yang artinya "running together"/"dijalankan bersama-sama".

```rust
fn main() {

    let thread1 = std::thread::spawn(|| {
        for _ in 0..5 {
            println!("Thread 1 is working!")
        }
    });

    let thread2 = std::thread::spawn(|| {
        for _ in 0..5 {
            println!("Thread 2 is working!")
        }
    });

    thread1.join().unwrap();
    thread2.join().unwrap();
    println!("Exiting the program");
}
```

Hasilnya adalah:

```text
Thread 1 is working!
Thread 1 is working!
Thread 1 is working!
Thread 1 is working!
Thread 1 is working!
Thread 2 is working!
Thread 2 is working!
Thread 2 is working!
Thread 2 is working!
Thread 2 is working!
Exiting the program
```

Sekarang kita ingin mengubah nilai dari `my_number`. Typenya adalah `i32`. Kita akan menggunakan `Arc<Mutex<i32>>`: sebuah type `i32` yang bisa diubah, dan diproteksi menggunakan `Arc`.

```rust
// 🚧
let my_number = Arc::new(Mutex::new(0));
```

Sekarang setelah kita memiliki `my_number`, kita bisa melakukan clone. Setiap clone bisa menuju ke thread yang berbeda. Kita memiliki dua threads, jadinya kita akan membuat dua clone:

```rust
// 🚧
let my_number = Arc::new(Mutex::new(0));

let my_number1 = Arc::clone(&my_number); // Clone yang ini akan menuju ke Thread 1
let my_number2 = Arc::clone(&my_number); // Clone yang ini akan menuju ke Thread 2
```

Sekarang kita memiliki safe clone yang melekat ke `my_number`, kita bisa melakukan `move` (memindahkannya) ke dalam thread yang lain threads tanpa ada masalah apapun.

```rust
use std::sync::{Arc, Mutex};

fn main() {
    let my_number = Arc::new(Mutex::new(0));

    let my_number1 = Arc::clone(&my_number);
    let my_number2 = Arc::clone(&my_number);

    let thread1 = std::thread::spawn(move || { // Hanya clone yang akan dimasukkan ke Thread 1
        for _ in 0..10 {
            *my_number1.lock().unwrap() +=1; // kunci Mutexnya, ubah nilainya
        }
    });

    let thread2 = std::thread::spawn(move || { // Hanya clone yang akan dimasukkan ke Thread 2
        for _ in 0..10 {
            *my_number2.lock().unwrap() += 1;
        }
    });

    thread1.join().unwrap();
    thread2.join().unwrap();
    println!("Value is: {:?}", my_number);
    println!("Exiting the program");
}
```

Hasilnya adalah:

```text
Value is: Mutex { data: 20 }
Exiting the program
```

Dan, berhasil! :D

Kita bisa menggabungkan dua thread ke dalam sebuah loop `for`, dan membuat codenya menjadi lebih singkat.

Kita perlu untuk menyimpan handle (bertype `JoinHandles`) sehingga kita bisa menggunakan `.join()` untuk setiap handle yang berada di luar loop. Jika kita melakukan ini di dalam loop, ia akan menunggu thread pertama selesai sebelum menjalankan thread yang kedua.

```rust
use std::sync::{Arc, Mutex};

fn main() {
    let my_number = Arc::new(Mutex::new(0));
    let mut handle_vec = vec![]; // JoinHandles akan dimasukkan ke sini

    for _ in 0..2 { // lakukan dua kali
        let my_number_clone = Arc::clone(&my_number); // Buat clone sebelum memulai thread
        let handle = std::thread::spawn(move || { // Gunakan clonenya disini
            for _ in 0..10 {
                *my_number_clone.lock().unwrap() += 1;
            }
        });
        handle_vec.push(handle); // simpan handle, sehingga kita bisa menggunakan join pada handle di luar loop
                                 // jika kita tidak push handle ke dalam vec, ia akan hangus di sini
    }

    handle_vec.into_iter().for_each(|handle| handle.join().unwrap()); // gunakan method join untuk setiap handles
    println!("{:?}", my_number);
}
```

Dan hasil akhirnya adalah `Mutex { data: 20 }`.

Mungkin `Arc<Mutex<SomeType>>>` terlihat rumit di Rust, namun ia sangat sering digunakan di Rust, so it becomes natural. Selain itu, Anda selalu dapat menulis code Anda menjadi lebih rapi. Ini adalah code yang menggunakan lebih dari satu statement `use` dan dua buah function. Functionnya tidak melakukan sesuatu yang baru. Ia hanya memindahkan beberapa bagian code keluar dari `main()`. Anda bisa menuliskan ulang codenya seperti berikut ini apabila Anda merasa code sebelumnya sulit untuk dibaca.

```rust
use std::sync::{Arc, Mutex};
use std::thread::spawn; // sehingga kita cukup menuliskan spawn

fn make_arc(number: i32) -> Arc<Mutex<i32>> { // Function yang berguna untuk membuat Mutex di dalam Arc
    Arc::new(Mutex::new(number))
}

fn new_clone(input: &Arc<Mutex<i32>>) -> Arc<Mutex<i32>> { // Function untuk membuat arc clone
    Arc::clone(&input)
}

// Sekarang main() menjadi lebih mudah untuk dibaca
fn main() {
    let mut handle_vec = vec![]; // setiap handle akan masuk ke sini
    let my_number = make_arc(0);

    for _ in 0..2 {
        let my_number_clone = new_clone(&my_number);
        let handle = spawn(move || {
            for _ in 0..10 {
                let mut value_inside = my_number_clone.lock().unwrap();
                *value_inside += 1;
            }
        });
        handle_vec.push(handle);    // handle selesai, sehingga dimasukkan ke dalam vector
    }

    handle_vec.into_iter().for_each(|handle| handle.join().unwrap()); // buat setiap handle menunggu

    println!("{:?}", my_number);
}
```

## Channels

Channel adalah cara termudah untuk menggunakan banyak thread dan mengirimkannya ke satu tempat. Ia cukup popular karena ia sangatlah mudah untuk digunakan. Anda bisa membuat channel di Rust menggunakan `std::sync::mpsc`. `mpsc` adalah singkatan dari "multiple producer, single consumer", jadi "banyak thread mengirim ke satu tempat". Untuk menggunakan channel, Anda bisa menuliskan `channel()`. Ia akan membuat `Sender` dan `Receiver` yang mana terhubung satu sama lain. Anda bisa melihat ini pada function signaturenya:

```rust
// 🚧
pub fn channel<T>() -> (Sender<T>, Receiver<T>)
```

Jadi Anda harus menentukan satu nama untuk sender dan satu lagi untuk receiver. Biasanya Anda menuliskannya dengan format `let (sender, receiver) = channel();` untuk memulainya. Namun, karena ini adalah generic, Rust tidak mengetahui typenya jika hanya itu yang Anda tulis:

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel(); // ⚠️
}
```

Compiler mengatakan:

```text
error[E0282]: type annotations needed for `(std::sync::mpsc::Sender<T>, std::sync::mpsc::Receiver<T>)`
  --> src\main.rs:30:30
   |
30 |     let (sender, receiver) = channel();
   |         ------------------   ^^^^^^^ cannot infer type for type parameter `T` declared on the function `channel`
   |         |
   |         consider giving this pattern the explicit type `(std::sync::mpsc::Sender<T>, std::sync::mpsc::Receiver<T>)`, where
the type parameter `T` is specified
```

Ia menyarankan untuk menambahkan type untuk `Sender` dan `Receiver`. Anda bisa menuliskannya seperti ini jika Anda mau:

```rust
use std::sync::mpsc::{channel, Sender, Receiver}; // tambahkan Sender dan Receiver disini

fn main() {
    let (sender, receiver): (Sender<i32>, Receiver<i32>) = channel();
}
```

Tapi Anda tidak perlu menuliskannya seperti itu juga. Di saat kita mulai menggunakan `Sender` dan `Receiver`, Rust dapat menebak typenya.

Jadi, mari kita lihat cara termudah untuk menggunakan channel.

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel();

    sender.send(5);
    receiver.recv(); // recv = receive, bukan "rec v"
}
```

Sekarang compiler mengetahui typenya. `sender` adalah `Result<(), SendError<i32>>` dan `receiver` adalah `Result<i32, RecvError>`. Sehingga Anda bisa menggunakan `.unwrap()` untuk melihat apakah pengirimannya bekerja, atau menggunakan error handling yang lebih baik. Mari tambahkan `.unwrap()` dan juga `println!` untuk melihat hasilnya:

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel();

    sender.send(5).unwrap();
    println!("{}", receiver.recv().unwrap());
}
```

Hasilnya adalah `5`.

`channel` mirip seperti `Arc` karena Anda bisa melakukan clone dan mengirimkan clonenya ke thread yang lain. Mari kita membuat dua buah thread dan mengirim valuenya ke `receiver`. Code di bawah ini akan berjalan, tapi bukanlah seperti yang kita inginkan.

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel();
    let sender_clone = sender.clone();

    std::thread::spawn(move|| { // move sender ke dalam thread
        sender.send("Send a &str this time").unwrap();
    });

    std::thread::spawn(move|| { // move sender_clone ke dalam thread
        sender_clone.send("And here is another &str").unwrap();
    });

    println!("{}", receiver.recv().unwrap());
}
```

Dua thread mulai mengirim, dan kemudian kita lakukan `println!`. Hasilnya adalah `Send a &str this time` atau `And here is another &str`, tergantung dari thread mana yang terlebih dahulu selesai. Mari kita buat join handle Untuk membuatnya menunggu.

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel();
    let sender_clone = sender.clone();
    let mut handle_vec = vec![]; // Letakkan handlenya disini

    handle_vec.push(std::thread::spawn(move|| {  // push thread ke dalam vec
        sender.send("Send a &str this time").unwrap();
    }));

    handle_vec.push(std::thread::spawn(move|| {  // dan push thread yang ini juga ke dalam vec
        sender_clone.send("And here is another &str").unwrap();
    }));

    for _ in handle_vec { // sekarang handle_vec memiliki 2 item. Mari kita print hasilnya
        println!("{:?}", receiver.recv().unwrap());
    }
}
```

Hasil printnya adalah:

```text
"Send a &str this time"
"And here is another &str"
```

Sekarang, mari kita buat `results_vec` alih-alih langsung melakukan print.

```rust
use std::sync::mpsc::channel;

fn main() {
    let (sender, receiver) = channel();
    let sender_clone = sender.clone();
    let mut handle_vec = vec![];
    let mut results_vec = vec![];

    handle_vec.push(std::thread::spawn(move|| {
        sender.send("Send a &str this time").unwrap();
    }));

    handle_vec.push(std::thread::spawn(move|| {
        sender_clone.send("And here is another &str").unwrap();
    }));

    for _ in handle_vec {
        results_vec.push(receiver.recv().unwrap());
    }

    println!("{:?}", results_vec);
}
```

Sekarang, hasilnya berada di dalam `results_vec`: `["Send a &str this time", "And here is another &str"]`.

Sekarang, anggap saja bahwa kita memiliki banyak task untuk dilakukan, dan kita ingin menggunakan thread. Kita memiliki vec yang besar yang berisi 1 juta item/element, yang semua elementnya itu berisi angka 0. Kita ingin mengganti setiap 0 dengan 1. Kita ingin menggunakan 10 thread, dan setiap thread akan melakukan sepersepuluh (porsi 1/10) dari keseluruhan task tersebut. Kita akan membuat vec baru dan menggunakan `.extend()` untuk membagi tugasnya.

```rust
use std::sync::mpsc::channel;
use std::thread::spawn;

fn main() {
    let (sender, receiver) = channel();
    let hugevec = vec![0; 1_000_000];
    let mut newvec = vec![];
    let mut handle_vec = vec![];

    for i in 0..10 {
        let sender_clone = sender.clone();
        let mut work: Vec<u8> = Vec::with_capacity(hugevec.len() / 10); // vec baru untuk membagi-bagi tugasnya. Ukurannya adalah 1/10 dari ukuran hugevec
        work.extend(&hugevec[i*100_000..(i+1)*100_000]); // bagian pertama mengambil 0..100_000, selanjutnya mengambil 100_000..200_000, dst.
        let handle =spawn(move || { // membuatnya handlenya

            for number in work.iter_mut() { // lakukan tugasnya, yaitu mengubah 0 menjadi 1
                *number += 1;
            };
            sender_clone.send(work).unwrap(); // gunakan sender_clone untuk mengirim `work` ke receiver
        });
        handle_vec.push(handle);
    }
    
    for handle in handle_vec { // menunggu sampai semua threadnya selesai
        handle.join().unwrap();
    }
    
    while let Ok(results) = receiver.try_recv() {
        newvec.push(results); // push result dari receiver.recv() ke dalam newvec
    }

    // Sekarang kita menggunakan Vec<Vec<u8>>. Untuk menggabungkannya menjadi satu, kita bisa menggunakan .flatten()
    let newvec = newvec.into_iter().flatten().collect::<Vec<u8>>(); // sudah menjadi sebuah vec dengan 1_000_000 element yang bertype u8
    
    println!("{:?}, {:?}, total length: {}", // cetak beberapa angka untuk memastikan bahwa semuanya berubah menjadi 1
        &newvec[0..10], &newvec[newvec.len()-10..newvec.len()], newvec.len() // Dan tunjukkan pula bahwa panjangnya adalah 1_000_000 element
    );
    
    for number in newvec { // Dan beritahukan Rust bahwa ia akan panic jika ada satu angka yang bernilai 1
        if number != 1 {
            panic!();
        }
    }
}
```

## Reading Rust documentation

Adalah hal yang penting untuk mengetahui bagaimana cara membaca dokumentasi di Rust, sehingga Anda bisa memahami apa yang orang lain tuliskan. Berikut adalah beberapa hal yang penting untuk diketahui pada dokumantasi Rust:

### assert_eq!

Anda bisa melihat bahwa `assert_eq!` digunakan di saat melakukan testing. Anda masukkan dua buah item ke dalam function tersebut dan programnya akan panic jika keduanya tidak sama. Berikut adalah contoh sederhana di mana kita memerlukan bilangan genap agar programnya tidak panic.

```rust
fn main() {
    prints_number(56);
}

fn prints_number(input: i32) {
    assert_eq!(input % 2, 0); // angkanya harus sama.
                              // jika angka % 2 hasilnya bukan 0, ia akan panic
    println!("The number is not odd. It is {}", input);
}
```

Mungkin Anda tidak berencana untuk menggunakan `assert_eq!` pada code Anda, namun ia digunakan dimana pun di dokumentasi Rust. Ini dikarenakan dalam sebuah dokumen Anda akan membutuhkan banyak ruang untuk mem-`println!` semuanya. Juga, Anda akan membutuhkan `Display` atau `Debug` untuk sesuatu yang ingin Anda cetak. Itulah mengapa dokumentasi memiliki `assert_eq!` dimana-mana. Berikut adalah contoh [https://doc.rust-lang.org/std/vec/struct.Vec.html](https://doc.rust-lang.org/std/vec/struct.Vec.html) yang menunjukkan bagaimana cara menggunakan Vec:

```rust
fn main() {
    let mut vec = Vec::new();
    vec.push(1);
    vec.push(2);

    assert_eq!(vec.len(), 2);
    assert_eq!(vec[0], 1);

    assert_eq!(vec.pop(), Some(2));
    assert_eq!(vec.len(), 1);

    vec[0] = 7;
    assert_eq!(vec[0], 7);

    vec.extend([1, 2, 3].iter().copied());

    for x in &vec {
        println!("{}", x);
    }
    assert_eq!(vec, [7, 1, 2, 3]);
}
```

Pada contoh ini, Anda bisa menganggap `assert_eq!(a, b)` mengatakan "a sama dengan b". Sekarang lihat contoh yang telah disertai dengan komentar di sebelah kanannya. Komentar tersebut menunjukkan apa yang sebenarnya dimaksud oleh `assert_eq!()`.

```rust
fn main() {
    let mut vec = Vec::new();
    vec.push(1);
    vec.push(2);

    assert_eq!(vec.len(), 2); // "Panjang dari vec sama dengan 2"
    assert_eq!(vec[0], 1); // "vec[0] sama dengan 1"

    assert_eq!(vec.pop(), Some(2)); // "Di saat Anda menggunakan .pop(), itu sama dengan Some(2)"
    assert_eq!(vec.len(), 1); // "sekarang panjang vec sama dengan 1"

    vec[0] = 7;
    assert_eq!(vec[0], 7); // "Vec[0] sama dengan 7"

    vec.extend([1, 2, 3].iter().copied());

    for x in &vec {
        println!("{}", x);
    }
    assert_eq!(vec, [7, 1, 2, 3]); // "isi vec sama dengan [7, 1, 2, 3]"
}
```

### Searching

Top bar dari dokumentasi Rust adalah search bar. Ia akan mencarikan apapun yang Anda ketik. Di saat Anda men-scroll pagenya ke bawah, Anda tidak bisa melihat search barnya lagi, namun jika Anda menekan **s** pada keyboard, Anda akan kembali ke search bar tersebut. Sehingga menekan **s** di manapun memungkinkan Anda untuk langsung melakukan pencarian.

### [src] button

Biasanya code untuk method, struct, dll. tidak ditampilkan secara lengkap. Ini karena Anda biasanya tidak perlu untuk melihat source code lengkapnya untuk mengetahui cara kerjanya, dan code lengkapnya bisa saja membingungkan. Tapi, jika Anda ingin mempelajarinya lebih lanjut, Anda bisa klik pada [src] dan melihat semuanya. Misalnya, pada halaman tentang `String`, Anda bisa melihat signature untuk `.with_capacity()`:

```rust
// 🚧
pub fn with_capacity(capacity: usize) -> String
```

Okay, jadi Anda memasukkan angka ke dalamnya dan ia akan mengembalikan `String`. Ini mudah untuk dipahami, tapi mungkin saja kita penasaran dan ingin mempelajarinya lebih lanjut. Jika Anda klik pada [src], Anda bisa melihat ini:

```rust
// 🚧
pub fn with_capacity(capacity: usize) -> String {
    String { vec: Vec::with_capacity(capacity) }
}
```

Menarik! Kita bisa melihat bahwa String ternyata adalah semacam `Vec`. Dan sebenarnya `String` memanglah vector dari type `u8`, yang mana ini sangat menarik untuk diketahui. Anda tidak perlu mengetahui hal itu hanya untuk menggunakan method `with_capacity`, sehingga Anda hanya bisa melihatnya apabila anda meng-klik [src]. Jadi, meng-klik [src] adalah ide yang bagus apabila dokumen tidak memiliki cukup detail atau Anda ingin mempelajarinya lebih lanjut.

### Information on traits

Bagian terpenting dari dokumentasi mengenai trait adalah "Required Methods" pada bagian sebelah kiri. Jika Anda melihat Required Methods, itu mungkin artinya bahwa Anda harus menuliskan methodnya sendiri. Contohnya, untuk `Iterator` Anda perlu menuliskan method `.next()`. Dan untuk `From`, Anda perlu menuliskan method `.from()`. Tapi beberapa trait bisa diimplementasikan cukup dengan sebuah **attribute**, seperti yang kita lihat pada `#[derive(Debug)]`. `Debug` memerlukan method `.fmt()`, tapi biasanya Anda hanya memerlukan `#[derive(Debug)]`, kecuali jika Anda ingin menuliskannya sendiri. Inilah mengapa pada laman `std::fmt::Debug` mengatakan bahwa "Generally speaking, you should just derive a Debug implementation." (Secara umum, Anda sebaiknya men-derive (menurunkan) implementasi Debug)

## Attributes

Anda telah melihat code seperti `#[derive(Debug)]` sebelumnya: code seperti ini disebut sebagai *attribute*. Attribute adalah bagian kecil dari code yang meberikan informasi ke compiler. Attribute ini tidaklah mudah untuk dibuat, tetapi mereka sangat mudah untuk digunakan. Jika Anda menulis sebuah attribute dengan menggunakan `#`, maka itu akan mempengaruhi code di baris berikutnya. Tapi jika Anda menuliskannya dengan `#!` maka ia akan mempengaruhi segala sesuatu di lingkupnya sendiri.

Ini adalah beberapa attributes yang akan sering Anda lihat:

`#[allow(dead_code)]` dan `#[allow(unused_variables)]`. Jika Anda menulis code yang tidak Anda gunakan, Rust akan tetap melakukan compile Tapi ia akan memberitahukannya ke Anda. Sebagai contoh, di sini ada struct yang tidak memiliki apapun di dalamnya, dan sebuah variabel. Kita tidak menggunakan keduanya.

```rust
struct JustAStruct {}

fn main() {
    let some_char = 'ん';
}
```

Jika Anda menuliskan ini, Rust akan mengingatkan Anda bahwa Anda tidak menggunakan mereka:

```text
warning: unused variable: `some_char`
 --> src\main.rs:4:9
  |
4 |     let some_char = 'ん';
  |         ^^^^^^^^^ help: if this is intentional, prefix it with an underscore: `_some_char`
  |
  = note: `#[warn(unused_variables)]` on by default

warning: struct is never constructed: `JustAStruct`
 --> src\main.rs:1:8
  |
1 | struct JustAStruct {}
  |        ^^^^^^^^^^^
  |
  = note: `#[warn(dead_code)]` on by default
```

Kita tahu bahwa kita bisa menuliskan sebuah `_` (underscore) sebelum namanya untuk membuat compilernya tidak memberikan warning:

```rust
struct _JustAStruct {}

fn main() {
    let _some_char = 'ん';
}
```

Tapi Anda bisa menggunakan attribute. Anda akan melihat pesan dari code di atas, bahwa disarankan untuk menggunakan `#[warn(unused_variables)]` dan `#[warn(dead_code)]`. Di code tersebut, `JustAStruct` adalah dead code, dan `some_char` adalah unused variable (variabel yang tidak digunakan). Kebalikan dari `warn` adalah `allow`, sehingga kita bisa menuliskan ini dan compilernya tidak akan memberikan warning apapun:

```rust
#![allow(dead_code)]
#![allow(unused_variables)]

struct Struct1 {} // Buat lima buah struct
struct Struct2 {}
struct Struct3 {}
struct Struct4 {}
struct Struct5 {}

fn main() {
    let char1 = 'ん'; // dan empat buah variabel. Kita tidak menggunakan satupun dari variabel-variabel ini, tapi compiler tidak akan memberikan warning apapun
    let char2 = ';';
    let some_str = "I'm just a regular &str";
    let some_vec = vec!["I", "am", "just", "a", "vec"];
}
```

Tentu saja, berurusan dengan dead code dan unused variables sangatlah penting. Tapi terkadan Anda menginginkan compiler "untuk tetap diam" sementara waktu. Atau mungkin Anda perlu menunjukkan beberapa bagian code ke orang lain. Atau mungkin juga Anda ingin mengajarkan orang lain tentang Rust dan Anda tidak ingin membingungkan mereka dengan pesan yang ditampilkan oleh compiler.

`#[derive(TraitName)]` memungkinkan kita untuk men-derive (menurunkan) beberapa trait untuk struct dan enum yang kita buat. Attribute ini bekerja pada banyak trait-trait umum yang dapat diturunkan secara otomatis. Beberapa seperti `Display` tidak bisa diturunkan secara otomatis. Karena, untuk `Display`, Anda perlu memilih bagaimana cara menampilkannya:

```rust
// ⚠️
#[derive(Display)]
struct HoldsAString {
    the_string: String,
}

fn main() {
    let my_string = HoldsAString {
        the_string: "Here I am!".to_string(),
    };
}
```

Pesan errornya akan memberitahu hal tersebut.

```text
error: cannot find derive macro `Display` in this scope
 --> src\main.rs:2:10
  |
2 | #[derive(Display)]
  |
```

Tapi untuk trait-trait yang bisa secara otomatis diturunkan, Anda bisa memasukkannya sebanyak yang Anda mau. Mari kita berikan `HoldsAString` tujuh buah trait dalam satu baris (sekedar coba-coba), meskipun sebenarnya Anda hanya membutuhkan satu saja. :D

```rust
#[derive(Debug, PartialEq, Eq, Ord, PartialOrd, Hash, Clone)]
struct HoldsAString {
    the_string: String,
}

fn main() {
    let my_string = HoldsAString {
        the_string: "Here I am!".to_string(),
    };
    println!("{:?}", my_string);
}
```

Dan juga, Anda bisa membuat struct dengan type `Copy` jika (dan hanya jika) semua fieldnya adalah `Copy`. `HoldsAString` memiliki `String` yang mana ia bukanlah `Copy`, jadi Anda tidak bisa menggunakan `#[derive(Copy)]` untuk hal ini. Anda bisa membuat struct seperti di bawah ini:

```rust
#[derive(Clone, Copy)] // Anda juga membutuhkan Clone untuk menggunakan Copy
struct NumberAndBool {
    number: i32, // i32 adalah Copy
    true_or_false: bool // bool juga adalah Copy. Jadi, tidak ada masalah
}

fn does_nothing(input: NumberAndBool) {

}

fn main() {
    let number_and_bool = NumberAndBool {
        number: 8,
        true_or_false: true
    };

    does_nothing(number_and_bool);
    does_nothing(number_and_bool); // Jika ia bukanlah copy, maka ia akan error
}
```

`#[cfg()]` adalah konfigurasi dan memberitahukan ke compiler apakah Anda menjalankan codenya atau tidak. Anda biasanya melihatnya seperti ini: `#[cfg(test)]`. Anda akan menggunakannya di saat menulis function untuk keperluan testing, sehingga ia tahu untuk tidak menjalankannya kecuali Anda sedang melakukan testing. Anda juga bisa menuliskan testnya setelah menuliskan codenya, namun compiler tidak akan menjalankannya kecuali Anda menyuruh compiler untuk menjalankannya.

Satu contoh lain dalam penggunaan `cfg` adalah `#[cfg(target_os = "windows")]`. Dengan attribute itu, Anda bisa memberitahukan compiler untuk hanya menjalankan codenya di Windows, atau Linux, atau yang lainnya.

`#![no_std]` adalah attribute menarik yang memberitahukan Rust untuk tidak membawa standard library ke dalam code. Ini berarti, Anda tidak bisa menggunakan `Vec`, `String`, dan apapun yang ada di dalam standard library. Anda akan sering melihat code seperti ini di dalam code untuk perangkat-perangkat kecil yang tidak memiliki banyak memori atau ruang.

Anda bisa melihat attribute-attribute lainnya [disini](https://doc.rust-lang.org/reference/attributes.html).


## Box

`Box` adalah type yang cukup membantu di Rust. Jika kita menggunakan `Box`, kita bisa memasukkan type ke dalam heap, alih-alih menempatkannya pada stack. Untuk membuat `Box`, cukup tulisknya `Box::new()` dan letakkan item di dalamnya.

```rust
fn just_takes_a_variable<T>(item: T) {} // Ambil parameter dari type apapun dan lakukan drop.

fn main() {
    let my_number = 1; // Ini adalah i32
    just_takes_a_variable(my_number);
    just_takes_a_variable(my_number); // Tidak ada masalah menggunakan function ini dua kali, karena my_number adalah Copy

    let my_box = Box::new(1); // Ini adalah Box<i32>
    just_takes_a_variable(my_box.clone()); // Tanpa .clone(), function kedua akan menjadi error
    just_takes_a_variable(my_box); // karena Box bukanlah Copy
}
```

Di awal-awal, memang sulit untuk membayangkan dimana dan di kasus seperti apa kita akan menggunakannya, tapi nantinya Anda akan sering menggunakan ini di Rust. Anda ingat bahwa `&` digunakan pada `str` karena compiler tidak mengetahui ukuran dari `str`: karena panjangnya bisa berapa saja. Tapi reference `&` selalu memiliki panjang yang sama, sehingga compiler bisa menggunakannya. `Box` juga seperti itu. Juga, Anda bisa menggunakan `*` pada `Box` untuk mendapatkan valuenya, sama seperti `&`:

```rust
fn main() {
    let my_box = Box::new(1); // Ini adalah Box<i32>
    let an_integer = *my_box; // Ini adalah i32
    println!("{:?}", my_box);
    println!("{:?}", an_integer);
}
```

Inilah mengapa Box disebut sebagai "smart pointer", karena ia mirip dengan reference `&` (semacam pointer) namun bisa melakukan lebih banyak hal lainnya.

Anda juga bisa menggunakan Box untuk membuat struct dengan struct yang sama didalamnya. ini biasa disebut sebagai *rekursi*, yang berarti bahwa di dalam Struct A, mungkin ada field yang berisi Struct A pula. Terkadang Anda bisa menggunakan Box untuk membuat linked lists, meskipun list ini tidak begitu populer untuk digunakan di Rust. Jika Anda ingin membuat struct yang rekursif, Anda bisa menggunakan `Box`. Inilah yang terjadi apabila Anda membuat sebuah struct yang rekursif tanpa menggunakan `Box`:


```rust
struct List {
    item: Option<List>, // ⚠️
}
```

`List` di atas memiliki satu item, yang typenya adalah `Some<List>` (list lainnya), atau `None`. Karena kita bisa memilih `None`, ia tidak akan melakukan rekursi terus-menerus. Tetapi compiler tetap tidak mengetahui ukurannya:

```text
error[E0072]: recursive type `List` has infinite size
  --> src\main.rs:16:1
   |
16 | struct List {
   | ^^^^^^^^^^^ recursive type has infinite size
17 |     item: Option<List>,
   |     ------------------ recursive without indirection
   |
   = help: insert indirection (e.g., a `Box`, `Rc`, or `&`) at some point to make `List` representable
```

Anda bisa melihat, bahkan compiler menyarankan untuk mencoba menggunakan `Box`. Jadi, mari kita coba gunakan `Box`:

```rust
struct List {
    item: Option<Box<List>>,
}
fn main() {}
```

Sekarang compiler menerima `List` tersebut, karena ia berada di dalam `Box`, dan compiler mengetahui ukuran dari `Box`. Berikut kita coba code di bawah ini:

```rust
struct List {
    item: Option<Box<List>>,
}

impl List {
    fn new() -> List {
        List {
            item: Some(Box::new(List { item: None })),
        }
    }
}

fn main() {
    let mut my_list = List::new();
}
```

Meskipun kita tidak memasukkan data apapun, ia terlihat agak rumit, dan Rust tidak terlalu sering menggunakan pattern/pola sepert ini. Ini dikarenakan Rust memiliki aturan yang sangat ketat mengenai borrowing dan ownership, seperti yang dari awal kita ketahui. Tapi jika Anda ingin membuat list seperti ini (linked list), `Box` bisa digunakan untuk membuatnya.

`Box` juga memungkinkan Anda untuk menggunakan `std::mem::drop`, karena ia diletakkan di heap. Dan terkadang ini sangat membantu.

## Box around traits

`Box` sangatlah berguna untuk mengembalikan trait. Kita mengetahui bahwa kita bisa menulis traits pada generic functions seperti pada contoh di bawah ini:

```rust
use std::fmt::Display;

struct DoesntImplementDisplay {}

fn displays_it<T: Display>(input: T) {
    println!("{}", input);
}

fn main() {}
```

Function display_ithanya mengambil inputan yang memiliki trait `Display`, sehingga ia tidak bisa menerima struct `DoesntImplementDisplay`. Tapi ia bisa mengambil type lain seperti `String`.

Anda juga melihat bahwa kita bisa menggunakan `impl Trait` untuk mengembalikan trait lainnya atau juga closure. `Box` bisa digunakan dengan cara yang sama. Anda bisa menggunakan `Box`, karena jika tidak menggunakannya, compiler tidak akan tahu ukuran valuenya. Contoh ini menunjukkan bahwa sebuah trait bisa digunakan pada sesuatu dengan size berapa pun:

```rust
#![allow(dead_code)] // memberitahu compiler untuk tidak memberikan warning
use std::mem::size_of; // ini memberikan informasi tentang ukuran dari sebuah type

trait JustATrait {} // kita akan mengimplementasikan ini ke semuanya

enum EnumOfNumbers {
    I8(i8),
    AnotherI8(i8),
    OneMoreI8(i8),
}
impl JustATrait for EnumOfNumbers {}

struct StructOfNumbers {
    an_i8: i8,
    another_i8: i8,
    one_more_i8: i8,
}
impl JustATrait for StructOfNumbers {}

enum EnumOfOtherTypes {
    I8(i8),
    AnotherI8(i8),
    Collection(Vec<String>),
}
impl JustATrait for EnumOfOtherTypes {}

struct StructOfOtherTypes {
    an_i8: i8,
    another_i8: i8,
    a_collection: Vec<String>,
}
impl JustATrait for StructOfOtherTypes {}

struct ArrayAndI8 {
    array: [i8; 1000], // ukuran yang ini tentunya akan besar
    an_i8: i8,
    in_u8: u8,
}
impl JustATrait for ArrayAndI8 {}

fn main() {
    println!(
        "{}, {}, {}, {}, {}",
        size_of::<EnumOfNumbers>(),
        size_of::<StructOfNumbers>(),
        size_of::<EnumOfOtherTypes>(),
        size_of::<StructOfOtherTypes>(),
        size_of::<ArrayAndI8>(),
    );
}
```

Jika kita mencetak ukuran dari setiap enum dan struct di atas, kita mendapatkan `2, 3, 32, 32, 1002`. Sehingga jika Anda melakukan hal seperti dibawah ini, ia akan mencetak error:

```rust
// ⚠️
fn returns_just_a_trait() -> JustATrait {
    let some_enum = EnumOfNumbers::I8(8);
    some_enum
}
```

Compiler akan memberikan pesan:

```text
error[E0746]: return type cannot have an unboxed trait object
  --> src\main.rs:53:30
   |
53 | fn returns_just_a_trait() -> JustATrait {
   |                              ^^^^^^^^^^ doesn't have a size known at compile-time
```

Dan ini adalah benar, ukurannya adalah 2, 3, 32, 1002, atau berapapun. Sehingga kita masukkan ia ke dalam `Box`. Disini kita juga menambahkan keyword `dyn`. `dyn` adalah keyword yang menunjukkan bahwa kita berurusan dengan trait, bukan dengan struct atapun yang lainnya.

Sehingga Anda bisa menggunakan functionnya menjadi seperti ini:

```rust
// 🚧
fn returns_just_a_trait() -> Box<dyn JustATrait> {
    let some_enum = EnumOfNumbers::I8(8);
    Box::new(some_enum)
}
```

Dan sekarang codenya berjalan, karena yang berada di stack adalah `Box` dan kita mengetahui ukuran dari `Box`.

Anda akan sering melihat hal ini dalam bentuk `Box<dyn Error>`, karena terkadang Anda bisa memiliki lebih dari satu kemungkinan error.

Kita bisa membuat dua buah type error untuk menunjukkan ini. Untuk membuat type error (yang resmi disediakan oleh Rust), Anda perlu untuk mengimplementasikan `std::error::Error`. Hal ini sangatlah mudah: cukup tuliskan impl `std::error::Error {}`. Tapi error juga memerlukan `Debug` dan `Display` sehinga ia bisa memberikan informasi tentang problem yang muncul. `Debug` bisa digunakan dengan mudah menggunakan `#[derive(Debug)]`, namun `Display` memerlukan method `.fmt()`. Kita sudah pernah melakukannya sekali sebelumnya.

Codenya adalah seperti berikut:

```rust
use std::error::Error;
use std::fmt;

#[derive(Debug)]
struct ErrorOne;

impl Error for ErrorOne {} // ErrorOne adalah sebuah type error dengan trait Debug. Saatnya kita tambahkan trait Display:

impl fmt::Display for ErrorOne {
    fn fmt(&self, f: &mut fmt::Formatter) -> fmt::Result {
        write!(f, "You got the first error!") // tuliskan pesan errornya
    }
}


#[derive(Debug)] // Lakukan hal yang sama dengan ErrorTwo
struct ErrorTwo;

impl Error for ErrorTwo {}

impl fmt::Display for ErrorTwo {
    fn fmt(&self, f: &mut fmt::Formatter) -> fmt::Result {
        write!(f, "You got the second error!")
    }
}

// Buat sebuah function yang mengembalikan sebuah String atau sebuah error
fn returns_errors(input: u8) -> Result<String, Box<dyn Error>> { // Dengan Box<dyn Error>, Anda bisa mengembalikan apapun yang memiliki trait Error

    match input {
        0 => Err(Box::new(ErrorOne)), // Jangan lupa untuk meletakkan type errornya di dalam Box
        1 => Err(Box::new(ErrorTwo)),
        _ => Ok("Looks fine to me".to_string()), // Ini adalah type Result Ok
    }

}

fn main() {

    let vec_of_u8s = vec![0_u8, 1, 80]; // Tiga angka yang akan dicoba dengan function returns_errors

    for number in vec_of_u8s {
        match returns_errors(number) {
            Ok(input) => println!("{}", input),
            Err(message) => println!("{}", message),
        }
    }
}
```

Hasil cetaknya adalah:

```text
You got the first error!
You got the second error!
Looks fine to me
```

Jika kita tidak memiliki `Box<dyn Error>` dan menuliskannya, kita akan mendapatkan problem seperti berikut:

```rust
// ⚠️
fn returns_errors(input: u8) -> Result<String, Error> {
    match input {
        0 => Err(ErrorOne),
        1 => Err(ErrorTwo),
        _ => Ok("Looks fine to me".to_string()),
    }
}
```

Inilah pesan errornya:

```text
21  | fn returns_errors(input: u8) -> Result<String, Error> {
    |                                 ^^^^^^^^^^^^^^^^^^^^^ doesn't have a size known at compile-time
```

Error tidaklah mengejutkan, karena kita tahu bahwa sebuah trait bisa berjalan di banyak struktur, dan setiap dari mereka memiliki ukuran yang berbeda.

## Default and the builder pattern

Anda bisa mengimplementasikan trait `Default` untuk memberi value ke `struct` atau `enum` yang menurut Anda paling umum (paling sering) digunakan. Builder pattern berfungsi dengan baik dengan menggunakan `Default` ini, agar pengguna dengan mudah membuat perubahan saat mereka mau. Pertama-tama, kita lihat terlebih dahulu apa itu `Default`. Sebenarnya, hampir semua type di Rust telah memiliki `Default`. Contohnya: 0, "" (empty strings), `false`, dll.

```rust
fn main() {
    let default_i8: i8 = Default::default();
    let default_str: String = Default::default();
    let default_bool: bool = Default::default();

    println!("'{}', '{}', '{}'", default_i8, default_str, default_bool);
}
```

Hasil printnya adalah `'0', '', 'false'`.

Jadinya, `Default` mirip seperti function `new`, namun Anda tidak memberikan input apapun. Pertama, kita akan membuat sebuah `struct` yang belum mengimplementasikan `Default`. Ia memiliki function `new` yang mana kita gunakan untuk membuat karakter bernama Billy dengan beberapa status.

```rust
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
}

enum LifeState {
    Alive,
    Dead,
    NeverAlive,
    Uncertain
}

impl Character {
    fn new(name: String, age: u8, height: u32, weight: u32, alive: bool) -> Self {
        Self {
            name,
            age,
            height,
            weight,
            lifestate: if alive { LifeState::Alive } else { LifeState::Dead },
        }
    }
}

fn main() {
    let character_1 = Character::new("Billy".to_string(), 15, 170, 70, true);
}
```

Tapi, mungkin di dunia yang kita ciptakan ini kita menginginkan hampir semua karakternya bernama Billy, berusia 15, tinggi 170, berat 70, dan berstatus alive. Kita bisa mengimplementasikan `Default` sehingga kita bisa menuliskan `Character::default()`. Codenya terlihat seperti berikut:

```rust
#[derive(Debug)]
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
}

#[derive(Debug)]
enum LifeState {
    Alive,
    Dead,
    NeverAlive,
    Uncertain,
}

impl Character {
    fn new(name: String, age: u8, height: u32, weight: u32, alive: bool) -> Self {
        Self {
            name,
            age,
            height,
            weight,
            lifestate: if alive {
                LifeState::Alive
            } else {
                LifeState::Dead
            },
        }
    }
}

impl Default for Character {
    fn default() -> Self {
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
        }
    }
}

fn main() {
    let character_1 = Character::default();

    println!(
        "The character {:?} is {:?} years old.",
        character_1.name, character_1.age
    );
}
```

Hasil printnya adalah `The character "Billy" is 15 years old.` Jauh lebih mudah!

Sekarang kita bahas builder pattern. Nantinya, kita akan memiliki banyak Billy, jadinya kita akan tetap menyimpan default valuenya. Tetapi banyak karakter lain yang hanya sedikit berbeda statnya. Builder pattern memungkinkan kita untuk melakukan chain menggunakan method-method sederhana untuk mengubah satu value. Ini adalah salah satu method yang dibuat untuk `Character`:

```rust
fn height(mut self, height: u32) -> Self {    // 🚧
    self.height = height;
    self
}
```

Perhatikan pula, bahwa untuk melakukan hal ini kita memerlukan `mut self`. Kita sudah melihatnya sekali sebelumnya, dan ini bukanlah mutable reference (`&mut self`). Ia akan mengambil ownership dari `Self` dan dengan `mut` ia akan menjadi mutable, meskipun sebelumnya ia bukan mutable. Ini dikarenakan `.height()` memiliki full ownership (kepemilikan penuh) dan tidak ada siapapun yang bisa menyentuhnya, sehingga ia safe untuk menjadi mutable. Kemudian, ia hanya mengubah `self.height` dan mengembalikan `Self` (yang mana adalah `Character`).

Jadi, mari kita buat 3 buah builder method untuk Character. Ketiganya kurang lebih mirip satu sama lainnya:

```rust
fn height(mut self, height: u32) -> Self {     // 🚧
    self.height = height;
    self
}

fn weight(mut self, weight: u32) -> Self {
    self.weight = weight;
    self
}

fn name(mut self, name: &str) -> Self {
    self.name = name.to_string();
    self
}
```

Setiap satu method tersebut mengubah satu variabel dan mengembalikan `Self`: inilah apa yang kita lihat pada builder pattern. Jadi sekarang kita bisa menulis seperti ini untuk membuat karakter : `let character_1 = Character::default().height(180).weight(60).name("Bobby");`. Jika Anda sedang membuat library untuk digunakan oleh orang lain, ini akan memudahkan mereka. Ini sangatlah mudah untuk dipahami oleh pengguna lainnya, karena codenya bisa dipahami persis seperti kalimat berikut : "Berikan aku karakter default, tetapi dengan tinggi 180, berat 60, dan namanya adalah Bobby ." Sejauh ini, codenya akan menjadi seperti berikut:

```rust
#[derive(Debug)]
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
}

#[derive(Debug)]
enum LifeState {
    Alive,
    Dead,
    NeverAlive,
    Uncertain,
}

impl Character {
    fn new(name: String, age: u8, height: u32, weight: u32, alive: bool) -> Self {
        Self {
            name,
            age,
            height,
            weight,
            lifestate: if alive {
                LifeState::Alive
            } else {
                LifeState::Dead
            },
        }
    }

    fn height(mut self, height: u32) -> Self {
        self.height = height;
        self
    }

    fn weight(mut self, weight: u32) -> Self {
        self.weight = weight;
        self
    }

    fn name(mut self, name: &str) -> Self {
        self.name = name.to_string();
        self
    }
}

impl Default for Character {
    fn default() -> Self {
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
        }
    }
}

fn main() {
    let character_1 = Character::default().height(180).weight(60).name("Bobby");

    println!("{:?}", character_1);
}
```

Method terakhir yang ditambahkan biasanya disebut `.build()`. Method ini adalah semacam final check / pemeriksaan terakhir. Di saat Anda memberikan user sebuah method seperti `.height()`, Anda bisa memastikan bahwa mereka hanya memasukkan data yang bertype `u32()`, tapi bagaimana jika mereka memasukkan 5000 untuk tinggi karakternya? Tentu saja itu bukanlah hal yang baik untuk game yang Anda buat. Kita akan menggunakan method terakhir bernama `.build()` yang mengembalikan `Result`. Di dalam method tersebut, kita akan memeriksa apakah inputan dari user sudah benar, dan jika memang sudah benar, maka kita akan mengembalikan `Ok(Self)`.

Pertama, kita ubah terlebih dahulu method `.new()`. Kita tidak ingin user bebas membuat karakter apapun. Jadi kita akan memindahkan value dari `impl Default` ke `.new()`. Dan sekarang `.new()` tidak lagi mengambil inputan apapun.

```rust
    fn new() -> Self {    // 🚧
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
        }
    }
```

Ini berarti kita tidak lagi memerlukan `impl Default`, karena `.new()` telah memiliki semua default value. Jadinya kita bisa menghapus `impl Default`.

Sekarang codenya menjadi seperti ini:

```rust
#[derive(Debug)]
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
}

#[derive(Debug)]
enum LifeState {
    Alive,
    Dead,
    NeverAlive,
    Uncertain,
}

impl Character {
    fn new() -> Self {
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
        }
    }

    fn height(mut self, height: u32) -> Self {
        self.height = height;
        self
    }

    fn weight(mut self, weight: u32) -> Self {
        self.weight = weight;
        self
    }

    fn name(mut self, name: &str) -> Self {
        self.name = name.to_string();
        self
    }
}

fn main() {
    let character_1 = Character::new().height(180).weight(60).name("Bobby");

    println!("{:?}", character_1);
}
```

Tentunya hasilnya pun akan sama: `Character { name: "Bobby", age: 15, height: 180, weight: 60, lifestate: Alive }`.

Kita hampir siap untuk membuat method `.build()`, tapi masih ada satu problem: bagaimana caranya kita mendorong user untuk menggunakan method tersebut? Sekarang user bisa menuliskan `let x = Character::new().height(76767);` dan mendapatkan `Character`. Ada banyak cara untuk membuat (memaksa) user nantinya menggunakan method tersebut, dan mungkin Anda bisa membayangkan cara Anda sendiri. Tapi, disini kita akan menggunakan suatu cara, yaitu menambahkan value `can_use: bool` ke `Character`.

```rust
#[derive(Debug)]       // 🚧
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
    can_use: bool, // field ini digunakan untuk menyetel apakah user bisa menggunakan karakter tersebut atau tidak
}

\\ Cut other code

    fn new() -> Self {
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
            can_use: true, // .new() selalu mengembalikan Character, jadi secara default valuenya kita set ke true
        }
    }
```

Dan untuk method lainnya seperti `.height()`, kita akan setel `can_use` menjadi `false`. Hanya method `.build()` yang akan mengubah `can_use` kembali menjadi `true`, so now the user has to do a final check with `.build()`. We will make sure that `height` is not above 200 and `weight` is not above 300. Also, in our game there is a bad word called `smurf` that we don't want characters to use.

Beginilah method `.build()` yang kita buat:

```rust
fn build(mut self) -> Result<Character, String> {      // 🚧
    if self.height < 200 && self.weight < 300 && !self.name.to_lowercase().contains("smurf") {
        self.can_use = true;
        Ok(self)
    } else {
        Err("Could not create character. Characters must have:
1) Height below 200
2) Weight below 300
3) A name that is not Smurf (that is a bad word)"
            .to_string())
    }
}
```

`!self.name.to_lowercase().contains("smurf")` memastikan user tidak menuliskan sesuatu seperti "SMURF" atau "IamSmurf" . Ia membuat seluruh `String` tersebut menjadi lowercase (huruf kecil), dan memeriksa isinya menggunakan method `.contains()` (alih-alih menggunakan `==`). Dan `!` pada bagian awal tersebut adalah "not".

Jika semua inputannya sudah benar, maka kita set `can_use` menjadi `true`, dan berikan `Character` ke user dengan dibungkus di dalam `Ok`.

Sekarang code kita telah selesai. Kita akan membuat tiga karakter yang tidak bisa dibuat, dan satu karakter yang bisa dibuat. Maka, codenya sekarang menjadi seperti ini:

```rust
#[derive(Debug)]
struct Character {
    name: String,
    age: u8,
    height: u32,
    weight: u32,
    lifestate: LifeState,
    can_use: bool, // Ini adalah value yang baru
}

#[derive(Debug)]
enum LifeState {
    Alive,
    Dead,
    NeverAlive,
    Uncertain,
}

impl Character {
    fn new() -> Self {
        Self {
            name: "Billy".to_string(),
            age: 15,
            height: 170,
            weight: 70,
            lifestate: LifeState::Alive,
            can_use: true,  // .new() secara otomatis akan menciptakan character, sehingga kita set dengan true
        }
    }

    fn height(mut self, height: u32) -> Self {
        self.height = height;
        self.can_use = false; // Karena data default diubah melalui method .height(), user tidak bisa menggunakan karakter tersebut
        self
    }

    fn weight(mut self, weight: u32) -> Self {
        self.weight = weight;
        self.can_use = false;
        self
    }

    fn name(mut self, name: &str) -> Self {
        self.name = name.to_string();
        self.can_use = false;
        self
    }

    fn build(mut self) -> Result<Character, String> {
        if self.height < 200 && self.weight < 300 && !self.name.to_lowercase().contains("smurf") {
            self.can_use = true;   // Jika semua inputan sudah sesuai, maka akan diubah kembali menjadi true
            Ok(self)               // dan mengembalikan Character
        } else {
            Err("Could not create character. Characters must have:
1) Height below 200
2) Weight below 300
3) A name that is not Smurf (that is a bad word)"
                .to_string())
        }
    }
}

fn main() {
    let character_with_smurf = Character::new().name("Lol I am Smurf!!").build(); // Berisi kata "smurf" - not okay
    let character_too_tall = Character::new().height(400).build(); // Terlalu tinggi - not okay
    let character_too_heavy = Character::new().weight(500).build(); // Terlalu berat - not okay
    let okay_character = Character::new()
        .name("Billybrobby")
        .height(180)
        .weight(100)
        .build();   // Karakter yang ini bisa dibuat. Namanya bisa diterima, tinggi dan beratnya juga sesuai

    // Kembaliannya bukan Character, melainkan Result<Character, String>. Jadi kita masukkan karakter-karakter di atas ke dalam Vec sehingga kita bisa melihatnya:
    let character_vec = vec![character_with_smurf, character_too_tall, character_too_heavy, okay_character];

    for character in character_vec { // Sekarang kita akan mencetak karakternya jika Ok, dan mencetak error jika ia adalah Err
        match character {
            Ok(character_info) => println!("{:?}", character_info),
            Err(err_info) => println!("{}", err_info),
        }
        println!(); // Tambahkan jeda 1 baris
    }
}
```

Hasilnya adalah:

```text
Could not create character. Characters must have:
1) Height below 200
2) Weight below 300
3) A name that is not Smurf (that is a bad word)

Could not create character. Characters must have:
1) Height below 200
2) Weight below 300
3) A name that is not Smurf (that is a bad word)

Could not create character. Characters must have:
1) Height below 200
2) Weight below 300
3) A name that is not Smurf (that is a bad word)

Character { name: "Billybrobby", age: 15, height: 180, weight: 100, lifestate: Alive, can_use: true }
```



## Deref and DerefMut

`Deref` adalah trait yang memungkinkan Anda untuk menggunakan `*` untuk melakukan dereference. Kita tahu bahwa reference tidaklah sama dengan value:

```rust
// ⚠️
fn main() {
    let value = 7; // Ini bertype i32
    let reference = &7; // Ini bertype &i32
    println!("{}", value == reference);
}
```

Dan Rust bahkan tidak akan memberikan `false` karena keduanya tidak bisa dibandingkan.

```text
error[E0277]: can't compare `{integer}` with `&{integer}`
 --> src\main.rs:4:26
  |
4 |     println!("{}", value == reference);
  |                          ^^ no implementation for `{integer} == &{integer}`
```

Tentu saja, solusinya adalah menggunakan `*`. Sehingga programnya akan mencetak `true`:

```rust
fn main() {
    let value = 7;
    let reference = &7;
    println!("{}", value == *reference);
}
```


Sekarang mari kita bayangkan type struct sederhana yang hanya menampung angka. Ia akan menjadi mirip seperti `Box`, dan kita memiliki ide untuk menambahkan beberapa function tambahan untuk struct tersebut. Tapi jika kita hanya memberikannya angka, kita tidak bisa berbuat banyak pada struct tersebut.

Kita tidak bisa menggunakan `*` sebagaimana kita bisa melakukannya dengan `Box`:

```rust
// ⚠️
struct HoldsANumber(u8);

fn main() {
    let my_number = HoldsANumber(20);
    println!("{}", *my_number + 20);
}
```

Errornya adalah seperti berikut:

```text
error[E0614]: type `HoldsANumber` cannot be dereferenced
  --> src\main.rs:24:22
   |
24 |     println!("{:?}", *my_number + 20);
```

Tentu saja kita bisa melakukannya dengan cara seperti ini: `println!("{:?}", my_number.0 + 20);`. Kita hanya ingin menambahkan isi dari struct yang bertype `u8` dengan 20. Alangkah baiknya jika kita bisa langsung menjumlahkannya dengan menggunakan `*`. Pesan `cannot be dereferenced` memberikan kita petunjuk: kita perlu mengimplementasikan `Deref`. Sesuatu yang mengimplementasikan `Deref` terkadang disebut sebagai "smart pointer". Smart pointer bisa merujuk pada sebuah item, memiliki informasi tentang item tersebut, dan bisa menggunakan method-method yang tersedia untuk item tersebut. Karena untuk sekarang ini, kita bisa menggunakan `my_number.0`, yang mana bertype `u8`, namun kita tidak bisa berbuat banyak dengan `HoldsANumber`: satu-satunya yang kita miliki sejauh ini hanyalah `Debug`.

Fakta menariknya adalah: `String` adalah smart pointer dari `&str` dan `Vec` adalah smart pointer dari array (atau type lainnya). Jadi sebenarnya kita telah menggunakan smart pointer sejak awal.

Mengimplementasikan `Deref` tidaklah terlalu sulit dan contohnya di standard library cukup mudah. [Ini adalah contoh code dari standard library](https://doc.rust-lang.org/std/ops/trait.Deref.html):

```rust
use std::ops::Deref;

struct DerefExample<T> {
    value: T
}

impl<T> Deref for DerefExample<T> {
    type Target = T;

    fn deref(&self) -> &Self::Target {
        &self.value
    }
}

fn main() {
    let x = DerefExample { value: 'a' };
    assert_eq!('a', *x);
}
```


Jadi kita mengikuti contoh tersebut dan sekarang `Deref` kita menjadi seperti berikut:

```rust
// 🚧
impl Deref for HoldsANumber {
    type Target = u8; // Ingat, ini adalah "associated type": type yang ikut dijalankan bersama.
                      // Anda harus menggunakan type Target yang tepat = (type yang ingin Anda kembalikan)

    fn deref(&self) -> &Self::Target { // Rust menggunakan .deref() di saat Anda menggunakan *. Kita hanya mendefinisikan Target sebagai u8, Sehingga ia menjadi mudah untuk dipahami
        &self.0   // Kita memilih &self.0 karena ia adalah struct tuple. Di dalam struct yang bernama, ia akan menjadi seperti "&self.number"
    }
}
```

Dan sekarang kita bisa menjalankan ini dengan menggunakan `*`:

```rust
use std::ops::Deref;
#[derive(Debug)]
struct HoldsANumber(u8);

impl Deref for HoldsANumber {
    type Target = u8;

    fn deref(&self) -> &Self::Target {
        &self.0
    }
}

fn main() {
    let my_number = HoldsANumber(20);
    println!("{:?}", *my_number + 20);
}
```

Maka ia akan mencetak `40` dan kita tidak perlu untuk menulis `my_number.0`. Ini artinya kita mendapatkan method dari `u8` dan kita bisa menuliskan method kita sendiri untuk `HoldsANumber`. Kita akan menambahkan method sederhana buatan kita sendiri dan menggunakan method lainnya yang kita dapatkan dari `u8` yang bernama `.checked_sub()`. Method `.checked_sub()` adalah operasi pengurangan yang safe, yang mana kembaliannya adalah `Option`. Jika ia berhasil melakukan pengurangan, maka ia akan memberikan hasilnya terbungkus di dalam `Some`. Dan apabila ia tidak bisa melakukannya, maka ia akan mengembalikan `None`. Ingatlah,  `u8` tidak bisa negatif sehingga akan lebih safe untuk menggunakan `.checked_sub()` sehingga tidak menimbulkan panic.

```rust
use std::ops::Deref;

struct HoldsANumber(u8);

impl HoldsANumber {
    fn prints_the_number_times_two(&self) {
        println!("{}", self.0 * 2);
    }
}

impl Deref for HoldsANumber {
    type Target = u8;

    fn deref(&self) -> &Self::Target {
        &self.0
    }
}

fn main() {
    let my_number = HoldsANumber(20);
    println!("{:?}", my_number.checked_sub(100)); // Method yang ini diambil dari u8
    my_number.prints_the_number_times_two(); // Ini adalah method buatan kita sendiri
}
```

Hasilnya adalah:

```text
None
40
```

Kita juga bisa mengimplementasikan `DerefMut` sehingga kita bisa mengubah valuenya melalui `*`. Ini terlihat hampir sama. Anda membutuhkan `Deref` sebelum Anda bisa mengimplement `DerefMut`.

```rust
use std::ops::{Deref, DerefMut};

struct HoldsANumber(u8);

impl HoldsANumber {
    fn prints_the_number_times_two(&self) {
        println!("{}", self.0 * 2);
    }
}

impl Deref for HoldsANumber {
    type Target = u8;

    fn deref(&self) -> &Self::Target {
        &self.0
    }
}

impl DerefMut for HoldsANumber { // Anda tidak memerlukan type Target = u8; dibagian ini, karena ia sudah mengetahuinya. Thanks to Deref :D
    fn deref_mut(&mut self) -> &mut Self::Target { // Semua yang tertulis di sini adalah sama seperti yang tertulis di Deref. Yang berbeda adalah disini diselipkan mut dimana-mana
        &mut self.0
    }
}

fn main() {
    let mut my_number = HoldsANumber(20);
    *my_number = 30; // DerefMut memungkinkan kita untuk melakukan ini
    println!("{:?}", my_number.checked_sub(100));
    my_number.prints_the_number_times_two();
}
```

Jadi, kita bisa melihat bahwa `Deref` memberikan kemampuan lebih kepada type yang kita buat.

Ini juga alasan mengapa standard library mengatakan: `Deref should only be implemented for smart pointers to avoid confusion`. Hal itu dikarenakan Anda bisa melakukan suatu hal yang aneh menggunakan `Deref` untuk type yang rumit. Mari kita bayangkan contoh yang sangat membingungkan untuk memahami apa yang dimaksud oleh kalimat di standard library tersebut. Kita mulai dengan struct `Character` untuk sebuah game. `Character` baru memerlukan stats seperti intelligence dan strength. Jadi, inilah karakter pertama kita:

```rust
struct Character {
    name: String,
    strength: u8,
    dexterity: u8,
    health: u8,
    intelligence: u8,
    wisdom: u8,
    charm: u8,
    hit_points: i8,
    alignment: Alignment,
}

impl Character {
    fn new(
        name: String,
        strength: u8,
        dexterity: u8,
        health: u8,
        intelligence: u8,
        wisdom: u8,
        charm: u8,
        hit_points: i8,
        alignment: Alignment,
    ) -> Self {
        Self {
            name,
            strength,
            dexterity,
            health,
            intelligence,
            wisdom,
            charm,
            hit_points,
            alignment,
        }
    }
}

enum Alignment {
    Good,
    Neutral,
    Evil,
}

fn main() {
    let billy = Character::new("Billy".to_string(), 9, 8, 7, 10, 19, 19, 5, Alignment::Good);
}
```

Sekarang mari bayangkan bahwa kita ingin untuk menyimpan hit points karakter tersebut di dalam vec yang besar. Mungkin kita akan menempatkan data monster di sana juga, dan menyimpan semuanya bersama-sama menjadi satu. Karena `hit_points` adalah `i8`, kita implementasikan `Deref` sehingga kita bisa melakukan segala macam operasi matematika kepadanya. Tapi lihatlah dan perhatikan baik-baik, betapa anehnya codenya pada function `main()` sekarang ini:


```rust
use std::ops::Deref;

// Semua code yang ada di sini sama, kecuali setelah enum Alignment
struct Character {
    name: String,
    strength: u8,
    dexterity: u8,
    health: u8,
    intelligence: u8,
    wisdom: u8,
    charm: u8,
    hit_points: i8,
    alignment: Alignment,
}

impl Character {
    fn new(
        name: String,
        strength: u8,
        dexterity: u8,
        health: u8,
        intelligence: u8,
        wisdom: u8,
        charm: u8,
        hit_points: i8,
        alignment: Alignment,
    ) -> Self {
        Self {
            name,
            strength,
            dexterity,
            health,
            intelligence,
            wisdom,
            charm,
            hit_points,
            alignment,
        }
    }
}

enum Alignment {
    Good,
    Neutral,
    Evil,
}

impl Deref for Character { // impl Deref for Character. Sekarang kita bisa melakukan operasi matematis (untuk integer) yang kita inginkan!
    type Target = i8;

    fn deref(&self) -> &Self::Target {
        &self.hit_points
    }
}



fn main() {
    let billy = Character::new("Billy".to_string(), 9, 8, 7, 10, 19, 19, 5, Alignment::Good); // buat dua buah karakter, billy dan brandy
    let brandy = Character::new("Brandy".to_string(), 9, 8, 7, 10, 19, 19, 5, Alignment::Good);

    let mut hit_points_vec = vec![]; // masukkan data hit pointnya ke dalam vec ini
    hit_points_vec.push(*billy);     // Push *billy ?
    hit_points_vec.push(*brandy);    // Push *brandy ?

    println!("{:?}", hit_points_vec);
}
```

Ia akan mencetak `[5, 5]`. Code yang kita buat di atas sangatlah aneh untuk dibaca oleh orang lain. Kita bisa membaca `Deref` di bagian atas `main()` dan mengetahui bahwa `*billy` itu adalah `i8`, tapi bagaimana jika codenya menjadi sangat banyak? Mungkin code kita panjangnya adalah 2000 baris, dan tiba-tiba kita harus mencari tahu mengapa kita melakukan `.push()` kepada `*billy`. `Character` tentu lebih dari sekedar smart pointer untuk `i8`.

Tentu saja, tidaklah ilegal/haram/terlarang (atau apapun itu :D) untuk menuliskan `hit_points_vec.push(*billy)`, tapi itu membuat codenya jadi terlihat aneh. Mungkin dengan membuat method sederhana `.get_hp()` akan membuatnya jauh lebih baik. Atau juga bisa dengan cara membuat struct lain yang menyimpan karakter-karakter tersebut. Lalu kemudian Anda bisa mengiterasinya dan melakukan push setiap `hit_points` yang ada pada karakter tersebut. `Deref` memberikan Anda keleluasaan dan kemampuan lebih, tapi akan lebih baik untuk memastikan bahwa code yang kita buat itu logis untuk dipahami oleh kita sendiri dan orang lain.



## Crates and modules

Setiap kali kita menuliskan code di Rust, kita menuliskannya di dalam `crate`. `crate` adalah sebuah file, atau banyak file, yang berjalan bersama code kita. Di dalam file yang Anda tulis, Anda juga bisa membuat `mod`. `mod` adalah wadah untuk function, struct, dll. Dan ia digunakan untuk beberapa alasan:

- Menuliskan code: ia membantu Anda untuk memikirkan tentang gambara besar dari code yang ingin Anda buat. Ini menjadi sangat penting sebagaimana code Anda semakin membesar dan terus membesar.
- Membaca code: orang lain jadi bisa memahami code yang kita tuliskan dengan sangat mudah. Contohnya, nama `std::collections::HashMap` memberitahukan kita bahwa ia merupakan bagian dari `std` dan di dalam sebuah module bernama `collections`. Ini memberikan Anda petunjuk bahwa mungkin ada lebih banyak type collection di dalam `collections` yang bisa Anda coba.
- Privasi: semua dimulai dengan private. Hal ini memungkinkan Anda untuk mencegah pengguna menggunakan function secara langsung.

Untuk membuat `mod`, cukup tuliskan `mod` dan mulai code block dengan menggunakan `{}`. Kita akan membuat sebuah mod bernama `print_things` yang memiliki beberapa function yang berkaitan dengan cetak-mencetak.

```rust
mod print_things {
    use std::fmt::Display;

    fn prints_one_thing<T: Display>(input: T) { // Print apapun yang mengimplementasikan Display
        println!("{}", input)
    }
}

fn main() {}
```

Anda bisa melihat bahwa kita menuliskan `use std::fmt::Display;` di dalam `print_things`, karena ia adalah tempat yang terpisah. Jika Anda menuliskan `use std::fmt::Display;` di dalam `main()`, hal itu tidaklah berguna. Juga, sekarang ini kita tidak bisa memanggil function `prints_one_thing` dari function `main()`. Tanpa menggunakan keyword `pub` di depan `fn` ia akan tetap bersifat private. Mari kita coba memanggilnya tanpa `pub`. Ini adalah salah satu cara untuk menuliskannya:

```rust
// 🚧
fn main() {
    crate::print_things::prints_one_thing(6);
}
```

`crate` artinya "di dalam project ini", atau dengan bahasa yang lebih sederhana "di dalam file ini". Di dalam `crate` tersebut terdapat mod bernama `print_things`, dan kemudian ada function `prints_one_thing()`. Anda bisa menuliskannya seperti itu setiap saat, atau Anda bisa menuliskannnya menggunakan `use` mengimportnya. Sekarang kita bisa melihat error yang mengatakan bahwa ia bersifat private:

```rust
// ⚠️
mod print_things {
    use std::fmt::Display;

    fn prints_one_thing<T: Display>(input: T) {
        println!("{}", input)
    }
}

fn main() {
    use crate::print_things::prints_one_thing;

    prints_one_thing(6);
    prints_one_thing("Trying to print a string...".to_string());
}
```

Berikut adalah pesan errornya:

```text
error[E0603]: function `prints_one_thing` is private
  --> src\main.rs:10:30
   |
10 |     use crate::print_things::prints_one_thing;
   |                              ^^^^^^^^^^^^^^^^ private function
   |
note: the function `prints_one_thing` is defined here
  --> src\main.rs:4:5
   |
4  |     fn prints_one_thing<T: Display>(input: T) {
   |     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
```
Sangatlah mudah untuk memahami bahwa function `print_one_thing` adalah private. Pesan error tersebut juga menuliskan `src\main.rs:4:5` yaitu letak dimana functionnya berada. Ini cukup membantu karena Anda bisa menulis `mod` tidak hanya dalam satu file, tetapi bisa ditulisakn di banyak file juga.

Sekarang kita menuliskan `pub fn` menggantikan `fn`, dan codenya bekerja.

```rust
mod print_things {
    use std::fmt::Display;

    pub fn prints_one_thing<T: Display>(input: T) {
        println!("{}", input)
    }
}

fn main() {
    use crate::print_things::prints_one_thing;

    prints_one_thing(6);
    prints_one_thing("Trying to print a string...".to_string());
}
```

Hasil printnya adalah:

```text
6
Trying to print a string...
```

Bagaimana `pub` pada sebuah struct, enum, trait, ataua module? `pub` bekerja seperti ini untuk mereka masing-masing:

- `pub` pada sebuah struct: ia membbuat structnya menjadi public, namun item-item di dalamnya tidaklah public. Untuk membuat itemnya public, Anda perlu menuliskan `pub` pada setiap item tersebut.
- `pub` pada sebuah enum atau trait: semuanya menjadi public. Ini sangatlah masuk akal, karena trait adalah tentang memberikan perilaku yang sama pada sesuatu. Dan enum adalah tentang memilih salah satu dari banyaknya item, dan Anda perlu melihat semua pilihan tersebut untuk memilihnya.
- `pub` pada sebuah module: top level module semestinya akan menjadi `pub` karena jika ia bukanlah pub maka tidak ada yang bisa menyentuh apapun yang berada di dalamnya. Tapi module yang berada di dalam module memerlukan `pub` untuk menjadi public.

Jadi, mari kita tambahkan sebuah struct bernama `Billy` di dalam `print_things`. Struct ini hampir semua isinya akan menjadi bersifat public, namun tidak sepenuhnya. Struct sendiri adalah public, sehingga tentu saja kita nantinya akan menuliskan `pub struct Billy`. Di dalam strust tersebut terdapat field `name` dan `times_to_print`. `name` tidaklah public, karena kita hanya menginginkan user membuat struct dengan nama `"Billy".to_string()`. Tapi pengguna dapat memilih berapa kali untuk mencetak, sehingga `times_to_print` akan menjadi publik. Codenya terlihat seperti ini:

```rust
mod print_things {
    use std::fmt::{Display, Debug};

    #[derive(Debug)]
    pub struct Billy { // Billy adalah public
        name: String, // name adalah private.
        pub times_to_print: u32,
    }

    impl Billy {
        pub fn new(times_to_print: u32) -> Self { // Ini artinya user perlu untuk menggunakan new untuk membuat Billy. User hanya bisa mengubah angka dari times_to_print
            Self {
                name: "Billy".to_string(), // Kita pilihkan namanya - user tidak bisa memilihkannya
                times_to_print,
            }
        }

        pub fn print_billy(&self) { // function ini akan mencetak Billy
            for _ in 0..self.times_to_print {
                println!("{:?}", self.name);
            }
        }
    }

    pub fn prints_one_thing<T: Display>(input: T) {
        println!("{}", input)
    }
}

fn main() {
    use crate::print_things::*; // Sekarang kita menggunakan *. Ini mengimport semua dari print_things

    let my_billy = Billy::new(3);
    my_billy.print_billy();
}
```

This will print:

```text
"Billy"
"Billy"
"Billy"
```

Ah ya, tanda `*` yang digunakan untuk mengimport semuanya disebut sebagai "glob operator". Glob artinya "global", sehingga itu berarti seluruhnya/semuanya.

Di dalam sebuah `mod` Anda bisa membuat mod yang lain. Child mod (mod yang berada di dalam mod) selalu bisa menggunakan apapun yang ada di dalam parent mod. Anda bisa melihat ini pada contoh selanjutnya dimana kita memiliki `mod city` di dalam `mod province` di dalam `mod country`.

Anda bisa membayangkan strukturnya seperti ini: Meskipun Anda berada di sebuah negara, itu bukan berarti Anda berada di sebuah provinsinya. Dan bahkan jika Anda berada di sebuah provinsi, bukan berarti Anda di dalam kota. Tapi jika Anda berada di dalam kota, maka sudah dipastikan bahwa Anda berada di dalam suatu provinsi dan berada di dalam suatu negara.


```rust
mod country { // mod utama tidak memerlukan pub
    fn print_country(country: &str) { // Catatan: function ini tidaklah public
        println!("We are in the country of {}", country);
    }
    pub mod province { // buat mod ini menjadi mod public

        fn print_province(province: &str) { // Catatan: function ini bukanlah public
            println!("in the province of {}", province);
        }

        pub mod city { // buat mod ini menjadi mod public
            pub fn print_city(country: &str, province: &str, city: &str) {  // function ini bersifat public
                crate::country::print_country(country);
                crate::country::province::print_province(province);
                println!("in the city of {}", city);
            }
        }
    }
}

fn main() {
    crate::country::province::city::print_city("Canada", "New Brunswick", "Moncton");
}
```

Bagian menariknya adalah bahwa `print_city` bisa mengakses `print_province` dan `print_country`. Itu dikarenakan `mod city` berada di dalam mod-mod lainnya. Ia tidak memerlukan `pub` di depan `print_province` untuk menggunakannya. Dan ini sangatlah masuk akal: city tidaklah perlu melakukan apapun untuk berada di dalam province dan di dalam country.

Anda juga mungkin menyadari bahwa `crate::country::province::print_province(province);` sangatlah panjang. Di saat kita berada di dalam sebuah module, kita bisa menggunakan `super` untuk membawa item yang berada di level atas. Sebenarnya kata `super` sendiri artinya adalah "atas", seperti pada kata "superior" (peringkat atas). Pada contoh kita ini, kita hanya menggunakan functionnya sekali saja. Namun jika Anda menggunakannya lebih dari sekali, adalah ide yang bagus untuk mengimportnya. Dan tentu saja ini merupakan hal yang baik pula jika membuat codenya menjadi lebih mudah untuk dibaca, meskipun Anda hanya menggunakan fungsinya hanya satu kali saja. Code yang ada di bawah ini hampir sama, tapi sedikit lebih mudah dibaca:

```rust
mod country {
    fn print_country(country: &str) {
        println!("We are in the country of {}", country);
    }
    pub mod province {
        fn print_province(province: &str) {
            println!("in the province of {}", province);
        }

        pub mod city {
            use super::super::*; // gunakan semua yang berada di "above above": yang mana itu artinya adalah mod country
            use super::*;        // gunakan semua yang berada di "above": yang artinya itu adalah mod province

            pub fn print_city(country: &str, province: &str, city: &str) {
                print_country(country);
                print_province(province);
                println!("in the city of {}", city);
            }
        }
    }
}

fn main() {
    use crate::country::province::city::print_city; // bawa functionnya ke sini

    print_city("Canada", "New Brunswick", "Moncton");
    print_city("Korea", "Gyeonggi-do", "Gwangju"); // Dengan cara seperti ini, kita tidak perlu menuliskannya secara panjang jika ingin menggunakannya lagi
}
```



## Testing

Testing materi yang baik untuk dipelajari sekarang setelah memahami tentang module. Melakukan test pada code Anda sangatlah mudah di Rust, karena Anda bisa menuliskan testnya tepat setelah penulisan codenya.

Cara termudah untuk menuliskan test adalah menambahkan `#[test]` di atas functionnya. Seperti inilah contohnya:

```rust
#[test]
fn two_is_two() {
    assert_eq!(2, 2);
}
```

Tapi jika Anda mencoba menjalankannya di Playground, ia akan memberikan error: ``error[E0601]: `main` function not found in crate `playground``. Itu dikarenakan Anda tidak bisa menggunakan _Run_ untuk menjalankan testnya, semestinya Anda menggunakan _Test_. Dan juga, Anda tidak menggunakan function `main()` untuk testnya - testnya ditulis di luar `main()`. Untuk menjalankan ini di Playground, klik pada `···` disebelah _RUN_ dan ubah ke _Test_. Sekarang jika Anda mengkliknya, maka testnya akan dijalankan. (Jika Anda sudah menginstall Rust, Anda bisa menggunakan `cargo test` untuk melakukan ini)

Inilah outputnya:

```text
running 1 test
test two_is_two ... ok

test result: ok. 1 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out
```

Mari kita ubah `assert_eq!(2, 2)` menjadi `assert_eq!(2, 3)` dan kita lihat apa yang akan kita dapatkan. Jika testnya gagal, Anda akan mendapatkan informasi:

```text
running 1 test
test two_is_two ... FAILED

failures:

---- two_is_two stdout ----
thread 'two_is_two' panicked at 'assertion failed: `(left == right)`
  left: `2`,
 right: `3`', src/lib.rs:3:5
note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace


failures:
    two_is_two

test result: FAILED. 0 passed; 1 failed; 0 ignored; 0 measured; 0 filtered out
```

`assert_eq!(left, right)` adalah cara yang paling umum digunakan untuk melakukan test pada sebuah function di Rust. Jika ia tidak bekerja, ia akan menunjukkanvalue yang berbeda: left (kiri) bernilai 2, tapi right (kanan) bernilai 3.

Apa yang dimaksud dengan `RUST_BACKTRACE=1`? Ini adalah sebuah setting pada komputer untuk memberikan lebih banyak informasi tentang error tersebut. Playground juga memiliki fitur itu: klik pada `···` di sebelah `STABLE` dan set `Backtrace`nya menjadi `ENABLED`. Jika Anda melakukan itu, ia akan memberikanmu *sangat banyak* informasi:

```text
running 1 test
test two_is_two ... FAILED

failures:

---- two_is_two stdout ----
thread 'two_is_two' panicked at 'assertion failed: 2 == 3', src/lib.rs:3:5
stack backtrace:
   0: backtrace::backtrace::libunwind::trace
             at /cargo/registry/src/github.com-1ecc6299db9ec823/backtrace-0.3.46/src/backtrace/libunwind.rs:86
   1: backtrace::backtrace::trace_unsynchronized
             at /cargo/registry/src/github.com-1ecc6299db9ec823/backtrace-0.3.46/src/backtrace/mod.rs:66
   2: std::sys_common::backtrace::_print_fmt
             at src/libstd/sys_common/backtrace.rs:78
   3: <std::sys_common::backtrace::_print::DisplayBacktrace as core::fmt::Display>::fmt
             at src/libstd/sys_common/backtrace.rs:59
   4: core::fmt::write
             at src/libcore/fmt/mod.rs:1076
   5: std::io::Write::write_fmt
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/io/mod.rs:1537
   6: std::io::impls::<impl std::io::Write for alloc::boxed::Box<W>>::write_fmt
             at src/libstd/io/impls.rs:176
   7: std::sys_common::backtrace::_print
             at src/libstd/sys_common/backtrace.rs:62
   8: std::sys_common::backtrace::print
             at src/libstd/sys_common/backtrace.rs:49
   9: std::panicking::default_hook::{{closure}}
             at src/libstd/panicking.rs:198
  10: std::panicking::default_hook
             at src/libstd/panicking.rs:215
  11: std::panicking::rust_panic_with_hook
             at src/libstd/panicking.rs:486
  12: std::panicking::begin_panic
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/panicking.rs:410
  13: playground::two_is_two
             at src/lib.rs:3
  14: playground::two_is_two::{{closure}}
             at src/lib.rs:2
  15: core::ops::function::FnOnce::call_once
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libcore/ops/function.rs:232
  16: <alloc::boxed::Box<F> as core::ops::function::FnOnce<A>>::call_once
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/liballoc/boxed.rs:1076
  17: <std::panic::AssertUnwindSafe<F> as core::ops::function::FnOnce<()>>::call_once
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/panic.rs:318
  18: std::panicking::try::do_call
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/panicking.rs:297
  19: std::panicking::try
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/panicking.rs:274
  20: std::panic::catch_unwind
             at /rustc/c367798cfd3817ca6ae908ce675d1d99242af148/src/libstd/panic.rs:394
  21: test::run_test_in_process
             at src/libtest/lib.rs:541
  22: test::run_test::run_test_inner::{{closure}}
             at src/libtest/lib.rs:450
note: Some details are omitted, run with `RUST_BACKTRACE=full` for a verbose backtrace.


failures:
    two_is_two

test result: FAILED. 0 passed; 1 failed; 0 ignored; 0 measured; 0 filtered out
```

Anda tidak perlu menggunakan backtrace kecuali Anda benar-benar tidak menemukan dimana problemnya berasal. Tapi sebenarnya Anda tidak perlu untuk memahami semua yang tertulis di situ. Jika Anda tetap membaca hasil backtrace tersebut, Anda nantinya akan melihat line 13 dimana ia mengatakan `playground` - itu adalah bagian dimana backtrace berbicara tentang code kita. Sedangkan yang lainnya itu adalah tentang apa yang Rust lakukan pada library yang lain untuk menjalankan program kita. Namun dua line ini menunjukkan Anda bahwa ia melihat pada baris 2 dan baris 3 yang ada di playground, yang mana adalah petunjuk untuk memeriksa apakah ada kesalahan disana. Inilah bagian dari backtrace tersebut:

```text
  13: playground::two_is_two
             at src/lib.rs:3
  14: playground::two_is_two::{{closure}}
             at src/lib.rs:2
```

Edit: Rust memutakhirkan backtrace messagenya di awal 2021 untuk hanya menampilkan information yang paling penting. Dan sekarang ia jadi lebih mudah untuk dibaca:

```text
failures:

---- two_is_two stdout ----
thread 'two_is_two' panicked at 'assertion failed: `(left == right)`
  left: `2`,
 right: `3`', src/lib.rs:3:5
stack backtrace:
   0: rust_begin_unwind
             at /rustc/cb75ad5db02783e8b0222fee363c5f63f7e2cf5b/library/std/src/panicking.rs:493:5
   1: core::panicking::panic_fmt
             at /rustc/cb75ad5db02783e8b0222fee363c5f63f7e2cf5b/library/core/src/panicking.rs:92:14
   2: playground::two_is_two
             at ./src/lib.rs:3:5
   3: playground::two_is_two::{{closure}}
             at ./src/lib.rs:2:1
   4: core::ops::function::FnOnce::call_once
             at /rustc/cb75ad5db02783e8b0222fee363c5f63f7e2cf5b/library/core/src/ops/function.rs:227:5
   5: core::ops::function::FnOnce::call_once
             at /rustc/cb75ad5db02783e8b0222fee363c5f63f7e2cf5b/library/core/src/ops/function.rs:227:5
note: Some details are omitted, run with `RUST_BACKTRACE=full` for a verbose backtrace.


failures:
    two_is_two

test result: FAILED. 0 passed; 1 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.02s
```

Sekarang kita ubah lagi backtracenya menjadi dan kembali ke test yang biasanya. Sekarang kita akan menuliskan function lainnya, dan menggunakan function test untuk mengetestnya. Berikut adalah contohnya:

```rust
fn return_two() -> i8 {
    2
}
#[test]
fn it_returns_two() {
    assert_eq!(return_two(), 2);
}

fn return_six() -> i8 {
    4 + return_two()
}
#[test]
fn it_returns_six() {
    assert_eq!(return_six(), 6)
}
```

Dan ini adalah hasil dari menjalankan kedua function test tersebut:

```text
running 2 tests
test it_returns_two ... ok
test it_returns_six ... ok

test result: ok. 2 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out
```

Tentu saja ini tidak sulit untuk dipahami.

Biasanya kita ingin menempatkan test yang kita buat di module mereka sendiri. Untuk melakukan hal ini, gunakan keyword `mod` dan tambahkan `#[cfg(test)]` di atasnya (ingat: `cfg` berarti "configure"/"pengaturan"). Anda juga perlu untuk selalu menuliskan `#[test]` di bagian atas setiap test. Ini karena nantinya di saat Anda sudah menginstall Rust, Anda bisa melakukan testing yang jauh lebih rumit. Anda bisa mejalankan satu test saja, atau semuanya, atau hanya beberapa saja. Juga jangan lupa untuk menuliskan `use super::*;` karena module test perlu menggunakan function-function di atasnya. Sekarang codenya menjadi seperti ini:

```rust
fn return_two() -> i8 {
    2
}
fn return_six() -> i8 {
    4 + return_two()
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn it_returns_six() {
        assert_eq!(return_six(), 6)
    }
    #[test]
    fn it_returns_two() {
        assert_eq!(return_two(), 2);
    }
}
```

### Test-driven development

Anda mungkin pernah mendengar tentang "test-driven development" di saat membaca tentang Rust atau bahasa pemrograman yang lain. Itu adalah salah satu cara untuk menulis program, dan beberapa orang menyukainya, sedangkan beberapa lagi lebih menyukai cara lain. "Test-driven development" berarti "tulis testnya terlebih dahulu, lalu tulis codenya kemudian". Saat Anda menggunakan cara ini, Anda akan memiliki banyak test yang merepresentasikan apa yang Anda inginkan pada code yang Anda tuliskan nantinya. Kemudian Anda mulai menulis codenya, dan menjalankan testing untuk melihat apakah Anda melakukannya dengan benar. Kemudian test selalu ada untuk menunjukkan kepada Anda jika terjadi kesalahan saat Anda menambahkan dan menulis ulang kode Anda. Ini cukup mudah di Rust karena compiler memberikan banyak informasi tentang apa yang harus diperbaiki. Mari kita tulis contoh kecil test-driven development dan kita lihat seperti apa bentuk codenya.

Mari bayangkan sebuah calculator yang mengambil inputan dari user. Ia bisa melakukan penjumlahan (+) dan juga pengurangan (-). Jika user menuliskan "5 + 6" ia semestinya mengembalikan 11, jika user menuliskan "5 + 6 - 7" maka semestinya mengembalikan 4, dst. Jadi, kita akan mulai dengan function testnya. Anda juga bisa melihat bahwa nama function di dalam test biasanya lumayan panjang. Ini dikarenakan kita ingin menjalankan begitu banyak test, dan kita ingin mengetahui test yang mana saja yang gagal.

Kita akan bayangkan ada satu function bernama `math()` yang akan melakukan apapun. Ia akan mengembalikan `i32` (kita tidak menggunakan floats). Karena ia perlu mengembalikan sesuatu, kita hanya akan mengembalikan `6` setiap saat. Kemudian kita menuliskan tiga buah function test. Dan tentu saja semuanya akan gagal. Sekarang codenya terlihat seperti berikut:

```rust
fn math(input: &str) -> i32 {
    6
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn one_plus_one_is_two() {
        assert_eq!(math("1 + 1"), 2);
    }
    #[test]
    fn one_minus_two_is_minus_one() {
        assert_eq!(math("1 - 2"), -1);
    }
    #[test]
    fn one_minus_minus_one_is_two() {
        assert_eq!(math("1 - -1"), 2);
    }
}
```

Inilah informasi yang diberikan oleh test tersebut:

```text
running 3 tests
test tests::one_minus_minus_one_is_two ... FAILED
test tests::one_minus_two_is_minus_one ... FAILED
test tests::one_plus_one_is_two ... FAILED
```

dan juga informasi `failure` lainnya yang menuliskan tentang ``thread 'tests::one_plus_one_is_two' panicked at 'assertion failed: `(left == right)` ``. Kita tidak perlu menuliskan itu semua di sini.

Sekarang pikirkan tentang bagaimana membuat kalkulator. Kita akan menerima angka apapun, dan simbol `+-`. Kita juga memperbolehkan penggunaan spasi, selain dari itu, karakter apapun tidak diperbolehkan. Jadi, mari kita mulai dengan `const` yang berisi semua valuenya. Kemudian kita menggunakan `.chars()` untuk melakukan iterasi berdasarkan karakter, dan `.all()` untuk memastikan karakter yang dimasukkan merupakan bagian dari karakter yang boleh dimasukkan.

Kemudian kita akan menambahkan test yang harus memunculkan panic. Untuk melakukan itu, tambahkan attribute `#[should_panic]`: sekarang jika ia panic, testnya akan berhasil.

Sekarang codenya menjadi seperti ini:

```rust
const OKAY_CHARACTERS: &str = "1234567890+- "; // Jangan lupakan spasi pada bagian akhir dari kumpulan karakter

fn math(input: &str) -> i32 {
    if !input.chars().all(|character| OKAY_CHARACTERS.contains(character)) {
        panic!("Please only input numbers, +-, or spaces");
    }
    6 // kita tetap mengembalikan 6 untuk sekarang
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn one_plus_one_is_two() {
        assert_eq!(math("1 + 1"), 2);
    }
    #[test]
    fn one_minus_two_is_minus_one() {
        assert_eq!(math("1 - 2"), -1);
    }
    #[test]
    fn one_minus_minus_one_is_two() {
        assert_eq!(math("1 - -1"), 2);
    }

    #[test]
    #[should_panic]  // ini adalah test yang baru kita buat - seharusnya ia panic
    fn panics_when_characters_not_right() {
        math("7 + seven");
    }
}
```

Sekarang, di saat kita menjalankan testnya kita mendapatkan hasil berikut:

```text
running 4 tests
test tests::one_minus_two_is_minus_one ... FAILED
test tests::one_minus_minus_one_is_two ... FAILED
test tests::panics_when_characters_not_right ... ok
test tests::one_plus_one_is_two ... FAILED
```

Satu test berhasil! Function `math()` kita selanjutnya akan menerima inputan yang benar.


Langkah selanjutnya adalah menuliskan aplikasi kalkulator yang sebenarnya. Bagian menarik dari menuliskan testnya di awal adalah code dari programnya dibuat jauh setelahnya. Pertama, kita akan membuat aturan-aturan untuk kalkulator kita. Kita menginginkan aturan-aturan berikut:

- Semua space kosong akan dihapus. Ini mudah dilakukan menggunakan `.filter()`
- Inputnya harus diubah menjadi `Vec`. `+` tidak perlu dijadikan input. Namun di saat program melihat `+`, program harus tahu bahwa angka yang sebelumnya telah selesai. Contohnya, input `11+1` akan diperlakukan seperti ini: 1) Ada `1`, push angka tersebut ke string kosong. 2) Selanjutnya ada `1` lagi, push lagi ke dalam string (sekarang string tersebut adalah "11"). 3) Ada tanda `+`, program mengetahui bahwa string angka yang sebelumnya telah selesai. String tersebut dipush ke dalam vec, dan kemudian menghapus string tersebut.
- Program kalkulator harus menghitung jumlah dari tanda `-`. Jika jumlahnya ganjil (1, 3, 5...), artinya itu adalah sebuah pengurangan. Jika ia berjumlah genap (2, 4, 6...) maka itu adalah sebuah penjumlahan. Sehingga "1--9" harus memberikan 10, bukan -8.
- Program harus menghapus apapun setelah angka terakhir. `5+5+++++----` dibuat dari semua karakter yang berada di dalam `OKAY_CHARACTERS`, tapi ia haruslah mengembalikan `5+5`. Hal ini mudah dilakukan dengan menggunakan `.trim_end_matches()`, dimana ia bisa menghapus apapun (tuliskan karakter yang ingin dihapus) dibagian akhir `&str`.

(Ah ya, `.trim_end_matches()` dan `.trim_start_matches()` adalah method yang sama dengan `trim_right_matches()` dan `trim_left_matches()`. Namun kemudian orang-orang menyadari bahwa beberapa bahasa dituliskan dari kanan ke kiri (Persian, Hebrew, dll.) jadi kanan dan kiri dirasa kurang cocok untuk hal ini. Anda mungkin masih akan menemukan method lama tersebut di beberapa code, namun itu sebenarnya adalah code yang sama dengan yang versi end dan start.)

Jadinya kita akan membuat code yang kita buat lolos dari semua test. Setelah lolos dari test-test tersebut, kita bisa melakukan "refactor". Refactor artinya membuat codenya menjadi lebih baik, biasanya dengan menggunakan struct, enum dan juga method. Inilah code yang ditulis agar kita bisa melewati semua test tersebut:

```rust
const OKAY_CHARACTERS: &str = "1234567890+- ";

fn math(input: &str) -> i32 {
    if !input.chars().all(|character| OKAY_CHARACTERS.contains(character)) ||
       !input.chars().take(2).any(|character| character.is_numeric())
    {
        panic!("Please only input numbers, +-, or spaces.");
    }

    let input = input.trim_end_matches(|x| "+- ".contains(x)).chars().filter(|x| *x != ' ').collect::<String>(); // Hapus + dan - yang ada pada bagian akhir, dan juga semua spasi
    let mut result_vec = vec![]; // Hasilnya akan masuk ke vec ini
    let mut push_string = String::new(); // Ini adalah string yang kita push setiap saat. Kita akan tetap menggunakannya di dalam loop.
    for character in input.chars() {
        match character {
            '+' => {
                if !push_string.is_empty() { // Jika stringnya kosong, kita tidak menginginkan "" dipush ke dalam result_vec
                    result_vec.push(push_string.clone()); // Namun jika ia tidak kosong, semestinya ia adalah angka. Push ke dalam vec
                    push_string.clear(); // Kemudian clear stringnya
                }
            },
            '-' => { // Jika kita mendapatkan tanda -,
                if push_string.contains('-') || push_string.is_empty() { // periksa untuk mengetahui apakah ia kosong atau memiliki tanda -
                    push_string.push(character) // jika ya, maka push
                } else { // sebaliknya, ia tentunya berisi angka
                result_vec.push(push_string.clone()); // push angkanya ke dalam result_vec, clear dan kemudian push tanda -
                push_string.clear();
                push_string.push(character);
                }
            },
            number => { // number disini maksudnya adalah "apapun yang match". kita menggunakan nama "number disini"
                if push_string.contains('-') { // kita mungkin saja memiliki beberapa karakter - untuk di push pertama kali
                    result_vec.push(push_string.clone());
                    push_string.clear();
                    push_string.push(number);
                } else { // Namun jika kita tidak melakukannya, itu berarti kita bisa push numbernya ke dalam push_string
                    push_string.push(number);
                }
            },
        }
    }
    result_vec.push(push_string); // Push untuk terakhir kalinya setelah loopnya selesai. Kita tidak memerlukan .clone() karena kita tidak memerlukannya lagi

    let mut total = 0; // Sekarang saatnya kita melakukan operasi matematika. Mulai dengan total
    let mut adds = true; // true = tambah, false = kurang
    let mut math_iter = result_vec.into_iter();
    while let Some(entry) = math_iter.next() { // lakukan iter pada semua itemnya
        if entry.contains('-') { // Jika ia memiliki karakter - , periksa apakah jumlahnya genap atau ganjil
            if entry.chars().count() % 2 == 1 {
                adds = match adds {
                    true => false,
                    false => true
                };
                continue; // ke item yang selanjutnya
            } else {
                continue;
            }
        }
        if adds == true {
            total += entry.parse::<i32>().unwrap(); // Jika tidak ada '-', ia semestinya adalah sebuah angka. Jadinya kita aman untuk melakukan unwrap
        } else {
            total -= entry.parse::<i32>().unwrap();
            adds = true;  // Setelah melakukan pengurangan, ubah kembali addsnya menjadi true.
        }
    }
    total // Akhrnya, return totalnya
}
   /// Kita akan menambahkan beberapa test untuk memastikan program kita telah berjalan dengan benar

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn one_plus_one_is_two() {
        assert_eq!(math("1 + 1"), 2);
    }
    #[test]
    fn one_minus_two_is_minus_one() {
        assert_eq!(math("1 - 2"), -1);
    }
    #[test]
    fn one_minus_minus_one_is_two() {
        assert_eq!(math("1 - -1"), 2);
    }
    #[test]
    fn nine_plus_nine_minus_nine_minus_nine_is_zero() {
        assert_eq!(math("9+9-9-9"), 0); // Ini adalah test yang baru
    }
    #[test]
    fn eight_minus_nine_plus_nine_is_eight_even_with_characters_on_the_end() {
        assert_eq!(math("8  - 9     +9-----+++++"), 8); // Ini adalah test yang baru
    }
    #[test]
    #[should_panic]
    fn panics_when_characters_not_right() {
        math("7 + seven");
    }
}
```

Dan sekarang semua testnya telah terlewati!

```text
running 6 tests
test tests::one_minus_minus_one_is_two ... ok
test tests::nine_plus_nine_minus_nine_minus_nine_is_zero ... ok
test tests::one_minus_two_is_minus_one ... ok
test tests::eight_minus_nine_plus_nine_is_eight_even_with_characters_on_the_end ... ok
test tests::one_plus_one_is_two ... ok
test tests::panics_when_characters_not_right ... ok

test result: ok. 6 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out
```

Anda bisa melihat bahwa ada proses "bolak-balik" di saat kita melakukan test-driven development. Kira-kira seperti ini:

- Pertama, kita tuliskan semua test yang terbersit di pikiran kita.
- Kemudian kita mulai menuliskan codenya.
- Di saat proses penulisan code, gita mendapatkan ide untuk menambahkan test-test baru.
- Anda tambahkan lagi testnya, dan testnya terus bertambah seiring codenya bertambah. Semakin banyak test yang Anda miliki, semakin sering code Anda diperiksa.

Tentu saja, test tidak memeriksa semuanya dan salah jika kita berpikir bahwa "lolos semua test = codenya sempurna". Tapi test sangatlah berguna di saat code kita mengalami perubahan. Apabila Anda mengubah codenya kemudian dan menjalankan testnya, jika ada salah satunya yang tidak bekerja maka kita akan tahu yang mana yang semestinya kita perbaiki.

Sekarang kita bisa melakukan refactor codenya sedikit demi sedikit. Salah satu cara yang baik untuk melakukan refactor adalah menggunakan clippy. Jika Anda menginstall Rust maka Anda bisa menuliskan perintah `cargo clippy`, dan jika Anda menggunakan Playground maka klik pada `TOOLS` dan pilih Clippy. Clippy melihat pada code yang kita buat dan memberikan kita tips untuk membuat codenya menjadi lebih sederhana. Code yang kita buat tidak memiliki kesalahan, namun kita bisa membuatnya menjadi lebih baik.

Clippy memberi tahu kita tentang dua hal:

```text
warning: this loop could be written as a `for` loop
  --> src/lib.rs:44:5
   |
44 |     while let Some(entry) = math_iter.next() { // Iter through the items
   |     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ help: try: `for entry in math_iter`
   |
   = note: `#[warn(clippy::while_let_on_iterator)]` on by default
   = help: for further information visit https://rust-lang.github.io/rust-clippy/master/index.html#while_let_on_iterator

warning: equality checks against true are unnecessary
  --> src/lib.rs:53:12
   |
53 |         if adds == true {
   |            ^^^^^^^^^^^^ help: try simplifying it as shown: `adds`
   |
   = note: `#[warn(clippy::bool_comparison)]` on by default
   = help: for further information visit https://rust-lang.github.io/rust-clippy/master/index.html#bool_comparison
```

Ini benar: `for entry in math_iter` lebih simple daripada `while let Some(entry) = math_iter.next()`. Dan sebuah loop `for` sebenarnya adalah sebuah iterator sehingga kita tidak punya alasan untuk menuliskan `.iter()`. Terima kasih, clippy! :D Dan juga kita tidak perlu untuk membuat `math_iter`: kita hanya perlu menuliskan `for entry in result_vec`.

Sekarang kita mulai refactor yang sesungguhnya. Alih-alih menggunakan variabel yang terpisah, kita akan membuat struct `Calculator`. Ia akan memiliki semua variabel yang kita gunakan. Kita akan mengubah dua nama untuk membuatnya menjadi jelas. `result_vec` akan menjadi `results`, dan `push_string` akan menjadi `current_input` (current berarti "sekarang"). Dan sejauh ini ia hanya memiliki satu method: new.

```rust
// 🚧
#[derive(Clone)]
struct Calculator {
    results: Vec<String>,
    current_input: String,
    total: i32,
    adds: bool,
}

impl Calculator {
    fn new() -> Self {
        Self {
            results: vec![],
            current_input: String::new(),
            total: 0,
            adds: true,
        }
    }
}
```

Sekarang code kita menjadi agak panjang, namun menjadi lebih mudah untuk dibaca. Contohnya, `if adds` sekarang menjadi `if calculator.adds`, yang mana menjadi seperti membaca bahasa Inggris pada umumnya. Codenya menjadi seperti berikut:

```rust
#[derive(Clone)]
struct Calculator {
    results: Vec<String>,
    current_input: String,
    total: i32,
    adds: bool,
}

impl Calculator {
    fn new() -> Self {
        Self {
            results: vec![],
            current_input: String::new(),
            total: 0,
            adds: true,
        }
    }
}

const OKAY_CHARACTERS: &str = "1234567890+- ";

fn math(input: &str) -> i32 {
    if !input.chars().all(|character| OKAY_CHARACTERS.contains(character)) ||
       !input.chars().take(2).any(|character| character.is_numeric()) {
        panic!("Please only input numbers, +-, or spaces");
    }

    let input = input.trim_end_matches(|x| "+- ".contains(x)).chars().filter(|x| *x != ' ').collect::<String>();
    let mut calculator = Calculator::new();

    for character in input.chars() {
        match character {
            '+' => {
                if !calculator.current_input.is_empty() {
                    calculator.results.push(calculator.current_input.clone());
                    calculator.current_input.clear();
                }
            },
            '-' => {
                if calculator.current_input.contains('-') || calculator.current_input.is_empty() {
                    calculator.current_input.push(character)
                } else {
                calculator.results.push(calculator.current_input.clone());
                calculator.current_input.clear();
                calculator.current_input.push(character);
                }
            },
            number => {
                if calculator.current_input.contains('-') {
                    calculator.results.push(calculator.current_input.clone());
                    calculator.current_input.clear();
                    calculator.current_input.push(number);
                } else {
                    calculator.current_input.push(number);
                }
            },
        }
    }
    calculator.results.push(calculator.current_input);

    for entry in calculator.results {
        if entry.contains('-') {
            if entry.chars().count() % 2 == 1 {
                calculator.adds = match calculator.adds {
                    true => false,
                    false => true
                };
                continue;
            } else {
                continue;
            }
        }
        if calculator.adds {
            calculator.total += entry.parse::<i32>().unwrap();
        } else {
            calculator.total -= entry.parse::<i32>().unwrap();
            calculator.adds = true;
        }
    }
    calculator.total
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn one_plus_one_is_two() {
        assert_eq!(math("1 + 1"), 2);
    }
    #[test]
    fn one_minus_two_is_minus_one() {
        assert_eq!(math("1 - 2"), -1);
    }
    #[test]
    fn one_minus_minus_one_is_two() {
        assert_eq!(math("1 - -1"), 2);
    }
    #[test]
    fn nine_plus_nine_minus_nine_minus_nine_is_zero() {
        assert_eq!(math("9+9-9-9"), 0);
    }
    #[test]
    fn eight_minus_nine_plus_nine_is_eight_even_with_characters_on_the_end() {
        assert_eq!(math("8  - 9     +9-----+++++"), 8);
    }
    #[test]
    #[should_panic]
    fn panics_when_characters_not_right() {
        math("7 + seven");
    }
}
```

Akhirnya kita menambahkan 2 method baru. Yang satu bernama `.clear()` dan melakukan clear terhadap `current_input()`. Yang satu lagi bernama `push_char()` dan melakukan push terhadap input ke dalam `current_input()`. Inilah code yang telah sepenuhnya direfactor:

```rust
#[derive(Clone)]
struct Calculator {
    results: Vec<String>,
    current_input: String,
    total: i32,
    adds: bool,
}

impl Calculator {
    fn new() -> Self {
        Self {
            results: vec![],
            current_input: String::new(),
            total: 0,
            adds: true,
        }
    }

    fn clear(&mut self) {
        self.current_input.clear();
    }

    fn push_char(&mut self, character: char) {
        self.current_input.push(character);
    }
}

const OKAY_CHARACTERS: &str = "1234567890+- ";

fn math(input: &str) -> i32 {
    if !input.chars().all(|character| OKAY_CHARACTERS.contains(character)) ||
       !input.chars().take(2).any(|character| character.is_numeric()) {
        panic!("Please only input numbers, +-, or spaces");
    }

    let input = input.trim_end_matches(|x| "+- ".contains(x)).chars().filter(|x| *x != ' ').collect::<String>();
    let mut calculator = Calculator::new();

    for character in input.chars() {
        match character {
            '+' => {
                if !calculator.current_input.is_empty() {
                    calculator.results.push(calculator.current_input.clone());
                    calculator.clear();
                }
            },
            '-' => {
                if calculator.current_input.contains('-') || calculator.current_input.is_empty() {
                    calculator.push_char(character)
                } else {
                calculator.results.push(calculator.current_input.clone());
                calculator.clear();
                calculator.push_char(character);
                }
            },
            number => {
                if calculator.current_input.contains('-') {
                    calculator.results.push(calculator.current_input.clone());
                    calculator.clear();
                    calculator.push_char(number);
                } else {
                    calculator.push_char(number);
                }
            },
        }
    }
    calculator.results.push(calculator.current_input);

    for entry in calculator.results {
        if entry.contains('-') {
            if entry.chars().count() % 2 == 1 {
                calculator.adds = match calculator.adds {
                    true => false,
                    false => true
                };
                continue;
            } else {
                continue;
            }
        }
        if calculator.adds {
            calculator.total += entry.parse::<i32>().unwrap();
        } else {
            calculator.total -= entry.parse::<i32>().unwrap();
            calculator.adds = true;
        }
    }
    calculator.total
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn one_plus_one_is_two() {
        assert_eq!(math("1 + 1"), 2);
    }
    #[test]
    fn one_minus_two_is_minus_one() {
        assert_eq!(math("1 - 2"), -1);
    }
    #[test]
    fn one_minus_minus_one_is_two() {
        assert_eq!(math("1 - -1"), 2);
    }
    #[test]
    fn nine_plus_nine_minus_nine_minus_nine_is_zero() {
        assert_eq!(math("9+9-9-9"), 0);
    }
    #[test]
    fn eight_minus_nine_plus_nine_is_eight_even_with_characters_on_the_end() {
        assert_eq!(math("8  - 9     +9-----+++++"), 8);
    }
    #[test]
    #[should_panic]
    fn panics_when_characters_not_right() {
        math("7 + seven");
    }
}
```

Mungkin ini cukup baik untuk sekarang ini. Kita bisa menuliskan lebih banyak method, namun baris code seperti `calculator.results.push(calculator.current_input.clone());` sudah sangat cukup jelas. Refactor yang baik adalah jika Anda masih bisa dengan mudah membaca codenya setelah Anda telah selesai merefactornya. Anda tentunya tidak ingin melakukan refactor hanya untuk membuat codenya terlihat pendek: contohnya, `clc.clr()` lebih buruk dibanding `calculator.clear()`.



## External crates

External crate artinya adalah "crate yang dibuat oleh orang lain".

Pada bagian ini, Anda *hampir* perlu menginstall Rust, namun kita masih bisa cukup menggunakan Playground. Sekarang kita akan mempelajari bagaimana cara melakukan import crates yang dibuat oleh orang lain. Ini sangatlah penting di Rust karena dua alasan:

- Sangatlah mudah untuk mengimport crates, dan
- Standard library yang dimiliki oleh Rust sangatlah kecil.

Artinya, adalah normal di Rust untuk memasukkan sebuah external crate untuk menggunakan beberapa basic function. Jika kita bisa dengan mudah menggunakan external crates, maka Anda bisa memilih crate yang paling terbaik. Mungkin seseorang akan membuat sebuah crate untuk sebuah function, dan kemudian ada orang lain yang membuat function serupa yang lebih baik.

Di buku ini, kita hanya akan mengulas crates yang paling populer, crates yang mana semua orang yang menggunakan Rust tahu.

Untuk mulai mempelajari external crates, kita akan mulai dengan crate yang paling umum digunakan: `rand`.

### rand

Apakah Anda menyadari sejauh ini kita belum ada menggunakan angka random? Itu dikarenakan angka random tidak berada di dalam standard library. Tapi ada banyak crate yang "hampir menjadi standard library" karena semua orang menggunakannya. Bagaimanapun, adalah hal yang mudah untuk memasukkan dan menggunakan sebuah crate. Jika Anda memiliki Rust pada komputer Anda, ada file yang bernama `Cargo.toml` yang menyimpan informasi tentang crate. File `Cargo.toml` terlihat seperti ini pada awalnya:

```text
[package]
name = "rust_book"
version = "0.1.0"
authors = ["David MacLeod"]
edition = "2018"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]
```

Sekarang, jika Anda ingin menambahkan crate `rand`, cari cratenya di `crates.io`, yang mana adalah tempat semua crate dipost. Ia akan mengarahkanmu ke `https://crates.io/crates/rand`. Dan di saat Anda mengkliknya, Anda bisa melihat screen yang bertuliskan `Cargo.toml   rand = "0.7.3"`. Yang perlu Anda lakukan adalah menambahkannya setelah [dependencies], seperti ini:

```text
[package]
name = "rust_book"
version = "0.1.0"
authors = ["David MacLeod"]
edition = "2018"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]
rand = "0.7.3"
```

Dan Cargo akan melakukan sisanya untuk Anda. Kemudian Anda bisa mulai menulis code seperti [code contoh](https://docs.rs/rand/0.7.3/rand/) yang ada pada website dokumentasi `rand`. Untuk mendapatkan dokumentasinya Anda bisa klik pada tombol `docs` pada [laman di crates.io](https://crates.io/crates/rand).

Jadi cukup berbicara tentang Cargo: kita tetap menggunakan Playground. Beruntungnya, Playground telah terinstall 100 crate teratas (yang sering digunakan). Sehingga Anda tidak perlu menuliskannya di dalam `Cargo.toml`. Pada Playground Anda bisa membayangkan bahwa ia memiliki list yang panjang (seperti di bawah ini) dengan 100 crate terdaftar di dalamnya:

```text
[dependencies]
rand = "0.7.3"
some_other_crate = "0.1.0"
another_nice_crate = "1.7"
```

Itu berarti bahwa untuk menggunakan `rand`, Anda bisa melakukan hal seperti ini.

```rust
use rand; // Ini berarti seluruh dari crate rand
          // Pada komputer Anda, Anda tidak bisa langsung menulisnya seperti ini;
          // Anda perlu menuliskannya di dalam file Cargo.toml terlebih dahulu

fn main() {
    for _ in 0..5 {
        let random_u16 = rand::random::<u16>();
        print!("{} ", random_u16);
    }
}
```

Ia akan mencetak angka `u16` yang berbeda setiap saat, seperti `42266 52873 56528 46927 6867`.


Function utama yang ada di dalam `rand` adalah `random` dan `thread_rng` (rng artinya "random number generator"). Dan sebenarnya jika Anda melihat pada `random`, ia mengatakan: "Ini sebenarnya adalah shortcut untuk `thread_rng().gen()`". Jadi ia sebenarnya hanyalah `thread_rng` yang melakukan hampir semua hal.

Ini adalah contoh sederhana angka random dari angka 1 sampai dengan 10. Untuk mendapatkan angka tersebut, kita menggunakan `.gen_range()` di antara 1 dan 11.

```rust
use rand::{thread_rng, Rng}; // atau cukup use rand::*; jika kita cukup malas untuk menuliskannya

fn main() {
    let mut number_maker = thread_rng();
    for _ in 0..5 {
        print!("{} ", number_maker.gen_range(1, 11));
    }
}
```

Hasil cetaknya kira-kira seperti ini: `7 2 4 8 6`.

Dengan angka random kita bisa membuat hal-hal menarik seperti membuat karakter untuk game. Kita akan menggunakan `rand` dan hal lain yang kita ketahui untuk membuatnya. Pada game ini, karakter kita memiliki enam stats, dan Anda menggunakan d6 untuk stats tersebut. d6 adalah dadu yang memberikan 1, 2, 3, 4, 5, atau 6 di saat Anda melemparkannya. Setiap karakter melempar d6 tiga kali, jadinya setiap stat nilainya berada di antara 3 dan 18.

Tapi terkadang tidak adil jika karakter kita mendapatkan nilai yang rendah seperti 3 atau 4. Misalnya, jika strength Anda hanya bernilai 3, Anda tidak bisa melakukan apapun. Jadi ada satu method dimana akan menggunakan d6 empat kali. Anda lempar dadunya empat kali, dan buang angka yang paling rendah. Sehingga, jika Anda mendapatkan 3, 3, 1, 6 maka Anda bisa simpan 3, 3, 6 = 12. Kita akan membuat method ini juga sehingga si pemain game bisa menentukannya.

Ini adalah character creator sederhana yang kita buat. Kita membuat sebuah struct `Character` untuk statnya, dan bahkan mengimplementasikan `Display` untuk mencetak statnya dengan cara yang kita inginkan.

```rust
use rand::{thread_rng, Rng}; // Atau cukup tuliskan use rand::*; jika kita malas menuliskannya
use std::fmt; // digunakan di impl Display untuk character yang kita buat


struct Character {
    strength: u8,
    dexterity: u8,    // ini adalah "kecepatan"
    constitution: u8, // ini adalah "health"
    intelligence: u8,
    wisdom: u8,
    charisma: u8, // Ini adalah "popularitas karakter"
}

fn three_die_six() -> u8 { // "die" adalahsesuatu yang kita lempar untuk mendapatkan angkanya
    let mut generator = thread_rng(); // buat random number generator
    let mut stat = 0; // ini adalah totalnya
    for _ in 0..3 {
        stat += generator.gen_range(1..=6); // jumlahkan setiap dilempar
    }
    stat // Return totalnya
}

fn four_die_six() -> u8 {
    let mut generator = thread_rng();
    let mut results = vec![]; // pertama-tama, taruh angka-angkanya ke dalam vec
    for _ in 0..4 {
        results.push(generator.gen_range(1..=6));
    }
    results.sort(); // sekarang yang hasilnya seperti [4, 3, 2, 6] akan menjadi [2, 3, 4, 6]
    results.remove(0); // sekarang ia menjadi [3, 4, 6]
    results.iter().sum() // Return resultnya
}

enum Dice {
    Three,
    Four
}

impl Character {
    fn new(dice: Dice) -> Self { // true untuk tiga dadu, false untuk empat dadu
        match dice {
            Dice::Three => Self {
                strength: three_die_six(),
                dexterity: three_die_six(),
                constitution: three_die_six(),
                intelligence: three_die_six(),
                wisdom: three_die_six(),
                charisma: three_die_six(),
            },
            Dice::Four => Self {
                strength: four_die_six(),
                dexterity: four_die_six(),
                constitution: four_die_six(),
                intelligence: four_die_six(),
                wisdom: four_die_six(),
                charisma: four_die_six(),
            },
        }
    }
    fn display(&self) { // Kita bisa melakukan ini karena kita mengimplementasikan Display di bawah
        println!("{}", self);
        println!();
    }
}

impl fmt::Display for Character { // Cukup ikuti code di https://doc.rust-lang.org/std/fmt/trait.Display.html dan ubah sedikit saja
    fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(
            f,
            "Your character has these stats:
strength: {}
dexterity: {}
constitution: {}
intelligence: {}
wisdom: {}
charisma: {}",
            self.strength,
            self.dexterity,
            self.constitution,
            self.intelligence,
            self.wisdom,
            self.charisma
        )
    }
}



fn main() {
    let weak_billy = Character::new(Dice::Three);
    let strong_billy = Character::new(Dice::Four);
    weak_billy.display();
    strong_billy.display();
}
```

Hasil cetaknya adalah seperti berikut:

```text
Your character has these stats:
strength: 9
dexterity: 15
constitution: 15
intelligence: 8
wisdom: 11
charisma: 9

Your character has these stats:
strength: 9
dexterity: 13
constitution: 14
intelligence: 16
wisdom: 16
charisma: 10
```

Karakter yang dibuat dengan empat dadu biasanya sedikit lebih baik dalam banyak hal (statnya).


### rayon

`rayon` adalah crate popular yang memungkinkan Anda mempercepat code Rust yang Anda buat. Ia popular karena ia akan membuat threads tanpa perlu menuliskan `thread::spawn`. Dengan kata lain, ia popular karena ia sangat efektif namun mudah untuk ditulis. Contohnya:

- `.iter()`, `.iter_mut()`, `into_iter()` di rayon ditulis seperti ini:
- `.par_iter()`, `.par_iter_mut()`, `par_into_iter()`. Jadi Anda cukup menambahkan `par_` dan code Anda menjadi lebih cepat. (par artinya "parallel")

Method lain yang juga sama: `.chars()` diganti dengan `.par_chars()`, dan seterusnya.

Ini adalah contoh sederhana dari sebuah potongan code yang membuat komputer bekerja lebih berat:
```rust
fn main() {
    let mut my_vec = vec![0; 200_000];
    my_vec.iter_mut().enumerate().for_each(|(index, number)| *number+=index+1);
    println!("{:?}", &my_vec[5000..5005]);
}
```

Ia membuat sebuah vector dengan 200,000 item di dalamnya: semua item tersebut adalah 0. Kemudian kita panggil `.enumerate()` untuk mendapatkan index setiap angka, dan mengubah setiap 0 menjadi angka indexnya. Tentunya terlalu panjang jika kita cetak semuanya, sehingga kita hanya cetak item ke-5000 sampai dengan item ke-5004. Hal ini tetaplah cepat dilakukan Rust, namun jika Anda ingin Anda bisa membuatnya lebih cepat dengan menggunakan Rayon. Codenya hampir sama:

```rust
use rayon::prelude::*; // Import rayon

fn main() {
    let mut my_vec = vec![0; 200_000];
    my_vec.par_iter_mut().enumerate().for_each(|(index, number)| *number+=index+1); // tambahkan par_ ke iter_mut
    println!("{:?}", &my_vec[5000..5005]);
}
```

Dan seperti itulah cara penggunaannya. `rayon` memiliki method lainnya untuk mengkostumisasi apa yang ingin kita lakukan, tetapi yang paling sederhana, cukup "tambahkan `_par` untuk membuat program Anda menjadi lebih cepat".

### serde

`serde` adalah crate yang populer yang memungkinkan Anda untuk mengkonversi ke dan dari format seperti JSON, YAML, dll. Cara paling umum untuk menggunakannya adalah dengan membuat `struct` dengan dua buah attribute di atasnya. [Ia terlihat seperti ini](https://serde.rs/):

```rust
#[derive(Serialize, Deserialize, Debug)]
struct Point {
    x: i32,
    y: i32,
}
```

Trait `Serialize` dan `Deserialize` adalah trait yang membuat konversinya menjadi lebih mudah. (Hal ini pulalah yang menjadi asal-muasal dari nama `serde`) Jika Anda memiliki trait tersebut pada struct Anda, maka Anda bisa memanggil method untuk mengubahnya dari/menjadi JSON, atau format lainnya.

### regex

Crate [regex](https://crates.io/crates/regex) memungkinkan Anda melakukan pencarian melalui text menggunakan [regular expressions](https://en.wikipedia.org/wiki/Regular_expression). Dengan ini Anda bisa mencocokkan sesuatu text seperti `colour`, `color`, `colours` dan `colors` hanya dengan satu pencarian. Regular expressions adalah bahasa lain yang harus Anda pelajari jika Anda ingin menggunakannya.

### chrono

[chrono](https://crates.io/crates/chrono) adalah crate yang biasanya digunakan oleh programmer yang perlu berurusan dengan function-function waktu. Kita melihat standard library yang sekarang telah banyak memiliki function-function yang berhubungan dengan waktu, tapi jika Anda memerlukan lebih dari sekedar function standard, `chrono` adalah crate yang bagus untuk digunakan.


## A tour of the standard library

Sekarang setelah Anda mengetahu banyak hal tentang Rust, Anda akan dapat memahami sebagian besar hal yang ada di dalam standard library. Code yang berada di dalamnya tidaklah lagi terlihat begitu menakutkan. Mari kita lihat beberapa bagian di dalamnya yang belum kita pelajari. Tour ini akan membahas sebagain besar standard library yang mana tidak perlu lagi Anda install di Rust. Kita akan meninjau ulang banyak hal yang telah kita ketahui sehingga kita dapat mempelajarinya dengan pemahaman yang lebih baik.

### Arrays

Satu hal yang perlu dicatat tentang array adalah bahwa mereka tidak mengimplementasikan `Iterator.`. Yang artinya, jika kita memiliki array, Anda tidak bisa menggunakan `for`. Tapi Anda bisa menggunakan method seperti `.iter()` pada array. Atau Anda bisa menggunakan `&` untuk mendapatkan slicenya. Sebenarnya compiler akan memberitahukannya jika Anda mencoba untuk menggunakan `for`:

```rust
fn main() {
    // ⚠️
    let my_cities = ["Beirut", "Tel Aviv", "Nicosia"];

    for city in my_cities {
        println!("{}", city);
    }
}
```

Pesan errornya adalah:

```text
error[E0277]: `[&str; 3]` is not an iterator
 --> src\main.rs:5:17
  |
  |                 ^^^^^^^^^ borrow the array with `&` or call `.iter()` on it to iterate over it
```

Jadi, kita coba keduanya. Keduanya memberikan hasil yang sama.

```rust
fn main() {
    let my_cities = ["Beirut", "Tel Aviv", "Nicosia"];

    for city in &my_cities {
        println!("{}", city);
    }
    for city in my_cities.iter() {
        println!("{}", city);
    }
}
```

Hasil cetaknya adalah:

```text
Beirut
Tel Aviv
Nicosia
Beirut
Tel Aviv
Nicosia
```



Jika Anda ingin mendapatkan variabel dari array, Anda bisa meletakkan nama variabelnya di dalam `[]` untuk melakukan destructure. Ini sama seperti menggunakan sebuah tuple di dalam statement `match` atau mengambil variabel dari sebuah struct.

```rust
fn main() {
    let my_cities = ["Beirut", "Tel Aviv", "Nicosia"];
    let [city1, city2, city3] = my_cities;
    println!("{}", city1);
}
```

Hasil cetaknya adalah `Beirut`.

### char

Anda bisa menggunakan method `.escape_unicode()` untuk mendapatkan angka Unicode dari sebuah `char`:

```rust
fn main() {
    let korean_word = "청춘예찬";
    for character in korean_word.chars() {
        print!("{} ", character.escape_unicode());
    }
}
```

Hasil cetaknya adalah `\u{ccad} \u{cd98} \u{c608} \u{cc2c}`.


Anda bisa mendapatkan char dari `u8` menggunakan trait `From`, namun untuk `u32` Anda perlu menggunakan `TryFrom` karena bisa saja ia gagal. Ada banyak angka di `u32` daripada seluruh karakter yang ada di Unicode. Kita bisa melihat ini dengan contoh yang sederhana.

```rust
use std::convert::TryFrom; // Anda perlu menggunakan TryFrom
use rand::prelude::*;      // kita akan menggunakan angka random juga

fn main() {
    let some_character = char::from(99); // Untuk hal ini sangatlah mudah dilakukan - tidak perlu menggunakan TryFrom
    println!("{}", some_character);

    let mut random_generator = rand::thread_rng();
    // Ia akan mencoba 40,000 kali untuk membuat sebuah char dari u32.
    // Range loopnya adalah dari 0 (std::u32::MIN) sampai ke angka terbesar di u32 (std::u32::MAX). Jika ia tidak bekerja, kita akan memberinya '-'.
    for _ in 0..40_000 {
        let bigger_character = char::try_from(random_generator.gen_range(std::u32::MIN..std::u32::MAX)).unwrap_or('-');
        print!("{}", bigger_character)
    }
}
```

Hampir setiap saat ia akan men-generate `-`. Ini adalah bagian dari output yang akan Anda lihat:

```text
------------------------------------------------------------------------𤒰---------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-------------------------------------------------------------춗--------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
------------򇍜----------------------------------------------------
```

Jadi, adalah hal yang baik jika Anda perlu menggunakan `TryFrom`.

Juga, sebagaimana pada rilis di akhir Agustus 2020, Anda sekarang bisa mendapatkan `String` dari `char`. (`String` mengimplementasikan `From<char>`) Cukup tuliskan `String::from()` dan letakkan `char` di dalamnya.


### Integers

Ada banyak method matematis untuk type ini, ditambah dengan method-method lainnya. Berikut adalah beberapa method yang paling berguna.



`.checked_add()`, `.checked_sub()`, `.checked_mul()`, `.checked_div()`. Ini merupakan method yang baik jika Anda berpikir bahwa Anda mungkin mendapatkan angka yang tidak cocok dengan sebuah type. Method-method tersebut akan mengembalikan `Option` sehingga Anda bisa dengan aman memeriksa apakah operasi matematika yang Anda lakukan bekerja tanpa membuat programnya menjadi panic.

```rust
fn main() {
    let some_number = 200_u8;
    let other_number = 200_u8;

    println!("{:?}", some_number.checked_add(other_number));
    println!("{:?}", some_number.checked_add(1));
}
```

Hasilnya adalah:

```text
None
Some(201)
```


Anda pasti menyadari pada laman tentang integer, banyak tertulis `rhs`. Ini berarti "right hand side", yang artinya adalah sisi sebelah kanan di saat Anda melakukan beberapa operasi matematika. Contohnya, di `5 + 6`, `5` ada di sebelah kiri dan `6` ada di sebelah kanan. Nah, itulah `rhs`. Ini bukanlah sebuah keyword, namun Anda akan sering melihatnya, sehingga ini adalah hal yang penting untuk Anda ketahui.

Sementara kita membahas topik ini, mari mempelajari tentang bagaimana mengimplementasikan `Add`. Setelah Anda mengimplementasikan `Add`, Anda bisa menggunakan `+` pada type yang kita buat. Anda perlu untuk mengimplementasikan `Add` sendiri karena "add" bisa berarti banyak hal. Berikut adalah contoh yang ada pada laman standard library:

```rust
use std::ops::Add; // pertama-tama, kita import Add

#[derive(Debug, Copy, Clone, PartialEq)] // PartialEq mungkin adalah bagian yang paling penting pada bagian ini. Anda ingin bisa membandingkan angka
struct Point {
    x: i32,
    y: i32,
}

impl Add for Point {
    type Output = Self; // Ingat, ini disebut sebagai "associated type": a "type yang berjalan bersamaan".
                        // Pada kasus ini, ia hanyalah sebuah Point

    fn add(self, other: Self) -> Self {
        Self {
            x: self.x + other.x,
            y: self.y + other.y,
        }
    }
}
```

Sekarang mari implementasikan `Add` untuk type yang kita buat. Mari kita bayangkan bahwa kita ingin menambahkan dua negara bersamaan sehingga kita bisa membandingkan ekonominya. Berikut adalah codenya:

```rust
use std::fmt;
use std::ops::Add;

#[derive(Clone)]
struct Country {
    name: String,
    population: u32,
    gdp: u32, // ini adalah ukuran ekonominya
}

impl Country {
    fn new(name: &str, population: u32, gdp: u32) -> Self {
        Self {
            name: name.to_string(),
            population,
            gdp,
        }
    }
}

impl Add for Country {
    type Output = Self;

    fn add(self, other: Self) -> Self {
        Self {
            name: format!("{} and {}", self.name, other.name), // Kita akan menambahkan namanya bersama-sama,
            population: self.population + other.population, // dan populasinya,
            gdp: self.gdp + other.gdp,   // dan juga GDPnya
        }
    }
}

impl fmt::Display for Country {
    fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
        write!(
            f,
            "In {} are {} people and a GDP of ${}", // Kemudian kita bisa print semuanya hanya dengan menggunakan {}
            self.name, self.population, self.gdp
        )
    }
}

fn main() {
    let nauru = Country::new("Nauru", 10_670, 160_000_000);
    let vanuatu = Country::new("Vanuatu", 307_815, 820_000_000);
    let micronesia = Country::new("Micronesia", 104_468, 367_000_000);

    // Kita bisa memberikan Country sebuah &str sebagai ganti String untuk namanya. Tapi kita harus menuliskan lifetimenya dimana-mana
    // dan itu terlalu berlebihan untuk contoh yang sederhana. Lebih baik cukup clone saja di saat kita memanggil println!.
    println!("{}", nauru.clone());
    println!("{}", nauru.clone() + vanuatu.clone());
    println!("{}", nauru + vanuatu + micronesia);
}
```

Hasilnya adalah:

```text
In Nauru are 10670 people and a GDP of $160000000
In Nauru and Vanuatu are 318485 people and a GDP of $980000000
In Nauru and Vanuatu and Micronesia are 422953 people and a GDP of $1347000000
```

Nantinya di code ini kita bisa mengubah `.fmt()` untuk menampilkan angka yang lebih mudah dibaca.

Tiga trait lainnya adalah `Sub`, `Mul`, dan `Div`. Dan pada dasarnya, ketiganya sama pengimplementasiannya. Untuk `+=`, `-=`, `*=` dan `/=`, cukup tambahkan `Assign`: `AddAssign`, `SubAssign`, `MulAssign`, dan `DivAssign`. Anda bisa melihat daftarnya [disini](https://doc.rust-lang.org/std/ops/index.html#structs), karena masih ada banyak lagi. Contohnya, `%` disebut dengan `Rem`, `-` disebut dengan `Neg`, dll.


### Floats

`f32` dan `f64` memiliki method yang sangat banyak yang bisa Anda gunakan di saat Anda melakukan operasi matematis. Kita tidak akan mempelajari semuanya, namun ini adalah beberapa method yang mungkin nantinya Anda gunakan. Mereka adalah: `.floor()`, `.ceil()`, `.round()`, dan `.trunc()`. Semua method tersebut mengembalikan `f32` atau `f64` yang mirip seperti integer, namun dengan angka `0` setelah titik. Inilah yang dilakukan oleh method-method tersebut:

- `.floor()`: memberikan Anda integer terkecil.
- `.ceil()`: memberikan Anda integer terbesar.
- `.round()`: memberikan Anda integer terbesar jika angkanya bernilai 0.5 atau lebih, atau angka yang sama jika ia kurang dari 0.5. Ini disebut sebagai "rounding" (pembulatan) karena ia memberikan angka "yang dibulatkan" (angka yang memiliki bentuk yang pendek, sederhana).
- `.trunc()`: memotong angka setelah titik. Truncate artinya "memotong".

Ini adalah function sederhana untuk mencetak hasil dari method-method tersebut.

```rust
fn four_operations(input: f64) {
    println!(
"For the number {}:
floor: {}
ceiling: {}
rounded: {}
truncated: {}\n",
        input,
        input.floor(),
        input.ceil(),
        input.round(),
        input.trunc()
    );
}

fn main() {
    four_operations(9.1);
    four_operations(100.7);
    four_operations(-1.1);
    four_operations(-19.9);
}
```

Hasil cetaknya adalah:

```text
For the number 9.1:
floor: 9
ceiling: 10
rounded: 9 // because less than 9.5
truncated: 9

For the number 100.7:
floor: 100
ceiling: 101
rounded: 101 // because more than 100.5
truncated: 100

For the number -1.1:
floor: -2
ceiling: -1
rounded: -1
truncated: -1

For the number -19.9:
floor: -20
ceiling: -19
rounded: -20
truncated: -19
```

`f32` dan `f64` memiliki method bernama `.max()` dan `.min()` yang memberikan Anda nilai tertinggi atau nilai terendah dari dua buah angka. (Untuk type yang lain, Anda bisa menggunakan `std::cmp::max` dan `std::cmp::min`.) Berikut ini adalah cara menggunakan method-method tersebut dengan method `.fold()` untuk mendapatkan nilai tertinggi atau terendah. Anda bisa melihat lagi bahwa methid `.fold()` tidak hanya digunakan untuk menambahkan angka.

```rust
fn main() {
    let my_vec = vec![8.0_f64, 7.6, 9.4, 10.0, 22.0, 77.345, 10.22, 3.2, -7.77, -10.0];
    let maximum = my_vec.iter().fold(f64::MIN, |current_number, next_number| current_number.max(*next_number)); // Catatan: mulai dengan angka terkecil di f64.
    let minimum = my_vec.iter().fold(f64::MAX, |current_number, next_number| current_number.min(*next_number)); // Dan pada bagian ini, mulai dengan angka terbesar di f64
    println!("{}, {}", maximum, minimum);
}
```

### bool

Di Rust, Anda bisa mengubah `bool` menjadi sebuah integer jika Anda menginginkannya, karena hal itu aman untuk dilakukan. Namun Anda tidak bisa melakukan hal tersebut sebaliknya. Seperti yang Anda lihat, `true` diubah menjadi 1 dan `false` diubah menjadi 0.

```rust
fn main() {
    let true_false = (true, false);
    println!("{} {}", true_false.0 as u8, true_false.1 as i32);
}
```

Hasil cetaknya adalah `1 0`. Atau Anda bisa menggunakan `.into()` jika Anda memberitahukan typenya ke compiler:

```rust
fn main() {
    let true_false: (i128, u16) = (true.into(), false.into());
    println!("{} {}", true_false.0, true_false.1);
}
```

Hasil cetaknya sama seperti yang di atas.

Dengan rilir Rust 1.50 (rilis pada Februari 2021), sekarang ada method bernama `then()`, yang mana mengubah `bool` menjadi `Option`. Dengan method `then()`, Anda menuliskan sebuah closure, dan closurenya dipanggil jika itemnya bernilai `true`. Juga, apapun yang di return dari closure tersebut akan dimasukkan ke dalam `Option`. Ini adalah contoh sederhananya:

```rust
fn main() {

    let (tru, fals) = (true.then(|| 8), false.then(|| 8));
    println!("{:?}, {:?}", tru, fals);
}
```

Hasil cetaknya adalah `Some(8), None`.

Dan yang di bawah ini merupakan contohnya yang agak rumit:

```rust
fn main() {
    let bool_vec = vec![true, false, true, false, false];
    
    let option_vec = bool_vec
        .iter()
        .map(|item| {
            item.then(|| { // masukkan ke dalam map sehingga kita bisa pass item tersebut
                println!("Got a {}!", item);
                "It's true, you know" // Ini akan masuk ke dalam Some jika ia true
                                      // sebaliknya, ia akan menghasilkan None
            })
        })
        .collect::<Vec<_>>();

    println!("Now we have: {:?}", option_vec);

    // Ia akan mencetak None juga. Mari kita gunakan filter_map ke vector tersebut dan kumpulkan hasilnya di Vec yang baru.
    let filtered_vec = option_vec.into_iter().filter_map(|c| c).collect::<Vec<_>>();

    println!("And without the Nones: {:?}", filtered_vec);
}
```

Dan ini adalah hasil cetaknya:

```text
Got a true!
Got a true!
Now we have: [Some("It\'s true, you know"), None, Some("It\'s true, you know"), None, None]
And without the Nones: ["It\'s true, you know", "It\'s true, you know"]
```

### Vec

Vec memiliki banyak method yang sama sekali kita pelajari untuk sekarang ini. Kita mulai dari `.sort()`. `.sort()` menggunakan `&mut self` untuk menyortir vector.

```rust
fn main() {
    let mut my_vec = vec![100, 90, 80, 0, 0, 0, 0, 0];
    my_vec.sort();
    println!("{:?}", my_vec);
}
```

Hasil cetaknya adalah `[0, 0, 0, 0, 0, 80, 90, 100]`. Namun yang lebih menarik adalah ada cara lain untuk menyortir yaitu `.sort_unstable()`, dan ia biasanya lebih cepat. Ia bisa menjadi lebih cepat karena ia tidak peduli tentang urutan angkanya jika angkanya sama. Pada `.sort()`, Anda tahu bahwa bagian akhir vector `0, 0, 0, 0, 0` akan berada pada urutan yang sama setelah melakukan `.sort()`. Namun `.sort_unstable()` mungkin memndahkan nol terakhir ke index 0, kemudian nol terakhir yang ke-3 di pindah ke index 2, dst.


`.dedup()` artinya "de-duplicate". Ia akan menghapus item yang sama dalam sebuah vector, namun hanya jika mereka bersebelahana. Code di bawah ini tidak hanya mencetak `"sun", "moon"`:

```rust
fn main() {
    let mut my_vec = vec!["sun", "sun", "moon", "moon", "sun", "moon", "moon"];
    my_vec.dedup();
    println!("{:?}", my_vec);
}
```

Ia hanya akan menghapus "sun" yang berada di sebelah "sun", kemudian menghapus "moon" yang berada di sebelah "moon", dan kemudian lagi dengan "moon" yang bersebelahan dengan "moon". Maka hasilnya adalah: `["sun", "moon", "sun", "moon"]`.

Jika Anda ingin menghapus setiap duplikat, maka lakukan `.sort()` terlebih dahulu:

```rust
fn main() {
    let mut my_vec = vec!["sun", "sun", "moon", "moon", "sun", "moon", "moon"];
    my_vec.sort();
    my_vec.dedup();
    println!("{:?}", my_vec);
}
```

Maka hasilnya adalah: `["moon", "sun"]`.


### String

Anda akan mengingat bahwa `String` adalah type yang mirip dengan `Vec`. Ia mirip seperti `Vec` Anda bisa melakukan banyak hal dengan method yang sama. Contohnya, Anda bisa menggunakan `String::with_capacity()`. Anda mungkin akan memerlukannya jika Anda selalu melakukan push pada `char`menggunakan `.push()` atau melakukan push terhadap `&str` dengan menggunakan `.push_str()`. Ini adalah sebuah contoh dari `String` yang terlalu banyak melakukan alokasi.

```rust
fn main() {
    let mut push_string = String::new();
    let mut capacity_counter = 0; // kapasitasnya dimulai dari 0
    for _ in 0..100_000 { // lakukan sebanyak 100,000 kali
        if push_string.capacity() != capacity_counter { // Pertama, periksa apakah kapasitasnya sekarang telah berbeda
            println!("{}", push_string.capacity()); // Jika ya, cetak kapasitasnya
            capacity_counter = push_string.capacity(); // kemudian perbarui counternya
        }
        push_string.push_str("I'm getting pushed into the string!"); // dan push &str ini setiap loopnya berulang
    }
}
```

Hasilnya adalah:

```text
35
70
140
280
560
1120
2240
4480
8960
17920
35840
71680
143360
286720
573440
1146880
2293760
4587520
```

Kita telah melakukan realokasi (menyalin secara keseluruhan) sebanyak 18 kali. Namun sekarang kita tahu berapa kapasitas akhirnya yang terpakai. Sehingga kita bisa langsung memberikan batas kapasitasnya, dan kita tidak perlu lagi untuk melakukan realokasi: cukup memerlukan satu buah `String` dengan kapasitas yang muat untuk menyimpan semuanya sampai akhir.

```rust
fn main() {
    let mut push_string = String::with_capacity(4587520); // Kita mengetahui kapasitasnya secara tepat. Beberapa ukuran besar yang berbeda juga bisa dipakai
    let mut capacity_counter = 0;
    for _ in 0..100_000 {
        if push_string.capacity() != capacity_counter {
            println!("{}", push_string.capacity());
            capacity_counter = push_string.capacity();
        }
        push_string.push_str("I'm getting pushed into the string!");
    }
}
```

Dan ia mencetak hanya sekali, yaitu `4587520`. Sempurna! Kita tidak perlu melakukan alokasi lagi.

Tentu saja, panjang sebenarnya pasti lebih kecil dari ini. Jika Anda mencoba 100,001 kali, 101,000 kali, dst., ia akan tetap mencetak `4587520`. Ini dikarenakan setiap kali kapasitasnya bertambah, ia bertambah dua kali lipat dari yang sebelumnya. Kita bisa mengecilkannya menggunakan method `.shrink_to_fit()` (sama juga dengan `Vec`). `String` yang kita miliki sangatlah besar dan kita tidak ingin menambahkan apa-apa lagi ke `String` tersebut, sehingga kita bisa membuatnya menjadi lebih kecil dari yang sebelumnya. Tapi lakukan hal ini jika Anda sudah merasa yakin. Inilah alasannya:

```rust
fn main() {
    let mut push_string = String::with_capacity(4587520);
    let mut capacity_counter = 0;
    for _ in 0..100_000 {
        if push_string.capacity() != capacity_counter {
            println!("{}", push_string.capacity());
            capacity_counter = push_string.capacity();
        }
        push_string.push_str("I'm getting pushed into the string!");
    }
    push_string.shrink_to_fit();
    println!("{}", push_string.capacity());
    push_string.push('a');
    println!("{}", push_string.capacity());
    push_string.shrink_to_fit();
    println!("{}", push_string.capacity());
}
```

Hasilnya adalah:

```text
4587520
3500000
7000000
3500001
```

Jadi pertama kita memiliki ukuran kapasitas `4587520`, namun kita tidak menggunakan semuanya. Kita gunakan method `.shrink_to_fit()` dan mendapatkan kapasitasnya mengecil menjadi `3500000`. Tapi kemudian kita lupa bahwa kita perlu melakukan push sebuah karakter `a`. Di saat kita melakukan hal tersebut, Rust melihat bahwa kita memerlukan space lebih dan memberikan kita ukuran dua kali lipat dari sebelumnya: sekarang ia menjadi `7000000`. Whoops! Sehingga kita menggunakan `.shrink_to_fit()` lagi dan sekarang kapasitasnya kembali turun menjadi `3500001`.

`.pop()` bekerja juga pada `String`, sama seperti saat digunakan pada `Vec`.

```rust
fn main() {
    let mut my_string = String::from(".daer ot drah tib elttil a si gnirts sihT");
    loop {
        let pop_result = my_string.pop();
        match pop_result {
            Some(character) => print!("{}", character),
            None => break,
        }
    }
}
```

Hasil cetaknya adalah `This string is a little bit hard to read.` karena ia dimulai dari karakter yang terakhir.

`.retain()` adalah method yang menggunakan closure, yang mana `String` jarang sekali memiliki method seperti ini. Ia mirip seperti `.filter()` untuk iterator.

```rust
fn main() {
    let mut my_string = String::from("Age: 20 Height: 194 Weight: 80");
    my_string.retain(|character| character.is_alphabetic() || character == ' '); // Tetap simpan jika ia adalah huruf atau spasi
    dbg!(my_string); // Mari kali ini kita iseng menggunakan dbg!() menggantikan println!
}
```

Hasilnya adalah:

```text
[src\main.rs:4] my_string = "Age  Height  Weight "
```


### OsString and CString

`std::ffi` adalah bagian dari `std` yang membantu Anda untuk menghubungkan Rust dengan bahasa lain atau operating system yang lain. Ia memiliki type seperti `OsString` dan `CString`, yang mana mirip seperti `String` yang ada pada operating system atau `String` untuk bahasa C. Masing-masing dari mereka memiliki type `&str`nya sendiri juga: yaitu `OsStr` dan `CStr`. `ffi` adalah singkatan dari "foreign function interface".

Anda bisa menggunakan `OsString` di saat Anda bekerja dengan operating system yang tidak memiliki Unicode. Semua string di Rust adalah unicode. Hanya saja, tidak semua operating system memilikinya. Ini adalah penjelasan sederhana dari standard library tentang mengapa kita perlu `OsString`:

- String di Unix (Linux, etc.) mungkin saja memiliki banyak byte yang sama sekali tidak memiliki angka 0. Dan terkadang Anda membacanya sebagai Unicode UTF-8.
- String di Windows bisa saja dibuat dari random 16-bit yang tidak memiliki angka 0.Dan terkadang Anda membacanya sebagai Unicode UTF-16.
- Di Rust, string selalu valid sebagai UTF-8, yang mungkin saja mengandung angka 0.

Jadi `OsString` dibuat agar bisa dibaca oleh semua operating system tersebut.

Anda bisa melakukan semua hal-hal umum dengan menggunakan `OsString` seperti `OsString::from("Write something here")`. Ia juga memiliki method `.into_string()` yang mana ia akan mencoba untuk mengubah `OsString` menjadi regular `String`. Ia mengembalikan `Result`, namun bagian `Err`nya adalah `OsString`:

```rust
// 🚧
pub fn into_string(self) -> Result<String, OsString>
```

Jadi jika ia tidak bekerja, Anda akan kembali mendapatkan `OsString`. Anda tidak bisa menggunakan `.unwrap()` karena ia akan panic, tapi Anda bisa menggunakan `match` untuk kembali mendapatkan `OsString`. Mari kita coba dengan cara memanggil method yang sama sekali tidak ada.

```rust
use std::ffi::OsString;

fn main() {
    // ⚠️
    let os_string = OsString::from("This string works for your OS too.");
    match os_string.into_string() {
        Ok(valid) => valid.thth(),           // Compiler: "Apa ini .thth()??"
        Err(not_valid) => not_valid.occg(),  // Compiler: "Apa ini .occg()??"
    }
}
```

Kemudian compiler memberitahu kita persis apa yang ingin kita ketahui:

```text
error[E0599]: no method named `thth` found for struct `std::string::String` in the current scope
 --> src/main.rs:6:28
  |
6 |         Ok(valid) => valid.thth(),
  |                            ^^^^ method not found in `std::string::String`

error[E0599]: no method named `occg` found for struct `std::ffi::OsString` in the current scope
 --> src/main.rs:7:37
  |
7 |         Err(not_valid) => not_valid.occg(),
  |                                     ^^^^ method not found in `std::ffi::OsString`
```

Kita bisa melihat bahwa type dari `valid` adalah `String` dan type dari `not_valid` adalah `OsString`.

### mem

`std::mem` memiliki method-method yang menarik. Kita sudah melihatnya beberapa, misalnya `.size_of()`, `.size_of_val()` dan `.drop()`:


```rust
use std::mem;

fn main() {
    println!("{}", mem::size_of::<i32>());
    let my_array = [8; 50];
    println!("{}", mem::size_of_val(&my_array));
    let mut some_string = String::from("You can drop a String because it's on the heap");
    mem::drop(some_string);
    // some_string.clear();   jika kita melakukan ini, maka programnya akan panic
}
```

Hasilnya adalah:

```text
4
200
```

Ini adalah beberapa method lainnya di `mem`:

`swap()`: dengan method ini, Anda bisa mengubah value diantara dua variabel. Anda perlu menggunakan mutable reference di masing-masing variabel tersebut untuk melakukannya. Ini sangat berguna ketika Anda memiliki dua variabel yang ingin Anda tukar valuenya dan Rust tidak mengizinkannya karena adanya borrowing rules. Atau juga di saat Anda ingin menukar dua variabel dengan cepat.

Berikut adalah contohnya:

```rust
use std::{mem, fmt};

struct Ring { // Buat sebuah ring dari Lord of the Rings
    owner: String,
    former_owner: String,
    seeker: String, // seeker artinya "orang yang mencari-cari cincin tersebut"
}

impl Ring {
    fn new(owner: &str, former_owner: &str, seeker: &str) -> Self {
        Self {
            owner: owner.to_string(),
            former_owner: former_owner.to_string(),
            seeker: seeker.to_string(),
        }
    }
}

impl fmt::Display for Ring { // Display untuk menampilkan siapa yang memilikinya dan siapa yang menginginkannya
        fn fmt(&self, f: &mut fmt::Formatter<'_>) -> fmt::Result {
            write!(f, "{} has the ring, {} used to have it, and {} wants it", self.owner, self.former_owner, self.seeker)
        }
}

fn main() {
    let mut one_ring = Ring::new("Frodo", "Gollum", "Sauron");
    println!("{}", one_ring);
    mem::swap(&mut one_ring.owner, &mut one_ring.former_owner); // Gollum mendapatkan cincinnya kembali
    println!("{}", one_ring);
}
```

Hasilnya adalah:

```text
Frodo has the ring, Gollum used to have it, and Sauron wants it
Gollum has the ring, Frodo used to have it, and Sauron wants it
```

`replace()`: mirip seperti swap, dan sebenarnya di dalamnya memang menggunakan swap, seperti yang Anda lihat:

```rust
pub fn replace<T>(dest: &mut T, mut src: T) -> T {
    swap(dest, &mut src);
    src
}
```

Jadi sebenarnya ia hanya melakukan swap dan kemudian mengembalikan item yang lain. Dengan method ini, Anda mengganti value dengan value lain yang Anda masukkan. Dan karena ia mengembalikan value yang terdahulu, jadi Anda harus menggunakan `let`. Beginilah contohnya.

```rust
use std::mem;

struct City {
    name: String,
}

impl City {
    fn change_name(&mut self, name: &str) {
        let old_name = mem::replace(&mut self.name, name.to_string());
        println!(
            "The city once called {} is now called {}.",
            old_name, self.name
        );
    }
}

fn main() {
    let mut capital_city = City {
        name: "Constantinople".to_string(),
    };
    capital_city.change_name("Istanbul");
}
```

Hasilnya adalah `The city once called Constantinople is now called Istanbul.`.

Ada juga function yang bernama `.take()` yang mirip dengan `.replace()`, tapi ia menyisakan default value pada itemnya. Anda akan mengingat bahwa default value biasanya adalah sesuatu yang bernilai 0, "", dan lain-lain. Inilah signaturenya:

```rust
// 🚧
pub fn take<T>(dest: &mut T) -> T
where
    T: Default,
```

Sehingga Anda bisa melakukan hal seperti berikut:

```rust
use std::mem;

fn main() {
    let mut number_vec = vec![8, 7, 0, 2, 49, 9999];
    let mut new_vec = vec![];

    number_vec.iter_mut().for_each(|number| {
        let taker = mem::take(number);
        new_vec.push(taker);
    });

    println!("{:?}\n{:?}", number_vec, new_vec);
}
```

Dan sebagaimana yang Anda lihat, ia menggantikan semua angka dengan 0: tidak ada index yang dihapus.

```text
[0, 0, 0, 0, 0, 0]
[8, 7, 0, 2, 49, 9999]
```


Tentu saja, untuk type yang Anda buat, Anda bisa mengimplementasikan `Default` ke apapun yang Anda inginkan. Mari kita lihat contoh dimana kita memiliki sebuah `Bank` dan sebuah `Robber`. Setiap si maling merampok `Bank`, ia merampok uangnya dari desk. Namun si desk bisa mengambil uang lagi dari brankas kapanpun, sehingga ia selalu memiliki 50. Kita akan membuat type kita sendiri untuk kasus ini, sehingga ia selalu memiliki 50. Beginilah codenya:

```rust
use std::mem;
use std::ops::{Deref, DerefMut}; // Kita akan menggunakan ini untuk mendapatkan fitur dari u32

struct Bank {
    money_inside: u32,
    money_at_desk: DeskMoney, // Ini adalah type "smart pointer" yang kita buat. Ia memiliki nilai defaultnya sendiri, namun ia juga akan menggunakan u32
}

struct DeskMoney(u32);

impl Default for DeskMoney {
    fn default() -> Self {
        Self(50) // defaultnya selalu bernilai 50, bukan 0
    }
}

impl Deref for DeskMoney { // Dengan ini, kita bisa mengakses u32 menggunakan *
    type Target = u32;

    fn deref(&self) -> &Self::Target {
        &self.0
    }
}

impl DerefMut for DeskMoney { // Dan dengan ini, kita bisa menambahkan, mengurangi, dst.
    fn deref_mut(&mut self) -> &mut Self::Target {
        &mut self.0
    }
}

impl Bank {
    fn check_money(&self) {
        println!(
            "There is ${} in the back and ${} at the desk.\n",
            self.money_inside, *self.money_at_desk // Gunakan * sehingga kita bisa mencetak u32
        );
    }
}

struct Robber {
    money_in_pocket: u32,
}

impl Robber {
    fn check_money(&self) {
        println!("The robber has ${} right now.\n", self.money_in_pocket);
    }

    fn rob_bank(&mut self, bank: &mut Bank) {
        let new_money = mem::take(&mut bank.money_at_desk); // Disini, ia akan mengambil uangnya, dan meninggalkan 50 karena itu merupakan nilai defaultnya
        self.money_in_pocket += *new_money; // Gunakan * karena kita hanya bisa menambahkan u32. DeskMoney tidak bisa melakukan pertambahan
        bank.money_inside -= *new_money;    // Disini juga
        println!("She robbed the bank. She now has ${}!\n", self.money_in_pocket);
    }
}

fn main() {
    let mut bank_of_klezkavania = Bank { // Buat sebuah bank
        money_inside: 5000,
        money_at_desk: DeskMoney(50),
    };
    bank_of_klezkavania.check_money();

    let mut robber = Robber { // Buat seorang perampok
        money_in_pocket: 50,
    };
    robber.check_money();

    robber.rob_bank(&mut bank_of_klezkavania); // Rampok, kemudian periksa uangnya
    robber.check_money();
    bank_of_klezkavania.check_money();

    robber.rob_bank(&mut bank_of_klezkavania); // Lakukan lagi
    robber.check_money();
    bank_of_klezkavania.check_money();

}
```

Hasil cetaknya adalah:

```text
There is $5000 in the back and $50 at the desk.

The robber has $50 right now.

She robbed the bank. She now has $100!

The robber has $100 right now.

There is $4950 in the back and $50 at the desk.

She robbed the bank. She now has $150!

The robber has $150 right now.

There is $4900 in the back and $50 at the desk.
```

Anda bisa melihat bahwa di desk selalu ada $50.


### prelude

Standard library juga memiliki prelude. Inilah mengapa Anda tidak perlu menuliskan sesuatu seperti `use std::vec::Vec` untuk membuat sebuah `Vec`. Anda bisa melihat semua itemnya [di sini](https://doc.rust-lang.org/std/prelude/index.html#prelude-contents), dan kita sudah mengetahui hampir semuanya:

- `std::marker::{Copy, Send, Sized, Sync, Unpin}`. Anda belum pernah melihat `Unpin` sebelumnya, karena ia sudah digunakan hampir di semua type (seperti `Sized`, yang juga sangat umum). "Pin" berarti tidak membiarkan sesuatu bergerak. Pada kasus ini, `Pin` berarti bahwa ia tidak bisa berpindah di memory, namun banyak item yang memiliki `Unpin`, sehingga Anda bisa melakukannya. Inilah mengapa function-function seperti `std::mem::replace` bekerja, karena mereka tidak dalam kondisi ter-pin.
- `std::ops::{Drop, Fn, FnMut, FnOnce}`.
- `std::mem::drop`
- `std::boxed::Box`.
- `std::borrow::ToOwned`. Anda sudah melihat ini sedikit di saat mempelajari `Cow`, yang mana bisa mengambil borrowed value dan membuat kepemilikannya menjadi owned. Ia menggunakan method `.to_owned()` untuk melakukan. Anda juga bisa menggunakan `.to_owned()` pada `&str` untuk mendapatkan `String`, dan sama pula pada borrowed value lainnya.
- `std::clone::Clone`
- `std::cmp::{PartialEq, PartialOrd, Eq, Ord}`.
- `std::convert::{AsRef, AsMut, Into, From}`.
- `std::default::Default`.
- `std::iter::{Iterator, Extend, IntoIterator, DoubleEndedIterator, ExactSizeIterator}`. Sebelumnya kita menggunakan `.rev()` untuk iterator: Ini sebenarnya membuat `DoubleEndedIterator`. `ExactSizeIterator` hanyalah sesuatu seperti `0..10`: ia sudah tahu bahwa ia memiliki `.len()` sebesar 10. Iterator yang lain tidak mengetahui panjangnya secara pasti.
- `std::option::Option::{self, Some, None}`.
- `std::result::Result::{self, Ok, Err}`.
- `std::string::{String, ToString}`.
- `std::vec::Vec`.

Bagaimana jika Anda tidak menginginkan prelude karena suatu hal tertentu? Cukup tambahkan attribute `#![no_implicit_prelude]`. Mari kita coba dan kita lihat teguran dari compiler:

```rust
// ⚠️
#![no_implicit_prelude]
fn main() {
    let my_vec = vec![8, 9, 10];
    let my_string = String::from("This won't work");
    println!("{:?}, {}", my_vec, my_string);
}
```

Sekarang Rust tidak mengerti apa yang ingin kita lakukan:

```text
error: cannot find macro `println` in this scope
 --> src/main.rs:5:5
  |
5 |     println!("{:?}, {}", my_vec, my_string);
  |     ^^^^^^^

error: cannot find macro `vec` in this scope
 --> src/main.rs:3:18
  |
3 |     let my_vec = vec![8, 9, 10];
  |                  ^^^

error[E0433]: failed to resolve: use of undeclared type or module `String`
 --> src/main.rs:4:21
  |
4 |     let my_string = String::from("This won't work");
  |                     ^^^^^^ use of undeclared type or module `String`

error: aborting due to 3 previous errors
```

Jadi untuk code ini, Anda perlu memberitahukan Rust untuk menggunakan crate `extern` (external) bernama `std`, dan kemudian menyebutkan item-item yang Anda ingin gunakan. Berikut ini adalah semua yang harus kita lakukan hanya untuk membuat sebuah Vec dan String, dan juga mencetaknya:

```rust
#![no_implicit_prelude]

extern crate std; // Sekarang Anda perlu memberitahukan kepada Rust bahwa Anda ingin menggunakan crate bernama std
use std::vec; // kita memerlukan macro vec
use std::string::String; // dan juga string
use std::convert::From; // dan ini berguna untuk mengkonversi dari &str ke String
use std::println; // dan ini untuk print

fn main() {
    let my_vec = vec![8, 9, 10];
    let my_string = String::from("This won't work");
    println!("{:?}, {}", my_vec, my_string);
}
```

Dan sekarang codenya berjalan. Hasilnya adalah  `[8, 9, 10], This won't work`. Jadinya, Anda bisa melihat mengapa Rust menggunakan prelude. Namun jika Anda ingin, Anda tidak perlu menggunakannya. Dan bahkan Anda bisa menggunakan `#![no_std]` (kita pernah melihatnya sekali sebelumnya) ketika Anda bahkan tidak bisa menggunakan sesuatu seperti stack memory. Tetapi seringnya kita tidak perlu berpikir tentang tidak menggunakan prelude atau `std` sama sekali.

Jadi mengapa sebelumnya kita belum pernah melihat keyword `extern`? Ini karena kita tidak terlalu memerlukannya lagi. Di Rust versi lama, di saat kita memanggil external crate, kita harus menggunakannya. Jadi, di Rust versi lama, untuk menggunakan `rand`, Anda perlu menuliskan:

```rust
extern crate rand;
```

dan kemudian statement `use` untuk mod, trait, dll. yang ingin Anda gunakan. Namun compiler Rust sekarang tidak membutuhkan bantuan ini lagi - Anda cukup menggunakan `use` dan compiler tahu dimana menemukannya. Jadi Anda hampir tidak pernah membutuhkan `extern crate` lagi. Tapi di code Rust yang ditulis oleh orang lain, mungkin Anda masih melihatnya di bagian atas codenya.



### time

`std::time` adalah dimana Anda bisa mendapatkan function untuk waktu. (Jika Anda menginginkan lebih banyak function, crate seperti `chrono` bisa digunakan.) Function paling sederhana adalah mengambil system time dengan `Instant::now()`.

```rust
use std::time::Instant;

fn main() {
    let time = Instant::now();
    println!("{:?}", time);
}
```

Jika Anda mencetaknya, Anda akan mendapatkan sesuatu seperti berikut: `Instant { tv_sec: 2738771, tv_nsec: 685628140 }`. Itu adalah detik dan nanosecond, namun itu tidaklah terlalu berguna. Misalnya, jika Anda melihat pada 2738771 detik (dicetak pada bulan Agustus), itu adalah 31.70 hari. Itu sama sekali tidak ada hubungannya dengan bulan atau hari dalam setahun. Namun laman tentang `Instant` memberi tahu kita bahwa `Instant` tidaklah berguna jika dipakai begitu saja. Dikatakan bahwa "opaque and useful only with Duration." Opaque berarti "Anda tidak bisa memahaminya", dan duration/durasi artinya "berapa lama waktu sudah berlalu". Sehingga ia hanya berguna di saat kita perlu melakukan sesuatu seperti membandingkan waktu.

Jika Anda melihat pada trait-trait yang berada di sebelah kiri, salah satu dari trait tersebut adalah `Sub<Instant>`. Yang berarti kita bisa menggunakan `-` untuk mengurangkannya dengan yang lain. Dan saat kita klik pada [src] untuk melihat apa yang ia lakukan, maka kita akan melihat code berikut:

```rust
impl Sub<Instant> for Instant {
    type Output = Duration;

    fn sub(self, other: Instant) -> Duration {
        self.duration_since(other)
    }
}
```

Jadinya, ia mengambil `Instant` dan menggunakan method `.duration_since()` untuk mendapatkan `Duration`. Mari kita coba untuk mencetaknya. Kita akan membuat dua buah `Instant::now()` tepat setelah satu sama lain (time2 ditulis setelah time1), kemudian kita akan membuat programnya sibuk untuk sementara waktu. Kemudian kita akan membuat satu lagi `Instant::now()`. Akhirnya kita akan melihat berapa lama waktu yang dibutuhkan.

```rust
use std::time::Instant;

fn main() {
    let time1 = Instant::now();
    let time2 = Instant::now(); // time2 dibuat tepat setelah dibuatnya time1

    let mut new_string = String::new();
    loop {
        new_string.push('წ'); // buat Rust melakukan push karakter Georgian ini ke dalam String
        if new_string.len() > 100_000 { //  lakukan sampai panjangnya 100,000 byte
            break;
        }
    }
    let time3 = Instant::now();
    println!("{:?}", time2 - time1);
    println!("{:?}", time3 - time1);
}
```

Hasilnya adalah seperti berikut:

```text
1.025µs
683.378µs
```

Jadi ada jeda 1 microsecond vs. 683 microsecond. Kita bisa lihat bahwa Rust memerlukan waktu untuk melakukannya.

Ada satu hal menarik yang bisa kita lakukan dengan sebuah `Instant`. Kita bisa mengubahnya menjadi `String` dengan menggunakan `format!("{:?}", Instant::now());`. Begini codenya:

```rust
use std::time::Instant;

fn main() {
    let time1 = format!("{:?}", Instant::now());
    println!("{}", time1);
}
```

Hasil cetaknya adalah seperti ini: `Instant { tv_sec: 2740773, tv_nsec: 632821036 }`. Tentu saja itu tidak bergunak, namun jika kita menggunakan `.iter()` dan `.rev()` dan `.skip(2)`, kita bisa membuang `}` dan ` `. Kita bisa menggunakannya untuk membuat sebuah random number generator.

```rust
use std::time::Instant;

fn bad_random_number(digits: usize) {
    if digits > 9 {
        panic!("Random number can only be up to 9 digits");
    }
    let now = Instant::now();
    let output = format!("{:?}", now);

    output
        .chars()
        .rev()
        .skip(2)
        .take(digits)
        .for_each(|character| print!("{}", character));
    println!();
}

fn main() {
    bad_random_number(1);
    bad_random_number(1);
    bad_random_number(3);
    bad_random_number(3);
}
```

Hasilnya adalah seperti berikut:

```text
6
4
967
180
```

Functionnya kita beri nama `bad_random_number` karena itu bukanlah cara yang bagus untuk membuat random number generator. Rust memiliki crates yang lebih baik untuk membuat angka random dengan code yang lebih singkat dari `rand` contohnya `fastrand`. Namun ini adalah contoh yang baik tentang bagaimana kita bisa menggunakan imajinasi kita membuat sesuatu dengan menggunakan `Instant`.

Jika Anda memiliki thread, Anda bisa menggunakan `std::thread::sleep` untuk membuatnya stop untuk sementara waktu. Di saat Anda melakukan ini, Anda perlu memberikannya durasi. Anda tidak perlu membuat membuat lebih dari satu thread untuk melakukan ini karena sebenarnya setiap program berjalan dengan menggunakan setidaknya satu thread. `sleep` memerlukan `Duration`, sehingga ia bisa mengetahui seberapa lama ia sleep. Anda bisa memilih unitnya (satuannya) seperti ini: `Duration::from_millis()`, `Duration::from_secs`, dll. Seperti inilah contohnya:

```rust
use std::time::Duration;
use std::thread::sleep;

fn main() {
    let three_seconds = Duration::from_secs(3);
    println!("I must sleep now.");
    sleep(three_seconds);
    println!("Did I miss anything?");
}
```

Hasilnya adalah:

```text
I must sleep now.
Did I miss anything?
```

namun thread tidak melakukan apapun selama tiga detik. Anda biasanya menggunakan `.sleep()` di saat Anda menggunakan banyak thread yang perlu mencoba melakukan banyak hal, misalnya memeriksa koneksi. Anda tidak menginginkan thread menggunakan processor Anda untuk mencoba 100,000 kali dalam sedetik ketika Anda hanya ingin memeriksanya sewaktu-waktu. Jadi, Anda dapat menyetel `Duration`, dan ia akan mencoba melakukan tugasnya setiap kali threadnya mulai aktif.


### Other macros


Mari kita melihat-lihat beberapa macro yang lain.

`unreachable!()`

Macro ini mirip seperti `todo!()`, namun untuk code yang tidak pernah Anda tuliskan. Mungkin Anda memiliki `match` di dalam enum yang Anda sendiri tahu bahwa kondisinya tidak akan memilih salah satu arm pun, jadi codenya sama sekali tidak pernha bisa dijangkau (reached). Jika demikian, Anda bisa menuliskan `unreachable!()` sehingga compiler tahu bagian itu diabaikan saja.

Sebagai contoh, anggap saja Anda memiliki program yang menuliskan sesuatu di saat Anda memilih tempat tinggal. Lokasinya ada di Ukraina, dan semua kota-kotanya baik-baik saja kecuali Chernobyl. Program yang Anda buat tidak akan mengizinkan siapapun memilih Chernobyl, karena kota itu bukanlah tempat yang layak untuk ditinggali untuk sekarang ini. Tapi, enumnya sudah lama dibuat oleh orang lain, dan kita tidak bisa mengubahnya. Jadi di arm yang ada pada `match`, Anda bisa menggunakan macro `unreachable!()` disini. Codenya terlihat seperti ini:

```rust
enum UkrainePlaces {
    Kiev,
    Kharkiv,
    Chernobyl, // Anggap saja kita tidak bisa mengubah enumnya - Chernobyl akan selalu ada di dalam enum ini
    Odesa,
    Dnipro,
}

fn choose_city(place: &UkrainePlaces) {
    use UkrainePlaces::*;
    match place {
        Kiev => println!("You will live in Kiev"),
        Kharkiv => println!("You will live in Kharkiv"),
        Chernobyl => unreachable!(),
        Odesa => println!("You will live in Odesa"),
        Dnipro => println!("You will live in Dnipro"),
    }
}

fn main() {
    let user_input = UkrainePlaces::Kiev; // Anggap saja inputan dari user dibuat dari suatu function. User tidak akan bisa memilih Chernobyl, apapun yang terjadi
    choose_city(&user_input);
}
```

Hasilnya adalah `You will live in Kiev`.

`unreachable!()` juga baik digunakan untuk membaca code karena ia akan mengingatkan Anda bahwa ada beberapa bagian dari code yang kondisinya tidak bisa dijangkau (unreachable). Anda harus pastikan bahwa code tersebut memang benar tidak bisa dijangkau. Karena jika Anda menggunakan `unreachable!()`, padahal armnya bisa dijangkau, maka programnya akan panic.

Juga, jika Anda memiliki code yang unreachable, maka compiler akan mengetahuinya, dan memberitahukannya ke Anda. Seperti ini contohnya:

```rust
fn main() {
    let true_or_false = true;

    match true_or_false {
        true => println!("It's true"),
        false => println!("It's false"),
        true => println!("It's true"), // Oops, kita menuliskan true lagi disini
    }
}
```

Compiler akan mengatakan:

```text
warning: unreachable pattern
 --> src/main.rs:7:9
  |
7 |         true => println!("It's true"),
  |         ^^^^
  |
```

Sedangkan `unreachable!()` ini diperuntukkan di saat compiler tidak mengetahuinya, seperti contoh kita yang di awal tersebut (tentang Chernobyl).



`column!`, `line!`, `file!`, `module_path!`

Empat macro ini mirip seperti `dbg!()` karena Anda memasukannya ke code Anda untuk memberikan informasi mengenai debug. Namun ia tidak mengambil variabel apapun - Anda cukup menggunakan mereka dengan bracket (tanda kurung) dan tidak ada yang lain. Keempatnya mudah untuk dipelajari:

- `column!()` memberikan Anda informasi kolom dimana Anda menuliskannya,
- `file!()` memberikan Anda informasi nama file dimana Anda menuliskannya,
- `line!()` memberikan Anda informasi line/baris dimana Anda menuliskannya, dan
- `module_path!()` memberikan Anda informasi di module mana ia berada.

Code berikut ini menunjukkan keempatnya dalam contoh yang sederhana. Kita akan menganggap ada lebih banyak code (mod di dalam mod), karena itulah alasannya kita ingin menggunakan macro `module_path!()`. Anda bisa membayangkan sebuah program Rust yang besar yang dibuat dengan banyak mod dan file.

```rust
pub mod something {
    pub mod third_mod {
        pub fn print_a_country(input: &mut Vec<&str>) {
            println!(
                "The last country is {} inside the module {}",
                input.pop().unwrap(),
                module_path!()
            );
        }
    }
}

fn main() {
    use something::third_mod::*;
    let mut country_vec = vec!["Portugal", "Czechia", "Finland"];
    
    // lakukan sesuatu
    println!("Hello from file {}", file!());

    // lakukan sesuatu
    println!(
        "On line {} we got the country {}",
        line!(),
        country_vec.pop().unwrap()
    );

    // lakukan sesuatu

    println!(
        "The next country is {} on line {} and column {}.",
        country_vec.pop().unwrap(),
        line!(),
        column!(),
    );

    // ada banyak code di bagian ini

    print_a_country(&mut country_vec);
}
```

Hasil cetaknya adalah:

```text
Hello from file src/main.rs
On line 23 we got the country Finland
The next country is Czechia on line 32 and column 9.
The last country is Portugal inside the module rust_book::something::third_mod
```



`cfg!`

Kita mengetahui bahwa kita bisa menggunakan attribute seperti `#[cfg(test)]` dan `#[cfg(windows)]` untuk memberitahukan compiler apa yang harus dilakukan dalam kasus tertentu. Di saat Anda memiliki `test`, ia akan menjalankan code ketika kita menjalankan Rust dalam mode testing (jika ia ada di dalam komputer Anda, maka Anda perlu mengetikkan `cargo test`). Dan di saat Anda menggunakan `windows`, ia akan menjalankan code jika user menggunakan Windows. Tapi mungkin Anda hanya ingin mengubah sedikit code tergantung pada operating systemnya, dll. Di saat seperti itulah macro ini menjadi berguna. ia akan me-return `bool`.

```rust
fn main() {
    let helpful_message = if cfg!(target_os = "windows") { "backslash" } else { "slash" };

    println!(
        "...then in your hard drive, type the directory name followed by a {}. Then you...",
        helpful_message
    );
}
```

Hasil cetaknya akan berbeda, berdasarkan operating system yang Anda gunakan. Rust Playground berjalan di atas Linux, sehingga ia akan mencetak:

```text
...then in your hard drive, type the directory name followed by a slash. Then you...
```

`cfg!()` berfungsi untuk setiap jenis konfigurasi. Berikut adalah contoh dari sebuah function yang berjalan dengan cara yang berbeda saat Anda menjalankannya di dalam test.

```rust
#[cfg(test)] // cfg! akan bisa mencari kata test
mod testing {
    use super::*;
    #[test]
    fn check_if_five() {
        assert_eq!(bring_number(true), 5); // Function bring_number() ini semestinya me-return 5
    }
}

fn bring_number(should_run: bool) -> u32 { // Function ini memerlukan bool untuk mengetahui apakah ia harus dijalankan
    if cfg!(test) && should_run { // jika ia semestinya dijalankan dan memiliki konfigurasi test, maka akan me-return 5
        5
    } else if should_run { // if ia bukan test namun ia harus dijalankan, maka cetak sesuatu. Jika Anda menjalankan test. ia akan mengabaikan statement println!
        println!("Returning 5. This is not a test");
        5
    } else {
        println!("This shouldn't run, returning 0."); // sebaliknya, return 0
        0
    }
}

fn main() {
    bring_number(true);
    bring_number(false);
}
```

Sekarang ia akan berjalan secara berbeda, tergantung dari konfigurasinya. Jika Anda hanya menjalankan programnya, hasil cetaknya adalah seperti ini:

```text
Returning 5. This is not a test
This shouldn't run, returning 0.
```

Namun jika Anda menjalankannya di dalam test mode (`cargo test` untuk Rust yang ada pada komputer), maka ia akan menjalankan testnya. Dan karena di kasus ini testnya selalu me-return 5, testnya akan pass.

```text
running 1 test
test testing::check_if_five ... ok

test result: ok. 1 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out
```



## Writing macros

Membuat macro bisa menjadi hal yang rumit. Anda hampir tidak perlu untuk membuatnya, namun terkadang Anda mungkin ingin membuatnya karena hal ini menyenangkan meskipun cukup menantang. Membuat macro sangatlah menarik karena bisa dikatakan bahwa membuat macro ini merupakan bahasa yang hampir berbeda. Untuk membuatnya, Anda sebenarnya perlu menggunakan macro lain yang bernama `macro_rules!`. Kemudian Anda menambahkan nama macro Anda dan block `{}`. Di dalamnya ada semacam statement `match`.

Contoh di bawah ini hanya memerlukan `()`, kemudian hanya me-return 6:

```rust
macro_rules! give_six {
    () => {
        6
    };
}

fn main() {
    let six = give_six!();
    println!("{}", six);
}
```

Tapi ia sama sekali bukan statement `match`, karena macro sebenarnya tidak meng-compile apapun. Ia mhanya mengambil input dan memberikan output. Kemudian compiler memeriksa untuk melihat apakah macro rulenya masuk akal. Itulah sebabnya mengapa macro seperti "code yang menuliskan code". Anda akan mengingat bahwa sebuah statement `match` perlu untuk me-return type yang sama, sehingga code di bawah ini tidak akan berjalan:

```rust
fn main() {
// ⚠️
    let my_number = 10;
    match my_number {
        10 => println!("You got a ten"),
        _ => 10,
    }
}
```

Compiler akan memberikan pesan teguran bahwa Anda ingin me-return `()` di satu arm, dan me-return `i32` di arm yang lainnya.

```text
error[E0308]: `match` arms have incompatible types
 --> src\main.rs:5:14
  |
3 | /     match my_number {
4 | |         10 => println!("You got a ten"),
  | |               ------------------------- this is found to be of type `()`
5 | |         _ => 10,
  | |              ^^ expected `()`, found integer
6 | |     }
  | |_____- `match` arms have incompatible types
```

Namun macro tidak peduli tentang itu, karena ia hanya memberikan output. Ia bukanlah compiler - ia hanyalah code yang dilandasi oleh code yang lain. Sehingga Anda bisa melakukan hal seperti ini:

```rust
macro_rules! six_or_print {
    (6) => {
        6
    };
    () => {
        println!("You didn't give me 6.");
    };
}

fn main() {
    let my_number = six_or_print!(6);
    six_or_print!();
}
```

Semuanya berjalan normal, dan hasil cetaknya adalah `You didn't give me 6.`. Anda juga bisa melihat bahwa itu bukanlah arm yang ada pada match karena disitu tidak ada case `_`. Kita hanya bisa memberikannya `(6)`, atau `()`. Selain daripada itu akan membuat error. Dan angka `6` yang kita berikan itu pun sebenarnya bukanlah `i32`, ia hanyalah inputan 6. Anda sebenarnya bisa mengatur apapun sebagai input untuk macro, karena ia hanya melihat input untuk melihat apa yang didapatkannya. Contohnya:

```rust
macro_rules! might_print {
    (THis is strange input 하하はは哈哈 but it still works) => {
        println!("You guessed the secret message!")
    };
    () => {
        println!("You didn't guess it");
    };
}

fn main() {
    might_print!(THis is strange input 하하はは哈哈 but it still works);
    might_print!();
}
```

Jadinya, macro aneh yang kita buat ini hanya memberikan respond pada dua hal: `()` dan `(THis is strange input 하하はは哈哈 but it still works)`. Tidak ada selain itu. Hasil cetaknya adalah:

```text
You guessed the secret message!
You didn't guess it
```

Jadi, macro itu sendiri tepatnya bukanlah syntax yang umumnya ada pada Rust. Namun macro juga bisa memahami type yang berbeda dari input yang Anda berikan. Lihatlah contoh ini:

```rust
macro_rules! might_print {
    ($input:expr) => {
        println!("You gave me: {}", $input);
    }
}

fn main() {
    might_print!(6);
}
```

Ia akan mencetak `You gave me: 6`. Bagian `$input:expr` adalah bagian yang penting. Ini berarti "untuk sebuah expression, berikan ia nama variabel $input". Di dalam macro, variabel dimulai dengan `$`. Di dalam macro ini, jika Anda memberikan satu expression, ia akan mencetaknya. Mari kita coba lagi:

```rust
macro_rules! might_print {
    ($input:expr) => {
        println!("You gave me: {:?}", $input); // Sekarang kita menggunakan {:?} karena kita akan memberikannya jenis expression yang berbeda
    }
}

fn main() {
    might_print!(()); // berikan ia ()
    might_print!(6); // berikan ia 6
    might_print!(vec![8, 9, 7, 10]); // berikan ia vec
}
```

Hasil cetaknya adalah:

```text
You gave me: ()
You gave me: 6
You gave me: [8, 9, 7, 10]
```

Perhatikan juga bahwa kita menuliskan `{:?}`, namun ia tidak memeriksa apakah `&input` mengimplementasikan `Debug`. Ia hanya akan menuliskan code dan mencoba membuatnya ter-compile, dan jika tidak maka ia akan memberikan error.

Jadi apa saja yang bisa dilihat oleh macro selain `expr`? Mereka adalah: `block | expr | ident | item | lifetime | literal  | meta | pat | path | stmt | tt | ty | vis`. Ini adalah bagian yang rumit. Anda bisa melihat apa arti dari masing-masing macro attribute tersebut [di sini](https://doc.rust-lang.org/beta/reference/macros-by-example.html), yang mana laman tersebut menjelaskan:

```text
item: an Item
block: a BlockExpression
stmt: a Statement without the trailing semicolon (except for item statements that require semicolons)
pat: a Pattern
expr: an Expression
ty: a Type
ident: an IDENTIFIER_OR_KEYWORD
path: a TypePath style path
tt: a TokenTree (a single token or tokens in matching delimiters (), [], or {})
meta: an Attr, the contents of an attribute
lifetime: a LIFETIME_TOKEN
vis: a possibly empty Visibility qualifier
literal: matches -?LiteralExpression
```

Ada situs bagus lainnya yang bernama cheats.rs yang menjelaskan semua macro attribute tersebut. Anda bisa membacanya penjelasannya [di sini](https://cheats.rs/#macros-attributes) dan disana ada contoh untuk masing-masing macro attribute yang disebutkan itu.

Namun, untuk kebanyakan macro Anda biasanya akan menggunakan `expr`, `ident`, dan `tt`. `ident` berarti adalah identifier dan ia berguna untuk nama variabel atau nama function. `tt` adalah token tree dan semacamnya yang berarti itu adalah semua jenis inputan. Mari kita coba buat macro sederhana dengan kedua macro attribute tersebut.

```rust
macro_rules! check {
    ($input1:ident, $input2:expr) => {
        println!(
            "Is {:?} equal to {:?}? {:?}",
            $input1,
            $input2,
            $input1 == $input2
        );
    };
}

fn main() {
    let x = 6;
    let my_vec = vec![7, 8, 9];
    check!(x, 6);
    check!(my_vec, vec![7, 8, 9]);
    check!(x, 10);
}
```

Jadi, macro di atas akan mengambil satu `ident` (seperti nama variabel) dan sebuah expression, dan melihat apakah `ident` dan `expr` tersebut sama. Hasil cetaknya adalah:

```text
Is 6 equal to 6? true
Is [7, 8, 9] equal to [7, 8, 9]? true
Is 6 equal to 10? false
```

Dan ini adalah satu macro yang mengambil `tt` dan mencetaknya. Macro tersebut akan menggunakan macro lainnya yang bernama `stringify!` untuk membuatnya menjadi string terlebih dahulu.

```rust
macro_rules! print_anything {
    ($input:tt) => {
        let output = stringify!($input);
        println!("{}", output);
    };
}

fn main() {
    print_anything!(ththdoetd);
    print_anything!(87575oehq75onth);
}
```

Hasil cetaknya adalah:

```text
ththdoetd
87575oehq75onth
```

Tetapi ia tidak akan mencetak apapun apabila kita memberikan sesuatu dengan spasi, koma, dll. Ia akan mengira bahwa kita memberikannya lebih dari satu item atau informasi tambahan, sehingga ia akan menjadi bingung.

Di sinilah macro mulai menjadi sulit untuk dibuat.

Untuk memberi macro lebih dari satu item, kita perlu menggunakan syntax yang berbeda. Alih-alih menggunakan `$input`, kita akan menggunakan `$($input1),*`. Ini berarti nol, satu atau lebih dari satu (inilah apa yang dimaksud dengan *), dipisahkan dengan koma. Jika Anda menginginkan satu atau lebih, gunakan `+` alih-alih menggunakan `*`.

Sekarang macro kita menjadi seperti ini:

```rust
macro_rules! print_anything {
    ($($input1:tt),*) => {
        let output = stringify!($($input1),*);
        println!("{}", output);
    };
}


fn main() {
    print_anything!(ththdoetd, rcofe);
    print_anything!();
    print_anything!(87575oehq75onth, ntohe, 987987o, 097);
}
```

Sehingga ia akan mengambil apapun token tree yang dipisahkan dengan koma, dan menggunakan `stringify!` untuk membuatnya menjadi string, kemudian mencetaknya. Hasilnya adalah sebagai berikut:

```text
ththdoetd, rcofe

87575oehq75onth, ntohe, 987987o, 097
```

Jika kita menggunakan `+` menggantikan `*`, ia akan memberikan error, karena terkadang kita tidak memberikan input. Sehingga `*` adalah pilihan yang lebih aman.

Jadi, sekarang kita bisa mulai melihat power dari macro. Pada contoh kali ini, kita sebenarnya bisa membuat function kita sendiri:

```rust
macro_rules! make_a_function {
    ($name:ident, $($input:tt),*) => { // Pertama, Anda berikan ia satu nama untuk function tersebut, lalu kemudian memeriksa yang lainnya
        fn $name() {
            let output = stringify!($($input),*); // Ia membuat segala sesuatunya menjadi string
            println!("{}", output);
        }
    };
}


fn main() {
    make_a_function!(print_it, 5, 5, 6, I); // Kita ingin membuat function bernama print_it() yang mencetak apapun yang kita berikan
    print_it();
    make_a_function!(say_its_nice, this, is, really, nice); // Yang dilakukan pada bagian ini juga sama, namun kita mengubah nama functionnya
    say_its_nice();
}
```

Hasil cetaknya adalah:

```text
5, 5, 6, I
this, is, really, nice
```


Jadi sekarang kita bisa mulai memahami macro lainnya. Anda bisa melihat bahwa beberapa macro yang pernah kita gunakan ternyata sangatlah sederhana. Salah satu contohnya adalah `write!` yang biasa kita gunakan untuk menulis ke file:

```rust
macro_rules! write {
    ($dst:expr, $($arg:tt)*) => ($dst.write_fmt($crate::format_args!($($arg)*)))
}
```

Jadi untuk menggunakannya, Anda perlu memasukkan ini:

- sebuah expression (`expr`) yang mengambil nama variabel `$dst`.
- apapu yang ada setelahnya. Jika disitu tertulis `$arg:tt` maka ia hanya bisa mengambil satu argument, tapi karena disitu tertulis `$($arg:tt)*` ia akan mengambil nol, satu, atau banyak argument.

Kemudian ia mengambil `$dst` dan menggunakan method `write_fmt` pada `$dst` tersebut. Di dalamnya, ia menggunakan macro lainnya yang bernama `format_args!` yang mengambil semua `$($arg)*`, atau semua argument yang kita masukkan.



Sekarang saatnya kita melihat isi dari macro `todo!`. Macro ini digunakan ketika Anda menginginkan programnya tercompile namun beberapa bagian codenya belum dituliskan. Berikut isi dari macro tersebut:

```rust
macro_rules! todo {
    () => (panic!("not yet implemented"));
    ($($arg:tt)+) => (panic!("not yet implemented: {}", $crate::format_args!($($arg)+)));
}
```

Macro ini memiliki dua opsi: Anda bisa memasukkan `()`, atau beberapa token tree (`tt`).

- Jika Anda memasukkan `()`, ia akan menggunakan `panic!` dengan sebuah pesan. Jadi sebenarnya Anda bisa menulis `panic!("not yet implemented")` untuk menggantikan `todo!` dan ia akan melakukan hal yang sama.
- Jika Anda memasukkan beberapa argument, ia akan mencoba untuk mencetaknya. Anda bisa melihat hal yang sama di dalam macro `format_args!` macro, yang mana bekerja seperti `println!`.

Jadi jika Anda menuliskan ini, ia pun juga akan berjalan:

```rust
fn not_done() {
    let time = 8;
    let reason = "lack of time";
    todo!("Not done yet because of {}. Check back in {} hours", reason, time);
}

fn main() {
    not_done();
}
```

Hasilnya adalah:

```text
thread 'main' panicked at 'not yet implemented: Not done yet because of lack of time. Check back in 8 hours', src/main.rs:4:5
```


Di dalam sebuah macro, Anda bahkan bisa memanggil macro yang sama. Seperti ini contohnya:

```rust
macro_rules! my_macro {
    () => {
        println!("Let's print this.");
    };
    ($input:expr) => {
        my_macro!();
    };
    ($($input:expr),*) => {
        my_macro!();
    }
}

fn main() {
    my_macro!(vec![8, 9, 0]);
    my_macro!(toheteh);
    my_macro!(8, 7, 0, 10);
    my_macro!();
}
```

Macro ini mengambil `()`, atau satu expression, atau banyak expression. Tapi ia akan mengabaikan semua expression yang diberikan, tidak peduli apapun yang Anda masukkan, dan kita hanya bisa memanggil `my_macro!` dengan `()`. Sehingga outputnya adalah `Let's print this` yang dicetak sebanyak empat kali.

Anda bisa melihat hal yang sama pada macro `dbg!`, yang mana ia memanggil dirinya sendiri.

```rust
macro_rules! dbg {
    () => {
        $crate::eprintln!("[{}:{}]", $crate::file!(), $crate::line!()); //$crate artinya adalah crate yang berada di dalamnya.
    };
    ($val:expr) => {
        // Penggunaan `match` di sini memanglah disengaja karena ia akan memengaruhi lifetime
        // https://stackoverflow.com/a/48732525/1063961
        match $val {
            tmp => {
                $crate::eprintln!("[{}:{}] {} = {:#?}",
                    $crate::file!(), $crate::line!(), $crate::stringify!($val), &tmp);
                tmp
            }
        }
    };
    // Koma yang mengikuti sebuah argument (koma yang ditulis setelah ditulisnya satu argument, tanpa ada argument lanjutan) akan diabaikan
    ($val:expr,) => { $crate::dbg!($val) };
    ($($val:expr),+ $(,)?) => {
        ($($crate::dbg!($val)),+,)
    };
}
```

(`eprintln!` sama seperti `println!`. Yang membedakannya adalah ia akan mencetak ke `io::stderr`, bukan mencetak ke `io::stdout` seperti yang dilakukan oleh `println!`. Ada juga `eprint!` yang tidak menambahkan baris baru)

Jadinya, kita akan mencoba macro tersebut.

```rust
fn main() {
    dbg!();
}
```

Macro tersebut cocok dengan arm yang pertama, sehingga ia akan mencetak nama file dan nomor line dengan menggunakan macro `file!` dan `line!`. Hasil cetaknya adalah `[src/main.rs:2]`.

Akan kita coba dengan vec:

```rust
fn main() {
    dbg!(vec![8, 9, 10]);
}
```

Ini cocok dengan arm yang selanjutnya (arm kedua), karena ia hanya memiliki satu expression. Ia akan memanggil input `tmp` dan menggunakan code: ` $crate::eprintln!("[{}:{}] {} = {:#?}", $crate::file!(), $crate::line!(), $crate::stringify!($val), &tmp);`. Sehingga ia akan mencetak dengan macro `file!` dan `line!`, kemudian membuat `$val` menjadi `String`, dan juga pretty print `{:#?}` untuk `tmp`. Sehingga inputan vec kita itu akan memberi output seperti ini:

```text
[src/main.rs:2] vec![8, 9, 10] = [
    8,
    9,
    10,
]
```

Dan selebihnya, ia hanya memanggil `dbg!` pada dirinya sendiri meskipun Anda memasukkan koma tambahan.

Sebagaimana yang bisa kita lihat, macro sangatlah rumit! Biasanya, kita hanya ingin menggunakan macro yang melakukan sesuatu secara otomatis yang mana tidak bisa dilakukan oleh function sederhana. Cara terbaik untuk mempelajari macro adalah melihat pada contoh macro yang lainnya. Tidak banyak orang yang bisa menulis macro dengan cepat tanpa mendapatkan masalah apapun. Jadi jangan berpikir bahwa Anda perlu mengetahui semua tentang macro untuk mengetahui cara membuat program di Rust. Namun jika Anda membaca macro lainnya yang sudah ada, dan mencoba mengubahnya sedikit-sedikit, Anda bisa dengan mudah meminjam "kekuatan" dari macro ini. Dan kemudian Anda mungkin mulai merasa nyaman untuk menulis macro Anda sendiri.


# Part 2 - Rust on your computer

Anda bisa melihat bahwa kita bisa mempelajari hampir semua yang ada di Rust hanya dengan menggunakan Playground. Tapi jika Anda mempelajari semuanya sejauh  ini, mungkin saja Anda menginginkan Rust di komputer Anda sekarang. Selalu ada hal-hal yang tidak bisa Anda lakukan di Playground, misalnya menggunakan file atau code yang memiliki lebih dari satu file. Beberapa hal lain yang membuat Anda membutuhkan Rust di komputer Anda adalah untuk mengambil inputan dari user dan juga flag. Namun hal terpenting yang bisa dilakukan oleh Rust yang terinstall di komputer adalah Anda bisa menggunakan crate. Kita telah mempelajari tentang crate, namun di Playground kita hanya bisa menggunakan crate-crate yang paling populer saja. Jadi dengan Rust yang telah terinstall di komputer kita bisa menggunakan crate apapun untuk program yang kita buat.

## cargo

`rustc` adalah singkatan dari Rust Compiler, dan perintah itulah yang sebenarnya digunakan saat melakukan compiling. Rust file diakhiri dengan ekstensi `.rs`. Namun pada umumnya banyak orang yang tidak menuliskan `rustc main.rs` untuk melakukan compile. Mereka biasanya menggunakan sesuatu yang biasanya disebut sebagai `cargo`, yang mana ini adalah package manager untuk Rust.

Satu catatan tentang nama `cargo`: ia disebut `cargo` karena di saat Andan meletakkan crates (peti) bersama-sama, Anda akan mendapatkan cargo. Sebuah peti adalah kotak kayu yang biasanya Anda lihat di kapal ataupun di truk, namun Anda mengingat bahwa setiap project di Rust juga disebut sebagai crate. Kemudian, di saat Anda menggabungkan semua crate-crate tersebut, Anda akan mendapatkan cargo.

Anda bisa melihat ini di saat Anda menggunakan cargo untuk menjalankan sebuah project. Mari kita mencoba melakukan sesuatu yang sederhana menggunakan `rand`: kita akan secara random memilih antara 8 huruf.

```rust
use rand::seq::SliceRandom; // gunakan ini untuk mengaplikasikan .choose terhadap slices

fn main() {

    let my_letters = vec!['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h'];

    let mut rng = rand::thread_rng();
    for _ in 0..6 {
        print!("{} ", my_letters.choose(&mut rng).unwrap());
    }
}
```

Kita akan mendapatkan output seperti `b c g h e a`. Namun pertama-taman kita ingin melihat apa yang `cargo` lakukan. Untuk menggunakan `cargo` dan menjalankan program kita, biasanya kita menggunakan `cargo run`. Ia akan mem-build program kita dan menjalankannya. Namun di saat ia mulai melakukan compiling, ia melakukan hal seperti ini:

```text
   Compiling getrandom v0.1.14
   Compiling cfg-if v0.1.10
   Compiling ppv-lite86 v0.2.8
   Compiling rand_core v0.5.1
   Compiling rand_chacha v0.2.2
   Compiling rand v0.7.3
   Compiling rust_book v0.1.0 (C:\Users\mithr\OneDrive\Documents\Rust\rust_book)
    Finished dev [unoptimized + debuginfo] target(s) in 13.13s
     Running `C:\Users\mithr\OneDrive\Documents\Rust\rust_book\target\debug\rust_book.exe`
g f c f h b
```

Jadi terlihat bahwa ia sepertinya tidak hanya menggunakan crate `rand`, namun ada beberapa crate lainnya juga. Ini dikarenakan kita memerlukan `rand`, namun `rand` juga memiliki beberapa bagian code yang memerlukan crate-crate lainnya. Sehingga `cargo` akan mencari semua crate yang kita perlukan dan memasukkan semuanya bersamaan. Di kasus kita ini, kita hanya memerlukan tujuh buah crate. Namun pada project yang besar Anda mungkin bisa memerlukan 200 atau lebih banyak crate yang harus dimasukkan ke project tersebut.

Ini adalah dimana Anda bisa melihat tradeoff pada Rust. Rust benar-benar sangat cepat, karena ia sebelumnya telah melakukan compile sebelum programnya digunakan. Hal ini dilakukan dengan cara (compilernya) melihat semua codenya dan memeriksa apa yang sebenarnya dilakukan oleh code yang kita tuliskan. Sebagai contoh, Anda menuliskan sebuah generic function:

```rust
use std::fmt::Display;

fn print_and_return_thing<T: Display>(input: T) -> T {
    println!("You gave me {} and now I will give it back.", input);
    input
}

fn main() {
    let my_name = print_and_return_thing("Windy");
    let small_number = print_and_return_thing(9.0);
}
```

Function ini bisa mengambil apapun yang memiliki trait `Display`, sehingga kita membarikannya `&str` dan selanjutnya `f64`, dan kita pun tidak mendapatkan masalah. Namun compiler tidak melihat ke generic, karena ia tidak ingin melakukan apapun di saat runtime (perlu diingat kembali, compiler harus mengetahui typenya di saat compile time). Compiler ingin membuat program yang bisa berjalan dengan sendirinya secepat mungkin. Sehingga di saat compiler melihat `"Windy"`, ia tidak melihat functionnya sebagai `fn print_and_return_thing<T: Display>(input: T) -> T`. Ia akan meliha function tersebut seperti `fn print_and_return_thing(input: &str) -> &str`. Dan selanjutnya compiler akan melihat functionnya seperti `fn print_and_return_thing(input: f64) -> f64`. Semua pemeriksaan mengenai trait dan lainnya diselesaikan saat compile time. Ini sebabnya mengapa generic memakan waktu yang lebih lama untuk di-compile, karena ia perlu mengetahui semua posibilitas type yang digunakan, dan membuatnya menjadi concrete.

Satu hal lagi: Rust di 2020 sedang berupaya keras untuk mengupgrade compile time, karena bagian inilah yang memakan waktu paling lama. Setiap version di Rust menjadi sedikit lebih cepat saat melakukan compiling, dan ada beberapa rencana lain untuk mempercepatnya. Untuk saat ini, inilah yang harus Anda ketahui:

- `cargo build` akan mem-build program Anda, sehingga Anda bisa menjalankannya
- `cargo run` akan mem-build program Anda dan menjalankannya sekaligus
- `cargo build --release` dan `cargo run --release` akan melakukan hal yang sama namun di dalam mode release. Apa itu? Mode release berguna saat code Anda telah selesai dibuat. Kemudian Rust akan memerlukan waktu yang lebih lama untuk meng-compile, tapi compiler melakukan ini karena compiler akan melakukan apapun yang ia ketahui dan yang ia bisa untuk membuat programnya menjadi lebih cepat. Program dari mode release sebenarnya *jauh lebih cepat* daripada menggunakan mode regular, yang mana biasa disebut dengan mode debug. Ini dikarenakan ia meng-compile lebih cepat dan memiliki lebih banyak informasi debug. `cargo build` yang biasa (regular) biasa disebut dengan "debug build" dan `cargo build --release` biasa disebut dengan "release build".
- `cargo check` adalah cara untuk memeriksa code Anda. Ia mirip seperti melakukan compiling, namun ia tidak benar-benar membuatkan programnya. Ini adalah cara yang baik yang sering digunakan untuk memeriksa code karena ia tidak memakan waktu lama seperti `build` ataupun `run`.

Ah ya, `--release` adalah bagian dari perintah yang biasa disebut dengan `flag`. Yang mana itu adalah informasi extra di dalam sebuah perintah.

Hal-hal lain yang perlu Anda ketahui adalah:

- `cargo new`. Anda menggunakan ini untuk membuat project Rust yang baru. Setelah `new`, tuliskany nama projectnya dan `cargo` akan membuat folder dan semua file yang Anda perlukan.
- `cargo clean`. Di saat Anda menambahkan crate pada `Cargo.toml`, computer akan men-download semua file yang diperlukan dan crate-crate ini akan memakan banyak space di harddisk Anda. Jika Anda tidak menginginkan crate-crate itu lagi pada komputer Anda, tuliskan perintah `cargo clean`.

Satu hal lagi tentang compiler: ia hanya membutuhkan waktu paling lama di saat Anda menggunakan `cargo build` atau `cargo run` untuk pertama kalinya. Setelah itu compilernya akan mengingatnya, dan selanjutnya ia akan melakukan compile dengan cepat lagi. Namun jika Anda menggunakan `cargo clean` dan kemudian menggunakan perintah `cargo build`, ia akan sekali lagi melakukan compile dengan lambat.


## Taking user input

Cara termudah untuk mendapatkan input dari user adalah dengan menggunakan `std::io::stdin`. Ini berarti "standard in", yang mana itu adalah input yang masuk dari keyboard. Dengan `stdin()` Anda bisa mengapatkan inputan dari user, tapi Anda ingin meletakkannya pada type `&mut String` dengan method `.read_line()`. Ini adalah contohnya. Programnya akan bekerja, namun tidak bekerja dengan semestinya:

```rust
use std::io;

fn main() {
    println!("Please type something, or x to escape:");
    let mut input_string = String::new();

    while input_string != "x" { // Ini adalah bagian dimana programnya tidak bekerja dengan semestinya
        input_string.clear(); // Pertama kita clear Stringnya. Jika tidak, ia akan terus bertambah
        io::stdin().read_line(&mut input_string).unwrap(); // dapatkan stdin dari user, dan masukkan ke read_string
        println!("You wrote {}", input_string);
    }
    println!("See you later!");
}
```

Maka seperti inilah outputnya:

```text
Please type something, or x to escape:
something
You wrote something

Something else
You wrote Something else

x
You wrote x

x
You wrote x

x
You wrote x
```

Ia mengambil input yang kita berikan dan mengembalikannya, dan ia pun tahu bahwa kita menuliskan `x`. Hanya saja, ia tidak keluar dari programnya. Cara stu-satunya untuk keluar dari program tersebut adalah dengan menggunakan menutup window dimana Terminalnya terbuka, atau menggunakan Ctrl+c. Mari kita ubah `{}` menjadi `{:?}` di `println!` untuk mendapatkan informasi (atau Anda bisa menggunakan `dbg!(&input_string)` jika Anda menyukai macro tersebut). Sekarang outputnya menjadi seperti ini:

```text
Please type something, or x to escape:
something
You wrote "something\r\n"
Something else
You wrote "Something else\r\n"
x
You wrote "x\r\n"
x
You wrote "x\r\n"
```



Ini dikarenakan inputan dari keyboard sebenarnya tidak hanya mendapatkan tulisan `something`. Ia sebenarnya mendapatkan tulisan `something` dan juga `Enter`. Ada method yang mudah digunakan yang digunakan untuk memperbaiki hal ini, namanya adalah `.trim()`, yang mana akan menghapus semua whitespace. Whitespace, adalah semua [karakter yang terdaftar di sini](https://doc.rust-lang.org/reference/whitespace.html):

```text
U+0009 (horizontal tab, '\t')
U+000A (line feed, '\n')
U+000B (vertical tab)
U+000C (form feed)
U+000D (carriage return, '\r')
U+0020 (space, ' ')
U+0085 (next line)
U+200E (left-to-right mark)
U+200F (right-to-left mark)
U+2028 (line separator)
U+2029 (paragraph separator)
```

Sehingga ia akan mengubah `x\r\n` menjadi hanya `x`. Dengan itu, program kita sudah berjalan sebagaimana semestinya:

```rust
use std::io;

fn main() {
    println!("Please type something, or x to escape:");
    let mut input_string = String::new();

    while input_string.trim() != "x" {
        input_string.clear();
        io::stdin().read_line(&mut input_string).unwrap();
        println!("You wrote {}", input_string);
    }
    println!("See you later!");
}
```

Inilah outputnya:

```text
Please type something, or x to escape:
something
You wrote something

Something
You wrote Something

x
You wrote x

See you later!
```



Ada inputan user berjenis lain yang biasanya disebut `std::env::Args` (env adalah environment). `Args` adalah apa yang user tuliskan saat memulai program. Sebenarnya selalu ada setidaknya satu buah `Arg` dalam sebuah program. Mari kita buat program yang hanya mencetak menggunakan `std::env::args()` untuk melihat apa sebenarnya `Args` ini.

```rust
fn main() {
    println!("{:?}", std::env::args());
}
```

Jika kita menjalankan `cargo run` maka ia mencetak sesuatu seperti ini:

```text
Args { inner: ["target\\debug\\rust_book.exe"] }
```

Mari kita berikan lebih banyak input dan melihat apa yang dilakukannya. Kita akan menuliskan `cargo run but with some extra words`. Outputnya adalah seperti berikut:

```text
Args { inner: ["target\\debug\\rust_book.exe", "but", "with", "some", "extra", "words"] }
```

Menarik. Dan saat kita melihat pada [laman tentang Args](https://doc.rust-lang.org/std/env/struct.Args.html), kita melihat bahwa ia mengimplementasikan `IntoIterator`. Yang berarti kita bisa melakukan semua hal yang kita ketahui tentang iterator untuk membacanya dan juga mengubahnya. Mari kita coba:

```rust
use std::env::args;

fn main() {
    let input = args();

    for entry in input {
        println!("You entered: {}", entry);
    }
}
```

Outputnya adalah:

```text
You entered: target\debug\rust_book.exe
You entered: but
You entered: with
You entered: some
You entered: extra
You entered: words
```

Anda bisa melihat bahwa argument pertama selalu menuliskan nama programnya, sehingga Anda seringkali ingin mengabaikannya, seperti ini:

```rust
use std::env::args;

fn main() {
    let input = args();

    input.skip(1).for_each(|item| {
        println!("You wrote {}, which in capital letters is {}", item, item.to_uppercase());
    })
}
```

Outputnya adalah seperti ini:

```text
You wrote but, which in capital letters is BUT
You wrote with, which in capital letters is WITH
You wrote some, which in capital letters is SOME
You wrote extra, which in capital letters is EXTRA
You wrote words, which in capital letters is WORDS
```

Penggunaan paling umum dari `Args` adalah untuk memasukkan setting dari user. Anda bisa memastikan bahwa user menuliskan input yang Anda butuhkan, dan hanya menjalankan programnya jika inputannya benar. Ini adalah program sederhana yang membuat outputnya menjadi huruf besar (capital) atau huruf kecil (lowercase):

```rust
use std::env::args;

enum Letters {
    Capitalize,
    Lowercase,
    Nothing,
}

fn main() {
    let mut changes = Letters::Nothing;
    let input = args().collect::<Vec<_>>();

    if input.len() > 2 {
        match input[1].as_str() {
            "capital" => changes = Letters::Capitalize,
            "lowercase" => changes = Letters::Lowercase,
            _ => {}
        }
    }

    for word in input.iter().skip(2) {
      match changes {
        Letters::Capitalize => println!("{}", word.to_uppercase()),
        Letters::Lowercase => println!("{}", word.to_lowercase()),
        _ => println!("{}", word)
      }
    }
    
}
```

Berikut adalah beberapa contoh outputnya:

Input: `cargo run please make capitals`:

```text
make capitals
```

Input: `cargo run capital`:

```text
// Nothing here...
```

Input: `cargo run capital I think I understand now`:

```text
I
THINK
I
UNDERSTAND
NOW
```

Input: `cargo run LOWERCASE Does this work too`

```text
Does
this
work
too
```



Selain `Args` yang bisa mengambil inputan dari user melalui `std::env::args()`, ada juga `Vars` yang mana ia adalah system variable. Itu adalah setting dasar untuk program yang tidak diketikkan oleh pengguna. Anda bisa menggunakan `std::env::vars()` untuk melihat semua setting tersebut sebagai `(String, String)`. Dan ada banyak sekali. Contohnya:

```rust
fn main() {
    for item in std::env::vars() {
        println!("{:?}", item);
    }
}
```

Dengan menuliskan code seperti di atas, Anda bisa melihat semua informasi tentang user session. Ia akan menampilkan informasi seperti ini:

```text
("CARGO", "/playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo")
("CARGO_HOME", "/playground/.cargo")
("CARGO_MANIFEST_DIR", "/playground")
("CARGO_PKG_AUTHORS", "The Rust Playground")
("CARGO_PKG_DESCRIPTION", "")
("CARGO_PKG_HOMEPAGE", "")
("CARGO_PKG_NAME", "playground")
("CARGO_PKG_REPOSITORY", "")
("CARGO_PKG_VERSION", "0.0.1")
("CARGO_PKG_VERSION_MAJOR", "0")
("CARGO_PKG_VERSION_MINOR", "0")
("CARGO_PKG_VERSION_PATCH", "1")
("CARGO_PKG_VERSION_PRE", "")
("DEBIAN_FRONTEND", "noninteractive")
("HOME", "/playground")
("HOSTNAME", "f94c15b8134b")
("LD_LIBRARY_PATH", "/playground/target/debug/build/backtrace-sys-3ec4c973f371c302/out:/playground/target/debug/build/libsqlite3-sys-fbddfbb9b241dacb/out:/playground/target/debug/build/ring-cadba5e583648abb/out:/playground/target/debug/deps:/playground/target/debug:/playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib:/playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib")
("PATH", "/playground/.cargo/bin:/playground/.cargo/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin")
("PLAYGROUND_EDITION", "2018")
("PLAYGROUND_TIMEOUT", "10")
("PWD", "/playground")
("RUSTUP_HOME", "/playground/.rustup")
("RUSTUP_TOOLCHAIN", "stable-x86_64-unknown-linux-gnu")
("RUST_RECURSION_COUNT", "1")
("SHLVL", "1")
("SSL_CERT_DIR", "/usr/lib/ssl/certs")
("SSL_CERT_FILE", "/usr/lib/ssl/certs/ca-certificates.crt")
("USER", "playground")
("_", "/usr/bin/timeout")
```

Jadi jika Anda memerlukan informasi ini, `Vars` adalah hal yang Anda perlukan.

Cara termudah untuk mendapatkan single information dari `Var` adalah menggunakan macro `env!`. Anda cukup memberikannya nama variabel, dan ia akan memberikan kembalian value yang berupa `&str`. Ini tidak akan berfungsi jika variabelnya dituliskan dengan salah (typo) atau memang tidak ada, jadinya jika Anda tidak yakin maka gunakan `option_env!`. Jika kita menuliskan seperti ini di Playground:

```rust
fn main() {
    println!("{}", env!("USER"));
    println!("{}", option_env!("ROOT").unwrap_or("Can't find ROOT"));
    println!("{}", option_env!("CARGO").unwrap_or("Can't find CARGO"));
}
```

maka kita akan mendapatkan output:

```text
playground
Can't find ROOT
/playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo
```

Jadi, `option_env!` akan selalu menjadi macro yang lebih aman untuk hal ini. `env!` lebih baik digunakan jika sebenarnya Anda menginginkan programnya menjadi crash di saat Anda tidak bisa menemukan environment variablenya.



## Using files

Sekarang setelah kita menggunakan Rust di komputer, kita dapat mulai bekerja dengan file. Anda akan melihat bahwa sekarang kita akan mulai melihat lebih banyak `Result` di dalam kode kita. Itu dikarenakan saat kita mulai bekerja dengan file dan hal semacamnya, besar kemungkinan kita melakukan kesalahan. Bisa saja mungkin filenya tidak ada di sana (tidak bisa mengaksesnya), atau bisa jadi juga mungkin komputer kita tidak dapat membacanya. 

Anda mungkin masih ingat bahwa jika Anda menggunakan operator `?`, ia akan mengmbalikan `Result` pada function tempat ia berada. Jika Anda tidak bisa mengingat error typenya, anda bisa mengosongkannya (dengan `()`) dan biarkan compiler yang memberitahukannya kepada Anda. Mari kita coda dengan sebuah function yang mencoba untuk membuat sebuah angkan menggunakan method `.parse()`.

```rust
// ⚠️
fn give_number(input: &str) -> Result<i32, ()> {
    input.parse::<i32>()
}

fn main() {
    println!("{:?}", give_number("88"));
    println!("{:?}", give_number("5"));
}
```

Compiler memberi tahu kita secara tepat tentang apa yang harus kita lakukan:

```text
error[E0308]: mismatched types
 --> src\main.rs:4:5
  |
3 | fn give_number(input: &str) -> Result<i32, ()> {
  |                                --------------- expected `std::result::Result<i32, ()>` because of return type
4 |     input.parse::<i32>()
  |     ^^^^^^^^^^^^^^^^^^^^ expected `()`, found struct `std::num::ParseIntError`
  |
  = note: expected enum `std::result::Result<_, ()>`
             found enum `std::result::Result<_, std::num::ParseIntError>`
```

Mantap! Jadi kita cukup mengubah returnnya menjadi apa yang compiler katakan:

```rust
use std::num::ParseIntError;

fn give_number(input: &str) -> Result<i32, ParseIntError> {
    input.parse::<i32>()
}

fn main() {
    println!("{:?}", give_number("88"));
    println!("{:?}", give_number("5"));
}
```

Sekarang programnya berjalan!

```text
Ok(88)
Ok(5)
```

Jadi sekarang kita ingin menggunakan `?` agar langsung memberikan valuenya jika programnya berjalan, dan memberikan error jika programnya tidak bisa dijalankan. Tapi bagaimana caranya melakukan hal tersebut di dalam `fn main()`? Jika kita mencoba untuk menggunakan `?` di dalam `main()`, maka ia tidak akan berfungsi.

```rust
// ⚠️
use std::num::ParseIntError;

fn give_number(input: &str) -> Result<i32, ParseIntError> {
    input.parse::<i32>()
}

fn main() {
    println!("{:?}", give_number("88")?);
    println!("{:?}", give_number("5")?);
}
```

Compiler akan memunculkan ini:

```text
error[E0277]: the `?` operator can only be used in a function that returns `Result` or `Option` (or another type that implements `std::ops::Try`)
  --> src\main.rs:8:22
   |
7  | / fn main() {
8  | |     println!("{:?}", give_number("88")?);
   | |                      ^^^^^^^^^^^^^^^^^^ cannot use the `?` operator in a function that returns `()`
9  | |     println!("{:?}", give_number("5")?);
10 | | }
   | |_- this function should return `Result` or `Option` to accept `?`
```

Tapi sebenarnya `main()` bisa mengembalikan `Result`, sama seperti function lainnya. Jika function kita bekerja, kita tidak ingin me-return apapun (`main()` tidak memberikan apapun). Dan jika ia tidak bekerja, ia akan mengembalikan error yang sama. Sehingga kita bisa menuliskan codenya seperti ini:

```rust
use std::num::ParseIntError;

fn give_number(input: &str) -> Result<i32, ParseIntError> {
    input.parse::<i32>()
}

fn main() -> Result<(), ParseIntError> {
    println!("{:?}", give_number("88")?);
    println!("{:?}", give_number("5")?);
    Ok(())
}
```

Jangan lupa `Ok(())` pada bagian akhir: ini sangatlah umum di Rust. Itu artinya adalah `Ok` yang di dalamnya ada `()`, yang mana itu adalah merupakan value kembaliannya. Beginilah outputnya:

```text
88
5
```


Ini memanglah tidak terlalu berguna di saat kita menggunakan `.parse()`, namun ia akan berguna ketika kita melakukan sesuatu yang berkaitan dengan file. Ini dikarenakan operator `?` juga mengubah error typenya. Inilah informasi yang bisa dilihat pada [laman tentang operator ?](https://doc.rust-lang.org/std/macro.try.html) yang ditulis dengan simple English:

```text
If you get an `Err`, it will get the inner error. Then `?` does a conversion using `From`. With that it can change specialized errors to more general ones. The error it gets is then returned.
```

Artinya, "Jika Anda mendapatkan `Err` ia akan mendapatkan inner error. Kemudian `?` melakukan konversi menggunakan `From`. Dengan itu ia bisa mengubah error yang spesifik menjadi error yang umum. Error yang didapatkan tersebut kemudian dikembalikan."

Juga, Rust memiliki type `Result` di saat menggunakan `File` atau hal semacamnya. Ia biasa disebut `std::io::Result`, dan ini adalah apa yang biasanya Anda lihat di dalam `main()` saat Anda menggunakan `?` untuk membuka dan melakukan sesuatu terhadap file. Itu sebenarnya adalah type alias. Ia terlihat seperti berikut:

```text
type Result<T> = Result<T, Error>;
```

Jadi ia sebenarnya adalah `Result<T, Error>`, namun kita hanya perlu menuliskan `Result<T>`.

Sekarang mari kita coba mengerjakan sesuatu dengan file untuk pertama kalinya. `std::fs` adalah tempat dimana method-method yang berguna untuk bekerja dengan file berada, dan dengan `std::io::Write` Anda bisa menuliskan sesuatu ke dalam file tersebut. Dengan `std::io::Write` kita bisa menggunakan method `.write_all()` untuk menuliskan sesuatu ke dalam file.

```rust
use std::fs;
use std::io::Write;

fn main() -> std::io::Result<()> {
    let mut file = fs::File::create("myfilename.txt")?; // Buat sebuah file dengan nama ini.
                                                        // PERINGATAN! Jika Anda sudah memiliki file dengan nama tersebut,
                                                        // ia akan menghapus apapun yang ada di dalamnya.
    file.write_all(b"Let's put this in the file")?;     // Jangan lupa dengan b yang ditulis di depan ". Itu karena file akan mengambil bytenya.
    Ok(())
}
```

Kemudian jika Anda klik pada file baru tersebut (`myfilename.txt`), di dalamnya akan ada tulisan `Let's put this in the file`.

Sebenarnya kita tidak perlu melakukannya dengan menuliskannya dalam 2 baris seperti itu, karena kita menggunakan operator `?`. Ia akan pass hasil yang kita inginkan jika ia bekerja, seperti saat kita menggunakan banyak metode pada iterator. Di sinilah kita mendapatkan "kenyamanan" saat menggunakan operator `?`.

```rust
use std::fs;
use std::io::Write;

fn main() -> std::io::Result<()> {
    fs::File::create("myfilename.txt")?.write_all(b"Let's put this in the file")?;
    Ok(())
}
```

Jadi, bahasa mudahnya adalah "Tolong coba buatkan sebuah file dan periksa apakah kita berhasil membuatnya. Jika ya, kemudian gunakan `.write_all()` untuk menulis sesuatu di dalamnya dan kemudian periksa apakah kita berhasil menuliskannya."

Dan sebenarnya, ada juga function yang melakukan keduanya secara bersamaan (membuat file sekaligus menuliskan sesuatu di dalamnya). Ia adalah `std::fs::write`. Di dalamnya, Anda memberikan nama file yang Anda inginkan, dan juga isi/tulisan yang ingin Anda masukkan ke dalamnya. Lagi-lagi, berhati-hatilah! Ia akan menghapus apapun yang ada di dalam file tersebut jika sebelumnya file tersebut sudah ada. Juga, method ini memungkinkan kita menuliskan `&str` tanpa `b` di bagian depannya, karena beginilah signaturenya:

```rust
pub fn write<P: AsRef<Path>, C: AsRef<[u8]>>(path: P, contents: C) -> Result<()>
```

`AsRef<[u8]>` adalah alasan mengapa Anda bisa menuliskannya tanpa menuliskan `b` di depannya.

Penggunaannya pun sangat sederhana:

```rust
use std::fs;

fn main() -> std::io::Result<()> {
    fs::write("calvin_with_dad.txt", 
"Calvin: Dad, how come old photographs are always black and white? Didn't they have color film back then?
Dad: Sure they did. In fact, those photographs *are* in color. It's just the *world* was black and white then.
Calvin: Really?
Dad: Yep. The world didn't turn color until sometimes in the 1930s...")?;

    Ok(())
}
```

Jadi, itu merupakan file yang akan kita gunakan. Isinya adalah percakapan antara tokoh fiktif bernama Calvin dan juga ayahnya, yang menjawab pertanyaan anaknya dengan tidak serius. Dengan cara ini, kita bisa membuat sebuah file untuk digunakan setiap saat.



Membuka file sama mudahnya dengan membuatnya. Anda cukup menggunakan `open()`. Setelah itu (jika filenya ditemukan), Anda bisa melakukan sesuatu seperti `read_to_string()`. Untuk melakukan itu Anda bisa membuat sebuah `String` yang mutable dan membaca filenya di dalam situ. Codenya menjadi seperti ini:

```rust
use std::fs;
use std::fs::File;
use std::io::Read; // untuk menggunakan function .read_to_string()

fn main() -> std::io::Result<()> {
     fs::write("calvin_with_dad.txt", 
"Calvin: Dad, how come old photographs are always black and white? Didn't they have color film back then?
Dad: Sure they did. In fact, those photographs *are* in color. It's just the *world* was black and white then.
Calvin: Really?
Dad: Yep. The world didn't turn color until sometimes in the 1930s...")?;


    let mut calvin_file = File::open("calvin_with_dad.txt")?; // Buka file yang kita buat
    let mut calvin_string = String::new(); // String ini akan menyimpannya
    calvin_file.read_to_string(&mut calvin_string)?; // baca filenya dan letakkan di dalam mutable Stringnya

    calvin_string.split_whitespace().for_each(|word| print!("{} ", word.to_uppercase())); // melakukan sesuatu dengan String tersebut

    Ok(())
}
```

Hasilnya adalah:

```text
CALVIN: DAD, HOW COME OLD PHOTOGRAPHS ARE ALWAYS BLACK AND WHITE? DIDN'T THEY HAVE COLOR FILM BACK THEN? DAD: SURE THEY DID. IN 
FACT, THOSE PHOTOGRAPHS *ARE* IN COLOR. IT'S JUST THE *WORLD* WAS BLACK AND WHITE THEN. CALVIN: REALLY? DAD: YEP. THE WORLD DIDN'T TURN COLOR UNTIL SOMETIMES IN THE 1930S...
```

Okay, bagaimana jika kita ingin membuat sebuah file namun kita tidak akan melakukannya jika di situ sudah ada file lainnya dengan nama yang sama? Mungkin Anda tidak ingin menghapus file lain tersebut (jika ia sudah terlebih dahulu ada disana), hanya karena ingin membuat satu file yang baru. Untuk melakukan ini, ada struct yang bernama `OpenOptions`. Sebenarnya, kita sudah menggunakan `OpenOptions` selama ini dan kita tidak mengetahuinya. Coba lihatlah source code dari `File::open`:

```rust
pub fn open<P: AsRef<Path>>(path: P) -> io::Result<File> {
        OpenOptions::new().read(true).open(path.as_ref())
    }
```

Menarik, ini mirip dengan builder pattern yang sebelumnya kita pelajari. Sama pula dengan `File::create`:

```rust
pub fn create<P: AsRef<Path>>(path: P) -> io::Result<File> {
        OpenOptions::new().write(true).create(true).truncate(true).open(path.as_ref())
    }
```

Jika Anda pergi ke [laman tentang OpenOptions](https://doc.rust-lang.org/std/fs/struct.OpenOptions.html), Anda bisa melihat semua method yang bisa Anda gunakan. Kebanyakan method tersebut akan mengambil inputan `bool`:

- `append()`: Ini berarti "tambahkan ke isi file tersebut (yang mana filenya sudah ada disana) alih-alih menghapus isinya".
- `create()`: Ini memungkinkan `OpenOptions` membuat sebuah file.
- `create_new()`: Ini berarti ia akan hanya membuat filenya jika filenya memang belum ada.
- `read()`: Ubah ia menjadi `true` jika Anda ingin method tersebut bisa membaca sebuah file.
- `truncate()`: Ubah ia menjadi `true` jika Anda ingin memotong isi dari filenya sampai ke 0 (menghapus isinya) di saat Anda membuka filenya.
- `write()`: memungkinkan Anda menulis ke dalam file.

Dan kemudian, ada `.open()` dengan nama filenya, dan ia akan mengembalikan `Result`. Code di bawah ini adalah contohnya:

```rust
// ⚠️
use std::fs;
use std::fs::OpenOptions;

fn main() -> std::io::Result<()> {
     fs::write("calvin_with_dad.txt", 
"Calvin: Dad, how come old photographs are always black and white? Didn't they have color film back then?
Dad: Sure they did. In fact, those photographs *are* in color. It's just the *world* was black and white then.
Calvin: Really?
Dad: Yep. The world didn't turn color until sometimes in the 1930s...")?;

    let calvin_file = OpenOptions::new().write(true).create_new(true).open("calvin_with_dad.txt")?;

    Ok(())
}
```

Pertama-tama, kita membuat sebuah `OpenOptions` menggunakan `new` (selalu dimulai dengan `new`). Kemudian kita memberikannya "kemampuan" untuk menulis (menggunakan `write`). Setelah itu, kita ubah `create_new()` menjadi `true`, dan mencoba membuka file yang kita buat. Dan ini tidak akan berhasil, sesuai seperti yang kita inginkan (karena sudah ada file dengan nama yang sama sebelumnya):

```text
Error: Os { code: 80, kind: AlreadyExists, message: "The file exists." }
```

Mari kita coba menggunakan `.append()` untuk menuliskan sesuatu ke dalam file yang sudah ada itu. Untuk menulis ke dalam file, kita bisa menggunakan `.write_all()`, yang mana itu adalah method yang mencoba menuliskan apapun yang inputan kita berikan.

Dan juga, kita akan menggunakan macro `write!` untuk melakukan hal yang sama. Anda akan mengingat macro ini dari saat kita menggunakan `impl Display` untuk struct yang kita buat. Kali ini kita menggunakannya pada file.

```rust
use std::fs;
use std::fs::OpenOptions;
use std::io::Write;

fn main() -> std::io::Result<()> {
    fs::write("calvin_with_dad.txt", 
"Calvin: Dad, how come old photographs are always black and white? Didn't they have color film back then?
Dad: Sure they did. In fact, those photographs *are* in color. It's just the *world* was black and white then.
Calvin: Really?
Dad: Yep. The world didn't turn color until sometimes in the 1930s...")?;

    let mut calvin_file = OpenOptions::new()
        .append(true) // Now we can write without deleting it
        .read(true)
        .open("calvin_with_dad.txt")?;
    calvin_file.write_all(b"And it was a pretty grainy color for a while too.\n")?;
    write!(&mut calvin_file, "That's really weird.\n")?;
    write!(&mut calvin_file, "Well, truth is stranger than fiction.")?;

    println!("{}", fs::read_to_string("calvin_with_dad.txt")?);

    Ok(())
}
```

Hasilnya adalah:

```text
Calvin: Dad, how come old photographs are always black and white? Didn't they have color film back then?
Dad: Sure they did. In fact, those photographs *are* in color. It's just the *world* was black and white then.
Calvin: Really?
Dad: Yep. The world didn't turn color until sometimes in the 1930s...And it was a pretty grainy color for a while too.
That's really weird.
Well, truth is stranger than fiction.
```

## cargo doc

Mungkin Anda menyadari bahwa dokumentasi Rust selalu terlihat hampir sama semuanya. Di bagian sebelah kiri Anda bisa melihat `struct` dan `trait`, contoh codenya ada di sebelah kanan, dst. Ini karena Anda bisa secara otomatis membuat dokumentasi hanya dengan menuliskan perintah `cargo doc`.

Bahkan membuat project yang tidak melakukan apapun bisa membantu Anda mempelajari tentang trait di Rust. Sebagai contoh, di bawah ini ada dua struct yang tidak melakukan apapun, dan sebuah `fn main()` yang juga tidak melakukan apa-apa.

```rust
struct DoesNothing {}
struct PrintThing {}

impl PrintThing {
    fn prints_something() {
        println!("I am printing something");
    }
}

fn main() {}
```


Tapi jika Anda menuliskan perintah `cargo doc --open`, Anda bisa melihat lebih banyak informasi daripada yang Anda kira. Pertama-tama ia akan menampilkan ini:

```text
Crate rust_book

Structs
DoesNothing
PrintThing

Functions
main
```

Namun jika Anda klik pada salah satu struct, ia akan menampilkan banyak trait yang mungkin menurut Anda sebenarnya tidak ada:

```text
Struct rust_book::DoesNothing
[+] Show declaration
Auto Trait Implementations
impl RefUnwindSafe for DoesNothing
impl Send for DoesNothing
impl Sync for DoesNothing
impl Unpin for DoesNothing
impl UnwindSafe for DoesNothing
Blanket Implementations
impl<T> Any for T
where
    T: 'static + ?Sized,
[src]
[+]
impl<T> Borrow<T> for T
where
    T: ?Sized,
[src]
[+]
impl<T> BorrowMut<T> for T
where
    T: ?Sized,
[src]
[+]
impl<T> From<T> for T
[src]
[+]
impl<T, U> Into<U> for T
where
    U: From<T>,
[src]
[+]
impl<T, U> TryFrom<U> for T
where
    U: Into<T>,
[src]
[+]
impl<T, U> TryInto<U> for T
where
    U: TryFrom<T>,
```

Ini karena Rust secara otomatis menerapkan semua trait untuk setiap type.

Kemudian, jika kita menambahkan beberapa documentation comments, Anda bisa melihatnya di saat Anda menuliskan perintah `cargo doc`.

```rust
/// This is a struct that does nothing
struct DoesNothing {}
/// This struct only has one method.
struct PrintThing {}
/// It just prints the same message.
impl PrintThing {
    fn prints_something() {
        println!("I am printing something");
    }
}

fn main() {}
```


Sekarang ia akan mencetak:

```text
Crate rust_book
Structs
DoesNothing This is a struct that does nothing
PrintThing  This struct only has one method.
Functions
main
```

`cargo doc` sangatlah bagus jika Anda menggunakan banyak crate yang dibuat oleh orang lain. Karena crate-crate ini berada di websites yang berbeda, tentunya akan memakan waktu jika kita mencari semuanya. Namun jika kita menggunakan `cargo doc`, Anda akan memiliki semuanya di satu tempat di dalam hard drive Anda.

## The end?

Ini adalah bagian akhir dari (terjemahan) "Rust in Easy English". But I am still here, dan Anda bisa memberitahu saya jika Anda memiliki pertanyaan. Silakan [hubungi saya di Twitter](https://twitter.com/mithridates) atau tambahkan pull request, issue, dll. Anda juga bisa memberi tahu saya jika ada bagian yang sulit untuk dipahami. "Rust in Easy English" haruslah sangat mudah dipahami, jadi tolong beri tahu saya jika penjelasan dalam bahasa Inggrisnya terlalu sulit dipahami. Tentu saja, Rust itu sendiri mungkin sulit untuk dipahami, tapi setidaknya kita dapat memastikan bahwa penjelasannya dalam bahasa Inggris mudah dimengerti.
