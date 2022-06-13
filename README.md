# Index Fungorum as linked data

Generate a version of Index Fungorum’s data as N-triples for import into a triple store.

## Index Fungorum

The [Index Fungorum](http://www.indexfungorum.org) contains names of fungi (including yeasts, lichens, chromistan fungal analogues, protozoan fungal analogues and fossil forms) at all ranks.


Each name in Index Fungorum has a Life Science Identifier (LSID) which has an associated set of metadata in RDF/XML. This repository takes the XML for each Index Fungorum name and reformats it as N-triples, correcting any minor format issues as part of that process. The resulting N-triples are intended to be uploaded into a triple store.

## License

The code in this repository is under a MIT license. The data from Index Fungorum is under a [Creative Commons CC-BY](http://opendefinition.org/licenses/cc-by/) license.

