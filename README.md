void main() {

  var kazak = new List.filled(5, ""); //5 elemanlı liste oluşturduk. tırnak içinde boşluk bırakmamız değer gelicek diyeydi sanırım
  // kazak listemizin ismi new List.filled diyerek yeni liste açıyoruz sadece list diyince olmadı internetten yaptığım araştırmalar sonucunda filled kullandığımız zaman liste içindeki tüm öğelerin aynı çeşit olacağı anlamına geliyormuş.

  kazak[0] = 'Yünlü ip.';
  kazak[1] = 'Dior';
  kazak[2] = 'Kırmızı';
  kazak[3] = 'Standart beden.';
  kazak[4] = 'Yeni sezon ürünü.';
  
  print("A180E ÜRÜNÜ ÖZELLİKLERİ: ");
  
  //şimdi burda for kullanarak listede verdiklerimizi çıktı olarak bize verecek
  for (int i = 0; i<=kazak.length-1;i++){ // .length için internette bize liste uzunluğunu döndürdüğünü söylüyordu en kullanılabilir bu geldi diğerleri arasında 
    print(kazak[i]); //burda dedik ki kazak listesini yukarıda belirttiğimiz şekilde yazdır
  }

  
}
