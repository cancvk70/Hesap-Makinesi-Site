# 🧮 Hesap Makinesi

Modern, akıllı ve mobil uyumlu hesap makinesi uygulaması.

## 📋 Özellikler

- ✨ Temiz ve modern tasarım
- 🌓 Dark/Light tema desteği (kalıcı)
- 📊 Hesaplama geçmişi (kalıcı)
- 📱 Tam mobil uyumlu
- 🔬 Bilimsel hesaplamalar
- ⌨️ Klavye desteği

## 🎨 Özelleştirme

### Tema Renkleri
`src/App.jsx` dosyasında tema renklerini değiştirebilirsiniz:

```javascript
// Dark tema ana rengi (satır 150-160)
bg-blue-600  // Mavi yerine istediğiniz renk

// Light tema ana rengi
bg-blue-500  // Değiştirilebilir
```

### Buton Düzeni
`src/App.jsx` içinde buton dizilerini düzenleyebilirsiniz:

```javascript
const buttons = [
  ['C', '(', ')', '÷'],
  ['7', '8', '9', '×'],
  // Buradan değiştirebilirsiniz
];
```

### Geçmiş Limiti
Kayıt sayısını değiştirmek için:

```javascript
if (newHistory.length > 20)  // 20 yerine istediğiniz sayı
```

### Varsayılan Tema
Başlangıç temasını değiştirmek için:

```javascript
const [theme, setTheme] = useState('dark');  // 'light' yapabilirsiniz
```

## 🚀 Kurulum

```bash
npm install
npm run dev
```

## 📦 Gereksinimler

- React 18+
- Tailwind CSS
- lucide-react

---

**Made By Can** 💙
