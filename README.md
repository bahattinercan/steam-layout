# Steam Layout

Steam mağaza arayüzünün **saf HTML/CSS/JS** ile yeniden yorumu. Framework, derleme adımı ve
bağımlılık yok — dosyayı aç, çalışır.

## Sayfalar

`Steam Projesi/` klasörünün içinde:

| Dosya | Ne |
|---|---|
| `index.html` | Ana sayfa / vitrin |
| `magaza.html` | Mağaza listeleme |
| `topluluk.html` | Topluluk sayfası |
| `destek.html` | Destek |
| `giris.html` | Giriş formu |
| `hakkinda.html` | Hakkında |
| `steam_yukleyin.html` | İstemci indirme sayfası |

Stil `css/index.css`, davranış `js/index.js`, logo `logo_steam.svg` (vektör, harici istek yok).

## Çalıştırma

```bash
start "" "Steam Projesi\\index.html"      # Windows
xdg-open "Steam Projesi/index.html"       # Linux
```

Statik sunucu tercih ederseniz: `npx serve "Steam Projesi"`.

## Sınırlar

Bu bir **arayüz çalışması**, işleyen bir mağaza değil: arama, sepet ve ödeme yoktur; içerik sabit
metindir. Yerleşim masaüstü öncelikli yazıldı, klavye ve ekran okuyucu davranışı test edilmedi.
