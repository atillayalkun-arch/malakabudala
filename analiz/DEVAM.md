# Devam notu (2026-10-20) — yeni oturum buradan başlar

## 1. Amaç ve aşama
Kullanıcı (IT öğrencisi) faceless **Japonca YouTube kanalı** kuruyor. Plan: hedef kanalı analiz et → **kanal DNA'sı + kanal haritası** yaz → sonra video fikri üretim hattı. Hedef kanal: **深淵回廊@人間の脳と心の仕組み** (ID UCV8Jcbou4ei7HhtuffgvUYg), açılış 2026-07-16, çekim 2026-10-14: 55 video, ~14M izlenme, ~97K abone.
**Biten:** Aşama 0-4 (veri kontrolü, 13 video kartı, çapraz analiz, tam liste güncellemesi, kanal analizi raporu, çürütme turu).
**Sırada (4 soru cevaplandı, bkz. 4):** **kanal DNA'sı + kanal haritası** → video fikri üretim hattı.
Bu analiz yalnızca bir aşama; niş kararı hedef kanalı inceleyerek verilecek, sonra "daha iyi/mantıklı" bulgular eklenecek.

## 2. Dosya haritası (okuma sırası)
1. `analiz/rapor-kanal-analizi.md` — **ana rapor** (Aşama 3-4: ne yapıyor, neden tutuyor, başarı kalıpları, zayıf video teşhisi, eksikler, boş hücreler, çıkarımlar, çürütme tablosu).
2. `analiz/capraz-analiz.md` — sayısal tablo, kodlanmış özellikler, bulgular B1-B14; **bölüm 0b (U1-U9) tam liste ile güncellemedir ve eski bulguları düzeltir**.
3. `analiz/video-listesi-kodlu.md` — 55 video + benim konu kodlamam.
4. `analiz/kartlar/NNN.md` — 13 derin kart (002, 004, 008, 009, 010, 014, 015, 017, 018, 042, 048, 049, 052). İhtiyaç olunca aç.
5. Ham veri: `japa analizzz/NNN/` (her video: transkript, kapak jpg, video.md, yorum.md) ve `japa analizzz/video_listesi.md`.

