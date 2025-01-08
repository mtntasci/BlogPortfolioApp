# Blog veya Portföy Uygulaması

Bu proje, Razor Pages kullanarak basit bir blog veya portföy sitesi oluşturmanızı sağlar. Kullanıcılar makaleler ekleyebilir, düzenleyebilir ve silebilir.

## Özellikler

- Makale ekleme, görüntüleme, düzenleme ve silme.
- SQLite veritabanı kullanımı.
- Razor Pages ile hızlı ve basit bir yapı.

## Kullanılan Teknolojiler

- **.NET Core 6+**
- **Razor Pages**
- **Entity Framework Core**
- **SQLite**

## Proje Nasıl Çalıştırılır?

1. **Projeyi Klonlayın**:
   ```bash
   https://github.com/kullanici_adi/BlogPortfolioApp.git
   ```

2. **Bağımlılıkları Yükleyin**:
   ```bash
   dotnet restore
   ```

3. **Veritabanını Oluşturun**:
   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

4. **Projeyi Çalıştırın**:
   ```bash
   dotnet run
   ```

5. **Ana Sayfa**: `https://localhost:5001`

## Geliştirme Notları

Bu proje basit bir başlangıç sunmaktadır. Daha fazla özellik eklemek için Entity Framework veya Razor Pages ile geliştirme yapabilirsiniz.