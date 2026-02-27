# ReFollow Policies

Policy and support site for the ReFollow app (Gezegensel Core). Hosted on GitHub Pages.

## Setup

- **Branch:** `main`
- **GitHub Pages:** Repository → Settings → Pages → **Deploy from a branch** → Branch: `main`, Folder: **/(root)** → Save.

### İlk yayın (bir kez)

1. GitHub’da **gezegenselcore** hesabıyla yeni repo oluştur: [New repository](https://github.com/new?name=refollow-policies) — isim: `refollow-policies`, Public, README/gitignore ekleme.
2. Lokal projede (zaten yapıldı): `git remote add origin https://github.com/gezegenselcore/refollow-policies.git` (veya `git remote -v` ile kontrol et).
3. `git push -u origin main` ile gönder.
4. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main**, Folder: **/(root)** → Save. Birkaç dakika sonra sayfalar yayında olur.

## Pages

| Page | URL |
|------|-----|
| Home | https://gezegenselcore.github.io/refollow-policies/ |
| Privacy | https://gezegenselcore.github.io/refollow-policies/privacy.html |
| Terms | https://gezegenselcore.github.io/refollow-policies/terms.html |
| Support | https://gezegenselcore.github.io/refollow-policies/support.html |

## Structure

```
├── index.html      # ReFollow Policies (home)
├── privacy.html    # Gizlilik Politikası / Privacy Policy
├── terms.html      # Kullanım Şartları / Terms of Use
├── support.html    # Destek / Support (export steps, FAQ, contact)
├── assets/
│   └── style.css   # Minimal, mobile-friendly styles
└── README.md
```

Content is in **Turkish + English** on each page. Last updated: 2025-02-26.
