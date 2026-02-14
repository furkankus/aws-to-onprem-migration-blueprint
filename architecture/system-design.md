# Sistem Mimarisi Tasarımı

Bu doküman, AWS ortamında çalışan bir sistemin on-prem Kubernetes altyapısına
taşınması sürecinde kullanılan **mimari yaklaşımı ve tasarım kararlarını** açıklar.

---

## 🎯 Tasarım Hedefleri

- Yüksek erişilebilirlik
- Sıfıra yakın kesinti (zero-downtime)
- Güvenli ağ mimarisi
- Kolay ölçeklenebilirlik
- Gelişmiş izlenebilirlik

---

## 🏗 Genel Mimari

- Kubernetes cluster (HA)
- Nginx Ingress Controller
- CI/CD pipeline ile otomatik deployment
- Merkezi monitoring ve loglama

---

## 🌐 Network Tasarımı

- DMZ → Internal → Cluster ayrımı
- Firewall kuralları
- Internal servis haberleşmesi

---

## 🔐 Güvenlik Yaklaşımı

- Secrets yönetimi
- Network policy
- RBAC
- Image scanning

---

## ⚖ Yüksek Erişilebilirlik (HA)

- Çoklu node mimarisi
- Load balancer
- Health check ve failover mekanizmaları
