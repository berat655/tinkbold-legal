# tinkbold.com — GitHub Pages kurulumu

Bu repo **public** ve yalnızca yasal HTML sayfalarını içerir. Uygulama kodu gizli repoda kalır.

Repo: **https://github.com/berat655/tinkbold-legal**

## Sonuç URL’leri

| Sayfa | Adres |
|---|---|
| Gizlilik | https://tinkbold.com/ezan-vakti/privacy |
| Kullanım koşulları | https://tinkbold.com/ezan-vakti/terms |

---

## Bölüm 1 — GitHub Pages (5 dk)

1. [github.com/berat655/tinkbold-legal/settings/pages](https://github.com/berat655/tinkbold-legal/settings/pages) adresine gidin.
2. **Build and deployment** → **Source**: `Deploy from a branch`.
3. **Branch**: `main` — klasör **`/ (root)`** — **Save**.
4. 2–5 dakika bekleyin.
5. **Custom domain:** `tinkbold.com` → **Save**.
6. DNS yayıldıktan sonra **Enforce HTTPS** işaretleyin.

> Public repo olduğu için **ücretsiz**, süre sınırı yok.

---

## Bölüm 2 — İsimtescil DNS

İsimtescil → **tinkbold.com** → **DNS Yönetimi**

**Silin:** Park sayfası, yönlendirme, ücretsiz hosting kayıtları.

**Ekleyin:**

| Tip | Host | Değer |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `berat655.github.io` |

Yayılım: genelde 15 dk – 2 saat.

---

## Bölüm 3 — Doğrulama

- https://tinkbold.com/ezan-vakti/privacy
- https://tinkbold.com/ezan-vakti/terms

---

## Bölüm 4 — App Store Connect

**Privacy Policy URL:** `https://tinkbold.com/ezan-vakti/privacy`
