# NCTKGS — NovaCast Türk Kanalları Güncelleme Sistemi

Gerçek uydu alıcılarındaki **TKGS** mantığından ilham alınarak **Sparkle TV** ve uyumlu IPTV oynatıcılar için hazırlanan, tek parça ve otomatik güncellenebilen Türkçe kanal listesi altyapısı.

## İçerik
- `nctkgs_list.m3u8`: Ulusal, Haber, Spor, Çocuk, Belgesel & Kültür, Müzik, Uluslararası ve Yerel kategorilerini içeren tek dosya M3U8 oynatma listesi.
- **EPG Desteği:** Kanal kimlikleri (`tvg-id`) XMLTV rehber eşleşmelerine (`turkey1.xml` / `epg_TR.xml.gz`) uyumlu şekilde düzenlenmiştir.

## Kurulum (Sparkle TV)
1. `nctkgs_list.m3u8` dosyasının GitHub **Raw** bağlantısını kopyalayın.
2. **Sparkle TV > Ayarlar > Kaynaklar > Kaynak Ekle > M3U Oynatma Listesi** bölümüne yapıştırın.
3. EPG bağlantısını tanımlayın ve otomatik güncelleme aralığını (**Her 6 Saatte Bir** / **Açılışta Güncelle**) aktif edin.

## Not
- Açık ve ücretsiz yayın akışları temel alınmıştır; şifreli/abonelik gerektiren yayınlar listede yer almaz.
- Geliştirici: `novalang-dev`
