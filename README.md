# İnsan Statları

İnsan özelliklerini farklı kategorilerde puanlayıp, sonuçları futbolcu kartı görünümünde bir görsele dönüştüren Türkçe bir web uygulaması.

## Özellikler

- Fiziksel özellikler, sosyal beceriler, zihinsel kapasite, yaşam becerileri, karakter, duygusal zeka, iş ve organizasyon gibi kategorilerde değerlendirme yapın.
- Her özelliği **1–10** arasında puanlayın; kategori puanları ve genel puan (OVR) otomatik hesaplansın.
- İsim ve fotoğraf ekleyerek kişiselleştirilmiş kartınızı oluşturun.
- Puanınıza göre kart teması otomatik seçilsin.
- Kartı PNG olarak indirin; Instagram Story paylaşımı için kullanın.

## Çalıştırma

Uygulama derleme veya paket kurulumu gerektirmeyen statik bir web sayfasıdır. `index.html`, `data.json` ve `ratings/` klasörünü birlikte sunmanız gerekir. Veriler `fetch()` ile yüklendiği için dosyayı doğrudan `file://` üzerinden açmak yerine yerel bir web sunucusu kullanın.

Python 3 yüklüyse depo klasöründe şu komutları çalıştırın:

```bash
python -m http.server 8000
```

Ardından tarayıcıda [http://localhost:8000](http://localhost:8000) adresini açın.

## Kullanım

1. Kart oluşturucuya adınızı yazın.
2. İsteğe bağlı olarak fotoğraf çekin veya bir görsel yükleyin.
3. Kategorilerdeki özelliklere 1–10 arasında puan verin.
4. Oluşan kartı görmek için **Instagram Story İçin İndir** düğmesine basın.

## Proje dosyaları

- `index.html` — Arayüz, puanlama ve kart oluşturma işlevleri.
- `data.json` — Kategori ve özellik adları ile açıklamaları.
- `ratings/` — Puan seviyelerine göre kullanılan kart arka plan görselleri.

## Teknolojiler

HTML, CSS ve JavaScript. Harici kütüphane veya derleme aracı gerektirmez.
