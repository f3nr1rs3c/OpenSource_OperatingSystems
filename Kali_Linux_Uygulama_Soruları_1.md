**1.Linux sistemlerde program kurmak için kullanılan yöntemleri listeleyiniz?**
* Kaynak koddan derleyerek
* Paket yönetim sistemi
* Repository (Repo'dan kurulum)

**2."soruces.list" dosyasındaki repolara bakarak paket listelerini kontrol edip paketlerin son sürümleri hakkında bilgi veren ve en son güncellemeleri gerçekleştiren komut bloğunu yazınız?**
- Komut: apt-get update
- Komut: apt-get upgrade

**3.Depoda indirilmiş olarak bulunan tüm paketlerin tutulduğu klasör yapısını listelemeyi sağlayan komut bloğunu yazınız?**
- Komut: ls /var/cache/apt/archives

**4.Linux sisteminde bulunan programları listelemek için kullanılan komutları yazınız?**
- Komut: dpkg --list
- apt list --installed

**5."FileZilla" programının depoda olup olmadığını kontrol etmeyi sağlayan komut bloğunu yazınız?**
- Komut: apt-get cache search filezilla

**6."Synaptic" paket yöneticisini kurmayı ve kaldırmayı sağlayan komut bloğunu yazınız?**
- Komut: apt-get install synaptic
- Komut: apt-get remove synaptic

**7."intel.com" bulunan waf'ı bulmayı ve detaylı açıklama vermesini sağlayan komut bloğunu yazınız?**
- Komut: wafw00f -v intel.com

**8.Sistemde bulunan tüm Web Uygulama Güvenlik Duvarı (WAF) listesini bulmayı sağlayan komut bloğunu yazınız?***
- Komut: wafw00f -l

**9."trendyol.com" adresinde Cloudflare Waf'ı ile korunup korunmadığını öğrenmeyi sağlayan komut bloğunu yazınız?**
- Komut: wafw00f -t Cloudflare

**10."samsung.com.tr" adresinde bulunan tüm waf'ları bulmayı ve sayfada bulunan 3xx durum yönlendirmeleri olsa bile taramaya devam etmeyi sağlayan komut bloğunu yazınız?**
- Komut: wafw00f -a -r -v samsung.com.tr

**11.Gelişim Üniversitesinin web sayfasında ana dizininde gizlenmiş dosya ve klasörleri tespit etmek için /usr/share/wordlists/dirb/common.txt wordlist'ini kullanarak tarama yapmayı sağlayan
komut bloğunu yazınız?**
- Komut: dirb http://gelisim.edu.tr /usr/share/wordlists/dirb/common.txt

**12.testphp.vulnweb.com sayfasında sadece .php uzantılı dosyaları listelemek için kullanılan komut bloğunu yazınız?**
- Komut: dirb "php" http://testphp.vulnweb.com -X

**13.Bir CTF senaryosunda hedef sistemin IP adresi 192.168.1.1 ve HTTPS servis çalışıyor. İlgili adreste bulunan dosya dizinleri listelemek için kullanmak istediğiniz wordlist common.txt
dosyası ve /usr/share/wordlists/dirb dizininde yer alıyor. Bulunan sonuçlar output.txt dökümanına kaydetmeyi sağlayan komut bloğunu yazınız?**
- Komut:  dirb https://192.168.1.1 /usr/share/wordlists/dirb -o output.txt
