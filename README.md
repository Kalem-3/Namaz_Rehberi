# Namaz Rehberi — görselli sürüm 4

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
