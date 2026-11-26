# SİYAMDER Kurumsal Tasarım Rehberi — Taslak v0.1

> Durum: **Taslak.** 10 Instagram paylaşımının (Ekim–Aralık 2025) analizinden çıkarıldı.
> Resmî kurumsal kimlik dosyası henüz incelenmedi. `[ONAY BEKLİYOR]` işaretli maddeler
> dernek tarafından doğrulanana kadar kesin kural sayılmaz.
> Her yeni tasarımdan önce bu dosya okunur; onaylanan kurallar buraya işlenir.

---

## 1. Kurum

- **Ad:** SİYAMDER — Sivil Yaşam Derneği
- **Yapı:** Genel merkez + yerel kurullar (görülenler: Ankara, Mersin, Sakarya; ayrıca Adıyaman hesabı)
- **Web / sosyal:** `www.siyamder.org.tr` · tüm platformlarda `/siyamder`
- **Odak alanları (paylaşımlardan):** gençlik, kişisel-mesleki gelişim, psikolojik sağlam­lık,
  sağlık/beslenme, kültür, çevre (fidan), kapsayıcılık/engelli hakları, çocuk hakları, Avrupa fırsatları

## 2. Logo

- Wordmark: **SİYAMDER**; "A" harfi yatay çizgisi olmayan, kâğıt uçak / ok ucu biçimli bir üçgen.
- Yerel kurul versiyonu: wordmark'ın altında **"ANKARA YEREL KURULU"** gibi alt satır
  (büyük harf, ince/orta ağırlık; Mersin örneğinde harf aralığı açık).
- Genel merkez paylaşımlarında (özel günler) alt satırsız tek wordmark.
- Renk: ana petrol-gri tonu (bkz. §3). Koyu zeminde beyaz versiyon (profil görseli).
- Yerleşim: üst-orta. Ortak kurum logosu varsa **sağında**, aynı yükseklik hattında;
  birden fazla paydaş varsa logolar tek satırda yan yana (Gençlik Kampı) veya alt şeritte (Yeşil Vatan).
- **Kural:** Logo yeniden çizilmez, rengi değiştirilmez, gerilmez, efekt eklenmez.
  `[ONAY BEKLİYOR]` Orijinal SVG/PNG dosyaları ve koruma alanı ölçüsü.

## 3. Renk Paleti

Değerler görsellerden örneklenmiş yaklaşık değerlerdir. `[ONAY BEKLİYOR]` resmî HEX kodları.

| Rol | Ad | HEX (yaklaşık) | Kullanım |
|---|---|---|---|
| Ana | SİYAMDER Petrol | `#6A909B` | Logo, isim etiketi (pill), ikonlar, başlık |
| Ana koyu | Derin Petrol | `#55707A` | Ana başlıklar, tarih/saat metni, footer |
| Vurgu | Hardal Sarı | `#EDB43A` | Alt başlık veya ana başlık vurgusu, tarih satırı, yıldızlar |
| Vurgu açık | Açık Sarı | `#F2C760` | Fırça darbesi şeritleri, büyük dolgu alanları |
| Zemin | Kırık Beyaz | `#F4F3EF` | Ana zemin (çoğunlukla dokulu) |
| Destek | Açık Petrol | `#B4C3C7` | İllüstrasyon gölgeleri, ikincil şekiller |

**Oran:** ~%70 kırık beyaz zemin · ~%20 petrol · ~%10 sarı. Sarı hiçbir zaman baskın zemin değildir
(istisna: genel merkezden gelen 3 Aralık gibi kampanya görselleri).
**Yasak:** Neon, saf siyah zemin, palet dışı doygun renkler (konu illüstrasyonu hariç).

## 4. Tipografi

`[ONAY BEKLİYOR]` Font adları doğrulanmadı; aşağıdakiler gözlemdir.

