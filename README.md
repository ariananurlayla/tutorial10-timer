## 1.2. Understanding how it works
- `Ariana's computer: hey hey` dicetak terlebih dahulu karena `println!("Ariana's computer: hey hey");
  ` berada di luar fungsi async. Hal ini menyebabkan text tersebut dieksekusi tanpa menunggu selesainya eksekusi fungsi async. Dengan demikian, text `Ariana's computer: hey hey` dicetak terlebih dahulu sebab fungsi async perlu menunggu hasil dari future. Output yang dihasilkan program adalah sebagai berikut.
![img.png](img.png)