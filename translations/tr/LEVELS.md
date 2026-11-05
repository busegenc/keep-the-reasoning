# Risk seviyeleri

> İngilizce [LEVELS.md](../../LEVELS.md) dosyasının çevirisidir.

Her iş aynı titizliği hak etmez. Her kuralı her işe uygulamak sürdürülebilir değil; sürdüremediğin kurallar da tam önemli oldukları anda atlanır. İşe başlamadan seviyeni seç.

## L1 — Düşük risk

Prototipler, kişisel scriptler, denemeler, spike'lar, yalnızca senin kullandığın iç araçlar: yanılmanın ucuz, geri almanın kolay olduğu her şey.

Tamamen devredebilirsin. Yine de:
- özetten önce kanıta bak (ne çalıştı, ne döndü),
- imza testini geç: *Buna adımı koyar mıyım?*

## L2 — Yüksek risk

Prod sistemler, auth, ödeme, veri migration'ları, kullanıcı verisine dokunan her şey, başkasının bakımını yapacağı kod, geri alınması zor her şey.

Bütün kurallar geçerli.

## Nasıl karar verilir

Tek bir soru sor: **Bu yanlışsa, sonucuna başka biri katlanmak zorunda kalacak mı?**

- Hayır → L1. İşi devret.
- Evet → L2. Muhakemeyi elinde tut.

**Emin değilsen L2'dir.**

Bir projede ikisi birden olabilir: repo varsayılan olarak L1'de çalışırken belirli bir iş (ör. şema migration'ı) L2 olarak yürütülebilir. Bunu brief'inde belirt.
