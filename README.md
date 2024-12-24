# Blazor Nedir?

Blazor, modern web uygulamaları geliştirmek için kullanılan bir framework'tür. .NET ekosistemi içinde yer alır ve geliştiricilere C# dilini kullanarak interaktif ve zengin özelliklere sahip web uygulamaları oluşturma imkânı tanır.

Ayrıca, Blazor web uygulamalarını geliştirirken JavaScript'e alternatif olarak C# dilini kullanarak geliştiricilerin daha önce bildikleri bir dil ve aracı kullanmalarını sağlar. Bu özellik, hem frontend hem de backend için aynı dili kullanarak daha tutarlı ve verimli bir geliştirme süreci sunar.

Blazor'un adı, iki temel bileşeni birleştirerek oluşturulmuştur: "Browser" ve ".NET Razor". Razor, Blazor'un dinamik içerik oluşturmak için kullandığı syntax'tır. Bu yaklaşım, .NET geliştiricilerinin zaten aşina olduğu bir ortamda rahat çalışmasına olanak tanır.

- **Blazor'un Temel Özellikleri**

    - **C# ve .NET Kullanımı**: İstemci tarafı uygulamaları yazmak için JavaScript yerine C# kullanılabilir. Bu sayede geliştiriciler, var olan .NET kütüphanelerini ve kodlarını kullanmaya devam edebilir.
    - **.NET Ekosistemi ile Entegrasyon:** Şimdiye kadar yazılmış olan .NET kütüphaneleri, NuGet paketleri ve Entity Framework gibi teknolojiler kolayca kullanılabilir.
    - **Zengin Kullanıcı Arayüzleri:** Blazor, Razor bileşenlerini kullanarak dinamik ve zengin içerik oluşturmayı kolaylaştırır. State management gibi modern geliştirme kavramlarını destekler.
    - **Open Source ve Topluluk Desteği:** Blazor, Microsoft'un desteklediği açık kaynak kodlu bir projedir ve büyük bir topluluk tarafından geliştirilmeye devam etmektedir.

- - -

## ⚡️Blazor Çalışma Prensibi (Client-Side / Server Side)

Blazor, iki farklı çalışma modu sunar. Bu iki mod, uygulamanın çalıştırıldığı yer ve performans açısından önemli farklılıklar içerir.

### 🟣 **Client-Side (Blazor WebAssembly)**

**⚙️ Çalışma Mantığı**: Blazor WebAssembly*(WASM)*, uygulamayı tamamen istemci tarafında (client-side) çalıştırır. Uygulama, tarayıcıya indirilen bir WebAssembly dosyası olarak çalışır ve doğrudan tarayıcıda render edilir.

**🟢 Avantajları**: Sunucu ile sürekli bağlantı kurmak gerekmez, uygulama çevrimdışı çalışabilir ve sayfa yüklemeleri daha hızlı gerçekleşebilir.

**🔴 Dezavantajları**: İlk yükleme süresi daha uzundur çünkü tüm uygulama dosyalarının tarayıcıya indirilmesi gerekir. Ayrıca, cihazın işlem gücüne bağlı olarak performans değişiklikleri yaşanabilir.