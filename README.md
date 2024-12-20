﻿# Appipum_VerCucumberWithNewServer

Bu proje, Appium ve Cucumber kullanarak çeşitli Android uygulamaları için otomatik testler yapmayı amaçlar. `/Apps` dizininde yer alan `.apk` dosyaları ile farklı uygulamalar test edilmektedir.

---

## Proje Yapısı

- **Apps**: Test edilecek uygulamaların APK dosyalarını içerir.
- **src/test/java**:
    - **pages**: Farklı uygulamaların arayüz yapısını ve etkileşimlerini temsil eden sayfa nesneleri içerir.
        - `Arabam`
        - `AllCurrency`
        - `HesapMakinesi`
        - `KiwiApp`
    - **runners**: Cucumber için test çalıştırıcıları içerir.

---

## Gereksinimler

- Java 11
- Maven
- Appium Sunucusu (yapılandırılmış ve çalışır durumda)
- Android SDK ve Android Sanal Cihaz (AVD) veya test için fiziksel cihaz
- Android Inspector 
---

## Bağımlılıklar

Proje aşağıdaki bağımlılıkları kullanmaktadır:

- **Cucumber**: Özellik dosyalarını ve senaryoları yazmak ve düzenlemek için.
- **Selenium Remote Driver**: Appium’da WebDriver işlevselliği için.
- **Appium Java Client**: Mobil uygulamalarla etkileşim kurmak için.
- **ExtentReports**: HTML raporları oluşturmak için.

Tüm bağımlılıklar `pom.xml` dosyasında yönetilmektedir.

---

 
    
 
