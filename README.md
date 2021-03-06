# livre-blanc-seo
Ouvert à toutes les contributions. Partager ce qu'il faut savoir pour bien référencer un site.

:information_source: Pour contribuer, vous pouvez soit écrire du contenu, soit :
- donner votre avis ;
- râler ;
- applaudir ;
- remonter des erreurs ;
- parler de ce projet (ou écrire sur ce projet) ;
- corriger des fautes qu'elles soient de français ou techniques, grossières ou non ;
- sûrement beaucoup d'autres choses.
Quoi que vous fassiez, ça se passe par ici : https://github.com/MathRobin/livre-blanc-seo/issues

PS : quoi qu'il en soit, d'avance : merci ! :thumbsup:

Fait avec :heart: pour toutes et tous

## Table des matières

* [URLs](#urls)
   * [Domaine et localisation](#domaine-et-localisation)
   * [Sous domaine](#sous-domaine)
   * [La requête](#la-requête)
      * [Usage du / terminal](#usage-du--terminal)
   * [Protocole HTTPS](#protocole-https)
   * [Protocole HTTP 2](#protocole-http-2)
* [Code](#code)
   * [Contenu](#contenu)
      * [Liens internes et externes](#liens-internes-et-externes)
      * [Ratio HTML / Texte](#ratio-html--texte)
      * [Hierarchie de la page](#hierarchie-de-la-page)
   * [Headers](#headers)
      * [CSP](#csp)
      * [STS](#sts)
   * [Meta tags](#meta-tags)
      * [Canonical](#canonical)
      * [Description](#description)
      * [Author](#author)
      * [OpenGraph](#opengraph)
      * [Twitter Cards](#twitter-cards)
      * [Alternate Lang](#alternate-lang)
      * [Publisher](#publisher)
   * [JavaScript](#javascript)
   * [Ligne de flottaison](#ligne-de-flottaison)
   * [Sitemaps](#sitemaps)
   * [Schema](#schema)
   * [AMP](#amp)
   * [FIA](#fia)
   * [Favicons](#favicons)
      * [Apple Touch Icon](#apple-touch-icon)
      * [Shortcut icon](#shortcut-icon)
      * [Icon](#icon)
* [Outils](#outils)
   * [Google](#google)
      * [Google Search Console](#google-search-console)
      * [Google Analytics](#google-analytics)
      * [Embed API](#embed-api)
* [Algorithmes Google](#algorithmes-google)
    * [PageRank](#pagerank)
    * [Pénalités](#pénalités)
    * [Google Panda](#google-panda)
    * [Google Penguin](#google-penguin)
    * [Page Layout](#page-layout)
    * [PayDay Loan](#payday-loan)
   * [Bing](#bing)
      * [Bing Webmaster Tools](#bing-webmaster-tools)
   * [Mozilla](#mozilla)
      * [Mozilla Observatory](#mozilla-observatory)
   * [Indépendants](#indépendants)
* [Le monde extérieur](#le-monde-extérieur)
   * [Backlinks](#backlinks)
      * [Annauaires](#annauaires)
   * [Réseaux sociaux](#réseaux-sociaux)
      * [Page facebook](#page-facebook)
      * [Compte Twitter](#compte-twitter)
      * [Instagram](#instagram)
      * [Youtube](#youtube)

## URLs
### Domaine et localisation
Ici se situeront les conseils concernant le domaine à utiliser.

Par exemple qu'il est préférable d'utiliser un .fr pour un site qui vise le marché français et non un .com, plutôt destiné aux USA.

### Sous domaine

Ce qu'il faut savoir sur avec ou sans www, les autres sous-domaines.

Par défaut Google (qui des autres moteurs ?), considère que les domaines www.[unSite.uneTld] et [unSite.uneTld] doivent être des sites différents. Si vous n'avez pas prévu d'utiliser les deux sous-domaines en tant que sites indépendants, il est préférable d'en choisir un comme référence et de rediriger toutes URL de l'autre via 301 vers le premier.

### La requête

Comment faire une URL proprement pour tout ce qui suit le domaine

#### Usage du / terminal

### Protocole HTTPS

Quid de l'usage de HTTPS face à HTTP

### Protocole HTTP 2

Quid de l'usage de HTTP 2

## Code

Ce qu'il faut savoir côté code

### Contenu
#### Hierarchie de la page
#### Liens internes et externes
#### Ratio HTML / Texte

### Headers

Dans les en-têtes de vos pages, un certain nombre d'infos doivent être présentes. Surtout our une question de sécurité.

#### CSP

Permet de réduire les risques d'attaques XSS. N'est pas un critère SEO chez Google mais on peut parier que des moteurs se préoccupant de la confidentialité soient intéressés par la présence de cette en-tête.

https://content-security-policy.com/

#### STS

### Meta tags
#### Alternate Lang

#### Author

#### Canonical

#### Meta-description

La meta-description est un élément clé pour attirer vos visiteurs. En soit, elle ne compte pas pour le référencement. Cette description s'affiche dans les résultats Google. Au delà des 160 caractères, le reste ne s'affichera pas et est donc inutile. Autant ne pas alourdir votre page avec du contenu en trop.

Pour chaque page, elle doit être unique et être comprise entre 150 et 160 caractères.

Source : https://moz.com/learn/seo/meta-description

Vidéo de Matt Cutts [_"Is it necessary for every page to have a meta description?"_](https://www.youtube.com/watch?v=W4gr88oHb-k)

#### OpenGraph

#### Publisher

#### Twitter Cards

### JavaScript

Ce qui est compris ou non.

### Ligne de flottaison

### Sitemaps

Usage d'un sitemap pour les pages indexables
Usage d'un sitemap alternatif provisoire pour les redirections 301 et 302

### Schema
https://schema.org/

### AMP
https://www.ampproject.org/

### FIA
https://instantarticles.fb.com/

### Favicons
#### Apple Touch Icon
#### Shortcut icon
#### Icon

## Outils
### Google
#### Google Search Console
https://www.google.com/webmasters/tools/home

#### Google Analytics
https://www.google.fr/intl/fr/analytics/

#### Embed API
https://ga-dev-tools.appspot.com/embed-api/basic-dashboard/

####  Algorithmes Google
Google à mis en place de nombreux algorithmes pour améliorer la qualité de ses résultats : amélioration des contenu, lutte contre le spam, gestion de la publicité, performances du site, etc. 

##### PageRank
Le PageRank est l'algorithme qui permet à Google de connaitre le nombre de liens qui pointent vers une page donnée. Plus il existe de liens qui pointent vers cette page et plus la page est populaire. En gros, on peut dire que le PageRank indique la probabilité de tomber sur une page donnée en suivant des liens. Le nombre de liens qui pointent vers une page est tempéré par la qualité et le classement des liens qui pointent vers elle.  

##### Pénalités
A côté du PageRank, Google a mis en place une série de pénalités pour éviter que des pages de qualité douteuse ne trustent les premiers résultats. Cf. http://www.webrankinfo.com/dossiers/conseils/algos-google 

###### Google Panda
https://webmasters.googleblog.com/2011/05/more-guidance-on-building-high-quality.html

###### Google Penguin
https://webmasters.googleblog.com/2016/09/penguin-is-now-part-of-our-core.html

###### Page Layout
Publicité envahissante
https://webmasters.googleblog.com/2012/01/page-layout-algorithm-improvement.html

###### PayDay Loan
Antispam
http://searchengineland.com/google-pay-day-loan-algorithm-google-search-algorithm-update-to-target-spammy-queries-162941


### Bing
#### Bing Webmaster Tools
http://www.bing.com/toolbox/webmaster

### Mozilla
#### Mozilla Observatory
https://observatory.mozilla.org/

### Indépendants
- onpage.org
- woorank
- https://www.seobility.net/en/

## Le monde extérieur
### Backlinks
#### Annuaires
### Réseaux sociaux
#### Page facebook
#### Compte Twitter
#### Instagram
#### Youtube
