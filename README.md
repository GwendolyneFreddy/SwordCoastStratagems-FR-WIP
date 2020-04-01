# SwordCoastStratagems-FR-WIP

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

POINTS NOTABLES :

Penser à supprimer iwdspells.tra dans stratagems\stratagems\lang\french. // Je m'en occupe, c'est juste un pense-bête.

fiend_summoning.tra et spell.tra vérifier Convocation d'un Fiélon -> "Zone d'effet : Aucune" devrait être "Zone d'effet : spéciale" en toute logique.

SCS intègre des sorts (issu de icewind dale), de convocation d'élémentaire(6) et de convocation d'élémentaire "mineur"(5), comparé à IWDification qui ne possède que des convocation d'élémentaire (5). Notez bien la différence de nom et de (niveau).

Le sort Tempête acide possède des différences de dégats entre SCS et IWDification. 

Le sort Projection d'épines possède des différences de dégats entre SCS et IWDification.

Le sort Projectiles de force de Mordenkainen possède des différences de nombre de projectiles entre SCS et IWDification.

Des sorts portent des noms différents Égide divine = Bouclier de Lathandre entre SCS et IWDification.

Des sorts portent des noms différents Création de squelette de garde = Convocation de monstres VII entre SCS et IWDification.

Coquille antimagique, sort d'IWD est cité dans speel.tra @40014. Mais le sort lui-même n'est pas présent.

Gros doute sur le nom des capacités et leurs ordres d'apparition des flagelleurs mentaux dans difficulty.tra (Coup spirituel, Trajet planaire et Détournement psionique, trouvé dans psionic.tra), à vérifier.

Gros doute sur le nom des créatures vampires dans le composant "Bodhi" de difficulty.tra (full-strength et adult).

Gros doute sur le pédoncule de mort (@233) et de désintégration (@235) dans difficulty.tra, voir beholder.tra.

Vérifier traduction @224 difficulty.tra "et non des copies génériques de démons".

Impossible de convertir l'encodage de undead.tra en ANSI. C'est pas très grave puisque aucun caractères spéciaux n'est présent.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

CORRECTED TYPOS ENGLISH TRA FILES : 

durlag.tra @22410 space at the beginning

sendai.tra @701 deleted "Katana (\n)"

difficulty.tra @191 space between other  undead

difficulty.tra @263 space between and  use

difficulty.tra @403 "of its spells increase.." -> "of its spells increase."

difficulty.tra @1073 "d'Arnise" -> "de'Arnise"

difficulty.tra @1110 space between \n  INSANE / lack of space between .\n

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

CHANGEMENTS ET CORRECTIONS AUX PRECEDENTES TRADUCTIONS FRANCAISES :

beholder.tra @100 Telekinesie -> Télékinesie

fiend.tra @100 Telekinesie -> Télékinesie

fiend.tra @3212 Donner aux celestes legerement plus d'endurance -> Imposition des mains // "Lay on Hands" en anglais

mage.tra @1202 bénéficiions -> bénéficions

sarevok.tra @22001 ajout version féminine

sarevok.tra @22002 ajout version féminine

sarevok.tra @22006 ajout version féminine

sarevok.tra @22008 ajout version féminine

setup.tra @63 Demons ameliores -> Demons et celestes ameliores

setup.tra @188 suppression de "(inspiree du mod Tactics)" //pas ou plus indiqué en anglais

setup.tra @3317 suppression de "(adapte du Quest Pack)" //pas ou plus indiqué en anglais

spell.tra @??? beaucoup trop d'espaces, de retours à la ligne, de tour -> round, jeteur -> lanceur, /n -> par niveau, ect... pour garder le compte. // Une relecture COMPLÈTE DES SORTS s'impose.

spell.tra @14100 " ([ÉE]vocation)" -> " (Évocation)" // [ÉE] ?!

spell.tra @14101 " (Invocation */ *[ÉE]vocation)" -> " (Invocation/Évocation)" // [ÉE] ?!

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

A RELIRE :

Abazigal.tra : @3200, @3201, @3202

beholder.tra : @101 à @115

difficulty.tra : tout

doppelganger.tra : tout

durlag.tra : Rien, juste un typo corrigé (espace à @22410)

dw_iwdspells_arcane.tra : tout

dw_iwdspells_divine.tra : tout

fiend.tra : @101, @1027, @3212, @3213, @40000 à @40005, @40010 à @40012

fiend_summoning.tra : tout

firegiant.tra : @3000, @3001

gameplay.tra : @609 à @751, @1331, @1341, @22300

initial.tra : @50074, @50075

leveller.tra : tout

lib.tra : tout // attention toutes les lignes sont les mêmes que dans difficulty.tra

mage.tra : @304, @1209 à @1214

priest.tra : Rien, juste un commentaire

sarevok.tra : @22001 féminin, @22002 féminin, @22006 féminin, @22008 féminin

setup.tra : @8, @27, @64, @155, @189, @190, @226 à @233, @3316, @3393, @3400, @16056, @20013, @20094, @20095, @24119 à @24124, @50000 à @50009

shapeshift.tra : @13144 -> ligne 80, @13146 -> ligne 106 et 107

shared.tra : tout sauf @100200, @100201

spell.tra : @100, @300 à @1102, @5002, @32000 et tout ce qu'il y a après //Une relecture COMPLÈTE DES SORTS s'impose. Il y a beaucoup de changements, notamment aux niveaux des précédentes traductions DES SORTS !

undead.tra : tout

vampire.tra : @14506
