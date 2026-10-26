# Exercices

## Partie 1
Les exercices sont à réaliser dans l'application en ligne [Regex101](https://regex101.com/)

```
Carnet de terrain, vallée d'Aspe (Pyrénées-Atlantiques)
Notes de Jean-Baptiste Marcellin (1749-1788), recopiées en 2019 par Marie-Claire Dufour.

12 mars 1749. Un isard descend vers le gave ; il est suivi d'un jeune de l'année, qui pèse 2,5 kg. Le troupeau compte dix-huit bêtes.
3 juin 1763. Ma première marmotte de l'année siffle au-dessus du col, à 2 100 m. Elle est extraordinairement  vive.
21 août 1771. Un ours brun, grrr, puis « grrrrr », se dresse dans la hêtraie ; j'ai noté « grr » dans mon carnet.
Registre latin des peaux de loup : lupa, lupi, lupo, puis lupos, lupis et enfin lupus.
5 mai 1802. Louis-Philippe Garnier, cité par erreur sous le nom de « MArcellin », signale un gypaète barbu. Il se réfère à BUffon,
qu'il lit chaque soir. Ce Garnier est incontestablement   précis.
En 2019, Marie-Claire Dufour pèse un marmotton : 2.5 kg, comme l'isard de 1749 ; elle retrouve aussi 3,5 kg chez la marmotte adulte.
```

### Caractères littéraux et métacaractères

1. Cherchez “un”. Que constatez-vous ? 

2. Trouver “lupa”, “lupi” et “lupo”.

3. Trouver tous les points et les virgules.

4. Remplacer “il” et “elle” par “iel”

5. Corriger “2.5 kg” en “2,5 kg”

6. Trouver “(Pyrénées-Atlantiques)”

### Classes de caractères

1. Trouver “marmotte” et “marmotto”

2. Trouver “lupos” et “lupis”, mais pas “lupus”.

3. Trouver toutes les années.

4. Trouver les années à partir de 2000.

5. Trouver les années antérieurs à 1800.

6. Trouver les années de 1700 à 1749.

### Quantificateurs

1. Trouver “grrr”, “grrrrr” et “grr”. Les remplacer par “ouille”.

2. Trouver les années antérieures à 1900.

3. Trouver les prénoms composés.

4. Trouver les mots de 15 lettres et plus.

5. Trouver les espaces doublées et les remplacer par une seule espace.

6. Trouver les mots qui commencent par deux majuscules.

## Partie 2

```
Notice : le renard roux (Vulpes vulpes)
Auteur : Camille Lenoir
Source : https://exemple.org/faune/renard-roux (consulté en 2021).
Observations transmises par M. Dubois, Mme Martin et Mlle Bernard, relevées le 03/11/2019 et le 12-05-2021.

Le renard roux[^ voir la fiche complète du Muséum] vit dans les bois, les prés et les villes. Longueur : 90 cm ; poids : 6 kg.
Il chasse au crépuscule, avec patience, sur un sol sec ou au bord d'un lac. Son régime est varié : campagnols, campagnols,
campagnols, fruits, insectes.
Les anciens le jugeaient "rusé comme un renard", mais un renard pas rusé finit mal ; un renard rusé survit. Le renard polaire
(Vulpes lagopus) vit plus au nord ; le renard véloce, sur les prairies d'Amérique. Ce renard est très très très prudent.

Le renard passe au crépuscule,
sa fourrure brille dans l'herbe ;
il guette le mulot qui recule,
Puis disparaît, souple et superbe.
```

### Groupes

1. Supprimer les civilités. Obtenir “Dubois, Martin et Bernard”.

2. Transformer “Auteur : Camille Lenoir” en “Auteur : Lenoir, Camille”.

3. Trouver les mots répétés trois fois.

4. Convertir l’URL en markdown.

5. Remplacer les guillemets droits en guillemets français.

6. Transformer la note [^ voir la fiche…] en <note>voir la fiche…</note>

7. Supprimer les civilités. Obtenir “Dubois, Martin et Bernard”.

### Ancres

1. Trouver tous les mots terminant par la lettre “c”.

2. Trouver tous les mots d’exactement 3 lettres.

3. Trouver tous les “c” en milieu de mot.

4. Trouver les minuscules en début de vers.

5. Trouver les vers qui se terminent par une virgule.

### ***Lookahead*** et ***lookbehind***

1. Trouver les occurrences de "renard" suivi de "roux", sans capturer "roux".

2. Trouver les nombres qui ne sont pas suivis d'une unité, sans capturer l'unité.

3. Trouver les mots suivis d'une virgule, sans capturer la virgule.

4. Trouver "rusé" sauf dans l'expression "pas rusé".

5. Trouver le mois de la date "12-05-2021".

6. Extraire le texte de la note de bas de page sans les délimiteurs, puis le texte entre guillemets sans capturer les guillemets.
