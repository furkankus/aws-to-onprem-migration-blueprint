# GitHub Actions Self-Hosted Runner Kurulumu

Bu doküman, on-prem ortamda **self-hosted GitHub Actions runner** kurulumu ve
güvenli pipeline entegrasyonunu açıklar.

---

## 🎯 Amaç

- Daha hızlı pipeline süreleri
- Network izolasyonu
- Güvenli secret yönetimi
- On-prem kaynaklara doğrudan erişim

---

## 🛠 Kurulum Adımları

1. Runner için dedicated VM oluşturulması  
2. Docker ve gerekli bağımlılıkların kurulması  
3. GitHub runner servisinin kurulumu  
4. Servis olarak çalıştırılması  

---

## 🔐 Güvenlik

- Sadece outbound bağlantı
- Token rotasyonu
- Minimal yetki

---

## 🚀 Pipeline Entegrasyonu

- Build
- Test
- Image build
- Kubernetes deployment
