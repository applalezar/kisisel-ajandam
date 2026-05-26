<p align="center">
<img src="github/logo.svg" width="100px"/>
</p>

<h1 align="center"> Kişisel Yönetim Sistemi<br/>Arka Uç</h1>
<p align="center"><i>Kişisel verilerinizi yönetmek için merkezi noktanız.</i></p>
<p align="center"><i>Bu sadece arka uçtur - aşağıyı okuyun!</i></p>

<h3>Belgeleme / Demo</h3>
<hr>

<ul>
<li><b>Ön Uç</b> - <a href="https://github.com/Volmarg/personal-management-system-front"><b>burada</b></a></li>
<li><b>Belgeleme</b> - <a href="https://volmarg.github.io"><b>burada</b></a></li>
<li><b>Demo</b> - buraya tıklayın <a href="http://personal-management-system.pl/"><b>burada</b></a>
<ul>
<li><b>Giriş:</b> admin@admin.admin</li>
<li><b>Şifre/Şifre Kilidi:</b> admin</li>
</ul>
</li>
</ul>

<h3>Açıklama</h3>
<hr>
<p align="justify">

Bu web uygulamasını anlamak, bir CMS (WordPress) veya CRM (SugarCRM) düşündüğünüzde daha kolaydır; bu sistemin arkasındaki mantık bu ikisine çok benzer. Benim PMS'im yukarıdaki sistemlerden daha az olanak sunabilir, ancak sadece istediğim şeyi yapıyor. Ayrıca, gerekli mantığa bağlı olarak uzantılar yazmak çok zor değil. Yazılım geliştirme bilgisine sahip herkes, kişisel ihtiyaçları için kendi eklentilerini yazabilir.

</p>

<h3>Gerekçe/Amaç</h3>
<hr>

<p align="justify">
Kendi sistemimi oluşturmaya karar verdim çünkü WordPress için bir sürü eklentiyle uğraşmak ve mevcut CRM'lere özelleştirmeler yazmak, kendi sistemimi yazmak kadar zamanımı alacaktı ve temel mantığını bildiğim için eklentiler yazmak ve ek modüller eklemek - neye ihtiyacım olursa olsun - benim için daha kolay.

</p>

<p align="justify">

İkincisi, böyle bir sistem yok ve Docker tabanlı bir bulutu CMS ile entegre etmek istemedim. Ayrıca, sadece düzenli kalmak için böyle bir uygulamaya ihtiyacım var ve bazı çok kişisel verilerimin OneDrive'da, diğer verilerin Google bulutunda, bazı notların burada, bazı notların da orada olmasından bıktım. Nihai hedef, internet erişimi olmadan, ev ağımına bağlı, terminalde veya Raspberry Pi'de 7/24 çalışan bir uygulamaya sahip olmaktır.

</p>

<h3>Önizleme</h3>
<hr>

<img src="github/dashboard.png">
<img src="github/contacts.png">
<img src="github/calendar.png">

<h3>Mevcut seçenekler ve modüller</h3>
<hr>

<ol>

<li><b style="display:inline">🎯 Yapılacaklar/Hedefler</b> - <span align="justify"><i>Kişisel hedeflerinizi takip edin. Hedeflerinizin ilerlemesini takip etmek için yapılacaklar listesini kullanabilir veya bir şey için toplamak istediğiniz para miktarını takip etmek için ödemeler alt modülünü kullanabilirsiniz.</i>

</span></li><br/>

<li><b>📖 Notlar</b> <span align="justify"> - <i>İstediğiniz kategoriye kişisel bir not ekleyin.</i> Burada, ihtiyacınız olan her türlü küçük bilgiyi saklayabilirsiniz; bunlar telefon görüşmelerinden alınan hızlı notlar, farklı sayfalardan toplanan bilgiler veya daha sonra kontrol etmek istediğiniz şeylere ait bağlantılar olabilir.</i></span></li><br/>

<li><b>📞 Kişiler</b> - <span align="justify">Telefonunuzu kaybetmeniz durumunda yedeklemek veya kurtulmak istediğiniz onlarca telefon rehberi, e-posta vb. olduğunu hiç hissettiniz mi? Bu basit modül ile kişisel kişilerinizi düzenleyebilirsiniz.

</span></li><br/>

<li><b>🔑 Şifreler</b> - <span align="justify"> <i>Hepimiz bir noktada çok fazla şifreyle uğraşmak zorunda kalıyoruz. Evet, bunları e-postada, USB bellekte saklayabilir, aklımızda özel kalıplar oluşturabiliriz, ama kabul edelim ki bazen çok fazla oluyor. Parolalar modülü ile parolalarınızı veritabanınızda şifrelenmiş olarak saklayabilirsiniz, ön uçta ise size orijinal parolayı geri getirecek bir kopyala düğmesi bulunur.
</i></span></li><br/>
<li><b>🏆 Başarılar</b> - <span><i>Yaptığınız harika şeylerin kaydını tutmak istiyorsanız, bu modüle ekleyin!</i></span></li><br/>
<li><b>📅 Planlar</b> - <span align="justify"><i>Bu modülün amacı, örneğin araba yağı değişimi, ödemeler, ziyaretler vb. gibi yapmanız gereken tekrarlayan şeyleri takip etmektir. Plan gruplarına eklenen veriler, Kontrol Paneli'nde ve bildirim zilinde görüntülenecektir.</i></span></li><br/>
<li><b>🔁 Sorunlar</b> - <span align="justify"><i>Bu bölümde, sonunda çözülmesi gereken devam eden/bekleyen vakaları takip edebilirsiniz, ancak sürekli olarak takip etmeniz gerekmez - yine de gelecekte bir gün geri dönmeniz gerekebilir, bu nedenle gerçekleştirilen iletişimlerin ve belirli bir alandaki ilerlemenin alt kayıtlarını eklemenize olanak tanır. durum</i></span></li><br/>

