<div align="center">
	<h1 style="font-size:1rem"">1002 - HIZLI DESTEK PROGRAMI<br/>
	1002-A HIZLI DESTEK MODÜLÜ<br/>
	PROJE BAŞVURU FORMU</h1>
</div>

<table>
  <tr>
    <td><strong>Proje Başlığı:</strong> Video Konferans Yazılımlarının Test Otomasyonu: Gerçek Zamanlı Video ve Ses Benzerlik Analizi</td>
  </tr>
  <tr>
    <td><strong>Proje Yürütücüsü:</strong> Dr.Öğr.Üyesi Savaş Öztürk</td>
  </tr>
    <tr>
    <td><strong>Projenin Yürütüleceği Kurum/Kuruluş:</strong> Marmara Üniversitesi</td>
  </tr>
</table>

# 1. ÖZGÜN DEĞER

## 1.1. Konunun Önemi, Projenin Özgün Değeri ve Araştırma Sorusu veya Hipotezi

Proje önerisinde ele alınan konunun kapsamı ve sınırları ile önemi literatürün eleştirel bir değerlendirmesinin yanı sıra nitel veya nicel verilerle açıklanır. 

Özgün değer yazılırken projenin bilimsel kalitesi, farklılığı ve yeniliği, hangi eksikliği nasıl gidereceği veya hangi soruna nasıl bir çözüm geliştireceği ve ilgili bilim veya teknoloji alan(lar)ına kavramsal, kuramsal ve/veya metodolojik olarak ne gibi özgün katkılarda bulunacağı literatüre atıf yapılarak açıklanır. Kaynaklar http://www.tubitak gov.tr/ardeb-kaynakca sayfasındaki açıklamalara uygun olarak EK-1’de verilir. 

Projenin araştırma sorusu ve varsa hipotezi veya ele aldığı problem(ler)i açık bir şekilde ortaya konulur.

> 2020 yılının başından itibaren hayatımızı etkileyen Covid-19 salgını ile iş yapış şekilleri de etkilenmiş, uzaktan çalışma ve uzaktan eğitim amacıyla kullanılan teknolojilere daha çok ihtiyaç duyulmaya başlanmıştır. Çevrim içi eğitim ve toplantılar için kullanılan araçlar, dünya ağ trafiğine önemli bir yük oluşturmuş ve bu ise beraberinde performans kayıpları meydana getirmiştir. Hem iletişimdeki veri kaybını en aza indiren hem de kullanışlılığı ile herkes tarafından tercih edilen araçlar bir adım öne çıksa da güvenlik ve veri mahremiyeti endişeleri, kurumları ve insanları yerli ve iyi test edilmiş araçları araştırmaya yönlendirmiştir. Ülkemizde bu ihtiyacı karşılamak üzere, salgın sürecinde yirmiye yakın video konferans aracı ihtiyaçlara uygun şekilde güncellenmiş veya en baştan geliştirilmiştir. Bu araçların genel ihtiyaca uygunluğunun belirlenmesi amacıyla kapsamlı bir test çalışması yürütülmüş ve test sonuçları ilgili kurumlarla paylaşılmıştır. Bu test sürecinde, tüm araçların WebRTC altyapısı kullandığı görülmüş ve bu doğrultuda işlevsel özellikleri test edebilmek için standart bir test tasarımı yapmak mümkün olmuştur. Ancak bu testlerde video ve ses kalitesi sübjektif olarak gözlem yoluyla değerlendirilmiş bu ise tamamen otomatik bir test otomasyonu yapılmasını imkansız kılmıştır. Video ve ses kalitesinin sayısal yöntemler kullanılarak hızlı ve pratik bir şekilde ölçülmesi ve bu işlemin test otomasyonuna dahil edilmesi bu projenin ana hedefi olacaktır. WebRTC’nin ana geliştirme amacı video konferans ürünleri olmakla birlikte dronların izlenmesi ve kontrolü gibi ekstrem durumlarda da kullanılabilmektedir (Kilic vd., 2024). Bu nedenle video ve ses kalitesinin yüksek tutulması büyük önem arz etmektedir. 
>
>WebRTC, video, ses, metin gibi çeşitli türde verileri etkin bir şekilde paylaşabilmek için geliştirilmiş bir Javascript kütüphanesidir ve Selenium gibi test otomasyonu araçları ile pratik olarak test edilmektedir (Suciu vd., 2020)(García vd., 2020). Test otomasyonu, yapılması zaman alan ve insan faktörünün getirdiği riskleri içeren manuel yazılım testlerini, bilgisayar yardımı ile otomatik olarak gerçekleştirmeyi amaçlar (Şahin Gebizli vd., 2018) otomasyon için hazırlanan test senaryoları istenilen zamanda ve istenilen sayıda işletilerek, yazılım üzerinde sürümler arasında oluşacak farklar objektif bir değerlendirmeye tabi tutulduğu gibi, yorgunluk, tecrübe eksikliği, ön yargı, eğitim farklılıkları, yeterli süre ayıramama ve ihmal gibi insan faktörü dezavantajları elimine edilir. Test otomasyonu özelikle form doldurma gibi yapılması zaman alan rutin işlemlerin testleri için çok faydalı olsa da testlerin tamamının otomatikleştirilmesi de mümkün olmayabilir. Video konferans ürünlerinde ise video ve sesin alıcılara yeterli kalitede ulaşıp ulaşmadığı ve ses ve görüntüde kayıp olup olmadığının test otomasyonu ile sınanmasında güçlükler yaşanmaktadır. 
>
>WebRTC tabanlı video konferans ürünlerinin testlerine yönelik literatür incelendiğinde çalışmaların ağırlıklı olarak performans, ağ ve yük testlerine yönelik olduğu gözlenmektedir (Seker & Kilinc, 2021)(Garcia, Lopez-Fernandez, vd., 2016). Bu testler video ve ses kalitesinin ölçülmesi ve hatta test otomasyonunu da içerir (Garcia vd., 2017). (Garcia, Gallego, vd., 2016). NUBOMEDIA adlı Avrupa Birliği projesinde, açık kaynaklı bir WebRTC sunucusu olan Kurento üzerinde kullanıcı deneyiminin ve ağdaki gecikmenin ölçülmesi üzerinde çalışmışlardır. Bu çalışmada sentetik bir test videosu üzerindeki sayaç ve zaman bilgisi görüntü işleme (karakter tespiti) yöntemleri kullanılarak internet kaynaklı gecikmenin ve videodan alınan anlık görüntülerin yapısal benzerlik oranının karşılaştırılmasından faydalanılmıştır. İki görüntünün benzerlik oranını tespit etmek amacıyla Yapısal Benzerlik İndeksi (Structural Similarity Index -SSIM) kullanılmıştır (Wang vd., 2004) (Ke Gu vd., 2013). Video görüntülerinin kalite ve benzerlik analizi için benzer şekilde geliştirilen metrikler ve modeller mevcuttur (Liu vd., 2013) . Netfix’in geliştirdiği ve karşılaştırmaları orijinal videoyu referans alarak yapan Video Multimethod Assessment Fusion (VMAF) (Netflix, 2016), PEVQ(Performance Evaluation of Video Quality) (Mello vd., 2017), yapay sinir ağı tabanlı öğrenme ile referans video kullanmadan videodaki bozulmaları tespit ettiğini iddia eden NARVAL(Neural network-based Aggregation of no-Reference metrics for Video quAlity evaLuation) (Lemesle vd., 2019) bu metriklere örnek gösterilebilir. Ayrıca benzer şekilde sesteki bozulmaları incelemek için kullanılan metriklerden en bilineni PESQ (Performance Evaluation of Sound Quality) metriğidir (Rix vd., 2001). Literatürdeki bu çalışmalar, WebRTC gibi kullanıcı deneyiminin öne çıktığı ortamlarda insan faktörünü tamamen ortadan kaldırıp testleri otomatikleştirmeyi sağlayan önemli katkılar sağlasa da aşağıdaki nedenlerden dolayı araştırmanın geliştirilmesi ve yerli ürünlerin testleri için ihtiyaçlarımıza uygun olarak ele alınması gerekmektedir.
>- Önerilen bu yöntemler test edilen yazılımın koduna ve sistemine müdahale etmeyi gerektirmektedir. 
>- Testler hareketli insan ve ortam içeren videolarda değil, test amaçlı oluşturulan ve az renk ve detay içeren sentetik videolarda gerçekleştirilmiştir. 
>- Bazı çalışmalar dağıtık bir ortamda değil tek bir makinada çok sayıda tarayıcı açılarak gerçekleştirilmiştir. 
>- Belirli bir kullanıcı sayısına kadar neredeyse orijinal görüntünün aynısını tüm kullanıcılara sorunsuz ilettiği ama o eşiğe gelince birden tüm kullanıcılarda görüntü kaybı yaşandığı gibi gerçekçi olmayan sonuçlar elde edilmiştir.
>- Bazı metriklerin karşılaştırılması canlı deneylerde değil görüntü veritabanları üzerinde gerçekleştirilmiştir. 
>- Tercih edilen ve bazıları ticarileşmiş medya sunucusu, işletim sistemi ve platform bağımlılıklarından dolayı bazı çözümlerden bire bir faydalanılabilmesi mümkün olmamaktadır. 
>
>Önerdiğimiz bu proje ile WebRTC protokolüne uygun olarak geliştirilmiş herhangi bir video konferans aracının, video ve ses kalitesindeki değişimi değerlendirmek de dahil olmak üzere işlevsel özelliklerini, insan müdahalesi olmadan baştan başa gerçekleştirecek bir test aracı geliştirilecektir. Bu aracı geliştirirken dört önemli araştırma sorusuna cevap aranacaktır:
>1. Video ve sesteki senkronizasyon nasıl sağlanacaktır? Zaman damgası nasıl basılacak ve nasıl kontrol edilecektir?
>2. Video ve ses benzerlik analizi için tam otomatik bir test düzeneğinde kullanılabilecek işlem gücü gereksinimi, hız ve doğruluk açısından en uygun benzerlik analiz yöntemleri hangileridir?
>3. Performans testlerinde video ve sesteki gecikmeler için uygulanabilecek makul geçti kaldı kriterleri (süre olarak) nelerdir?
>4. Performans testlerinde video ve sesteki benzerlik karşılaştırması için uygulanabilecek makul geçti/kaldı kriterleri (benzerlik oranı) nelerdir? Gerçek zamanlı testlerde benzerlik oranında ne kadarlık bir düşüş tolere edilmelidir?
>
>Özet olarak, önerdiğimiz bu proje ile video konferans ürünleri test edilirken, test otomasyonuna sadece bir butona basılması, bir metnin kopyalanması gibi işlevsel özelliklerin değil görüntü ve seslerin karşı tarafta bozulma oranının da hızlı ve pratik bir şekilde ölçülerek testin baştan başa otomatikleştirilmesi, aynı anda çok sayıda video konferans aracının farklı zamanlarda, farklı platform ve farklı sunucu konfigürasyonlarında tekrar tekrar test edilebilmesine olanak sağlanması amaçlanmaktadır. Projemizin çıktısı, diğer çalışmaların aksine, sadece görüntünün ya da sesin kaybolup kaybolmaması ile değil yüklü testlerdeki (kaliteli video ve ses aktarımı) kalite düşme oranının sayısallaştırılmasıdır. Çünkü bazı video konferans ürünleri görüntü ya da sesi iletiyor ve testleri geçiyor gibi görünse de bulanıklık, cızırtı, kesiklik vb. nedenlerden dolayı kullanıcı deneyimi açısından olumlu puanlar alamamaktadır. Kullanıcı deneyimini onun yerine pratik bir şekilde ölçebilmek bu çalışmanın en temel amacıdır ve çalışma başarılı olursa farklı video ve ses konfigürasyonları çok sayıda sanal kullanıcı yüklenerek istenilen zaman aralığında test altındaki ürün üzerinde sınanabilecektir. 
>
>Ülkemizde yerli ve güvenli yazılımlara her zaman ihtiyaç olacaktır. Video konferans ürünleri de sadece insanların değil, kurumların da iletişiminde önemli yer tutmakta ve video konferans ürünleri pazarının büyüyeceği öngörülmektedir. Bu ürünleri insan faktörünün olumsuz etkilerini devre dışı bırakarak, standart ve eksiksiz şekilde test edecek ve raporlayacak test sistemine ihtiyaç olacaktır. Bu projede WebRTC altyapısı kullanılarak geliştirilmiş ürünlerin, işlevsellik ve performans testlerinin tam otomatik olarak gerçekleştirilmesini sağlayacak bir sistemin oluşturulması ve devreye alınması amaçlanmaktadır. Bu sistem, dışa bağımlılığı azaltacak ve ürününü test etmek isteyen firma ve kurumlara güvenli bir ortam sağlayacaktır.  

