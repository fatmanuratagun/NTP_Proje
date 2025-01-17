# Kart Oyunu

Bu, C# ile geliştirilen konsol tabanlı bir kart oyunudur. Oyunda kullanıcı ve bilgisayar arasında beş tur boyunca bir kart savaşı yapılır.
Her turda yüksek değere sahip kart raundu kazanır. Oyunun sonunda toplam puanlara göre kazanan belirlenir.

---

## Özellikler

- 20 kartlık bir deste oluşturulur ve karıştırılır.
- Kullanıcı ve bilgisayara 5'er kart dağıtılır.
- Kullanıcı, elindeki kartlardan birini seçerken bilgisayar rastgele bir kart oynar.
- Her raund sonunda kazanan belirlenir ve raund kazanan sayısı güncellenir.
- Oyun sonunda toplam sonuçlar gösterilir.
- Renkli konsol çıktıları ve ses efektleriyle daha eğlenceli bir deneyim sunar.

---

## Gereksinimler

- **.NET Framework**: 6.0 veya üzeri bir sürüm.
- **Windows** işletim sistemi (ses efektlerini oynatmak için `SoundPlayer` kullanılmaktadır).
- **Visual Studio** veya başka bir IDE kullanabilirsiniz.

---

## Gerekli müzik dosyalarını ekleyin

- Aşağıdaki dosyaları temin edin ve projenin çalışacağı bilgisayarın C:\Users\\[KullanıcıAdı]\Downloads dizinine kopyalayın:

Alkış sesi: applause-236785.wav

Kaybetme sesi: Aaa - Üzülme Ses Efekti.wav

---

## Nasıl Oynanır?

1.Oyun başladığında kartlar otomatik olarak dağıtılır.

2.Kullanıcıya, elindeki kartlar listelenir. Hangi kartı oynamak istediğini seçmesi istenir.

3.Bilgisayar rastgele bir kart oynar.

4.Her raund sonunda kazanan belirlenir.

5.Beş raundun sonunda oyun sonuçları görüntülenir.

6.Oyuncu, yeni bir oyun başlatmak isteyip istemediğini seçebilir.

---

## Geliştirici Notları

**1.Renk Ayarları:**

KartCiz(int deger, string renk) metodu ile kartların rengini değiştirebilirsiniz.

**2.Ses Dosyaları:**

SoundPlayer kullanıldığı için yalnızca .wav formatındaki ses dosyalarını kullanabilirsiniz. Farklı ses formatlarını desteklemek için başka bir ses kütüphanesi entegre edebilirsiniz.




