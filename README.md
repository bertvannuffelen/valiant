valiant
=======

Valiant is a Java based transformation engine to extract from XML documents RDF data using XSLT processing.

The XML documents which are the input can be access through 3 different channels:
* a single file
* a directory and all the contents below
* a webDAV repository (tested w.r.t. Virtuoso Open Source Web Dav)

The resulting RDF is exported via 4 different channels:
* to a single file
* to a directory (creating a similar tree structure as the input directory)
* to a webDAV repository 
* to Virtuoso Open Source triple store

The XSLT engine included is the public version of saxon, however, in principle, it can be replaced with other engines like Xalan.

This tool is developed with the support of the LOD2 project, funded by the European Commission within the 7th Framework Programme (GA no. 257934).
You can find further information about the LOD2 Component Stack and the LOD2 project at http://lod2.eu.
