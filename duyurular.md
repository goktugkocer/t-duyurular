# TenaMobile Duyuruları

Bu dosya TenaMobile'ın Keşfet sekmesinde listelenir. İlk `##` satırına kadar olan bu
açıklama uygulamada görünmez.

Nasıl yazılır:

- Her duyuru `## TARİH | TÜR | BAŞLIK` satırıyla başlar. Tarih `YYYY-AA-GG` biçiminde.
- TÜR: `Yenilik`, `İyileştirme`, `Düzeltme` ya da `Duyuru` (renk ve ikon buna göre).
- Başlıktan sonraki ilk paragraf listede görünen kısa özettir.
- Boş satırdan sonrası "Detay" sayfasında görünür. Kullanılabilenler:
  `### Ara başlık`, `- madde`, `1. numaralı madde`, `**kalın**`, `` `kod` ``,
  `> not kutusu`, `---` ayraç.
- En yeni tarih en üstte listelenir; aynı tarihliler bu dosyadaki sırayla.
- Yeni duyurular kullanıcıya "YENİ" etiketiyle gösterilir.

## 2026-10-07 | Yenilik | Etiket sepeti

Farklı ürünlerin etiketlerini sepette biriktirip hepsini tek seferde basabilirsiniz.

### Sepete ekleme
- Sepet boşken **Etiket**'e basınca sorulur: **Tekli Etiket** hemen yazdırır, **Toplu Etiket** sepete ekler
- Sepette ürün varken her Etiket doğrudan sepete gider, bir daha sorulmaz
- Tek renk/bedende adet sorulur; **Envanter kadar** ile mağaza stoğu kadar eklenir
- Ürünün tümüne "Etiket Yazdır" denirse mağazada stoğu olan renk/bedenler stok kadar eklenir
- Aynı ürün tekrar eklenirse adetler toplanır

### Sepet
- **Stok Durumu** başlığında, yenile düğmesinin yanındaki sepet simgesinden açılır (üzerinde ürün sayısı)
- Ürünler gruplu; renk adı, beden ve **− adet +** ile adet değiştirilir
- Kutucuğu kaldırılan kalem bu baskıya girmez ama sepette kalır; çöp kutusu onay sorarak siler
- Sıra: önce **Etiket Tipi**, sonra **yazıcı** (etiket tipine bağlı, otomatik gelir), **Önizle**, **Yazıcıya Bas**
- Basılan etiketler sepetten çıkar, basılmayanlar kalır

> Sepet kişiye özeldir ve telefonunuzda saklanır.

## 2026-10-07 | Yenilik | Stok Durumu: onaylanmamış transferler

Mağazanıza gönderilmiş ama henüz onaylanmamış transferleri envantere katarak görebilirsiniz.

- Depolar bölümündeki **Onaylanmamış transferler dahil edilerek gösterilsin** seçeneğini açın; yanlışlıkla dokunmaya karşı onay sorulur
- **Yeşil:** mevcut envanter · **Sarı:** transfer dahil toplam (yanında yoldaki adet)
- Ürün Kodu ekranı ve Diğer Varyantlar'da aynı seçenek ve görünüm

## 2026-10-07 | İyileştirme | Okutulanlarda adet ve silme

Trendyol Bayi Satış ve Mağaza Transfer İrsaliyesi'nde okuttuğunuz ürünleri listeden düzenleyebilirsiniz.

- **×adet** rozetine dokunun: adet güncel envantere göre sınırlanır
- Silme aşamalıdır: **Vazgeç / 1 Adet Çıkar / Tümünü Sil**

## 2026-10-07 | İyileştirme | Toplu onay

Bayi Satış İrsaliyeleri (SORBET onayı, fatura) ve Talepler'de birden fazla kaydı tek seferde onaylayabilirsiniz.

- Kartın üstündeki **Toplu onaya ekle** ile seçin ya da **Tümünü seç**
- İşlem sırasında ilerleme görünür, **Durdur** ile durdurulabilir; sonunda hangisinin onaylandığı, hangisinin hata verdiği listelenir
- Talep sahiplerine bildirim, tek tek onaydaki gibi gider

## 2026-10-07 | İyileştirme | Okutma sesleri ve uyarılar

Barkod okutmada ses ve uyarılar tüm ekranlarda aynı kurala bağlandı.

