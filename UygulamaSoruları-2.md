
<img width="656" alt="Ekran Resmi 2025-04-10 22 53 51" src="https://github.com/user-attachments/assets/885c5a19-59dd-43df-8a0f-1a3454835ada" />


**1. Yukarıdaki görselde gerçekleşen komut adımlarını açıklayınız?**
- Komut 1: Masaüstüne geçiş yaptı.
- Komut 2: Touch komutu ile güvenlik.txt adında bir dosya oluşturdu.
- Komut 3: Bulunduğu dizin içerisinde ls komutu ile dizindeki dosyaları listeliyor.
- Komut 4: Güvenlik.txt adlı dosya içerisine yeni metinler ekliyor.
- Komut 5: Güvenlik.txt dosyasını cat komutu ile okuyor.
- Komut 6: Dosya üzerine cat >> komutu ile yeniden ekleme yapıyor.
- Komut 7: cat komutu ile dosyayı tekrardan görüntülüyor.

**2. "cat -n /etc/passwd" komutunun işlevini açıklayınız?**
- Açıklama: passwd içerisinde bulunan yazıları düzenli bir şekilde sıralama yapıyor.

**3. $ echo Açık Kaynak > ders1.txt
   $ echo İşletim Sistemi > ders2.txt
   $ cat ders1.txt ders2.txt
Yukarıdaki komut bloğu çalıştırıldığında ekran çıktısı ne olur?**
- Ekran Çıktısı: Açık Kaynak
               İşletim Sistemi

**4. "Deneme.txt" dokümanı içerisinde 100 satırlık paragraf bulunmaktadır. Paragrafın sadece 2 satırını görüntülemek için kullanılan komutu yazınız?**
- Komut: more -n 2 deneme.txt

**5. Sistem yapılandırma dosyaları içerisinde bulunan "passwd" dokümanının ilk ve son 5 satırını görüntülemek için kullanılan komutu yazınız?**
- Komut: head -n 5 /etc/passwd
- Komut: fail -n 5 /etc/passwd

**6. Masaüstünde "okul.txt" adında döküman oluşturunuz. Doküman içerisinde adınızı, soyadınızı ve okuduğunuz bölüm bilgisini komut blokları ile ekleme ve görüntüleme sağlayınız. Son olarak oluşturduğunuz dokümanda karakter ve kelime sayısını bulan komut bloklarını yazınız?**
- Komut: cd /Masaüstü
- Komut: touch okul.txt
- Komut: echo "Doğukan İspirli - Bilişim Güvenliği" > okul.txt
- Komut: cat okul.txt
- Komut: wc -c okul.txt
- Komut: wc -w okul.txt

**7. Masaüstünde "ben.txt ve program.txt" adında iki adet doküman oluşturunuz ben.txt içerisine; ad, soyad ve memleket bilgisi ekleyin ve görüntüleme sağlayınız. program.txt içerisine; bildiğiniz üç tane programlama dilini ekleyin ve görüntüleme sağlayınız.
Oluşturulan her iki dökümanı aralarına tab boşluğu koyarak "birleştirme.txt" dökümanı içerisine ekleyiniz.
Son olarak "komut" dizini oluşturup içerisine "birlestirme.txt" dökümanını taşıyan ve arşivleyen komut bloklarını yazınız?**
- Komut: cd /Masaüstü
- Komut: touch ben.txt
- Komut: echo "Doğukan İspirli - Bilişim Güvenliği" > ben.txt
- Komut: cat ben.txt
- Komut: touch program.txt
- Komut: echo "Python, C++, Html" > program.txt
- Komut: cat program.txt
- Komut: paste ben.txt program.txt > birlestirme.txt
- Komut: cat birlestirme.txt
- Komut: mkdir komut
- Komut: mv birlestirme.txt komut
- Komut: tar  -cf arsivle.tar komut

**8. Masaüstünde "yetki" adında dizin oluşturunuz. Dizin içerisine "yetkilendirme.txt" dokümanı oluşturup erişim izinlerini listeleyiniz. Grup ve diğer kullanıcıların erişim izinlerine yazma yetkisini veren komut bloklarını yazınız?**
- Komut: cd /Masaüstü
- Komut: mkdir yetki
- Komut: cd yetki
- Komut: touch yetkilendirme.txt
- Komut: ls -l yetkilendirme.txt
- Komut: chmod go+w yetkilendirme.txt
- Komut: ls -l yetkilendirme.txt