## 1.2. Amaç ve Hedefler

Proje önerisinin amacı ve hedefleri açık, ölçülebilir, gerçekçi ve proje süresince ulaşılabilir nitelikte olacak şekilde yazılır.

>Salgın ile birlikte evden çalışma ve eğitim ihtiyacı zirve yapınca tüm dünyada olduğu gibi ülkemizde de pratik, güvenli ve kullanılabilir ürünler araştırılmaya ve karşılaştırılmaya başlanmıştır. T.C. Cumhurbaşkanlığı Dijital Dönüşüm Ofisi koordinatörlüğünde aksiyon alınarak TÜBİTAK BİLGEM’de yerli video konferans ürünlerinin işlevsellik, güvenlik, kullanılabilirlik ve performans testleri gerçekleştirilmiştir. Hızlı gelişen ve tamamlanan bu test sürecinde zaman kısıtı nedeniyle gerçekleştirilemeyen ve AR-GE çalışması gerektiren bazı hususlar ileride yapılmak üzere not edilmiştir (Öztürk vd., 2021). Video konferans ürünlerinin objektif ve otomatik olarak test edilmesi her zaman bir ihtiyaç olacaktır. Hızlı bir destek ile bu ihtiyacın karşılanmasına yönelik çalışmaların tamamlanması planlanmaktadır. 
>
>Video konferans araçlarını test etmek aşağıdaki özelliklerinden dolayı çok sayıda zorluk içermektedir (Garcia ve ark., 2017):
>1. Bağlanmak için kullanılan cihazlar (bilgisayar, telefon, VoIP cihazı vb.), yazılımlar (masaüstü yazılım, web tarayıcı, mobil uygulama vb.) ve ağlar(bulut, VPN vb.) farklılık gösterir.
>2. Dağıtık, karmaşık ve heterojen sistemler üzerinde çalışırlar.
>3. Çok sayıda işlevsel (ses ve görüntü aktarımı, farklı rollerde kullanıcılar, beyaz tahta, kayıt, mesajlaşma vb.) ve işlevsel olmayan (kullanılabilirlik, performans, güvenlik vb.) özelliğe sahip olması beklenir.
>
>WebRTC testleri servis kalitesi ve deneyim kalitesi temelli olarak iki türde gerçekleştirilir. Servis kalitesi testlerinde bant genişliği ve gecikme gibi somut, deterministik ölçümlerden faydalanılır. Servis kalitesi testleri verinin aktarım hızı, sinyal genliği, bant genişliği gibi parametreleri içerir ancak görüntü ve sesteki bozulmaları tam olarak anlayabilmede tek başına yeterli değildir. Örneğin, veri; tam, eksiksiz ve zamanında gönderilmiş olabilir ancak arayüz yazılımdaki bir hata yüzünden yanlış gösteriliyor olabilir. Diğer bir deyişle TV yayınında sorun yoksa ama LCD panel bozulmuşsa görüntünün olmaması servis kalitesi testleri ile anlaşılamayabilir. 
>
>Deneyim kalitesi (Quality of Experience - QoE) testlerinde ise görüntünün benzerlik analizi, ses kalitesinin katılımcılar tarafından anketle değerlendirilmesi gibi sezgiye, tecrübeye ve öznel yargıya dayalı yöntemler kullanıldığı görülmektedir (Brunnström vd, 2013) (Ben Letaifa vd., 2017). Deneyim kalitesinin ölçümü için standartlaşmış ve nesnelliği artırmaya yönelik anketler, Likert ölçekleri ve Delphi tekniği gibi yöntemler kullanılmaktadır. Ancak bir konuda alan uzmanı bulmak ve ondan gerekli bilgileri alabilmek, yetersiz veri olduğunda yargıya varabilmek zorlayıcı ve güvenilir bulunmayan bir konudur. Video ve ses odaklı WebRTC ürünleri için önerilebilecek olgunlaşmış, standart bir test yöntemi yoktur. Literatürdeki testlerin çoğu sistemin geliştiricisi tarafından koda müdahale edilerek ya da veri girilerek gerçekleştirilmiştir (Garcia vd., 2017) (Taheri vd., 2015). Test otomasyondan alınacak faydanın artırılabilmesi için bilgisayarın görüntü ve sesteki farklılıkları analiz ederek bozulma ve kayıp miktarını sayısal olarak ifade edebileceği bir yönteme ihtiyaç vardır. 
>
>Projenin temel amacı WebRTC kütüphanesi kullanılarak geliştirilen video konferans ürünlerinin işlevsellik testlerinin ve deneyim kalitesine yönelik incelemelerinin, tam otomatik olarak yapılması ve raporlanmasıdır. Bu proje tamamlandığında ortaya çıkacak test aracı, Selenium yardımı ile test betikleri oluşturulmuş bir video konferans ürününü, gerçek test katılımcısı gerekmeden istenildiği zaman, istenildiği miktarda, istenilen ses ve video verisi ile test edebilmeyi sağlayacaktır. Kısaca bu proje, salgın sürecinde kısmen manuel olarak gerçekleştirilen deneyim kalitesi incelemelerini, aradan insan faktörünü çıkararak objektif ve standart hale getirecektir. Bu ana amaç çerçevesinde hedefleri aşağıdaki gibi sıralanabilir:
>1) WebRTC testleri için herkesin kullanımına açık bir web tabanlı bir test ara yüzünü hizmete almak
>2) WebRTC teknolojisi ve testleri konusunda bir yüksek lisans tezinin tamamlanmasını sağlamak
>3) Görüntü ve ses kalitesinin değerlendirilmesi konusunda elde edilecek deneyimleri akademik çıktıya (makale ve konferans sunumları) dönüştürmek
>
>Projede gerçekleştirilecek temel faaliyetler aşağıdaki şekilde listelenmiştir:
>
>1. Projenin gerekli teçhizat ve iş gücü ihtiyacının sağlanabilmesi, zamanında test ve teslimat yapabilmek için etkin proje yönetiminin yapılması
>2. Üzerinde testlerin ve denemelerin yapılacağı sunucunun kurulması ve konfigürasyonunun yapılması
>3. SSIM, PESQ, PVQM, PSQM gibi görüntü ve ses karşılaştırma modellerinin incelenmesi ve test yazılımına uyarlanması
>4. Raporlama amacıyla karşılaştırma skoru algoritmasının oluşturulması ve test bilgilerinin veritabanında tutulması, skorlamada kullanılan katsayıların periyodik olarak kalibrasyonu
>5. Güvenilir, kullanılabilir, performanslı bir WebRTC test aracının işlevlerini yerine getirdiğinin tespiti için sistematik bir entegrasyon ve test uygulanması  

