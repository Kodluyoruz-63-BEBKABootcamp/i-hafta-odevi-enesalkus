# 24 Ekim Ödevleri
Bakılması/yapılması istenen şeyler:

## Hesaplarım:
* [HackerRank](https://www.hackerrank.com/enesalkus)
* [StackOverFlow](https://stackoverflow.com/users/14515392/enes-alku%c5%9f)

## Docker nedir ve Docker'a ait kavramlar nelerdir?
> #### Docker Nedir: 
> Docker, geliştirme ekiplerinin her yerde uygulamalar oluşturup yönetmesine ve güvenli hale getirmesine olanak tanıyan yeni bir teknolojidir.
> #### Docker Container Nedir:
> Docker Container'lar docker imajlarının çalışan örnekleridir. Bir imajı çalıştırmak bir docker container oluşturur. İmajlar container oluşturmakta kullanılabilecek bir şablon sağlar. Container oluşturmak için neyin gerektiğinin bilgisini içerirler. İmajlar yerel olarak veya uzakta depolanabilir.
> #### Docker Image Nedir:
> Docker image adından da anlaşılacağı gibi çalışacak uygulamanızın ve uygulamanızın altyapısında çalışan gerekli işletim sistemi kütüphanelerinin bulunduğu bir yapıdır. İmajları, container yaratmak için gereken talimatların bulunduğu bir şablon olarak düşünebiliriz. docker image build komutu ile bir Dockerfile üzerinden oluşturduğumuz yapılardır.
> #### Docker Registry Nedir:
> İmajların tutulduğu ve dağıtıldığı bir ortamdır. Aynı Github'da olduğu gibi elimizdeki imajları docker registry'sine push edebilir veya daha önceden yüklenmiş olan bir docker imajı kendi localimize çekebiliriz. Bu sayede ihtiyaçlarınızı karşılayacak bir imaja çok hızlı bir şekilde erişebilir, gerekirse üzerinde değişiklik yapabilir ve tag'leyerek farklı bir versiyon olarak yeniden gönderebiliriz.

## .Net Core versiyonları ve bu versiyonlar arasındaki farklar
> #### .NET Core 1.0 :
> - .NET Core 1.0 platformlardan tamamen bağımsız olacak şekilde geliştirilmiştir.
> - MVC ve Web API birleştirildi ve MVC controller’lar kullanıma sunuldu. Bu sayede tek projede ikisinden de yararlanma imkânı oluşuyor.
> - Modüler bir alt yapıya sahip olduğundan dolayı istemediğimiz etmenleri çıkarıp, istemediğimizi kullanmamızı sağlıyor.
> - config ve XML yerine JSON bazlı yapılandırma belirlenmiş.
> - .NET Core 1.0’ın en önemli özelliklerinden biri de Tag helpers’tır. Razon dosyalarındaki HTML elementlerini manipüle ederek ya da ekleyerek C# kullanabilme imkânı sağlıyor.

> #### .NET Core 2.0 :
> - C# ve F#'ı desteklemektedir.
> - .NET Core Visual Basic 2017'yi desteklemektedir.
> - Çeşitli yeni özellikler ekleyen C# 7.1'i destekler.
> - .NET Core'u yüklemeyi ve desteklenen işletim sistemlerinde kullanmayı kolaylaştıran birçok özellik içerir.
> - .NET Core 2.0'da mevcut olan API'lerin toplam sayısı, .NET Core 1.1 ile karşılaştırıldığında iki katına çıkar.

> #### .NET Core 3.0 :
> En büyük geliştirmelerden biri, Windows Masaüstü uygulamaları için destek içerir (yalnızca Windows). .NET Core 3.0 SDK bileşeni Windows Masaüstünü kullanarak Windows Forms ve Windows Presentation Foundation (WPF) uygulamalarınızın bağlantı noktası oluşturabilirsiniz.

> #### .NET Core Çıkış Tarihleri;
> - `.NET Core 1.0`	: `27 Haziran 2016`
> - `.NET Core 1.1`	: `16 Kasım 2016`
> - `.NET Core 2.0`	: `14 Ağustos 2017`
> - `.NET Core 2.1`	: `30 Mayıs 2018`
> - `.NET Core 2.2`	: `04 Aralık 2018`
> - `.NET Core 3.0`	: `23 Eylül 2019`
> - `.NET Core 3.1`	: `03 Aralık 2019`

## .Net 5 geçilme ihtiyaçları nelerdir, geçiş sürecinin tamamlanmasıyla neler hedeflenmektedir.
> Neden .NET 5’e geçme ihtiyacı duyulduğunu gelecek olan yeniliklerin cevap
olacağını düşünüyorum. .NET 5’in asıl amacı .NET Core, .NET Framework,
Xamarin ve Mono platformlarını tek bir çatı altına toplamak. Bundan önce ki
.NET platformları gibi ayrı ayrı platformlar arasında çalışmak yerine .NET 5 ile
tek platform üzerinden tüm framework’lere erişim sağlayabileceğiz. Bununda
çoklu platformların öğrenimini ve çalışma zamanını hızlandıracağı temel hedefi
denilebilir.


## Markdown yazımı ve kullanımı
> #### Tanımı
> En basit tanımı ile, web yazarları için text-to-HTML (metinden HTML’e) dönüştürme aracıdır. Markdown tasarımının temel hedefi geliştiricileri tarafından okunulabilirlik (readability) olarak belirtilmektedir.
> #### Kullanımı
```
<ul> ve <li> etiket kullanmak yerine liste yapmak istersek şöyle yapabiliriz;
- liste 1
- liste 2
- liste 3

Düzenli (sayılı) liste yapmak için ise şu formatı kullanabilirsiniz;
1. test
2. test 2
    1. test 2.1
3. test 3

<a> etiketi yerine markdown'da şöyle bir kullanım var;
[Link Başlık](https://link.com)

Resim göstermek için kullanım şöyle;
![](https://resim.com/yol)

<blockquote> etiketini kullanmak için metnin başına > işareti koymanız yeterli.
> bu alan ve
> bu alan alıntı içeriği temsil ediyor
```

## Yazılım alanında takip ettiğiniz kişiler kimlerdir?
- Şadi Evren ŞEKER [LinkedIn](https://www.linkedin.com/in/sadiseker/)
- Selman KAHYA [LinkedIn](https://www.linkedin.com/in/selmankahya/) 

## Microsoft Azure tarafında ne gibi hizmetler vardır?
> * Ağ İletişimi : Buluttaki ve şirket içindeki altyapı ve hizmetler arasında bağlantı
kurarak müşterilerimize mümkün olan en iyi deneyimi sunabiliriz.
> * Analiz : Herhangi bir türdeki, hacimdeki veya hızdaki verileri toplayabilir,
depolayabilir, işleyebilir, analiz edebilir ve görselleştirebiliriz.
> * Bilgi İşlem : Bulut işlem kapasitesi ve isteğe bağlı ölçeklendirme özelliklerine
erişim elde edebilir ve sadece kullandığımız kaynaklar için ödeme yapabiliriz.
> * Blok Zinciri : Tümleşik araç paketiyle blok zinciri tabanlı uygulamalar derleyebilir
ve yönetebiliriz.
> * Depolama : Verilerimiz, uygulamalarımız ve iş yüklerimiz için büyük oranda
ölçeklenebilir, güvenli bir bulut depolama alanı edinebiliriz.
> * DevOps : Sürekli teslimatlar için basit ve güvenilir araçlarla yenilikleri daha hızlı
bir şekilde sunabiliriz.
> * Geçiş : Kılavuzlar, araçlar ve kaynaklar sayesinde buluta geçişimizi
kolaylaştırabilir ve hızlandırabiliriz.
> * Geliştirici Araçları : Dilediğimiz platform veya dili kullanarak bulut uygulamaları
oluşturabilir, yönetebilir ve bu uygulamaları sürekli olarak kullanıma sunabiliriz.
> * Güvenlik : Kuruluşumuzu hibrit bulut iş yüklerinde gelişmiş tehditlere karşı
koruyabiliriz.
> * Hibrit : Azure yeniliğine her yerde kullabiliriz. Bulut bilişimin çevikliğini ve
yeniliğini şirket içi iş yüklerimize taşıyabiliriz.
> * Kapsayıcılar : Tümleşik araçları kullanarak kapsayıcılı uygulamalarımızı daha hızlı
geliştirebilir ve yönetebiliriz.
> * Karma Gerçeklik : Kapsamlı ve işbirliğine dayalı deneyimler oluşturmak için
fiziksel ve dijital dünyalarımızı bir araya getirebiliriz.
> * Kimlik : Cihazlarda, verilerde, uygulamalarda ve altyapıdaki gelişmiş tehditlere
karşı korunmak için kullanıcı kimliklerini ve erişimi yönetebiliriz.
> * Medya : İstediğimiz yerde, istediğimiz zaman, istediğimiz cihazda yüksek kaliteli
video içerikleri sunabiliriz.
> * Mobil : Tüm mobil cihazlara yönelik platformlar arası ve yerel uygulamalar
oluşturup dağıtabiliriz.
> * Nesnelerin İnterneti : Altyapımızı değiştirmeksizin herhangi bir cihaza ve
platforma IOT özellikleri ekleyebiliriz.
> * Tümleştirme : Şirket içi ve bulut tabanlı uygulamalarımızı, verilerimizi ve
işlemlerimizi kuruluşumuzun tamamıyla sorunsuz şekilde tümleştirebiliriz.
> * Veritabanları : Güvenli, kurumsal sınıf ve tam olarak yönetilen veritabanı
hizmetleriyle daha hızlı bir şekilde yenilik gerçekleştirebiliriz.
> * Web : Güçlü web uygulamalarımı hızlı ve verimli bir şekilde oluşturabilir,
dağıtabilir ve ölçeklendirebiliriz.
> * Windows Sanal Masaüstü : Azure’da sunulan en iyi sanal masaüstünü
deneyimleyebiliriz.
> * Yapay Zeka ve Makine Öğrenimi : Herhangi bir geliştirici ve herhangi bir senaryo
içi yapay zeka özelliklerini kullanarak yeni nesil uygulamalar oluşturabiliriz.
> * Yönetim ve İrade : Bulut kaynaklarımızın yönetimini ve uyumluluğunu
basitleştirme, otomatikleştirme ve iyileştirme olanağımız bulunmakta.


