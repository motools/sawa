Sonic Annotator Web Application
===============================

About
-----

The [Sonic Annotator Web Application](http://www.isophonics.net/sawa/) generates and serves a web interface for 
[Vamp plugins](http://www.vamp-plugins.org/) available on the system and allows feature extraction of uploaded audio files using [Sonic Annotator](http://www.omras2.org/SonicAnnotator).

An example of a generated html page can be found in ./examples

Requirements
------------

* Cherrypy (web server)
* Sonic Annotator
* Cheetah template library
* [Mopy](https://github.com/motools/mopy) 
* Musicbrainz2 library
* ...more to come here

TODO
----

* This is really in the phase of "testing ideas" but 
 already quite usable

* Display enhanced plugin information using mopy+vamp ontology
* Finalize JSON generator for mb data (maybe use mopy e.g. like [GNAT](https://github.com/motools/gnatlib))
* Post process RDF output to include metadata from musicbrainz
* Visualisations of RDF (e.g. using Matplotlib/ Flash interface)
* Cache the resulting RDF on the Virtuoso server (Kurt?) 

Any more ideas?

PS
--

The [old project repository location at SourceForge](http://motools.svn.sourceforge.net/viewvc/motools/sawebapp/) is now deprecated. All new developments will be pushed to this repository location here at GitHub.

