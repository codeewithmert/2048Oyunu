# 2048 Web Oyunu

## Açıklama

Bu proje, JavaScript, HTML5 ve CSS3 kullanılarak geliştirilmiş, modern ve modüler bir 2048 web oyunudur. Kullanıcılar klavye veya dokunmatik kontrollerle oynayabilir, skorlarını takip edebilir, oyunu sıfırlayabilir ve responsive arayüz sayesinde her cihazda keyifle oynayabilir.

## Özellikler
- 4x4 klasik 2048 oyun tahtası
- Klavye ve dokunmatik kontrol desteği
- Skor ve en yüksek skor takibi (localStorage)
- Hızlı ve akıcı animasyonlar
- Oyun sonu ve kazanma bildirimleri
- Yeniden başlatma (reset) seçeneği
- Mobil ve masaüstü uyumlu responsive tasarım
- Koyu/açık tema desteği (isteğe bağlı)
- Temiz, modüler ve anlaşılır kod yapısı
- Tüm kod yorumlu ve dokümantasyonlu

## Klasör Yapısı
```
.
├── index.html
├── README.md
├── LICENSE
├── js/
│   ├── animframe_polyfill.js
│   ├── application.js
│   ├── bind_polyfill.js
│   ├── classlist_polyfill.js
│   ├── game_manager.js
│   ├── grid.js
│   ├── html_actuator.js
│   ├── keyboard_input_manager.js
│   ├── local_storage_manager.js
│   └── tile.js
├── style/
│   └── main.css
```

## Kurulum
```bash
# Sadece dosyaları indirin ve açın
# Ekstra bağımlılık veya kurulum gerekmez
```

## Kullanım
- `index.html` dosyasını bir tarayıcıda açın.
- Klavye ok tuşları veya dokunmatik hareketlerle oynayın.
- Skorunuzu ve en yüksek skorunuzu takip edin.
- Oyunu sıfırlamak için arayüzdeki "Yeniden Başlat" butonunu kullanın.

## Özelleştirme
- Oyun tahtası boyutunu veya tema renklerini değiştirmek için `js/` ve `style/` klasörlerindeki dosyaları düzenleyin.
- Kendi logonuzu veya marka renklerinizi ekleyin.
- Yeni özellikler veya animasyonlar ekleyin.

## Lisans
MIT
