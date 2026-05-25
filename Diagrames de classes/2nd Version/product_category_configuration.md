# Configuration des categories de produits FMCG

## 1. Huiles et graisses

**Categories :**
- Olive Oil
- Argan Oil
- Vegetable Oil
- Margarine

**Attributs configurables :**
- `oilType` : type d'huile
- `extractionMethod` : methode d'extraction (premiere pression a froid, raffinage, etc.)
- `acidityRate` : taux d'acidite
- `refined` : huile raffinée ou non
- `organic` : certification biologique
- `bottleVolume` : volume en litre
- `fatComposition` : composition en acides gras

**Contraintes :**
- Lot tracking recommande
- DDM recommandee
- Certifications possibles : organic, halal, food grade

---

## 2. Conserves et bocaux

**Categories :**
- Olives
- Canned Sardines
- Tomato Sauce and Tomato Concentrates

**Attributs configurables :**
- `preservationMethod` : methode de conservation (sterilisation, pasteurisation)
- `drainedWeight` : poids egoutte
- `netWeight` : poids net
- `medium` : milieu de conservation (huile, sauce, eau)
- `canType` : type de boite
- `sterilized` : sterilise ou non

**Contraintes :**
- DDM obligatoire
- Lot tracking obligatoire
- Poids net / poids egoutte selon produit

---

## 3. Boissons

**Categories :**
- Fruit Juices
- Soft Drinks
- Orange Concentrate

**Attributs configurables :**
- `volume` : volume en litre
- `sugarContent` : teneur en sucre
- `juicePercentage` : pourcentage de jus
- `carbonated` : boisson gazeuse ou non
- `brixLevel` : degre Brix
- `concentrateRatio` : ratio de concentration
- `pasteurized` : pasteurise ou non

**Contraintes :**
- DDM
- Lot tracking
- Nutrition
- Taux de sucre utile pour filtres

---

## 4. Epicerie seche

**Categories :**
- Pasta and Couscous
- Noodles
- Wheat Flour and Semolina
- Dry Yeast
- Carob Powder

**Attributs configurables :**
- `grainType` : type de cereale
- `flourType` : type de farine
- `proteinRate` : taux de proteines
- `humidityRate` : taux d'humidite
- `glutenPresence` : presence de gluten
- `format` : format (poudre, granules, pates)
- `cookingTime` : temps de cuisson

**Contraintes :**
- Allergenes
- Gluten
- DDM
- Stockage sec

---

## 5. The, herbes et epices

**Categories :**
- Green Tea, Black Tea and Infusions
- Aromatic Herbs
- Organic Saffron

**Attributs configurables :**
- `plantType` : type de plante
- `form` : forme (feuilles, poudre, sachets)
- `grade` : grade qualite
- `organic` : certification biologique
- `harvestYear` : annee de recolte
- `dryingMethod` : methode de sechage
- `infusionTime` : temps d'infusion recommande
- `aromaProfile` : profil aromatique

**Contraintes :**
- Origine
- Grade qualite
- Certification bio si concerne

---

## 6. Snacks et confiserie

**Categories :**
- Biscuits
- Confectionery
- Popcorn / Cotton Candy
- Licorice / Jellys
- Chocolate
- Chips and Salted Snacks

**Attributs configurables :**
- `flavor` : gout / parfum
- `sugarContent` : teneur en sucre
- `saltContent` : teneur en sel
- `cocoaPercentage` : pourcentage de cacao
- `fatContent` : teneur en matieres grasses
- `texture` : texture
- `individuallyWrapped` : emballage individuel

**Contraintes :**
- Allergenes
- Nutrition
- DDM
- Taux sucre/sel utiles pour filtres

---

## 7. Produits laitiers

**Categories :**
- Dairy Products (UHT Milk)
- Cheese

**Attributs configurables :**
- `dairyType` : type de produit laitier
- `milkOrigin` : origine du lait
- `fatPercentage` : pourcentage de matiere grasse
- `pasteurizationType` : type de pasteurisation
- `uht` : UHT ou non
- `lactoseFree` : sans lactose
- `cheeseTexture` : texture du fromage
- `maturationDays` : jours de maturation
- `storageTemperature` : temperature de stockage

**Contraintes :**
- DLC ou DDM selon produit
- Chaine du froid possible pour fromage
- Allergene lait

---

## 8. Surgele

**Categories :**
- Frozen Red Fruits
- Frozen Fish
- Frozen Ready Meals

**Attributs configurables :**
- `freezingMethod` : methode de congelation
- `storageTemperature` : temperature de stockage
- `temperatureMin` : temperature minimale
- `temperatureMax` : temperature maximale
- `thawingInstructions` : instructions de decongelation
- `cookingInstructions` : instructions de cuisson
- `glazingRate` : taux de glaçage

**Contraintes :**
- Chaine du froid obligatoire
- Temperature de stockage
- Lots
- DLC/DDM
- Instructions de decongelation/cuisson

---

## 9. Fruits frais

**Categories :**
- Fresh Fruits
- Dates

**Attributs configurables :**
- `variety` : variete
- `caliber` : calibre
- `grade` : grade qualite
- `harvestDate` : date de recolte
- `harvestSeason` : saison de recolte
- `ripenessLevel` : niveau de maturite
- `treatment` : traitement
- `storageHumidity` : humidite de stockage
- `storageTemperature` : temperature de stockage

**Contraintes :**
- Saisonnalite
- Calibre
- Origine
- Lot/recolte

---

## 10. Huiles essentielles

**Categories :**
- Essential Oils

**Attributs configurables :**
- `botanicalName` : nom botanique
- `extractionMethod` : methode d'extraction
- `plantPartUsed` : partie de la plante utilisee
- `purityPercentage` : pourcentage de purete
- `usageType` : type d'usage (alimentaire, cosmetique, externe)
- `chemotype` : chemotype
- `safetyWarnings` : avertissements de securite
- `foodGrade` : qualite alimentaire

**Contraintes :**
- `usageType` obligatoire
- Distinguer alimentaire, cosmetique, usage externe
- Avertissements de securite possibles

---

## 11. Hygiene et papier

**Categories :**
- Hygiene and Paper Products

**Attributs configurables :**
- `paperType` : type de papier
- `plyCount` : nombre de plis
- `sheetCount` : nombre de feuilles
- `rollCount` : nombre de rouleaux
- `grammage` : grammage
- `absorbencyLevel` : niveau d'absorbance
- `softnessLevel` : niveau de douceur
- `fragranceFree` : sans parfum
- `recycledContentPercentage` : pourcentage de contenu recycle
- `biodegradable` : biodégradable ou non
- `recyclablePackaging` : emballage recyclable
- `intendedUse` : usage prevu

**Contraintes :**
- Pas de nutrition
- Pas d'allergenes alimentaires
- Lots recommandes
- Informations recyclage/ecologie utiles
- Prevoir future extension si produits chimiques ajoutes
