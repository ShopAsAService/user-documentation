# Erste Schritte

## Stammdaten einpflegen

_Grundeinstellungen > Stammdaten : Stamm_

* Name, Anschrift und weitere Firmeninformationen werden im Shop Admin unter Grundeinstellungen > Stammdaten eingepflegt.

## Sprachen einstellen

_Grundeinstellungen > Sprachen_

* im Standard sind Deutsch und Englisch enthalten.

## Domain aufschalten

* Setze einen CNAME Eintrag auf _meinshop_.cluster1.shopasaservice.de in Deiner DNS Verwaltung.
* Schreibe eine E-Mail an hello@shopasaservice.de, damit wir ein SSL Zertifikat für Deine Domain einrichten (kostenlos im Monatspreis enthalten).

## Mailversand einrichten

_Stammdaten > Grundeinstellungen : Stamm_

* Hierzu benötigst Du ein SMTP-fähiges Postfach. Trage die Zugangsdaten im Shop Admin unter Grundeinstellungen > Stammdaten ein.

## Shopdesign Anpassen

_Erweiterungen > Themes + "Shop as a Service" : Einstell._

### Logo hochladen

_Stammdaten > Grundeinstellungen : Design_

* Lade Dein Logo als JPEG oder PNG hoch.
 
## Das erste Produkt anlegen

_Artikel verwalten > Artikel_

### Kategorien

_Artikel verwalten > Kategorien_

### Attribute

_Artikel verwalten > Attribute_

### Hersteller 

_Stammdaten > Hersteller_ 

Am besten erst die Hersteller anlegen, dann kann ein Artikel einem Hersteller zugeordnet werden.

### Lieferanten

_Stammdaten > Lieferanten_

Am besten erst die Lieferanten anlegen, dann kann ein Artikel einem Lieferanten zugeordnet werden.

## Startseiten-Inhalte anpassen

_Kundeninformationen > CMS_

* Pflege dazu den Inahlt im CMS-Ident: oxstartwelcome 

## Zahlungsarten konfigurieren

_Shopeinstellungen > Zahlungsarten_

* Am einfachsten ist die Zahlart Vorkasse und Kauf auf Rechnung. Diese ist bereits standardmäßig vorkonfiguriert. Um diese zu nutzen, musst Du nur Deine Bankverbindung unter Grundeinstellungen > Stammdaten einpflegen, damit Deine Kunden wissen, wohin sie überweisen müssen.
* Für alle anderen Zahlarten brauchst Du die Anbindung an einen Zahlarte-Provider. Hierfür sind bereits diverse Schnittstellen zu Zahlaungsanbietern wie Klarna, Payone oder Mollie im ShopAsAService enthalten.
* Am einfachsten ist es mit [Mollie](https://www.mollie.com/dashboard/signup/4902724?lang=de). Mollie bietet Dir diverse internationale Zahlarten wie Paypal, Kreditkarte oder Sofortüberweisung aus einer Hand und Du kannst Dich einfach Online bei Mollie registrieren, Händlerdaten erhalten und diese im Adminbereich unter Erweiterungen > Module > Mollie hinterlegen. Anschließend musst du die gewünschten und gebuchten Zahlungsarten unter Shopeinstellungen > Zahlungsarten aktivieren.

## Versandarten anlegen

_Shopeinstellungen > Versandarten_

* die Versandarten anlegen, die es geben soll

## Versandkostenregeln bestimmen

_Shopeinstellungen > Versandkostenregeln_

lege hier die Kosten für den Versand fest, dabei kannst Du folgende Konditionen bestimmen: 

* Zahlarten,
* Länder,
* Versand-Gewicht,
* Kunden und Kundengruppen

## Rechtstexte anpassen

_Kundeninformationen > CMS_

Gib Deine Informationen ein, indem Du die CMS-Ihanle bearbeitest:

* oxagb
* oximpress
* oxorderinfo
* ...

## Deine erste Bestellung

