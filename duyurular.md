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
