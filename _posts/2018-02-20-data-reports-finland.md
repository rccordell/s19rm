---
layout: post
title: Digitized Newspapers at the National Library of Finland, Suomen kansalliskirjaston digitoidut sanomalehdet
tags: [dh, DiD, data reports]
author: moiva, hsalmi, anivala
---
_Report also available in [Suomi](#suomi)_

The digital collection of the National Library of Finland includes 12.8 million pages of newspapers and journals. Only the newspapers published before 1930 are freely available online at the website of the Library. The collection includes all published newspapers and journals, from the first newspaper _Tidningar Utgifne af et Sällskap i Åbo_, founded in 1771, until the end of the year 1929. The extent of the collection is as follows (as of 19 February 2018):

Newspapers:

* Total digitized pages			6,259,133
* Pages in open use				4,031,018  (64%) (-1929) 
* Pages in restricted use		2,228,115  (36%) (1930-)

Journals:

* Total digitized pages 		6,507,310
* Pages in open use				3,360,240  (51%) (-1929)
* Pages in restricted use  		3,147,070  (49%) (1930-)

The open collection, up to 1929, can be browsed at the website of the [National Library of Finland](https://digi.kansalliskirjasto.fi/). The data packages available for the Oceanic Exchanges project have been presented below. The Finnish team has already worked with the newspapers of the years 1771-1910 in the project _Computational History and the Transformation of Public Discourse in Finland, 1640-1910_. The following estimation of data quality is based on that work.

## Data Quality 

The overall OCR quality of the early collection is approximately 69-75%. Most of the newspapers in the collection were printed using Fraktur typeset, while Antiqua printing style remained in minority. This causes problems for the OCR quality. As a general rule, the older newspapers are more difficult to OCR, and the newspapers closer to the late 19th and early 20th centuries provide less OCR errors. Around 25-30% of the collections needs further processing in order to improve the overall quality of the data.

The volume of newspaper publishing increased towards the turn of the century in Finland: in the 1771-1910 dataset, 82.7% of the data is from the 1890-1910, and 92.3% is from the last four decades, 1870-1910. The majority of the newspapers consists of pages in Finnish and Swedish language, but there are also pages in Russian and German. Different languages dominated the Finnish publication sphere in different periods: more than 50% of the publications before the late 1880s were in Swedish, after which the share of Finnish language publications increased to over 75% in 1910. The Russian language publications emerged after the year 1900, while there were German language publications already during the 1820s and 1830s (_Wiburgs Wochenblatt_ covers years 1823-1832). Out of the total number of newspaper pages in the collection between 1771-1910 1,063,648 are in Finnish, 892,191 in Swedish, 8997 in Russian, and 2551 in German.

The journal data is more varied in terms of languages. Out of the 1,147,791 pages published between 1771-1910, 605,762 are in Finnish, 479,462 in Swedish, and the rest are either multilingual or in other languages.

## Data Availability & Legal Restrictions Concerning the Data

The data collected for Oceanic Exchanges include: 

1. _The Newspaper and Periodical OCR Corpus of the National Library of Finland (1771-1874)_ was released in 2011. The data package is in the METS/ALTO format and downloadable via the [Language Bank of Finland](http://urn.fi/urn:nbn:fi:lb-2015051201). It has been released under the Creative Commons license (CC BY 4.0).
2. The data package 1771-1910 has been provided by the National Library of Finland to the project _Computational History and the Transformation of Public Discourse in Finland, 1640-1910 (COMHIS)_, and it is already at the disposal of the Finnish team of the Oceanic Exchanges project. This data package is not openly available, but there are no legal restrictions concerning the usage of the data for the purpose of research. The [COMHIS project](http://comhis.fi/clusters) has studied text reuse in Finnish newspapers and journals between 1771-1910.
3. The _Newspaper and Periodical OCR Corpus of the National Library of Finland (1875-1920)_ was released in November 2017. The data package is downloadable via the [Language Bank of Finland](http://urn.fi/urn:nbn:fi:lb-201801191). The data dump includes all those newspapers and journals that had been digitized by the end of the year 2013. This includes all published newspapers 1875-1920. Some journals, published in the 1910s and digitized after 2013 are still missing but they can be accessed at the searchable online collection which is constantly updated. More details on the license (CLARIN ACA end-user license +NC 1.0) can be found at [https://www.kielipankki.fi/lic/digilib-1920-dl/](https://www.kielipankki.fi/lic/digilib-1920-dl/).
 
## Metadata Structure

The National Library of Finland has been digitizing the collection with an average speed of about one million pages a year. Almost every year the back-end system has been improved, and new versions containing new features have been introduced.

The main database of the National Library contains metadata, page data, and file data containing the archive directory information. The online system of the database offers page images of the content, and access to the content of the pages in ALTO XML (Analyzed Layout and Text Object) format.

In the data packages, pages are located in two separate directories: one based on ISSN and the other on the publication year. Below the publication year in the data structure is the language of the publication, below which are the actual ALTO XML files. They are named descriptively: ISSN_YEAR_DATE_ISSUE_PAGE.

### Metadata in the data package 1771-1874
The data package 1771-1874 includes ALTO files and metadata in METS format. As an example:

```xml
<dmdSec ID="MODSMD_CHAP2">
	<mdWrap MIMETYPE="text/xml" MDTYPE="MODS" LABEL="Bibliographic meta-data of chapter 0">
		<xmlData>
			<MODS:mods>
				<MODS:titleInfo ID="MODSMD_CHAP2_TI2" xml:lang="fi">
					<MODS:title>Minkätähden Hüneburg ei antautunut.</MODS:title>
				</MODS:titleInfo>
				<MODS:name ID="MODSMD_CHAP2_N2" type="personal">
					<MODS:namePart type="given">A.</MODS:namePart>
					<MODS:namePart type="family">G</MODS:namePart>
					<MODS:role>
						<MODS:roleTerm>aut</MODS:roleTerm>
					</MODS:role>
				</MODS:name>
				<MODS:language>
					<MODS:languageTerm type="code" authority="rfc3066">fi</MODS:languageTerm>
				</MODS:language>
			</MODS:mods>
		</xmlData>
	</mdWrap>
</dmdSec>
```

### Metadata in the data package 1771-1910
The data package for 1771-1910 includes ALTO files but no METS. Metadata has been included in the beginning of the files in XML format. Example:

```xml
<metadata>
	<title>Kirkollinen kuukauslehti : uskonnollista lukemista perheille</title>
	<identifier type="nbn">fk00873</identifier>
	<published format="edtf">1881-11</published>
	<issue>11</issue>
		<pageOrder>21</pageOrder>
		<pageLabel></pageLabel>
	<language>fin</language>
	<contentType>serial</contentType>
	<originalPublisher/>
	<latestPublisher>[s.n.]</latestPublisher>
		<publishingPlace country="fi"></publishingPlace>
	<copyright>Copyrights expired</copyright>
	<license>ESIVERSIO - EI EDELLEENJAKELUUN</license>
		<pageIdentifier>7687234</pageIdentifier>
		<bindingIdentifier>984738</bindingIdentifier>
	<imageURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/image/21</imageURL>
	<pdfURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/pdf</pdfURL>
	<browseURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/#?page=21</browseURL>
	<pingURL/>
	<ocrVersion/>
	<lastModified>2012-04-12T00:04:00</lastModified>
</metadata>
```

### Metadata in the data package 1875-1920
The metadata of the collection for years 1875-1920 is in ALTO/METS format. For instance: 

```xml
<mets xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://www.loc.gov/METS/" xsi:schemaLocation="http://www.loc.gov/METS/ //Themis/docworks/docWORKS/schema/mets-metae.xsd" xmlns:MODS="http://www.loc.gov/mods/v3" xmlns:mix="http://www.loc.gov/mix/" xmlns:xlink="http://www.w3.org/TR/xlink" TYPE="METAe_Serial" LABEL="Finsk Tidskrift no. 1-2 01.1911">
	<metsHdr CREATEDATE="2007-03-27T10:35:59" LASTMODDATE="2007-03-27T10:35:59">
		<agent ROLE="CREATOR" TYPE="OTHER" OTHERTYPE="SOFTWARE">
			<name>CCS docWORKS/METAe Version 6.0-8</name>
		</agent>
	</metsHdr>
<dmdSec ID="MODSMD_PRINT">
	<mdWrap MIMETYPE="text/xml" MDTYPE="MODS" LABEL="Bibliographic meta-data of the printed version">
		<xmlData>
			<MODS:mods>
				<MODS:titleInfo ID="MODSMD_PRINT_TI1" xml:lang="sv">
					<MODS:title>Finsk Tidskrift</MODS:title>
					<MODS:partName>70-71</MODS:partName>
				</MODS:titleInfo>
				<MODS:language>
					<MODS:languageTerm type="code" authority="rfc3066">sv</MODS:languageTerm>
				</MODS:language>
				<MODS:originInfo>
					<MODS:dateIssued encoding="w3cdtf" keyDate="yes" qualifier="approximate">1911</MODS:dateIssued>
				</MODS:originInfo>
				<MODS:identifier type="ISSN">0015-248X</MODS:identifier>
			</MODS:mods>
		</xmlData>
	</mdWrap>
</dmdSec>
```

## Collection History

In Finland, the digitization of cultural heritage started in the mid 1990s. From the perspective of newspaper collections, an essential turning point was the launching of the Nordic project TIDEN in 1998. It was a joint project of four institutions: the Royal Library of Sweden, The National Library of Norway, the University Library of Århus (Denmark), and the Helsinki University Library which was the coordinator of the project. The Helsinki University Library had established the Center for Microfilming and Conservation already in 1990, in the small town of Mikkeli in Eastern Finland, with the idea of creating a comprehensive microfilm collection of Finnish newspapers and journals. Soon, it became obvious that digitization would be more fruitful for developing research infrastructures, and the TIDEN project gave the possibility to concentrate on exploring the problems of digitization but also in producing actual digital copies of Finnish newspapers, mostly on the basis of previously produced microfilms. Today, the Mikkeli center is known as the Centre for Preservation and Digitisation, which is part of the National Library of Finland.

In 2001, the National Library of Finland finally opened its [online collection of digitized newspapers](http://digi.lib.helsinki.fi/). It was announced that all Finnish newspapers from 1771 to 1860 will be digitized and made openly available in the net. It was estimated that, in the end, the collection would cover 44 different titles and 90,000 pages. At the time of the launching of the website in 2001, only one third, in sum 36,000 pages was available. This was the start, and now, after 17 years, the open collection includes all newspapers and journals from 1771 to 1929.

The TIDEN project was important in defining best practices for future digitization projects. Its main ideas were published together with the recommendations of The International Federation of Library Associations and Institutions (IFLA) in the publication _Guidance on the Best Practices for Microfilming of Newspapers in Preparation for Possible Future Digitisation_ (2003). In Finland, the digital collection is based on microfilms, which means that both the quality of the microfilm and the quality of the original newspaper are essential. In the present collection, the differences in quality have obviously had an impact on the accuracy of optical character recognition which varies from decade to decade.

# <a name="suomi"></a>Suomen kansalliskirjaston digitoidut sanomalehdet

Suomen kansalliskirjaston digitaalinen kokoelma sisältää 12,8 miljoonaa sivua sanoma- ja aikakauslehtiä. Tällä hetkellä lehtiä voi vuoden 1929 numeroihin asti lukea avoimesti kirjaston sivustolla. Kokoelma kattaa kaikki suomalaiset sanoma- ja aikakauslehdet, ensimmäisestä, vuonna 1771 perustetusta sanomalehdestä _Tidningar Utgifne af et Sällskap i Åbo_ lähtien vuoden 1929 loppuun. Kokoelmaa voi kuvata seuraavin luvuin (tilanne 19.2.2018):

Sanomalehtiä:

* Digitoituja sivuja yhteensä  	6 259 133
* Sivuja vapaassa käytössä  		4 031 018  (64%) (-1929)
* Sivuja rajatussa käytössä  		2 228 115  (36%) (1930-)

Aikakauslehtiä:

* Digitoitu sivuja yhteensä  		6 507 310
* Sivuja vapaassa käytössä  		3 360 240  (51%) (-1929)
* Sivuja rajatussa käytössä  		3 147 070  (49%) (1930-)

Koko vapaassa käytössä oleva aineisto on selattavissa Kansalliskirjaston hakuportaalin kautta [https://digi.kansalliskirjasto.fi/](https://digi.kansalliskirjasto.fi/). _Oceanic Exchanges_ -hankkeen käytössä olevat datapaketit on eritelty alempana. Projektin suomalaisilla jäsenillä on aiempaa kokemusta vuosien 1771-1910 aineiston tutkimuksesta hankkeessa _Computational History and the Transformation of Public Discourse in Finland, 1640-1910_ (ks. julkaisuluettelo). Seuraava aineiston laatua käsittelevä osuus perustuu tähän työhön. 

## Aineiston laatu 

Vuosien 1771-1910 aineistossa optisen tekstintunnistuksen (OCR) tarkkuus on keskimäärin 69-75%. Suurin osa sanomalehdistä on painettu fraktuurakirjasimella, joka on vaikeammin OCR-ohjelmien tunnistettavissa. Koska erityisesti vanhemmissa lehdissä käytettiin fraktuurakirjasinta, voidaan yleistää, että mitä vanhempi sanomalehti, sen vaikeampi tekstiä on tunnistaa koneellisesti. Aineisto sisältää keskimäärin vähemmän OCR-virheitä 1800-luvun lopussa ja 1900-luvun alussa kuin 1800-luvun alussa. Noin 25-30% kokoelman aineistosta vaatisi lisäkäsittelyä aineiston kokonaislaadun parantamiseksi.

Sanomalehtiaineiston määrä painottuu kokoelman loppupäähän, sillä sanomalehtiä oli verrattain vähän 1700-luvun lopussa ja 1800-luvun alussa, mutta niiden määrä kasvoi nopeasti 1800-luvun lopussa. Aineistosta 82,7% on vuosilta 1890-1910 ja peräti 92,3% neljältä viimeiseltä vuosikymmeneltä 1870-1910. Valtaosa aineistosta on suomen ja ruotsin kielellä, mutta materiaalia on myös saksaksi ja venäjäksi. Eri kielet hallitsevat aineistossa eri aikakausia: yli 50% julkaisuista ennen 1880- ja 1890-luvun taitetta olivat ruotsiksi, minkä jälkeen suomenkielisten lehtien osuus kasvoi. Vuonna 1910 suomeksi julkaistiin yli 75% sanomalehdistä. Venäjänkielisiä lehtiä julkaistiin vuoden 1900 jälkeen, kun taas saksankielisiä lehtiä ilmestyi 1820- ja 1830-luvulla (_Wiburgs Wochenblatt_ kattaa vuodet 1823-1832). Jos tarkastellaan vuosien 1771-1910 sanomalehtien kokonaismäärää, suomeksi julkaistiin 1 063 648 sivua, ruotsiksi 892 191 sivua, venäjäksi 8 997 sivua ja saksaksi 2 551 sivua.

Aikakauslehtien kohdalla kielivalikoima on vaihtelevampi. Vuosilta 1771-1910 sivuja on lähes 1 147 791, joista 605 762 on suomeksi, 479 462 ruotsiksi ja muu aineisto on joko monikielistä tai jollakin muulla kielellä.

## Datan saatavuus ja rajoitukset

Digitoitujen sanoma- ja aikakauslehtien kokoelmaa voi avoimesti selata, ja siihen voi tehdä hakuja Kansalliskirjaston kotisivulla osoitteessa [https://digi.kansalliskirjasto.fi/](https://digi.kansalliskirjasto.fi/).

Seuraavat aineistopaketit ovat tutkimuskäyttöä varten:

1. _The Newspaper and Periodical OCR Corpus of the National Library of Finland (1771-1874)_ julkaistiin vuonna 2011. Datadump on ladattavissa METS/ALTO-muodossa Kielipankin kautta osoitteesta [http://urn.fi/urn:nbn:fi:lb-2015051201](http://urn.fi/urn:nbn:fi:lb-2015051201). Aineiston käyttöoikeudet on määritelty Creative Commons (CC BY 4.0).
2. Vuosien 1771-1910 datadump on saatu Kansalliskirjastosta _Computational History and the Transformation of Public Discourse in Finland, 1640-1910_ (COMHIS) -projektin käyttöön, ja se on myös _Oceanic Exchanges_ -hankkeen käytössä. Sen käyttöoikeudet on määritelty samoin kuin vuosien 1771-1874 aineiston. COMHIS-projektissa tutkimme tekstin uudelleenkäyttöä suomalaisessa sanoma- ja aikakauslehdistössä vuosina 1771-1910. Tämän projektin tulokset ovat selattavissa osoitteessa [http://comhis.fi/clusters](http://comhis.fi/clusters).
3. _The Newspaper and Periodical OCR Corpus of the National Library of Finland (1875-1920)_ julkaistiin marraskuussa 2017. Datadump on ladattavissa Kielipankin kautta osoitteesta [http://urn.fi/urn:nbn:fi:lb-201801191](http://urn.fi/urn:nbn:fi:lb-201801191). Datadump sisältää kaikki ne sanoma- ja aikakauslehdet, jotka oli digitoituna vuoden 2013 loppuun mennessä. Sanomalehtien osalta kokoelma on kattava, mutta aikakauslehtiä on digitoitu lisää vuoden 2013 jälkeen. Tämä uusin aineisto löytyy Kansalliskirjaston digikokoelmasta, mutta ei vielä datadumpista. Aineiston käyttöoikeuksista (CLARIN ACA end-user license +NC 1.0) löytyy lisätietoja osoitteesta [https://www.kielipankki.fi/lic/digilib-1920-dl/](https://www.kielipankki.fi/lic/digilib-1920-dl/).

## Metadatan rakenne

Kansalliskirjasto on digitoinut sanoma- ja aikakauslehtien kokoelmaa noin miljoonan sivun vuosivauhtia. Vuosittain aineisto on parantunut, ja uusia versioita ja uusia ominaisuuksia on tarjottu tutkimuskäyttöön.

Kansalliskirjaston aineisto sisältää metadatan, sivudatan ja tiedostodatan, joka kertoo arkiston hakemistorakenteen. Historiallisen sanomalehtiarkiston online-palvelu tarjoaa sivunäkymän kuvana sekä pääsyn sivujen sisältötietoihin ALTO XML-muodossa (Analyzed Layout and Text Object).

Kaikki sivut ovat kahdessa erillisessä hakemistossa, joista toinen pohjautuu ISSN-numeroon, toinen julkaisuvuoteen. Julkaisuvuoden alta löytyy julkaisun kieli, minkä alla ovat varsinaiset ALTO XML -tiedostot. Ne on nimetty seuraavasti: ISSN_YEAR_DATE_ISSUE_PAGE.

### Metadata 1771-1874
Kokoelman 1771-1874 metatiedot sisältävät tietoa muun muassa sanomalehtiartikkeleista ja muista sisäisistä segmenteistä. Datadump sisältää ALTO-tiedostot ja metatiedot METS-muodossa. Tässä esimerkki metadatasta: 

```xml
<dmdSec ID="MODSMD_CHAP2">
	<mdWrap MIMETYPE="text/xml" MDTYPE="MODS" LABEL="Bibliographic meta-data of chapter 0">
		<xmlData>
			<MODS:mods>
				<MODS:titleInfo ID="MODSMD_CHAP2_TI2" xml:lang="fi">
					<MODS:title>Minkätähden Hüneburg ei antautunut.</MODS:title>
				</MODS:titleInfo>
				<MODS:name ID="MODSMD_CHAP2_N2" type="personal">
					<MODS:namePart type="given">A.</MODS:namePart>
					<MODS:namePart type="family">G</MODS:namePart>
					<MODS:role>
						<MODS:roleTerm>aut</MODS:roleTerm>
					</MODS:role>
				</MODS:name>
				<MODS:language>
					<MODS:languageTerm type="code" authority="rfc3066">fi</MODS:languageTerm>
				</MODS:language>
			</MODS:mods>
		</xmlData>
	</mdWrap>
</dmdSec>
```

### Metadata 1771-1910

Vuosien 1771-1910 datadump sisältää ALTO-tiedostot. Metatiedot löytyvät tiedostojen alusta XML-muodossa. Tässä esimerkki: 

```xml
<metadata>
	<title>Kirkollinen kuukauslehti : uskonnollista lukemista perheille</title>
	<identifier type="nbn">fk00873</identifier>
	<published format="edtf">1881-11</published>
	<issue>11</issue>
		<pageOrder>21</pageOrder>
		<pageLabel></pageLabel>
	<language>fin</language>
	<contentType>serial</contentType>
	<originalPublisher/>
	<latestPublisher>[s.n.]</latestPublisher>
		<publishingPlace country="fi"></publishingPlace>
	<copyright>Copyrights expired</copyright>
	<license>ESIVERSIO - EI EDELLEENJAKELUUN</license>
		<pageIdentifier>7687234</pageIdentifier>
		<bindingIdentifier>984738</bindingIdentifier>
	<imageURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/image/21</imageURL>
	<pdfURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/pdf</pdfURL>
	<browseURL>http://digi.kansalliskirjasto.fi/aikakausi/binding/984738/#?page=21</browseURL>
	<pingURL/>
	<ocrVersion/>
	<lastModified>2012-04-12T00:04:00</lastModified>
</metadata>
```

### Metadata 1875-1920

Kokoelman 1875-1920 metatiedot noudattavat ALTO/METS-standardia. Tässä esimerkki metadatasta:

```xml
<mets xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://www.loc.gov/METS/" xsi:schemaLocation="http://www.loc.gov/METS/ //Themis/docworks/docWORKS/schema/mets-metae.xsd" xmlns:MODS="http://www.loc.gov/mods/v3" xmlns:mix="http://www.loc.gov/mix/" xmlns:xlink="http://www.w3.org/TR/xlink" TYPE="METAe_Serial" LABEL="Finsk Tidskrift no. 1-2 01.1911">
	<metsHdr CREATEDATE="2007-03-27T10:35:59" LASTMODDATE="2007-03-27T10:35:59">
		<agent ROLE="CREATOR" TYPE="OTHER" OTHERTYPE="SOFTWARE">
			<name>CCS docWORKS/METAe Version 6.0-8</name>
		</agent>
	</metsHdr>
<dmdSec ID="MODSMD_PRINT">
	<mdWrap MIMETYPE="text/xml" MDTYPE="MODS" LABEL="Bibliographic meta-data of the printed version">
		<xmlData>
			<MODS:mods>
				<MODS:titleInfo ID="MODSMD_PRINT_TI1" xml:lang="sv">
					<MODS:title>Finsk Tidskrift</MODS:title>
					<MODS:partName>70-71</MODS:partName>
				</MODS:titleInfo>
				<MODS:language>
					<MODS:languageTerm type="code" authority="rfc3066">sv</MODS:languageTerm>
				</MODS:language>
				<MODS:originInfo>
					<MODS:dateIssued encoding="w3cdtf" keyDate="yes" qualifier="approximate">1911</MODS:dateIssued>
				</MODS:originInfo>
				<MODS:identifier type="ISSN">0015-248X</MODS:identifier>
			</MODS:mods>
		</xmlData>
	</mdWrap>
</dmdSec>
```

## Kokoelman historia

Suomessa kulttuuriperinnön digitointi alkoi 1990-luvun puolivälissä. Sanomalehtikokoelman kannalta olennainen käännekohta oli pohjoismaisen TIDEN-projektin käynnistyminen vuonna 1998. Se oli neljän instituution yhteishanke: mukana olivat Ruotsin kuninkaallinen kirjasto, Norjan kansalliskirjasto, Århusin yliopiston kirjasto (Tanska) ja Helsingin yliopiston kirjasto, joka oli hankkeen koordinaattori. Helsingin yliopiston kirjasto oli jo vuonna 1990 perustanut Mikkeliin digitointi- ja konservointikeskuksen, ja tavoitteena oli luoda suomalaisen sanoma- ja aikakauslehdistön kattava mikrofilmikokoelma. Pian kävi kuitenkin ilmeiseksi, että digitointi olisi hedelmällisempi tapa kehittää tutkimuksen infrastruktuuria. TIDEN-projekti antoi mahdollisuuden tutkia nimenomaan digitoinnin kysymyksiä sekä tuottaa digitaalisia kopioita aiemmin tuotettujen mikrofilmikopioiden pohjalta. Tänään Mikkelin toimipiste on osa Kansalliskirjastoa.

Vuonna 2001 Kansalliskirjasto avasi digitaalisten lehtien kokoelman osoitteessa [http://digi.lib.helsinki.fi](http://digi.lib.helsinki.fi). Samalla ilmoitettiin, että kaikki suomalaiset sanomalehdet vuodesta 1771 vuoteen 1860 digitoidaan ja saatetaan avoimiksi verkon kautta. Kokoelman laajuudeksi ilmoitettiin 44 nimikettä, yhteensä 90 000 sivua. Kun sivusto avattiin vuonna 2001, vasta kolmannes, noin 36 000 sivua, oli valmiina. Nyt, 17 vuotta myöhemmin, avoin kokoelma sisältää kaikki sanoma- ja aikakauslehdet vuosilta 1771-1929.

TIDEN-projekti rakensi pohjaa tulevien digitointiprojektien parhaille käytännöille. Sen keskeiset havainnot julkaistiin yhdessä The International Federation of Library Associations and Institutions (IFLA) -järjestön suositusten kanssa julkaisussa _Guidance on the Best Practices for Microfilming of Newspapers in Preparation for Possible Future Digitisation (2003)_. Suomen digitoitu kokoelma perustuu mikrofilmeihin ja siksi sekä alkuperäisen lehden laatu että filmauksen taso ovat olennaisia. Nykyistä kokoelmaa arvioitaessa tämä on syytä ottaa huomioon: se vaikuttaa siihen, miksi optisen tekstintunnistuksen laatu vaihtelee vuosikymmenittäin.

## <a name="sources"></a>Sources / Lähteet

Bremer-Laamanen, Majlis: Connecting to the past - newspaper digitisation in the Nordic Countries. _International Newspaper Librarianship for the 21st Century_. Ed. Hartmut Walravens. IFLA Publications Series 118. Munich: K.G. Saur, 2006, 45-50.

Ilva, Jyrki: Kansallisen kulttuuriperinnön digitointi - loppuuko vauhti ennen alkua? _Agricolan tietosanomat_ 2/2004.

Kettunen, Kimmo & Tuula Pääkkönen & Mika Koistinen: Between Diachrony and Synchrony: Evaluation of Lexical Quality of a Digitized Historical Finnish Newspaper and Journal Collection with Morphological Analyzers.
[Conference paper](https://www.researchgate.net/publication/307904574_Between_Diachrony_and_Synchrony_Evaluation_of_Lexical_Quality_of_a_Digitized_Historical_Finnish_Newspaper_and_Journal_Collection_with_Morphological_Analyzers).

National Library of Finland (2011). _The Newspaper and Periodical OCR Corpus of the National Library of Finland (1771-1874)_ [text corpus]. [Kielipankki](http://urn.fi/urn:nbn:fi:lb-2015051201).

National Library of Finland (2017). _The Newspaper and Periodical OCR Corpus of the National Library of Finland (1875-1920)_ [text corpus]. [Kielipankki](http://urn.fi/urn:nbn:fi:lb-201801191).

Onnela, Tapio: Historiallinen sanomalehtikirjasto 1771-1860. _Agricolan tietosanomat_ 2/2001.

Pääkkönen, Tuula, Jukka Kervinen, Asko Nivala, Kimmo Kettunen and Eetu Mäkelä: Exporting Finnish Digitized Historical Newspaper Contents for Offline Use. [Conference paper](https://www.academia.edu/27807323/Exporting_Finnish_Digitized_Historical_Newspaper_Contents_for_Offline_Use).

Vesanto, Aleksi, Asko Nivala, Heli Rantala, Tapio Salakoski, Hannu Salmi and Filip Ginter, ’Applying BLAST to Text Reuse Detection in Finnish Newspapers and Journals, 1771-1910’, _Proceedings of the 21st Nordic Conference of Computational Linguistics_. Gothenburg, Sweden, 23-24 May 2017 (Linköping 2017): 54-58, [http://www.ep.liu.se/ecp/133/010/ecp17133010.pdf](http://www.ep.liu.se/ecp/133/010/ecp17133010.pdf)

Vesanto, Aleksi, Asko Nivala, Tapio Salakoski, Hannu Salmi ja Filip Ginter, ’A System for Identifying and Exploring Text Repetition in Large Historical Document Corpora’, _Proceedings of the 21st Nordic Conference of Computational Linguistics_. Gothenburg, Sweden, 23-24 May 2017 (Linköping 2017): 330-333, [http://www.ep.liu.se/ecp/131/049/ecp17131049.pdf](http://www.ep.liu.se/ecp/131/049/ecp17131049.pdf)
