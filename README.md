
# Generate SILL data

"SILL" stands for "Socle Interministériel de Logiciels Libres", which
refers to the list of recommended free softwares for the [french]
public sector.

You can browse it on [sill.etalab.gouv.fr](https://sill.etalab.gouv.fr).

This repository contains the code to generate various `json` files that
are used by the SILL frontend.

It takes SILL data from [this csv file](https://git.sr.ht/~etalab/sill/blob/master/sill.csv) and convert it to `json`, also
adding wikidata additional information when available.


# Generate the binary file

Assuming GraalVM is installed:

    clj -A:native-image


# Contribute

The development of this repository happens on [the SourceHut
repository](https://git.sr.ht/~etalab/sill-data).  The code is also published on [GitHub](https://github.com/etalab/sill-data) to reach more
developers.

Your help is welcome.  You can contribute with bug reports, patches,
feature requests or general questions by sending an email to
`~etalab@lists.sr.ht`.


# License

2020-2021 DINUM, Bastien Guerry.

This application is published under the EPL 2.0 license.

