Awesome OCR
===========

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list contains links to great software tools and libraries and literature
related to [Optical Character Recognition
(OCR)](http://en.wikipedia.org/wiki/Optical_Character_Recognition).

Contributions are welcome, as is feedback.

<!-- BEGIN-MARKDOWN-TOC -->
* [Software](#software)
	* [OCR engines](#ocr-engines)
	* [Older and possibly abandoned OCR engines](#older-and-possibly-abandoned-ocr-engines)
	* [OCR file formats](#ocr-file-formats)
		* [hOCR](#hocr)
		* [ALTO XML](#alto-xml)
		* [TEI](#tei)
		* [PAGE XML](#page-xml)
	* [OCR CLI](#ocr-cli)
	* [OCR GUI](#ocr-gui)
	* [OCR Preprocessing](#ocr-preprocessing)
	* [OCR as a Service](#ocr-as-a-service)
	* [OCR evaluation](#ocr-evaluation)
	* [OCR libraries by programming language](#ocr-libraries-by-programming-language)
		* [Go](#go)
		* [Java](#java)
		* [.Net](#net)
		* [Object Pascal](#object-pascal)
		* [PHP](#php)
		* [Python](#python)
		* [Javascript](#javascript)
		* [Ruby](#ruby)
		* [Swift](#swift)
		* [Rust](#rust)
		* [R](#r)
	* [OCR training tools](#ocr-training-tools)
* [Datasets](#datasets)
	* [Ground Truth](#ground-truth)
* [Literature](#literature)
	* [OCR-related publication and link lists](#ocr-related-publication-and-link-lists)
	* [Blog Posts and Tutorials](#blog-posts-and-tutorials)
	* [OCR Showcases](#ocr-showcases)
	* [Academic articles](#academic-articles)
		* [2011 and before](#2011-and-before)
		* [2012](#2012)
		* [2013](#2013)
		* [2014](#2014)
		* [2015](#2015)
		* [2016](#2016)
		* [2017](#2017)
		* [2018](#2018)

<!-- END-MARKDOWN-TOC -->

## Software

### OCR engines

* [tesseract](https://github.com/tesseract-ocr/tesseract) - The definitive Open Source OCR engine `Apache 2.0`
* [ocropus](https://github.com/tmbdev/ocropy) - OCR engine based on LSTM, `Apache 2.0`
* [ocropus 0.4](https://github.com/jkrall/ocropus) - Older v0.4 state of Ocropus, with tesseract 2.04 and iulib, C++
* [kraken](https://github.com/mittagessen/kraken) - Ocropus fork with sane defaults
* [Ocrad](http://www.gnu.org/software/ocrad/) - The GNU OCR. `GPL`
* [digit](https://github.com/SHUCV/digit) - OCR for numbers in meter displays, such as a power meter, using [caffe](http://caffe.berkeleyvision.org/)
* [ocular](https://github.com/tberg12/ocular) - Machine-learning OCR for historic documents
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - fast and simple OCR library written in Swift
* [attention-ocr](https://github.com/emedvedev/attention-ocr) - OCR engine using visual attention mechanisms
* [RWTH-OCR](https://www-i6.informatik.rwth-aachen.de/rwth-ocr/) - The RWTH Aachen University Optical Character Recognition System
* [simple-ocr-opencv](https://github.com/goncalopp/simple-ocr-opencv) and its [fork](https://github.com/RedFantom/simple-ocr-opencv) - A simple pythonic OCR engine using opencv and numpy
* [Calamari](https://github.com/Calamari-OCR/calamari) - OCR Engine based on OCRopy and Kraken

### Older and possibly abandoned OCR engines

* [Clara OCR](http://freecode.com/projects/claraocr/) - Open source OCR in C `GPL`
* [Cuneiform](https://en.wikipedia.org/wiki/CuneiForm_(software)) - CuneiForm OCR was developed by Cognitive Technologies
* [Eye](https://sourceforge.net/projects/eyeocr/) - an experimental Java OCR (image-to-text) application
* [kognition](https://sourceforge.net/projects/kognition/) - An omnifont OCR software for KDE
* [OCRchie](https://people.eecs.berkeley.edu/~fateman/kathey/ocrchie.html) - Modular Optical Character Recognition Software
* [ocre](http://lem.eui.upm.es/ocre.html) - o.c.r. easy
* [xplab](http://www.pattern-lab.de/) - A GTK 2 tool for pattern matching
* [hebOCR](https://github.com/yaacov/hebocr) - Hebrew character recognition library (previously named hocr, see [Wikipedia article](https://de.wikipedia.org/wiki/HebOCR)) `GPL`

### OCR file formats

* [abby2hocr.xslt XSLT script](https://gist.github.com/tfmorris/5977784)
* [ocr-conversion-scripts](https://github.com/cneud/ocr-conversion-scripts)

#### hOCR

* [hocr-tools](https://github.com/tmbdev/hocr-tools) - Tools for doing various useful things with hOCR files, `Apache 2.0`
* [hocr-spec](https://github.com/kba/hocr-spec) - hOCR 1.2 specification
* [ocr-transform](https://github.com/UB-Mannheim/ocr-transform) - CLI tool to convert between hOCR and ALTO, `MIT`
* [hocr-parser](https://github.com/athento/hocr-parser) - hOCR Specification Python Parser
* [hOCRTools](https://github.com/ONB-RD/hOCRTools) - hOCR to ALTO conversion XSLT

#### ALTO XML

* [ALTO XML Schema](https://github.com/altoxml/schema) - XML Schema and development of the ALTO XML format
* [ALTO XML Documentation](https://github.com/altoxml/documentation) - Documentation and use cases for ALTO
* [alto-tools](https://github.com/cneud/alto-tools) - Various tools to work with ALTO files, Python
* [AbbyyToAlto](https://github.com/ironymark/AbbyyToAlto) - PHP script converting from Abbyy 6 to ALTO XML

#### TEI

* [TEI-OCR](https://github.com/OpenPhilology/tei-ocr) - TEI customization for OCR generated layout and content information
* [TEI SIG on Libraries](http://www.tei-c.org/SIG/Libraries/teiinlibraries/main-driver.html) - Best Practices for TEI in Libraries
* [GDZ](http://gdz.sub.uni-goettingen.de/uploads/media/GDZ_document_format_2005_12_08.pdf) - METS/TEI-based GDZ document format

#### PAGE XML

* [PAGE-XML Schema](https://github.com/PRImA-Research-Lab/PAGE-XML/tree/master/pagecontent) - XML schema of the PAGE XML format along with documentation and examples

### OCR CLI

* [OCRmyPDF](https://github.com/jbarlow83/OCRmyPDF) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them to be searched
* [Pdf2PdfOCR](https://github.com/LeoFCardoso/pdf2pdfocr) - A tool to OCR a PDF (or supported images) and add a text "layer" (a "pdf sandwich") in the original file making it a searchable PDF. GUI included. Tesseract and cuneiform supported.
* [Ocrocis](https://github.com/kaumanns/ocrocis) - Project manager interface for Ocropy, see also [external project homepage](http://cistern.cis.lmu.de/ocrocis/)

### OCR GUI

* [moz-hocr-editor](https://github.com/garrison/moz-hocr-edit) - Firefox Addon for editing hOCR files **Discontinued**
* [qt-box-editor](https://github.com/zdenop/qt-box-editor) - QT4 editor of tesseract-ocr box files.
* [ocr-gt-tools](https://github.com/UB-Mannheim/ocr-gt-tools) - Client-Server application for editing OCR ground truth.
* [Paperwork](https://github.com/openpaperwork/paperwork) - Using scanners and OCR to grep paper documents the easy way.
* [Paperless](https://github.com/danielquinn/paperless) - Scan, index, and archive all of your paper documents.
* [gImageReader](https://github.com/manisandro/gImageReader) - gImageReader is a simple Gtk/Qt front-end to tesseract-ocr.
* [VietOCR](http://vietocr.sourceforge.net/) - A Java/.NET GUI frontend for Tesseract OCR engine, including [jTessBoxEditor](http://vietocr.sourceforge.net/training.html) a graphical Tesseract [box data](https://github.com/tesseract-ocr/tesseract/wiki/Make-Box-Files) editor
* [PoCoTo](https://github.com/cisocrgroup/PoCoTo) - Fast interactive batch corrections of complete OCR error series in OCR'ed historical documents.
* [OCRFeeder](https://wiki.gnome.org/Apps/OCRFeeder) - GTK graphical user interface that allows the users to correct characters or bounding boxes, ODT export and more.
* [PRImA PAGE Viewer](https://github.com/PRImA-Research-Lab/prima-page-viewer) - Java based viewer for PAGE XML files (layout + text content). Also supports ALTO XML, FineReader XML, and HOCR.
* [LAREX](https://github.com/chreul/larex) - A semi-automatic open-source tool for Layout Analysis and Region EXtraction on early printed books. 
* [archiscribe](https://github.com/jbaiter/archiscribe) - Web application for transcribing OCR ground truth from Archive.org. Deployed instance available at https://archiscribe.jbaiter.de/, results are available in [@jbaiter/archiscribe-corpus](https://github.com/jbaiter/archiscribe-corpus).

### OCR Preprocessing

* [NoiseRemove.java in MathOCR](https://github.com/chungkwong/MathOCR/blob/master/src/main/java/com/github/chungkwong/mathocr/preprocess/NoiseRemove.java) - Java implementation of Adaptive degraded document image binarization by B. Gatos , I. Pratikakis, S.J. Perantonis
* [binarize.c in ZBar](https://github.com/ZBar/ZBar/blob/master/zbar/qrcode/binarize.c) - C implementations of two binarization algorithms, based on Sauvola
* [typeface-corpus](https://github.com/jbest/typeface-corpus) - A repository for typefaces to train Tesseract and OCRopus for natural history collections and digital humanities.
* [binarizewolfjolion](https://github.com/zp-j/binarizewolfjolion) - Comparison of binarization algorithms. [Blog post](http://zp-j.github.io/2013/10/04/document-binarization/)
* [`crop_morphology.py` in oldnyc](https://github.com/danvk/oldnyc) - Cropping a page to just the text block
* [Whiteboard Picture Cleaner](https://gist.github.com/lelandbatey/8677901) - Shell one-liner/script to clean up and beautify photos of whiteboards
* Fred's ImageMagick script [textcleaner](http://www.fmwconcepts.com/imagemagick/textcleaner/index.php) - Processes a scanned document of text to clean the text background
* [localcontrast](https://sourceforge.net/projects/localcontrast/) - Fast O(1) local contrast optimization


### OCR as a Service

* [Open OCR](https://github.com/tleyden/open-ocr) - Run Tesseract in Docker containers
* [tesseract-web-service](https://github.com/guitarmind/tesseract-web-service) - An implementation of RESTful web service for tesseract-OCR using tornado.
* [docker-ocropy](https://github.com/kba/docker-ocropy) - A Docker container for running the [ocropy OCR system](htps://github.com/tmbdev/ocropy).
* [ABBYY Cloud OCR SDK Code samples](https://github.com/abbyysdk/ocrsdk.com) - Code samples for using the proprietary commercial ABBYY OCR API.
* [nidaba](https://github.com/OpenPhilology/nidaba) -  An expandable and scalable OCR pipeline
* [gamera](https://github.com/hsnr-gamera/gamera) - A meta-framework for building document processing applications, e.g. OCR
* [ocr-tools](https://github.com/subugoe/ocr-tools) - Project to provide CLI and web service interfaces to common OCR engines
* [ocrad-docker](https://github.com/kba/ocrad-docker) - Run the [ocrad](http://www.gnu.org/software/ocrad/) OCR engine in a docker container
* [kraken-docker](https://github.com/kba/kraken-docker) - Run the [kraken](https://github.com/mittagessen/kraken) OCR engine in a docker container
* [ocr.space](https://ocr.space/) - Free Online OCR and OCR API by [@a9t9](https://github.com/A9T9) based on Tesseract (code is not open)

### OCR evaluation

* [ISRI OCR Evaluation Tools](https://code.google.com/archive/p/isri-ocr-evaluation-tools/) with a [User Guide from 1996 :!:](https://github.com/eddieantonio/isri-ocr-evaluation-tools/blob/HEAD/user-guide.pdf)
  * [isri-ocr-evaluation-tools](https://github.com/eddieantonio/isri-ocr-evaluation-tools) - further development by [@eddieantonio](https://github.com/eddieantonio) (2015, 2016)
  * [ancientgreekocr-evaluation-tools](https://github.com/ryanfb/ancientgreekocr-ocr-evaluation-tools) - further development by [@nickjwhite](https://github.com/nickjwhite) (2013, 2014)
* [ocrevalUAtion](https://github.com/impactcentre/ocrevalUAtion) - Cross-format evaluation, CLI and GUI
* [ngram-ocr-eval](https://github.com/impactcentre/hackathon2014/tree/master/ngram-ocr-eval) - Brute and simple OCR evaluation using ngrams
* [quack](https://github.com/tokee/quack) - Quality-Assurance-tool for scans with corresponding ALTO-files

### OCR libraries by programming language

#### Go

* [gosseract](https://github.com/otiai10/gosseract) - Golang OCR library, wrapping Tesseract-ocr.

#### Java

* [Tess4J](https://github.com/nguyenq/tess4j) - Java Native Access bindings to Tesseract.
* [tess-two](https://github.com/rmtheis/tess-two) - Tools for compiling Tesseract on Android and Java API.

#### .Net

* [tesseract for .net](https://github.com/charlesw/tesseract) - A .Net wrapper for tesseract-ocr.

#### Object Pascal

* [TTesseractOCR4](https://github.com/r1me/TTesseractOCR4) - Object Pascal binding for tesseract-ocr 4.x.

#### PHP

* [Tesseract OCR for PHP](https://github.com/thiagoalessio/tesseract-ocr-for-php) - Tesseract PHP bindings.

#### Python

* [pytesseract](https://github.com/madmaze/pytesseract) - A Python wrapper for Google Tesseract.
* [pyocr](https://github.com/jflesch/pyocr) - A Python wrapper for Tesseract and Cuneiform.
* [ocrodjvu](https://github.com/jwilk/ocrodjvu) - A library and standalone tool for doing OCR on DjVu documents, wrapping Cuneiform, gocr, ocrad, ocropus and tesseract
* [tesserocr](https://github.com/sirfz/tesserocr) - A Python wrapper for the tesseract-ocr API

#### Javascript

* [ocracy](https://github.com/naptha/ocracy) - pure javascript lstm rnn implementation based on ocropus
* [gocr.js](https://github.com/antimatter15/gocr.js) - Javascript port (emscripten) of gocr
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - Javascript port (emscripten) of ocrad
* [tesseract.js](https://github.com/naptha/tesseract.js) - Javascript port (emscripten) of Tesseract
* [node-tesseract-ocr](https://github.com/zapolnoch/node-tesseract-ocr) - A simple wrapper for the Tesseract OCR package.
* [node-tesseract-native](https://github.com/mdelete/node-tesseract-native) - C++ module for node providing OCR with tesseract and leptonica.

#### Ruby

* [rtesseract](https://github.com/dannnylo/rtesseract) - Ruby library wrapping the tesseract and imagemagick executables.
* [ruby-tesseract](https://github.com/meh/ruby-tesseract-ocr) - Native Tesseract bindings for Ruby MRI and JRuby
* [ocr_space](https://github.com/suyesh/ocr_space) - API wrapper for free ocr service ocr.space. Includes CLI

#### Rust

* [tesseract.rs](https://github.com/antimatter15/tesseract-rs) - Rust bindings for tesseract OCR.
* [leptess](https://crates.io/crates/leptess) - Productive and safe Rust bindings/wrappers for tesseract and leptonica.

#### R

* [tesseract](https://github.com/ropensci/tesseract) - R bindings for tesseract OCR.

#### Swift

* [Tesseract OCR iOS](https://github.com/gali8/Tesseract-OCR-iOS) - Swift and Objective-C wrapper for Tesseract OCR.
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift. Optimized for recognizing short, one line long alphanumeric codes.

### OCR training tools

* [glyph-miner](https://github.com/benedikt-budig/glyph-miner) - A system for extracting glyphs from early typeset prints
* [ocrodeg](https://github.com/NVlabs/ocrodeg) - Document image degradation for OCR data augmentation

## Datasets

### Ground Truth

* [archiscribe-corpus](https://github.com/jbaiter/archiscribe-corpus) - >4,200 lines transcribed from 19th Century German prints via [archiscribe](https://archiscribe.jbaiter.de/) `CC-BY 4.0`
* [CIS OCR Test Set](https://github.com/cisocrgroup/Resources/tree/master/ocrtestset) - 2 example documents each in German/Latin/Greek with ground truth for [PoCoTo](https://github.com/cisocrgroup/PoCoTo)
- [Rescribe](https://github.com/rescribe/carolineminuscule-groundtruth) - Transcriptions of Caroline Minuscule Manuscripts `PDM 1.0`
* [CLTK](https://github.com/cltk) - Corpora from [Classical Language Toolkit](http://cltk.org/) `PDM 1.0`
* [DIVA-HisDB](https://diuf.unifr.ch/main/hisdoc/diva-hisdb) - 150 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> of three medieval manuscripts `CC-BY-NC 3.0`
* [EarlyPrintedBooks](https://github.com/chreul/OCR_Testdata_EarlyPrintedBooks) - ~8,800 lines from several early printed books `CC-BY-NC-SA 4.0`
* [EEBO-TCP](https://github.com/Anterotesis/historical-texts/tree/master/eebo-tcp) - 25,363 EEBO documents transcribed by [TCP](http://www.textcreationpartnership.org/tcp-eebo/) `PDM 1.0`
* [ECCO-TCP](https://github.com/Anterotesis/historical-texts/tree/master/ecco-tcp) - 2,188 ECCO documents transcribed by [TCP](http://www.textcreationpartnership.org/tcp-ecco/) `PDM 1.0`
* [eMOP-TCP](https://github.com/Early-Modern-OCR/TCP-ECCO-texts) - 2,188 ECCO-TCP documents, cleaned up by [eMOP](http://emop.tamu.edu/) `PDM 1.0`
* [Evans-TCP](https://github.com/Anterotesis/historical-texts/tree/master/evans-tcp) - 4,977 Evans documents transcribed by [TCP](http://www.textcreationpartnership.org/tcp-evans/)
* [FDHN](https://digi.kansalliskirjasto.fi/opendata/submit?set_language=en) - Finnish Digitised Historical Newspapers, [Paper](http://doi.org/10.1045/july2016-paakkonen), (free) [registration](https://digi.kansalliskirjasto.fi/opendata/submit?set_language=en) required, [Terms of Use](https://digi.kansalliskirjasto.fi/terms)
* [FROC-MSS](https://github.com/Jean-Baptiste-Camps/FROC-MSS) - 4 Old French Medieval Manuscripts `CC-BY 4.0`
* [GERMANA](https://www.prhlt.upv.es/wp/resource/the-germana-corpus) - 764 Spanish manuscript pages, (free) [registration](https://www.prhlt.upv.es/wp/resource/the-germana-corpus) required `non-commercial use only`
* [GT4HistOCR](https://doi.org/10.5281/zenodo.1344132) - Ground Truth for German Fraktur and Early Modern Latin `CC-BY 4.0`
* [imagessan](https://github.com/Shreeshrii/imagessan/) - Sanskrit images & ground truth (Devanagari script)
* [IMPACT-BHL](http://www.bhle.eu/en/results-of-the-collaboration-of-bhl-europe-and-impact) - 2,418 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the Biodiversity Heritage Library, [XML@GitHub](https://github.com/impactcentre/groundtruth-bhl) `CC-BY 3.0`
* [IMPACT-BL](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=BL&search-filter-language=&search-filter-script=&search-filter-year=) - 294 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the British Library, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required `PDM 1.0`
* [IMPACT-BNE](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=BNE&search-filter-language=&search-filter-script=&search-filter-year=) - 215 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the National Library of Spain, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required, [XML@GitHub](https://github.com/impactcentre/groundtruth-spa) `CC-BY-NC-SA 4.0`
* [IMPACT-BNF](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=BNE&search-filter-language=&search-filter-script=&search-filter-year=) - 151 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the National Library of France, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required `CC-BY-NC-SA 4.0`
* [IMPACT-KB](http://lab.kb.nl/dataset/ground-truth-impact-project#access) - 142 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the National Library of the Netherlands `CC-BY 4.0`
* [IMPACT-NKC](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=NKC&search-filter-language=&search-filter-script=&search-filter-year=) - 187 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the Czech National Library, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required `CC-BY-NC-SA 4.0`
* [IMPACT-NLB](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=NLB&search-filter-language=&search-filter-script=&search-filter-year=) - 19 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the National Library of Bulgaria, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required `CC-BY-NC-ND 4.0`
* [IMPACT-NUK](https://www.digitisation.eu/tools-resources/image-and-ground-truth-resources/impact-dataset-browser/?query=&search-filter-institution=NUK&search-filter-language=&search-filter-script=&search-filter-year=) - 209 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from the National Library of Slovenia, (free) [registration](https://www.digitisation.eu/wp-login.php?action=register) required `CC-BY-NC-SA 4.0`
* [IMPACT-PSNC](http://dl.psnc.pl/activities/projekty/impact/results/) - 478 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> from four Polish digital libraries, [XML@GitHub](https://github.com/impactcentre/groundtruth-pol) `CC-BY 3.0`
* [LascivaRoma/lexical](https://github.com/lascivaroma/lexical) - Transcription of 19th century lexical resources for Latin learning
* [MJSynth](http://www.robots.ox.ac.uk/~vgg/data/text/) - 9m synthetic images covering 90k English words
* [OCR19thSAC](https://files.ifi.uzh.ch/cl/OCR19thSAC/) - 19,000 pages Swiss Alpine Club yearbooks transcribed via [Text+Berg digital](http://textberg.ch/site/en/welcome/) `CC-BY 4.0`
* [OCR-D](http://ocr-d.de/daten) - 180 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> of German historical prints from [OCR-D](http://ocr-d.de/) `CC-BY-SA 4.0`
* [OCR_GS_Data](https://github.com/OpenITI/OCR_GS_Data) - Double-checked Arabic Gold Standard from [OpenITI](https://github.com/OpenITI)
* [old-books](https://github.com/PedroBarcha/old-books-dataset) - 322 old books from [Project Gutenberg](https://www.gutenberg.org/) `GPL 3.0`
* [PRImA-ENP](http://www.primaresearch.org/datasets/ENP) - 528 pages<sup>[PAGE-XML](https://github.com/PRImA-Research-Lab/PAGE-XML)</sup> historic newspapers from [Europeana Newspapers](http://www.europeana-newspapers.eu/), (free) [registration](http://www.primaresearch.org/register) required `PDM 1.0`
* [RODRIGO](https://www.prhlt.upv.es/wp/resource/the-rodrigo-corpus) - 853 Spanish manuscript pages, (free) [registration](https://www.prhlt.upv.es/wp/resource/the-rodrigo-corpus) required `non-commercial use only`
* [Toebler-OCR](https://github.com/PonteIneptique/toebler-ocr) - (Kraken) Ground Truth transcription of few pages of the Tobler-Lommatzsch: Altfranzösisches Wörterbuch

## Literature

### OCR-related publication and link lists

* [IMPACT: Tools for text digitisation](http://www.digitisation.eu/tools-resources/tools-for-text-digitisation/) - List of tools software projects related, some related to OCR
* [OCR-D](https://www.zotero.org/groups/ocr-d) - List of OCR-related academic articles in the context of the [OCR-D](http://www.ocr-d.de/) project. :de:
* [Mendeley Group "OCR - Optical Character Recognition"](https://www.mendeley.com/groups/752871/ocr-optical-character-recognition/) - Collection of 34 papers on OCR
* [eadh.org projects](http://eadh.org/projects) - List of Digital Humanities-related projects in Europe, some related to OCR
* [Wikipedia: Comparison of optical character recognition software](https://en.wikipedia.org/wiki/Comparison_of_optical_character_recognition_software)
* [OCR [and Deep Learning]](http://handong1587.github.io/deep_learning/2015/10/09/ocr.html) by [@handong1587](https://github.com/handong1587/)
* [Ocropus Wiki: Publications](https://github.com/tmbdev/ocropy/wiki/Publications)

### Blog Posts and Tutorials

* [Tesseract Blends Old and New OCR Technology](https://github.com/tesseract-ocr/docs/tree/master/das_tutorial2016) (2016) [@theraysmith](https://github.com/theraysmith)
  * Tutorial@DAS2016, Updated "What You Always Wanted to Know" slides
* [What You Always Wanted To Know About Tesseract](https://drive.google.com/folderview?id=0B7l10Bj_LprhQnpSRkpGMGV2eE0&usp#list) (2014) [@theraysmith](https://github.com/theraysmith)
  * Tutorial@DAS2014, includes demos
* [Extracting text from an image using Ocropus](http://www.danvk.org/2015/01/09/extracting-text-from-an-image-using-ocropus.html) (2015)
* [Training an Ocropus OCR model](http://www.danvk.org/2015/01/11/training-an-ocropus-ocr-model.html) (2015) [@danvk](https://github.com/danvk)
* [Ocropus Wiki: Compute errors and confusions](https://github.com/tmbdev/ocropy/wiki/Compute-errors-and-confusions) (2016) [@zuphilip](https://github.com/zuphilip)
* [Ocropus Wiki: Working with Ground Truth](https://github.com/tmbdev/ocropy/wiki/Compute-errors-and-confusion://github.com/tmbdev/ocropy/wiki/Working-with-Ground-Truth) (2016) [@zuphilip](https://github.com/zuphilip)
* [OCRopus](https://comsys.informatik.uni-kiel.de/lang/de/res/ocropus/) (2016) [@jze](https://github.com/jze)
  * mostly on column separation in ocropus
* [10 Tips for making your OCR project succeed](http://blog.kbresearch.nl/2013/12/12/10-tips-for-making-your-ocr-project-succeed/) (2013) [@cneud](https://github.com/cneud)
  * general things to consider for OCR projects
* [Overview of LEADTOOLS Image Cleanup and Pre-processing SDK Technology](https://www.leadtools.com/sdk/image-processing/document) -
  * feature list for a commercial image pre-processing library; has nice before-after samples for pre-processing steps related to OCR
* [Extracting Text from PDFs; Doing OCR; all within R](https://electricarchaeology.ca/2014/07/15/doing-ocr-within-r/) [@shawngraham](https://github.com/shawngraham)
  * How to work with OCR from PDFs in the [R programming environment](https://www.r-project.org/)
* [Tutorial: Command-line OCR on a Mac](http://benschmidt.org/dighist13/?page_id=129) [@bmschmidt](https://github.com/bmschmidt)
  * Tutorial on how to run tesseract in Mac OSX
* [Practical Expercience with OCRopus Model Training](https://comsys.informatik.uni-kiel.de/lang/de/res/practical-expercience-with-ocropus-model-training/) (2016) [@jze](https://github.com/jze)
* [Homemade Manuscript OCR (1): OCRopy](http://graal.hypotheses.org/786) (2017) [@Jean-Baptiste-Camps](https://github.com/Jean-Baptiste-Camps)
  * Tutorial on applying OCR to medieval manuscripts with OCRopy
* [Optimizing Binarization for OCRopus](https://comsys.informatik.uni-kiel.de/lang/de/res/optimizing-binarization-for-ocropus/) (2017) [@jze](https://github.com/jze)
* [Prototype demo for OCR postfix in Danish Newspapers](https://sbdevel.wordpress.com/2016/11/15/prototype-demo-for-ocr-postfix-in-danish-newspapers/) (2016) [@thomasegense](https://github.com/thomasegense)
* [How Can I OCR My Dictionary?](https://digilex.hypotheses.org/153) (2016) [@JessedeDoes](https://github.com/JessedeDoes)
* ["Needlessly complex" blog](https://mzucker.github.io/) (2016) [@mzucker](https://github.com/mzucker). Several image processing how-tos (Python based), particularly:
  * [Page dewarping](https://mzucker.github.io/2016/08/15/page-dewarping.html) ([code](https://github.com/mzucker/page_dewarp))
  * [Compressing and enhancing hand-written notes](https://mzucker.github.io/2016/09/20/noteshrink.html) ([code](https://github.com/mzucker/noteshrink))
  * [Unprojecting text with ellipses](https://mzucker.github.io/2016/10/11/unprojecting-text-with-ellipses.html) ([code](https://github.com/mzucker/unproject_text))
* [(Open-Source-)OCR-Workflows](https://edoc.bbaw.de/frontdoor/index/index/docId/2786) (2017) [@wrznr](https://github.com/wrznr) :de: overview of the state of the art in open source OCR and related technologies (binarisation, deskewing, layout recognition, etc.), lots of example images and information on the [@OCR-D](https://github.com/OCR-D) project.
* [A gentle introduction to OCR](https://towardsdatascience.com/a-gentle-introduction-to-ocr-ee1469a201aa) (2018) [@shgidi](https://github.com/shgidi)
* [Worauf kann ich mich verlassen? Arbeiten mit digitalisierten Quellen, Teil 1: OCR](https://blog.ub.unibas.ch/2019/06/04/worauf-kann-ich-mich-verlassen-arbeiten-mit-digitalisierten-quellen-teil-1-ocr/)  (2019) [@eliaskreyenbuehl](https://github.com/eliaskreyenbuehl) :de: A reflection/criticism on OCR quality, OCR pitfalls in Fraktur fonts.

### OCR Showcases

* [abbyy-finereader-ocr-senate](https://github.com/dannguyen/abbyy-finereader-ocr-senate) - Using OCR to parse scanned Senate Financial Disclosure forms.
* [cvOCR](https://github.com/Halfish/cvOCR) - An OCR system for recognizing resume or cv text, implemented in Python and C and based on tesseract
* [MathOCR](https://github.com/chungkwong/MathOCR) - A printed scientific document recognition system, **pre-alpha**

### Academic articles

#### 2011 and before
* [High performance document layout analysis](http://www.dfki.de/web/research/publications/renameFileForDownload?filename=HighPerfDocLayoutAna.pdf&file_id=uploads_552) (2003) Breuel
* [Adaptive degraded document image binarization](http://doai.io/10.1016/j.patcog.2005.09.010) (2006) Gatos, Pratikakis, Perantonis
* [[Internship Report]](http://www.madm.eu/_media/theses/ocropusgupta.pdf) (2007) Gupta
* [OCRopus Addons (Internship Report)](http://madm.dfki.de/_media/theses/ocropusdantrey.pdf) (2007) Dantrey

#### 2012
* [Local Logistic Classifiers for Large Scale Learning](http://www.academia.edu/2959462/Local_Logistic_Classifiers_for_Large_Scale_Learning) (2012) Yousefi, Breuel

#### 2013
* [High Performance OCR for Printed English and Fraktur using LSTM Networks](http://staffhome.ecm.uwa.edu.au/~00082689/papers/Breuel-LSTM-OCR-ICDAR13.pdf) (2013) Breuel, Ul-Hasan, Mayce Al Azawi. Shafait
* [Can we build language-independent OCR using LSTM networks?](https://www.researchgate.net/publication/260341307_Can_we_build_language-independent_OCR_using_LSTM_networks) (2013) Ul-Hasan, Breuel
* [Offline Printed Urdu Nastaleeq Script Recognition with Bidirectional LSTM Networks](http://staffhome.ecm.uwa.edu.au/~00082689/papers/Adnan-Urdu-OCR-ICDAR13.pdf) (2013) Ul-Hasan, Ahmed, Rashid, Shafait, Breuel

#### 2014
* [OCR of historical printings of Latin texts: Problems, Prospects, Progress.](http://www.springmann.net/papers/2014-04-07-DATeCH2014-springmann.pdf) (2014) Springmann, Najock, Morgenroth, Schmid, Gotscharek, Fink
* [Correcting Noisy OCR: Context beats Confusion](http://dx.doi.org/10.1145/2595188.2595200) (2014) Evershed, Fitch

#### 2015
* [TypeWright: An Experiment in Participatory Curation](http://www.digitalhumanities.org/dhq/vol/9/4/000220/000220.html) (2015) Bilansky
  * On crowd-sourcing OCR postcorrection
* [Benchmarking of LSTM Networks](http://arxiv.org/abs/1508.02774) (2015) Breuel
* [Recognition of Historical Greek Polytonic Scripts Using LSTM](http://users.iit.demokritos.gr/~bgat/OldDocPro/05_paper_305.pdf) (2015) Simistira, Ul-Hassan, Papavassiliou, Basilis Gatos, Katsouros, Liwicki
* [A Segmentation-Free Approach for Printed Devanagari Script Recognition](https://www.researchgate.net/publication/280777081_A_Segmentation-Free_Approach_for_Printed_Devanagari_Script_Recognition) (2015) Karayil, Ul-Hasan, Breuel
* [A Sequence Learning Approach for Multiple Script Identification](https://www.researchgate.net/publication/280777013_A_Sequence_Learning_Approach_for_Multiple_Script_Identification) (2015) Ul-Hasan, Afzal, Shfait, Liwicki, Breuel

#### 2016
* [Important New Developments in Arabographic Optical Character Recognition (OCR)](https://arxiv.org/abs/1703.09550) (2016) Romanov, Miller, Savant, Kiessling
  * on [kraken](#ocr-engines)
  * using [OpenArabic/OCR_GS_Data](https://github.com/OpenArabic/OCR_GS_Data) for ground truth data
* [OCR of historical printings with an application to building diachronic corpora: A case study using the RIDGES herbal corpus](https://arxiv.org/abs/1608.02153) (2016) Springmann, Lüdeling
* [Automatic quality evaluation and (semi-) automatic improvement of mixed models for OCR on historical documents](http://arxiv.org/abs/1606.05157) (2016) Springmann, Fink, Schulz
* [Generic Text Recognition using Long Short-Term Memory Networks](https://kluedo.ub.uni-kl.de/frontdoor/index/index/docId/4353) (2016) Ul-Hasan -- Ph.D Thesis
* [OCRoRACT: A Sequence Learning OCR System Trained on Isolated Characters](https://www.researchgate.net/publication/294575734_OCRoRACT_A_Sequence_Learning_OCR_System_Trained_on_Isolated_Characters) (2016) Dengel, Ul-Hasan, Bukhari
* [Recursive Recurrent Nets with Attention Modeling for OCR in the Wild](https://arxiv.org/abs/1603.03101) (2016) Lee, Osindero

#### 2017

* [Telugu OCR Framework using Deep Learning](https://arxiv.org/abs/1509.05962) (2015/2017) [Achanta](https://github.com/rakeshvar), Hastie
  * see also [TeluguOCR](https://github.com/TeluguOCR), [banti_telugu_ocr](https://github.com/TeluguOCR/banti_telugu_ocr), [chamanti_ocr](https://github.com/rakeshvar/chamanti_ocr), [#49](https://github.com/kba/awesome-ocr/issues/49)


#### 2018

* [A Two-Stage Method for Text Line Detection in Historical Documents](https://arxiv.org/abs/1802.03345) (2018) [Grüning](https://github.com/TobiasGruening), Leifert, Strauß, Labahn. Code available at https://github.com/TobiasGruening/ARU-Net
