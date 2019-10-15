# Software Citation Checklist for Developers

Produced by the FORCE11 Software Citation Implementation Working Group

Editor: Neil Chue Hong (ORCID: 0000-0002-8876-7606). 

Contributors: Alice Allen (ORCID: 0000-0003-3477-2845), Alejandra Gonzalez-Beltran (ORCID: 0000-0003-3499-8262), Anita de Waard (ORCID: 0000-0002-9034-4119), Arfon M. Smith (ORCID: 0000-0002-3957-2474), Carly Robinson (ORCID: 0000-0002-8523-1478), Catherine Jones (ORCID: 0000-0002-5112-835X), Daina Bouquin (ORCID: 0000-0003-2626-3688) , Daniel S. Katz (ORCID: 0000-0001-5934-7525), David Kennedy (ORCID: 0000-0002-9377-0797), Gerry Ryder (ORCID: 0000-0001-7444-4489), Jessica Hausman (ORCID: 0000-0002-1861-1526), Lorraine Hwang (ORCID: 0000-0002-1021-3101), Matthew B. Jones (ORCID: 0000-0003-0077-4738), Melissa Harrison (ORCID: 0000-0003-3523-4408), Mercè Crosas (ORCID: 0000-0003-1304-1939), Mingfang Wu (ORCID: 0000-0003-1206-3431), Peter Löwe (ORCID: 0000-0003-2257-0517), Robert Haines (ORCID: 0000-0002-9538-7919), Scott Edmunds (ORCID: 0000-0001-6444-1436), Shelley Stall (ORCID: 0000-0003-2926-8353), Sowmya Swaminathan (ORCID: 0000-0002-0285-4910), Stephan Druskat (ORCID: 0000-0003-4925-7248), Tom Crick (ORCID: 0000-0001-5196-9389), Tom Morrell (ORCID: 0000-0001-9266-5146), Tom Pollard (ORCID: 0000-0002-5676-7898). 

DOI: 10.5281/zenodo.3482769

## Background

This document provides a minimal, generic checklist that developers of software (either open or closed source) used in research can use to ensure they are following good practice around software citation. This will help developers get credit for the software they create, and improve transparency, reproducibility, and reuse.

## Checklist for making a release of your software citable

- Have I assigned an appropriate license to my software?
- Have I described my software properly, using an appropriate metadata format, and included this metadata file with my software?
  - Have I given my software a clear version number?
  - Have I determined the authors to be credited for this release of my software, and included this in my metadata file?
- Have I procured a persistent identifier for this release of my software?
- Have I added my recommended citation to the documentation for my software?

There are other things that we consider as good practice for research software development which are not directly related to making software citable - these are described in the Additional Guidancee below.

## License

