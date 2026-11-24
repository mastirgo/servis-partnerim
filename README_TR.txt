SERVİS PARTNERİM - ANDROID BAŞLANGIÇ PROJESİ

Paket kimliği: com.mastirgo.servispartnerim

Bu proje mevcut çalışan HTML dosyasını Capacitor ile Android uygulamasına sarar. İlk adım GitHub Actions üzerinden TEST APK üretmektir.

1) ZIP'i açın.
2) GitHub'da servis-partnerim reposunu açın.
3) Android hazırlığı için bu ZIP içindeki dosyaları repo köküne yükleyin (www/index.html, package.json, capacitor.config.json, .github/workflows/android-apk.yml).
4) GitHub Actions sekmesi > Servis Partnerim Android APK > Run workflow.
5) İşlem tamamlanınca artifact bölümünden APK'yı indirin.

NOT: Bu workflow test/debug APK üretir. Play Store'a yüklemek için imzalı Android App Bundle (AAB), Play Console veri güvenliği/gizlilik beyanları, simge ve mağaza materyalleri ile izinlerin gözden geçirilmesi gerekir. Bu ZIP henüz Play Store için imzalı AAB değildir.