- Veri geldi → başarılı sesi
- Yanlış / tanımsız barkod → barkod hatası sesi ve **Barkod Hatası** penceresi
- Ürün yok ya da stok yetersiz → hata sesi ve **Ürün Eklenemedi** penceresi
- Çift ses çalma giderildi; kamerada ses, veri gelince aynı anda çalar

## 2026-10-07 | İyileştirme | Ekran düzeni ve mesajlar

- **Mağaza:** Mağaza Parametreleri (Stok Durumu, Fiyat Sorgula, Kampanya Sorgula) ile Transfer İşlemleri (Mağaza Transfer İrsaliyesi, Ürün Transferi) ayrıldı
- **Talepler** Bilgi İşlem Destek İşlemleri'ne taşındı; sıra: Trendyol Bayi Satış, Trendyol İade, Talepler, Tedarikçi Ayırma, Tedarikçi Bilgisi, Fotoğraf
- **Mesajlar ve Sistem Bildirimleri:** okunmuş mesajlarla yeniler arasında "n yeni mesaj" çizgisi
- Etiket önizleme daha hızlı açılır

## 2026-10-07 | Düzeltme | Diğer Varyantlar

Diğer Varyantlar paneli bazen boş açılıyordu, düzeltildi. Panel artık etiket paneliyle aynı görünümde.

## 2026-10-06 | Yenilik | Mağaza Transfer İrsaliyesi

Mağazanızdan başka bir mağazaya ya da merkeze iade olarak transfer irsaliyesi ve e-irsaliye kesebilirsiniz.

### İrsaliye kesme
- **Mağaza → Mağaza Parametreleri → Mağaza Transfer İrsaliyesi**'ni açın; gönderen her zaman bağlı olduğunuz depo / mağazadır
- Sırayla seçin: **araç / sürücü** → **gönderilecek mağaza** → ürünleri okutun
- Kendi mağazanız listede yer almaz; İnternet Mağaza seçilemez
- Stok ve ürün izni Nebim kurallarıyla kontrol edilir; mağazada stok eksiye düşecekse uyarı verilir
- **İrsaliye Kes** ile Nebim'de irsaliye ve e-irsaliye kesilir, e-irsaliye önizlemesi açılır; ekran yeni işlem için baştan başlar

### Merkeze iade
- Gönderilecek yer olarak **Merkez (iade)**'yi seçin, ardından **merkez deposunu** seçin (Merkez ANA, DEFO …)
- İrsaliye merkeze iade olarak kesilir; ürünler merkez kabul edince deposuna girer

### Kesilen irsaliyeler (sağ üstteki simge)
- Kestiğiniz irsaliyeler listelenir; **Gidilen yer** ile mağazaya ya da merkez deposuna göre süzün
- Her irsaliyede **e-İrsaliyeyi Görüntüle / Yazdır**

> Ekranı görmek için "Mağaza Transfer İrsaliyesi" yetkisi gerekir; yöneticiniz Yönetim → Yetkilendirme'den verir.

## 2026-10-06 | Yenilik | e-İrsaliye önizleme ve yazdırma

Kesilen e-irsaliyeyi resmi formuyla (GİB amblemi, QR kod) görüntüleyip yazdırabilirsiniz.

- Telefon ve tablette, iPhone ve Android'de aynı görünür
- **Merkez Ofis:** irsaliye yazıcısı seçili ve kilitli gelir, **Yazıcıya Bas** ile basılır
- **Diğer ofisler:** **Yazdır** ile cihazın yazdırma penceresinden ağdaki yazıcınızı seçin; **Paylaş** ile de gönderebilirsiniz
- Basılınca önizleme kapanır

## 2026-10-06 | İyileştirme | Birden fazla ürün okutma: Barkod Okuyucu ya da Kamera

Ürün okutulan ekranlarda "Birden fazla ürün okut" açılınca nasıl okutacağınızı seçersiniz.

- **Barkod Okuyucu:** barkod alanı hep hazır kalır, okuttuklarınız sırayla listeye eklenir
- **Kamera:** kamera açık kalır, ürünleri art arda okutursunuz
- Kapalıyken kamera tek ürün okutup kapanır
- Trendyol Bayi Satış, Mağaza Transfer İrsaliyesi, Tedarikçi Ayırma ve Tedarikçi Bilgisi ekranlarında aynı
- Stok, Fiyat ve Kampanya ekranlarında barkod alanı açılışta hazır

