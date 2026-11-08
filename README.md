# Düzada haritası — 3B parçalar

Kems Komuta Merkezi'nin (KKM) 3B harita denemesi için üretilmiş arazi parçaları.
Blender'da kodla üretildi (Kems Ajans, Kasım 2026). **Taslaktır**; Kemal onaylamadan kanon değildir.

- `parca/<ad>-uzak.glb`: kaba arazi ve kutu yapılar (uzak bakış, toplam ~9 MB)
- `parca/<ad>-yakin.glb`: ayrıntılı arazi, yapılar ve bitkiler (yakın bakış, toplam ~220 MB)
- `parca/deniz.glb`: deniz yüzeyi
- `parcalar.json`: parça listesi (`i`, `j`: 1 km'lik ızgara; `kara_m2`: parçadaki kara alanı)

Birimler metre. Parça `(i, j)` Blender düzleminde `x = i·1000 … (i+1)·1000`, `y = j·1000 … (j+1)·1000`
aralığını kaplar; glTF dışa aktarımı Y yukarı (x doğu, −z kuzey). Düzlemin sıfır noktası
boylam 25,7895 · enlem 39,6265. Dosyalar Draco ile sıkıştırılmıştır.

Bu depo yalnız dosya deposudur; görüntüleyici KKM'dedir.
