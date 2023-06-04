# Smart Plug Project - Akıllı Priz Projesi

Malzemeler:
•	Nodemcu V3 ESP8266-E12 Geliştirme kartı-CH340

•	AC220V-DC5V Dönüştürücü, 5V-700mA

•	4 Kanal 5V Röle Kartı

•	4 Adet Buton

•	4 Adet Modüler Priz

•	1 Adet Alüminyum Priz Kasası

•	Farklı Boyutlarda Klemensler

•	Jumper Kablo

•	3x2.5 Kablo

 
Nodemcu V3 ESP8266-E12 Geliştirme kartı-CH340

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/ce5249ec-e916-4aae-8318-5af65606df00)


 
NodeMCU üzerinde ESP8266 modülü bulunduran açık kaynak kodlu, ufak boyutlu elektronik geliştirme kartıdır. 
Ucuz olmasına rağmen çok stabil çalışan bir karttır.  Kullanım alanı oldukça geniştir. Üzerinde bulunan ESP8266 Wifi modülü sayesinde internete kolay bir şekilde bağlanabiliyor, bu özelliği sayesinde uzaktan kontrol ve IOT projelerinde çok fazla kullanılır. Ayrıca düşük güç tükettiği için, güç tüketimi önemli olan projelerde de çok tercih edilir.

 
Esp8266 kartı ile internet olan her yerde kullanılır. En büyük kullanım alanları ise evlerimiz, bilindiği üzere günümüzde evde ki kullandığımız çoğu eşya elektronik eşyalardır.

İnternete kolayca bağlanabilen bu kart blynk uygulamasıyla kontrol edilip evinizdeki lamba, su ısıtıcısı, televizyon , kahve makinası , buzdolabı , fırın gibi eşyaları telefonla veya kullandığınız elektronik cihazla kolayca kontrol edebilirsiniz .

Sadece elektronik cihazları kontrol etmek dışında evinizdeki çiçeklerin nem oranını ölçüp blynk uygulamasıyla röleyi aktif edip su motorunu çalıştırıp sulayabilirsiniz. Hayatımızı kolaylaştıran bu kart çok avantajlı gibi gözükse de kullanıldığı yere göre dezavantajları da bulunmaktadır.

Akıllı priz uygulamasında kullanılan röle uygun seçilmez ise fazla akım çekmesi sonucu devreye zarar verir ve yanmasına neden olabilir.
Bu yüzden kullanılması gereken yere göre uygun malzeme seçimi yapılması çok büyük önem arz etmektedir.

 
Esp8266 Datasheet
 
![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/393494aa-cb5f-47aa-964c-45231ef38c07)

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/ded2573c-58cb-40e2-a973-a0ff1f621701)


 

 
Pin Kategorisi	İsim	Tanım
Güç	Mikro USB, 3.3V, GND, Vin	Mikro USB: NodeMCU, USB bağlantı noktasından güç alabilir
 
3.3V: Karta güç sağlamak için bu pime düzenlenmiş 3.3V sağlanabilir
 
GND: Toprak pimleri
 
Vin: Harici Güç Kaynağı
Kontrol Pimleri	TR, RST	Pim ve düğme mikrodenetleyiciyi sıfırlar
Analog Pim	A0	0-3.3V aralığında analog voltajı ölçmek için kullanılır
GPIO Pinleri	GPIO1'den GPIO16'ya	NodeMCU kartında 16 adet genel amaçlı giriş-çıkış pini bulunmaktadır.
SPI Pinleri	SD1, CMD, SD0, CLK	NodeMCU'nun SPI iletişimi için dört pine sahiptir.
UART Pimleri	TXD0, RXD0, TXD2, RXD2	NodeMCU'nun iki UART ara yüzü vardır, UART0 (RXD0 & TXD0) ve UART1 (RXD1 & TXD1). UART1, bellenimi/programı yüklemek için kullanılır. 
I2C Pimleri	 	NodeMCU, I2C işlevsellik desteğine sahiptir ancak bu pinlerin dahili işlevselliği nedeniyle hangi pinin I2C olduğunu bulmanız gerekir.


NodeMCU ESP8266 Teknik Özellikler ve Özellikler
•	Mikrodenetleyici: Tensilica 32-bit RISC CPU Xtensa LX106
•	Çalışma Gerilimi: 3.3V
•	Giriş Voltajı: 7-12V
•	Dijital G/Ç Pimleri (DIO): 16
•	Analog Giriş Pimleri (ADC): 1
•	UART'lar: 1
•	SPI'ler: 1
•	I2C'ler: 1
•	Flash Bellek: 4 MB
•	SRAM: 64 KB
•	Saat Hızı: 80 MHz
•	CP2102 tabanlı USB-TTL yerleşiktir, Tak ve Çalıştır'ı etkinleştirir
•	PCB Anteni
 

