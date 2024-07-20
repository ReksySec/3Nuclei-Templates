# LFI-Detector

**LFI-Detector** (Local File Inclusion Detector) yerel dosya dahil etme (LFI) zafiyetlerini tespit etmek için kullanılan bir araçtır. Bu YAML dosyası, LFI zafiyetlerini taramak amacıyla çeşitli test konfigürasyonlarını içerir.

## Özellikler

- **Test Edilecek Dosya Yolları**: Potansiyel olarak zafiyet gösterebilecek dosya yollarını belirtir.
- **Payload Konfigürasyonları**: LFI zafiyetlerini denemek için kullanılan payload'lar.
- **Test Stratejileri**: Çeşitli test stratejilerini tanımlar ve uygular.

## Kullanım

1. YAML dosyasını uygun bir LFI tarayıcıya veya güvenlik testi aracına yükleyin.
2. Dosya yollarını ve payload'ları ihtiyaçlarınıza göre özelleştirin.
3. Tarayıcıyı çalıştırarak LFI zafiyetlerini test edin.

**Not**: Bu dosya, eğitim ve güvenlik testleri amacıyla kullanılmalıdır. Gerçek ortamda kullanılmadan önce kapsamlı testler yapılması önerilir.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Sql-Injection-Detector

**Sql-Injection-Detector** SQL enjeksiyonu (SQLi) zafiyetlerini tespit etmek için kullanılan bir araçtır. Bu YAML dosyası, SQL enjeksiyonu testlerini yapılandırmak için gerekli konfigürasyonları içerir.

## Özellikler

- **Test Edilecek Payload'lar**: SQL enjeksiyonu tespit etmek için kullanılan çeşitli payload'ları içerir.
- **URL ve Parametre Konfigürasyonları**: SQL enjeksiyonu testlerinin yapılacağı URL'ler ve parametreler.
- **Hata Kontrolü**: SQL hatalarını ve yanıtlarını analiz ederek potansiyel zafiyetleri belirler.

## Kullanım

1. YAML dosyasını uygun bir SQL enjeksiyonu tarayıcısına veya güvenlik testi aracına yükleyin.
2. Payload'ları ve URL parametrelerini ihtiyaçlarınıza göre özelleştirin.
3. Tarayıcıyı çalıştırarak SQL enjeksiyonu zafiyetlerini test edin.

**Not**: Bu dosya, eğitim ve güvenlik testleri amacıyla kullanılmalıdır. Gerçek ortamda kullanılmadan önce kapsamlı testler yapılması önerilir.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# XSS-Detector

**XSS-Detector** (Cross-Site Scripting Detector) XSS zafiyetlerini tespit etmek için kullanılan bir araçtır. Bu YAML dosyası, XSS açıklarını test etmek için gerekli olan konfigürasyonları içerir.

## Özellikler

- **Test Edilecek Payload'lar**: XSS zafiyetlerini denemek için kullanılan çeşitli payload'ları içerir.
- **Form ve Parametre Konfigürasyonları**: XSS testlerinin yapılacağı form eylemleri ve URL parametreleri.
- **Yanıt Analizi**: XSS saldırı vektörlerini kontrol etmek için yanıt analizleri.

## Kullanım

1. YAML dosyasını uygun bir XSS tarayıcısına veya güvenlik testi aracına yükleyin.
2. Payload'ları ve form eylemlerini ihtiyaçlarınıza göre özelleştirin.
3. Tarayıcıyı çalıştırarak XSS zafiyetlerini test edin.

**Not**: Bu dosya, eğitim ve güvenlik testleri amacıyla kullanılmalıdır. Gerçek ortamda kullanılmadan önce kapsamlı testler yapılması önerilir.
