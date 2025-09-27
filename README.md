# Projet-Peroxydases-Classe3
# Caractérisation de la famille des peroxydases de classe III

Mini-projet réalisé en Master 1 Bioinformatique .  
Travail réalisé en binôme .

## Objectif
L'objectif de ce projet est de caractériser les peroxydases de **classe III** et de différencier efficacement ces séquences des peroxydases de **classe I** présentes chez les plantes.

## Contexte
- Les peroxydases sont des enzymes catalysant la réduction du peroxyde d'hydrogène (H₂O₂) tout en oxydant d'autres substrats.  
- La classe III est spécifique aux plantes et possède des fonctions variées (défense, biosynthèse de paroi, détoxification).  
- Les classes I et III se retrouvent chez les plantes, mais la classe II concerne uniquement les champignons.  

## Méthodologie
1. **Alignement multiple** des séquences des classes I et III (MAFFT, ClustalO, MUSCLE, T-Coffee).  
2. Identification de **domaines conservés** spécifiques à chaque classe.  
3. Génération de **signatures** avec PRATT et de **profils HMM** pour chaque classe.  
4. Vérification de la spécificité des HMM et signatures via comparaison avec les bases **Swiss-Prot** et **Peroxibase**.  
5. Analyse des domaines caractéristiques via **InterProScan** et **CD-Search**.  

## Résultats clés
- Les alignements multiples permettent de distinguer visuellement les classes I et III.  
- La classe III possède un **domaine de sécrétion** et conserve plusieurs cystéines impliquées dans des ponts disulfure.  
- Les profils HMM générés sont **spécifiques** à chaque classe et permettent une classification fiable des séquences.  
- Les signatures PRATT sont efficaces pour la classe III mais moins significatives pour la classe I.  

## Contenu
Ce dépôt contient uniquement les **diapositives de présentation** du projet.  
Elles résument les étapes, les analyses et les résultats obtenus. 
