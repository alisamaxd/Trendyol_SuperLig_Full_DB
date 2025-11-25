# Trendyol Süper Lig - Veritabanı Yönetim Sistemi (DBMS)

Bu proje, Türkiye Süper Ligi'nin veri yapısını simüle eden, ilişkisel bütünlüğe (Relational Integrity) ve normalizasyon kurallarına (3NF) uygun olarak tasarlanmış kapsamlı bir **SQL Server** veritabanı projesidir.

## Proje Hakkında
Futbol dünyasındaki karmaşık verilerin (Fikstür, Transferler, Maç İstatistikleri, Puan Durumu vb.) yönetilmesi amacıyla geliştirilmiştir. Excel tabanlı takibin yarattığı veri tekrarını ve tutarsızlığı önlemek için **MS SQL Server** üzerinde profesyonel bir mimari kurulmuştur.

### Temel Özellikler
* **İlişkisel Mimari:** Takımlar, Oyuncular, Hakemler ve Stadyumlar arasındaki Foreign Key ilişkileriyle veri bütünlüğü sağlandı.
* **Veri Optimizasyonu:** `tinyint`, `smallint` ve `decimal` gibi doğru veri tipleri seçilerek performans optimize edildi.
* **Dinamik İstatistikler:** Maç olayları (Gol, Kart) girildiğinde sorgulanabilir detaylı maç raporları.
* **Transfer Takibi:** Oyuncuların geçmiş ve gelecek transfer hareketlerinin tutulabildiği yapı.
* **Normalizasyon:** Veri tekrarını önlemek için Pozisyonlar, Ülkeler ve Lisans Türleri ayrı tablolara (Lookup Tables) bölündü.

## Kullanılan Teknolojiler
* **Veritabanı:** Microsoft SQL Server (T-SQL)
* **Araçlar:** SSMS (SQL Server Management Studio)
* **Konseptler:** Database Normalization (1NF, 2NF, 3NF), Relational Design, Primary & Foreign Keys, Joins, Subqueries.

## Kurulum
1. `Trendyol_SuperLig_Full_DB.sql` dosyasını indirin.
2. SSMS (SQL Server Management Studio) üzerinde açın.
3. Kodu çalıştırın (Execute).
4. Veritabanı, tablolar ve örnek veriler (GS, FB, BJK kadroları ve 2023-24 sezonu puan durumu) otomatik olarak oluşturulacaktır.

## Örnek Sorgular
Proje içerisinde aşağıdaki analizleri yapabileceğiniz altyapı mevcuttur:
* *"Hangi takımın kaç yabancı oyuncusu var?"*
* *"Derbi maçında gol atan oyuncuların mevkileri nelerdir?"*
* *"Ligin averaj ve puan sıralamasına göre şampiyonu kim?"*

---
*Geliştirici: Ali Şener
*Yönetim Bilişim Sistemleri (MIS) Öğrencisi*
