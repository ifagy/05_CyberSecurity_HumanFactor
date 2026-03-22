# Wiener Linien: Human-Centric Security & Social Engineering Analysis

This repository contains the documentation and technical analysis of a field study conducted to evaluate the "human factor" in digital security systems. The project demonstrates how technically sound verification methods (encrypted QR codes) can be bypassed using social engineering and cognitive biases.

## 🎯 Project Objective
The goal was to analyze the vulnerabilities in the digital ticket inspection mechanism of Vienna’s transport network (**Wiener Linien**). Despite the technical robustness of the WienMobil app, the study tested how ticket controllers rely on "cognitive shortcuts" instead of technical verification.

## 🧪 Methodology & Field Experiment
This study involved an empirical field test within the Vienna U-Bahn network:

* **Artifact Development**: Replicated the WienMobil app interface using **React Native (Snack Expo)**, focusing on the specific color palette and the "animated real-time clock" feature.
* **Experimental Design**: A controlled test where a team member used the simulated ticket during a live inspection while the controller's reaction was recorded for analysis.
* **Key Finding**: Controllers consistently validated the fraudulent ticket by observing the **animated clock (psychological validation)** instead of **scanning the QR code (technical verification)**.

## 🧠 Cognitive Biases Targeted
The analysis identified three primary psychological vulnerabilities exploited during the process:

1.  **Anchoring Bias**: The inspectors' tendency to rely on the first visible sign of validity (the moving clock) as their primary anchor.
2.  **Confirmation Bias**: Because the UI design perfectly matched the official app, controllers automatically confirmed validity without further scrutiny.
3.  **Normalcy Bias**: An assumption that since the situation appeared "standard," a technical fraud was unlikely.

## 🛠 Technical Stack
* **Frontend**: JavaScript / React Native (Snack Expo).
* **Security Research**: Comparative analysis against existing vulnerabilities in global transit systems like Boston’s *CharlieCard* and London’s *Oyster Card*.

## ⚖️ Ethical Disclosure
This project was conducted strictly for **academic research and security awareness purposes**. The findings aim to encourage the development of robust, non-human-dependent verification systems to enhance public infrastructure security.

---
**Author**: Efe Bideci  
**Institution**: TU Wien, Bachelor of Computer Science

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