AC220V-DC5V Dönüştürücü, 5V-700mA

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/8e2a5b2e-80dc-49b2-af84-d2f9e4cc49d6)

 
•	Giriş voltajı: AC 85 ~ 265V 50/60 Hz veya DC 100 ~ 370V
•	Giriş akımı: 0.0273A (AC110V) - 0.014A (AC220V)
•	Giriş Tahliye Akımı: 20A
•	Çıkış voltajı: DC  5 ± 0,2 V
•	Çıkış akımı 700 mA
•	Güç: 3.5 W
•	Çalışma sıcaklığı: 20 ~ 60 derece
•	Bağıl nem: % 40-90 RH
•	Çıkış: 5V, maksimum akım 700mA,
•	Anlık azami akım: 800mA
•	Çıkış aralığı: 4.8 - 5.2V
•	Ripple Gerilimi: 60mV
•	Çıkış gücü: 0-4W (DC akımı)
•	Çıkış verimliliği: 80%
•	Çıkış aşırı voltaj: 4.8-5.2V


4 Kanal 5V Röle Kartı

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/a5cdc7b1-a336-4340-9cbe-1271b6eefc1c)

 
Röle Nedir
Röle elektrik devrelerine anahtarlama yapan bir devre elemanıdır. Üzerinden geçirilen sinyal akımıyla kullanıcının istediği zamanlarda elektriğe yol vererek devreyi tamamlayabilmelerini sağlar. Devrelerde güvenlik amacıyla, belirli işlemleri istenen koşullarda yapmak için, belirli zaman periyotlarında devreyi açıp kapama işlemleri için röleler ve röle modülleri kullanılabilir.

Röle Çalışma Prensibi:

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/b415da1b-7dd1-456e-9794-c7c0618d26bf)
 

•	4'lü röle kontrol kartı, 5V ile kontakların kontrol edilebildiği, Arduino veya diğer başka mikrodenetleyeciler ile kullanılabilen bir röle kartıdır.

•	Mikrodenetleyeciden tetik sinyali sırasında 20mA'lik bir akım çekmektedir. Çeşitli hobi, endüstriyel ve robotik projelerde sıklıkla kullanılır.

•	30VDC veya 220VAC gerilimde 10A'e kadar akımı anahtarlayabilmektedir. Her bir role için kontrol ledleri bulunmaktadır.

•	Röleler lojik 0(0V) ile tetiklenir.

•	Röleler için NC, NO ve COM bacakları dışarı alınmıştır. Böylece tetikleme durumunda kısa devre veya tetikleme durumunda açık devre olması istenilen durumlarda kullanılabilir. 

 
Buton
 
 ![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/3fc0b506-112e-4963-8ad5-70cb184e8c57)


•	Butona basıldığında bacaklar arası kısa devre yaparak
Devrenin tamamlanmasını sağlar.
•	Butona tekrar basıldığında ise konum değiştirerek devreyi açık devre haline getirir.
•	1-3 ve 4-6 bacakları butona basıldığında açık veya kapalı devre olur.
•	2-5 bacakları ise genelde GND(toprak )bacağı olarak kullanılır.

Buton Çalışma Prensibi
 
 ![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/cded0f5a-e926-4a25-955a-b0998a36f07e)

Modüler Priz

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/4b0b24d7-5f9c-4819-bfd8-9a1bec29f94b)

 
•	Günlük yaşantımızdaki kullandığımız prizlerden farklı olarak iki tarafında da faz,nötr ve toprak köprüleri atabilmemiz için giriş yerleri vardır.
•	Şebeke prizi olarak da bilinir.
•	Güvenlik açısından çocuk kilidi vardır.
 
Klemens

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/1107a977-f24d-4000-847c-910a8beb79a4)

 
•	İki ya da daha fazla parçanın elektrik iletim kablolarının birbirine bağlanmasına yarayan parçalar klemens olarak isimlendirilmektedir. 

Klemenslerde yalıtkan kısımlar vardır. Bu kısımlar parçaların kullanılacakları yere göre porselen, seramik, metal ya da bakalit olabilmektedir.

 
Alüminyum Priz Kasası

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/bd4b2c80-ce42-4f0e-af03-0a8bb3a4de20)

 
•	45x45 cm prizlerin içine yerleştirildiği alüminyum priz kasasıdır.
•	Farklı priz sayılarına göre çerçeve uzunluğu değişmektedir.
•	İstenilen yere asılabilmesi için uçlarında plastik deliklerden oluşan bir yapısı vardır.

 
Jumper Kablo

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/a6207be9-3659-4c83-8118-840336970f4a)
 
•	Jumper kablo devrede kullanılan elemenlar arasında gerek sinyal gerek voltaj iletimi için kullanılır.
•	Köprü görevi görmektedir.

•	3 tip jumper kablo vardır:

1-erkek-erkek jumper kablo

2-erkek-dişi

3-dişi dişi

 

3x2.5 Kablo

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/9ba02c70-c82c-4d64-b765-3dc75464b0a0)

 
•	Çok sayıda ince bakırın bir araya gelmesi ile oluşan 3x2.5 TTR elektirk kabloları birçok alanda yagın olarak kullanılır. 

•	2,5 milimlik 3 damardan oluşan kabloların teknik özellikleri standart olur.

•	Bu 3 damarlı kabloların renginin bir temsili vardır.

•	Rengi kırmızı veya kahverengi olan kablo faz olarak isimlendirilir.

