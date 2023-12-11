package main

import "fmt"

func main() {

    fmt.Print("Bir sayi giriniz = ") //İlk önce dışarıdan atayacağımız sayı için Print fonksiyonunu oluşturuyoruz.
    var sayi int  //Değişkeni tanımladıktan sonra,değişkenin adını ve türünü yazıyoruz.
    fmt.Scanf("%d", &sayi) //Scanf fonksiyonu girdiğimiz sayıyı int değişkenine kaydetmek için yazdım.
//Daha sonra  %d ifadesini tam sayılar için yazdım.
    
    if sayi%2 == 0 {  //Eğer dışarıdan girilen sayı 2 'ye tam bölünüyorsa 
        fmt.Println("Asal Sayı Değildir.") //Bu bir asal sayı değildir.
    } else {  //If koşulu sağlanmadığı takdirde else komutuna geçer)
        print("Sayi asaldır") //Burada da Sayı asaldır der.
    }
}
