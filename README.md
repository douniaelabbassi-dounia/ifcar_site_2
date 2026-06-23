# Site IFCAR Solutions — Proposition 2 (thème sombre)

Deuxième proposition de design pour le site vitrine IFCAR Solutions.
Même contenu que la proposition 1, **univers visuel radicalement différent** :
sombre, premium, type agence/tech, très animé.

## Ce qui change vs la proposition 1
| | Proposition 1 | Proposition 2 (ce dossier) |
|---|---|---|
| Thème | Clair / corporate | **Sombre / premium** |
| Polices | Plus Jakarta Sans + Inter | **Space Grotesk + DM Sans** |
| Fond | Blanc + sections grises | **Orbes lumineux animés + grille + bruit** |
| Composants | Cartes classiques | **Grille bento, glassmorphism, dégradés néon** |
| Animations | Reveal + marquees | **Reveal + tilt 3D + boutons magnétiques + lueur curseur + parallax** |
| Nav | Barre pleine largeur | **Pill flottante en verre** |

## Structure
Identique à la proposition 1 : 8 pages HTML statiques, `assets/css/style.css`,
`assets/js/main.js`, images partagées. Aucune compilation.

## Charte
Mêmes couleurs marque : vert `#95ce0a`, bleu `#0081bf`, utilisées en **dégradés
néon** sur fond sombre `#070b12`. Logo en version blanche (`logo-white.png`).

## Aperçu local
```
cd ifcar_site_2 && python3 -m http.server 8002
```
→ http://localhost:8002/

## À personnaliser avant prod
Identique à la proposition 1 : téléphone, email, ICE, adresse + carte Maps,
réseaux sociaux, chiffres `data-count`, logos clients, formulaires (brancher
sur Formspree/Web3Forms). Voir le README de la proposition 1.
