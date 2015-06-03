# metadata

The Connecticut Digital Archive, CTDA, provides long-term preservation services to non profit Connecticut based institutions, including libraries, archives, history centers and museums. The CTDA normalizes metadata to the standard Metadata Object Description Schema version 3.5. The CTDA does not prescribe one set of cataloging rules, though the CTDA asks that HTML be removed from metadata descriptions as well as punctuation that is unnecessary. Each CTDA MODS record should have: title, resource type, digital resource origin, held by statement, rights statement, persistent identifier (handle system), and the language of the MODS record. The CTDA does not enforce metadata consistency or accuracy except to ensure that all records have data for those categories just listed. 

The MODS datastream is transformed to simple Dublin Core. The Simple Dublin Core datastream contains the metadata that is harvested.

First, there are the CTDA MODS Guidelines and the CTDA Metadata Application Profile. These should be the latest version. However, the most up-to-date version can be found on our main web site on our [Resources Page](http://ctdigitalarchive.org/resources-for-participants/).

Secondly, there is the mods to dc xsl transformation. This xsl file was used to replace the existing (default) mods_to_dc.xsl in the following Islandora modules:
* all/modules/islandora_xml_forms/builder/transforms/mods_to_dc.xsl
* all/modules/islandora_importer/xsl/mods_to_dc.xsl
* all/modules/islandora_batch/transforms/mods_to_dc.xsl
Further, this new mods to dc xsl was renamed to mods_to_dc_oai.xsl and used to replace the existing (default) mods_to_dc_oai.xsl in the following Islandora module:
* /var/www/html/archives-dev/sites/all/modules/islandora_oai/transforms/mods_to_dc_oai.xsl
