
# Open Source Initiative

> webexcess GmbH veröffentlicht einen Grossteil der in den letzten Jahren bei dotpulse entwickelten Basis-Quellcodes und Erweiterungen für die Website-Entwicklung mit Neos.


_Sorry, currently this text is only available in German. Head over to the [Packages](#headingPackages), they should be more or less self explaining._


## Wie kommt es?

Die ursprünglichen dotpulse AG Entwickler haben sich Anfang 2017 mit der Firma webexcess GmbH selbstständig gemacht, unterstreichen somit ihren klaren Fokus auf Neos- und Flow-Projekte und ermöglichen dotpulse die Technologie unabhängige Beratung.

Wir haben nun die Möglichkeit erhalten, die erarbeiteten Basis-Quellcodes zu übernehmen und nutzen diese Chance, um manche der Packages gleich öffentlich verfügbar zu machen.


## Wie kann ich diese nutzen?

Die Packages wurden in und für die generelle Architektur von dotpulse Web-Projekten entwickelt, manchmal auch mit dem Ansatz “ein konfigurierbares Package für unterschiedliche Funktionen”, und beinhalten somit einiges, was nur selten genutzt wird, sind stark miteinander verzahnt oder für ein spezifisches Projekt entwickelt.

Nichtsdestotrotz könnten diese Packages manchem einen Nutzen bringen und sind nun öffentlich über composer installierbar. Wir helfen auch gern weiter, wenn bei der Nutzung Fragen auftauchen.

Bitte beachte, dass diese Packages unter der GNU GPLv3 Lizenz veröffentlicht wurden und, solltest du eigene Änderungen vornehmen, diese ebenfalls veröffentlicht werden müssen, und die vorgenommenen Änderungen in unsere Packages zurückfliessen können. Benötigst du eine lockerere Lizenzierung, lies bitte unter “Wie geht es weiter?” mehr dazu oder frage uns direkt an.

Natürlich freuen wir uns, wenn beim Durchstöbern in unseren Repositories neue Lösungsideen entstehen oder kleine Snippets daraus direkt eine Verwendung finden und einem anderen Entwickler / einer anderen Entwicklerin vielleicht ein akutes Problem löst.


## Ist das der richtige Weg, um mit Neos zu arbeiten?

Ganz klar JEIN.

Neos erlaubt es, mit seiner Flexibilität alles dem vorliegenden Prozess oder der gewünschten Architektur anzupassen, was viel Sinn machen und Aufwand sparen kann, wenn man sich bei der Entwicklung genau in dem so abgesteckten Bereich bewegt.

Wir haben aber auch gelernt, dass es gefährlich ist, “mit Kanonen auf Spatzen zu schiessen” (bsp. Base Package) und empfehlen inzwischen oft ein von Grund auf neu aufgesetztes Projekt, um einerseits keinen Ballast mitzunehmen und andererseits um dem Kunden ein optimal auf ihn angepasstes Produkt bieten zu können.


## Wie geht es weiter?

Ausgewählte Packages überarbeiten wir in der nächsten Zeit so, dass sie generalistisch verwendbar sind. Diese werden wir unter der noch offeneren MIT-Lizenz veröffentlichen, damit sie wirklich frei verwendbar sind. Geht es zu langsam voran oder besteht akuter Bedarf, sind wir offen für Vorschläge.


## <a name="headingPackages"></a>Um welche Packages geht es?

### Base Packages

- [Dotpulse.Base](https://github.com/webexcess/dotpulse-neos-plugin-base) Sehr umfangreiches Basis-Package zur Erstellung
- [Dotpulse.Basic](https://github.com/webexcess/dotpulse-neos-plugin-basic) Leichtgewichtigeres Basis-Package als Nachfolger von dotpulse.base
- [~~Dotpulse-Gulpfile~~](https://github.com/webexcess/dotpulse-gulpfile.js) Umfangreiches Frontend Build-Tool für Neos und Flow
  - [Gulpfile](https://github.com/jonnitto/gulpfile.js) Jonnitto Fork unter der MIT-Lizenz

### Content Elements

- [Dotpulse.Accordion](https://github.com/webexcess/dotpulse-neos-plugin-accordion) Accordion Content-Elemente
- [Dotpulse.Accordionpages](https://github.com/webexcess/dotpulse-neos-plugin-accordion-pages) Accordion Elemente aus Dokumenten
- [Dotpulse.Button](https://github.com/webexcess/dotpulse-neos-plugin-button) Flexibles Button-ContentElement
- [Dotpulse.Devider](https://github.com/webexcess/dotpulse-neos-plugin-divider) Trenner- oder Störer-ContentElement
- [Dotpulse.Emergency](https://github.com/webexcess/dotpulse-neos-plugin-emergency) Notfallbenachrichtigungen
- [~~Dotpulse.Form~~](https://github.com/webexcess/dotpulse-neos-plugin-form) Formular Erweiterung mit Layout- und Übersetzungs-Optimierungen
  - [WebExcess.Form](https://github.com/webexcess/WebExcess.Form) Production Fork unter der MIT-Lizenz
- [Dotpulse.GoogleMaps](https://github.com/webexcess/dotpulse-neos-plugin-googlemaps) Einfaches Google-Maps ContentElement
- [Dotpulse.Issuu](https://github.com/webexcess/dotpulse-neos-plugin-issuu) ContentElement zur Einbundung von issuu Papers
- [Dotpulse.Mediarow](https://github.com/webexcess/dotpulse-neos-plugin-mediarow) ContentElement zur dynamischen Ausgabe von Media-Inhalten
- [~~Dotpulse.Multicolumn~~](https://github.com/webexcess/dotpulse-neos-plugin-multicolumn) Konfigurierbares Mehrspalten-Element
  - [WebExcess.MultiColumn](https://github.com/webexcess/WebExcess.MultiColumn) Production Fork unter der MIT-Lizenz
- [Dotpulse.ResponsiveTabs](https://github.com/webexcess/dotpulse-neos-plugin-responsivetabs) ContentElement für Responsive Tabs

### Extensions and Helpers

- [Dotpulse.MediaHelper](https://github.com/webexcess/dotpulse-neos-application-mediahelper) Media Asset Tags per Commands zuweisen und TypoScript2 auslesen
- [Dotpulse.GeoIP](https://github.com/webexcess/dotpulse-neos-package-geoip) GeoIP Abfrage und Zuweisung der nächsten Dimension
- [Dotpulse.Mailchimp](https://github.com/webexcess/dotpulse-neos-plugin-mailchimp) Mailchimp Newsletter-Archiv ContentElement
- [Dotpulse.Namingconvention](https://github.com/webexcess/dotpulse-neos-plugin-namingconvention) Erweiterung für konfigurier- und vererbbare SEO-Texte
- [Dotpulse.Searchly](https://github.com/webexcess/dotpulse-neos-plugin-searchly) Einfache Suchresultate des searchly.com Indexers/Crawlers
- [Dotpulse.Visibility](https://github.com/webexcess/dotpulse-neos-plugin-visibility) Erweitert Content Elemente um Responsive Visibility Einstellungen

### More Packages and Packagist

- [https://packagist.org/packages/dotpulse/](https://packagist.org/packages/dotpulse/)
- [https://packagist.org/packages/webexcess/](https://packagist.org/packages/webexcess/)
- [https://github.com/webexcess](https://github.com/webexcess)


## Credits

Der Dank geht an die [Neos Community](https://neos.io) für diese grossartige Content Application Platform,

an [dotpulse AG](http://dotpulse.ch) dafür, dass wir die Quellcodes übernehmen und veröffentlichen durften

und natürlich an die Webentwickler die hinter den veröffentlichten Packages stehen:
- Samuel Hauser
- Jonathan Uhlmann
- Stefan Bruggmann


## Über webexcess

webexcess realisiert Webprojekte mit hohem Anspruch an Inhaltsstruktur, Usability und Nachhaltigkeit.

Wir entwickeln mit Leidenschaft Werkzeuge für mehr Effizienz, Qualität und Freude an der Arbeit in der digitalen Welt. Unsere Lösungen sind langfristig gedacht und überleben auch die kommenden Design-Zyklen.

[webexcess.ch](https://webexcess.ch)
