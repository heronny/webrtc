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