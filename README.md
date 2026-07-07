# Anaé — Refonte de la page produit

Refonte de la fiche produit **Anaé — Cutting Mix Berbérine + Yerba Maté** sur le thème Shrine Pro.
Déployé sur le thème brouillon **« Shrinepro vClaude »** (non publié).

## Charte graphique utilisée
- Primaire (framboise) : `#D4537E`
- Accent (terracotta) : `#E8915B` — dégradé `linear-gradient(54deg, #E8915B, #D4537E)`
- Texte : `#3A2A22`
- Fonds : crème `#FBF3E9` / beige `#F0DCC4`
- Titres : Fraunces (serif) · Corps : Nunito Sans

## Fichiers

### `templates/product.json`
Reconfiguration de la colonne d'achat :
- Titre aligné à gauche + **étoiles d'avis** (couleur primaire, `(127 avis)`) cliquables → ancre `#avis`.
- Prix inchangé.
- Bloc **custom_liquid** sous le bouton Ajouter au panier : 3 bénéfices clés (icône + texte),
  badges de paiement (`shop.enabled_payment_types`), garantie **Satisfait ou remboursé 60 jours**,
  3 lignes de réassurance (Livraison France & Québec / Paiement sécurisé / Garantie 60 j).
- Bloc description (pourquoi le produit, bénéfices, garantie).
- Accordéons : Composition & ingrédients / Conseils d'utilisation / Livraison & retours / Garantie 60 jours.
- Timeline de livraison **supprimée**.
- Section « Nos bénéfices clés » : titre **aligné à gauche**.
- Nouvel ordre des sections (voir ci-dessous).

### Sections de contenu (inspirées de resilia.shop, adaptées au branding Anaé)
Images laissées en **placeholder** (« Image à venir ») en attendant la génération des visuels.
- `sections/anae-ingredients.liquid` — mise en avant de la formule / ingrédients.
- `sections/anae-how-it-works.liquid` — « Comment ça marche » (3 étapes).
- `sections/anae-benefits.liquid` — bénéfices appuyés par les actifs.
- `sections/anae-five-reasons.liquid` — « 5 raisons de passer à Anaé ».
- `sections/anae-reviews.liquid` — avis clients (ancre `#avis`, note + témoignages placeholder).

## Prochaine étape
Génération des icônes (3 bénéfices, badges) et des images des sections, puis publication du thème.
