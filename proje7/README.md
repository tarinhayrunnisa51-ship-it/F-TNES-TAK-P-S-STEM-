# Fitness Takip Sistemi

Bu proje, Python ve SQLite veritabanı kullanarak basit bir fitness takip sistemi uygulamasıdır. Sporcuların kişisel bilgilerini, antrenman kayıtlarını ve kilo/yağ oranı gibi gelişim verilerini yönetmeyi amaçlar.

## Projenin Amacı

Fitness Takip Sistemi'nin temel amacı, sporcuların antrenman ve fiziksel gelişimlerini kolayca kaydedip takip edebilmelerini sağlamaktır. Bu sistem, sporcuların zaman içindeki ilerlemelerini gözlemlemelerine ve motivasyonlarını artırmalarına yardımcı olacak temel verileri sunar.

## Özellikler

-   **Sporcu Yönetimi:** Sporcuların adı, soyadı, cinsiyeti, boyu, ilk kilosu, güncel kilosu, güncel yağ oranı ve kayıt tarihi gibi bilgileri saklar.
-   **Antrenman Kayıtları:** Yapılan antrenmanların türünü (örn. Kuvvet Antrenmanı, Kardiyo) ve süresini kaydeder.
-   **Takip Kayıtları:** Hangi sporcunun, hangi antrenmanı ne zaman yaptığını ve bu antrenmanda ne kadar kalori yaktığını takip eder.
-   **Gelişim Takibi:** Sporcuların güncel kilo ve yağ oranı bilgilerini güncelleyerek zaman içindeki değişimlerini izlemeyi sağlar.
-   **Gelişim Raporu:** Sporcuların başlangıç ve güncel kiloları arasındaki farkı, ayrıca güncel yağ oranlarını gösteren özet bir rapor sunar.

## Nasıl Çalışır?

Proje, `sqlite3` modülünü kullanarak yerel bir SQLite veritabanı (`fitness_takip.db`) oluşturur ve yönetir. Tüm veritabanı işlemleri (tablo oluşturma, veri ekleme, güncelleme, sorgulama) Python kodunun içinden gerçekleştirilir.

## Kurulum ve Çalıştırma

Bu projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### Önkoşullar

-   Python 3.x yüklü olmalıdır. (Genellikle modern işletim sistemlerinde varsayılan olarak gelir veya kolayca kurulabilir.)
-   `sqlite3` modülü Python ile birlikte gelir, ek bir kurulum gerektirmez.

### Adımlar

1.  Yukarıdaki Python kodunu `proje_7_fitness_takip_sistemi.py` adıyla bir dosyaya kaydedin.

2.  Bir terminal veya komut istemcisi açın.

3.  Dosyayı kaydettiğiniz dizine gidin:
    ```bash
    cd c:\Users\hayru\OneDrive\Desktop\proje7
    ```

4.  Python betiğini çalıştırın:
    ```bash
    python proje_7_fitness_takip_sistemi.py
    ```

Bu komutu çalıştırdığınızda, `fitness_takip.db` adında bir veritabanı dosyası oluşturulacak (eğer yoksa), tablolar kurulacak, örnek veriler eklenecek ve konsola sporcu gelişim raporu yazdırılacaktır.

## Kullanılan Teknolojiler
-   **Python:** Betik dili olarak kullanılmıştır.
-   **SQLite3:** Hafif ve dosya tabanlı bir veritabanı sistemi olarak kullanılmıştır.