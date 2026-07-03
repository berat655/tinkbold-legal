# GitHub’a ilk push (bir kez)

Repo yerelde hazır: `/Users/berat/Projects/tinkbold-legal`

## 1. GitHub’da public repo oluşturun

1. https://github.com/new
2. **Repository name:** `tinkbold-legal`
3. **Public** seçin
4. README / .gitignore **eklemeyin** (boş repo)
5. **Create repository**

## 2. Push edin

Terminalde:

```bash
cd /Users/berat/Projects/tinkbold-legal
git push -u origin main
```

(GitHub girişi istenirse onaylayın.)

## 3. GitHub Pages

1. https://github.com/berat655/tinkbold-legal/settings/pages
2. **Branch:** `main` — klasör **`/ (root)`** — Save
3. **Custom domain:** `tinkbold.com`
4. DNS ayarları: `GITHUB-PAGES-KURULUM.md`

---

Bu repoda **sadece** şunlar var:

- `index.html` — ana sayfa linkleri
- `CNAME` — tinkbold.com
- `ezan-vakti/privacy/index.html`
- `ezan-vakti/terms/index.html`

Uygulama kaynak kodu **yok**.
