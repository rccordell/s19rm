---
layout: post
title: British Library 19th-Century Newspapers
tags: [dh, DiD, data reports]
author: mhbeals, pfyfe
---
 
Building upon [previous projects](#Related), *Oceanic Exchanges* is using approximately 3 million pages of nineteenth-century newspapers from the British Library to better understand the structure of digitised newspaper collections and the spread of texts and ideas across global information networks. Although the British Library’s physical collections of historical newspapers are far more extensive, these newspapers were selected for digitisation to provide a representative sample of the wider collection, covering the metropolitan and provincial press, ranging in political and geographical coverage, and representing both English- and Welsh-language titles. The library has and continues to grow its digital newspaper collections in stages; OcEx uses XML data from the first two of these stages, known as “[Part I](https://www.gale.com/c/british-library-newspapers-part-i)” and “[Part II](https://www.gale.com/c/british-library-newspapers-part-ii)”.

## History of the Collection

The British Library’s initial efforts to digitise its newspaper collections in the 2000s were funded by a series of grants from the United Kingdom’s Joint Information Systems Committee (JISC). The proposed “British Newspapers 1800-1900” project had an initial target of making 2 million pages available and broadly useful to scholars, researchers, and the public. Because of constraints of budget and available technology, newspapers were not directly scanned to digital files. Instead, new microfilms were made of the newspapers and these films were subsequently scanned. The British Library partnered with commercial vendors to process the scanned images, separate articles into page zones, conduct optical character recognition (OCR) on the text, impose a metadata scheme, and build a searchable database for the collection. These partners included Gale Cengage and later Brightsolid, who continues to expand the collection as the British Newspaper Archive. More information on the library's digitisation projects can be found [here](http://www.bl.uk/reshelp/findhelprestype/news/newspdigproj/index.html).

## Composition

The British Library’s digitised newspaper collections contains 69 distinct publications. Of these, 21 were produced in London, 33 in England outside London, 5 in Scotland, 5 in Wales, and 2 in Ireland. Many of the titles published in Scotland, Wales, and Ireland are primarily held by their respective national libraries, which have pursued separate digitisation projects. The Library aimed to provide the full date range of each selected title to the extent allowable by physical collection and within the project criteria (1800-1900). Thus, titles such as the *Glasgow Herald*, which began publication in 1783 and continues today, was only digitised from 1820-1900, or from the first issue held by the British Library until the project cut-off date. Although the entire collection covers the period from 1800 to 1900, the number of titles increases substantially as the century progresses.

## Data and Metadata
The data for the digitised newspapers comes in two forms: a scanned image of each newspaper page and an XML file containing the text and metadata from each issue. The BL obtained the text of these newspapers through optical character recognition (OCR) -- an automatic process that translates an image of text into machine-readable characters. Of course, the OCR process is hardly perfect; it sometimes struggles with non-standard fonts, broken or light print, poor quality scans, skewed pages, complex typographical layouts, advertisements, tables, and more. The overall OCR quality of BL1 and BL2 collections is approximately 60-85% but varies widely within and between titles. The machine-readable text appears within the XML file, surrounded by metadata that describes various features about the page, including the title, date, section, article, and page number. With the help of its team of scholar advisors and commercial partners, JISC and the BL established a standard metadata schema to label information consistently across different newspapers and collections. The metadata itself was created partly through automatic processes and partly by contract workers.

Owing to the joint nature of the digitisation project, the machine-readable data and metadata for the BL collections currently exists in multiple forms. The version most readily accessible to individual researchers can be obtained from Gale. Each XML file contains information for a single article, or textual unit, within the collection. Within a holding element, it contains the following metadata tree:

+ Standardised identifier
+ Newspaper title
+ Standardised title abbreviation
+ Project codes
+ Digitized collection name
+ Issue number
+ Date as printed
+ Standardised date (Month, DD, YYYY)
+ Standardised date (YYYYMMDD)
+ Day of the week
+ Number of Pages
+ Copyright holder
+ Language
+ Unique ID for publication
+ Holding Library
+ Citation of the physical item
    + Title metadata
        + Title as recorded in the MARC Library Catalogue
    + Dates of publication
    + Genre, such as newspaper
    + Conversion credit, usually a vendor
+ Article
    + Unique ID
    + OCR quality
    + SC, or standardized category of article
    + Unique ID(s) of page(s)
    + Unique ID(s) of individual column(s)
    + Column number
    + Headline
    + Article type

This is followed by the machine-readable text, in which each individual word is encoded with spatial coordinates of its location on the corresponding image, as well as marker elements indicating new pages or columns.

A second, pre-processed version of the data is also held by British Library Labs and has been used by BL Labs Competition winners and award recipients in supported projects. This version of the XML is encoded at page rather than issue or article level. Within a holding element, it contains the following tree

+ Title Metadata
  + Title, as written
  + Normalised title across all variants
  + Standardised title abbreviation
  + Variant titles, with associated dates
  + Place of publication
  + Dates of publication
  + Genre, such as newspaper
  + Sub-collection, such as Regional Daily

+ Issue Metadata
    + Volume Number
    + Issue Number
    + Date as printed
    + Normalised date (YYYY.MM.DD)
    + Number of pages
    + The microfilm reel number
    + The OCR quality

+ Page image data
    + The number of the image within that issue
    + The filename
    + The spatial coordinates for the page within the image
    + The degree of page skew

As with the Gale version, each word is encoded with the spatial coordinates. As it is encoded at page level, it does not contain the marker elements for page or column breaks. This provides a possibly more researcher-friendly variant of the XML, with human-readable element names and an intuitive nesting of elements, but lacks any form of delimitation between articles, which can be found in the GALE version.

## Access and Use

In the United Kingdom, the BL1 and BL2 digitized newspapers collections can be freely accessed within the British Library reading rooms as well as remotely through Gale and British Library interfaces provided to all UK Higher Education Institutions (and some others) via JISC agreements. The underlying data can be accessed by request and a cost recovery fee by subscribing institutions. Elsewhere, the BL1 and BL2 digitised newspapers are accessible only through institutional subscriptions to Gale’s products, with the same provision for requesting source files.

While OcEx cannot share the source data provide by Gale and the British Library, it can share its derivatives, analyses, and visualizations of this data as approved transformational uses, according to current copyright law. Small quotations and downsampled page images can also be shared under academic fair use provisions.

<a name="Related"></a>
## Related Projects
+ Beals, M. H. [*Scissors and Paste*](http://www.scissorsandpaste.net) 
+ Cordell, Ryan. [*Viral Texts*](http://www.viraltexts.org)
+ Fyfe, Paul. [“An Archaeology of Victorian  Newspapers” *Victorian Periodicals Review* 49:4 (2016): 546-577](https://repository.lib.ncsu.edu/bitstream/handle/1840.20/33457/fyfe.newspaper.archaeology.VPR.pdf?sequence=1)
