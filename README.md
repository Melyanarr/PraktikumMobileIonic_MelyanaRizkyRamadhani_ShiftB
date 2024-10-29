Langkah-langkah dalam menambahkan component pada ionic
1.	Membuka folder yang telah dibuat pada praktikum sebelumnya
2.	Membuka terminal untuk menampilkan hasilnya
-	Ketik ionic serve pada terminal visual studi code
3.	Klik UI Component yang berada pada tampilan hasil dari folder firstApp
4.	Cari komponen yang ingin dirubah sesuai dengan tampilan yang diinginkan
5.	Menambahkan source code 
-	Untuk memberikan nama dan nim pada title dan subtitle
6.	 <ion-card>
7.	        <ion-card-header>
8.	          <ion-card-title>Melyana Rizky Ramadhani</ion-card-title>
9.	          <ion-card-subtitle>H1D022013</ion-card-subtitle>
10.	        </ion-card-header>

-	Untuk menambahakan list gambar dan keterangan
<ion-list>
          <ion-item>
            <ion-thumbnail slot="start">
              <img alt="Cake" src="assets/cake1.jpg" />
            </ion-thumbnail>
            <ion-label>Slice cake</ion-label>
          </ion-item>
    
          <ion-item>
            <ion-thumbnail slot="start">
              <img alt="Cake" src="assets/cake2.jpg" />
            </ion-thumbnail>
            <ion-label>Donat</ion-label>
          </ion-item>
    
          <ion-item>
            <ion-thumbnail slot="start">
              <img alt="Cake" src="assets/cake3.jpg" />
            </ion-thumbnail>
            <ion-label>Macaron</ion-label>
          </ion-item>
    
          <ion-item lines="none">
            <ion-thumbnail slot="start">
              <img alt="Cake" src="assets/cake4.jpg" />
            </ion-thumbnail>
            <ion-label>Pancake</ion-label>
          </ion-item>
        </ion-list>

-	Untuk menambahkan bagian search dan progress
<ion-header>
  <ion-toolbar>
    <ion-searchbar style="--background: #e5ffeb; --color: #333;"></ion-searchbar>
    <ion-progress-bar type="indeterminate"></ion-progress-bar>
  </ion-toolbar>
</ion-header>

-	Untuk mengatur bagian searchbar
ion-searchbar {
  --background: #ffffff !important; 
  --color: #333; 
  --placeholder-color: #aaa; 
  --icon-color: #666; 
}

-	Untuk mngatur bagian progress
ion-progress-bar {
  --background: #d3d3d3; 
  --buffer-background: #e0e0e0; 
  --progress-background: #190dc4; 
}

-	Untuk mengatur bagian background agar dapat menampilkan background sesuai gambar yang dimasukkan
#container {
  background-image: url('/assets/background.jpg'); 
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  min-height: 100vh;
  width: 100%;
  text-align: center;
  position: relative;
  padding: 20px;
}

![Ionic1](https://github.com/user-attachments/assets/47dad7b1-33cd-4221-b501-0d51c432c42c)
