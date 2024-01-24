---
title: Go Hugo - Wordpress vs. Static Site Generators
description: Static Site Generators sind beliebter denn je, doch können Sie mit etablierten Systemen wie Wordpress und Co. mithalten? Wir haben für Sie den Vergleich gemacht.
image: /content/blog/hugo-blog-post.jpg
tags: [Webentwicklung, SEO]
published: 2023-04-11T06:34:52.350Z
modified: 2024-01-24T11:11:42.350Z
---

# Go Hugo - Wordpress vs. Static Site Generators
Wenn es darum geht eine Webseite zu entwickeln, stellt sich schnell die Frage auf welcher Grundlage Sie dies tun möchten. Je nachdem welches technisches Know-How sie besitzen und welche Anforderungen Sie an Ihre zukünftige Webseite haben, kann die Antwort auf diese Frage ganz unterschiedlich aussehen. Wordpress und Co. machen es Ihnen einfach eine Webseite zu betreiben aber gibt es Alternativen? In diesem Blog Eintrag möchten wir Ihnen sogenannte Static Site Generators vorstellen, welche es Ihnen ebenfalls leicht machen eine Webseite zu betreiben, dabei jedoch einen ganz anderen Ansatz wählen.

## Wordpress: CMS und noch viel mehr
Wordpress und Typo3 sind Content Management Systeme, welche es Ihnen ermöglichen, ohne Programmierkenntnisse schnell und einfach eine Webseite zu betreiben. Dabei ist Wordpress so erfolgreich, dass es heute für [über 40% aller im Internet erreichbaren Webseiten](https://colorlib.com/wp/wordpress-statistics/) genutzt wird - über 810 Millionen Webseiten nutzen Wordpress. Die Relevanz ist damit unumstritten und das System funktioniert aber ist Wordpress immer die beste Wahl?

Wordpress und Co. sind modular aufgebaut, was es ermöglicht fertige **Plugins und Themes aus der Community** einzusetzen, um schnell und einfach Funktionen wie ein Cookie Banner oder Kontaktformulare in die Webseite einzubauen ohne diese selbst entwickeln zu müssen. Themes ermöglichen es vorgefertigte Designs für Ihre Webseite zu benutzen, welche vollständig responsiv sind und schön aussehen. Der Inhalt der Webseite, die Plugins und Themes werden über ein Admin-Dashboard verwaltet, welches einfach über den Browser aufgerufen werden kann.

Um diese Funktionen zu ermöglichen arbeitet die Wordpress Webseite im Hintergrund mit einer Datenbank, in welcher sämtliche Inhalte und Konfigurationen für Plugins und Themes gespeichert werden. Wenn ein Besucher die Webseite aufruft, wird diese mit den in der Datenbank gespeicherten Informationen dynamisch zusammengebaut.

### Vor- und Nachteile Wordpress
Der größte Vorteil von Wordpress ist die **einfache Bedienung zur Konfiguration der Webseite**. Man kann ganz ohne Vorkenntnisse im Umgang mit HTML, CSS und JavaScript über das Admin-Dashboard eine vollumfängliche Webseite zusammenbauen und diese mit Hilfe von Plugins und Themes modular erweitern. So kann man ohne Probleme innerhalb kürzester Zeit bspw. einen Online-Shop oder eine Webseite für das eigene Unternehmen erstellen.

Diese einfache Bedienung bringt aber einen Nachteil mit sich: Man ist sehr an das vorgegebene System von Wordpress gebunden. So sind selbst kleine Abweichungen von einem vorgegeben Theme oder Plugin meistens nur schwer möglich. Wer also im Umgang mit HTML, CSS und JavaScript versiert ist und gerne seine individuellen Vorstellungen selbst umsetzen möchte, bekommt hier Steine in den Weg gelegt.

Zudem ist die komplexe Struktur mit Datenbank und Backend für eine einfache statische Webseite wie ein Blog oder eine Unternehmenswebseite meist gar nicht notwendig. Diese Struktur macht die Webseite eher träge und langsam, ist jedoch für die einfache Handhabung über das Admin-Dashboard notwendig. Außerdem ist das Admin-Dashboard öffentlich im Internet zugänglich, wodruch es ein [attraktives Angriffsziel für Hacker](https://www.cminds.com/blog/wordpress/7-types-wordpress-attacks/) ist.

## Was ist ein Static Site Generator?
Static Site Generators (SSGs) sind eine neuere Art von Website-Bauwerkzeugen, die in den letzten Jahren an Beliebtheit gewonnen haben. Im Gegensatz zu WordPress, welches dynamisch Webseiten zusammenbaut, erstellen SSGs statische HTML-Dateien, die Besuchern angezeigt werden. SSGs sind daher ausschließlich für technisch versierte Benutzer geeignet, welche sich mit HTML, CSS und JavaScript bereits auskennen.

Die Idee hinter Static Site Generators ist, dass aus statischen Textdateien - meistens [Markdown Dateien](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - am Ende statische HTML Dateien generiert werden. Man kann somit den Inhalt der Webseite übersichtlich in Text- bzw. Markdown-Dateien verwalten und der SSG produziert aus diesen dann die komplexen und meist unübersichtlichen HTML Dateien, welche vom Webserver für die Besucher der Webseite bereitgestellt werden. Ein SGG braucht keine Datenbank, da alle in der Webseite verbauten Informationen aus diesen Textdateien stammen.

Die statischen HTML Dateien, welche durch den SSG generiert werden, können anschließend in einem Webspace hochgeladen werden. Anfragen an den Webserver hinter dem Webspace, werden dann mit genau diesen HTML Dateien direkt beantwortet. Die Webseite muss also nicht mehr dynamisch zusammengebaut werden wie bei Wordpress.

### Vor- und Nachteile SSG
Vorteil und Nachteil zu gleich ist die Einfachheit dieser SSGs. Da sie nur grundlegenste Strukturen festlegen, hat man alle erdenklichen Möglichkeiten aber man muss eben auch vieles selber machen. Es gibt ähnlich zu Wordpress auch [fertige Themes](https://themes.gohugo.io/) aber gerade Plugins für Formulare oder Webshops sind nicht so einfach implementierbar wie man es von Systemen wie Wordpress kennt.

Ein großer Vorteil gegenüber Wordpress ist die Performance der Webseite, dessen Ausgangslage durch die statischen Dateien kaum besser sein könnte. Wenn die Webseite nicht erst dynamisch zusammengebaut werden muss sondern auf Abruf bereit steht, ist sie schnellstmöglich im Browser des Besuchers angekommen, sofern keine riesigen Inhalte wie Bilder o.ä. nachgeladen werden müssen.

Auch was die Sicherheit vor potenziellen Angreifern angeht, könnte es mit den statischen Dateien nicht besser aussehen. Dadurch dass es kein Admin-Dashboard, keine Datenbank und kein Backend gibt, gibt es auch nichts was ein Hacker angreifen könnte. Somit ist die Webseite absolut sicher vor jeglichen Angriffen.

### Etablierte Lösungen
In den letzten Jahren sind einige Static Site Generators auf dem Markt erschienen. Alle mit ihren unterschiedlichen Ansätzen. Eine gute Übersicht über die bekanntesten SSGs finden Sie auf [Jamstack](https://jamstack.org/generators/).

#### Hugo
Bei der Wahl für einen SSG für unsere Webseite ist die Entscheidung auf [Hugo](https://gohugo.io/) gefallen. Hugo ist weit verbreitet, simpel und setzt auf die Programmiersprache Go, welche sehr schnell ist und ebenfalls zur Zeit große Beliebheit gewonnen hat.

Ohne großes Schnick Schnack bietet Hugo alles was man für eine simple oder auch eine komplexere statische Webseite benötigt. Wie Hugo im Detail funktioniert, lässt sich wunderbar in der [offiziellen und sehr ausführlichen Dokumentation](https://gohugo.io/documentation/) nachlesen. Egal ob Multi Language Support, Menüs, Layouts oder Assets wie Bilder oder SCSS Dateien - Hugo bietet für fast alle technischen Herausforderungen rund um die statische Webseite eine Lösung.

#### Next.js
Wer bereits Erfahrung im Umgang mit [React](https://react.dev/) hat, ist mit [Next.js](https://nextjs.org/) gut beraten. Das React Framework von Meta (ehemals Facebook) ist seit Jahren eines der am weitesten verbreiteten JavaScript Frameworks zum erstellen von dynamischen Webapplikationen. Das Next.js Framework bietet ihnen nun die Möglichkeit, die Vorzüge von React auch für Ihre statische Webseite zu nutzen.

Das macht Next.js zwar komplexer als Hugo, bietet dafür aber diverse Möglichkeiten gerade in Bezug auf client-seitige dynamische Funktionen. Dadurch haben Sie die Möglichkeit Ihre statische Webseite stellenweise wie eine Webanwendung zu entwickeln und bspw. per AJAX Call aus dem Browser auf externe APIs einfach zuzugreifen.

## Netlify: Hosting und mehr
Wenn Sie einen Static Site Generator benutzen, müssen Sie sich nun noch die Frage stellen, wie und wo Sie diese statischen Dateien dem Internet bereitstellen. Hier haben Sie im Grunde alle erdenkbaren Möglichkeiten, egal ob ein einfacher Webspace bei Strato und Co. oder ein eigener Server, die statischen Dateien können von überall bereitgestellt werden. Alles was dafür benötigt wird ist ein Webserver.

[Netlify](https://www.netlify.com/) ist ein Anbieter der in den letzten Jahren sehr große Beliebheit erlangt hat. Er bietet diverse Services rund um das Web und eben auch die Möglichkeit die statischen Dateien zu hosten. Dabei bietet Netlify weit mehr als nur einen einfachen Workspace zum Bereitstellen Ihrer statischen HTML Dateien.

Wenn Sie einen SSG nutzen, werden sie die dafür erstellten Dateien wahrscheinlich in einem Git Repository bspw. auf [GitHub](https://github.com/) hinterlegten. Dieses Git Repository kann Netlify als Verwaltungsgrundlage Ihrer statischen Webseite benutzen. Sobald eine neue Version in dieses Repository gepusht wird, wird automatisch ein Build-Prozess bei Netlify angestoßen, welcher die neue Version Ihrer Webseite im Internet bereitstellt. Dadurch müssen Sie nicht händisch die statischen HTML-Dateien generieren und anschließend in einem Webspace hochladen.

### Netlify CMS (Decap)
**Update:** Netlify CMS wurde inzwischen in [Decap](https://decapcms.org/) umbenannt.

Über das Hosting hinaus bietet Netlify eine [Headless CMS Funktion](https://jamstack.org/headless-cms/netlify-cms/), welches es Ihnen ermöglicht, ähnlich wie bei Wordpress, die Inhalte Ihrer Webseite schnell und einfach über ein Dashboard im Browser anzupassen. Änderungen aus diesem CMS werden dann in das gerade beschriebene Git Repository gepusht, wodurch wiederum der Build-Prozess angestoßen und die neue Version der Webseite veröffentlicht wird.

Das CMS können Sie dabei selbst mit Hilfe einer config.yaml Datei konfigurieren. Wie das Netlify CMS im Detail funktioniert, können Sie [hier](https://decapcms.org/docs/intro/) nachlesen.

### Formulare
Formulare wie z.B. ein Kontaktformular über welches Besucher Ihnen Nachrichten senden können, benötigen immer zwangsläufig ein Backend. Doch wie kann das Umgesetzt werden, wenn mit der statischen Webseiten gar kein Backend vorhanden ist?

Für genau diesen Zweck bietet Netflify die [Forms](https://www.netlify.com/products/forms/) Funktion. Hier wird uns ein Endpoint gestellt, an welche wir die Daten aus einem HTML-Formular schicken können. Über das Netlfiy Dashboard kann dann festgelegt werden, wie und wer über das gerade abgeschickte Formular benachrichtigt werden soll. Beispielsweise kann das ausgefüllte Formular dann per Email an eine bestimmte Email-Adresse verschickt werden, wie man es auch aus Wordpress-Formularen kennt.