Proje: Euclidean Mesafesi Hesaplayıcı

Bu proje, iki boyutlu uzaydaki noktalar arasındaki Öklid mesafesini hesaplayan bir Python programı içermektedir. Program, iki boyutlu noktaları temsil eden bir listeye dayalı olarak, her nokta çifti arasındaki mesafeyi bulur ve en kısa mesafeyi ekrana yazdırır.
Dosyalar:

    öklid.py: Python kodunu içeren ana dosya.

Kullanılan Yöntemler:

    Euclidean Distance (Öklid Mesafesi): İki nokta arasındaki düz çizgi mesafesi aşağıdaki formülle hesaplanır:
    d=(x2−x1)2+(y2−y1)2
    d=(x2​−x1​)2+(y2​−y1​)2

    ​

Programın Genel Yapısı:

    points Listesi: Bu liste, uzaydaki noktaları temsil eder ve her bir nokta (x, y) şeklinde bir demet (tuple) olarak tanımlanır.
    euclideanDistance Fonksiyonu: Bu fonksiyon iki nokta alır ve aralarındaki Öklid mesafesini döndürür.
    Mesafelerin Hesaplanması: Program, her nokta çifti arasındaki mesafeyi hesaplar ve bu mesafeleri distances listesine ekler.
    Minimum Mesafe: distances listesinden minimum mesafe bulunur ve ekrana yazdırılır.

Kurulum ve Çalıştırma:

    Python'ın yüklü olduğundan emin olun.
    Programı çalıştırmak için terminalde şu komutu çalıştırın:

    bash

    python main.py

    Çalıştırıldığında, noktalar arasındaki minimum Öklid mesafesi ekrana yazdırılacaktır.

Gereksinimler:

    Python 3.x

Bu proje, basit geometrik hesaplamalar ve Python'da fonksiyonlar ve döngüler kavramlarını öğrenmek için uygun bir uygulamadır.
