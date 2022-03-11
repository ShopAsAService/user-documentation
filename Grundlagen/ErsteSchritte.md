# Erste Schritte

## Stammdaten einpflegen

_Grundeinstellungen > Stammdaten : Stamm_

* Name, Anschrift und weitere Firmeninformationen werden im Shop Admin unter Grundeinstellungen > Stammdaten eingepflegt.

![Screenshot 2022-03-03 144329](https://user-images.githubusercontent.com/54799393/156576686-e07bb9a0-e2f0-4c71-b784-0841bfe2a894.png)

## Sprachen einstellen

_Grundeinstellungen > Sprachen_

* im Standard sind Deutsch und Englisch enthalten.

![Screenshot 2022-03-03 144456](https://user-images.githubusercontent.com/54799393/156577020-e354e6af-6e7a-4fcb-a77a-1449147eb7fd.png)

## Domain aufschalten

* Setze einen CNAME Eintrag auf _meinshop_.cluster1.shopasaservice.de in Deiner DNS Verwaltung.
* Schreibe eine E-Mail an hello@shopasaservice.de, damit wir ein SSL Zertifikat für Deine Domain einrichten (kostenlos im Monatspreis enthalten).

## Mailversand einrichten

_Stammdaten > Grundeinstellungen : Stamm_

* Hierzu benötigst Du ein SMTP-fähiges Postfach. Trage die Zugangsdaten im Shop Admin unter Grundeinstellungen > Stammdaten ein (Siehe o. Stammdaten einpflegen).

## Shopdesign Anpassen

_Erweiterungen > Themes + "Shop as a Service" : Einstell._

### Logo hochladen

_Stammdaten > Grundeinstellungen : Design_

* Lade Dein Logo als JPEG oder PNG hoch.
 
## Das erste Produkt anlegen

_Artikel verwalten > Artikel_

Lege hier am Artikel die Eigenschaften des Artikels fest.

![image](https://user-images.githubusercontent.com/54799393/156577726-b21feffa-2250-4b06-b63e-d33a6d234b79.png)


_Artikel verwalten > Artikel_ : Stamm

* Name, Menge/Lagerbestand, Preis, Beschreibung und andere Besonderheiten des Artikels angeben.


_Artikel verwalten > Artikel_ : Varianten

* Falls es den genannten Artikel in verschiedenen Varianten gibt, deren Preise variieren, kann das hier festgelegt werden, anstatt einen eigenen Artikel hierfür anzulegen.

_Artikel verwalten > Artikel_ : Bilder

* Jeder Artikel kann bis zu zwölf Artikelbilder haben, die in der Detailansicht des Artikels angezeigt werden. Artikel verfügen über Zoombilder, die ebenfalls auf der Detailseite aufrufbar sind. Kleinere Artikelbilder zeigen den Artikel in den Artikellisten, in Produktboxen und im Warenkorb. Alle benötigten Bildarten werden automatisch generiert.

### Kategorien

_Artikel verwalten > Kategorien_

* Kategorien stellen durch ihre Struktur das Navigationsmenü im Shop dar und dienen dazu, Kunden des Onlineshops intuitiv zum gewünschten Artikel zu führen. Kategorien fassen Artikel zu Produktgruppen zusammen, präsentieren Artikel einer bestimmten Rubrik oder offerieren Sonderangebote. 

### Attribute

_Artikel verwalten > Attribute_

* Attribute können im Administrationsbereich unter Artikel verwalten > Attribute bearbeitet werden. Es werden eine Liste der Attribute und darunter der Eingabebereich für die Attribute angezeigt.

* Werden Attribute zu Kategorien zugeordnet, lassen sich die Kategorien nach diesen Attributen filtern. In der Kategorieübersicht des Shops können in einer Dropdown-Liste alle Werte des Attributes ausgewählt werden.

![image](https://user-images.githubusercontent.com/54799393/156578226-294e80e5-be39-4f3a-b44a-dc5f12b385b0.png)


### Hersteller 

_Stammdaten > Hersteller_ 

Am besten erst die Hersteller anlegen, dann kann ein Artikel einem Hersteller zugeordnet werden.

![image](https://user-images.githubusercontent.com/54799393/156578587-c09e589d-74db-4070-86d9-d7ba9234a4d0.png)


### Lieferanten

_Stammdaten > Lieferanten_

Am besten erst die Lieferanten anlegen, dann kann ein Artikel einem Lieferanten zugeordnet werden.

![image](https://user-images.githubusercontent.com/54799393/156578645-a101251c-be47-4758-99e7-979d3e234825.png)


## Startseiten-Inhalte anpassen

_Kundeninformationen > CMS-Seiten_

* Pflege dazu den Inahlt im CMS-Ident: oxstartwelcome 

## Zahlungsarten konfigurieren

_Shopeinstellungen > Zahlungsarten_

* Die simpelste Zahlart ist Vorkasse und Kauf auf Rechnung. Diese ist bereits standardmäßig vorkonfiguriert. Um diese zu nutzen, musst Du nur Deine Bankverbindung unter Grundeinstellungen > Stammdaten einpflegen, damit Deine Kunden wissen, wohin sie überweisen müssen.
* Für alle anderen Zahlarten brauchst Du die Anbindung an einen Zahlarte-Provider. Hierfür sind bereits diverse Schnittstellen zu Zahlaungsanbietern wie Klarna, Payone oder Mollie im ShopAsAService enthalten.
* Am einfachsten ist es mit [Mollie](https://www.mollie.com/dashboard/signup/4902724?lang=de). Mollie bietet Dir diverse internationale Zahlarten wie Paypal, Kreditkarte oder Sofortüberweisung aus einer Hand und Du kannst Dich einfach Online bei Mollie registrieren, Händlerdaten erhalten und diese im Adminbereich unter Erweiterungen > Module > Mollie hinterlegen. Anschließend musst du die gewünschten und gebuchten Zahlungsarten unter Shopeinstellungen > Zahlungsarten aktivieren.

![image](https://user-images.githubusercontent.com/54799393/156579029-ccd465ef-3b67-42c9-8258-6c5e95f5b52a.png)


## Versandarten anlegen

_Shopeinstellungen > Versandarten_

* Die Versandarten anlegen, die es geben soll

![image](https://user-images.githubusercontent.com/54799393/156579185-94d6e961-7c1d-469f-a277-d6e6ca4d6a0b.png)


## Versandkostenregeln bestimmen

_Shopeinstellungen > Versandkostenregeln_

lege hier die Kosten für den Versand fest, dabei kannst Du folgende Konditionen bestimmen: 

* Zahlarten,
* Länder,
* Versand-Gewicht,
* Kunden und Kundengruppen

![image](https://user-images.githubusercontent.com/54799393/156579420-d722699b-8a8e-428b-87fe-aa21133d12f6.png)


## Rechtstexte anpassen

_Kundeninformationen > CMS-Seiten_

Gib Deine Informationen ein, indem Du die CMS-Inhalte bearbeitest:

* oxagb
* oximpress
* oxorderinfo
* ...

![image](https://user-images.githubusercontent.com/54799393/156579623-0d9916c5-2284-405f-b0e9-484022132222.png)


### Links zum Thema Rechtssicherer Onlineshop

* Website von Trusted Shops mit Mustertexten für Mitglieder: [www.trustedshops.de](www.trustedshops.de)

* Blog zu aktuellen Rechtsthemen: [www.shopbetreiber-blog.de](www.shopbetreiber-blog.de)

* Weitere Rechtsinformationen für Shopbetreiber: [www.shopbetreiber-recht.de](www.shopbetreiber-recht.de)

## Deine erste Bestellung

### Kunden Verwalten

_Benutzer verwalten > Benutzer_

* Jeder Kunde, der das erste Mal im Shop mit oder ohne Registrierung einkauft, wird als Benutzer erfasst. Auch wenn ein Kunde sich anmeldet, um ein Kundenkonto zu erstellen, oder den Newsletter abonniert, erstellt der Shop einen neuen Benutzer oder aktualisiert einen bereits vorhandenen.

![image](https://user-images.githubusercontent.com/54799393/156579784-5b0ffd5a-4e0c-4540-b905-84cdcc5d8f6b.png)


#### Kundengruppen

_Benutzer verwalten > Benutzergruppen_
* Benutzergruppen dienen dazu, Benutzer mit bestimmten Eigenschaften zusammenzufassen. Solche Eigenschaften können beispielsweise der Status des Benutzers, der bisherigen Umsatz im Shop, die Anmeldung für den Newsletter oder spezielle Preise für bestimmte Artikel sein. Benutzer, die einer Benutzergruppe angehören, lassen sich an anderer Stelle komfortabel zuordnen.

![image](https://user-images.githubusercontent.com/54799393/156580116-00ee5d53-dcf3-4251-afc7-100bb3cc8a9e.png)


### Bestellungen bearbeiten

_Bestellungen verwalten > Bestellungen_

* Eine beim Einkauf im Online-Shop erstellte Bestellung kann nachträglich geändert werden, um beispielsweise eine andere Zahlungs- oder Versandart zuzuweisen. Der Zahlungseingang kann ebenso dokumentiert werden, wie der Versand der Artikel. Rechnung und Lieferschein lassen sich aus der Bestellung heraus erstellen.

![image](https://user-images.githubusercontent.com/54799393/156580270-c2fd7b3a-fb8c-4542-837b-565a5313f810.png)


### Bestellung versenden

_Bestellungen verwalten > Bestellungen : Übersicht -> [Jetzt versenden]_
* Werden die Artikel an den Käufer versendet, kann der Shopbetreiber das bei der Bestellung dokumentieren. Ein Klick auf die Schaltfläche Jetzt versenden ändert den Bestellstatus und den Hinweis Bestellung wurde noch nicht versandt. Stattdessen wird nun ein Hinweis ausgegeben, der den Versand mit Datum und Uhrzeit bestätigt. Zusätzlich wird die Schaltfläche Versendedatum zurücksetzen eingeblendet. Damit kann das bisherige Datum des Versandes zurückgesetzt und die Ware mit aktuellem Datum erneut verschickt werden.

![image](https://user-images.githubusercontent.com/54799393/156580555-0fadf974-b07b-464e-8f8a-1e492c0dc2ff.png)


## Marketing

### Aktionen
 _Kundeninformationen > Aktionen verwalten_
 
* Aktionen können unter Kundeninformationen > Aktionen verwalten bearbeitet werden. Es gibt eine Liste der Aktionen und darunter den Eingabebereich für die Aktionen. Dieser unterscheidet sich für den Typ Banner von Aktion und Promotion, indem es die Möglichkeit gibt, ein Foto für das Banner hochzuladen und zu verlinken.

![image](https://user-images.githubusercontent.com/54799393/156580783-7f9f53e9-4b04-4f1e-813f-8f6db89ff8ac.png)


### Rabatte planen

_Shopeinstellungen > Rabatte_

* Rabatte lassen sich für einen bestimmten Zeitraum oder gar länderspezifisch definieren. Sie können so eingestellt werden, dass das Angebot direkt mit den ermäßigten Preisen angezeigt wird. Es ist aber auch möglich, dass der Rabatt erst im Warenkorb berechnet und ausgewiesen wird. Rabatte können prozentual oder absolut zum Artikelpreis vergeben werden. Neben der Ermäßigung des Artikelpreises gibt es auch die Möglichkeit, bei jedem Kauf, der den Rabattkriterien entspricht, einen Gratisartikel in den Warenkorb zu legen.

![image](https://user-images.githubusercontent.com/54799393/156581679-4e805e84-ac35-4b34-9b67-961fd109b59a.png)


### Gutscheine einrichten

_Shopeinstellungen > Gutscheinserien -> Neue Gutscheinserie anlegen_

* Gutscheinserien sind eine definierte Anzahl von Gutscheinen mit identischer Gültigkeit und den selben Bedingungen zum Einlösen. Die Gutscheine können nach dem Anlegen einer Gutscheinserie mit gleichem Gutscheincode oder individuellen Gutscheinnummern generiert werden. Nachdem die Gutscheine den Weg zum Kunden gefunden haben, beispielsweise über einen verschickten Newsletter, kann der Gutscheincode beim Onlinekauf verwendet werden. Der Kunde gibt seinen Gutscheincode im ersten Bestellschritt ein und erhält einen relativen oder absoluten Rabatt auf bestimmte Artikel oder den gesamten Warenkorb. Dabei wird der gesamte Wert des Gutscheins verbraucht. Es können nicht, wie bei Geschenkgutscheinen üblich, nur Anteile eines vorhandenen Guthabens verwendet werden.

![image](https://user-images.githubusercontent.com/54799393/156581807-b0dc884d-75ae-4eb0-880f-11419f594ed6.png)

![image](https://user-images.githubusercontent.com/54799393/156581886-2261ea38-a76f-44c9-bedf-0bbb7b621bda.png)


### Landingpages erstellen

* Landingpages können Beispielsweise über eine CMS Seite erstellt werden oder über eine Kategorie (wenn auf der Landingpage auch Produkte angezeigt werden sollen)

#### Landingpage via CMS-Seite

_Kundeninformationen > CMS-Seiten : Stamm_

* Im Stamm eine neue CMS-Seite anlegen und Inhalt der LandingPage einfügen

![image](https://user-images.githubusercontent.com/54799393/156586320-0e506d7d-1eaa-4fdb-9e58-1e3a8a8df650.png)


_Kundeninformationen > CMS-Seiten : SEO_

* Eigenschaften zum Umgang durch Suchmaschinen ergänzen

![image](https://user-images.githubusercontent.com/54799393/156586429-527ac755-16be-4efb-9f1a-c710d919d5f9.png)


### Offline Seite

* Im Falle von Fehlern im Shop oder laufenden Wartungsarbeiten, wird der Shop als offline angezeigt worauf der User mit einer Infoseite hingewiesen wird

![5d4c4120ef2b767c6f15fa97c7081d627853d0f4](https://user-images.githubusercontent.com/54799393/156582604-572338a0-c490-4893-bfbf-72c2b2a7773b.png)