## 2026-10-06 | Duyuru | Yazıcılar: Merkez Ofis ve mağazalar

Etiket ve e-irsaliye yazdırmada yazıcı, bulunduğunuz ofise göre gelir.

- **Merkez Ofis:** etiket şablonunun ve e-irsaliyenin yazıcısı seçili ve kilitli gelir
- **Mağazalar:** **Yazdır** cihazın yazdırma penceresini açar; ağdaki yazıcınızı oradan seçin

## 2026-10-06 | Düzeltme | Talepler ekranında onay

Talep onaylanırken yeni bir talep gelirse işlem artık yarıda kalmıyor; onay tamamlanır, yeni talep listeye eklenir.

## 2026-10-05 | Yenilik | Trendyol Bayi Satış

Ürünleri art arda okutup SORBET'e bayi satış irsaliyesi kesebilir, SORBET onayından faturaya ve e-faturaya kadar her adımı tek ekrandan takip edebilirsiniz.

### İrsaliye
- **Bilgi İşlem → Trendyol Bayi Satış**'ı açın; kamera açık kalır, okuttuğunuz her ürün altta anında listelenir
- Aynı üründen birden fazla için barkodu her ürün için ayrı okutun; el terminaliyle de okutabilirsiniz
- Depodaki stoktan fazlası okutulamaz; araç / sürücü seçilir, **İrsaliye Oluştur** ile irsaliye ve e-irsaliye kesilir

### Adımlar (sağ üstteki İrsaliyeler)
1. **SORBET Onayı:** gelen ürün SORBET'te onaylanır
2. **Fatura:** onaylanan irsaliyeler birikir; seçtikleriniz ya da **Tümünü Faturala** ile hepsi tek faturada kesilir
3. **E-Fatura:** fatura kesilince sorulur, sonra da gönderilebilir
4. **SORBET Alış:** e-fatura SORBET'in gelen kutusuna düşünce alış faturası olarak alınır

> Faturada fiyat, irsaliyenin kesildiği günkü fiyattır. Her adımı yapan kişi kayda geçer.

## 2026-10-05 | Yenilik | Trendyol İade ve İade Faturaları

Trendyol iadeleri kargo barkodu okutularak tek adımda alınıyor; iade edilen ürünler toplu faturalanıyor.

- **Bilgi İşlem → Trendyol İade:** kargo barkodunu okutun; Trendyol onayı ve Nebim iadesi birlikte yapılır
- Uygun olmayan ürün **Reddet** ile sebep, açıklama ve fotoğrafla reddedilir
- **İade Faturaları** (üstteki fatura simgesi): Fatura → Etiket → E-Fatura → Tena sırasıyla ilerler; farklı faturalara bağlı ürünler tek faturada kesilebilir

## 2026-10-05 | Duyuru | Sunucu ekranları için "API Erişimi" yetkisi

Stok, fiyat, kampanya, talepler, transfer, raporlar ve Bilgi İşlem ekranları artık "API Erişimi" yetkisi istiyor.

- Yetkiniz yoksa ekran açılmaz, **API Erişim Yetkiniz Yok** uyarısı çıkar
- Yetkiyi yöneticiniz **Yönetim → Yetkilendirme**'den verir; verildiği an ekranlar açılır

## 2026-10-05 | Düzeltme | Sunucu uyarısı ve hata düzeltmeleri

Sunucuya ulaşılamadığında uyarı artık beklemeden çıkıyor; hata durumunda ekranlar çökmüyor.

- Sunucu kapalıyken **Sunucu Bağlantısı Yok** uyarısı anında çıkar, ekran asılı kalmaz
- Stok, fiyat ve kampanya ekranları hata aldığında çökmüyor; anlaşılır Türkçe mesaj gösteriliyor
- Fotoğraf ekranında barkod alanı açılışta hazır
- Transfer talepleri sayfalı listelenir; depo listesinde kendi deponuz en üstte

## 2026-10-02 | Düzeltme | Çevrimiçi durumu ve transfer onayı düzeltmeleri

Uygulamayı kapatan kişiler artık mesajlarda çevrimiçi görünmüyor; transfer fişi reddederken / onaylarken çıkan hata giderildi.

