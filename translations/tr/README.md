# keep-the-reasoning (Türkçe)

> İngilizce sürümün çevirisidir. Ayrılık olursa [İngilizce sürüm](../../README.md) esastır.

**İşi AI agent'lara devret. Muhakemeyi elinde tut.**

Modeller iyileştikçe bariz hatalar azalıyor. Agent çıktıları çoğunlukla düzgün yazılmış ve büyük ölçüde doğru oluyor; ikinci kez bakmayı gerektirmemelerinin nedeni de tam bu. Fark etmeden işi *devretmekten* işe *teslim olmaya* kayarsın: çıktı, açıklayamadığın hâlde sessizce senin olur.

Bu repo, agent'larının ürettiği işin sahibi olarak kalman için küçük ve uyarlanabilir bir kural seti. İki tarafı var:

- **Senin için:** riske göre ölçeklenen bir [checklist](checklist.md) ve haftalık/aylık [ritüeller](../../rituals.md).
- **Agent'ın için:** [Claude Code](../../agent-rules/CLAUDE.md), [AGENTS.md](../../agent-rules/AGENTS.md) uyumlu araçlar, [Cursor](../../agent-rules/cursor.mdc) ve [GitHub Copilot](../../agent-rules/copilot-instructions.md) için doğrudan kullanılabilir kurallar.

Her şey **iki [risk seviyesine](LEVELS.md)** göre ölçeklenir; geçici bir script, bir ödeme migration'ı ile aynı ritüeli görmez.

## Hızlı başlangıç (2 dakika)

1. Aracına uygun kural dosyasını `agent-rules/` klasöründen projene kopyala (eşleşme tablosu [İngilizce README](../../README.md#quick-start-2-minutes)'de).
2. Dosyanın başında risk seviyesini seç: `L1` veya `L2`.
3. Agent işinin başında ve sonunda [checklist](checklist.md)'i aç.
4. İsteğe bağlı: brief, agent raporu ve PR için [template'leri](../../templates/) kullan.

## Kendine uyarla

Bu kurallar bir başlangıç noktası, standart değil. Repoyu fork'la; seviyeleri değiştir, yerini hak etmeyen kuralları çıkar, kendi hatalarından öğrendiklerini ekle. Bir kural çoğu kişiye yarayacaksa [öner](../../CONTRIBUTING.md).

## Kaynak

Addy Osmani'nin **[Critical thinking when agents do the work](https://x.com/addyosmani/article/2117512471930167377)** yazısından uyarlanmıştır. Yazının metni bu repoda yer almaz; kurallar fikirlerin özgün ve pratik bir uyarlamasıdır. Orijinalini okumaya değer.

## Lisans

[CC BY 4.0](../../LICENSE) — atıf vererek özgürce kullan, paylaş, uyarla.

---

Maintained by [@busegenc](https://github.com/busegenc).
