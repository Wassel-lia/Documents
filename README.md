# Wassel'lia – Déménagement à prix fixe au Maroc

> Déménagement sans surprise – Prix fixe, équipe coordonnée, 48h garanti.  
> Casablanca · Rabat · Fès · Kénitra · Tanger · Tétouan · Meknès

---

## 📌 Vue d’ensemble

Wassel'lia est une plateforme marocaine de mise en relation entre particuliers (étudiants, familles, jeunes actifs) et déménageurs vérifiés. Le client décrit son déménagement en ligne (inventaire, adresses, formule transport seul ou clé en main), reçoit un devis détaillé généré par IA sur WhatsApp, et finalise sa réservation par contrat électronique ou paiement sécurisé – le tout en moins de 48h.

**Modèle économique :** Commission de 25% sur chaque déménagement. Modèle asset‑light (pas de flotte propre). Sleeping partner : 250 kDH injectés en Y1, remboursement 500 kDH (50% du résultat net).

**Statut :** Lauréat SNEE (UH2C – Université Hassan II Casablanca)

---

## 📁 Structure du dépôt

| Fichier | Description |
| :--- | :--- |
| `0_Sources.html` | Liste complète des sources – données marché, concurrents, juridique, financier |
| `1_Wassel'lia.html` | One‑pager principal (problème, solution, tarifs, équipe, traction) |
| `2_Marche_analyse.html` | ICP, 4P, PESTEL, TOWS, 5 forces, TAM/SAM/SOM |
| `3_Cadre_legal.html` | Structure juridique, contrats, CNSS, CNDP, assurances, TVA |
| `4_Business_Model_Canvas.html` | Business Model Canvas – partenaires, activités, ressources, coûts, revenus |
| `5_Financial_Statements.html` | P&L, bilan, trésorerie, unit economics (Y1-Y10 – scénario prudent) |
| `6_Cash_Flow_Balance_Sheets.html` | Flux de trésorerie détaillé (mensuel + annuel) et bilans |
| `7_Forecast_Charts.html` | Graphiques – CA, résultat net, trésorerie, marge, volume |
| `8_Software_Specifications.html` | Architecture cloud, PWA, base de données, edge functions, IA |
| `9_Design_UI.html` | Charte graphique, typographie, composants, mobile‑first |
| `10_Processus_48h_WhatsApp.html` | Processus 48h, flux WhatsApp, statuts, garantie |
| `11_Risk_Register.html` | Risques opérationnels, concurrence, financiers, juridiques, technologiques |
| `12_ESG_Impact_Report.html` | Impact social, environnemental, alignement ODD, économie circulaire |
| `13_TradeSecret_Collapse.html` | Déclaration d’existence – secret commercial & protocole d’effondrement |
| `SECURITY.md` | Politique de signalement des vulnérabilités |
| `LICENSE.md` | Licence propriétaire (confidentiel – usage limité) |
| `index.html` | Page d’accueil de la documentation |

> ⚠️ **Note :** Les documents `666.html` et `999.html` (Secret commercial & Protocole d’effondrement – versions complètes) ne sont **PAS** dans ce dépôt. Ils existent hors ligne, accessibles uniquement aux trois co‑fondateurs via authentification matérielle (Yubikey).

---

## 🚀 Indicateurs clés (scénario prudent 2027‑2036 / Y1-Y10)

| Indicateur | Y1 (2027) | Y10 (2036) |
| :--- | :--- | :--- |
| Déménagements annuels | 1 500 | 6 460 |
| Chiffre d’affaires HT (kDH) | 450 | 2 426 |
| Résultat net après part (kDH) | 145 | 778 |
| Marge nette après part | 32,2% | 32,1% |
| Trésorerie fin d’année (kDH TTC) | 529 | 10 898 |
| Salariés (hors fondateurs) | 1 | 29 |
| Émissions CO₂ évitées (t/an) | 22,5 | 96,9 |
| Cartons réutilisés (cumul) | 7 500 | 75 000 |

**Unit economics :**
- Commission moyenne : 300 DH par déménagement
- Marge brute : 25% (fixe)
- Seuil de rentabilité : atteint dès le 1er mois
- Sleeping partner : injection 250 kDH, remboursement 500 kDH en Y3

---

## 🛠️ Stack technique

| Couche | Technologie |
| :--- | :--- |
| **Frontend** | React 18, TypeScript, Vite, TailwindCSS, shadcn/ui, Framer Motion |
| **Backend** | Supabase (PostgreSQL, Auth, Storage, RLS) |
| **Edge Functions** | Deno (génération devis IA, PDF, webhooks) |
| **IA** | Lovable / OpenAI – génération de devis détaillé avec justificatif |
| **Cartographie** | Google Distance Matrix API (calcul distance routière) |
| **Paiement** | Stripe (phase 2) + paiement à l’arrivée (espèces/virement) |
| **Mobile** | PWA (installable) – Capacitor pour builds natifs futurs |

---

## 🔒 Propriété intellectuelle

| Actif | Statut | Accès |
| :--- | :--- | :--- |
| **Marque** | Déposée – « Wassel'lia » et « Wssel » (OMPIC, classes 35,39,42) | Public |
| **Droit d’auteur** | Code source, algorithme IA | Protégé, non public |
| **Secret commercial** | Actif, stocké hors ligne (`666.html`) | Fondateurs uniquement |
| **Protocole d’effondrement** | Actif, stocké hors ligne (`999.html`) | Fondateurs uniquement (2FA Yubikey + phrase morte) |

---

## 📊 Documents prioritaires pour investisseurs

| Priorité | Document | Objectif |
| :--- | :--- | :--- |
| 1 | `1_Wassel'lia.html` | Synthèse exécutive |
| 2 | `5_Financial_Statements.html` | Projections financières & unit economics |
| 3 | `6_Cash_Flow_Balance_Sheets.html` | Flux de trésorerie et bilans |
| 4 | `4_Business_Model_Canvas.html` | Modèle de revenus & structure de coûts |
| 5 | `2_Marche_analyse.html` | Taille du marché & positionnement concurrentiel |

---

## 👥 Co‑fondateurs

| Nom | Rôle |
| :--- | :--- |
| **Zayd Bentalha** | Co‑fondateur – Stratégie, finance, levée de fonds, commercial |
| **Selma Rouchdi** | Co‑fondatrice – Marketing digital, acquisition, relation prestataires, communication |
| **Douaa Ghilali** | Co‑fondatrice – Développement full‑stack, intégration IA, base de données, sécurité |

*Lauréats SNEE (UH2C – Université Hassan II Casablanca)*

---

## 📞 Contact

- **Email :** wassel.lia@gmail.com
- **WhatsApp :** +212 679 267 545
- **Instagram :** @wassellia
- **Facebook :** Wassel'lia
- **Statut :** Pré‑amorçage / bootstrappé – recherche d’un sleeping partner (250 kDH)

---

## 📜 Licence & confidentialité

Tous les documents de ce dépôt sont **confidentiels** et destinés à :
- La due diligence d’investisseurs
- Les soumissions à des concours
- La référence interne uniquement

**Ne pas** distribuer, copier ou référencer sans autorisation explicite des co‑fondateurs.

---

## 📝 Dernière mise à jour

Avril 2026

---

*Déménagement transparent, prix fixe, équipe coordonnée.*