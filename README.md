# III-hafta-odevi


1.Task vs process- task vs Thread vs .. ve c# task vs thread vs .. kıyaslamalarını ve task haricinde diğer yöntemler nelerdir araştırınız.
2.Extension Nedir? --> Extra paket ekleme. <br/>
3.SQLite, bunu doğru şekilde (en güncel yol ile) nasıl kullanmalıyız? (Aktif halde kullanıp uygulama)


Task ve Thread Nedir? Farklılıkları Nelerdir? 

Task ve Thread async programlama yapısı ile kullanılan komutlardır. Task daha çok performansı artırmak amacı ile kullanılır. Thread değer döndürmez. Fakat Task için hem geriye döndürülecek değer alınıp hem de ContinueWith() komutu ile süreklilik sağlanabilir. Task’ın genel amacı; bir iş gerçekleştirilirken, o işin tamamlanmasını beklemeden başka bir işe başlamamız gerektiğinde kullanılır. Bekleyen iş gerekli komutlar ile tekrar çağırılmasına gerek olmadan tamamlanır.


Extension Nedir?

Genişletme metodları bir tip (integer veya string vb.) üzerinde herhangi bir değişiklik yapmadan o tipi kolayca genişletmemize olanak sağlayan bir yapıdır. Daha basit olarak anlatacak olursak tanımladığımız bu Genişletme Metodları özünde bildiğimiz static metodlardır. .Net Framework 3.5 ile kullanıma gelmişlerdir, .Net Frameworkte içerisinde bulunan ve tanımlamış olduğumuz her tip için uygulanabilmektedir.


Nasıl Genişleme metodu oluşturulur?

Genişletme metodlarını basit bir şekilde tanımlayacak olursak yapmamız gereken adımlar aşağıdaki gibi olacaktır.

1. Public static bir sınıf oluşturulur.
2. Yapmak istediğiniz işlemleri gerçekleştirecek metod yazılır.
3. Fonksiyon genişleme metoduna dönüştürülür.




