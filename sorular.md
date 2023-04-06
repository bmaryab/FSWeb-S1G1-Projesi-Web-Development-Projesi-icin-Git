# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? 
Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir.
2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal, bir bulut sistemidir.
3. Neden bir branch oluşturuyoruz?
Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıkması halinde geri dönüp önceki versiyona kolaylıkla erişebiliriz. Bunun yanında projemizde bir versiyon çıkarttığımız zaman, her yeni versiyon için repository oluşturmak yerine bu versiyonlar için farklı branchler açabiliriz. Böylece versiyonları bir arada kolayca takip edip erişebiliriz.
4. Pull Request'in amacı nedir?
Pull Request, branch'ten sorumlu kişiden kodumuzu eklemesini istemektir. Ayrıca bu kişinin kodda neleri ekleyip çıkardığımzı da görebilir. Böylece düzenledğimiz kodu eklemeden önce değişiklikleri kontrol edebilir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Branch'ler arası geçiş yapmak için git checkout komutunu kullanırız. Main branch'e geçmek için terminale git checkout main yazarız.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklılıkları açıklayınız. Bu komutlar ne yapar açıklayınız.
git fetch: Kodu uzak depodan yerel depoya çeken bir komut.
git pull: Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komut.
git merge: Herhangi bir brach'te yaptığımız değişiklikleri main branch'imiz ile birleştirme veya entegre etme komutudur.
git fetch ile sadece uzaktaki kodları indirmiş oluruz ancak bunları kendi çalışmamızla birleştirmez. git pull ise hem bu kodları indirir, hem de lokaldeki kodlarımızı bu yeni gelen kodlarla eşleşecek şekilde günceller.
git pull = git fetch + git merge gibi açıklanabilir.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda merge conflict olur.
8. Merge conflict'i nasıl çözeriz?
Merge conflict olduğunda çakışma yaşayan kişiler bunu birlikte değerlendirip hangi kodla ilerleyeceklerine karar verir ve merge ederler.
