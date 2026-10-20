# Niş değerlendirmesi ve kanal çekirdeği önerisi (TASLAK, karar bekliyor)

Güven: **Y** yüksek, **O** orta, **D** düşük. Kaynak: **[G]** gözlem, **[S]** hesap, **[Ç]** çıkarım, **[H]** hipotez, **[K]** kullanıcı bildirimi.
Dayanak: `rapor-kanal-analizi.md`, `capraz-analiz.md` (özellikle 0b), `video-listesi-kodlu.md`, `kartlar/` (13 kart). Ham veri (`japa analizzz/`) **yeniden okunmadı** (kullanıcı kararı: kartlar yeterli).

## 0. Kanıt sınırı (karar bunun içinde verilir)
- Derin kartı olan video 13/55. Kalan 42 video yalnızca **başlık + sayı + benim konu kodlamam** düzeyinde biliniyor. Bunlardan çıkan her sonuç bir kademe düşük güvenle okunur.
- Tek rakip kanal inceleniyor. CTR, izlenme süresi, trafik kaynağı, abone dönüşümü yok. Talep kanıtı **yorum + izlenme** üzerinden dolaylı; arama hacmi verisi yok.
- Yorum yazanlar izleyicinin küçük, seçilmiş kısmı.

## 1. Rakip kanaldan alınacak değerler

| # | Değer | Kanıt | Güven | Bizde nasıl kullanılır |
|---|---|---|---|---|
| 1 | **Çerçeve: "iki taraf aynı yapıyı yaşıyor" + tek adlandırılmış kavram** (翻訳者, 階段, モヤモヤ) | 048 (yorum tonu en sıcak), 052, 017, 049 | O-Y [G] | Her videoda tek, adı olan bir kavram; kimse "aşağıda/yukarıda" değil |
| 2 | **Kendini yerleştirme + "yaşanmış an" CTA'sı** | 017 (1.968 beğenili "0段目"), 049, 052; derin, kişisel yorumlar | O-Y [G] | Sayı/etiket yerine yaşanmış an isteyen CTA; yorum alanı ürün |
| 3 | **Adı olmayan şeye ad vermek** | 049, 009, 052 (gözyaşı yorumları) | Y [G] | Her video bir "ad konmamış yaşantı"ya ad verir |
| 4 | **Güven katmanı:** kaynakça, "とされる" hedge'i, uyarı/yardım hattı, "tez + bedel" | 048, 049, 009, 014 | Y [G] | Asgari standart; üstüne çıkacağız (bkz. 2) |
| 5 | **Sahne ile giriş + açık vaat + marka cümlesi iskeleti** (11/11) | rapor 2.2 | Y [G]; performansı belirlediği **D** | İskelet alınır, **ifadeler özgün** olur |
| 6 | **Yorum → video döngüsü** (ASD talebi 009/014 → 030) | 009 (24 beğeni), 014 (7) | D-O [H] (sıra doğrulanmadı) | Resmî üretim girdisi |
| 7 | **Short = uzun videonun tek sahnesi + sabit yorum linki** | 015 (3,2M), 018 | O [G]; 015 aykırı değer | Açı testi aracı (kullanıcı onayladı) |
| 8 | **Taban talep hücreleri:** kişiler arası çekim/uyum (medyan 138K, n=6), IQ/düşünme (158K, n=7), bulmaca (186K, n=3) | video-listesi-kodlu | O [S], konu kodlaması benim | Talep haritasının zemini |

**Alınmayacaklar [Y-O]:** ilgisiz etiket şablonu; kapak-başlık-içerik tutarsızlığı; damgalayıcı/gerçek yüz kapak; tartışmalı iddiayı kesin sunmak; vaadin tersini söyleyen başlık (008); klinik "ben" odaklı konu ile başlamak.

## 2. Bizim eklememiz gereken katmanlar (rakipteki eksik)

