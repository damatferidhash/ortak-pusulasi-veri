# Ortak Pusulası · veri deposu

Selçuk Üniversitesi Araştırma Dekanlığı'nın **Ortak Pusulası** platformunun her hafta otomatik güncellenen verileri.

| Dosya | İçerik |
|---|---|
| `ortak-dizini.json` | Avrupa Komisyonu Funding & Tenders Portal'daki, şu an açık veya yakında açılacak çağrılara verilmiş ortak arama ilanları (herkese açık kaynak: EU Search API). |
| `etkinlikler.json` | Ufuk Avrupa, Erasmus+, COST ve MSCA için eşleştirme (brokerage) etkinlikleri, bilgi günleri ve son başvuru tarihleri. |

Dosyalar her pazartesi yenilenir; her güncelleme ayrı bir commit olarak eklenir. Platform sayfası bu dosyaları doğrudan buradan okur:

```
https://raw.githubusercontent.com/damatferidhash/ortak-pusulasi-veri/main/ortak-dizini.json
https://raw.githubusercontent.com/damatferidhash/ortak-pusulasi-veri/main/etkinlikler.json
```

Ortak arama ilanları AB tarafından denetlenmez; iletişime geçmeden önce kurumu doğrulayın. Kişisel veri içermez.
