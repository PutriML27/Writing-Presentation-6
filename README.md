# React.js Basic - JavaScript for React.js
**React JS** adalah pustaka atau library Javascript yang dimanfaatkan untuk membuat desain interface website. Bisa dibilang, React JS seperti perpustakaan yang menyimpan kode-kode Javascript.

**Cara Install React.JS**
1. Download dan install Node.js 
2. Buat folder baru untuk instalasi react
Buka command prompt (CMD), lalu ketik: npm -v
Masuk ke folder instalasi react yang sudah dibuat, kemudian ketik: cd nama_folder 
3. Install React dengan mengetik kode: npm install -g create-react-app
4. Untuk mengecek proses instalasinya, bisa dilakukan dengan mengetik: create-react-app –version
5. Jika proses instalasi sudah selesai, kamu bisa membuat project React JS pertamamu. 
> create-react-app nama-project

6. Lalu Ketik: npm start. Setelah proses pembuatan project selesai, akan muncul halaman web yang terbuka otomatis dengan alamat localhost:3000

**Kenapa ReactJS?**
![survey](https://dwblog-ecdf.kxcdn.com/wp-content/uploads/2022/01/statista-reactjs.jpg)

**Fitur Unggulan React JS**
1. JSX

Salah satu fitur unggulan ReactJS yaitu JSX. JSX adalah ekstensi sintaks Javascript yang memungkinkan untuk penggunaan HTML di Javascript.

2. Virtual DOM

Virtual DOM berguna untuk melihat bagian dari DOM asli yang diubah. 

**Contoh project react js:**
![ex](https://www.petanikode.com/img/react/intro/react-vscode.avif)

**React.js-Component**

Komponen mirip dengan fungsi pada Javascript. Komponen menerima beberapa masukan (“props”) dan mengembalikan element React yang mendeskripsikan apa yang seharusnya tampil pada layar. dalam 1 page ada terdiri dari beberapa komponen. 

**Membuat komponen**

Cara paling sederhana untuk mendefinisikan sebuah komponen adalah dengan menuliskan sebuah fungsi Javascript:
``` 
    function Welcome(props) {
    return <h1>Halo, {props.name}</h1>;
    }
```
Komponen Class:
``` 
    class Welcome extends React.Component {
        render() {
            return <h1>Halo, {this.props.name}</h1>;
        }
    }
```
