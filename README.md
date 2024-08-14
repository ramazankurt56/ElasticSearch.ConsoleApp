# ElasticSearch.ConsoleApp

Bu proje, ElasticSearch kullanarak veri işlemleri gerçekleştiren basit bir .NET Core konsol uygulamasıdır. Uygulama, ElasticSearch'te bir "product" indeksi üzerinden CRUD (Create, Read, Update, Delete) işlemlerini yapmayı gösterir.

## Proje Yapısı

### 1. Program.cs
- **Amaç**: ElasticSearch'te ürün bilgilerini depolamak ve sorgulamak için CRUD işlemlerini gerçekleştiren bir uygulamadır.
- **Kullanılan Teknolojiler**: 
  - **Elastic.Clients.Elasticsearch**: ElasticSearch ile iletişim kurmak için kullanılan .NET kütüphanesi.
  - **NEST**: ElasticSearch ile entegre çalışan güçlü bir .NET istemci kütüphanesi.

## CRUD İşlemleri

### 1. Create (Oluşturma)
ElasticSearch'e yeni bir ürün kaydı eklemek için kullanılır.

### 2. GetById (ID ile Getirme)
ElasticSearch'te belirli bir ürün kaydını ID'si ile almak için kullanılır.

### 3. Update (Güncelleme)
Mevcut bir ürün kaydını güncellemek için kullanılır.

### 4. Delete (Silme)
Belirli bir ürün kaydını ElasticSearch'ten silmek için kullanılır.

### 5. GetAll (Hepsini Getirme)
Tüm ürün kayıtlarını getirmek için kullanılır.


