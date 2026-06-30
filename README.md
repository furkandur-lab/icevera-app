# icevera — Cari & Stok Takip

Tek dosyalık, kuruluma ihtiyaç duymayan bir cari ve stok takip uygulaması. Tüm veriler tarayıcınızda (localStorage) saklanır; sunucu veya veritabanı gerekmez.

## GitHub'da yayınlama (GitHub Pages)

1. GitHub'da yeni bir repo oluşturun (örn. `icevera-takip`).
2. Bu klasördeki `index.html` dosyasını repoya yükleyin (sürükle-bırak veya `git push` ile).
3. Repo **Settings → Pages** menüsünden:
   - Source: `Deploy from a branch`
   - Branch: `main` / `(root)` seçip kaydedin.
4. Birkaç dakika içinde uygulamanız şu adreste yayında olacak:
   `https://kullaniciadiniz.github.io/icevera-takip/`

## Yerel kullanım

`index.html` dosyasını çift tıklayarak tarayıcıda doğrudan da açabilirsiniz, internet bağlantısı gerekmez (logo görseli hariç).

## Özellikler

- **Cariler**: Müşteri/tedarikçi kartları, telefon, vergi no, açılış bakiyesi.
- **Stok**: Ürün, birim, alış/satış fiyatı, miktar, kritik stok uyarısı.
- **Hesap Hareketleri**: Satış, alış, tahsilat, ödeme, manuel borç/alacak. Satış ve alışta ürün satırı seçilince stok otomatik güncellenir.
- **Ekstre / Dekont**: icevera antetli kağıdı ile yazdırılabilir cari hesap ekstresi veya tekil dekont (PDF için tarayıcının "Yazdır → PDF olarak kaydet" seçeneğini kullanabilirsiniz).
- **Ayarlar**: Antetli kağıtta görünen firma bilgilerini ve logo adresini değiştirebilirsiniz.
- **Yedekleme**: Ayarlar sekmesinden tüm verinizi JSON olarak indirip, başka bir cihazda geri yükleyebilirsiniz.

## Önemli not

Veriler yalnızca kullandığınız tarayıcıda saklanır. Farklı bir bilgisayardan veya tarayıcıdan girdiğinizde veriler görünmez — bu yüzden düzenli olarak "Yedek İndir" ile dışa aktarma yapmanız ve ekibinizin aynı cihaz/tarayıcıyı kullanması (ya da yedeği paylaşması) önerilir.
