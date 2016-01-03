crestmatic
==========

A documentation generator for [EVE Online](http://www.eveonline.com/) which uses [crestschema](https://github.com/jimpurbrick/crestschema) to generate [JSON Schema](http://json-schema.org/) from the self describing [CREST API](https://wiki.eveonline.com/en/wiki/CREST_Getting_Started) discovered by the [crestschemaspider.js](https://github.com/jimpurbrick/crestschema/blob/master/crestschemaspider.js) [NODE](https://nodejs.org/) application. The documentation is then generated from the JSON schema using [Matic]. [nightli.es](https://nightli.es/) is used to trigger [Travis](https://travis-ci.org/jimpurbrick/crestmatic) builds every night which push to [gh-pages](jimpurbrick.com/crestmatic/web/) to keep the documentation up to date.
