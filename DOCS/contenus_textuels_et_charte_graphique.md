# Kit de ressources pédagogiques (« Bio & Co »)

Ce document rassemble les contenus textuels bruts et les spécifications de la charte graphique nécessaires pour réaliser l'intégration des 4 exercices.

---

## 1. Charte graphique & Variables CSS

Les valeurs ci-dessous doivent être centralisées sous forme de variables personnalisées dans la feuille de style principale :

```css
:root {
  /* Palette de couleurs */
  --color-primary: #2d5a27;      /* Vert forêt / Marque */
  --color-secondary: #a3b18b;    /* Vert sauge / Accompagnement */
  --color-accent: #dda15e;       /* Terracotta doux / Mise en avant & prix */
  --color-bg-light: #fefae0;     /* Blanc cassé / Fond de page */
  --color-text: #283618;         /* Texte principal */
  --color-text-muted: #606c38;   /* Texte secondaire */
  --color-white: #ffffff;

  /* Typographie */
  --font-main: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

  /* Espacements */
  --spacing-xs: 0.5rem;
  --spacing-sm: 1rem;
  --spacing-md: 1.5rem;
  --spacing-lg: 2rem;
  --spacing-xl: 3rem;

  /* Rayon de bordure */
  --radius-sm: 4px;
  --radius-md: 8px;
}
```

---

## 2. Contenus textuels par exercice

### Exercice 1 : Fiche produit et encadré légal (« Le Savon Solide Argan »)
* **Titre principal du produit :** Savon Surgras Bio à l'Huile d'Argan
* **Accroche :** Nourrissant et protecteur, idéal pour les peaux sèches et sensibles. Fabriqué à froid en France.
* **Description des ingrédients :** 
  * *Huile d'argan bio* : Riche en vitamine E et en antioxydants, elle nourrit intensément et prévient le dessèchement cutané.
  * *Beurre de karité brut* : Apporte douceur et élasticité à l'épiderme.
  * *Glycérine végétale naturelle* : Issue de la saponification, elle maintient l'hydratation naturelle de la peau.
* **Conseils d'utilisation :** Faire mousser sur peau mouillée, masser délicatement le visage ou le corps, puis rincer abondamment à l'eau claire. Éviter le contact avec les yeux.
* **Encadré légal (CGV & Retours) :** 
  > **Conditions générales et retours :** Conformément à l'article L. 221-18 du Code de la consommation, vous disposez d'un délai de 14 jours à compter de la réception de votre commande pour exercer votre droit de rétractation. Les retours sont acceptés uniquement pour les produits non déballés et dans leur emballage d'origine. Frais de port de retour à la charge du client, sauf produit endommagé ou non conforme.
* **Formulaire d'avis rapide (Labels et champs attendus) :**
  * Libellé : Votre adresse email
  * Libellé : Votre avis sur le produit
  * Bouton de validation : Envoyer mon avis

---

### Exercice 2 : En-tête de navigation et identité de marque
* **Identité / Logo :** Bio & Co
* **Liens du menu de navigation :**
  * Visage
  * Corps
  * Zéro Déchet
  * Nos Engagements
* **Boutons d'action :**
  * Mon Compte
  * Panier (0)

---

### Exercice 3 : Catalogue de produits phares (Grille de 4 cartes)

* **Carte 1 :**
  * Badge / Label : Best-seller
  * Nom : Shampoing Solide Douceur
  * Description : À l'huile de ricin et argile blanche. Cheveux normaux à regraissant vite.
  * Prix : 8,50 €

* **Carte 2 :**
  * Badge / Label : Nouveau (-15%)
  * Nom : Crème Hydratante Visage
  * Description : Extrait d'aloe vera et jojoba bio. Tous types de peaux, format 50ml.
  * Prix : 14,90 € *(au lieu de 17,50 €)*

* **Carte 3 :**
  * Badge / Label : Zéro Déchet
  * Nom : Brosse à Dents Bambou
  * Description : Poils souples infusés au charbon actif, manche biodégradable.
  * Prix : 4,20 €

* **Carte 4 :**
  * Badge / Label : Éco-recharge
  * Nom : Déodorant Baume Cacao
  * Description : 100% d'origine naturelle, sans sels d'aluminium. Parfum coco.
  * Prix : 9,00 €

---

### Exercice 4 : Section des avis clients et réassurance
* **Titre de la section :** Ce que pensent nos clients
* **Témoignage 1 :**
  > « Enfin des produits clean qui tiennent leurs promesses ! Le savon à l'argan n'assèche pas du tout la peau, je recommande les yeux fermés. » — **Élodie M.** (Avis vérifié)
* **Témoignage 2 :**
  > « Livraison ultra rapide et emballage zéro déchet irréprochable. Le shampoing solide mousse très bien, c'est validé pour toute la famille. » — **Thomas L.** (Avis vérifié)
* **Blocs de réassurance (Engagements) :**
  * **Livraison verte :** Expédition neutre en carbone via des transporteurs écoresponsables.
  * **Paiement sécurisé :** Transactions cryptées et options de paiement échelonné disponibles.
  * **Service client local :** Équipe basée en France à votre écoute du lundi au vendredi.