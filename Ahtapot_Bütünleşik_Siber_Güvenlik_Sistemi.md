# Ahtapot Bütünleşik Siber Güvenlik Sistemi (BSGS)

**Ahtapot Bütünleşik Siber Güvenlik Sistemi, TÜBİTAK tarafından geliştirilen**, açık kaynak tabanlı ve bütünleşik bir siber güvenlik çözümüdür. Kurum ve kuruluşların ağ güvenliğini kapsamlı bir şekilde sağlamak amacıyla; log yönetimi, saldırı tespiti, kimlik doğrulama, merkezi yönetim ve izleme gibi kritik güvenlik bileşenlerini tek bir platformda bir araya getirir. Özellikle kamu kurumlarının ihtiyaçları göz önünde bulundurularak geliştirilen **yerli ve milli** bir projedir.

## Üç farklı ürünlere sahiptir;

![AhtapotNAC-02](https://github.com/user-attachments/assets/583c82e2-15c3-4958-b080-43100c2bf419)
### AHTAPOT NAC - Ağ Erişimi Kontrol Sistemi (NAC)
Ağ erişim kontrol sistemi, switchleri yöneterek ya da trafiğini üzerinden geçirerek (inline) yetkisiz cihazları ağ dışında bırakıp, yetkili cihazlara rol tabanlı erişim izinleri tanımlayabilmektedir.
Bağlı olan cihazlara malware taraması, siber güvenlik uyumluluk taraması gibi uç nokta güvenlik kriterlerini de yerine getirebilmektedir.

*Ahtapot Ağ Erişim Kontrol Sisteminin başlıca özellikleri ;*
- Esnek VLAN yönetimi ve rol tabanlı erişim kontrol sistemi
- Misafir cihaz yönetimi
- Portal Profilleri
- DHCP Parmak izi tanıma
- User-Agent tanıma
- MAC Adres tanıma
- Otomatik yetkilendirme
  - Ağ cihazı ile
  - DHCP parmak izi ile
  - MAC adres sağlayıcı ile
- PKI ve EAP-TLS desteği
- Sınırlı süreli erişim kontrolü
- Güvenlik Duvarı Entegrasyonu
- Trafik sınırlama
- Mobil Ağ Erişim Cihazı tanıma
- Esnek Yetkilendirme Sistemi
- Microsoft Active Directory entegrasyonu
- Yönlendirilmiş ağlar üzerinden çalışma
- Ağ cihazları erişim bypass özelliği
- Yüksek Erişilebilirlik
- Uluslararası standartlar desteği
  - 802.1X
  - SNMP (Simple Network Management Protocol)
  - BRIDGE-MIB, Q-BRIDGE-MIB, IF-MIB, IEEE8021-PAE-MIB
  - RADIUS
  - Netflow / IPFIX
  - WISPR (Wireless ISP Roaming)
- Basit eklenti yapısı (Perl desteği ile)
- Düzenlenebilir Şablonlar

![a-vds](https://github.com/user-attachments/assets/349fa1b5-9da5-4136-908f-e2d8587b75ef)
### AHTAPOT VDS - Veri Dağıtım Sistemi (VDS)
Ahtapot Veri Dağıtım Sistemi, güvenli, hızlı ve merkezi veri iletimini sağlayan bir altyapıdır. Log kayıtları, güvenlik uyarıları ve yapılandırma verileri gibi kritik bilgilerin sistem bileşenleri arasında senkronize ve tutarlı bir şekilde paylaşılmasını hedefler.
Bu yapı, Ahtapot Bütünleşik Siber Güvenlik Sistemi'nin bütünsel ve etkin bir şekilde çalışmasına katkı sağlar. Veri Dağıtım Sistemi ile, uç noktaların merkezi olmayan bir ağ yapısı üzerinden, hem yönetim merkezi ile hem de diğer uç birlikler ile, uplink aktif olduğu sürece bilgi ve veri paylaşımı yapabilmesi sağlanmaktadır.

Ahtapot VDS izole bir ağ olmasına rağmen, tüm veri trafiği ayrıca kripto algoritmaları ile şifrelemektedir. Bunun için MESH ve P2P teknolojilerinin beraber kullanılmaktadır.

Aynı zamanda, her bir uç noktanın paylaştığı veri Layer 7 üzerinden dağıtılan unicast trafik olmasına rağmen, trafik multicast trafiğe çevirilerek (unicast->multicast dönüşümü ile), bu izole ağ üzerinde dağıtımı yapılmaktadır.

Ağ içerisinde istenen uç noktalar bireysel ya da gruplar halinde bu veriyi okuyup deşifre edebilir ve multicast->unicast dönüşümü üzerinden ilgili sistemlere aktarılabilmektedir..

![ulak vk logo](https://github.com/user-attachments/assets/a12c9386-3932-41e3-94f4-5a19d409fc97)
### ULAK Video Konferans 
Ahtapot BSGS ekibi tarafından eklentileri geliştirilen ve idame ettirilen Jitsi-Meet Açık Kaynak Video Konferans Yazılımı için, kurumunuzun ihtiyaçlarına göre ölçeklendirilerek ve özelleştirilerek destek sağlanmaktadır.
Ahtapot BSGS tarafından eklenen özelliklerden dolayı, ULAK Video Konferans olarak anılmaktadır.

*Başlıca özellikler;*
- Aktif konuşmacının otomatik gösterimi
- Mobil uygulama desteği
- Metin tabanlı yazışma
- Toplantı/Konferans odasına güvenlik katmanı
- Rezervasyon Sistemi
- Ekran paylaşımı
- Canlı yayın ile webinar mod desteği
- Paylaşılan döküman yeteneği ile ortak çalışma imkanı
- Söz isteme, söz hakkı isteyenleri sıralama
- Katılımcı konuşma ve katılım sürelerinin istatistikleri, Detaylı kullanım istatistikleri
- Bas-konuş yeteneği
- Ortak ekranda video ve/veya ses paylaşma yeteneği
- API yeteneğiyle tüm uygulamalarla entegrasyon
- Toplantı/konferansların kaydedilmesii
- Simultane çeviri modülüyle, sınırsız dil desteği ve anlık canlı çeviri
- Sanal Arkaplan desteği
