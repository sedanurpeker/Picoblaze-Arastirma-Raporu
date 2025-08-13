# PicoBlaze Araştırma Raporu

Bu çalışma, **Xilinx PicoBlaze** mikrodenetleyicisinin yapısını, özelliklerini ve kullanım alanlarını inceleyen bir araştırma raporudur.  
PicoBlaze, FPGA tasarımlarında gömülü kontrol uygulamaları için kullanılan, düşük kaynak tüketimine sahip 8-bit bir işlemcidir.

---

## İçerik

### 1. PicoBlaze Nedir?
- Xilinx tarafından geliştirilen 8-bit RISC tabanlı mikrodenetleyici
- FPGA’lerde gömülü kontrol işlemleri için optimize edilmiştir
- Donanım tanımlama dilleri (VHDL, Verilog) ile FPGA içerisine gömülür

### 2️. Mimarisi
- 8-bit işlemci çekirdeği
- 1K x 18-bit program belleği
- 64 byte veri belleği
- 16 adet genel amaçlı register
- Kesme (interrupt) desteği
- Sıralı ve hızlı komut yürütme (her komut 2 saat darbesinde çalışır)

### 3️. Komut Seti
- 8-bit veri işlemleri
- Atama, aritmetik ve mantıksal işlemler
- Karar yapıları (koşullu dallanma)
- Giriş/çıkış (I/O) işlemleri
- Program akışı kontrolü (CALL, RETURN vb.)

### 4️. Programlama ve Kullanım
- PicoBlaze için programlar **KCPSM** (Ken Chapman’s PicoBlaze Assembler) ile yazılır
- FPGA tasarımına gömülerek özel donanım ile birlikte çalışır
- Düşük donanım kaynağı kullanımı sayesinde küçük ve hızlı projeler için uygundur

### 5️. Kullanım Alanları
- Gömülü kontrol sistemleri
- Sensör verisi işleme
- Seri haberleşme protokolleri
- FPGA üzerinde küçük yardımcı işlemci görevleri

---

## Rapor Dosyası
📄 `Picoblaze Ödev.pdf` – Tüm detaylı açıklamaları ve örnekleri içerir.

---

## Kaynakça
- Xilinx PicoBlaze resmi dokümantasyonu
- FPGA tasarım örnekleri
- Akademik makaleler

---

## Hazırlayan
**Sedanur Peker**  
**Teslim Tarihi:** 01.01.2025  