•	Rengi mavi olan nötr olarak isimlendirilir.

•	Rengi sarı-yeşil olan ise topraklama kablosudur.

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/b9e647e4-50a9-4c85-8e85-256324157a30)


 Akıllı priz nedir?
Akıllı priz, geleneksel elektrik prizine takılan ve uygulama veya sanal asistan aracılığıyla prize takılan her şeyi kontrol etmeyi sağlayan bir akıllı ev cihazıdır. Akıllı priz, akıllı olmayan sıradan cihazları bile akıllı ev ağının bir parçası haline getirir. Akıllı priz, tipik bir ışık anahtarı gibi çalışan bir tür anahtardır. 

Akıllı priz ve ışık anahtarı arasındaki fark, elektriği fiziksel bir düğme yerine bir uygulamanın kontrol etmesidir. 

Bazı akıllı prizler üzerinde internet bağlantısının kesildiği durumlarda prizi açıp kapamak için kullanılan fiziksel düğme de bulunmaktadır.
Akıllı priz, herhangi bir standart prizle çalışabilir. 

Akıllı prizi kullanmak için fişe takmanın dışında ek bir elektrik veya mekanik bir bağlantı yapmaya gerek yoktur. Akıllı prize takılan cihazın akıllı olmasına gerek yoktur.
Akıllı prizler , internete bağlanabilen ve uzaktan kontrol merkezli modüllerdir.
Akıllı prizler , ev otomasyon sistemleri ve akıllı ev uygulamaları ile birlikte evdeki elektronik cihazları kullanarak uzaktan kontrol merkezleri sağlarlar.

Akıllı prizlerin bazı modelleri , enerji tüketimi takip edebilir ve farklı cihaz kullanımlarını ayrı ayrı harcayarak enerji tasarrufu yapmanıza yardımcı olabilir.
Ayrıca , zamanlama özellikleri sayesinde cihazlar ne zaman açılıp kapanacağına da karar verebilir.

Akıllı prizler , mobil uygulamalar veya sesli komutlar yoluyla kontrol edilebilir. Bazı modellerinde ise hareket sensörleri veya uzaktan kumandalar kullanılabilir.

Akıllı prizlerin kulanım alanları oldukça geniştir. Evdeki herhangi bir yerine akıllı priz kullanarak , çamaşır makinesi ,bulaşık makinesi , klima , fırın , ısıtıcı , aydınlatma vb. cihazlar uzaktan kontrol etkinleştirilebilir.
Akıllı prizlerin sağladığı özellikler arasında enerji tasarrufu , kolay kullanım , uzaktan kontrol , cihazları koruma ve konforlu bir ev çalıştırma yer alır.
Dezavantajları ise bazı modellerin olması ve internet bağlantısı gerektirmektedir. Ayrıca bazı kullanıcılar için gizlilik ve güvenlik endişeleri de olabilir.

Akıllı prizler evde ve ofiste elektronik cihazların uzaktan kontrol edilmesi için kullanılır. Evde akıllı prizler çamaşır makinesi , bulaşık makinesi , klima , fırın , ısıtıcı , aydınlatma gibi elektronik cihazların kontrol edilmesinde kullanılabilir.
Örneğin , bir akıllı priz kullanarak çamaşır makinesinin  ne zaman açılacağını ayarlayabilir ve bu sayede enerji tasarrufu sağlayabilirsiniz.

Ofislerde de akıllı prizler kullanan cihazlarda uzak mesafe çalıştırma ve enerji tasarrufu sağlamak mümkündür. Ayrıca , akıllı prizlerin zamanlama özellikleri sayesinde ofisteki cihazları otomatik olarak açılan açılışı da bekleniyor.

Akıllı prizlerin diğer kullanım alanları arasında merkezler, kafeler alışveriş merkezleri gibi toplu kullanım alanları , üniversiteler , hastaneler ve kamu binaları yer alır. 
Bu alanlarda da akıllı prizler , elektronik cihazların uzaktan kontrol edilmesi , enerji tasarrufu sağlanması ve güvenlik açısından kullanılmaktadır.

Genel olarak , akıllı prizlerin kullanım alanları oldukça geniştir ve elektronik cihazların kontrolü , enerji tasarrufu sağlanması ve güvenlik açısından birçok alanda faydalı olabilir.

 

 



 Akıllı priz kullanımı neden gereklidir?
Günümüzde hayatımızın bir parçası olan elektrikli ev aletleri hayatımızı oldukça kolaylaştırmaktadır.

Bunun yanı sıra bize getirdiği problemlerde vardır;
En basit örneği evde ütü yaptınız ve evden çıktınız ama acaba ütünün fişini çıkartım mı diye düşündünüz işte tam bu noktada akıllı priz uygulaması en büyük yardımcınız olacaktır.

Sadece çok basit bir uygulama sayesinde prizin açık veya kapalı olduğunu görebilir ve istediğiniz gibi açıp kapatabilirsiniz.
Bu uygulama  elektrik tüketimi açısından size bilgi vermektedir. 
Kullandığınız prizin ne kadar güç tükettiğini rahatlıkla öğrenebilirsiniz.
Bu sayede elektrik faturanız gelmeden ortalama ne kadar ödeyeceğinizi hesaplayabilir ve gerekirse tasarruf sağlayabilirsiniz.

