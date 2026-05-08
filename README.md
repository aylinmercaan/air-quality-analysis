# Air Quality PCA Analysis

Bu proje, hava kalitesi verileri üzerinde veri temizleme, eksik veri tamamlama, temel bileşen analizi (PCA) ve matematiksel modelleme adımlarını içeren bir MATLAB çalışmasıdır.

## Proje Amacı

Bu çalışmanın amacı, hava kalitesi ölçümlerinden yararlanarak genel bir hava kirliliği göstergesi oluşturmak ve zaman içindeki kirlilik eğilimini analiz etmektir.

Veri setindeki eksik değerler lineer interpolasyon yöntemiyle doldurulmuş, ardından değişkenler normalize edilerek PCA uygulanmıştır. Birinci temel bileşen (PC1), genel hava kirliliği indeksi olarak yorumlanmıştır.

## Kullanılan Teknolojiler

- MATLAB
- Live Script (.mlx)
- PCA
- Veri görselleştirme
- Polinom eğri uydurma
- Sayısal integral

## Uygulanan Adımlar

- AirQuality veri setinin içe aktarılması
- Tarih ve saat bilgilerinin birleştirilerek zaman ekseni oluşturulması
- Eksik verilerin lineer interpolasyon ile doldurulması
- Ham ve temizlenmiş verinin görselleştirilmesi
- Verinin Z-score normalizasyonu
- Kovaryans matrisi hesaplama
- Özdeğer ve özvektör analizi
- PCA ile temel bileşenlerin çıkarılması
- PC1 üzerinden genel hava kirliliği indeksi oluşturulması
- Polinom eğri uydurma ile kirlilik trendinin modellenmesi
- Kritik eşik analizi yapılması
- Sayısal integral ile toplam kirlilik yükünün hesaplanması

## Modelleme Yaklaşımı

Projede hava kalitesi değişkenleri normalize edildikten sonra kovaryans matrisi oluşturulmuştur. Bu matris üzerinden özdeğer ve özvektör analizi yapılarak PCA uygulanmıştır.

Birinci temel bileşen (PC1), veri setindeki genel değişimi temsil ettiği için hava kirliliği indeksi olarak kullanılmıştır. Daha sonra PC1 zaman serisi üzerinde polinom eğri uydurma uygulanarak kirlilik eğilimi modellenmiştir.

## Sonuç

Bu çalışma sonucunda hava kalitesi verileri temizlenmiş, PCA ile daha düşük boyutlu bir gösterim elde edilmiş ve PC1 üzerinden genel kirlilik trendi analiz edilmiştir.

Ayrıca kritik eşik analizi ve sayısal integral yöntemiyle kirlilik seviyesinin belirli dönemlerdeki davranışı incelenmiştir.

## Not

Bu proje eğitim ve portfolyo amacıyla hazırlanmıştır. Veri dosyası repoya dahil edilmemiştir.
