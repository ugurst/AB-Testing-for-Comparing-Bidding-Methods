# AB-Testing-for-Comparing-Bidding-Methods
 Bu proje, Facebook'un "maximum bidding" ve "average bidding" teklif türlerinin performansını karşılaştırmak için tasarlanmış bir A/B testi uygulamasını içerir. Ana hedef, bu iki teklif türünün dönüşüm oranları arasındaki farkı analiz etmek ve hangi metodun daha etkili olduğunu belirlemektir.

# İş problemi

Facebook kısa süre önce mevcut "maximum bidding" adı verilen teklif verme türüne alternatif olarak yeni bir teklif türü olan "average bidding"’i tanıttı.

Müşterilerimizden biri olan bombabomba.com, bu yeni özelliği test etmeye karar verdi ve average bidding'in maximum bidding'den daha fazla dönüşüm getirip getirmediğini anlamak için bir A/B testi yapmak istiyor.

A/B testi 1 aydır devam ediyor ve bombabomba.com şimdi sizden bu A/B testinin sonuçlarını analiz etmenizi bekliyor.
---.com için nihai başarı ölçütü Purchase'dır. Bu
nedenle, istatistiksel testler için Purchase metriğine odaklanılmalıdır.

Bir firmanın web site bilgilerini içeren bu veri setinde kullanıcıların gördükleri ve tıkladıkları reklam sayıları gibi bilgilerin yanı sıra buradan gelen kazanç bilgileri yer almaktadır. Kontrol ve Test grubu olmak üzere iki ayrı veri seti vardır. Bu veri setleri ab_testing.xlsx excel’inin ayrı sayfalarında yer almaktadır. Kontrol grubuna Maximum Bidding, test grubuna Average Bidding uygulanmıştır.


	4 Değişken		 	40 Gözlem		 	26 KB	


Impression	Reklam görüntüleme sayısı
Click	Görüntülenen reklama tıklama sayısı
Purchase	Tıklanan reklamlar sonrası satın alınan ürün sayısı
Earning	Satın alınan ürünler sonrası elde edilen kazanç

Veri seti gizli tutulmuştur.
