# ⚡ Yakala

Aklına geleni kaçırma: sesle ya da yazıyla anlık not yakala, önem derecesiyle listele, tek dokunuşla WhatsApp mesajına dönüştür.

**Kullan:** https://hzafert.github.io/yakala/ — telefonda aç, tarayıcı menüsünden **"Ana Ekrana Ekle"** de; uygulama gibi çalışır (PWA).

## Nasıl çalışır

- **🎤 Mavi buton** — konuş (veya kutuya yaz), sona önem derecesini söyle: `A1`…`C3`
  - Önem: **A** kritik (mavi) · **B** önemli (yeşil) · **C** delege et (kırmızı)
  - Aciliyet: **1** hemen · **2** yakında · **3** esnek — söylemezsen `B2`
- **W yeşil buton** — kişinin adını ve mesajı söyle: *"Ali yarın toplantıyı unutma"* → WhatsApp, Ali'nin sohbeti ve mesaj hazır halde açılır; sadece **gönder**'e basarsın
- **👥 Kişiler** — ad + numara (+ söyleyeceğin ad) ekle; W butonu ve sesli komutlar bu listeyi kullanır
- Notlar cihazında saklanır (localStorage); 📋 Kopyala / 📥 Yapıştır / 📤 Paylaş ile cihazlar arası taşınır

## Gizlilik

Her şey tarayıcında, cihazında kalır — sunucu yok, hesap yok, takip yok. Kişi listen yalnızca senin cihazında saklanır.

---

Tek dosyalık uygulama (`index.html`) — HTML + CSS + vanilla JS, bağımlılık yok.

🤖 [Claude Code](https://claude.com/claude-code) ile geliştirildi.
