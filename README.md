# aysecetin.github.io

Portfolyo sayfası. Tek dosya: `index.html` — derleme adımı, bağımlılık ve
paket yok. Dosyayı değiştirip `main` dalına ittiğin anda GitHub Pages yeniden
yayınlıyor.

Adres: <https://aysecetin.github.io/>

## Düzen

Sayfa bir saha kayıt föyü gibi kurgulandı: her iş *kim kullanıyor / hangi
koşulda / ne yapıyor / benim yaptığım / durum* satırlarıyla yazılıyor. Bunun
sebebi projelerin ortak hikâyesi: hepsi masa başında olmayan biri için
yapıldı.

- Gövde yazı tipi **Atkinson Hyperlegible** — düşük görme için tasarlanmış bir
  yüz. SürüTakip'in kullanıcı tezinin sayfanın kendisindeki karşılığı.
- Başlıklar **Newsreader**.
- Renkler `:root` altındaki değişkenlerde; koyu tema `prefers-color-scheme` ile
  geliyor. Yazdırma için ayrı bir `@media print` bloğu var.

## Açık kalan iş

**Projelere link yok.** SürüTakip, DisasterAI, Daily Brew ve Color Gates
depolarının hepsi private, o yüzden sayfada hiçbir proje linki verilmedi.
Karar verilince iki yol var:

1. Seçilen depoları public yapıp `.record-head` içine depo linki eklemek.
2. Depoları private bırakıp canlı demo adreslerini eklemek.

İkisi de `index.html` içinde ilgili `<article class="record">` bloğuna bir
`<a>` eklemekten ibaret.
