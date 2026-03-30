# python-zabbix-automation

# Zabbix Bulk Host Importer via Python API

Bu araç, binlerce ağ cihazını ve sunucuyu Zabbix izleme sistemine otomatik olarak aktarmak için geliştirilmiştir. Manuel olarak günlerce sürecek işlemleri saniyeler içinde tamamlar.

## ✨ Özellikler
- **Toplu Import:** CSV dosyasından binlerce hostu okur.
- **Dinamik Etiketleme (Tagging):** Her cihaz için şehir, ilçe, departman gibi etiketleri otomatik atar.
- **SNMPv3 Desteği:** Güvenli izleme için SNMPv3 konfigürasyonunu otomatik yapar.
- **Akıllı Kontrol:** Mevcut hostları tespit eder, varsa günceller yoksa yeni oluşturur.

## 🚀 Kurulum
1. Gereksinimleri yükleyin:
   ```bash
   pip install pandas pyzabbix
