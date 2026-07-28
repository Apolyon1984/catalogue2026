# catalogue2026

Deux pages autonomes (HTML, sans dépendance serveur), publiables via GitHub Pages :

| Fichier | Contenu |
|---|---|
| `index.html.html` | Catalogue Protranslex Éditions 2026 (67 ouvrages, commande WhatsApp) |
| `metamorphrase.html` | **Boutique MétamorPhrase** — e-books, guides, formations et podcasts, panier + commande WhatsApp (+223 93 48 88 80) |
| `assets/` | Logo MétamorPhrase et couvertures de livres (compressées pour le web) |

## Boutique MétamorPhrase

- **Numéro WhatsApp / nom** : bloc `CONFIG` en haut du `<script>`.
- **E-books** : tableau `EBOOKS` (71 titres, repris du catalogue 2026 + nouveautés) — champs `t` titre, `s` sous-titre, `a` auteur, `p` prix FCFA, `d` description, `img` couverture (optionnel, ex. `assets/covers/xxx.jpg`).
- **Guides** : tableau `GUIDES` — encore des exemples (`demo:true`, badge « Exemple ») à remplacer.
- **Formations** : tableau `FORMATIONS` — les 4 parcours réels (De l'idée au Manuscrit, Common Law, Pensée Critique, Traduction contrats miniers) ; les prix `p` sont indicatifs, à ajuster.
- **Podcasts** : tableau `PODCASTS` — prix `0` = « Gratuit », bouton « Recevoir » qui ouvre WhatsApp.
- Le panier est enregistré dans le navigateur du visiteur ; la commande part sur WhatsApp avec la liste des produits et le total pré-remplis.
