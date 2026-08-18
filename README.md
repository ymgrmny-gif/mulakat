# Akıllı Mülakat Asistanı

Windows üzerinde çalışan, Almanca iş görüşmelerini dinleyip hazır soru-cevap havuzuyla eşleştiren masaüstü uygulaması.

## Temel yaklaşım

- Önce yerel JSON soru havuzu eşleştirilir.
- Hazır soru bulunursa cevap doğrudan yerelden gösterilir; API çağrısı yapılmaz.
- Yalnızca yerel eşleşme bulunamazsa Groq sınıflandırma / dinamik cevap fallback'i devreye girer.
- Transdev soru havuzu `transdev-dosyalar/transdev_mulakat_tum_sorular.json` içinde tutulur.

Kaynak proje, kullanıcı tarafından sağlanan `MulakatSistemi.zip` temel alınarak düzenlenmiştir.