<li><b>🌴 Seyahatler</b> - <span align="justify"> <i>Ziyaret etmek istediğiniz yerler hakkında bazı fikirleriniz var ama henüz belirli bir planınız yok mu? Google harita bağlantısı ve bazı resimlerle bu Modüle ekleyin, böylece istediğiniz zaman geri dönebilirsiniz. Resim, bu belirli yere neden ilgi duyduğunuzu size hatırlatsın.</i></span></li><br/>

<li><b>💸 Ödemeler</b> - <span align="justify"> <i>Yiyecek, seyahat, yurt içi alışverişe ne kadar para harcadığınızı bilmiyor musunuz? Basitçe buradan Şimdi tüm alışveriş detaylarını listeye ekleyin ve programın tüm hesaplamaları, ilgili ay için özetle birlikte yapmasına izin verin. </i></span>
<p align="justify"><i>Öte yandan, belirli ürünlerin fiyatlarını takip etmek isterseniz, Ürün Fiyatları alt modülüne (şu anda başka bir ülkede olduğum için şahsen kullandığım modül) bu ürünler hakkında bilgi ekleyebilirsiniz.</i></p>
<p align="justify"><i>Burada ayrıca <b>Borçlu Para</b> alt modülünü kullanarak size kimin borçlu olduğunu veya kime borçlu olduğunuzu da takip edebilirsiniz.</i></p> <p align="justify"><i><b>Faturalar</b> alt modülü, belirli şeylere harcanan para hakkında bilgi kaydetmenizi sağlar (tatil vb. için harcanan para gibi aylık ödemelerden ayrı olarak).</i></p></li><br/>
<li><b>🛒 Alışveriş</b> - <span align="justify"><i>Gelecekte bir şey satın almayı planlıyor musunuz?</span></ ... Listeye ekleyin ve sonra bir göz atın, belki de bu ürünü şimdi satın alabilirsiniz.</i></span></li><br/>
<li><b>💻 İş</b> - <span align="justify"><i>Mesai Sonrası alt modülü, işte geçirdiğiniz tüm mesai sonrası sürelerini takip etmenin güzel bir yoludur. Bununla, belirli bir hedef için belirli dakikaları/saatleri de ayırabilirsiniz. Örneğin, seyahat için 24 saate ve bir şey yapmak için 4 saate ihtiyacınız var. Mevcut hedefe biraz zaman ekleyin, yeni bir tane oluşturun veya boş bırakın (genel amaçlı havuza gidecektir). Tatiller alt modülü, yıllık tatil havuzundan kaç gün kullandığınızı takip etmenin basit bir yoludur.</i></span></li><br/>
<li><b>📷 Resimler</b> - <span align="justify"><i>Bu modül, fotoğraflarınızı/taramalarınızı/indirdiğiniz resimleri mozaik galeriler şeklinde düzenlemenizi sağlar. Resim minyatürüne tıklamak, resmi yeniden adlandırma, silme veya indirme olanağı sunan bir lightbox galerisi açacaktır. İstediğiniz kadar galeri (klasör) oluşturabilirsiniz.</i></span></li><br/>

<li><b>📁 Dosyalar</b> - <span align="justify"><i>Bu modül için yüklenen dosyalar, dosya hakkında basit bilgiler görebileceğiniz bir Veri Tablosu şeklinde görünür: uzantı, dosya türü simgesi (verilen tür için tanımlanmışsa), dosya boyutu. Dosyalar GUI'den yeniden adlandırılabilir, indirilebilir ve silinebilir.</i></span></li><br/>

<li><b>🎬 Video</b> - <span align="justify"><i>İnternetten indirdiğiniz veya telefonda kaydettiğiniz kısa bir videonuz mu var? Bu, verileri depolamak için bir modüldür - en popüler web video formatlarını destekler.</i></span></li><br/>

<li><b>📑 Raporlar</b> - <span align="justify"><i>veritabanında zaten mevcut verilerden oluşturulmuş salt okunur raporlar içerir</i></span></li><br/>
</ol>

<h2>Kurulum/Belgeleme</h2>

Resmi belgelere buradan ulaşabilirsiniz: [burada](https://volmarg.github.io/docs/getting-started/installation.html)

<h2>Gelecek Geliştirme Planları</h2>

<h3>İyileştirmeler</h3>
<p>

<i>Genel olarak, zaman zaman sadece bazı hata düzeltmeleri/iyileştirmeler/modüller ekleyeceğim - sadece ihtiyaç duyduğum her şey.</i>
</p>
<hr>

<h2>Destek</h2>

<p <p>

Destek garantisi veremem. Bir işim, kişisel işlerim var, vb., sadece kodumu/uygulamamı MIT lisansı altında paylaşıyorum. Ancak, bir şey hakkında soru sormaktan, sorun bildirmekten vb. tamamen çekinmeyin. Belirttiğim gibi, bu uygulamayı şu andan itibaren günlük olarak kullanıyorum ve kullanmaya devam edeceğim, bu nedenle benim için bile iyi olabilecek bazı değişiklikler olabilir.

</p>

<p>

Üzerinde çalıştığım için, ihtiyaç duyduğum her şeye ulaştığımda gelecekte bazı düzeltmeler ve yeni modüller olacaktır.</p>

<h2>Teknoloji / çerçeveler / çözümler</h2>

Resmi dokümantasyona buradan ulaşabilirsiniz: [burada](https://volmarg.github.io/docs/technical/tech-stack.html)

<h2>Katkılar / özel teşekkürler</h2>

Buraya gidin: [burada](https://volmarg.github.io/docs/other/contributors.html)
