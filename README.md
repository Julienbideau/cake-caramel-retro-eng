# Projet "Cake Honoré" — Recherche & développement

> Reproduire le **Cake au Caramel** de la Boulangerie d'Honoré (vu à la cantine Doctolib, vendu chez La Boulangerie d'Honoré, Paris).
> Profil cible : mie orangée-cuivrée, croûte fortement caramélisée acajou, profil aromatique caramel lacté ("Carambar"), amandes effilées.
> Allergènes officiels : gluten, œufs, lait, sulfites, fruits à coques.

## Lignée des versions

```
V1 (caramel pot + spéculoos)         ❌ beige raté
 │
 ├─→ V2 (miel forêt + mascobado)     ❌ effondrée + goût pain d'épices
 │    │
 │    └─→ V2bis SANS LACTOSE         🔱 fork pain d'épices châtaignier (Madame approved)
 │
 └─→ V3 (vergeoise + huile)          ✅ mie parfaite, ❌ croûte ratée
      │
      └─→ V4 (vergeoise + beurre)    ❌ croûte parfaite, ❌ mie quatre-quarts
           │
           └─→ V5 (caramel lacté +   ✅ Carambar OK, tout le monde a aimé
                   beurre noisette +     ❌ AB testing : couleur trop sombre,
                   crème + maryse)         mie trop dense, pas de "boom beurre"
                │
                ├─→ V6 (eau bouillante)  ⚠️ basée sur diag erroné "fudge", ignorer
                │
                └─→ V7 (vergeoise +      🎯 à tester : pivot "cake riche aéré"
                        beurre + huile +     pas fudge, plus orangé, friable
                        levure chimique)
```

## Index des fichiers

| Fichier | Statut | Note |
|---|---|---|
| [`cake-honore-v1.md`](cake-honore-v1.md) | ❌ Échec | Caramel en pot dilué → couleur beige |
| [`cake-pain-epices-v2.md`](cake-pain-epices-v2.md) | ❌ Effondrée | Bicarbonate surdosé + repos frigo |
| [`cake-honore-v3.md`](cake-honore-v3.md) | ✅ Mie validée | "La Magnifique" — manque la croûte |
| [`cake-honore-v4.md`](cake-honore-v4.md) | ⚠️ Mixte | Croûte OK mais mie quatre-quarts |
| [`cake-honore-v5.md`](cake-honore-v5.md) | ✅ Très bon, ❌ pas Honoré | Validé en bureau ; AB test révèle écart couleur + texture |
| [`cake-honore-v6.md`](cake-honore-v6.md) | ⚠️ Ignorer | Basé sur diagnostic erroné (fudge), avant AB testing |
| [`cake-honore-v7.md`](cake-honore-v7.md) | 🎯 À tester | Pivot post-AB : vergeoise + beurre/huile + levure chimique |
| [`cake-pain-epices-v2bis-sans-lactose.md`](cake-pain-epices-v2bis-sans-lactose.md) | 🔱 Fork | Pain d'épices châtaignier sans lactose |

## Apprentissages-clés (synthèse)

### Sur la couleur de la mie (orangée-cuivrée Honoré)
- ✅ **Vergeoise brune** ou **muscovado** = base sombre indispensable
- ✅ **Bicarbonate** (alcalinise → boost Maillard) — pas de levure chimique
- ✅ **Café soluble** (1 c. à c.) = booster discret
- ✅ **Eau bouillante** (V3) = aide à la couleur via dissolution complète des sucres
- ❌ Caramel en pot industriel ≠ caramel maison foncé
- ❌ Miel = donne couleur mais aussi goût pain d'épices non voulu

### Sur la croûte (acajou caramélisé)
- ✅ **Beurre fondu** dans la pâte (vs huile) = Maillard sur les bords
- ✅ **Beurrer + saupoudrer vergeoise** sur paroi du moule
- ✅ **Cuisson 165 °C chaleur tournante** (pas 150 °C statique)
- ✅ **Moule papier (panibois)** = idéal pour caramélisation directe
- ❌ Huile seule = pas de croûte (V3)

### Sur la texture (mie dense, pas quatre-quarts)
- ✅ **Mélanger à la maryse**, jamais "fouetter vigoureusement"
- ✅ **Beurre fondu** (pas crémé pommade)
- ✅ **Crème fleurette** (gras lacté lourd qui ne s'évapore pas)
- ✅ **Caramel lacté maison** (humectant + structurant)
- ❌ "Fouetter vigoureusement" → quatre-quarts garanti
- ❌ Repos 1h frigo avec bicarbonate → effondrement

### Sur le goût ("Carambar")
- ✅ **Caramel à sec très foncé décuit à la crème** puis **re-cuit 5 min**
- ✅ **Vergeoise / muscovado** = profondeur de fond
- ✅ **Fleur de sel** = exhausteur
- ❌ Sucre brun seul = manque la note lactée caractéristique
- ❌ Miel = vire pain d'épices

### Pratique transverse
- ✅ **Filmer hermétiquement encore tiède** (momification)
- ✅ **Repos 24 h à T° ambiante** (pas frigo) avant dégustation
- ✅ **Œufs à T° ambiante**

## À tester ensuite

- 🎯 **V5** telle qu'écrite (priorité absolue)
- 🛟 **Plan B** si mie V5 régresse vs V3 : refaire V3 telle quelle mais cuire dans **moule papier panibois** au lieu du Pyrex (récupère la croûte sans toucher la chimie de la mie)
- 🔱 **V2bis** version sans lactose (fork pain d'épices) à tester en parallèle pour avis Madame

## Sources externes consultées

- Page produit La Boulangerie d'Honoré : <https://laboulangeriedhonore.fr/produit/cake-au-caramel/>
- Référence couleur (pain d'épices Borie d'Imbert)
- Cake ultime au caramel — La cuisine de Bernard
- Cake au caramel beurre salé — Jujube en cuisine
- Cake vanille/caramel/muscovado — iletaitungateau (architecture)
