# Demo Site Vitrine — Yves Roland NKOME

Site vitrine one-page pour **Yves Roland NKOME — Business Developer**.

## Aperçu

Le site présente un positionnement professionnel autour de :

- développement commercial B2B ;
- prospection et qualification ;
- partenariats stratégiques ;
- stratégie de croissance ;
- négociation et closing.

L’objectif de cette première version est de disposer d’une base sobre, premium, responsive et facile à personnaliser.

## Stack

- HTML5
- CSS3
- JavaScript Vanilla
- Google Fonts : DM Sans + Manrope
- aucune dépendance JavaScript
- aucun framework CSS

## Structure

```text
.
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Lancer le site en local

Le site étant statique, il peut être ouvert directement dans un navigateur.

Pour un serveur local :

```bash
python3 -m http.server 8000
```

Puis ouvrir :

```text
http://localhost:8000
```

## Personnalisation à prévoir

Cette première version n’invente volontairement aucune donnée personnelle non fournie.

À compléter lorsqu’elles seront disponibles :

1. photo professionnelle d’Yves ;
2. adresse e-mail ;
3. téléphone ;
4. profil LinkedIn ;
5. localisation / zone d’intervention ;
6. expériences professionnelles ;
7. secteurs d’activité ;
8. réalisations, références ou chiffres clés ;
9. CV téléchargeable si souhaité.

### Formulaire de contact

Le formulaire prépare actuellement un e-mail dans l’application de messagerie de l’utilisateur **sans destinataire prérempli**.

Une fois l’adresse professionnelle d’Yves connue, on pourra :
- la renseigner directement dans `script.js` ;
- ou connecter le formulaire à Formspree, EmailJS ou une API dédiée.

## Design

Direction artistique :
- bleu nuit pour la confiance et le positionnement B2B ;
- doré comme accent premium ;
- fond ivoire / minéral ;
- typographie éditoriale et forte hiérarchie ;
- animations légères au scroll ;
- navigation responsive.

## Déploiement

Le site peut être déployé sans build sur :
- GitHub Pages ;
- Vercel ;
- Netlify ;
- Cloudflare Pages.

## Prochaines évolutions possibles

- intégration de la photo réelle ;
- section Expériences / Parcours ;
- portfolio de réalisations ;
- témoignages ;
- version anglaise ;
- SEO enrichi et Open Graph ;
- analytics ;
- formulaire de contact connecté ;
- nom de domaine personnalisé.