Akıllı prizler, geleneksel prizlerin yerini alabilen ve birçok avantajı olan bir teknolojik cihazdır. İşte akıllı prizleri kullanmanın bazı nedenleri :
1.	 Enerji tasarrufu: Akıllı prizleri , enerji tasarrufu sağlamak için tasarlandı. Çünkü akıllı prizler cihazların güç kaynağına sürekli oalrak bağlı kalmaları önleyebilir. Bu sayede gereksiz yere enerjinin tüketilmesinin önüne geçebilirler.
2.	 Uzaktan kontrol: Akıllı prizler , bir mobil uygulama veya diğer akıllı ev cihazları üzerinden uzaktan kontrol edilebilirler. Bu özellik , cihazların evde olmadığınız sürelerinde de muhafaza edebilmenizi kapatabilmenizi sağlar.

3.	 Programlanabilir: Akıllı prizler , zamanlama özelliği sayesinde cihazların belirli zamanda açılmasını veya açılışını programlayabilirsiniz. Bu özellik, günlük yaşantınızı kolaylaştırırken enerji tasarrufu sağlar.

4.	 Güvenlik: Akıllı prizler , aşırı yükü veya kısa devreleri algılayarak, cihazları güvenli bir şekilde çalıştırabilirler.

5.	 Entegrasyon: Akıllı prizler, diğer akıllı ev cihazlarıyla entegre olabilirler. Bu sayede evlerdeki cihazları tek bir yerden kontrol edilebilirler.
  
Tüm bu nedenler göz önlerinde, akıllı prizlerin kullanımı oldukça hızlı. Akıllı prizler, enerji tasarrufu sağlamak, evinizi daha akıllı hale getirmek ve evinizin yollarını artırmak için harika bir yol

 
Akıllı prizi bluetooth yerine internetle kullanmanın avantajları
1.	Uzaktan erişim: İnternet üzerinden kontrol ettiğinizde, dünyanın herhangi bir yerinden erişilebilir. Böylece, evde kapatmadığınızda bile prizi kapatabilirsiniz. Seyahat ederken veya işteyken prizi kontrol etmeyi sağlar.

2.	Geniş Kapsama Alanı: Bluetooth, kısa mesafeli bir iletişim protokolüdür ve genellikle 10 metreye kadar sınırlı bir kapsama sahiptir. Ancak internet üzerinden kontrol ederek, dünyanın herhangi bir yerinden yönetebilirsiniz. Uzak mesafelerde bile priz kontrol etme imkanı sunar.


3.	Zamanlama ve Otomasyon: İnternet bağlantılı akıllı prizler, zamanlama ve otomasyon özelliklerini sunar. Kayıt bir tarih saklama prizi otomatik olarak korumalı kapatabilir veya tekrarlayan programlar oluşturabilirsiniz. Örneğin, tatildeyken evdeki ışıkları saklayarak koruyabilir kapatabilir, güvenlik önlemleri alabilirsiniz.

4.	Entegrasyon ve Uzantılar: İnternet bağlantılı akıllı prizler,  diğer akıllı cihazlarla dağıtım sağlama ve ek özellikler sunma potansiyeline sahiptir. Günlük, sesli asistanlarla entegre olabilir, akıllı ev sistemleriyle iletişimi kontrol edebilir ve diğer loT cihazlarıyla senkronize edilebilir.

5.	Güncelleme ve Yenilikler: İnternet bağlantılı akıllı prizler, bellenim paketi boyunca yeni özellikler ve yapılandırmalar olabilir. Üretici tarafından sağlanan önlemleri kolayca uygulayabilir ve prizinizi teknolojiyle uyumlu hale getirebilirsiniz.

Akıllı prizi bluetooth yerine internetle kullanmanın dezavantajları
1.	Bağlantı Sorunları: İnternet bağlantısı akıllı prizler, internet bağlantısı olmadan yapılırlar. Eğer internet bağlantınız kesilirse, prizi uzaktan kontrol edemezsiniz. Ayrıca, bazen internet bağlantısı kesilmiş veya yavaş olabilir ve bu da prizin doğru şekilde çalışmasını engelleyebilir.

2.	Güvenlik Sorunları: İnternet bağlantılı akıllı prizler, internet üzerinden yönetildiği için, internet güvenliği konusunda bir risk taşır. Hacklenme veya siber saldırılara karşı karşıya kalabilirler. Bu nedenle, prizin internet verilerini ve yolculuklarını elde etmek için ek olarak alınması mümkündür.

3.	Yüksek Maliyet: Bluetooth ile çalışan akıllı prizlere göre, internet bağlantılı akıllı prizler genellikle daha pahalıdır. Bu nedenle, bütçesi kısıtlı olanlar için tercih edilmesi daha zor olabilir.

