# tinkbold.com — yasal sayfalar

**Public** repo: yalnızca statik HTML sayfaları. Ezan Vakti uygulama kaynak kodu burada yok.

## Canlı URL’ler

| Sayfa | URL |
|---|---|
| Gizlilik | https://tinkbold.com/ezan-vakti/privacy |
| Kullanım koşulları | https://tinkbold.com/ezan-vakti/terms |

## GitHub Pages

- **Branch:** `main`
- **Klasör:** `/` (root)
- **Custom domain:** `tinkbold.com` (`CNAME` dosyasında)

Kurulum adımları: [GITHUB-PAGES-KURULUM.md](./GITHUB-PAGES-KURULUM.md)

## İçerik güncelleme

Ana uygulama repodaki `legal/ezan-vakti/` klasöründen kopyalayın:

```bash
cp -R ../ezan-vakti-guncel/legal/ezan-vakti ./
git add ezan-vakti/
git commit -m "Update legal pages"
git push
```

İletişim: beratlaleci@gmail.com
