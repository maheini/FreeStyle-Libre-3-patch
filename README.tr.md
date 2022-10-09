
# FreeStyle Libre 3 patch

Bu metin otomatik olarak çevrilmiştir. en son güncellemeler için İngilizce veya Almanca sürümü okumalısınız.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> İngilizce Readme</a>

Libre 3 gelişimini yönlendirmek için genel repo. Bu depo Libre 3 hakkında bilgi alışverişi için kullanılmalıdır. Olası hedefler şifre çözme ve Xdrip için bir arayüz oluşturulmasıdır.

## Sorumluluk Reddi

github.com'daki bilgilerin ve uygulamanın kullanımı kendi sorumluluğunuzdadır ve herhangi bir garanti veya resmi destek olmadan. bu projenin Abbott ile hiçbir ilişkisi yoktur ve Abbott tarafından onaylanmamıştır.

## Juggluco çözümü

Tüm çalışmalar için [jkaltes](http://jkaltes.byethost16.com/)'e çok teşekkürler. Yeni FSTL3 yaması](http://jkaltes.byethost16.com/Juggluco/libre3/) ile, 
Sonunda root erişimi gerektirmeyen ve Xdrip ile tamamen entegre olan çevrimdışı bir çözüm var. talimatları burada bulabilirsiniz: [Juggluco ile Libre3 yaması için talimatlar](./Juggluco-solution/instructions/en/instructions.md). Veya [İndirme bağlantısı](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1)'nı kullanabilirsiniz. Lütfen dikkat: Bu çözümün riski size aittir ve herhangi bir garanti veya resmi destek yoktur. Bu projenin Abbott ile hiçbir ilişkisi yoktur ve Abbott tarafından desteklenmemektedir.

Lütfen dikkat: Juggluco'nun ve son Libre 3 yamasının geliştirilmesine dahil olmadım, ancak devam eden tüm geliştirme çalışmalarını paylaşmayı seviyorum.

## FSL 3 için diğer çözümler (root veya çevrimiçi bağlantı gerektirir)

- Ücretsiz Üç: Çevrimdışı bir çözüm -> root ve biraz bilgi birikimi gerektirir, ayrıca yalnızca libre 3 uygulamasını 3.3.1 sürümüne kadar destekler. [Bağlantı (Almanca)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->En son indirme: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink'ten Nightscout'a yan yükleme: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- Linkup verilerini indirmek ve Xdrip ile paylaşmak için uygulama (LLU Client) (kaynak: Libre 2): [Link (Almanca)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): LLU İstemcisi için Xdrip+ olmadan BG'yi bildirim olarak gösterebilen bir alternatif
- Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): Xdrip+'ın Nightly yapısındaki özellik (kalibrasyon mümkün değil)
- iOS için geliştirme aşamasında: DiaBLE -> FSTL3 yeteneklerinden yararlanmaya çalışıyor. [Github repo](https://github.com/gui-dos/DiaBLE)

## Mevcut durum

Şifre çözme az önce bozuldu :smiley:. Sonunda Android ve Xdrip ile çalışan, köklü olmayan telefonlar için bir çözüm var.

## Nasıl katkıda bulunulur

Libre 3 hakkında yararlı bilgileriniz varsa, bunları [tartışmalar sekmesinde] (https://github.com/maheini/FreeStyle-Libre-3-patch/discussions) paylaşın.

## Şifreleme bilgileri

Libre 3 uygulaması hakkında aşağıdakiler bilinmektedir: Başlangıçtan sonra, uygulama herhangi bir değişiklik olup olmadığını kontrol eder. WhiteCryption kod koruması burada kullanılır.

### #WeAreNotWaiting
