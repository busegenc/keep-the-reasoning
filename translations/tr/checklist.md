# Checklist

> İngilizce [checklist.md](../../checklist.md) dosyasının çevirisidir.

Anlaşmanın senin tarafı. Agent sana kanıt gösterebilir, kararlarını listeleyebilir, seni sınayabilir; ama bunu sen kurarsan ve gerçekten bakarsan.

L1 / L2 için bkz. [LEVELS.md](LEVELS.md).

## Başlamadan önce

| Kural | L1 | L2 |
|---|---|---|
| Risk seviyesini belirle | ✅ | ✅ |
| Beklediğin cevabı tek cümlelik bir hipotez olarak yaz, kötü bir tahmin bile olsa | opsiyonel | ✅ |
| Sor: *Bunun yanlış olması için ne doğru olmalı?* | — | ✅ |
| Brief: amaç, kapsam dışı, "bitti" tanımı ([template](../../templates/task-brief.md)) | kısa | yazılı |
| "Doğrulandı"yı önceden tanımla: bir test, bir ekran görüntüsü, bir log | ✅ | ✅ |
| Sor: *Agent'ı düşünmeme yardım etsin diye mi, benim yerime düşünsün diye mi kullanıyorum?* | — | ✅ |
| Problem hâlâ bulanıksa önce agent seni mülakat etsin ya da kör nokta taraması yapsın | opsiyonel | ✅ |
| Açık uçlu kararlarda, karar vermeden önce bir modele karşı tarafı savundur | — | ✅ |

## Çalışırken

| Kural | L1 | L2 |
|---|---|---|
| İki tur düzeltmeden sonra yamamayı bırak, prompt'u baştan yaz | ✅ | ✅ |
| Kritik kaynak materyali doğrudan ver; agent özetlerinden oluşan zincirlere güvenme | — | ✅ |

## Çıktı geldiğinde

| Kural | L1 | L2 |
|---|---|---|
| Çalışan komutları ve gerçek çıktılarını özetten **önce** oku | ✅ | ✅ |
| Agent'ın karar ve varsayım listesini oku | göz at | ✅ |
| Her yeşil check için sor: *Neyi kanıtladı? Neyi kanıtlamadı?* | — | ✅ |
| Diff'i AI yazmamış gibi oku: transaction sınırları, ters çevrilmiş default'lar, edge case'ler | — | ✅ |
| Rastgele 3 satır seç: açıklayabiliyor musun? | — | ✅ |
| Agent'ın quiz'ini hatasız geçmeden merge yok | — | ✅ |
| İmza testi: *Bunu, bakımını yapacak kişinin önünde savunabilir miyim?* | ✅ | ✅ |
| Agent'ın kontrol etmediği bir şeyi not et | — | ✅ |

## İlkeler

- Agent'ın yardımıyla bile açıklayamıyorsan, ona teslim olmuşsun demektir.
- Yeşil bir check tek bir şeyi kanıtlar. Hangisi olduğunu bil.
- Cila artık kalitenin işareti değil.
- Adını koymayacağın şey yayına çıkmaz.
- İşi devredebilirsin. Sorumluluğu devredemezsin.