# 2. YÖNTEM

Projede uygulanacak yöntem ve araştırma teknikleri (veri toplama araçları ve analiz yöntemleri dahil) ilgili literatüre atıf yapılarak açıklanır. Yöntem ve tekniklerin projede öngörülen amaç ve hedeflere ulaşmaya elverişli olduğu ortaya konulur.

Yöntem bölümünün araştırmanın tasarımını, bağımlı ve bağımsız değişkenleri ve istatistiksel yöntemleri kapsaması gerekir. Proje önerisinde herhangi bir ön çalışma veya fizibilite yapıldıysa bunların sunulması beklenir. Yöntemlerin iş paketleri ile ilişkilendirilmesi gerekir.

>WebRTC API üç ana kategoriye ayrılır :
>1. GetUserMedia: Kamera, mikrofon ve ekran gibi kullanıcı aygıtlarına erişimi sağlar, erişim izin ve yetkilerini düzenler.
>2. DataChannel: Uç noktalar arasında veri iletimini (kişiye özel mesaj, dosya paylaşımı vb.) sağlar.
>3. RTCPeerConnection: İki Web-RTC uç noktası arasında iletişim kanalı kurarak ortam içeriklerinin aktarımını sağlar. Ayrıca ortam içerik kalitesini artırmaya yönelik bazı kontroller gerçekleştirir.
>
>WebRTC ürünlerinin testleri için Selenium Web Driver test otomasyonu aracından etkin biçimde faydalanılabilmektedir. Video konferans ürünlerinin arayüzleri Selenium ile kolayca kontrol edilebilecek şekilde tasarlanmaktadır. Ancak konu, video ve sesin iletimindeki gecikme ve bozulmaları tespit etmeye geldiğinde otomasyon işe yaramamakta deneyim kalitesinin değerlendirilmesi gerekmektedir (García vd., 2019) (Garcia ve ark., 2019). (Garcia vd., 2017), NUBOMEDIA adını verdikleri bir test altyapısı geliştirerek Google Chrome'un test amacıyla sunduğu videoyu ve videodaki zamanlayıcıyı kullanarak video iletimindeki gecikmeyi ve video kalitesini ölçmeye çalışmışlardır. Bu amaçla görüntü işleme ve zaman bilgisinin videodan alınabilmesi için çalışma yapılmıştır. Ayrıca alıcı ve göndericideki görüntünün eşzamanlı olarak çekilip video kalitesinin karşılaştırılması ve ses kalitesinin değerlendirilmesi için anket uygulanması tekniklerini de önermişlerdir. 
>
>(García vd., 2020) performansı otomatik yolla test etmek için uygun bir araç bulunmadığına vurgu yapmış ve bağlantı kalitesi ile ilintili servis kalitesi göstergeleri yanında ortam içeriği kalitesi ile ilintili deneyim kalitesi göstergelerini de dikkate alan bir yöntem önermişlerdir. Bu yönteme göre test amacıyla kullanılan etmenlerin yayınladığı görüntü ve seslerin karşı taraftaki değişim oranı, PVQM (Perceptual Video Quality Measure) ve MOS (Mean Opinion Score) (Viswanathan & Viswanathan, 2005) gibi karşılaştırma algoritmaları ile ölçeklendirilmiştir (Hekstra vd., 2002). 
>
>(Taheri vd., 2015) ise WebRTCBench adını verdikleri altyapı üzerinde daha çok servis kalitesi odaklı bir çalışma yürütmüş, video çözünürlüğü, çerçeve sayısı gibi metrikleri belirleyerek farklı platform ve farklı ağlarda iletimin performansının nasıl değiştiğini sorgulamışlardır. 
>
>Görüntü benzerliği için kullanılan en pratik yöntemlerden birisi SSIM’dir (Wang vd., 2004). Bu yönteme göre analiz 3 aşamada gerçekleştirilir. Pikseller arasında önce parlaklık (luminance), sonra keskinlik (contrast) ve sonra yapısallık (structure) karşılaştırılarak orijinal resimle benzerlik oranı hesaplanır. Tüm pikseller için yapılan karşılaştırmanın ortalaması -1 ile +1 arasında (genellikle 0 ile 1 arasında) değişir. Algoritmanın testi orijinal resmin kendisi ile karşılaştırılması ile yapılabilir ve +1.0 sonucu çıkıyorsa algoritma beklendiği şekilde çalışıyor anlamı çıkarılır. Şekil 1’de bu çalışmada kullandığı örnek sunulmuştur. Orijinal Einstein fotoğrafı birtakım bozucu etkiler uygulanmış kopyaları ile karşılaştırılmıştır. SSIM modeli uygulaması kolay ve çeşitli alanlarda pratik olarak kullanılabilen etkin bir yöntemdir; örneğin (Peng vd., 2020) SSIM’i ilaç dozajını ölçebilmek için kullanmışlardır. 
>
><img width="927" height="722" alt="Şekil 1. SSIM Görüntü Karşılaştırma Örnekleri" src="https://github.com/user-attachments/assets/815b91e3-0674-489e-bab2-71abf7f0fdf1" /><div align="center"><sup>Şekil 1. SSIM Görüntü Karşılaştırma Örnekleri</sup></div>
>
>Ses benzerliği analizi için en bilinen yöntemlerden birisi ise Perceptual Evaluation of Sound Quality (PESQ) yöntemidir (Rix & Hollier, 2000). Bu yöntem telefondaki ses bozulmalarının tespiti için ses uzmanlarının parametrelere göre eşleştirme yaptığı görsel katman ile servis kalitesi parametrelerini birleştirmek amacıyla geliştirilmiştir. Ses kalitesine etki eden en önemli faktörler olan sesin keskinliği, sesin gücü, arkaplan sesleri, gecikme, kırpma ve dış müdahaleleri dikkate alır. Şekil 2’de ticari bir PESQ uygulamasının 1.0 ilâ 5.0 arasında notlandırdığı iki örnekte ses histogramları sunulmuştur (https://www.spearline.com/blog/whatis-pesq/). Ses benzerliği analizi için insanların katıldığı testler de gerçekleştirilmiştir ancak otomasyon açısından çalışmamızda uygulanabilirliği mümkün gözükmemektedir (Mühl vd., 2018) (Hu vd., 2022).
>
><div align="center"><img width="983" height="270" alt="image" src="https://github.com/user-attachments/assets/175b06f2-f835-4cbd-8a37-6f3dc0fae2a6" /><br /><img width="972" height="260" alt="image" src="https://github.com/user-attachments/assets/dc1222ec-a481-442d-b0e4-5a5c9097a8ff" /><br /><sup style="text-align:center">Şekil 2. PESQ Ses Karşılaştırma Örnekleri</sup></div>
>
>Adı geçen yöntemlerin projede geliştirilecek yazılıma nasıl uyarlanacağı iş paketleri kırılımı ile anlatılacaktır. Ayrıca insan kaynakları ve makina/teçhizat gereksinimlerine de değinilecektir.
>
>## İŞ PAKETLERİ: 
>
>### İŞ PAKETİ 1: WebRTC Test Sunucu Altyapısının Geliştirilmesi: 
>
>Video konferans ürünlerinin testleri, video, ses ve metin gibi farklı türde verileri içermesinden dolayı standart bir şekilde yapılamamakta, tasdik testleri (assertion testing) kısmen tatbik edilebilmektedir. Video ve sesteki bozulmalar ve kayıplar servis kalitesi ölçümleri ile tespit edilebilse de bunun son kullanıcıya yansıması üründen ürüne değişebilmektedir. Test eden son kullanıcı, ses ve görüntüdeki kayıpları birtakım kontrol listeleri yardımıyla yaklaşık bir sayısal büyüklük olarak ifade edebilmektedir. Ancak insan faktörünün ve kullanılan ekipman farklılıklarının getirdiği dezavantajlar (zaman kısıtı, yorgunluk, mikrofon kalitesi, internet hızı vb.) bu ölçümün nesnelliğini sorgulanır hale getirmektedir.
>
>Bu projede bu kısıtları aşabilmek ve ürünler hakkında nesnel yargı oluşturmaya yardımcı olabilmek için, bir test aracı geliştirilecektir. Bu araç, herhangi bir insan müdahalesi ya da eforu gerekmeden WebRTC kütüphanesi ile geliştirilmiş bir video konferans aracının işlevsellik, performans ve deneyim kalitesi testlerini gerçekleştirecektir. Bu proje ile bu iş paketi kapsamında proje ekibinin mevcut yetenekleri ile kazanmayı planladığı yetenekleri Tablo 1’de listelenmiştir. 
>
>Tablo 1: WebRTC Test Aracı, Mevcut ve Planlanan Yetenekler
>
>
><table><thead>
>  <tr>
>    <th></th>
>    <th><span>Özellik/Yetenek</span></th>
>    <th><span>Mevcut</span></th>
>    <th><span>Planlanan</span></th>
>  </tr></thead>
><tbody>
>  <tr>
>    <td>1</td>
>    <td>Web kamerası ve mikrofon başlangıç ayarlarının belirlenmesi ve her testte sorulmasının aktive/deaktive edilmesinin sağlanması</td>
>    <td style="text-align:center;">VAR</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td>2</td>
>    <td>Güvenlik ve sertifika ayarlarının otomatik yapılarak teste gereksiz müdahalenin önlenmesi</td>
>    <td style="text-align:center;">VAR</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td>3</td>
>    <td>Test amaçlı oluşturulan çeşitli videoların çok-katılımcılı (multi-party) testlerde kullanılabilmesi</td>
>    <td style="text-align:center;">VAR</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td>4</td>
>    <td>Belirlenen işlevsel test senaryolarının (seçilen katılımcının mikrofonu açma/kapatma, seçilen katılımcıya mesaj atma, gösterim modları vb.) otomatik işletimi ve raporlanması</td>
>    <td style="text-align:center;">KISMEN<br>(Bazı<br>testler<br>manuel<br>yapılıyor)</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td>5</td>
>    <td>Belirlenen performans test senaryolarının (yük testi, sunucu kaynak kullanımı vb.) otomatik işletimi ve raporlanması</td>
>    <td style="text-align:center;">KISMEN (Bazı testler<br>manuel<br>yapılıyor)</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td>6</td>
>    <td>Video ve sesteki bozulma, gecikme ve kayıpların otomatik tespiti ve raporlanması</td>
>    <td style="text-align:center;">YOK (Manuel yapılıyor)</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
>  <tr>
>    <td style="text-align:center;">7</td>
>    <td style="text-align:center;">İlgili kurumlarla paylaşmak için otomatik karşılaştırma skorlarının (benchmark) oluşturulması ve revizyon (tarih, sürüm vb.) bilgileri ile veritabanında saklanması</td>
>    <td style="text-align:center;">YOK</td>
>    <td style="text-align:center;">VAR</td>
>  </tr>
></tbody></table>
>
>Mevcutta geliştirilmiş olan test aracının yönetim arayüzünden bir kesit Şekil 3a’da yer almaktadır. Bu arayüz ile gerçek katılımcı mikrofon ve kamerasını kullanarak katılabilir, Google Chrome test videosu kullanılabilir (Şekil 3b) ya da önceden hazırlanmış y4m uzantılı video dosyaları yayına gönderilebilir. Bu ayarlar hem yeni oda oluşturmada hem de oluşturulmuş bir sohbet odasına  6 1002ABF-01 Güncelleme Tarihi: 01/01/2024 ziyaretçi olarak katılmakta kullanılabilir.
>
><div align="center"><img width="701" height="531" alt="image" src="https://github.com/user-attachments/assets/882bfe24-5a76-47d1-81f0-6af669a00e9c" /><br /><sup>Şekil 3. a) WebRTC Testleri İçin Geliştirilen Oda Başlatma Aracı b) Google Chrome web tarayıcısının test amaçlı videosu</sup></div>
>
>Test aracı daha önceden hazırlanmış y4m uzantılı videoları çevrimsel olarak oynatabilmektedir. Bu ise gerçek katılımcı olmadığı durumda, gerçekçi veri üretebilmek açısından faydalı olmakta ve testlerin güvenilirliğini artırmaktadır. Şekil 4’de testlerden iki enstantane görünmektedir. Şekil 4a’daki durumda, sol üstteki katılımcı gerçek katılımcı olup, diğerleri daha önceden hazırlanmış videolardır. Şekil 4b’de ise performans testi amacıyla testi yöneten gerçek kişi, 24 adet sanal makinadan aynı videoyu otomatik olarak başlatmıştır. Burada bazı görüntü kayıpları olduğu görülmektedir. Bu kayıpların otomatik olarak tespiti, yazılıma İş Paketi 3 kapsamında eklenecek özelllikler ile otomatik olarak gerçekleştirilebilecek ve insan görüşü devreden çıkarılabilecektir.
>
><div align="center"><img width="1600" height="674" alt="image" src="https://github.com/user-attachments/assets/d7c444df-3392-4cd8-bf66-8e91b0bf12c8" /><br /><img width="812" height="476" alt="image" src="https://github.com/user-attachments/assets/a506fbaa-d37e-4d38-ac32-27cc5e69d635" /><br /><sup>Şekil 4. Önceden oluşturulmuş videoların gerçek katılımcı yerine kullanılması a) Farklı videolar ile az sayıda sanal katılımcı b) Aynı video ile çok sayıda sanal katılımcı</sup></div>
>
> #### İş Paketi 1’in Çıktısı:
>Herhangi bir video konferans ürününü tam otomatik test edebilmek için geliştirilecek ?bir test otomasyon altyapısı ve bu otomasyonu test edebilmek için bir video konferans aracı geliştirilmesi.
>
>### İŞ PAKETİ 2: Video ve Ses Benzerlik Analizi
>
>İş Paketi 1 başlığı altında Tablo 1’de listelenen yeni geliştirilecek özelliklerden katma değeri en yüksek olanı, 6 nolu “Video vesesteki bozulma, gecikme ve kayıpların otomatik tespiti ve raporlanması” maddesidir. Bu madde kapsamında, oluşturulacak test videolarının kalitesi literatürdeki video ve ses kalitesi ölçme yöntemlerden faydalanarak hem yayınlayıcı ve hem de alıcı tarafında ölçülecektir. Bu ölçme iki açıdan olacaktır:
>
>1. Gecikme (Latency): Video görüntüsüne harf, numara ya da zaman dalgası gibi bir işaret eklenecek, yayıncı ve alıcı taraftaki işaretler karşılaştırılacaktır. Örneğin, Şekil 5’teki resimde VHS formatında bir video kaydı örneği bulunmaktadır. Yazılım Java’da geliştirileceği için Java ile uyumlu pratik bir çözüm araştırılacaktır. Günümüzde OpenCV gibi görüntü işleme ve Tesseract gibi nesne/karakter tanımlama yazılımları ile zaman etiketleri videodan kolayca temin edilebilmektedir.
><div align="center"><img width="415" height="333" alt="image" align="center" src="https://github.com/user-attachments/assets/3ee1cdb0-1bc9-4866-bfa0-f598fd2fc913" /><br /><sup>Şekil 5. Tarih ve zaman damgalı VHS video örneği</sup></div>
>
>2. Video kalitesi: Videodan alınacak anlık görüntülerin yapısal kalitesinin ölçümü mümkündür. Bu amaçla geliştirilmiş Structural Similarity Index (SSIM) algoritmasının kullanımı pratik olduğundan tercih edilecektir. Herhangi iki video karesi, SSIM yöntemi ile kıyaslanarak görüntüdeki bozulma miktarı tespit edilecektir. Burada ana amaç, yeni ve daha iyi bir SSIM algoritması geliştirmek değildir, mevcut çözümlerin incelenmesi, denenmesi ve gerçekleştirilecek testlere en uygun olanının adapte edilmesidir. Örneğin; resmi bir bütün olarak değil de lokal olarak incelediklerinin ortalamasını olarak inceleyen Mean Structural Similarity Index (MSSIM) daha doğru sonuç verecek gözükmektedir. Bu proje sonunda, denenmiş alternatif çözümlerin karşılaştırmasını sunan bir yayın çıkarılması da hedeflenmektedir. <br/> <br/> Projede uygulanacak SSIM testlerinde video konferans aracı, bant genişliğini optimize etmek amacıyla yayıncı tarafında da görüntüyü orijinal haliyle sunamayabilir. Bu nedenle orijinal resim web kamerasının fotoğraf çekme özelliği ile yakaladığı yüksek çözünürlüklü görüntü olacaktır. Bu sayede test edilen yazılımın yayınlamadan önce orijinal görüntüyü ne kadar bozduğu da tespit edilecektir.
>
>3. Ses Kalitesi: Videoda olduğu gibi ses benzerliği ölçen yöntemler mevcuttur. PESQ yönteminin pratik uygulamaları denenerek araca uyarlanacaktır. 
>
>Gecikme ve kalite testleri karşılıklı olarak birbirini destekler şekilde planlanacaktır. Örneğin, gecikme testinde iki tarafta da aynı zaman damgasındaki görüntülerin SSIM değerleri karşılaştırılacaktır. Ya da tam tersi şekilde SSIM değerleri birbirine çok yakın olduğu durumda zaman damgası, gecikme değerindeki zaman damgası ile karşılaştırılarak doğrulama yapılacaktır.
>
>Bu projede planlanan test kurgusu aşağıdaki gibi olacak, uygulama esnasında gerekirse güncellenecektir:
>
>1) Test Yönetim Arayüzü çoklu katılım testleri için güncellenecektir. Testi başlatmak için kullanılacak sunucu arayüzü, karşı taraftaki arayüzlere test başlatma, durdurma gibi işaretleri verecektir. Bu amaçla web servis temelli bir yapıya geçilecek ve arayüz web tabanlı olacaktır. Selenium Grid bu amaçla geliştirilmiş bir uygulama olup karşı tarafta testleri yönetmeye, diğer düğümlerden verileri toplayıp konsolide etmeye yardımcı olmaktadır. Bu bir hızlı destek projesi olacağı için ilk etapta yüksek sayıda kullanıcı sayısına ulaşmak amaçlanmamaktadır. 10 tam yüklü (yüksek kaliteli kamera görüntüsü ve yüksek kaliteli ses) sanal kullanıcının tam otomatik teste katılabilmesi ilk aşamada hedeflenen kapasitedir.
>2) Çeşitli çözünürlüklerde (4K, 2K, 1080p, 720p, 480p) videolar hazırlanıp videolara  belirli periyotlarla beliren ve görüntü işleme teknikleriyle kolayca ayırt edilebilecek filigranlar ya da zaman damgaları eklenecektir.
>3) Oda başlatıldığında, test katılımcılarının odaya girdiği bilgisi (Acknowledgement) geldiğinde, test yönetim arayüzü aracılığı ile görüntü benzerlik analizi başlatılacaktır. Bu amaçla yayınlanan görüntüdeki filigranın çıktığı anlarda zaman bilgisi loglanacaktır. Ayrıca ekran görüntüsü resim olarak kaydedilecektir. Benzer işlem alıcı tarafta da yapılacaktır.
>4) Aynı zaman damgasındaki görüntüler SSIM yöntemiyle yapılacak hesaplama sonucuna göre karşılaştırılacaktır. Skor - 1.0 ile +1.0 arasında değişecektir. +1.0 olan görüntüler birbirinin tamamen aynısı olup yayınlayıcı ve alıcı arasında mükemmel bir iletim olduğu anlamını taşıyacaktır.
>5) Yayınlayıcı ve alıcı arasındaki zaman farkı ise filigranların arasındaki zaman ölçülerek bulunacaktır. Kısaca beklenen gecikmenin olabildiğince az, SSIM skorunun ise 1.0’a yakın olmasıdır.
>6) 2 ila 5. Adımda yapılanlar ses dosyaları ile seçilen PESQ uygulaması tekrar >edilecektir.
>
>### İŞ PAKETİ 3: Karşılaştırma Skoru Oluşturma (Benchmarking)
>
>Gecikme ve video kalitesinin sayısal bir değer olarak ifade edilebilmesi, test sonuçları ve araç karşılaştırmalarının daha nesnel yapılabilmesini sağlayacaktır. Eğer testlerdeki geçti/kaldı durumları, gecikme süresi, videodaki bozulma her araç için standart bir şekilde otomatik olarak notlandırılabilirse, bu ürünlerin potansiyel müşterileri olan kurumlar kendi kriterlerine göre uygun aracı seçebileceklerdir. Örneğin, bazı kurumlar az sayıdaki katılımcıyla yüksek kaliteli toplantılar veya kayıtlar yapmak isteyebilir, bazıları ise yüzlerce katılımcıya kayıpsız bir webinar deneyimi yaşatmak isteyebilir. Bazı kurumların istediği ise eğitim verdiği sınıfta güvenliğin sağlanması ve mahremiyetin korunması olabilir. 
>
>Geliştirilecek olan aracın sunduğu raporlar ile hem ürün sahipleri teknik bilgilere sahip olacak hem de karar vericiler yönetimsel düzeyde bir özete erişebileceklerdir. 
>
>Bu projede pilot bir uygulama geliştirilecek onun üzerinde gerçekleştirilecek testlerle 3 kategoride (toplantı, eğitim, webinar) ayrı ayrı skorları oluşturulacaktır. Skor için kullanılacak bileşenlerin seçimi, kriter kümesinin geçerlenmesi, kriterlerin ağırlıklandırılması ve herkes tarafından anlaşılacak ve kabul görecek objektif bir skor üretimi bir araştırma konusu olup bu projenin en önemli katkılarından biri olacaktır. Özet olarak bu iş paketinin temel amacı video konferans araçlarının standardizasyonuna yönelik araştırma yapmak olacaktır
>
>## İNSAN KAYNAKLARI: 
>
>İş Paketi 1 başlığı altında Tablo 1’de listelenen yeni geliştirilecek özelliklerin yazılıma uyarlanmasından ve projenin hedeflerini gerçekleştirmesinden Proje yürütücüsü sorumlu olacaktır. 
>
>Görüntü işleme, video ve ses benzerlik analizi konularında danışmandan destek alınacaktır. Test videolarının üretilmesi, Selenium Grid ile test yüklerinin dağıtılması, uçtan uca test otomasyonunun geliştirilmesi, test senaryolarının araca uygulanması ve tüm bu sürecin testlerinden bir lisans öğrencisi sorumlu olacaktır. Öğrenciye daha önceki çalışmalar aktarılacak ve ihtiyaçlara göre uyarlanması beklenecektir. 
>
>Görüntü ve ses benzerlik ve kalite analizlerini yapan algoritma ve yöntemlerin araştırılması, örnek görüntü ve seslerle denenmesi, test otomasyon sistemine uyarlanması bir yüksek lisans bursiyerinin sorumluluğunda olacaktır. Bu bursiyerimiz ayrıca video konferans ürünlerinin karşılaştırılmasına yardımcı olmak amacıyla gereksinim duyulacak kriter setini oluşturmak için literatürü tarayacak ve endüstrideki uygulamaları araştıracaktır.
> 
>İki bursiyer de proje süresi boyunca (5 ay) projeye katkı sağlayacaktır.
>
>## MEVCUT ALTYAPI VE MAKİNA/TEÇHİZAT İHTİYAÇLARI: 
>
>Proje bütçesi, video üzerinde yapılacak SSIM, PESQ, PVQM gibi yüksek işlem gücü gerektiren analizleri yapmak için gerekli donanımı satın almaya yeterli olamayacağı için mevcut altyapının kısıtları dâhilinde yapılmaya çalışılacaktır. Mevcut altyapıda kullanılacak bilgisayarlar aşağıdaki gibidir: 
>1. Asus Rog Zephyrus Dizüstü Bilgisayar, AMD Ryzen 7 6800HS, Nvidia G3060 grafik işlemci, 16 GB RAM, 512 GB SSD 
>2. Asus Zenbook Dizüstü Bilgisayar, Intel UX334FLC, NVidia MX230 grafik i., 16 GB RAM, 512 GB SSD
>
>1 nolu bilgisayara 32 GB RAM takviyesi ile performansının artırılması hedeflenecektir. Maliyeti yaklaşık 4000 TL olup öz imkânlarla çözülecektir. 
>
>Dizüstü bilgisayarlardan oluşan mevcut donanımın işlem gücü yeterli olsa da görüntüleri inceleyebilmek için daha **geniş ve yüksek çözünürlüklü ekrana** da ihtiyaç bulunmaktadır. Dizüstü bilgisayarlarda bulunan web kameraları düşük çözünürlükte video yayını yapabilmektedir. Performans testleri için **480p’den 4k’ya farklı çözünürlükte videoları kaydedebilmek ve yayınlayabilmek** amacıyla bu özelliklerde mikrofonlu kameraya ihtiyaç vardır.
>
# 3. PROJE YÖNETİMİ

