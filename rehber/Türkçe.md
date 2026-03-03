# 🐺 Wolvesville Rehberi (Türkçe)

Bu döküman, Wolvesville dünyasına yeni adım atanlardan, işin teknik/kodlama kısmıyla ilgilenen geliştiricilere kadar herkes için hazırlanmış kapsamlı bir rehberdir.

> 💡 **Katkıda Bulunun:** Eğer eksik bir şey görürseniz veya yeni bir taktik eklemek isterseniz lütfen **Pull Request** gönderin veya bir **Issue** açın.

## 📑 İçindekiler

### 🏁 1. Başlangıç ve Temeller

* [1.1. Wolvesville Nedir?](#11-wolvesville-nedir)
* [1.2. Oyunun Hikayesi ve Amacı](#12-oyunun-hikayesi-ve-amaci)
* [1.3. Wolvesville Nasıl Yüklenir?](#13-wolvesville-nasil-yuklenir)
* [1.4. Hesap Oluşturma ve Giriş Seçenekleri](#14-hesap-olusturma-ve-giris-secenekleri)
* [1.5. Cihaz Performansı ve Optimizasyon](#15-cihaz-performansi-ve-optimizasyon)

### 🕹️ 2. Oyun Mekanikleri ve Arayüz

* [2.1. Arayüz Tanıtımı: Ana Menüde Neler Var?](#21-arayuz-tanitimi-ana-menude-neler-var)
* [2.2. İlk Maçınıza Hazırlık: Eğitim Modu](#22-ilk-maciniza-hazirlik-egitim-modu)
* [2.3. Oyun Modları Arasındaki Farklar](#23-oyun-modlari-arasindaki-farklar)
* [2.4. Görevler ve Ödül Sistemi](#24-gorevler-ve-odul-sistemi)
* [2.5. Ekonomi Yönetimi](#25-ekonomi-yonetimi)

### 🎭 3. Roller ve Kart Sistemi

* [3.1. Roller ve Görevleri](#31-roller-ve-gorevleri)
* [3.2. Rol Kartları ve Geliştirme Özellikleri](#32-rol-kartlari-ve-gelistirme-ozellikleri)
* [3.3. Rol Öncelik Listesi (Meta Roller)](#33-rol-oncelik-listesi-meta-roller)
* [3.4. Oyun İçi İtemler ve İşlevleri](#34-oyun-ici-itemler-ve-islevleri)

### 🧠 4. Strateji, Taktik ve Sosyal

* [4.1. Temel Terimler Sözlüğü](#41-temel-terimler-sozlugu)
* [4.2. Oyun İçi İletişim Protokolü](#42-oyun-ici-iletisim-protokolu)
* [4.3. Hızlı Gelişme Taktikleri](#43-hizli-gelisme-taktikleri)
* [4.4. Orta Seviye Analiz Taktikleri](#44-orta-seviye-analiz-taktikleri)
* [4.5. İleri Seviye Taktikler ve Manipülasyon](#45-ileri-seviye-taktikler-ve-manipulasyon)
* [4.6. Psikoloji ve Blöf Sanatı](#46-psikoloji-ve-blof-sanati)

### 👥 5. Sosyal Yapı ve Topluluk

* [5.1. Arkadaş Ekleme ve Sosyal Özellikler](#51-arkadas-ekleme-ve-sosyal-ozellikler)
* [5.2. Klanlar, Mağaza ve Özelleştirme](#52-klanlar-magaza-ve-ozellestirme)
* [5.3. Topluluk Kuralları ve Güvenlik](#53-topluluk-kurallari-ve-guvenlik)

### 💻 6. Teknik ve Geliştirici Bölümü

* [6.1. Teknik Bilgiler ve Geliştiricilik (Yakında)](#61-teknik-bilgiler-ve-gelistiricilik-yakinda)

## 🏁 1. Başlangıç ve Temeller

### 1.1. Wolvesville Nedir?

* Wolvesville genellikle 16 kişilik köyde kazanmaya çalıştığınız bir sosyal mühendislik oyunudur. Oyun web tabanlı 2D'dir.

### 1.2. Oyunun Hikayesi ve Amacı

* Oyunun belirli bir resmi hikayesi olmamakla beraber amacı; köyde üç takımdan birine ait rolle galibiyet almaya çalışmaktır.

### 1.3. Wolvesville Nasıl Yüklenir?

* Wolvesville'i [Webden](https://www.wolvesville.com/), Android için Play Store'dan, iOS için App Store'dan indirebilirsiniz. Kayıt olarak / Giriş yaparak oynamaya başlayabilirsiniz.

### 1.4. Hesap Oluşturma ve Giriş Seçenekleri

* Wolvesville'de hesap oluşturmak ücretsizdir. Gmail, mail türevi hesaplarla kayıt olduktan ve nick (kullanıcı adı) seçiminden sonra oynamaya başlayabilirsiniz.

### 1.5. Cihaz Performansı ve Optimizasyon

* Wolvesville ortalama bir cihazda sorun çıkarmadan oynatacak bir arayüze sahiptir. Fakat cihazınız eski sürümse ayarlardan animasyonları kapatabilirsiniz.

## 🕹️ 2. Oyun Mekanikleri ve Arayüz

### 2.1. Arayüz Tanıtımı: Ana Menüde Neler Var?

* Oyna, Envanter, Mağaza, Klanlar, Roller başlangıç tuşlarıdır.

* Bunlardan bağımsız olarak klana katılmanız halinde sağ altta (veya web'den giriyorsanız sağ üstte) klanla alakalı butonlar var.

* Eğer teklif, davet vesaire aldıysanız sol tarafta uzun liste halinde, web kısmında yine sol tarafta fakat roller tuşunun altında gözükür.

* Buna ek olarak mobilde profil ayarı için başlangıç tuşlarında **Profil** var. Mobilden farklı olarak webde sağdan kullanıcı adınıza tıklayarak bu menüye giriyorsunuz. Onun harici tüm tuşları tek tek açıklamama gerek yok bence.

### 2.2. İlk Maçınıza Hazırlık: Eğitim Modu

* Mümkünse ilk maçınıza girmeden önce rollerin özelliklerini okuyun. Kullanmayı bilmezseniz küfür + rep yeme olasılığınız yüksek (özellikle TR serverında).

### 2.3. Oyun Modları Arasındaki Farklar

Oyun modları şu şekildedir: **Hızlı oyun, Çılgın oyun, Gelişmiş oyun, Dereceli oyun, Özel oyunlar, Kum havuzu (Sandbox).**

* **XP Kazandırmayanlar:** Çılgın oyun ve Özel oyunların geneli (vill win / grind harici).

* Hepsinin amacı aynı fakat oynanma süreleri ve roller bakımından farklılık göstermektedir.

* **Kum Havuzu:** Yeni güncellemelerde gelecek roller içindir.

* **Dereceli:** Adıyla aynı fakat çok zor dolduğundan ben hiç göremedim. Eskiden TR sunucusunda varmış, kalkmış.

* **Hızlı ve Gelişmiş:** Gelişmiş oyun, Hızlı oyunun daha çok rol barındıran ve daha yavaş oynanan versiyonudur.

* **Çılgın Oyun:** Türü arttırmak için eklenmiş bir oyun türüdür. Tek kazancı, içinde farklı türleri olmasıdır. Her türü oynadığınızda yükleme ekranı veriyor genelde veya basit bir item veriyor.

### 2.4. Görevler ve Ödül Sistemi

* **Günlük Görevler:** Genelde "X rolüyle kazan", "Y rolüyle oyna" şeklindedir ve oyun sonu ek XP vermektedir.

* **Haftalık Görevler:** Herkeste aynıdır; elmas ve rol kartı verir.

* **Savaş Bileti (Battle Pass) Görevleri:** Herkeste aynıdır ve 7 günlüktür. Karşılığında 200 BP jetonu verir. Bunlarla BP mağazasında altın, görev değiştirme kartı ve skin alabilirsiniz. Battlepass'i açıklamama gerek yok, her oyundaki klasik bir sistemden ibaret.

* **Rol İkonu Meydan Okumaları:** BP görevi bitirdikçe bunları da yapmış oluyorsunuz. Karşılığında BP teması ile alakalı rol ikonları veriyor.

* **Çarklar:** Gül çarkı ve Altın çarkı olarak ikiye ayrılır. Altın çarkı reklam izleyerek çevirebilirsiniz. Gül çarkı ise topladığınız gül sayısı 30 olduğunda çevirebildiğiniz, içinden özel şeyler çıkabilen bir çarktır.

* **Klan Görevleri:** Skin kasmak için altınla veya elmasla satılan görevlerdir. Klandaki üye başına fiyat artmaktadır.

### 2.5. Ekonomi Yönetimi

Wolvesville ekonomisi **Altın**, **Elmas** ve **Gül**'den oluşur.

* **Elmas:** Tüm oyunun kalbi gibidir. Tüm ekonomi genel olarak elmas üzerinden döner.

* **Gül:** Elmas'tan sonra en çok kullanılan birimdir. Gülü altına çevirmek, skine çevirmek veya takas yapmak diğer birimlere göre daha kolaydır.

* **Altın:** Herkesin kolayca erişebileceği birimdir. Dolaylı olarak güle ve elmasa çevirebilirsiniz ama kolay erişilebilir olması değer konumundan onu sonuncu yapıyor.

* **BP Jetonu:** Sadece BP markette geçen bir birimdir. Altına, skine ve görev değiştirme kartına dönüştürülebilir.

**Ekonomi Kazanım Yolları:**

* Tüm para birimleri parayla satın alınarak kullanılabilir.

* **Elmas:** BP'den, görevlerden ve sandıklardan çıkabilir.

* **Gül:** Diğer insanlarla takas yaparak kazanılır. Diğer birimlere çevirmesi çok kolaydır. Gül karşılığı skin, elmas, altın bağışı (klan yoluyla) veya Gül çarkı (30 güle bir çevirme) ile diğer birimlere çevirebilirsiniz.

* **Altın:** Reklam izleyerek, çark çevirmeden, sandıklardan direkt çıkarak veya sandıklardan aynı skinler gelirse altına çevrilerek kazanılır. Gül çarkı çevirmeden de kazanılabilir. Altını skine (doğrudan ve dolaylı), güle (dolaylı) ve Elmasa (dolaylı) olarak çevirebilirsiniz.

## 🎭 3. Roller ve Kart Sistemi

### 3.1. Roller ve Görevleri

Genel olarak roller 3 takıma ayrılır: **Kurtlar**, **Köylüler**, **Solo**. Bunlardan bağımsız olarak takım değiştirebilen takımsız roller de vardır (Örn: Aylakçı).

* **Kurtlar:** Kurt Adam Hayranı hariç hepsi kurttur.

* **Köylüler:** Diğer köylülerin yaşamından ve kurtların yok edilmesinden sorumludur.

* **Solo Roller:** Çoğunlukla kendilerine oynarlar fakat duruma bağlı olarak kötü rollerle ittifak yapmakta serbesttirler.

* *(Detaylı roller için oyun içindeki "Roller" sekmesine bakabilirsiniz).*

### 3.2. Rol Kartları ve Geliştirme Özellikleri

* Rol kartları yeni roller ve yeni özellikler açmanıza olanak sağlar.

* Gelişmiş roller çoğunlukla temel rollerden daha iyidir.

* Kart birleştirme yaparak destansı kartları açarsanız gelişmiş rollere erişebilirsiniz.

* Her yükseltmede açılan bazı özellikler vardır. Bunlar size ek XP, ek altın, ek gül veya araç sağlayan özelliklerdir (araçlar genelde çok işlevsel değildir).

### 3.3. Rol Öncelik Listesi (Meta Roller)

Genel olarak kesin bir meta yoktur ama çoğunlukla gelişmiş roller temellerden daha iyidir.

* **Önerilen Gelişmiş Roller:** Manipülatör Kurt, Gunner, Sihirdar Kurt, Çılgın Kurt, Fırtına Kurt, Efsuncu, Analist, Flagger.

* Lobiye göre belki Yargıç ve Hatip de tercih listesinde değişebilir.

### 3.4. Oyun İçi İtemler ve İşlevleri

Oyun içinde genel olarak şu itemler bulunur:

* Para birimleri

* Skinler

* Rol özelliği değiştirme kartı

* Günlük görev değiştirme kartı

* Rol kartları ve türevleri

## 🧠 4. Strateji, Taktik ve Sosyal

### 4.1. Temel Terimler Sözlüğü

Oyundaki rollerin çoğunun kısaltması bir temel terimdir.

* **Det:** Dedektif

* **Çç:** Çiçek Çocuk

* **Aura İnfosu:** İyi, Kötü, Unk (Bilinmeyen)

* **Mentalist İnfosu:** Kırmızı, Mavi

* **Dedektif İnfosu:** Eşit (=), Eşit değil (≠ / #)

* **Gözcü:** Direkt rol söyler.

* **Şerif:** İki şüpheli söyler.

* **Gözcü Çırağı:** Hepsini söyleyebilir ama ilk hangisinin öldüğüne bağlıdır.

* **Analist:** 2 kişiye bakar. Aura'nın gelişmişidir.

* **Kumarbaz:** Köyden/değil, Kurtlardan/değil, Solo/değil.

* **Mortisyen:** X kişisini öldüren iki şüpheliyi bulur.

* **Kemancı:** Ölen oyuncuların yasını tutup tutmadığına bakabilirsiniz.

* **Kurt İnfo Rolleri:**

  * **Kör Kurt Adam:** İki kişiye sadece takımına bakarsınız.

  * **Gözcü Kurt:** 1 kişinin rolüne bakarsınız.

  * **Sorcerer:** 1 kişinin rolüne bakarsınız ama kurtlarla konuşamazsınız, tek artısı kendinizi baktığınız role gizlemektir.

* Bunun dışı, her rolün ayrı özelliği olduğundan özelliklerine göre kısaltmalar görebilirsiniz (Örn: "Manip" -> Manipülendim demektir).

### 4.2. Oyun İçi İletişim Protokolü

* **İnfocuysanız:** Oyunun anahtarı genellikle sizdedir. AFK bırakmayınız ve solo rollerin (Fool ve HH için) rolünüzü çalmasına izin vermeyiniz. Baskıcı olmanız lazım, hızlı mesaj yazmak önemlidir.

* **Güçlü köylülerdenseniz:** Genelde adam öldürme veya canlandırmaya sahipsinizdir. Mümkünse info varsa vurun, infocular öldüyse oyunu devralma hakkı sizindir. İnfocular öldüğünde random rol sorup vurmakta özgürsünüz.

* **Normal köylülerdenseniz:** Üst rütbeli köylüleri korumaktan ve asılmaktan korumaktan sorumlusunuz. Daha üst rütbeli köylüler varsa random rol sormanız oyunun kurallarına aykırıdır.

* **Kurtsanız:** Hedefiniz köylü öldürmek olmalı. Eğer çok fazla kişiyseniz asıldığınızda solo ifşalamamalısınız (sizin yararınıza kurt kesmiyorsa).

* **Solo katil veya Solo iseniz:** Belirli bir kuralınız yok. İstediğinize oynayabilirsiniz ama öncelik sizsiniz, unutmayın.

* **Genel Chat Kuralı:** Oyun chatinde saygılı olunuz, kurallara uyunuz.

### 4.3. Hızlı Gelişme Taktikleri

Oyundaki en hızlı gelişme taktiği şüphesiz **"Vill Win"** dir. Bunun dışında **"Grind"** ve **"HH Win"** modları da vardır. Oda sahibi siz değilseniz bulmanız zor oluyor, özel oyun dışı modlar diğerlerine kıyasla daha yavaş kalıyor.

* **Vill Win Nedir?** Genelde 8-9 kişiyle oynanan çifter takımlar halinde oyuna başladığınız oyun türüdür. Bu oyunda amacınız en hızlı şekilde köye "win" salmaktır. Kurtsanız eşinizi öldürerek köye win salarsınız. En hızlı biten oyunlar genellikle Yavru Kurt'un kendi eşini öldürüp yanına sizin eşinizi almasıdır. (8 kişi optimaldir).

* Daha hızlı level atlamak için: Görev yaparak, her maç sonu reklam izleyerek 2x XP alarak veya 2x XP paketi satın alarak daha hızlı XP kasabilirsiniz.

### 4.4. Orta Seviye Analiz Taktikleri

Analiz yapmak Wolvesville'de çok önemlidir: Emoji analizi, skin+icon analizi, level+rol analizi gibi.

* **Örnek:** Biri öldükten sonra "gülme" emojisi atan kişi ya ölen oyuncuyla kavgalıdır ya da kurttur. Bu sadece örneklerden biri; mantık kullanarak analiz yapmalısınız. Çoğu oyunda bu tür orta seviye analizleri kullanabilirsiniz.

### 4.5. İleri Seviye Taktikler ve Manipülasyon

Bu konu Wolvesville'de artık ustalaşmak anlamına geliyor. Özellikle derecelide (ranked) kullanabileceğiniz taktikleri içeriyor:

* **Taktik 1 (Sessizlik):** Sabahları en sessizler, geceleri en gürültü çıkaranlardır. Eğer hiç konuşmamış biri varsa ve 2 günden fazla süredir yaşıyorsa, ya kurttur ya da önemli roldür.

* **Taktik 2 (Baskı):** Eğer kurtsanız ve kurt olduğunuz henüz kesinleşmedi ama üzerinizde bir suçlama varsa; hemen rol claimleyin (rol iddia edin) ve spam olmayacak şekilde baskıyla mesaj atın. Rakibinize fırsat vermeden onun kurt olduğuna diğer köylüleri ikna edin.

* **Taktik 3 (Kelle Avcısı - HH):** Bu taktiğimiz Kelle Avcısı oynayanlar içindir. Eğer hedefinizi astırmak istiyorsanız "kötü" diyerek dikkatleri üzerine çekmeyin. Sanki hedefiniz değilmiş gibi "Unk" (Bilinmeyen) deyin. Eğer gerçek Aura birine "kötü" derse (ki muhtemelen o kişi kurttur) siz asıl Aura'nın Kelle Avcısı (HH) olduğunu söyleyin. Böylece Aura rolünü çalmış (claimlemiş) olursunuz.

* **Taktik 4 (Soytarı - Fool):** Soytarıysanız iki tarafa da oynayın. Kurtlar ve köy genelde sizi kesmeyeceğinden, kişi sayısı azaldığında bir tarafı diğer tarafa kazandırmakla tehdit edip oyunu kendinize çevirebilirsiniz. Ayrıca solo katillere de oynayabilirsiniz, sololar birbirine destek olmalıdır.

* **Taktik 5 (İnfocular):** Fırtına kurt varken infolarınız kaynayabilir, bu yüzden oyunculara isim olarak bakmalısınız. Sohbette hızlıca 3 harf yazabildiğiniz için eğer baktığınız kişi iyiyse \`3iy\`, unk ise \`3un\`, kötüyse \`3kö\` yazmanız yeterli. Baş harfli olduğu için anlaşılmanız daha kolay olacaktır.

* **Taktik 6 (Manipülatör Kurt):** İlk başlarda her zaman infocuların oyunu kullanın. Belediye Başkanı rolünü oyunun sonlarına saklar. Oyun sonu Belediye Başkanının 2x oyu (çift oy hakkı) çok işinize yarayacaktır.

* **Taktik 7 (Ruh Bağlayan - RB):** Bu biraz illegal/etik dışı bir taktiktir fakat en etkili taktiklerden biridir. RB olarak kendinizi kanıtlamanız çok kolaydır. İlk gece istediğiniz bir kişiye bağlanıp fısıldayarak rol sorabilirsiniz. Rol vermezse köye dönüp "Ben RB'yim, bu adam gece rol vermedi" diyebilirsiniz. İtiraz gelirse genelde kurtlardan gelir, bu da ayrı bir infodur.

* **Taktik 8 (Kundakçı):** Çok açgözlü olmayın. Aynı anda çok kişi yakmaya çalışırsanız elinizdekilerden olma (ölme) ihtimaliniz daha yüksektir.

*(Taktikler şimdilik bu kadardı. Daha fazla taktik önermek için PR veya Issue açabilirsiniz.)*

### 4.6. Psikoloji ve Blöf Sanatı

Yalan söylemek bu oyunda temel bir şeydir. Sosyal mühendislik oyunu olduğu için; akıl karıştırma, hedef değiştirme, rol çalma, "fool" taklidi, "noob" (acemi) taklidi yapmayı öğrenmelisiniz. Stres yönetimi de oyun içinde ayrıca çok önemli bir faktördür.

## 👥 5. Sosyal Yapı ve Topluluk

### 5.1. Arkadaş Ekleme ve Sosyal Özellikler

Wolvesville bir sosyal mühendislik oyunudur ve bu oyunu oynayan bir çevrenizin olması gelişmenize büyük katkı sağlar. Arkadaş ekleyerek ekonomik ve sosyal olarak güçlenebilirsiniz. Skin gönderme, hediye gönderme gibi birçok özellik var. Arkadaşlarla yapılmalık onca görev varken fırsatları kaçırmayın.

### 5.2. Klanlar, Mağaza ve Özelleştirme

* **Klanlar:** Her insan klana katılmak zorunda değildir ama klan oyun içinde gelişmenize büyük katkı sağlayacak bir araçtır. Ekonomik ve sosyal olarak arkadaş eklemekten bile daha çok faydası olabilir.

* **Mağaza:** Mağazada birçok şey satılıyor, hepsini açıklamaya gerek yok. Oyun genellikle pahalı fiyatlardan satıyor, TL cinsinden oyuncular arası "trade" (takas) sistemiyle itemleri daha ucuza getirebilirsiniz.

* **Özelleştirme:** Her oyuncu kendi skinini zevkine göre tasarlayabilir. Eskiden envanterde oylama sistemi vardı ve skinleri yarışmalarda kullanıp ödüller alınabiliyordu (Şimdi ne durumda bilmiyorum).

### 5.3. Topluluk Kuralları ve Güvenlik

Detaylı açıklamaya gerek yok: Saygı ve sevgi çerçevesinde olun.

* Oyunun kendi kurallarını ihlal etmeyin.

* Teaming (gizli takım olma/hile) yapmayın.

* İnsanların mahrem/kişisel bilgilerini oyunda paylaşmayın.

* Oyunu sabote etmeyin.

* Herkes birbirinin güvenliğinden sorumludur. Oyunun asıl amacı kurallara uygun olarak "en az kayıpla kurtları alt etmek" olduğundan, bu kurallar klan gibi oyun dışı ortamlarda da geçerlidir.

## 💻 6. Teknik ve Geliştirici Bölümü

### 6.1. Teknik Bilgiler ve Geliştiricilik (Yakında)

*(Geliştirici kısmı yakında eklenecektir! Özellikle C# ve benzeri dillerle API kullanımı, bot yazımı ve oyun içi verilerin çekilmesiyle ilgili teknik detaylar bu bölümde yer alacaktır.)*`;
