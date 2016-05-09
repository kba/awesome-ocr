Awesome OCR
===========

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list contains links to great software tools and libraries and literature
related to [Optical Character Recognition
(OCR)](http://en.wikipwdia.org/wiki/Optical_Character_Recognition).

Contributions are welcome, as is feedback.

## Table of Contents

<!-- vim: GenTocGFM -->
* [Software](#software)
	* [OCR engines](#ocr-engines)
	* [OCR file formats](#ocr-file-formats)
	* [OCR GUI](#ocr-gui)
	* [OCR Preprocessing](#ocr-preprocessing)
	* [OCR Showcases](#ocr-showcases)
	* [OCR as a Service](#ocr-as-a-service)
	* [OCR libraries](#ocr-libraries)
		* [Go](#go)
		* [Java](#java)
		* [.Net](#net)
		* [NodeJS](#nodejs)
		* [PHP](#php)
		* [Python](#python)
		* [Ruby](#ruby)
* [Literature](#literature)
	* [OCR-related publication and link lists](#ocr-related-publication-and-link-lists)
	* [Blog Posts and Tutorials](#blog-posts-and-tutorials)
	* [Academic articles](#academic-articles)

## Software

### OCR engines

* [tesseract](https://github.com/tesseract-ocr/tesseract) - The definitive Open Source OCR engine
* [ocropus](https://github.com/tmbdev/ocropy) - OCR engine based on CLSTM
* [Ocrad](http://www.gnu.org/software/ocrad/) - The GNU OCR.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - Javascript port (emscripten) of ocrad
* [MathOCR](https://github.com/chungkwong/MathOCR) - A printed scientific document recognition system, **pre-alpha**
* [ocracy](https://github.com/naptha/ocracy) - pure javascript lstm rnn implementation based on ocropus
* [kraken](https://github.com/mittagessen/kraken) - Ocropus fork with sane defaults

### OCR file formats

#### hOCR

* [hocr-tools](https://github.com/tmbdev/hocr-tools) - Tools for doing various useful things with hOCR files
* [hocr-spec](https://github.com/kba/hocr-spec) - hOCR 1.1 specification
* [ocr-transform](https://github.com/UB-Mannheim/ocr-transform) - CLI tool to convert between hOCR and ALTO
* [hocr-parser](https://github.com/athento/hocr-parser) - hOCR Specification Python Parser

#### ALTO XML

* [ALTO XML Schema](https://github.com/altoxml/schema) - XML Schema and development of the ALTO XML format


### OCR GUI

* [moz-hocr-editor](https://github.com/garrison/moz-hocr-edit) - Firefox Addon for editing hOCR files **Discontinued**
* [qt-box-editor](https://github.com/zdenop/qt-box-editor) - QT4 editor of tesseract-ocr box files.
* [ocr-gt-tools](https://github.com/UB-Mannheim/ocr-gt-tools) - Client-Server application for editing OCR ground truth.
* [Paperwork](https://github.com/jflesch/paperwork) - Using scanners and OCR to grep paper documents the easy way (Linux only).
* [gImageReader](https://github.com/manisandro/gImageReader) - gImageReader is a simple Gtk/Qt front-end to tesseract-ocr.
* [VietOCR](http://vietocr.sourceforge.net/) - A Java/.NET GUI frontend for Tesseract OCR engine.
* [PoToCo](https://github.com/cisocrgroup/PoCoTo) - Fast interactive batch corrections of complete OCR error series in OCR'ed historical documents.

### OCR Preprocessing

* [NoiseRemove.java in MathOCR](https://github.com/chungkwong/MathOCR/blob/master/src/net/sf/mathocr/preprocess/NoiseRemove.java) - Java implementation of 
* [binarize.c in ZBar](https://github.com/ZBar/ZBar/blob/master/zbar/qrcode/binarize.c) - C implementations of two binarization algorithms, based on Sauvola 

### OCR Showcases

* [abbyy-finereader-ocr-senate](https://github.com/dannguyen/abbyy-finereader-ocr-senate) - Using OCR to parse scanned Senate Financial Disclosure forms.

### OCR as a Service

* [Open OCR](https://github.com/tleyden/open-ocr) - Run Tesseract in Docker containers
* [tesseract-web-service](https://github.com/guitarmind/tesseract-web-service) - An implementation of RESTful web service for tesseract-OCR using tornado.
* [docker-ocropus](https://github.com/tmbdev/docker-ocropus) - A small Docker built for the OCRopus OCR system.
* [ABBYY Cloud OCR SDK Code samples](https://github.com/abbyysdk/ocrsdk.com) - Code samples for using the proprietary commercial ABBYY OCR API.
* [nidaba](https://github.com/OpenPhilology/nidaba) -  An expandable and scalable OCR pipeline

### OCR libraries

#### Go

* [gosseract](https://github.com/otiai10/gosseract) - Golang OCR library, wrapping Tesseract-ocr.

#### Java

* [Tess4J](https://github.com/nguyenq/tess4j) - Java Native Access bindings to Tesseract.
* [tess-two](https://github.com/rmtheis/tess-two) - Tools for compiling Tesseract on Android and Java API.

#### .Net

* [tesseract for .net](https://github.com/charlesw/tesseract) - A .Net wrapper for tesseract-ocr.

#### NodeJS

* [node-tesseract](https://github.com/desmondmorris/node-tesseract) - A simple wrapper for the Tesseract OCR package.
* [node-tesseract-native](https://github.com/mdelete/node-tesseract-native) - C++ module for node providing OCR with tesseract and leptonica.

#### PHP

* [Tesseract OCR for PHP](https://github.com/thiagoalessio/tesseract-ocr-for-php) - Tesseract PHP bindings.

#### Python

* [pytesseract](https://github.com/madmaze/pytesseract) - A Python wrapper for Google Tesseract.
* [pyocr](https://github.com/jflesch/pyocr) - A Python wrapper for Tesseract and Cuneiform.

#### Ruby

* [rtesseract](https://github.com/dannnylo/rtesseract) - Ruby library wrapping the tesseract and imagemagick executables.
* [ruby-tesseract](https://github.com/meh/ruby-tesseract-ocr) - Native Tesseract bindings for Ruby MRI and JRuby

## Literature

### OCR-related publication and link lists

* [OCR-D](https://www.zotero.org/groups/ocr-d) - List of OCR-related academic articles in the context of the [OCR-D](http://www.ocr-d.de/) project. :de:
* [eadh.org projects](http://eadh.org/projects) - List of Digital Humanities-related projects in europe, some related to OCR

### Blog Posts and Tutorials

* [@danvk](https://github.com/danvk): [Extracting text from an image using Ocropus](http://www.danvk.org/2015/01/09/extracting-text-from-an-image-using-ocropus.html)
* [@danvk](https://github.com/danvk): [Training an Ocropus OCR model](http://www.danvk.org/2015/01/11/training-an-ocropus-ocr-model.html)
* [@zuphilip](https://github.com/zuphilip): [Ocropus Wiki: Compute errors and confusions](https://github.com/tmbdev/ocropy/wiki/Compute-errors-and-confusions)
* [@zuphilip](https://github.com/zuphilip): [Ocropus Wiki: Working with Ground Truth](https://github.com/tmbdev/ocropy/wiki/Compute-errors-and-confusion://github.com/tmbdev/ocropy/wiki/Working-with-Ground-Truth)
* [@jze](https://github.com/jze): [OCRopus](https://comsys.informatik.uni-kiel.de/lang/de/res/ocropus/) - mostly on column separation in ocropus
* [Overview of LEADTOOLS Image Cleanup and Pre-processing SDK Technology](https://www.leadtools.com/sdk/image-processing/document) -
  This feature list for a commercial image pre-processing library has nice before-after samples for pre-processing steps related to OCR

### Academic articles

* [Gatos, Pratikakis, Perantonis: "Adaptive degraded document image binarization" (2006)](http://doai.io/10.1016/j.patcog.2005.09.010)
