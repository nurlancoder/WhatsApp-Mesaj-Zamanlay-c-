# WhatsApp Mesaj Zamanlayıcı

Belirli bir tarih ve saatte WhatsApp mesajlarını otomatik olarak göndermek için geliştirilmiş, Python tabanlı bir grafik kullanıcı arayüzü (GUI) uygulaması. Bu uygulama `tkinter` kütüphanesi ile arayüz, `pywhatkit` ile WhatsApp mesajlarını gönderme, ve `schedule` ile görevleri zamanlama işlemlerini gerçekleştirir.

## Özellikler

- WhatsApp mesajlarını belirli bir tarih ve saatte gönderme.
- Gönderim zamanı bir dakikadan kısa süre kalmışsa otomatik ayarlama.
- Mesajları kolayca zamanlamak ve yönetmek için entegre edilmiş bir GUI.

## Gereksinimler

Aşağıdaki kütüphanelerin yüklü olduğundan emin olun:

- `tkinter`: Python ile birlikte gelir (standart kütüphane).
- `pywhatkit`: Yüklemek için `pip install pywhatkit` komutunu çalıştırın.
- `schedule`: Yüklemek için `pip install schedule` komutunu çalıştırın.

Ek olarak, `pywhatkit` mesajları göndermek için varsayılan tarayıcınızda WhatsApp Web'e giriş yapmış olmanızı gerektirir.

## Kurulum
1. Bu projeyi klonlayın:
   git clone https://github.com/kullanici-adi/whatsapp-mesaj-zamanlayici.git

2. Gerekli kütüphaneleri yükleyin:
  pip install pywhatkit schedule

3. Projeyi çalıştırın:
   python main.py

Kullanım
Telefon Numarası: Gönderilecek numarayı girin (Türkiye dışındaysa ülke kodunu ekleyin; aksi takdirde "+994" eklenir).
Mesaj: Gönderilecek mesaj metnini girin.
Tarih: YYYY-AA-GG formatında tarihi girin (örneğin: 2024-12-31).
Saat: HH
formatında saati girin (örneğin: 14:30).
"Mesajı Zamanla" düğmesine bastığınızda, mesajınız belirtilen tarih ve saatte gönderilmek üzere zamanlanır.

Not
schedule modülü kullanılarak her saniye programda zamanlanmış görevler kontrol edilir.
pywhatkit, mesaj gönderirken tarayıcıyı açacak ve WhatsApp Web’i kullanarak mesajı gönderecektir.
Katkıda Bulunma
Bu projeye katkıda bulunmak isterseniz lütfen önce bir issue açın, ardından pull request gönderin.

Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına göz atın.
Bu `README.md`, projenin açıklamasını, gerekli kütüphaneleri ve kurulumu içerir. Ayrıca, kullanıcının projeyi nasıl çalıştırabileceği ve kullanabileceği hakkında bilgiler de sunar.
