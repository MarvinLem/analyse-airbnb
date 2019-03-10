# Analyse de Site - Airbnb

## Scenario

1. Contactez le site

2. Reserver un hotel

## Anysurfer

1. Navigation
 	1. La totalité du site est navigable au clavier. X
 		On ne peut pas voir l'outline sur les images. 

 	2. Les intitulés des liens sont significatifs dans leur contexte. V

2. Contenu
 	1. Le code source est conforme à la spécification du language. X
 		Certains éléments de type block dans éléments de type inline. Il manque des attributs for sur les labels. Balises P dans balises de titre. Code CSS incorrect "text-transform: undifined". !important utilisé trop souvent.

 	2. Texte
 		1. Chaque page possède un titre significatif. V
 		2. Les pages sont structurées par la sémantique. X
 			Il manque la présence des attributs aria-level et l'ordre de la sémantique H1, H2 n'est pas toujours correcte. Certains parties du site devraient être par des balises UL ou OL mais ne le sont pas. 
 		3. La langue principale de chaque page est indiquée. V

 	3. Images
 		1. Chaque image a un attribut alt. V
 		2. Les images complexes sont décrites par un texte. V
 		3. Les images d'arrière-plan qui contiennent de l'information ont une variante accessible. V

 	4. Tableaux de données - Il y en a pas. /

 	5. Video et son - Il y en a pas. /

3. Mise en forme
	1. Texte
		1. Les liens sont facilement identifiables comme tels. X
			La plupart des liens sont identifiables mais certains pourait avoir besoin d'un mouse hover. 
		2. Les espaces et autres caractères ne sont pas utilisés pour produire des effets visuels. V

	2. Mise en page
		1. Le contenu de la page suit un ordre logique. V
		2. Chaque cadre possède un nom et un titre significatifs. X
			Les Iframes ne possedent pas d'attributs name et title. 

	3. Mouvement
		1. Les textes et les images ne clignotent pas plus de 3 fois par seconde. V
		2. Les animations peuvent être arrêtées. V

	4. Couleur et autres informations visuelle.
		1. Le contenu est compréhensible pour quelqu'un qui ne peut distinguer les couleurs. V

4. Interactivité
	1. Formulaires
		1. Les labels et éléments des formulaires sont intimement liés. X
			Attributs For incorrect sur les labels. 

		2. Les champs sans label sont décrits par un tooltip. V

		3. L'étiquette des champs de saisie de date indique le format requis. V

		4. Les champs de formulaires liés sont regroupés par un fieldset. X 
			Fieldset non présents et remplacés par des balises de titrate 

		5. Les regroupements d'éléments dans une liste déroulante se font avec optgroup. /

		6. Les champs obligatoires sont annoncés dans leur label. X
			Les champs obligatoires ne sont pas toujours annoncés.

		7. Chaque formulaire a un bouton d'envoi visible. X
			Pas de bouton pour le champ de recherche.

		8. Lors de la validation, les erreurs sont indiquées et expliquées par du texte. V

	2. Contraintes de temps V

## GTMetrix

## Audits

1. Perfomance: 22% V
(Il faudra regarder pourquoi)

2. Accesibility: 98% V

3. Best Practices: 93% V

4. SEO: 82% V

## Problèmes Divers

1. On ne peut pas se déconnecter

2. Il y a des balises DIVS dans des balises A ou des balises BUTTON, P dans des balises H?

3. Certains liens ne ressemblent pas toujours à des liens.

4. Width du site trop grand sur mobile.

5. La structure est remplie de DIV mais bon c'est du réact.

## Tests utilisateurs

## Synthese des problemes rencontrés

## Refonte du site

Rajouter de l'outline quand on utilise le clavier pour visiter le site.

Rajouter un effet de zoom et d'assombrisement sur les liens.
