# Namaz Rehberi — görselli sürüm 9

## Başlatma
ZIP dosyasını çıkarıp index.html dosyasını açın. Vakti seçin. Erkek/kadın görünümü üst çubuktan değişir. Önce duruş ve yanındaki ayrıntılar, sonra açıklama, dua, okunuş ve anlamı gösterilir. Görsellere dokunarak büyütün. Birden çok duruş içeren adımlarda üstteki duruş düğmeleri kullanılır. Önceki/sonraki adımla ilerlenir. Tüm adımları birlikte görmek de mümkündür.

## GitHub Pages
Bu klasörün içeriğini GitHub deposunun köküne yükleyin. index.html kökte bulunmalıdır. Pages ayarlarında yayın kaynağını main dalının kökü olarak seçin. Derleme, API anahtarı veya sunucu gerekmez. Tüm yollar görecelidir, font ve görseller paketin içindedir. ZIP arşivini tek başına yüklemek siteyi yayınlamaz; içindeki dosyalar yüklenmelidir.

## Görseller ve kıyafetler
Yetişkin erkek için beyaz takke, daha açık yumuşak yeşil gömlek ve daha koyu yeşil pantolon; yetişkin kadın için beyaz elbise ve yeşil başörtüsü kullanılmıştır. Renkler kullanıcı isteğine göre düzenlenmiştir. Bunlar tarikatın tarihî kıyafet standardına ilişkin bir belgeleme iddiası taşımaz.

İki görsel levhasının her birinde 9 çizim yer alır: tekbir, kıyam, rükû, kavme, secde, oturuş, selâm için baş yönü, el bağlama yakın planı ve oturuşta ayak yakın planı. Web sayfası levhanın ilgili hücresini gösterir. İlave ayrıntılar ilgili hücrenin büyütülmüş görünümüdür. Video, GIF veya animasyon yoktur.

Sağ ve sol namaz kılan kişinin kendi sağı ve soludur. Selâm yakın planı kişinin soluna dönmesini gösterir; açıklamada önce sağa sonra sola selâm verileceği belirtilir. Yakın planlar açıklamayı destekleyen çizimlerdir; uzuvların her açısını ölçülü biçimde gösteren anatomik model değildir.

## İçerik ve kaynak
Orijinal beş HTML dosyasının Arapça, okunuş, anlam ve duruş paragrafları değiştirilmemiştir. Sabah rehberindeki ayrıntılı dua metinleri, yalnızca önceki adımlara atıf yapan bazı adımlarda yeniden gösterilir. Bu çalışmada orijinal metinlerin tümü bağımsız dinî içerik incelemesinden geçirilmemiştir.

Kadın/erkek duruş açıklamalarında kullanılan resmî kaynak:
Diyanet İşleri Başkanlığı Din İşleri Yüksek Kurulu, “Kılınış bakımından kadınların namazı ile erkeklerin namazı arasında ne gibi farklar bulunmaktadır?”, 12.07.2017.
https://kurul.diyanet.gov.tr/tr/fetva/kilinis-bakimindan-kadinlarin-namazi-ile-erkeklerin-namazi-arasinda-ne-gibi-farklar-bulunmaktadir/0193c42d-64a5-7ba1-9af3-f9f4a7f97245

## Dosyalar
assets/gorseller.js: görsel eşleme, ayrıntı açıklamaları, adım geçişleri ve büyütme.
assets/gorseller.css: duyarlı sayfa düzeni ve görsel kesitler.
assets/dualar.js: orijinal rehberden alınmış tekrar kullanılabilir dua metinleri.
assets/erkek-duruslar.png ve assets/kadin-duruslar.png: resimli levhalar.
kaynak-metin.txt: kullanıcının sağladığı kaynak metin.

## Kontroller
Beş sayfanın orijinal dua/duruş paragrafları programatik olarak karşılaştırıldı; yerel dosya bağlantıları doğrulandı. Tarayıcıda tek-adım görünümü, tüm-adımlar görünümü, cinsiyet seçimi, adım seçimi ve görsel büyütme kontrol edildi. Gerçek iPhone cihazında test yapılmadı.

## Sürüm 3 düzeltmesi
Seccadelerin uzun ekseni kişinin gövde/dizlerinin yöneldiği namaz doğrultusuna göre düzeltildi. Selâmda seccade, başın döndüğü yöne göre çevrilmez. Önden ve yandan görünümlerde perspektif farklıdır.

## Sürüm 4 — okuma ve tema
Okunuşlar masaüstünde 23 px, telefonda 21 px; mealler 20/18 px; Arapça metin 14/13 px olarak düzenlendi. Dua kartlarında önce okunuş, sonra anlam ve en altta Arapça gösterilir. Sade yeşil-beyaz açık tema ana sayfa ve beş vakitte ortaktır. Dua metinleri ve duruş görselleri değiştirilmedi.

## Sürüm 5 — tüm adımlar görünümü ve renkler
Tüm adımlar açıkken önceki/sonraki adım çubuğu gizlenir. Gizli çubuğun CSS tarafından tekrar görünür yapılması engellendi. Üstteki adım seçimi, tüm adımlar görünümünde seçilen bölüme kaydırır. Tek-adım görünümüne dönüldüğünde gezinme geri gelir. Sıcak kırık beyaz, koyu yeşil, adaçayı ve sınırlı mat altın vurgularla renk dengesi güncellendi. Büyük okunuş/meal ve küçük Arapça düzeni korundu.