| Seviye | Gözlem | Örnek |
|---|---|---|
| Başlık | Geometrik/humanist sans, **kalın, BÜYÜK HARF** | KAYGI YÖNETİMİ, CALIFORNIA ROLL ATÖLYESİ |
| Alt başlık | Aynı aile, daha küçük; ya sarı ya da harf aralığı açık | SİYAMDER YOLCULUĞU, ZİHİNSEL DAYANIKLILIK |
| Bilgi satırı | Yuvarlak hatlı, kendine özgü kıvrık **"k"** harfli sans, orta-kalın | 6 Aralık Cumartesi \| 21.00 |
| El yazısı vurgu | İnce script, sarı veya yeşil | *Kutlu Olsun*, *Biz de Sahadayız* |
| Özel gün tarihi | Geniş harf aralıklı büyük harf | 2 0  K A S I M |

- Türkçe karakterler (İ, Ş, Ğ, Ç, Ö, Ü) her fontta eksiksiz olmalı — büyük harfte **İ** noktası korunur.
- Bir afişte en fazla 2 aile + 1 script.
- Not: Gençlik Kampı afişindeki sıkışık (condensed) başlık fontu genel dilden ayrışıyor; tekrar kullanılmamalı `[ONAY BEKLİYOR]`.

## 5. Format

- **Kare 1:1 — 1080×1080 px** (tüm feed paylaşımları).
- `[ONAY BEKLİYOR]` Story (1080×1920) ve 4:5 şablon kullanılıyor mu?
- Kenar güvenli alanı: ~%7 (≈ 75 px). Footer alt kenara ≈ 50 px.

## 6. Şablonlar

### A. Etkinlik / Söyleşi Afişi (ana şablon)

```
┌───────────────────────────────┐
│   [SİYAMDER logo] [paydaş]    │  1 · Logo + yerel kurul (+ ortak kurum)
│      ANKARA YEREL KURULU      │
│                               │
│     ETKİNLİK BAŞLIĞI          │  2 · Başlık (petrol) + alt başlık (sarı)
│     ALT BAŞLIK                │      — renkler ters de kullanılabilir
│                               │
│        ( yuvarlak foto )      │  3 · Merkez görsel: konuşmacı fotoğrafı
│        veya illüstrasyon      │      (daire çerçeve) ya da konu çizimi
│      ╭ Ad SOYAD ─────────╮    │  4 · Petrol pill etiket, beyaz metin
│      ╰ Unvan ────────────╯    │
│                               │
│   6 Aralık Cumartesi | 21.00  │  5 · Tarih | saat (1. satır)
│            ZOOM               │      Yer / platform (2. satır)
│                               │
│ www.siyamder.org.tr  ⓖⓕⓧ… /siyamder │  6 · Footer
└───────────────────────────────┘
```

- Hiyerarşi her zaman: **logo → başlık → görsel → konuşmacı → tarih/yer → footer.**
- Her şey ortalı, simetrik.
- Konuşmacı adı: `Ad SOYAD` (soyad büyük harf), unvan kısaltması önde (`Dyt.`), görev alt satırda.
- Tarih biçimi: `GG Ay Gün | SS.DD` — bkz. §9 tutarsızlık.
- Çok satırlı bilgi gerektiğinde etiketli liste: `Tarih: … / Saat: … / Yer: …` (etiket petrol, değer sarı).

### B. Özel Gün / Kutlama

- Genel merkez wordmark'ı (yerel kurul alt satırı yok).
- `20 KASIM` (aralıklı küçük başlık) → büyük başlık → sarı el yazısı vurgu (`Kutlu Olsun`).
- Alt yarıda geniş, çok kişili, kapsayıcı düz (flat) illüstrasyon.
- Footer genellikle yok.

### C. Kampanya / Paydaş Ortaklığı

- Paydaş logoları üstte satır veya altta beyaz şeritte; SİYAMDER logosu şeritte en sağda/sonda olabilir.
- Footer isteğe bağlı.

## 7. Görsel Dil

- **Zemin:** Kırık beyaz + doku (buruşuk kâğıt, kaba kâğıt, ince kıvrımlı çizgi desenleri, yumuşak dalga katmanları).
- **İllüstrasyon:** Düz (flat) veya çizgi (line-art) — palete uyarlanmış, yüzleri sade/çizgisiz figürler.
  İnsan figürlerinde çeşitlilik ve kapsayıcılık (tekerlekli sandalye, protez, farklı ten renkleri).
