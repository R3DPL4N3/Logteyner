--EN--
# Logteyner

**Logteyner** is an open-source Docker security agent that monitors the lifecycle of Docker containers on Linux servers in real-time. It detects critical events such as container starts, stops, and failures, analyzes activity for anomalies, and securely forwards logs to your SIEM platform.

- Captures Docker events with low latency  
- Maintains a whitelist of trusted container images  
- Flags suspicious or unknown container activity  
- Integrates with Harbor registry for image vulnerability insights  
- Sends structured logs to SIEM systems (Splunk, ELK, QRadar, etc.)  
- Lightweight and highly reliable agent  

Designed to enhance the observability of your Docker infrastructure and detect threats before they spread.

---

## Features

- Real-time Docker event listener  
- Image whitelist & risk scoring  
- Harbor security scan integration  
- SIEM log forwarding (Syslog, HTTP)  
- Modular and scalable architecture  
- Easy setup and containerized deployment  

---

## Use Cases

- DevOps & SRE security monitoring  
- Container runtime security in Docker/Kubernetes environments  
- Incident detection & response automation  
- Centralized logging with SIEM integration  

---

Contributions, bug reports, and feature suggestions are always welcome via GitHub Issues.

---

Greetings from Container Faruk 🚢🛡️



---
---
-TR-
# Logteyner

Logteyner, Linux üzerinde çalışan Docker containerlarının yaşam döngüsünü gerçek zamanlı izleyen, container başlatma, durma, başarısızlık gibi kritik olayları tespit eden ve güvenlik açısından analiz eden açık kaynak bir Docker güvenlik ajanıdır.

- Docker olaylarını düşük gecikmeyle yakalar.
- Bilinen güvenilir container görüntülerini whitelist’ler.
- Şüpheli veya bilinmeyen container aktivitelerini tanımlar.
- Harbor registry ile entegre olarak image güvenlik taramalarını kontrol eder.
- SIEM sistemlerine (Splunk, ELK, QRadar vb.) standart formatta loglar gönderir.
- Performans dostu ve yüksek kararlılıkla çalışır.

Güvenlik operasyonlarınızda Docker ortamınızın görünürlüğünü artırmak ve tehditleri anında yakalamak için tasarlanmıştır.

---

## Özellikler

- Gerçek zamanlı Docker event dinleme
- Image whitelist ve risk skorlama
- Harbor güvenlik taraması entegrasyonu
- SIEM log gönderimi (Syslog, HTTP)
- Ölçeklenebilir ve modüler mimari
- Kolay kurulum ve Docker container olarak deployment

---

## Kullanım Alanları

- DevOps ve SRE güvenlik izleme
- Kubernetes ve Docker Swarm ortamları için konteyner güvenliği
- Olay yönetimi ve güvenlik analizi
- SIEM entegrasyonu ile merkezi log yönetimi

---

Projeye katkı sağlamak, hata bildirmek veya özellik önermek için GitHub Issues’a bekleriz!

---

Konteyner Faruk’tan selamlar ve iyi çalışmalar! 🚀
