[README.md](https://github.com/user-attachments/files/29551774/README.md)
# Luneth & Lord Carsus — Karanlıktan Doğan Işık

Otofiksiyon türünde, baskı-hazır (print-ready) tek dosyalık bir HTML kitap projesi. Kapak, iç kapak, içindekiler, ithaf sayfaları, bölümler ve arka kapak dahil olmak üzere tam bir kitap düzeni tek bir `book.html` dosyasında tanımlıdır.

## İçerik

- **Kapak & arka kapak** — gece mavisi/lacivert zemin üzerine gümüş tonlarında tipografi, dekoratif çerçeve ve sahte barkod
- **İç kapak & içindekiler**
- **İthaf sayfaları**
- **5 bölüm** + *Ophelia'nın Son Mektubu* + *Epilog*
- Her bölümün sonunda **"Psikolojik Not"** ve **"Ey Okuyucu!"** kutuları
- 6in × 9in sayfa boyutunda, baskıya hazır `@page` ayarları

## Tema

Zemin: koyu lacivert / gece mavisi (`#0a1024`)
Metin & vurgular: gümüş tonları (`#c3cadf`, `#a9b8e0`, `#8b98c2`)
Font: Georgia / Palatino Linotype / Liberation Serif (serif)

## Kullanım

Dosyayı bir tarayıcıda açıp **Yazdır → PDF olarak kaydet** ile PDF çıktısı alabilirsiniz:

```bash
# Yerelde önizleme
open book.html        # macOS
xdg-open book.html    # Linux
start book.html       # Windows
```

Tarayıcı yazdırma ayarlarında:
- Kağıt boyutu: **6in × 9in** (özel boyut)
- Kenar boşukları: **Yok** (dosya içinde zaten tanımlı)
- Arka plan grafikleri: **Açık** (tema renklerinin ve dokunun görünmesi için gerekli)

## Dosya Yapısı

```
.
├── book.html    # Tüm kitap: stil + içerik tek dosyada
└── README.md
```

## Notlar

- Emoji kullanımı yerine, PDF dönüştürücüler arasında tutarlı görünmesi için bazı ifadeler inline SVG ikon olarak gömülmüştür.
- Bu kitap bir otofiksiyon eseridir.

## Lisans

Bu depodaki metin ve tasarım telif hakkı yazarına aittir. Kullanım koşulları için yazarla iletişime geçin.
