**1.Sistem bulunan tüm network interface'leri ve sadece eth0 inteface bilgisini görüntülemek için gereken komut bloğunu yazınız?**
- Komut: ifconfig -a
- Komut: ifconfig -eth0

**2.Sistemde mevcut tüm arayüzlerin ip adreslerini ve yönlendirici tablosunu görüntülemek için gereken komut bloğunu yazınız?**
- Komut: ip addr show
- Komut: route -n

**3.Sistemde bulunan tüm TCP bağlantılarının rakamsal olarak istatiksel verilerini görüntülümek için gereken komut bloğunu yazınız?**
- Komut: netstat -ents

**4.www.google.com.tr adresinin adres çözümlemesini sağlayan komut bloğunu yazınız?**
- Komut: nslookup
- Komut: www.google.com.tr

**5.www.google.com.tr adresini gönderilen e-postaları kabul eden sunucuları görmek için kullanılan komut bloğunu yazınız?**
- Komut: nslookup
- Komut: set type=mx
- Komut: www.google.com.tr

**6.Nmap tool'u kullanarak www.google.com.tr adresinde bulunan UDP portlarından en sık kullanılan 10 portunu udplistesi.xml dökümanına kaydetmeyi sağlayan komut bloğunu yazınız?**
- Komut: nmap -sU -top-ports 10 -oX udpoutput.xml

**7.Nmap tool'u kullanılarak 192.168.1.1 ip adresindeki açık portlarda çalışan hizmetlerin sürüm bilgilerini sağlayan komut bloğunu yazınız?**
- Komut: nmap -sV -v 192.168.1.1

**8.Nmap tool'u kullanarak 192.168.1.1 ip adresindeki HTTP hizmetleriyle ilgili bilgi toplamak için kullanılan komut bloğunu yazınız?**
- Komut: nmap --script=http-title 192.168.1.1
