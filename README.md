# Responsive Email Boilerplate
Ce template est une base de travail lorsque l'on souhaite construire un modèle pour des emailings. Pour la réalisation d'un email, c'est à partir de cette base que je commence.

Essentiellement basé sur [Antwort](http://internations.github.io/antwort/), c'est un regroupement d'astuces, de pratiques glanées à travers de nombreux articles et ressources tels que [HTML Email Boilerplate](http://htmlemailboilerplate.com/), mais aussi bien sûr de mes propres expériences.

Difficile d'envoyer des emails non adaptés aux mobiles de nos jours au vu des taux d'ouverture sur ces appareils. Là aussi les bases sont posées avec un mix entre design fluide et adaptatif.

## Caractéristiques
* Adapté aux mobiles sur iOS et Android
* Fonctionne sur la majorité des clients web tel que Gmail, Outlook.com, Yahoo!, LaPoste.net, Orange, SFR et Voilà
* Fonctionne sur les logiciels Outlook (2000+)

## Comment ça marche ?
Voir le code source ! Un certain nombre d'éléments sont commentés, mais c'est en anglais car je commente toujours en anglais (commentaires qu'il est préférable d'enlever en production).

**Quelques précisions tout de même :**

J'ai fait le choix de ne pas utiliser de balises `<p>`, `<h1>`, `<h2>`, etc.  
Les balises de titres sont les plus risquées à utiliser car les clients mails ont parfois déjà des styles qu'ils leur appliquent. Je privilégie donc l'utilisation de `<div>` pour les titres.

La balise `<p>` est moins problématique à utiliser, mais je fais le choix de m'en passer lorsque cela est possible [depuis que Outlook.com ne supporte plus la propriété `margin`](https://litmus.com/blog/hotmail-and-outlook-com-drop-support-for-margin). A la place je mets un double retour à la ligne `<br /><br />` qui a l'avantage de proposer quasiment le même rendu peu importe le client, mais aussi de n'avoir à déclarer les propriétés de font qu'une seule fois sur le `<td>` plutôt que chaque `<p>`.

## Ressources
* [Guide du support CSS](http://www.campaignmonitor.com/css) et [guide du support des medias queries](http://www.campaignmonitor.com/guides/mobile/) chez Campaign Monitor
* [Les guides proposés par MailChimp](http://mailchimp.com/resources/)
* Les blogs de [Campaign Monitor](http://www.campaignmonitor.com/blog), [EmailOnAcid](http://www.emailonacid.com/blog) et [Litmus](https://litmus.com/blog/)
* [Les slides de la conférence d'HTeuMeuLeu sur l'intégration d'e-mails responsive lors de la Kiwi Party 2013](http://fr.slideshare.net/HTeuMeuLeu/lintgration-demails-responsive)
* Le tutoriel [Un e-mail en HTML responsive multi-clients](http://www.alsacreations.com/tuto/lire/1533-un-e-mail-en-html-responsive-multi-clients.html) sur Alsacreations
* [Top 10 des clients mails par Litmus](http://emailclientmarketshare.com/)
* [Conférence Paris Web 2014 de HTeuMeuLeu : "Comment sortir l'intégration d'e-mails de la préhistoire ?"](https://speakerdeck.com/hteumeuleu/comment-sortir-lintegration-de-mails-de-la-prehistoire)
* [Le blog dédié aux emails de HTeuMeuLeu](http://emails.hteumeuleu.fr)

## Changelog

### 0.3
* L'utilisation du hack pour Yahoo! Mail des media queries n'est désormais plus nécessaire
* Nettoyage du template pour retirer le code inutile

### 0.2
* Changement du doctype en rapport avec celui utilisé par la majorité des clients web
* Prise en compte des spécificités liées aux clients web Français

### 0.1
* Hello world!

### A venir...
Déclinaison de versions utilisables dans MailChimp et Campaign Monitor avec utilisation des langages qui leur sont propres.

## License
[MIT License](http://opensource.org/licenses/MIT)