4.	Veri Gizliliği: İnternet bağlantılı akıllı prizler, kullanıcı prizleriyle ilgili verilerinin incelenmesine ve paylaşılmasına izin verebilir. Bu nedenle, veri gizliliği konusunda hassas olan kişiler için tercih edilmesi daha zor olabilir.


 
Kullanılan uygulamalar
Arduino IDE 

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/b8148d01-e991-4e1a-a32b-bc053fb701de)

 
•	C ve C++ dilleri ile yazılmış bir platformlar arası uygulamadır.
•	Arduino uyumlu kartlara program yazmak ve yüklemek için kullanılır, aynı zamanda 3. taraf çekirdekler ve satıcıların geliştirme kartları içinde kullanılabilir.
•	Arduino IDE, Wiring projesinde bulunan birçok yaygın giriş ve çıkış prosedürünü bir yazılım kütüphanesi ile sağlamaktadır.
•	Arduino IDE temelde, çalıştırılabilir kodu hexadecimal format ile metin dosyasına işler. Ardından kullandığımız Arduino IDE'si bu metin dosyasını bağlı olan arduino kartına firmware'ına yükleyici program ile aktarmayı gerçekleştirir.

Arduino IDE (Integrated Development Environment ) açık kaynaklı bir yazılım geliştirme ortamıdır. Bu ortam, Arduino mikrodenetleyicilerini proglamlamak için kullanılır. Arduino IDE, basit bir kullanıcı arayüzüne sahiptir ve birçok proglamlama dili desteği sunar. Ayrıca, platformun açık kaynak kodlu olması sayesinde kullanıcılar, araçlar ve özellikleri kendi özelliklerine göre uyarlayabilirler.
Arduino IDE, kullanıcılar Arduino kartlarına yüklenen programları yazmalarına, yüklemelerine ve yönetmelerine olanak tanır. Bu programlar, Arduino mikrodenetleyicilerinin çalışma mantığını kontrol eder. Arduino IDE, C++ programlama yöntemlerini kullanarak, Arduino kartlarına yazılan programların derlenmesini ve kullanım gösterimi sonuçlarını kontrol etmesine olanak tanır.
Arduino IDE, kullanıcıların yazdıkları kodların hatalarını belirlemelerine yardımcı olacak araçlar sağlar. Örneğin, kullanıcıların yazdığı kodlarda belirtilen hatalar tanımsız değişkenleri, çalıştırma veya sabitleri tespit edebilir. Bu şekilde kullanıcılar, kodlarının hatasız çalıştırmalarını sağlayabilirler.

Arduino IDE, basit ve kullanıcı dostu bir erişimi sağlar. Bu erişimleri, kullanıcıların kodlarına yazmalarına, indirmelerine ve yüklemelerine olanak tanır. Ayrıca, Arduino IDE, kullanıcıların Arduino kartlarını seçmelerine, seri bağlantı kurmalarına ve hata ölümlerini gerçekleştirmelerine olanak tanır.
Sonuç olarak, Arduino IDE, açık kaynak kodlu bir yazılım geliştirme ortamıdır. Bu ortam, Arduino mikrodenetleyicilerinin programlanmasını ve kontrol edilmesini sağlar. Kullanıcılar, Arduino IDE aracılığıyla basit bir kullanıcı arayüzü sayesinde kodlarını yazabilir, derleyebilir ve yükleyebilirler. Bu şekilde Arduino IDE kullanıcıları Arduino kartlarını programlamalarına ve projelerinde kullanımlarına olanak tanır.

Blynk  

![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/63bd55a4-e3a7-47b9-a0ec-4fdbd52d702e)

