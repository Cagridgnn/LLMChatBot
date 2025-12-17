# 🤖 LLM ChatBot Simulator (WinForms)

Bu uygulama, Nesne Tabanlı Programlama (NTP) prensipleri kullanılarak geliştirilmiş, modern bir yapay zeka (LLM) arayüz simülasyonudur. Uygulama, gerçek zamanlı veri işleme ve JSON mimarisi üzerine kurgulanmıştır.

## 🌟 Öne Çıkan Teknik Özellikler

* **Asenkron Programlama (Async/Await):** Yapay zeka yanıt üretme süreci asenkron olarak yönetilir. Bu sayede "bot düşünüyor" aşamasında kullanıcı arayüzü (UI) donmaz ve uygulama yanıt vermeye devam eder.
* **JSON Veri Yönetimi:** `Newtonsoft.Json` kütüphanesi kullanılarak veriler nesneden JSON formatına (Serialize) ve JSON'dan tekrar nesneye (Deserialize) dönüştürülür. Bu yapı, gerçek dünya API entegrasyonlarının temelini oluşturur.
* **Dinamik UI Kontrolü:** `RichTextBox` üzerinde mesaj gönderen kişiye göre (Kullanıcı/Bot) dinamik renklendirme, font stili ve otomatik kaydırma (ScrollToCaret) işlemleri uygulanmıştır.

## 🛠 Kullanılan Teknolojiler
* **Dil:** C# (.NET Framework / Core)
* **Kütüphane:** Newtonsoft.Json
* **Mimari:** Event-Driven Programming & Asynchronous Task Management

## 💡 Neden Simülasyon?
Hocaya Sunum Notu: "Uygulama, sunum sırasında internet bağımlılığını ortadan kaldırmak ve kaynak yönetimini optimize etmek amacıyla simüle edilmiş bir LLM motoru kullanmaktadır. Ancak `GetLLMResponse` metodu tamamen modülerdir; istenildiği takdirde saniyeler içerisinde **OpenAI** veya **Ollama** API bağlantısı yapılabilecek altyapıya sahiptir."

## 📋 Kullanım
1. Alt kısımdaki metin kutusuna mesajınızı yazın.
2. **Gönder** butonuna basın veya **Enter** tuşunu kullanın.
3. Botun "düşünme" sürecini takiben verdiği yanıtı renkli sohbet ekranında görüntüleyin.

---
**Ders:** Nesne Tabanlı Programlama (NTP)  
**Geliştirici:**
