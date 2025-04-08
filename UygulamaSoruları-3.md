# AÇIK KAYNAK İŞLETİM SİSTEMLERİ DERSİ GENEL TEKRAR SORULARI

**Özgür yazılım felsefesi nedir? Açık kaynak kodlu yazılım kavramı ile arasındaki farkı açıklayınız?**
- **Cevap: Özgür yazılım felsefesi**, kullanıcıya yazılımı çalıştırma, kopyalama, dağıtma, inceleme ve değiştirme özgürlüklerini tanır.
- **Cevap: Açık kaynak yazılım**, kaynak kodu açık olan yazılımdır; ancak her zaman bu özgürlükleri tam anlamıyla sunmayabilir.
- **Aralarında fark:** Her özgür yazılım açık kaynaklıdır, fakat her açık kaynaklı yazılım özgür değildir.
---

# İşletim Sistemi Katmanları nelerdir?
1. **Kernal (Çekirdek)**: Donanım yönetimi ve sistem kaynaklarının kontrolünü sağlar.
2. **Hizmet Katmanı**: Çekirdek hizmetleri üzerine kurulu sistem işlevlerini sağlar.
3. **Uygulama Katmanı**: Kullanıcıların doğrudan kullandığı uygulamaları barındırır.
4. **Shell**: Kullanıcı komutlarını çekirdeğe ileten bir arayüzdür.

---

# CPU'nun işlemci zamanını planlaması için kullanılan algoritmaları nelerdir?
1. **First-Come, First-Served (FCFS)**: İlk Gelen, İlk Hizmet Edilen.
2. **Round Robin**: Zaman Dilimli.
3. **Priority Scheduling**: Öncelikli Planlama.
4. **Shortest Job First (SJF)**: En Kısa İşlem Süresi Kalan.

---

# Aşağıdaki tabloda CPU’da işletilmek üzere bir kuyruk tablosu verilmiştir. Tablodaki bilgiler kullanılarak q=5 için planlama algoritmalarında işletim sırasını oluşturunuz?

| İşlem | İşlem yürütme süresi(ms) | Öncelik |
|-------|-------------------|---------|
| P1    | 10                | 1       |
| P2    | 12                | 0       |
| P3    | 7                 | 3       |
| P4    | 5                 | 2       |

*Round Robin Algoritması* ile işlem sırası:
1. *P1 (Kalan süre(Başlangıç): 10ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 5ms)*
2. *P2 (Kalan süre(Başlangıç): 12ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 7ms)*
3. *P3 (Kalan süre(Başlangıç): 7ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 2ms)*
4. *P4 (Kalan süre(Başlangıç): 5ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 0 ms)*
5. *P1 (Kalan süre(Başlangıç): 5ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 0ms)*
6. *P2 (Kalan süre(Başlangıç): 70ms, İşlem Süresi(q=5): 5ms, Kalan Süre(Bitiş): 2ms)*
7. *P3 (Kalan süre(Başlangıç): 2ms, İşlem Süresi(q=5): 2ms, Kalan Süre(Bitiş): 0ms)*
8. *P2 (Kalan süre(Başlangıç): 2ms, İşlem Süresi(q=5): 2ms, Kalan Süre(Bitiş): 0ms)*

---

# Dosya Erişim Hakları
Dosya: dr-xrw-r-- 2 root root 4096 Kas 5 01:02 bin
- *d*: Bu bir dizindir.
- *r-x*: Sahibi (root) dizini okuyabilir ve çalıştırabilir, yazamaz.
- *rw-*: Grup, dizini okuyabilir ve yazabilir, çalıştırma yetkisi yoktur.
- *r--*: Diğer kullanıcılar dizini sadece okuyabilir.

---

# Bulut Bilişim Hizmet Modelleri
1. *IaaS (Infrastructure as a Service)*: Fiziksel altyapı hizmetleri sunar. Örnek: AWS EC2.
2. *PaaS (Platform as a Service)*: Uygulama geliştirme platformları sağlar. Örnek: Google App Engine.
3. *SaaS (Software as a Service)*: Yazılım hizmetleri sunar. Örnek: Dropbox.

---

# Sanallaştırma Teknolojileri Grupları
1. *Donanım Sanallaştırması*: Örnek: VMware ESXi.
2. *İşletim Sistemi Seviyesi Sanallaştırma*: Örnek: Docker.
3. *Uygulama Sanallaştırması*: Örnek: Citrix XenApp.

---

# Hypervizör, SELinux, Docker Containers ve Virtualization Kavramları
1. *Hypervizör*: Sanal makineleri çalıştıran yazılım (örnek: Hyper-V).
2. *SELinux*: Linux için güvenlik modülü; erişim kontrolleri sağlar.
3. *Docker Containers*: Uygulamaları konteynerler içinde çalıştıran hafif sanallaştırma teknolojisi.
4. *Virtualization*: Fiziksel kaynakları sanal olarak birden fazla ortama böler.

---
