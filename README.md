# Page de vente diamond3c.com

Déposer tous les fichiers (CNAME compris) à la racine d'un NOUVEAU dépôt GitHub
(par exemple `diamond3c-site`), puis Settings > Pages > branche main, dossier root,
domaine personnalisé `diamond3c.com`.

DNS OVH (zone diamond3c.com), pour le domaine nu :
- 4 enregistrements A (sous-domaine vide) : 185.199.108.153, 185.199.109.153,
  185.199.110.153, 185.199.111.153
- 1 CNAME `www` vers `diamond3c.github.io.`
(adresses de mémoire, à confirmer dans la documentation GitHub Pages)
Attention : supprimer d'abord les anciens A/AAAA et les redirections OVH du domaine nu.
Ne pas toucher au CNAME `app` : l'application reste sur app.diamond3c.com.

A compléter avant l'ouverture de la vente :
- lien de paiement dans le bouton « Acheter » (id="buy" dans index.html)
- prix (6,99 € par défaut dans index.html)
- mentions.html, confidentialite.html, cgv.html (zones jaunes)
