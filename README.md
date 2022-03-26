| Reza Tariki taser     | 312010265         |
| --------------------- | ----------------  |
|PEMROGRAMAN WEB        | PRAKTIKUM         |

## 1) MEMBUAT ORDER LIST
![order_list](img/order_list.png)

order list adalah list yang  tersusun dan terurut
```html
    <header>
        <h1>Membuat List</h1>
    </header>
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
        </ol>
        </section>
```

## 2). MEMBUAT UNORDERED LIST
![unordered_list](img/unordered_list.png)

unordered list adalah list yang tidak terurut atau tersusun
```html
<section id="unorder-list">
            <h2>Unordered List</h2>
            <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
            </ul>
            </section>
```

## 3). MEMBUAT DESCRIPTION LIST
![desripction_list](img/deskirpsi_list.png)

Description list adalah list yang didalam nya terdapat dt sebagai sebuah istilah konten sedangkan penjelasannya yaitu dd
```html
<section id="unorder-list">
                <h2>Description List</h2>
                <dl>
                <dt>Fakultas Teknik</dt>
                <dd>Teknik Industri</dd>
                <dd>Teknik Informatika</dd>
                <dd>Teknik Lingkungan</dd>
                <dt>Fakultas Ekonomi dan Bisnis</dt>
                <dd>Akuntansi</dd>
                <dd>Manajemen</dd>
                <dd>Bisnis Digital</dd>
                </dl>
                </section>
```

## 4).MEMBUAT TABLE
![membuat_table](img/table.png)

dalam membuat table diperlukan tag table kemudian tag thead dan th untuk table head dan tbody dan td untuk table data dan tr sendiri adalah table row.
```html
<header>
        <h1>Membuat Table</h1>
    </header>
    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
```
## 5).MENAMBAHKAN MARGIN DAN PADDING
![margin_padding](img/margin_padding.png)

seperti gambar di atas saya menambahkan padding menjadi 8 yang sebelum nya 4 dalam mengubah nya cukup tambah atribute cellpadding.
```html
    <table border="1" cellpadding="8" cellspacing="0">
```

## 6). MENGGABUNGKAN SELL DATA
![menggabungkan_selldata](img/sell_data.png)

dalam menggabungkan sell data vertikal diperlukan atribute rowspan dan horizontal dengan colspan