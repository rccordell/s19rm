---
layout: post
title: German Newspapers in Europeana and the Bavarian State Library (digiPress), Deutschsprachige Zeitungen in Europeana und der Bayerischen Staatsbibliothek
tags: [dh, DiD, data reports]
author: jkeck, cneudecker
---

_Report also available in [deutsch](#deutsch)_

## 1. Europeana

### Data Quantity

[Europeana Newspapers](http://www.europeana-newspapers.eu/) is a collection of collections. It assembles digitised historical newspaper content from 20 distinct data providers, each with their own data parameters and histories. In total, the Europeana collection includes 28,816,750 pages in 40 different languages.

The Oceanic Exchanges team is concentrating on the German-language newspapers provided by the following sources:

__Österreichische Nationalbibliothek/Austrian National Library__
* Approximately 1.6 million pages
* JP2000, and (on request) TIFF page facsimiles
* TXT and XML page-level data
* [333 titles available](https://www.europeana.eu/portal/de/search?f%5BDATA_PROVIDER%5D%5B%5D=%C3%96sterreichische+Nationalbibliothek+-+Austrian+National+Library&f%5BREUSABILITY%5D%5B%5D=open&q=europeana_collectionName%3A92%2Aewspapers%2A)

__Staatsbibliothek zu Berlin – Preußischer Kulturbesitz/Berlin State Library__
* Approximately 1.5 million pages
* JP2000, and (on request) TIFF page facsimiles
* TXT and XML page-level data with one title having article-level refinement
* [4 titles available](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Staatsbibliothek+zu+Berlin+-+Preu%C3%9Fischer+Kulturbesitz)

__Staats- und Universitätsbibliothek Hamburg/Hamburg State and University Library__
* Approximately 1.6 million pages
* JP2000, and (on request to LoC) TIFF page facsimiles
* TXT and XML page-level data with a subset also including article-level refinement
* [7 titles available](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Hamburg+State+Library)

__Dr. Friedrich Tessmann Landesbibliothek Südtirol/Dr. Friedrich Tessman Library South-Tyrol__
* Approximately 1 million pages
* JP2000, and (on request) TIFF page facsimiles
* TXT and XML page-level data
* [47 titles available](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Te%C3%9Fmann+Library)

### Data Quality

The overall OCR quality of the Europeana Newspapers collection is approximately 70-85% but varies widely. See also this [detailed report](http://www.europeana-newspapers.eu/wpcontent/uploads/2015/05/D3.5_Performance_Evaluation_Report_1.0.pdf) on quality of OCR and layout recognition performance. For German language newspapers, the average OCR quality is 84% word accuracy for newspapers printed in Roman fonts and around 70% word accuracy for newspapers printed in Gothic fonts (Fraktur). Images from Europeana Newspapers are provided either as 300ppi TIFF or JPEG2000.

A majority of the Europeana newspapers were scanned from microfilm. The performance evaluation has shown that this only slightly impacts OCR quality with less than 1% loss of accuracy while it enables an efficient digitisation of large-scale volumes. Newspaper formats and scan quality can impact the error rate, including challenges of advertisements, tables, and other non-narrative text. In particular, newspapers suffer more from insufficient layout analysis (e.g. merging of articles set in narrow columns) than from the mere text recognition.

The newspapers consist of pages in German language, but there are also some varieties such as, for instance, Austrian or other German dialects.

### Data Availability & Legal Restrictions Concerning the Data

A majority of the newspapers assembled by Europeana Newspapers are dedicated to the public domain with all metadata being released under a CC0 license. All titles are freely searchable through The European Library and Europeana. API access to the data will be re-launched in 2018 with support for IIIF. However, access to recent twentieth-century content is problematic. Europeana Newspapers has developed a ["Roadmap for Improving Access to Newspapers"](http://www.europeana-newspapers.eu/wpcontent/uploads/2015/05/Roadmap_for_Improving_Access_to_Newspapers_final.pdf) to urge policy makers to consider open licenses for digitised newspapers.

### Metadata Structure

All Europeana Newspapers data and metadata follows the [ENMAP profile](http://www.europeana-newspapers.eu/wp-content/uploads/2015/05/D5.3_Final_release_ENMAP_1.0.pdf), a dedicated metadata profile for digital newspapers based on established community standards METS and ALTO.

In addition, Europeana Metadata has also been released in the following five formats: [EDM in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.xml), [EDM in JSONLD](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.jsonld), [Dublin Core in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.dc.xml), and [CLARIN CMDI in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.cmdi.xml).

### Collection History

The Europeana Newspapers data was collected, processed with OCR/OLR and subsequently published with a common full-text search and presentation environment during the EU-funded Europeana Newspapers project (2012-2015). For more information, please see the [project outputs](http://www.europeana-newspapers.eu/public-materials/deliverables/) and [Final Report](http://europeananewspapers.github.io/).


Following the closing of the TEL service end of 2016, work is currently underway to migrate the collection to a "thematic collection" subsite of the main Europeana platform with an anticipated re-launch in Q2/2018.

### Sources
For a list of project outputs, see [http://www.europeana-newspapers.eu/public-materials/deliverables/](http://www.europeana-newspapers.eu/public-materials/deliverables/).
For a list of publications from the project, see [http://www.europeana-newspapers.eu/public-materials/publications/](http://www.europeana-newspapers.eu/public-materials/publications/).
For a review of the Europeana Newspapers portal by Dr. Bob Nicholson, see
[http://www.history.ac.uk/reviews/review/1894](http://www.history.ac.uk/reviews/review/1894).

**2. digiPress**

### Data Quantity
digiPress is the newspaper portal of the Bayerische Staatsbibliothek/Bavarian State Library’s [digitized historical newspapers](https://digipress.digitale-sammlungen.de). It is also a collection of collections and one data provider of German and Austrian digitized historical newspaper content, which is not part of Europeana newspapers. The Bavarian State Library collection includes approximately 6 million digitized newspaper pages, 657 newspaper publishers, 1 million issues and 11,787 recorded articles. The Bavarian State Library has the second largest newspaper collection in Germany.

The Oceanic Exchanges team is concentrating on the German-language newspapers provided by the __Bayerische Staatsbibliothek/Bavarian State Library:__
* Approximately 6 million pages
* PDF, JPG, and (on request) TIFF page facsimiles
* TXT and XML page-level data
* [890 titles available](https://digipress.digitale-sammlungen.de/)

### Data Quality
The newspapers consist of pages in German language, but there are also some varieties such as, for instance, Austrian or other German dialects.

The Bavarian State Library offers each digital copy in two different quality levels. Digital copies for general use are usually produced with a resolution of 150 ppi, in the JPG format and without contained colour profile. High-quality, reproducible copies are made in the form of coloured digital copies with a resolution of 400 ppi, in the TIFF format and with ICC colour profile. In addition, digital copies in 256 grayscale quality can be produced on this basis. However, the files are converted to the sRGB colour space prior to this, conserving the original colouring.

### Data Availability & Legal Restrictions Concerning the Data
The portal digiPress stands out for its particular user-friendliness because, on the one hand, it offers the option to sort all titles according to their area or place of distribution. On the other hand, the new calendar overview provides a time-directed point of entry across the individual newspaper titles. All digitized titles can be retrieved individually via the title list. They are searchable in their entirety in the full-text version.

Bavarikon offers a further possibility to access digiPress directly from its home page. The portal to the art, culture and regional studies of the Free State of Bavaria expands its digital holdings, for the first time presenting a [large collection of historical newspapers](https://www.bavarikon.de/?locale=en).

The Bayerische Staatsbibliothek holds licenses for some electronic newspapers. Among them are e.g. the "Sueddeutsche Zeitung" or the "Frankfurter Allgemeine". The majority of the electronic newspaper titles can be retrieved from two comprehensive databases: via "Nexis" with several thousand international newspapers and via "wiso", whose press module offers full-text access to over 100 German-language newspapers. These newspaper titles, important information regarding the conditions of access and a number of links to further frequently used newspapers are all available in the Database Information System (DBIS).

Digital copies of newspapers held by the Bayerische Staatsbibliothek are provided in the newspaper portal "digiPress". Further free and also licensed offers of historical newspapers and newspaper collections, such as "The Times Digital Archive 1785 – 1985" or also "Austrian Newspapers Online" are also accessible using the Database Information System.

* [Sueddeutsche Zeitung](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=7881)
* [Frankfurter Allgemeine](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=5333)
* [Nexis](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=1670)
* [wiso](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=1232)
* [digiPress](https://digipress2.digitale-sammlungen.de/)
* [The Times Digital Archive](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=5199)
* [ANNO – Austrian Newspapers Online](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=2012)
* [Database Information System  (selection newspaper)](http://dbis.ur.de/dbliste.php?bib_id=bsb&lett=k&db_type[]=8)

### Metadata Structure
All digipress data and metadata follows the [IIIF profile](http://iiif.io/) (International Image Interoperability Framework). The metadata of a digitized cultural object are--as defined by the IIIF Presentation API 2.1.1--offered as IIIF manifest in JSON LD. Find metadata here [https://opacplus.bsb-muenchen.de/title/2165563-7](https://opacplus.bsb-muenchen.de/title/2165563-7), as well as links to other representations, e.g. in the format MARC-XML.

### Collection History
A fairly large number of historical newspapers has already been digitized. There have been several projects, also in cooperation with archives, which made it possible to make around 25 Bavarian journals available online, among them the topical focus on "Bavarian Newspapers 1848 – 1950." A substantial portion of the copyright-free newspaper titles of the Bayerische Staatsbibliothek (over 1,000 newspaper titles) have been digitized within the framework of a public-private partnership with Google. These are made available consecutively via the newspaper portal of the Bayerische Staatsbibliothek, "digiPress".

The Bavarian newspapers published after 1945 have been preserved almost comprehensively by the Bayerische Staatsbibliothek. Currently, around 250 Bavarian newspapers are archived sustainably in the form of legal deposits.

In the course of the years, the collection profile has been expanded to encompass important daily newspapers of other European countries and to cover, where possible, different political orientations. Beyond Europe, important daily newspapers have also been purchased selectively. More than 60 international and German newspapers are continuously subscribed in the form of printed issues or microfilm issues.

E-journals are also gaining in importance. The Bayerische Staatsbibliothek holds individual licenses for some electronic journals. Among them are the Sueddeutsche Zeitung or the Frankfurter Allgemeine Zeitung. The majority of electronic newspaper titles can be retrieved via two comprehensive databases: Via Nexis, covering several thousand international newspapers, and via wiso, whose press module offers full-text access to over 100 German-language newspapers.

The Bayerische Staatsbibliothek continues looking for newspapers and individual issues of newspapers which were published but whose copies are not currently known to exist (so-called ["bibliographical ghosts" or "lost newspapers"](https://www.bayerische-landesbibliothek-online.de/zeitungen-amtsblaetter)).

### Sources

For current activities, see [https://www.bsb-muenchen.de/en/collections/article/digital-search-in-the-historical-press-bayerische-staatsbibliothek-starts-newspaper-portal-digipress-1840/](https://www.bsb-muenchen.de/en/collections/article/digital-search-in-the-historical-press-bayerische-staatsbibliothek-starts-newspaper-portal-digipress-1840/). For a collection overview, see [https://www.bsb-muenchen.de/en/collections/collection-overview/](https://www.bsb-muenchen.de/en/collections/collection-overview/).

# <a name="deutsch"></a>Deutschsprachige Zeitungen in Europeana und der Bayerischen Staatsbibliothek (digiPress)

## 1. Europeana

### Datenmenge

[Europeana Newspapers](http://www.europeana-newspapers.eu/) ist eine Sammlung von Sammlungen. Die Plattform stellt digitalisierte historische Zeitungsinhalte von 20 verschiedenen Datenanbietern zusammen, jede mit ihren eigenen Datenparametern und Historien. Insgesamt umfasst die Europeana-Sammlung 28.816.750 Seiten in 40 verschiedenen Sprachen.

Das Team von Oceanic Exchanges arbeitet mit den deutschsprachigen Zeitungen aus den folgenden Quellen:

__Österreichische Nationalbibliothek/Austrian National Library__
* Etwa 1,6 Millionen Seiten
* JP2000 und (auf Anfrage) TIFF Page Facsimiles
* TXT und XML Daten auf Seitenebene
* [333 Zeitungsttitel verfügbar](https://www.europeana.eu/portal/de/search?f%5BDATA_PROVIDER%5D%5B%5D=%C3%96sterreichische+Nationalbibliothek+-+Austrian+National+Library&f%5BREUSABILITY%5D%5B%5D=open&q=europeana_collectionName%3A92%2Aewspapers%2A)

__Staatsbibliothek zu Berlin – Preußischer Kulturbesitz/Berlin State Library__
* Etwa 1,5 Millionen Seiten
* JP2000 und (auf Anfrage) TIFF Page Facsimiles
* TXT and XML Daten auf Seitenebene mit einem Titel mit Verfeinerungen auf Artikelebene
* [4 Zeitungstitel verfügbar](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Staatsbibliothek+zu+Berlin+-+Preu%C3%9Fischer+Kulturbesitz)

__Staats- und Universitätsbibliothek Hamburg/Hamburg State and University Library__
* Etwa 1,6 Millionen Seiten
* JP2000 and (auf Anfrage zu LoC) TIFF Page Facsimiles
* TXT und XML Daten auf Seitenebene mit einer Untermenge, die auch Verfeinerungen auf Artikelebene enthält
* [7 Zeitungstitel verfügbar](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Hamburg+State+Library)

__Dr. Friedrich Tessmann Landesbibliothek Südtirol/Dr. Friedrich Tessman Library South-Tyrol__
* Etwa 1 Million Seiten
* JP2000 und (auf Anfrage) TIFF Page Facsimiles
* TXT und XML Daten auf Seitenebene
* [47 Zeitungstitel verfügbar](https://www.europeana.eu/portal/de/search?q=europeana_collectionName%3A92*ewspapers*&f[DATA_PROVIDER][]=Te%C3%9Fmann+Library)

### Datenqualität

Die gesamte OCR-Qualität der Europeana Newspapers-Sammlung beträgt ca. 70-85%. Diese variiert jedoch stark. Ein ausführlicher Bericht zur Qualität der OCR- und Layout-Erkennungsleistung finden Sie hier unter: [http://www.europeana-newspapers.eu/wpcontent/uploads/2015/05/D3.5_Performance_Evaluation_Report_1.0.pdf](http://www.europeana-newspapers.eu/wpcontent/uploads/2015/05/D3.5_Performance_Evaluation_Report_1.0.pdf). Für deutschsprachige Zeitungen beträgt die durchschnittliche OCR-Qualität 84% Wortgenauigkeit für in römischen Fonts gedruckte Zeitungen und etwa 70% Wortgenauigkeit für in Frakturschrift gedruckte Zeitungen. Bilder von Europeana Newspapers stehen entweder als 300ppi TIFF oder JPEG2000 zur Verfügung.

Ein Großteil der Europeana-Zeitungen wurde von Mikrofilm gescannt. Die Leistungsbewertung hat gezeigt, dass dies die OCR-Qualität nur geringfügig mit einem Genauigkeitsverlust von weniger als 1% beeinflusst bei der Durchführung einer effizienten Digitalisierung großer Volumina. Zeitungsformate und Scanqualität können die Fehlerrate beeinflussen, einschließlich der Herausforderungen von Anzeigen, Tabellen und anderem nicht-narrativen Textmaterial. Insbesondere leiden Zeitungen eher unter unzureichender Layout-Analyse (z. B. beim Zusammenführen von Artikeln, die in engen Spalten angeordnet sind) als nach der bloßen Texterkennung.

Die Zeitungen bestehen aus Seiten, die in deutscher Sprache verfasst wurden, aber es gibt auch einige Varianten wie zum Beispiel österreichische oder andere deutsche Dialekte.

### Datenverfügbarkeit & Rechtliche Einschränkungen der Daten

Die Mehrheit der Zeitungen, die von Europeana Newspapers zusammengestellt werden, sind dem öffentlichen Bereich gewidmet, wobei alle Metadaten unter einer CC0-Lizenz veröffentlicht werden. Alle Titel sind frei durch die Europäische Bibliothek und Europeana durchsuchbar. API-Zugriff auf die Daten wird 2018 mit Unterstützung für IIIF neu gestartet. Der Zugang zu Inhalten des letzten Jahrhunderts ist jedoch problematisch. Europeana Newspapers hat ein ["Roadmap zur Verbesserung des Zugangs zu Zeitungen"](http://www.europeana-newspapers.eu/wpcontent/uploads/2015/05/Roadmap_for_Improving_Access_to_Newspapers_final.pdf) entwickelt, um politische Entscheidungsträger aufzufordern, offene Lizenzen für digitalisierte Zeitungen in Betracht zu ziehen.

### Metadatenstruktur

Alle Daten und Metadaten von Europeana Newspapers folgen dem [ENMAP-Profil](http://www.europeana-newspapers.eu/wp-content/uploads/2015/05/D5.3_Final_release_ENMAP_1.0.pdf), einem speziellen Metadatenprofil für digitale Zeitungen, das auf den etablierten Gemeinschaftsstandards METS und ALTO basiert.

Darüber hinaus wurde Europeana Metadata auch in den folgenden fünf Formaten veröffentlicht: [EDM in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.xml), [EDM in JSONLD](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.jsonld), [Dublin Core in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.dc.xml), [CLARIN CMDI in XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.cmdi.xml).

### Sammlungsgeschichte

Die Daten von Europeana Newspapers wurden während des EU-finanzierten Projekts Europeana Newspapers (2012-2015) gesammelt, mit OCR / OLR verarbeitet und anschließend in einer gemeinsamen Volltextsuch- und Präsentationsumgebung veröffentlicht. Weitere Informationen finden Sie in den Projektausgaben ([http://www.europeana-newspapers.eu/public-materials/deliverables/](http://www.europeana-newspapers.eu/public-materials/deliverables/)) und im Abschlussbericht ([http://europeananewspapers.github.io/](http://europeananewspapers.github.io/)).


Nach Abschluss des TEL-Dienstes Ende 2016 wird derzeit daran gearbeitet, die Sammlung in einen "thematischen Sammlungsbereich" der Hauptplattform Europeana zu migrieren, mit einem erwarteten Relaunch in Q2 / 2018.

### Quellen
* Einen Überlick der Projekte finden Sie unter [http://www.europeana-newspapers.eu/public-materials/deliverables/](http://www.europeana-newspapers.eu/public-materials/deliverables/)
* Eine Liste der Veröffentlichungen des Projekts finden Sie unter [http://www.europeana-newspapers.eu/public-materials/publications/](http://www.europeana-newspapers.eu/public-materials/publications/)
* Einen Überblick über das Portal Europeana Newspapers von Dr. Bob Nicholson finden Sie unter
[http://www.history.ac.uk/reviews/review/1894](http://www.history.ac.uk/reviews/review/1894)

## 2. digiPress

### Datenmenge

digiPress ist das Zeitungsportal der digitalisierten historischen Zeitungen der Bayerischen Staatsbibliothek ([https://digipress.digitale-sammlungen.de](https://digipress.digitale-sammlungen.de)). Es ist auch eine Sammlung von Sammlungen und ein Datenanbieter von digitalisierten deutschen historischen Zeitungsinhalten, die nicht Teil von Europeana Newspapers ist. Die Sammlung der Bayerischen Staatsbibliothek umfasst ca. 6 Millionen digitalisierte Zeitungsseiten, 657 Zeitungsverlage, 1 Million Ausgaben und 11.787 bespielte Artikel. Die Bayerische Staatsbibliothek verfügt über die zweitgrößte Zeitungssammlung in Deutschland.

Das Team von Oceanic Exchanges konzentriert sich auf die deutschsprachigen Zeitungen der __Bayerischen Staatsbibliothek/Bavarian State Library:__
* Etwa 6 Millionen Seiten
* PDF, JPG und (auf Anfrage) TIFF page facsimiles
* TXT und XML Daten auf Seitenebene
* [890 Zeitungstitel verfügbar](https://digipress.digitale-sammlungen.de/)

### Datenqualität

Die Zeitungen bestehen aus Seiten in deutscher Sprache, aber es gibt auch einige Varianten wie zum Beispiel österreichische oder andere deutsche Dialekte.

Die Bayerische Staatsbibliothek bietet jede digitale Kopie in zwei verschiedenen Qualitätsstufen an. Digitale Kopien für den allgemeinen Gebrauch werden normalerweise mit einer Auflösung von 150 ppi im JPG-Format und ohne Farbprofil erstellt. Hochwertige, reproduzierbare Kopien werden in Form von farbigen digitalen Kopien mit einer Auflösung von 400 ppi im TIFF-Format und mit ICC-Farbprofil erstellt. Darüber hinaus können auf dieser Basis digitale Kopien in 256 Graustufenqualität erstellt werden. Die Dateien werden jedoch zuvor in den sRGB-Farbraum konvertiert, wobei die ursprüngliche Farbgebung erhalten bleibt.

### Datenverfügbarkeit & Rechtliche Einschränkungen der Daten

Das Portal digiPress zeichnet sich durch besondere Benutzerfreundlichkeit aus, da es zum einen die Möglichkeit bietet, alle Titel nach ihrer Region oder ihrem Verbreitungsort zu sortieren. Auf der anderen Seite bietet die neue Kalenderübersicht einen zeitabhängigen Einstiegspunkt für die einzelnen Zeitungstitel. Alle digitalisierten Titel können einzeln über die Titelliste abgerufen werden. Sie sind in der Volltextversion vollständig durchsuchbar.

Bavarikon bietet eine weitere Möglichkeit, direkt von seiner Homepage auf digiPress zuzugreifen. Das Portal zur Kunst-, Kultur- und Landeskunde des Freistaates Bayern erweitert seine digitalen Bestände und präsentiert erstmals eine große Sammlung historischer Zeitungen ([https://www.bavarikon.de/?locale=en](https://www.bavarikon.de/?locale=en)).

Die Bayerische Staatsbibliothek besitzt Lizenzen für einige elektronische Zeitungen. Unter ihnen sind z. B. die "Süddeutsche Zeitung" oder die "Frankfurter Allgemeine". Der Großteil der elektronischen Zeitungstitel kann aus zwei umfangreichen Datenbanken abgerufen werden: über "Nexis" mit mehreren tausend internationalen Zeitungen und über "wiso", dessen Pressemodul Volltextzugriff auf über 100 deutschsprachige Zeitungen bietet. Die Zeitungstitel, wichtige Informationen zu den Zugangsbedingungen und eine Reihe von Links zu weiteren häufig verwendeten Zeitungen sind im Datenbankinformationssystem (DBIS) verfügbar.

Die Digitalisate der Zeitungen der Bayerischen Staatsbibliothek werden im Zeitungs-Portal "digiPress" bereitgestellt. Weitere freie und auch lizensierte Angebote von historischen Zeitungen und Zeitungssammlungen wie "The Times Digital Archive 1785 - 1985" oder auch "Austrian Newspapers Online" sind ebenfalls über das Datenbank-Informationssystem zugänglich.
* [Süddeutsche Zeitung](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=7881)
* [Frankfurter Allgemeine](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=5333)
* [Nexis](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=1670)
* [wiso](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=1232)
* [digiPress](https://digipress2.digitale-sammlungen.de/)
* [The Times Digital Archive](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=5199)
* [ANNO – Austrian Newspapers Online](http://dbis.ur.de/detail.php?bib_id=bsb&lett=fs&titel_id=2012)
* [Database Information System  (Auswahl Zeitungen)](http://dbis.ur.de/dbliste.php?bib_id=bsb&lett=k&db_type[]=8)

### Metadatenstruktur

Alle Digipress Daten und Metadaten folgen dem IIIF Profil (International Image Interoperability Framework; [http://iiif.io/](http://iiif.io/)). Die Metadaten eines digitalisierten Kulturobjekts werden - wie in der IIIF Presentation API 2.1.1 definiert - als IIIF Manifest in JSON LD angeboten. Dort finden Sie Metadaten für die Anzeige und hier [https://opacplus.bsb-muenchen.de/title/2165563-7](https://opacplus.bsb-muenchen.de/title/2165563-7) Links zu anderen Darstellungen, z. B. im Format MARC-XML.

### Sammlungsgeschichte

Eine ziemlich große Anzahl historischer Zeitungen wurde bereits digitalisiert. Es gab mehrere Projekte, auch in Kooperation mit Archiven, die es ermöglichten, rund 25 bayerische Zeitschriften online zur Verfügung zu stellen, darunter den aktuellen Schwerpunkt "Bayerische Zeitungen 1848 - 1950". Ein wesentlicher Teil der urheberrechtsfreien Zeitungstitel die Bayerische Staatsbibliothek (über 1.000 Zeitungstitel) wurden im Rahmen einer Public-Private-Partnership mit Google digitalisiert, die über das Zeitungs-Portal der Bayerischen Staatsbibliothek "digiPress" fortlaufend zur Verfügung gestellt werden.

Die nach 1945 erschienenen bayerischen Zeitungen sind von der Bayerischen Staatsbibliothek fast vollständig erhalten. Derzeit werden rund 250 bayerische Zeitungen in Form von legalen Einlagen nachhaltig archiviert.

Im Laufe der Jahre wurde das Sammelprofil auf wichtige Tageszeitungen anderer europäischer Länder ausgeweitet und, soweit möglich, auf unterschiedliche politische Orientierungen ausgerichtet. Außerhalb Europas wurden auch wichtige Tageszeitungen selektiv gekauft. Mehr als 60 internationale und deutsche Zeitungen werden kontinuierlich in Form von gedruckten Ausgaben oder Mikrofilmausgaben abonniert.

E-Journale gewinnen ebenfalls an Bedeutung. Die Bayerische Staatsbibliothek besitzt Einzellizenzen für einige elektronische Zeitschriften. Darunter sind die Süddeutsche Zeitung oder die Frankfurter Allgemeine Zeitung. Die Mehrzahl der elektronischen Zeitungstitel kann über zwei umfassende Datenbanken abgerufen werden: über Nexis, welches mehrere tausend internationale Zeitungen umfasst, und über wiso, dessen Pressemodul Volltextzugriff auf über 100 deutschsprachige Zeitungen bietet.

Die Bayerische Staatsbibliothek sucht weiterhin nach Zeitungen und Einzelausgaben von Zeitungen, die zwar veröffentlicht wurden, deren Kopien aber derzeit nicht bekannt sind (sogenannte "bibliographische Geister" oder "verlorene Zeitungen") ([https://www.bayerische-landesbibliothek-online.de/zeitungen-amtsblaetter](https://www.bayerische-landesbibliothek-online.de/zeitungen-amtsblaetter)).

### Quellen

* Aktuelle Aktivitäten finden Sie unter [https://www.bsb-muenchen.de/en/collections/article/digital-search-in-the-historical-press-bayerische-staatsbibliothek-starts-newspaper-portal-digipress-1840/](https://www.bsb-muenchen.de/en/collections/article/digital-search-in-the-historical-press-bayerische-staatsbibliothek-starts-newspaper-portal-digipress-1840/)
* Einen Sammlungsüberblick finden Sie unter [https://www.bsb-muenchen.de/en/collections/collection-overview/](https://www.bsb-muenchen.de/en/collections/collection-overview/)
