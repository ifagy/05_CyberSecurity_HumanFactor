# Winner Linien: Human-Centric Security & Social Engineering Analysis
Bu proje, teknik olarak güvenli görünen sistemlerin (şifrelenmiş QR kodlar), sosyal mühendislik yöntemleri ve kognitif önyargılar kullanılarak nasıl manipüle edilebileceğini kanıtlayan bir Siber Güvenlik ve Sosyal Mühendislik çalışmasıdır.

🎯 Projenin Amacı
Viyana ulaşım ağındaki (Wiener Linien) dijital bilet kontrol mekanizmasının zayıf halkasını analiz etmek. Sistem teknik olarak güvenli olsa da (şifreli QR kodlar), kontrolörlerin "kognitif kısa yollar" kullanarak hata yapmaya ne kadar meyilli olduğunu test ettik.

🧪 Saha Testi ve Metodoloji (Field Experiment)
Bu çalışma sadece teoride kalmamış, Viyana metro ağında bizzat test edilmiştir:


Artefakt Geliştirme: WienMobil uygulamasının arayüzünü, renk paletini ve en önemlisi "hareketli gerçek zamanlı saat" özelliğini taklit eden bir simülasyon geliştirildi.


Deney Tasarımı: Bir ekip üyesi simülasyon biletle kontrole girerken, süreç gizlice kayıt altına alınarak kontrolörün tepkisi analiz edildi.


Sonuç: Kontrolörlerin QR kodu taramak (teknik doğrulama) yerine, görsel olarak hareket eden saate (psikolojik doğrulama) güvenerek sahte bileti onayladığı kanıtlandı.

🧠 Hedeflenen Kognitif Önyargılar (Biases)
Analizimizde kontrolörlerin şu zafiyetlerinden yararlanıldı:


Anchoring Bias: Kontrolörlerin biletin güncelliğini anlamak için ilk gördükleri "hareketli saate" odaklanmaları.


Confirmation Bias: Biletin genel tasarımı gerçek biletle örtüştüğü için kontrolörün şüphe duymaması ve onaylama eğilimi göstermesi.


Normalcy Bias: Her şey "normal" göründüğü için teknik bir sahtekarlık ihtimalinin göz ardı edilmesi.

🛠 Teknik Detaylar

Frontend: JavaScript / React Native (Snack Expo).


Analiz: Boston "CharlieCard" ve Londra "Oyster Card" gibi sistemlerin teknik açıklarıyla karşılaştırmalı siber güvenlik raporu.

⚖️ Etik Not
Bu çalışma tamamen akademik bir güvenlik analizi olup, sistemin zayıf yönlerini ortaya çıkararak daha güvenli (insan faktörüne dayanmayan) kontrol mekanizmalarının geliştirilmesini önermek amacıyla yapılmıştır.
