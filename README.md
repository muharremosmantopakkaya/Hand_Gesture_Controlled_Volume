# Hand_Gesture_Controlled_Volume

Bu proje, el hareketlerini kullanarak bilgisayarın ses seviyesini kontrol etmek için geliştirilmiş bir Python uygulamasıdır. El izleme ve hareket tespiti için Mediapipe kütüphanesi kullanılmıştır.

## Özellikler

- El izleme ve pozisyon tespiti
- Parmak sayısına göre ses kontrolü
- Ses seviyesi görselleştirme
- FPS (Kare Per Saniye) gösterimi

## Gereksinimler

- Python 3.x
- OpenCV
- Mediapipe
- PyCaw

## Kullanım

1. Öncelikle gerekli kütüphaneleri yükleyin:

    ```bash
    pip install opencv-python mediapipe pycaw
    ```

2. `VolumeHandControlAdvance.py` dosyasını çalıştırarak uygulamayı başlatın.

3. Elinizin konumunu ve parmaklarını kullanarak ses seviyesini kontrol edin.

## Nasıl Çalışır?

Uygulama, bilgisayar kamerasından alınan görüntüyü işleyerek el izleme ve pozisyon tespiti yapar. Eldeki pozisyonlara göre ses seviyesi belirlenir ve uygun şekilde ayarlanır. Parmakların konumu ve sayısı, ses seviyesinin artırılması veya azaltılması için kullanılır. Ayrıca, ekran üzerinde ses seviyesi görselleştirilir ve FPS bilgisi gösterilir.

## Dikkat Edilmesi Gereken Noktalar

- Programın düzgün çalışması için elin kamereaya net bir şekilde görünmesi gerekmektedir.
- Parmak sayısına göre ses seviyesinin kontrol edilmesi sağlanmalıdır.
- Ses seviyesi ayarlanırken parmak konumlarına dikkat edilmelidir.

## Ekran Görüntüsü

![Ekran Görüntüsü](videos/video.mp4)
