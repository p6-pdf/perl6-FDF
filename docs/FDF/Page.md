[[Raku PDF Project]](https://pdf-raku.github.io)
 / [[FDF Module]](https://pdf-raku.github.io/FDF-raku)
 / [FDF](https://pdf-raku.github.io/FDF-raku/FDF)
 :: [Page](https://pdf-raku.github.io/FDF-raku/FDF/Page)

role FDF::Page
==============

Description
-----------

The FDF Page dictionary describes a new page that is added to the target document.

Methods
-------

class FDF::Template @.Templates
-------------------------------

(Required) An array of FDF template dictionaries describing the named pages that serve as templates on the page.

class Hash $.Info
-----------------

(Optional) An FDF page information dictionary containing additional information about the page. At the time of ISO-32000 publication, no entries have been defined for this dictionary.

