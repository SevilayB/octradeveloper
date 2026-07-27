# Proje Hafızası

- Bu projenin GitHub deposu: `https://github.com/SevilayB/octradeveloper.git`
- Canlı yayın adresi: `https://developers.octraglobal.com`
- Kullanıcı açıkça istemedikçe projede yapılan değişiklikler GitHub deposuna otomatik olarak gönderilmemelidir.
- GitHub'a gönderme işlemi yalnızca kullanıcının açık talimatıyla yapılmalıdır.
- GitHub'a gönderilen değişikliklerin canlı siteye yansıyacağı kabul edilmelidir.
- Değişiklikleri göndermeden önce ilgili dosyalar ve mümkünse sayfanın görünümü kontrol edilmelidir.

## HTML Önizleme Kuralı

- Kullanıcı hangi bölüm veya sayfa için değişiklik istediyse ve bu değişiklik `index.html` içinde hazırlanıyorsa, yerel `index.html` açıldığında doğrudan üzerinde çalışılan bölüm veya sayfa görüntülenmelidir.
- Her yeni bölüm değişikliğinde başlangıç sayfası ilgili hedefe göre güncellenmeli; kullanıcı önizleme için menüden hedef sayfayı yeniden bulmak zorunda bırakılmamalıdır.
- GitHub'a gönderim öncesinde başlangıç sayfasının canlı ortam için hangi sayfa olması gerektiği ayrıca değerlendirilmelidir.

## Ürün Yaklaşımı

- Proje; Bank of America, Adyen ve Stripe gibi global finans ve ödeme kuruluşlarında farklı ürün alanlarında deneyim kazanmış kıdemli bir Product Owner'ın profesyonel bakış açısı ve kalite standardıyla hazırlanmalıdır.
- İçerikler yalnızca teorik veya pazarlama odaklı olmamalı; gerçek ödeme akışlarını, üretim ortamı istisnalarını, operasyonel sorumlulukları, ürün sınırlarını, riskleri ve kurumsal müşteri beklentilerini yansıtmalıdır.
- Ürün dili kendinden emin, sade ve gerçekçi olmalı; doğrulanmamış özellikler, yapay başarı iddiaları veya desteklenmeyen kurumsal vaatler kullanılmamalıdır.
- Bilgi mimarisi ve tasarım kararları geliştirici deneyimi kadar payment operations, finance, risk, compliance ve ürün ekiplerinin ihtiyaçlarını da dikkate almalıdır.

## Benchmark Kuralı

- Kullanıcı “benchmark yapalım” dediğinde, ilgili ürün kategorisinde global ölçekte öne çıkan ilk 10 rakip platformun güncel guide/product dokümanları incelenmelidir.
- Benchmark kapsamı, kullanıcının benchmark talebinde bulunduğu modüle göre belirlenmelidir:
  - Payment Gateway benchmark: globalde öne çıkan ilk 10 Payment Gateway platformunun guide dokümanları.
  - Acquiring benchmark: globalde öne çıkan ilk 10 acquiring platformunun guide dokümanları.
  - Issuing benchmark: globalde öne çıkan ilk 10 issuing platformunun guide dokümanları.
  - Full Processing (Acquiring + Sanal POS) benchmark: acquiring ve sanal POS kabiliyetlerini birlikte sunan global full-processing platformlarının guide dokümanları.
- “İlk 10” listesi sabit kabul edilmemelidir. Her benchmark çalışmasında güncel pazar görünümü, ürün kapsamı, global erişim ve dokümantasyon kalitesi araştırılarak rakip seçimi gerekçelendirilmelidir.
- İnceleme yalnızca pazarlama sayfalarıyla sınırlı kalmamalı; mümkün olduğunda overview, concepts, integration guides, payment flows, lifecycle, operations, testing, go-live, API navigation ve hata yönetimi bölümleri karşılaştırılmalıdır.
- Benchmark sonucunda Octra dokümanındaki eksikler, rakiplerden ayrışma fırsatları, önerilen bilgi mimarisi ve uygulanabilir içerik geliştirmeleri açıkça çıkarılmalıdır.
