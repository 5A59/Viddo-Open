# QWEN 3 CODER Pazara Sunuldu... KIMI K2'den Daha İyi

Son zamanlarda bir video izledim ve oldukça bilgilendirici buldum. İçeriği daha iyi anlamak ve paylaşmak için videoyu yapılandırılmış bir makaleye dönüştürmek için **[Viddo](https://viddo.pro/)** kullandım. Bu makale bu analiz için referans olarak hizmet etti.

**Orijinal Video:** [Videoyu İzle](> - Alibaba, güçlü yeni açık kaynak kodlama modeli Quin 3 coder'ı tanıttı.
> - 480 milyar parametreli Powerful1 adlı devasa bir modele sahip.
> - Quin 3 coder çeşitli kıyaslamalarda öne çıkmakta ve rakiplerini geride bırakmakta.
> - Ageentic kodlama için bir komut satırı aracı, Quin Code, artık mevcut.
> - Pekiştirmeli öğrenmedeki yeni yöntemler, gerçek dünya kodlama görevlerinde performansı artırıyor.

Alibaba bir yenilik daha sundu: **Quin 3 coder**. Dünyanın **Kimi K2** adlı diğer büyük açık kaynak kodlama modeline alışmaya başladığı sırada, Alibaba **Quin 3 coder**'ı ortaya koydu ve Quin 3 coder birden fazla boyutta mevcut.

Ancak asıl büyük model olan **Powerful1**, Quin 3 Coder 480B A35B instruct yani bu **480 milyar parametreli bir model** olduğunu gösteriyor. Uzmanların karışımı ile inşa edildiği için, herhangi bir çağrıda yalnızca **35 milyar parametre aktiftir**. Instruct, temel modeline göre daha dostça ve yardımcı bir asistan modunu ifade eder; temel modeli ise biraz daha metin tamamlama modeli gibidir.

Nataly, **256k bağlamı** destekliyor ve **1 milyona** kadar ölçeklenebiliyor. Burada görüldüğü gibi, kıyaslamalar şimdi oldukça iyi görünüyor. Kıyaslamalara her zaman güven olunamaz, bu yüzden herkesin buna ulaşmasını ve test etmesini beklemek en iyisi.

Ancak **Kimi K2** oldukça etkileyiciydi. **Gwin 3 coder**, Kimi K2'yi rahatlıkla geride bırakıyor. Sadece bu da değil, aynı zamanda **Claud Sounded** ile karşılaştırılabilir. Ayrıca **OpenAI'nin GPT 4.1**'ini geride bırakıyor ve hem **ageentic tarayıcı kullanımı** hem de **ageentic araç kullanımı** konusunda çok güçlü puanlar alıyor. Tekrar belirtmek gerekirse, yalnızca Cloud Sounded 4 bazı durumlarda onu geride bırakıyor.

**Gwin ekibi**, en iyi geliştirici araçları ile sorunsuz bir şekilde çalıştığını ve dijital dünyada her yerde kullanılabileceğini vaat ediyor. Dünyadaki age genic kodlama ve bunun ciddiye alındığını söyleyebilirim.

Modelle birlikte, **Quin Code** adlı ageentic kodlamaya yönelik bir komut satırı aracı da açık kaynaklı hale getiriliyor. Bu, **Google'ın Gemini kodundan** çatallandı. Burada görüldüğü gibi, **GitHub Apache 2.0 lisansı** altında açık kaynaklı. Cımbız koduna oldukça benziyor ve Quin 3 coder'ın ageentic kodlama görevlerinde tam potansiyelini ortaya çıkarmak için özelleştirilmiş istemler ve fonksiyon çağrısı protokolleri ile uyarlanmıştır.

Temelde **Quin code**, sadece uyarlanmış **Gemini cli**'dır. **Quwin modellerini** kullanmak üzere değiştirilmiştir. **Quin 3 coder modellerini** **cloud code** ile de kullanabilirsiniz. Birçok kişi cloud code’u tercih ediyor, bu yüzden Quin 3 Coder modellerini Cloud code ile rahatlıkla kullanabilirsiniz. **K Clin** ile de kullanılabilir. Bu bağlantıları aşağıda bırakacağım.

Şu anda tartışılan önemli bir konu **pekıştirmeli öğrenme**dir. Bu modelleri alıp çeşitli becerileri öğretmek için bir RL gym'e götürmek, kodlama, matematik vb. olarak. Burada söylediğim gibi, ölçekleme kod pekiştirmeli öğrenme zor bir problem, fakat doğrulaması kolaydır.

Bu modeli eğitirken, eğitim adımlarını artırırken, performansın farklı alanlarında - kod oluşturma, yazılım geliştirme, rekabetçi kodlama, **SQL komut takip** vb. - devamlı artıyor. Önceki frontier laboratuvarına bir eleştiri getiriyorlar; topluluktaki rekabet düzeyindeki kod oluşturma odaklanmasının aksine, tüm kod görevlerinin yürütme odaklı büyük ölçekli RL pekiştirmeli öğrenme için doğal olarak uygun olduğuna inanıyoruz.

Bu nedenle, gerçek dünya kodlama görevlerinin daha geniş bir setinde kod RL eğitimini ölçeklediklerini belirtiyorlar. Temelde, bu sınavları ve testleri, bu rekabet tarzı soruları en üst düzeye çıkarmak yerine, bu modeli **gerçek dünyada gerçek işler yapması için** eğitiyorlar.

Otomatik olarak çeşitli kodlama görevlerinin test durumlarını ölçeklendirerek yüksek kaliteli eğitim durumları oluşturduk ve pekiştirmeli öğrenmenin tam potansiyelini başarıyla açtık. Bu yalnızca kod yürütme başarı oranlarını önemli ölçüde artırmakla kalmadı, aynı zamanda diğer görevlerde de kazanımlar sağladı.

Bu, bu yaklaşımın genel olduğunu gösterir. Örneğin, onu kod yapmaya eğitirken, matematik problemlerini çözme yeteneğini geliştirdiğini gördük, oysa bu konuda açıkça eğitilmedi. Kesinlikle, onların yaklaşımının birçok farklı görev arasında genelleştiği anlaşılıyor. Umarım daha sonra bu konuyu nasıl ele aldıklarını açıklayan bir makale yayınlarlar.

Burada ise, zor çözülebilir ama doğrulaması kolay görevleri büyük ölçekli ve pekiştirmeli öğrenme için verimli bir zemin olarak kullandıklarını belirtiyorlar.

İşte **SUI bench Verified** üzerindeki performansının bir grafiği; bu modelin boyutudur. Sağdaki modeller daha büyük, soldaki modeller daha küçük ve yukarı çıktıkça alt-ölçüm doğrulamalarda puan daha iyi oluyor. SWbench, insanların inceleyip çözülebilir olduğunu doğruladığı **500 gerçek dünya insan onaylı Python GitHub sorusu** içeriyor.

Buradan görebildiğiniz üzere, **Quin 3 coder**, **Kimmy K2**, **GPT 4.1** ve hatta **Gemini 2.5 Pro Preview** dahil olmak üzere gördüğümüz çoğu başka modelin üstündedir. Sadece **Cloud Sont 4** biraz daha büyük bir model olarak onları geride bırakıyor. Orta boy bir model olmasına rağmen, performans açısından ona eşdeğer bir şey yok. **Kimmik K2** çok daha büyük olmasına rağmen o kadar da iyi değil.

Önemli olan, **SUI bench verified**'da yer alan gerçek dünya yazılım mühendisliği görevlerinde **Quin 3 coder**'ın planlama, araç kullanımı, geribildirim alma ve karar verme gibi çok turlu etkileşimlerde bulunması gerektiğidir. Bu basit bir soru-cevap formatı değildir. Bu, planlama ve geribildirim içeren uzun vadeli bir görevdir.

Bu modeli uzun vadeli görevlerde bu kadar iyi hale getirme hileleri neydi? **Quint threeoder**'ın post-training aşamasında **Long Horizon rl** olarak adlandırdıkları bir şey tanıttılar. Bunu, modelin çok turlu etkileşimlerle araç kullanarak o gerçek dünya görevlerini çözmesini teşvik etmek için yapmışlar.

Bu oldukça ilginç. Bunu **Agent rl** şeklinde yapmanın ana zorluğu çevre ölçeklendirmesidir. Bunun üstesinden gelmek için, **20,000 bağımsız ortamı paralel olarak çalıştırabilen ölçeklenebilir bir sistem** geliştirdiler. Bunu, **Alibaba'nın bulut alt yapısını** kullanarak gerçekleştirdiler.

Bu, bu devasa pekiştirmeli öğrenme boru hattını çalıştırmak için gereken ölçeği sağladı. Bu, **Coin 3 Coder**'ın açık kaynak modeller arasında **son nokta performansı** elde etmesine olanak tanıdı; bu önemli bir nokta—test süresi ölçeklendirmesi olmadan. Bu bir akıl yürütme modeli değil. **DeepSeq R1** veya **Gemini 2.5 Pro Preview** gibi değil; bu, akıl yürütmeyen bir model.

Paylaştıkları bazı gösterimler arasında bina yıkımı ve gösterimler bulunuyor. İşte **Quinn with Klein** kullanarak, etkileşimli bir renk patlaması oluşturmuşlar. Gayet hoş görünüyor.

Bu şeyleri test etmemiz gerekecek: **3D Google Earth arazi görselleştirmesi**, yazma hızınızı test etmek için küçük bir uygulama, dönen zıplayan bir top, bir hiper küp, hipnotize edici bir güneş sistemi simülasyonu ve bir duet oyunu. **Quen AI** ile nasıl yüzleşeceğiniz ve sohbet edeceğiniz konusunda mevcut.

Bu şey üzerinde kapsamlı bir test turu yapacağım, fakat şimdilik, yaptığım bazı hızlı testler burada. Bir ofis binasının içinde masalar ve odalar bulunan bir simülasyon yapmayı denedim. Dış kısımda bir tür **şeffaf pencereler** yapmasını istemiştim, ama şeffaflığı başaramadı. Ya çok opak ya da tamamen şeffaf değillerdi.

Ama içeride, masalar ve bilgisayarlar olan odaları yaratmayı başardı. Her odada bir ışık var gibi görünüyor. Şimdilik başlangıç için fena değil. Bu, ilk girişim için oldukça iyi.

Ayrıca şehri dolaşabileceğiniz küçük bir **drone uçuş oyunu** oluşturmuş oldum. Şikayet edemem. Oldukça iyi. Anahtarlar biraz garip ama şu anda beğeniyorum. Biraz alışmak gerekiyor ama bir kez gazı fethetmeyi başardığınızda, dolaşabiliyorsunuz ve bir seferde iyi değil.

Bir **Minecraft klonu** var. Minecraft klonu olmadan nerede olurduk? Blokları yerleştirip inşa edebilir ve etrafta hareket edebilirsiniz. Fena değil, oldukça kolay bir şekilde bunu tek denemeyle başardım.

Bu yüzden kontrol et, senin fikrini bilmek isterim. Daha fazla test ve kullanım durumu çok yakında geliyor. Ayrıca, biri için bu küçük **cloud code** hack’ini yaptı ve neden bunu daha önce yapmadık ki?

Görev listesi üzerinden. **Yapılacaklar listesini** oluşturma. Efendim. Python kodu ayarlamalarına başlama. Bir numara yap. Görev listesi üzerinde çalışın. Aslında bu oldukça hızlı sinir bozucu olabilir.

Ve açık kaynak yapay zekanın bu kadar iyi olmasını hiç beklemiyordum. Frontier laboratuvarlarının arkasında birkaç yıl olmasını umut ediyorduk. Şimdi bunun aylar olduğunu görüyorum. **Hayatta olmak için muazzam bir zaman.**  
**Referans Makale:** [Viddo'da Görüntüle](https://viddo.pro/zh/video-result/de3fa85b-5156-4186-a39d-60c839fb0371)