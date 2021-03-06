---
title: VS Code'da Github Deposuna Proje Aktarmak
subtitle: >-
  Merhaba arkadaşlar, günümüzde birçok proje VS Code ile yazılmakta. Ve bu
  projeleri GitHub depolarında saklıyoruz. Peki yeni başlayanlar için bu
  bağlantıyı nasıl sağlayacağız ve güncellemeleri nasıl yapacağız bunu
  öğreneceğiz.
date: '2021-01-30'
thumb_img_alt: ''
content_img_alt: ''
excerpt: ''
canonical_url: ''
author: ihsansunman
template: post
thumb_img_path: images/git0.png
content_img_path: images/git0.png
---
Öncelik olarak VS Code üzerinden yeni bir depo oluşturalım. Sol menüden "Source Control" kısmına girerek "Publish to GitHub"  butonuna tıklayarak üst kısımda çıkan bölmeden ayarlamaları yaparak depoyu oluşturuyoruz.

![](https://raw.githubusercontent.com/asnuscom/asnus/master/static/images/git1.png)


Daha sonrasında yeni bir terminal başlatmak adına yukarıdaki menüden  Terminal > New Terminal tuşlamalarını yaparak terminalimizi başlatalım.  Açılan terminale daha öncesinde de [şu konuda](https://asnus.com/posts/projede-git-kullanici-adi-ve-epostasi-nasil-degistirilir/) bahsettiğimiz gibi GitHub kullanıcı adı ve mail adreslerimizi ayarlıyalım.

```

git config user.name "KULLANICIADI"
git config user.email "KULLANICIADI@MAIL.COM"
git remote add origin https://github.com/ihsansunman/test.git
git branch -M main
git push -u origin main

```

Artık dosyalarımızın GitHub depomuzda olduğunu göreceksiniz. Ayarlamalarımızı da yaptıktan sonra düzenlemelerimizi işlemek (commit) için yine "Source Control" üzerinden aşağıda bulunan görselde "MESAJINIZ" yazan yere yapılan değişiklikleri yazarak yukarıda bulanan tik (check) işaretine basarak değğişiklerimizi ayarlıyalım. Ve en son halini görselde bulunan "Push" seçeneği ile GitHub ile eşitleyelim. Artık bu şekilde deponuzu güncelleyebilirsiniz.

![](https://raw.githubusercontent.com/asnuscom/asnus/master/static/images/git2.png)

İyi Kodlamalar.