- iPhone'da uygulamayı kapatan kişi mesaj listesinde ve sohbette **çevrimiçi** kalıyordu; artık en geç 2,5 dakikada çevrimdışı ve doğru **son görülme** saatiyle görünür
- Sohbet başlığı ve mesaj listesi aynı bilgiyi gösterir
- Transfer fişi reddedilirken / onaylanırken işlem başarılı olsa da çıkan **"İşlem tamamlanamadı"** hatası düzeltildi
- iPhone: zorunlu güncelleme ekranındaki **TestFlight'ta Güncelle** düğmesi TestFlight'ı açar

## 2026-10-02 | Yenilik | Ürünler Arası Transfer

Mağazanızın deposunda bir ürünün adedini başka bir renk/bedene ya da başka bir modele onaylı bir akışla aktarabilirsiniz; envanter onaylanınca anında güncellenir.

### İki transfer tipi
- **Kendi İçinde (Varyantlar Arası):** Aynı modelin bir renk/bedeninden başka bir renk/bedenine
- **Modeller Arası:** Bir modelin renk/bedeninden başka bir modelin renk/bedenine

### Fiş oluşturmak
1. **Mağaza → Ürün Transferi**'ni açın ve transfer tipini seçin
2. Ürünün barkodunu okutun ya da ürün kodunu yazın; yazdıkça eşleşen kodlar listelenir
3. **Kaynak** renk/bedeni seçin (yalnız deponuzda envanteri olanlar seçilebilir), sonra **hedef** renk/bedeni ve **adedi** girin
4. **Fişe Ekle**; bir fişe birden fazla ürün ekleyebilirsiniz
- Adet hiçbir zaman deponuzdaki envanteri aşamaz
- Her satırda kaynakta **−adet**, hedefte **+adet** kutusu görünür; adet değişince anında güncellenir
- Adede dokunarak adedi, hedefe dokunarak hedefi (modeller arasıda modeli de) değiştirebilirsiniz
- **Sil** önce sorar; yanlışlıkla silinmez
- Satırdaki **Etiket Yazdır** ile yeni ürüne onaydan önce etiket basabilirsiniz

### Onaya göndermek
- **Onaya Gönder**'e basınca önizleme açılır: ne nereye kaç adet gidecek ve her renk/bedenin envanteri **kaçtan kaça** değişecek
- *"Kabul ediyor musunuz?"* sorusunu onaylayınca fiş onaylayanlara gider ve bildirim alırlar
- Onaya göndermeden ekrandan çıkarsanız fiş silinir; yarım fiş kalmaz

### Onaylamak (transfer onay yetkisi olanlar)
- Onaylarken de önizleme açılır; deponun **o anki** envanteri gösterilir
- Talepten sonra ürün satıldıysa ve envanter yetmiyorsa uyarı çıkar; onaylanırsa fiş **otomatik reddedilir**
- **Onayla** → stok anında güncellenir; **Reddet** → isterseniz neden yazabilirsiniz
- Kimse kendi oluşturduğu fişi onaylayamaz ya da geri alamaz; onaylanan fiş başka bir yetkili tarafından **geri alınabilir**
- Fişi oluşturana onay, red ve geri alma bildirimi ile **sarı sistem mesajı** gider

> İşlemler her zaman sizin ofisinizin deposunda yapılır ve her adım kim / ne zaman bilgisiyle kayıt altına alınır.

## 2026-10-02 | Yenilik | Talepler: tüm onaylar tek ekranda

Satışa açma talepleri ve ürün transferi onayları artık **Mağaza → Talepler** ekranında birlikte.

- Yetkinize göre **Satışa Açma** ve **Ürün Transferi** sekmeleri görünür
- Bekleyen talep sayısı Talepler kutusunda ve sekme başlıklarında **canlı** güncellenir
- Transfer sekmesinde **Onay Bekleyen**, **Tümü** ve **Fişlerim** filtreleri vardır
- Bildirime ya da sohbetteki sistem mesajına dokununca ilgili sekme açılır

## 2026-10-02 | Yenilik | Etiket yazdırma

Ürün ekranlarından deponuzdaki etiket yazıcısına etiket basabilirsiniz (etiket yazdırma yetkisi olanlar).