•	Blynk uygulaması İOS ve Android’te mevcuttur. Blynk ile Arduino, Raspberry Pİ gibi benzer kartları kontrol etmenize olanak sağlayan bir platformdur.
•	Blynk nesnelerin interneti için tasarlanmıştır. Bağlı donanımları uzaktan kontrol edebilir, sensör verilerini okuyabilir, verileri görselleştirebilir, depolayabilir ve bir çok daha güzel şeyler yapabilir.
Blynk, loT (Nesnelerin İnterneti) uygulamaları için bir görsel programlama aracıdır. Blnyk, akıllı telefon veya tablet gibi mobil cihazlar üzerinden kontrol cihazları loT yapıları oluşturmak için kullanılır. Akıllı prizlerde loT cihazlarından biri ve Blynk uygulaması ile kontrol edilebilir.
Blynk uygulaması, akıllı prizlerin uzaktan kontrol edilmesini sağlar. Akıllı prizler, internete bağlı oldukları için, Blynk uygulaması aracılığıyla mobil cihazlar üzerinden ödülleri kontrol etmek mümkündür. Örneğin, Blynk uygulaması üzerinden akıllı prizi kapatabilirsiniz.
Ayrıca, Blynk uygulaması ile akıllı prizlerin enerji tüketimini takip etmek ve bu şekilde enerji tasarrufu yapmak da mümkündür. Blynk uygulaması, akıllı prizlerin özelliklerinin daha kullanıcı dostu hale getirilmesini sağlar, akıllı ev uygulamalarının daha yaygın olarak kullanılmasını sağlar.
Sonuç olarak, akıllı prizlerin uzaktan kontrol edilmesi için Blynk uygulaması kullanılabilir ve bu şekilde akıllı prizlerin kullanımı daha da kolaylaşır.
blynk, modüller loT tasarımları için kullanılan birçok bileşen (sensörler, modüller, uyarı sistemleri vb.) bir araya getirme ve iletişim kurma imkanı verir. Böylece kullanıcılar, kendilerine yönelik loT projelerini kullanabilirler.
Blynk uygulaması, kullanıcıların projelerini programlamadan önceki hayallerine olanak tanır. Bu kullanıcıların kayıtlarındaki kayıtları, ekran ve kontrol düğmelerini istedikleri şekilde ayarlamalarını ve düzenlemelerini sağlar. Blynk uygulaması, türü olarak kullanmka widgetler sunar ve bu vidgetler aracılığıyla kullanıcıların verilerini elinde tutanları kolayca kullanırlar.
Blynk, kullanıcısı projelerinde yer alan nesnelerin ve sensörlerin gözlemlerini kolayca görselleştirmelerini sağlar. Örneğin,kullanıcılar bir sıcaklık sensörü projelerinde kullanıyorsa, Blynk uygulaması bu sensörün yüzeyi görsel olarak işleyerek sıcaklık değerlerini gösterir.
Blynk uygulaması ayrıca kullanıcıların loT projelerini uzaktan kontrol etmelerini sağlar. Kullanıcılar, akıllı telefon veya tablet gibi mobil cihazlarını kullanarak loT projelerini kontrol edebilirler. Örneğin, akıllı kullanıcılar bir prizi kapatabilir veya bir sensörden okuduğu verileri uzaktan kontrol edebilirler.
Sonuç olarak, Blynk uygulaması loT yapıları oluşturmak, yönetmek ve kontrol etmek için kullanılan bir görsel programlama aracıdır. Blynk, saldırganlar ve kullanıcı dostu loT yapıları oluşturma imkanı vererek, loT teknolojilerinin daha kolay ve erişilebilir hale getirir. 


 
Nodemcu –Blynk ilişkisi
Blynk ile Arduino, ESP8266 gibi benzer kartları kontrol etmenize olanak sağlayan bir platformdur.
Blynk nesnelerin interneti için tasarlanmıştır. Bağlı donanımları uzaktan kontrol edebilir, sensör verilerini okuyabilir, verileri görselleştirebilir, depolayabilir ve bir çok daha güzel şeyler yapabilir.
Nodemcu, bir mikrodenetleyici kartıdır ve wi-fi bağlantısı kurabilen bir ESP8266 wi-fi mödülüne sahiptir. Bu kart, programlanabilir ve internet üzerinden kontrol edilebilir cihazlar yapmak için kullanılabilir. Öte yandan, Blynk bir loT (Nesnelerin İnterneti) uygulama geliştirme platformudur ve cihazlarınızı uzaktan kontrol etmenizi sğalayan bir mobil uygulama sunar.
Nodemcu ve Blynk arasındaki ilişki, Nodemcu’nun Blynk platformuyla ortaya çıkması sayesinde gerçekleşir. Nodemcu, Blynk’ten gelen veriler işler ve Blynk uygulaması üzerinden cihazları kontrol etmeye izin verir.
Bynk, kullanıcıların özel mobil uygulamaları ve internet bağlantısı olmadan loT cihazlarını ortadan kaldırmalarını sağlar. Bu, Blynk’in kullanıcıları wi-fi bağlantısı olan cihazları kontrol etmelerini sağlayarak ,akıllı evler, akıllı tarım sistemleri, otomatik sulama sistemleri ve daha pek çok uygulama için ideal bir çözüm sağlanmasını sağlar.
Nodemcu ve Blynk arasındaki ilişkiyi kullanarak, kullanıcılar mobil cihazlarını kullanarak cihazları kontrol edebilirler. Blynk uygulaması üzerinden kullanıcılar, Nodemcu ile bağlantılı cihazları kapatabilir, cihazların sıcaklığı nem ve diğer sensörlerlerden alınan verileri izleyebilir ve cihazlara veri aktarabilirler. 
Sonuç olarak , Nodemcu ve Blynk arasındaki ilişki, evler akıllı, akıllı tarım sistemleri ve loT cihazlarının bileşimi için çok önemlidir. Blynk platformunun kullanımı, loT cihazlarına erişmek için özel mobil olmayan uygulamalar kullanıcıların ihtiyaçlarını karşılayan ve Nodemcu ile birlikte kullanımı çok bulunan farklı loT uygulaması için uygun bir çözüm sunuyor.  


 
            Kodlar Ve Yapım Aşaması

