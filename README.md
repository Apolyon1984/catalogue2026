# catalogue2026

Deux pages autonomes (HTML, sans dépendance serveur), publiables via GitHub Pages :

| Fichier | Contenu |
|---|---|
| `index.html.html` | Catalogue Protranslex Éditions 2026 (67 ouvrages, commande WhatsApp) |
| `metamorphrase.html` | **Boutique Metamorphrase** — e-books, guides et formations, panier + commande WhatsApp |

## Boutique Metamorphrase

- **Modifier le numéro WhatsApp / le nom** : bloc `CONFIG` en haut du `<script>`.
- **Modifier les e-books** : tableau `EBOOKS` (repris du catalogue 2026) — champs `t` titre, `s` sous-titre, `a` auteur, `p` prix FCFA, `d` description.
- **Ajouter vos guides et formations** : tableaux `GUIDES` et `FORMATIONS`. Les produits d'exemple portent `demo:true` (badge « Exemple ») — supprimez ce champ ou remplacez l'entrée par votre vrai produit.
- Le panier est enregistré dans le navigateur du visiteur ; la commande part sur WhatsApp avec la liste des produits et le total pré-remplis.
