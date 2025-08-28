# PAPK (Ported Android Package Kit)

PAPK, Android APK dosyalarını **Windows, Linux ve macOS** üzerinde, geleneksel emülatörlere ihtiyaç duymadan çalıştırmanızı sağlayan yenilikçi bir uygulamadır. Bu uygulama **AOSP Android Runtime** kullanır; yani bir emülatör değil, doğrudan APK’yı çalıştırır.

> ⚠️ Uyarı: Bazı APK’lar AOSP dışı özel API’ler kullandığı için çalışmayabilir.

## Özellikler

- Cross-platform: Windows, Linux, macOS
- APK kurulum ve analiz arayüzü
- Hafif ve hızlı çalışma
- Backend, frontend ve Lua tabanlı modüler yapı
- Kullanıcı APK’ları ve runtime dosyaları yerel olarak yönetilir

## Kurulum ve Çalıştırma

### Linux / macOS

PAPK paketlenmiş uygulamayı Linux veya macOS üzerinde çalıştırmak için:

```bash
# Paketlenen klasöre girin
cd dist/Linux/PAPK-linux-x64

# Çalıştırılabilir izni verin
chmod +x PAPK

# Uygulamayı başlatın
./PAPK