## Sürüm 6 — tanıtım dili
Ana sayfadaki sloganlar ve vakit kartlarının ifadeleri daha sade ve mütevazı bir dille yenilendi. Ana sayfa ile beş vaktin tanıtım/alt bilgi bölümlerinde İmam-ı Âzam Ebû Hanîfe Hazretleri’nin adı eklendi. Beş vaktin ders gövdeleri, dua metinleri, okunuşlar ve mealler V5 ile harfi harfine karşılaştırıldı ve aynen korundu. Görseller, stiller ve işlev dosyaları değişmedi.

## Sürüm 7 — içerik düzeltmeleri ve altın tema

- İstenen alt bilgi paragrafı kaldırıldı. Hanefî usulünün Türkiye’de yaygınlığı, tercih gerekçesi olarak tanıtıma eklendi; İmam-ı Âzam Ebû Hanîfe Hazretleri’nin adı korundu.
- Sabah namazında ikinci secdeden son oturuşa geçiş “Allahü ekber diyerek” olarak düzeltildi.
- İkindi ve yatsı ilk sünnetinin ara oturuşlarında Ettehiyyâtü ve Salli–Bârik bırakıldı. Bu iki noktada fazladan tekrarlanan Rabbenâ kartları kaldırıldı; son oturuşlardaki metinler korundu.
- Şehadet parmağının kaldırılma ve indirilme zamanı açıklandı; ikindi üçüncü rekât açıklamasındaki yazım hatası düzeltildi.
- Farzlarda örnek olarak aynı sûrenin gösterilmesine ilişkin açıklama eklendi. Mevcut İhlâs metni değiştirilmedi; başka sûre eklenmedi.
- Anlatımın tek başına namaz kılan kişi için olduğu belirtildi.
- Zeminler açık altın, şampanya ve krem tonlarına taşındı. Yeşil, ana eylem düğmeleri ve sınırlı metin vurgularında kullanıldı.

Koruma kontrolü: Kalan bütün dua kartlarının HTML içeriği V6 ile birebir karşılaştırıldı. Hiçbir Arapça metin, okunuş veya meal yeniden yazılmadı. Yalnızca yukarıda belirtilen iki ara oturuştaki ikişer tekrar kaldırıldı. Ortak dua verileri ile erkek/kadın görselleri V6 ile aynı. Kaynakla yapılan açıklama düzeltmeleri, görsellerdeki her anatomik ayrıntının uzman onayı anlamına gelmez.

Tercih gerekçesi kaynağı: TDV İslâm Ansiklopedisi, Hanefî Mezhebi: https://islamansiklopedisi.org.tr/hanefi-mezhebi
Uygulama açıklamaları: Diyanet Haber “Beş Vakit Namazın Kılınışı”, Din İşleri Yüksek Kurulu’nun ikindi/yatsı ilk sünneti açıklaması ve V6 içerik kontrol raporundaki kaynaklar.

## Sürüm 8 — yayın tasarımı

Tema tek bir tutarlı stil dosyasıyla yeniden kuruldu. Ana sayfa, solda tanıtım ve sağda çizgilerle ayrılmış beş vakit listesinden oluşuyor; telefonda tek sütuna dönüyor. Renkli kutuların ve yoğun zemin renklerinin yerini sıcak beyaz, koyu yazı ve sınırlı zeytin/altın vurgular aldı. Başlıklarda serif, okuma ve arayüz metinlerinde sistem yazı tipi kullanılıyor; haricî font veya ağ bağımlılığı eklenmedi. Namaz sayfaları aynı görsel düzene uyarlandı; yakın planlar çizgilerle ayrıldı, dua kartları sadeleştirildi. Okunuş/meal/Arapça büyüklükleri korundu.

Kontrol: V7 ile karşılaştırıldığında yalnızca assets/tema.css ve bu sürüm notu değişti. HTML içerikleri, dua verileri, görseller ve işlev dosyaları aynı. Tarayıcıda ana sayfa ve namaz sayfası incelendi; okunuş 23 px, meal 20 px ve Arapça 14 px olarak doğrulandı. Tüm-adımlar görünümünde gezinmenin gizlenmesi korundu. Gerçek telefonda test yapılmadı.

## Sürüm 9 — abdest ve yeni tema

Ana sayfanın ilk sırasına Abdest rehberi eklendi. Er ve bacılar için aynı sırayı gösteren 11 adım, yeni görseller, yakın planlar, yıkama tekrarları ve farz/sünnet açıklamaları bulunur. Tek-adım ve tüm-adımlar görünümleri, adım seçimi, büyütme ve tamamlama düğmesi kullanılabilir. Başın meshinde doğrudan başa temas gerektiği belirtilir.

Kaynaklar: Din İşleri Yüksek Kurulu “Abdest nedir ve nasıl alınır?”, Diyanet Haber “Abdest ile ilgili bilinmesi gerekenler” ve Din İşleri Yüksek Kurulu “Abdest alırken başörtüsünün üzerinden baş mesh edilebilir mi?” Kaynak bağlantıları abdest sayfasındadır.

Tasarım, kullanıcının bugrakaplan.com/denemeler/ sayfasındaki koyu yeşil, krem ve mat altın paletiyle yenilendi. Ana sayfaya kemerli görsel alanı eklendi. Haricî font veya sunucu bağımlılığı eklenmedi.

Kontroller: V8 ile karşılaştırmada beş namaz sayfasının tek değişikliği Abdest menü bağlantısıdır. Mevcut dua verileri, işlev dosyası ve namaz görselleri birebir korundu. İkindi/yatsı ilk sünnetinin ara oturuşlarında Ettehiyyâtü, Salli ve Bârik korundu. Yeni abdest okuyucusunda cinsiyet seçimi, adım seçimi, 11 adımın birlikte gösterilmesi, gezinmenin gizlenmesi ve tamamlama tarayıcıda kontrol edildi. Yerel bağlantılar ve JavaScript sözdizimi doğrulandı. Gerçek telefonda test yapılmadı.
