# Ham çalışma paketinin kapsamı

Bu paket önceki genişletilmiş deney paketinin yerine kullanılmak üzere hazırlandı.

## Korunan kaynak dosyalar

Üç notebook (grafik2.ipynb, veri.ipynb, veri2.ipynb), 3.bildiri_monte_carlo.pdf, Desteklemeli_Öğrenme_03.docx, mat_metot.docx ve süreç raporu. İçerikleri değiştirilmedi. Yalnızca klasör düzeni ve bazı dosya adları sadeleştirildi. SHA-256 eşitliğiyle doğrulandı.

## Bu pakete alınmayan eklemeler

Önceki pakette yeni oluşturulan src/estimators.py, src/experiment.py, test kodları, configs/experiment.json, scripts/plot_results.py, scripts/check_install.py, yeni results/ çıktıları, yeni dört grafik ve yeni deney mimarisi bu pakette bulunmaz. 1/5 adımlı yeni ortam, gamma=.95, yeni 100 tekrar × 50.000 bölüm deneyi ve bootstrap karşılaştırmaları eklenmedi.

## Düzenleme amacıyla eklenen dosyalar

README, GitHub yükleme rehberi, bu kapsam açıklaması, dosya kayıtları, requirements.txt ve .gitignore sonradan hazırlanmış yardımcı dosyalardır. assets/ içindeki PNG'ler kaynak notebook çıktılarının doğrudan kopyalarıdır; yeni sonuç değildir.

Eski dosyalardaki bilimsel tutarsızlıklar düzeltilmeden korundu ve README'de açıklandı. Bu arşiv düzenlemesi bir bilimsel doğrulama değildir. Kaynak metin ve grafiklerin aslına sadakat, bunların bilimsel iddialarını onaylamak anlamına gelmez.

Drive ana klasöründeki başka taslakların/literatür PDF'lerinin tümü pakete alınmadı. Ayrı dijital ikiz alt projesi dahil edilmedi.
