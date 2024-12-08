# Blazor Nedir?

Blazor, web uygulamaları geliştirmek için kullanılan bir framework’tür. .NET ekosistemi içinde çalışır ve C# dilini kullanarak interaktif web uygulamaları oluşturmanı sağlar.

- **Özellikleri**
    - C# ve .NET ile istemci tarafı uygulamalar yazma.
    - WebAssembly(WASM) veya SignalR üzerinden sunucu tarafı çalışabilme.
    - .NET ile tam entegrasyon.

- - -

## ⚡️Blazor Çalışma Prensibi (Client-Side / Server Side)

Blazor, iki farklı çalışma modu sunar. Bu iki mod, uygulamanın çalıştırıldığı yer ve performans açısından önemli farklılıklar içerir.

### 🟣 **Client-Side (Blazor WebAssembly)**

**⚙️ Çalışma Mantığı**: Blazor WebAssembly*(WASM)*, uygulamayı tamamen istemci tarafında (client-side) çalıştırır. Uygulama, tarayıcıya indirilen bir WebAssembly dosyası olarak çalışır ve doğrudan tarayıcıda render edilir.

**🟢 Avantajları**: Sunucu ile sürekli bağlantı kurmak gerekmez, uygulama çevrimdışı çalışabilir ve sayfa yüklemeleri daha hızlı gerçekleşebilir.

**🔴 Dezavantajları**: İlk yükleme süresi daha uzundur çünkü tüm uygulama dosyalarının tarayıcıya indirilmesi gerekir. Ayrıca, cihazın işlem gücüne bağlı olarak performans değişiklikleri yaşanabilir.