## 3.1. Yönetim Düzeni: İş Paketleri (İP), Görev Dağılımı ve Süreleri

Projede yer alacak başlıca iş paketleri ve hedefleri, her bir iş paketinin kimler tarafından hangi sürede gerçekleştirileceği, başarı ölçütü ve projenin başarısına katkısı “İş-Zaman Çizelgesi” doldurularak verilir. Her bir iş paketinde görev alacak yürütücü, araştırmacı ve personel ayrıntılı olarak belirtilir. Literatür taraması, sonuç raporu hazırlama aşaması, proje sonuçlarının paylaşımı, makale yazımı ve malzeme alımı ayrı birer iş paketi olarak <ins>gösterilmemelidir</ins>.

Başarı ölçütü olarak her bir iş paketinin hangi kriterleri sağladığında başarılı sayılacağı açıklanır. Başarı ölçütü, ölçülebilir ve izlenebilir nitelikte olacak şekilde nicel veya nitel ölçütlerle (ifade, sayı, yüzde, vb.) belirtilir.

<h3 style="text-align:center;">İŞ-ZAMAN ÇİZELGESİ(*)</h4>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-uzvj{border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-uzvj">İP No</th>
    <th class="tg-uzvj">İş Paketlerinin Adı ve Hedefleri</th>
    <th class="tg-uzvj">Kim(ler) Tarafından Gerçekleştirileceği</th>
    <th class="tg-uzvj">Zaman Aralığı (..-.. Ay)</th>
    <th class="tg-uzvj">Başarı Ölçütü ve Projenin Başarısına Katkısı</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-9wq8">1</td>
    <td class="tg-9wq8">WebRTC Test Sunucu Altyapısının Geliştirilmesi</td>
    <td class="tg-9wq8">Yürütücü<sup>1</sup>,<br>Yüksek Lisans Bursiyeri<sup>4</sup>,<br>Lisans Bursiyeri<sup>5</sup></td>
    <td class="tg-9wq8">0-4.ay</td>
    <td class="tg-0pky">a-Pilot WebRTC uygulamasının geliştirilmesi,<br>b-Selenium ekosisteminin (Webdriver ve Grid) video ve ses benzerlik analizi haricindeki işlevler için çalışır hale getirilmesi ve<br>c-En az 30 işlevsel test durumunun oluşturulması ve pilot sisteme uyarlanması, testlerde %100 başarı raporlanması (%30)<br><br>Bir yüksek lisans bursiyerinin projedeki tüm çalışmalarını jüriye sunmak için tez haline getirmiş olması (%10)</td>
  </tr>
  <tr>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Video ve Ses Benzerlik Analizi</td>
    <td class="tg-9wq8">Yürütücü<sup>1</sup>,<br>Danışman1<sup>2</sup>,<br>Yüksek Lisans Bursiyeri<sup>4</sup>,<br>Lisans Bursiyeri<sup>5</sup></td>
    <td class="tg-9wq8">1-5.ay</td>
    <td class="tg-0pky">Görüntü ve ses kalitesi performans test kriterlerinin (gecikme ve benzerlik oranı) belirlenmesi (%10)<br><br>SSIM, PEVQ, VAMF ve NARVAL arasından en az iki tanesinin video konferans testlerinde (İP1’de geliştirilen sisteme) uyarlanması, tam otomatik test yaptırılarak otomatik test raporu üretilebilir olması (%20)<br><br>WebRTC için video ve ses benzerlik analiz yöntemlerinin araştırılması ve bu konuda bir yayın taslağının bir konferans ya da dergiye gönderilmiş olması (%20)</td>
  </tr>
  <tr>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Karşılaştırma Skoru Oluşturma(Benchmarking)<br></td>
    <td class="tg-9wq8">Yürütücü<sup>1</sup>,<br>Danışman2<sup>3</sup>,<br>Yüksek Lisans Bursiyeri<sup>4</sup></td>
    <td class="tg-9wq8">4-5.ay</td>
    <td class="tg-0pky">Bir video konferans ürününün sahip olması gereken işlev ve kalite gereksinimlerinin belirlenerek ağırlıklandırıldığı, karşılaştırma amacı ile üretilmiş standart bir notlandırma modeli sunan yayının bir dergi ya da konferansa gönderilmiş olması (%10)</td>
  </tr>
</tbody></table>

<sup>**(*)** Çizelgedeki satırlar gerektiği kadar genişletilebilir ve çoğaltılabilir.İş paketlerinin toplam süresi 12 ayı geçemez.</sup>

#### <sup>1</sup> Proje Yürütücüsü: Dr.Öğr.Üyesi Savaş Öztürk (Marmara Üniversitesi, Teknoloji Fakültesi, Elektrik-Elektronik Müh. Bölümü)

#### <sup>2</sup> Danışman1: Doç.Dr.Uğur Demir (Marmara Üniversitesi, Teknoloji Fakültesi, Elektrik-Elektronik Müh. Bölümü)

&nbsp;2210861 ve 121E492 nolu TÜBİTAK destekli projelerde Skolyoz tedavisi için tedavi öncesi teşhiste bir planlama
asistanı ve simülatörü geliştirip ardından tedavi için manyetik aktüatör ve kontrol ünitesinin geliştirilmesine katkıda
bulunmuştur. Bu projelerde MR görüntüsünden üç boyutlu omurga modelinin çıkarılması esnasında edindiği tecrübeden
bu projede de faydalanılması beklenmektedir. 

#### <sup>3</sup> Danışman2: Dr.Öğr.Üyesi Veysel Gökhan Böcekçi (Marmara Üniversitesi, Teknoloji Fakültesi, ElektrikElektronik Müh. Bölümü)
&nbsp;Video Görüntü İşleme Uygulamaları üzerinde çalışmalar yapmakta ve EEM7041 Video İşleme Uygulamaları yüksek
lisans dersini vermektedir. Görüntü ve Video kalitesinin değerlendirilmesi için kullanılacak benzerlik ve kalite ölçüm
yöntemleri üzerine destek verecektir. 

#### <sup>4</sup> Yüksek Lisans Bursiyeri:
&nbsp;Marmara Üniversitesi Elektrik-Elektronik Mühendisliği yüksek lisans programı öğrencisi olan ve ders dönemini Ocak 2025’te tamamlayacak olan Doğukan Biçer’in tez konusu, video konferans uygulamalarında video ve ses kalitesinin tam otomatik testleri olacaktır.

#### <sup>5</sup> Lisans Bursiyeri:
&nbsp;Marmara Üniversitesi Elektrik-Elektronik Mühendisliği lisans programı öğrencilerinden belirlenecek bir tanesi projede geliştirme ve test işleri için görevlendirilecek, bitirme tezi konusunda destek verilecektir. 

## 3.2. Risk Yönetimi

Projenin başarısını olumsuz yönde etkileyebilecek riskler ve bu risklerle karşılaşıldığında projenin başarıyla yürütülmesini
sağlamak için alınacak tedbirler (B Planı) ilgili iş paketleri belirtilerek ana hatlarıyla aşağıdaki Risk Yönetimi Tablosunda
ifade edilir. B planlarının uygulanması projenin temel hedeflerinden sapmaya yol açmamalıdır.
<h3 style="text-align:center;"> RİSK YÖNETİMİ TABLOSU (*)</h4>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-uzvj{border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-uzvj">İP No</th>
    <th class="tg-uzvj">En Önemli Riskler<br></th>
    <th class="tg-uzvj">Risk Yönetimi (B Planı)<br></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-9wq8">1</td>
    <td class="tg-9wq8">Döviz kurundaki değişim yüzünden makineteçhizat alımında zorluk yaşanması<br></td>
    <td class="tg-9wq8">Alternatif konfigürasyonlar değerlendirilecektir.<br></td>
  </tr>
  <tr>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">SSIM algoritmasının uygulanmasında düşünülen, test görüntüsüne harf ve rakam ekleme işleminin ya da okuma işleminin başarısız olması<br></td>
    <td class="tg-9wq8">Bu amaçla açık kaynaklı hazır videolar bulunması ya da sentetik videolar üretilmesi (son zamanlarda yaygınlaşmaya başlayan üretken yapay zeka tarafından üretilmiş videolar dahil) araştırılacaktır.<br></td>
  </tr>
  <tr>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">SSIM algoritmasının yazılıma doğru şekilde uyarlanamaması<br></td>
    <td class="tg-9wq8">PEVQ, VAMF ve NARVAL gibi alternatifler üzerinde çalışılacaktır.<br></td>
  </tr>
  <tr>
    <td class="tg-nrix">4</td>
    <td class="tg-0lax">Dağıtık testleri yapabilmek için gerekli uygun konfigürasyon yeterli bilgisayar bulunamaması</td>
    <td class="tg-0lax">NUBOMEDIA projesinde Garcia ve vd. yaptığı gibi güçlü bir bilgisayarda sanallaştırma yöntemiyle yük oluşturulacaktır.</td>
  </tr>
  <tr>
    <td class="tg-nrix">5</td>
    <td class="tg-0lax">Selenium Grid’in istemci makinalarda ekran görüntülerini yakalama ve geri göndermede ya da benzerlik analizlerini beklendiği gibi yapabilmeden yeterli olamaması</td>
    <td class="tg-9wq8">Cypress gibi alternatif test otomasyonu araçları değerlendirilecektir.</td>
  </tr>
</tbody></table>

<sup>**(*)** Tablodaki satırlar gerektiği kadar genişletilebilir ve çoğaltılabilir.
</sup>

# 4. YAYGIN ETKİ

Proje başarıyla gerçekleştirildiği takdirde projeden elde edilmesi öngörülen çıktı(lar) ve etki(ler kısa ve net cümlelerle ilgili
bölümde belirtilmelidir.

## 4.1. Projeden Elde Edilmesi Öngörülen Çıktılara İlişkin Bilgiler

Bu bölümde, projeden elde edilmesi öngörülen çıktılara yer verilmelidir. Söz konusu çıktılar, amaçlarına göre belirlenen
kategorilere ayrılarak belirtilmeli, nicel gösterge ve hedeflere dayandırılmalı ve varsa bu çıktıları kullanacak
kurum/kuruluş(lar)a ilişkin bilgi verilmelidir. Her bir çıktının elde edilmesinin öngörüldüğü zaman aralığı belirtilmelidir.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-wa1i">Çıktı Türü</th>
    <th class="tg-wa1i">Çıktı</th>
    <th class="tg-wa1i">Çıktının Elde Edilmesi Öngörülen Zaman Aralığı</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-nrix"><span style="font-weight:bold">Bilimsel/Akademik Çıktılar</span> (Bildiri, Makale, Kitap Bölümü, Kitap vb.):</td>
    <td class="tg-nrix">Proje çıktısı olarak 1 adet uluslararası dergi makalesi ve 2 adet (1 uluslararası, 1 ulusal) konferans bildirisi yayımlanması beklenmektedir. Dergi makalelerinin SCI indekslerinde taranan dergilerde yayımlanması, konferans bildirilerinin ise IEEE, ACM gibi yüksek profilli uluslararası yazılım mühendisliği, yazılım test mühendisliği ile IEEE Sinyal İşleme Uygulamaları (SIU) konferansında sunulması planlanmaktadır.</td>
    <td class="tg-wa1i">6-12. aylar</td>
  </tr>
  <tr>
    <td class="tg-nrix"><span style="font-weight:bold">Ekonomik/Ticari/Sosyal Çıktılar</span> (Ürün, Prototip, Patent, Faydalı Model, Üretim İzni, Tescil, Görsel/İşitsel Arşiv, Envanter/Veri Tabanı/Belgeleme Üretimi, Telife Konu Olan Eser, Spin-off/Start- up Şirket vb.):</td>
    <td class="tg-nrix">Ürün: Proje sonunda geliştirilen aracın yerli video konferans ürünlerinin testleri için kullanılması planlanmaktadır. Bu araç, dışa bağımlılığı azaltacak ve yerli video konferans ürünlerinin standart bir test sürecinden geçerek sertifikalandırılmasının yolu açılacaktır. <br><br>Ürünün Turkcell, Aselsan (Bites), Havelsan, Netaş, May Siber gibi yaklaşık 20 yerli video konferans sistemi üreticisi tarafından kullanılabilme potansiyeli vardır. <br><br>Start-up: Projenin başarılı olması halinde ürünleştirilerek ticarileşmesinin ve bir girişim kurulmasının önü açılacaktır. Sonraki aşamada TÜBİTAK TEYDEB başta olmak üzere yatırım fırsatları değerlendirilecektir. WebRTC teknolojisi sadece video konferans uygulaması üretiminde değil eğitim, otonom sistemler, oyun&amp;eğlence ve sağlık gibi sektörlerde potansiyeli olan gelişmeye açık bir teknolojidir. Bu nedenle bu girişimin önemli bir boşluğu dolduracağı değerlendirilmektedir.</td>
    <td class="tg-wa1i">6-12. aylar</td>
  </tr>
  <tr>
    <td class="tg-nrix"><span style="font-weight:bold">Araştırmacı Yetiştirilmesine Yönelik Çıktılar</span> (Yüksek Lisans/ Doktora/Tıpta Uzmanlık Tezleri):</td>
    <td class="tg-nrix">Projenin araştırma soruları bir yüksek lisans tezinin belkemiğini oluşturacaktır. Bu nedenle projenin en önemli çıktılarından birisi bir yüksek lisans araştırmacısı yetiştirmek olacaktır. <br><br>Bir lisans öğrencisi ise test otomasyonunda edineceği tecrübe ile gerek yazılım testi gerekse haberleşme ve video konferans alanında çalışan firmalarda kariyer fırsatı veya proje tecrübesi nedeniyle akademide kariyer imkanı yakalamasının önü açılacaktır.</td>
    <td class="tg-wa1i">6-12. aylar</td>
  </tr>
</tbody></table>

<sup>**(*)** Proje başlangıcından itibaren 6 aylık süreler halinde belirtilmelidir (Örn. 0-6 ay/6-12 ay/12-18 ay vb.). 
</sup>

## 4.2. Projeden Elde Edilmesi Öngörülen Etkilere İlişkin Bilgiler

Proje başarıyla gerçekleştirildiği takdirde projeden elde edilmesi öngörülen
- Toplumsal/kültürel etki,
- Akademik etki,
-  Ekonomik etki,
-  Ulusal Güvenlik etkisi

Proje Başvuru Sisteminde (PBS) seçilen [12. Kalkınma Planı](https://www.resmigazete.gov.tr/eskiler/2023/11/20231101M1-1-1.pdf) hedefleri ve politikaları çerçevesinde hedef kitle/alan belirtilerek açıklanmalıdır. Beklenen etkiler doğrulanabilir ve ölçülebilir olmalıdır. Etkilerin elde edilme zamanına ilişkin öngörüler belirtilmelidir.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-wa1i">Etki Türü</th>
    <th class="tg-wa1i">Etki</th>
    <th class="tg-wa1i">Etkinin Elde Edilmesi Öngörülen Zaman</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0lax"><span style="font-weight:bold">Toplumsal/Kültürel Etki: </span><br>&nbsp;• Yaşam Kalitesine Katkı, <br>&nbsp;• Sürdürülebilir Çevre ve Enerjiye Katkı, <br>&nbsp;• Refah veya Eğitim Seviyesinin İyileştirilmesine Katkı, <br>&nbsp;• Ülke ya da Dünya Düzeyinde Önemli Bir Sosyal Soruna Getirilecek Çözümler vb.</td>
    <td class="tg-0lax">Projede toplumsal ya da kültürel bir etki amaçlanmamaktadır.</td>
    <td class="tg-wa1i">-</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:bold">Akademik Etki:</span> <br>&nbsp;• Yeni Ar-Ge Kararları, <br>&nbsp;• Ulusal/Uluslararası Ar-Ge İşbirlikleri, <br>&nbsp;• Araştırmacı Sayısındaki ve Niteliğindeki Değişim, <br>&nbsp;• Üniversite- Sanayi İşbirliklerine Katkı vb.</td>
    <td class="tg-0lax">(590. İleri dijital teknolojilerin geliştirilmesi, yaygınlaştırılması ve bu teknolojileri kullanacak işgücünün yetiştirilmesini desteklemek amacıyla mekanizmalar kurgulanacaktır.) <br><br>Video konferans ürünleri testlerinde video ve ses analiz yaparak testlerin otomasyona geçirilmesi akademik açıdan yeni ve önemli bir konudur. Bu proje ile ülkemizde bu konuda araştırmacıların bulunması önemli etki oluşturacaktır. <br><br>Proje tamamlandığında bir yüksek lisans tezinin de sunulmaya hazır hale getirileceği değerlendirilmektedir. <br><br>(586. Açık kaynak kodlu yazılım ekosistemi geliştirilecektir.) 2017’de tamamlanan NUBOmedia gibi AB projelerinde yer alabilmek için önemli bir fırsat olacaktır. Bu amaçla endüstriden paydaş arayışına girilecek ve AB projeleri için çalışmalara başlanacaktır.</td>
    <td class="tg-wa1i">0-12. aylar</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:bold">Ekonomik Etki: </span><br>&nbsp;• Potansiyel Sektörel Uygulama Alanları, <br>&nbsp;• Küresel Pazar Öngörüleri, <br>&nbsp;• İstihdam Katkısı, <br>&nbsp;• Rekabetçilik (İhracata Etkisi, İthal İkamesi, Yeni Firmaların Oluşumu, Yabancı Sermaye Yatırımının Tetiklenmesi vb.)</td>
    <td class="tg-0lax">(,579. BİT sektöründe yerli ürün ve hizmet gelişimi desteklenerek yerlilik oranları artırılacaktır.) Video konferans ürünleri pazarı son iki yılda olağanüstü bir şekilde büyümüştür ve uzaktan çalışmanın yaygınlaşması ile büyümeye de devam edecektir. Bu nedenle WebRTC gibi güncel teknolojileri geliştirme ve test ihtiyacı daima olacaktır. Ekonomik ve teknolojik açıdan dışa bağımlılığımızı azaltacak bu araç ülkemizde ilk defa tasarlanmış olacaktır. <br><br>(582.1. Yerli ürünlerin uluslararası pazarda rekabetçi biçimde yer almalarını sağlayacak şekilde geliştirilmesi desteklenecektir.) <br><br>Dronelar ve robotlarda da pratikliği nedeniyle tercih edilmeye başlanan WebRTC teknolojisi kullanımı yaygınlaştırılarak maliyet tasarrufu sağlanacaktır.</td>
    <td class="tg-wa1i">6-12. aylar</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:bold">Ulusal Güvenlik Etkisi: </span><br>&nbsp;• Siber güvenlik, <br>&nbsp;• Enerji güvenliği, <br>&nbsp;• Sınır güvenliği, <br>&nbsp;• Ekonomik güvenlik vb.</td>
    <td class="tg-0lax">(590.1. Kamu kurumlarının ve özel sektörün dijital teknolojiler alanında ortak çözümler geliştirecekleri ekosistem güçlendirilecektir.) <br>Projenin çıkış noktası, özellikle pandemi ile ortaya çıkan güvenli yerli video konferans ürünlerine olan büyük ihtiyaç ve mevcut ürünlerin standart ve objektif bir şekilde test edilebilmesidir. Bu amaçla, projenin güvenlik ve veri mahremiyeti açısından faydası yadsınamaz.</td>
    <td class="tg-wa1i">6-18.aylar</td>
  </tr>
</tbody></table>

# BELİRTMEK İSTEDİĞİNİZ DİĞER KONULAR

Sadece proje önerisinin değerlendirilmesine katkı sağlayabilecek bilgi/veri (grafik, tablo, vb.) eklenebilir. 

# BAŞVURU FORMU EKLERİ

# EK-1: KAYNAKLAR

# EK-2: BÜTÇE VE GEREKÇESİ