Esp8266, wi-fi modülü ve mikrokontrolörü bir arada içeren bir geliştirme kartıdır. Bu kartı kullanarak bir akıllı priz tasarlayabilirsiniz.
İşlemci kartı üzerindeki wi-fi modülü sayesinde, kartı wi-fi ağına bağlayabilir ve prizi uzaktan kontrol edebilirsiniz. İşlemci kartının GPIO pinleri üzerindeki prizin açık/kapalı geçişini kontrol etmek için kullanılabilir.
İşlemci kartı programlanabilir ve birçok programlama dili ile programlanabilir. ESP8266 ile programlama yapmak için Arduino IDE veya ESP8266 için özel olarak bir IDE kullanabilirsiniz.
Akıllı bir priz tasarımı yapmak için öncelikle priz tipine uygun bir AC/DC çevirici devresi tasarlamalısınız bu devre, AC elektriği DC’ye dönüştürme ve işlemci kartının yürütülmesini sağlar.
Ardından, işlemci kartının GPIO pinlerinin birini, prizin güç anahtarına bağlamalısınız. Bu sayede, işlemci kartı üzerinden prizin açık/kapalı gideceğini kontrol edebilirsiniz.
Son olarak, işlemci kartına uygun bir yazaılım yükleyerek, prizin açık/kapalı giderken kontrol edebilirsiniz. Yazılım, wi-fi bağlantısını, kullanıcıların prizi tutmasını/kapatmasını ve prizin açık/kapalı olmasını kontrol etmeyi sağlar.
Özetle, ESP8266 kullanarak akıllı bir priz tasarlamak için bir AC/DC çevirici devre tasarlayın, işlemci kartının GPIO pinlerini kullanarak priz güç anahtarına geçin ve işlemci kartına uygun bir yazılım yükleyin.
ESP8266, wi-fi bağlantısı sağlayabilen bir mikrodenetleyicidir, örneğin akıllı prizlerde.
Akıllı prizler, elektronik cihazlar uzaktan açma ve kapama imkanı sunan cihazlardır. ESP8266 kullanarak bir akıllı priz yapmak için, şu yolları izleriz.
1.	Arduino IDE kurulumu:
•	Arduino IDE’yi indirin veyükleyin.
•	Ardından, ESP8266 modülünü Arduino IDE’ye entegre etmek için “Arduino Board Manager” kullanarak ESP8266 desteğini ekleyin. Bunun için Arduino IDE’yi açın, “Araçlar” menülerinden “Kart” seçeneklerine gelin, “Kart Yöneticisi” ni seçin ve “ESP8266” yı aramaya başlayın. ESP8266 için uygun olan son sürümü yükleyin.
2.	Devre Bağlantısı:
•	ESP8266 modülünü USB-TTL koruyucuya veya Arduino’ya uyumlu seçilmelidir.
•	ESP8266’nın VCC pini USB-TTL  koruyucunun 3.3V çıkışına veya Arduino’nun 3.3V pinine bağlanmalıdır.
•	ESP8266’nın GND pini USB-TTL  koruyucunun GND pinine veya Arduino’nun GND pinine bağlanmalıdır.
•	ESP8266’nın TX pini USB-TTL  koruyucunun RX pinine veya Arduino’nun RX pinine bağlanmalıdır.
•	ESP8266’nın RX pini USB-TTL  koruyucunun TX pinine veya Arduino’nun TX pinine bağlanmalıdır.
•	ESP8266’nın GPIO2 pini, akıllı prizdeki kontrol hattına bağlanmalıdır. Bu dağıtım, priz kontrol hattını yüksek veya düşük çekme için kullanacağız.
3.	Arduino IDE yapılandırması:
•	Arduino IDE’yi açın ve “Araçlar” programlarının doğru kartı ve seri bağlantı noktalarını seçin. ESP8266 modülünüzü kullanıyorsanız, doğru kart korumasından emin olun (Örneğin: NODEMCU).
•	Ayrıca “Araçlar” programlarından “flaş boyutu”nu “4M (1MSPIFFS )” olarak ayarlayın.
•	Ardından “Araçlar” yöneticilerinden “Kütüphane Yöneticisi”ni seçin “ESP8266WİFİ” kütüphanesini arayın veyükleyin.
4.	Blynk yazılımını indirin:
•	Blynk uygulamasını App store veya Google Play Store’dan indirin.
5.	Hesap oluşturma:
•	Blynk girişi açın ve “Yeni Hesap Oluştur” ayarlarına tıklayın.
•	Gerekli bilgileri girin: Adınız, e-posta adresiniz ve şifreniz.
•	İletimi doğrulamak için e-postanıza gelen doğrulama bağlantısına tıklayın.
6.	Yeni bir proje oluşturma:
•	Ana sayfada “create new Project” seçeneğine tıklayın.
•	Projenize bir ad verin ve edinebileceğiniz donanım özelliklerini seçin (Örneğin:ESP8266).
•	Ayrıca bağlantı bağlantısını da seçin (Örneğin: Wi-fi).
•	Son olarak, proje oluşturma verilerini saklamak için “Oluştur” seçeneğine tıklayın.
7.	Projeniz için bir Auth Token alın:
•	Proje sayfasına gidin ve sol üst köşedeki “Proje Ayarları” öğelerine tıklayın.
•	“Auth Token” bölümündeki “Email” butonuna tıklayın ve e-postanızdaki Auth Token’ınızı kopyalayın.

 
•	Gerekli malzemeleri temin edin: ESP8266, bir giriş modülü, bir priz kutusu, bir fiş ve birkaç bağlantı kablosu.

