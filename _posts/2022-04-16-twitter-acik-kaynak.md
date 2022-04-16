---
layout: article
title: Twitter Algoritmasının Kaynak Kodunun Açılması Neleri Değiştirecek?
tags: ÖAKK Twitter Blokzincir
article_header:
  type: overlay
  theme: dark
  background_color: '#000'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(0, 0, 0, .7), rgba(0, 0, 0, .7))'
    src: /assets/images/twitter-acik.png
---

Geçtiğimiz günlerde Elon Musk, Twitter’ı 43 milyar dolara satın almayı teklif etmesiyle gündem oldu. Bunun üzerine katıldığı [TED konuşmasında](https://vid.puffyan.us/watch?v=cdZZpaB2kDM) da Twitter algoritmasının kaynak kodunu açıp GitHub’a yüklenmesiyle platformun saydamlaştırılması gerektiğini belirtti. Peki ya bunun faydaları neler?

ÖAKK (Özgür ve Açık Kaynak Kodlu) yazılımlar; kaynak kodunun çalıştırılması, incelenmesi, değiştirilmesi ve kopyalanmasına izin verir. Bu tür yazılımların kapalı kaynak yani mülki yazılımlara karşı kullanıcı tarafında artısı yazılımın erişilebilir ve güvenilir olmasıdır. Örneğin kapalı kaynak bir işletim sistemi olan Windows’da sistemin arkaplanda ne yaptığını (aktivitenizi izleyip devlet ve şirketlerle paylaşmak, yeni donanım almanız için zorunlu güncellemelerle sistemi yavaşlatmak vs.) bilemezken özgür ve açık kaynak olan Linux tabanlı işletim sistemlerinde sistem çekirdeği ve etrafındaki yazılımların kaynak kodları açık olduğu için içiniz rahat olabilir.

Twitter şu an kapalı kaynak bir sosyal medya platformu. Twitter’ın arayüzü, algoritması ve sunucu yazılımının kodları büyük oranda kapalı. Bu da verilerimizin nasıl kullanıldığı, taymımıza düşen içeriklerin ve önerilen kişilerin nasıl karşımıza çıktığı gibi konularda cahil kalmamıza sebebiyet veriyor. Eğer Twitter algoritması açık kaynak olursa ne değişecek? Algoritma halka açık olacak ve dışarıdan destek kabul edebilecek. Algoritmanın nasıl çalıştığını herkes bilecek, bu sayede platform kapalı olması durumunda algoritmayı bilen sayılı kişilerin manipülasyonuna maruz kalmayacak.

Ancak küçük bir sorun var: Twitter’ın kaynak kodu açık olan algoritmayı web tarafında kullandığından nasıl emin olabiliriz? Twitter şu anki haliyle merkezi yani Twitter şirketinin himayesindeki sunucularda bulunan bir platform olduğu için bunu bilmek imkansız. Halka açık olan algoritma kodu geçirgen bir açık kaynak lisansı altında olduğu sürece Twitter şirketi yasal olarak bu kodu modifiye edip kapalı şekilde web tarafına yüklediği vakit değişen bir şey olmayacak.

Bunun bir çözümü var, o da federatif ve adem-i merkezi sosyal medya platformları. Adem-i merkezi platformlar blokzincir veya fediverse gibi tek bir merkez yerine farklı merkezlerde veya doğrudan kullanıcılarda tutulan verileri federatif şekilde bir araya getirip ortaya bir ağ çıkarır. Örneğin [Mastodon](https://joinmastodon.org/); Twitter’a çok benzeyen, benim sık sık kullandığım federatif bir sosyal ağ. Mastodon tamamen özgür ve açık kaynak kodlu bir platform olduğu, aynı zamanda da tek bir merkez yerine fediverse protokolünü kullanarak birçok farklı sunucuda gönüllülerce barındırıldığı için algoritması ve kişisel verilerin mahremiyetine saygısı konusunda içim rahat.

Blokzincir tabanlı platformlar seviyeyi bir tık arttırıp hiçbir merkez olmadan tamamen kullanıcıların dijital varlıklarının zincir gibi birbirine bağlandığı bağlardan oluşuyor. Bu tarz platformlar Web 3.0'ı oluşturuyor. Örneğin [IPFS](https://ipfs.io/), merkezi sunuculara HTTP protokolü yerine adem-i merkezi düğümlere dayanan ancak her bir parçası birbirine zincir gibi kenetlenen kendi blokzincir tabanlı protokolünü kullanan, Web'i kökten değiştirmeyi amaçlayan adem-i merkezi bir platform. [Zeronet](https://zeronet.io/) ve [GNUnet](https://www.gnunet.org) de benzer şekilde çalışan platformlara örnek gösterilebilir.

---

Sonuç olarak Twitter algoritmasının kaynak kodunun açılması çok güzel bir haber olmakla beraber web tarafının özgür olduğundan emin olamadıkça pek bir şey değişmeyecek. Web tarafının özgür olması, kullanıcılar olarak neler döndüğünü bilmemiz ve kontrol edebilmemiz için platform tek bir merkez yerine birçok farklı merkezde yani federatif veya blokzincir tabanlı olmalı.


Yazar: [Tan Siret Akıncı](https://yutyo.github.io/)
