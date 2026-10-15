# links.sakoi-cyber.me

Page de liens (type « Linktree ») de Dmod, auto-hébergée et **sans pistage**.
Site statique publié par **GitHub Pages**. Un seul fichier à éditer : `index.html`.

## Modifier les liens

Ouvre `index.html` sur github.com, section `<nav class="links">`. Chaque lien est un bloc :

```html
<a class="lnk" href="https://exemple.com" style="--c:#7ee2a8">
  <span class="ic">…icône SVG…</span>
  <span class="t"><b>Titre</b><span>Sous-titre</span></span>
  <span class="go">…flèche…</span>
</a>
```

- `href` : la destination.
- `--c:#xxxxxx` : la couleur de survol et de l'icône.
- `<b>` et `<span>` : le titre et le sous-titre.

**Commit changes** → en ligne ~1 minute plus tard.

## Domaine

`CNAME` contient `links.sakoi-cyber.me`. Côté Cloudflare, un enregistrement
**CNAME** `links` → `h1v3-lab.github.io.` (DNS only, nuage gris).
Dans GitHub → Settings → Pages, cocher **Enforce HTTPS**.

Aucune police ni script tiers : tout est hébergé ici.
