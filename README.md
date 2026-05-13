# Piano Deri V6

Yapılan değişiklikler:
- Yüklenen D.HTML dosyasındaki uyruk listesi eklendi.
- Admin otel eklemeye ACENTAKOD eklendi.
- ACENTAKOD merkez ana listede görünmez; rapor ve Excel dışa aktarımda görünür.
- Admin otel iptal/silme düzeltildi: otel satırını siler.
- Rezervasyona çıkış saati eklendi.
- Merkez ana ekranda ID sütunu kaldırıldı.
- Girdi satırı sarı, çıktı satırı yeşil, iptal satırı kırmızı.
- Sol menüye Raporlar eklendi.
- Sağ üstte Dışa Aktar eklendi.
- Dışa aktarım Excel 97-2003 .xls üretir, ilk sayfa adı sayfa1 olur.
- İzinli personel kayıt hatası düzeltildi.

Yeni Hotels başlığı:
ID | HOTEL_NAME | AGENT_CODE | USER_CODE | PASSWORD | STATUS | CREATED_AT

Yeni Reservations başlığı:
ID | DATE | TIME | EXIT_TIME | HOTEL | PAX_ADULT | PAX_CHILD | NATION | NOTES | STATUS | KART | AYAK | TEZGAHTAR_1 | TEZGAHTAR_2 | TEZGAHTAR_3 | TEZGAHTAR_4 | GIRDI | CIKTI | CREATED_AT | UPDATED_AT
