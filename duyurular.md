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
- Sıra önemli değil; uygulama tarihe göre en yeniyi üste koyar.
- Yeni duyurular kullanıcıya "YENİ" etiketiyle gösterilir.

## 2026-09-25 | Yenilik | Fiyatlarda eski fiyat gösterimi

Peşin fiyat değiştiyse eski fiyat artık üstü çizili olarak görünüyor.

### Neler eklendi
- Stok Durumu, Fiyat Sorgula ve ürün kodu arama ekranlarında peşin fiyatın üstünde **Eski fiyat** satırı
- Eski fiyat yalnızca güncel fiyattan farklıysa gösterilir

> Fiyatlar her okutmada merkezden anlık alınır.

## 2026-09-25 | İyileştirme | Tedarikçi Ayırma, Tedarikçi Bilgisi ve Fotoğraf ekranları yenilendi

Üç ekran yeni tasarıma taşındı; okutma daha hızlı, hata mesajları daha anlaşılır.

### Tedarikçi Ayırma
- E-posta ve Telegram gönderim sonucu artık ayrı ayrı gösteriliyor
- Aynı barkod listede tek satırda toplanıyor
- Barkod alanı her okutmadan sonra otomatik odaklanıyor

### Tedarikçi Bilgisi
- Ürünler telefona uygun kartlarla listeleniyor
- İnternet ya da sunucu hataları artık "ürün bulunamadı" diye görünmüyor

### Fotoğraf
- Fotoğraflar ızgara görünümünde, arama ile bulunabiliyor
- Aynı ürüne yeni fotoğraf eskisinin yerine geçiyor

## 2026-09-25 | Yenilik | Profil ve hesap ayarları

Profil sayfası yenilendi; şifrenizi değiştirebilir, dilerseniz hesabınızı silebilirsiniz.

### Neler değişti
- Profil sekmesinde hesap bilgileriniz, mağazanız ve yetkiniz
- **Hesap Ayarları**: ad, soyad, telefon ve profil fotoğrafı
- Şifre değiştirme artık doğrudan giriş şifrenizi günceller
- Hesabı silme: onay ve şifre doğrulamasıyla

## 2026-09-25 | Düzeltme | Mağaza cirosu ve personel raporları

Geçmiş ayların verileri artık görüntülenebiliyor.

- Mağaza Cirosu ve Personel Performansı ekranlarına ay ve tarih filtresi
- **Geçmiş Aylar**: son 12 ayın hedef gerçekleşme oranları