This guidance is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license. You are free to share and adapt this material for any purpose, including commercially, as long as you give [appropriate credit](https://wiki.creativecommons.org/wiki/License_Versions#Detailed_attribution_comparison_chart), provide a [link to the license](https://creativecommons.org/licenses/by-sa/4.0/), indicate if [changes were made](https://wiki.creativecommons.org/wiki/License_Versions#Modifications_and_adaptations_must_be_marked_as_such), and you distribute your contributions under the same license as the original. More information: https://creativecommons.org/licenses/by-sa/4.0/

## Additional Guidance on Software Citation for Developers

### Why is software citation important?

Software is part of the research process, across a wide range of disciplines and domains, and it is therefore important that pieces of software that have contributed to the research are cited. 

Software citation is vital in the acknowledgment of the crucial role of software in research, as it allows researchers publishing software rather than papers to participate in the academic credit system.

The scholarly communications system that underpins research relies on accurate citations to ensure research integrity, give appropriate credit and show dependencies with other works. As one step towards reproducing a computational procedure, researchers need to be able to access all inputs to the procedure including the specific version of software packages used to produce the original results. Research software should be as open as possible to enable traceability and reproducibility of research results.

Members of the FORCE11 community, representing authors, developers, researchers, publishers and funders, have published the Software Citation Guidelines [1] to encourage broad adoption of a consistent policy for software citation across disciplines and venues. This checklist aims to provide guidance to make it easier to implement these principles as a developer.

### What is an appropriate license?

Open source license guidance is readily available [2]. Choose a license that meets your needs, and that of your community of users.

### What are appropriate metadata formats?

The CodeMeta.json format [3] captures software metadata, and is understood by a growing number of digital repositories, It is also easy to convert this to many common metadata schema used by software repositories.

The Citation File Format (CFF) [4] is a human- and machine-readable file format in YAML 1.2 which provides citation metadata for software. 

Your community may already have a recommended metadata format for software metadata.

### How do I give a clear version number?

We recommend using semantic versioning [5].

### How do I procure a persistent identifier for my software release?

The easiest way of getting a persistent identifier is to deposit your source code in a digital repository which accepts software and issues Digital Object Identifiers (DOIs). Zenodo's integration with GitHub [6] makes this easier to do automatically, but you can also manually deposit it into a repository.

### Where should I add my recommended citation to the documentation for my software?

We recommend placing your recommended citation in your README file or a separate CITATION file. This should be done using the standard citation style for your community.

#### Example from astronomy, with text in the README file asking people to cite both the package and a paper

Software citation:
> Angeline Burrell, Christer van der Meeren, & Karl M. Laundal. (2019, September 19). aburrell/aacgmv2: Version 2.5.2 (Version 2.5.2). Zenodo. http://doi.org/10.5281/zenodo.3451419

Recommended citation from the README file:
> When referencing this package, please cite both the package DOI (10.5281/zenodo.3451419) and the AACGM-v2 journal article:
>
> Shepherd, S. G. (2014), Altitude‐adjusted corrected geomagnetic coordinates: Definition and functional approximations, Journal of Geophysical Research: Space Physics, 119, 7501–7521, doi:10.1002/2014JA020264.

#### Example from mathematics, providing people with a BibTeX snippet in a CITATION file

Software citation:
> Vince Knight, & Ria Baldevia. (2018, January 31). drvinceknight/Nashpy: v0.0.13 (Version v0.0.13). Zenodo. http://doi.org/10.5281/zenodo.1163694

Here is how this project has put the citation as a BibTeX snippet in a CITATION file: https://github.com/drvinceknight/Nashpy/blob/v0.0.13/CITATION.md

> Please use the following to cite the latest version of the Nashpy library::
> 
> @misc{axelrodproject,
>  author       = {{ {The Nashpy project developers} }}
>  title        = {Nashpy: <RELEASE TITLE>},
>  month        = <MONTH>,
>  year         = <YEAR>,
>  doi          = {<DOI INFORMATION>},
>  url          = {http://dx.doi.org/10.5281/zenodo.<DOI NUMBER>}
> }
>
> To check the details (RELEASE TITLE, DOI INFORMATION and DOI NUMBER) please view the Zenodo page for the project. 

### How should I determine authorship?

Determining authorship is still best done by the project, considering which people have contributed to a release, and may change with each release.

### Additional guidance

Additional guidance is available from https://research-software.org/citation/developers [7]

## References

  1. Smith, Arfon M., Katz, Daniel S., Niemeyer, Kyle E., & FORCE11 Software Citation Working Group. (2016). Software citation principles. PeerJ Computer Science, 2, e86. https://doi.org/10.7717/peerj-cs.86
  2. Choose a License: https://choosealicense.com/
  3. Matthew B. Jones, Carl Boettiger, Abby Cabunoc Mayes, Arfon Smith, Peter Slaughter, Kyle Niemeyer, Yolanda Gil, Martin Fenner, Krzysztof Nowak, Mark Hahnel, Luke Coy, Alice Allen, Mercè Crosas, Ashley Sands, Neil Chue Hong, Patricia Cruse, Daniel S. Katz, Carole Goble. 2017. CodeMeta: an exchange schema for software metadata. Version 2.0. KNB Data Repository. doi:10.5063/schema/codemeta-2.0
  4. Druskat, Stephan, Chue Hong, Neil, Haines, Robert, & Baker, James. (2018, August 29). Citation File Format (CFF) - Specifications (Version 1.0.3-3). Zenodo. http://doi.org/10.5281/zenodo.1405679
  5. Preston-Werner, Tom. (2013). Semantic Versioning 2.0.0 https://semver.org/
  6. Making Your Code Citable https://guides.github.com/activities/citable-code/
  7. Druskat, Stephan. (2018). Research software citation for software developers. https://research-software.org/citation/developers



