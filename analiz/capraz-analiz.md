# Aşama 2 — Çapraz Analiz (hedef kanal: 深淵回廊, 13 video)

Etiketler: **[G]** gözlem (kartlardan/dosyalardan), **[S]** hesaplanmış sayı, **[Ç]** çıkarım, **[H]** hipotez, **[K]** kullanıcı bildirimi (doğrulanmadı).
Kaynak: `analiz/kartlar/*.md` (13 kart) ve `japa analizzz/*/` ham verisi.

## 0. Veri ve sınırlar (önce bunu oku)
- **Örneklem 13/55 video ve yanlı seçilmiş:** 8 "üst grup" + 5 "zayıf grup". Ortadaki videolar (özellikle 10 Ağu - 19 Eyl arası) örneklemde **yok**. Bu yüzden "tipik video" değil, **uç örnekleri** kıyaslıyoruz.
- **Zaman karıştırıcısı:** Beş zayıf video (004, 008, 009, 010, 014) 24 Tem - 5 Ağu arası, yani kanalın ilk 3 haftasında. Dört geç üst video (042, 048, 049, 052) 20 Eyl - 9 Eki arası. Konu etkisi ile **kanal büyüme etkisi** tam ayrıştırılamaz.
- **Olgunluk:** 052 (5 gün), 048 (13), 049 (11), 042 (24) olgunlaşmadı; günlük ortalamalar yüksek.
- **Eksik veriler:** CTR, izlenme süresi, trafik kaynağı, abone dönüşümü yok. "Neden tuttu" cevapları dolaylı kalır.
- **Yorum verisi:** Videonun yorumlarının tamamı değil, seçilmiş 36-100 ana yorum.
- **Kullanıcı bildirimleri [K]:** Konuşmacı sesi **kaliteli, bu kanala özgü AI ses** (başka kanalla ortak ya da kopya değil); arka planda **hafif gerilim/gizem müziği**; kapaklar düzensiz görünüyor; kapak stili animasyonla uyuşmuyor; animasyon: lacivert gece sahneleri, düz vektör, parlak hale, üst solda bölüm başlığı, altta büyük kalın altyazı (ekran görüntüsü, **örneklemde olmayan** bir videodan; bkz. kart 042 düzeltmesi). Şiddet içeren/ayrımcı yorumlar (002, 018) bizim için olumsuz değil, **dikkatsiz izleyici sinyali** olarak okunacak.

## 0b. GÜNCELLEME — 55 videonun tam listesi geldi (bu bölüm aşağıdaki bulguları geçersiz kılar/düzeltir)
Kaynak: `japa analizzz/video_listesi.md` (ham), `analiz/video-listesi-kodlu.md` (benim konu kodlamam). Artık "ortadaki videolar yok" sınırı kalktı; **kalan sınırlar:** CTR/izlenme süresi yok, konu kodlaması benim yargım, olgunlaşmamış son videolar (050-055).

**U1. Tabanın zamanla yükselmesi artık veriyle kanıtlı [S].** Uzun video medyanı (n=49, genel 89.868): **16 Tem - 10 Ağu: 37.7K (n=15)** → **11 Ağu - 1 Eyl: 89.9K (n=11)** → **2 Eyl - 14 Eki: 123.7K (n=23)**. Aylık: Tem 46,7K / Ağu 78,0K / Eyl 154,6K / Eki 117,4K (Eki olgunlaşmadı). **Dönemler arası konu kıyası yanıltıcı; yalnızca aynı dönem içi kıyas yapılmalı.** (Eski B8 "zayıf" idi, artık **güçlü**.)

