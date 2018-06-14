# UE génétique médicale examen 2018-06-14
Jean Jellimann
https://frama.link/jeanjellimann2018
## Exercice 1
### Q1
Les gènes associés au syndrome de Rett sont :
-MECP2
-FOXG1 (variant congenital du syndrome de Rett)
(D'après OMIM : https://www.omim.org/entry/312750?search=Rett%20syndrome&highlight=syndromic%20syndrome%20rett)
-CDKL5 (D'après http://mecp2.chw.edu.au/#mutations)
### Q2
1. NM_005249.4:c.1200C>A se trouve dans le gène FOXG1 (https://mutalyzer.nl/name-checker?description=NM_005249.4%3Ac.1200C%3EA)
2. NM_005249.4:c.326C>T se trouve dans le gène foxG1 (https://mutalyzer.nl/name-checker?description=NM_005249.4%3Ac.326C%3ET)
### Q3
Ce gène se trouve dans le chromosome X (https://www.omim.org/entry/312750?search=Rett%20syndrome&highlight=syndromic%20syndrome%20rett)
### Q4
Le mode de transmission est lié à l'X dominante (XLD : https://www.omim.org/entry/312750?search=Rett%20syndrome&highlight=syndromic%20syndrome%20rett)
### Q5
Une personne possédant un chromosome X avec la mutation exprime la maladie. Les femmes et les hommes peuvent être touchés mais l'expression est généralement plus sévère chez les hommes que chez les femmes (inactivation de l'X chez ces dernières)
### Q6
Un père malade transmet à toutes ses filles (mais pénétrance variable) mais JAMAIS à ses fils. Une mère malade transmet toujours à ses fils et une fois sur deux à ses filles.
rmq : Syndrome de Rett ==> non viable pour garçons.
### Q7
Les notations protéiques sont :
1. NM_005249.4:c.1200C>A ==> NM_005249.4(FOXG1_i001):p.(Tyr400*) (https://mutalyzer.nl/name-checker?description=NM_005249.4%3Ac.1200C%3EA)
2. NM_005249.4:c.326C>T ==> NM_005249.4(FOXG1_i001):p.(Pro109Leu) (https://mutalyzer.nl/name-checker?description=NM_005249.4%3Ac.326C%3ET)
### Q8
Prenons NM_005249.4(FOXG1_i001):p.(Tyr400*)
- NM_ : signifie qu'il s'agit de séquence d'ARNm
- 005249 : c'est le numéro d'accession du transcrit
- .4 : signifie qu'il s'agit de la 4ième version de ce transcrit
- (FOXG1_i001) : signifie que la séquence est situé dans l'isoforme 1 du gène FOXG1
- :p. : signifie qu'il s'agit d'une séquence protéique (suite d'acides aminés)
- (Tyr400*) : signifie que la Tyrosine en position 400 est remplacée par un codon stop.
### Q9
1.NM_005249.4:c.1200C>A est un variant npn-sens : il fait apparaitre un codon stop à la place d'une tyrosine.
2.NM_005249.4:c.326C>T est un variant faux-sens (remplacement d'un acide aminé (proline) par un autre (leucine).
### Q10
D'après la base de donnée de variants RettBase (http://mecp2.chw.edu.au/foxg1/foxg1_variant_list_copy.php)
1. Le variant NM_005249.4:c.1200C>A (NM_005249.4(FOXG1_i001):p.(Tyr400*)) est pathogénique ( 	22091895, De Filippis, R. et al (2012) ).
2. Le variant NM_005249.4:c.326C>T (NM_005249.4(FOXG1_i001):p.(Pro109Leu)) est probablement bénin (21280142, Le Guen, T. et al (2010) ).
### Q11
1. Pour le variant NM_005249.4:c.1200C>A : http://genome.ucsc.edu/cgi-bin/hgTracks?db=hg19&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr14%3A29237675%2D29237695&hgsid=676702359_MUdmw198lisa83b9Ivjn1Hr6wHx9
2. Pour le variant NM_005249.4:c.326C>T : http://genome.ucsc.edu/cgi-bin/hgTracks?db=hg19&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr14%3A29236801%2D29236821&hgsid=676702439_u1OtzAUSaswPWApmAOLNFoi2S5Cq
### Q12
1. Le variant NM_005249.4:c.1200C>A est sur le brin sens (flèche vers la droite dans UCSC).
2. Le variant NM_005249.4:c.326C>T est sur le brin sens aussi (flèche vers la droite sur UCSC.
### Q13
Le gène comporte un exon (visible en passant la souris sur la séquence du gène dans UCSC).
### Q14
Les deux variants se trouvent dans l'exon 1 du transcrit 5249.4

## Exercice 2
### Q1
OMIM est une base de données qui contient des informations à propos de toutes les maladies mendeléiennes connues et sur plus de 15,000 gènes. C'est un outils utile pour analyser les liens entre un phénotype observé et des gènes candidats pour expliquer ces phénotypes.
DDG2P gene list (Developmental Disorders Genotype-Phenotype Database) est une base de données contenant une liste de gènes dont on soupçonne l'association avec des troubles du développement. Elle est réalisée part des cliniciens faisant partie de l'étude DDD (Decipehering Developmental Disorders). Elle permet d'associer à un gène la probabilité qu'il soit impliqué dans un phénotype de déficience intellectuelle par exemple.
### Q2
La classification proposée par Plon et al. est une classification qui permet de classer les variant en fonction de leur probabilité d'être pathogène. C'est un système qui permet en théorie de classifier tout gène de susceptibilité à un cancer.
En fonction de différents critères les gènes sont classés dans une catégorie :
- definitely pathogenic : probabilité de poathogénicité > 0.99
- likely pathogénique : 0.95-0.99
- uncertain : 0.05-0.949
- likely not pathogenic or of little clinical significance : 0.001-0.049
-not pathogenic or of no clinical significance : <0.001
(sources : Plon SE et al (2008) Sequence variant classification and reporting: 
recommendations for improving the interpretation of cancer sus-
ceptibility genetic test results. Hum Mutat 29:1282–1291)

Il existe d'autre système de classification : par exemple celle proposée dans les recommandations de bonnes pratique de la Dutch and British societies for clinical molecular genetics (http://cmgsweb.shared.hosting.zen.co.uk/BPGs/Best_Practice_Guidelines.htm)

### Q3
a) NM_001190274.1 est le numéro de la séquence de FBXO11 prise comme référence pour l'étude de ce gène. NM_ signifie qu'il s'agit d'une séquence d'ARNm, 001190274 est le numéro d'accession de la séquenc"e et 1 signifie qu'il s'agit de la première version de cette séquence.
b)HGVS correspond à human genome variation society. Il s'agit d'une société qui a pour but de rassembler les information à propos des variants génomiques et leurs liens avec des phénotypes. La notation HGVS correspond à un système de classification des variants expliqué dans la question 3.a)
c) GRCh37/hg19 (Genome Reference Consortium Human Build 37) est un génome de référence d'un humain (Homo Sapiens) publié le 27/02/2009. hg 19 est un synonyme de GRCh37

### Q4
L'exome des patients a été séquencé à partir de sang périphérique. Puis le résultat de séquençage est analysé : les variants sont isolés et annotés en fonction de leur qualité. Puis les variants ont été comparés aux bases de données pour éliminer les variants déjà connus pour causer des déficiences intellectuelles. Puis des prévisions in silico de la pathogénicité des mutations sont réalisées. Les gènes candidats isolés sont ensuite séquencés par séquençage de Sanger

### Q5
Après avoir isolé FBXO11 comme gène candidat pour expliquer les déficiences intellectuels des deux sujets, un séquençage de Sanger est réalisé. C'est le gold standard : il permet de s'assurer que les mutations obsorvées lors du séquençage de l'exome entier existent réellement. Dans l'article, on suppose que les mutations qui causent le phénotype de déficience intellectuelle sont de novo. Il faut donc aussi séquencer les gènes FBXO11 des parents et confirmer la paternité et la maternité (don d'ovocytes) pour affirmer le statut de novo des mutations des enfants.

### Q6
Pour le patient 1 :
-variant d'épissage sans équivoque
Pour le patient 2 : 
- décalage de cadre avec apparition d'un codon stop prématuré en position 913
- toutes les autres variations ont été classés bénigne ou sans lien avec le phénotype du sujet

### Q7
FBXO11 est un bon candidat pour la déficience intellectuelle car :
-il est statistiquement associé à la schizophrénie lors de GWAS lorsqu'il est muté
-il est exprimé dans le système nerveux central (“Brain—Cerebellar Hemisphere” and “Brain—Cerebellum”)
-Les variants qui entrainent une perte de fonction du gène sont très rares (absent de nombreuses bases de données), lmais présent chez deux individus (patients 1 et 2) qui présentent un phénotype de déficience intellectuelle
-le gène est conservé à 100% dans le génome de cent vertébrés ce qui indique une importance fonctionnelle
-les trois individus étudiés dans l'articles qui présentent une mutation sur ce gène ont tous le même phénotype
