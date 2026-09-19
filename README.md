# Recoding : aux sources du dessin génératif

## Présentation
_« Recoding : aux sources du dessin génératif »_ est un atelier de programmation créative consacré à l'exploration du dessin génératif dans la continuité des expérimentations des pionniers de l'art algorithmique des années 1960 et 1970.

À partir d'une sélection de programmes issus de [recodeproject.com](https://recodeproject.com/), les participants analyseront les systèmes graphiques imaginés par d'autres artistes avant de les transformer ou de les détourner. L'objectif n'est pas de partir d'une page blanche, mais de considérer le code comme un matériau de création : lire, comprendre, modifier et faire évoluer un programme existant.

En jouant sur les paramètres, les règles ou la structure même des algorithmes, chacun développera sa propre interprétation, entre hommage, variation et expérimentation.

Les créations réalisées pendant l'atelier seront ensuite dessinées à l'aide de plotters faisant le lien entre programmation, dessin algorithmique et matérialité du trait.

<img src="img/260918_Atelier_Recoding_ESAD_Orléans_01_w2000.jpeg" />

## Collection de sketches
https://editor.p5js.org/v3ga/collections/N_0k_UUxE

#### Template
https://editor.p5js.org/v3ga/sketches/C9dFixyWn

## Déroulé
### Mardi 15 Septembre
- Présentation Julien / parcours.
- Présentation de l'atelier.
- Présentation et installation des outils :
    - création d'un compte sur [editor.p5js.org](https://editor.p5js.org/)
    - installation de [Inkscape](https://inkscape.fr/)
    - installation [des outils AxiDraw](https://wiki.evilmadscientist.com/Axidraw_Software_Installation)
- Découverte des concepts de base de la programmation : 
    - Recoding pas à pas de [« Schotter » de Georg Nees](https://collections.vam.ac.uk/item/O221321/schotter-print-nees-georg/) (1968-1970), briques programmation.
    - Expérimentation autour de cet algorithme de dessin.
- Découverte d'algorithmes classiques utilisés dans le dessin algorithmique : https://drawingbots.com/algorithms/
- Test d'impression à plusieurs sur une machine (AxiDraw v3) ou iDraw.

### Mercredi 16 & Jeudi 17 Septembre
- Découverte d'algorithmes interactions temps réel via [ml5.js](https://ml5js.org/)
- Utilisation de prompts en s'appuyant sur les connaissances pour l'aide à l'écriture de programme, être capable de comprendre et d'orienter le code généré.  
- Créations et impressions de dessin.

### Vendredi 18 Septembre
- Exposition des productions à l'école, prévoir une courte vidéo pour communiquer sur l'évènement.  

## Méthodes de travail
Pour faciliter l'impression sur traceur, nous travaillerons à partir d'un programme (ou _sketch_) template : https://editor.p5js.org/v3ga/sketches/C9dFixyWn
Ce template intègre directement un export au format [SVG](https://developer.mozilla.org/fr/docs/Web/SVG) du dessin produit sur l'écran, avec une interface minimale.
Plusieurs façons de créer :
1. **La plus « ardue »** : partir du template et écrire soi-même le code.
2. **La plus « naturelle »** : partir d'un programme existant sur [recodeproject.com](https://recodeproject.com/) et modifier le code, en essayant de comprendre comment tel ou tel paramètre influe sur le dessin final, comment vous pouvez modifier les commandes de dessin pour s'approprier l'écriture de code. Voir comment l'importer dans [le template](https://editor.p5js.org/v3ga/sketches/C9dFixyWn).
3. **La plus « facile »** et plutôt dans l'air du temps : utiliser un chatbot (Claude, Copilot, ChatGPT entre autres) en lui donnant le code [du template](https://editor.p5js.org/v3ga/sketches/C9dFixyWn) impérativement et lui indiquant précisément la composition graphique, en utilisant des algorithmes déjà connus (voir par exemple le site [drawingbots.com/algorithms](https://drawingbots.com/algorithms/))
<br />👉 **« Contrat »** pour démarrer une conversation : https://github.com/v3ga/Workshop_ESAD_Orleans_Recoding_2026/blob/main/primer-recoding-chatbot.md

## Rendu
Dans le dossier / drive https://drive.google.com/drive/folders/1ym-fd3AQx3gC_75QnPE4HP94GriLb9-C?usp=sharing : 
- créer un dossier avec votre nom / prénom
- créer un dossier avec le nom du sketch / œuvre
- télécharger les fichiers (index.html / sketch.js / style.css) dans ce dossier
- télécharger une courte description du procédé et de l'œuvre produire au format .txt (text brut, pas de mise en page)
- télécharger :
    - le fichier .svg et .png du dessin
    - une photo du dessin

## Ressources 
- [recodeproject.com](https://recodeproject.com/)<br />_The ReCode Project is a community-driven effort to preserve computer art by translating it into a modern programming language (p5.js). Every translated work will be available to the public to learn from, share, and build on._
- [drawingbots.com/algorithms](https://drawingbots.com/algorithms/)<br />_A visual catalog of the algorithms behind pen-plotter art_.
- [bookofshapes.com](https://bookofshapes.com/)<br />_A collection of minimal, generative and customizable SVG-patterns_.
- [Recoding : aux sources du dessin génératif / Stereolux / 2026](https://github.com/v3ga/Workshop_Recoding_Stereolux_2026)<br />Atelier à Stereolux (Nantes) sur le même thème.
- [p5.plotSvg](https://github.com/golanlevin/p5.plotSvg) <br />_p5.js library for exporting SVG files tailored for pen plotting._
- [Computer art on V&A museum](https://collections.vam.ac.uk/search/?id_category=THES49037&page=1&page_size=15)


<img src="img/260918_Atelier_Recoding_ESAD_Orléans_04_w1000.jpeg" width="400" /><img src="img/260918_Atelier_Recoding_ESAD_Orléans_03_w1000.jpeg" width="400px"/><img src="img/260918_Atelier_Recoding_ESAD_Orléans_05_w1000.jpeg" width="400px"/>
