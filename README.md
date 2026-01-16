# 🧮 Hesap Makinesi - Calculator

Basit ama kullanışlı, modern bir hesap makinesi uygulaması. Günlük hesaplamalarınızı kolayca yapabileceğiniz, temiz ve kullanıcı dostu bir arayüze sahip.

## ✨ Özellikler

- **🎨 Tema Desteği** - Dark ve Light tema arasında geçiş yapabilirsiniz. Seçtiğiniz tema kalıcı olarak saklanır.
- **📊 Hesaplama Geçmişi** - Yaptığınız tüm hesaplamalar otomatik olarak kaydedilir ve istediğiniz zaman tekrar kullanabilirsiniz.
- **🔬 Bilimsel Fonksiyonlar** - sin, cos, tan, karekök, logaritma ve daha fazlası.
- **📱 Mobil Uyumlu** - Her cihazda mükemmel görünür ve çalışır.
- **⌨️ Klavye Desteği** - Enter ile hesapla, Escape ile temizle.
- **💾 Kalıcı Veri** - Tarayıcıyı kapatıp açsanız bile verileriniz kaybolmaz.
- **🔢 Binlik Ayırıcı** - Büyük sayılar otomatik olarak formatlanır (örn: 5555 → 5,555)
- **🔊 Dokunma Sesi** - Her buton tıklamasında hoş bir ses efekti ile dokunma hissiyatı

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone <repo-url>
cd hesap-makinesi
```

2. Bağımlılıkları yükleyin:
```bash
npm install
```

3. Geliştirme sunucusunu başlatın:
```bash
npm run dev
```

4. Tarayıcınızda `http://localhost:5173` adresine gidin.

## 📦 Yapı

Proje standart bir React + Vite yapısına sahiptir:

```
hesap-makinesi/
├── src/
│   └── App.jsx          # Ana uygulama dosyası (tüm kod burada)
├── package.json
└── README.md
```

`App.jsx` dosyasını direkt olarak projenizin `src` klasörüne kopyalayabilirsiniz. Ekstra konfigürasyon dosyasına gerek yoktur.

## 🛠️ Teknolojiler

- **React** - UI kütüphanesi
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **Lucide React** - İkonlar
- **Web Audio API** - Ses efektleri

## 📝 Son Güncellemeler

- ✅ Binlik ayırıcı formatı eklendi (5555 → 5,555)
- ✅ Butonlara dokunma sesi eklendi
- ✅ Sayı formatlaması input, sonuç ve geçmiş alanlarında uygulandı
- ✅ Web Audio API ile performanslı ses efektleri

## 💡 Kullanım İpuçları

- Klavyeden Enter tuşuna basarak hesaplama yapabilirsiniz
- Escape tuşu ile ekranı temizleyebilirsiniz
- Geçmiş bölümünden önceki hesaplamalarınıza tek tıkla erişebilirsiniz
- Tema tercihleriniz otomatik olarak kaydedilir

---

**Made By Can** 💙
