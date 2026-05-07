Fitness Takip Sistemi
Bu proje, Python ve SQLite veritabanını kullanarak basit bir fitness takip sistemi uygulamasıdır. Sporcuların kişisel seçimi, antrenman kayıtları ve kilo/yağ oranı gibi gelişimin yönetilmesini sağlar.

Projenin Amacı
Fitness Takip Sistemi'nin temel amacı, sporcuların antrenman ve fiziksel gelişimlerini kolayca kaydedip takip edebilmelerini sağlamaktır. Bu sistem, sporcuların zamanlarındaki ilerlemelerini gözlemlemelerine ve motivasyonlarını artırmalarına yardımcı olacak temel veriler sunar.

Özellikler
Sporcu Yönetimi: Sporcuların adı, soyadı, cinsiyeti, boyu, ilk kilosu, güncel kilosu, güncel yağ oranı ve kayıt tarihi gibi bilgileri saklar.
Antrenman Kayıtları: Yapılan antrenmanların tamamı (örn. Kuvvet Antrenmanı, Kardiyo) ve sürelerini destekleyecektir.
Takip Kayıtları: Hangi sporcunun, hangi antrenmanı ne zaman yaptığını ve bu antrenmanda ne kadar kalori yaktığını takip edeceğini.
Gelişim Takibi: Sporcuların güncel kilo ve yağ oranını alarak güncelleyerek zaman içindeki değişimlerinin izlenmesini sağlar.
Gelişim Raporu: Sporcuların başlangıç ​​ve güncel kiloları arasındaki fark, ayrıca güncel yağ oranlarını gösteren özet bir rapor sunar.
Nasıl Çalışır?
Proje, sqlite3modülü kullanarak yerel bir SQLite veri tabanı ( fitness_takip.db) oluşturur ve yönetir. Tüm veri tabanı işlemleri (tablo oluşturma, veri ekleme, güncelleme, sorgulama) Python'un işlenmesinden itibaren kalır.

Kurulum ve çalışma
Bu projeyi çalıştırmak için aşağıdaki adımları izleyin:

Önkuşullar
Python 3.x yüklü olmalıdır. (Genellikle modern işletim sistemleri varsayılan olarak gelir veya kolayca kurulabilir.)
sqlite3Modül Python ile birlikte gelir, ek bir kurulum yapılmaz.
Adımlar
Yukarıdakileri Python proje_7_fitness_takip_sistemi.pyyazarak bir dosyaya kaydedin.

Bir terminal veya komut açılıri açılır.

Dosyayı kaydettiğiniz dizine geçiş:

cd c:\Users\hayru\OneDrive\Desktop\proje7
Python'un çalıştırılması:

python proje_7_fitness_takip_sistemi.py
Bu çalıştırdığınızda, fitness_takip.dbkişisel veri dosyası oluşturulacak (eğer yoksa), tablolar kurulacak, örnek veriler eklenecek ve konsola sporcunun gelişim raporu yazdırılacaktır.

Kullanılan Teknolojiler
Python: Betik dili olarak kullanılmıştır.
SQLite3: Hafif ve dosya tabanlı bir veritabanı sistemi olarak kullanılmıştır.
