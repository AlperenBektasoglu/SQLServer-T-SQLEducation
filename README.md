# SQLServer-T-SQLEducations

![Türkiye](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/tr.png 'Türkiye') TR: SQL Server ve T-SQL Eğitimleri

![United Kingdom](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png 'United Kingdom') EN: SQL Server And T-SQL Educations

1. 001-GenelBilgiler

- [Genel Bilgiler](#genel-bilgiler)
	- [Veri/Data Nedir?](#veri/data-nedir?)
	- [Veritabanı/Database Nedir?](#veritabanı/database-nedir?)
	- [Veritabanı Yönetim Sistemi (VTYS)/Database Management System(DBMS) Nedir?](#veritabanı-yönetim-sistemi-(vtys)/database-management-system(dbms)-nedir?)
	- [VTYS’lerin Faydaları](#vtys’lerin-faydaları)
	- [Veri Modelleri/Data Model](#veri-modelleri/data-model)
		- [İlişkisel Veri Modeli (Relational Data Model)](#i̇lişkisel-veri-modeli-(relational-data-model))

1. 002-VeritabanıTasarımı

- [VeritabanıTasarımı](#veritabanıtasarımı)
	- [Veritabanı Tasarım Aşamaları](#veritabanı-tasarım-aşamaları)
	- [Entity Relationship Model (ER)](#entity-relationship-model-(er))
		- [Recursive İlişki](#recursive-i̇lişki)
		- [İlişki Türleri](#i̇lişki-türleri)

1. 003-Normalizasyon

- [Normalizasyon](#normalizasyon)
	- [Normalizasyonun Amaçları](#normalizasyonun-amaçları)
	- [Normalizasyon Kuralları](#normalizasyon-kuralları)

1. 004-SqlTemelKavramlar

- [Sql Temel Kavramlar](#sql-temel-kavramlar)
	- [Sql Server Genel İsimlendirme Kuralları](#sql-server-genel-i̇simlendirme-kuralları)
	- [Genel Bilgiler](#genel-bilgiler)
	- [Use Anahtar Kelimesi](#use-anahtar-kelimesi)
	- [Sql Komut Kategorileri](#sql-komut-kategorileri)
	- [Sql Dosya Formatları](#sql-dosya-formatları)
	- [Sıklıkla Kullanılan Veri Tipleri](#sıklıkla-kullanılan-veri-tipleri)
		- [Unicode Nedir? Unicode ile ASCII Farkları Nelerdir? ](#unicode-nedir?-unicode-ile-ascii-farkları-nelerdir?-)
	- [Uniqueidentifier Veri Tipi](#uniqueidentifier-veri-tipi)

1. 006-DDLKomutları

- [DDL(Data Definition Language) Komutları (CREATE / ALTER / DROP)](#ddl(data-definition-language)-komutları-(create-/-alter-/-drop))
	- [CREATE Komutu](#create-komutu)
	- [ALTER Komutu](#alter-komutu)
	- [DROP Komutu](#drop-komutu)

1. 009-DMLKomutları

- [DML(Data Manipulation Language) Komutları (INSERT/ UPDATE/ Delete)](#dml(data-manipulation-language)-komutları-(insert/-update/-delete))
	- [Insert Komutu](#insert-komutu)
		- [Insert Komutu İle Select Sorgusu Sonucunda Gelen Verileri FarklI Bir Tabloya Kaydetme](#insert-komutu-i̇le-select-sorgusu-sonucunda-gelen-verileri-farkli-bir-tabloya-kaydetme)
	- [Update Komutu](#update-komutu)
	- [Delete Komutu](#delete-komutu)
	- [Truncate Komutu](#truncate-komutu)

1. 011-TemelSqlKomutları

- [Temel Sql Komutları](#temel-sql-komutları)
	- [Top Komutu](#top-komutu)
		- [Top Komutu İle Update İşlemi](#top-komutu-i̇le-update-i̇şlemi)
		- [Top Komutu İle Delete İşlemi](#top-komutu-i̇le-delete-i̇şlemi)
	- [Distinct Komutu](#distinct-komutu)
	- [Group By Komutu](#group-by-komutu)
	- [Having Komutu](#having-komutu)
	- [With Rollup Komutu](#with-rollup-komutu)
	- [With Cube Komutu](#with-cube-komutu)
	- [Order By Komutu](#order-by-komutu)
	- [With Ties komutu](#with-ties-komutu)
	- [Toplu Kullanım](#toplu-kullanım)

1. 012-Joinler

- [Joinler](#joinler)
	- [Inner Join Yapısı](#inner-join-yapısı)
		- [Inner Join İle Birden Fazla Tabloyu Birleştirme](#inner-join-i̇le-birden-fazla-tabloyu-birleştirme)
	- [Left Outher Join Yapısı](#left-outher-join-yapısı)
	- [Right Outher Join Yapısı](#right-outher-join-yapısı)
	- [Full Outher Join Yapısı](#full-outher-join-yapısı)
	- [Cross Join Yapısı](#cross-join-yapısı)
	- [Join Yapısında Group By Komutu Kullanma](#join-yapısında-group-by-komutu-kullanma)
	- [Intersect Komutu](#intersect-komutu)
	- [Except Komutu](#except-komutu)
	- [Union Komutu](#union-komutu)
	- [Union All Komutu](#union-all-komutu)

1. 017-Fonksiyonlar

- [Fonksiyonlar](#fonksiyonlar)
	- [Scalar Fonksiyonlar](#scalar-fonksiyonlar)
	- [Inline Fonksiyonlar](#inline-fonksiyonlar)
	- [Alter Komutu İle Fonksiyon Yapısını Değiştirme](#alter-komutu-i̇le-fonksiyon-yapısını-değiştirme)
	- [Fonsiyon Silme](#fonsiyon-silme)

1. 010-ÖzelFonksiyonlar

- [Özel Fonksiyonlar](#özel-fonksiyonlar)
	- [Aggregate Fonksiyonları](#aggregate-fonksiyonları)
	- [String Fonksiyonları](#string-fonksiyonları)
	- [Sayısal Değer İşlemleri ve Sayısal Fonksiyonlar](#sayısal-değer-i̇şlemleri-ve-sayısal-fonksiyonlar)
	- [Tarih Fonksiyonları](#tarih-fonksiyonları)
	- [Coalesce Fonksiyonu İle Null Değer Kontrolü](#coalesce-fonksiyonu-i̇le-null-değer-kontrolü)
	- [IsNull Fonksiyonu İle Null Değer Kontrolü](#isnull-fonksiyonu-i̇le-null-değer-kontrolü)
	- [NullIf Fonksiyonu İle Null Değer Kontrolü](#nullif-fonksiyonu-i̇le-null-değer-kontrolü)

1. 015-ProgramlamaYapıları

- [Programlama Yapıları](#programlama-yapıları)
	- [Sql'de Değişken Tanımlama](#sql'de-değişken-tanımlama)
	- [Birleşik Operatörler](#birleşik-operatörler)
	- [Go Komutu](#go-komutu)
	- [If-Else Yapısı](#if-else-yapısı)
	- [While Döngüsü](#while-döngüsü)
	- [Break Komutu](#break-komutu)
	- [Continue Komutu](#continue-komutu)
	- [Case Kullanımı](#case-kullanımı)
	- [Exists / Not Exists Fonksiyonu](#exists-/-not-exists-fonksiyonu)
	- [Tablo Tipi Değişkenler](#tablo-tipi-değişkenler)
	- [Try-Catch Yapısı](#try-catch-yapısı)

1. 007-Constraints(Kısıtlayıcılar)

- [Contraints (Kısıtlayıcılar)](#contraints-(kısıtlayıcılar))
	- [Default Constraint](#default-constraint)
	- [Check Constraint](#check-constraint)
	- [Primary Key Constraint](#primary-key-constraint)
	- [Unique Constraint](#unique-constraint)
	- [Foreign Key Constraint](#foreign-key-constraint)
	- [Identity Kullanımı](#identity-kullanımı)
	- [Constraint Nasıl Silinir?](#constraint-nasıl-silinir?)
	- [Cacade Komutu](#cacade-komutu)
	- [Set Default Komutu](#set-default-komutu)
	- [Create Komutu içerisinde Constraint'lerin Kullanılması](#create-komutu-içerisinde-constraint'lerin-kullanılması)

1. 005-Operatörler

- [Operatörler](#operatörler)
	- [Karşılaştırma Operatörleri](#karşılaştırma-operatörleri)
	- [Mantıksal Operatörler](#mantıksal-operatörler)
	- [Aritmetiksel Operatörler](#aritmetiksel-operatörler)

1. 020-Indexes

- [Indexes](#indexes)
	- [Index Nedir?](#index-nedir?)
	- [Indexlerin Çalışma Prensibi](#indexlerin-çalışma-prensibi)
	- [B-tree(Balance Tree) Yapısının Çalışma Mantığı](#b-tree(balance-tree)-yapısının-çalışma-mantığı)
	- [Heap Table](#heap-table)
	- [Index Çeşitleri](#index-çeşitleri)
		- [Clustered Index](#clustered-index)
			- [Clustered Index Oluşturma](#clustered-index-oluşturma)
		- [Non-Clustered Index](#non-clustered-index)
			- [Non-Clustered Index Oluşturma](#non-clustered-index-oluşturma)
	- [Index Tanımlama Yaklaşımları](#index-tanımlama-yaklaşımları)
	- [Composite Index Oluşturma](#composite-index-oluşturma)
	- [Unique Index Oluşturma](#unique-index-oluşturma)
	- [Komplex Index Örneği](#komplex-index-örneği)
	- [Index Silme](#index-silme)

1. 023-DiğerKonular

- [Diğer Konular](#diğer-konular)
	- [Identity Kullanımı](#identity-kullanımı)
	- [@@Rowcount Kullanımı](#@@rowcount-kullanımı)
	- [Veritabanındaki Tabloları Listeleme](#veritabanındaki-tabloları-listeleme)
	- [Bir Tabloda Primary Key Olup Olmadığını Kontrol Etme](#bir-tabloda-primary-key-olup-olmadığını-kontrol-etme)
	- [En Son Primary Key Id Değerinin Bulunması](#en-son-primary-key-id-değerinin-bulunması)
	- [Default Values Kullanımı](#default-values-kullanımı)
	- [ROW_NUMBER() Fonksiyonu](#row_number()-fonksiyonu)
	- [Ansi_Nulls Komutu](#ansi_nulls-komutu)
	- [Dynamic Data Masking](#dynamic-data-masking)
	- [Temporal Tables](#temporal-tables)
	- [Row Level Security](#row-level-security)
	- [Execution Plan Nedir?](#execution-plan-nedir?)
	- [Sql Bulk Insert](#sql-bulk-insert)
	- [DCL (Data Control Language - Veri Kontrol Dili)](#dcl-(data-control-language---veri-kontrol-dili))

1. 022-BackupRestore

- [Backup / Restore](#backup-/-restore)
	- [Veritabanının Recovery Modelinin Öğrenilmesi](#veritabanının-recovery-modelinin-öğrenilmesi)
	- [Yedekleme Türleri](#yedekleme-türleri)
		- [Full Backup (Tam Yedekleme)](#full-backup-(tam-yedekleme))
		- [Differential Backup (Fark Yedekleme)](#differential-backup-(fark-yedekleme))
		- [Transaction Log Backup (İşlem Günlüğü Yedekleme)](#transaction-log-backup-(i̇şlem-günlüğü-yedekleme))
	- [Full Recovery Model’de Full Backup](#full-recovery-model’de-full-backup)
	- [Full Model’de Restore](#full-model’de-restore)
	- [Farklı Backup Türlerinin Dosya Boyutları](#farklı-backup-türlerinin-dosya-boyutları)
	- [Backup-Restore’un SQL Kodlarıyla Yapılması](#backup-restore’un-sql-kodlarıyla-yapılması)
	- [BackUp İşleminin Job Olarak Yapılması](#backup-i̇şleminin-job-olarak-yapılması)

1. 008-SelectKullanımı

- [Select Kullanımı](#select-kullanımı)
	- [Select Komutu](#select-komutu)
	- [Alias(Takma Ad) Kulanımı](#alias(takma-ad)-kulanımı)
	- [Kolon Birleştirme](#kolon-birleştirme)
	- [Tablo Oluştururken As komutu kullanma](#tablo-oluştururken-as-komutu-kullanma)
	- [Select Komutunda Where Şartı](#select-komutunda-where-şartı)
		- [Where Bloğunda Kullanılan Bağlaçların İşlem Önceliği Sıralaması](#where-bloğunda-kullanılan-bağlaçların-i̇şlem-önceliği-sıralaması)
	- [Select Komutunda Like Şartı](#select-komutunda-like-şartı)
		- [Like Sorgusunda Escape(Kaçış) Karakteri](#like-sorgusunda-escape(kaçış)-karakteri)

1. 014-Views

- [Views (Sanal Tablolar)](#views-(sanal-tablolar))
	- [View Oluşturma](#view-oluşturma)
	- [View'in Yapısını Değiştirme](#view'in-yapısını-değiştirme)
	- [Varolan View’in Kodunu Görme](#varolan-view’in-kodunu-görme)
	- [Tanımlı View Listesini Görme](#tanımlı-view-listesini-görme)
	- [View Kodunun Şifrelenmesi / With Encryption Komutu](#view-kodunun-şifrelenmesi-/-with-encryption-komutu)
	- [View’in Silinmesi](#view’in-silinmesi)
	- [View’daki Tabloya Kayıt Ekleme / Güncelleme / Silme](#view’daki-tabloya-kayıt-ekleme-/-güncelleme-/-silme)
	- [With Check Option Komutu](#with-check-option-komutu)
	- [View’in Adını Değiştirme](#view’in-adını-değiştirme)

1. README

- [SQLServer-T-SQLEducations](#sqlserver-t-sqleducations)

1. 019-TransactionYapısı

- [Transaction Yapısı](#transaction-yapısı)
	- [WAITFOR Kullanımı](#waitfor-kullanımı)

1. 013-AltSorgular

- [Alt Sorgular](#alt-sorgular)
	- [With Kullanımı](#with-kullanımı)

1. 021-GeçiciTablolar

- [Geçici Tablolar - Temporary Tables](#geçici-tablolar---temporary-tables)

1. 016-StoredProcedures

- [Stored Procedures (SP)](#stored-procedures-(sp))
	- [Stored Procedure Oluşturma](#stored-procedure-oluşturma)
	- [Alter Komutu İle Stored Procedure Yapısını Değiştirme](#alter-komutu-i̇le-stored-procedure-yapısını-değiştirme)
	- [Stored Procedure İle With Encryption Komutunun Kullanımı](#stored-procedure-i̇le-with-encryption-komutunun-kullanımı)
	- [Stored Procedure İle With Recompile Komutunun Kullanımı](#stored-procedure-i̇le-with-recompile-komutunun-kullanımı)
	- [Stored Procedure İle Set Nocount On Komutunun Kullanımı](#stored-procedure-i̇le-set-nocount-on-komutunun-kullanımı)
	- [Stored Procedure Silme](#stored-procedure-silme)

1. 018-Triggers

- [Triggers(Tetikleyiciler)](#triggers(tetikleyiciler))
	- [DDL Trigger](#ddl-trigger)
	- [DML Trigger](#dml-trigger)
	- [Trigger'ı Devre Dışı Bırakma - Aktifleştirme](#trigger'ı-devre-dışı-bırakma---aktifleştirme)
	- [Alter Komutu İle DDL Trigger Güncelleme ](#alter-komutu-i̇le-ddl-trigger-güncelleme-)
	- [Alter Komutu İle DML Trigger Güncelleme](#alter-komutu-i̇le-dml-trigger-güncelleme)
	- [Trigger Kaldırma](#trigger-kaldırma)

