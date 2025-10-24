**tag:** #Javascript #Web 


## Pengenalan
JavaScript termasuk dalam salah satu bahasa pemrograman yang menggunakan interpreter (scripting language). Artinya, kita dapat menulis kode dengan bahasa ini dan langsung diserahkan ke mesin. Baris per baris kode akan diterjemahkan dan dieksekusi oleh mesin. Jika ada kode yang salah, error akan langsung ditampilkan pada saat runtime (program berjalan).

Pesatnya perkembangan teknologi menuntun JavaScript berkembang. Saat ini, JavaScript sudah merambah ke berbagai platform. Selain aplikasi browser, banyak juga aplikasi server, desktop, dan lainnya yang dapat dibangun dengan JavaScript. Ini tercapai berkat runtime JavaScript, seperti [[00 Pengenalan NodeJS|Nodejs]] dan [[Bun|Bun]]. Bahkan, beberapa database management system (DBMS), seperti MongoDB, juga menggunakan JavaScript sebagai bahasa scripting dan querynya.
## Javascript Runtime Environtment
[[Runtime|Runtime Enviontment]] adalah tempat sebuah program akan dieksekusi. Ia akan menentukan global object yang dapat diakses oleh program JavaScript.
### Browser
Kebanyakan program JavaScript dijalankan melalui lingkungan browser. Ada beberapa cara untuk menjalankan code JavaScript, menjalankan langsung melalui satu file html di dalam tag `<script></script>` (embedded) atau menggunakan file .js dan mengimportnya di dalam file html (external).

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My Website</h1>
	// ini cara embedded
    <script>
      window.alert('Hello, world!');
    </script>
    
    // ini cara external, membuat file .js lalu mengimportnya
    <script src="index.js"></script>
  </body>
</html>
```

Jika dijalankan hasilnya akan seperti ini
![[compile-process.png|700x394]]

Cara terakhir adalah menjalankannya secara langsung melalui browser atau REPL. Read-Eval-Print-Loop atau disingkat REPL dimiliki juga oleh browser. Dengan menggunakan console di developer tools browser.
### NodeJs
[[00 Pengenalan NodeJS|NodeJs]]  Runtime javascript yang memungkinkan kodenya dijalankan di luar browser.
### Bun
