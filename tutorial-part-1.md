# Tutorial Expo untuk React Native part 1 ✨

## Instalasi Expo CLI

![image](https://github.com/Ladybert/ReactNative-Expo-Tutorial-Part-1/assets/137638007/2a0bde07-d5e2-4a7c-88f3-a27321000aba)

Hari ini kita akan membahas tentang Expo, sebuah alat yang sangat berguna dalam membangun aplikasi mobile menggunakan React Native. Expo memberikan kita kemampuan untuk membuat aplikasi Android dan iOS dengan cepat dan efisien.

Apa itu Expo? Expo adalah platform pengembangan yang memungkinkan kita untuk membuat aplikasi React Native tanpa perlu konfigurasi awal yang rumit. Dengan Expo, kita bisa langsung mulai menulis kode React Native dan melihat hasilnya di perangkat fisik atau emulator secara langsung.

Langkah pertama yang perlu kita lakukan adalah menginstal Expo CLI (Command Line Interface) di komputer kita. Expo CLI akan membantu kita dalam membuat, mengelola, dan menjalankan proyek Expo.

Berikut langkah-langkahnya:

1. Buka terminal atau command prompt.
2. Ketikkan perintah:
```cli
npm install -g expo-cli
``` 
3. Tekan enter dan tunggu proses instalasi selesai.

Setelah Expo CLI terinstal, kita bisa mulai membuat proyek Expo baru dengan menjalankan perintah expo init nama_projek. Kemudian, Expo akan memandu kita untuk memilih template proyek dan menyiapkan proyek tersebut.

Ini adalah langkah awal yang perlu kita lakukan untuk memulai pengembangan aplikasi Android menggunakan Expo. Selanjutnya, kita bisa mulai mengeksplorasi berbagai fitur dan kemampuan Expo untuk memperluas dan meningkatkan aplikasi kita.


## Instalasi Proyek Expo menggunakan CLI


![proyek expo](https://github.com/Ladybert/ReactNative-Expo-Tutorial-Part-1/assets/137638007/09024e9c-5f0e-4390-8305-423d8280b656)


Bila anda telah selesai menginstalasi expo cli, maka anda dapat memulai instalasi proyek melalui prompt di bawah ini. Dapat digunakan pada powershell, cmd, dll :
```poweshell
npx create-expo-app@latest
```

you juga bisa menambahkan flag **--template** di belakang prompt untuk menggunakan template yang di sediakan pada expo. sebagaimana mestinya hal ini hanya bersifat opsional, bolehb anda gunakan ataupun tidak juga tidak masalah.
Lakukan test untuk mengetahui apakah proyek anda dapat digunakan dalam lingkup pengembangan. Dengan menggunakan perintah berikut untuk memulai tahap development anda :
```vscode
npx expo start 
```

perintah ini sebelumnya sudah terkonfigurasi saat pemasangan proyek, untuk itu coba anda check pada file **package.json** untuk memastikan apakah perintah tersbeut sesuai dengan isi script pada file tersebut. Harusnya mendapati kondisi prompt script berikut :

![default script as package json](https://github.com/Ladybert/ReactNative-Expo-Tutorial/assets/137638007/d160a8a6-3180-4d79-b9df-ece529880f42)

NB : Bila anda mengalami masalah error pada terminal atau mendapati message error pada aplikasi expo bila saat menjalankannya anda dapat mencantumkan **--tunnel** pada file **package.json** anda tepatnya pada bagian **script**. Berikut ini adalah contoh penerapannya :

![modifyed script as tunnel for expo](https://github.com/Ladybert/ReactNative-Expo-Tutorial/assets/137638007/360a4fd0-ed0d-401a-ac7c-b6ab902f788a)

Solusi di atas relevan bila error yang di dapat seperti demikian : 

![error message on Android](https://user-images.githubusercontent.com/6944394/218597585-98a52f4f-b5d0-4858-a07b-12cdcb56ea68.png)

![error message on Android](https://user-images.githubusercontent.com/6944394/218598005-3f2f0a40-f256-4469-a76e-4cad0fea6c17.png)