**U2. Aynı dönem kıyası: IQ konusu sınırı net ayırıyor, ama Short karıştırıcısı duruyor [S].** 16 Tem - 10 Ağu arasındaki 15 uzun videoda:
| Grup | Videolar | İzlenme |
|---|---|---|
| IQ / zekâ (4) | 002, 003, 005, 017 | 441K, 158K, 83K, 1,02M (medyan ~300K) |
| Diğer (11) | 001, 004, 006, 007, 008, 009, 010, 011, 012, 014, 016 | 10,8K - 74K (medyan 30,6K) |
Gruplar **tam ayrışıyor**: IQ grubunun en düşüğü (005: 82,8K) diğerlerinin en yükseğinden (007: 74K) büyük. **Aynı gün yüklenen 003 (IQ, 158K) ile 004 (nostalji, 14K): 11 kat.** Bu, B1'i **güçlendiriyor**. **Hâlâ geçerli uyarı:** 002/003 sonradan 015'in sabit yorumu ve 048'in açıklamasındaki "関連動画" bağlantılarıyla beslenmiş olabilir (048 açıklaması 002 ve **003**'e link veriyor). Yani erken tahminin ilk günlerdeki hızı bilinmiyor.

**U3. IQ tek başına değil; konu haritası genişledi [S].** Uzun videoların konu medyanları (benim kodlamam; `video-listesi-kodlu.md`):
| Konu grubu | n | Medyan | Aralık |
|---|---|---|---|
| **Problem / düşünce deneyi** (025, 028, 033) | 3 | **185,7K** | 168K - 203K (**3/3 medyanın ~2x'i**) |
| **IQ / zekâ / düşünce gücü** | 7 | 158,4K | 82,8K - 2,64M |
| **Kişiler arası çekim / uyum / sohbet** (011, 026, 040, 042, 051, 053) | 6 | 137,9K | 31,9K - 352,6K |
| Aile / ACE / "yaşamak zor" (006, 020, 024, 035) | 4 | 98,4K | 62,7K - 195,5K |
| Diğer (kognisyon, trivia, kuşak, dil, zaman, ...) | 14 | 86,7K | 2,2K (yeni) - 534K |
| İş yerinde insan tipi / istifa (001, 007, 012, 023, 039, 043, 047) | 7 | 74,0K | 22,6K - 301K |
| **Klinik / özellik** (009, 014, 016, 030, 045) | 5 | **37,7K** | 15K - 90K |
| 004 / 008 / 010 (nostalji, kan grubu, film) | 3 | **14,2K** | 10,8K - 26,8K |
Yani **zayıf uç: klinik/özellik ve duygu-nostalji-etiket-film**; **güçlü uç: bulmaca/düşünce deneyi, IQ/zekâ, kişiler arası çekim-uyum**. Eylül'den sonraki 🔥 videoların çoğu IQ dışı: 034 (心理トリック 245K), 035 (30 dk "人生が辛い" 195K), 036 (スマホで脳退化 354K), 039 (会社員8類型 301K), 040 (相性5つのサイン 341K), 042 (魅力 353K).
- **Klinik "見えている世界" videoları** 030 (ASD) = 89,9K (kendi döneminde ortalama), 045 (HSP) = 81,8K (Eylül medyanının ~0,5x'i). Eski B2 doğrulandı ama "çok zayıf" yerine **"kendi dönem medyanının altında/yanında"**.
- **Bulmaca/düşünce deneyi** formatı (025: "実際に出題された入社試験", 028: "この答えが分かりますか", 033: "この答えがわかったら超天才です") **örneklemde yoktu ve 3/3 sağlam** → yeni bir kalıp aday: **zekâ meydan okuma + net cevap**.
- **Sınıflama/sayı başlıkları** (039 "8類型", 040 "5つのサイン", 042 "5つの秘密", 043 "7類型", 047 "7つのサイン"): 5 videonun 4'ü 107K - 353K. Sayı içeren başlıkların uzun video medyanı **113K** (n=10), olmayanlar 83K (n=39). Zaman karıştırıcısı var.

**U4. Short'lar [S].** Toplam 6 Short (4 - 13 Ağu), **medyan 68K**; yalnızca **015 (3,2M) ve 018 (516K)** patladı. **IQ'lu Short'lardan 019 (58K) ve 021 (78K) ortalama**, 013 (36K), 022 (53K) de öyle. **Short sıçraması konuyla açıklanmıyor; 015 bir aykırı değer.** **13 Ağu'dan sonra hiç Short yüklenmemiş** (22 gün). Short → uzun bağlantısı: **015 sabit yorumu → 002**, **018 sabit yorumu → 007** (**007: "仕事できないのにプライド高い人の正体", 74K**, bunu önceki karttaki "hedef video bu örneklemde yok" notu yerine koyuyorum).
- **DÜZELTME (B4):** 018'in Dunning-Kruger cümleleri 002'dekiyle aynı, **ama** 018'in sabit yorumu 007'ye bağlıyor ve 018'in başlığı 007'nin konusu. 007'nin transkriptine sahip değiliz; **018'in kaynağı 002 değil 007 olabilir** (iki videoda da aynı bilgi bulunması muhtemel). "018 = 002'nin kesiti" kesin değil, **"002 ya da 007'nin kesiti"**. 015 → 002 eşleşmesi sağlam (metin birebir + sabit yorum).

**U5. Memnuniyet ↔ erişim ilişkisi 54 videoda da var, ama daha zayıf [S].** İzlenme ↔ beğeni oranı: tüm videolar (n=54, >10K) **ρ = -0,52**, yalnızca uzun (n=48) **ρ = -0,54**; izlenme ↔ yorum oranı **-0,35** (tüm) / **-0,46** (uzun). Eski n=13 sonucu (-0,61 / -0,70) **fazla güçlüydü**; gerçek değer daha ılımlı. Yön tutarlı.

**U6. Süre [S].** Uzun videolarda süre ↔ izlenme ρ = +0,33 (zayıf). 29-33 dk'lık 035 (195K), 046 (155K) iyi; 045 (29 dk, 82K) orta. Süre belirleyici değil.

**U7. Başlık özellikleri [S]; hepsi zaman karıştırıcılı.** 【…】 etiketi taşıyan uzun videolar (n=33) medyan **119,9K**, taşımayanlar (n=16) **63,6K**; ama etiketli videolar çoğunlukla Eylül sonrası. Başlıkta açıkça "見えてる/視えてる世界" olanlar (002, 030, 045, 052; n=4) medyan 265K ama dağılım 82K - 534K. "?" soru işareti fark yaratmıyor (89,9K / 97,7K). "あなた" 105K / 89K. Hiçbiri kendi başına güvenilir değil.

**U8. Dikkat: art arda gelen videoların karşılaştırması olgunluk yüzünden yanıltıcı.** 050-055 henüz 0-9 günlük. **054'ün 68K'sı ve 051'in 80K'sı** 049/042 ile doğrudan kıyaslanamaz.

**U9. Ekran görüntülerinin kaynağı doğrulandı.** Kullanıcının animasyon kareleri **051 "【進化心理学】男女が感じる"魅力"の違い、考えてみた。" (16:30)** videosundan (süre 16:29 uyuşuyor). Bu video örneklem dışı, 80K.

## 1. Sayısal tablo [S]
Beğeni/yorum oranı = beğeni (ya da yorum) / izlenme. Veri çekimi 2026-10-14.

| Video | Tarih | Tür | Süre | İzlenme | Beğeni % | Yorum % | Gün | İzlenme/gün | Outlier |
|---|---|---|---|---|---|---|---|---|---|
| 002 | 21 Tem | Uzun | 18:32 | 441.124 | 2,58 | 0,306 | 85 | 5.190 | 4,9x |
| 004 | 24 Tem | Uzun | 12:20 | 14.169 | 3,03 | 0,353 | 82 | 173 | 0,2x |
| 008 | 28 Tem | Uzun | 12:44 | 26.750 | 2,00 | 0,344 | 78 | 343 | 0,3x |
| 009 | 29 Tem | Uzun | 14:23 | 19.569 | 3,54 | 0,353 | 77 | 254 | 0,2x |
| 010 | 31 Tem | Uzun | 11:41 | 10.790 | 1,99 | 0,593 | 75 | 144 | 0,1x |
| 014 | 5 Ağu | Uzun | 17:15 | 15.183 | 3,28 | 0,323 | 70 | 217 | 0,2x |
| 015 | 6 Ağu | Short | 0:44 | 3.214.126 | 1,02 | 0,119 | 69 | 46.582 | 47,2x |
| 017 | 8 Ağu | Uzun | 14:29 | 1.019.163 | 2,77 | 0,165 | 67 | 15.211 | 11,3x |
| 018 | 9 Ağu | Short | 0:58 | 515.619 | 1,10 | 0,108 | 66 | 7.812 | 7,6x |
| 042 | 20 Eyl | Uzun | 18:09 | 352.561 | 0,90 | 0,029 | 24 | 14.690 | 3,9x |
| 048 | 1 Eki | Uzun | 15:09 | 2.639.145 | 0,64 | 0,098 | 13 | 203.011 | 29,4x |
| 049 | 3 Eki | Uzun | 13:11 | 452.458 | 1,05 | 0,051 | 11 | 41.133 | 5,0x |
| 052 | 9 Eki | Uzun | 19:25 | 533.779 | 0,82 | 0,127 | 5 | 106.756 | 5,9x |

## 2. Kodlanmış özellikler (13 kartın özeti) [G]
| Video | Konu grubu | Başlık kalıbı | Kapak ailesi | Açık döngü | CTA türü |
|---|---|---|---|---|---|
| 002 | IQ / iş yeri | uzun şok: 【理解不能】…異常すぎる | korku-sinematik (yüz+beyin) | tek vaat "両方の正体" | "これ苦手かも" itirafı |
| 004 | nostalji / duygu | duygusal hitap "〜あなたへ" | sıcak anı | yok | "戻りたいあの頃" |
| 008 | kimlik etiketi (kan grubu) | "〇〇に△△が多い科学的理由を知っていますか" | korku-sinematik | yok (sonuç önce) | "etiket ve gerçek ben" |
| 009 | klinik (ADHD) | SEO "なぜ…徹底解説" | korku-sinematik (aynı yüz) | yok | "betimleme ne kadar yakın" |
| 010 | film zevki | 【閲覧注意】…◯◯です | korku-sinematik | yok (4 cevap) | film önerisi |
| 014 | klinik (şizofreni) | 「alıntı」+ について知っていますか | korku-sinematik (folyo şapka) | var ("2 yanlış anlama") | yok (videoda) |
| 015 | IQ / iş yeri (Short) | 〇〇に視えてる世界 | gerçek yüz + neon | — | sabit yorumla 002'ye link |
| 017 | düşünce kademeleri | 【思考心理学】…何を考えているのか | kademe-beyin | var | "kaçıncı kademe, öfkede kaça düşersin" |
| 018 | iş yeri etiketi (Short) | あなたの職場にも〜がいませんか | gerçek fotoğraf | — | sabit yorumla uzun videoya link |
| 042 | çekicilik | 【社会心理学】5つの秘密 | manga bölünmüş | yok (sonuç önce) | "hangi bileşen" |
| 048 | IQ kademeleri | 【IQ70とIQ160】…見える世界 | kademe-beyin | var | "sayı yazma, manzara farkı yaz" |
| 049 | dil / duygu adlandırma | 【心理言語学】…脳内の仕組み | manga bölünmüş | var | "sonradan ad konan an" |
| 052 | kuşak | 【社会心理学】世代ごとに視えてる世界 | boyama portre | var (2 tane) | "çeviri anı" |

## 3. Ana bulgular

### B1. Konu, paketlemeden daha belirleyici görünüyor (en güçlü bulgu) [G, Ç]
**Erken pencere kıyası (21 Tem - 9 Ağu, 9 video):** Aynı ses, aynı marka cümlesi, aynı kaynakça disiplini, **aynı kapak ailesi**.
| Grup | Videolar | İzlenme |
|---|---|---|
| IQ / zekâ / iş yeri | 002, 015, 017, 018 | 441K - 3,2M |
| Diğer konular | 004, 008, 009, 010, 014 | 10,8K - 26,8K |

En düşük "IQ/iş yeri" videosu (441K), en yüksek "diğer" videonun (26,8K) **16 katı**. Kapak ailesi bunu açıklamıyor: 009 ve 014, 002/015 ile **aynı yüzü ve estetiği** kullanıyor.
- **Karşı kanıt / uyarı:** 015 ve 018, 002'nin **kesitleri** (kart 002). Bu üçü bağımsız değil; 017'yi de 015'in viral olmasından 2 gün sonra yüklendiği için bağımsız saymıyorum. Yani gerçekten bağımsız yalnızca **002** (21 Tem) ve **015**. 002'nin kendisinin günlük ortalaması 5.190, yani yavaş birikmiş; kesitlerden gelen trafikle şişmiş olabilir.
- **Sonuç:** "Talep önce gelir" ilkesi destekleniyor ama **kanıt orta güçte**: n küçük, Short sıçraması ve zaman karıştırıcı var.

### B2. Klinik/damgalı konularda "視えてる世界" kalıbı tek başına yetmiyor [G]
Kalıp (kapakta/başlıkta) 009 (ADHD) ve 014 (şizofreni)'de var, ikisi de ~15-20K. Devam notundaki ek veriye göre ASD (030) ~90K, HSP (045) ~82K; Eylül aylık uzun video medyanı 155K. Yani klinik konular geç dönemde de medyanın altında. **Kalıp IQ ve kuşakta patlıyor** (048: 2,6M, 052: 534K). Orta güven.

### B3. Memnuniyet ile erişim ters orantılı [S]
Spearman (13 video): izlenme ↔ beğeni oranı **ρ = -0,61**, izlenme ↔ yorum oranı **ρ = -0,70**. Yalnızca uzun videolar (n=11): **-0,55 / -0,77**. Yalnızca erken pencere (n=9): **-0,45**.
- En düşük beğeni oranları en yüksek erişimde: 048 %0,64, 052 %0,82, 042 %0,90. En yüksekler en düşük erişimde: 009 %3,54, 014 %3,28, 004 %3,03.
- **Olası açıklamalar [H]:** (a) yüksek erişimde izleyicinin çoğu çekirdek kitle dışından geliyor (öneri akışı); (b) küçük videoları sadece çekirdek kitle izliyor ve hepsi memnun; (c) olgunlaşma farkı (048 ve 052 çok yeni; ama 042 24 gün, 049 11 günlük ve onlarda da oranlar düşük).
- **Zayıflık:** n küçük, ρ güven aralığı geniş. Yön, üç ayrı alt örnekte aynı.

### B4. Short = uzun videonun kesiti; Short uzun videoyu büyütmüş olabilir [G]
015'in metni 002'nin içinde var (kart 002); 018'in DK cümleleri de 002'dekiyle aynı ama sabit yorum 007'ye bağlıyor (bkz. U4). 015 (3,2M) 002'den 7 kat, 018 (516K) 1,2 kat fazla izlendi. İkisinin sabit yorumunda uzun videoya link var. **Açı değişimi:** 002'deki Dunning-Kruger "rahatlatıcı" (endişeleniyorsan metabilişin çalışıyor), 018'de "suçlayıcı" (プライド高い無能). Aynı öncül, farklı açı, farklı sonuç: **Short'larda dışlama/suçlama açıları** daha çok yorum ve hakaret çekmiş (015: patron suçlaması; 018: şiddet şakaları), **uzun videolarda "iki taraf aynı yapı"** çerçevesi daha sıcak yorumlar çekmiş.

### B5. Aynı iskelet 11 uzun videonun hepsinde var [G]
- **Açılış marka cümlesi** "今夜も深淵を覗いていこう" 11/11 videoda, **0:46 - 1:35** arasında; **kapanış** "また次の深淵でお会いしましょう" 11/11.
- Kapanışta "高評価とチャンネル登録で支えてもらえると嬉しい" ve **CTA**.
- Ortak parça sırası: açık sahne/soru → vaat → (çoğunda) açık döngü → 3-5 bölüm → "bedel/tersine çevirme" → pratik 3 adım → CTA.
- **Açık döngü olanlar:** 014, 017, 048, 049, 052 (5/11); **sonuç önce verenler:** 008, 042 (2/11). Performansta net fark yok (açık döngülüler 15K ile 2,6M arasında dağılıyor). **Açık döngü tek başına belirleyici değil.**
- **Kaynakça:** 002'den itibaren her videoda (004 hariç). "とされる / 追試は限られる" hedge'leri düzenli.
- **Hashtag/etiket şablonu:** 002 (farklı set), 004 ("uyku/çalışma BGM" etiketleri ilk burada), 008'den itibaren **"ダーク心理学 / #偉そうな人 / #ADHD / #ASD / #HSP"** kopya seti ve 004'ten gelen `#睡眠用bgm #作業用bgm` etiketleri 042, 049, 052'de yeniden. İçerikle ilgisi çoğu videoda yok. **Başarıyı açıklamıyor, kanalın bir eksikliği.**

### B6. Kapak: 4 aile, tutarlı kural yok [G]
1. **Korku/sinematik** (002, 008, 009, 010, 014, 015): karanlık, neon yeşil/kırmızı, gerçekçi yüz. Erken dönemin tamamı; hem kazananlar (002, 015) hem kaybedenler (009, 010, 014) bu ailede.
2. **Kademe-beyin** (017, 048): beyaz-mavi arka plan, devasa kırmızı yazı, 4-7 portre, `平均` oku. **Şablon yeniden kullanılmış** ve iki videonun da performansı yüksek (1,0M, 2,6M).
3. **Manga bölünmüş** (042, 049): önce/sonra karşılaştırma; ikisi de 350-450K.
4. **Boyama portre** (052): üç kuşak yüzü.
Ek: 018 gerçek fotoğraf (risk: kimlik/siyaset), 004 sıcak anı (tek örnek). **Kapak ailesi performansı tek başına açıklamıyor** (B1). Animasyon ile kapak dili **hiçbir zaman uyuşmuyor** [K + G].
**Kapak-başlık-içerik tutarsızlıkları:** 052 (kapak 氷河期, video 昭和), 009 (üç farklı vaat), 004 (başlık/kapak cümlesi farklı), 008 (başlık "bilimsel neden", video "yok"), 002 (sert paket, nazik içerik).

### B7. Başlık: erken şok → geç etiketli analiz [G]
Erken başlıklar (002, 004, 008, 009, 010, 014) çeşitli: şok, duygusal hitap, SEO, merak boşluğu. **Geç dönemin 5 uzun üst videosunun hepsinde başlıkta 【disiplin/kalıp】 etiketi var:** 【思考心理学】(017), 【社会心理学】(042, 052), 【IQ70とIQ160】(048), 【心理言語学】(049). 002 de 【理解不能】, 010 【閲覧注意】 taşıyor (etiket tek başına işe yaramıyor). **Zaman karıştırıcısı güçlü:** etiket 017'de (8 Ağu) başlıyor ve sonrası hepsi etiketli.

### B8. Geç dönem tabanı yükseldi [G, S]
6 Ağu'dan sonraki dört örneklem videosunun hepsi **≥ 353K** (042, 048, 049, 052), konu fark etmeksizin (çekicilik, dil, IQ, kuşak). Erken beş "diğer" video ≤ 27K. Devam notuna göre Eylül uzun video medyanı 155K. **Kanal tabanı** (abone/öneri güveni) Short sıçramasından sonra bir kademe yükselmiş olabilir. **Seçilim yanlılığı uyarısı:** bu dört video "üst grup" olarak seçildi.

### B9. CTA türü yorum kalitesini belirliyor, hacmini değil [G]
- **Yaşanmış an CTA'ları** (049: "ad konan an"; 052: "çeviri anı"; 017: "kademe + öfkede düşüş"; 048: "manzara farkı"): uzun, kişisel, destekleyici yorumlar.
- **Liste CTA'sı** (010: film önerisi): en yüksek yorum oranı (%0,59) ama talep sinyali yok.
- **CTA yok** (014 videoda): düşük yorum, yorumlar yine de kişisel.
- **Yorum oranı en düşük** videolar (042 %0,029, 049 %0,051, 048 %0,098) ters orantı bulgusuyla (B3) uyumlu.

### B10. Seslendirme: izleyici ağırlıklı olarak olumlu [G, K]
Kullanıcıya göre ses **kaliteli, bu kanala özgü AI ses**. Kartlardaki ses yorumlarının beğeni-ağırlıklı kaba sayımı (yalnızca videolarda geçen kayıtlar, tam sayım değil):
- **Olumlu ~110 beğeni:** 052 ("声に癒やされる" 34 + 3), 014 (32 + 4), 042 (13 + 5), 010 ("読み間違いが可愛らしい" 11), 008 (7), 002 (2), 004 (1).
- **Olumsuz ~20 beğeni:** 052 ("ボカロか何か…キモい" 7), 017 ("ボイスロイド…" 1, "声がガビガビ" 4), 048 (3), 015 (2), 010 (2), 042 (1).
- **Tekrar eden küçük eleştiriler:** kanji okuma hataları (010, 042: "まわす/かわす"), altyazıdaki fazla "、" (042, 048), ani efekt/müzik seviyesi (049), tempo değişimi (049). **Okuma hataları erken dönemde daha çoktu; hâlâ var.** İzleyicilerin bir kısmı AI olduğunu fark ediyor, bir kısmı etmiyor, birkaçı bunu olumlu ("量産が可能なのは嬉しい" 004). **AI ses kanalın büyümesine engel olmamış.**

### B11. İzleyici profili hipotezi (yalnızca yorumlardan) [G, H]
- **Çalışan yetişkin, çoğu 30-55 yaş** (052'de 26 yorum kendini 氷河期 olarak tanımlıyor; 002'de "字が小さくて老眼"; 017'de "toplantı/ebeveyn" dili; 049'da "老親を亡くした"). Gençler (Z) yorum alanında nadir.
- **Kendini ve başkasını anlamaya çalışan, "aşırı düşünen":** 017 ("考えすぎ"), 049 ("INTP多そう"), 048 (MENSA/giftedness), 002 (WAIS profili paylaşımı).
- **Yönetici/ebeveyn/aile bakıcısı rolleri** sık: 002, 009, 014, 015, 052.
- **AI araçlarını düşünme/duygu için kullanan:** ChatGPT/Claude/Copilot'a atıflar 002, 004, 015, 017, 042, 049'da.
- **Şüpheci, kaynak arayan alt grup:** 018, 042, 049'da "kaynak/yenilik" eleştirisi (küçük ama tutarlı).
- **Sınır:** Yorum yazanlar izleyicilerin küçük, seçilmiş bir alt kümesi.

### B12. Karşılanmamış ihtiyaçlar (tekrar edenler) [G]
1. **Farklı bilişsel/iletişim tarzına sahip kişilerle nasıl çalışılır/yaşanır** (yönetici, ebeveyn, aile, iş arkadaşı): 002, 009, 014, 015, 017, 052.
2. **Kendi profilini tanıma ve stratejiye çevirme** (WAIS, güçlü/zayıf yanlar, dışsallaştırma): 002, 009, 048.
3. **Duygu/öfke adlandırma ve düzenleme** (モヤモヤ, öfkede 1. kademeye düşme): 017, 049, 004.
4. **Seri talepleri:** ASD (009: 24, 014: 7), EQ (048: 6 + 1), görsel düşünür (048, 049), 離人症 (014), α/丙午 kuşakları (052), 一目惚れ/恋人依存 (042), MBTI/kişilik etiketi (008), "8. kademe" (017), "運がいい人" (049).
5. **Pratik ürünler:** özet PDF (042: 3), 36 soru listesi (042: 5), yazılı talimat şablonları (015).
6. **AI ve düşünme/çalışma:** "AI zihin desteği mi, bağımlılık mı" (017, 049, 002).
7. **Kaynak ve tazelik:** güncel araştırmaları isteyen alt grup (049: verbal overshadowing eleştirisi; 018: Dunning-Kruger eleştirisi).

### B13. Kanalın zayıf yanları (hedef kanalda iyileştirme alanı) [G]
- İçerikle ilgisiz hashtag/etiket şablonu (özellikle uyku/çalışma BGM etiketleri); 010'da bozuk bölüm zaman damgası.
- Kapak ↔ başlık ↔ içerik tutarsızlıkları; kapakların mevcut videoların animasyon diliyle uyuşmaması [K].
- Uzman/yüz yok: "AI üretimi" ve "kendin uygulamamışsın" eleştirisi (042).
- Damgalayıcı kapaklar (018 gerçek yüz/etiket, 014 folyo şapka).
- Kısa videoda (018) yalnızca etiketleme; "ben miyim?" / "ne yapmalı?" cevapsız.
- Bazı bilimsel iddialar tartışmalı ve güncel değil (018 バカの山, 049 verbal overshadowing, 015 çalışma belleği ≈ IQ).
- Kanal sahibinin yorum cevabı yok (erken dönemde vardı, 010/004'te).
- Müzik/efekt seviyesi ve kanji okuma hataları.

### B14. Kanalın güçlü yanları [G]
- Yeniden üretilebilir iskelet (B5) ve marka cümleleri; "kademe/bileşen" yapısı; tek net fikir/kavram ("翻訳者", "階段", "ストレス時の最低点").
- Kaynak + hedge + güvenlik katmanı (009, 014: yardım hatları; 017/042/048: model uyarıları).
- Tez + bedel (049) ve "iki taraf aynı yapı" (048) gibi dengeli çerçeveler.
- Yorum → video döngüsü (ASD talebi, olası).
- Short → uzun döngüsü (015/018 → 002).
- Sakin, tutarlı ses ve müzik kimliği [K].

## 4. Çürütme turu (Aşama 4'ün ilk geçişi)
| Bulgu | En güçlü karşı kanıt | Durum |
|---|---|---|
| B1 Konu belirleyici | Short/"関連動画" beslemesi; ilk günlerin hızı bilinmiyor. **Tam listede aynı dönemde 4 IQ videosu 11 diğerinin hepsinin üstünde (U2); 003 vs 004 aynı gün 11x** | **Güçlendi** (orta-yüksek güven) |
| B1 Kapak ailesi belirleyici değil | 009/014 aynı aile, zayıf; 002/015 aynı aile, güçlü | **Güçlü** |
| B2 Klinik konu zayıf | Erken dönem (kanal küçük) ve yalnızca 2 örnek; devam notundaki ASD/HSP verisi doğrulanmamış | **Orta** |
| B3 Ters ilişki | n=13'te fazla güçlü çıkmıştı; n=54'te ρ -0,52 (beğeni), -0,35 (yorum) | **Orta; yön tutarlı, büyüklük ılımlı (U5)** |
| B5 İskelet ortak | Seçilim yanlılığı yok (11/11) | **Güçlü (gözlem)** |
| B5 Açık döngü önemli | Performans dağılımı aynı | **Çürütüldü (belirleyici değil)** |
| B8 Taban yükselmesi | (tam liste) dönem medyanları 37,7K → 89,9K → 123,7K | **Güçlü (U1)** |
| B9 CTA kalitesi | Küçük örnek; yorum kalitesi öznel | **Orta** |
| B10 Ses olumlu | Beğeni-ağırlıklı küçük sayım; yorum yazanlar seçilmiş | **Orta** |
| B11 Profil | Yalnızca yorum yazanlar | **Zayıf-orta (hipotez)** |

## 5. Açık sorular (sonraki aşama için)
1. **IQ/zekâ talebi mi, yoksa Short sıçraması mı?** Tam liste geldi (bkz. 0b/U2): aynı dönem içinde ayrışma net, ama ilk günlerin hızı (CTR/ilk 7 gün) bilinmiyor. Bu soru kesin kapanmayacak; hipotez düzeyinde "talep" ilkesini sürdürüyoruz.
2. **Tüm kapakların yan yana kıyası** (13 kapağı biz gördük; diğer 42 gerekirse).
3. ~~Animasyondan örnek kareler~~: kullanıcı animasyon dilini kendisi gördü, test gerekmiyor.
4. **Kanalın gerçek izleyici yaşı/cinsiyeti** (YouTube Analytics yok; yalnızca yorumlardan çıkarım).
