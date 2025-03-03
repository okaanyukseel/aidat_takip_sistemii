# Aidat Takip Uygulaması

Dernek, apartman veya benzeri toplulukların üye aidatlarını takip etmek için geliştirilmiş bir web uygulaması.

## Özellikler

- Üye yönetimi (ekleme, düzenleme, silme)
- Aidat takibi (ödeme durumu, tarih, miktar)
- Kullanıcı dostu arayüz
- Arama ve filtreleme özellikleri
- Responsive tasarım

## Kurulum

1. Projeyi klonlayın:
   ```
   git clone https://github.com/KULLANICI_ADINIZ/aidat-takip-uygulamasi.git
   cd aidat-takip-uygulamasi
   ```

2. Sanal ortam oluşturun ve aktifleştirin:
   ```
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # Linux/Mac
   source venv/bin/activate
   ```

3. Gerekli paketleri yükleyin:
   ```
   pip install -r requirements.txt
   ```

4. Veritabanını oluşturun:
   ```
   python db_setup.py
   ```

5. Uygulamayı çalıştırın:
   ```
   python app.py
   ```

6. Tarayıcınızda aşağıdaki adresi açın:
   ```
   http://127.0.0.1:5000
   ```

## Teknolojiler

- **Backend**: Python Flask
- **Veritabanı**: SQLite
- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5
- **İkonlar**: Font Awesome

## Ekran Görüntüleri

![Ana Sayfa](screenshots/anasayfa.png)
![Üye Listesi](screenshots/uyeler.png)
![Aidat Ekleme](screenshots/aidat_ekle.png)

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.