- **Konu objeleri:** Fotoğraf ise dekupe (arka planı temizlenmiş), gölgeli, havada/dinamik (sushi örneği).
- **Süs öğeleri (tekrarlayan):** ✦ dört köşeli yıldız/pırıltı (sarı + petrol), nokta matrisleri,
  organik blob şekiller, ince kıvrımlı çizgiler, **kâğıt uçak** (logodaki A'ya gönderme — marka motifi olarak korunmalı),
  ilerleme noktaları/yol çizgisi.
- Konuşmacı fotoğrafı: daire kırpım, beyaz/sade arka plan, gerekirse noktalı halka çerçeve.
- **Kaçınılacaklar:** Gradyan dolu "stok" görünüm, kalabalık kolaj, 3D/parlak efektler, gölgeli WordArt metin.

## 8. İletişim Dili

- **Ton:** Sıcak, davetkâr, umutlu, kapsayıcı; "biz" dili ("Biz de Sahadayız", "Gerçekleri Konuşuyoruz").
- **Başlık formülü:** `Etkinlik Adı: Çekici Alt Başlık` → "Beslenme: Trendin Ötesi", "Kaygı Yönetimi: Zihinsel Dayanıklılık".
- **Afiş metni:** Minimum — başlık, isim, tarih/yer. Açıklama afişte değil, gönderi metninde.
- **Gönderi metni (caption):** Başlık + 1–2 emoji (✨ 🌟 konuya uygun 🧠 🥗 🍣) → kısa davet paragrafı → tarih/yer.
  Ünlem ölçülü ("Ankara'da!✨", "Lezzetli Bir Deneyim!").
- **Değer cümleleri:** "Farkındalığı yüksek bir toplum için, sevgi her şeyi mümkün kılar." /
  "Sivil Yaşam Derneği olarak, kök salan her fidanla…" — kısa, duygulu, toplum odaklı.
- Anma paylaşımlarında: sade ve ağırbaşlı ("Saygı ve özlemle").
- Türkçe yazım kurallarına (TDK) tam uyum; kurum adı daima **SİYAMDER** (noktalı İ, tamamı büyük).

## 9. Tespit Edilen Tutarsızlıklar (karar bekliyor)

| Konu | Görülen varyantlar | Öneri |
|---|---|---|
| Saat ayracı | `21.00`, `20.00` / `19:00` | TDK'ya uygun **`21.00`** |
| Platform yazımı | `ZOOM` / `Zoom` / `Google Meet (Çevrimiçi)` | Bilgi satırında **`Zoom`**, `Google Meet` (gerekirse "Çevrimiçi") |
| Başlık fontu | Geometrik sans çoğunlukta; kamp afişinde condensed | Tek başlık ailesi |
| Footer | Etkinliklerde var, özel günlerde yok | Etkinlikte zorunlu, özel günde opsiyonel |
| Tarih rengi | Sarı veya petrol | Zemin açıksa petrol, büyük boşlukta sarı |

## 10. Tasarım Öncesi Kontrol Listesi

- [ ] Doğru logo (genel / doğru yerel kurul) üst-ortada, orijinal dosyadan
- [ ] Yalnızca paletteki renkler; sarı ≤ %10–15
- [ ] Başlık BÜYÜK HARF, Türkçe karakterler doğru
- [ ] Hiyerarşi: logo → başlık → görsel → kişi → tarih/yer → footer
- [ ] Tarih `GG Ay Gün | SS.DD`, yer/platform ikinci satırda
- [ ] Konuşmacı `Unvan Ad SOYAD` + görev
- [ ] Footer: `www.siyamder.org.tr` + sosyal ikonlar + `/siyamder`
- [ ] Paydaş logoları izinli ve doğru sürümde
- [ ] Etkinliğe özgü yaratıcı bir görsel fikir var (şablonun kopyası değil)
- [ ] Metin, derneğin sıcak ve kapsayıcı diline uygun

## 11. Onay Günlüğü

| Tarih | Karar | Onaylayan |
|---|---|---|
| — | — | — |
