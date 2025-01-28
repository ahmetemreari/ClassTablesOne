# Sınıf Tablosu Projesi

Bu proje, öğrenci bilgilerini görüntülemek için oluşturulmuş basit bir HTML tablosudur. CSS ile stillendirilmiş modern ve responsive bir tasarıma sahiptir.

## Proje Yapısı

```
sinif-tablosu/
├── index.html
└── css/
    └── sinif_tablosu.css
```

## Özellikler

- Responsive tablo tasarımı
- Modern görünüm
- Hover efektleri
- Çift satırlarda farklı arka plan rengi
- Gölge efekti
- Yuvarlatılmış köşeler

## Kurulum

1. Projeyi bilgisayarınıza indirin
2. `index.html` dosyasını bir web tarayıcısında açın

## CSS Özellikleri

### Tablo Temel Özellikleri
- Genişlik: 100%
- Gölge efekti
- Beyaz arka plan
- Yuvarlatılmış köşeler

### Başlıklar (th)
- Yeşil arka plan (#4CAF50)
- Beyaz yazı rengi
- Kalın yazı tipi
- Büyük harfler
- Alt kenarlık (3px)

### Hücreler (td)
- İç boşluk: 12px 15px
- Alt kenarlık: 1px
- Gri yazı rengi

### Hover Efekti
- Açık gri arka plan
- Geçiş animasyonu

### Çift Satırlar
- Açık gri arka plan (#f8f8f8)

## HTML Yapısı

```html
<table>
    <tr> <!-- Başlık satırı -->
        <th>Ad</th>
        <th>Soyad</th>
        <th>Doğum Tarihi</th>
        <th>Not</th>
        <th>Öğrenci Numarası</th>
    </tr>
    <tr> <!-- Veri satırı -->
        <td>...</td>
        <td>...</td>
        <td>...</td>
        <td>...</td>
        <td>...</td>
    </tr>
</table>
```

## Tarayıcı Desteği

- Chrome (son sürüm)
- Firefox (son sürüm)
- Safari (son sürüm)
- Edge (son sürüm)
- Opera (son sürüm)

## Geliştirme

Yeni özellikler eklemek veya mevcut özellikleri değiştirmek için:
1. CSS dosyasını düzenleyin
2. HTML dosyasına yeni içerik ekleyin
3. Değişiklikleri tarayıcıda test edin
