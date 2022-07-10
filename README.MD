# Notes web application

### Node.js Version
`v16.14.2`

### Fist Installation
`npm init --y`

### Install nodemon
`npm install nodemon --save-dev`

### Run application
`npm run start`

---

## Use ESLint

### Install ESLint
`npm install eslint --save-dev`

### Configuration ESLinst
`npx eslint --init`

### Answer the questions
* How would you like to use ESLint? -> <b>To check, find problems, and enforce code style.</b>
* What type of modules does your project use? -> <b>CommonJS (require/exports).</b>
* Which framework did you use? -> <b>None of these. </b>
* Does your project use TypeScript? -> <b>No.</b>
* Where does your code run? -> <b>Node</b> (pilih menggunakan spasi).
* How would you like to define a style for your project? -> <b>Use a popular style guide.</b>
* Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih <b>AirBnB</b>).
* What format do you want your config file to be in? -> <b>JSON</b>.
* Would you like to install them no? -> <b>Yes.</b>

### Add npm runner in <b>package.json</b>
<pre>
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "nodemon ./src/server.js",
    "lint": "eslint ./src"
  }
</pre>

### Run ESLint
`npm run lint`

### Pada .eslintrc.json tambahkan code berikut
<pre>
  "rules": {
        "no-console": "off",
        
        // line break in windows
        "linebreak-style": 0
    }
</pre>

Untuk detail penggunaan ESLInt bisa dilihat pada dokumen yang membahas tentang ESLint juga bisa dilihat 
pada dokumen 4 Membuat Http Server pada folder Restfull api with Hapi.

---

### Install Hapi
`npm install @hapi/hapi`

---

### Install nanoid
`npm install nanoid@3.x.x`

Catatan: Pastikan Anda memasang nanoid dengan versi 3.x.x. Karena jika menggunakan versi terbaru, nanoid tidak dapat digunakan dengan format module CommonJS.

---

### Url notes Application


#### Client app
`http://notesapp-v1.dicodingacademy.com/`

#### Public ip
`http://54.151.191.180:5000`

#### JSON
`http://54.151.191.180:5000/notes`

---