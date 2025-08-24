# Kredi Kartı Harcamaları Veri Analizi Projesi
Bu proje, kredi kartı kullanıcılarının harcama verilerini analiz etmek ve görselleştirmek amacıyla hazırlanmıştır. Python ile veri analizi ve Power BI ile dashboard oluşturma aşamalarını içermektedir.

## Proje Amacı
- Kullanıcı harcama verilerini analiz ederek anlamlı çıkarımlar elde etmek.
- Harcama davranışlarını şehir, saat, cinsiyet ve gelir gruplarına göre görselleştirmek.
- Python ve Power BI kullanarak analiz sonuçlarını görselleştirmek.

## Kullanılan Veri Setleri
- **users.csv**: Kullanıcılara ait bilgiler.
- **transactions.csv**: Kredi kartı harcamaları.

## 1. Aşama: Python ile Veri Görselleştirme
### Yapılan İşlemler
1. **Veri Yükleme ve Temizleme**
   - `users.csv` ve `transactions.csv` dosyaları okunup birleştirildi.
2. **En Fazla Harcama Yapılan Şehirler**
   - `Merchant City` kolonuna göre toplam harcama miktarları hesaplandı.
   - İlk 10 şehir bar grafiği ile görselleştirildi.
3. **Saatlik Harcama Dağılımı**
   - Saatlik toplam harcama hesaplandı ve çizgi grafik ile görselleştirildi.
4. **Cinsiyete Göre Harcama**
   - Kullanıcıların cinsiyetine göre toplam harcama gruplandı ve bar grafik ile gösterildi.
5. **Gelire Göre Harcama**
   - Gelir ile harcama arasındaki ilişki scatter plot ile görselleştirildi.
6. **Yorum ve Sonuç**
   - Her grafik için kısa açıklamalar ve çıkarımlar yapıldı.

### Python Çalışır Halinin Ekran Görüntüleri
![En Fazla Harcama Yapılan Şehirler](C:\Users\ASUS\Pictures\Screenshots\Ekran görüntüsü 2025-08-24 205257.png)  
![Saatlik Harcama Dağılımı](C:\Users\ASUS\Pictures\Screenshots\Ekran görüntüsü 2025-08-24 210121.png)  
![Cinsiyete Göre Harcama](C:\Users\ASUS\Pictures\Screenshots\Ekran görüntüsü 2025-08-24 210730.png)  
![Gelire Göre Harcama](C:\Users\ASUS\Pictures\Screenshots\Ekran görüntüsü 2025-08-24 211005.png)


## 2. Aşama: Power BI ile Veri Görselleştirme
### Yapılan İşlemler
1. **Veri Yükleme ve Temizleme**
   - `users.csv` ve `transactions.csv` dosyaları Power BI içerisine yüklendi ve ilişkilendirildi.
2. **Dashboard İçerikleri**
   - En fazla harcama yapılan 10 şehir.
   - Harcamaların saate göre dağılımı.
   - Harcamaların cinsiyete göre dağılımı.
   - Gelir grubuna göre harcama dağılımı.

