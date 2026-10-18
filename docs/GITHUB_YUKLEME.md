# GitHub'a yükleme

1. Bu yeni ZIP'i indir ve Tümünü ayıkla.
2. İçindeki monte-carlo-ham-calisma klasörünü aç.
3. GitHub'da bu Monte Carlo çalışmasına ait depoyu aç. Disleksi deposuna ekleme.
4. Boş depoda Quick setup → uploading an existing file; dolu depoda Add file → Upload files.
5. Klasörün içindeki dosya ve klasörleri Ctrl+A ile birlikte seçip sürükle. Dış klasörü veya ZIP'i yükleme. README.md depo kökünde olmalı.
6. Commit mesajı: Archive original Monte Carlo study and notebooks.
7. Commit changes düğmesine bas. README, PDF ve notebook bağlantılarını kontrol et.

## Önceki yeni-deney paketini yüklediysen

Sadece bu dosyaları üstüne yüklemek eski deneyleri silmez. Önce Code → Download ZIP ile yedek al. Bu çalışma için yeni boş bir depo oluşturup bu paketi yüklemek en kolay yoldur (ör. monte-carlo-original-study).

Aynı depoyu kullanacaksan önceki pakete ait src/, configs/, tests/, scripts/, results/, plots/ ve assets/architecture.svg ile eski docs/METHOD.md, docs/SOURCE_REVIEW.md, docs/FILE_HASHES.json, eski yükleme rehberi, paper/README.md ve RIGHTS.md dosyalarını kaldır. Yalnızca önceki paketle eklenen bu dosyaları kaldır; başka çalışmalarını silme. README.md, requirements.txt ve .gitignore dosyalarını bu yeni paketle değiştir. Eski paper/source_manuscript.pdf ve source_manuscript_2025_04.docx aynı kaynakların farklı adlı kopyalarıdır; yeni adlarıyla paper/ içinde bulunduğundan eski kopyaları da kaldırabilirsin.

Git geçmişinde önceki commitler kalır; güncel dosya görünümü yeni paketle eşleşir. Eski deneyleri hiç yüklemediysen bu temizleme adımına ihtiyacın yok.