| Eksik | Kanıt | Eklenecek |
|---|---|---|
| **"Anla" var, "ne yapmalı" yüzeysel** | 002 (yönetici: 18+28), 048 ("çevirmen nasıl, ayrıntılı?" 9), 017 (öfke 16/43/47), 052 (yeni çalışanla gerçek diyalog), 009 (yakını için rehber) | Her videoda **kullanılabilir cümle/kalıp** ("şunu deme → şunu de"), senaryolu örnek, indirilebilir şablon/checklist |
| **Özet/şablon ürünü yok** | 042 ("PDF özet" 3, "36 soru" 5) | Videoya bağlı tek sayfalık kart (ücretli/ücretsiz kararı sonra) |
| **Doğruluk ve güncellik** | 018 (Dunning-Kruger), 049 (verbal overshadowing), 015 (WM≈IQ), 002 ("50 yıl önce kasa") | **İddia başına kanıt derecesi** (güçlü/orta/zayıf) ve karşı bulgu. "Uzman yok" eleştirisine yüzle değil **şeffaflıkla** cevap |
| **"Kim konuşuyor, neden güvenmeliyim?"** | 042 ("AI üretimi", "kendin uygulamamışsın") | Yöntem + kaynak sayfası; (karar: Soru 2) |
| **Görsel kimlik tutarsızlığı** | [K] kapak ≠ animasyon; B6 | Kapak = animasyon dili, başlık vaadi = içerik |
| **AI ile düşünme/iletişim** | 049 (80 beğeni "AI'a yaptırınca kelime çıkmıyor"), 002 (106), 017, 052 | Kanalda yok; izleyici AI kullanıyor **[G, O]** |
| **Çıkıntılı profil (凸凹) sonrası strateji** | 002 (WAIS paylaşımları 63/64), 048 (212'nin altı) | Kısmen 029/031'de |
| **Moderasyon/cevap politikası** | 002, 018 (şiddet şakaları), 004 (kriz içerikli yorumlar, cevap yok) | Yorum politikası ve kriz kaynağı (karar: Soru 4) |

## 3. Niş adaylarının değerlendirmesi

Ölçütler (kullanıcı): **(1) gerçek talep, (2) tükenmeyen fikir kaynağı, (3) Japonca pazar, (4) hedef kanaldan fark.**

| Aday | Talep | Fikir kaynağı | Fark | Not |
|---|---|---|---|---|
| **A. İş yeri insan tipi** | **D-O.** Medyan 74K (n=7, genel medyanın altı); 039 (301K), 043 (120K), 047 (107K) güçlü; 001/023/012/007 zayıf (erken dönem karıştırıcı) | Orta; "tip" videoları tekrara düşer (etiketleme) | Düşük; rakip zaten yapıyor | **Tek başına niş değil; bir sahne** |
| **B. Bulmaca/düşünce deneyi** | O (3/3, 168K-203K) ama **kartı yok, yalnızca başlık**; izleyici profili ve abone etkisi bilinmiyor | Orta; format yorulabilir | Orta | **Yan format / kanca**; ana çatı için kanıt eksik |
| **C. Klinik/özellik** | Zayıf (medyan 38K, n=5); 030 (90K) ve 045 (82K) kendi dönemi civarı | Geniş ama damga/etik riski | Düşük | Ana eksen değil; **"karşı taraf için pratik rehber"** açısıyla yan hücre |
| **D. Kişiler arası anlama + uygulama** (iş, aile, çekim, kuşak, bilişsel tarz farkı) | **O.** Çekim/uyum grubu medyan 138K (n=6: 011 32K, 026 165K, 040 341K, 042 353K, 051 80K, 053 111K); yorumlarda "ne yapmalı" talebi 6+ videoda | **Yüksek** (aşağıda matris) | **Yüksek** (pratik katman + kanıt derecesi) | **Önerilen çekirdek** |

Ek ayrım **[S, D-O]:** Pratik "kişisel gelişim alışkanlığı" videoları zayıf (032 "継続の簡単な方法" 40K; 031 88K; 055 yeni, 2K), **kişiler arası pratik** videoları güçlü (026, 040, 042, 053). Yani "how-to" tek başına değil, **kişiler arası** olduğunda talep görüyor gibi. Zaman karıştırıcısı var.

**DÜZELTME (2026-10-20, kullanıcının rakip ekran görüntüsü):** 055 ("hata yapmayan insanların 5 alışkanlığı") veri çekiminde 0 günlük ve 2,2K idi; ekran görüntüsünde ~5 gün sonra ~153K. 054 (言語化 5 aşama) ~106K (7 gün), 053 ~132K (9 gün). Bu, yukarıdaki "kişisel how-to zayıf, kişiler arası how-to güçlü" ayrımını **desteklemiyor**; ayrımın güveni D'ye düşürüldü.

## 4. Öneri: kanal çekirdeği (karar bekliyor)

**Çalışma tanımı:** *"Farklı düşünen, farklı konuşan, farklı kuşaktan insanla nasıl anlaşılır"*, yani **対人翻訳 (kişiler arası çeviri)**: anlama (neden böyle görüyor) **+ uygulama** (ne söyleyeyim/yapayım) **+ kanıt derecesi** (bu ne kadar sağlam).

Neden bu:
1. **Talep zinciri kanıtlı [O]:** hitlerin ortak çekirdeği "başkasının/kendimin dünyası + kendimi yerleştirme" (048, 052, 017, 049); yorum talebi **"ne yapmalı"** (002, 015, 048, 052, 009); kişiler arası pratik videolar medyan 138K.
2. **Hedef kanalla çakışmayı azaltır:** rakip "anlama"da güçlü, "uygulama"da zayıf **[G, O]**. Hücre boş değil ama **katman** boş.
3. **Fikir kaynağı tükenmez (yapı gereği):** matris (aşağıda). Darboğaz fikir sayısı değil **talep süzgeci**.
4. **İş yeri bir sahne olur, niş olmaz:** (A)'nın zayıf kanıtına bağımlı kalmayız.
5. **Bulmaca = giriş kancası ve Short formatı** (B), kanıt gelene kadar ana çatı değil.

## 5. Fikir motoru

**Matris:** `Kimle (karşı taraf/çift)` × `Nerede (bağlam)` × `Ne yapılır (araç)`.
- **Kimle (örnek eksenler):** çalışma belleği düşük/yüksek kişi, görsel düşünür/sözel düşünür, çıkıntılı profil, ASD/ADHD eğilimli yakın, kuşaklar (昭和/ゆとり/Z/氷河期 + alt gruplar: 丙午, α, バブル, 団塊), yönetici-çalışan, ebeveyn-çocuk, yaşlı ebeveyn, partner, "özetleyen vs ayrıntıcı", içine kapanık-dışa dönük.
- **Nerede:** toplantı, LINE/mesaj, geri bildirim, talimat verme, çatışma, özür, ret, övgü, yeni çalışan, aile sofrası, yaşlı ebeveynle karar.
- **Araç:** cümle kalıbı, sıra, "ne zaman söylememeli", yazılı şablon, deney.

Yaklaşık 12 × 11 × 4 > 500 hücre. **Ama aynı gün yüklenen iki videonun farkı 11 kat (003 vs 004), yani hücrelerin talebi eşit değil.** Bu yüzden her aday üç süzgeçten geçer:
1. **Talep kanıtı:** hedef kanal yorumunda doğrudan istek (video no + beğeni) ya da listede benzer hit deseni.
2. **Boşluk:** hedef kanalda "uygulama katmanı" ile işlenmemiş mi?
3. **Kopya testi:** YouTube araması (15-30 sorgu), "aynı ihtiyaç + aynı açı" elemesi, risk = benzerlik × erişim × yenilik.

**Ham hücre örnekleri (HİPOTEZ, aday değil; her biri kanıtı ile):**
| Hücre | Talep dayanağı | Hedef kanalda |
|---|---|---|
| Üçlü talimat veren patrona yönelik: talimatı nasıl verirsin | 015 (patron yorumları 5.747/2.358/965) | Short var, rehber yok |
| Yeni çalışana geri bildirim zamanlaması ve gerekçe ekleme | 052 (132 beğeni "40'lar yeni çalışan") | Tek bölüm |
| "Söyleyemiyorum"u birine nasıl anlatırım (kelimesi olmayan kişiyi dinleme) | 049 (kelime/çocuğa anlatma 4, "相手の隙間" 11) | Yok |
| Görsel düşünürle konuşma | 048 (3), 049 (0+4) | Yok |
| AI'a yaptırınca kelime/düşünme körelmesi | 049 (80), 052 (7), 002 (106) | Yok |
| Çıkıntılı profilli çalışan/partnerle iş bölümü | 002 (63/64/44/35), 048 (212'nin altı) | Kısmen |
| Öfkeyle kademe düşüşünde ne söylenir/söylenmez | 017 (16, 43/47) | Kısmen |
| Kuşak alt grupları (丙午, α, バブル) | 052 (6, 3, 3) | Yok |

## 6. Çürütme: bu öneri nerede yanlış çıkabilir?
| Risk | Ne bilmiyoruz | Nasıl sınarız |
|---|---|---|
| Hitler "pratik katman"dan değil çerçeve/IQ meraktan geliyor olabilir | 048 beğeni oranı %0,64: büyük erişim çekirdek dışından olabilir | Short/video çiftleriyle açı testi; yorumda "uygula" isteği oranı |
| "How-to" kişiler arasında bile geniş talep olmayabilir | 026/040/042/053 kartsız (042 hariç); 042 yorum oranı %0,029 | O 4 videonun yalnızca başlık düzeyinden öte okunması gerekir **(kullanıcı: yapılmayacak; bu durumda güven D-O kalır)** |
| Katman ayrımı izleyiciye görünmez | CTR yok | Başlıkta uygulama vaadi + kopya testi |
| Rakip bizi kopyalar | — | Kanıt derecesi ve şablon bizim imza |
| Yorum yazanlar ≠ izleyici | Y profil yok | Karar verirken yorumu tek belirleyici yapma |

## 7. Karar bekleyenler
1. **Soru 1 (niş yönü):** D çekirdeği (A sahne, B kanca, C yan hücre) mi, farklı bir birleşim mi?
2. Soru 2: yüzsüz AI ses + "kim konuşuyor" yanıtı (yöntem/kaynak sayfası, kanıt derecesi sistemi bunun bir parçası olur).
3. Soru 3: Short sıklığı ve yapı.
4. Soru 4: yorum cevaplama.
