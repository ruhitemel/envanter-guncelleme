# Envanter güncelleme dosyaları

Bu herkese açık depo yalnızca Envanter programının temiz dağıtım paketini ve
sürüm bilgisini içerir. Kaynak kod özel depodadır.

- `surum.json` — güncel sürüm numarası, indirme adresi ve SHA-256 özeti
- `Envanter-USB.zip` — 6 güvenli dosyalı temiz paket

Program açılışta `surum.json` dosyasını okur. Yeni sürüm varsa kullanıcıya sorar;
onaylanırsa zip'i indirir, SHA-256 doğrular ve yalnızca `Envanter.exe`,
`sablon.xlsx`, `KULLANIM.txt`, `KULLANIM.md` dosyalarını günceller.
`Envanter.xlsx`, `ayarlar.json`, `metinler.json` ve `envanter.log` asla değiştirilmez.
