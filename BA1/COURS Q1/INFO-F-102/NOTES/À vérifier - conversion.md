# Points à vérifier après conversion

Cette liste est séparée des notes : aucune de ces corrections n'a été appliquée au contenu converti.

## Représentation de l'information

- [ ] Définition physique du binaire : « absence ou présence d'une charge électrique » est une simplification trop restrictive.
- [ ] Conversion décimal → binaire : le premier reste donne le bit de poids faible, et non « le nombre de départ divisé ».
- [ ] Division par 2 : préciser qu'enlever le dernier bit d'un entier non signé fournit le quotient entier ; ce bit est le reste. Une multiplication à taille fixe peut déborder.
- [ ] Partie fractionnaire : la liste des poids omet 1/8 entre 1/4 et 1/16. L'exemple 0,625 et la méthode des multiplications sont à développer.
- [ ] Complément à 1 de 5 sur 8 bits : le résultat attendu est 11111010 ; la source écrit 1111 101.
- [ ] Virgule fixe : clarifier les limites de la répartition choisie et l'exemple écrit « 2^(16) ».
- [ ] Normalisation : 0,0011₂ = 1,1₂ × 2⁻³, et non × 2⁻².
- [ ] IEEE 754 : vérifier le champ fractionnaire de 42,625. Le résultat attendu en simple précision est 0 | 10000100 | 01010101000000000000000. La dernière égalité pour 132 comporte aussi un bit supplémentaire dans la source.
- [ ] Unicode : le titre existe mais l'explication manque.
- [ ] Images : compléter les explications autour de la figure.
- [ ] Parité et Hamming : préciser les hypothèses sur le nombre d'erreurs et développer l'exemple.

## Introduction et organisation

- [ ] « Transistors : cuivre et silicium » ne constitue pas une définition ; préciser ou déplacer cette mention.
- [ ] Programme du second degré : les deux racines calculées ne sont pas affichées ; l'exemple suppose a ≠ 0.
- [ ] Ordre des octets : la partie est amorcée mais non développée ; du contenu sur le CPU figure sous ce titre.
- [ ] Cache : vérifier les capacités et niveaux donnés à titre d'exemples ; les registres et la RAM ne sont pas des niveaux de cache. L2 n'est pas le dernier niveau possible.
- [ ] Registre IR : il conserve l'instruction récupérée en cours de traitement, et non l'adresse ou l'instruction suivante. Développer la distinction PC/IR.
- [ ] CISC/RISC : revoir le nom « Paterson », la date et la comparaison historique ; ARM et Intel sont des exemples à contextualiser.
- [ ] Pipeline et architecture superscalaire : les figures ont toujours la légende « A définir ».
- [ ] Les schémas des additionneurs et du décalage restent des emplacements textuels, comme dans les sources.

## Sources et mise en forme

- Le fichier LaTeX d'origine et le PDF présentent une différence : la section « Des transistors aux circuits », présente dans le PDF, a été reprise pour conserver le contenu de ce dernier.
- Les mots, fautes, exemples et calculs d'origine ont été conservés. Cette conversion n'est pas une correction scientifique complète.
- Les passages ont été regroupés sous les rubriques du syllabus. Les numéros des noms de fichiers suivent le classement déjà commencé dans le coffre ; les numéros des sous-parties renvoient au syllabus.
- Les sauts de page, couleurs et positionnements propres à LaTeX ne sont pas reproduits à l'identique. Les formules, listes, tableaux, légendes, images et le code ont été adaptés au Markdown.
- Le syllabus, les diapos annotées et les exports Goodnotes restent des références : ils n'ont pas été retranscrits ou fusionnés dans cette conversion.
