# Hi there, I'm Hatice 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=6B5FF7&center=true&vCenter=true&width=435&lines=Software+Engineering+Student;42+T%C3%BCrkiye+Student;Full+Stack+Developer" alt="Typing SVG" />
</div>

## 👩‍💻 About Me

- 🎓 Software Engineering Student at Istinye University
- 💻 Currently studying at 42 Türkiye
- 🌱 I'm passionate about developing innovative solutions
- 🚀 Always eager to learn new technologies

## 🛠️ Tech Stack

<div align="center">
  
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

</div>

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ozkyhatice&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ozkyhatice&theme=tokyonight" alt="GitHub Streak" />
</div>

## 🚀 Featured Projects

### 📱 Mobile Development
#### [StreetPaws_MobilApp](https://github.com/ozkyhatice/StreetPaws_MobilApp)
A React Native-based volunteer platform designed to support stray animals by connecting volunteers, businesses, and organizations.
- 🔧 **Tech Stack**: React Native, Expo, TypeScript
- ⭐ **Key Features**: Task management, QR code scanning, Map integration, Donation system
- 🎯 **Status**: Active Development

### 🌐 Web Development
#### [Recipe Website](https://github.com/ozkyhatice/recipe-website)
- 💻 **Tech Stack**: PHP, MySQL
- 🔑 **Features**: Recipe sharing, user authentication, recipe categories
- 📝 **Description**: A platform for sharing and discovering recipes

### 📚 Library Management System
#### [Library Management System](https://github.com/ozkyhatice/library_management_system)
- 🔧 **Tech Stack**: C#
- 🎯 **Purpose**: Efficient book tracking and management
- ⚡ **Features**: Book cataloging, member management, borrowing system

## 🎓 42 École Projects

<div align="center">
  <img src="https://img.shields.io/badge/42-Projects-00599C?style=for-the-badge&logo=42&logoColor=white" alt="42 Projects"/>
</div>

### Core Projects
| Project Name | Description | Status | Score |
|--------------|-------------|---------|-------|
| [Libft](https://github.com/ozkyhatice/_LIBFT_) | Recreation of basic C library functions | ✅ Completed | 100 |
| [ft_printf](https://github.com/ozkyhatice/FT_PRINTF) | Recreation of printf function | ✅ Completed | 100 |
| [get_next_line](https://github.com/ozkyhatice/get_next_line) | Function that reads a line from a file descriptor | ✅ Completed | 100 |

### Advanced Projects
| Project Name | Description | Tech Stack |
|--------------|-------------|------------|
| [Minishell](https://github.com/ozkyhatice/MINISHELL) | A simple shell implementation | C |
| [Philosophers](https://github.com/ozkyhatice/philosophers) | Solution to dining philosophers problem | C |
| [FT_IRC](https://github.com/ozkyhatice/FT_IRC) | Internet Relay Chat server implementation | C++ |
| [Inception](https://github.com/ozkyhatice/Inception) | Docker-based service deployment | Docker, PHP |

### System Administration
| Project Name | Description | Skills Gained |
|--------------|-------------|---------------|
| [Born2beroot](https://github.com/ozkyhatice) | System administration and VM setup | Virtual Machine, Linux |

## 🤝 Connect with Me

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ozkyhatice)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/ozky.hatice)

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=ozkyhatice&color=blueviolet" alt="Profile Views" />
</div>

# StreetPaws Mobile App

StreetPaws, sokak hayvanlarına yardım etmek için oluşturulmuş bir mobil uygulamadır. Gönüllüler, görevleri üstlenebilir, tamamlayabilir ve sokak hayvanlarına yardım ederek XP kazanabilirler.

## Özellikler

- Görev yönetimi (görüntüleme, üstlenme, tamamlama)
- Kullanıcı kimlik doğrulama
- QR kod tarama
- Harita entegrasyonu
- Gönüllü profil sayfası
- Bağış sistemi

## Gereksinimler

- Node.js (v14 veya üzeri)
- npm (v6 veya üzeri)
- Expo CLI
- iOS için: Xcode (macOS)
- Android için: Android Studio ve JDK

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/ozkyhatice/StreetPaws_MobilApp.git
cd StreetPaws_MobilApp
```

2. Bağımlılıkları yükleyin:
```bash
npm install
```

3. Geliştirici istemcisini yükleyin:
```bash
npx expo install expo-dev-client
```

## Bağımlılıklar

Projenin ana bağımlılıkları şunlardır:

```
"dependencies": {
  "@react-navigation/bottom-tabs": "^6.5.11",
  "@react-navigation/native": "^6.1.9",
  "@react-navigation/native-stack": "^6.9.17",
  "expo": "~50.0.11",
  "expo-barcode-scanner": "~12.5.3",
  "expo-camera": "~13.2.1",
  "expo-dev-client": "~2.2.1",
  "expo-location": "~16.1.0",
  "expo-status-bar": "~1.6.0",
  "lucide-react-native": "^0.302.0",
  "react": "18.2.0",
  "react-native": "0.72.6",
  "react-native-maps": "1.7.1",
  "react-native-paper": "^5.11.1",
  "react-native-safe-area-context": "4.6.3",
  "react-native-screens": "~3.22.0",
  "react-native-vector-icons": "^10.0.0"
}
```

## Uygulamayı Çalıştırma

Uygulamayı geliştirme modunda başlatmak için:

```bash
npx expo start
```

Expo Go uygulaması ile test etmek için:

```bash
npx expo start --dev-client
```

iOS simülatöründe çalıştırmak için:

```bash
npx expo run:ios
```

Android emülatöründe çalıştırmak için:

```bash
npx expo run:android
```

## Notlar ve Sorun Giderme

1. İlk kurulum sırasında expo-dev-client yüklemek gereklidir:
   ```bash
   npx expo install expo-dev-client
   ```

2. iOS'ta "AirGoogleMaps dizini bulunamadı" hatası alırsanız, Google Maps yerine varsayılan harita sağlayıcısını kullanın.

3. QR kod tarayıcısı için kamera izinlerinin verildiğinden emin olun.

4. Expo'nun en son sürümünü kullanmak için düzenli olarak güncelleme yapmanız önerilir:
   ```bash
   npm install -g expo-cli
   ```

## Projeyi Hazırlama ve Derleme

Üretim için APK/IPA oluşturmak için:

```bash
eas build --platform android
eas build --platform ios
```

Önce EAS CLI'yi yüklemeniz gerekebilir:

```bash
npm install -g eas-cli
```

## Proje Yapısı

```
streetpaws/
├── assets/           # Görsel ve statik dosyalar
├── src/
│   ├── components/   # Yeniden kullanılabilir bileşenler
│   ├── contexts/     # React context dosyaları
│   ├── hooks/        # Özel hook'lar
│   ├── navigation/   # Navigasyon yapılandırması
│   ├── screens/      # Uygulama ekranları
│   ├── services/     # Veri ve API servisleri
│   └── types/        # TypeScript tip tanımlamaları
├── App.tsx           # Ana uygulama bileşeni
└── package.json      # Paket bağımlılıkları
```

## Lisans

MIT Lisansı

---
