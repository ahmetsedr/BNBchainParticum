## Blok Zincirinin Temellerini Anlamak maddeler halinde :
* Blok zinciri, bir veri yapısıdır ve birçok bilgisayar tarafından kullanılan bir paylaşımlı defter olarak düşünülebilir.
* Her blok, birçok işlemi içerir ve bir önceki bloğa bağlıdır. Bu, her işlemin geri dönülemez olduğu anlamına gelir.
* Blok zinciri, güvenli ve merkezi olmayan bir sistemdir. Bu, herhangi bir tek noktanın kontrolünün olmadığı anlamına gelir.
* Blok zinciri, kriptografik fonksiyonlar kullanarak güvenliğini sağlar. Bu, işlemlerin doğruluğunu ve bireylerin hesaplarının güvenliğini sağlar.
* Blok zinciri, özellikle de Bitcoin ve diğer kripto paralar için kullanılır. Ancak, diğer uygulamalar için de kullanılabilir, örneğin finans, sağlık, e-ticaret vb.

## Blok Zincirinin Temellerininin elemanları nelerdir ? 

* Bloklar: Her blok, birçok işlemi içerir ve bir önceki bloğa bağlıdır. Her blok, ayrıca bir zorluk derecesi, bir nonce ve bir madencilik ödülü içerir.

* işlemler: Her işlem, bir gönderici, bir alıcı ve bir miktar gibi bilgileri içerebilir. işlemler, bloklar arasında taşınır ve blok zincirinin temel yapı taşıdır.

* Hash: Her blok, bir önceki bloğun hash değerini içerir. Bu, bloklar arasındaki bağlantıyı sağlar ve geri dönüşümü engellemek için kullanılır.

* Kriptografi: Blok zinciri, kriptografik fonksiyonlar kullanarak güvenliğini sağlar. Bu, işlemlerin doğruluğunu ve bireylerin hesaplarının güvenliğini sağlar.

* Madencilik: Madencilik, blokların oluşturulmasını ve işlemlerin onaylanmasını sağlar. Madenciler, belirli bir zorluk derecesine ulaşmak için bilgisayarlarını kullanır ve ödül olarak madencilik ödülü kazanır.

* Konsensüs: Blok zinciri, merkezi olmayan bir sistemdir ve işlemleri onaylamak için bir konsensüs mekanizması kullanır. Bu, işlemlerin doğruluğunu ve bireylerin hesaplarının güvenliğini sağlar.

## Blok nedir ve yapısı nedir?

Blok, blok zinciri veri yapısının temel birimidir. Her blok, birçok işlemi içerebilir ve bir önceki bloğa bağlıdır. Bu, her işlemin geri dönülemez olduğu anlamına gelir.

Blokların yapısı genellikle şöyle olabilir:

* Başlık: Blokların başlığı, blok zincirinin genel yapısını tanımlayan bilgileri içerir. Başlık, önceki bloğun hash değerini, zorluk derecesini, nonce değerini ve madencilik ödülünü içerebilir.

* işlemler: Her blok, birçok işlem içerebilir. işlemler, blok zincirinin temel yapı taşıdır ve bir gönderici, bir alıcı ve bir miktar gibi bilgileri içerebilir.

* Hash: Her blok, kendine özgü bir hash değerine sahiptir. Bu, bloklar arasındaki bağlantıyı sağlar ve geri dönüşümü engellemek için kullanılır.

* Merkle root: işlemlerin güvenliğini ve doğruluğunu sağlamak için bloklar, Merkle ağacı yapısını kullanabilir. Bu, her işlem için bir hash değeri oluşturur ve bunları bir ağaç yapısına dizer.

* Kriptografi: Bloklar, kriptografik fonksiyonlar kullanarak güvenliğini sağlar. Bu, işlemlerin doğruluğunu ve bireylerin hesaplarının güvenliğini sağlar.

### Günlük Hayyattan örnek verilirse 

