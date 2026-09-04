# ExtraSpeech — Site vitrine : déploiement et sources

## Déploiement sur GitHub Pages (identifiant : extraspeech)

1. github.com → New repository → nom exact **`extraspeech.github.io`** (public, sans README).
2. Dans le dossier `extraspeech-site/` (contient `index.html`), ouvrir un terminal et lancer :
   ```
   git init
   git add index.html
   git commit -m "Site ExtraSpeech v1"
   git branch -M main
   git remote add origin https://github.com/extraspeech/extraspeech.github.io.git
   git push -u origin main
   ```
3. Le site est en ligne sous quelques minutes à **https://extraspeech.github.io** — aucune configuration Pages supplémentaire n'est nécessaire pour un dépôt nommé ainsi.
4. Pour un domaine perso plus tard (ex. extraspeech.com) : Settings → Pages → Custom domain, dans ce même dépôt.

## Principes de Cialdini appliqués (et pourquoi)

- **Autorité** — diplômes (MA Portsmouth, BA Lyon II), 30+ ans, 190+ projets/100 % délais, volume MTPE. Toutes les données viennent de `IDENTITY.md` (vault), rien n'est arrondi à la hausse.
- **Preuve sociale** — les 5 recommandations LinkedIn publiques et nommées (seul levier disponible : aucun nom de client final n'est cité, conformément à la règle permanente du 9 juillet 2026). Citations reprises mot pour mot depuis `IDENTITY.md`.
- **Sympathie** — section "Why work directly" positionne Olivier comme partenaire ("with you, not for an agency against you"), ton direct et chaleureux plutôt que vendeur.
- **Rareté** — "New direct-client work is limited each quarter" : formulation plausible, non chiffrée, conforme au garde-fou anti-faux-chiffre.
- **Cohérence** — l'accroche du hero ("if your English content converts... your French version should do exactly the same") amène le lecteur à un premier constat qu'il ne peut qu'approuver avant l'argumentaire.
- **Réciprocité — volontairement absente.** Un site statique n'a pas de mécanisme naturel pour "donner d'abord" ; l'ajouter proprement demanderait une ressource téléchargeable (ex. guide terminologique), à envisager comme amélioration future plutôt que forcée ici.

## Ce qui n'est PAS sur le site (et pourquoi)
- Pas d'adresse postale (cohérent avec la décision prise pour la signature email).
- Pas de grille tarifaire chiffrée (décision du 27/08/2026 : les tarifs varient par client, communiqués sur demande).
- Aucun nom de client final (Moody's, StoneX, Kaspersky, etc.) — interdiction permanente.

## Sources du contenu (vault Obsidian)
- `Charte-Graphique-Logo.md` — couleurs, typographie, logo vectoriel
- `ExtraSpeech-Service-Offer-CANONIQUE.md` + email HTML "beyond translation" — liste des services
- `IDENTITY.md` — crédentials, témoignages, tableau des 9 secteurs
- `Cialdini-Influence-Principes.md` (projet claude.ai) — principes appliqués ci-dessus
