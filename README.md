<div align="center">

# 📝 PersonelNotes

**Node-RED ve MongoDB tabanlı düşük kodlu (low-code) çözümlerle kişisel verilerinizi ve notlarınızı zahmetsizce yönetin, otomatikleştirin.**

[![GitHub Stars](https://img.shields.io/github/stars/UmutGuvenUslu/PersonelNotes?style=for-the-badge&color=blue)](https://github.com/UmutGuvenUslu/PersonelNotes/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/UmutGuvenUslu/PersonelNotes?style=for-the-badge&color=teal)](https://github.com/UmutGuvenUslu/PersonelNotes/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

## 🎯 Neden PersonelNotes?

> Dağınık notlardan, katı organizasyon yapılarından ve kişisel verilerinizi birbirine bağlayamamaktan sıkıldınız mı? Geleneksel not alma uygulamaları; dinamik veri ilişkileri, özel otomasyonlar veya basit metin dosyalarının ötesinde ölçeklenebilir bir depolama gerektiğinde genellikle yetersiz kalır.

**PersonelNotes**, Node-RED'in görsel programlama gücünü MongoDB'nin esnek doküman modeliyle birleştirerek bu sorunu çözer. Kendi not akışlarınızı tasarlamanıza, veri girişini otomatikleştirmenize ve bilgilerinizin güvenli, esnek ve hızlı sorgulanabilir bir şekilde saklanmasına olanak tanır.

---

## ✨ Temel Özellikler

* **⚡ Akış Tabanlı Veri Yönetimi (Flow-Based):** Notların nasıl yakalanacağını, işleneceğini ve saklanacağını Node-RED sürükle-bırak arayüzü ile görsel olarak tasarlayın.
* **💾 Kalıcı MongoDB Depolaması:** Notlarınızı ve ilişkili verilerinizi NoSQL doküman tabanında güvenle saklayın.
* **🤖 Güçlü Otomasyon Desteği:** Notlara bağlı veri girişlerini, hatırlatıcıları, çapraz referansları veya anlık bildirim tetikleyicilerini otomatikleştirin.
* **🛠️ Özelleştirilebilir İş Akışları:** Sistemi kendi not alma alışkanlıklarınıza ve iş modelinize göre kolayca uyarlayın.
* **🚀 Düşük Kod (Low-Code) Geliştirme:** Minimum kod yazarak Node-RED üzerinden hızlıca gelişmiş veri akışları inşa edin.
* **🔍 Hızlı ve Esnek Sorgulama:** İhtiyacınız olan notları ve verileri anında filtreleyip görüntüleyin.

---

## 🏗️ Teknik Mimari

| Teknoloji | Kullanım Amacı | Temel Avantaj |
| :--- | :--- | :--- |
| **Node-RED** | Görsel Programlama Ortamı & Akış Motoru | Hızlı prototipleme, düşük kod ve sezgisel iş akışı tasarımı |
| **MongoDB** | NoSQL Doküman Veritabanı | Esnek şema, yüksek ölçeklenebilirlik ve zengin sorgulama |
| **Node.js** | JavaScript Çalışma Zamanı (Runtime) | Yüksek performans, asenkron G/Ç ve zengin npm ekosistemi |

### Dizin Yapısı

```plaintext
PersonelNotes/
├── 📄 .gitignore
├── 📄 README.md
├── 📄 flows.json          # Node-RED ana akış ve mantık tanımları
├── 📄 flows_cred.json     # Şifrelenmiş kimlik/bağlantı bilgileri
└── 📄 package.json        # Bağımlılıklar ve proje betikleri
```

---

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler

Başlamadan önce sisteminizde aşağıdakilerin kurulu olduğundan emin olun:

* **Node.js**: Sürüm 14.x veya üzeri ([Node.js İndir](https://nodejs.org/))
* **npm**: Node.js ile birlikte kurulu gelir.
* **MongoDB**: Yerel veya uzak bir MongoDB sunucusu (varsayılan port `27017`).

---

### Kurulum Adımları

1. **Repoyu Klonlayın:**
   ```bash
   git clone [https://github.com/UmutGuvenUslu/PersonelNotes.git](https://github.com/UmutGuvenUslu/PersonelNotes.git)
   cd PersonelNotes
   ```

2. **Bağımlılıkları Yükleyin:**
   ```bash
   npm install
   ```

3. **Node-RED'i Başlatın:**
   ```bash
   npm start
   ```
   *(Eğer global olarak kuruluysa doğrudan `node-red` komutuyla da başlatabilirsiniz.)*

4. **Arayüze Erişin:**
   Tarayıcınızı açın ve `http://localhost:1880` adresine gidin.

---

## ⚙️ Yapılandırma Dosyaları

* **`flows.json`**: Node-RED üzerinde tasarladığınız tüm görsel iş akışlarını, fonksiyon düğümlerini ve yönlendirmeleri tutan ana dosyadır.
* **`flows_cred.json`**: Akışlardaki veritabanı parolaları ve API anahtarları gibi hassas bilgilerin şifrelenerek tutulduğu dosyadır. Güvenlik gerekçesiyle **manuel düzenlenmemeli** ve `.gitignore` dosyasında tutulmalıdır.

---

## 🤝 Katkıda Bulunma

Projeye katkıda bulunmak için:

1. Repoyu Fork'layın (`Fork`)
2. Yeni bir özellik/düzeltme dalı açın (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Yeni akış entegrasyonu'`)
4. Dalınıza push yapın (`git push origin feature/YeniOzellik`)
5. Bir **Pull Request** açın


---

<div align="center">

Geliştirici: **[Umut Güven Uslu](https://github.com/UmutGuvenUslu)**

⭐ Projeyi faydalı bulduysanız yıldız vermeyi unutmayın!

</div>