## 3. Kullanıcının kararları ve bildirimleri (kesin)
- **Niş kararı** hedef kanalı analiz edince verilecek; analiz sonrası "daha iyi" bulgular eklenecek.
- **Short'lar açı testi aracı** olarak kullanılacak (kullanıcı onayladı).
- **Ses:** hedef kanalın konuşmacı sesi **bu kanala özgü, kaliteli AI ses** (kopya/ortak değil; kullanıcı ElevenLabs'e aşina). Arka planda **hafif gerilim/gizem müziği**.
- **Kapaklar düzensiz**, **kapak dili animasyonla alakasız**. Animasyon: koyu lacivert gece sahneleri, düz vektör, karakter etrafında parlak hale, üstte kalıcı bölüm başlığı, altta büyük kalın altyazı (kullanıcının ekran görüntüleri **051** videosundan; test gerekmiyor).
- **Moderasyon/şiddet içeren yorumlar:** kullanıcıya göre olumsuz değil; "dikkatsiz izleyici" sinyali olarak oku.
- Her video **aynı derinlikte** işlendi (yorumlar dahil), yorumlar nişin tek belirleyicisi değil ama "neden seviyor/karşılanmamış ihtiyaç" kanıtı.
- Depo şu an **Public**; yorumlar gerçek kişilerin metni. **Kullanıcıya Private yapmasını önerdim** (Settings → Danger Zone → Change visibility); henüz yapıp yapmadığı bilinmiyor.

- **Ham veri (`japa analizzz/`) tekrar analiz edilmeyecek** (kullanıcı kararı, 2026-10-20). Kartlar (13) ve `video-listesi-kodlu.md` yeterli sayılır; kalan 42 video başlık düzeyinde kalır, sonuçlar bir kademe düşük güvenle okunur.
- **Kanal DNA'sı:** `analiz/kanal-dna.md` (sürüm 1.0; tek başına okunabilir, başka modellere verilecek). Yapı: kimlik cümlesi → izleyici → vaat → açı → konu alanları → ton/marka → sınırlar. Fikir değerlendirme süzgeci ve kaynak kanal taraması: `analiz/fikir-suzgeci.md`. Gerekçe, kanıt, açık işler: `analiz/dna-gerekce.md`. Strateji taslağı arşivde. Çalışma kuralı: veriyle çözülebilen kararları model verir; kullanıcıya yalnızca ona ait kararlar (maskot, kanal adı vb.) sorulur.
- **Taslak niş değerlendirmesi:** `analiz/nis-degerlendirme.md` (çekirdek önerisi: kişiler arası anlama + uygulama + kanıt derecesi; iş yeri=sahne, bulmaca=kanca). Karar bekliyor.

## 4. Kullanıcıdan beklenen 4 karar (kullanıcı tek tek cevaplayacak)
1. **Niş yönü (KARARLANDI 2026-10-20: çekirdek = kişiler arası anlama + uygulama + kanıt derecesi; iş yeri bir sahne/katman, bulmaca kanca, klinik yan hücre; ayrıntı `nis-degerlendirme.md`).** Eski soru: (a) iş hayatı ağırlıklı alt alan, (b) bulmaca/düşünce deneyi formatı, (c) pratik rehber katmanı ya da birleşimi. *Benim önerim: (a)+(c) ana eksen, (b) yan format.*
2. **Kanal kimliği (KARARLANDI 2026-10-20: kanalın bir marka yüzü = maskot karakter; kanal 'AI yapımı' olarak gösterilmeyecek [K]. Benim notum: maskot uzman gibi sunulmaz, güven kaynak + kanıt derecesi ile kurulur; doğrudan sorulursa yalan söylenmez [kullanıcı onayı bekliyor]; YouTube sentetik içerik etiketi kuralı kanal açılmadan doğrulanmalı [web ile doğrulanmadı]).** Eski soru: yüzsüz AI ses kalıyor mu; "kim konuşuyor, neden güvenmeliyim?" sorusuna cevap (yöntem/kaynak sayfası?).
3. **Short stratejisi (KARARLANDI 2026-10-20: ilk etapta Short öncelikli değil; hem test hem uzun video kesiti/tanıtım amaçlı kullanılabilir; ara sıra, kullanıcı vaka başına karar verir. Kullanıcı gerekçesi: Short izleyicisi ile uzun video izleyicisi farklı algoritma, Short abone için iyi olabilir [K]; bu bizim verimizde ayrıştırılamıyor).** Eski soru: sıklık ve yapı (uzun videonun tek sahnesi + sabit yorum linki; açı testi).
4. **Yorum cevaplama politikası (KARARLANDI 2026-10-20: ilk etapta her yoruma cevap, sonra seçici; fikir değeri taşıyan yorumlar fikir hattına girer; kanala saldırı olmadıkça içsel düşünce/şiddet içerikli yorumlar engellenmez, tartışma serbest. Not: YouTube'un nefret söylemi kuralları ve reklam riski ayrıca geçerli [kullanıcı bilgilendirildi]). DNA'ya yalnızca 'yorum = fikir girdisi' girer; cevap/moderasyon ayrıntısı operasyon notudur.** Eski soru: kanal sahibi cevap verecek mi?

## 5. Ana bulgular (özet; güven rapor içinde)
- Aynı dönemde (16 Tem-10 Ağu) **4 IQ/zekâ videosu 83K-1,02M, diğer 11 video 10,8K-74K**; 003 (IQ, 158K) vs 004 (nostalji, 14K) aynı gün. Short/"関連動画" beslemesi karıştırıcı. (Orta-yüksek güven.)
- Konu medyanları (uzun): bulmaca/düşünce deneyi 186K (3/3 sağlam), IQ 158K, kişiler arası çekim/uyum 138K, aile/ACE 98K, iş yeri insan tipi 74K, klinik 38K, nostalji/kan grubu/film 14K.
- **Kapak ailesi tek başına belirleyici değil** (aynı aile hem 002/015'te güçlü, hem 009/014'te zayıf). Güçlü.
- **Taban zamanla yükseldi:** uzun video medyanı 37,7K → 89,9K → 123,7K. Dönemler arası kıyas yanıltıcı.
- **Memnuniyet ↔ erişim ters:** Spearman -0,52 (beğeni oranı, n=54).
- **11/11 uzun videoda aynı iskelet ve marka cümleleri**; açık döngü performansı belirlemiyor.
- 6 Short (4-13 Ağu, medyan 68K); yalnızca 015 (3,2M, 002'nin birebir kesiti) ve 018 (516K) patladı; 62 gündür Short yok.
- Eksikler: ilgisiz etiket şablonu, kapak-başlık-içerik tutarsızlığı, damgalayıcı kapaklar (018, 014), "uzman yok" eleştirisi, tartışmalı bilimsel iddialar, kanal sahibi cevap vermiyor.
- Boş hücreler: görsel düşünür, 離人症, MBTI/etiket kültürü, kuşak alt grupları, "farklı bilişsel tarzdaki kişiyle çalışma rehberi", özet/PDF/şablon ürünleri. (ASD=030, EQ=029 kanalda zaten var.)

## 6. Düzeltmeler (karışmasın)
- Ekran görüntüleri **042'den değil 051'den** (kart 042 başında düzeltme notu).
- **018'in kaynağı 002 mi 007 mi kesin değil** (DK cümleleri 002'de, sabit yorum 007'ye bağlıyor). **015 → 002 kesin.**
- n=13'te bulunan ρ=-0,61/-0,70 fazla güçlüydü; n=54'te -0,52/-0,35.
- "Zaman karıştırıcısı" kritik: erken zayıf videolar kanalın ilk 3 haftasından.

## 7. Bilinen sınırlar
CTR, izlenme süresi, trafik kaynağı, abone dönüşümü yok. 55 videonun yalnızca 13'ü derin okundu. Yorumlar yalnızca yorum yazanları yansıtıyor. Konu kodlaması benim yargım. Japonca çevirileri benim okumam; kritik nüansta düşük güven.

## 8. Çalışma biçimi
- Kartlar: `analiz/kartlar/NNN.md` şablonu (künye, paketleme, giriş+yapı, neden tutmuş/tutmamış, zayıflıklar, karşılanmamış ihtiyaçlar, bizim için notlar, güven notu).
- Sonraki video fikri hattı (kullanıcıyla kararlaştırıldı): video başına özet kartı (ihtiyaç, vaat, açı, format, 3-5 iddia) + süzülmüş yorumlar + DNA → 30-50 aday → dış doğrulama (kaynak URL+alıntı) → **kopya testi** (15-30 sorgu, YouTube arama, LLM ile "aynı ihtiyaç+açı mı" eleme, risk=benzerlik×erişim×yenilik) → paketleme. Başarısız videolar negatif örnek.