- **Stok Durumu** ve **Ürün Kodu Ara** ekranlarında **Etiket Yazdır** düğmesi
- Depo stoklarında kendi deponuzun beden çiplerinde yazıcı ikonu; dokununca o renk/beden için etiket ekranı açılır
- Önce **adet** sorulur (varsayılan 1, **Envanteri kadar yazdır** düğmesi), sonra **etiket tipi** seçilir
- Basmadan önce etiketin önizlemesini görebilirsiniz

## 2026-10-02 | İyileştirme | Sohbette profil kartı ve çevrimiçi durumu

- Sohbette isme ya da fotoğrafa dokununca **profil kartı** açılır; fotoğraf tam ekran büyütülebilir
- Profilde ve sohbet başlığında canlı **Çevrimiçi / Son görülme** bilgisi
- Kendi profil fotoğrafınıza dokunarak büyük görebilir ve değiştirebilirsiniz
- Uygulama arka plana alınınca çevrimiçi durumu doğru kapanır (iPhone'da sürekli çevrimiçi görünüyordu)

## 2026-10-02 | İyileştirme | Daha hızlı ve daha rahat kullanım

- Stok sorgusu ve ürün fotoğrafları **daha hızlı** yükleniyor
- Tüm alt pencereler klavyenin ve alt gezinme çubuğunun üstünde açılır; tablette ortada, okunur genişlikte
- **Yenile** düğmeleri dokununca titreşir, dönerek yenilemenin sürdüğünü gösterir; iki kez basılınca çift istek gitmez
- Bilgilendirme pencereleri türüne göre ses çalar; iPhone sessiz moddayken de
- Kenardan kaydırarak geri dönme her sayfada çalışır
- Yükleme ekranı tüm sayfalarda ekranı tam kaplar

## 2026-10-02 | Düzeltme | Hata düzeltmeleri ve güvenlik

- Yetki seçiminde yanlış sayaç (*"28/29"*) düzeltildi
- Ürün kodu aramasında Enter, yazılanı değil listedeki kodu açar
- Tedarikçi iade listesi artık yalnız e-posta ile gönderilir
- Güvenlik iyileştirmeleri

## 2026-10-01 | Yenilik | Satışa kapalı ürünler için satışa açma talebi

Stok sorgularken satışa kapalı bir ürün gördüğünüzde, tek dokunuşla yetkililerden ürünün satışa açılmasını isteyebilirsiniz.

### Talep göndermek
- Barkod ile **Stok Durumu** ya da **Ürün Kodu** ile sorguladığınızda ürün satışa kapalıysa sarı bir uyarı kartı çıkar
- **Satışa Açılmasını İste**'ye basın; onay verdiğinizde yetkililere bildirim ve sistem mesajı gider
- Talepte adınız, mağazanız, **mağazanızdaki stok** ve **tüm mağazalardaki toplam stok** yer alır
- Ürün için talep zaten gönderildiyse kartta **"Satışa Kapalı - Onay Bekliyor"** ve talep edenler yazar; tekrar göndermeye gerek yoktur

### Onaylamak (satışa açma yetkisi olanlar)
- **Mağaza → Satış Talepleri** ekranında bekleyen talepler listelenir; bekleyen varsa kutu **sarı çerçeveli** olur ve sayısı yazar
- Talep kartında ürün fotoğrafı, kodu, renk/beden, tedarikçi, kampanya ve talep edenlerin stokları görünür
- **Onayla ve Satışa Aç** → *"Emin misiniz?"* → ürün satışa açılır
- Ürünü eskisi gibi **Mağazada Satışa Açık** anahtarıyla açmak da bekleyen talebi kapatır

### Onaydan sonra
- Talep eden kişiye bildirim ve **sarı sistem mesajı** gelir
- Talep edenin mağazasının e-posta adresine ürün bilgileri ve stoklarıyla bilgilendirme e-postası gider

## 2026-10-01 | Yenilik | WhatsApp gibi mesaj bildirimleri ve hızlı yanıt

Mesaj bildirimleri artık kişiye göre gruplanıyor ve uygulamayı açmadan yanıt verebiliyorsunuz.

- Aynı kişiden gelen mesajlar **tek bildirimde** alt alta görünür, başlıkta **"(N mesaj)"** yazar
- Bildirimi aşağı çekince **Yanıtla** alanı açılır; yazdığınız mesaj doğrudan gönderilir (Android)
- Bildirime dokununca ilgili sohbet ya da ekran açılır; giriş yapmanız gerekiyorsa **girişten sonra** o ekrana gidilir
- Bir sohbeti açınca yalnız **o kişinin** bildirimleri temizlenir, diğerleri kalır

## 2026-10-01 | İyileştirme | Sistem bildirimleri sarı, rozetler daha anlaşılır

Sistem bilgilendirmeleri artık sarı renkle normal mesajlardan ayrılıyor.

- **Mesajlar** simgesinde normal mesajlar **kırmızı**, sistem bildirimleri **sarı** sayıyla gösterilir; ikisi birden olabilir
- Mesajlar listesinde **Sistem Bildirimleri** satırı her zaman sarı çerçeveli ve sarı simgelidir
- Sohbetteki sistem mesajları sarı kutuda **"Sistem Bilgilendirmesi"** başlığıyla görünür

## 2026-10-01 | İyileştirme | Kaydırma çubuğu, yukarı çık butonu ve hızlı profil resimleri

Uzun sayfalarda gezinmek ve uygulamaya giriş daha rahat.

- Ekrandan uzun sayfalarda kaydırırken sağda **kaydırma çubuğu** görünür
- Aşağı inildikçe alt menünün üstünde **yukarı çık** butonu çıkar; klavye açıkken klavyenin üstüne yerleşir
- Profil resimleri girişte önceden indirilir; yan menüde **beklemeden** görünür
- Yeni yüklenen profil resimleri küçültülerek kaydedilir, daha hızlı açılır
- **Keşfet**'te yeni duyurular **sarı "YENİ"** etiketi ve sarı çerçeveyle öne çıkar; **Tümünü okundu say** ile hepsini okundu yapabilirsiniz

## 2026-10-01 | Düzeltme | Barkod sorgulama, varyantlar ve kayıt

- Ürün kodu ile aramada sonuç yüklendikten sonra **klavye kendiliğinden açılmıyor**; yalnız alana dokununca açılır
- Boş bir yere dokununca klavye kapanır (tüm ekranlarda)
- **Diğer Varyantlar** paneli beklemeden açılır, yüklenirken panel üstüne panel açılmaz
- Kayıt olurken mağaza listesinde **Merkez Ofis** seçeneği en üstte yer alır

## 2026-09-29 | Yenilik | Mesajlara emoji tepkisi ve emoji gönderme

Mesajlara artık emoji ile tepki verebilir, mesaj yazarken emoji panelinden emoji ekleyebilirsiniz.

### Emoji tepkileri
- Mesaja **basılı tutun**; üstteki hızlı tepkilerden birini seçin (👍 ❤️ 😂 😮 😢 🙏) ya da **+** ile tüm emojileri açın
- Tepkiler mesajın altında görünür; aynı emojiyi birden fazla kişi koyduysa sayısı yazar
- Tepkiye dokunarak kendi tepkinizi ekleyip kaldırabilirsiniz; her mesaja bir tepki verilebilir

### Bildirim ve sohbet listesi
- Mesajınıza tepki verildiğinde bildirim gelir: *"Mesajına ❤️ bıraktı"*
- Sohbet listesinde son mesaj yerine **son yapılan işlem** görünür; tepki verildiyse o sohbet en üste çıkar

### Emoji gönderme
- Mesaj kutusundaki **😊** simgesiyle emoji paneli açılır, seçilen emoji yazının içine eklenir
- **⌨️** simgesiyle ya da mesaj kutusuna dokunarak klavyeye dönülür

## 2026-09-29 | İyileştirme | Yönetim panelinde işlem sonrası geri dönüş

Kaydet, onayla, yetki ver gibi işlemlerden sonra "Tamam"a basınca artık önceki sayfaya dönülüyor.

- Kullanıcı düzenleme: profil, e-posta, şifre, hesap durumu, onay ve API anahtarı işlemleri
- Kullanıcı yetkilerini kaydetme
- Önceki sayfadaki liste yapılan değişiklikle güncel gelir

## 2026-09-29 | Düzeltme | Kamera ve alt menü düzeltmeleri

Kamera görüntüsü açılırken siyah ekran yerine yükleniyor göstergesi çıkıyor; alt menüler sanal tuşların arkasında kalmıyor.

- Kamera açılırken ilk görüntü gelene kadar **Bağlanıyor…** göstergesi döner
- Sanal (geri / ana sayfa) tuşları olan telefonlarda alttan açılan menüler artık tam görünür
- Mesaja basılı tutunca açılan menü klavyenin altında kalmaz

## 2026-09-25 | Yenilik | Fiyatlarda eski fiyat gösterimi

Peşin fiyat değiştiyse eski fiyat artık üstü çizili olarak görünüyor.

### Neler eklendi
- Stok Durumu, Fiyat Sorgula ve ürün kodu arama ekranlarında peşin fiyatın üstünde **Eski fiyat** satırı
- Eski fiyat yalnızca güncel fiyattan farklıysa gösterilir

> Fiyatlar her okutmada merkezden anlık alınır.

## 2026-09-25 | Yenilik | Mesajlaşma baştan yenilendi

Mesaj bildirimleri artık uygulama kapalıyken de anında geliyor; sohbet ekranları yeni tasarımla daha hızlı ve anlaşılır.

### Bildirimler
- Yeni mesajda telefonunuza **tek bir bildirim** gelir; uygulama kapalı ya da arka plandayken de
- Açık sohbetteyken gelen mesaj için ayrıca bildirim gösterilmez
- Bildirime dokununca doğrudan ilgili sohbet açılır

### Sohbet ekranı
- Gönderilen mesaj internet yokken saat simgesiyle bekler, bağlantı gelince gönderilir
- **İletildi** ve **okundu** işaretleri artık doğru ve anlık
- Karşı taraf yazarken "yazıyor…" göstergesi
- Son 50 mesaj hemen açılır; yukarı kaydırınca eski mesajlar yüklenir
- Fotoğraf gönderme ve mesaja yanıt verme

### Sohbet listesi ve kişiler
- Kişi adında ve mesajlarda arama
- **Okunmamış** ve kişisel sohbet filtreleri
- Kişiler ekranında çevrimiçi olanları gösteren filtre

## 2026-09-25 | İyileştirme | Stok okutma ve varyant listeleme

Barkod okutma daha hızlı; ürün, fiyat ve stok bilgisi tek bakışta okunuyor.

### Barkod alanı
- Sayfaya girince ekran klavyesi açılmaz; terminal okuyucu doğrudan yazar
- Elle yazmak için alandaki **klavye ikonuna** basın
- Kamera ile okutmada yalnızca ortadaki çerçevedeki barkod okunur; raftaki yan barkodlar karışmaz

### Ürün bilgisi
- Ürün fotoğrafları büyük gösterilir, kaydırarak diğerlerine geçilir
- Peşin ve taksitli fiyat büyük kutularda, aktif kampanya dikkat çekici bir bantta
- Ürün adı, kod, renk, beden ve tedarikçi tek kartta

### Diğer varyantlar
- Stoklu renk/beden varyantları **depoya** ya da **renge göre** gruplanır
- Kendi mağaza deponuz her zaman en üstte ve açık gelir
- **Benim Depom / Tüm Depolar** özeti
- Bedenler doğru sırada: sayısal küçükten büyüğe, harfliler XS → XXL

## 2026-09-25 | Yenilik | Kayıt ve giriş sistemi

Kayıt olmak artık daha kolay; kullanıcı adınız otomatik oluşuyor, mağazanızı kendiniz seçiyorsunuz.

### Kayıt
- Kullanıcı adı ad ve soyadınızdan otomatik oluşur (örn. `goktug.kocer`)
- Adınız düzgün biçimde kaydedilir: **Göktuğ KOÇER**
- Kayıt sırasında çalıştığınız **mağazayı listeden seçersiniz**
- Kaydınız yönetici onayından sonra açılır; yetkileriniz onayla birlikte tanımlanır

### Giriş ve güvenlik
- **Beni hatırla** artık şifrenizi telefona kaydetmez; oturum güvenli şekilde saklanır
- Şifreler yalnızca giriş sisteminde tutulur; yöneticinin verdiği yeni şifre hemen geçerli olur
- Hesabı pasife alınan kullanıcının açık oturumları kapanır

### Açılış
- Uygulama Tena logosu ve yükleme animasyonuyla açılır
- Güncel sürümü kullananlar yanlışlıkla güncelleme ekranında kalmaz
- Sunucu bağlantısı koparsa uyarı çıkar, bağlantı gelince devam edilir
- Uygulama açıkken ekran kararmaz

## 2026-09-25 | İyileştirme | Yeni tema ve tasarım

Tüm uygulama tek, modern bir lacivert-mor temaya geçti.

- Bütün ekranlarda aynı kartlar, butonlar ve renkler
- İşlem sonuçları kaybolan kısa yazılar yerine **net pencerelerle** gösterilir: yükleniyor → başarılı / hata
- Yan menü yenilendi: profil kartı, mesaj sayıları, hesap ayarları ve çıkış
- Alt menüdeki **Profil** doğrudan profil sayfasını açar
- Sekmelerde başlık ile içerik arası boşluk eşitlendi
- Keşfet sekmesi artık duyuru ve yenilik ekranı

## 2026-09-25 | Yenilik | Profil ve hesap ayarları

Profil sayfası yenilendi; şifrenizi değiştirebilir, dilerseniz hesabınızı silebilirsiniz.

### Neler değişti
- Profil sekmesinde hesap bilgileriniz, mağazanız ve yetkiniz
- **Hesap Ayarları**: ad, soyad, telefon ve profil fotoğrafı
- Şifre değiştirme artık doğrudan giriş şifrenizi günceller
- Hesabı silme: onay ve şifre doğrulamasıyla

> Hesap silindiğinde sohbetleriniz ve fotoğraflarınız da kalıcı olarak silinir.

## 2026-09-25 | İyileştirme | Tedarikçi Ayırma, Tedarikçi Bilgisi ve Fotoğraf ekranları yenilendi

Üç ekran yeni tasarıma taşındı; okutma daha hızlı, hata mesajları daha anlaşılır.

### Tedarikçi Ayırma
- E-posta ve Telegram gönderim sonucu artık ayrı ayrı gösteriliyor
- Aynı barkod listede tek satırda toplanıyor
- Barkod alanı her okutmadan sonra otomatik odaklanıyor

### Tedarikçi Bilgisi
- Ürünler telefona uygun kartlarla listeleniyor
- İnternet ya da sunucu hataları artık "ürün bulunamadı" diye görünmüyor
- Barkod alanı her okutmadan sonra otomatik odaklanıyor

### Fotoğraf
- Fotoğraflar ızgara görünümünde, arama ile bulunabiliyor
- Aynı ürüne yeni fotoğraf eskisinin yerine geçiyor

## 2026-09-25 | İyileştirme | Mağaza kameraları

Canlı izleme ve kayıtlar gerçek bir kamera uygulaması gibi çalışıyor.

### Canlı izle
- Ekranı **1, 4 ya da 9** kameraya bölme
- Tam ekran ve HD görüntü
- Kanal listesinden hızlı geçiş

### Kayıtlar
- Zaman çizelgesi üzerinde kaydırarak izleme
- Gün seçimi ve anlık tarih/saat göstergesi
- Görüntüden ekran görüntüsü alıp paylaşma

> Kamera izleme artık yetkiye bağlıdır. Göremiyorsanız yöneticinizden **Mağaza Kamera İzleme** yetkisini isteyin.

## 2026-09-25 | Yenilik | Mağaza cirosu ve personel raporları

Geçmiş ayların verileri artık görüntülenebiliyor.

- Mağaza Cirosu ve Personel Performansı ekranlarına ay ve tarih filtresi
- **Geçmiş Aylar**: son 12 ayın hedef gerçekleşme oranları, en iyi ay ve üst üste hedef serisi
- Günlük gereken satış, bugünkü satış ve ay sonu tahmini

## 2026-09-25 | İyileştirme | Yönetim paneli

Kullanıcı, yetki ve mağaza yönetimi yeni tasarımla daha hızlı ve güvenli.

- Yeni kullanıcı onayında yetki ve **başlangıç yetkileri** tek ekranda seçilir
- Onaylanan kullanıcıya API anahtarı otomatik atanır
- Kullanıcı şifresi değiştirildiğinde giriş şifresi de değişir
- Yetkiler, Yetkilendirme, Reddedilenler ve Mağazalar sayfaları yenilendi

## 2026-09-25 | Duyuru | Kaldırılan özellikler

Kullanılmayan bazı bölümler uygulamadan kaldırıldı.

- Sayım Gerçekleştir
- Sipariş Yönetimi
- Satış Raporu
- Anket Yönetimi
- Lokasyon Stok
- Trendyol İade

> Bu bölümlerle ilgili bir ihtiyacınız olursa bilgi işlem birimine iletebilirsiniz.
