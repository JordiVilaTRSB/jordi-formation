# jPlatformSocle

<p>
  <a href="https://travis-ci.org/organizations/departement-loire-atlantique">
    <img src="https://travis-ci.org/departement-loire-atlantique/jPlatformSocle.svg?branch=master" />
  </a>
  <a href="https://sonarcloud.io/organizations/departement-loire-atlantique">
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=ncloc" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=bugs" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=code_smells" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=coverage" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=duplicated_lines_density" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=sqale_rating" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=alert_status" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=reliability_rating" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=security_rating" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=sqale_index" />
    <img src="https://sonarcloud.io/api/project_badges/measure?project=departement-loire-atlantique_jPlatformSocle&metric=vulnerabilities" />
    </a>
</p>

<h1>Je suis une fougère !</h1>

WOLOLOOOOO

Ce module regroupe tous les types de contenu « socle éditorial » pour les sites JCMS du Département ainsi que les gabarits d'affichage associés.

Socle des contenus éditorial :

-	Accueil de rubrique (WelcomSection)
-	Article de rubrique (CollectivityArticle)
-	Article géolocalisé (ArticleGeolocalie)
-	Fiche lieux (Place)
- Fiche aide (Help)
-	Actualité (News)
-	Dossier d'actualités (Directory)
-	Carousel (Carousel)
-	Élément carrousel (CarouselElement)
-	Alerte (AlertCG)
-	Résultat de recherche (ResultatDeRecherche)
-	Chapitre de vidéo YouTube (Chapitre)

Un nouveau type de contenu "**VideoChapitree**" a été créée pour faciliter la saisie et fonctionner avec l'insertion unifiée.

<h2>Et les ornythorinques c'est trop la classe</h2>

**LE GABARIT EST A REVOIR : js inclus dans le corps de la JSP + bug si plusieurs vidéos ajoutées dans un article**

<b>Ca vous en bouche un coin, hein ?</b>

Socle des contenus représentant le découpage territorial (synchronisés entre tous les sites depuis le site institutionnel) :

-	Canton (Canton)
-	Délégation (Delegation)
-	Commune (City)
-	Commune hors département (CommuneHorsDepartement)
-	Élu (ElectedMember)

<a href="google.se">Le meilleur moteur de recherche au monde !</a>

# Personnalisation de l'éditeur wysiwyg et des styles wysiwyg

<h2>All your git belong to us</h2>

Fichiers :

=> Ajout du fichier configuration-charteconfig.conf pour surcharger les options de la configuration par defaut du wysiwyg.

Permet notamment de personnaliser la liste des types de blocs à appliquer au texte sélectionné (**paragraphe**, **titre 2-6**, **encadré**, **bouton**...)

=> Ajout du fichier configuration-styles.conf pour ajouter une liste de styles "**Formats**" à l'éditeur wysiwyg.
ces (fr.cg44.plugin.socle.interfaces) ?
