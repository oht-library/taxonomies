# OHTL taxonomies

The published taxonomies and typologies of the [Online Harms Taxonomy Library](https://ohtl.org) (OHTL), as RDF.

Each taxonomy is taken from a published source, such as a regulator's guidance, and mapped to the open [OHT schema](https://github.com/oht-library/schema). Publishers' text is kept exactly as published.

## Traceable to the source

Each taxonomy version cites the exact source edition it was built from, by a permanent URL:

1. the publisher's own permanent URL where there is one, such as a legislation.gov.uk address, an EU ELI or a DOI
2. otherwise, an unaltered copy in an open repository such as Zenodo, where the publisher's terms allow
3. otherwise, a Wayback Machine capture while permission is sought

## Layout

No taxonomies have been published yet. Planned:

```
<publisher>-<taxonomy>/     one folder per taxonomy, for example ofcom-content-harmful-to-children
    <YYYY-MM>/              one folder per source edition, never overwritten
```

The file formats in each edition folder (for example Turtle and JSON-LD) are still to be decided. Crosswalks between taxonomies will also be published as [SSSOM](https://mapping-commons.github.io/sssom/) mapping sets.

## How the files are made

The files are generated, not written by hand. Each source is extracted, the extraction is checked by a person, and the result is mapped to a pinned schema release and validated. Corrections are made at source and the files regenerated.

## Releases and citation

No release has been published yet. Each release will be archived on [Zenodo](https://zenodo.org) with its own DOI, so that it can be cited.

## Licence

Not yet settled. The taxonomies combine OHTL's own structure and mappings with publishers' text, which stays under each publisher's terms. OHTL's own contribution will be reusable in other knowledge graphs, with attribution at most.

## Contact

Questions, corrections and suggestions are welcome: open an issue or email [contact@ohtl.org](mailto:contact@ohtl.org). The website, [ohtl.org](https://ohtl.org), explains the project.