•	ESP8266’yı programlayın: ESP8266’yı Arduino IDE veya benzeri bir programlama ortamında programlayabilirsiniz. Programlama yapılırken, ESP8266’nın Wi-fi sürelerini ve çalıştırmayı kontrol etmek için gerekli kodları yazmanız gerekir. 


•	Röle modülünü birleştirin: Röle modülü, ESP8266’nın GPIO pinlerine bağlanmalıdır. Röle modülü prizi açmak ve kapatmak için kullanılacak olan yüksek akımlı devreyi kontrol eder.

•	Fiş ve priz uygulaması: Fişi priz kutusuna koyun ve kutuyu kapatın. Priz kapatmanın üzerine bir açma/kapama kumandası veya iletişim sensörleri gibi bir kontrol noktası ayrılır.


•	Wi-fi bağlantı ayarı: ESP8266’nın Wifi hızı ayarları için, Wifi ağınızın SSID ve şifresini programlama kodunda tanımlamanız gerekir.

•	Akıllı prizinizi kullanın: ESP8266 Wifi bağlantısı kurulduktan sonra, akıllı prizinizi uzaktan kapatabilirsiniz.

 ![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/5ebbcecd-8024-40ce-af73-9e60824f8df2)


 
 Örnek bir bağlantı şemasıdır. Bu şemada isterseniz
 Yazılımınızdaki tanımladığınız çıkış pinlerine göre sadece 
 ESP8266 kartındaki çıkış pinlerini ayarlayabilirsiniz.
 Besleme uçları bağlantıdaki gibidir.

 ![image](https://github.com/bahadirdemir/smart-plug/assets/135511336/5e9dc6e2-bf9b-4f64-8777-8418ef699e08)

 
Yukarıda yazılan kod kişiye özgüdür. Çünkü bu projeyi yapmak için Blynk’den bir hesap oluşturursunuz. Akıllı priz dışında birçok uygulama için Blynk uygulaması tercih edilebilir, kurulumu kolay ve anlaşılır. Proje için mobil uygulama veya internet üzerinden hesabınıza giriş yapıp, yaptığınız proje için size özel verilen Autoken bilgilerini kod satırlarına ekleyerek projenizi oluşturabilirsiniz.
Sizin için verilen bilgileri yazdıktan sonra kartınızın hangi pininden çıkış akıp prizi kontrol etmek size kalmış, yaptığınız bağlantıda prizleri kontrol ederken prizlerin Blynkten tanımladığınız Switchleri prizlerle aynı sırada olduğuna dikkat etmeniz yararınıza olur yada butonlara isim atayarak bu karışıklığı ortadan da kaldırabilirsiniz.
Kullandığınız kütüphanelerin sürümlerine dikkat edin çünkü bazen bazı kütüphane sürümleri desteklemeyebilir ve sürekli kodunuz doğru dahi olsa hata alabilirsiniz.
“blynk-cloud.com 8080” hatası bunun bir örneğidir. Sizin IP adresinize bağlanamaz ve kartınızı aktif olarak uygulama içinde göremezsiniz.
Bunun için doğru kütüphaneyi seçip IP adresinizi tanımlamanız işinizi kolaylaştıracaktır.
Ve lütfen unutmayın ki çalıştığınız proje şebeke gerilimi taşımaktadır, bu yüzden dalgınlığınız size zarar verebilir dikkat etmeniz sizin için çok önemlidir.

 
 
MALZEMELER	ADET	FİYAT($)
ESP8266
(Nodemcu)	1	4.48
AC220V-DC5V
Dönüştürücü	1	1.77
4 Kanak Röle Kartı	1	2.89
Buton	4	0.17x4
Modüler Priz	4	2.02x4
Alüminyum Priz Kasası	1	6.56
Klemens	2	0.25x2
Jumper Kablo	20	0.050x20
Çok Damarlı 3x2.5 Kablo	3 Metre	1.01x3
	     Toplam	28.96$
               MALİYET TABLOSU


 
                            KAYNAKÇA
1.	Al-Ali, Ar-Mashaqbeh, GA (2017). Akıllı telefon kullanan Wi-fi tabanlı bir akıllı ev otomasyon sisteminin tasarımı veuygulaması. Uluslararası İleri Bilgisayar Bilimi ve Uygulamaları Dergisi, 8(3), 1-9.

2.	Wang, Y., Wang, J., Zhang, C. Ve zheng, L. (2019). ZigBee kablosuz iletişim tabanlı akıllı priz tasarımı. 2019’da 2. Uluslararası Akıllı Şebeke ve Yenilenebilir Enerji Konferansı (SGRE) (s. 178-181). IEEE.


3.	Yu,X., Guo, J., Wang, Q. Ve Jiang, Z. (2019). ESP8266 Temelli Akıllı Priz Tasarımı. 2019’da 7.Uluslararası Akıllı Enerji Şebeke Mühendisliği Konferansı (SEGE) (s. 32-35). IEEE.

4.	Örnek Bağlantı Şeması (Robotistan Maker).


5.	Örnek Fotoğraflar (Google)



