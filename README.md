# AWS’ten On-Prem’e Geçiş – Production DevOps Blueprint

Bu repo, **AWS üzerinde çalışan bir sistemin on-prem Kubernetes altyapısına taşınması**
sürecinde kullanılan **gerçek dünya mimari yaklaşımı, CI/CD pipeline tasarımı ve operasyonel kararları**
dokümante etmek amacıyla hazırlanmıştır.

> Tüm firma bilgileri, domain’ler ve özel konfigürasyonlar güvenlik sebebiyle anonimleştirilmiştir.

---

## 🎯 Amaç

- Production ortamda çalışan sistemlerin **güvenli, ölçeklenebilir ve sürdürülebilir** hale getirilmesi  
- AWS → On-Prem geçiş sürecinde **sıfıra yakın kesinti (zero-downtime)** sağlamak  
- CI/CD süreçlerini **tam otomasyon** ile yönetmek  
- İzlenebilirlik (observability) altyapısını kurmak  

---

## 🏗 Mimari Yaklaşım

Bu projede:

- Yüksek erişilebilirlik (High Availability)
- Güvenli network tasarımı
- İzlenebilirlik odaklı mimari
- Otomatik deployment süreçleri  

esas alınmıştır.

---

## 🔄 CI/CD Süreci

- GitHub Actions
- Self-hosted runner mimarisi
- Güvenli secret yönetimi
- Otomatik build → test → deploy pipeline

---

## 🚀 Migration Stratejisi (AWS → On-Prem)

- Mevcut AWS mimarisinin analizi  
- On-prem Kubernetes ortamının tasarımı  
- Paralel ortam kurulumu  
- Trafik kademeli yönlendirme  
- Rollback senaryoları  

---

## 📊 Observability

- Prometheus
- Grafana
- Merkezi loglama
- Alarm ve uyarı sistemleri

---

## 🔐 Güvenlik

- Secret yönetimi
- Network izolasyonu
- Least-privilege yaklaşımı
- Güvenli deployment süreçleri
