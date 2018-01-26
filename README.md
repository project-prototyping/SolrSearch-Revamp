# SolrSearch-Revamp
Large overhaul to update our internal search solutions; From Google Search Appliance to Apache Solr.
All projects in repository require WinRar/Winzip to extract. This is for backup purposes.

---

### Notes and References:
..* Markdown https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
..* internal js library http://localhost/search-recherche/Frontend/wet-boew/js/jquery/2.1.4/jquery.js

---

The following metadata required for Apache Solr schema; applied on both Elgg and MediaWiki:

### MediaWiki
* platform
* dcterms.title
* dcterms.type
* dcterms.modified
* dcterms.description

### GCconnex
* platform
* dcterms.title
* dcterms.type
* dcterms.modified
* dcterms.description

---

## SolrWebSearch.rar
* this is the main C# web application that will be used when a user attempts for a search
* connects to a Solr Engine to retrieve results
* tested on Google Chrome and Internet Explorer 11 (Edge)
* uses the wet-boew for consistent web application layout

## AddHTMLMetaAndTitle.rar
* MediaWiki extension
* tested on Google Chrome and Internet Explorer 11 (Edge)
* places specific metadata in the header for the crawler

## wet4.rar
* Elgg plugin
* tested on Google Chrome and Internet Explorer 10 ~ Internet Exploerer 11 (Edge)
* places specific metadata in the header and applies the wet-boew layout for common look and feel