* Başlık: Örneğin bir online alışveriş sitesinde yaptığınız bir satın alma işlemi, o satın almanın detaylarını içeren bir blok oluşturur. Başlık, önceki bloğun hash değerini, zorluk derecesini, nonce değerini ve madencilik ödülünü içeremez fakat önceki işlemlerin referansını içerebilir.

* işlemler: Örneğin, bir banka hesabından başka bir banka hesabına para transferi yaparken, işlemler blok olarak kaydedilir. işlemler, blok zincirinin temel yapı taşıdır ve gönderen hesap numarası, alıcı hesap numarası ve transfer edilen miktar gibi bilgileri içerebilir.

* Hash: Her blok, kendine özgü bir hash değerine sahiptir. Bu, bloklar arasındaki bağlantıyı sağlar ve geri dönüşümü engellemek için kullanılır. Örneğin, bir online alışveriş sitesinde yaptığınız bir satın alma işlemi, o satın almanın hash değerini içererek diğer işlemlerle bağlantılı hale getirir

* Merkle ağacı: Örneğin, bir sağlık platformunda kullanıcıların sağlık verileri, Merkle ağacı yapısını kullanarak güvenli ve doğrulanmış şekilde saklanabilir. Bu, her veri için bir hash değeri oluşturur ve bunları bir ağaç yapısına dizer.

* Kriptografi: Örneğin, bir online bankacılık uygulamasında kullanıcıların hesap bilgileri, kriptografik fonksiyonlar kullanarak güvenli bir şekilde saklanabilir. Bu, işlemlerin doğruluğunu ve kullanıcıların hesaplarının güvenliğini sağlar.

## bloklar birlikte nasıl değiştirilir?

Bloklar, bir hash işaretçisi kullanarak birbirlerine bağlanır.
Her blok, önceki bloğun hash değerine referans içerir.
Bu, blokların kronolojik bir sıraya bağlı olarak bir zincir oluşmasını sağlar.
Her blok için oluşan hash değerleri benzersizdir.
Herhangi bir blokta yapılan değişiklik, onun hash değerini değiştirecektir ve böylece tüm bloğun zincirinde değişecektir.
Bu mekanizma, blok zincirindeki herhangi bir işlemi geri dönüşümsüz hale getirir ve aynı zamanda bloğun değiştirilmesini önler.

<img src="https://cdn-images-1.medium.com/max/1600/1*aGxmgvg8XTsuqRnQkfj_aQ.jpeg">

## Dağıtılmış Defter ve Blok Zinciri Şeffaflığı

Kısaca Blockchain birden fazla bilgisayar tarafından kontrol edilir ve otorite yoktur.

### Database vs Blockchain

- Data Base :

** merkezileştirilmiş
** Hızlı
** değişken

- Blockchain

** merkezi olmayan
** Yavaş
** değişmez

- Pros and Cons

* Artıları
** Güvenlik
** Transparency
** şeffaflık
** ademi merkeziyetçilik

* Eksileri
** Performans
** karmaşıklık
** Kontrol
** İşlem hızı

## İzinsiz ve İzin Verilen Blockchain Türler

* İzinsiz Blockchain: Bu tür blockchaing, herhangi bir merkezi otoriteye ihtiyaç duymadan çalışır. Bu, herkesin işlemleri onaylamasına ve yeni blokların eklenmesine izin verir. Bitcoin ve Ethereum gibi kamuya açık blockchainler izinsiz blockchaining örnekleridir.

* İzin Verilen Blockchain: Bu tür blockchaining, işlemleri gerçekleştirmek için merkezi bir otoriteye ihtiyaç duyar. Bu, işlemlerin onayının veya yeni blokların eklenmesinin sadece belirli kişilerce yapılmasına izin verir. Örneğin, bir banka için kullanılan bir blockchain izin verilen blockchaining örneklerinden biridir.

Genellikle İzinsiz blockchainler daha güvenlidirler ve verilerin manipüle edilme riski daha düşüktür. İzin verilen blockchainler ise daha kontrollü ve veri erişiminin sınırlandırılmasına olanak sağlar.

