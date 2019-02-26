# For English click [here.](README.en.md)

Eğer SSH sunucunuzdaki web.itu.edu.tr adlı 'dosyayı' silerseniz web sitenizi görünteleyemezsiniz.

Çözüm için aşağıdaki adımları sırası ile izleyiniz.

SSH sunucunuzun terminaline erişin, bunu kullandığınız programın konsol kısmından veya linux terminalden bağlanarak gerçekleştirebilirsiniz.

Aşağıda verilen kodlarda [itüKullanıcıAdı] kısımlarını kendi kullanıcı adınız ile değiştiriniz. Örneğin: altinpinar18 gibi.

1. Terminal ile SSH'a bağlanma
```shell
ssh -p 22 [itüKullanıcıAdı]@ssh.itu.edu.tr
```
yazıp daha sonra şifrenizi giriniz.


2. Önceden birşeyler denemiş iseniz o dosyayı silmek için aşağıdaki kodu giriniz. __sonuna / koymayın!__
```shell
rm web.itu.edu.tr
```

3. 
```shell
ln -s ../../web.itu.edu.tr/[itüKullanıcıAdı] web.itu.edu.tr
```
