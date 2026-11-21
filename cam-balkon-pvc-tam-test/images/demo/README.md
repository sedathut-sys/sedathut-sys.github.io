# Cam Balkon & PVC — Görsel varlıkları

**Durum:** 18 Kasım 2026 tarihinde WebP ve PNG dosyaları izole geliştirme dalına eklendi. Yerel görsel paketi ile GitHub ikili dosyalarının SHA-1 blob kimlikleri karşılaştırıldı ve birebir eşleşti.

## Web için optimize edilmiş dosyalar

- `hero-cam-balkon.webp` — ana sayfa, 1600 × 900
- `cam-balkon-dis-cephe.webp` — cam balkon dış cephe
- `cam-balkon-kis-bahcesi.webp` — cam balkon iç mekân
- `pvc-pencere.webp` — PVC pencere/kapı ortamı
- `logo-cam-balkon-pvc.png` — kullanıcı onaylı yatay logo
- `logo-isaret.png` — kullanıcı onaylı küçük marka işareti

Ek olarak önceki hazırlık sürümünden `*.svg` logolar tutuluyor. Sayfa şablonu PNG asıllarını kullanır.

## Kullanım

`src/lib/demo-assets.ts` yolları merkezî tutar. `demoImageUrl(base, source)` hem site kökünde hem `/cam-balkon-pvc-tam-test/` alt yolunda görsel adresini doğru oluşturur.

**Etiket:** Bu görseller yapay zekâ ile oluşturulmuştur; gerçek işletmenin tamamlanmış projesi, müşteri referansı veya fotoğraflanmış uygulaması değildir. Canlı müşteri sitesinde gerçek fotoğrafla değiştirilmelidir.
