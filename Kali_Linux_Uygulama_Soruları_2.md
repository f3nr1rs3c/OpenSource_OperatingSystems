**1.Kullanıcının parola bilgisini gösteriniz ve yeni şifre ataması yapınız. Oluşturulan yeni şifre ve eski şifreyi karşılaştıran komut bloğunu yazınız?**
- Komut: cat /etc/shadow | grep root
- Komut: passwd
- Komut: cat /etc/shadow | grep root

**2.Sistemde bulunan grup ve kullanıcıların sadece son satırlarını görüntelemeyi sağlayınız. Sisteme "acikkaynak" adında yeni bir kullanıcı ve "ders" adında yeni bir grup oluşturup
görüntüleme sağlayanız. Son olarak yeni eklenen kullanıcının hesabını kilitlemeyi sağlayan komut bloklarını yazınız?**
- Komut: tail -nt /etc/group
- Komut: etc /passwd
- Komut: adduser acikkaynak
- Komut: cd /home
- Komut: groupadd ders
- Komut: tail -n 1 /etc/group
- Komut: gpasswd -a acikkaynak
- Komut: tail -n 2 /etc/group
- Komut: usermod -L acikkaynak
- Komut: grep acikkaynak /etc/shadow

**3.Sisteme "ders" adında yeni bir kullanıcı oluşturup, kullanıcıyı gruba dahil edip görüntüleyiniz. Oluşturulan kullanıcıya ait bilgilerin ve parolanın saklandığı dosyaları görüntülemeyi sağlayanız.
En son olarak kullanıcıya ait bilgileri silmeyi sağlayan komut bloğunu yazınız.**
- Komut: adduser ders
- Komut: cd /home
- Komut: ls
- Komut: groups ders
- Komut: cat /etc/passwd | grep ders
- Komut: cat /etc/shadow | grep ders
- Komut: deluser -remote -home ders
- Komut: ls -l kontrol

**4.Sistemde "deneme" adında yeni bir kullanıcı oluşturunuz. Kullanıcın kimliğinde sistemde o an hangi kimlikle çalıştığını bulmayı sağlayan komut bloğunu yazınız?
- Komut: adduser deneme
- Komut: su - deneme -ı kullanıcı kimliğine
- Komut: whoami

**5.theHarvester tool'u kullanarak gelisim.edu üzerinde duckduckgo arama motorunda ve shadon üzerinde tarama yapıp sonuçları "deneme" dosyasına kaydeden komut bloğunu yazınız?**
- Komut: theHarvester -d gelisim.edu.tr -b duckduckgo -f deneme -s shadon

**6.theHarvester tool'u kullanarak gelisim.edu üzerinde bing arama motorunda brute-force yönetimi ile subdomainleri bulup "test" dokümanına kaydeden komut bloğunu yazınız?**
- Komut: theHarvester -d gelisim.edu.tr -b bing -f test -c

**7.Dmitry tool'u kullanarak gelisim.edu.tr üzerinde subdomainleri ve mail adreslerini bulup "test2" dokümanına kaydeden komut bloğunu yazınız?**
- Komut: dmitry -w gelisim.edu.tr -o test8

**8.Dmitry tool'u kullanarak gelisim.edu.tr ip adresini netcraft üzerinde tarama yapıp bulunan verileri "test3" dokümanına kaydeden komut bloğunu yazınız?
- Komut: dmitry -m gelisim.edu.tr -o test9
